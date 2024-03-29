# Policy on Creating Subject Terms

## Guidelines for Preparing New Subject Terms

New subject terms can be added by contacting the system administrator. Terms can be added as required, or in batches.

### Subject Term Sources

* [Art & Architecture Thesaurus](https://www.getty.edu/research/tools/vocabularies/aat/)
* [FAST (Faceted Application of Subject Terminology)](https://www.oclc.org/research/areas/data-science/fast.html)
* [Genre Terms: A Thesaurus for Use in Rare Book and Special Collections Cataloguing](https://rbms.info/vocabularies/genre/alphabetical_list.htm)
* [Getty Thesaurus of Geographic Names](https://www.getty.edu/research/tools/vocabularies/tgn/)
* [Library of Congress Children's Subject Headings](https://id.loc.gov/authorities/childrensSubjects.html) 
* [Library of Congress Genre/Form Terms](https://id.loc.gov/authorities/genreForms.html)
* [Library of Congress Temporal Terms](https://www.loc.gov/standards/sourcelist/temporal.html)
* Local authority creation
* [National Agricultural Library subject headings](https://agclass.nal.usda.gov/)
* [Répertoire de vedettes-matière](https://www5.bibl.ulaval.ca/la-bibliotheque/repertoire-de-vedettes-matiere-rvm)
* [TGM II, Genre and physical characteristic terms](https://www.loc.gov/rr/print/tgm2/)
* [Thesaurus for Graphic Materials](https://www.loc.gov/pictures/collection/tgm/)
* [Government of Canada Core Subject Thesaurus](https://canada.multites.net/cst/index.htm)
* [Canadian Subject Headings (CSH)](https://www.bac-lac.gc.ca/eng/services/canadian-subject-headings/Pages/canadian-subject-headings.aspx)
* [Library of Congress Subject Headings (LCSH)](https://id.loc.gov/authorities/subjects.html)
* [Manitoba Archival Information Network Database (MAIN Database)](https://doi.org/10.5203/ss_ama.main_bon.chr.2015.1)
* [Medical Subject Headings(MeSH)](https://meshb.nlm.nih.gov/)
* [Wikidata](https://www.wikidata.org/wiki/Wikidata:Main_Page)

## Topics

| Guideline | Example |
|-----------|---------|
| Do not add quotation marks to titles | <ul><li><strike>"ROMEO + JULIET"</strike></li><li>ROMEO + JULIET</li></ul> |
| If suggesting a new term not already documented in other controlled vocabularies, strive to be as unambiguous as possible. <br /><br />For example if you are trying to isolate a homograph (multiple meanings for one spelling of a word) include a parenthetical note for the domain to which the term belongs  | <ul><li>Mercury (metal)</li><li>Mercury (planet)</li><li>Mercury (Roman deity)</li><li>Model (architecture)</li><li>Model (fashion)</li><li>Model (trade show) </li><li>Bow (archery)</li><li>Bow (gesture)</li><li>Bow (fashion accessory)</li><li>Sewer (sewage infrastructure)</li><li>Sewer (textile worker)</li><li>Sewer (agricultural worker)</li> |
|If a singular object is depicted use a subject term in its plural form | <ul><li>Porcupines</li></ul> |
    
### Name
    
If individuals are significant in some way to the content of an item, consider adding a Name. In general, only include names as structured subjects if a surname is known. If only a first name, given names or nickname is known, include the name in the [Description](https://github.com/yorkulibraries/yudl-map/blob/main/metadata-input-guidelines/description.md) field or the [Title](https://github.com/yorkulibraries/yudl-map/blob/main/metadata-input-guidelines/title.md) of the work.  

Where possible, enter names following instructions as laid out in [RAD Chapter 22: Headings for Persons](http://www.cdncouncilarchives.ca/RAD/RAD_Chapter22_March2008.pdf) or as documented in authorities such as [VIAF](https://viaf.org/).

All names added as subject keywords should follow the same format:

| Guideline | Example |
| --------- | ------- |
| Invert the name (Family name, Given name ) | <ul><li>Cooper, Dale</li></ul> |
| Use any known part of the name including initials if the full name is unknown | <ul><li>Ware, K.</li></ul> |
| Include additional names as middle names | |
| Names that are hyphenated or have multiple parts are all considered "last names" | <ul><li>Sainte-Marie, Buffy</li></ul> |
| Use appropriate abbreviations: include known titles after the first name, include known suffixes at the end of the name after a second comma | <ul><li>Cumberbatch, B., Lieutenant</li><li>Cumberbatch, B., Lady</li></ul>|
| Nicknames can be included in parentheses, unless their nickname is included in authority listings like VIAF. | <ul><li>Vig, Butch </li></ul> |
| If a person is identified with both a married name and a previous name, use a separate named person entry for each surname | <ul><li>Weldon, Lois</li><li>Marshall, Lois</li></ul>|
| If a person performs or whose public life is connected with a particular name or pseudonym, use that name|<ul><li>Lady Gaga **OR** Gaga, Lady</li><li>**NOT** Germanotta, Stefani Joanne</li><li>Peck, Orville</li><li>K'naan</li><li>**NOT** Warsame, Keinan Abdi</li>|
| If a person is affiliated with the subject of the object but is not directly involved, do not add their name as a Name subject | <ul><li>Depictions of a parade in honour of Martin Luther King Jr. Day should **NOT** have a Name keyword for King, Martin Luther, 1929-1968</li><li>A photograph taken at a statue of Champlain should **NOT** have a Name keyword for Champlain, Samuel de, 1574-1635</li><li>Instead, consider adding a Geographic term for the location or subject topic, eg. Samuel de Champlain Monument (Orillia,Ont.)</li><li>A photograph taken at an Ada Lovelace Day Edit-a-thon should NOT include a Name subject for Ada Lovelace, 1815-1852</li></ul>|
    
## Geographic

| Guideline | Example |
| --------- | ------- |
| If an object has a strong connection and affiliation with a geographic location but all other metadata fields lack specificity | [Perugia](https://digital.library.yorku.ca/islandora/object/yul:1005028) |


## Temporal

| Guideline | Example |
| --------- | ------- |
| If an object has a strong connection to a particular temporal period but all other metadata fields lack specify | [Pontiac's Conspiracy, 1763-1765](https://digital.library.yorku.ca/islandora/object/yul:754409)  |
| If an object has a multiple locations in time include years active, and city and province if known | The Isaacs Gallery, 1956-1961 (Toronto, Ont.) |

## Keywords

| Guideline | Example |
| --------- | ------- |
|Add keywords as needed to help users locate the resource | <ul><li>puppies</li></ul> |
|It is not necessary to repeat terms in the Subject Topic controlled vocabularies as Keywords | <ul><li>*Subject*: Dogs</li><li>Do <strong>NOT</strong> add:</li><ul><li>*Keywords*: dogs</li></ul></ul> |
|Keywords should be lowercase | <ul><li>regalia **NOT** Regalia</li></ul> |
|Only capitalize proper nouns | <ul><li>Marpiosa Folk Festival</li></ul> |
|Use punctuation when applicable |<ul><li>Pan-African music</li></ul> |
|If required, include multiple versions of a term with different spacing and punctuation |<ul><li>man-made disasters **AND** manmade disasters</li></ul> |
|Use plural forms of keywords | <ul><li>cats</li><li>children</li><li>porcupines</li></ul>|
|the singular form of a keyword may be used when there is no reasonable plural | <ul><li>quilting</li></ul> |
|If the keyword's plural is formed irregularly, the singular and plural forms can both be added as separate keywords | <ul><li>mouse</li><li>mice</li><li>knife</li><li>knives</li></ul>|
| When referring to a company, organization, school, institution, etc. the abbreviated version of the name can be used but the full name MUST appear at least once in the record where it will also be picked up in keyword searches. If it is important, both the full name and abbreviated versions can be included as keywords | <ul><li>*Description*: Image of exterior of Toronto Dominion Bank branch 123.</li><li>*keyword*: TD bank </li></ul> |
