# Element Name

[Language](https://www.dublincore.org/specifications/dublin-core/dcmi-terms/#http://purl.org/dc/terms/language)

# Definition

The language(s) of the resource.

# How the language field works in the metadata form

* Autocomplete field
* Repeatable
* Required

# Where can the language information be found?

Language can be determined by examining the item:

| Item Type | Information Sources |
| --------- | ------------------- |
| Text | <ul><li>title page</li><li>words of the text</li></ul> |
| Images | <ul><li>caption</li><li>visible words within the image (e.g., a sign in a photograph)</li><li>text written on the front or back of a photo or image</li></ul> |
| Maps | <ul><li>caption or legend</li><li>place/physical feature labels</li></ul> |
| Music scores | <ul><li>title</li><li>lyrics</li></ul> |
| Videos | <ul><li>spoken/sung words</li><li>title screen(s)</li><li>label on disc</li><li>container cover</li></ul> |
| Sound files | <ul><li>spoken/sung words</li><li>information on disc/cassette</li><li>container information</li></ul> |
| Computer files | <ul><li>title page/screen</li><li>text</li><li>container information</li></ul> |

# How should the language be filled in?

| Guidelines | Examples |
| ---------- | -------- |
| Choose the appropriate language(s) | <ul><li>English</li></ul> |
| Include all relevant languages | <ul><li>English</li><li>French</li></ul> |
| For visual images that do not have a textual caption or text shown in the image | <ul><li>No linguistic content</li></ul> |
| If there are special circumstances or additional information about the language uses of the item, include it in the Note field | <ul><li>Language: English</li><li>Language: French</li><li>Note: this report is printed in two parts, the first in English and the second in the French.</li></ul> |
| If the language of the object is not available in the autocomplete, choose "Undetermined" and include a note in the record. Notify the sytems administrators if the language is not on the list. | <ul><li>Language: Undetermined</li><li>Note: Text is in the Lnuismk language</li></ul> |
| If the only text on the item consists of persons' names, "No linguistic content" should be chosen and the text can be described in the content description or a display note. | <ul><li>Language: No linguistic content</li><li>Note: The name "Nacho" is carved into the top of the box.</li></ul> |

# Comments

* Preferred usage is to utilize a standard schema for language names as defined by ISO639-2:
  * To simplify data entry, autocomplete on the language name is used instead of the three letter code.
* For less common languages that are not documented in the ISO standard, codes will come from [Glottolog](https://glottolog.org/); undocumented languages may be added to Glottolog according to their requirements.

# Resources

* Quick-Start Metadata Guide
* Input Guidelines for Descriptive Metadata
* Metadata Home

# Acknowledgments

This guide was inspired by, and adapted from [UNT's Metadata Input Guidelines for Language](https://library.unt.edu/digital-projects-unit/metadata/fields/language).
