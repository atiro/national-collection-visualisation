# Methodology

Work in Progress (including documenting the work in progress).

The institutions used for this work are taken from the report commisioned by the 
'[Towards a National Collection](https://www.nationalcollection.org.uk/)' project - "[Digital Collections Audit](https://museumdata.uk/wp-content/uploads/2023/11/Digital-Audit.pdf) by Kevin Gosling & Gordon McKenna (Collections Trust), Adrian Cooper (Intelligent Heritage) - March 2022" with some additions.

## Data sources (websites/annual reports)

For each institution, the website for the institution was searched for. From the information on the website the
institution was placed into:

  * A sector
  * A primary topic (topic 'mixed' if no one clear primary topic)
  * A type of institution (museum, library, archive, university)

Then I tried to identify the number of artefacts (and indidivual counts of museum, library and archive objects/items/collections)
and then from any collections search facility on the institutions site the number of records - that is how many of the artefacts
have been catalogued and have a catalogue record avialable online. I have avoided in almost all cases taking the numbers from
a third party site - but sometimes have needed to retrieve numbers by running an empty search or searching with wildcards to
get a number of results.

### Sectors

The sectors are:

  * DCMS Funded Institution
  * National Institution (with no strict definition of what this means)
  * Independent Institutions
  * Libraries
  * Regional Institutions
  * Societies
  * University

For most institutions the sector is fairly apparent although some could fall into two different sectors

### Primary Topics and Sub-collections

By picking a single topic for a large institution to say this is the sole purpose of the collection, this may
miss out on some very large areas of the institutions collection on another topic. Additionaly, some collections 
have such varied collections (both on topics and cataloguing types) that a single type and topic obscure this.
To try to give a wider view, sub-collections are also shown, able to have different topics and types, and 
there are presentations of the data at the sub-collections level. Ideally both would be visible in one chart, but this
information density starts to become unreadable as a visualisation.

Sub-collections are sometimes fairly clearly delineated by the institution itself, either where a institution is formed
of multiple smaller institutions, or it is formed of a set of individual collections. Sub-collections could be taken 
down to the department level as well, but this would require a large amount of work and understanding of each 
institutions structure that is not always possible to discover from the website.

### Types

The institution types are:

  * Archive
  * Building
  * Gallery
  * Library
  * Museum
  * University

## Artefacts

How an institution states the size of its collection is varied. The words artefacts, items, objects, records, images and so on are
all used and it is not always clear if that refers to the physical objects in its collections; to the records of the objects; to museum 
objects only or all (museum, library, archives); if the numbers are precise or estimated; and so on. Some institutions will include
millions of archive items in their number of artefacts, others with likely larger collections do not include their archives in their
figures so appear to have fewer "artefacts". Until some standard lightweight agreement is settled on how these sizes could be presented
with  agreed definitions it has to be shown as is, with some obvious inconsistencies.

## Records

The records count has been taken from the institutions website but it could be one of many ways:

  * Annual Report
  * Statement on the website ("Collections site containing X searchable records of our Y artefacts")
  * Collections search showing total number of records
  * Collections search - Running an empty query to get the total number
  * Collections search - Running a query with wildcard to get the total number
  * Collections Search - Summing up counts from individual collections after an empty search

And some more one-off variations on this. The sadly least common is the provision of an API to allow these numbers to be retrieved, this
is again something that could be standardised to make monitoring of these numbers easier.

