ステートメント
SQLで言うなら「SELECT」や「INSERT」「DELETE」などで一つのクエリを構築しますが、この構築された文の全体をステートメントと言います。
ステートメントの種類（データ定義言語 / データ操作言語）

データ定義言語（DDL）
データベース構造の作成や変更、削除といった機能を担っています。
ALTER
照合順序
CREATE
DROP
DISABLE TRIGGER
ENABLE TRIGGER
RENAME
UPDATE STATISTICS

データ操作言語（DML）
データベースに格納されるデータを挿入、更新、変更、削除するためのもの
BULK INSERT
DELETE
INSERT
SELECT
UPDATE
MERGE
TRUNCATE TABLE

sqlインジェクション
Webアプリケーションに対し不正なSQL文を注入して不正に操作する攻撃手法

物理削除
SQLでDELETE文を発行してレコードを削除すること
原則として容易にデータの復活はできません（バックアップから復元することはできます）

論理削除
テーブルに削除フラグを用意し、TRUE/FALSEで削除をされたか管理する方法

スケールアップ
サーバーのCPUやメモリーなどハードウエアの増設によって処理能力を向上させること

スケールアウト
システムを構成するサーバーの台数を増やして処理能力を向上させること
何らかのトラブルでサーバーが故障しても別のサーバーでカバーできる
機器の数だけ構築作業や設計変更の手間が増え、保守する費用も台数分かかる

ロードバランサー
サーバーにかかる負荷分散を行うデバイス（機器）

トラフィック量
ネットワーク回線で送受信される通信データ量

ハードウェア
物理サーバやネットワーク機器（モニター、ハードディスク、プリンタ、 スキャナ、キーボード、マウス）

ソフトウェア
コンピュータやスマートフォン、その他電子機器に搭載されたプログラム

カーネル
オペレーティングシステム（OS）の基本機能の役割を担うソフトウェア

RDBMS（リレーショナルデータベース管理システム）
