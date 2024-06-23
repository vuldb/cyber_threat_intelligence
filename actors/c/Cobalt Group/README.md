# Cobalt Group - Cyber Threat Intelligence

These _indicators_ were reported, collected, and generated during the [VulDB CTI analysis](https://vuldb.com/?kb.cti) of the actor known as [Cobalt Group](https://vuldb.com/?actor.cobalt_group). The _activity monitoring_ correlates data from social media, forums, chat rooms, and darknet markets. It helps to determine associated actors, specific activities, expected intentions, emerging research, and ongoing attacks. Our unique _predictive model_ uses _big data_ to forecast activities and their characteristics.

_Live data_ and more _analysis capabilities_ are available at [https://vuldb.com/?actor.cobalt_group](https://vuldb.com/?actor.cobalt_group)

## Countries

These _countries_ are directly (e.g. origin of attacks) or indirectly (e.g. access by proxy) associated with Cobalt Group:

* [GB](https://vuldb.com/?country.gb)
* [RU](https://vuldb.com/?country.ru)
* [PL](https://vuldb.com/?country.pl)
* ...

There are 11 more country items available. Please use our online service to access the data.

## IOC - Indicator of Compromise

These _indicators of compromise_ (IOC) indicate associated network resources which are known to be part of research and attack activities of Cobalt Group.

ID | IP address | Hostname | Campaign | Confidence
-- | ---------- | -------- | -------- | ----------
1 | [5.45.66.161](https://vuldb.com/?ip.5.45.66.161) | - | - | High
2 | [5.135.237.216](https://vuldb.com/?ip.5.135.237.216) | - | - | High
3 | [23.152.0.210](https://vuldb.com/?ip.23.152.0.210) | nordns.crowncloud.net | - | High
4 | [23.249.164.26](https://vuldb.com/?ip.23.249.164.26) | - | - | High
5 | ... | ... | ... | ...

There are 16 more IOC items available. Please use our online service to access the data.

## TTP - Tactics, Techniques, Procedures

_Tactics, techniques, and procedures_ (TTP) summarize the suspected MITRE ATT&CK techniques used by _Cobalt Group_. This data is unique as it uses our predictive model for actor profiling.

ID | Technique | Weakness | Description | Confidence
-- | --------- | -------- | ----------- | ----------
1 | T1006 | CWE-21, CWE-22, CWE-24, CWE-36, CWE-425 | Path Traversal | High
2 | T1055 | CWE-74 | Improper Neutralization of Data within XPath Expressions | High
3 | T1059 | CWE-94, CWE-1321 | Argument Injection | High
4 | T1059.007 | CWE-79, CWE-80 | Cross Site Scripting | High
5 | T1068 | CWE-264, CWE-269, CWE-284 | Execution with Unnecessary Privileges | High
6 | ... | ... | ... | ...

There are 21 more TTP items available. Please use our online service to access the data.

## IOA - Indicator of Attack

These _indicators of attack_ (IOA) list the potential fragments used for technical activities like reconnaissance, exploitation, privilege escalation, and exfiltration by Cobalt Group. This data is unique as it uses our predictive model for actor profiling.

ID | Type | Indicator | Confidence
-- | ---- | --------- | ----------
1 | File | `.github/workflows/combine-prs.yml` | High
2 | File | `/academy/home/courses` | High
3 | File | `/action/import_https_cert_file/` | High
4 | File | `/admin/action/new-feed.php` | High
5 | File | `/admin/admin_login_process.php` | High
6 | File | `/admin/book_add.php` | High
7 | File | `/admin/borrow_add.php` | High
8 | File | `/admin/cms_admin.php` | High
9 | File | `/admin/conferences/list/` | High
10 | File | `/admin/contacts/organizations/edit/2` | High
11 | File | `/admin/course.php` | High
12 | File | `/admin/curriculum/view_curriculum.php` | High
13 | File | `/Admin/dashboard.php` | High
14 | File | `/admin/edit-accepted-appointment.php` | High
15 | File | `/admin/edit.php` | High
16 | File | `/admin/edit_category.php` | High
17 | File | `/admin/edit_subject.php` | High
18 | File | `/admin/index.php` | High
19 | File | `/admin/index.php?act=reset_admin_psw` | High
20 | File | `/admin/index3.php` | High
21 | File | `/admin/list_addr_fwresource_ip.php` | High
22 | File | `/admin/manage-users.php` | High
23 | File | `/admin/modal_add_product.php` | High
24 | File | `/Admin/News.php` | High
25 | File | `/admin/order.php` | High
26 | File | `/admin/pages/edit_chicken.php` | High
27 | File | `/admin/pages/subjects.php` | High
28 | File | `/admin/sales/view_details.php` | High
29 | File | `/admin/service.php` | High
30 | File | `/admin/students/manage_academic.php` | High
31 | File | `/admin/test_status.php` | High
32 | File | `/admin/theme-edit.php` | High
33 | File | `/admin/view_sendlist.php` | High
34 | File | `/adminapi/system/crud` | High
35 | File | `/adminapi/system/file/openfile` | High
36 | File | `/ample/app/ajax/member_data.php` | High
37 | File | `/api/wechat/app_auth` | High
38 | File | `/app/index/controller/Common.php` | High
39 | File | `/application/index/common.php` | High
40 | File | `/application/index/controller/Databasesource.php` | High
41 | File | `/application/index/controller/Icon.php` | High
42 | File | `/application/pay/controller/Api.php` | High
43 | File | `/asms/classes/Master.php?f=delete_img` | High
44 | File | `/assets/php/upload.php` | High
45 | File | `/auth/user/all.api` | High
46 | File | `/blog` | Low
47 | File | `/cgi-bin/cstecgi.cgi` | High
48 | File | `/cgi-bin/vitogate.cgi` | High
49 | File | `/classes/Master.php` | High
50 | File | `/classes/Master.php?f=save_inquiry` | High
51 | File | `/classes/Master.php?f=save_item` | High
52 | File | `/classes/Users.php` | High
53 | File | `/classes/Users.php?f=save` | High
54 | File | `/cms/notify` | Medium
55 | File | `/dashboard/message` | High
56 | File | `/depotHead/list` | High
57 | File | `/device/signin` | High
58 | File | `/devinfo` | Medium
59 | File | `/dipam/save-delegates.php` | High
60 | File | `/fusiondirectory/index.php` | High
61 | File | `/general/attendance/manage/ask_duty/delete.php` | High
62 | File | `/general/email/outbox/delete.php` | High
63 | File | `/general/ipanel/menu_code.php?MENU_TYPE=FAV` | High
64 | File | `/goform/addressNat` | High
65 | File | `/goform/RGFirewallEL` | High
66 | File | `/goform/SetOnlineDevName` | High
67 | File | `/goform/WifiBasicSet` | High
68 | File | `/goform/wifiSSIDset` | High
69 | File | `/h/` | Low
70 | File | `/HNAP1` | Low
71 | File | `/hslist` | Low
72 | File | `/importexport.php` | High
73 | ... | ... | ...

There are 644 more IOA items available (file, library, argument, input value, pattern, network port). Please use our online service to access the data.

## References

The following list contains _external sources_ which discuss the actor and the associated activities:

* https://blog.talosintelligence.com/2018/07/multiple-cobalt-personality-disorder.html
* https://www.proofpoint.com/us/threat-insight/post/microsoft-word-intruder-integrates-cve-2017-0199-utilized-cobalt-group-target
* https://www.ptsecurity.com/upload/corporate/ww-en/analytics/Cobalt-Snatch-eng.pdf
* https://www.riskiq.com/blog/labs/cobalt-group-spear-phishing-russian-banks/
* https://www.riskiq.com/blog/labs/cobalt-strike/
* https://www.trendmicro.com/en_us/research/17/k/cobalt-spam-runs-use-macros-cve-2017-8759-exploit.html

## Literature

The following _articles_ explain our unique predictive cyber threat intelligence:

* [VulDB Cyber Threat Intelligence Documentation](https://vuldb.com/?kb.cti)
* [Cyber Threat Intelligence - Early Anticipation of Attacks](https://www.scip.ch/en/?labs.20201022)

## License

(c) [1997-2024](https://vuldb.com/?kb.changelog) by [vuldb.com](https://vuldb.com/?kb.about). All data on this page is shared under the license [CC BY-NC-SA 4.0](https://creativecommons.org/licenses/by-nc-sa/4.0/). Questions? Check the [FAQ](https://vuldb.com/?kb.faq), read the [documentation](https://vuldb.com/?kb) or [contact us](https://vuldb.com/?contact)!
