HeaderGridView
=======

## Introduction

This is an updated version of GridView which allows for Headers. The Headers themselves are not part of the adapter / data source. This means that the headers only are not being recycled.

## Setup

To use HeaderGridView in your projects, simply add this project to your workspace then add it as a library project to your current project. 

## Usage

HeaderGridView can be added as a custom view to any layout. 

instead of ``` <GridView /> ``` use…
```xml
    <com.origamilabs.library.views.HeaderGridView />
```
then simply add header views via
```xml
    addHeaderView(View v, Object data, boolean isSelectable);
```
or
```xml
    addHeaderView(View v);
```

## Tests

None.


## TODO:

* implement Footer support. should be simple
* develop tests

