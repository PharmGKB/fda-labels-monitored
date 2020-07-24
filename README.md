# FDA Labels Monitored

This repo stores snapshots of FDA structured label data that comes from the [OpenFDA API](https://open.fda.gov/). The labels included here are the labels that have been annotated by [PharmGKB](https://www.pharmgkb.org/).

Each JSON file represents an FDA drug label. The label contents were retrieved at the time of the commit. Metadata is included in the JSON file itself that describes the source of the data.

The `labels_with_no_reponse.tsv` file lists all the PharmGKB-annotated labels that are not available through the OpenFDA system and, thus, have no file available for them.

## Dev Note

This is run with the `cl.FdaLabelDownloader` class in the main repo. Use the `-d` arg to point at your clone of this direcotry to update.
