This folder contains OWL ontology files for the TB21 GIMI metadata. 
They are arranged as follows:

- [geo.ttl](geo.ttl) - a copy of the GeoSPARQL ontology from https://github.com/opengeospatial/ogc-geosparql/tree/master/vocabularies
- [sf_geometries.ttl](sf_geometries.ttl) - a copy of the Simple Features extension to GeoSPARQL ontology from https://github.com/opengeospatial/ogc-geosparql/tree/master/vocabularies
- [tb21-geosparql.ttl](tb21-geosparql.ttl) - a GeoSPARQL alignment to BFO/CCO
- [tb21-region.ttl](tb21-region.ttl) - an extension of BFO/CCO for region-of-interest
- [tb21-image.ttl](tb21-image.ttl) - image definition, corner correspondences, cell-properties schema
- [tb21-coord.ttl](tb21-coord.ttl) - Coordinate and Coordinate Reference Systems elements based on CCO
- SWE Common (some experiments)
  - [swecommon-data-record.ttl](swecommon-data-record.ttl) - a manually constructed OWL Ontology that attempts to implement the JSON Schema implementation of the [SWE Common Data Model Encoding Standard v3.0](https://docs.ogc.org/is/24-014/24-014.html) 
  - [swecommon-data-record-uml.ttl](swecommon-data-record-uml.ttl) - a manually constructed OWL Ontology that attempts to implement the UML implementation of the [SWE Common Data Model Encoding Standard v3.0](https://docs.ogc.org/is/24-014/24-014.html)

The files are in OWL/TTL format.

These files are example ontology artifacts prepared solely for OGC Testbed 21 reporting and demonstration activities. 
They is based on a point in time developmental ontology slim and are not an official NGA, GMSB, or IDO ontology release. 
The IRIs, labels, definitions, axioms, and module structure in these files should not be treated as authoritative, stable, reusable, or suitable for incorporation into OGC baseline standards, operational systems, or future testbed activities.

Future work should reference officially published GMSB IDO releases when they become available.

