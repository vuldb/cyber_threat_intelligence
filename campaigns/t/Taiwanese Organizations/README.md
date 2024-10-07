# Taiwanese Organizations - Cyber Threat Intelligence

These _indicators_ were reported, collected, and generated during the [VulDB CTI analysis](https://vuldb.com/?kb.cti) of the campaign known as _Taiwanese Organizations_. The _activity monitoring_ correlates data from social media, forums, chat rooms, and darknet markets. It helps to determine associated actors, specific activities, expected intentions, emerging research, and ongoing attacks. Our unique _predictive model_ uses _big data_ to forecast activities and their characteristics.

_Live data_ and more _analysis capabilities_ are available at [https://vuldb.com/?actor](https://vuldb.com/?actor)

## Countries

These _countries_ are directly (e.g. origin of attacks) or indirectly (e.g. access by proxy) associated with Taiwanese Organizations:

* [CN](https://vuldb.com/?country.cn)
* [US](https://vuldb.com/?country.us)
* [ES](https://vuldb.com/?country.es)
* ...

There are 4 more country items available. Please use our online service to access the data.

## Actors

These _actors_ are associated with Taiwanese Organizations or other actors linked to the campaign.

ID | Actor | Confidence
-- | ----- | ----------
1 | [Flax Typhoon](https://vuldb.com/?actor.flax_typhoon) | High

## IOC - Indicator of Compromise

These _indicators of compromise_ (IOC) indicate associated network resources which are known to be part of research and attack activities of Taiwanese Organizations.

ID | IP address | Hostname | Actor | Confidence
-- | ---------- | -------- | ----- | ----------
1 | [39.98.208.61](https://vuldb.com/?ip.39.98.208.61) | - | [Flax Typhoon](https://vuldb.com/?actor.flax_typhoon) | High
2 | [45.88.192.118](https://vuldb.com/?ip.45.88.192.118) | Host-By.DMIT.com | [Flax Typhoon](https://vuldb.com/?actor.flax_typhoon) | High
3 | [45.195.149.224](https://vuldb.com/?ip.45.195.149.224) | - | [Flax Typhoon](https://vuldb.com/?actor.flax_typhoon) | High
4 | ... | ... | ... | ...

There are 9 more IOC items available. Please use our online service to access the data.

## TTP - Tactics, Techniques, Procedures

_Tactics, techniques, and procedures_ (TTP) summarize the suspected MITRE ATT&CK techniques used within Taiwanese Organizations. This data is unique as it uses our predictive model for actor profiling.

ID | Technique | Weakness | Description | Confidence
-- | --------- | -------- | ----------- | ----------
1 | T1006 | CWE-21, CWE-22, CWE-23, CWE-24, CWE-29, CWE-425 | Path Traversal | High
2 | T1055 | CWE-74 | Improper Neutralization of Data within XPath Expressions | High
3 | T1059 | CWE-94 | Argument Injection | High
4 | T1059.007 | CWE-79, CWE-80 | Cross Site Scripting | High
5 | ... | ... | ... | ...

There are 17 more TTP items available. Please use our online service to access the data.

## IOA - Indicator of Attack

These _indicators of attack_ (IOA) list the potential fragments used for technical activities like reconnaissance, exploitation, privilege escalation, and exfiltration during Taiwanese Organizations. This data is unique as it uses our predictive model for actor profiling.

ID | Type | Indicator | Confidence
-- | ---- | --------- | ----------
1 | File | `/act/ActDao.xml` | High
2 | File | `/admin/?setting-base.htm` | High
3 | File | `/admin/bookings/manage_booking.php` | High
4 | File | `/admin/controller/JobLogController.java` | High
5 | File | `/admin/del_service.php` | High
6 | File | `/admin/index.php` | High
7 | File | `/admin/index2.html` | High
8 | File | `/admin/list_resource_icon.php?action=delete` | High
9 | File | `/admin/read.php?mudi=announContent` | High
10 | File | `/admin/upload.php` | High
11 | File | `/adminapi/system/crud` | High
12 | File | `/analysisProject/pagingQueryData` | High
13 | File | `/api/authentication/login` | High
14 | File | `/api/blade-user/export-user` | High
15 | File | `/api/upload.php` | High
16 | File | `/api/v1/terminal/sessions/?limit=1` | High
17 | File | `/api /v3/auth` | High
18 | File | `/app/sys1.php` | High
19 | File | `/application/common.php#action_log` | High
20 | File | `/assets/php/upload.php` | High
21 | File | `/b2b-supermarket/shopping-cart` | High
22 | File | `/bin/ate` | Medium
23 | File | `/bin/rc4_crypt` | High
24 | File | `/bitrix/admin/ldap_server_edit.php` | High
25 | File | `/cgi-bin/cstecgi.cgi` | High
26 | File | `/cgi-bin/kerbynet` | High
27 | File | `/cgi-bin/login.cgi` | High
28 | File | `/cgi-bin/luci/api/switch` | High
29 | File | `/cgi-bin/luci;stok=/locale` | High
30 | File | `/cgi-bin/qcmap_auth` | High
31 | File | `/cgi-bin/wlogin.cgi` | High
32 | File | `/classes/Master.php?f=delete_category` | High
33 | File | `/classes/Master.php?f=delete_inquiry` | High
34 | File | `/classes/Master.php?f=delete_item` | High
35 | File | `/classes/Master.php?f=delete_service` | High
36 | File | `/classes/Master.php?f=save_service` | High
37 | File | `/classes/Users.php` | High
38 | File | `/classes/Users.php?f=save` | High
39 | File | `/CMD_ACCOUNT_ADMIN` | High
40 | File | `/conf/` | Low
41 | File | `/config/getuser` | High
42 | File | `/config/php.ini` | High
43 | File | `/Content/Plugins/uploader/FileChoose.html?fileUrl=/Upload/File/Pics/&parent` | High
44 | File | `/core/admin/categories.php` | High
45 | File | `/CPE` | Low
46 | File | `/cupseasylive/taxstructuredisplay.php` | High
47 | File | `/dayrui/My/View/main.html` | High
48 | File | `/dede/sys_sql_query.php` | High
49 | File | `/dus/fotos_grafiken/index.php` | High
50 | ... | ... | ...

There are 435 more IOA items available (file, library, argument, input value, pattern, network port). Please use our online service to access the data.

## References

The following list contains _external sources_ which discuss the campaign and the associated activities:

* https://www.microsoft.com/en-us/security/blog/2023/08/24/flax-typhoon-using-legitimate-software-to-quietly-access-taiwanese-organizations/

## Literature

The following _articles_ explain our unique predictive cyber threat intelligence:

* [VulDB Cyber Threat Intelligence Documentation](https://vuldb.com/?kb.cti)
* [Cyber Threat Intelligence - Early Anticipation of Attacks](https://www.scip.ch/en/?labs.20201022)

## License

(c) [1997-2024](https://vuldb.com/?kb.changelog) by [vuldb.com](https://vuldb.com/?kb.about). All data on this page is shared under the license [CC BY-NC-SA 4.0](https://creativecommons.org/licenses/by-nc-sa/4.0/). Questions? Check the [FAQ](https://vuldb.com/?kb.faq), read the [documentation](https://vuldb.com/?kb) or [contact us](https://vuldb.com/?contact)!
