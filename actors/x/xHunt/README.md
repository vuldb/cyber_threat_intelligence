# xHunt - Cyber Threat Intelligence

These _indicators_ were reported, collected, and generated during the [VulDB CTI analysis](https://vuldb.com/?kb.cti) of the actor known as [xHunt](https://vuldb.com/?actor.xhunt). The _activity monitoring_ correlates data from social media, forums, chat rooms, and darknet markets. It helps to determine associated actors, specific activities, expected intentions, emerging research, and ongoing attacks. Our unique _predictive model_ uses _big data_ to forecast activities and their characteristics.

_Live data_ and more _analysis capabilities_ are available at [https://vuldb.com/?actor.xhunt](https://vuldb.com/?actor.xhunt)

## Campaigns

The following _campaigns_ are known and can be associated with xHunt:

* BumbleBee

## Countries

These _countries_ are directly (e.g. origin of attacks) or indirectly (e.g. access by proxy) associated with xHunt:

* [US](https://vuldb.com/?country.us)
* [PW](https://vuldb.com/?country.pw)
* [DE](https://vuldb.com/?country.de)
* ...

There are 12 more country items available. Please use our online service to access the data.

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
1 | T1006 | CWE-21, CWE-22 | Path Traversal | High
2 | T1055 | CWE-74 | Improper Neutralization of Data within XPath Expressions | High
3 | T1059 | CWE-94, CWE-1321 | Argument Injection | High
4 | T1059.007 | CWE-79, CWE-80, CWE-84 | Basic Cross Site Scripting | High
5 | ... | ... | ... | ...

There are 18 more TTP items available. Please use our online service to access the data.

## IOA - Indicator of Attack

These _indicators of attack_ (IOA) list the potential fragments used for technical activities like reconnaissance, exploitation, privilege escalation, and exfiltration by xHunt. This data is unique as it uses our predictive model for actor profiling.

ID | Type | Indicator | Confidence
-- | ---- | --------- | ----------
1 | File | `/action.php` | Medium
2 | File | `/actuator` | Medium
3 | File | `/add-admin.php` | High
4 | File | `/addProduct.php` | High
5 | File | `/add_librarian.php` | High
6 | File | `/admin.php` | Medium
7 | File | `/admin.php?c=upload&f=zip&_noCache=0.1683794968` | High
8 | File | `/admin/add-boat.php` | High
9 | File | `/admin/adddoctorclinic.php` | High
10 | File | `/admin/admin_class.php` | High
11 | File | `/admin/betweendates-detailsreports.php` | High
12 | File | `/admin/candidates_edit.php` | High
13 | File | `/Admin/changepassword.php` | High
14 | File | `/admin/cms/category/addtitle` | High
15 | File | `/admin/cms/material/add` | High
16 | File | `/admin/create_product.php` | High
17 | File | `/admin/delete_s5.php` | High
18 | File | `/admin/edit_categories.php` | High
19 | File | `/admin/invoices.php` | High
20 | File | `/admin/login.php` | High
21 | File | `/admin/login_query.php` | High
22 | File | `/admin/pass-bwdates-reports-details.php` | High
23 | File | `/admin/product.php` | High
24 | File | `/admin/products/index.php?view=add` | High
25 | File | `/admin/quesadd.php` | High
26 | File | `/admin/school_year.php` | High
27 | File | `/admin/user-bookings.php` | High
28 | File | `/admin/voters_row.php` | High
29 | File | `/administrator/addcategory.php` | High
30 | File | `/adminLogin.php` | High
31 | File | `/admin_delete.php` | High
32 | File | `/ajax.php?action=delete_position` | High
33 | File | `/ajax.php?action=login` | High
34 | File | `/api/authentication/login` | High
35 | File | `/api/wizard/networkSetup` | High
36 | File | `/base/safe_setting/` | High
37 | File | `/binutils/debug.c` | High
38 | File | `/boafrm/formDdns` | High
39 | File | `/boafrm/formMultiAP` | High
40 | File | `/boafrm/formStaticDHCP` | High
41 | File | `/boafrm/formSysTel` | High
42 | File | `/boafrm/formWsc` | High
43 | File | `/c6/Jhsoft.Web.module/ToolBar/GetWordFileName.aspx/?text=GetUrl&style=add` | High
44 | File | `/cart/update/attr` | High
45 | File | `/cgi-bin/cstecgi.cgi` | High
46 | File | `/cgi-bin/wireless.cgi` | High
47 | File | `/check_student.php` | High
48 | File | `/chkuser.php` | Medium
49 | File | `/contact_us.php` | High
50 | File | `/controller/api/hotelList.php` | High
51 | File | `/controller/api/Room.php` | High
52 | File | `/customer_details.php` | High
53 | ... | ... | ...

There are 465 more IOA items available (file, library, argument, input value, pattern, network port). Please use our online service to access the data.

## References

The following list contains _external sources_ which discuss the actor and the associated activities:

* https://unit42.paloaltonetworks.com/bumblebee-webshell-xhunt-campaign/
* https://unit42.paloaltonetworks.com/xhunt-campaign-backdoors/

## Literature

The following _articles_ explain our unique predictive cyber threat intelligence:

* [VulDB Cyber Threat Intelligence Documentation](https://vuldb.com/?kb.cti)
* [Cyber Threat Intelligence - Early Anticipation of Attacks](https://www.scip.ch/en/?labs.20201022)

## License

(c) [1997-2026](https://vuldb.com/?kb.changelog) by [vuldb.com](https://vuldb.com/?kb.about). All data on this page is shared under the license [CC BY-NC-SA 4.0](https://creativecommons.org/licenses/by-nc-sa/4.0/). Questions? Check the [FAQ](https://vuldb.com/?kb.faq), read the [documentation](https://vuldb.com/?kb) or [contact us](https://vuldb.com/?contact)!
