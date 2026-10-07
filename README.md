# Chieri 1328–1329: councils, sapienti and notaries of the commune

*I consigli, i sapienti e i notai del comune di Chieri nel 1328–1329*

**db** · 1998 · version 1998  
Author: **Massimo Sbarbaro** ([ORCID 0009-0006-8965-9013](https://orcid.org/0009-0006-8965-9013))

## Overview

A prosopographical database of the political personnel of the commune of Chieri (Piedmont) in the year 1328–1329. It records the members of the major council (*maggior consiglio*), of the added council (*consiglio aggiunto*) and of the council of the forty-six *sapienti*, the *sapienti* elected month by month, and the notaries of the commune with the length of their office and the person who elected them. Saved queries and reports find the people who sat in more than one council, the notaries who were also councillors, the absences from the councils and the grouping of members by family.

I designed this database and entered and analysed the data in 1998, as part of my historical research. It is published here with all its data, so that the results can be checked and reused.

## Tables

| Table | Records | Content |
|---|---|---|
| `Tabella delle persone elette al maggior consiglio di Chieri` | 149 | Members of the major council: title *dominus*, first name, surname, fines/absences. |
| `Elenco delle persone elette al consiglio aggiunto` | 75 | Members of the added council. |
| `Elenco delle persone elette al consiglio dei XLVI sapienti` | 47 | Members of the council of the forty-six *sapienti*. |
| `Elenco dei sapienti eletti nei vari mesi del 1328 -1329` | 48 | *Sapienti* elected each month (four per month, November–October), with folio reference. |
| `Tabella dei notai del comne di Chieri` | 18 | Notaries of the commune: date, folio, duration of office, type (*del comune*, *massario*), elector. |

## Method

The tables are flat lists without keys: people are linked across councils by matching first name and surname, and families by surname. The field *Ammende* contains letter codes (a–i) that mark fines or absences in the sessions of the council; their key is not recorded in the database. Folio references (e.g. `f. 13 r.`, `f. 23* v.`) are those of the edition.

## Sources

- Data entered from the printed edition: Brezzi, Paolo, ed. 1937. *Gli Ordinati del Comune di Chieri. 1328–1329*. Torino: Regia Deputazione Subalpina di Storia Patria.

## Repository contents

| Path | Content |
|---|---|
| `database/Chieri 1998.mdb` | The original db with all data, queries, forms and reports. |
| `data/*.csv` | Every table exported as UTF-8 CSV. |
| `docs/schema.md` | Tables and fields. |

## How to cite

> Sbarbaro, Massimo. 1998. *Chieri 1328–1329: councils, sapienti and notaries of the commune*. Dataset (db, 1998), version 1998. Zenodo.

## License

Data and database are released under the [Creative Commons Attribution 4.0 International](LICENSE) license (CC BY 4.0). 
