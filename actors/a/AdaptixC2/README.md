# AdaptixC2 - Cyber Threat Intelligence

These _indicators_ were reported, collected, and generated during the [VulDB CTI analysis](https://vuldb.com/?kb.cti) of the actor known as [AdaptixC2](https://vuldb.com/?actor.adaptixc2). The _activity monitoring_ correlates data from social media, forums, chat rooms, and darknet markets. It helps to determine associated actors, specific activities, expected intentions, emerging research, and ongoing attacks. Our unique _predictive model_ uses _big data_ to forecast activities and their characteristics.

_Live data_ and more _analysis capabilities_ are available at [https://vuldb.com/?actor.adaptixc2](https://vuldb.com/?actor.adaptixc2)

## Countries

These _countries_ are directly (e.g. origin of attacks) or indirectly (e.g. access by proxy) associated with AdaptixC2:

* [US](https://vuldb.com/?country.us)
* [CN](https://vuldb.com/?country.cn)
* [RU](https://vuldb.com/?country.ru)
* ...

There are 18 more country items available. Please use our online service to access the data.

## IOC - Indicator of Compromise

These _indicators of compromise_ (IOC) indicate associated network resources which are known to be part of research and attack activities of AdaptixC2.

ID | IP address | Hostname | Campaign | Confidence
-- | ---------- | -------- | -------- | ----------
1 | [3.88.14.227](https://vuldb.com/?ip.3.88.14.227) | ec2-3-88-14-227.compute-1.amazonaws.com | - | Medium
2 | [5.188.86.168](https://vuldb.com/?ip.5.188.86.168) | - | - | High
3 | [8.137.85.34](https://vuldb.com/?ip.8.137.85.34) | - | - | High
4 | [8.138.96.41](https://vuldb.com/?ip.8.138.96.41) | - | - | High
5 | [20.17.96.220](https://vuldb.com/?ip.20.17.96.220) | - | - | High
6 | [23.227.196.13](https://vuldb.com/?ip.23.227.196.13) | 23-227-196-13.static.hvvc.us | - | High
7 | [23.227.196.19](https://vuldb.com/?ip.23.227.196.19) | 23-227-196-19.static.hvvc.us | - | High
8 | [23.227.199.37](https://vuldb.com/?ip.23.227.199.37) | 23-227-199-37.static.hvvc.us | - | High
9 | [23.227.199.61](https://vuldb.com/?ip.23.227.199.61) | 23-227-199-61.static.hvvc.us | - | High
10 | [23.227.203.128](https://vuldb.com/?ip.23.227.203.128) | 23-227-203-128.static.hvvc.us | - | High
11 | [23.227.203.190](https://vuldb.com/?ip.23.227.203.190) | 23-227-203-190.static.hvvc.us | - | High
12 | [23.227.203.191](https://vuldb.com/?ip.23.227.203.191) | 23-227-203-191.static.hvvc.us | - | High
13 | [23.227.203.193](https://vuldb.com/?ip.23.227.203.193) | 23-227-203-193.static.hvvc.us | - | High
14 | [23.227.203.205](https://vuldb.com/?ip.23.227.203.205) | 23-227-203-205.static.hvvc.us | - | High
15 | [23.227.203.246](https://vuldb.com/?ip.23.227.203.246) | 23-227-203-246.static.hvvc.us | - | High
16 | [23.227.203.248](https://vuldb.com/?ip.23.227.203.248) | 23-227-203-248.static.hvvc.us | - | High
17 | ... | ... | ... | ...

There are 66 more IOC items available. Please use our online service to access the data.

## TTP - Tactics, Techniques, Procedures

_Tactics, techniques, and procedures_ (TTP) summarize the suspected MITRE ATT&CK techniques used by _AdaptixC2_. This data is unique as it uses our predictive model for actor profiling.

ID | Technique | Weakness | Description | Confidence
-- | --------- | -------- | ----------- | ----------
1 | T1006 | CWE-21, CWE-22, CWE-24, CWE-35, CWE-425 | Path Traversal | High
2 | T1040 | CWE-294 | Authentication Bypass by Capture-replay | High
3 | T1055 | CWE-74 | Improper Neutralization of Data within XPath Expressions | High
4 | T1059 | CWE-88, CWE-94, CWE-1321 | Argument Injection | High
5 | T1059.007 | CWE-79, CWE-80 | Basic Cross Site Scripting | High
6 | ... | ... | ... | ...

There are 21 more TTP items available. Please use our online service to access the data.

## IOA - Indicator of Attack

These _indicators of attack_ (IOA) list the potential fragments used for technical activities like reconnaissance, exploitation, privilege escalation, and exfiltration by AdaptixC2. This data is unique as it uses our predictive model for actor profiling.

ID | Type | Indicator | Confidence
-- | ---- | --------- | ----------
1 | File | `/+CSCOE+/logon.html` | High
2 | File | `//proc/kcore` | Medium
3 | File | `/act/ActDao.xml` | High
4 | File | `/add-subadmin.php` | High
5 | File | `/add_new_invoice.php` | High
6 | File | `/add_user.php` | High
7 | File | `/admin/about-us.php` | High
8 | File | `/admin/action/delete-vaccine.php` | High
9 | File | `/Admin/akun_edit.php` | High
10 | File | `/admin/apply.php` | High
11 | File | `/admin/content/editor` | High
12 | File | `/admin/create-package.php` | High
13 | File | `/admin/doAdminAction.php?act=addCate` | High
14 | File | `/admin/edit-brand.php` | High
15 | File | `/admin/edit-post.php` | High
16 | File | `/admin/index2.html` | High
17 | File | `/admin/profile.php` | High
18 | File | `/Admin/Proses_Edit_Akun.php` | High
19 | File | `/admin/robot.php` | High
20 | File | `/admin/scripts/pi-hole/phpqueryads.php` | High
21 | File | `/admin/search-invoices.php` | High
22 | File | `/admin/twitter.php` | High
23 | File | `/ajax` | Low
24 | File | `/api/admin/settings` | High
25 | File | `/api/swaggerui/static` | High
26 | File | `/api/wechat/app_auth` | High
27 | File | `/app/controller/Api.php` | High
28 | File | `/app/index/controller/Common.php` | High
29 | File | `/application/index/controller/Service.php` | High
30 | File | `/applications/core/modules/admin/editor/toolbar.php` | High
31 | File | `/Applications/Google\ Drive.app/Contents/MacOS` | High
32 | File | `/applications/nexus/modules/front/store/store.php` | High
33 | File | `/backend/doc/his_doc_update-account.php` | High
34 | File | `/bitrix/admin/ldap_server_edit.php` | High
35 | File | `/cgi-bin/apkg_mgr.cgi` | High
36 | File | `/cgi-bin/cstecgi.cgi` | High
37 | File | `/cgi-bin/downloadFile.cgi` | High
38 | File | `/cgi-bin/nas_sharing.cgi` | High
39 | File | `/cgi-bin/photocenter_mgr.cgi` | High
40 | File | `/classes/Master.php` | High
41 | File | `/classes/Master.php?f=delete_record` | High
42 | File | `/classes/Master.php?f=save_category` | High
43 | File | `/classes/SystemSettings.php?f=update_settings` | High
44 | File | `/classes/Users.php?f=save` | High
45 | File | `/customnode/install` | High
46 | File | `/deal/{note_id}/note` | High
47 | File | `/detailed.php` | High
48 | File | `/dtale/chart-data/1` | High
49 | File | `/etc/shadow.sample` | High
50 | File | `/fftools/ffmpeg_enc.c` | High
51 | ... | ... | ...

There are 445 more IOA items available (file, library, argument, input value, pattern, network port). Please use our online service to access the data.

## References

The following list contains _external sources_ which discuss the actor and the associated activities:

* https://github.com/stamparm/maltrail/blob/master/trails/static/malicious/adaptix_c2.txt
* https://search.censys.io/hosts/5.188.86.168
* https://search.censys.io/hosts/8.137.85.34
* https://search.censys.io/hosts/20.17.96.220
* https://search.censys.io/hosts/23.227.196.13
* https://search.censys.io/hosts/23.227.196.19
* https://search.censys.io/hosts/23.227.199.37
* https://search.censys.io/hosts/23.227.199.61
* https://search.censys.io/hosts/23.227.203.128
* https://search.censys.io/hosts/23.227.203.190
* https://search.censys.io/hosts/23.227.203.191
* https://search.censys.io/hosts/23.227.203.193
* https://search.censys.io/hosts/23.227.203.205
* https://search.censys.io/hosts/23.227.203.246
* https://search.censys.io/hosts/23.227.203.248
* https://search.censys.io/hosts/38.132.122.141
* https://search.censys.io/hosts/38.132.122.145
* https://search.censys.io/hosts/38.132.122.161
* https://search.censys.io/hosts/38.132.122.198
* https://search.censys.io/hosts/39.108.79.95
* https://search.censys.io/hosts/43.156.15.56
* https://search.censys.io/hosts/43.255.159.28
* https://search.censys.io/hosts/45.129.0.102
* https://search.censys.io/hosts/49.13.163.25
* https://search.censys.io/hosts/62.113.59.107
* https://search.censys.io/hosts/62.141.44.37
* https://search.censys.io/hosts/86.106.85.206
* https://search.censys.io/hosts/89.41.26.181
* https://search.censys.io/hosts/89.41.26.187
* https://search.censys.io/hosts/89.45.4.74
* https://search.censys.io/hosts/94.198.52.210
* https://search.censys.io/hosts/94.232.249.166
* https://search.censys.io/hosts/101.42.100.236
* https://search.censys.io/hosts/103.171.35.150
* https://search.censys.io/hosts/107.158.128.78
* https://search.censys.io/hosts/113.45.177.81
* https://search.censys.io/hosts/117.72.118.156
* https://search.censys.io/hosts/121.41.113.184
* https://search.censys.io/hosts/123.249.103.174
* https://search.censys.io/hosts/139.59.113.130
* https://search.censys.io/hosts/141.164.44.177
* https://search.censys.io/hosts/144.172.103.74
* https://search.censys.io/hosts/146.70.41.141
* https://search.censys.io/hosts/146.70.41.167
* https://search.censys.io/hosts/146.70.44.174
* https://search.censys.io/hosts/146.70.87.64
* https://search.censys.io/hosts/146.70.87.96
* https://search.censys.io/hosts/146.70.87.237
* https://search.censys.io/hosts/154.91.180.29
* https://search.censys.io/hosts/166.88.61.58
* https://search.censys.io/hosts/167.88.168.160
* https://search.censys.io/hosts/179.43.186.234
* https://search.censys.io/hosts/185.208.158.168
* https://search.censys.io/hosts/193.5.65.114
* https://search.censys.io/hosts/196.251.118.249
* https://search.censys.io/hosts/204.152.192.54
* https://search.censys.io/hosts/217.28.130.34
* https://search.censys.io/hosts/217.28.130.37
* https://search.censys.io/hosts/217.28.130.61
* https://search.censys.io/hosts/217.28.130.82
* https://threatfox.abuse.ch
* https://www.shodan.io/host/43.156.64.185#4444
* https://www.shodan.io/host/45.88.109.34#123
* https://www.shodan.io/host/45.144.221.24#1337
* https://www.shodan.io/host/77.73.39.176#4444
* https://www.shodan.io/host/107.154.172.8#16010
* https://www.shodan.io/host/110.41.44.100#4433
* https://www.shodan.io/host/154.223.21.252#4444

## Literature

The following _articles_ explain our unique predictive cyber threat intelligence:

* [VulDB Cyber Threat Intelligence Documentation](https://vuldb.com/?kb.cti)
* [Cyber Threat Intelligence - Early Anticipation of Attacks](https://www.scip.ch/en/?labs.20201022)

## License

(c) [1997-2025](https://vuldb.com/?kb.changelog) by [vuldb.com](https://vuldb.com/?kb.about). All data on this page is shared under the license [CC BY-NC-SA 4.0](https://creativecommons.org/licenses/by-nc-sa/4.0/). Questions? Check the [FAQ](https://vuldb.com/?kb.faq), read the [documentation](https://vuldb.com/?kb) or [contact us](https://vuldb.com/?contact)!
