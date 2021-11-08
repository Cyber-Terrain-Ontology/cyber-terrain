# The Cyber Terrain
## Models of Cybersecurity
The talented cybersecurity expert has knowledge about multiple facets of the problem space. They hold mental models of how things work together. The cybersecurity community is composed of experts in multiple disciplines and multiple specialized models.

It is inconceiveable that a single model can adequately cover the whole of cybersecurity. The Cyber Terrain Ontology brings together a collection of ontologies that describe in greater detail the bigger picture of cyber situational awareness. It is an ontology alignment project that resolves ambiguity that can exist between the separate ontologies being integrated together.

### Essential Pieces to the Cybersecurity Puzzle
The Cyber Terrain contains:
* Adversary
* Defender
* Asset
* Vulnerability
* Risk
* TTP 
* Controls

### Upper Ontologies
* Organization
* SOSA

The Cyber Terrain Ontology is an ontology that imports the best of breed models.

## Ontology Style Guide
At this time, there is no Cyber Terrain Ontology Style Guide. 

When there are multiple contributors to an ontology each with there own style and conventions it is important that differences in style do not cause difficulty and confusion. In order to remove any stylistic differences in the ontology prior to pushing to its repository we use the rdf-toolkit to consistently format it.

By using the rdf-toolkit utility all but the significant changes are removed. This is a real timesaver for the reviewer of any Pull Request. They only have to review the significant changes because minor stylistic changes have been removed.

An easy way to ensure that you consistently use the rdf-toolkit is to write a precommit script which gets executed when you commit any changes to your local repositiory.
The rdf-toolkit is a command-line tool for reading and writing RDF and OWL files. The primary reason the tool was created was to have a formatter that consistently creates ontologies for storing in a GitHub repository with multiple contributors.
This will be used in a commit-hook to make sure that all RDF files in the repo are stored in the same way.
The recommended Output Format for the Cyber Terrain Ontology is RDF/XML. 
For additional information on the rdf-toolkit see: https://github.com/edmcouncil/rdf-toolkit/blob/master/docs/RdfFormatter.md 

