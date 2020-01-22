●Unity+PHP+MariaDBで、ハイスコアをデータベースに持たす実権。
制作日数2日間。
あえてJSONは使っていません。

完全版は、
https://www.edge-bp.com/test/test905.zip
にアップしてあります。

●mariaDBのuser名とpassはhttpdで設定しています。

vi /etc/sysconfig/httpd

一番最後に、

 例えば、mariaDBのrootユーザー名がdbrootでpassが1234abcdだとすると、

#mariaDB
 DBUSER=dbroot
 export DBUSER
 DBPASS=123abcd
 export DBPASS


●mariaDBには初期に以下の事をしています。
CREATE DATABASE test905;
USE test905;

CREATE TABLE test905.hiscore (
 id int AUTO_INCREMENT NOT NULL PRIMARY KEY,
 name varchar(32) NOT NULL,
 score int NOT NULL
 );

次は同じ物をswiftで組んでみようと思います。

●5日間で作ったローグライクなゲーム
https://github.com/kenjikakera/TEST903unity2d


●以前開発したARkit1.5の音ゲーですが、音ゲーに付随する打ち込み用ツールの実行型(win7以降の-64bit)の公開の許諾を得ましたのでこうかいします。
https://www.edge-bp.com/test/qedit.zip


●webページ
https://www.ne.jp/asahi/kenji/pda/


