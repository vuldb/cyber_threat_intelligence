# Serpent Stealer - Cyber Threat Intelligence

These _indicators_ were reported, collected, and generated during the [VulDB CTI analysis](https://vuldb.com/?kb.cti) of the actor known as [Serpent Stealer](https://vuldb.com/?actor.serpent_stealer). The _activity monitoring_ correlates data from social media, forums, chat rooms, and darknet markets. It helps to determine associated actors, specific activities, expected intentions, emerging research, and ongoing attacks. Our unique _predictive model_ uses _big data_ to forecast activities and their characteristics.

_Live data_ and more _analysis capabilities_ are available at [https://vuldb.com/?actor.serpent_stealer](https://vuldb.com/?actor.serpent_stealer)

## Countries

These _countries_ are directly (e.g. origin of attacks) or indirectly (e.g. access by proxy) associated with Serpent Stealer:

* [US](https://vuldb.com/?country.us)

## IOC - Indicator of Compromise

These _indicators of compromise_ (IOC) indicate associated network resources which are known to be part of research and attack activities of Serpent Stealer.

ID | IP address | Hostname | Campaign | Confidence
-- | ---------- | -------- | -------- | ----------
1 | [3.210.242.78](https://vuldb.com/?ip.3.210.242.78) | ec2-3-210-242-78.compute-1.amazonaws.com | - | Medium
2 | [3.213.37.39](https://vuldb.com/?ip.3.213.37.39) | ec2-3-213-37-39.compute-1.amazonaws.com | - | Medium
3 | [3.219.159.186](https://vuldb.com/?ip.3.219.159.186) | ec2-3-219-159-186.compute-1.amazonaws.com | - | Medium
4 | [18.204.80.51](https://vuldb.com/?ip.18.204.80.51) | ec2-18-204-80-51.compute-1.amazonaws.com | - | Medium
5 | [34.197.122.235](https://vuldb.com/?ip.34.197.122.235) | ec2-34-197-122-235.compute-1.amazonaws.com | - | Medium
6 | ... | ... | ... | ...

There are 18 more IOC items available. Please use our online service to access the data.

## TTP - Tactics, Techniques, Procedures

_Tactics, techniques, and procedures_ (TTP) summarize the suspected MITRE ATT&CK techniques used by _Serpent Stealer_. This data is unique as it uses our predictive model for actor profiling.

ID | Technique | Weakness | Description | Confidence
-- | --------- | -------- | ----------- | ----------
1 | T1006 | CWE-22 | Path Traversal | High
2 | T1055 | CWE-74 | Improper Neutralization of Data within XPath Expressions | High
3 | T1059 | CWE-88, CWE-94 | Argument Injection | High
4 | T1059.007 | CWE-79, CWE-80 | Cross Site Scripting | High
5 | ... | ... | ... | ...

There are 16 more TTP items available. Please use our online service to access the data.

## IOA - Indicator of Attack

These _indicators of attack_ (IOA) list the potential fragments used for technical activities like reconnaissance, exploitation, privilege escalation, and exfiltration by Serpent Stealer. This data is unique as it uses our predictive model for actor profiling.

ID | Type | Indicator | Confidence
-- | ---- | --------- | ----------
1 | File | `*-sub-menu.php` | High
2 | File | `/admin/conferences/get-all-status/` | High
3 | File | `/admin/conferences/list/` | High
4 | File | `/admin/extended` | High
5 | File | `/admin/general/change-lang` | High
6 | File | `/admin/group` | Medium
7 | File | `/admin/moduleinterface.php` | High
8 | File | `/catcompany.php` | High
9 | File | `/cgi.cgi` | Medium
10 | File | `/controllers/MgrDiagnosticTools.php` | High
11 | File | `/designer/add/layout` | High
12 | File | `/filemanager/upload/drop` | High
13 | File | `/Forms/oadmin_1` | High
14 | File | `/forms/web_runScript` | High
15 | File | `/forum/away.php` | High
16 | File | `/front/roomtype-details.php` | High
17 | File | `/inc/lists/edit-list.php` | High
18 | File | `/inc/lists/edit_member.php` | High
19 | File | `/index.php` | Medium
20 | File | `/KK_LS9ReportingPortal/GetData` | High
21 | File | `/lists/admin/` | High
22 | File | `/LogoStore/search.php` | High
23 | File | `/mcategory.php` | High
24 | File | `/opt/tms/bin/cli` | High
25 | File | `/panel/uploads` | High
26 | File | `/roomtype-details.php` | High
27 | File | `/search-result/` | High
28 | File | `/swms/ms.cgi` | Medium
29 | File | `/system/www/pem/ck.pem` | High
30 | File | `/TeleoptiWFM/Administration/GetOneTenant` | High
31 | File | `/tmp` | Low
32 | File | `/usr/local/contego/scripts/hostname.sh` | High
33 | File | `/var/run/cloudera-scm-agent/process` | High
34 | File | `/vmi/manager/engine/management/commands/apns_worker.py` | High
35 | File | `/zm/index.php` | High
36 | File | `4.7.0/4.7.1` | Medium
37 | File | `aacplusenc.c` | Medium
38 | File | `aac_parser.c` | Medium
39 | ... | ... | ...

There are 333 more IOA items available (file, library, argument, input value, pattern, network port). Please use our online service to access the data.

## References

The following list contains _external sources_ which discuss the actor and the associated activities:

* https://search.censys.io/hosts/3.210.242.78
* https://search.censys.io/hosts/3.213.37.39
* https://search.censys.io/hosts/18.204.80.51
* https://search.censys.io/hosts/34.197.122.235
* https://search.censys.io/hosts/34.200.37.176
* https://search.censys.io/hosts/34.207.38.46
* https://search.censys.io/hosts/34.230.177.18
* https://search.censys.io/hosts/52.20.229.84
* https://search.censys.io/hosts/52.22.239.204
* https://search.censys.io/hosts/52.23.117.205
* https://search.censys.io/hosts/52.200.22.116
* https://search.censys.io/hosts/52.205.60.154
* https://search.censys.io/hosts/54.86.17.63
* https://search.censys.io/hosts/54.88.105.125
* https://search.censys.io/hosts/54.175.203.218
* https://search.censys.io/hosts/54.234.189.192
* https://search.censys.io/hosts/54.237.138.159
* https://threatfox.abuse.ch

## Literature

The following _articles_ explain our unique predictive cyber threat intelligence:

* [VulDB Cyber Threat Intelligence Documentation](https://vuldb.com/?kb.cti)
* [Cyber Threat Intelligence - Early Anticipation of Attacks](https://www.scip.ch/en/?labs.20201022)

## License

(c) [1997-2024](https://vuldb.com/?kb.changelog) by [vuldb.com](https://vuldb.com/?kb.about). All data on this page is shared under the license [CC BY-NC-SA 4.0](https://creativecommons.org/licenses/by-nc-sa/4.0/). Questions? Check the [FAQ](https://vuldb.com/?kb.faq), read the [documentation](https://vuldb.com/?kb) or [contact us](https://vuldb.com/?contact)!
