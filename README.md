# Beginner-friendly projects (Awesome KB)

An [OpenShelf](https://github.com/OpenNorms/openshelf) 1.7 knowledge base ingested from [MunGell/awesome-for-beginners](https://github.com/MunGell/awesome-for-beginners).

**[Browse the knowledge base](index.md)**

## Scope

Imports only top-level curated entries in the upstream README. Linked resources are not crawled or copied. Stubs preserve the source description and URL; status is `unknown`, and `last_checked` is omitted until verified.

## Reproduce

```sh
python3 tools/ingest.py --date 2026-11-04
python3 tools/check.py
openshelf lint .
```

The default input is the immutable capture in `raw/2026-11-04/`. To ingest a newer source checkout, preserve its README and license evidence as a new capture before updating `tools/config.json`. Existing UUIDs, creation dates, authored content/depth and verification fields survive re-ingestion.

## License and attribution

Imported list metadata follows the upstream collection's CC0-1.0 terms as documented in [THIRD_PARTY_NOTICES.md](THIRD_PARTY_NOTICES.md). The linked projects keep their own licenses. Upstream revision: [`f7bf7d43cb26d555e51a4c6c83af563a08795605`](https://github.com/MunGell/awesome-for-beginners/tree/f7bf7d43cb26d555e51a4c6c83af563a08795605).
