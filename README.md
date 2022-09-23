# genomics_packages
List of useful genomics R packages

## restez

https://github.com/ropensci/restez

Maintainer: [@joelnitta](https://github.com/joelnitta)

Downloading sequences and sequence information from GenBank and related NCBI taxonomic databases is often performed via the NCBI API, Entrez. Entrez, however, has a limit on the number of requests and downloading large amounts of sequence data in this way can be inefficient. For programmatic situations where multiple Entrez calls are made, downloading may take days, weeks or even months.

This package aims to make sequence retrieval more efficient by allowing a user to download large sections of the GenBank database to their local machine and query this local database either through package specific functions or Entrez wrappers. This process is more efficient as GenBank downloads are made via NCBI’s FTP using compressed sequence files. With a good internet connection and a middle-of-the-road computer, a database comprising 20 GB of sequence information can be generated in less than 10 minutes.

## gbfetch

https://github.com/joelnitta/gbfetch

Maintainer: [@joelnitta](https://github.com/joelnitta)

`gbfetch` makes it easy to download DNA sequences from GenBank directly into R.

You can provide a query string exactly as you would for a GenBank search, and it will return the corresponding sequences or metadata in a tidy format.

