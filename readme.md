# Documentation of "(Album and single) releases to Spotify (2015/10/30 - 2018/6/26)"

This is a repository which hosts the source code to prepare the public version of the data set:

Datta, Hannes, 2020, "(Album and single) releases to Spotify", https://doi.org/10.34894/DX857S, DataverseNL.

If you are a (potential) user of the data, please directly access its documentation using the link above.

<!-- remove if necessary-->
__Note:__ The data set is *not* released to the public yet (expected end of 2020). For questions, please mail h.datta@tilburguniversity.edu. The documentation of the data
can already be accessed in `doc\readme-data.txt`.
<!-- -->

## Maintaining (new) releases of the data

Use this repository to *maintain* the dataset.

* Obtain a valid API key from Dataverse ("API Token" in the main menu)
* Download the most recent version of the Dataverse uploading tool (run `bash init.sh` on Mac, or paste the link contained in the file in your browser on Windows)
* Archiving confidential raw data: `push_raw.sh` pushes the raw data to Dataverse (done once, `bash push_raw.sh`; or paste code into your command prompt on Windows)
* Releasing public versions of the data: `release.sh` pushes (updates) to the documentation in `\doc`, or the prepared data set in `\release`.

Note: API keys used in the `.sh` scripts is deprecated.
