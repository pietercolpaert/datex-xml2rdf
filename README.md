# Datex 2 RDF

This repo contains scripts to:
 1. Convert XML files in datex2 to RDF triples
 2. Generate the datex ontology (licensed CC BY SA NC 1.0 - XSLT script adapted from [xsd2owl](http://rhizomik.net/html/redefer/xsd2owl/)) in RDF from the XSD file available at http://datex2.eu

## Convert datex 2 XML files to RDF triples

_TODO_

## Generate the datex2 ontology

Check the folder ontology, in which you'll find an xslt file. You can generate the ontology as follows:

```bash
$ saxonb-xslt datex.xsd datex2owl.xsl
```

If you don't have saxonb-xslt installed, I'm sure you're able to find it (e.g., for ubuntu, you can `apt-get install` it).
