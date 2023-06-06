# Loda - Cyber Threat Intelligence

These _indicators_ were reported, collected, and generated during the [VulDB CTI analysis](https://vuldb.com/?kb.cti) of the actor known as [Loda](https://vuldb.com/?actor.loda). The _activity monitoring_ correlates data from social media, forums, chat rooms, and darknet markets. It helps to determine associated actors, specific activities, expected intentions, emerging research, and ongoing attacks. Our unique _predictive model_ uses _big data_ to forecast activities and their characteristics.

_Live data_ and more _analysis capabilities_ are available at [https://vuldb.com/?actor.loda](https://vuldb.com/?actor.loda)

## Countries

These _countries_ are directly (e.g. origin of attacks) or indirectly (e.g. access by proxy) associated with Loda:

* [SH](https://vuldb.com/?country.sh)
* [US](https://vuldb.com/?country.us)
* [ME](https://vuldb.com/?country.me)
* ...

There are 4 more country items available. Please use our online service to access the data.

## IOC - Indicator of Compromise

These _indicators of compromise_ (IOC) indicate associated network resources which are known to be part of research and attack activities of Loda.

ID | IP address | Hostname | Campaign | Confidence
-- | ---------- | -------- | -------- | ----------
1 | [2.58.56.188](https://vuldb.com/?ip.2.58.56.188) | powered.by.rdp.sh | - | High
2 | [3.141.204.47](https://vuldb.com/?ip.3.141.204.47) | ec2-3-141-204-47.us-east-2.compute.amazonaws.com | - | Medium
3 | [13.40.105.36](https://vuldb.com/?ip.13.40.105.36) | ec2-13-40-105-36.eu-west-2.compute.amazonaws.com | - | Medium
4 | [34.174.95.150](https://vuldb.com/?ip.34.174.95.150) | 150.95.174.34.bc.googleusercontent.com | - | Medium
5 | ... | ... | ... | ...

There are 17 more IOC items available. Please use our online service to access the data.

## TTP - Tactics, Techniques, Procedures

_Tactics, techniques, and procedures_ (TTP) summarize the suspected MITRE ATT&CK techniques used by _Loda_. This data is unique as it uses our predictive model for actor profiling.

ID | Technique | Weakness | Description | Confidence
-- | --------- | -------- | ----------- | ----------
1 | T1006 | CWE-21, CWE-22, CWE-23, CWE-24 | Pathname Traversal | High
2 | T1040 | CWE-319 | Authentication Bypass by Capture-replay | High
3 | T1055 | CWE-74 | Injection | High
4 | T1059 | CWE-94 | Cross Site Scripting | High
5 | T1059.007 | CWE-79, CWE-80 | Cross Site Scripting | High
6 | ... | ... | ... | ...

There are 20 more TTP items available. Please use our online service to access the data.

## IOA - Indicator of Attack

These _indicators of attack_ (IOA) list the potential fragments used for technical activities like reconnaissance, exploitation, privilege escalation, and exfiltration by Loda. This data is unique as it uses our predictive model for actor profiling.

ID | Type | Indicator | Confidence
-- | ---- | --------- | ----------
1 | File | `/?p=products` | Medium
2 | File | `/admin/?page=product/manage_product&id=2` | High
3 | File | `/admin/admin.php` | High
4 | File | `/admin/ajax.php?action=delete_window` | High
5 | File | `/admin/api/theme-edit/` | High
6 | File | `/admin/casedetails.php` | High
7 | File | `/admin/fields/manage_field.php` | High
8 | File | `/admin/maintenance/brand.php` | High
9 | File | `/admin/mechanics/manage_mechanic.php` | High
10 | File | `/admin/offenses/view_details.php` | High
11 | File | `/admin/sales/index.php` | High
12 | File | `/admin/user/manage_user.php` | High
13 | File | `/admin/voters_row.php` | High
14 | File | `/ad_js.php` | Medium
15 | File | `/agc/vicidial.php` | High
16 | File | `/ajax/myshop` | Medium
17 | File | `/alumni/admin/ajax.php?action=save_settings` | High
18 | File | `/api/gen/clients/{language}` | High
19 | File | `/apply.cgi` | Medium
20 | File | `/APR/signup.php` | High
21 | File | `/authenticationendpoint/login.do` | High
22 | File | `/aux` | Low
23 | File | `/backup.pl` | Medium
24 | File | `/cas/logout` | Medium
25 | File | `/categorypage.php` | High
26 | File | `/cgi-bin/system_mgr.cgi` | High
27 | File | `/cha.php` | Medium
28 | File | `/classes/Master.php?f=delete_sub_category` | High
29 | File | `/College/admin/teacher.php` | High
30 | File | `/contactform/contactform.php` | High
31 | File | `/dayrui/Fcms/View/system_log.html` | High
32 | File | `/drivers/block/floppy.c` | High
33 | File | `/ecommerce/admin/category/controller.php` | High
34 | File | `/etc/config/product.ini` | High
35 | File | `/etc/crash` | Medium
36 | File | `/etc/shadow` | Medium
37 | File | `/files/list-file` | High
38 | File | `/fos/admin/ajax.php` | High
39 | File | `/goform/aspForm` | High
40 | File | `/goform/WifiBasicSet` | High
41 | File | `/index.php` | Medium
42 | File | `/intern/controller.php` | High
43 | File | `/kelasdosen/data` | High
44 | File | `/login/index.php` | High
45 | File | `/medicines/profile.php` | High
46 | File | `/menu.html` | Medium
47 | File | `/modules/projects/vw_files.php` | High
48 | File | `/Moosikay/order.php` | High
49 | File | `/multi-vendor-shopping-script/product-list.php` | High
50 | File | `/nasm/nasm-parse.c` | High
51 | File | `/ordering/admin/orders/loaddata.php` | High
52 | File | `/ordering/admin/stockin/loaddata.php` | High
53 | File | `/permissions/delete/2---` | High
54 | File | `/philosophy/admin/login.php` | High
55 | File | `/php-jms/updateview.php` | High
56 | File | `/php-opos/login.php` | High
57 | File | `/priv_mgt.html` | High
58 | File | `/queuing/index.php?page=display` | High
59 | File | `/resources//../` | High
60 | File | `/see_more_details.php` | High
61 | ... | ... | ...

There are 531 more IOA items available (file, library, argument, input value, pattern, network port). Please use our online service to access the data.

## References

The following list contains _external sources_ which discuss the actor and the associated activities:

* https://threatfox.abuse.ch

## Literature

The following _articles_ explain our unique predictive cyber threat intelligence:

* [VulDB Cyber Threat Intelligence Documentation](https://vuldb.com/?kb.cti)
* [Cyber Threat Intelligence - Early Anticipation of Attacks](https://www.scip.ch/en/?labs.20201022)

## License

(c) [1997-2023](https://vuldb.com/?kb.changelog) by [vuldb.com](https://vuldb.com/?kb.about). All data on this page is shared under the license [CC BY-NC-SA 4.0](https://creativecommons.org/licenses/by-nc-sa/4.0/). Questions? Check the [FAQ](https://vuldb.com/?kb.faq), read the [documentation](https://vuldb.com/?kb) or [contact us](https://vuldb.com/?contact)!
