# Element Name

* [relation](https://www.dublincore.org/specifications/dublin-core/dcmi-terms/#http://purl.org/dc/terms/relation)
* [part of](https://www.dublincore.org/specifications/dublin-core/dcmi-terms/#http://purl.org/dc/terms/isPartOf)

# Definition

These two fields relate to information about a related object that is connected to the object that you are describing. Relation is intented for how an object relates to objects outside of the repository. Part of is intented to show relationships between objects in the repository.

Please note: these fields are **NOT** to attribute provenance (e.g. what fonds or collection the object belongs to). 

# How the relation and part of fields work in the metadata form

* Relation
  * Text field
  * Repeatable
  * Not Required
* Part of
  * Autocomplete node ID
  * Not repeatable
  * Not required

# How should the relation and part of fields be filled in?

* Enter information about known relationships in the records for both items
* It is should not be necessary to do research to find related resources
* If the relationship is unclear, uncertain, or otherwise questionable, the information may be entered into a display note or non-display note instead
* For Toronto Telegram negatives, the part of value is the node ID (NID) of the contact sheet.

| Guidelines | Examples |
| ---------- | -------- |
| Relation <ul><li>Include the title of the related material</li><li>Include a unique identifier or additional information if it is important to identify the item</li><li>Include the permalink to the record of the related item if it is available</li></ul> ||
| Part of <ul><li>Toronto Telegram negatives</li></ul> | <ul><li>*Part of*: 45321</li></ul> |

# Resources

* Quick-Start Metadata Guide
* Input Guidelines for Descriptive Metadata
* Metadata Home

# Acknowledgments

This guide was inspired by, and adapted from [UNT's Metadata Input Guidelines for Resource Type](https://library.unt.edu/digital-projects-unit/metadata/fields/resource-type).
