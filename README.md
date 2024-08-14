# The kronieken dataset

This repository contains the (annotated) XML files of the corpus of chronicles that was created in the context of the NWO project _Chronicling Novelty. New knowledge in the Netherlands 1500-1850_, which ran from 2018 to 2024.

Creators: Judith Pollmann, Erika Kuijpers, Carolina Lenarduzzi, Theo Dekker, Alie Lassche, Roser Morante and with the help of many student assistants and volunteers, see the credits file.

## Licence

Attribution 4.0 International CC BY 4.0

## Repository Organization

The organization of this repository is as follows:
```
├── handleidingen/
│   ├── Annotatie_instructie_Vele_Handen.pdf            <- Tutorial for annotating chronicles (in Dutch)
│   ├── Annotatie_instructie_bronnen_Vele_Handen.pdf    <- Tutorial for annotating sources in chronicles (in Dutch)
│   ├── Invoerinstructie_Transkribus_Lite.pdf           <- Tutorial for transcribing chronicles
│                  
├─- Metadata/                                           <- csv files with metadata on provenance, authors and chronicles + overview of which chronicles have which tags
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

## Other Data publications

- Scans of the manuscripts together with the transcriptions and annotations can be viewed and searched on [this](https://kronieken.transkribus.eu/) website. 
- Notes on the individual chronicles and their authors can be found [here](https://chroniclingnovelty.github.io/corpus-documentation/about/).

## Publications
For a detailed description of the corpus:
- Theo Dekker, Erika Kuijpers, Alie Lassche, Carolina Lenarduzzi, Roser Morante, and Judith Pollmann. 2024. [The Kronieken Corpus: an Annotated Collection of Dutch/Flemish Chronicles from 1500-1850](https://aclanthology.org/2024.latechclfl-1.24). In _Proceedings of the 8th Joint SIGHUM Workshop on Computational Linguistics for Cultural Heritage, Social Sciences, Humanities and Literature (LaTeCH-CLfL 2024)_, pages 243–252, St. Julians, Malta. Association for Computational Linguistics.
- Kuijpers, Erika, Carolina Lenarduzzi, Judith Pollmann, Theo Dekker, and Alie Lassche. Forthcoming 2024. ‘Profiling Local Chroniclers in the Early Modern Low Countries’. _Urban History_.

  
### Other publications
- Dekker, T. (2022a). [God’s Invisible Particles as an Explanation for the Rinderpest Outbreak (1713–1714): The Reception of Medical Knowledge in the Dutch Republic](https://doi.org/10.1163/26667711-20220006). European Journal for the History of Medicine and Health, 79(1), 152–168. 
- Dekker, T. (2022b). [Statistiek van de koude grond: De opkomst van cijfers en tabellen in vroegmoderne kronieken](https://doi.org/10.5117/DAE2022.007.DEKK). Jaarboek de Achttiende Eeuw, 54(1), 110–129. 
- Dekker, T. (2024). Engaging with New Knowledge in Low Countries’ Chronicles (1500-1850) [Doctoral dissertation]. Universiteit Leiden.
- Dekker, T., Kuijpers, E., & Lenarduzzi, C. (2023). Van crowdsourcing naar echte burgerwetenschap. Investeer in de kwaliteit van samenwerking. Stadsgeschiedenis, 18 (2), 105–117.
- Dekker, T. M. a. M. (2023). [Coping with epidemics in early modern chronicles, the Low Countries, 1500–1850](https://doi.org/10.5117/9789463725798). In H. van Asperen & J. L (Eds.), Dealing with disasters from early modern to modern times: Cultural responses to catastrophes (pp. 229–247). Amsterdam University Press. 
- Kuijpers, E. (2022). [De informatiebronnen van Albert Louwen (1722–1798), kroniekschrijver te Purmerend](https://doi.org/10.2307/j.ctv2q49zx2.8). In E. Kuijpers & G. Verhoeven (Eds.), Makelaars in kennis. Informatie verzamelen, verwerken en verspreiden in de vroegmoderne Nederlanden (pp. 131–158). Leuven University Press. 
- Lassche, A. (2024). Information Dynamics in Low Countries’ Chronicles (1500–1860). A Computational Approach [Doctoral dissertation]. Universiteit Leiden.
- Lassche, A., Kostkan, J., & Nielbo, K. (2022). [Chronicling Crises: Event Detection in Early Modern Chronicles from the Low Countries](https://ceur-ws.org/Vol-3290/#short_paper4697). In F. Karsdorp, A. Lassche, & K. Nielbo (Eds.), Proceedings of the Computational Humanities Research  Conference 2022 (Vol. 3290, pp. 215–230). CEUR. 
- Lassche, A., & Morante, R. (2021). [The Early Modern Dutch Mediascape. Detecting Media Mentions in Chronicles Using Word Embeddings and CRF](https://doi.org/10.18653/v1/2021.latechclfl-1.1). Proceedings of the 5th Joint SIGHUM Workshop on Computational Linguistics for Cultural Heritage, Social Sciences, Humanities and Literature, 1–10. 
- Pollmann, J. (2023). [The Spirit of the Belltower: Chronicling Urban Time in an Age of Revolution](https://doi.org/10.1007/978-3-031-09504-7_12). In J. Pollmann & H. te Velde (Eds.), Civic Continuities in an Age of Revolutionary Change, c.1750–1850: Europe and the Americas (pp. 271–293). Springer International Publishing.
- Smith, E. L. T., Wilhelmus, L., Kuijpers, E., Lassche, A., & Morante, R. (2022). [Identifying Copied Fragments in an 18th Century Dutch Chronicle. Proceedings of the 13th Conference on Language Resources and Evaluation](http://www.lrec-conf.org/proceedings/lrec2022/pdf/2022.lrec-1.631.pdf) (LREC 2022), 5865–5878.
- Somers, M. (Director). (2020, October 13). A Digital Future for Old News. Volunteers Are Unlocking 300 Chronicles [Video recording](https://vimeo.com/467642998). 


---
Last edited by Erika Kuijpers & Alie Lassche, 14 August 2024
