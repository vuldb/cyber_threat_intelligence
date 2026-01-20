# GrayBravo - Cyber Threat Intelligence

These _indicators_ were reported, collected, and generated during the [VulDB CTI analysis](https://vuldb.com/?kb.cti) of the actor known as [GrayBravo](https://vuldb.com/?actor.graybravo). The _activity monitoring_ correlates data from social media, forums, chat rooms, and darknet markets. It helps to determine associated actors, specific activities, expected intentions, emerging research, and ongoing attacks. Our unique _predictive model_ uses _big data_ to forecast activities and their characteristics.

_Live data_ and more _analysis capabilities_ are available at [https://vuldb.com/?actor.graybravo](https://vuldb.com/?actor.graybravo)

## Campaigns

The following _campaigns_ are known and can be associated with GrayBravo:

* CastleRAT / CastleLoader

## Countries

These _countries_ are directly (e.g. origin of attacks) or indirectly (e.g. access by proxy) associated with GrayBravo:

* [US](https://vuldb.com/?country.us)
* [CN](https://vuldb.com/?country.cn)
* [RU](https://vuldb.com/?country.ru)
* ...

There are 13 more country items available. Please use our online service to access the data.

## IOC - Indicator of Compromise

These _indicators of compromise_ (IOC) indicate associated network resources which are known to be part of research and attack activities of GrayBravo.

ID | IP address | Hostname | Campaign | Confidence
-- | ---------- | -------- | -------- | ----------
1 | [5.35.44.176](https://vuldb.com/?ip.5.35.44.176) | v348180.hosted-by-vdsina.com | CastleRAT / CastleLoader | High
2 | [31.58.50.160](https://vuldb.com/?ip.31.58.50.160) | - | CastleRAT / CastleLoader | High
3 | [31.58.87.132](https://vuldb.com/?ip.31.58.87.132) | - | CastleRAT / CastleLoader | High
4 | [34.72.90.40](https://vuldb.com/?ip.34.72.90.40) | 40.90.72.34.bc.googleusercontent.com | CastleRAT / CastleLoader | Medium
5 | [45.11.180.174](https://vuldb.com/?ip.45.11.180.174) | - | CastleRAT / CastleLoader | High
6 | [45.11.180.198](https://vuldb.com/?ip.45.11.180.198) | - | CastleRAT / CastleLoader | High
7 | [45.11.181.59](https://vuldb.com/?ip.45.11.181.59) | - | CastleRAT / CastleLoader | High
8 | [45.11.183.19](https://vuldb.com/?ip.45.11.183.19) | - | CastleRAT / CastleLoader | High
9 | [45.11.183.45](https://vuldb.com/?ip.45.11.183.45) | - | CastleRAT / CastleLoader | High
10 | [45.11.183.165](https://vuldb.com/?ip.45.11.183.165) | - | CastleRAT / CastleLoader | High
11 | [45.32.69.11](https://vuldb.com/?ip.45.32.69.11) | 45.32.69.11.vultrusercontent.com | CastleRAT / CastleLoader | Medium
12 | [45.61.136.81](https://vuldb.com/?ip.45.61.136.81) | - | CastleRAT / CastleLoader | High
13 | [45.134.26.41](https://vuldb.com/?ip.45.134.26.41) | - | CastleRAT / CastleLoader | High
14 | [45.135.232.149](https://vuldb.com/?ip.45.135.232.149) | - | CastleRAT / CastleLoader | High
15 | [45.144.53.62](https://vuldb.com/?ip.45.144.53.62) | 137397.h2.nexus | CastleRAT / CastleLoader | High
16 | [45.155.249.121](https://vuldb.com/?ip.45.155.249.121) | - | CastleRAT / CastleLoader | High
17 | [46.28.67.22](https://vuldb.com/?ip.46.28.67.22) | vds1514425.hosted-by-itldc.com | CastleRAT / CastleLoader | High
18 | ... | ... | ... | ...

There are 68 more IOC items available. Please use our online service to access the data.

## TTP - Tactics, Techniques, Procedures

_Tactics, techniques, and procedures_ (TTP) summarize the suspected MITRE ATT&CK techniques used by _GrayBravo_. This data is unique as it uses our predictive model for actor profiling.

ID | Technique | Weakness | Description | Confidence
-- | --------- | -------- | ----------- | ----------
1 | T1006 | CWE-21, CWE-22 | Path Traversal | High
2 | T1055 | CWE-74 | Improper Neutralization of Data within XPath Expressions | High
3 | T1059 | CWE-88, CWE-94 | Argument Injection | High
4 | T1059.007 | CWE-79, CWE-80 | Basic Cross Site Scripting | High
5 | T1068 | CWE-264, CWE-269, CWE-284 | Execution with Unnecessary Privileges | High
6 | ... | ... | ... | ...

There are 19 more TTP items available. Please use our online service to access the data.

## IOA - Indicator of Attack

These _indicators of attack_ (IOA) list the potential fragments used for technical activities like reconnaissance, exploitation, privilege escalation, and exfiltration by GrayBravo. This data is unique as it uses our predictive model for actor profiling.

ID | Type | Indicator | Confidence
-- | ---- | --------- | ----------
1 | File | `/admin/aboutus.php` | High
2 | File | `/Admin/adminlogin.php` | High
3 | File | `/admin/ajax.php?action=save_settings` | High
4 | File | `/admin/delete_pending.php` | High
5 | File | `/admin/edit-admin.php` | High
6 | File | `/admin/edit_subject.php` | High
7 | File | `/admin/execedituser.php` | High
8 | File | `/admin/ipAddPost.php` | High
9 | File | `/admin/login` | Medium
10 | File | `/admin/nav/update` | High
11 | File | `/admin/search-pass.php` | High
12 | File | `/api/v1/admin/` | High
13 | File | `/backend/admin/his_admin_add_lab_equipment.php` | High
14 | File | `/cgi-bin/adm.cgi` | High
15 | File | `/cgi-bin/downloadFile.cgi` | High
16 | File | `/cgi-bin/widget_api.cgi` | High
17 | File | `/classes/Master.php` | High
18 | File | `/cms/category/list` | High
19 | File | `/CoinExchange_CryptoExchange_Java-master/00_framework/core/src/main/java/com/bizzan/bitrade/util/UploadFileUtil.java` | High
20 | File | `/courses/` | Medium
21 | File | `/device.rsp?opt=sys&cmd=___S_O_S_T_R_E_A_MAX___` | High
22 | File | `/Digital-Infrastructure-9.6.7/y9-digitalbase-webapp/y9-module-filemanager/risenet-y9boot-webapp-filemanager/src/main/java/net/risesoft/y9public/controller/Y9FileController.java` | High
23 | File | `/edit-photo.php` | High
24 | File | `/filex/read-raw` | High
25 | File | `/forum/away.php` | High
26 | File | `/goform/aspForm` | High
27 | File | `/goform/GetIPTV` | High
28 | File | `/goform/modules` | High
29 | File | `/goform/WriteFacMac` | High
30 | ... | ... | ...

There are 257 more IOA items available (file, library, argument, input value, pattern, network port). Please use our online service to access the data.

## References

The following list contains _external sources_ which discuss the actor and the associated activities:

* https://www.recordedfuture.com/research/graybravos-castleloader-activity-clusters-target-multiple-industries

## Literature

The following _articles_ explain our unique predictive cyber threat intelligence:

* [VulDB Cyber Threat Intelligence Documentation](https://vuldb.com/?kb.cti)
* [Cyber Threat Intelligence - Early Anticipation of Attacks](https://www.scip.ch/en/?labs.20201022)

## License

(c) [1997-2025](https://vuldb.com/?kb.changelog) by [vuldb.com](https://vuldb.com/?kb.about). All data on this page is shared under the license [CC BY-NC-SA 4.0](https://creativecommons.org/licenses/by-nc-sa/4.0/). Questions? Check the [FAQ](https://vuldb.com/?kb.faq), read the [documentation](https://vuldb.com/?kb) or [contact us](https://vuldb.com/?contact)!
