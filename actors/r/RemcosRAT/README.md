# RemcosRAT - Cyber Threat Intelligence

These _indicators_ were reported, collected, and generated during the [VulDB CTI analysis](https://vuldb.com/?kb.cti) of the actor known as [RemcosRAT](https://vuldb.com/?actor.remcosrat). The _activity monitoring_ correlates data from social media, forums, chat rooms, and darknet markets. It helps to determine associated actors, specific activities, expected intentions, emerging research, and ongoing attacks. Our unique _predictive model_ uses _big data_ to forecast activities and their characteristics.

_Live data_ and more _analysis capabilities_ are available at [https://vuldb.com/?actor.remcosrat](https://vuldb.com/?actor.remcosrat)

## Campaigns

The following _campaigns_ are known and can be associated with RemcosRAT:

* CVE-2017-0199

## Countries

These _countries_ are directly (e.g. origin of attacks) or indirectly (e.g. access by proxy) associated with RemcosRAT:

* [US](https://vuldb.com/?country.us)
* [LA](https://vuldb.com/?country.la)
* [RU](https://vuldb.com/?country.ru)
* ...

There are 13 more country items available. Please use our online service to access the data.

## IOC - Indicator of Compromise

These _indicators of compromise_ (IOC) indicate associated network resources which are known to be part of research and attack activities of RemcosRAT.

ID | IP address | Hostname | Campaign | Confidence
-- | ---------- | -------- | -------- | ----------
1 | [45.90.89.50](https://vuldb.com/?ip.45.90.89.50) | mail.xhhjxx.com | CVE-2017-0199 | High
2 | [45.141.233.196](https://vuldb.com/?ip.45.141.233.196) | - | - | High
3 | [62.60.208.170](https://vuldb.com/?ip.62.60.208.170) | - | - | High
4 | [62.60.226.165](https://vuldb.com/?ip.62.60.226.165) | - | - | High
5 | [67.21.33.181](https://vuldb.com/?ip.67.21.33.181) | - | - | High
6 | [67.217.240.53](https://vuldb.com/?ip.67.217.240.53) | ip67-217-240-53.pbiaas.com | - | High
7 | [74.208.45.193](https://vuldb.com/?ip.74.208.45.193) | ip74-208-45-193.pbiaas.com | - | High
8 | [76.76.21.22](https://vuldb.com/?ip.76.76.21.22) | - | CVE-2017-0199 | High
9 | [76.76.21.93](https://vuldb.com/?ip.76.76.21.93) | - | CVE-2017-0199 | High
10 | [76.76.21.164](https://vuldb.com/?ip.76.76.21.164) | - | CVE-2017-0199 | High
11 | [80.66.75.51](https://vuldb.com/?ip.80.66.75.51) | - | - | High
12 | [87.106.188.21](https://vuldb.com/?ip.87.106.188.21) | ip87-106-188-21.pbiaas.com | - | High
13 | [87.121.79.22](https://vuldb.com/?ip.87.121.79.22) | - | - | High
14 | [89.23.98.22](https://vuldb.com/?ip.89.23.98.22) | - | - | High
15 | [91.219.151.227](https://vuldb.com/?ip.91.219.151.227) | s1211027.smartape-vps.com | - | High
16 | [94.156.66.67](https://vuldb.com/?ip.94.156.66.67) | - | - | High
17 | [95.214.26.18](https://vuldb.com/?ip.95.214.26.18) | - | - | High
18 | [95.214.26.25](https://vuldb.com/?ip.95.214.26.25) | - | - | High
19 | [95.214.26.60](https://vuldb.com/?ip.95.214.26.60) | - | - | High
20 | ... | ... | ... | ...

There are 77 more IOC items available. Please use our online service to access the data.

## TTP - Tactics, Techniques, Procedures

_Tactics, techniques, and procedures_ (TTP) summarize the suspected MITRE ATT&CK techniques used by _RemcosRAT_. This data is unique as it uses our predictive model for actor profiling.

ID | Technique | Weakness | Description | Confidence
-- | --------- | -------- | ----------- | ----------
1 | T1006 | CWE-21, CWE-22, CWE-23, CWE-24 | Path Traversal | High
2 | T1040 | CWE-319 | Authentication Bypass by Capture-replay | High
3 | T1055 | CWE-74 | Improper Neutralization of Data within XPath Expressions | High
4 | T1059 | CWE-88, CWE-94, CWE-1321 | Argument Injection | High
5 | T1059.007 | CWE-79, CWE-80, CWE-85 | Basic Cross Site Scripting | High
6 | ... | ... | ... | ...

There are 20 more TTP items available. Please use our online service to access the data.

## IOA - Indicator of Attack

These _indicators of attack_ (IOA) list the potential fragments used for technical activities like reconnaissance, exploitation, privilege escalation, and exfiltration by RemcosRAT. This data is unique as it uses our predictive model for actor profiling.

ID | Type | Indicator | Confidence
-- | ---- | --------- | ----------
1 | File | `/+CSCOE+/logon.html` | High
2 | File | `/admin/about-us.php` | High
3 | File | `/admin/departments/manage_department.php` | High
4 | File | `/admin/file_manager/export` | High
5 | File | `/admin/index.php` | High
6 | File | `/admin/index2.html` | High
7 | File | `/admin/manage-ambulance.php` | High
8 | File | `/admin/pages/` | High
9 | File | `/admin/quote-details.php` | High
10 | File | `/admin/return_add.php` | High
11 | File | `/adminPage/conf/reload` | High
12 | File | `/admins` | Low
13 | File | `/admin_topic.php?action=delall` | High
14 | File | `/afltest/gpac/src/media_tools/av_parsers.c` | High
15 | File | `/ajax/getBasicInfo.php` | High
16 | File | `/api/admin/system/store/order/list` | High
17 | File | `/api/cron/settings/setJob/` | High
18 | File | `/api/wizard/setsyncpppoecfg` | High
19 | File | `/api2/html/` | Medium
20 | File | `/application/index/controller/Databasesource.php` | High
21 | File | `/application/index/controller/File.php` | High
22 | File | `/application/plugins/controller/Upload.php` | High
23 | File | `/apply.cgi` | Medium
24 | File | `/backend/admin/his_admin_add_lab_equipment.php` | High
25 | File | `/backend/admin/his_admin_register_patient.php` | High
26 | File | `/be/rpc.php` | Medium
27 | File | `/bitrix/admin/ldap_server_edit.php` | High
28 | File | `/cgi-bin/cstecgi.cgi` | High
29 | File | `/cgi-bin/koha/catalogue/search.pl` | High
30 | File | `/cgi-bin/login.cgi` | High
31 | File | `/cgi-bin/nas_sharing.cgi` | High
32 | File | `/cgi-bin/sysconf.cgi` | High
33 | File | `/cgi-bin/system_mgr.cgi` | High
34 | File | `/cgi-bin/wlogin.cgi` | High
35 | File | `/changeUsername.php` | High
36 | File | `/classes/Master.php` | High
37 | File | `/classes/master.php?f=delete_order` | High
38 | File | `/classes/Master.php? f=save_medicine` | High
39 | File | `/classes/SystemSettings.php?f=update_settings` | High
40 | File | `/clientdetails/admin/regester.php` | High
41 | File | `/control/register_case.php` | High
42 | File | `/core/config-revisions` | High
43 | File | `/cupseasylive/currencylist.php` | High
44 | File | `/cupseasylive/grnlist.php` | High
45 | File | `/cupseasylive/locationmodify.php` | High
46 | File | `/cupseasylive/unitofmeasurementcreate.php` | High
47 | File | `/details.php` | Medium
48 | File | `/Device/Device/GetDeviceInfoList?deviceCode=&searchField=&deviceState=` | High
49 | File | `/ext/collect/find_text.do` | High
50 | ... | ... | ...

There are 436 more IOA items available (file, library, argument, input value, pattern, network port). Please use our online service to access the data.

## References

The following list contains _external sources_ which discuss the actor and the associated activities:

* https://asec.ahnlab.com/en/52920/
* https://asec.ahnlab.com/en/65111/
* https://asec.ahnlab.com/en/66463/
* https://blog.morphisec.com/unveiling-uac-0184-the-remcos-rat-steganography-saga
* https://cert.gov.ua/article/6276567
* https://urlhaus.abuse.ch/url/3519411/
* https://urlhaus.abuse.ch/url/3522567/
* https://urlhaus.abuse.ch/url/3526358/
* https://urlhaus.abuse.ch/url/3527469/
* https://urlhaus.abuse.ch/url/3528150/
* https://urlhaus.abuse.ch/url/3544532/
* https://urlhaus.abuse.ch/url/3545199/
* https://urlhaus.abuse.ch/url/3547362/
* https://urlhaus.abuse.ch/url/3547363/
* https://urlhaus.abuse.ch/url/3547372/
* https://urlhaus.abuse.ch/url/3547842/
* https://urlhaus.abuse.ch/url/3547944/
* https://urlhaus.abuse.ch/url/3550882/
* https://urlhaus.abuse.ch/url/3551741/
* https://urlhaus.abuse.ch/url/3551831/
* https://urlhaus.abuse.ch/url/3552964/
* https://urlhaus.abuse.ch/url/3553407/
* https://urlhaus.abuse.ch/url/3553711/
* https://urlhaus.abuse.ch/url/3555585/
* https://urlhaus.abuse.ch/url/3555679/
* https://urlhaus.abuse.ch/url/3556114/
* https://urlhaus.abuse.ch/url/3556613/
* https://urlhaus.abuse.ch/url/3556628/
* https://urlhaus.abuse.ch/url/3556672/
* https://urlhaus.abuse.ch/url/3556693/
* https://urlhaus.abuse.ch/url/3556791/
* https://urlhaus.abuse.ch/url/3557923/
* https://urlhaus.abuse.ch/url/3558175/
* https://urlhaus.abuse.ch/url/3559203/
* https://urlhaus.abuse.ch/url/3559804/
* https://urlhaus.abuse.ch/url/3560170/
* https://urlhaus.abuse.ch/url/3561754/
* https://urlhaus.abuse.ch/url/3562120/
* https://urlhaus.abuse.ch/url/3562904/
* https://urlhaus.abuse.ch/url/3569157/
* https://urlhaus.abuse.ch/url/3569740/
* https://urlhaus.abuse.ch/url/3569856/
* https://urlhaus.abuse.ch/url/3569857/
* https://urlhaus.abuse.ch/url/3569858/
* https://urlhaus.abuse.ch/url/3569933/
* https://urlhaus.abuse.ch/url/3570774/
* https://urlhaus.abuse.ch/url/3571061/
* https://urlhaus.abuse.ch/url/3573572/
* https://urlhaus.abuse.ch/url/3575572/
* https://urlhaus.abuse.ch/url/3575974/
* https://urlhaus.abuse.ch/url/3578901/
* https://urlhaus.abuse.ch/url/3578902/
* https://urlhaus.abuse.ch/url/3584251/
* https://urlhaus.abuse.ch/url/3585915/
* https://urlhaus.abuse.ch/url/3602876/
* https://urlhaus.abuse.ch/url/3604574/
* https://urlhaus.abuse.ch/url/3605395/
* https://www.esentire.com/blog/from-onlydcratfans-to-remcosrat
* https://www.forcepoint.com/blog/x-labs/url-shortener-microsoft-word-remcos-rat-trojan
* https://www.malware-traffic-analysis.net/2024/09/11/index.html
* https://www.trellix.com/blogs/research/unmasking-the-hidden-threat-inside-a-sophisticated-excel-based-attack-delivering-fileless-remcos-rat/
* https://www.trustwave.com/en-us/resources/blogs/spiderlabs-blog/a-noteworthy-threat-how-cybercriminals-are-abusing-onenote-part-2/

## Literature

The following _articles_ explain our unique predictive cyber threat intelligence:

* [VulDB Cyber Threat Intelligence Documentation](https://vuldb.com/?kb.cti)
* [Cyber Threat Intelligence - Early Anticipation of Attacks](https://www.scip.ch/en/?labs.20201022)

## License

(c) [1997-2025](https://vuldb.com/?kb.changelog) by [vuldb.com](https://vuldb.com/?kb.about). All data on this page is shared under the license [CC BY-NC-SA 4.0](https://creativecommons.org/licenses/by-nc-sa/4.0/). Questions? Check the [FAQ](https://vuldb.com/?kb.faq), read the [documentation](https://vuldb.com/?kb) or [contact us](https://vuldb.com/?contact)!
