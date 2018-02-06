Melo Melo Search
================
[![Travis Build Status](https://travis-ci.org/loveemu/melosearch.svg?branch=master)](https://travis-ci.org/loveemu/melosearch) [![AppVeyor Build Status](https://ci.appveyor.com/api/projects/status/gxwayd6df3jtqhgd/branch/master?svg=true)](https://ci.appveyor.com/project/loveemu/melosearch/branch/master)

指定されたメロディーに対応するバイト列を検索するための小さなユーティリティです。

注：検索エンジンはノートのキーのみを利用します。長さなど、他の要素は無視されます。

使い方
------

Syntax: `MeloSearch (options) [input file] "[MML]"`

注: `<` はオクターブを上げて、`>` はオクターブを下げます。

### オプション

--help
  : ヘルプを表示します

-q
  : 静かなモード、エラーとオフセットのみを出力します

-l[length]
  : ノート間の最大距離（バイト単位）（既定値: `-l6`）

-eq
  : ノートが等間隔に配置されていると仮定します（`-l` は最大距離ではなく、正確な距離を意味します）
