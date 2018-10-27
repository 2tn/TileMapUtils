# TileMapUtils
OpenStreetMapなど、XYZ形式で配信されているオンラインタイルマップをローカルで取り扱うためのプログラムです。XYZ形式については以下を参照してください。

https://en.wikipedia.org/wiki/Tiled_web_map
https://wiki.openstreetmap.org/wiki/Slippy_map_tilenames#Lon..2Flat._to_tile_numbers_2
http://smellman.hatenablog.com/entry/2015/12/26/054520
https://maps.gsi.go.jp/development/siyou.html

ここではタイルマップをダウンロードして、kmlやmbtilesやjpgといった形式のファイルにまとめることを想定して、必要なプログラムを公開しています。
mbtiles形式にて出力したい場合は、[MBUtil](https://github.com/mapbox/mbutil)を使用してください。

## Overview

### TileMapDownloader

  タイルマップをダウンロードするプログラムです。

### TileMapCombiner

  既にダウンロード済みのタイルマップを結合して、一枚の画像として出力するプログラムです。

### TileMap2KML

  既にダウンロード済みのタイルマップをGoogle Earthで表示するためのkmlファイルを作成するプログラムです。

## Install

各プログラムのREADME.mdを参照してください。

## Licence

GNU General Public License v3.0
