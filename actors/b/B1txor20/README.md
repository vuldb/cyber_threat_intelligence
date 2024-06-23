# B1txor20 - Cyber Threat Intelligence

These _indicators_ were reported, collected, and generated during the [VulDB CTI analysis](https://vuldb.com/?kb.cti) of the actor known as [B1txor20](https://vuldb.com/?actor.b1txor20). The _activity monitoring_ correlates data from social media, forums, chat rooms, and darknet markets. It helps to determine associated actors, specific activities, expected intentions, emerging research, and ongoing attacks. Our unique _predictive model_ uses _big data_ to forecast activities and their characteristics.

_Live data_ and more _analysis capabilities_ are available at [https://vuldb.com/?actor.b1txor20](https://vuldb.com/?actor.b1txor20)

## Countries

These _countries_ are directly (e.g. origin of attacks) or indirectly (e.g. access by proxy) associated with B1txor20:

* [US](https://vuldb.com/?country.us)
* [CN](https://vuldb.com/?country.cn)
* [PL](https://vuldb.com/?country.pl)
* ...

There are 13 more country items available. Please use our online service to access the data.

## IOC - Indicator of Compromise

These _indicators of compromise_ (IOC) indicate associated network resources which are known to be part of research and attack activities of B1txor20.

ID | IP address | Hostname | Campaign | Confidence
-- | ---------- | -------- | -------- | ----------
1 | [5.2.69.50](https://vuldb.com/?ip.5.2.69.50) | - | - | High
2 | [23.129.64.216](https://vuldb.com/?ip.23.129.64.216) | - | - | High
3 | [23.154.177.4](https://vuldb.com/?ip.23.154.177.4) | - | - | High
4 | [45.13.104.179](https://vuldb.com/?ip.45.13.104.179) | nosoignons.cust.milkywan.net | - | High
5 | [45.61.185.90](https://vuldb.com/?ip.45.61.185.90) | MiamiTor4.us | - | High
6 | [45.154.255.147](https://vuldb.com/?ip.45.154.255.147) | cust-147.keff.org | - | High
7 | [46.166.139.111](https://vuldb.com/?ip.46.166.139.111) | - | - | High
8 | [51.15.43.205](https://vuldb.com/?ip.51.15.43.205) | 205-43-15-51.instances.scw.cloud | - | High
9 | [62.102.148.68](https://vuldb.com/?ip.62.102.148.68) | - | - | High
10 | [62.102.148.69](https://vuldb.com/?ip.62.102.148.69) | - | - | High
11 | ... | ... | ... | ...

There are 40 more IOC items available. Please use our online service to access the data.

## TTP - Tactics, Techniques, Procedures

_Tactics, techniques, and procedures_ (TTP) summarize the suspected MITRE ATT&CK techniques used by _B1txor20_. This data is unique as it uses our predictive model for actor profiling.

ID | Technique | Weakness | Description | Confidence
-- | --------- | -------- | ----------- | ----------
1 | T1006 | CWE-21, CWE-22, CWE-23, CWE-24 | Path Traversal | High
2 | T1040 | CWE-294, CWE-319 | Authentication Bypass by Capture-replay | High
3 | T1055 | CWE-74 | Improper Neutralization of Data within XPath Expressions | High
4 | T1059 | CWE-94 | Argument Injection | High
5 | ... | ... | ... | ...

There are 16 more TTP items available. Please use our online service to access the data.

## IOA - Indicator of Attack

These _indicators of attack_ (IOA) list the potential fragments used for technical activities like reconnaissance, exploitation, privilege escalation, and exfiltration by B1txor20. This data is unique as it uses our predictive model for actor profiling.

ID | Type | Indicator | Confidence
-- | ---- | --------- | ----------
1 | File | `/admin` | Low
2 | File | `/admin/?page=user/list` | High
3 | File | `/admin/admin-profile.php` | High
4 | File | `/admin/case-type` | High
5 | File | `/admin/clients` | High
6 | File | `/admin/config_MT.php?action=delete` | High
7 | File | `/admin/content` | High
8 | File | `/admin/court` | Medium
9 | File | `/admin/court-type` | High
10 | File | `/admin/expense-type` | High
11 | File | `/admin/foreigner-bwdates-reports-details.php` | High
12 | File | `/admin/foreigner-search.php` | High
13 | File | `/admin/forgot-password.php` | High
14 | File | `/admin/index.php` | High
15 | File | `/admin/index.php?page=categories` | High
16 | File | `/admin/index.php?page=manage_product` | High
17 | File | `/admin/login.php` | High
18 | File | `/admin/maintenance/manage_brand.php` | High
19 | File | `/admin/modules/product/controller.php?action=add` | High
20 | File | `/admin/normal-bwdates-reports-details.php` | High
21 | File | `/admin/normal-search.php` | High
22 | File | `/admin/role` | Medium
23 | File | `/admin/search-directory.php.` | High
24 | File | `/admin/tasks` | Medium
25 | File | `/admin/tax` | Medium
26 | File | `/admin/template` | High
27 | File | `/admin/vendor` | High
28 | File | `/admin_class.php` | High
29 | File | `/api/request-token` | High
30 | File | `/api/v1/custom_component` | High
31 | File | `/assoc_table.php` | High
32 | File | `/bin/boa` | Medium
33 | File | `/book-services.php` | High
34 | File | `/building/backmgr/urlpage/mobileurl/configfile/jx2_config.ini` | High
35 | File | `/catalog/all-products` | High
36 | File | `/channels//link` | High
37 | File | `/classes/Master.php?f=load_registration` | High
38 | File | `/classes/Master.php?f=log_employee` | High
39 | File | `/classes/Master.php?f=log_visitor` | High
40 | File | `/classes/SystemSettings.php?f=update_settings` | High
41 | File | `/classes/Users.php?f=delete` | High
42 | File | `/conf/app.conf` | High
43 | File | `/control/deactivate_case.php` | High
44 | File | `/control/register_case.php` | High
45 | File | `/dataSet/testTransform;swagger-ui` | High
46 | File | `/dolibarr/commande/list.php` | High
47 | File | `/endpoint/delete-bill.php` | High
48 | ... | ... | ...

There are 418 more IOA items available (file, library, argument, input value, pattern, network port). Please use our online service to access the data.

## References

The following list contains _external sources_ which discuss the actor and the associated activities:

* https://blog.netlab.360.com/b1txor20-use-of-dns-tunneling_cn/

## Literature

The following _articles_ explain our unique predictive cyber threat intelligence:

* [VulDB Cyber Threat Intelligence Documentation](https://vuldb.com/?kb.cti)
* [Cyber Threat Intelligence - Early Anticipation of Attacks](https://www.scip.ch/en/?labs.20201022)

## License

(c) [1997-2024](https://vuldb.com/?kb.changelog) by [vuldb.com](https://vuldb.com/?kb.about). All data on this page is shared under the license [CC BY-NC-SA 4.0](https://creativecommons.org/licenses/by-nc-sa/4.0/). Questions? Check the [FAQ](https://vuldb.com/?kb.faq), read the [documentation](https://vuldb.com/?kb) or [contact us](https://vuldb.com/?contact)!
