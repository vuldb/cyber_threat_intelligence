# PoshC2 - Cyber Threat Intelligence

These _indicators_ were reported, collected, and generated during the [VulDB CTI analysis](https://vuldb.com/?kb.cti) of the campaign known as _PoshC2_. The _activity monitoring_ correlates data from social media, forums, chat rooms, and darknet markets. It helps to determine associated actors, specific activities, expected intentions, emerging research, and ongoing attacks. Our unique _predictive model_ uses _big data_ to forecast activities and their characteristics.

_Live data_ and more _analysis capabilities_ are available at [https://vuldb.com/?actor](https://vuldb.com/?actor)

## Countries

These _countries_ are directly (e.g. origin of attacks) or indirectly (e.g. access by proxy) associated with PoshC2:

* [US](https://vuldb.com/?country.us)
* [RU](https://vuldb.com/?country.ru)
* [CN](https://vuldb.com/?country.cn)
* ...

There are 10 more country items available. Please use our online service to access the data.

## Actors

These _actors_ are associated with PoshC2 or other actors linked to the campaign.

ID | Actor | Confidence
-- | ----- | ----------
1 | [APT33](https://vuldb.com/?actor.apt33) | High
2 | [PoshC2](https://vuldb.com/?actor.poshc2) | High

## IOC - Indicator of Compromise

These _indicators of compromise_ (IOC) indicate associated network resources which are known to be part of research and attack activities of PoshC2.

ID | IP address | Hostname | Actor | Confidence
-- | ---------- | -------- | ----- | ----------
1 | [3.120.209.174](https://vuldb.com/?ip.3.120.209.174) | ec2-3-120-209-174.eu-central-1.compute.amazonaws.com | [PoshC2](https://vuldb.com/?actor.poshc2) | Medium
2 | [3.253.77.60](https://vuldb.com/?ip.3.253.77.60) | ec2-3-253-77-60.eu-west-1.compute.amazonaws.com | [PoshC2](https://vuldb.com/?actor.poshc2) | Medium
3 | [13.48.77.144](https://vuldb.com/?ip.13.48.77.144) | ec2-13-48-77-144.eu-north-1.compute.amazonaws.com | [PoshC2](https://vuldb.com/?actor.poshc2) | Medium
4 | [13.78.10.244](https://vuldb.com/?ip.13.78.10.244) | - | [PoshC2](https://vuldb.com/?actor.poshc2) | High
5 | [18.134.14.164](https://vuldb.com/?ip.18.134.14.164) | ec2-18-134-14-164.eu-west-2.compute.amazonaws.com | [PoshC2](https://vuldb.com/?actor.poshc2) | Medium
6 | [35.80.38.180](https://vuldb.com/?ip.35.80.38.180) | ec2-35-80-38-180.us-west-2.compute.amazonaws.com | [PoshC2](https://vuldb.com/?actor.poshc2) | Medium
7 | [35.202.253.45](https://vuldb.com/?ip.35.202.253.45) | 45.253.202.35.bc.googleusercontent.com | [PoshC2](https://vuldb.com/?actor.poshc2) | Medium
8 | [45.79.196.203](https://vuldb.com/?ip.45.79.196.203) | 45-79-196-203.ip.linodeusercontent.com | [PoshC2](https://vuldb.com/?actor.poshc2) | High
9 | ... | ... | ... | ...

There are 33 more IOC items available. Please use our online service to access the data.

## TTP - Tactics, Techniques, Procedures

_Tactics, techniques, and procedures_ (TTP) summarize the suspected MITRE ATT&CK techniques used within PoshC2. This data is unique as it uses our predictive model for actor profiling.

ID | Technique | Weakness | Description | Confidence
-- | --------- | -------- | ----------- | ----------
1 | T1006 | CWE-21, CWE-22, CWE-23 | Path Traversal | High
2 | T1055 | CWE-74 | Improper Neutralization of Data within XPath Expressions | High
3 | T1059 | CWE-94 | Argument Injection | High
4 | T1059.007 | CWE-79, CWE-80 | Cross Site Scripting | High
5 | ... | ... | ... | ...

There are 16 more TTP items available. Please use our online service to access the data.

## IOA - Indicator of Attack

These _indicators of attack_ (IOA) list the potential fragments used for technical activities like reconnaissance, exploitation, privilege escalation, and exfiltration during PoshC2. This data is unique as it uses our predictive model for actor profiling.

ID | Type | Indicator | Confidence
-- | ---- | --------- | ----------
1 | File | `/admin/config/uploadicon.php` | High
2 | File | `/admin/del_feedback.php` | High
3 | File | `/admin/login.php` | High
4 | File | `/app/Http/Controllers/Admin/NEditorController.php` | High
5 | File | `/cms/category/list` | High
6 | File | `/inquiries/view_inquiry.php` | High
7 | File | `/Login` | Low
8 | File | `/mgmt/tm/util/bash` | High
9 | File | `/mifs/c/i/reg/reg.html` | High
10 | File | `/product/savenewproduct.php?flag=1` | High
11 | File | `/search` | Low
12 | File | `/secure/ViewCollectors` | High
13 | File | `/Session` | Medium
14 | File | `/start_apply.htm` | High
15 | File | `/sysmanage/updatelib.php` | High
16 | File | `/thruk/#cgi-bin/extinfo.cgi?type=2` | High
17 | File | `/usr/bin/pkexec` | High
18 | File | `/var/log/nginx` | High
19 | File | `/xAdmin/html/cm_doclist_view_uc.jsp` | High
20 | File | `adclick.php` | Medium
21 | File | `add_comment.php` | High
22 | File | `admin/content.php` | High
23 | File | `booking.php` | Medium
24 | File | `browse-category.php` | High
25 | File | `BSW_cxttongr.htm` | High
26 | File | `cat.asp` | Low
27 | ... | ... | ...

There are 224 more IOA items available (file, library, argument, input value, pattern, network port). Please use our online service to access the data.

## References

The following list contains _external sources_ which discuss the campaign and the associated activities:

* https://github.com/jeFF0Falltrades/IoCs/blob/master/APT/poshc2_apt_33.md
* https://search.censys.io/hosts/3.253.77.60
* https://search.censys.io/hosts/13.48.77.144
* https://search.censys.io/hosts/18.134.14.164
* https://search.censys.io/hosts/45.79.196.203
* https://search.censys.io/hosts/46.101.126.207
* https://search.censys.io/hosts/51.250.38.28
* https://search.censys.io/hosts/65.20.68.219
* https://search.censys.io/hosts/70.77.124.96
* https://search.censys.io/hosts/79.143.181.62
* https://search.censys.io/hosts/88.210.9.139
* https://search.censys.io/hosts/94.23.228.43
* https://search.censys.io/hosts/139.84.149.193
* https://search.censys.io/hosts/139.84.172.20
* https://search.censys.io/hosts/157.245.128.27
* https://search.censys.io/hosts/159.100.29.105
* https://search.censys.io/hosts/161.35.21.152
* https://search.censys.io/hosts/164.90.183.39
* https://search.censys.io/hosts/165.227.246.129
* https://search.censys.io/hosts/176.119.159.177
* https://search.censys.io/hosts/184.72.153.18
* https://search.censys.io/hosts/185.167.63.27
* https://search.censys.io/hosts/185.234.216.64
* https://search.censys.io/hosts/213.219.37.158
* https://search.censys.io/search?resource=hosts&sort=RELEVANCE&per_page=25&virtual_hosts=EXCLUDE&q=services.software.product%3A+poshc2+and+not+labels%3A+tarpit
* https://threatfox.abuse.ch
* https://twitter.com/1ZRR4H/status/1582068501036273665
* https://twitter.com/TheDFIRReport/status/1407322479664762890
* https://www.lac.co.jp/lacwatch/people/20190213_001770.html
* https://www.lac.co.jp/lacwatch/people/20200424_002177.html
* https://x.com/drb_ra/status/1735296172758069289?s=20

## Literature

The following _articles_ explain our unique predictive cyber threat intelligence:

* [VulDB Cyber Threat Intelligence Documentation](https://vuldb.com/?kb.cti)
* [Cyber Threat Intelligence - Early Anticipation of Attacks](https://www.scip.ch/en/?labs.20201022)

## License

(c) [1997-2024](https://vuldb.com/?kb.changelog) by [vuldb.com](https://vuldb.com/?kb.about). All data on this page is shared under the license [CC BY-NC-SA 4.0](https://creativecommons.org/licenses/by-nc-sa/4.0/). Questions? Check the [FAQ](https://vuldb.com/?kb.faq), read the [documentation](https://vuldb.com/?kb) or [contact us](https://vuldb.com/?contact)!
