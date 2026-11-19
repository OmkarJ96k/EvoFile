# EvoFile

EVOLUTION patch files by region/variant.

| Folder | Variant |
|---|---|
| `VIETNAM/` | VNG (from VAITNAM) |
| `GLOBAL/` | PUBG Global (`com.tencent.ig`) |
| `KORIAN/` | Korea (`com.pubg.krmobile`) |
| `TAIWAN/` | Taiwan (`com.rekoo.pubgm`) |
| `EVOLUTION-repo/` | BGMI (`com.pubg.imobile`) |
| `PUBG-FLASH/` | PUBG Mobile Flash (`com.tencent.igfit`) |
| `BGMI-AIR/` | BGMI Air (`com.krafton.bgmilite`) |

Each folder holds `config.json`, which Evolution reads to find the pak file,
download URL and target path. The pak file itself must be uploaded next to it.

`PUBG-FLASH/` and `BGMI-AIR/` currently contain only their config. Upload the
real Flash/Air pak files, or update `fileName` and `downloadURL` in those two
configs so they match the uploaded files.
