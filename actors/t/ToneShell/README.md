# ToneShell - Cyber Threat Intelligence

These _indicators_ were reported, collected, and generated during the [VulDB CTI analysis](https://vuldb.com/?kb.cti) of the actor known as [ToneShell](https://vuldb.com/?actor.toneshell). The _activity monitoring_ correlates data from social media, forums, chat rooms, and darknet markets. It helps to determine associated actors, specific activities, expected intentions, emerging research, and ongoing attacks. Our unique _predictive model_ uses _big data_ to forecast activities and their characteristics.

_Live data_ and more _analysis capabilities_ are available at [https://vuldb.com/?actor.toneshell](https://vuldb.com/?actor.toneshell)

## Countries

These _countries_ are directly (e.g. origin of attacks) or indirectly (e.g. access by proxy) associated with ToneShell:

* [US](https://vuldb.com/?country.us)
* [CN](https://vuldb.com/?country.cn)
* [ID](https://vuldb.com/?country.id)
* ...

There are 5 more country items available. Please use our online service to access the data.

## IOC - Indicator of Compromise

These _indicators of compromise_ (IOC) indicate associated network resources which are known to be part of research and attack activities of ToneShell.

ID | IP address | Hostname | Campaign | Confidence
-- | ---------- | -------- | -------- | ----------
1 | [43.246.209.139](https://vuldb.com/?ip.43.246.209.139) | - | - | High
2 | [45.115.236.142](https://vuldb.com/?ip.45.115.236.142) | - | - | High
3 | [45.115.236.143](https://vuldb.com/?ip.45.115.236.143) | - | - | High
4 | ... | ... | ... | ...

There are 6 more IOC items available. Please use our online service to access the data.

## TTP - Tactics, Techniques, Procedures

_Tactics, techniques, and procedures_ (TTP) summarize the suspected MITRE ATT&CK techniques used by _ToneShell_. This data is unique as it uses our predictive model for actor profiling.

ID | Technique | Weakness | Description | Confidence
-- | --------- | -------- | ----------- | ----------
1 | T1006 | CWE-22, CWE-23, CWE-24, CWE-36 | Path Traversal | High
2 | T1040 | CWE-319 | Authentication Bypass by Capture-replay | High
3 | T1055 | CWE-74 | Improper Neutralization of Data within XPath Expressions | High
4 | T1059 | CWE-88, CWE-94 | Argument Injection | High
5 | ... | ... | ... | ...

There are 15 more TTP items available. Please use our online service to access the data.

## IOA - Indicator of Attack

These _indicators of attack_ (IOA) list the potential fragments used for technical activities like reconnaissance, exploitation, privilege escalation, and exfiltration by ToneShell. This data is unique as it uses our predictive model for actor profiling.

ID | Type | Indicator | Confidence
-- | ---- | --------- | ----------
1 | File | `/?r=report/api/getlist` | High
2 | File | `/addcompany.php` | High
3 | File | `/admin.php/appcenter/local.html?type=addon` | High
4 | File | `/admin.php?c=upload&f=zip&_noCache=0.1683794968` | High
5 | File | `/admin/?page=product/manage_product&id=2` | High
6 | File | `/admin/?page=reminders/view_reminder` | High
7 | File | `/admin/?page=system_info` | High
8 | File | `/admin/assign/assign.php` | High
9 | File | `/admin/budget/manage_budget.php` | High
10 | File | `/admin/candidates_row.php` | High
11 | File | `/admin/categories/manage_category.php` | High
12 | File | `/admin/categories/view_category.php` | High
13 | File | `/admin/contacts/organizations/edit/2` | High
14 | File | `/admin/content/index` | High
15 | File | `/admin/employee_add.php` | High
16 | File | `/admin/employee_edit.php` | High
17 | File | `/admin/forgot-password.php` | High
18 | File | `/admin/index2.html` | High
19 | File | `/admin/index3.php` | High
20 | File | `/admin/inventory/manage_stock.php` | High
21 | File | `/admin/manage_academic.php` | High
22 | File | `/admin/mechanics/manage_mechanic.php` | High
23 | File | `/admin/modal_add_product.php` | High
24 | File | `/admin/offenses/view_details.php` | High
25 | File | `/admin/positions_row.php` | High
26 | File | `/admin/product/manage.php` | High
27 | File | `/admin/read.php?mudi=announContent` | High
28 | File | `/admin/report/index.php` | High
29 | File | `/admin/reports/index.php` | High
30 | File | `/admin/robot/approval/list` | High
31 | File | `/admin/service_requests/manage_inventory.php` | High
32 | File | `/admin/students/view_details.php` | High
33 | File | `/admin/user/manage_user.php` | High
34 | File | `/admin/userprofile.php` | High
35 | File | `/adms/admin/?page=user/manage_user` | High
36 | File | `/adms/classes/Users.php` | High
37 | File | `/ajax.php?action=read_msg` | High
38 | File | `/api/admin/system/store/order/list` | High
39 | File | `/api/upload` | Medium
40 | File | `/api/v1/snapshots` | High
41 | File | `/api2/html/` | Medium
42 | File | `/author/list?limit=10&offset=0&order=desc` | High
43 | File | `/backend/admin/his_admin_add_lab_equipment.php` | High
44 | File | `/bilal final/login.php` | High
45 | File | `/boat/login.php` | High
46 | File | `/cgi-bin/system_mgr.cgi` | High
47 | File | `/classes/Login.php` | High
48 | File | `/classes/Master.php` | High
49 | File | `/classes/Master.php?f=delete_img` | High
50 | File | `/classes/Master.php?f=save_category` | High
51 | File | `/classes/Master.php?f=save_sub_category` | High
52 | File | `/classes/Master.php?f=update_order_status` | High
53 | File | `/classes/Users.php` | High
54 | File | `/data/config.ftp.php` | High
55 | File | `/ddos.asp` | Medium
56 | File | `/ecommerce/admin/category/controller.php` | High
57 | ... | ... | ...

There are 500 more IOA items available (file, library, argument, input value, pattern, network port). Please use our online service to access the data.

## References

The following list contains _external sources_ which discuss the actor and the associated activities:

* https://exchange.xforce.ibmcloud.com/report/details/guid:10feeb92eac94b959f1ec8cd523ba69d
* https://hunt.io/blog/toneshell-backdoor-used-to-target-attendees-of-the-iiss-defence-summit

## Literature

The following _articles_ explain our unique predictive cyber threat intelligence:

* [VulDB Cyber Threat Intelligence Documentation](https://vuldb.com/?kb.cti)
* [Cyber Threat Intelligence - Early Anticipation of Attacks](https://www.scip.ch/en/?labs.20201022)

## License

(c) [1997-2026](https://vuldb.com/?kb.changelog) by [vuldb.com](https://vuldb.com/?kb.about). All data on this page is shared under the license [CC BY-NC-SA 4.0](https://creativecommons.org/licenses/by-nc-sa/4.0/). Questions? Check the [FAQ](https://vuldb.com/?kb.faq), read the [documentation](https://vuldb.com/?kb) or [contact us](https://vuldb.com/?contact)!
