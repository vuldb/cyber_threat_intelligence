# Koi Stealer - Cyber Threat Intelligence

These _indicators_ were reported, collected, and generated during the [VulDB CTI analysis](https://vuldb.com/?kb.cti) of the campaign known as _Koi Stealer_. The _activity monitoring_ correlates data from social media, forums, chat rooms, and darknet markets. It helps to determine associated actors, specific activities, expected intentions, emerging research, and ongoing attacks. Our unique _predictive model_ uses _big data_ to forecast activities and their characteristics.

_Live data_ and more _analysis capabilities_ are available at [https://vuldb.com/?actor](https://vuldb.com/?actor)

## Countries

These _countries_ are directly (e.g. origin of attacks) or indirectly (e.g. access by proxy) associated with Koi Stealer:

* [US](https://vuldb.com/?country.us)
* [CN](https://vuldb.com/?country.cn)
* [NL](https://vuldb.com/?country.nl)
* ...

There are 6 more country items available. Please use our online service to access the data.

## Actors

These _actors_ are associated with Koi Stealer or other actors linked to the campaign.

ID | Actor | Confidence
-- | ----- | ----------
1 | [Koi Loader](https://vuldb.com/?actor.koi_loader) | High
2 | [Koi Stealer](https://vuldb.com/?actor.koi_stealer) | High
3 | [Unknown](https://vuldb.com/?actor.unknown) | High

## IOC - Indicator of Compromise

These _indicators of compromise_ (IOC) indicate associated network resources which are known to be part of research and attack activities of Koi Stealer.

ID | IP address | Hostname | Actor | Confidence
-- | ---------- | -------- | ----- | ----------
1 | [45.90.58.1](https://vuldb.com/?ip.45.90.58.1) | vds1337517.hosted-by-itldc.com | [Koi Loader](https://vuldb.com/?actor.koi_loader) | High
2 | [79.124.78.109](https://vuldb.com/?ip.79.124.78.109) | - | [Unknown](https://vuldb.com/?actor.unknown) | High
3 | [79.124.78.173](https://vuldb.com/?ip.79.124.78.173) | - | [Koi Stealer](https://vuldb.com/?actor.koi_stealer) | High
4 | ... | ... | ... | ...

There are 5 more IOC items available. Please use our online service to access the data.

## TTP - Tactics, Techniques, Procedures

_Tactics, techniques, and procedures_ (TTP) summarize the suspected MITRE ATT&CK techniques used within Koi Stealer. This data is unique as it uses our predictive model for actor profiling.

ID | Technique | Weakness | Description | Confidence
-- | --------- | -------- | ----------- | ----------
1 | T1006 | CWE-22, CWE-24, CWE-28 | Path Traversal | High
2 | T1055 | CWE-74 | Improper Neutralization of Data within XPath Expressions | High
3 | T1059 | CWE-94 | Argument Injection | High
4 | T1059.007 | CWE-79, CWE-80 | Basic Cross Site Scripting | High
5 | ... | ... | ... | ...

There are 15 more TTP items available. Please use our online service to access the data.

## IOA - Indicator of Attack

These _indicators of attack_ (IOA) list the potential fragments used for technical activities like reconnaissance, exploitation, privilege escalation, and exfiltration during Koi Stealer. This data is unique as it uses our predictive model for actor profiling.

ID | Type | Indicator | Confidence
-- | ---- | --------- | ----------
1 | File | `/?page=tickets` | High
2 | File | `/abs.php` | Medium
3 | File | `/action/upload_file` | High
4 | File | `/add-students.php` | High
5 | File | `/addcategory.php` | High
6 | File | `/addcustcom.php` | High
7 | File | `/addcustind.php` | High
8 | File | `/addstock.php` | High
9 | File | `/admin/` | Low
10 | File | `/admin/?page=product/manage_product&id=2` | High
11 | File | `/admin/?page=reports` | High
12 | File | `/admin/action/new-feed.php` | High
13 | File | `/admin/action/update-deworm.php` | High
14 | File | `/admin/add_postlogin.php` | High
15 | File | `/admin/admin_cl.php?mudi=revPwd` | High
16 | File | `/admin/application-bwdates-reports-details.php` | High
17 | File | `/admin/contact-us.php` | High
18 | File | `/admin/foreigner-search.php` | High
19 | File | `/Admin/Http/Controllers/FileManagerController.php` | High
20 | File | `/admin/index.php` | High
21 | File | `/admin/index.php?r=friendly-link%2Fupdate` | High
22 | File | `/admin/invoice.php` | High
23 | File | `/admin/list_ipAddressPolicy.php` | High
24 | File | `/admin/login.php` | High
25 | File | `/admin/mod_room/controller.php?action=add` | High
26 | File | `/admin/programm//export/statistics` | High
27 | File | `/Admin/registration.php` | High
28 | File | `/admin/search-vehicle.php` | High
29 | File | `/admin/system.html` | High
30 | File | `/admin/template/update` | High
31 | File | `/adminpanel/admin/facebox_modal/updateCourse.php` | High
32 | File | `/admin_ping.htm` | High
33 | File | `/admin_route/dec_service_credits.php` | High
34 | File | `/ajax.php` | Medium
35 | File | `/ajax.php?action=delete_deductions` | High
36 | File | `/ajax.php?action=login` | High
37 | File | `/ajax.php?action=signup` | High
38 | File | `/ajax/check_medicine_name.php` | High
39 | File | `/ajax/getBasicInfo.php` | High
40 | File | `/animalsupdate.php` | High
41 | File | `/api/authentication/login` | High
42 | File | `/api/controllers/admin/app/ComboController.php` | High
43 | File | `/api/file/multiDownload` | High
44 | File | `/api/files/recipepictures/` | High
45 | File | `/api/role` | Medium
46 | File | `/api/v2/open/tablesInfo` | High
47 | File | `/api /v3/auth` | High
48 | File | `/application/index/controller/Databasesource.php` | High
49 | File | `/application/index/controller/Screen.php` | High
50 | File | `/application/pay/controller/Api.php` | High
51 | File | `/apps/login_auth.php` | High
52 | File | `/apps/reg_go.php` | High
53 | File | `/assets/php/upload.php` | High
54 | File | `/boafrm/formMapDelDevice` | High
55 | File | `/building/backmgr/urlpage/mobileurl/configfile/jx2_config.ini` | High
56 | File | `/catalog/all-products` | High
57 | File | `/cgi-bin/adm.cgi` | High
58 | File | `/cgi-bin/cstecgi.cgi` | High
59 | File | `/cgi-bin/myMusic.cgi` | High
60 | File | `/cgi-bin/nas_sharing.cgi` | High
61 | File | `/cgi-bin/p1_ftpserver.php` | High
62 | File | `/cgi-bin/photocenter_mgr.cgi` | High
63 | File | `/cgi-bin/vitogate.cgi` | High
64 | File | `/check_image_and_trigger_recovery API` | High
65 | File | `/classes/Master.php?f=delete_category` | High
66 | File | `/classes/SystemSettings.php?f=update_settings` | High
67 | File | `/classes/Users.php?f=save` | High
68 | File | `/common/info.cgi` | High
69 | File | `/controllers/add_client.php` | High
70 | ... | ... | ...

There are 617 more IOA items available (file, library, argument, input value, pattern, network port). Please use our online service to access the data.

## References

The following list contains _external sources_ which discuss the campaign and the associated activities:

* https://bazaar.abuse.ch/sample/94a3f02f1a22dad90488190c429e7d6d2d6bcd3a4bcc57b7d07cc6026e5dcb0c/
* https://bazaar.abuse.ch/sample/84577db0b164c06ef9628a94eb693150dc2101332ed526f4d431ddb56b3a7c4c/
* https://bazaar.abuse.ch/sample/f87cf2f67dbbbe69e14dc40cca510ec19034f1787b6c4167c1fae078f3fe5aed/
* https://github.com/esThreatIntelligence/iocs/blob/main/Koi/iocs_4-4-2024.txt
* https://www.malware-traffic-analysis.net/2025/01/23/index.html

## Literature

The following _articles_ explain our unique predictive cyber threat intelligence:

* [VulDB Cyber Threat Intelligence Documentation](https://vuldb.com/?kb.cti)
* [Cyber Threat Intelligence - Early Anticipation of Attacks](https://www.scip.ch/en/?labs.20201022)

## License

(c) [1997-2025](https://vuldb.com/?kb.changelog) by [vuldb.com](https://vuldb.com/?kb.about). All data on this page is shared under the license [CC BY-NC-SA 4.0](https://creativecommons.org/licenses/by-nc-sa/4.0/). Questions? Check the [FAQ](https://vuldb.com/?kb.faq), read the [documentation](https://vuldb.com/?kb) or [contact us](https://vuldb.com/?contact)!
