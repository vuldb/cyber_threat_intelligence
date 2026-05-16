# Microsoft Exchange - Cyber Threat Intelligence

These _indicators_ were reported, collected, and generated during the [VulDB CTI analysis](https://vuldb.com/?kb.cti) of the campaign known as _Microsoft Exchange_. The _activity monitoring_ correlates data from social media, forums, chat rooms, and darknet markets. It helps to determine associated actors, specific activities, expected intentions, emerging research, and ongoing attacks. Our unique _predictive model_ uses _big data_ to forecast activities and their characteristics.

_Live data_ and more _analysis capabilities_ are available at [https://vuldb.com/?actor](https://vuldb.com/?actor)

## Countries

These _countries_ are directly (e.g. origin of attacks) or indirectly (e.g. access by proxy) associated with Microsoft Exchange:

* [US](https://vuldb.com/?country.us)
* [CN](https://vuldb.com/?country.cn)
* [JP](https://vuldb.com/?country.jp)
* ...

There are 31 more country items available. Please use our online service to access the data.

## Actors

These _actors_ are associated with Microsoft Exchange or other actors linked to the campaign.

ID | Actor | Confidence
-- | ----- | ----------
1 | [Tortilla](https://vuldb.com/?actor.tortilla) | High
2 | [Unknown](https://vuldb.com/?actor.unknown) | High

## IOC - Indicator of Compromise

These _indicators of compromise_ (IOC) indicate associated network resources which are known to be part of research and attack activities of Microsoft Exchange.

ID | IP address | Hostname | Actor | Confidence
-- | ---------- | -------- | ----- | ----------
1 | [5.180.61.17](https://vuldb.com/?ip.5.180.61.17) | - | [Unknown](https://vuldb.com/?actor.unknown) | High
2 | [47.242.39.92](https://vuldb.com/?ip.47.242.39.92) | - | [Unknown](https://vuldb.com/?actor.unknown) | High
3 | [54.221.65.242](https://vuldb.com/?ip.54.221.65.242) | ec2-54-221-65-242.compute-1.amazonaws.com | [Tortilla](https://vuldb.com/?actor.tortilla) | Medium
4 | [61.244.94.85](https://vuldb.com/?ip.61.244.94.85) | 061244094085.ctinets.com | [Unknown](https://vuldb.com/?actor.unknown) | High
5 | ... | ... | ... | ...

There are 15 more IOC items available. Please use our online service to access the data.

## TTP - Tactics, Techniques, Procedures

_Tactics, techniques, and procedures_ (TTP) summarize the suspected MITRE ATT&CK techniques used within Microsoft Exchange. This data is unique as it uses our predictive model for actor profiling.

ID | Technique | Weakness | Description | Confidence
-- | --------- | -------- | ----------- | ----------
1 | T1006 | CWE-21, CWE-22, CWE-23, CWE-24, CWE-27, CWE-36 | Path Traversal | High
2 | T1040 | CWE-294, CWE-319 | Authentication Bypass by Capture-replay | High
3 | T1055 | CWE-74 | Improper Neutralization of Data within XPath Expressions | High
4 | T1059 | CWE-94, CWE-1321 | Argument Injection | High
5 | T1059.007 | CWE-79, CWE-80 | Basic Cross Site Scripting | High
6 | ... | ... | ... | ...

There are 22 more TTP items available. Please use our online service to access the data.

## IOA - Indicator of Attack

These _indicators of attack_ (IOA) list the potential fragments used for technical activities like reconnaissance, exploitation, privilege escalation, and exfiltration during Microsoft Exchange. This data is unique as it uses our predictive model for actor profiling.

ID | Type | Indicator | Confidence
-- | ---- | --------- | ----------
1 | File | `/about.php` | Medium
2 | File | `/addproduct.php` | High
3 | File | `/add_new_invoice.php` | High
4 | File | `/admin` | Low
5 | File | `/Admin/add-student.php` | High
6 | File | `/admin/add_user_modal.php` | High
7 | File | `/admin/admin-profile.php` | High
8 | File | `/admin/api/theme-edit/` | High
9 | File | `/admin/app/profile_crud.php` | High
10 | File | `/admin/app/service_crud.php` | High
11 | File | `/admin/article/article-add.php` | High
12 | File | `/admin/article/article-edit-run.php` | High
13 | File | `/admin/assets/plugins/DataTables/media/unit_testing/templates/dymanic_table.php` | High
14 | File | `/admin/blood/update/o-.php` | High
15 | File | `/admin/category/cate-edit-run.php` | High
16 | File | `/admin/conferences/list/` | High
17 | File | `/admin/employee/index.php` | High
18 | File | `/admin/index.php?language=en&nv=upload` | High
19 | File | `/admin/index/index.html#/admin/mall.goods/index.html` | High
20 | File | `/admin/inquiries/view_inquiry.php` | High
21 | File | `/admin/login.php` | High
22 | File | `/admin/modal_add_product.php` | High
23 | File | `/admin/new-content` | High
24 | File | `/admin/pages_account.php` | High
25 | File | `/admin/read.php?mudi=announContent` | High
26 | File | `/admin/services/manage_service.php` | High
27 | File | `/admin/sign/out` | High
28 | File | `/admin/suppliers/view_details.php` | High
29 | File | `/admin/system.php` | High
30 | File | `/admin/transactions/track_shipment.php` | High
31 | File | `/admin/upload.php` | High
32 | File | `/admin/user/manage_user.php` | High
33 | File | `/adminlogin.php` | High
34 | File | `/alarm_pi/alarmService.php` | High
35 | File | `/anony/mjpg.cgi` | High
36 | File | `/api/blade-system/menu/list?updatexml` | High
37 | File | `/api/es/admin/v3/security/user/1` | High
38 | File | `/api/ping` | Medium
39 | File | `/api/runscript` | High
40 | File | `/api/sys/login` | High
41 | File | `/api/sys/set_passwd` | High
42 | File | `/app/admin/controller/api/Plugs.php` | High
43 | File | `/asms/admin/products/manage_product.php` | High
44 | File | `/asms/products/view_product.php` | High
45 | File | `/building/backmgr/urlpage/mobileurl/configfile/jx2_config.ini` | High
46 | File | `/category.php` | High
47 | File | `/cgi-bin/nightled.cgi` | High
48 | File | `/cgi-bin/photocenter_mgr.cgi` | High
49 | File | `/cgi-bin/sysconf.cgi` | High
50 | File | `/cgi-bin/wlogin.cgi` | High
51 | File | `/changeimage.php` | High
52 | File | `/ci_hms/massage_room/edit/1` | High
53 | File | `/ci_hms/search` | High
54 | File | `/ci_ssms/index.php/orders/create` | High
55 | File | `/classes/Master.php?f=delete_category` | High
56 | File | `/classes/Master.php?f=delete_service` | High
57 | File | `/clearance/clearance.php` | High
58 | File | `/cms/category/list` | High
59 | File | `/cms/templates/templatesAssetsEditor` | High
60 | File | `/config/getuser` | High
61 | File | `/config/list` | Medium
62 | File | `/controller/company/Index.php#sendCompanyLogo` | High
63 | File | `/core/config-revisions` | High
64 | File | `/core/config-revisions/` | High
65 | File | `/dosen/data` | Medium
66 | File | `/E-mobile/App/System/File/downfile.php` | High
67 | File | `/ecommerce/admin/settings/setDiscount.php` | High
68 | File | `/edit-category.php` | High
69 | File | `/edituser.php` | High
70 | File | `/export` | Low
71 | File | `/forum/away.php` | High
72 | File | `/gena.cgi` | Medium
73 | ... | ... | ...

There are 641 more IOA items available (file, library, argument, input value, pattern, network port). Please use our online service to access the data.

## References

The following list contains _external sources_ which discuss the campaign and the associated activities:

* https://blog.talosintelligence.com/2021/11/babuk-exploits-exchange.html
* https://github.com/Cisco-Talos/IOCs/blob/main/2022/09/threat-advisory-exchange-server-vulns.txt
* https://isc.sans.edu/forums/diary/Scanning+for+Microsoft+Exchange+eDiscovery/27748/

## Literature

The following _articles_ explain our unique predictive cyber threat intelligence:

* [VulDB Cyber Threat Intelligence Documentation](https://vuldb.com/?kb.cti)
* [Cyber Threat Intelligence - Early Anticipation of Attacks](https://www.scip.ch/en/?labs.20201022)

## License

(c) [1997-2026](https://vuldb.com/?kb.changelog) by [vuldb.com](https://vuldb.com/?kb.about). All data on this page is shared under the license [CC BY-NC-SA 4.0](https://creativecommons.org/licenses/by-nc-sa/4.0/). Questions? Check the [FAQ](https://vuldb.com/?kb.faq), read the [documentation](https://vuldb.com/?kb) or [contact us](https://vuldb.com/?contact)!
