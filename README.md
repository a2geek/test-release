# Experiment

This is an experimental alternative for simply hosting blobs as an HREF for BOSH development work.
There should be zero impact to running BOSH.

Key differences:

* `config/blobs.yml` has `href` entries for where the blobs were sourced.
* `config/finaly.yml` does not have a blobstore configured.
