# Sandworm - Cyber Threat Intelligence

These _indicators_ were reported, collected, and generated during the [VulDB CTI analysis](https://vuldb.com/?kb.cti) of the actor known as [Sandworm](https://vuldb.com/?actor.sandworm). The _activity monitoring_ correlates data from social media, forums, chat rooms, and darknet markets. It helps to determine associated actors, specific activities, expected intentions, emerging research, and ongoing attacks. Our unique _predictive model_ uses _big data_ to forecast activities and their characteristics.

_Live data_ and more _analysis capabilities_ are available at [https://vuldb.com/?actor.sandworm](https://vuldb.com/?actor.sandworm)

## Countries

These _countries_ are directly (e.g. origin of attacks) or indirectly (e.g. access by proxy) associated with Sandworm:

* [CN](https://vuldb.com/?country.cn)
* [US](https://vuldb.com/?country.us)
* [SC](https://vuldb.com/?country.sc)
* ...

There are 8 more country items available. Please use our online service to access the data.

## IOC - Indicator of Compromise

These _indicators of compromise_ (IOC) indicate associated network resources which are known to be part of research and attack activities of Sandworm.

ID | IP address | Hostname | Campaign | Confidence
-- | ---------- | -------- | -------- | ----------
1 | [2.56.164.52](https://vuldb.com/?ip.2.56.164.52) | exit.node | - | High
2 | [2.58.56.101](https://vuldb.com/?ip.2.58.56.101) | 2.58.56.101.powered.by.rdp.sh | - | High
3 | [5.45.73.243](https://vuldb.com/?ip.5.45.73.243) | - | - | High
4 | [5.181.80.132](https://vuldb.com/?ip.5.181.80.132) | local.charge.manufacturingservices.de | - | High
5 | [5.252.118.19](https://vuldb.com/?ip.5.252.118.19) | blocked.aeza.net | - | High
6 | [5.255.99.205](https://vuldb.com/?ip.5.255.99.205) | - | - | High
7 | [23.129.64.133](https://vuldb.com/?ip.23.129.64.133) | - | - | High
8 | [45.139.122.241](https://vuldb.com/?ip.45.139.122.241) | - | - | High
9 | [45.141.215.111](https://vuldb.com/?ip.45.141.215.111) | - | - | High
10 | [45.154.98.225](https://vuldb.com/?ip.45.154.98.225) | - | - | High
11 | [46.182.21.248](https://vuldb.com/?ip.46.182.21.248) | tor-exit-relay.anonymizing-proxy.digitalcourage.de | - | High
12 | [51.89.153.112](https://vuldb.com/?ip.51.89.153.112) | ns3145504.ip-51-89-153.eu | - | High
13 | [62.102.148.68](https://vuldb.com/?ip.62.102.148.68) | - | - | High
14 | [62.182.84.146](https://vuldb.com/?ip.62.182.84.146) | ml148.spryraven.com | - | High
15 | [77.48.28.204](https://vuldb.com/?ip.77.48.28.204) | 204.28.48.77.finalhosting.cz | - | High
16 | [77.48.28.236](https://vuldb.com/?ip.77.48.28.236) | missun.intervocalically.com | - | High
17 | [77.91.123.136](https://vuldb.com/?ip.77.91.123.136) | vm1756241.stark-industries.solutions | - | High
18 | [79.137.194.146](https://vuldb.com/?ip.79.137.194.146) | karlx1da.pwh | - | High
19 | [80.67.167.81](https://vuldb.com/?ip.80.67.167.81) | nosoignons.cust.milkywan.net | - | High
20 | [82.180.150.197](https://vuldb.com/?ip.82.180.150.197) | - | - | High
21 | [82.221.128.191](https://vuldb.com/?ip.82.221.128.191) | - | - | High
22 | ... | ... | ... | ...

There are 86 more IOC items available. Please use our online service to access the data.

## TTP - Tactics, Techniques, Procedures

_Tactics, techniques, and procedures_ (TTP) summarize the suspected MITRE ATT&CK techniques used by _Sandworm_. This data is unique as it uses our predictive model for actor profiling.

ID | Technique | Weakness | Description | Confidence
-- | --------- | -------- | ----------- | ----------
1 | T1006 | CWE-22, CWE-29 | Path Traversal | High
2 | T1055 | CWE-74 | Improper Neutralization of Data within XPath Expressions | High
3 | T1059 | CWE-88, CWE-94 | Argument Injection | High
4 | T1059.007 | CWE-79, CWE-80 | Cross Site Scripting | High
5 | T1068 | CWE-264, CWE-269, CWE-274, CWE-284 | Execution with Unnecessary Privileges | High
6 | ... | ... | ... | ...

There are 18 more TTP items available. Please use our online service to access the data.

## IOA - Indicator of Attack

These _indicators of attack_ (IOA) list the potential fragments used for technical activities like reconnaissance, exploitation, privilege escalation, and exfiltration by Sandworm. This data is unique as it uses our predictive model for actor profiling.

ID | Type | Indicator | Confidence
-- | ---- | --------- | ----------
1 | File | `/admin.php?p=/Area/index#tab=t2` | High
2 | File | `/admin/admin-profile.php` | High
3 | File | `/Admin/changepassword.php` | High
4 | File | `/admin/edit-post.php` | High
5 | File | `/admin/index.php` | High
6 | File | `/admin/normal-bwdates-reports-details.php` | High
7 | File | `/admin/tax` | Medium
8 | File | `/adminPage/conf/reload` | High
9 | File | `/adminPage/main/upload` | High
10 | File | `/adminPage/www/addOver` | High
11 | File | `/ajax.php` | Medium
12 | File | `/applications/core/modules/admin/editor/toolbar.php` | High
13 | File | `/applications/nexus/modules/front/store/store.php` | High
14 | File | `/backend/register.php` | High
15 | File | `/cgi-bin/koha/opac-MARCdetail.pl` | High
16 | File | `/cgi-bin/nas_sharing.cgi` | High
17 | File | `/chart/plot/CompassPlot.java` | High
18 | File | `/control/register_case.php` | High
19 | File | `/dayrui/Fcms/View/system_log.html` | High
20 | File | `/dayrui/My/View/main.html` | High
21 | File | `/edit-subject.php` | High
22 | File | `/Employee/edit-photo.php` | High
23 | File | `/Employee/edit-profile.php` | High
24 | File | `/fftools/ffmpeg_enc.c` | High
25 | File | `/Forms/tools_test_1` | High
26 | File | `/goform/DhcpSetSe` | High
27 | File | `/goform/Natlimit` | High
28 | File | `/goform/setUplinkInfo` | High
29 | File | `/goform/WriteFacMac` | High
30 | File | `/importhtml.php` | High
31 | ... | ... | ...

There are 259 more IOA items available (file, library, argument, input value, pattern, network port). Please use our online service to access the data.

## References

The following list contains _external sources_ which discuss the actor and the associated activities:

* https://cert.gov.ua/article/3718487
* https://cert.gov.ua/article/6123309
* https://www.mandiant.com/resources/blog/sandworm-disrupts-power-ukraine-operational-technology

## Literature

The following _articles_ explain our unique predictive cyber threat intelligence:

* [VulDB Cyber Threat Intelligence Documentation](https://vuldb.com/?kb.cti)
* [Cyber Threat Intelligence - Early Anticipation of Attacks](https://www.scip.ch/en/?labs.20201022)

## License

(c) [1997-2024](https://vuldb.com/?kb.changelog) by [vuldb.com](https://vuldb.com/?kb.about). All data on this page is shared under the license [CC BY-NC-SA 4.0](https://creativecommons.org/licenses/by-nc-sa/4.0/). Questions? Check the [FAQ](https://vuldb.com/?kb.faq), read the [documentation](https://vuldb.com/?kb) or [contact us](https://vuldb.com/?contact)!
