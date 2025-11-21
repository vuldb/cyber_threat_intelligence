# Hive - Cyber Threat Intelligence

These _indicators_ were reported, collected, and generated during the [VulDB CTI analysis](https://vuldb.com/?kb.cti) of the actor known as [Hive](https://vuldb.com/?actor.hive). The _activity monitoring_ correlates data from social media, forums, chat rooms, and darknet markets. It helps to determine associated actors, specific activities, expected intentions, emerging research, and ongoing attacks. Our unique _predictive model_ uses _big data_ to forecast activities and their characteristics.

_Live data_ and more _analysis capabilities_ are available at [https://vuldb.com/?actor.hive](https://vuldb.com/?actor.hive)

## Countries

These _countries_ are directly (e.g. origin of attacks) or indirectly (e.g. access by proxy) associated with Hive:

* [US](https://vuldb.com/?country.us)
* [SC](https://vuldb.com/?country.sc)
* [IS](https://vuldb.com/?country.is)
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
4 | T1059.007 | CWE-79, CWE-80 | Basic Cross Site Scripting | High
5 | T1068 | CWE-250, CWE-264, CWE-269, CWE-284 | Execution with Unnecessary Privileges | High
6 | ... | ... | ... | ...

There are 18 more TTP items available. Please use our online service to access the data.

## IOA - Indicator of Attack

These _indicators of attack_ (IOA) list the potential fragments used for technical activities like reconnaissance, exploitation, privilege escalation, and exfiltration by Hive. This data is unique as it uses our predictive model for actor profiling.

ID | Type | Indicator | Confidence
-- | ---- | --------- | ----------
1 | File | `/.vnc/sesman_${username}_passwd` | High
2 | File | `/admin/add-category.php` | High
3 | File | `/admin/allemployees.php` | High
4 | File | `/admin/cashadvance_row.php` | High
5 | File | `/admin/eligibility.php` | High
6 | File | `/admin/group/edit.do` | High
7 | File | `/admin/login.php` | High
8 | File | `/admin/manage-pages.php` | High
9 | File | `/admin/receipt.php` | High
10 | File | `/admin/user/edit.do` | High
11 | File | `/admin/user_update.php` | High
12 | File | `/admin_ping.htm` | High
13 | File | `/api/wizard/getBasicInfo` | High
14 | File | `/Applications/Content%20Manager/Execute.aspx?cmd=convert&mode=HTML` | High
15 | File | `/asms/classes/Master.php?f=delete_transaction` | High
16 | File | `/cgi-bin/cstecgi.cgi` | High
17 | File | `/cgi-bin/editBookmark` | High
18 | File | `/cgi-bin/login.cgi` | High
19 | File | `/cgi-bin/wlogin.cgi` | High
20 | File | `/change_password_process` | High
21 | File | `/controller/Index.php` | High
22 | File | `/controllers/updatesettings.php` | High
23 | File | `/CPE` | Low
24 | File | `/delete_student.php` | High
25 | File | `/Employer/EditProfile.php` | High
26 | File | `/endpoint/add-guest.php` | High
27 | File | `/goform/addressNat` | High
28 | ... | ... | ...

There are 236 more IOA items available (file, library, argument, input value, pattern, network port). Please use our online service to access the data.

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

(c) [1997-2025](https://vuldb.com/?kb.changelog) by [vuldb.com](https://vuldb.com/?kb.about). All data on this page is shared under the license [CC BY-NC-SA 4.0](https://creativecommons.org/licenses/by-nc-sa/4.0/). Questions? Check the [FAQ](https://vuldb.com/?kb.faq), read the [documentation](https://vuldb.com/?kb) or [contact us](https://vuldb.com/?contact)!
