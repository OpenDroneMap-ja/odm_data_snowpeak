#OpenDroneMapのサンプル・データ集


OpenDroneMapを用いるためのサンプル・データ集です。  
サンプル・データを用いる際に次の手順でクローンをしてください。  
※OpenDroneMapはインストール済みとします。  

##サンプル・データの利用手順
###①サンプル・データのClone
gitをインストールして、コマンドよりサンプル・データをダウンロード

`git clone https://github.com/OpenDroneMap-ja/{data_name}.git`

###②run.pyの実行
OpenDroneMapのrun.pyを実行すると画像処理がはじまります。

`./../../OpenDroneMap/run.py`

##サンプル・データ一覧
初心者の方は太字に示されているデータから扱うことをオススメします

リポジトリ名 | 画像数 | サイズ (MB) | Coordinates in EXIF: | GCPs in File:
------|:----------:|:-----------:|:----------------------:|:---------------:
odm_data_apt | 76 | 579 | ✕ | ✕
odm_data_benchmark | 25 | 106 | ◯ | ✕
**odm_data_caliterra** | 77 | 272 | ◯ | ✕
odm_data_langley | 200 | 706 | ✕ | ✕
odm_data_pacifica | 12 | 66.4 | ✕ | ✕
odm_data_seneca | 167 | 358 | ◯ | ✕
odm_data_keioSFC | 194 | 979.7 |  ◯ | ✕
odm_data_snowpeak | 140 | 767.3 |  ◯ | ✕

