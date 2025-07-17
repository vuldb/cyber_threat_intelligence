# SolarMarker - Cyber Threat Intelligence

These _indicators_ were reported, collected, and generated during the [VulDB CTI analysis](https://vuldb.com/?kb.cti) of the actor known as [SolarMarker](https://vuldb.com/?actor.solarmarker). The _activity monitoring_ correlates data from social media, forums, chat rooms, and darknet markets. It helps to determine associated actors, specific activities, expected intentions, emerging research, and ongoing attacks. Our unique _predictive model_ uses _big data_ to forecast activities and their characteristics.

_Live data_ and more _analysis capabilities_ are available at [https://vuldb.com/?actor.solarmarker](https://vuldb.com/?actor.solarmarker)

## Countries

These _countries_ are directly (e.g. origin of attacks) or indirectly (e.g. access by proxy) associated with SolarMarker:

* [US](https://vuldb.com/?country.us)
* [CN](https://vuldb.com/?country.cn)
* [GB](https://vuldb.com/?country.gb)
* ...

There are 28 more country items available. Please use our online service to access the data.

## IOC - Indicator of Compromise

These _indicators of compromise_ (IOC) indicate associated network resources which are known to be part of research and attack activities of SolarMarker.

ID | IP address | Hostname | Campaign | Confidence
-- | ---------- | -------- | -------- | ----------
1 | [2.58.15.118](https://vuldb.com/?ip.2.58.15.118) | - | - | High
2 | [3.91.136.192](https://vuldb.com/?ip.3.91.136.192) | ec2-3-91-136-192.compute-1.amazonaws.com | - | Medium
3 | [3.224.26.65](https://vuldb.com/?ip.3.224.26.65) | ec2-3-224-26-65.compute-1.amazonaws.com | - | Medium
4 | [5.181.156.17](https://vuldb.com/?ip.5.181.156.17) | no-rdns.mivocloud.com | - | High
5 | [5.181.159.42](https://vuldb.com/?ip.5.181.159.42) | 5-181-159-42.mivocloud.com | - | High
6 | [37.120.233.92](https://vuldb.com/?ip.37.120.233.92) | no-rdns.m247.com | - | High
7 | [37.120.237.251](https://vuldb.com/?ip.37.120.237.251) | - | - | High
8 | [44.217.145.201](https://vuldb.com/?ip.44.217.145.201) | ec2-44-217-145-201.compute-1.amazonaws.com | - | Medium
9 | [45.42.201.248](https://vuldb.com/?ip.45.42.201.248) | - | - | High
10 | [46.30.188.221](https://vuldb.com/?ip.46.30.188.221) | 46.30.188.221.static.quadranet.com | - | High
11 | [50.19.154.168](https://vuldb.com/?ip.50.19.154.168) | ec2-50-19-154-168.compute-1.amazonaws.com | - | Medium
12 | [52.7.205.182](https://vuldb.com/?ip.52.7.205.182) | ec2-52-7-205-182.compute-1.amazonaws.com | - | Medium
13 | ... | ... | ... | ...

There are 50 more IOC items available. Please use our online service to access the data.

## TTP - Tactics, Techniques, Procedures

_Tactics, techniques, and procedures_ (TTP) summarize the suspected MITRE ATT&CK techniques used by _SolarMarker_. This data is unique as it uses our predictive model for actor profiling.

ID | Technique | Weakness | Description | Confidence
-- | --------- | -------- | ----------- | ----------
1 | T1006 | CWE-21, CWE-22, CWE-23, CWE-37 | Path Traversal | High
2 | T1055 | CWE-74 | Improper Neutralization of Data within XPath Expressions | High
3 | T1059 | CWE-94, CWE-1321 | Argument Injection | High
4 | T1059.007 | CWE-79, CWE-80 | Basic Cross Site Scripting | High
5 | T1068 | CWE-250, CWE-264, CWE-269, CWE-273, CWE-284 | Execution with Unnecessary Privileges | High
6 | ... | ... | ... | ...

There are 20 more TTP items available. Please use our online service to access the data.

## IOA - Indicator of Attack

These _indicators of attack_ (IOA) list the potential fragments used for technical activities like reconnaissance, exploitation, privilege escalation, and exfiltration by SolarMarker. This data is unique as it uses our predictive model for actor profiling.

ID | Type | Indicator | Confidence
-- | ---- | --------- | ----------
1 | File | `/AcceptZip.ashx` | High
2 | File | `/admin/index.PHP` | High
3 | File | `/admin/index.php` | High
4 | File | `/admin/index2.html` | High
5 | File | `/admin/network/wifi_schedule` | High
6 | File | `/admin/tag.php` | High
7 | File | `/alphaware/details.php` | High
8 | File | `/api/baskets/{name}` | High
9 | File | `/api2/html/` | Medium
10 | File | `/apiadmin/notice/add` | High
11 | File | `/apply.cgi` | Medium
12 | File | `/backend/admin/his_admin_add_lab_equipment.php` | High
13 | File | `/backend/admin/his_admin_register_patient.php` | High
14 | File | `/bitrix/admin/ldap_server_edit.php` | High
15 | File | `/calendar/minimizer/index.php` | High
16 | File | `/cgi-bin-sdb/` | High
17 | File | `/cgi-bin/cstecgi.cgi` | High
18 | File | `/cgi-bin/mainfunction.cgi/apmcfgupload` | High
19 | File | `/cgi-bin/mesh.cgi?page=upgrade` | High
20 | File | `/cgi-bin/p1_ftpserver.php` | High
21 | File | `/cgi-bin/touchlist_sync.cgi` | High
22 | File | `/classes/master.php?f=delete_order` | High
23 | File | `/debug/pprof` | Medium
24 | File | `/ecommerce/support_ticket` | High
25 | File | `/Forms/tools_test_1` | High
26 | File | `/forum/away.php` | High
27 | File | `/forum/PostPrivateMessage` | High
28 | File | `/fossasia/open-event-server/blob/development/app/api/helpers/mail.py` | High
29 | File | `/goform/RP_checkCredentialsByBBS` | High
30 | File | `/goform/ShutdownSetAdd` | High
31 | File | `/goform/wirelessAdvancedHidden` | High
32 | File | `/h/autoSaveDraft` | High
33 | File | `/h/calendar` | Medium
34 | File | `/holiday.php` | Medium
35 | File | `/home/cavesConsole` | High
36 | File | `/interlib/order/BatchOrder?cmdACT=admin_order&xsl=adminOrder_OrderList.xsl` | High
37 | File | `/lam/tmp/` | Medium
38 | File | `/librarian/bookdetails.php` | High
39 | File | `/login/index.php` | High
40 | File | `/model/update_grade.php` | High
41 | File | `/module/word_model/view/index.php` | High
42 | File | `/monitoring` | Medium
43 | File | `/nagiosxi/admin/banner_message-ajaxhelper.php` | High
44 | File | `/oauth/idp/.well-known/openid-configuration` | High
45 | File | `/OpenPublicCourse.aspx` | High
46 | File | `/out.php` | Medium
47 | File | `/param.file.tgz` | High
48 | File | `/patient/appointment.php` | High
49 | File | `/personal/updateInfo` | High
50 | File | `/php-opos/index.php` | High
51 | File | `/php/exportrecord.php` | High
52 | File | `/php/ping.php` | High
53 | File | `/plesk-site-preview/` | High
54 | File | `/pm/v2/activites` | High
55 | ... | ... | ...

There are 479 more IOA items available (file, library, argument, input value, pattern, network port). Please use our online service to access the data.

## References

The following list contains _external sources_ which discuss the actor and the associated activities:

* https://1275.ru/ioc/184/solarmarker-malware-iocs/
* https://github.com/esThreatIntelligence/iocs/blob/main/SolarMarker/iocs_4-8-2024.txt
* https://ioc.exchange/@squiblydoo@infosec.exchange/110854242511709508
* https://ioc.exchange/@squiblydoo@infosec.exchange/110952627273483306
* https://threatfox.abuse.ch
* https://tria.ge/210824-j7r4atcshe/behavioral2
* https://tria.ge/240509-r6z91sfc2z
* https://twitter.com/SquiblydooBlog/status/1498447061628379140
* https://twitter.com/SquiblydooBlog/status/1660782805687865344
* https://twitter.com/SquiblydooBlog/status/1671556028226207746
* https://www.esentire.com/blog/solarmarker-impersonates-job-employment-website-indeed-with-a-team-building-themed-lure

## Literature

The following _articles_ explain our unique predictive cyber threat intelligence:

* [VulDB Cyber Threat Intelligence Documentation](https://vuldb.com/?kb.cti)
* [Cyber Threat Intelligence - Early Anticipation of Attacks](https://www.scip.ch/en/?labs.20201022)

## License

(c) [1997-2025](https://vuldb.com/?kb.changelog) by [vuldb.com](https://vuldb.com/?kb.about). All data on this page is shared under the license [CC BY-NC-SA 4.0](https://creativecommons.org/licenses/by-nc-sa/4.0/). Questions? Check the [FAQ](https://vuldb.com/?kb.faq), read the [documentation](https://vuldb.com/?kb) or [contact us](https://vuldb.com/?contact)!
