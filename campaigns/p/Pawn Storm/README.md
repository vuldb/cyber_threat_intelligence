# Pawn Storm - Cyber Threat Intelligence

These _indicators_ were reported, collected, and generated during the [VulDB CTI analysis](https://vuldb.com/kb/cti) of the campaign known as _Pawn Storm_. The _activity monitoring_ correlates data from social media, forums, chat rooms, and darknet markets. It helps to determine associated actors, specific activities, expected intentions, emerging research, and ongoing attacks. Our unique _predictive model_ uses _big data_ to forecast activities and their characteristics.

_Live data_ and more _analysis capabilities_ are available at [https://vuldb.com/actor](https://vuldb.com/actor)

## Countries

These _countries_ are directly (e.g. origin of attacks) or indirectly (e.g. access by proxy) associated with Pawn Storm:

* [VN](https://vuldb.com/country/vn)
* [AR](https://vuldb.com/country/ar)
* [SE](https://vuldb.com/country/se)

## Actors

These _actors_ are associated with Pawn Storm or other actors linked to the campaign.

ID | Actor | Confidence
-- | ----- | ----------
1 | [APT28](https://vuldb.com/actor/apt28) | High
2 | [Pawn Storm](https://vuldb.com/actor/pawn_storm) | High

## IOC - Indicator of Compromise

These _indicators of compromise_ (IOC) indicate associated network resources which are known to be part of research and attack activities of Pawn Storm.

ID | IP address | Hostname | Actor | Confidence
-- | ---------- | -------- | ----- | ----------
1 | [14.198.168.140](https://vuldb.com/ip/14.198.168.140) | 014198168140.ctinets.com | [Pawn Storm](https://vuldb.com/actor/pawn_storm) | High
2 | [23.227.202.14](https://vuldb.com/ip/23.227.202.14) | 23-227-202-14.static.hvvc.us | [Pawn Storm](https://vuldb.com/actor/pawn_storm) | High
3 | [24.11.70.85](https://vuldb.com/ip/24.11.70.85) | c-24-11-70-85.hsd1.ut.comcast.net | [Pawn Storm](https://vuldb.com/actor/pawn_storm) | High
4 | [24.88.87.29](https://vuldb.com/ip/24.88.87.29) | syn-024-088-087-029.res.spectrum.com | [Pawn Storm](https://vuldb.com/actor/pawn_storm) | High
5 | [24.142.165.2](https://vuldb.com/ip/24.142.165.2) | 024-142-165-002.biz.spectrum.com | [Pawn Storm](https://vuldb.com/actor/pawn_storm) | High
6 | [32.143.50.222](https://vuldb.com/ip/32.143.50.222) | - | [Pawn Storm](https://vuldb.com/actor/pawn_storm) | High
7 | [42.98.5.225](https://vuldb.com/ip/42.98.5.225) | 42-98-5-225.static.netvigator.com | [Pawn Storm](https://vuldb.com/actor/pawn_storm) | High
8 | [45.83.90.11](https://vuldb.com/ip/45.83.90.11) | - | [Pawn Storm](https://vuldb.com/actor/pawn_storm) | High
9 | [45.91.95.181](https://vuldb.com/ip/45.91.95.181) | sks3.simoxap.xyz | [Pawn Storm](https://vuldb.com/actor/pawn_storm) | High
10 | [46.166.162.90](https://vuldb.com/ip/46.166.162.90) | - | [APT28](https://vuldb.com/actor/apt28) | High
11 | [46.183.217.74](https://vuldb.com/ip/46.183.217.74) | ip-217-74.dataclub.info | [APT28](https://vuldb.com/actor/apt28) | High
12 | [50.173.136.70](https://vuldb.com/ip/50.173.136.70) | c-50-173-136-70.unallocated.comcastbusiness.net | [Pawn Storm](https://vuldb.com/actor/pawn_storm) | High
13 | [61.14.68.33](https://vuldb.com/ip/61.14.68.33) | - | [Pawn Storm](https://vuldb.com/actor/pawn_storm) | High
14 | [62.4.36.126](https://vuldb.com/ip/62.4.36.126) | - | [Pawn Storm](https://vuldb.com/actor/pawn_storm) | High
15 | ... | ... | ... | ...

There are 54 more IOC items available. Please use our online service to access the data.

## TTP - Tactics, Techniques, Procedures

_Tactics, techniques, and procedures_ (TTP) summarize the suspected MITRE ATT&CK techniques used within Pawn Storm. This data is unique as it uses our predictive model for actor profiling.

ID | Technique | Weakness | Description | Confidence
-- | --------- | -------- | ----------- | ----------
1 | T1006 | CWE-22, CWE-24, CWE-35 | Path Traversal | High
2 | T1040 | CWE-294 | Authentication Bypass by Capture-replay | High
3 | T1055 | CWE-74 | Improper Neutralization of Data within XPath Expressions | High
4 | T1059 | CWE-88, CWE-94, CWE-1321 | Argument Injection | High
5 | T1059.007 | CWE-79, CWE-80 | Basic Cross Site Scripting | High
6 | ... | ... | ... | ...

There are 22 more TTP items available. Please use our online service to access the data.

## IOA - Indicator of Attack

These _indicators of attack_ (IOA) list the potential fragments used for technical activities like reconnaissance, exploitation, privilege escalation, and exfiltration during Pawn Storm. This data is unique as it uses our predictive model for actor profiling.

ID | Type | Indicator | Confidence
-- | ---- | --------- | ----------
1 | File | `/?\_route=pool/add` | High
2 | File | `/?_route=settings/users-view/` | High
3 | File | `/about.php` | Medium
4 | File | `/addcat.php` | Medium
5 | File | `/admin-cp/media` | High
6 | File | `/admin-cp/theme/editor/default` | High
7 | File | `/admin.php` | Medium
8 | File | `/admin/Add%20notice/batch-notice.php` | High
9 | File | `/admin/add-new.php` | High
10 | File | `/admin/add-subcategory.php` | High
11 | File | `/admin/add_expenses.php` | High
12 | File | `/admin/add_title.php` | High
13 | File | `/admin/admin-profile.php` | High
14 | File | `/Admin/adminlogin.php` | High
15 | File | `/admin/admin_edit_menu_action.php` | High
16 | File | `/admin/admin_feature.php` | High
17 | File | `/admin/admin_product.php` | High
18 | File | `/admin/admin_running.php` | High
19 | File | `/admin/book-details.php` | High
20 | File | `/admin/booking-bwdates-reports-details.php` | High
21 | File | `/admin/category/cate-edit-run.php` | High
22 | File | `/admin/change-image.php` | High
23 | File | `/admin/check_availability.php` | High
24 | File | `/admin/check_studid.php` | High
25 | File | `/admin/contact-us.php` | High
26 | File | `/admin/content/editor` | High
27 | File | `/admin/deletemanagerclinic.php` | High
28 | File | `/admin/doctor_action.php` | High
29 | File | `/admin/edit-subadmin.php` | High
30 | File | `/admin/extend/list.html` | High
31 | File | `/admin/index.php` | High
32 | File | `/admin/modal_add_product.php` | High
33 | File | `/admin/mod_room/controller.php?action=add` | High
34 | File | `/admin/network/diag_pinginterface` | High
35 | File | `/admin/network/diag_traceroute` | High
36 | File | `/admin/reminders/manage_reminder.php` | High
37 | File | `/admin/sensitive_word/list` | High
38 | File | `/admin/sn_package/sn_https` | High
39 | File | `/admin/tools.php` | High
40 | File | `/admin/update-image1.php` | High
41 | File | `/admin/update_fst.php` | High
42 | File | `/admin/update_s5.php` | High
43 | File | `/admin/update_s6.php` | High
44 | File | `/admin/update_s8.php` | High
45 | File | `/admin/user.php` | High
46 | File | `/adminPage/conf/reload` | High
47 | File | `/admin_link.php?action=delall` | High
48 | File | `/ajax.php?action=delete_user` | High
49 | File | `/ajax.php?action=login` | High
50 | File | `/ajax.php?action=save_establishment` | High
51 | File | `/ajax.php?action=save_user` | High
52 | File | `/api` | Low
53 | File | `/api/av/removeUnusedAttributeView` | High
54 | File | `/api/backend/ext/import-data/import-channel` | High
55 | File | `/api/blade-system/menu/list?updatexml` | High
56 | File | `/api/browserextension/UpdatePassword/` | High
57 | File | `/api/data.php` | High
58 | File | `/api/endpoint` | High
59 | File | `/api/files/extract-text` | High
60 | File | `/api/health/detailed` | High
61 | File | `/api/v1/@apostrophecms/login/reset-request` | High
62 | File | `/api/v1/attack` | High
63 | File | `/api/v1/editor/` | High
64 | File | `/app/controller/share.class.php` | High
65 | File | `/app/controller/systemMember.class.php` | High
66 | File | `/app/controller/systemRole.class.php` | High
67 | File | `/application/controller/Pelanggan.php` | High
68 | File | `/application/models/Crud_model.php` | High
69 | File | `/assetsGroupReport/fixedAssetsList.j%73p` | High
70 | File | `/AssignmentSection/submission/upload.php` | High
71 | File | `/b2c/package-information` | High
72 | File | `/backend/app/api/v1/module_common/file/controller.py` | High
73 | File | `/balance/service/list` | High
74 | File | `/Base/BaseHandler.ashx` | High
75 | File | `/bin.rar` | Medium
76 | File | `/bin/bash` | Medium
77 | File | `/bin/httpd` | Medium
78 | File | `/blog` | Low
79 | File | `/boafrm/formFilter` | High
80 | File | `/boafrm/formMapDelDevice` | High
81 | File | `/boafrm/formMapReboot` | High
82 | File | `/boafrm/formVpnConfigSetup` | High
83 | File | `/boafrm/formWlanSetup` | High
84 | File | `/booknow.php` | Medium
85 | File | `/book_car.php` | High
86 | File | `/borrowedtool.php` | High
87 | File | `/BranchManagement/ProfitAndLossReport.php` | High
88 | File | `/cart.php` | Medium
89 | File | `/catageory.php` | High
90 | File | `/cgi-bin/account_mgr.cgi` | High
91 | File | `/cgi-bin/app_mgr.cgi` | High
92 | File | `/cgi-bin/cstecgi.cgi` | High
93 | File | `/cgi-bin/dsk_mgr.cgi` | High
94 | File | `/cgi-bin/firewall.cgi` | High
95 | ... | ... | ...

There are 837 more IOA items available (file, library, argument, input value, pattern, network port). Please use our online service to access the data.

## References

The following list contains _external sources_ which discuss the campaign and the associated activities:

* https://documents.trendmicro.com/assets/txt/IOCs_Pawn_Storm_Campaign_Deploys_PRISMEX_Targets_Government_and_Critical_Infrastructure_Entities-nb92d9u.txt
* https://documents.trendmicro.com/assets/wp/wp-two-years-of-pawn-storm.pdf
* https://www.threatminer.org/report.php?q=wp-operation-pawn-storm.pdf&y=2014
* https://www.trendmicro.com/content/dam/trendmicro/global/en/research/23/l/pawn-storm-uses-brute-force-and-stealth-against-high-value-targets-/iocs-pawn-storm-uses-brute-force-and-stealth-against-high-value-targets.txt
* https://www.trendmicro.com/en_us/research/24/e/router-roulette.html

## Literature

The following _articles_ explain our unique predictive cyber threat intelligence:

* [VulDB Cyber Threat Intelligence Documentation](https://vuldb.com/kb/cti)
* [Cyber Threat Intelligence - Early Anticipation of Attacks](https://www.scip.ch/en/?labs.20201022)

## License

(c) [1997-2026](https://vuldb.com/kb/changelog) by [vuldb.com](https://vuldb.com/kb/about). All data on this page is shared under the license [CC BY-NC-SA 4.0](https://creativecommons.org/licenses/by-nc-sa/4.0/). Questions? Check the [FAQ](https://vuldb.com/kb/faq), read the [documentation](https://vuldb.com/kb) or [contact us](https://vuldb.com/contact)!
