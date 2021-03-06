---
layout: page
title: "Vocabulary"
header: "Vocabulary"
group: navigation
description: ""
---

## CTS concepts equivalency table

This table has been written by B. Almas and H. Cayless in the context of the Distributed Text Services efforts.

{: .table .table-striped .table-hover}
| CTS         | LAWD                  | FRBR       | Concept                             | Notes                                                                                                                                                                                                                                                                                                      |
|-------------|-----------------------|------------|-------------------------------------|------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| Namespace   | N/A                   | N/A        | Naming Authority, Collection        | The intent of the CTS namespace was to serve as a naming authority for a set of CTS URN identifiers in order to be able to declare uniqueness of all textgroup identifiers only within the scope of a given namespace. In practice, this has been interpreted mainly as a Collection or Corpus identifier. |
| Textgroup   | N/A                   | N/A        | Collection, Author/logical grouping | an identifier for any group of texts that are conventionally cited together in the naming authority's tradition                                                                                                                                                                                            |
| Work        | ConceptualWork        | Work       | Abstract Work                       |                                                                                                                                                                                                                                                                                                            |
| Version     | WrittenWork, Edition  | Expression | Digital Edition                     | According to LAWD, an "Edition" is a published version of a WrittenWork; I think this might correspond more closely to the CTS concept of "Version" than just WrittenWork because a CTS Version is a distinct publication of an expression of a Conceptual Work                                            |
| Edition     | Written Work, Edition | Expression | Digital Edition                     | a CTS Edition is a type of a CTS version, with the restriction that it must be an expression of a work in the original source language of the work                                                                                                                                                         |
| Translation | Translation           | Expression | Digital Edition                     | a CTS Edition is a type of a CTS version, with the restriction that it must be an expression of a work in a different language than the original source language of the work                                                                                                                               |
| Exemplar    | n/a                   | Item       | Derived Resource                    | The HMT has been using Exemplars to represent specific derivations of a CTS version created for the purpose of analysis and unambiguous citation at the level of the token. E.g. a tokenization by morphemes. This might be more of a derivation than an interpretation but it has elements of both.       |
| Passage     | Citation              | N/A        | Resource Fragment                   | a CTS Passage identifies a singe citable section of a work - it might be a single "node" or a range of "nodes" 

## CTS Request Diagram

![CTS Request Diagram](/assets/images/CTS_Calls.png)