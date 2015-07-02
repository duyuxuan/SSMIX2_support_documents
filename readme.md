#本リポジトリの目的

独立行政法人国立病院機構(以下、「機構」という。)は、電子カルテシステムから標準化された形式(SS-MIX2形式)の診療情報を収集し、一元的に集約するデータベース(以下、「診療情報データベース」という。) を構築し、またその実施方法を手順書としてまとめる事業 (以下、「本事業」という。) を実施している。本事業においては「SS-MIX2 Ver.1.2c」に準拠したSS-MIX2出力モジュールを本事業に参加する各病院に導入することとしており、本ドキュメント群は、そのモジュールに搭載すべき機能について記載した技術仕様及び、提供するマスター類である。

##docフォルダ内の構成
* ascii_unit.md      asciiコードにおけるコード表記に関するドキュメント
* vital_sign_def.md  バイタル検査結果通知に関する定義
* cp932_JIS_convart.md  環境依存文字　変換テーブル
* convert_unit.md 単位変換
* convert_to_sn.md 定性結果・不等号の表現
* jlac10_units.md JLAC10ごとの単位
* sample_value.md 複合検査結果値の分離

##masterフォルダ内の構成
* sn.ptn 定性結果・不等号の変換用正規表現パターンファイル


##sampleフォルダ内の構成
* standard_root 標準化ストレージのルートディレクトリ

* extended_root 拡張ストレージのルートディレクトリ
    * 0123456789_20160101_L-OBSERVATIONS^OBSERVATIONS^99ZL01_000000020160101_201601011500321_1: 1日1ファイルのサンプル
    * 0123456789_20160101_L-OBSERVATIONS^OBSERVATIONS^99ZL01_000002016010115_201601011500321_1: 1日複数ファイルのサンプル