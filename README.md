# CalcDaytime
Calculate daytime lentgh all through the year.

## 説明

日の出🌅、日の入🌇、日中の長さ🌞などを計算して可視化するサンプルプログラムです。

本サンプルは [Google Colab](https://colab.research.google.com/) で開発しました。

サンプルアプリを [Mercury Cloud](https://cloud.runmercury.com/) で公開しています。

サンプルアプリのURLは次のとおりです。

https://daytime.runmercury.com/app/sample

![image](assets/SampleAppImage.jpg)

### 🗺位置

#### デフォルト

##### 横浜（神奈川）@国立天文台

https://daytime.runmercury.com/app/sample

#### カスタム位置

##### 🗾国内

| 地域     | リンク                                                                  |
| ------ | -------------------------------------------------------------------- |
| 東京     | <https://daytime.runmercury.com/app/sample?lat=35.6812&lon=139.7671> |
| 札幌     | <https://daytime.runmercury.com/app/sample?lat=43.0642&lon=141.3469> |
| 沖縄（那覇） | <https://daytime.runmercury.com/app/sample?lat=26.2124&lon=127.6809> |

##### 🌏海外

| 地域         | リンク                                                                   |
| ---------- | --------------------------------------------------------------------- |
| グリニッジ天文台   | <https://daytime.runmercury.com/app/sample?lat=51.4769&lon=-0.0005>   |
| ワシントンDC    | <https://daytime.runmercury.com/app/sample?lat=38.9072&lon=-77.0369>  |
| メルボルン      | <https://daytime.runmercury.com/app/sample?lat=-37.8136&lon=144.9631> |
| チクラーヨ（ペルー） | <https://daytime.runmercury.com/app/sample?lat=-6.7714&lon=-79.8411>  |

### ライブラリ

サンプルアプリでは、主に以下の Python ライブラリを使用しています。

* 天文計算ライブラリ： [PyEphem](https://rhodesmill.org/pyephem/)
* アプリ化ライブラリ： [Mercury](https://github.com/mljar/mercury)

### 構成ファイル

サンプルアプリを構成するファイル（※Mercury Cloudへアップロードするファイル）は以下のとおりです。

* パッケージ管理ファイル： [requirements.txt](requirements.txt)
* Jupyter Notebookファイル： [sample.ipynb](sample.ipynb)

### 補足

 本プログラムを [Google Colab](https://colab.research.google.com/) で実行する前に以下のコマンドを実行してモジュールをインストールしておく必要があります。

```
pip install mercury
```

```
pip install ephem
```


## 参照
* https://cloud.runmercury.com/
* https://runmercury.com/docs/
* https://docs.runmercury.com/app/checkbox
* https://rhodesmill.org/pyephem/
* https://github.com/mljar/mercury
* https://qiita.com/gmoriki/items/665426c88b0662403443
* https://qiita.com/DoroDango/items/269c74d091ef6b94b9ab
* https://eco.mtk.nao.ac.jp/koyomi/dni/dni15.html
* http://zakii.la.coocan.jp/physics/22_sunrise_circle.htm
