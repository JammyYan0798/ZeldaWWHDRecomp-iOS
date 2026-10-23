# ZeldaWWHDRecomp iOS/iPadOS source-only snapshot

This repository provides the audited source-only package as a ZIP archive. Extract `ZeldaWWHDRecomp-source-only.zip`; the project tree is under `source-candidate/`. The adjacent SHA-256 manifest covers the 1,431 files inside that directory.

To verify the extracted files, run this from the directory containing the extracted `source-candidate/` folder and the manifest:

```sh
cd source-candidate && shasum -a 256 -c ../ZeldaWWHDRecomp-source-files.sha256
```

Archive SHA-256: `e882918eda8a7557dcbe4ac09e4a847d13c37d9f904360512162da779171a027`

The package contains source and documentation only; game files, keys, saves, signing materials, generated game data, and personal records are excluded. See the included project files for licensing and third-party notices.
