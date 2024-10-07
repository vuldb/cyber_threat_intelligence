# APT33 - Cyber Threat Intelligence

These _indicators_ were reported, collected, and generated during the [VulDB CTI analysis](https://vuldb.com/?kb.cti) of the actor known as [APT33](https://vuldb.com/?actor.apt33). The _activity monitoring_ correlates data from social media, forums, chat rooms, and darknet markets. It helps to determine associated actors, specific activities, expected intentions, emerging research, and ongoing attacks. Our unique _predictive model_ uses _big data_ to forecast activities and their characteristics.

_Live data_ and more _analysis capabilities_ are available at [https://vuldb.com/?actor.apt33](https://vuldb.com/?actor.apt33)

## Campaigns

The following _campaigns_ are known and can be associated with APT33:

* Elfin
* PoshC2
* Powerton

## Countries

These _countries_ are directly (e.g. origin of attacks) or indirectly (e.g. access by proxy) associated with APT33:

* [US](https://vuldb.com/?country.us)
* [ES](https://vuldb.com/?country.es)
* [FR](https://vuldb.com/?country.fr)
* ...

There are 11 more country items available. Please use our online service to access the data.

## IOC - Indicator of Compromise

These _indicators of compromise_ (IOC) indicate associated network resources which are known to be part of research and attack activities of APT33.

ID | IP address | Hostname | Campaign | Confidence
-- | ---------- | -------- | -------- | ----------
1 | [5.79.66.241](https://vuldb.com/?ip.5.79.66.241) | - | Powerton | High
2 | [5.79.127.177](https://vuldb.com/?ip.5.79.127.177) | - | Elfin | High
3 | [5.135.120.57](https://vuldb.com/?ip.5.135.120.57) | - | - | High
4 | [5.135.199.25](https://vuldb.com/?ip.5.135.199.25) | - | - | High
5 | [5.187.21.70](https://vuldb.com/?ip.5.187.21.70) | - | Elfin | High
6 | [5.187.21.71](https://vuldb.com/?ip.5.187.21.71) | - | Elfin | High
7 | [8.26.21.117](https://vuldb.com/?ip.8.26.21.117) | 117.21.26.8.serverpronto.com | Elfin | High
8 | [8.26.21.119](https://vuldb.com/?ip.8.26.21.119) | ns1.glasscitysoftware.net | Elfin | High
9 | [8.26.21.120](https://vuldb.com/?ip.8.26.21.120) | ns2.glasscitysoftware.net | Elfin | High
10 | [8.26.21.220](https://vuldb.com/?ip.8.26.21.220) | mail2.boldinbox.com | Elfin | High
11 | [8.26.21.221](https://vuldb.com/?ip.8.26.21.221) | mail3.boldinbox.com | Elfin | High
12 | [8.26.21.222](https://vuldb.com/?ip.8.26.21.222) | mail9.servidorz.com | Elfin | High
13 | [8.26.21.223](https://vuldb.com/?ip.8.26.21.223) | mail5.boldinbox.com | Elfin | High
14 | [31.7.62.48](https://vuldb.com/?ip.31.7.62.48) | - | - | High
15 | [37.48.105.178](https://vuldb.com/?ip.37.48.105.178) | - | Elfin | High
16 | ... | ... | ... | ...

There are 60 more IOC items available. Please use our online service to access the data.

## TTP - Tactics, Techniques, Procedures

_Tactics, techniques, and procedures_ (TTP) summarize the suspected MITRE ATT&CK techniques used by _APT33_. This data is unique as it uses our predictive model for actor profiling.

ID | Technique | Weakness | Description | Confidence
-- | --------- | -------- | ----------- | ----------
1 | T1006 | CWE-21, CWE-22, CWE-23, CWE-24 | Path Traversal | High
2 | T1055 | CWE-74 | Improper Neutralization of Data within XPath Expressions | High
3 | T1059 | CWE-88, CWE-94 | Argument Injection | High
4 | T1059.007 | CWE-79, CWE-80 | Cross Site Scripting | High
5 | T1068 | CWE-250, CWE-264, CWE-269, CWE-284 | Execution with Unnecessary Privileges | High
6 | ... | ... | ... | ...

There are 21 more TTP items available. Please use our online service to access the data.

## IOA - Indicator of Attack

These _indicators of attack_ (IOA) list the potential fragments used for technical activities like reconnaissance, exploitation, privilege escalation, and exfiltration by APT33. This data is unique as it uses our predictive model for actor profiling.

ID | Type | Indicator | Confidence
-- | ---- | --------- | ----------
1 | File | `/academy/tutor/filter` | High
2 | File | `/account/delivery` | High
3 | File | `/accounts_con/register_account` | High
4 | File | `/admin.php?c=upload&f=zip&_noCache=0.1683794968` | High
5 | File | `/admin/` | Low
6 | File | `/admin/?page=reminders/view_reminder` | High
7 | File | `/admin/?page=user/list` | High
8 | File | `/admin/action/update-deworm.php` | High
9 | File | `/admin/add_user_modal.php` | High
10 | File | `/admin/api/theme-edit/` | High
11 | File | `/admin/article/article-edit-run.php` | High
12 | File | `/admin/courses/view_course.php` | High
13 | File | `/admin/del_category.php` | High
14 | File | `/admin/edit-admin.php` | High
15 | File | `/admin/edit_product.php` | High
16 | File | `/admin/edit_supplier.php` | High
17 | File | `/admin/forgot-password.php` | High
18 | File | `/admin/invoice.php` | High
19 | File | `/admin/leancloud.php` | High
20 | File | `/Admin/login.php` | High
21 | File | `/admin/maintenance/view_designation.php` | High
22 | File | `/admin/modal_add_product.php` | High
23 | File | `/admin/orders/update_status.php` | High
24 | File | `/admin/orders/view_order.php` | High
25 | File | `/admin/settings/` | High
26 | File | `/admin/students/manage_academic.php` | High
27 | File | `/admin/sys_sql_query.php` | High
28 | File | `/admin/theme-edit.php` | High
29 | File | `/admin/update-clients.php` | High
30 | File | `/admin/userprofile.php` | High
31 | File | `/ajax.php?action=delete_block` | High
32 | File | `/api/controllers/admin/app/ComboController.php` | High
33 | File | `/api/controllers/common/UploadsController.php` | High
34 | File | `/api/log/killJob` | High
35 | File | `/application/index/common.php` | High
36 | File | `/application/index/controller/Pay.php` | High
37 | File | `/application/index/controller/Screen.php` | High
38 | File | `/application/index/controller/Unity.php` | High
39 | File | `/apply/index.php` | High
40 | File | `/author_posts.php` | High
41 | File | `/blog` | Low
42 | File | `/book-services.php` | High
43 | File | `/booking/show_bookings/` | High
44 | File | `/building/backmgr/urlpage/mobileurl/configfile/jx2_config.ini` | High
45 | File | `/cas/logout` | Medium
46 | File | `/category.php` | High
47 | File | `/cgi-bin/cstecgi.cgi` | High
48 | File | `/cgi-bin/cstecgi.cgi?action=login` | High
49 | File | `/cgi-bin/mainfunction.cgi` | High
50 | File | `/change-language/de_DE` | High
51 | File | `/classes/Login.php` | High
52 | File | `/classes/Master.php?f=delete_service` | High
53 | File | `/classes/Master.php?f=save_inquiry` | High
54 | File | `/classes/Master.php?f=save_item` | High
55 | File | `/classes/Users.php?f=save` | High
56 | File | `/cms/notify` | Medium
57 | File | `/contact/store` | High
58 | File | `/Duty/AjaxHandle/UploadFloodPlanFileUpdate.ashx` | High
59 | File | `/Duty/AjaxHandle/UploadHandler.ashx` | High
60 | File | `/Duty/AjaxHandle/Write/UploadFile.ashx` | High
61 | File | `/ecommerce/support_ticket` | High
62 | File | `/edit.php` | Medium
63 | File | `/Employer/ManageJob.php` | High
64 | File | `/en/blog-comment-4` | High
65 | File | `/endpoint/add-computer.php` | High
66 | File | `/endpoint/add-guest.php` | High
67 | File | `/endpoint/add-user.php` | High
68 | File | `/ext/collect/filter_text.do` | High
69 | File | `/farm/product.php` | High
70 | File | `/file_manager/admin/save_user.php` | High
71 | File | `/foms/routers/cancel-order.php` | High
72 | File | `/forum/away.php` | High
73 | File | `/general/email/outbox/delete.php` | High
74 | File | `/general/ipanel/menu_code.php?MENU_TYPE=FAV` | High
75 | File | `/get.php` | Medium
76 | File | `/goform/formEasySetupWWConfig` | High
77 | File | `/goform/RgUrlBlock.asp` | High
78 | ... | ... | ...

There are 686 more IOA items available (file, library, argument, input value, pattern, network port). Please use our online service to access the data.

## References

The following list contains _external sources_ which discuss the actor and the associated activities:

* https://github.com/jeFF0Falltrades/IoCs/blob/master/APT/poshc2_apt_33.md
* https://securelist.com/twas-the-night-before/91599/
* https://securityaffairs.co/wordpress/93845/apt/apt33-vpn-networks.html
* https://symantec-enterprise-blogs.security.com/blogs/threat-intelligence/elfin-apt33-espionage
* https://www.fireeye.com/blog/threat-research/2018/12/overruled-containing-a-potentially-destructive-adversary.html
* https://www.symantec.com/blogs/threat-intelligence/elfin-apt33-espionage

## Literature

The following _articles_ explain our unique predictive cyber threat intelligence:

* [VulDB Cyber Threat Intelligence Documentation](https://vuldb.com/?kb.cti)
* [Cyber Threat Intelligence - Early Anticipation of Attacks](https://www.scip.ch/en/?labs.20201022)

## License

(c) [1997-2024](https://vuldb.com/?kb.changelog) by [vuldb.com](https://vuldb.com/?kb.about). All data on this page is shared under the license [CC BY-NC-SA 4.0](https://creativecommons.org/licenses/by-nc-sa/4.0/). Questions? Check the [FAQ](https://vuldb.com/?kb.faq), read the [documentation](https://vuldb.com/?kb) or [contact us](https://vuldb.com/?contact)!
