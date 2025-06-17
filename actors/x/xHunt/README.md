# xHunt - Cyber Threat Intelligence

These _indicators_ were reported, collected, and generated during the [VulDB CTI analysis](https://vuldb.com/?kb.cti) of the actor known as [xHunt](https://vuldb.com/?actor.xhunt). The _activity monitoring_ correlates data from social media, forums, chat rooms, and darknet markets. It helps to determine associated actors, specific activities, expected intentions, emerging research, and ongoing attacks. Our unique _predictive model_ uses _big data_ to forecast activities and their characteristics.

_Live data_ and more _analysis capabilities_ are available at [https://vuldb.com/?actor.xhunt](https://vuldb.com/?actor.xhunt)

## Campaigns

The following _campaigns_ are known and can be associated with xHunt:

* BumbleBee

## Countries

These _countries_ are directly (e.g. origin of attacks) or indirectly (e.g. access by proxy) associated with xHunt:

* [US](https://vuldb.com/?country.us)
* [RU](https://vuldb.com/?country.ru)
* [UA](https://vuldb.com/?country.ua)
* ...

There are 19 more country items available. Please use our online service to access the data.

## IOC - Indicator of Compromise

These _indicators of compromise_ (IOC) indicate associated network resources which are known to be part of research and attack activities of xHunt.

ID | IP address | Hostname | Campaign | Confidence
-- | ---------- | -------- | -------- | ----------
1 | [23.92.127.18](https://vuldb.com/?ip.23.92.127.18) | - | BumbleBee | High
2 | [46.246.3.253](https://vuldb.com/?ip.46.246.3.253) | - | BumbleBee | High
3 | [46.246.3.254](https://vuldb.com/?ip.46.246.3.254) | - | BumbleBee | High
4 | [77.243.191.20](https://vuldb.com/?ip.77.243.191.20) | - | BumbleBee | High
5 | [82.102.21.219](https://vuldb.com/?ip.82.102.21.219) | - | BumbleBee | High
6 | [84.17.55.68](https://vuldb.com/?ip.84.17.55.68) | unn-84-17-55-68.cdn77.com | BumbleBee | High
7 | ... | ... | ... | ...

There are 24 more IOC items available. Please use our online service to access the data.

## TTP - Tactics, Techniques, Procedures

_Tactics, techniques, and procedures_ (TTP) summarize the suspected MITRE ATT&CK techniques used by _xHunt_. This data is unique as it uses our predictive model for actor profiling.

ID | Technique | Weakness | Description | Confidence
-- | --------- | -------- | ----------- | ----------
1 | T1006 | CWE-21, CWE-22, CWE-24, CWE-425 | Path Traversal | High
2 | T1040 | CWE-294, CWE-319 | Authentication Bypass by Capture-replay | High
3 | T1055 | CWE-74 | Improper Neutralization of Data within XPath Expressions | High
4 | T1059 | CWE-88, CWE-94, CWE-1321 | Argument Injection | High
5 | T1059.007 | CWE-79, CWE-80 | Basic Cross Site Scripting | High
6 | T1068 | CWE-264, CWE-269, CWE-284 | Execution with Unnecessary Privileges | High
7 | ... | ... | ... | ...

There are 22 more TTP items available. Please use our online service to access the data.

## IOA - Indicator of Attack

These _indicators of attack_ (IOA) list the potential fragments used for technical activities like reconnaissance, exploitation, privilege escalation, and exfiltration by xHunt. This data is unique as it uses our predictive model for actor profiling.

ID | Type | Indicator | Confidence
-- | ---- | --------- | ----------
1 | File | `.git/` | Low
2 | File | `/add-admin.php` | High
3 | File | `/add-students.php` | High
4 | File | `/addstock.php` | High
5 | File | `/add_new_supplier.php` | High
6 | File | `/admin` | Low
7 | File | `/admin-api/upload_image` | High
8 | File | `/admin/?page=reports` | High
9 | File | `/admin/?page=system_info/contact_info` | High
10 | File | `/admin/add-subadmin.php` | High
11 | File | `/admin/admin-update-employee.php` | High
12 | File | `/admin/app/login_crud.php` | High
13 | File | `/admin/application-bwdates-reports-details.php` | High
14 | File | `/admin/betweendates-detailsreports.php` | High
15 | File | `/admin/book-details.php` | High
16 | File | `/admin/categories/manage_category.php` | High
17 | File | `/admin/check_admin_login.php` | High
18 | File | `/admin/create_product.php` | High
19 | File | `/admin/edit-brand.php` | High
20 | File | `/admin/edit-card-detail.php` | High
21 | File | `/admin/edit_categories.php` | High
22 | File | `/admin/list_crl_conf` | High
23 | File | `/admin/login.php` | High
24 | File | `/admin/manage_user.php` | High
25 | File | `/admin/massage.php` | High
26 | File | `/admin/network/ajax_getChannelList` | High
27 | File | `/admin/pages/list` | High
28 | File | `/admin/pass-bwdates-reports-details.php` | High
29 | File | `/admin/password-recovery.php` | High
30 | File | `/admin/profile.php` | High
31 | File | `/admin/search.php` | High
32 | File | `/admin/system.html` | High
33 | File | `/admin/user-search.php` | High
34 | File | `/admin/view-card-detail.php` | High
35 | File | `/animalsupdate.php` | High
36 | File | `/api/process.php` | High
37 | File | `/api/swaggerui/static` | High
38 | File | `/api/sys/ng-alain/getDictItemsByTable/` | High
39 | File | `/api/v2/maps` | Medium
40 | File | `/api/wizard/networkSetup` | High
41 | File | `/app/admin/controller/api/Plugs.php` | High
42 | File | `/apply/index.php` | High
43 | File | `/b2b-supermarket/catalog/all-products` | High
44 | File | `/backend/admin/his_admin_add_lab_equipment.php` | High
45 | File | `/backend/register.php` | High
46 | File | `/boafrm/formStaticDHCP` | High
47 | File | `/cgi-bin/cstecgi.cgi` | High
48 | File | `/cgi-bin/myMusic.cgi` | High
49 | File | `/cgi-bin/nas_sharing.cgi` | High
50 | File | `/cgi-bin/p1_ftpserver.php` | High
51 | File | `/cgi-bin/photocenter_mgr.cgi` | High
52 | File | `/cgi-bin/system_mgr.cgi` | High
53 | File | `/cgi/get_param.cgi` | High
54 | File | `/classes/Master.php` | High
55 | File | `/classes/Master.php?f=save_medicine` | High
56 | File | `/classes/SystemSettings.php?f=update_settings` | High
57 | File | `/classes/Users.php?f=save` | High
58 | File | `/com/esafenet/servlet/ajax/MultiServerAjax.java` | High
59 | ... | ... | ...

There are 515 more IOA items available (file, library, argument, input value, pattern, network port). Please use our online service to access the data.

## References

The following list contains _external sources_ which discuss the actor and the associated activities:

* https://unit42.paloaltonetworks.com/bumblebee-webshell-xhunt-campaign/
* https://unit42.paloaltonetworks.com/xhunt-campaign-backdoors/

## Literature

The following _articles_ explain our unique predictive cyber threat intelligence:

* [VulDB Cyber Threat Intelligence Documentation](https://vuldb.com/?kb.cti)
* [Cyber Threat Intelligence - Early Anticipation of Attacks](https://www.scip.ch/en/?labs.20201022)

## License

(c) [1997-2025](https://vuldb.com/?kb.changelog) by [vuldb.com](https://vuldb.com/?kb.about). All data on this page is shared under the license [CC BY-NC-SA 4.0](https://creativecommons.org/licenses/by-nc-sa/4.0/). Questions? Check the [FAQ](https://vuldb.com/?kb.faq), read the [documentation](https://vuldb.com/?kb) or [contact us](https://vuldb.com/?contact)!
