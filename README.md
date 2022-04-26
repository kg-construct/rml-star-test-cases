# RML-star test-cases
The RML-star test cases are used to determine the conformance to the [RML-star specification](https://w3id.org/kg-construct/rml-star) of tools that execute RML-star rules.

In the folder test-cases you can find the different test cases. Each test case is comprised in a single folder, and contains three types of files:
- Zero or more files containing the data sources in CSV format
- One file with the RML-star rules, called mapping.ttl, in the Turtle format.
- Zero or one file with the expected RDF-star extracted from the [N-Triples RDF-star test-cases](https://w3c.github.io/rdf-star/tests/nt/syntax/). No file is provided if an error is expected that must halt the generation of the RDF-star.

Each RDF-star test case is transformed to two different RML-star test-cases: RMLSTARTCXXXa cases do not contain joins among sources, while RMLSTARTCXXXb cases do.

## License
This code is copyrighted under the Apache 2.0 License
