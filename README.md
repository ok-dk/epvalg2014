epvalg2014 [![CSV-status badge][travis-badge-img]][travis-badge-url] [![MIT-license badge][license-badge-img]][license-badge-url]
==========

Fra valgdataworkshop om Europa-parlamentsvalget 2014 og patentdomstolsafstemningen.

CSV- og TSV-Filer
-----------------

Filnavn | Beskrivelse | CSV-validitet
------------------------------|----------------------------------|:---------------------------------------------------------------------:
[`epvalg.csv`][epvalg]        | Stemmer på partier               | [![csvlint of epvalg.csv][epvalg-badge-img]][epvalg-badge-url]
[`patentdomstol.csv`][patent] | Ja/Nej-stemmer til patentdomstol | [![csvlint of patentdomstol.csv][patent-badge-img]][patent-badge-url]
`epvalgPersonlige.tsv`        | Stemmer på politikere            |

XLSX-Filer
----------

Filnavn | Beskrivelse
------------------------------------------|-------------------------------
`ep14ValgresultatPrOpstillingskreds.xlsx` | Opstillingskredskorrelationer
`ep14ValgresultatPrValgsted.xlsx`         | Valgstedskorrelationer
`valgresultatPersonlige.xlsx`             | Stemmer på politikere


[travis-badge-img]: https://travis-ci.org/ok-dk/epvalg2014.svg
[travis-badge-url]: https://travis-ci.org/ok-dk/epvalg2014
[license-badge-img]: http://img.shields.io/badge/License-MIT-blue.svg
[license-badge-url]: https://github.com/ok-dk/epvalg2014/blob/master/LICENSE.md
[epvalg]: https://github.com/ok-dk/epvalg2014/blob/master/epvalg.csv
[patent]: https://github.com/ok-dk/epvalg2014/blob/master/patentdomstol.csv
[epvalg-badge-img]: http://csvlint.io/validation/53863574637376031a430400.svg
[epvalg-badge-url]: http://csvlint.io/validation/53863574637376031a430400
[patent-badge-img]: http://csvlint.io/validation/5386357a637376031a440400.svg
[patent-badge-url]: http://csvlint.io/validation/5386357a637376031a440400
