##Version 1.2.1
* Fixed a minor bug which would occur in the absence of a search input field

##Version 1.2.0
* Added new API method .filterizr('search', text), which is used to apply a search filter.
* Added new search control in the form of an input text which must have a data-search attribute.
* Updated public API methods to account for and apply the search filter over their intended operations.

##Version 1.1.0
* Added new API method .filterizr('toggleFilter', toggledFilter), which is used for the new multi-filtering mode.
* Added new filtering mode and filtering controls for multi-filtering. The user can now activate filters and display specific portions of the gallery alone or in combination. When all filters are turned of an unfiltered gallery is shown.
* All filtered out .filtr-item elements now get a 'filteredOut' class when they are filtered out of the visible elements, so that the user can target them if needed.
* Improved error checking, when the value of the data-category attribute of .filtr-item elements is not an integer or a string of integers delimited by ', ' a comprehensive error is thrown.

##Version 1.0.1
* Improved sorting functionality. Users can now sort based on custom data-attributes. Just add your custom data-attribute
(e.g. data-mySortData) and then call ```` .filterizr('sort', 'mySortData', 'asc') ```` Remember to omit the "data-" part when passing the attribute name as the parameter.
