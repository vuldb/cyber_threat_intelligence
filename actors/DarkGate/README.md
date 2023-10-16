# DarkGate - Cyber Threat Intelligence

These _indicators_ were reported, collected, and generated during the [VulDB CTI analysis](https://vuldb.com/?kb.cti) of the actor known as [DarkGate](https://vuldb.com/?actor.darkgate). The _activity monitoring_ correlates data from social media, forums, chat rooms, and darknet markets. It helps to determine associated actors, specific activities, expected intentions, emerging research, and ongoing attacks. Our unique _predictive model_ uses _big data_ to forecast activities and their characteristics.

_Live data_ and more _analysis capabilities_ are available at [https://vuldb.com/?actor.darkgate](https://vuldb.com/?actor.darkgate)

## Countries

These _countries_ are directly (e.g. origin of attacks) or indirectly (e.g. access by proxy) associated with DarkGate:

* [US](https://vuldb.com/?country.us)
* [CN](https://vuldb.com/?country.cn)
* [LA](https://vuldb.com/?country.la)
* ...

There are 18 more country items available. Please use our online service to access the data.

## IOC - Indicator of Compromise

These _indicators of compromise_ (IOC) indicate associated network resources which are known to be part of research and attack activities of DarkGate.

ID | IP address | Hostname | Campaign | Confidence
-- | ---------- | -------- | -------- | ----------
1 | [5.2.68.68](https://vuldb.com/?ip.5.2.68.68) | - | - | High
2 | [5.2.68.77](https://vuldb.com/?ip.5.2.68.77) | - | - | High
3 | [5.34.178.21](https://vuldb.com/?ip.5.34.178.21) | udfurgqxmjzcc.pserver.ru | - | High
4 | [5.188.87.58](https://vuldb.com/?ip.5.188.87.58) | - | - | High
5 | [45.89.65.198](https://vuldb.com/?ip.45.89.65.198) | 2.server.com | - | High
6 | [45.141.87.89](https://vuldb.com/?ip.45.141.87.89) | - | - | High
7 | [54.39.198.245](https://vuldb.com/?ip.54.39.198.245) | ip245.ip-54-39-198.net | - | High
8 | [64.190.113.154](https://vuldb.com/?ip.64.190.113.154) | - | - | High
9 | [65.20.75.41](https://vuldb.com/?ip.65.20.75.41) | 65.20.75.41.vultrusercontent.com | - | High
10 | [66.42.63.27](https://vuldb.com/?ip.66.42.63.27) | 66.42.63.27.dedic.cheap | - | High
11 | [79.110.62.96](https://vuldb.com/?ip.79.110.62.96) | - | - | High
12 | ... | ... | ... | ...

There are 43 more IOC items available. Please use our online service to access the data.

## TTP - Tactics, Techniques, Procedures

_Tactics, techniques, and procedures_ (TTP) summarize the suspected MITRE ATT&CK techniques used by _DarkGate_. This data is unique as it uses our predictive model for actor profiling.

ID | Technique | Weakness | Description | Confidence
-- | --------- | -------- | ----------- | ----------
1 | T1006 | CWE-21, CWE-22, CWE-23 | Pathname Traversal | High
2 | T1040 | CWE-319 | Authentication Bypass by Capture-replay | High
3 | T1055 | CWE-74 | Injection | High
4 | T1059 | CWE-88, CWE-94, CWE-1321 | Cross Site Scripting | High
5 | T1059.007 | CWE-79, CWE-80 | Cross Site Scripting | High
6 | ... | ... | ... | ...

There are 20 more TTP items available. Please use our online service to access the data.

## IOA - Indicator of Attack

These _indicators of attack_ (IOA) list the potential fragments used for technical activities like reconnaissance, exploitation, privilege escalation, and exfiltration by DarkGate. This data is unique as it uses our predictive model for actor profiling.

ID | Type | Indicator | Confidence
-- | ---- | --------- | ----------
1 | File | `//WEB-INF` | Medium
2 | File | `/about.php` | Medium
3 | File | `/admin.php/update/getFile.html` | High
4 | File | `/admin/cashadvance_row.php` | High
5 | File | `/admin/index/index.html#/admin/mall.goods/index.html` | High
6 | File | `/admin/maintenance/view_designation.php` | High
7 | File | `/admin/save.php` | High
8 | File | `/admin/sys_sql_query.php` | High
9 | File | `/admin/userprofile.php` | High
10 | File | `/api/baskets/{name}` | High
11 | File | `/api/download` | High
12 | File | `/api/v1/terminal/sessions/?limit=1` | High
13 | File | `/bitrix/admin/ldap_server_edit.php` | High
14 | File | `/category.php` | High
15 | File | `/categorypage.php` | High
16 | File | `/cgi-bin/luci/api/wireless` | High
17 | File | `/cgi-bin/vitogate.cgi` | High
18 | File | `/classes/Master.php?f=save_item` | High
19 | File | `/company/store` | High
20 | File | `/Content/Template/root/reverse-shell.aspx` | High
21 | File | `/Controller/Ajaxfileupload.ashx` | High
22 | File | `/core/conditions/AbstractWrapper.java` | High
23 | File | `/DXR.axd` | Medium
24 | File | `/etc/passwd` | Medium
25 | File | `/feeds/post/publish` | High
26 | File | `/forum/away.php` | High
27 | File | `/h/` | Low
28 | File | `/HNAP1` | Low
29 | File | `/inc/jquery/uploadify/uploadify.php` | High
30 | File | `/index.php?app=main&func=passport&action=login` | High
31 | File | `/index.php?page=category_list` | High
32 | File | `/jeecg-boot/sys/common/upload` | High
33 | File | `/jobinfo/` | Medium
34 | File | `/load.php` | Medium
35 | File | `/Moosikay/order.php` | High
36 | File | `/opac/Actions.php?a=login` | High
37 | File | `/PreviewHandler.ashx` | High
38 | File | `/recipe-result` | High
39 | File | `/register.do` | Medium
40 | File | `/reservation/add_message.php` | High
41 | File | `/resources//../` | High
42 | File | `/RPS2019Service/status.html` | High
43 | File | `/Service/ImageStationDataService.asmx` | High
44 | File | `/sicweb-ajax/tmproot/` | High
45 | File | `/spip.php` | Medium
46 | File | `/student/bookdetails.php` | High
47 | File | `/SystemManage/User/GetGridJson?_search=false&nd=1680855479750&rows=50&page=1&sidx=F_CreatorTime+desc&sord=asc` | High
48 | File | `/uploads/exam_question/` | High
49 | File | `/user/ticket/create` | High
50 | File | `/user/updatePwd` | High
51 | File | `/UserSelfServiceSettings.jsp` | High
52 | File | `/var/lib/docker/<remapping>` | High
53 | ... | ... | ...

There are 462 more IOA items available (file, library, argument, input value, pattern, network port). Please use our online service to access the data.

## References

The following list contains _external sources_ which discuss the actor and the associated activities:

* https://github.com/prodaft/malware-ioc/blob/master/PTI-66/DarkGate.md
* https://github.com/stamparm/maltrail/blob/master/trails/static/malware/darkgate.txt
* https://github.com/stamparm/maltrail/commit/447dfd954176b9c1810cce08043ad5cfbf72175b
* https://github.security.telekom.com/2023/08/darkgate-loader.html
* https://search.censys.io/hosts/94.232.45.90
* https://search.censys.io/hosts/162.33.178.63
* https://search.censys.io/hosts/195.211.98.105
* https://search.censys.io/search?resource=hosts&sort=RELEVANCE&per_page=25&virtual_hosts=EXCLUDE&q=services.service_name%3A+DARKGATE
* https://search.censys.io/search?resource=hosts&sort=RELEVANCE&per_page=25&virtual_hosts=EXCLUDE&q=services.service_name%3A+DARKGATE+and+not+labels%3A+tarpit&ref=threatfox
* https://threatfox.abuse.ch
* https://tria.ge/230811-bmv8ysbf8s/behavioral2
* https://tria.ge/230822-xp3lpsgc6v/behavioral2
* https://tria.ge/230828-zp22aaah9s/behavioral1
* https://twitter.com/AnFam17/status/1701963227955945552
* https://twitter.com/malwrhunterteam/status/1704231060865778097
* https://twitter.com/malwrhunterteam/status/1704483766461173984
* https://twitter.com/r3dbU7z/status/1712256418483519885
* https://twitter.com/ULTRAFRAUD/status/1702067641983119421
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

(c) [1997-2023](https://vuldb.com/?kb.changelog) by [vuldb.com](https://vuldb.com/?kb.about). All data on this page is shared under the license [CC BY-NC-SA 4.0](https://creativecommons.org/licenses/by-nc-sa/4.0/). Questions? Check the [FAQ](https://vuldb.com/?kb.faq), read the [documentation](https://vuldb.com/?kb) or [contact us](https://vuldb.com/?contact)!
