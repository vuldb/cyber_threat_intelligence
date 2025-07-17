# WhiteSnake Stealer - Cyber Threat Intelligence

These _indicators_ were reported, collected, and generated during the [VulDB CTI analysis](https://vuldb.com/?kb.cti) of the actor known as [WhiteSnake Stealer](https://vuldb.com/?actor.whitesnake_stealer). The _activity monitoring_ correlates data from social media, forums, chat rooms, and darknet markets. It helps to determine associated actors, specific activities, expected intentions, emerging research, and ongoing attacks. Our unique _predictive model_ uses _big data_ to forecast activities and their characteristics.

_Live data_ and more _analysis capabilities_ are available at [https://vuldb.com/?actor.whitesnake_stealer](https://vuldb.com/?actor.whitesnake_stealer)

## Countries

These _countries_ are directly (e.g. origin of attacks) or indirectly (e.g. access by proxy) associated with WhiteSnake Stealer:

* [US](https://vuldb.com/?country.us)
* [RU](https://vuldb.com/?country.ru)
* [DE](https://vuldb.com/?country.de)
* ...

There are 8 more country items available. Please use our online service to access the data.

## IOC - Indicator of Compromise

These _indicators of compromise_ (IOC) indicate associated network resources which are known to be part of research and attack activities of WhiteSnake Stealer.

ID | IP address | Hostname | Campaign | Confidence
-- | ---------- | -------- | -------- | ----------
1 | [3.12.151.253](https://vuldb.com/?ip.3.12.151.253) | ec2-3-12-151-253.us-east-2.compute.amazonaws.com | - | Medium
2 | [5.181.12.94](https://vuldb.com/?ip.5.181.12.94) | - | - | High
3 | [8.130.31.155](https://vuldb.com/?ip.8.130.31.155) | - | - | High
4 | [18.158.249.75](https://vuldb.com/?ip.18.158.249.75) | ec2-18-158-249-75.eu-central-1.compute.amazonaws.com | - | Medium
5 | [18.171.15.157](https://vuldb.com/?ip.18.171.15.157) | ec2-18-171-15-157.eu-west-2.compute.amazonaws.com | - | Medium
6 | [18.218.18.183](https://vuldb.com/?ip.18.218.18.183) | ec2-18-218-18-183.us-east-2.compute.amazonaws.com | - | Medium
7 | [37.252.188.127](https://vuldb.com/?ip.37.252.188.127) | xn--037h1a4d.ml | - | High
8 | [39.96.33.40](https://vuldb.com/?ip.39.96.33.40) | - | - | High
9 | [45.132.96.113](https://vuldb.com/?ip.45.132.96.113) | - | - | High
10 | [45.147.99.158](https://vuldb.com/?ip.45.147.99.158) | - | - | High
11 | [45.155.171.134](https://vuldb.com/?ip.45.155.171.134) | - | - | High
12 | [46.235.26.83](https://vuldb.com/?ip.46.235.26.83) | 1248.de-provider.de | - | High
13 | [51.159.4.50](https://vuldb.com/?ip.51.159.4.50) | 51-159-4-50.rev.poneytelecom.eu | - | High
14 | ... | ... | ... | ...

There are 51 more IOC items available. Please use our online service to access the data.

## TTP - Tactics, Techniques, Procedures

_Tactics, techniques, and procedures_ (TTP) summarize the suspected MITRE ATT&CK techniques used by _WhiteSnake Stealer_. This data is unique as it uses our predictive model for actor profiling.

ID | Technique | Weakness | Description | Confidence
-- | --------- | -------- | ----------- | ----------
1 | T1006 | CWE-21, CWE-22, CWE-23 | Path Traversal | High
2 | T1040 | CWE-294, CWE-319 | Authentication Bypass by Capture-replay | High
3 | T1055 | CWE-74 | Improper Neutralization of Data within XPath Expressions | High
4 | T1059 | CWE-94, CWE-1321 | Argument Injection | High
5 | T1059.007 | CWE-79, CWE-80 | Basic Cross Site Scripting | High
6 | T1068 | CWE-250, CWE-264, CWE-269, CWE-274, CWE-284 | Execution with Unnecessary Privileges | High
7 | ... | ... | ... | ...

There are 22 more TTP items available. Please use our online service to access the data.

## IOA - Indicator of Attack

These _indicators of attack_ (IOA) list the potential fragments used for technical activities like reconnaissance, exploitation, privilege escalation, and exfiltration by WhiteSnake Stealer. This data is unique as it uses our predictive model for actor profiling.

ID | Type | Indicator | Confidence
-- | ---- | --------- | ----------
1 | File | `/admin` | Low
2 | File | `/admin#themes` | High
3 | File | `/admin/` | Low
4 | File | `/admin/add-customer-services.php` | High
5 | File | `/admin/categories/save` | High
6 | File | `/admin/categories/view_category.php` | High
7 | File | `/admin/cmsVote/save` | High
8 | File | `/Admin/CustomerReport.php` | High
9 | File | `/Admin/dashboard.php` | High
10 | File | `/admin/delete_user.php` | High
11 | File | `/admin/edit-scdetails.php` | High
12 | File | `/admin/emp-profile-avatar.php` | High
13 | File | `/admin/maintenance/manage_category.php` | High
14 | File | `/admin/sales/manage_sale.php` | High
15 | File | `/admin/sales/view_details.php` | High
16 | File | `/admin/sign/out` | High
17 | File | `/admin/user/manage_user.php` | High
18 | File | `/admin/v1/blog/edit` | High
19 | File | `/admin_system/api.php` | High
20 | File | `/adms/admin/?page=user/manage_user` | High
21 | File | `/api/audits` | Medium
22 | File | `/api/browserextension/UpdatePassword/` | High
23 | File | `/api/esps` | Medium
24 | File | `/api/front/search/books` | High
25 | File | `/apngopt/ubuntu.png` | High
26 | File | `/App/Tpl/Admin/Default/Channel/index.html.Attackers` | High
27 | File | `/appointment.php` | High
28 | File | `/asms/classes/Master.php?f=delete_service` | High
29 | File | `/balance/service/list` | High
30 | File | `/be/rpc.php` | Medium
31 | File | `/boafrm/formFilter` | High
32 | File | `/cgi-bin/cstecgi.cgi` | High
33 | File | `/cgi-bin/cstecgi.cgi?action=login` | High
34 | File | `/cgi-bin/discovery.cgi` | High
35 | File | `/cgi-bin/widget_api.cgi` | High
36 | File | `/churchcrm/v2/family/not-found` | High
37 | File | `/classes/Login.php` | High
38 | File | `/classes/Master.php` | High
39 | File | `/classes/Master.php?f=delete_sub_category` | High
40 | File | `/classes/SystemSettings.php?f=update_settings` | High
41 | File | `/com/esafenet/servlet/system/PolicyActionService.java` | High
42 | File | `/control/register_case.php` | High
43 | File | `/dashboard.php` | High
44 | File | `/debug/pprof` | Medium
45 | File | `/dosen/data` | Medium
46 | File | `/ecommerce/admin/settings/setDiscount.php` | High
47 | File | `/editor/index.php` | High
48 | File | `/env` | Low
49 | File | `/fax/fax_send.php` | High
50 | ... | ... | ...

There are 438 more IOA items available (file, library, argument, input value, pattern, network port). Please use our online service to access the data.

## References

The following list contains _external sources_ which discuss the actor and the associated activities:

* https://russianpanda.com/2023/07/04/WhiteSnake-Stealer-Malware-Analysis/
* https://threatfox.abuse.ch

## Literature

The following _articles_ explain our unique predictive cyber threat intelligence:

* [VulDB Cyber Threat Intelligence Documentation](https://vuldb.com/?kb.cti)
* [Cyber Threat Intelligence - Early Anticipation of Attacks](https://www.scip.ch/en/?labs.20201022)

## License

(c) [1997-2025](https://vuldb.com/?kb.changelog) by [vuldb.com](https://vuldb.com/?kb.about). All data on this page is shared under the license [CC BY-NC-SA 4.0](https://creativecommons.org/licenses/by-nc-sa/4.0/). Questions? Check the [FAQ](https://vuldb.com/?kb.faq), read the [documentation](https://vuldb.com/?kb) or [contact us](https://vuldb.com/?contact)!
