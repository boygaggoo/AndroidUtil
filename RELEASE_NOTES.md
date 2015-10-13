# AndroidSidebar - RELEASE NOTES

## Version 1.0.0 (Oct. 14th 2015)

The first stable release of the library, which provides the following utility classes:

- The class `Condition` provides methods, which allow to ensure that variables or objects fulfill certain conditions by throwing exceptions, if conditions are violated, e.g. when an object is null.
- The class `BitmapUtil` provides methods, which allow to create and edit bitmaps, e.g. clipping them.
- The class `ClassUtil` provides methods, which allow to handle class names.
- The class `DisplayUtil` provides methods, which are related to a device's display metrics, e.g. converting DP values to pixel values and vice versa.
- The annotation `VisibleForTesting` can be used to mark types, constructors, methods or fields, which are only part of a publicly exposed API for testing purposes.