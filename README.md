# OULU-NPU

[![License: CC BY 4.0](https://img.shields.io/badge/License-CC%20BY%204.0-green?logo=creativecommons&logoColor=white)](https://creativecommons.org/licenses/by/4.0/)
[![GitHub](https://img.shields.io/badge/GitHub-biometric--community%2FOULU--NPU-181717?logo=github)](https://github.com/biometric-community/OULU-NPU)
[![Access: register](https://img.shields.io/badge/access-register-important.svg)](https://site.oulu.fi/csv/)

**OULU-NPU** — tbiom catalog packaging for `oulu-npu` (face-pad; access `register`). Docs/helpers only; obtain data via upstream registration.

- **Dataset repository**: https://github.com/biometric-community/OULU-NPU
- **Upstream source**: https://site.oulu.fi/csv/
- **License (helpers / docs)**: CC BY 4.0 (see [`LICENSE`](LICENSE))
- **License (data)**: upstream terms — this packaging does **not** relicense or redistribute gated data

| Field | Value |
|-------|-------|
| Catalog id (tbiom) | `oulu-npu` |
| Category | `face-pad` |
| Access | `register` |
| Upstream homepage | https://site.oulu.fi/csv/ |

## TL;DR

- **Access**: **register** — obtain data from the upstream homepage / license process
- **This mirror**: documentation + download helpers only (no bulk payload in git)
- **Notes**: OULU-NPU face PAD; request from University of Oulu.

## Download

### Clone this repository

```bash
git clone git@github.com:biometric-community/OULU-NPU.git
cd OULU-NPU
```

### tbiom monorepo helper

```bash
bash projects/datasets/scripts/download_oulu_npu.sh
```

Place licensed archives under `projects/datasets/oulu-npu/` (gitignored).

## Dataset structure

```text
OULU-NPU/
├── README.md
├── LICENSE
├── .gitignore
└── extracted/   # local only after you obtain upstream data
```

## License

Helpers/docs: CC BY 4.0. Dataset files: upstream license / registration agreement.

## Contact

- Upstream: https://site.oulu.fi/csv/
- Packaging: https://github.com/biometric-community/OULU-NPU/issues
