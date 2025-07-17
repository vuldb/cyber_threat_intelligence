# Bandit Stealer - Cyber Threat Intelligence

These _indicators_ were reported, collected, and generated during the [VulDB CTI analysis](https://vuldb.com/?kb.cti) of the actor known as [Bandit Stealer](https://vuldb.com/?actor.bandit_stealer). The _activity monitoring_ correlates data from social media, forums, chat rooms, and darknet markets. It helps to determine associated actors, specific activities, expected intentions, emerging research, and ongoing attacks. Our unique _predictive model_ uses _big data_ to forecast activities and their characteristics.

_Live data_ and more _analysis capabilities_ are available at [https://vuldb.com/?actor.bandit_stealer](https://vuldb.com/?actor.bandit_stealer)

## Countries

These _countries_ are directly (e.g. origin of attacks) or indirectly (e.g. access by proxy) associated with Bandit Stealer:

* [SH](https://vuldb.com/?country.sh)
* [US](https://vuldb.com/?country.us)
* [BR](https://vuldb.com/?country.br)
* ...

There are 8 more country items available. Please use our online service to access the data.

## IOC - Indicator of Compromise

These _indicators of compromise_ (IOC) indicate associated network resources which are known to be part of research and attack activities of Bandit Stealer.

ID | IP address | Hostname | Campaign | Confidence
-- | ---------- | -------- | -------- | ----------
1 | [3.92.209.204](https://vuldb.com/?ip.3.92.209.204) | ec2-3-92-209-204.compute-1.amazonaws.com | - | Medium
2 | [20.102.80.176](https://vuldb.com/?ip.20.102.80.176) | - | - | High
3 | [20.150.218.195](https://vuldb.com/?ip.20.150.218.195) | - | - | High
4 | [24.199.107.85](https://vuldb.com/?ip.24.199.107.85) | - | - | High
5 | [41.216.183.23](https://vuldb.com/?ip.41.216.183.23) | - | - | High
6 | [41.216.183.94](https://vuldb.com/?ip.41.216.183.94) | - | - | High
7 | [45.42.45.10](https://vuldb.com/?ip.45.42.45.10) | web9-redirect.me | - | High
8 | ... | ... | ... | ...

There are 30 more IOC items available. Please use our online service to access the data.

## TTP - Tactics, Techniques, Procedures

_Tactics, techniques, and procedures_ (TTP) summarize the suspected MITRE ATT&CK techniques used by _Bandit Stealer_. This data is unique as it uses our predictive model for actor profiling.

ID | Technique | Weakness | Description | Confidence
-- | --------- | -------- | ----------- | ----------
1 | T1006 | CWE-21, CWE-22, CWE-24, CWE-35, CWE-36 | Path Traversal | High
2 | T1040 | CWE-319 | Authentication Bypass by Capture-replay | High
3 | T1055 | CWE-74 | Improper Neutralization of Data within XPath Expressions | High
4 | T1059 | CWE-94, CWE-1321 | Argument Injection | High
5 | T1059.007 | CWE-79, CWE-80 | Basic Cross Site Scripting | High
6 | ... | ... | ... | ...

There are 20 more TTP items available. Please use our online service to access the data.

## IOA - Indicator of Attack

These _indicators of attack_ (IOA) list the potential fragments used for technical activities like reconnaissance, exploitation, privilege escalation, and exfiltration by Bandit Stealer. This data is unique as it uses our predictive model for actor profiling.

ID | Type | Indicator | Confidence
-- | ---- | --------- | ----------
1 | File | `/aboutedit.php` | High
2 | File | `/abs.php` | Medium
3 | File | `/account.php` | Medium
4 | File | `/adicionar-cliente.php` | High
5 | File | `/admin.php?page=album` | High
6 | File | `/admin/` | Low
7 | File | `/admin/?page=inventory/view_inventory&id=2` | High
8 | File | `/Admin/add-admin.php` | High
9 | File | `/admin/add-property.php` | High
10 | File | `/admin/admin_action.php` | High
11 | File | `/admin/admin_login.php` | High
12 | File | `/admin/admin_members.php?ac=search` | High
13 | File | `/admin/ajax.php?action=confirm_order` | High
14 | File | `/admin/article.php` | High
15 | File | `/admin/article.php?action=upload_cover` | High
16 | File | `/admin/articles/create` | High
17 | File | `/admin/assets/plugins/DataTables/media/unit_testing/templates/dymanic_table.php` | High
18 | File | `/admin/assets/plugins/DataTables/media/unit_testing/templates/html_table.php` | High
19 | File | `/admin/assets/plugins/DataTables/media/unit_testing/templates/js_data.php` | High
20 | File | `/admin/blood/update/B+.php` | High
21 | File | `/admin/chatroom.php` | High
22 | File | `/admin/config_ISCGroupNoCache.php` | High
23 | File | `/admin/config_time_sync.php` | High
24 | File | `/admin/content/book` | High
25 | File | `/admin/content/editor` | High
26 | File | `/admin/customermanagementframework/customers/list` | High
27 | File | `/admin/deleteBooking.php` | High
28 | File | `/admin/delete_event.php` | High
29 | File | `/admin/edit-services.php` | High
30 | File | `/admin/File/fileUpload` | High
31 | File | `/admin/home.php?con=add` | High
32 | File | `/admin/index.php` | High
33 | File | `/admin/inventory/manage_stock.php` | High
34 | File | `/admin/link.php` | High
35 | File | `/admin/network/diag_iperf` | High
36 | File | `/admin/network/diag_traceroute` | High
37 | File | `/admin/newsletter.php` | High
38 | File | `/admin/orders/update_status.php` | High
39 | File | `/admin/overtime_row.php` | High
40 | File | `/admin/password-recovery.php` | High
41 | File | `/admin/plugin.php` | High
42 | File | `/admin/positions_add.php` | High
43 | File | `/admin/print.php` | High
44 | File | `/admin/process_category_edit.php` | High
45 | File | `/admin/profile.php` | High
46 | File | `/admin/registration.php` | High
47 | File | `/admin/room.php` | High
48 | File | `/admin/sales/manage_sale.php` | High
49 | File | `/admin/search-booking-request.php` | High
50 | File | `/admin/search-invoices.php` | High
51 | File | `/admin/search-maid.php` | High
52 | File | `/admin/search-property.php` | High
53 | File | `/admin/store.php` | High
54 | File | `/admin/twitter.php` | High
55 | File | `/admin/update_room.php` | High
56 | File | `/admin/user-search.php` | High
57 | File | `/admin/user.php` | High
58 | File | `/animalsupdate.php` | High
59 | File | `/api/job/add/` | High
60 | File | `/api/upload` | Medium
61 | File | `/app/api/controller/Site.php` | High
62 | ... | ... | ...

There are 546 more IOA items available (file, library, argument, input value, pattern, network port). Please use our online service to access the data.

## References

The following list contains _external sources_ which discuss the actor and the associated activities:

* https://search.censys.io/hosts/41.216.183.23
* https://search.censys.io/hosts/41.216.183.94
* https://search.censys.io/hosts/45.42.45.10
* https://threatfox.abuse.ch

## Literature

The following _articles_ explain our unique predictive cyber threat intelligence:

* [VulDB Cyber Threat Intelligence Documentation](https://vuldb.com/?kb.cti)
* [Cyber Threat Intelligence - Early Anticipation of Attacks](https://www.scip.ch/en/?labs.20201022)

## License

(c) [1997-2025](https://vuldb.com/?kb.changelog) by [vuldb.com](https://vuldb.com/?kb.about). All data on this page is shared under the license [CC BY-NC-SA 4.0](https://creativecommons.org/licenses/by-nc-sa/4.0/). Questions? Check the [FAQ](https://vuldb.com/?kb.faq), read the [documentation](https://vuldb.com/?kb) or [contact us](https://vuldb.com/?contact)!
