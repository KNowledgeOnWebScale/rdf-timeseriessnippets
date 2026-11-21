# RDF Time Series Sources

RDF Time Series Sources (RDF-TSS) describes how to connect an RDF knowledge graph to time series: the readings stay compact, in the metadata or in an external CSV, Parquet or Arrow file, and RDF describes where they are and what they mean.

[Read the spec](https://knowledgeonwebscale.github.io/rdf-tss/)

## Developing

Build the spec using [Bikeshed](https://speced.github.io/bikeshed):

```
bikeshed spec spec.bs <output file>
```

## Vocabulary

The terms are in [tss.ttl](tss.ttl), under [CC BY 4.0](https://creativecommons.org/licenses/by/4.0/).
