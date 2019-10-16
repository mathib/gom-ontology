# The GOM ontology - Geometry Metadata Ontology

## HTML documentation and raw ontology per serialisation

* base URI: [https://w3id.org/gom#](https://mathib.github.io/gom-ontology/#)
* Canonical URI for the HTML representation: [https://w3id.org/gom/gom.html](https://mathib.github.io/gom-ontology/#)
* Canonical URI for the Turtle representation: [https://w3id.org/gom/gom.ttl](https://mathib.github.io/gom-ontology/ontology.ttl)
* Canonical URI for the n-triples representation: [https://w3id.org/gom/gom.nt](https://mathib.github.io/gom-ontology/ontology.nt)
* Canonical URI for the json-ld representation: [https://w3id.org/gom/gom.jsonld](https://mathib.github.io/gom-ontology/ontology.json)
* Canonical URI for the RDF/XML representation: [https://w3id.org/gom/gom.rdf](https://mathib.github.io/gom-ontology/ontology.xml)

The most recent version of GOM is always available in this Github repository

## Introduction to GOM

The Geometry Metadata Ontology (GOM) provides terminology for specifying the Coordinate System (CS), length units and additional metadata related to geometry descriptions. It is designed to be at least compatible with [OMG](https://w3id.org/omg#) / [FOG](https://w3id.org/fog#) linking methods. It can be used with [OMG level 2 or 3 links](https://w3id.org/omg#description) (1, resp 2 intermediate nodes between object and geometry description).

## Contributing to GOM

Additional geometry modelling/processing applications can be added as **instances** of the `gom:GeometryModellingApplication` class. If you notice that some geometry application is missing and you need it for your project, you can either create an issue in the [Github repository](https://github.com/mathib/gom-ontology), or you can fork it and submit a pull request.

## sparql-visualizer demo

An [online sparql-visualizer demo](https://madsholten.github.io/sparql-visualizer/?file=https://raw.githubusercontent.com/mathib/gom-ontology/master/examples/gom-demo.json) is available, containing sample Abox triples and example queries. 

## Contributors

[Mathias Bonduel](https://github.com/mathib) - KU Leuven

[Anna Wagner](https://github.com/AnnaWagner) - TU Darmstadt

[Pieter Pauwels](https://github.com/pipauwel) - UGent

## References

The GOM ontology module extends OMG (Ontology for Managing Geometry), documented in the following paper:

* Wagner, A., Bonduel, M., Pauwels, P. & Rüppel, U. (2019). Relating Geometry Descriptions to its Derivatives on the Web. In *Proceedings of the European Conference on Computing in Construction (EC3 2019)*. Chania, Greece.

The terminology of GOM can be used with the OMG / FOG linking method. FOG extends OMG for geometry schema specific properties. More information can be found in:

* Bonduel, M., Wagner, A., Pauwels, P., Vergauwen, M., & Klein, R. (2019). Including Widespread Geometry Formats in Semantic Graphs Using RDF Literals. In *Proceedings of the European Conference on Computing in Construction (EC3 2019)*. Chania, Greece.
