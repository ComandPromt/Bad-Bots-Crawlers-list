# Bad-Bots

## List of the most dangerous bots that should be blocked when doing statistics of your web

CREATE TABLE `bots`(
	`id`int(11)AUTO_INCREMENT PRIMARY KEY,
	`IP`varchar(64)NOT NULL UNIQUE
)DEFAULT CHARSET=utf8;

INSERT INTO bots VALUES ('1','46.229.168.129'),('2','46.229.168.130'),('3','46.229.168.131'),('4','46.229.168.132'),('5','46.229.168.133'),('6','46.229.168.134'),('7','46.229.168.135'),('8','46.229.168.136'),('9','46.229.168.137'),('10','46.229.168.138'),('11','46.229.168.139'),('12','46.229.168.140'),('13','46.229.168.141'),('14','46.229.168.142'),('15','46.229.168.143'),('16','46.229.168.144'),('17','46.229.168.145'),('18','46.229.168.146'),('19','46.229.168.147'),('20','46.229.168.148'),('21','46.229.168.149'),('22','46.229.168.150'),('23','46.229.168.151'),('24','46.229.168.152'),('25','46.229.168.153'),('26','46.229.168.154'),('27','46.229.168.161'),('28','46.229.168.162'),('29','46.229.168.163'),('30','54.36.148.21'),('31','216.244.66.237'),('32','66.249.69.222'),('33','66.249.69.218'),('34','103.131.71.156'),('35','103.131.71.149'),('36','54.36.148.248'),('37','54.36.150.129'),('38','54.36.148.181'),('39','54.36.150.107'),('40','54.36.150.179'),('41','54.36.148.87'),('42','54.36.150.96'),('43','54.36.148.170'),('44','54.36.148.144'),('45','54.36.148.12'),('46','54.36.148.91'),('47','54.36.148.210'),('48','54.36.150.159'),('49','54.36.150.180'),('50','54.36.150.27'),('51','207.46.13.194'),('52','157.55.39.129'),('53','40.77.167.212'),('54','207.46.13.177'),('55','207.46.13.192'),('56','207.46.13.173'),('57','157.55.39.95'),('58','157.55.39.248'),('59','207.46.13.20'),('60','157.55.39.145'),('61','207.46.13.74'),('62','207.46.13.219'),('63','157.55.39.242'),('64','40.77.167.73'),('65','157.55.39.240'),('66','157.55.39.185'),('67','207.46.13.56'),('68','207.46.13.105'),('69','207.46.13.117'),('70','207.46.13.135'),('71','40.77.167.129'),('72','157.55.39.29'),('73','40.77.167.96'),('74','40.77.167.21'),('75','157.55.39.110'),('76','40.77.167.139'),('77','40.77.167.38'),('78','157.55.39.114'),('79','157.55.39.224'),('80','40.77.167.172'),('81','40.77.167.20'),('82','40.77.167.169'),('83','207.46.13.53'),('84','40.77.167.94'),('85','157.55.39.191'),('86','207.46.13.130'),('87','207.46.13.157'),('88','207.46.13.182'),('89','207.46.13.144'),('90','157.55.39.68'),('91','207.46.13.166'),('92','207.46.13.71'),('93','157.55.39.231'),('94','40.77.167.47'),('95','40.77.167.41'),('96','207.46.13.184'),('97','40.77.167.137'),('98','207.46.13.32'),('99','40.77.167.123'),('100','207.46.13.28'),('101','207.46.13.218'),('102','40.77.167.28'),('103','157.55.39.159'),('104','157.55.39.193'),('105','207.46.13.204'),('106','40.77.167.210'),('107','207.46.13.69'),('108','207.46.13.171'),('109','40.77.167.120'),('110','40.77.167.22'),('111','207.46.13.196'),('112','157.55.39.228'),('113','207.46.13.36'),('114','207.46.13.139'),('115','207.46.13.154'),('116','207.46.13.183'),('117','207.46.13.68'),('118','40.77.167.161'),('119','157.55.39.138'),('120','40.77.167.150'),('121','40.77.167.108'),('122','40.77.167.119'),('123','207.46.13.203'),('124','157.55.39.157'),('125','40.77.167.144'),('126','40.77.167.130'),('127','157.55.39.51'),('128','40.77.167.118'),('129','40.77.167.100'),('130','157.55.39.136'),('131','157.55.39.97'),('132','157.55.39.132'),('133','40.77.167.43'),('134','40.77.167.39'),('135','157.55.39.93'),('136','40.77.167.117'),('137','40.77.167.70'),('138','40.77.167.142'),('139','40.77.167.49 '),('140','40.77.167.136'),('141','157.55.39.148'),('142','157.55.39.250'),('143','157.55.39.124'),('144','157.55.39.174'),('145','40.77.167.51'),('146','207.46.13.206'),('147','40.77.167.93'),('148','157.55.39.178'),('149','207.46.13.96'),('150','157.55.39.173'),('151','207.46.13.45'),('152','40.77.167.48'),('153','40.77.167.71'),('154','157.55.39.48'),('155','207.46.13.229'),('156','207.46.13.205'),('157','207.46.13.140'),('158','207.46.13.18'),('159','40.77.167.180'),('160','40.77.167.207'),('161','157.55.39.112'),('162','157.55.39.106'),('163','157.55.39.254'),('164','157.55.39.194'),('165','40.77.167.179'),('166','157.55.39.120'),('167','157.55.39.153'),('168','207.46.13.30'),('169','40.77.167.160'),('170','40.77.167.68'),('171','207.46.13.210'),('172','157.55.39.246'),('173','157.55.39.115'),('174','157.55.39.125'),('175','40.77.167.31'),('176','207.46.13.250'),('177','40.77.167.196'),('178','207.46.13.241'),('179','207.46.13.158'),('180','40.77.167.106'),('181','40.77.167.208'),('182','40.77.167.97'),('183','40.77.167.215'),('184','157.55.39.225'),('185','40.77.167.76'),('186','207.46.13.50'),('187','40.77.167.116'),('188','40.77.167.163'),('189','207.46.13.122'),('190','207.46.13.181'),('191','40.77.167.190'),('192','40.77.167.113'),('193','157.55.39.89'),('194','40.77.167.151'),('195','40.77.167.17'),('196','157.55.39.87'),('197','207.46.13.84'),('198','207.46.13.70'),('199','157.55.39.133'),('200','40.77.167.102'),('201','157.55.39.176'),('202','40.77.167.157'),('203','144.76.120.197'),('204','144.76.71.176'),('205','136.243.137.163'),('206','199.58.86.211'),('207','95.216.20.84'),('208','78.46.176.21'),('209','144.76.40.222'),('210','173.234.159.250'),('211','148.251.69.139'),('212','144.76.29.84'),('213','148.251.120.201'),('214','69.30.226.234'),('215','80.241.209.28'),('216','148.251.70.179'),('217','69.30.221.250'),('218','136.243.37.219'),('219','144.76.115.163'),('220','95.216.227.92'),('221','144.76.38.10'),('222','148.251.131.16'),('223','176.9.25.107'),('224','92.220.0.232'),('225','148.251.244.137'),('226','148.251.41.239'),('227','213.136.92.122'),('228','144.76.186.38'),('229','95.216.5.212'),('230','95.216.11.179'),('231','192.151.157.210'),('232','148.251.125.12'),('233','173.208.157.186'),('234','176.9.140.208'),('235','82.193.102.149'),('236','95.216.11.34'),('237','148.251.92.39'),('238','95.216.16.51'),('239','144.76.91.79'),('240','95.216.11.233'),('241','78.46.63.108'),('242','24.89.192.155'),('243','207.180.203.210'),('244','78.46.99.254'),('245','144.76.162.242'),('246','85.10.206.20'),('247','144.76.29.149'),('248','144.76.99.215'),('249','144.76.186.217'),('250','78.46.149.254'),('251','54.36.150.168'),('252','54.36.150.163'),('253','54.36.149.28'),('254','54.36.150.14'),('255','54.36.148.180'),('256','54.36.149.27'),('257','54.36.150.94'),('258','54.36.150.140'),('259','54.36.150.133'),('260','54.36.148.123'),('261','54.36.148.247'),('262','54.36.148.155'),('263','54.36.150.109'),('264','54.36.148.67'),('265','54.36.150.128'),('266','54.36.150.136'),('267','54.36.149.84'),('268','54.36.150.141'),('269','54.36.148.142'),('270','54.36.150.79'),('271','54.36.148.187'),('272','54.36.148.40'),('273','54.36.150.58'),('274','54.36.150.172'),('275','54.36.150.151'),('276','54.36.150.181'),('277','54.36.150.36'),('278','54.36.150.84'),('279','54.36.148.18'),('280','54.36.150.24'),('281','54.36.148.131'),('282','54.36.149.100'),('283','54.36.150.106'),('284','54.36.150.34'),('285','54.36.150.20'),('286','54.36.150.43'),('287','54.36.149.74'),('288','54.36.148.136'),('289','54.36.148.236'),('290','54.36.150.64'),('291','54.36.148.105'),('292','54.36.150.47'),('293','54.36.150.97'),('294','54.36.148.55'),('295','54.36.150.148'),('296','54.36.150.42'),('297','54.36.150.55'),('298','54.36.149.90'),('299','54.36.150.10'),('300','54.36.149.51'),('301','54.36.148.53'),('302','54.36.150.76'),('303','54.36.150.38'),('304','54.36.150.91'),('305','54.36.148.220'),('306','54.36.148.132'),('307','54.36.150.82'),('308','54.36.148.97'),('309','54.36.150.62'),('310','54.36.148.159'),('311','54.36.150.30'),('312','54.36.150.189'),('313','40.77.167.222'),('314','54.36.148.174'),('315','54.36.150.164'),('316','54.36.150.33'),('317','54.36.148.246'),('318','54.36.148.178'),('319','54.36.150.117'),('320','54.36.149.68'),('321','54.36.149.13'),('322','54.36.150.95'),('323','54.36.149.41'),('324','54.36.148.175'),('325','54.36.150.13'),('326','54.36.150.156'),('327','54.36.150.160'),('328','54.36.148.198'),('329','54.36.148.39'),('330','54.36.148.92'),('331','54.36.150.83'),('332','54.36.148.252'),('333','54.36.149.62'),('334','54.36.150.123'),('335','54.36.149.19'),('336','54.36.149.106'),('337','54.36.150.170'),('338','54.36.148.203'),('339','54.36.148.30'),('340','54.36.150.153'),('341','54.36.148.253'),('342','54.36.150.132'),('343','54.36.148.177'),('344','54.36.150.86'),('345','54.36.148.125'),('346','54.36.150.124'),('347','54.36.148.122'),('348','54.36.148.59'),('349','54.36.149.23'),('350','54.36.150.119'),('351','54.36.150.171'),('352','54.36.150.147'),('353','54.36.148.110'),('354','54.36.149.11'),('355','54.36.150.21'),('356','54.36.150.60'),('357','54.36.148.27'),('358','54.36.150.88'),('359','54.36.150.99'),('360','54.36.150.183'),('361','54.36.150.177'),('362','54.36.148.13'),('363','54.36.150.77'),('364','54.36.148.57'),('365','54.36.148.70'),('366','54.36.150.71'),('367','54.36.150.185'),('368','54.36.150.188'),('369','54.36.148.169'),('370','54.36.148.65'),('371','54.36.149.45'),('372','54.36.148.216'),('373','54.36.148.84'),('374','54.36.150.186'),('375','54.36.150.32'),('376','151.80.39.16'),('377','54.36.149.92'),('378','54.36.149.37'),('379','54.36.148.148'),('380','54.36.150.73'),('381','54.36.148.56'),('382','54.36.150.165'),('383','54.36.150.66'),('384','54.36.150.52'),('385','54.36.148.75'),('386','54.36.150.175'),('387','54.36.150.145'),('388','54.36.150.152'),('389','54.36.150.78'),('390','54.36.149.97'),('391','54.36.148.79'),('392','54.36.150.50'),('393','54.36.150.104'),('394','54.36.148.223'),('395','54.36.148.19'),('396','54.36.150.67'),('397','54.36.150.161'),('398','54.36.148.190'),('399','54.36.148.199'),('400','54.36.148.161'),('401','54.36.150.72'),('402','54.36.149.101'),('403','54.36.150.187'),('404','54.36.148.11'),('405','54.36.148.229'),('406','54.36.150.81'),('407','54.36.148.74'),('408','54.36.149.78'),('409','54.36.148.235'),('410','54.36.149.87'),('411','54.36.149.14'),('412','54.36.148.183'),('413','54.36.150.90'),('414','54.36.150.74'),('415','54.36.150.131'),('416','54.36.150.70'),('417','54.36.148.241'),('418','54.36.150.51'),('419','54.36.150.45'),('420','54.36.148.46'),('421','54.36.150.41'),('422','54.36.148.43'),('423','54.36.148.80'),('424','54.36.150.127'),('425','54.36.150.68'),('426','54.36.148.204'),('427','54.36.150.85'),('428','54.36.150.46'),('429','54.36.150.101'),('430','54.36.149.91'),('431','54.36.150.26'),('432','54.36.150.184'),('433','54.36.150.19'),('434','54.36.148.81'),('435','54.36.150.116'),('436','54.36.148.188'),('437','54.36.150.108'),('438','54.36.150.11'),('439','54.36.148.179'),('440','54.36.148.135'),('441','54.36.148.231'),('442','54.36.150.142'),('443','54.36.148.106'),('444','51.255.65.46'),('445','54.36.148.134'),('446','54.36.150.182'),('447','54.36.148.115'),('448','54.36.150.49'),('449','54.36.148.10'),('450','54.36.150.75'),('451','54.36.150.100'),('452','54.36.148.116'),('453','54.36.150.57'),('454','54.36.148.163'),('455','54.36.149.31'),('456','54.36.150.130'),('457','54.36.148.230'),('458','54.36.148.140'),('459','54.36.148.33'),('460','54.36.150.139'),('461','54.36.150.102'),('462','54.36.148.157'),('463','54.36.148.64'),('464','54.36.150.87'),('465','54.36.148.218'),('466','54.36.150.191'),('467','54.36.150.113'),('468','54.36.150.111'),('469','54.36.148.242'),('470','54.36.149.80'),('471','54.36.149.86'),('472','54.36.148.50'),('473','54.36.150.63'),('474','54.36.148.121'),('475','54.36.148.32'),('476','54.36.150.118'),('477','54.36.150.110'),('478','54.36.149.42'),('479','54.36.149.35'),('480','54.36.150.69'),('481','54.36.148.243'),('482','54.36.150.176'),('483','54.36.148.165'),('484','54.36.150.17'),('485','54.36.148.85'),('486','54.36.148.222'),('487','54.36.148.160'),('488','54.36.148.83'),('489','54.36.149.107'),('490','54.36.150.149'),('491','54.36.148.89'),('492','54.36.150.167'),('493','54.36.150.155'),('494','54.36.150.126'),('495','54.36.148.29'),('496','54.36.148.186'),('497','54.36.150.144'),('498','54.36.150.61'),('499','54.36.150.31'),('500','54.36.148.237'),('501','54.36.150.89'),('502','54.36.150.12'),('503','54.36.149.69'),('504','54.36.148.95'),('505','54.36.148.98'),('506','54.36.148.228'),('507','54.36.148.150'),('508','54.36.148.191'),('509','54.36.150.16'),('510','54.36.148.184'),('511','54.36.148.205'),('512','54.36.148.129'),('513','54.36.148.133'),('514','54.36.150.138'),('515','54.36.150.150'),('516','54.36.149.59'),('517','54.36.148.54'),('518','54.36.150.158'),('519','54.36.149.66'),('520','54.36.149.10'),('521','54.36.150.65'),('522','54.36.148.151'),('523','54.36.150.154'),('524','54.36.148.197'),('525','54.36.150.120'),('526','54.36.149.22'),('527','54.36.150.54'),('528','54.36.150.48'),('529','54.36.148.17'),('530','54.36.150.15'),('531','54.36.149.15'),('532','54.36.148.62'),('533','54.36.150.174'),('534','54.36.148.215'),('535','54.36.149.77'),('536','54.36.149.39'),('537','54.36.149.53'),('538','54.36.148.240'),('539','54.36.149.36'),('540','54.36.150.166'),('541','54.36.150.105'),('542','54.36.148.158'),('543','54.36.148.255'),('544','54.36.148.113'),('545','54.36.148.127'),('546','54.36.148.108'),('547','54.36.148.37'),('548','54.36.149.32'),('549','54.36.148.239'),('550','54.36.150.92'),('551','54.36.148.227'),('552','54.36.149.70'),('553','54.36.148.68'),('554','54.36.149.54'),('555','54.36.148.88'),('556','54.36.149.30'),('557','54.36.148.211'),('558','54.36.148.254'),('559','54.36.149.57'),('560','54.36.148.119'),('561','54.36.148.166'),('562','54.36.148.143'),('563','54.36.148.244'),('564','54.36.150.125'),('565','54.36.150.135'),('566','54.36.149.25'),('567','54.36.148.34'),('568','54.36.148.28'),('569','54.36.148.173'),('570','54.36.148.16'),('571','54.36.149.47'),('572','54.36.148.35'),('573','54.36.150.134'),('574','54.36.149.40'),('575','54.36.150.22'),('576','54.36.150.18'),('577','54.36.150.98'),('578','54.36.148.234'),('579','54.36.149.99'),('580','54.36.148.77'),('581','54.36.148.147'),('582','54.36.149.61'),('583','54.36.148.225'),('584','54.36.149.43'),('585','54.36.148.103'),('586','54.36.148.138'),('587','54.36.148.226'),('588','54.36.148.49'),('589','54.36.149.79'),('590','54.36.148.128'),('591','54.36.149.72'),('592','54.36.150.56'),('593','54.36.149.46'),('594','54.36.150.29'),('595','157.55.39.76'),('596','157.55.39.233'),('597','40.77.167.35'),('598','40.77.167.86'),('599','40.77.167.10'),('600','157.55.39.168'),('601','207.46.13.33'),('602','40.77.167.79'),('603','54.36.149.18'),('604','66.249.69.151'),('605','66.249.69.220'),('606','148.251.22.75'),('607','66.249.69.153'),('608','66.249.69.152'),('609','54.36.148.20'),('610','54.36.148.96'),('611','54.36.150.122'),('612','54.36.150.190'),('613','54.36.149.50'),('614','54.36.148.233'),('615','54.36.148.76'),('616','54.36.150.93'),('617','54.36.150.112'),('618','54.36.150.25'),('619','54.36.148.114'),('620','54.36.150.23'),('621','54.36.148.38'),('622','54.36.149.85'),('623','54.36.149.75'),('624','54.36.148.213'),('625','54.36.149.88'),('626','54.36.148.164'),('627','54.36.150.173'),('628','54.36.148.22'),('629','54.36.148.208'),('630','54.36.148.162'),('631','54.36.150.35'),('632','54.36.148.93'),('633','54.36.149.104'),('634','54.36.148.51'),('635','54.36.148.167'),('636','54.36.150.39'),('637','54.36.148.15'),('638','54.36.150.53'),('639','54.36.148.60'),('640','54.36.150.137'),('641','54.36.148.52'),('642','54.36.148.61'),('643','54.36.149.24'),('644','54.36.149.60'),('645','54.36.148.14'),('646','54.36.148.137'),('647','54.36.148.42'),('648','54.36.148.153'),('649','54.36.148.126'),('650','54.36.148.112'),('651','54.36.149.71'),('652','54.36.148.172'),('653','54.36.150.162'),('654','54.36.150.59'),('655','40.77.167.132'),('656','207.46.13.52'),('657','207.46.13.159'),('658','66.249.75.23'),('659','66.249.75.24'),('660','54.36.149.105'),('661','54.36.148.104'),('662','54.36.149.29'),('663','54.36.150.103'),('664','54.36.148.124'),('665','54.36.148.221'),('666','54.36.148.72'),('667','54.36.148.217'),('668','54.36.149.89'),('669','54.36.148.118'),('670','54.36.149.82'),('671','54.36.148.250'),('672','54.36.148.209'),('673','54.36.149.67'),('674','54.36.150.28'),('675','54.36.148.101'),('676','54.36.148.25'),('677','54.36.148.139'),('678','54.36.150.114'),('679','54.36.148.154'),('680','54.36.148.193'),('681','54.36.148.176'),('682','54.36.148.48'),('683','54.36.148.249'),('684','54.36.148.36'),('685','54.36.148.152'),('686','54.36.149.64'),('687','54.36.148.149'),('688','54.36.148.145'),('689','54.36.150.121'),('690','54.36.149.17'),('691','54.36.148.195'),('692','54.36.148.130'),('693','54.36.148.66'),('694','54.36.148.224'),('695','54.36.149.73'),('696','54.36.148.107'),('697','54.36.149.44'),('698','54.36.148.146'),('699','54.36.148.78'),('700','54.36.148.82'),('701','54.36.150.80'),('702','54.36.150.44'),('703','54.36.148.141'),('704','54.36.150.37'),('705','54.36.148.71'),('706','54.36.149.33'),('707','54.36.149.95'),('708','54.36.148.23'),('709','54.36.149.49'),('710','54.36.148.212'),('711','54.36.150.40'),('712','54.36.150.178'),('713','54.36.148.232'),('714','54.36.149.98'),('715','54.36.149.21'),('716','54.36.148.219'),('717','54.36.148.111'),('718','54.36.149.83'),('719','54.36.148.214'),('720','54.36.148.207'),('721','54.36.148.245'),('722','54.36.148.99'),('723','54.36.148.194'),('724','54.36.148.100'),('725','54.36.149.26'),('726','54.36.149.65'),('727','54.36.149.34'),('728','54.36.149.55'),('729','54.36.149.16'),('730','54.36.150.115'),('731','54.36.148.26'),('732','54.36.149.48'),('733','54.36.149.76'),('734','54.36.148.202'),('735','54.36.149.81'),('736','54.36.149.20'),('737','54.36.150.157'),('738','54.36.148.69'),('739','54.36.148.189'),('740','54.36.148.196'),('741','54.36.149.94'),('742','54.36.148.185'),('743','54.36.148.192'),('744','54.36.148.31'),('745','54.36.149.93'),('746','54.36.148.109'),('747','54.36.148.120'),('748','54.36.148.24'),('749','54.36.148.94'),('750','54.36.148.206'),('751','54.36.149.52'),('752','54.36.148.171'),('753','54.36.148.251'),('754','54.36.149.58'),('755','54.36.149.96'),('756','54.36.149.103'),('757','54.36.148.90'),('758','54.36.148.63'),('759','54.36.150.143'),('760','54.36.148.47'),('761','54.36.148.102'),('762','54.36.149.38'),('763','66.249.75.25'),('764','207.46.13.180'),('765','40.77.167.156'),('766','40.77.167.74'),('767','207.46.13.109'),('768','157.55.39.209'),('769','40.77.167.87'),('770','207.46.13.129'),('771','207.46.13.77'),('772','207.46.13.138'),('773','40.77.167.128'),('774','40.77.167.40'),('775','157.55.39.201'),('776','40.77.167.177'),('777','207.46.13.46'),('778','207.46.13.44'),('779','207.46.13.42'),('780','52.162.161.148'),('781','95.108.181.75'),('782','157.55.39.169'),('783','207.46.13.62'),('784','136.243.70.151'),('785','207.46.13.94'),('786','157.55.39.221'),('787','207.46.13.155'),('788','207.46.13.116'),('789','40.77.167.101'),('790','40.77.167.98'),('791','54.36.148.182'),('792','54.36.149.56'),('793','157.55.39.249'),('794','157.55.39.175'),('795','54.36.148.58'),('796','54.36.149.12'),('797','54.36.148.156'),('798','157.55.39.63'),('799','54.36.148.238'),('800','54.36.148.41'),('801','157.55.39.218'),('802','54.36.149.63'),('803','54.36.148.168'),('804','54.36.150.146'),('805','54.36.148.117'),('806','54.36.148.86'),('807','54.36.148.201'),('808','54.36.148.73'),('809','141.8.142.48'),('810','157.55.39.252'),('811','157.55.39.230'),('812','54.36.148.200'),('813','157.55.39.142'),('814','54.36.149.102'),('815','148.251.49.107'),('816','40.77.167.170'),('817','207.46.13.76'),('818','40.77.167.135'),('819','207.46.13.169'),('820','40.77.167.198'),('821','141.8.142.212'),('822','40.77.167.173'),('823','207.46.13.127'),('824','207.46.13.147'),('825','40.77.167.134'),('826','157.55.39.253'),('827','40.77.167.63'),('828','40.77.167.174'),('829','207.46.13.225'),('830','66.249.73.24'),('831','40.77.167.92'),('832','204.12.226.26'),('833','157.55.39.143'),('834','157.55.39.164'),('835','157.55.39.140'),('836','66.249.69.74'),('837','78.46.61.245'),('838','157.55.39.90'),('839','157.55.39.195'),('840','207.46.13.83'),('841','66.249.69.72'),('842','66.249.69.76'),('843','207.46.13.37'),('844','157.55.39.237'),('845','40.77.167.124'),('846','157.55.39.55'),('847','40.77.167.149'),('848','207.46.13.220'),('849','40.77.167.153'),('850','66.249.75.20'),('851','66.249.75.21'),('852','66.249.75.22'),('853','40.77.167.84'),('854','40.77.167.46'),('855','66.249.64.154'),('856','66.249.64.156'),('857','66.249.64.158'),('858','157.55.39.103'),('859','66.249.64.138'),('860','66.249.64.140'),('861','66.249.64.136'),('862','40.77.167.105'),('863','157.55.39.74'),('864','207.46.13.10'),('865','157.55.39.38'),('866','95.216.21.107'),('867','157.55.39.206'),('868','207.46.13.65'),('869','40.77.167.176'),('870','40.77.167.60'),('871','207.46.13.214'),('872','66.249.73.25'),('873','40.77.167.45'),('874','207.46.13.164'),('875','207.46.13.43'),('876','157.55.39.251'),('877','207.46.13.19'),('878','207.46.13.114'),('879','40.77.167.104'),('880','40.77.167.152'),('881','157.55.39.117'),('882','157.55.39.170'),('883','207.46.13.136'),('884','157.55.39.187'),('885','157.55.39.239'),('886','40.77.167.217'),('887','207.46.13.148'),('888','40.77.167.14'),('889','40.77.167.16'),('890','207.46.13.23'),('891','173.208.206.50'),('892','40.77.167.37'),('893','207.46.13.115'),('894','207.46.13.95'),('895','54.36.148.45'),('896','40.77.167.29'),('897','157.55.39.12'),('898','40.77.167.78'),('899','157.55.39.219'),('900','207.46.13.193'),('901','207.46.13.195'),('902','40.77.167.154'),('903','157.55.39.214'),('904','207.46.13.92'),('905','207.46.13.153'),('906','157.55.39.123'),('907','207.46.13.185'),('908','157.55.39.172'),('909','207.46.13.207'),('910','207.46.13.190'),('911','66.249.66.93'),('912','40.77.167.216'),('913','207.46.13.216'),('914','103.131.71.165'),('915','178.63.34.189'),('916','40.77.167.158'),('917','207.46.13.98'),('918','207.46.13.54'),('919','157.55.39.46'),('920','94.154.239.69'),('921','157.55.39.177'),('922','207.46.13.188'),('923','40.77.167.166'),('924','178.63.26.114'),('925','40.77.167.171'),('926','157.55.39.217'),('927','157.55.39.220'),('928','66.249.79.40'),('929','207.46.13.161'),('930','66.249.79.43'),('931','66.249.79.46'),('932','40.77.167.44'),('933','207.46.13.141'),('934','157.55.39.101'),('935','157.55.39.108'),('936','157.55.39.165'),('937','207.46.13.145'),('938','148.251.9.145'),('939','157.55.39.70'),('940','88.198.69.233'),('941','40.77.167.155'),('942','40.77.167.56'),('943','157.55.39.245'),('944','173.249.48.221'),('945','207.46.13.125'),('946','40.77.167.30'),('947','40.77.167.112'),('948','157.55.39.205'),('949','40.77.167.90'),('950','40.77.167.50'),('951','157.55.39.82'),('952','157.55.39.65'),('953','207.46.13.55'),('954','40.77.167.18'),('955','95.216.20.54'),('956','40.77.167.25'),('957','157.55.39.72'),('958','40.77.167.34'),('959','192.99.10.47'),('960','144.76.119.201'),('961','207.46.13.25'),('962','207.180.219.122'),('963','213.239.206.90'),('964','40.77.167.114'),('965','40.77.167.19'),('966','66.249.79.49'),('967','40.77.167.148'),('968','40.77.167.122'),('969','69.30.202.138'),('970','144.76.164.171'),('971','157.55.39.35'),('972','207.46.13.162'),('973','199.16.157.180'),('974','207.46.13.201'),('975','157.55.39.113'),('976','40.77.167.95'),('977','157.55.39.91'),('978','69.30.198.242'),('979','207.46.13.165'),('980','40.77.167.181'),('981','87.250.224.130'),('982','213.239.216.194'),('983','157.55.39.92'),('984','207.46.13.15'),('985','157.55.39.203'),('986','173.212.229.76'),('987','157.55.39.154'),('988','157.55.39.196'),('989','195.154.187.136'),('990','178.154.171.90'),('991','157.55.39.243'),('992','157.55.39.238'),('993','178.151.245.174'),('994','157.55.39.144'),('995','157.55.39.11'),('996','141.8.183.214'),('997','157.55.39.146'),('998','207.46.13.217'),('999','207.46.13.11'),('1000','207.46.13.78'),('1001','207.46.13.133'),('1002','192.151.145.178'),('1003','207.46.13.131'),('1004','144.76.60.198'),('1005','66.249.79.52'),('1006','66.249.79.61'),('1007','66.249.79.58'),('1008','66.249.79.55'),('1009','141.8.142.213'),('1010','157.55.39.69'),('1011','157.55.39.88'),('1012','207.46.13.99'),('1013','157.55.39.162'),('1014','66.249.79.122'),('1015','66.249.79.126'),('1016','66.249.79.182'),('1017','157.55.39.100'),('1018','66.249.79.124'),('1019','207.46.13.174'),('1020','66.249.79.186'),('1021','207.46.13.170'),('1022','157.55.39.105'),('1023','207.46.13.93'),('1024','40.77.167.66'),('1025','40.77.167.54'),('1026','66.249.73.156'),('1027','157.55.39.10'),('1028','207.46.13.88'),('1029','207.46.13.176'),('1030','66.249.79.184'),('1031','66.249.79.102'),('1032','66.249.79.106'),('1033','66.249.79.104'),('1034','66.249.79.108'),('1035','207.46.13.41'),('1036','157.55.39.244'),('1037','103.131.71.175'),('1038','207.46.13.59'),('1039','40.77.167.72'),('1040','157.55.39.139'),('1041','40.77.167.127'),('1042','149.202.82.11'),('1043','95.216.9.239'),('1044','66.249.73.158'),('1045','157.55.39.158'),('1046','207.46.13.64'),('1047','95.216.2.253'),('1048','69.30.213.202'),('1049','207.46.13.48'),('1050','40.77.167.26'),('1051','157.55.39.81'),('1052','157.55.39.235'),('1053','207.46.13.126'),('1054','157.55.39.71'),('1055','40.77.167.61'),('1056','5.189.172.182'),('1057','207.46.13.66'),('1058','207.180.218.247'),('1059','157.55.39.98'),('1060','207.46.13.26'),('1061','157.55.39.227'),('1062','157.55.39.60'),('1063','207.46.13.87'),('1064','207.46.13.34'),('1065','157.55.39.199'),('1066','157.55.39.67'),('1067','207.46.13.47'),('1068','157.55.39.192'),('1069','207.46.13.179'),('1070','157.55.39.161'),('1071','157.55.39.59'),('1072','207.46.13.16'),('1073','192.151.152.98'),('1074','40.77.167.131'),('1075','207.46.13.97'),('1076','217.249.205.17'),('1077','40.77.167.126'),('1078','157.55.39.215'),('1079','78.46.85.236'),('1080','157.55.39.234'),('1081','157.55.39.94'),('1082','40.77.167.80'),('1083','40.77.167.32'),('1084','157.55.39.163'),('1085','40.77.167.110'),('1086','157.55.39.61'),('1087','157.55.39.135'),('1088','157.55.39.156'),('1089','157.55.39.54'),('1090','66.249.64.124'),('1091','66.249.64.126'),('1092','66.249.64.122'),('1093','66.249.64.108'),('1094','40.77.167.36'),('1095','66.249.79.245'),('1096','66.249.79.247'),('1097','66.249.79.243'),('1098','95.216.19.59'),('1099','40.77.167.58'),('1100','40.77.167.57'),('1101','157.55.39.207'),('1102','40.77.167.69'),('1103','157.55.39.131'),('1104','207.46.13.91'),('1105','207.46.13.246'),('1106','157.55.39.73'),('1107','40.77.167.159'),('1108','157.55.39.22'),('1109','207.46.13.12'),('1110','52.168.126.172'),('1111','207.46.13.137'),('1112','176.9.146.84'),('1113','40.77.167.27'),('1114','207.244.157.10'),('1115','66.249.64.106'),('1116','157.55.39.134'),('1117','40.77.167.62'),('1118','207.46.13.227'),('1119','208.110.93.78'),('1120','157.55.39.204'),('1121','173.208.130.202'),('1122','66.249.64.104'),('1123','66.249.76.154'),('1124','144.76.81.229'),('1125','66.249.79.229'),('1126','66.249.79.227'),('1127','207.46.13.29'),('1128','103.131.71.167'),('1129','40.77.167.64'),('1130','91.137.17.122'),('1131','207.46.13.243'),('1132','157.55.39.200'),('1133','207.46.13.13'),('1134','207.46.13.86'),('1135','40.77.167.115'),('1136','40.77.167.11 '),('1137','207.46.13.85 '),('1138','40.77.167.91 '),('1139','40.77.167.125'),('1140','157.55.39.56'),('1141','66.249.79.30'),('1142','66.249.79.28'),('1143','157.55.39.210'),('1144','40.77.167.53'),('1145','157.55.39.186'),('1146','157.55.39.137'),('1147','148.251.78.18'),('1148','144.76.137.254'),('1149','178.63.11.212'),('1150','157.55.39.247'),('1151','85.10.199.185'),('1152','85.10.207.195'),('1153','91.209.51.22'),('1154','148.251.122.126'),('1155','192.151.145.82'),('1156','157.55.39.84'),('1157','207.46.13.35'),('1158','148.251.49.112'),('1159','66.249.76.90'),('1160','178.63.13.154'),('1161','40.77.167.42'),('1162','144.76.29.148'),('1163','40.77.167.75'),('1164','40.77.167.13'),('1165','144.76.2.149'),('1166','18.232.99.123'),('1167','207.46.13.212'),('1168','157.55.39.147'),('1169','157.55.39.232'),('1170','207.46.13.80'),('1171','40.77.167.12'),('1172','54.174.43.27'),('1173','157.55.39.64'),('1174','157.55.39.211'),('1175','91.121.109.55'),('1176','157.55.39.58'),('1177','40.77.167.121'),('1178','157.55.39.241'),('1179','173.212.220.26'),('1180','207.46.13.24'),('1181','69.30.205.218'),('1182','204.12.208.154'),('1183','207.46.13.215'),('1184','148.251.235.104'),('1185','207.46.13.224'),('1186','157.55.39.150'),('1187','198.204.244.90'),('1188','207.46.13.58'),('1189','207.46.13.222'),('1190','207.46.13.211'),('1191','144.76.14.153'),('1192','40.77.167.24'),('1193','157.55.39.208'),('1194','148.251.10.183'),('1195','144.76.38.40'),('1196','144.76.6.230'),('1197','157.55.39.255'),('1198','62.138.2.243'),('1199','207.46.13.61'),('1200','207.180.220.114'),('1201','207.46.13.63'),('1202','204.12.220.106'),('1203','144.76.96.236'),('1204','178.63.87.197'),('1205','141.8.132.30'),('1206','207.180.234.126'),('1207','207.46.13.49'),('1208','207.46.13.228'),('1209','207.46.13.72'),('1210','144.76.118.82'),('1211','50.110.91.221'),('1212','207.46.13.90'),('1213','162.210.196.100'),('1214','178.154.200.14'),('1215','52.168.125.139'),('1216','40.77.167.82'),('1217','66.249.66.140'),('1218','178.19.228.251'),('1219','157.55.39.77'),('1220','157.55.39.198'),('1221','157.55.39.130'),('1222','157.55.39.50'),('1223','157.55.39.79'),('1224','157.55.39.62'),('1225','173.234.153.122'),('1226','92.220.29.21'),('1227','173.212.224.157'),('1228','207.46.13.57'),('1229','95.216.11.95'),('1230','157.55.39.96'),('1231','207.46.13.143'),('1232','157.55.39.66'),('1233','148.251.195.14'),('1234','207.46.13.40'),('1235','207.46.13.14'),('1236','40.77.167.111'),('1237','40.77.167.55'),('1238','157.55.39.212'),('1239','103.131.71.178'),('1240','157.55.39.190'),('1241','192.99.13.88'),('1242','157.55.39.57'),('1243','207.46.13.73'),('1244','207.46.13.22'),('1245','207.46.13.60'),('1246','66.249.64.134'),('1247','66.249.64.150'),('1248','207.46.13.17'),('1249','40.77.167.99'),('1250','66.249.64.28'),('1251','66.249.64.30'),('1252','66.249.64.29'),('1253','66.249.64.58'),('1254','66.249.64.56'),('1255','66.249.70.12'),('1256','66.249.70.14'),('1257','66.249.64.92'),('1258','66.249.64.94'),('1259','66.249.64.90'),('1260','66.249.64.52'),('1261','66.249.64.54'),('1262','66.249.64.208'),('1263','66.249.64.206'),('1264','66.249.64.60'),('1265','66.249.64.184'),('1266','66.249.64.186'),('1267','144.76.90.142'),('1268','63.141.231.10'),('1269','40.77.167.67'),('1270','192.99.13.228'),('1271','40.77.167.88'),('1272','66.249.64.110'),('1273','66.249.64.18'),('1274','66.249.64.74'),('1275','40.77.167.89'),('1276','66.249.64.76'),('1277','54.36.148.44'),('1278','75.162.70.70'),('1279','95.91.140.170'),('1280','157.55.39.180'),('1281','40.77.167.23'),('1282','5.189.159.208'),('1283','40.77.167.33'),('1284','192.99.10.93'),('1285','103.131.71.176'),('1286','40.77.167.65'),('1287','157.55.39.141'),('1288','157.55.39.85'),('1289','69.30.198.186'),('1290','46.28.108.201'),('1291','207.46.13.51'),('1292','144.76.236.112'),('1293','207.46.13.67'),('1294','173.212.246.232'),('1295','207.180.226.173'),('1296','91.137.16.89'),('1297','83.240.61.14'),('1298','66.249.69.40'),('1299','66.249.69.42'),('1300','66.249.69.44'),('1301','148.251.8.250'),('1302','194.247.173.123'),('1303','157.55.39.99'),('1304','103.131.71.179'),('1305','176.31.104.153'),('1306','207.46.13.75'),('1307','40.77.167.83'),('1308','192.99.7.128'),('1309','185.20.6.136'),('1310','207.46.13.82'),('1311','144.76.176.171'),('1312','173.249.24.3'),('1313','40.77.167.15'),('1314','157.55.39.236'),('1315','66.249.73.11'),('1316','157.55.39.149'),('1317','157.55.39.80'),('1318','198.204.243.138'),('1319','157.55.39.152'),('1320','40.77.167.85'),('1321','95.108.213.6'),('1322','88.198.33.145'),('1323','40.117.35.169'),('1324','207.46.13.21'),('1325','157.55.39.167'),('1326','103.131.71.173'),('1327','172.241.112.83'),('1328','40.77.167.52'),('1329','69.30.210.242'),('1330','207.46.13.31'),('1331','18.206.13.39'),('1332','185.20.6.103'),('1333','157.55.39.189'),('1334','204.12.197.234'),('1335','199.47.87.143'),('1336','66.249.73.26'),('1337','78.46.105.172'),('1338','95.216.15.225'),('1339','192.99.13.133'),('1340','66.249.75.28'),('1341','66.249.75.29'),('1342','66.249.75.30'),('1343','66.249.79.44'),('1344','66.249.79.41'),('1345','66.249.79.47'),('1346','173.212.247.190'),('1347','158.69.245.214'),('1348','157.55.39.182'),('1349','66.249.79.53'),('1350','66.249.79.56'),('1351','66.249.79.59'),('1352','185.20.6.154'),('1353','148.251.235.76'),('1354','92.221.145.57'),('1355','95.91.15.240'),('1356','157.55.39.83'),('1357','95.91.75.233'),('1358','157.55.39.53'),('1359','207.180.225.4'),('1360','66.249.75.89'),('1361','66.249.75.106'),('1362','66.249.69.168'),('1363','89.163.242.108'),('1364','66.249.75.40'),('1365','66.249.75.90'),('1366','66.249.75.88'),('1367','66.249.75.102'),('1368','66.249.75.170'),('1369','66.249.69.233'),('1370','66.249.75.198'),('1371','66.249.69.104'),('1372','66.249.75.166'),('1373','66.249.69.202'),('1374','66.249.75.140'),('1375','66.249.75.138'),('1376','66.249.69.198'),('1377','66.249.75.42'),('1378','66.249.75.104'),('1379','66.249.69.229'),('1380','66.249.69.200'),('1381','89.163.242.78'),('1386','178.154.171.30'),('1388','89.163.242.161'),('1390','66.249.69.166'),('1391','66.249.69.170'),('1392','66.249.69.231'),('1393','66.249.75.136'),('1394','157.55.39.213'),('1395','66.249.69.102'),('1396','66.249.69.70'),('1397','66.249.64.31'),('1398','207.46.13.38'),('1399','66.249.64.214'),('1400','157.55.39.49'),('1401','87.250.224.214'),('1402','66.249.64.212'),('1403','66.249.64.216'),('1404','66.249.75.168'),('1405','66.249.75.38'),('1406','40.77.167.59'),('1408','157.55.39.40'),('1409','173.249.7.244'),('1410','66.249.69.38'),('1411','66.249.69.106'),('1412','158.69.245.202'),('1413','89.163.242.186'),('1414','144.76.3.131'),('1415','66.249.73.152'),('1416','91.137.19.220'),('1417','66.249.73.150'),('1418','89.163.146.232'),('1419','103.131.71.166'),('1420','89.163.146.110'),('1421','66.249.73.148'),('1422','138.201.126.84'),('1423','157.55.39.78'),('1424','103.131.71.164'),('1425','157.55.39.86'),('1426','66.249.79.198'),('1427','66.249.79.202'),('1428','66.249.79.200'),('1429','89.163.242.18'),('1430','158.69.243.108'),('1431','199.16.157.182'),('1432','66.249.65.229'),('1434','207.46.13.39'),('1435','89.163.242.129'),('1436','18.204.227.250'),('1437','157.55.39.188'),('1438','23.100.232.233'),('1439','103.131.71.170'),('1440','157.55.39.166'),('1441','94.130.237.168'),('1442','207.46.13.81'),('1443','157.55.39.197'),('1444','87.250.224.93'),('1445','178.154.171.14'),('1446','141.8.142.145'),('1447','207.46.13.79'),('1448','157.55.39.45'),('1449','92.220.10.100'),('1450','192.99.14.130'),('1451','66.249.64.102'),('1452','66.249.64.202'),('1453','66.249.64.120'),('1454','178.154.200.61'),('1455','136.243.70.68'),('1456','141.8.188.64'),('1457','141.8.183.215'),('1458','164.68.121.239'),('1459','66.249.79.114'),('1460','66.249.79.112'),('1461','164.68.117.152'),('1462','66.249.79.116'),('1463','66.249.69.212'),('1464','66.249.69.210'),('1465','66.249.69.208'),('1466','66.249.69.204'),('1467','213.202.253.46'),('1468','157.55.39.155'),('1469','103.131.71.177'),('1470','66.249.69.206'),('1471','40.77.167.77'),('1472','192.99.7.182'),('1474','66.249.69.223'),('1475','66.249.69.192'),('1476','66.249.69.195'),('1477','66.249.75.16'),('1478','213.202.253.44'),('1479','66.249.75.18'),('1480','89.163.146.71'),('1481','66.249.69.217'),('1482','178.154.171.24'),('1483','96.30.145.19'),('1484','173.208.200.154'),('1485','66.249.75.17'),('1490','173.212.242.224'),('1491','178.154.200.34'),('1492','158.69.245.219'),('1493','89.163.242.239'),('1494','144.76.56.124'),('1496','89.163.242.56'),('1497','66.249.75.19'),('1498','66.249.69.219'),('1499','158.69.243.140'),('1500','103.131.71.162'),('1501','207.46.13.27'),('1502','173.249.2.13'),('1503','95.91.15.173'),('1505','141.8.142.133'),('1508','178.150.14.250'),('1509','142.112.13.43'),('1510','158.69.243.138'),('8547','192.99.4.151'),('8548','66.249.75.41'),('8549','66.249.75.39'),('8550','66.249.64.135'),('8551','66.249.64.131'),('8552','66.249.64.128'),('8553','66.249.64.137'),('8554','66.249.64.159'),('8555','87.250.224.102'),('8556','95.163.255.141'),('8557','66.249.79.195'),('8558','66.249.79.223'),('8559','66.249.79.192'),('8560','66.249.79.217'),('8561','66.249.79.219'),('8562','66.249.79.221'),('8563','66.249.79.215'),('8564','213.136.75.74'),('8565','5.189.178.48'),('8569','192.99.14.117'),('8573','46.59.179.11'),('8578','95.108.213.34'),('8579','66.249.69.96'),('8580','66.249.69.127'),('8581','66.249.69.99'),('8582','141.8.183.202'),('8584','213.180.203.3'),('8586','66.249.69.199'),('8587','66.249.69.203'),('8588','167.86.107.199'),('8589','213.180.203.20'),('8590','141.8.142.194'),('8591','87.250.224.212'),('8593','66.249.69.201'),('8594','79.211.77.57'),('8595','69.30.213.82'),('8597','207.180.221.167'),('8598','103.131.71.163'),('8599','157.55.39.41'),('8600','173.212.241.58'),('8601','173.212.222.108'),('8602','103.131.71.168'),('8603','144.76.67.110'),('8604','89.163.242.62'),('8605','173.249.8.105'),('8606','207.46.13.89'),('8607','207.180.245.134');
