# WhiteSnake Stealer - Cyber Threat Intelligence

These _indicators_ were reported, collected, and generated during the [VulDB CTI analysis](https://vuldb.com/?kb.cti) of the actor known as [WhiteSnake Stealer](https://vuldb.com/?actor.whitesnake_stealer). The _activity monitoring_ correlates data from social media, forums, chat rooms, and darknet markets. It helps to determine associated actors, specific activities, expected intentions, emerging research, and ongoing attacks. Our unique _predictive model_ uses _big data_ to forecast activities and their characteristics.

_Live data_ and more _analysis capabilities_ are available at [https://vuldb.com/?actor.whitesnake_stealer](https://vuldb.com/?actor.whitesnake_stealer)

## Countries

These _countries_ are directly (e.g. origin of attacks) or indirectly (e.g. access by proxy) associated with WhiteSnake Stealer:

* [US](https://vuldb.com/?country.us)
* [ES](https://vuldb.com/?country.es)
* [CN](https://vuldb.com/?country.cn)
* ...

There are 6 more country items available. Please use our online service to access the data.

## IOC - Indicator of Compromise

These _indicators of compromise_ (IOC) indicate associated network resources which are known to be part of research and attack activities of WhiteSnake Stealer.

ID | IP address | Hostname | Campaign | Confidence
-- | ---------- | -------- | -------- | ----------
1 | [5.181.12.94](https://vuldb.com/?ip.5.181.12.94) | - | - | High
2 | [8.130.31.155](https://vuldb.com/?ip.8.130.31.155) | - | - | High
3 | [18.158.249.75](https://vuldb.com/?ip.18.158.249.75) | ec2-18-158-249-75.eu-central-1.compute.amazonaws.com | - | Medium
4 | [18.171.15.157](https://vuldb.com/?ip.18.171.15.157) | ec2-18-171-15-157.eu-west-2.compute.amazonaws.com | - | Medium
5 | [18.218.18.183](https://vuldb.com/?ip.18.218.18.183) | ec2-18-218-18-183.us-east-2.compute.amazonaws.com | - | Medium
6 | [37.252.188.127](https://vuldb.com/?ip.37.252.188.127) | xn--037h1a4d.ml | - | High
7 | [45.132.96.113](https://vuldb.com/?ip.45.132.96.113) | - | - | High
8 | [45.155.171.134](https://vuldb.com/?ip.45.155.171.134) | - | - | High
9 | [52.86.18.77](https://vuldb.com/?ip.52.86.18.77) | ec2-52-86-18-77.compute-1.amazonaws.com | - | Medium
10 | ... | ... | ... | ...

There are 38 more IOC items available. Please use our online service to access the data.

## TTP - Tactics, Techniques, Procedures

_Tactics, techniques, and procedures_ (TTP) summarize the suspected MITRE ATT&CK techniques used by _WhiteSnake Stealer_. This data is unique as it uses our predictive model for actor profiling.

ID | Technique | Weakness | Description | Confidence
-- | --------- | -------- | ----------- | ----------
1 | T1006 | CWE-21, CWE-22, CWE-23 | Pathname Traversal | High
2 | T1040 | CWE-294, CWE-319 | Authentication Bypass by Capture-replay | High
3 | T1055 | CWE-74 | Injection | High
4 | T1059 | CWE-94, CWE-1321 | Cross Site Scripting | High
5 | T1059.007 | CWE-79, CWE-80 | Cross Site Scripting | High
6 | T1068 | CWE-250, CWE-264, CWE-269, CWE-274, CWE-284 | J2EE Misconfiguration: Weak Access Permissions for EJB Methods | High
7 | ... | ... | ... | ...

There are 24 more TTP items available. Please use our online service to access the data.

## IOA - Indicator of Attack

These _indicators of attack_ (IOA) list the potential fragments used for technical activities like reconnaissance, exploitation, privilege escalation, and exfiltration by WhiteSnake Stealer. This data is unique as it uses our predictive model for actor profiling.

ID | Type | Indicator | Confidence
-- | ---- | --------- | ----------
1 | File | `//proc/kcore` | Medium
2 | File | `/action/import_nodejs_app/` | High
3 | File | `/admin/add_exercises.php` | High
4 | File | `/admin/categories/view_category.php` | High
5 | File | `/admin/delete_user.php` | High
6 | File | `/admin/login.php` | High
7 | File | `/admin/maintenance/manage_category.php` | High
8 | File | `/admin/sales/manage_sale.php` | High
9 | File | `/admin/sales/view_details.php` | High
10 | File | `/admin/sign/out` | High
11 | File | `/admin/user/manage_user.php` | High
12 | File | `/admin/users_add.php` | High
13 | File | `/admin_system/api.php` | High
14 | File | `/adms/admin/?page=user/manage_user` | High
15 | File | `/alarm_pi/alarmService.php` | High
16 | File | `/Ap4RtpAtom.cpp` | High
17 | File | `/api/audits` | Medium
18 | File | `/api/browserextension/UpdatePassword/` | High
19 | File | `/apngopt/ubuntu.png` | High
20 | File | `/app/options.py` | High
21 | File | `/asms/classes/Master.php?f=delete_service` | High
22 | File | `/balance/service/list` | High
23 | File | `/be/rpc.php` | Medium
24 | File | `/boafrm/formFilter` | High
25 | File | `/bsms/?page=manage_account` | High
26 | File | `/cgi-bin/cstecgi.cgi?action=login` | High
27 | File | `/churchcrm/v2/family/not-found` | High
28 | File | `/classes/Login.php` | High
29 | File | `/classes/Master.php?f=delete_sub_category` | High
30 | File | `/dashboard/blocks/stacks/view_details/` | High
31 | File | `/dosen/data` | Medium
32 | File | `/ecommerce/admin/settings/setDiscount.php` | High
33 | File | `/editor/index.php` | High
34 | File | `/foms/place-order.php` | High
35 | File | `/framework/mod/db/DBMapper.xml` | High
36 | File | `/FreshRSS/p/ext.php` | High
37 | File | `/goform/SafeClientFilter` | High
38 | File | `/goform/SetPptpServerCfg` | High
39 | File | `/goform/setSysAdm` | High
40 | File | `/goform/SetVirtualServerCfg` | High
41 | File | `/goform/sysTools` | High
42 | ... | ... | ...

There are 363 more IOA items available (file, library, argument, input value, pattern, network port). Please use our online service to access the data.

## References

The following list contains _external sources_ which discuss the actor and the associated activities:

* https://russianpanda.com/2023/07/04/WhiteSnake-Stealer-Malware-Analysis/
* https://threatfox.abuse.ch

## Literature

The following _articles_ explain our unique predictive cyber threat intelligence:

* [VulDB Cyber Threat Intelligence Documentation](https://vuldb.com/?kb.cti)
* [Cyber Threat Intelligence - Early Anticipation of Attacks](https://www.scip.ch/en/?labs.20201022)

## License

(c) [1997-2024](https://vuldb.com/?kb.changelog) by [vuldb.com](https://vuldb.com/?kb.about). All data on this page is shared under the license [CC BY-NC-SA 4.0](https://creativecommons.org/licenses/by-nc-sa/4.0/). Questions? Check the [FAQ](https://vuldb.com/?kb.faq), read the [documentation](https://vuldb.com/?kb) or [contact us](https://vuldb.com/?contact)!
