# Sandworm - Cyber Threat Intelligence

These _indicators_ were reported, collected, and generated during the [VulDB CTI analysis](https://vuldb.com/?kb.cti) of the actor known as [Sandworm](https://vuldb.com/?actor.sandworm). The _activity monitoring_ correlates data from social media, forums, chat rooms, and darknet markets. It helps to determine associated actors, specific activities, expected intentions, emerging research, and ongoing attacks. Our unique _predictive model_ uses _big data_ to forecast activities and their characteristics.

_Live data_ and more _analysis capabilities_ are available at [https://vuldb.com/?actor.sandworm](https://vuldb.com/?actor.sandworm)

## Countries

These _countries_ are directly (e.g. origin of attacks) or indirectly (e.g. access by proxy) associated with Sandworm:

* [VN](https://vuldb.com/?country.vn)
* [CN](https://vuldb.com/?country.cn)
* [US](https://vuldb.com/?country.us)
* ...

There are 19 more country items available. Please use our online service to access the data.

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
8 | [27.19.56.44](https://vuldb.com/?ip.27.19.56.44) | - | - | High
9 | [45.89.106.147](https://vuldb.com/?ip.45.89.106.147) | - | - | High
10 | [45.128.232.108](https://vuldb.com/?ip.45.128.232.108) | - | - | High
11 | [45.128.232.143](https://vuldb.com/?ip.45.128.232.143) | 143.232.128.45.pfcloud.io | - | High
12 | [45.139.122.241](https://vuldb.com/?ip.45.139.122.241) | - | - | High
13 | [45.141.215.111](https://vuldb.com/?ip.45.141.215.111) | - | - | High
14 | [45.154.98.225](https://vuldb.com/?ip.45.154.98.225) | - | - | High
15 | [46.8.198.196](https://vuldb.com/?ip.46.8.198.196) | - | - | High
16 | [46.182.21.248](https://vuldb.com/?ip.46.182.21.248) | tor-exit-relay.anonymizing-proxy.digitalcourage.de | - | High
17 | [51.89.153.112](https://vuldb.com/?ip.51.89.153.112) | ns3145504.ip-51-89-153.eu | - | High
18 | [62.102.148.68](https://vuldb.com/?ip.62.102.148.68) | - | - | High
19 | [62.182.84.146](https://vuldb.com/?ip.62.182.84.146) | ml148.spryraven.com | - | High
20 | [63.79.171.112](https://vuldb.com/?ip.63.79.171.112) | - | - | High
21 | [64.112.74.166](https://vuldb.com/?ip.64.112.74.166) | - | - | High
22 | [70.62.153.174](https://vuldb.com/?ip.70.62.153.174) | syn-070-062-153-174.biz.spectrum.com | - | High
23 | [77.48.28.204](https://vuldb.com/?ip.77.48.28.204) | 204.28.48.77.finalhosting.cz | - | High
24 | [77.48.28.236](https://vuldb.com/?ip.77.48.28.236) | missun.intervocalically.com | - | High
25 | [77.64.229.43](https://vuldb.com/?ip.77.64.229.43) | 77.64.229.43.dyn.pyur.net | - | High
26 | [77.91.123.136](https://vuldb.com/?ip.77.91.123.136) | vm1756241.stark-industries.solutions | - | High
27 | [79.137.194.146](https://vuldb.com/?ip.79.137.194.146) | karlx1da.pwh | - | High
28 | [80.67.167.81](https://vuldb.com/?ip.80.67.167.81) | nosoignons.cust.milkywan.net | - | High
29 | [82.180.150.197](https://vuldb.com/?ip.82.180.150.197) | - | - | High
30 | ... | ... | ... | ...

There are 115 more IOC items available. Please use our online service to access the data.

## TTP - Tactics, Techniques, Procedures

_Tactics, techniques, and procedures_ (TTP) summarize the suspected MITRE ATT&CK techniques used by _Sandworm_. This data is unique as it uses our predictive model for actor profiling.

ID | Technique | Weakness | Description | Confidence
-- | --------- | -------- | ----------- | ----------
1 | T1006 | CWE-21, CWE-22, CWE-23, CWE-24, CWE-37, CWE-425 | Path Traversal | High
2 | T1055 | CWE-74 | Improper Neutralization of Data within XPath Expressions | High
3 | T1059 | CWE-88, CWE-94, CWE-1321 | Argument Injection | High
4 | T1059.007 | CWE-79, CWE-80 | Cross Site Scripting | High
5 | T1068 | CWE-264, CWE-269, CWE-273, CWE-284 | Execution with Unnecessary Privileges | High
6 | T1078.001 | CWE-259 | Use of Hard-coded Password | High
7 | ... | ... | ... | ...

There are 22 more TTP items available. Please use our online service to access the data.

## IOA - Indicator of Attack

These _indicators of attack_ (IOA) list the potential fragments used for technical activities like reconnaissance, exploitation, privilege escalation, and exfiltration by Sandworm. This data is unique as it uses our predictive model for actor profiling.

ID | Type | Indicator | Confidence
-- | ---- | --------- | ----------
1 | File | `/admin/add_ikev2.php` | High
2 | File | `/admin/admin-update-employee.php` | High
3 | File | `/admin/ajax.php?action=login` | High
4 | File | `/admin/category_save.php` | High
5 | File | `/admin/cmsTemplate/replace` | High
6 | File | `/admin/cmsTemplate/savePlaceMetaData` | High
7 | File | `/admin/config_time_sync.php` | High
8 | File | `/admin/emp-profile-avatar.php` | High
9 | File | `/admin/index.php?page=manage_lot` | High
10 | File | `/admin/index2.html` | High
11 | File | `/admin/list_ipAddressPolicy.php` | High
12 | File | `/admin/manage_model.php` | High
13 | File | `/admin/manage_station.php` | High
14 | File | `/admin/manage_user.php` | High
15 | File | `/admin/pages/list` | High
16 | File | `/admin/print_barcode.php` | High
17 | File | `/admin/quizquestion.php` | High
18 | File | `/admin/sql` | Medium
19 | File | `/admin/students/manage.php` | High
20 | File | `/admin/subject.php` | High
21 | File | `/admin/system.html` | High
22 | File | `/admin/ueditor?action=catchimage` | High
23 | File | `/admin/vpsApiData_deal.php?mudi=rev&nohrefStr=close` | High
24 | File | `/adminPage/conf/reload` | High
25 | File | `/ajax.php?action=login` | High
26 | File | `/api/Common/uploadFile` | High
27 | File | `/api/swaggerui/static` | High
28 | File | `/api/user` | Medium
29 | File | `/app/admin/widgets/edit.php` | High
30 | File | `/application/index/controller/Icon.php` | High
31 | File | `/AttendanceMonitoring/department/index.php` | High
32 | File | `/bin/ate` | Medium
33 | File | `/boaform/device_reset.cgi` | High
34 | File | `/branch_viewmore.php` | High
35 | File | `/cgi-bin/alexserv` | High
36 | File | `/cgi-bin/cstecgi.cgi` | High
37 | File | `/cgi-bin/cstecgi.cgi?action=save&setting` | High
38 | File | `/cgi-bin/generateForm.cgi?formID=142` | High
39 | File | `/cgi-bin/p1_ftpserver.php` | High
40 | File | `/cgi-bin/photocenter_mgr.cgi` | High
41 | File | `/cgi-bin/tosei_kikai.php` | High
42 | File | `/classes/Master.php` | High
43 | File | `/classes/Master.php?f=save_package` | High
44 | File | `/classes/SystemSettings.php?f=update_settings` | High
45 | File | `/contact.php` | Medium
46 | File | `/dcim/console-ports/add` | High
47 | File | `/dcim/power-ports/add/` | High
48 | File | `/debug/pprof` | Medium
49 | File | `/designation_viewmore.php` | High
50 | File | `/detalheIdUra` | High
51 | File | `/DXR.axd` | Medium
52 | File | `/edit-subject.php` | High
53 | File | `/edit_account.php` | High
54 | File | `/endpoint/add-user.php` | High
55 | File | `/endpoint/delete-account.php` | High
56 | File | `/esm/qs.js` | Medium
57 | File | `/etc/init.d/update_notifications.sh` | High
58 | File | `/etc/postfix/sender_login` | High
59 | ... | ... | ...

There are 512 more IOA items available (file, library, argument, input value, pattern, network port). Please use our online service to access the data.

## References

The following list contains _external sources_ which discuss the actor and the associated activities:

* https://cert.gov.ua/article/3718487
* https://cert.gov.ua/article/6123309
* https://github.com/blackorbird/APT_REPORT/blob/master/Sandworm/Clearing%20the%20Fog%20of%20War%20A%20Critical%20Analysis%20of%20Recent%20Energy%20Sector%20Attacks%20in%20Denmark%20and%20Ukraine.pdf
* https://github.com/blackorbird/APT_REPORT/blob/master/Sandworm/NCSC-MAR-Infamous-Chisel.pdf
* https://github.com/blackorbird/APT_REPORT/blob/master/Sandworm/SBU%20exposes%20russian%20intelligence%20attempts%20to%20penetrate%20Armed%20Forces'%20planning%20operations%20system.pdf
* https://github.com/blackorbird/APT_REPORT/blob/master/Sandworm/sektorcert-angrebet-mod-dansk-kritisk-infrastruktur-tlp-clear-en.pdf
* https://www.mandiant.com/resources/blog/sandworm-disrupts-power-ukraine-operational-technology

## Literature

The following _articles_ explain our unique predictive cyber threat intelligence:

* [VulDB Cyber Threat Intelligence Documentation](https://vuldb.com/?kb.cti)
* [Cyber Threat Intelligence - Early Anticipation of Attacks](https://www.scip.ch/en/?labs.20201022)

## License

(c) [1997-2024](https://vuldb.com/?kb.changelog) by [vuldb.com](https://vuldb.com/?kb.about). All data on this page is shared under the license [CC BY-NC-SA 4.0](https://creativecommons.org/licenses/by-nc-sa/4.0/). Questions? Check the [FAQ](https://vuldb.com/?kb.faq), read the [documentation](https://vuldb.com/?kb) or [contact us](https://vuldb.com/?contact)!
