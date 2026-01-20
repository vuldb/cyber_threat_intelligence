# BlackNET RAT - Cyber Threat Intelligence

These _indicators_ were reported, collected, and generated during the [VulDB CTI analysis](https://vuldb.com/?kb.cti) of the actor known as [BlackNET RAT](https://vuldb.com/?actor.blacknet_rat). The _activity monitoring_ correlates data from social media, forums, chat rooms, and darknet markets. It helps to determine associated actors, specific activities, expected intentions, emerging research, and ongoing attacks. Our unique _predictive model_ uses _big data_ to forecast activities and their characteristics.

_Live data_ and more _analysis capabilities_ are available at [https://vuldb.com/?actor.blacknet_rat](https://vuldb.com/?actor.blacknet_rat)

## Countries

These _countries_ are directly (e.g. origin of attacks) or indirectly (e.g. access by proxy) associated with BlackNET RAT:

* [SH](https://vuldb.com/?country.sh)
* [US](https://vuldb.com/?country.us)
* [DE](https://vuldb.com/?country.de)
* ...

There are 9 more country items available. Please use our online service to access the data.

## IOC - Indicator of Compromise

These _indicators of compromise_ (IOC) indicate associated network resources which are known to be part of research and attack activities of BlackNET RAT.

ID | IP address | Hostname | Campaign | Confidence
-- | ---------- | -------- | -------- | ----------
1 | [2.57.19.173](https://vuldb.com/?ip.2.57.19.173) | - | - | High
2 | [3.16.203.28](https://vuldb.com/?ip.3.16.203.28) | ec2-3-16-203-28.us-east-2.compute.amazonaws.com | - | Medium
3 | [20.163.158.142](https://vuldb.com/?ip.20.163.158.142) | - | - | High
4 | [34.172.89.75](https://vuldb.com/?ip.34.172.89.75) | 75.89.172.34.bc.googleusercontent.com | - | Medium
5 | [45.133.1.98](https://vuldb.com/?ip.45.133.1.98) | - | - | High
6 | ... | ... | ... | ...

There are 20 more IOC items available. Please use our online service to access the data.

## TTP - Tactics, Techniques, Procedures

_Tactics, techniques, and procedures_ (TTP) summarize the suspected MITRE ATT&CK techniques used by _BlackNET RAT_. This data is unique as it uses our predictive model for actor profiling.

ID | Technique | Weakness | Description | Confidence
-- | --------- | -------- | ----------- | ----------
1 | T1006 | CWE-21, CWE-22, CWE-23, CWE-24, CWE-29, CWE-35, CWE-36 | Path Traversal | High
2 | T1040 | CWE-319 | Authentication Bypass by Capture-replay | High
3 | T1055 | CWE-74 | Improper Neutralization of Data within XPath Expressions | High
4 | T1059 | CWE-88, CWE-94 | Argument Injection | High
5 | T1059.007 | CWE-79, CWE-80 | Basic Cross Site Scripting | High
6 | ... | ... | ... | ...

There are 21 more TTP items available. Please use our online service to access the data.

## IOA - Indicator of Attack

These _indicators of attack_ (IOA) list the potential fragments used for technical activities like reconnaissance, exploitation, privilege escalation, and exfiltration by BlackNET RAT. This data is unique as it uses our predictive model for actor profiling.

ID | Type | Indicator | Confidence
-- | ---- | --------- | ----------
1 | File | `/admin.php?page=album` | High
2 | File | `/admin/?page=state` | High
3 | File | `/admin/action/new-feed.php` | High
4 | File | `/Admin/add-admin.php` | High
5 | File | `/admin/admin-profile.php` | High
6 | File | `/admin/admin_action.php` | High
7 | File | `/admin/admin_members.php?ac=search` | High
8 | File | `/admin/admin_running.php` | High
9 | File | `/admin/ajax.php?action=login` | High
10 | File | `/admin/assets/plugins/DataTables/media/unit_testing/templates/js_data.php` | High
11 | File | `/admin/blood/update/B+.php` | High
12 | File | `/admin/book_add.php` | High
13 | File | `/admin/bwdates-reports-details.php` | High
14 | File | `/admin/categories/manage_category.php` | High
15 | File | `/admin/category/controller.php` | High
16 | File | `/admin/category/view_category.php` | High
17 | File | `/admin/cmsTemplate/replace` | High
18 | File | `/admin/content/data` | High
19 | File | `/admin/content/editor` | High
20 | File | `/admin/create_product.php` | High
21 | File | `/admin/customermanagementframework/customers/list` | High
22 | File | `/admin/deleteBooking.php` | High
23 | File | `/admin/edit_account.php` | High
24 | File | `/admin/edit_student_query.php` | High
25 | File | `/admin/foreigner-search.php` | High
26 | File | `/admin/index.php` | High
27 | File | `/admin/index.php?act=reset_admin_psw` | High
28 | File | `/admin/list_crl_conf` | High
29 | File | `/admin/manage-foreigners-ticket.php` | High
30 | File | `/admin/moneyRecord_deal.php?mudi=delRecord` | High
31 | File | `/admin/normal-search.php` | High
32 | File | `/admin/password-recovery.php` | High
33 | File | `/admin/print.php` | High
34 | File | `/admin/product.php` | High
35 | File | `/admin/products/index.php` | High
36 | File | `/admin/registration.php` | High
37 | File | `/admin/sou.php` | High
38 | File | `/admin/template` | High
39 | File | `/admin/twitter.php` | High
40 | File | `/admin/update-progress.php` | High
41 | File | `/admin/update_room.php` | High
42 | File | `/admin/update_s7.php` | High
43 | File | `/admin/users_photo.php` | High
44 | File | `/admin/wangkan_list.php` | High
45 | File | `/adminpanel/admin/facebox_modal/updateExaminee.php` | High
46 | File | `/ajax/ajax_login.ashx` | High
47 | File | `/Android/data/com.myairtelapp/files/` | High
48 | File | `/animalsupdate.php` | High
49 | File | `/api/admin` | Medium
50 | File | `/api/admin/user?id` | High
51 | File | `/api/blade-user/export-user` | High
52 | File | `/api/upload` | Medium
53 | File | `/Auth.php` | Medium
54 | File | `/auth/list_projects` | High
55 | File | `/backend/admin/his_admin_register_patient.php` | High
56 | File | `/catalog/compare` | High
57 | File | `/cgi-bin/cstecgi.cgi` | High
58 | File | `/cgi-bin/cstecgi.cgi?action=login` | High
59 | File | `/cgi-bin/cstecgi.cgi?action=save&setting` | High
60 | File | `/cgi-bin/photocenter_mgr.cgi` | High
61 | File | `/cgi-bin/wlogin.cgi` | High
62 | File | `/class/edit/edit` | High
63 | File | `/classes/Master.php? f=save_medicine` | High
64 | File | `/classes/SystemSettings.php?f=update_settings` | High
65 | File | `/classes/Users.php?f=save` | High
66 | ... | ... | ...

There are 577 more IOA items available (file, library, argument, input value, pattern, network port). Please use our online service to access the data.

## References

The following list contains _external sources_ which discuss the actor and the associated activities:

* https://search.censys.io/hosts/2.57.19.173
* https://search.censys.io/hosts/3.16.203.28
* https://search.censys.io/hosts/20.163.158.142
* https://search.censys.io/hosts/34.172.89.75
* https://search.censys.io/hosts/45.138.16.106
* https://search.censys.io/hosts/47.116.171.20
* https://search.censys.io/hosts/91.92.251.210
* https://search.censys.io/hosts/92.62.251.76
* https://search.censys.io/hosts/101.35.240.162
* https://search.censys.io/hosts/103.90.161.122
* https://search.censys.io/hosts/172.206.26.225
* https://search.censys.io/hosts/185.49.126.146
* https://search.censys.io/hosts/190.123.44.240
* https://search.censys.io/hosts/195.24.236.8
* https://search.censys.io/hosts/196.251.100.50
* https://search.censys.io/hosts/196.251.100.51
* https://search.censys.io/hosts/196.251.100.52
* https://search.censys.io/hosts/203.115.83.231
* https://threatfox.abuse.ch
* https://tracker.viriback.com/index.php?q=80.85.157.98
* https://tracker.viriback.com/index.php?q=146.19.191.190
* https://tracker.viriback.com/index.php?q=190.123.44.228
* https://twitter.com/wwp96/status/1375103958872694788

## Literature

The following _articles_ explain our unique predictive cyber threat intelligence:

* [VulDB Cyber Threat Intelligence Documentation](https://vuldb.com/?kb.cti)
* [Cyber Threat Intelligence - Early Anticipation of Attacks](https://www.scip.ch/en/?labs.20201022)

## License

(c) [1997-2026](https://vuldb.com/?kb.changelog) by [vuldb.com](https://vuldb.com/?kb.about). All data on this page is shared under the license [CC BY-NC-SA 4.0](https://creativecommons.org/licenses/by-nc-sa/4.0/). Questions? Check the [FAQ](https://vuldb.com/?kb.faq), read the [documentation](https://vuldb.com/?kb) or [contact us](https://vuldb.com/?contact)!
