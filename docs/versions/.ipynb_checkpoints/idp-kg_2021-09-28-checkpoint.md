---
layout: dataset

bioschemas:
  "@context": https://schema.org
  "@type": Dataset
  "http://purl.org/dc/terms/conformsTo":
  - "@type": CreativeWork
    "@id": "https://bioschemas.org/profiles/Dataset/0.4-DRAFT"
  "description": "Knowledge graph about Intrinsically Disordered Proteins generated from Bioschemas markup embedded within DisProt, MobiDB, and ProteinEnsemble."
  "identifier": "https://alasdairgray.github.io/IDP-KG/versions/idp-kg_2021-09-28"
  "keywords": "IDP, Protein"
  "license": "https://creativecommons.org/share-your-work/public-domain/cc0/"
  "name": "Intrinsically Disordered Proteins Knowledge Graph (IDP-KG)"
  "url": "https://alasdairgray.github.io/IDP-KG/versions/idp-kg_2021-09-28"
  "creator":
  - "@type": Person
    name: "Alasdair Gray"
    "@id": http://orcid.org/0000-0002-5711-4872
    "url": http://orcid.org/0000-0002-5711-4872
  - "@type": Person
    name: "Petros Papadopoulos"
    "@id": https://orcid.org/0000-0002-8110-7576
    url: https://orcid.org/0000-0002-8110-7576
  - "@type": Person
    name: "Imran Asif"
    "@id": https://orcid.org/0000-0002-1144-6265
    url: https://orcid.org/0000-0002-1144-6265
  - "@type": Person
    name: "Ivan Mi&ccaron;eti&cacute;"
    "@id": https://orcid.org/0000-0003-1691-8425
    url: https://orcid.org/0000-0003-1691-8425
  - "@type": Person
    name: "Andras Hatos"
    "@id": https://orcid.org/0000-0001-9224-9820
    url: https://orcid.org/0000-0001-9224-9820
  "distribution":
  - "@type": DataDownload
    "name": "IDP-KG_2021-09-28"
    "encodingFormat": "application/n-quads"
    "contentURL": https://github.com/AlasdairGray/IDP-KG/raw/04f501425ee658dbe9c46cfc5cda949b2fa1189b/notebooks/IDPKG-Full.nq
  "isBasedOn":
  - "@type": Dataset
    "@id": https://disprot.org/#2021-08
    "name": "DisProt"
    "url": https://disprot.org/#2021-08
  - "@type": Dataset
    "@id": https://mobidb.org/#2020-09
    "name": "MobiDB"
    "url": https://mobidb.org/#2020-09
  - "@type": Dataset
    "@id": https://proteinensemble.org/#2020_10
    "name": "Protein Ensemble"
    "url": https://proteinensemble.org/#2020_10
  "version": "2021-09-28"
hcls:
  triples: 278572
  types:
  - Dataset: 2
    DataCatalog: 2
---
