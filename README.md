# Chronicling Novelty data dump

This repository contains the (annotated) XML files of the chronicles corpus that was created in the context of the NWO project _Chronicling Novelty. New knowledge in the Netherlands 1500-1850_, which ran from 2018 to 2024.

Creators: Judith Pollmann, Erika Kuijpers, Carolina Lenarduzzi, Theo Dekker, Alie Lassche, Roser Morante 

## Repository Organization

The organization of this repository is as follows:
```
├── handleidingen/
│   ├── Annotatie_instructie_Vele_Handen.pdf            <- Tutorial for annotating chronicles (in Dutch)
│   ├── Annotatie_instructie_bronnen_Vele_Handen.pdf    <- Tutorial for annotating sources in chronicles (in Dutch)
│   ├── Invoerinstructie_Transkribus_Lite.pdf           <- Tutorial for transcribing chronicles
│   └── Overview_Chronicles.xlsx                        <- Sheet with metadata of all chronicles                 
│
├── xmls_no_tags/                                       <- XML files of chronicles, without tags
│
├── xmls_with_source_tags/                              <- XML files of chronicles, containing tagged sources
│
└── xmls_with_tags/                                     <- XML files of chronicles, containing tags

```

## Tags

- Tags used in `xmls_with_tags`:
    - `datum` (date)
    - `locatie` (location)
    - `persoonsnaam` (person name)
    - `pagenumber`
    - `margetekst` (margin text)
    - `lijstjes_en_tabellen` (lists and tables)
    - `kopie` (copied text)
    - `afbeelding` (image)
    - `drukwerk` (printed text)

- Tags used in `xmls_with_source_tags`:
    - `informatiebron` (source)
    - `ontvanger` (receiver)
    - `waarneming` (perception)


## Publications
For a detailed description of the corpus:
- Theo Dekker, Erika Kuijpers, Alie Lassche, Carolina Lenarduzzi, Roser Morante, and Judith Pollmann. 2024. [The Kronieken Corpus: an Annotated Collection of Dutch/Flemish Chronicles from 1500-1850](https://aclanthology.org/2024.latechclfl-1.24). In _Proceedings of the 8th Joint SIGHUM Workshop on Computational Linguistics for Cultural Heritage, Social Sciences, Humanities and Literature (LaTeCH-CLfL 2024)_, pages 243–252, St. Julians, Malta. Association for Computational Linguistics.
  
### Other publications
- Roser Morante, Eleanor L. T. Smith, Lianne Wilhelmus, Alie Lassche, and Erika Kuijpers. 2022. [Identifying Copied Fragments in a 18th Century Dutch Chronicle](https://aclanthology.org/2022.lrec-1.631). In _Proceedings of the Thirteenth Language Resources and Evaluation Conference_, pages 5865–5878, Marseille, France. European Language Resources Association.
- Alie Lassche and Roser Morante. 2021. [The Early Modern Dutch Mediascape. Detecting Media Mentions in Chronicles Using Word Embeddings and CRF](https://aclanthology.org/2021.latechclfl-1.1). In _Proceedings of the 5th Joint SIGHUM Workshop on Computational Linguistics for Cultural Heritage, Social Sciences, Humanities and Literature (LaTeCH-CLfL 2021)_, pages 1–10, Punta Cana, Dominican Republic (online). Association for Computational Linguistics.

---
Last edited by Alie Lassche, 13 August 2024
