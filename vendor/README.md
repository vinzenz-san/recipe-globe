# Vendored libraries

Served from here instead of jsDelivr: no third-party requests from the public page (see
`PUBLISH_PLAN.md`), and no foreign script under `/admin/globe/`, where it would run with the admin
session. Byte-identical to the upstream release (`-text` in `.gitattributes`, no line-ending
conversion).

| File | Source | Version | License | SHA-256 |
|---|---|---|---|---|
| `globe.gl.min.js` | npm `globe.gl`, `dist/globe.gl.min.js` | 2.46.2 | MIT (`globe.gl.LICENSE`) | `2c3e445c04d121215910a89688b96091c8a72071c122a4f830081a39b636c94c` |
| `ne_50m_admin_0_countries.geojson` | `nvkelso/natural-earth-vector`, `geojson/` | v5.1.2 | public domain | `3e458fc036ad0a66411f2c1e6cac49c5d7bfb81cb1123bc513b22511a2b7fdeb` |

Update: download the new version, compare it with the npm tarball (`npm pack globe.gl@<v>`) or
the GitHub tag, then change the file and this table together.
