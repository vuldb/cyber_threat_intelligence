# RisePro - Cyber Threat Intelligence

These _indicators_ were reported, collected, and generated during the [VulDB CTI analysis](https://vuldb.com/?kb.cti) of the actor known as [RisePro](https://vuldb.com/?actor.risepro). The _activity monitoring_ correlates data from social media, forums, chat rooms, and darknet markets. It helps to determine associated actors, specific activities, expected intentions, emerging research, and ongoing attacks. Our unique _predictive model_ uses _big data_ to forecast activities and their characteristics.

_Live data_ and more _analysis capabilities_ are available at [https://vuldb.com/?actor.risepro](https://vuldb.com/?actor.risepro)

## Countries

These _countries_ are directly (e.g. origin of attacks) or indirectly (e.g. access by proxy) associated with RisePro:

* [US](https://vuldb.com/?country.us)
* [CN](https://vuldb.com/?country.cn)
* [GB](https://vuldb.com/?country.gb)
* ...

There are 18 more country items available. Please use our online service to access the data.

## IOC - Indicator of Compromise

These _indicators of compromise_ (IOC) indicate associated network resources which are known to be part of research and attack activities of RisePro.

ID | IP address | Hostname | Campaign | Confidence
-- | ---------- | -------- | -------- | ----------
1 | [5.42.79.238](https://vuldb.com/?ip.5.42.79.238) | - | - | High
2 | [5.161.143.161](https://vuldb.com/?ip.5.161.143.161) | static.161.143.161.5.clients.your-server.de | - | High
3 | [38.47.220.202](https://vuldb.com/?ip.38.47.220.202) | - | - | High
4 | [43.128.18.131](https://vuldb.com/?ip.43.128.18.131) | - | - | High
5 | [45.11.91.14](https://vuldb.com/?ip.45.11.91.14) | - | - | High
6 | [45.15.156.137](https://vuldb.com/?ip.45.15.156.137) | - | - | High
7 | [45.15.156.175](https://vuldb.com/?ip.45.15.156.175) | - | - | High
8 | [45.15.159.248](https://vuldb.com/?ip.45.15.159.248) | tranquil-sheep.aeza.network | - | High
9 | [45.74.19.132](https://vuldb.com/?ip.45.74.19.132) | - | - | High
10 | [45.81.39.247](https://vuldb.com/?ip.45.81.39.247) | - | - | High
11 | [45.135.232.54](https://vuldb.com/?ip.45.135.232.54) | - | - | High
12 | [45.153.242.188](https://vuldb.com/?ip.45.153.242.188) | - | - | High
13 | [51.89.205.213](https://vuldb.com/?ip.51.89.205.213) | ip213.ip-51-89-205.eu | - | High
14 | [77.105.147.123](https://vuldb.com/?ip.77.105.147.123) | high-alarm.aeza.network | - | High
15 | [79.110.49.141](https://vuldb.com/?ip.79.110.49.141) | - | - | High
16 | ... | ... | ... | ...

There are 60 more IOC items available. Please use our online service to access the data.

## TTP - Tactics, Techniques, Procedures

_Tactics, techniques, and procedures_ (TTP) summarize the suspected MITRE ATT&CK techniques used by _RisePro_. This data is unique as it uses our predictive model for actor profiling.

ID | Technique | Weakness | Description | Confidence
-- | --------- | -------- | ----------- | ----------
1 | T1006 | CWE-21, CWE-22, CWE-23, CWE-36, CWE-425 | Pathname Traversal | High
2 | T1055 | CWE-74 | Injection | High
3 | T1059 | CWE-88, CWE-94, CWE-1321 | Cross Site Scripting | High
4 | T1059.007 | CWE-79, CWE-80 | Cross Site Scripting | High
5 | T1068 | CWE-264, CWE-269, CWE-284 | J2EE Misconfiguration: Weak Access Permissions for EJB Methods | High
6 | ... | ... | ... | ...

There are 19 more TTP items available. Please use our online service to access the data.

## IOA - Indicator of Attack

These _indicators of attack_ (IOA) list the potential fragments used for technical activities like reconnaissance, exploitation, privilege escalation, and exfiltration by RisePro. This data is unique as it uses our predictive model for actor profiling.

ID | Type | Indicator | Confidence
-- | ---- | --------- | ----------
1 | File | `//WEB-INF` | Medium
2 | File | `/about.php` | Medium
3 | File | `/admin/edit-accepted-appointment.php` | High
4 | File | `/admin/reg.php` | High
5 | File | `/admin/save.php` | High
6 | File | `/admin/service.php` | High
7 | File | `/admin/sys_sql_query.php` | High
8 | File | `/api/baskets/{name}` | High
9 | File | `/api/download` | High
10 | File | `/api/v1/alerts` | High
11 | File | `/api/v1/terminal/sessions/?limit=1` | High
12 | File | `/be/erpc.php` | Medium
13 | File | `/bitrix/admin/ldap_server_edit.php` | High
14 | File | `/cas/logout` | Medium
15 | File | `/category.php` | High
16 | File | `/categorypage.php` | High
17 | File | `/cgi-bin/luci/api/wireless` | High
18 | File | `/cgi-bin/vitogate.cgi` | High
19 | File | `/changeimage.php` | High
20 | File | `/collection/all` | High
21 | File | `/company/store` | High
22 | File | `/Content/Template/root/reverse-shell.aspx` | High
23 | File | `/Controller/Ajaxfileupload.ashx` | High
24 | File | `/core/conditions/AbstractWrapper.java` | High
25 | File | `/debug/pprof` | Medium
26 | File | `/Duty/AjaxHandle/Write/UploadFile.ashx` | High
27 | File | `/ecommerce/support_ticket` | High
28 | File | `/etc/passwd` | Medium
29 | File | `/fcgi/scrut_fcgi.fcgi` | High
30 | File | `/forum/away.php` | High
31 | File | `/geoserver/gwc/rest.html` | High
32 | File | `/h/` | Low
33 | File | `/HNAP1` | Low
34 | File | `/inc/jquery/uploadify/uploadify.php` | High
35 | File | `/index.php?app=main&func=passport&action=login` | High
36 | File | `/index.php?page=category_list` | High
37 | File | `/index.php?page=member` | High
38 | File | `/jeecg-boot/sys/common/upload` | High
39 | File | `/jobinfo/` | Medium
40 | File | `/leaves/validate` | High
41 | File | `/Moosikay/order.php` | High
42 | File | `/OA_HTML/cabo/jsps/a.jsp` | High
43 | File | `/preview.php` | Medium
44 | File | `/PreviewHandler.ashx` | High
45 | File | `/proxy` | Low
46 | File | `/recipe-result` | High
47 | File | `/register.do` | Medium
48 | File | `/RPS2019Service/status.html` | High
49 | File | `/Service/ImageStationDataService.asmx` | High
50 | File | `/setting` | Medium
51 | File | `/sicweb-ajax/tmproot/` | High
52 | File | `/spip.php` | Medium
53 | File | `/student/bookdetails.php` | High
54 | File | `/subsys/net/l2/wifi/wifi_shell.c` | High
55 | ... | ... | ...

There are 477 more IOA items available (file, library, argument, input value, pattern, network port). Please use our online service to access the data.

## References

The following list contains _external sources_ which discuss the actor and the associated activities:

* https://app.any.run/tasks/057f15c5-864c-4535-b8af-70405ead5fcd
* https://app.any.run/tasks/8d068314-5e98-49d2-aac1-9756c9185d11
* https://app.any.run/tasks/66a96b13-f430-49b9-8ac2-a5c2698d61a9
* https://app.any.run/tasks/2457181d-fa22-4ef3-b171-6711c7456570
* https://app.any.run/tasks/a4b98e2a-4e47-436f-a50d-a5d1a0c520d1
* https://app.any.run/tasks/d1a96aea-a514-4f86-acd7-e9391a8ec959/
* https://threatfox.abuse.ch
* https://tracker.viriback.com/index.php?q=38.47.220.202
* https://tracker.viriback.com/index.php?q=45.15.159.248
* https://tracker.viriback.com/index.php?q=91.92.252.212
* https://tracker.viriback.com/index.php?q=91.103.253.146
* https://tracker.viriback.com/index.php?q=95.214.25.231
* https://tracker.viriback.com/index.php?q=185.173.38.198

## Literature

The following _articles_ explain our unique predictive cyber threat intelligence:

* [VulDB Cyber Threat Intelligence Documentation](https://vuldb.com/?kb.cti)
* [Cyber Threat Intelligence - Early Anticipation of Attacks](https://www.scip.ch/en/?labs.20201022)

## License

(c) [1997-2023](https://vuldb.com/?kb.changelog) by [vuldb.com](https://vuldb.com/?kb.about). All data on this page is shared under the license [CC BY-NC-SA 4.0](https://creativecommons.org/licenses/by-nc-sa/4.0/). Questions? Check the [FAQ](https://vuldb.com/?kb.faq), read the [documentation](https://vuldb.com/?kb) or [contact us](https://vuldb.com/?contact)!
