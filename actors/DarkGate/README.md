# DarkGate - Cyber Threat Intelligence

These _indicators_ were reported, collected, and generated during the [VulDB CTI analysis](https://vuldb.com/?kb.cti) of the actor known as [DarkGate](https://vuldb.com/?actor.darkgate). The _activity monitoring_ correlates data from social media, forums, chat rooms, and darknet markets. It helps to determine associated actors, specific activities, expected intentions, emerging research, and ongoing attacks. Our unique _predictive model_ uses _big data_ to forecast activities and their characteristics.

_Live data_ and more _analysis capabilities_ are available at [https://vuldb.com/?actor.darkgate](https://vuldb.com/?actor.darkgate)

## Countries

These _countries_ are directly (e.g. origin of attacks) or indirectly (e.g. access by proxy) associated with DarkGate:

* [US](https://vuldb.com/?country.us)
* [CN](https://vuldb.com/?country.cn)
* [LA](https://vuldb.com/?country.la)
* ...

There are 16 more country items available. Please use our online service to access the data.

## IOC - Indicator of Compromise

These _indicators of compromise_ (IOC) indicate associated network resources which are known to be part of research and attack activities of DarkGate.

ID | IP address | Hostname | Campaign | Confidence
-- | ---------- | -------- | -------- | ----------
1 | [5.2.68.68](https://vuldb.com/?ip.5.2.68.68) | - | - | High
2 | [5.2.68.77](https://vuldb.com/?ip.5.2.68.77) | - | - | High
3 | [5.2.68.89](https://vuldb.com/?ip.5.2.68.89) | - | - | High
4 | [5.34.178.21](https://vuldb.com/?ip.5.34.178.21) | udfurgqxmjzcc.pserver.ru | - | High
5 | [5.181.159.49](https://vuldb.com/?ip.5.181.159.49) | no-rdns.mivocloud.com | - | High
6 | [5.181.159.64](https://vuldb.com/?ip.5.181.159.64) | no-rdns.mivocloud.com | - | High
7 | [5.188.87.58](https://vuldb.com/?ip.5.188.87.58) | - | - | High
8 | [38.180.60.31](https://vuldb.com/?ip.38.180.60.31) | - | - | High
9 | [45.89.65.198](https://vuldb.com/?ip.45.89.65.198) | 2.server.com | - | High
10 | [45.141.87.89](https://vuldb.com/?ip.45.141.87.89) | - | - | High
11 | [54.39.198.245](https://vuldb.com/?ip.54.39.198.245) | ip245.ip-54-39-198.net | - | High
12 | [64.190.113.154](https://vuldb.com/?ip.64.190.113.154) | - | - | High
13 | [65.20.75.41](https://vuldb.com/?ip.65.20.75.41) | 65.20.75.41.vultrusercontent.com | - | High
14 | [66.42.63.27](https://vuldb.com/?ip.66.42.63.27) | 66.42.63.27.dedic.cheap | - | High
15 | [79.110.62.96](https://vuldb.com/?ip.79.110.62.96) | - | - | High
16 | ... | ... | ... | ...

There are 59 more IOC items available. Please use our online service to access the data.

## TTP - Tactics, Techniques, Procedures

_Tactics, techniques, and procedures_ (TTP) summarize the suspected MITRE ATT&CK techniques used by _DarkGate_. This data is unique as it uses our predictive model for actor profiling.

ID | Technique | Weakness | Description | Confidence
-- | --------- | -------- | ----------- | ----------
1 | T1006 | CWE-21, CWE-22, CWE-23, CWE-24, CWE-25, CWE-425 | Pathname Traversal | High
2 | T1040 | CWE-319 | Authentication Bypass by Capture-replay | High
3 | T1055 | CWE-74 | Injection | High
4 | T1059 | CWE-88, CWE-94, CWE-1321 | Cross Site Scripting | High
5 | T1059.007 | CWE-79, CWE-80 | Cross Site Scripting | High
6 | T1068 | CWE-264, CWE-269, CWE-284 | J2EE Misconfiguration: Weak Access Permissions for EJB Methods | High
7 | ... | ... | ... | ...

There are 22 more TTP items available. Please use our online service to access the data.

## IOA - Indicator of Attack

These _indicators of attack_ (IOA) list the potential fragments used for technical activities like reconnaissance, exploitation, privilege escalation, and exfiltration by DarkGate. This data is unique as it uses our predictive model for actor profiling.

ID | Type | Indicator | Confidence
-- | ---- | --------- | ----------
1 | File | `%SYSTEMDRIVE%\node_modules\.bin\wmic.exe` | High
2 | File | `/#ProductSerie/view/` | High
3 | File | `/?r=recruit/resume/edit&op=status` | High
4 | File | `/admin/?page=user/list` | High
5 | File | `/admin/?page=user/manage_user&id=3` | High
6 | File | `/admin/about-us.php` | High
7 | File | `/admin/action/add_con.php` | High
8 | File | `/admin/action/delete-vaccine.php` | High
9 | File | `/admin/action/edit_chicken.php` | High
10 | File | `/admin/action/new-father.php` | High
11 | File | `/admin/action/new-feed.php` | High
12 | File | `/admin/action/update-deworm.php` | High
13 | File | `/admin/add-services.php` | High
14 | File | `/admin/admin-profile.php` | High
15 | File | `/admin/clientview.php` | High
16 | File | `/admin/courses/view_course.php` | High
17 | File | `/admin/del_category.php` | High
18 | File | `/admin/del_feedback.php` | High
19 | File | `/admin/del_service.php` | High
20 | File | `/admin/edit_category.php` | High
21 | File | `/admin/edit_product.php` | High
22 | File | `/admin/forgot-password.php` | High
23 | File | `/admin/index/index.html#/admin/mall.goods/index.html` | High
24 | File | `/admin/list_addr_fwresource_ip.php` | High
25 | File | `/admin/pages/edit_chicken.php` | High
26 | File | `/admin/pages/student-print.php` | High
27 | File | `/admin/regester.php` | High
28 | File | `/admin/request-received-bydonar.php` | High
29 | File | `/admin/save.php` | High
30 | File | `/admin/search-appointment.php` | High
31 | File | `/admin/sys_sql_query.php` | High
32 | File | `/admin/update-clients.php` | High
33 | File | `/admin/vote_edit.php` | High
34 | File | `/admin_route/inc_service_credits.php` | High
35 | File | `/ample/app/ajax/member_data.php` | High
36 | File | `/api.php` | Medium
37 | File | `/api/v1/alerts` | High
38 | File | `/api/v1/terminal/sessions/?limit=1` | High
39 | File | `/app/api/controller/default/Sqlite.php` | High
40 | File | `/app/Http/Controllers/ImageController.php` | High
41 | File | `/app/index/controller/Common.php` | High
42 | File | `/auth/auth.php?user=1` | High
43 | File | `/b2b-supermarket/shopping-cart` | High
44 | File | `/bin/boa` | Medium
45 | File | `/blog` | Low
46 | File | `/boafrm/formMapDelDevice` | High
47 | File | `/categorypage.php` | High
48 | File | `/cgi-bin/cstecgi.cgi` | High
49 | File | `/cgi-bin/cstecgi.cgi?action=login` | High
50 | File | `/cgi-bin/vitogate.cgi` | High
51 | File | `/change-language/de_DE` | High
52 | File | `/classes/Master.php?f=delete_category` | High
53 | File | `/classes/Users.php?f=save` | High
54 | File | `/company/store` | High
55 | File | `/config-manager/save` | High
56 | File | `/Controller/Ajaxfileupload.ashx` | High
57 | File | `/debug/pprof` | Medium
58 | File | `/devinfo` | Medium
59 | File | `/dist/index.js` | High
60 | File | `/emap/devicePoint_addImgIco?hasSubsystem=true` | High
61 | File | `/EventBookingCalendar/load.php?controller=GzFront/action=checkout/cid=1/layout=calendar/show_header=T/local=3` | High
62 | File | `/fcgi/scrut_fcgi.fcgi` | High
63 | ... | ... | ...

There are 548 more IOA items available (file, library, argument, input value, pattern, network port). Please use our online service to access the data.

## References

The following list contains _external sources_ which discuss the actor and the associated activities:

* https://app.any.run/tasks/9b94c5e4-d5aa-4eaa-be23-a754f94a617b/
* https://github.com/PaloAltoNetworks/Unit42-timely-threat-intel/blob/main/2023-10-25-IOCs-from-DarkGate-activity.txt
* https://github.com/prodaft/malware-ioc/blob/master/PTI-66/DarkGate.md
* https://github.com/stamparm/maltrail/blob/master/trails/static/malware/darkgate.txt
* https://github.com/stamparm/maltrail/commit/447dfd954176b9c1810cce08043ad5cfbf72175b
* https://github.security.telekom.com/2023/08/darkgate-loader.html
* https://malware-traffic-analysis.net/2023/11/30/index.html
* https://search.censys.io/hosts/94.232.45.90
* https://search.censys.io/hosts/162.33.178.63
* https://search.censys.io/hosts/195.123.233.126
* https://search.censys.io/hosts/195.123.233.152
* https://search.censys.io/hosts/195.123.233.201
* https://search.censys.io/hosts/195.123.233.206
* https://search.censys.io/hosts/195.211.98.105
* https://search.censys.io/search?resource=hosts&sort=RELEVANCE&per_page=25&virtual_hosts=EXCLUDE&q=services.extended_service_name%3D%22DARKGATE%22
* https://search.censys.io/search?resource=hosts&sort=RELEVANCE&per_page=25&virtual_hosts=EXCLUDE&q=services.service_name%3A+DARKGATE
* https://search.censys.io/search?resource=hosts&sort=RELEVANCE&per_page=25&virtual_hosts=EXCLUDE&q=services.service_name%3A+DARKGATE+and+not+labels%3A+tarpit&ref=threatfox
* https://threatfox.abuse.ch
* https://tria.ge/230811-bmv8ysbf8s/behavioral2
* https://tria.ge/230822-xp3lpsgc6v/behavioral2
* https://tria.ge/230828-zp22aaah9s/behavioral1
* https://tria.ge/231026-31zl3sbe25
* https://tria.ge/231102-ssnvhafg98/behavioral2
* https://tria.ge/231102-zyfveahf27
* https://tria.ge/231120-vg8fwahc22
* https://twitter.com/0xw4ifu/status/1714738953016746247
* https://twitter.com/AnFam17/status/1701963227955945552
* https://twitter.com/malwrhunterteam/status/1704231060865778097
* https://twitter.com/malwrhunterteam/status/1704483766461173984
* https://twitter.com/r3dbU7z/status/1712256418483519885
* https://twitter.com/ULTRAFRAUD/status/1702067641983119421
* https://urlhaus.abuse.ch/url/2729402/
* https://www.virustotal.com/gui/file/8ba5c6c94e016941464bc65bd697749e7a2c88fb3a5b420f23cd1aa1ab022eef
* https://www.virustotal.com/gui/file/9921e057693d70d2f6bf13a04abf816c10fe209cff82cb533596ed313b9d2154/detection
* https://www.virustotal.com/gui/file/c2e90c45911b7b6e9d46f4dae5bfefa47e50abddd75cc6d5297cddeee23dd002
* https://www.virustotal.com/gui/file/f0f22f8f3b308b0d8fae34c9eb65ab1e8fde41f9933ef07d1e819163234adbee
* https://www.virustotal.com/gui/file/f12d21bdf3eea879223737eb604feef8c0b15be9b48ad2b1d9d3b43117b0bb3e/detection

## Literature

The following _articles_ explain our unique predictive cyber threat intelligence:

* [VulDB Cyber Threat Intelligence Documentation](https://vuldb.com/?kb.cti)
* [Cyber Threat Intelligence - Early Anticipation of Attacks](https://www.scip.ch/en/?labs.20201022)

## License

(c) [1997-2024](https://vuldb.com/?kb.changelog) by [vuldb.com](https://vuldb.com/?kb.about). All data on this page is shared under the license [CC BY-NC-SA 4.0](https://creativecommons.org/licenses/by-nc-sa/4.0/). Questions? Check the [FAQ](https://vuldb.com/?kb.faq), read the [documentation](https://vuldb.com/?kb) or [contact us](https://vuldb.com/?contact)!
