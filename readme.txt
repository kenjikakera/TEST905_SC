��Unity+PHP+MariaDB�ŁA�n�C�X�R�A���f�[�^�x�[�X�Ɏ����������B
�������2���ԁB
������JSON�͎g���Ă��܂���B


��mariaDB��user����pass��httpd�Őݒ肵�Ă��܂��B

vi /etc/sysconfig/httpd

��ԍŌ�ɁA

 �Ⴆ�΁AmariaDB��root���[�U�[����dbroot��pass��1234abcd���Ƃ���ƁA

#mariaDB
 DBUSER=dbroot
 export DBUSER
 DBPASS=123abcd
 export DBPASS


��mariaDB�ɂ͏����Ɉȉ��̎������Ă��܂��B
CREATE DATABASE test905;
USE test905;

CREATE TABLE test905.hiscore (
 id int AUTO_INCREMENT NOT NULL PRIMARY KEY,
 name varchar(32) NOT NULL,
 score int NOT NULL
 );


��5���Ԃō�������[�O���C�N�ȃQ�[��
https://github.com/kenjikakera/TEST903-unity2d

��web�y�[�W
https://www.ne.jp/asahi/kenji/pda/


