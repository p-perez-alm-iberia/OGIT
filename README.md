![Logo](/docs/images/OGIT_Logo.jpg)
# Welcome to the _Open Graph of IT_ Ontology

## Overview

_Open Graph of IT_ (OGIT) aims to build a semantic representation of all IT and its interaction with business processes and people.
Such an endeavour requires a sound data space as a foundation for computational evaluation of this enterprise space.
OGIT aims to become the 'IT version' of **Google's Knowledge Graph** or Facebook's **Social Graph**.
Hence we need a common language for IT entities and relationships between them.

OGIT aims to provide a such common language by defining an ontology for the _Graph of IT_.

The OGIT project is not only a hosting place for a specification. It also
provides a platform for domain experts to contribute to the ontology.
One of the basic principles is: _evolution over standardization_.

## OGIT Documentation

Find out more about OGIT using the following links.

* [Basic Concepts](https://github.com/almatoai/OGIT/wiki/Basic-Concepts)
* [OGIT ontology details](https://github.com/almatoai/OGIT/wiki/OGIT-ontology-details)
* [Maintaining the ontology](https://github.com/almatoai/OGIT/wiki/Maintaining-the-ontology)
* Get started with an implementation:
	+ [Using OGIT in Apache Jena Fuseki](https://github.com/almatoai/OGIT/wiki/Using-Fuseki)
	+ [Using OGIT with Apache Tinkerpop](https://github.com/almatoai/OGIT/wiki/Using-Tinkerpop)
	+ [Using OGIT in Cayley](https://github.com/almatoai/OGIT/wiki/Using-Cayley)
* [High level use cases](https://github.com/arago/OGIT/wiki/High-level-use-cases)
* [Contributing to the ontology](https://github.com/arago/OGIT/wiki/Contributing)

## GraphIT Documentation

There is an application called [GraphIT](https://graphit.co) that allows you to
manage IT data through a RESTful API ensuring compliance to the OGIT ontology.

The following links provide more information on OGIT and GraphIT.

(Pages updated on daily basis)

* [OGIT documentation](https://arago.github.io/OGIT/) for all elements of the OGIT ontology
* [OGIT namespace documentation](https://arago.github.io/OGIT/downloads)- documentation as PDF and Diagram for each namespace of the OGIT ontology
* [GraphIT developer resources](https://docs.hiro.arago.co) (free registration required)

### namespace specific Documentation
* Requirements
  + install pdflatex (on macOS run: `brew cask install mactex`)
  + install graphviz (on macOS run: `brew install graphviz`)
  + install doxygen (on macOS run: `brew install doxygen`)

* Run the following script to generate the documentation. Replace the namespacename with the name of the namespace(for ex. MRP, Accouting, Auth etc.) you want to create the documentation.  
````
sh namespace.sh namespacename
````
* It will generate the pdf and png files which can be found under folder with namespacename (for ex. MRP, Accounting etc). 
* For Example, **sh namespace.sh mrp** will generate the documentation for MRP namepsace under **MRP folder**.

## Getting Support

If you have general questions or need support please contact us at <info@almato.com>.

## License

Please see [LICENSE.md](LICENSE.md) for information about the licensing of OGIT and its components.








