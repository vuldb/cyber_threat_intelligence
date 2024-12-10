# Whitewarlock - Cyber Threat Intelligence

These _indicators_ were reported, collected, and generated during the [VulDB CTI analysis](https://vuldb.com/?kb.cti) of the actor known as [Whitewarlock](https://vuldb.com/?actor.whitewarlock). The _activity monitoring_ correlates data from social media, forums, chat rooms, and darknet markets. It helps to determine associated actors, specific activities, expected intentions, emerging research, and ongoing attacks. Our unique _predictive model_ uses _big data_ to forecast activities and their characteristics.

_Live data_ and more _analysis capabilities_ are available at [https://vuldb.com/?actor.whitewarlock](https://vuldb.com/?actor.whitewarlock)

## Countries

These _countries_ are directly (e.g. origin of attacks) or indirectly (e.g. access by proxy) associated with Whitewarlock:

* [US](https://vuldb.com/?country.us)
* [DE](https://vuldb.com/?country.de)
* [CN](https://vuldb.com/?country.cn)
* ...

There are 19 more country items available. Please use our online service to access the data.

## IOC - Indicator of Compromise

These _indicators of compromise_ (IOC) indicate associated network resources which are known to be part of research and attack activities of Whitewarlock.

ID | IP address | Hostname | Campaign | Confidence
-- | ---------- | -------- | -------- | ----------
1 | [5.47.87.202](https://vuldb.com/?ip.5.47.87.202) | - | - | High
2 | [37.19.210.21](https://vuldb.com/?ip.37.19.210.21) | unn-37-19-210-21.datapacket.com | - | High
3 | [37.19.210.34](https://vuldb.com/?ip.37.19.210.34) | unn-37-19-210-34.datapacket.com | - | High
4 | [45.86.221.146](https://vuldb.com/?ip.45.86.221.146) | - | - | High
5 | [45.134.140.144](https://vuldb.com/?ip.45.134.140.144) | unn-45-134-140-144.datapacket.com | - | High
6 | [45.134.142.200](https://vuldb.com/?ip.45.134.142.200) | unn-45-134-142-200.datapacket.com | - | High
7 | [45.155.91.99](https://vuldb.com/?ip.45.155.91.99) | - | - | High
8 | [66.63.167.147](https://vuldb.com/?ip.66.63.167.147) | 66.63.167.147.static.quadranet.com | - | High
9 | [66.115.189.247](https://vuldb.com/?ip.66.115.189.247) | - | - | High
10 | [79.127.217.44](https://vuldb.com/?ip.79.127.217.44) | unn-79-127-217-44.datapacket.com | - | High
11 | [87.249.134.11](https://vuldb.com/?ip.87.249.134.11) | unn-87-249-134-11.datapacket.com | - | High
12 | [93.115.0.49](https://vuldb.com/?ip.93.115.0.49) | - | - | High
13 | [96.44.191.140](https://vuldb.com/?ip.96.44.191.140) | 96.44.191.140.static.quadranet.com | - | High
14 | ... | ... | ... | ...

There are 53 more IOC items available. Please use our online service to access the data.

## TTP - Tactics, Techniques, Procedures

_Tactics, techniques, and procedures_ (TTP) summarize the suspected MITRE ATT&CK techniques used by _Whitewarlock_. This data is unique as it uses our predictive model for actor profiling.

ID | Technique | Weakness | Description | Confidence
-- | --------- | -------- | ----------- | ----------
1 | T1006 | CWE-22, CWE-27, CWE-35, CWE-36, CWE-425 | Path Traversal | High
2 | T1040 | CWE-294 | Authentication Bypass by Capture-replay | High
3 | T1055 | CWE-74 | Improper Neutralization of Data within XPath Expressions | High
4 | T1059 | CWE-94, CWE-1321 | Argument Injection | High
5 | T1059.007 | CWE-79, CWE-80 | Cross Site Scripting | High
6 | T1068 | CWE-250, CWE-264, CWE-269, CWE-274, CWE-284 | Execution with Unnecessary Privileges | High
7 | ... | ... | ... | ...

There are 22 more TTP items available. Please use our online service to access the data.

## IOA - Indicator of Attack

These _indicators of attack_ (IOA) list the potential fragments used for technical activities like reconnaissance, exploitation, privilege escalation, and exfiltration by Whitewarlock. This data is unique as it uses our predictive model for actor profiling.

ID | Type | Indicator | Confidence
-- | ---- | --------- | ----------
1 | File | `/?import` | Medium
2 | File | `/Account/login.php` | High
3 | File | `/add_new_invoice.php` | High
4 | File | `/admin/?page=reports` | High
5 | File | `/admin/ajax.php?action=save_settings` | High
6 | File | `/admin/bwdates-report-details.php` | High
7 | File | `/admin/config_ISCGroupNoCache.php` | High
8 | File | `/admin/emp-profile-avatar.php` | High
9 | File | `/admin/forms/option_lists/edit.php` | High
10 | File | `/admin/get_balance.php` | High
11 | File | `/admin/get_price.php` | High
12 | File | `/admin/home.php` | High
13 | File | `/admin/home.php?con=add` | High
14 | File | `/admin/index.php` | High
15 | File | `/admin/index3.php` | High
16 | File | `/admin/layout` | High
17 | File | `/admin/list_ipAddressPolicy.php` | High
18 | File | `/Admin/login.php` | High
19 | File | `/admin/manage_model.php` | High
20 | File | `/admin/manage_user.php` | High
21 | File | `/admin/pages/` | High
22 | File | `/admin/print_barcode.php` | High
23 | File | `/admin/search-vehicle.php` | High
24 | File | `/admin/settings/index.php?page=accounts` | High
25 | File | `/admin/student.php` | High
26 | File | `/admin/subject.php` | High
27 | File | `/admin/SysModule/upload/ajaxmodel/upload/uploadfilepath/sysmodule_1` | High
28 | File | `/admin/template/edit` | High
29 | File | `/adminpanel/admin/query/addCourseExe.php` | High
30 | File | `/ajax/getBasicInfo.php` | High
31 | File | `/ajax/get_patient_history.php` | High
32 | File | `/api/deploy/upload` | High
33 | File | `/api/deploy/upload /api/database/upload` | High
34 | File | `/api/files/recipepictures/` | High
35 | File | `/api/get-browser-snapshot` | High
36 | File | `/API/helm/verify` | High
37 | File | `/api/role` | Medium
38 | File | `/api/webhook` | Medium
39 | File | `/authMonitCallcenter` | High
40 | File | `/author_posts.php` | High
41 | File | `/boaform/admin/formPing` | High
42 | File | `/catalog/admin/categories.php?cPath=&action=new_product` | High
43 | File | `/category.php` | High
44 | File | `/cgi-bin/cstecgi.cgi` | High
45 | File | `/cgi-bin/cstecgi.cgi?action=save&setting` | High
46 | File | `/cgi-bin/hd_config.cgi` | High
47 | File | `/cgi-bin/myMusic.cgi` | High
48 | File | `/cgi-bin/p1_ftpserver.php` | High
49 | File | `/cgi-bin/wlogin.cgi` | High
50 | File | `/change_password.php` | High
51 | File | `/classes/Master.php?f=delete_category` | High
52 | File | `/classes/Master.php?f=save_item` | High
53 | File | `/classes/SystemSettings.php?f=update_settings` | High
54 | File | `/classes/Users.php?f=save` | High
55 | File | `/clientdetails/admin/regester.php` | High
56 | File | `/command_port.ini` | High
57 | File | `/config/authorized_keys` | High
58 | ... | ... | ...

There are 508 more IOA items available (file, library, argument, input value, pattern, network port). Please use our online service to access the data.

## References

The following list contains _external sources_ which discuss the actor and the associated activities:

* https://www.trustwave.com/en-us/resources/blogs/spiderlabs-blog/threat-advisory-snowflake-data-breach-impacts-its-clients/

## Literature

The following _articles_ explain our unique predictive cyber threat intelligence:

* [VulDB Cyber Threat Intelligence Documentation](https://vuldb.com/?kb.cti)
* [Cyber Threat Intelligence - Early Anticipation of Attacks](https://www.scip.ch/en/?labs.20201022)

## License

(c) [1997-2024](https://vuldb.com/?kb.changelog) by [vuldb.com](https://vuldb.com/?kb.about). All data on this page is shared under the license [CC BY-NC-SA 4.0](https://creativecommons.org/licenses/by-nc-sa/4.0/). Questions? Check the [FAQ](https://vuldb.com/?kb.faq), read the [documentation](https://vuldb.com/?kb) or [contact us](https://vuldb.com/?contact)!
