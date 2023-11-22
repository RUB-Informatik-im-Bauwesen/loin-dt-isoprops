Markdown documentation created by [pyLODE](http://github.com/rdflib/pyLODE) 2.4

# Data Template (TMP) Ontology

## Metadata
* **IRI**
  * `http://inf.bi.rub.de/ontology/tmp`
* **Creators(s)**
  * [Liu Liu](https://orcid.org/0000-0001-5907-7609)
    [[ORCID]](https://orcid.org/0000-0001-5907-7609)
    (<liu.liu-m6r@rub.de></a>) of [Ruhr University Bochum](https://www.inf.bi.ruhr-uni-bochum.de/iib/lehrstuhl/mitarbeiter/liu_liu.html.en)
  * [Marthina Mellenthin-Filardo](https://orcid.org/0000-0001-7759-7579)
    [[ORCID]](https://orcid.org/0000-0001-7759-7579)
    (<martina.mellenthin.filardo@uni-weimar.de></a>) of [Bauhaus-Universitaet Weimar](https://www.uni-weimar.de/en/civil-engineering/chairs/construction-engineering-and-management/people/martina-mellenthin-filardo-msc/)
  * [Philipp Hagedorn](https://orcid.org/0000-0002-6249-243X)
    [[ORCID]](https://orcid.org/0000-0002-6249-243X)
    (<philipp.hagedorn-n6v@rub.de></a>) of [Ruhr University Bochum](https://www.inf.bi.ruhr-uni-bochum.de/iib/lehrstuhl/mitarbeiter/philipp_hagedorn.html.en)
  * [Sven Zentgraf](https://orcid.org/0000-0001-6058-7614)
    [[ORCID]](https://orcid.org/0000-0001-6058-7614)
    (<sven.zentgraf@rub.de></a>) of [Ruhr University Bochum](https://www.inf.bi.ruhr-uni-bochum.de/iib/lehrstuhl/mitarbeiter/sven_zentgraf.html.en)
* **Created**
  * 2023-12-23
* **Version Information**
  * 1.0
* **Imports**
  * [https://w3id.org/iddo/v2](https://w3id.org/iddo/v2)
  * [https://w3id.org/loin/v2](https://w3id.org/loin/v2)
* **License &amp; Rights**
  * [https://creativecommons.org/licenses/by/4.0/](https://creativecommons.org/licenses/by/4.0/)
  * &copy; 2024 by Chair of Computing in Engineering, Ruhr University Bochum and Chair of Construction Management, Bauhaus Universitaet Weimar
* **Source**
  * [https://github.com/RUB-Informatik-im-Bauwesen/tmp-ontology](https://github.com/RUB-Informatik-im-Bauwesen/tmp-ontology)
* **Ontology RDF**
  * RDF ([dt.ttl](turtle))
### Description
<p>The Data Template (TMP) Ontology is defined for ...</p>

## Table of Contents
1. [Classes](#classes)
1. [Object Properties](#objectproperties)
1. [Namespaces](#namespaces)
1. [Legend](#legend)


## Overview

**Figure 1:** Ontology overview
## Classes
[Construction object](#Constructionobject),
[Data template](#Datatemplate),
[Library component](#Librarycomponent),
### Construction object
Property | Value
--- | ---
IRI | `http://inf.bi.rub.de/ontology/dt#ConstructionObject`
Description | <p>Enter a comment</p>
Super-classes |[dt:LibraryComponent](http://inf.bi.rub.de/ontology/dt#LibraryComponent) (c)<br />
### Data template
Property | Value
--- | ---
IRI | `http://inf.bi.rub.de/ontology/dt#DataTemplate`
Description | <p>Enter a comment</p>
Super-classes |[dt:LibraryComponent](http://inf.bi.rub.de/ontology/dt#LibraryComponent) (c)<br />
Restrictions |[dt:hasProperty](http://inf.bi.rub.de/ontology/dt#hasProperty) (op) **some** [https://w3id.org/iddo/v2#Property](https://w3id.org/iddo/v2#Property) (c)<br />[dt:isDataTemplateFor](http://inf.bi.rub.de/ontology/dt#isDataTemplateFor) (op) **some** [https://w3id.org/loin/v2#SpecificationPerObjectType](https://w3id.org/loin/v2#SpecificationPerObjectType) (c)<br />[dt:hasSetOfProperties](http://inf.bi.rub.de/ontology/dt#hasSetOfProperties) (op) **some** [https://w3id.org/iddo/v2#GroupOfProperties](https://w3id.org/iddo/v2#GroupOfProperties) (c)<br />
In domain of |[dt:hasSetOfProperties](http://inf.bi.rub.de/ontology/dt#hasSetOfProperties) (op)<br />[dt:isDataTemplateFor](http://inf.bi.rub.de/ontology/dt#isDataTemplateFor) (op)<br />[dt:hasProperty](http://inf.bi.rub.de/ontology/dt#hasProperty) (op)<br />
### Library component
Property | Value
--- | ---
IRI | `http://inf.bi.rub.de/ontology/dt#LibraryComponent`
Description | <p>Enter a comment</p>
Super-classes |[rdfs:Resource](http://www.w3.org/2000/01/rdf-schema#Resource) (c)<br />
Sub-classes |[dt:ConstructionObject](http://inf.bi.rub.de/ontology/dt#ConstructionObject) (c)<br />[dt:DataTemplate](http://inf.bi.rub.de/ontology/dt#DataTemplate) (c)<br />

## Object Properties
[has property](#hasproperty),
[has set of properties](#hassetofproperties),
[is data template for](#isdatatemplatefor),
[](hasproperty)
### has property
Property | Value
--- | ---
IRI | `http://inf.bi.rub.de/ontology/dt#hasProperty`
Super-properties |[owl:topObjectProperty](http://www.w3.org/2002/07/owl#topObjectProperty)<br />
Domain(s) |[dt:DataTemplate](http://inf.bi.rub.de/ontology/dt#DataTemplate) (c)<br />
Range(s) |[https://w3id.org/iddo/v2#Property](https://w3id.org/iddo/v2#Property) (c)<br />
[](hassetofproperties)
### has set of properties
Property | Value
--- | ---
IRI | `http://inf.bi.rub.de/ontology/dt#hasSetOfProperties`
Super-properties |[owl:topObjectProperty](http://www.w3.org/2002/07/owl#topObjectProperty)<br />
Domain(s) |[dt:DataTemplate](http://inf.bi.rub.de/ontology/dt#DataTemplate) (c)<br />
Range(s) |[https://w3id.org/iddo/v2#GroupOfProperties](https://w3id.org/iddo/v2#GroupOfProperties) (c)<br />
[](isdatatemplatefor)
### is data template for
Property | Value
--- | ---
IRI | `http://inf.bi.rub.de/ontology/dt#isDataTemplateFor`
Super-properties |[owl:topObjectProperty](http://www.w3.org/2002/07/owl#topObjectProperty)<br />
Domain(s) |[dt:DataTemplate](http://inf.bi.rub.de/ontology/dt#DataTemplate) (c)<br />
Range(s) |[https://w3id.org/loin/v2#SpecificationPerObjectType](https://w3id.org/loin/v2#SpecificationPerObjectType) (c)<br />

## Named Individuals
## Namespaces
* **dc**
  * `http://purl.org/dc/terms/`
* **dt**
  * `http://inf.bi.rub.de/ontology/dt#`
* **owl**
  * `http://www.w3.org/2002/07/owl#`
* **prov**
  * `http://www.w3.org/ns/prov#`
* **rdf**
  * `http://www.w3.org/1999/02/22-rdf-syntax-ns#`
* **rdfs**
  * `http://www.w3.org/2000/01/rdf-schema#`
* **sdo**
  * `https://schema.org/`
* **skos**
  * `http://www.w3.org/2004/02/skos/core#`
* **vann**
  * `http://purl.org/vocab/vann/`
* **vs**
  * `http://www.w3.org/2003/06/sw-vocab-status/ns#`
* **xml**
  * `http://www.w3.org/XML/1998/namespace`
* **xsd**
  * `http://www.w3.org/2001/XMLSchema#`

## Legend
* Classes: c
* Object Properties: op
* Functional Properties: fp
* Data Properties: dp
* Annotation Properties: dp
* Properties: p
* Named Individuals: ni