��Unity+PHP+MariaDB�ŁA�n�C�X�R�A���f�[�^�x�[�X�Ɏ����������B
�������2���ԁB
������JSON�͎g���Ă��܂���B

���S�ł́A
https://www.edge-bp.com/test/test905.zip
�ɃA�b�v���Ă���܂��B

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

���͓�������swift�őg��ł݂悤�Ǝv���܂��B

��5���Ԃō�������[�O���C�N�ȃQ�[��
https://github.com/kenjikakera/TEST903unity2d


���ȑO�J������ARkit1.5�̉��Q�[�ł����A���Q�[�ɕt������ł����ݗp�c�[���̎��s�^(win7�ȍ~��-64bit)�̌��J�̋����𓾂܂����̂ł����������܂��B
https://www.edge-bp.com/test/qedit.zip


��web�y�[�W
https://www.ne.jp/asahi/kenji/pda/


