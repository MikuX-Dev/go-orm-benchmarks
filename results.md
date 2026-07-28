# Results

- orm-benchmark (with no flags)
```
Reports:

InsertMulti
pgx_pool:	1664	722595 ns/op	47594 B/op	38 allocs/op
pgx:		1687	727795 ns/op	47752 B/op	38 allocs/op
sqlc:		1641	737692 ns/op	66531 B/op	639 allocs/op
raw:		1440	821844 ns/op	211887 B/op	537 allocs/op
beego:		1332	896982 ns/op	165535 B/op	2748 allocs/op
sq:		1233	935983 ns/op	261957 B/op	1305 allocs/op
reform:		1170	1013555 ns/op	486930 B/op	2354 allocs/op
gorm_prep:	1218	1013860 ns/op	242182 B/op	1885 allocs/op
pg:		942	1151791 ns/op	5644 B/op	112 allocs/op
bun:		960	1236031 ns/op	42687 B/op	218 allocs/op
jet:		961	1255742 ns/op	345457 B/op	5794 allocs/op
gorm:		901	1320717 ns/op	240501 B/op	5211 allocs/op
gen:		882	1359102 ns/op	255340 B/op	5345 allocs/op
upper:		829	1425791 ns/op	347619 B/op	3805 allocs/op
sqlx:		806	1470731 ns/op	199935 B/op	1558 allocs/op
zorm:		818	1498030 ns/op	178224 B/op	2041 allocs/op
ent:		1077	1644000 ns/op	407525 B/op	4200 allocs/op
godb:		718	1661563 ns/op	235762 B/op	4298 allocs/op
xorm:		716	1674676 ns/op	287747 B/op	5525 allocs/op
rel:		706	1716178 ns/op	300417 B/op	3270 allocs/op
dbr:		bulk-insert is not supported
gorp:		bulk-insert is not supported
sqlboiler:	bulk-insert is not supported
pop:		bulk-insert is not supported

Update
sqlc:		8096	142925 ns/op	288 B/op	8 allocs/op
raw:		8767	145946 ns/op	640 B/op	10 allocs/op
pgx:		4413	270939 ns/op	288 B/op	8 allocs/op
pgx_pool:	4522	275109 ns/op	306 B/op	8 allocs/op
gorp:		4332	278303 ns/op	1024 B/op	20 allocs/op
sqlboiler:	4279	282270 ns/op	792 B/op	14 allocs/op
reform:		3946	283501 ns/op	1664 B/op	48 allocs/op
beego:		4732	284956 ns/op	1720 B/op	50 allocs/op
gorm_prep:	4096	291799 ns/op	5040 B/op	55 allocs/op
ent:		4166	299362 ns/op	4632 B/op	95 allocs/op
jet:		4227	301026 ns/op	4160 B/op	119 allocs/op
sq:		4311	301706 ns/op	7233 B/op	78 allocs/op
dbr:		4046	313450 ns/op	2699 B/op	59 allocs/op
pop:		4010	315636 ns/op	4295 B/op	156 allocs/op
sqlx:		3838	317329 ns/op	1384 B/op	29 allocs/op
pg:		3847	324606 ns/op	800 B/op	9 allocs/op
bun:		3865	325879 ns/op	4826 B/op	5 allocs/op
gorm:		3514	353721 ns/op	5750 B/op	87 allocs/op
gen:		3012	378785 ns/op	14961 B/op	162 allocs/op
zorm:		2679	465474 ns/op	2152 B/op	45 allocs/op
xorm:		2540	485778 ns/op	4769 B/op	153 allocs/op
rel:		2394	495761 ns/op	3560 B/op	54 allocs/op
godb:		2486	499457 ns/op	4929 B/op	133 allocs/op
upper:		1244	966804 ns/op	15199 B/op	380 allocs/op

Read
pgx:		7960	141868 ns/op	736 B/op	10 allocs/op
sqlc:		8409	143459 ns/op	864 B/op	11 allocs/op
pgx_pool:	8268	146347 ns/op	923 B/op	11 allocs/op
beego:		7651	152997 ns/op	2160 B/op	77 allocs/op
raw:		7522	154451 ns/op	1600 B/op	40 allocs/op
reform:		7536	159384 ns/op	2729 B/op	76 allocs/op
gorp:		7285	165363 ns/op	2880 B/op	114 allocs/op
pop:		7718	171774 ns/op	2666 B/op	55 allocs/op
gorm_prep:	6880	173974 ns/op	4453 B/op	77 allocs/op
ent:		6585	174653 ns/op	5200 B/op	135 allocs/op
sq:		6700	177167 ns/op	10586 B/op	116 allocs/op
bun:		6571	182864 ns/op	5844 B/op	39 allocs/op
pg:		6835	184784 ns/op	904 B/op	20 allocs/op
dbr:		6894	187531 ns/op	2248 B/op	37 allocs/op
rel:		6052	190212 ns/op	2384 B/op	49 allocs/op
sqlboiler:	6452	192269 ns/op	791 B/op	23 allocs/op
zorm:		6230	197393 ns/op	3792 B/op	65 allocs/op
jet:		5856	203557 ns/op	11867 B/op	235 allocs/op
gorm:		5384	231445 ns/op	4609 B/op	91 allocs/op
upper:		5194	233712 ns/op	3928 B/op	104 allocs/op
gen:		4549	258903 ns/op	12623 B/op	158 allocs/op
sqlx:		4046	325988 ns/op	2136 B/op	48 allocs/op
godb:		3859	334227 ns/op	4145 B/op	99 allocs/op
xorm:		3664	354827 ns/op	5265 B/op	134 allocs/op

ReadSlice
reform:		7980	160995 ns/op	3321 B/op	92 allocs/op
pgx:		4831	233734 ns/op	30288 B/op	505 allocs/op
pgx_pool:	4808	236372 ns/op	30347 B/op	505 allocs/op
upper:		5262	236874 ns/op	3808 B/op	85 allocs/op
sqlc:		4608	252194 ns/op	54592 B/op	612 allocs/op
raw:		4056	281307 ns/op	25408 B/op	1029 allocs/op
pg:		3505	326237 ns/op	22422 B/op	629 allocs/op
gorp:		3396	347385 ns/op	43982 B/op	1413 allocs/op
ent:		3219	359679 ns/op	64401 B/op	2024 allocs/op
pop:		3163	364274 ns/op	63469 B/op	1284 allocs/op
sqlx:		3246	365973 ns/op	37560 B/op	1227 allocs/op
zorm:		2998	390910 ns/op	74896 B/op	1366 allocs/op
dbr:		2883	400509 ns/op	30944 B/op	1246 allocs/op
beego:		2916	402555 ns/op	55381 B/op	3078 allocs/op
sq:		2894	403345 ns/op	139405 B/op	1809 allocs/op
bun:		2902	405403 ns/op	34212 B/op	1124 allocs/op
sqlboiler:	2898	416364 ns/op	45788 B/op	1250 allocs/op
gorm_prep:	2752	423807 ns/op	43442 B/op	2070 allocs/op
gorm:		2450	484853 ns/op	44435 B/op	2185 allocs/op
gen:		2181	525175 ns/op	52564 B/op	2253 allocs/op
xorm:		2073	572800 ns/op	120478 B/op	4309 allocs/op
jet:		2078	578978 ns/op	169266 B/op	2713 allocs/op
godb:		1917	623552 ns/op	69104 B/op	2288 allocs/op
rel:		1798	668842 ns/op	149169 B/op	2558 allocs/op

Insert
pgx_pool:	4716	263446 ns/op	298 B/op	8 allocs/op
sqlc:		4724	266961 ns/op	280 B/op	8 allocs/op
raw:		4096	269455 ns/op	600 B/op	10 allocs/op
gorp:		4592	277073 ns/op	1511 B/op	26 allocs/op
pgx:		4332	280321 ns/op	280 B/op	8 allocs/op
jet:		4360	285645 ns/op	3352 B/op	99 allocs/op
ent:		3880	288739 ns/op	3935 B/op	90 allocs/op
beego:		4292	289560 ns/op	2352 B/op	58 allocs/op
reform:		4160	289594 ns/op	1665 B/op	48 allocs/op
sqlboiler:	3910	295146 ns/op	1359 B/op	26 allocs/op
gorm_prep:	3999	302249 ns/op	5184 B/op	60 allocs/op
sq:		3806	305879 ns/op	9481 B/op	84 allocs/op
pg:		4135	309425 ns/op	1096 B/op	10 allocs/op
dbr:		3354	309911 ns/op	2672 B/op	59 allocs/op
pop:		3079	325933 ns/op	4962 B/op	158 allocs/op
bun:		3786	328261 ns/op	5076 B/op	12 allocs/op
upper:		3165	353188 ns/op	5391 B/op	113 allocs/op
gen:		3351	354548 ns/op	10260 B/op	127 allocs/op
gorm:		3386	355344 ns/op	5920 B/op	92 allocs/op
zorm:		2697	444408 ns/op	2071 B/op	50 allocs/op
sqlx:		2690	451570 ns/op	1336 B/op	28 allocs/op
godb:		2728	459626 ns/op	4417 B/op	103 allocs/op
xorm:		2565	461716 ns/op	3152 B/op	92 allocs/op
rel:		2702	487666 ns/op	2671 B/op	50 allocs/op
```
