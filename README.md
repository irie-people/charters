# Charters

Thirty-eight texts of rights as a map to explore: **https://irie-people.github.io/charters/**

From Magna Carta (1215) to the Convention on the Rights of Persons with Disabilities (2006), with the Declaration of Independence, the Constitution and the Bill of Rights among them. The texts lie on a timeline by when and where they were made, with how each drew on the ones before it, their articles and sections, and the rights and ideas each one names. Pick one and the map lights what it bears on; the card beside it gives the words.

## Where it comes from

The page is made by [Irie](https://github.com/irie-people/irie)'s Charters plugin, which keeps the texts word for word from the bodies that keep them, each checked against other copies. Irie's [verification.md](https://github.com/irie-people/irie/blob/main/internal/skills/bundled/founding-documents/verification.md) says what each text was checked against and gives each file's SHA-512, and its [proposal](https://github.com/irie-people/irie/blob/main/docs/proposals/founding-documents.md) says how the map finds its links, parts and rights. In Irie's Mac app the same map is Window › Charters Graph.

The links between the texts are a reading of them, each quoting both texts word for word. A right or idea is shown where its words are in a text's own passages, and the page shows the words each one rests on.

## Terms

The page's code is Irie's, under the Apache License 2.0 ([LICENSE](LICENSE)). The texts keep their own terms, which each text's card on the page states and Irie's [PROVENANCE.md](https://github.com/irie-people/irie/blob/main/PROVENANCE.md) lists. The United Kingdom's texts contain public sector information licensed under the Open Government Licence v3.0. Sweden's Press Act of 1766 is Ian Giles and Peter Graves's translation, under CC BY 4.0.

## Updating it

The page is one file that loads nothing from elsewhere. From an Irie checkout, `go run ./tools/charters PATH-TO-THIS-CHECKOUT` writes it again.
