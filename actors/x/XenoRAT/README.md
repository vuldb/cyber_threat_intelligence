# XenoRAT - Cyber Threat Intelligence

These _indicators_ were reported, collected, and generated during the [VulDB CTI analysis](https://vuldb.com/?kb.cti) of the actor known as [XenoRAT](https://vuldb.com/?actor.xenorat). The _activity monitoring_ correlates data from social media, forums, chat rooms, and darknet markets. It helps to determine associated actors, specific activities, expected intentions, emerging research, and ongoing attacks. Our unique _predictive model_ uses _big data_ to forecast activities and their characteristics.

_Live data_ and more _analysis capabilities_ are available at [https://vuldb.com/?actor.xenorat](https://vuldb.com/?actor.xenorat)

## Countries

These _countries_ are directly (e.g. origin of attacks) or indirectly (e.g. access by proxy) associated with XenoRAT:

* [US](https://vuldb.com/?country.us)
* [LA](https://vuldb.com/?country.la)
* [RU](https://vuldb.com/?country.ru)
* ...

There are 8 more country items available. Please use our online service to access the data.

## IOC - Indicator of Compromise

These _indicators of compromise_ (IOC) indicate associated network resources which are known to be part of research and attack activities of XenoRAT.

ID | IP address | Hostname | Campaign | Confidence
-- | ---------- | -------- | -------- | ----------
1 | [2.58.85.196](https://vuldb.com/?ip.2.58.85.196) | sunucuduragi.com | - | High
2 | [5.14.110.90](https://vuldb.com/?ip.5.14.110.90) | 5-14-110-90.residential.rdsnet.ro | - | High
3 | [27.102.138.166](https://vuldb.com/?ip.27.102.138.166) | - | - | High
4 | [34.229.235.165](https://vuldb.com/?ip.34.229.235.165) | ec2-34-229-235-165.compute-1.amazonaws.com | - | Medium
5 | [45.8.22.113](https://vuldb.com/?ip.45.8.22.113) | - | - | High
6 | [45.32.188.16](https://vuldb.com/?ip.45.32.188.16) | 45.32.188.16.vultrusercontent.com | - | Medium
7 | [45.66.231.63](https://vuldb.com/?ip.45.66.231.63) | - | - | High
8 | [45.133.174.133](https://vuldb.com/?ip.45.133.174.133) | - | - | High
9 | [45.141.215.75](https://vuldb.com/?ip.45.141.215.75) | - | - | High
10 | [45.141.215.133](https://vuldb.com/?ip.45.141.215.133) | exit-pl-004.tor.0xcc01.de | - | High
11 | [49.194.29.240](https://vuldb.com/?ip.49.194.29.240) | n49-194-29-240.per2.wa.optusnet.com.au | - | High
12 | [51.38.196.118](https://vuldb.com/?ip.51.38.196.118) | server25.mentality.cloud | - | High
13 | ... | ... | ... | ...

There are 49 more IOC items available. Please use our online service to access the data.

## TTP - Tactics, Techniques, Procedures

_Tactics, techniques, and procedures_ (TTP) summarize the suspected MITRE ATT&CK techniques used by _XenoRAT_. This data is unique as it uses our predictive model for actor profiling.

ID | Technique | Weakness | Description | Confidence
-- | --------- | -------- | ----------- | ----------
1 | T1006 | CWE-21, CWE-22, CWE-24, CWE-35, CWE-36 | Path Traversal | High
2 | T1040 | CWE-319 | Authentication Bypass by Capture-replay | High
3 | T1055 | CWE-74 | Improper Neutralization of Data within XPath Expressions | High
4 | T1059 | CWE-88, CWE-94, CWE-1321 | Argument Injection | High
5 | T1059.007 | CWE-79, CWE-80 | Basic Cross Site Scripting | High
6 | ... | ... | ... | ...

There are 21 more TTP items available. Please use our online service to access the data.

## IOA - Indicator of Attack

These _indicators of attack_ (IOA) list the potential fragments used for technical activities like reconnaissance, exploitation, privilege escalation, and exfiltration by XenoRAT. This data is unique as it uses our predictive model for actor profiling.

ID | Type | Indicator | Confidence
-- | ---- | --------- | ----------
1 | File | `/aboutedit.php` | High
2 | File | `/abs.php` | Medium
3 | File | `/add_librarian.php` | High
4 | File | `/adicionar-cliente.php` | High
5 | File | `/admin/` | Low
6 | File | `/admin/?page=inventory/view_inventory&id=2` | High
7 | File | `/admin/?page=system_info/contact_info` | High
8 | File | `/admin/add-property.php` | High
9 | File | `/admin/add_product.php` | High
10 | File | `/admin/add_unit.php` | High
11 | File | `/admin/admin_product.ph` | High
12 | File | `/admin/article.php` | High
13 | File | `/admin/article.php?action=upload_cover` | High
14 | File | `/admin/articles/create` | High
15 | File | `/admin/assets/plugins/DataTables/media/unit_testing/templates/dymanic_table.php` | High
16 | File | `/admin/bwdates-reports-details.php` | High
17 | File | `/admin/category/controller.php` | High
18 | File | `/Admin/changepassword.php` | High
19 | File | `/admin/chatroom.php` | High
20 | File | `/admin/content/book` | High
21 | File | `/admin/content/editor` | High
22 | File | `/admin/create_product.php` | High
23 | File | `/admin/customermanagementframework/customers/list` | High
24 | File | `/admin/deletemanager.php` | High
25 | File | `/admin/edit-services.php` | High
26 | File | `/admin/File/fileUpload` | High
27 | File | `/admin/file_manager/export` | High
28 | File | `/admin/index.php` | High
29 | File | `/admin/info_deal.php` | High
30 | File | `/admin/link.php` | High
31 | File | `/admin/network/diag_iperf` | High
32 | File | `/admin/network/diag_traceroute` | High
33 | File | `/admin/newsletter.php` | High
34 | File | `/admin/password-recovery.php` | High
35 | File | `/admin/plugin.php` | High
36 | File | `/admin/process_category_edit.php` | High
37 | File | `/admin/profile.php` | High
38 | File | `/Admin/registration.php` | High
39 | File | `/admin/room.php` | High
40 | File | `/admin/search-booking-request.php` | High
41 | File | `/admin/search-invoices.php` | High
42 | File | `/admin/search-maid.php` | High
43 | File | `/admin/search-property.php` | High
44 | File | `/admin/store.php` | High
45 | File | `/admin/twitter.php` | High
46 | File | `/admin/user-search.php` | High
47 | File | `/admin/user.php` | High
48 | File | `/admin_topic.php?action=delall` | High
49 | File | `/ajax.php?action=save_user` | High
50 | File | `/api/cron/settings/setJob/` | High
51 | File | `/api/job/add/` | High
52 | File | `/api2/html/` | Medium
53 | File | `/app/api/controller/Site.php` | High
54 | File | `/app/checkout/delete.php` | High
55 | File | `/att_add.php` | Medium
56 | File | `/backend/admin/his_admin_add_lab_equipment.php` | High
57 | File | `/backend/admin/his_admin_register_patient.php` | High
58 | File | `/backend/doc/his_doc_update-account.php` | High
59 | ... | ... | ...

There are 519 more IOA items available (file, library, argument, input value, pattern, network port). Please use our online service to access the data.

## References

The following list contains _external sources_ which discuss the actor and the associated activities:

* https://bazaar.abuse.ch/sample/c8ed2f537f20c0085836325c810c2603be6b29251ece8c9f8e2e8873ba5b23e5/
* https://netresec.com/?b=258f641
* https://threatfox.abuse.ch
* https://urlhaus.abuse.ch/url/3522571/
* https://urlhaus.abuse.ch/url/3584881/
* https://urlhaus.abuse.ch/url/3696637/
* https://urlhaus.abuse.ch/url/3730045/
* https://www.virustotal.com/gui/file/b07dd7e831fe0a30ac139bb29d9ac836f0fb1e1034f4e00ad62f427423bc5a7f
* https://x.com/malwrhunterteam/status/1891402914024882374

## Literature

The following _articles_ explain our unique predictive cyber threat intelligence:

* [VulDB Cyber Threat Intelligence Documentation](https://vuldb.com/?kb.cti)
* [Cyber Threat Intelligence - Early Anticipation of Attacks](https://www.scip.ch/en/?labs.20201022)

## License

(c) [1997-2026](https://vuldb.com/?kb.changelog) by [vuldb.com](https://vuldb.com/?kb.about). All data on this page is shared under the license [CC BY-NC-SA 4.0](https://creativecommons.org/licenses/by-nc-sa/4.0/). Questions? Check the [FAQ](https://vuldb.com/?kb.faq), read the [documentation](https://vuldb.com/?kb) or [contact us](https://vuldb.com/?contact)!
