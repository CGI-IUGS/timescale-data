# Geologic Timescale

Multiple versions of a RDF representation of the ISC are in https://github.com/CGI-IUGS/timescale-data/tree/master/rdf. 
These are based on data published by the **International Commission on Stratigraphy** at https://stratigraphy.org/chart. 

ISC Timescale vocabularies after ISC2016-12 are formalized according to geologic timescale ontology http://resource.geosciml.org/ontology/timescale/gts, which aligns with OWL-Time (http://www.w3.org/2006/time), and imports SOSA (http://www.w3.org/ns/sosa/), a lightweight alignment with ISO19156. Spatial data uses GeoSPARQL.

ISC timescale vocabularies for ISC2004 through ISC2016-10 are formalized according to the geologic timescale ontology http://resource.geosciml.org/ontology/timescale/v3.0/gts-30, using the THORS/GTS model aligned to ISO 19108 temporal schema and ISO 19156 Obsservations schema, as described in https://link.springer.com/article/10.1007/s12145-014-0170-6 

**NOTE:** this repository is the current maintenance location for the RDF implementation of the timescale. 
It was forked from https://github.com/GeoscienceAustralia/geosciml.org/tree/master/resource/static/vocabulary/timescale 
