# DCRat - Cyber Threat Intelligence

These _indicators_ were reported, collected, and generated during the [VulDB CTI analysis](https://vuldb.com/?kb.cti) of the actor known as [DCRat](https://vuldb.com/?actor.dcrat). The _activity monitoring_ correlates data from social media, forums, chat rooms, and darknet markets. It helps to determine associated actors, specific activities, expected intentions, emerging research, and ongoing attacks. Our unique _predictive model_ uses _big data_ to forecast activities and their characteristics.

_Live data_ and more _analysis capabilities_ are available at [https://vuldb.com/?actor.dcrat](https://vuldb.com/?actor.dcrat)

## Countries

These _countries_ are directly (e.g. origin of attacks) or indirectly (e.g. access by proxy) associated with DCRat:

* [CN](https://vuldb.com/?country.cn)
* [PL](https://vuldb.com/?country.pl)
* [US](https://vuldb.com/?country.us)
* ...

There are 9 more country items available. Please use our online service to access the data.

## IOC - Indicator of Compromise

These _indicators of compromise_ (IOC) indicate associated network resources which are known to be part of research and attack activities of DCRat.

ID | IP address | Hostname | Campaign | Confidence
-- | ---------- | -------- | -------- | ----------
1 | [1.165.96.128](https://vuldb.com/?ip.1.165.96.128) | 1-165-96-128.dynamic-ip.hinet.net | - | High
2 | [1.242.139.44](https://vuldb.com/?ip.1.242.139.44) | - | - | High
3 | [5.135.83.205](https://vuldb.com/?ip.5.135.83.205) | 5-135-83-205.asyx.ru | - | High
4 | [5.178.3.191](https://vuldb.com/?ip.5.178.3.191) | - | - | High
5 | [20.223.128.97](https://vuldb.com/?ip.20.223.128.97) | - | - | High
6 | [43.243.111.229](https://vuldb.com/?ip.43.243.111.229) | - | - | High
7 | [45.77.34.211](https://vuldb.com/?ip.45.77.34.211) | 45.77.34.211.vultrusercontent.com | - | High
8 | [45.95.19.170](https://vuldb.com/?ip.45.95.19.170) | - | - | High
9 | [45.95.19.172](https://vuldb.com/?ip.45.95.19.172) | - | - | High
10 | [45.95.19.173](https://vuldb.com/?ip.45.95.19.173) | - | - | High
11 | [45.95.19.174](https://vuldb.com/?ip.45.95.19.174) | - | - | High
12 | [45.140.147.214](https://vuldb.com/?ip.45.140.147.214) | vm1329418.stark-industries.solutions | - | High
13 | [46.149.77.33](https://vuldb.com/?ip.46.149.77.33) | v1874993.hosted-by-vdsina.ru | - | High
14 | ... | ... | ... | ...

There are 52 more IOC items available. Please use our online service to access the data.

## TTP - Tactics, Techniques, Procedures

_Tactics, techniques, and procedures_ (TTP) summarize the suspected MITRE ATT&CK techniques used by _DCRat_. This data is unique as it uses our predictive model for actor profiling.

ID | Technique | Weakness | Description | Confidence
-- | --------- | -------- | ----------- | ----------
1 | T1006 | CWE-21, CWE-22, CWE-23 | Pathname Traversal | High
2 | T1040 | CWE-294, CWE-319 | Authentication Bypass by Capture-replay | High
3 | T1055 | CWE-74 | Injection | High
4 | T1059 | CWE-88, CWE-94 | Cross Site Scripting | High
5 | T1059.007 | CWE-79, CWE-80 | Cross Site Scripting | High
6 | ... | ... | ... | ...

There are 20 more TTP items available. Please use our online service to access the data.

## IOA - Indicator of Attack

These _indicators of attack_ (IOA) list the potential fragments used for technical activities like reconnaissance, exploitation, privilege escalation, and exfiltration by DCRat. This data is unique as it uses our predictive model for actor profiling.

ID | Type | Indicator | Confidence
-- | ---- | --------- | ----------
1 | File | `/acms/admin/cargo_types/manage_cargo_type.php` | High
2 | File | `/adfs/ls` | Medium
3 | File | `/admin/access` | High
4 | File | `/admin/ajax/avatar.php` | High
5 | File | `/admin/inventory/manage_stock.php` | High
6 | File | `/admin/media/upload` | High
7 | File | `/admin/options` | High
8 | File | `/admin/show.php` | High
9 | File | `/api/blade-log/api/list` | High
10 | File | `/api/RecordingList/download` | High
11 | File | `/Applications/Calculator.app/Contents/MacOS/Calculator` | High
12 | File | `/batm/app/admin/standalone/deployments` | High
13 | File | `/cgi-bin/go` | Medium
14 | File | `/cgi-bin/webproc` | High
15 | File | `/classes/conf/db.properties&config=filemanager.config.js` | High
16 | File | `/common/info.cgi` | High
17 | File | `/etc` | Low
18 | File | `/exec/` | Low
19 | File | `/forum/away.php` | High
20 | File | `/getcfg.php` | Medium
21 | File | `/HNAP1` | Low
22 | File | `/Home/GetAttachment` | High
23 | File | `/htdocs/cgibin` | High
24 | File | `/index.php?s=/admin-tpl-del&id=` | High
25 | File | `/my_photo_gallery/image.php` | High
26 | File | `/new` | Low
27 | File | `/oauth/authorized_applications.json` | High
28 | File | `/opt/tplink/EAPController/lib/eap-web-3.2.6.jar` | High
29 | File | `/patient/doctors.php` | High
30 | File | `/phpinventory/editcategory.php` | High
31 | File | `/phpinventory/edituser.php` | High
32 | File | `/probe?target` | High
33 | File | `/rk-responsive-contact-form/include/rk_user_list.php` | High
34 | File | `/root/.urcaps` | High
35 | File | `/schedules/view_schedule.php` | High
36 | File | `/see_more_details.php` | High
37 | File | `/service/upload` | High
38 | File | `/spip.php` | Medium
39 | File | `/template/edit` | High
40 | File | `/uncpath/` | Medium
41 | File | `/upload` | Low
42 | File | `/var/run/jboss-eap/` | High
43 | File | `/wp-json/wc/v3/webhooks` | High
44 | File | `4.edu.php\conn\function.php` | High
45 | File | `a1disp2.cgi/a1disp3.cgi/a1disp4.cgi` | High
46 | ... | ... | ...

There are 401 more IOA items available (file, library, argument, input value, pattern, network port). Please use our online service to access the data.

## References

The following list contains _external sources_ which discuss the actor and the associated activities:

* https://app.any.run/tasks/0c6eba9e-a4ca-4c40-beb1-a03bc903d904
* https://app.any.run/tasks/1a6872e0-d42c-4949-82ae-e8f8f96d47a7
* https://app.any.run/tasks/5f4f4268-36ec-4a62-8602-532292ddb0e0
* https://app.any.run/tasks/25cd593b-83ba-4940-b968-cbd2e8e7f7a2
* https://app.any.run/tasks/84d243ec-d740-414e-bbd1-d319ffcc0629
* https://app.any.run/tasks/cbaabb75-75e6-4441-a38f-f78948e1d925
* https://search.censys.io/hosts/1.165.96.128
* https://search.censys.io/hosts/1.242.139.44
* https://search.censys.io/hosts/5.178.3.191
* https://search.censys.io/hosts/20.223.128.97
* https://search.censys.io/hosts/43.243.111.229
* https://search.censys.io/hosts/45.77.34.211
* https://search.censys.io/hosts/45.95.19.170
* https://search.censys.io/hosts/45.95.19.172
* https://search.censys.io/hosts/45.95.19.173
* https://search.censys.io/hosts/45.95.19.174
* https://search.censys.io/hosts/64.44.166.203
* https://search.censys.io/hosts/64.176.43.239
* https://search.censys.io/hosts/77.92.154.211
* https://search.censys.io/hosts/87.121.221.220
* https://search.censys.io/hosts/89.23.96.202
* https://search.censys.io/hosts/91.227.113.154
* https://search.censys.io/hosts/95.214.26.63
* https://search.censys.io/hosts/103.144.148.219
* https://search.censys.io/hosts/103.146.78.130
* https://search.censys.io/hosts/103.170.118.35
* https://search.censys.io/hosts/103.186.108.229
* https://search.censys.io/hosts/104.219.234.167
* https://search.censys.io/hosts/109.195.94.247
* https://search.censys.io/hosts/111.229.139.47
* https://search.censys.io/hosts/112.213.98.87
* https://search.censys.io/hosts/139.180.143.50
* https://search.censys.io/hosts/142.202.242.168
* https://search.censys.io/hosts/154.53.42.53
* https://search.censys.io/hosts/179.61.251.188
* https://search.censys.io/hosts/192.99.10.207
* https://search.censys.io/hosts/193.42.32.159
* https://search.censys.io/hosts/198.23.212.148
* https://threatfox.abuse.ch
* https://tria.ge/220411-rpjwpsagg7
* https://tria.ge/220421-rkv36sbagj
* https://tria.ge/220425-r3br9agehp
* https://tria.ge/220504-qc7xbsgdgr
* https://tria.ge/220511-sbh8paddar
* https://tria.ge/220525-3tjmaaehd7
* https://tria.ge/220525-xj87asgcen
* https://tria.ge/220531-qxx8mabcg9
* https://tria.ge/220613-ttxz8shcbl
* https://tria.ge/220613-vjml7aheal
* https://tria.ge/220623-pbhelschbq
* https://tria.ge/230531-xdl5kshe47

## Literature

The following _articles_ explain our unique predictive cyber threat intelligence:

* [VulDB Cyber Threat Intelligence Documentation](https://vuldb.com/?kb.cti)
* [Cyber Threat Intelligence - Early Anticipation of Attacks](https://www.scip.ch/en/?labs.20201022)

## License

(c) [1997-2023](https://vuldb.com/?kb.changelog) by [vuldb.com](https://vuldb.com/?kb.about). All data on this page is shared under the license [CC BY-NC-SA 4.0](https://creativecommons.org/licenses/by-nc-sa/4.0/). Questions? Check the [FAQ](https://vuldb.com/?kb.faq), read the [documentation](https://vuldb.com/?kb) or [contact us](https://vuldb.com/?contact)!
