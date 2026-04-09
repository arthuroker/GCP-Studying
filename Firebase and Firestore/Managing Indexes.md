
In Firestore, documents can have further documents associated with them

This establishes relationships and hierarchies within the data model

A collection can contain one or more documents

A document can optionally contain one or more sub-collections

A sub-collection can contain one or more documents

*Exploding compound indexes*

To support enough filters, Filestore may generate an index for each possible combination of these fields. This results in an exploding index as the combinations multiply across the multiple job attributes

To support querying documents, Filestore creates an index with an entry for each possible combination of values

Though, when multiple fields have a wide range of values, this can lead to a combinatorial explosion

To prevent this, you can manually configure your indexes in the index configuration file



