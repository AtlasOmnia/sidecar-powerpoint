# Sidecar for PowerPoint — sidebar site

Static sidebar for **Sidecar for PowerPoint** (Sidecar by Atlas Omnia), served at
https://atlasomnia.github.io/sidecar-powerpoint/ — the plugin's default `addin_base`.

Built unchanged from [AtlasOmnia/sidecar@`cae879e0cddead4717ba381bc759e91552c9ee39`](https://github.com/AtlasOmnia/sidecar/tree/cae879e0cddead4717ba381bc759e91552c9ee39/powerpoint) with:

```
cd powerpoint && npm ci && npm run build:static -- --base https://atlasomnia.github.io/sidecar-powerpoint/
```

Rebuild from that commit and compare against `SHA256SUMS`. Load `manifest.xml` into desktop PowerPoint.
Source, issues and license: https://github.com/AtlasOmnia/sidecar (Apache-2.0). Not affiliated with Microsoft or Nous Research.
