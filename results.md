# Results

- orm-benchmark (with no flags)
```
Reports:

Read
sqlc:		7104	166950 ns/op	904 B/op	19 allocs/op
pgx:		7142	167107 ns/op	776 B/op	18 allocs/op
pgx_pool:	6814	167907 ns/op	964 B/op	19 allocs/op
raw:		7360	172199 ns/op	2093 B/op	50 allocs/op
beego:		7075	178310 ns/op	2128 B/op	76 allocs/op
reform:		6885	181298 ns/op	3230 B/op	86 allocs/op
gorp:		7036	184387 ns/op	3333 B/op	122 allocs/op
pop:		7117	186723 ns/op	3183 B/op	66 allocs/op
ent:		5990	193079 ns/op	5686 B/op	145 allocs/op
sqlboiler:	6387	194579 ns/op	948 B/op	14 allocs/op
sq:		5974	194811 ns/op	11080 B/op	126 allocs/op
gorm_prep:	6399	200014 ns/op	4597 B/op	89 allocs/op
dbr:		6019	203117 ns/op	2184 B/op	36 allocs/op
pg:		6086	203130 ns/op	872 B/op	20 allocs/op
bun:		5881	206237 ns/op	5847 B/op	39 allocs/op
rel:		6387	206493 ns/op	2336 B/op	47 allocs/op
jet:		5707	209441 ns/op	12859 B/op	249 allocs/op
zorm:		5530	214577 ns/op	3744 B/op	63 allocs/op
gorm:		4851	247412 ns/op	5013 B/op	102 allocs/op
gen:		4290	266166 ns/op	13151 B/op	170 allocs/op
sqlx:		3229	370186 ns/op	2008 B/op	43 allocs/op
godb:		3358	373699 ns/op	4033 B/op	94 allocs/op
upper:		3132	374812 ns/op	5085 B/op	110 allocs/op
xorm:		3160	386493 ns/op	5161 B/op	131 allocs/op

ReadSlice
reform:		7172	181402 ns/op	4046 B/op	100 allocs/op
pgx_pool:	4470	259934 ns/op	30381 B/op	513 allocs/op
pgx:		4280	261359 ns/op	30320 B/op	513 allocs/op
sqlc:		4178	277423 ns/op	54625 B/op	620 allocs/op
raw:		3697	307728 ns/op	38373 B/op	1038 allocs/op
pg:		3211	367767 ns/op	23766 B/op	629 allocs/op
gorp:		3117	377493 ns/op	56971 B/op	1422 allocs/op
ent:		2809	378367 ns/op	77398 B/op	2036 allocs/op
sqlx:		3048	389037 ns/op	37512 B/op	1225 allocs/op
pop:		3012	392296 ns/op	77091 B/op	1306 allocs/op
upper:		3052	396282 ns/op	4824 B/op	90 allocs/op
sq:		2798	410984 ns/op	152433 B/op	1821 allocs/op
zorm:		2791	424589 ns/op	74850 B/op	1364 allocs/op
dbr:		2749	425856 ns/op	30880 B/op	1245 allocs/op
bun:		2646	440228 ns/op	34209 B/op	1124 allocs/op
beego:		2572	443887 ns/op	55369 B/op	3078 allocs/op
sqlboiler:	2640	445456 ns/op	58952 B/op	1260 allocs/op
gorm_prep:	2624	463291 ns/op	43588 B/op	2082 allocs/op
gorm:		2395	524946 ns/op	44809 B/op	2196 allocs/op
gen:		1963	556439 ns/op	53051 B/op	2264 allocs/op
jet:		2018	577358 ns/op	184340 B/op	2828 allocs/op
xorm:		1988	584364 ns/op	121238 B/op	4407 allocs/op
godb:		1761	664812 ns/op	68994 B/op	2284 allocs/op
rel:		1671	717060 ns/op	149044 B/op	2553 allocs/op

Insert
raw:		3688	337355 ns/op	703 B/op	13 allocs/op
pgx_pool:	3166	346368 ns/op	298 B/op	8 allocs/op
sqlboiler:	3361	359151 ns/op	1582 B/op	33 allocs/op
pgx:		3223	370170 ns/op	280 B/op	8 allocs/op
beego:		2998	372908 ns/op	2416 B/op	57 allocs/op
reform:		3193	373609 ns/op	1776 B/op	51 allocs/op
sq:		3036	375489 ns/op	9705 B/op	91 allocs/op
sqlc:		3297	380930 ns/op	280 B/op	8 allocs/op
pg:		3016	383709 ns/op	1166 B/op	10 allocs/op
ent:		3030	385976 ns/op	4149 B/op	97 allocs/op
jet:		3265	387357 ns/op	3528 B/op	98 allocs/op
gorp:		3012	394485 ns/op	1734 B/op	33 allocs/op
dbr:		2932	401882 ns/op	2624 B/op	57 allocs/op
gorm_prep:	3097	408158 ns/op	5384 B/op	66 allocs/op
bun:		3064	428438 ns/op	5028 B/op	13 allocs/op
gorm:		2610	448490 ns/op	7400 B/op	106 allocs/op
gen:		2677	450660 ns/op	11738 B/op	141 allocs/op
godb:		2344	535714 ns/op	4410 B/op	99 allocs/op
sqlx:		2284	554721 ns/op	856 B/op	19 allocs/op
zorm:		2312	556794 ns/op	2038 B/op	45 allocs/op
rel:		2056	581657 ns/op	2638 B/op	45 allocs/op
upper:		2077	593699 ns/op	5914 B/op	125 allocs/op
xorm:		2136	618574 ns/op	3120 B/op	87 allocs/op
pop:		1549	796456 ns/op	9323 B/op	212 allocs/op

InsertMulti
pgx:		1366	842185 ns/op	47763 B/op	38 allocs/op
pgx_pool:	1374	879647 ns/op	47473 B/op	38 allocs/op
sqlc:		1246	910163 ns/op	66527 B/op	639 allocs/op
raw:		1363	929355 ns/op	187137 B/op	930 allocs/op
sq:		1184	1034278 ns/op	237246 B/op	1697 allocs/op
beego:		1162	1072492 ns/op	177776 B/op	2745 allocs/op
reform:		993	1149285 ns/op	462191 B/op	2746 allocs/op
gorm_prep:	1042	1167661 ns/op	254578 B/op	1891 allocs/op
ent:		958	1294778 ns/op	396540 B/op	4597 allocs/op
pg:		906	1332811 ns/op	4555 B/op	112 allocs/op
jet:		854	1376630 ns/op	332743 B/op	5793 allocs/op
bun:		853	1387724 ns/op	42709 B/op	219 allocs/op
gorm:		756	1520580 ns/op	276377 B/op	5231 allocs/op
sqlx:		816	1540334 ns/op	170914 B/op	1550 allocs/op
gen:		760	1604555 ns/op	291080 B/op	5364 allocs/op
zorm:		745	1609178 ns/op	149363 B/op	2032 allocs/op
xorm:		688	1768280 ns/op	258933 B/op	5518 allocs/op
godb:		693	1787370 ns/op	247947 B/op	4294 allocs/op
upper:		693	1790129 ns/op	328165 B/op	4204 allocs/op
rel:		681	1815586 ns/op	312570 B/op	3265 allocs/op
pop:		bulk-insert is not supported
dbr:		bulk-insert is not supported
sqlboiler:	bulk-insert is not supported
gorp:		bulk-insert is not supported

Update
raw:		7836	163016 ns/op	750 B/op	13 allocs/op
sqlc:		7257	165725 ns/op	288 B/op	8 allocs/op
sqlx:		3508	355476 ns/op	872 B/op	20 allocs/op
pgx:		3218	359532 ns/op	288 B/op	8 allocs/op
jet:		3132	375284 ns/op	4511 B/op	119 allocs/op
sq:		2941	378753 ns/op	7341 B/op	81 allocs/op
sqlboiler:	3213	384273 ns/op	900 B/op	17 allocs/op
reform:		2994	386880 ns/op	1774 B/op	51 allocs/op
beego:		3118	388270 ns/op	1752 B/op	47 allocs/op
gorm_prep:	3424	389726 ns/op	5104 B/op	56 allocs/op
gorp:		3358	391451 ns/op	1133 B/op	23 allocs/op
pop:		3450	392362 ns/op	5743 B/op	170 allocs/op
pgx_pool:	3285	392882 ns/op	306 B/op	8 allocs/op
dbr:		3098	398151 ns/op	2651 B/op	57 allocs/op
ent:		3406	410953 ns/op	4727 B/op	98 allocs/op
bun:		3066	424864 ns/op	4762 B/op	5 allocs/op
pg:		3015	431585 ns/op	768 B/op	9 allocs/op
gorm:		2782	469194 ns/op	6864 B/op	99 allocs/op
gen:		2197	494965 ns/op	16584 B/op	175 allocs/op
zorm:		2163	571226 ns/op	1640 B/op	36 allocs/op
godb:		1982	572909 ns/op	4953 B/op	130 allocs/op
xorm:		2174	591979 ns/op	4305 B/op	145 allocs/op
rel:		1923	602701 ns/op	3048 B/op	45 allocs/op
upper:		807	1334064 ns/op	16729 B/op	390 allocs/op
```
