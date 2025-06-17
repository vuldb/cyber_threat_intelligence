# Chaos - Cyber Threat Intelligence

These _indicators_ were reported, collected, and generated during the [VulDB CTI analysis](https://vuldb.com/?kb.cti) of the actor known as [Chaos](https://vuldb.com/?actor.chaos). The _activity monitoring_ correlates data from social media, forums, chat rooms, and darknet markets. It helps to determine associated actors, specific activities, expected intentions, emerging research, and ongoing attacks. Our unique _predictive model_ uses _big data_ to forecast activities and their characteristics.

_Live data_ and more _analysis capabilities_ are available at [https://vuldb.com/?actor.chaos](https://vuldb.com/?actor.chaos)

## Countries

These _countries_ are directly (e.g. origin of attacks) or indirectly (e.g. access by proxy) associated with Chaos:

* [VN](https://vuldb.com/?country.vn)
* [US](https://vuldb.com/?country.us)

## IOC - Indicator of Compromise

These _indicators of compromise_ (IOC) indicate associated network resources which are known to be part of research and attack activities of Chaos.

ID | IP address | Hostname | Campaign | Confidence
-- | ---------- | -------- | -------- | ----------
1 | [3.120.164.69](https://vuldb.com/?ip.3.120.164.69) | chaos.fk0.name | - | High
2 | [5.180.44.53](https://vuldb.com/?ip.5.180.44.53) | 53.44-180-5.rdns.scalabledns.com | - | High
3 | [8.134.85.229](https://vuldb.com/?ip.8.134.85.229) | - | - | High
4 | [8.138.47.191](https://vuldb.com/?ip.8.138.47.191) | - | - | High
5 | [8.139.6.64](https://vuldb.com/?ip.8.139.6.64) | - | - | High
6 | [8.140.20.239](https://vuldb.com/?ip.8.140.20.239) | - | - | High
7 | [8.141.114.161](https://vuldb.com/?ip.8.141.114.161) | - | - | High
8 | [8.141.114.174](https://vuldb.com/?ip.8.141.114.174) | - | - | High
9 | [8.156.73.92](https://vuldb.com/?ip.8.156.73.92) | - | - | High
10 | [14.241.100.39](https://vuldb.com/?ip.14.241.100.39) | static.vnpt.vn | - | High
11 | [20.90.110.121](https://vuldb.com/?ip.20.90.110.121) | - | - | High
12 | [20.187.95.103](https://vuldb.com/?ip.20.187.95.103) | - | - | High
13 | [23.88.62.122](https://vuldb.com/?ip.23.88.62.122) | static.122.62.88.23.clients.your-server.de | - | High
14 | [23.224.132.58](https://vuldb.com/?ip.23.224.132.58) | - | - | High
15 | [23.225.194.65](https://vuldb.com/?ip.23.225.194.65) | - | - | High
16 | [23.226.76.122](https://vuldb.com/?ip.23.226.76.122) | we.love.servers.at.ioflood.net | - | High
17 | [34.58.136.79](https://vuldb.com/?ip.34.58.136.79) | 79.136.58.34.bc.googleusercontent.com | - | Medium
18 | [34.79.229.30](https://vuldb.com/?ip.34.79.229.30) | 30.229.79.34.bc.googleusercontent.com | - | Medium
19 | [34.141.142.28](https://vuldb.com/?ip.34.141.142.28) | 28.142.141.34.bc.googleusercontent.com | - | Medium
20 | [38.55.138.146](https://vuldb.com/?ip.38.55.138.146) | - | - | High
21 | [38.180.142.165](https://vuldb.com/?ip.38.180.142.165) | - | - | High
22 | [39.106.3.184](https://vuldb.com/?ip.39.106.3.184) | - | - | High
23 | ... | ... | ... | ...

There are 87 more IOC items available. Please use our online service to access the data.

## TTP - Tactics, Techniques, Procedures

_Tactics, techniques, and procedures_ (TTP) summarize the suspected MITRE ATT&CK techniques used by _Chaos_. This data is unique as it uses our predictive model for actor profiling.

ID | Technique | Weakness | Description | Confidence
-- | --------- | -------- | ----------- | ----------
1 | T1006 | CWE-22, CWE-24 | Path Traversal | High
2 | T1055 | CWE-74 | Improper Neutralization of Data within XPath Expressions | High
3 | T1059 | CWE-94 | Argument Injection | High
4 | T1059.007 | CWE-79, CWE-80 | Basic Cross Site Scripting | High
5 | ... | ... | ... | ...

There are 18 more TTP items available. Please use our online service to access the data.

## IOA - Indicator of Attack

These _indicators of attack_ (IOA) list the potential fragments used for technical activities like reconnaissance, exploitation, privilege escalation, and exfiltration by Chaos. This data is unique as it uses our predictive model for actor profiling.

ID | Type | Indicator | Confidence
-- | ---- | --------- | ----------
1 | File | `/admin` | Low
2 | File | `/admin/?page=categories/view_category` | High
3 | File | `/admin/?page=musics/manage_music` | High
4 | File | `/admin/?page=orders/view_order` | High
5 | File | `/Admin/add-admin.php` | High
6 | File | `/admin/add_exercises.php` | High
7 | File | `/admin/admin-profile.php` | High
8 | File | `/admin/attendance_action.php` | High
9 | File | `/admin/categories/manage_category.php` | High
10 | File | `/admin/contactus.php` | High
11 | File | `/admin/content/editor` | High
12 | File | `/admin/customermanagementframework/customers/list` | High
13 | File | `/admin/edit-products.php` | High
14 | File | `/admin/edit-subadmin.php` | High
15 | File | `/admin/index.php` | High
16 | File | `/admin/makehtml_freelist_action.php` | High
17 | File | `/admin/password-recovery.php` | High
18 | File | `/admin/read.php` | High
19 | File | `/admin/report.php` | High
20 | File | `/admin/sign/out` | High
21 | File | `/admin/students/manage.php` | High
22 | File | `/admin/students/view_student.php` | High
23 | File | `/adminpanel/admin/query/addCourseExe.php` | High
24 | File | `/ajax.php?action=delete_deductions` | High
25 | File | `/api/system/meshsync/resources/kinds` | High
26 | File | `/api/wizard/getWifiNeighbour` | High
27 | File | `/application/index/controller/Databasesource.php` | High
28 | File | `/application/index/controller/Datament.php` | High
29 | File | `/application/index/controller/File.php` | High
30 | File | `/application/index/controller/Screen.php` | High
31 | File | `/application/plugins/controller/Upload.php` | High
32 | File | `/backup.pl` | Medium
33 | File | `/bsms_ci/index.php/book` | High
34 | File | `/cardo/api` | Medium
35 | File | `/category/order/hits/copyright/46/finish/1/list/1` | High
36 | File | `/cfg` | Low
37 | File | `/cgi-bin/photocenter_mgr.cgi` | High
38 | File | `/classes/Login.php` | High
39 | File | `/classes/Master.php?f=delete_category` | High
40 | File | `/classes/master.php?f=delete_order` | High
41 | File | `/classes/Master.php?f=save_brand` | High
42 | File | `/classes/Master.php?f=save_category` | High
43 | File | `/classes/Master.php?f=update_order_status` | High
44 | File | `/com/esafenet/servlet/ajax/MultiServerAjax.java` | High
45 | File | `/com/esafenet/servlet/ajax/NetSecPolicyAjax.java` | High
46 | File | `/company/view_be_browsed/total` | High
47 | File | `/contact.php` | Medium
48 | File | `/control/addcase_stage.php` | High
49 | File | `/control/adds.php` | High
50 | File | `/control/register_case.php` | High
51 | File | `/customeredit.php` | High
52 | File | `/deletefile.php` | High
53 | File | `/employeeview.php` | High
54 | File | `/event/admin/?page=user/list` | High
55 | File | `/fos/admin/index.php?page=menu` | High
56 | File | `/front/admin/tenancyDetail.php` | High
57 | File | `/goform/aspForm` | High
58 | File | `/goform/RgTime` | High
59 | File | `/goform/SetNetControlList` | High
60 | File | `/goform/SetPptpServerCfg` | High
61 | ... | ... | ...

There are 534 more IOA items available (file, library, argument, input value, pattern, network port). Please use our online service to access the data.

## References

The following list contains _external sources_ which discuss the actor and the associated activities:

* https://cloudsecurityalliance.org/blog/2023/06/15/chaos-malware-quietly-evolves-persistence-and-evasion-techniques/
* https://community.blueliv.com/#!/s/63353bd382df413eb5359c9b
* https://search.censys.io/hosts/3.120.164.69
* https://search.censys.io/hosts/8.134.85.229
* https://search.censys.io/hosts/8.138.47.191
* https://search.censys.io/hosts/8.139.6.64
* https://search.censys.io/hosts/8.140.20.239
* https://search.censys.io/hosts/8.141.114.161
* https://search.censys.io/hosts/8.141.114.174
* https://search.censys.io/hosts/8.156.73.92
* https://search.censys.io/hosts/14.241.100.39
* https://search.censys.io/hosts/23.88.62.122
* https://search.censys.io/hosts/34.58.136.79
* https://search.censys.io/hosts/34.79.229.30
* https://search.censys.io/hosts/34.141.142.28
* https://search.censys.io/hosts/38.55.138.146
* https://search.censys.io/hosts/38.180.142.165
* https://search.censys.io/hosts/39.106.3.184
* https://search.censys.io/hosts/43.131.244.144
* https://search.censys.io/hosts/45.14.185.146
* https://search.censys.io/hosts/45.76.80.199
* https://search.censys.io/hosts/47.97.178.157
* https://search.censys.io/hosts/47.103.98.239
* https://search.censys.io/hosts/47.108.160.69
* https://search.censys.io/hosts/47.108.221.225
* https://search.censys.io/hosts/47.108.249.44
* https://search.censys.io/hosts/47.109.40.109
* https://search.censys.io/hosts/47.110.144.223
* https://search.censys.io/hosts/47.113.145.151
* https://search.censys.io/hosts/50.193.250.21
* https://search.censys.io/hosts/52.0.83.31
* https://search.censys.io/hosts/52.87.248.40
* https://search.censys.io/hosts/52.221.213.139
* https://search.censys.io/hosts/57.128.76.137
* https://search.censys.io/hosts/58.215.146.108
* https://search.censys.io/hosts/64.227.71.105
* https://search.censys.io/hosts/79.137.51.184
* https://search.censys.io/hosts/81.71.155.224
* https://search.censys.io/hosts/82.180.162.193
* https://search.censys.io/hosts/89.42.88.41
* https://search.censys.io/hosts/93.90.59.79
* https://search.censys.io/hosts/94.21.157.169
* https://search.censys.io/hosts/94.154.172.175
* https://search.censys.io/hosts/95.216.184.3
* https://search.censys.io/hosts/100.25.226.74
* https://search.censys.io/hosts/101.37.12.180
* https://search.censys.io/hosts/103.56.19.194
* https://search.censys.io/hosts/104.156.255.27
* https://search.censys.io/hosts/107.150.0.237
* https://search.censys.io/hosts/108.181.155.15
* https://search.censys.io/hosts/113.106.204.68
* https://search.censys.io/hosts/113.106.204.206
* https://search.censys.io/hosts/116.203.230.194
* https://search.censys.io/hosts/117.20.108.15
* https://search.censys.io/hosts/118.184.186.43
* https://search.censys.io/hosts/118.184.187.167
* https://search.censys.io/hosts/118.184.187.174
* https://search.censys.io/hosts/120.26.48.72
* https://search.censys.io/hosts/121.9.235.20
* https://search.censys.io/hosts/121.9.235.32
* https://search.censys.io/hosts/122.143.2.28
* https://search.censys.io/hosts/130.61.253.246
* https://search.censys.io/hosts/141.147.108.142
* https://search.censys.io/hosts/158.255.2.21
* https://search.censys.io/hosts/161.97.117.117
* https://search.censys.io/hosts/168.100.10.177
* https://search.censys.io/hosts/172.105.190.211
* https://search.censys.io/hosts/178.217.98.23
* https://search.censys.io/hosts/185.196.8.218
* https://search.censys.io/hosts/185.234.65.107
* https://search.censys.io/hosts/209.74.77.200
* https://search.censys.io/hosts/217.154.22.37
* https://threatfox.abuse.ch
* https://tracker.viriback.com/index.php?q=194.87.216.75
* https://urlscan.io/result/c5c82047-0a7e-48ba-93f3-523f04671fa0

## Literature

The following _articles_ explain our unique predictive cyber threat intelligence:

* [VulDB Cyber Threat Intelligence Documentation](https://vuldb.com/?kb.cti)
* [Cyber Threat Intelligence - Early Anticipation of Attacks](https://www.scip.ch/en/?labs.20201022)

## License

(c) [1997-2025](https://vuldb.com/?kb.changelog) by [vuldb.com](https://vuldb.com/?kb.about). All data on this page is shared under the license [CC BY-NC-SA 4.0](https://creativecommons.org/licenses/by-nc-sa/4.0/). Questions? Check the [FAQ](https://vuldb.com/?kb.faq), read the [documentation](https://vuldb.com/?kb) or [contact us](https://vuldb.com/?contact)!
