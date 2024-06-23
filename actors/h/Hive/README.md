# Hive - Cyber Threat Intelligence

These _indicators_ were reported, collected, and generated during the [VulDB CTI analysis](https://vuldb.com/?kb.cti) of the actor known as [Hive](https://vuldb.com/?actor.hive). The _activity monitoring_ correlates data from social media, forums, chat rooms, and darknet markets. It helps to determine associated actors, specific activities, expected intentions, emerging research, and ongoing attacks. Our unique _predictive model_ uses _big data_ to forecast activities and their characteristics.

_Live data_ and more _analysis capabilities_ are available at [https://vuldb.com/?actor.hive](https://vuldb.com/?actor.hive)

## Countries

These _countries_ are directly (e.g. origin of attacks) or indirectly (e.g. access by proxy) associated with Hive:

* [US](https://vuldb.com/?country.us)
* [SC](https://vuldb.com/?country.sc)
* [RU](https://vuldb.com/?country.ru)
* ...

There are 14 more country items available. Please use our online service to access the data.

## IOC - Indicator of Compromise

These _indicators of compromise_ (IOC) indicate associated network resources which are known to be part of research and attack activities of Hive.

ID | IP address | Hostname | Campaign | Confidence
-- | ---------- | -------- | -------- | ----------
1 | [5.61.37.207](https://vuldb.com/?ip.5.61.37.207) | mx.domain.com | - | High
2 | [5.199.162.220](https://vuldb.com/?ip.5.199.162.220) | - | - | High
3 | [5.199.162.229](https://vuldb.com/?ip.5.199.162.229) | - | - | High
4 | [23.81.246.84](https://vuldb.com/?ip.23.81.246.84) | - | - | High
5 | [23.227.178.65](https://vuldb.com/?ip.23.227.178.65) | 23-227-178-65.static.hvvc.us | - | High
6 | [45.9.150.144](https://vuldb.com/?ip.45.9.150.144) | - | - | High
7 | [46.166.161.68](https://vuldb.com/?ip.46.166.161.68) | - | - | High
8 | ... | ... | ... | ...

There are 29 more IOC items available. Please use our online service to access the data.

## TTP - Tactics, Techniques, Procedures

_Tactics, techniques, and procedures_ (TTP) summarize the suspected MITRE ATT&CK techniques used by _Hive_. This data is unique as it uses our predictive model for actor profiling.

ID | Technique | Weakness | Description | Confidence
-- | --------- | -------- | ----------- | ----------
1 | T1006 | CWE-22, CWE-23 | Path Traversal | High
2 | T1055 | CWE-74 | Improper Neutralization of Data within XPath Expressions | High
3 | T1059 | CWE-94 | Argument Injection | High
4 | T1059.007 | CWE-79, CWE-80 | Cross Site Scripting | High
5 | ... | ... | ... | ...

There are 18 more TTP items available. Please use our online service to access the data.

## IOA - Indicator of Attack

These _indicators of attack_ (IOA) list the potential fragments used for technical activities like reconnaissance, exploitation, privilege escalation, and exfiltration by Hive. This data is unique as it uses our predictive model for actor profiling.

ID | Type | Indicator | Confidence
-- | ---- | --------- | ----------
1 | File | `/.vnc/sesman_${username}_passwd` | High
2 | File | `/admin/add-category.php` | High
3 | File | `/admin/cashadvance_row.php` | High
4 | File | `/admin/login.php` | High
5 | File | `/asms/classes/Master.php?f=delete_transaction` | High
6 | File | `/cgi-bin/cstecgi.cgi` | High
7 | File | `/cgi-bin/editBookmark` | High
8 | File | `/cgi-bin/login.cgi` | High
9 | File | `/cgi-bin/wlogin.cgi` | High
10 | File | `/change_password_process` | High
11 | File | `/controller/Index.php` | High
12 | File | `/CPE` | Low
13 | File | `/Employer/EditProfile.php` | High
14 | File | `/endpoint/add-guest.php` | High
15 | File | `/goform/addressNat` | High
16 | File | `/goform/aspForm` | High
17 | File | `/goform/SysToolRestoreSet` | High
18 | File | `/include/chart_generator.php` | High
19 | File | `/include/menu_v.inc.php` | High
20 | File | `/kubepi/api/v1/users/search?pageNum=1&&pageSize=10` | High
21 | File | `/librarian/lab.php` | High
22 | File | `/login/` | Low
23 | ... | ... | ...

There are 192 more IOA items available (file, library, argument, input value, pattern, network port). Please use our online service to access the data.

## References

The following list contains _external sources_ which discuss the actor and the associated activities:

* https://blog.netlab.360.com/warning-hive-variant-xdr33-is-coming_cn/
* https://de.darktrace.com/blog/tracking-the-hive-darktraces-detection-of-a-hive-ransomware-as-service
* https://www.cisa.gov/uscert/ncas/alerts/aa22-321a
* https://www.varonis.com/blog/hive-ransomware-analysis

## Literature

The following _articles_ explain our unique predictive cyber threat intelligence:

* [VulDB Cyber Threat Intelligence Documentation](https://vuldb.com/?kb.cti)
* [Cyber Threat Intelligence - Early Anticipation of Attacks](https://www.scip.ch/en/?labs.20201022)

## License

(c) [1997-2024](https://vuldb.com/?kb.changelog) by [vuldb.com](https://vuldb.com/?kb.about). All data on this page is shared under the license [CC BY-NC-SA 4.0](https://creativecommons.org/licenses/by-nc-sa/4.0/). Questions? Check the [FAQ](https://vuldb.com/?kb.faq), read the [documentation](https://vuldb.com/?kb) or [contact us](https://vuldb.com/?contact)!
