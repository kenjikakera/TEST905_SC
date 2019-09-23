●Unity+PHP+MariaDBで、ハイスコアをデータベースに持たす実権。
制作日数2日間。
あえてJSONは使っていません。


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


●5日間で作ったローグライクなゲーム
https://github.com/kenjikakera/TEST903-unity2d

●webページ
https://www.ne.jp/asahi/kenji/pda/


