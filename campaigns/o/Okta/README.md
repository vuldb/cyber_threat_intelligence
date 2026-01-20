# Okta - Cyber Threat Intelligence

These _indicators_ were reported, collected, and generated during the [VulDB CTI analysis](https://vuldb.com/?kb.cti) of the campaign known as _Okta_. The _activity monitoring_ correlates data from social media, forums, chat rooms, and darknet markets. It helps to determine associated actors, specific activities, expected intentions, emerging research, and ongoing attacks. Our unique _predictive model_ uses _big data_ to forecast activities and their characteristics.

_Live data_ and more _analysis capabilities_ are available at [https://vuldb.com/?actor](https://vuldb.com/?actor)

## Countries

These _countries_ are directly (e.g. origin of attacks) or indirectly (e.g. access by proxy) associated with Okta:

* [RU](https://vuldb.com/?country.ru)
* [US](https://vuldb.com/?country.us)
* [GB](https://vuldb.com/?country.gb)
* ...

There are 23 more country items available. Please use our online service to access the data.

## Actors

These _actors_ are associated with Okta or other actors linked to the campaign.

ID | Actor | Confidence
-- | ----- | ----------
1 | [Unknown](https://vuldb.com/?actor.unknown) | High

## IOC - Indicator of Compromise

These _indicators of compromise_ (IOC) indicate associated network resources which are known to be part of research and attack activities of Okta.

ID | IP address | Hostname | Actor | Confidence
-- | ---------- | -------- | ----- | ----------
1 | [23.105.182.19](https://vuldb.com/?ip.23.105.182.19) | warodism19.prescamawipe.com | [Unknown](https://vuldb.com/?actor.unknown) | High
2 | [23.106.56.11](https://vuldb.com/?ip.23.106.56.11) | - | [Unknown](https://vuldb.com/?actor.unknown) | High
3 | [23.106.56.21](https://vuldb.com/?ip.23.106.56.21) | - | [Unknown](https://vuldb.com/?actor.unknown) | High
4 | [23.106.56.36](https://vuldb.com/?ip.23.106.56.36) | - | [Unknown](https://vuldb.com/?actor.unknown) | High
5 | ... | ... | ... | ...

There are 16 more IOC items available. Please use our online service to access the data.

## TTP - Tactics, Techniques, Procedures

_Tactics, techniques, and procedures_ (TTP) summarize the suspected MITRE ATT&CK techniques used within Okta. This data is unique as it uses our predictive model for actor profiling.

ID | Technique | Weakness | Description | Confidence
-- | --------- | -------- | ----------- | ----------
1 | T1006 | CWE-21, CWE-22, CWE-24, CWE-36, CWE-425 | Path Traversal | High
2 | T1055 | CWE-74 | Improper Neutralization of Data within XPath Expressions | High
3 | T1059 | CWE-88, CWE-94 | Argument Injection | High
4 | T1059.007 | CWE-79, CWE-80 | Basic Cross Site Scripting | High
5 | T1068 | CWE-250, CWE-264, CWE-269, CWE-271, CWE-284 | Execution with Unnecessary Privileges | High
6 | ... | ... | ... | ...

There are 21 more TTP items available. Please use our online service to access the data.

## IOA - Indicator of Attack

These _indicators of attack_ (IOA) list the potential fragments used for technical activities like reconnaissance, exploitation, privilege escalation, and exfiltration during Okta. This data is unique as it uses our predictive model for actor profiling.

ID | Type | Indicator | Confidence
-- | ---- | --------- | ----------
1 | File | `//proc/kcore` | Medium
2 | File | `/accounts_con/register_account` | High
3 | File | `/actuator` | Medium
4 | File | `/addmem.php` | Medium
5 | File | `/addProduct.php` | High
6 | File | `/add_new_purchase.php?action=is_supplier` | High
7 | File | `/admin/?page=reports` | High
8 | File | `/admin/?page=system_info` | High
9 | File | `/admin/?page=system_info/contact_info` | High
10 | File | `/admin/?page=zone` | High
11 | File | `/admin/app/product.php` | High
12 | File | `/admin/app/service_crud.php` | High
13 | File | `/admin/blood/update/B-.php` | High
14 | File | `/admin/delete_student.php` | High
15 | File | `/admin/delete_user.php` | High
16 | File | `/admin/edit_categories.php` | High
17 | File | `/admin/fetch_product_details.php` | High
18 | File | `/admin/list_ipAddressPolicy.php` | High
19 | File | `/Admin/login.php` | High
20 | File | `/admin/login.php` | High
21 | File | `/admin/login_query.php` | High
22 | File | `/admin/massage.php` | High
23 | File | `/admin/password-recovery.php` | High
24 | File | `/admin/quesadd.php` | High
25 | File | `/admin/service/stop/` | High
26 | File | `/admin/student.php` | High
27 | File | `/admin/students/update_status.php` | High
28 | File | `/admin/system.html` | High
29 | File | `/admin/view-member-report.php` | High
30 | File | `/advanced-tools/nova/bin/netwatch` | High
31 | File | `/api/baskets/{name}` | High
32 | File | `/app/admin/controller/api/Plugs.php` | High
33 | File | `/app/api/controller/default/File.php` | High
34 | File | `/app/api/controller/default/Sqlite.php` | High
35 | File | `/app/controller/Setup.php` | High
36 | File | `/assets/php/upload.php` | High
37 | File | `/bin/boa` | Medium
38 | File | `/bin/httpd` | Medium
39 | File | `/binutils/debug.c` | High
40 | File | `/cancel.php` | Medium
41 | File | `/cart/update/attr` | High
42 | File | `/cgi-bin/account_mgr.cgi?cmd=cgi_user_add` | High
43 | File | `/cgi-bin/cstecgi.cgi` | High
44 | File | `/cgi-bin/firewall.cgi` | High
45 | File | `/cgi-bin/login.cgi` | High
46 | File | `/cgi-bin/luci;stok=/locale` | High
47 | File | `/cgi-bin/nas_sharing.cgi` | High
48 | File | `/com/esafenet/servlet/ajax/MultiServerAjax.java` | High
49 | ... | ... | ...

There are 425 more IOA items available (file, library, argument, input value, pattern, network port). Please use our online service to access the data.

## References

The following list contains _external sources_ which discuss the campaign and the associated activities:

* https://sec.okta.com/harfiles

## Literature

The following _articles_ explain our unique predictive cyber threat intelligence:

* [VulDB Cyber Threat Intelligence Documentation](https://vuldb.com/?kb.cti)
* [Cyber Threat Intelligence - Early Anticipation of Attacks](https://www.scip.ch/en/?labs.20201022)

## License

(c) [1997-2026](https://vuldb.com/?kb.changelog) by [vuldb.com](https://vuldb.com/?kb.about). All data on this page is shared under the license [CC BY-NC-SA 4.0](https://creativecommons.org/licenses/by-nc-sa/4.0/). Questions? Check the [FAQ](https://vuldb.com/?kb.faq), read the [documentation](https://vuldb.com/?kb) or [contact us](https://vuldb.com/?contact)!
