# Lazarus JSON Viewer

[![Build Status](https://github.com/gcarreno/laz-JSON-Viewer/workflows/build-test/badge.svg?branch=master)](https://github.com/gcarreno/laz-JSON-Viewer/actions)
[![License](https://img.shields.io/github/license/gcarreno/laz-JSON-Viewer)](https://github.com/gcarreno/laz-JSON-Viewer/blob/master/LICENSE)
[![Latest Release](https://img.shields.io/github/v/release/gcarreno/laz-JSON-Viewer?label=latest%20release)](https://github.com/gcarreno/laz-JSON-Viewer/releases)
![Downloads](https://img.shields.io/github/downloads/gcarreno/laz-JSON-Viewer/total)

Simple application to view a JSON file.

## Setup as default viewer

### Linux (Ubuntu)

The quick and dirty way I did it on my system was:

1. Create a file under `$HOME/.local/share/applications` named `jsonviewer.desktop` with the appropriate contents pointing to where you have uncompressed your binary.
2. Create and entry on `$HOME/.local/share/applications/defaults.list` that looks like:

```ini
[Default Applications]
application/json=jsonviewer.desktop
```

### Windows

At the moment I don't have an answer. Need to consult some Windows gurus.

## Screeshots
One file, none selected
![Picture1](images/lazJSONViewer-picture1.png)
One file, one selected, node selected
![Picture2](images/lazJSONViewer-picture2.png)
Many files, one selected, node selected
![Picture3](images/lazJSONViewer-picture3.png)
