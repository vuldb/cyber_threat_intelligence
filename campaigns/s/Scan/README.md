# Scan - Cyber Threat Intelligence

These _indicators_ were reported, collected, and generated during the [VulDB CTI analysis](https://vuldb.com/?kb.cti) of the campaign known as _Scan_. The _activity monitoring_ correlates data from social media, forums, chat rooms, and darknet markets. It helps to determine associated actors, specific activities, expected intentions, emerging research, and ongoing attacks. Our unique _predictive model_ uses _big data_ to forecast activities and their characteristics.

_Live data_ and more _analysis capabilities_ are available at [https://vuldb.com/?actor](https://vuldb.com/?actor)

## Countries

These _countries_ are directly (e.g. origin of attacks) or indirectly (e.g. access by proxy) associated with Scan:

* [CN](https://vuldb.com/?country.cn)
* [US](https://vuldb.com/?country.us)
* [TH](https://vuldb.com/?country.th)
* ...

There are 7 more country items available. Please use our online service to access the data.

## Actors

These _actors_ are associated with Scan or other actors linked to the campaign.

ID | Actor | Confidence
-- | ----- | ----------
1 | [ScanBox](https://vuldb.com/?actor.scanbox) | High
2 | [Unknown](https://vuldb.com/?actor.unknown) | High

## IOC - Indicator of Compromise

These _indicators of compromise_ (IOC) indicate associated network resources which are known to be part of research and attack activities of Scan.

ID | IP address | Hostname | Actor | Confidence
-- | ---------- | -------- | ----- | ----------
1 | [1.9.5.38](https://vuldb.com/?ip.1.9.5.38) | - | [ScanBox](https://vuldb.com/?actor.scanbox) | High
2 | [23.251.102.74](https://vuldb.com/?ip.23.251.102.74) | zl-dal-us-gp3-wk109.internet-census.org | [Unknown](https://vuldb.com/?actor.unknown) | High
3 | [45.77.237.243](https://vuldb.com/?ip.45.77.237.243) | 45.77.237.243.vultrusercontent.com | [ScanBox](https://vuldb.com/?actor.scanbox) | Medium
4 | [45.146.164.110](https://vuldb.com/?ip.45.146.164.110) | - | [Unknown](https://vuldb.com/?actor.unknown) | High
5 | [46.101.59.235](https://vuldb.com/?ip.46.101.59.235) | - | [Unknown](https://vuldb.com/?actor.unknown) | High
6 | [50.2.24.211](https://vuldb.com/?ip.50.2.24.211) | - | [ScanBox](https://vuldb.com/?actor.scanbox) | High
7 | [52.220.244.242](https://vuldb.com/?ip.52.220.244.242) | ec2-52-220-244-242.ap-southeast-1.compute.amazonaws.com | [Unknown](https://vuldb.com/?actor.unknown) | Medium
8 | [66.197.231.62](https://vuldb.com/?ip.66.197.231.62) | - | [ScanBox](https://vuldb.com/?actor.scanbox) | High
9 | [69.197.146.80](https://vuldb.com/?ip.69.197.146.80) | - | [ScanBox](https://vuldb.com/?actor.scanbox) | High
10 | ... | ... | ... | ...

There are 34 more IOC items available. Please use our online service to access the data.

## TTP - Tactics, Techniques, Procedures

_Tactics, techniques, and procedures_ (TTP) summarize the suspected MITRE ATT&CK techniques used within Scan. This data is unique as it uses our predictive model for actor profiling.

ID | Technique | Weakness | Description | Confidence
-- | --------- | -------- | ----------- | ----------
1 | T1006 | CWE-21, CWE-22, CWE-23 | Path Traversal | High
2 | T1055 | CWE-74 | Improper Neutralization of Data within XPath Expressions | High
3 | T1059 | CWE-88, CWE-94 | Argument Injection | High
4 | T1059.007 | CWE-79, CWE-80 | Cross Site Scripting | High
5 | ... | ... | ... | ...

There are 15 more TTP items available. Please use our online service to access the data.

## IOA - Indicator of Attack

These _indicators of attack_ (IOA) list the potential fragments used for technical activities like reconnaissance, exploitation, privilege escalation, and exfiltration during Scan. This data is unique as it uses our predictive model for actor profiling.

ID | Type | Indicator | Confidence
-- | ---- | --------- | ----------
1 | File | `/admin.php?p=/Area/index#tab=t2` | High
2 | File | `/admin/admin.php` | High
3 | File | `/admin/maintenance/view_designation.php` | High
4 | File | `/adminlogin.asp` | High
5 | File | `/ajax.php` | Medium
6 | File | `/cgi-bin/wapopen` | High
7 | File | `/forum/away.php` | High
8 | File | `/mc-admin/post.php?state=delete&delete` | High
9 | File | `/nagiosxi/admin/banner_message-ajaxhelper.php` | High
10 | File | `/proc/self/setgroups` | High
11 | File | `/secure/QueryComponent!Default.jspa` | High
12 | File | `/userRpm/PingIframeRpm.htm` | High
13 | File | `/webman/info.cgi` | High
14 | File | `/wp-admin/options.php` | High
15 | File | `adclick.php` | Medium
16 | File | `addentry.php` | Medium
17 | File | `addmember.php` | High
18 | File | `addtocart.asp` | High
19 | File | `addtomylist.asp` | High
20 | File | `admin.x-shop.php` | High
21 | File | `admin/adminlogin.php` | High
22 | ... | ... | ...

There are 186 more IOA items available (file, library, argument, input value, pattern, network port). Please use our online service to access the data.

## References

The following list contains _external sources_ which discuss the campaign and the associated activities:

* https://isc.sans.edu/forums/diary/10+Most+Popular+Targeted+Ports+in+the+Past+3+Weeks/28242/
* https://isc.sans.edu/forums/diary/Apache+is+Actively+Scan+for+CVE202141773+CVE202142013/27940/
* https://www.proofpoint.com/us/blog/threat-insight/chasing-currents-espionage-south-china-sea
* https://www.threatminer.org/report.php?q=cto-tib-20150223-01a.pdf&y=2015
* https://www.threatminer.org/report.php?q=pwc_ScanBox_framework.pdf&y=2014

## Literature

The following _articles_ explain our unique predictive cyber threat intelligence:

* [VulDB Cyber Threat Intelligence Documentation](https://vuldb.com/?kb.cti)
* [Cyber Threat Intelligence - Early Anticipation of Attacks](https://www.scip.ch/en/?labs.20201022)

## License

(c) [1997-2024](https://vuldb.com/?kb.changelog) by [vuldb.com](https://vuldb.com/?kb.about). All data on this page is shared under the license [CC BY-NC-SA 4.0](https://creativecommons.org/licenses/by-nc-sa/4.0/). Questions? Check the [FAQ](https://vuldb.com/?kb.faq), read the [documentation](https://vuldb.com/?kb) or [contact us](https://vuldb.com/?contact)!
