# Kalyan-Deva/scoop-bucket

A [Scoop](https://scoop.sh) bucket for [pqdoctor](https://pqdoctor.com): why isn't this server post-quantum?

```powershell
scoop bucket add kalyan-deva https://github.com/Kalyan-Deva/scoop-bucket
scoop install pqdoctor
pqdoctor --version
```

The manifest installs the Windows release binary from [pqdoctor.com/downloads](https://pqdoctor.com/get-started/downloads/), checked against its SHA-256. MIT licensed.
