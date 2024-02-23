# trove-parliamentary-papers-data

A GLAM Workbench data repository

These datasets were generated using notebooks in the [trove-government](https://github.com/GLAM-Workbench/trove-government/) repository.

For more information and documentation see the [Trove government](https://glam-workbench.net/trove-government) section of the [GLAM Workbench](https://glam-workbench.net).

## Dataset summary
- [trove-parliamentary-papers.csv](https://github.com/GLAM-Workbench/trove-parliamentary-papers-data/raw/main/trove-parliamentary-papers.csv) (30.1 MB, text/csv)


## Dataset contents

### [trove-parliamentary-papers.csv](https://github.com/GLAM-Workbench/trove-parliamentary-papers-data/raw/main/trove-parliamentary-papers.csv)

|                |                                                                                                                                                                                                                                                                                           |
|:---------------|:------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| date harvested | 2024-02-15                                                                                                                                                                                                                                                                                |
| file size      | 30.1 MB                                                                                                                                                                                                                                                                                   |
| format         | text/csv                                                                                                                                                                                                                                                                                  |
| created by     | <a href='https://github.com/GLAM-Workbench/trove-government/blob/master/harvest-parliamentary-papers.ipynb'>Harvest details of Commonwealth Parliamentary Papers digitised in Trove</a> ([documentation](https://glam-workbench.net/trove-government/harvest-parliament-press-releases/)) |
| number of rows | 24997                                                                                                                                                                                                                                                                                     |
| description    | This dataset contains metadata describing Commonwealth Parliamentary Papers that have been digitised and are made available through Trove.                                                                                                                                                |
| license        | [CC0 Public Domain Dedication](https://creativecommons.org/publicdomain/zero/1.0/)                                                                                                                                                                                                        |

#### Columns

| name                | type    | description                                                                                                        |
|:--------------------|:--------|:-------------------------------------------------------------------------------------------------------------------|
| `title`             | string  | title of the work; multiple values separated by | symbol                                                           |
| `alternative_title` | string  | can include additional publication details such as year and number, eg: 'Vol. 2 (1991/1992), PP no. 384 of 1993'   |
| `contributor`       | string  | contributors such as government agencies or committees; multiple values separated by | symbol                      |
| `publisher`         | string  | multiple values separated by | symbol                                                                              |
| `date`              | string  | publication date; multiple values separated by | symbol                                                            |
| `type`              | string  | eg: 'text'; multiple values separated by | symbol                                                                  |
| `format`            | string  | eg: 'Book', 'volume'; multiple values separated by | symbol                                                        |
| `extent`            | string  | size or physical dimensions, can include number of pages or number of words; multiple values separated by | symbol |
| `language`          | string  | publication language; multiple values separated by | symbol                                                        |
| `subject`           | string  | associated subject headings; multiple values separated by | symbol                                                 |
| `is_part_of`        | string  | collections or series this publication is part of; multiple values separated by | symbol                           |
| `identifier`        | string  | library identifiers; multiple values separated by | symbol                                                         |
| `rights`            | string  | copyright and licensing information; multiple values separated by | symbol                                         |
| `pages`             | integer | number of digitised pages (includes covers and endleaves)                                                          |
| `fulltext_url`      | string  | link to digitised book viewer                                                                                      |
| `fulltext_url_text` | string  | text of link to digitised book viewer                                                                              |
| `text_download_url` | string  | link to download OCRd text of book                                                                                 |
| `catalogue_url`     | string  | link to NLA catalogue; multiple values separated by | symbol                                                       |
| `work_url`          | string  | link to work record in Trove; multiple values separated by | symbol                                                |
| `work_type`         | string  | Trove work format, eg: 'Book'; multiple values separated by | symbol                                               |
| `parent`            | string  | parent work identifiers; multiple values separated by | symbol                                                     |
| `parent_url`        | string  | parent work links; multiple values separated by | symbol                                                           |
| `children`          | any     | child work identifiers; multiple values separated by | symbol                                                      |

## Examples of use

- [Explore using Datasette](https://glam-workbench.net/datasette-lite/?csv=https://media.githubusercontent.com/media/GLAM-Workbench/trove-parliamentary-papers-data/main/trove-parliamentary-papers.csv&fts=title,alternative_title,contributor&drop=work_type,fulltext_url_text,parent,parent_url,children)
- [Visualised in the *Trove Data Guide*](https://tdg.glam-workbench.net/other-digitised-resources/parliamentary-papers/overview.html)


----
Created by [Tim Sherratt](https://timsherratt.au) for the [GLAM Workbench](https://glam-workbench.net)