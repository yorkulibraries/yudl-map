# Element Name

* [date](https://www.dublincore.org/specifications/dublin-core/dcmi-terms/#http://purl.org/dc/terms/date)
* [date created](https://www.dublincore.org/specifications/dublin-core/dcmi-terms/#http://purl.org/dc/terms/created)
* [date issued](https://www.dublincore.org/specifications/dublin-core/dcmi-terms/#http://purl.org/dc/terms/issued)
* [date modified](https://www.dublincore.org/specifications/dublin-core/dcmi-terms/#http://purl.org/dc/terms/modified)

# Definition

Dates associated with events in the life cycle of the object.

# How the date fields works in the metadata form

* Date
  * Text field (with EDTF validation)
  * Repeatable
  * Note Required
* Date created
  * Text field (with EDTF validation)
  * Repeatable
  * Not required
* Date issued
  * Text field  (with EDTF validation)
  * Repeatable
  * Not required
* Date modified
  * Text field  (with EDTF validation)
  * Repeatable
  * Not required

# Where can identifier information be found?

| Item Type | Information Sources |
| --------- | ------------------- |
| Text | <ul><li>title page</li><li>copyright page</li><li>cover or inside coverpage</li><li>a catalogue record</li></ul> |
| Images | <ul><li>bottom or back of photograph</li><li>a time-stamp</li><li>envelope, slip cover, or case</li><li>supplementary or accompanying information</li></ul> |
| Maps | <ul><li>title, caption, or legend</li><li>notes around the outside of the map</li><li>on the back of the map</li></ul> |
| Music scores | <ul><li>top of page</li><li>title page</li><li>table of contents</li><li>cover or inside cover</li></ul> |
| Videos | <ul><li>title of credit screen(s)</li><li>label on disc/cassette</li><li>container cover</li></ul> |
| Sound files | <ul><li>information on disc/cassette</li><li>container information</li></ul> |
| Computer files | <ul><li>title page/screen</li><li>statement in header/footer</li></ul> |

# How should the identifier be filled in?

## General Date Rules

* If no date can be found, leave the field blank.
* For each date, choose the appropriate date type.
  * If unsure, use the "Date" field.
* Dates must be formatted in valid [Extended Date/Time Format (EDTF)](https://www.loc.gov/standards/datetime/edtf.html).
* Always format dates appropriately.

### Basic Format

| Guidelines | Form(s) | Examples |
| ---------- | ------- | -------- |
| <ul><li>Write dates Year-Month-Day, separating the sections with a single hyphen</li></ul> | <ul><li>YYY-MM-DD</li></ul> | <ul><li>1989-06-12</li></ul> |
| <ul><li>Include partial dates only if the year or only the month and year are known</li></ul> | <ul><li>YYYY</li><li>YYYY-MM</li></ul> | <ul><li>1992</li><li>1992-10</li></ul> |

### Date Ranges

| Guidelines | Form(s) | Examples |
| ---------- | ------- | -------- |
|  <ul><li>Date ranges are inclusive (e.g., a scrapbook or collection of items compiled over a period of time)</li><li>Follow the basic format (above) but separate the dates with a slash mark</li></ul> | <ul><li>YYYY-MM-DD/ YYYY-MM-DD</li></ul> | <ul><li>1992-10-17/1992-10-24</li></ul> |
| <ul><li>If part of the date range is unknown, one date can be replaced by a double-dot to designate an "open" range</li></ul> | <ul><li>YYYY-MM-DD/..</li><li>../YYYY-MM-DD</li></ul> | <ul><li>2020-03-23/..</li><li>../2021-07-19</li></ul> |

### Uncertain dates

| Guidelines | Form(s) | Examples |
| ---------- | ------- | -------- |
| <ul><li>If a date is uncertain, a question mark can be used at the end of the date</li></ul> | <ul><li>YYYY?</li><li>YYYY-MM?</li><li>YYYY-MM-DD?</li></ul> | <ul><li>1999?</li><li>1999-01?</li><li>1999-01-10?</li></ul> |
| <ul><li>If a date is approximate (e.g., "circa" dates), a tilde can be used at the end of the date</li></ul> | <ul><li>YYYY~</li><li>YYYY-MM~</li><li>YYYY-MM-DD~</li></ul> | <ul><li>1999~</li><li>1999-01~</li><li>1999-01-10~</li></ul> |
| <ul><li>If a date is uncertain **and** approximate, a percentage sign can be used at the end of the date</li></ul> | <ul><li>YYYY%</li><li>YYYY-MM%</li><li>YYYY-MM-DD%</li></ul> | <ul><li>1999%</li><li>1999-01%</li><li>1999-01-10%</li></ul> |

# Comments


# Resources

* Quick-Start Metadata Guide
* Input Guidelines for Descriptive Metadata
* Metadata Home

# Acknowledgments

This guide was inspired by, and adapted from [UNT's Metadata Input Guidelines for Date](https://library.unt.edu/digital-projects-unit/metadata/fields/date).
