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
2 | [5.42.92.51](https://vuldb.com/?ip.5.42.92.51) | hosted-by.yeezyhost.net | - | High
3 | [5.161.143.161](https://vuldb.com/?ip.5.161.143.161) | static.161.143.161.5.clients.your-server.de | - | High
4 | [5.188.159.44](https://vuldb.com/?ip.5.188.159.44) | - | - | High
5 | [37.27.22.139](https://vuldb.com/?ip.37.27.22.139) | static.139.22.27.37.clients.your-server.de | - | High
6 | [38.47.220.202](https://vuldb.com/?ip.38.47.220.202) | - | - | High
7 | [43.128.18.131](https://vuldb.com/?ip.43.128.18.131) | - | - | High
8 | [45.11.91.14](https://vuldb.com/?ip.45.11.91.14) | - | - | High
9 | [45.15.156.137](https://vuldb.com/?ip.45.15.156.137) | - | - | High
10 | [45.15.156.175](https://vuldb.com/?ip.45.15.156.175) | - | - | High
11 | [45.15.159.248](https://vuldb.com/?ip.45.15.159.248) | tranquil-sheep.aeza.network | - | High
12 | [45.74.19.132](https://vuldb.com/?ip.45.74.19.132) | - | - | High
13 | [45.81.39.247](https://vuldb.com/?ip.45.81.39.247) | - | - | High
14 | [45.135.232.54](https://vuldb.com/?ip.45.135.232.54) | - | - | High
15 | [45.153.242.188](https://vuldb.com/?ip.45.153.242.188) | - | - | High
16 | [46.4.10.254](https://vuldb.com/?ip.46.4.10.254) | 46-4-10-254.ptr | - | High
17 | [51.81.131.161](https://vuldb.com/?ip.51.81.131.161) | ip161.ip-51-81-131.us | - | High
18 | [51.89.205.213](https://vuldb.com/?ip.51.89.205.213) | ip213.ip-51-89-205.eu | - | High
19 | [51.255.78.213](https://vuldb.com/?ip.51.255.78.213) | ns3065941.ip-51-255-78.eu | - | High
20 | [77.105.147.123](https://vuldb.com/?ip.77.105.147.123) | high-alarm.aeza.network | - | High
21 | [79.110.49.141](https://vuldb.com/?ip.79.110.49.141) | - | - | High
22 | [79.110.62.11](https://vuldb.com/?ip.79.110.62.11) | - | - | High
23 | ... | ... | ... | ...

There are 89 more IOC items available. Please use our online service to access the data.

## TTP - Tactics, Techniques, Procedures

_Tactics, techniques, and procedures_ (TTP) summarize the suspected MITRE ATT&CK techniques used by _RisePro_. This data is unique as it uses our predictive model for actor profiling.

ID | Technique | Weakness | Description | Confidence
-- | --------- | -------- | ----------- | ----------
1 | T1006 | CWE-21, CWE-22, CWE-23, CWE-425 | Pathname Traversal | High
2 | T1040 | CWE-319 | Authentication Bypass by Capture-replay | High
3 | T1055 | CWE-74 | Injection | High
4 | T1059 | CWE-88, CWE-94, CWE-1321 | Cross Site Scripting | High
5 | T1059.007 | CWE-79, CWE-80 | Cross Site Scripting | High
6 | ... | ... | ... | ...

There are 21 more TTP items available. Please use our online service to access the data.

## IOA - Indicator of Attack

These _indicators of attack_ (IOA) list the potential fragments used for technical activities like reconnaissance, exploitation, privilege escalation, and exfiltration by RisePro. This data is unique as it uses our predictive model for actor profiling.

ID | Type | Indicator | Confidence
-- | ---- | --------- | ----------
1 | File | `%SYSTEMDRIVE%\node_modules\.bin\wmic.exe` | High
2 | File | `//WEB-INF` | Medium
3 | File | `/about.php` | Medium
4 | File | `/admin/save.php` | High
5 | File | `/admin/sys_sql_query.php` | High
6 | File | `/api/baskets/{name}` | High
7 | File | `/api/download` | High
8 | File | `/api/v1/alerts` | High
9 | File | `/api/v1/terminal/sessions/?limit=1` | High
10 | File | `/be/erpc.php` | Medium
11 | File | `/bitrix/admin/ldap_server_edit.php` | High
12 | File | `/category.php` | High
13 | File | `/categorypage.php` | High
14 | File | `/cgi-bin/luci/api/wireless` | High
15 | File | `/cgi-bin/vitogate.cgi` | High
16 | File | `/company/store` | High
17 | File | `/Content/Template/root/reverse-shell.aspx` | High
18 | File | `/Controller/Ajaxfileupload.ashx` | High
19 | File | `/core/conditions/AbstractWrapper.java` | High
20 | File | `/debug/pprof` | Medium
21 | File | `/etc/passwd` | Medium
22 | File | `/fcgi/scrut_fcgi.fcgi` | High
23 | File | `/forum/away.php` | High
24 | File | `/geoserver/gwc/rest.html` | High
25 | File | `/goform/formSysCmd` | High
26 | File | `/h/` | Low
27 | File | `/HNAP1` | Low
28 | File | `/inc/jquery/uploadify/uploadify.php` | High
29 | File | `/index.php` | Medium
30 | File | `/index.php?app=main&func=passport&action=login` | High
31 | File | `/index.php?page=category_list` | High
32 | File | `/jeecg-boot/sys/common/upload` | High
33 | File | `/jobinfo/` | Medium
34 | File | `/Moosikay/order.php` | High
35 | File | `/oauth/idp/.well-known/openid-configuration` | High
36 | File | `/OA_HTML/cabo/jsps/a.jsp` | High
37 | File | `/PreviewHandler.ashx` | High
38 | File | `/proxy` | Low
39 | File | `/recipe-result` | High
40 | File | `/register.do` | Medium
41 | File | `/RPS2019Service/status.html` | High
42 | File | `/Service/ImageStationDataService.asmx` | High
43 | File | `/setting` | Medium
44 | File | `/sicweb-ajax/tmproot/` | High
45 | File | `/spip.php` | Medium
46 | File | `/student/bookdetails.php` | High
47 | ... | ... | ...

There are 408 more IOA items available (file, library, argument, input value, pattern, network port). Please use our online service to access the data.

## References

The following list contains _external sources_ which discuss the actor and the associated activities:

* https://app.any.run/tasks/057f15c5-864c-4535-b8af-70405ead5fcd
* https://app.any.run/tasks/8d068314-5e98-49d2-aac1-9756c9185d11
* https://app.any.run/tasks/66a96b13-f430-49b9-8ac2-a5c2698d61a9
* https://app.any.run/tasks/2457181d-fa22-4ef3-b171-6711c7456570
* https://app.any.run/tasks/a4b98e2a-4e47-436f-a50d-a5d1a0c520d1
* https://app.any.run/tasks/d1a96aea-a514-4f86-acd7-e9391a8ec959/
* https://search.censys.io/hosts/5.188.159.44
* https://search.censys.io/hosts/37.27.22.139
* https://search.censys.io/hosts/46.4.10.254
* https://search.censys.io/hosts/51.81.131.161
* https://search.censys.io/hosts/51.255.78.213
* https://search.censys.io/hosts/82.115.223.71
* https://search.censys.io/hosts/82.147.85.246
* https://search.censys.io/hosts/85.209.11.247
* https://search.censys.io/hosts/91.92.241.214
* https://search.censys.io/hosts/91.92.251.191
* https://search.censys.io/hosts/91.212.166.58
* https://search.censys.io/hosts/95.217.5.29
* https://search.censys.io/hosts/128.140.73.191
* https://search.censys.io/hosts/152.89.198.49
* https://search.censys.io/hosts/152.89.198.222
* https://search.censys.io/hosts/152.89.198.229
* https://search.censys.io/hosts/185.216.70.233
* https://search.censys.io/hosts/185.216.70.238
* https://search.censys.io/hosts/194.49.94.96
* https://search.censys.io/hosts/194.49.94.126
* https://search.censys.io/hosts/194.49.94.158
* https://search.censys.io/hosts/194.49.94.164
* https://search.censys.io/hosts/194.49.94.166
* https://search.censys.io/hosts/194.49.94.168
* https://search.censys.io/hosts/194.49.94.171
* https://search.censys.io/hosts/194.49.94.172
* https://search.censys.io/hosts/194.49.94.183
* https://search.censys.io/hosts/194.49.94.184
* https://search.censys.io/hosts/195.10.205.24
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
