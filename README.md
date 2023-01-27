# hesperomys
:warning: work in progress 

A prototype for integrating https://hesperomys.com into [Nomer](https://github.com/globalbioticinteractions/nomer).

For context, see:
 * https://github.com/globalbioticinteractions/nomer/issues/144 
 * https://github.com/JelleZijlstra/taxonomy/
 * https://github.com/JelleZijlstra/hesperomys/

Data files are stored with gzip compression for size. `taxa.csv.gz` contains all taxa in the Hesperomys database, `hesperomys.csv.gz` contains all names. To decompress, run `gzip -d taxa.csv.gz`.