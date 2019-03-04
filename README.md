# GV100AD to JSON and SQL Example

This repository contains a simple php script for extracting data from the GV100AD formatted file. It only extracts some 
base data. If you wish to have a more complete extraction: Take it and extend it at your free will.

Read more about the data format or get fresh data source here: [Gemeindeverzeichnis-Informationssystem GV-ISys
](https://www.destatis.de/DE/ZahlenFakten/LaenderRegionen/Regionales/Gemeindeverzeichnis/Gemeindeverzeichnis.html)

## Usage
There must be the `GV100AD_300918.ASC` file in your working directory. Then execute
```bash
$ php extract-gv100ad.php
```
to generate the `ars.sql`, `ars.json` and `ars.min.json` files.
