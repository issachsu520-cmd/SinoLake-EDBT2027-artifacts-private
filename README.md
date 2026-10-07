# SinoLake: EDBT 2027 supplementary artifacts

Paper: [EA&B] SinoLake: Benchmarking Joinable and Unionable Table Discovery on a Real Chinese Socio-Economic Data Lake

Authors: Cong Xu, Xinwei Gao, and Jinglan Hu.

## Download

[Complete supplementary archive](https://github.com/issachsu520-cmd/SinoLake-EDBT2027-artifacts-private/releases/download/edbt2027-review-v1/SinoLake_EDBT2027_Supplement.zip) (203,391,133 bytes).

[Release page and SHA-256 checksum](https://github.com/issachsu520-cmd/SinoLake-EDBT2027-artifacts-private/releases/tag/edbt2027-review-v1).

The archive can be downloaded without signing in or requesting individual access permission. No viewer-identification or access-tracking code has been added to this repository by the authors.

The archive contains benchmark definitions, public registry snapshots, column labels, query sets, relevance grades, validation sheets, construction and evaluation code, all recorded retrieval rankings, and evaluation outputs. Read the README inside the ZIP and configure paths in `code/common.py` before executing code. Included rankings and relevance grades support re-evaluation of the recorded retrieval results without the original vendor tables or pretrained model weights.

Vendor-delivered raw tables are licensed and cannot be redistributed. File metadata and content hashes are provided. The separate 9.8 GB value store, column embeddings, and fine-tuned checkpoints are not included in this download. Full reconstruction of the lake or regeneration of rankings requires the corresponding additional inputs.

The complete ZIP passed CRC and manifest checks. Re-evaluation of two join methods over 547 queries and one union method over 510 queries matched the recorded per-query results. This check does not constitute complete reconstruction from raw data or a rerun of model training.

SHA-256: `179c4469faebd09492bb157f727aa25c63cad5c3aabe16b8e08127cc5557161f`
