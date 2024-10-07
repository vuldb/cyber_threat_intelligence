# Campaign 1 - Cyber Threat Intelligence

These _indicators_ were reported, collected, and generated during the [VulDB CTI analysis](https://vuldb.com/?kb.cti) of the campaign known as _Campaign 1_. The _activity monitoring_ correlates data from social media, forums, chat rooms, and darknet markets. It helps to determine associated actors, specific activities, expected intentions, emerging research, and ongoing attacks. Our unique _predictive model_ uses _big data_ to forecast activities and their characteristics.

_Live data_ and more _analysis capabilities_ are available at [https://vuldb.com/?actor](https://vuldb.com/?actor)

## Countries

These _countries_ are directly (e.g. origin of attacks) or indirectly (e.g. access by proxy) associated with Campaign 1:

* [CN](https://vuldb.com/?country.cn)
* [US](https://vuldb.com/?country.us)

## Actors

These _actors_ are associated with Campaign 1 or other actors linked to the campaign.

ID | Actor | Confidence
-- | ----- | ----------
1 | [Kwampirs](https://vuldb.com/?actor.kwampirs) | High

## IOC - Indicator of Compromise

These _indicators of compromise_ (IOC) indicate associated network resources which are known to be part of research and attack activities of Campaign 1.

ID | IP address | Hostname | Actor | Confidence
-- | ---------- | -------- | ----- | ----------
1 | [10.16.91.131](https://vuldb.com/?ip.10.16.91.131) | - | [Kwampirs](https://vuldb.com/?actor.kwampirs) | High
2 | [11.24.8.54](https://vuldb.com/?ip.11.24.8.54) | - | [Kwampirs](https://vuldb.com/?actor.kwampirs) | High
3 | [11.25.41.114](https://vuldb.com/?ip.11.25.41.114) | - | [Kwampirs](https://vuldb.com/?actor.kwampirs) | High
4 | [13.33.26.95](https://vuldb.com/?ip.13.33.26.95) | server-13-33-26-95.phx50.r.cloudfront.net | [Kwampirs](https://vuldb.com/?actor.kwampirs) | High
5 | [13.56.107.66](https://vuldb.com/?ip.13.56.107.66) | ec2-13-56-107-66.us-west-1.compute.amazonaws.com | [Kwampirs](https://vuldb.com/?actor.kwampirs) | Medium
6 | [14.40.57.104](https://vuldb.com/?ip.14.40.57.104) | - | [Kwampirs](https://vuldb.com/?actor.kwampirs) | High
7 | [15.85.30.84](https://vuldb.com/?ip.15.85.30.84) | atp467w084.sgp.hp.com | [Kwampirs](https://vuldb.com/?actor.kwampirs) | High
8 | [19.140.139.6](https://vuldb.com/?ip.19.140.139.6) | - | [Kwampirs](https://vuldb.com/?actor.kwampirs) | High
9 | [20.143.69.60](https://vuldb.com/?ip.20.143.69.60) | - | [Kwampirs](https://vuldb.com/?actor.kwampirs) | High
10 | [23.26.60.60](https://vuldb.com/?ip.23.26.60.60) | - | [Kwampirs](https://vuldb.com/?actor.kwampirs) | High
11 | [23.92.211.10](https://vuldb.com/?ip.23.92.211.10) | gramwide.net | [Kwampirs](https://vuldb.com/?actor.kwampirs) | High
12 | [25.108.63.68](https://vuldb.com/?ip.25.108.63.68) | - | [Kwampirs](https://vuldb.com/?actor.kwampirs) | High
13 | [26.50.108.98](https://vuldb.com/?ip.26.50.108.98) | - | [Kwampirs](https://vuldb.com/?actor.kwampirs) | High
14 | [27.22.41.133](https://vuldb.com/?ip.27.22.41.133) | - | [Kwampirs](https://vuldb.com/?actor.kwampirs) | High
15 | [29.136.101.40](https://vuldb.com/?ip.29.136.101.40) | - | [Kwampirs](https://vuldb.com/?actor.kwampirs) | High
16 | [30.101.13.14](https://vuldb.com/?ip.30.101.13.14) | - | [Kwampirs](https://vuldb.com/?actor.kwampirs) | High
17 | [33.9.140.76](https://vuldb.com/?ip.33.9.140.76) | - | [Kwampirs](https://vuldb.com/?actor.kwampirs) | High
18 | [36.75.63.47](https://vuldb.com/?ip.36.75.63.47) | - | [Kwampirs](https://vuldb.com/?actor.kwampirs) | High
19 | ... | ... | ... | ...

There are 71 more IOC items available. Please use our online service to access the data.

## TTP - Tactics, Techniques, Procedures

_Tactics, techniques, and procedures_ (TTP) summarize the suspected MITRE ATT&CK techniques used within Campaign 1. This data is unique as it uses our predictive model for actor profiling.

ID | Technique | Weakness | Description | Confidence
-- | --------- | -------- | ----------- | ----------
1 | T1006 | CWE-21, CWE-22, CWE-23, CWE-24 | Path Traversal | High
2 | T1055 | CWE-74 | Improper Neutralization of Data within XPath Expressions | High
3 | T1059 | CWE-88, CWE-94, CWE-1321 | Argument Injection | High
4 | T1059.007 | CWE-79, CWE-80 | Cross Site Scripting | High
5 | ... | ... | ... | ...

There are 18 more TTP items available. Please use our online service to access the data.

## IOA - Indicator of Attack

These _indicators of attack_ (IOA) list the potential fragments used for technical activities like reconnaissance, exploitation, privilege escalation, and exfiltration during Campaign 1. This data is unique as it uses our predictive model for actor profiling.

ID | Type | Indicator | Confidence
-- | ---- | --------- | ----------
1 | File | `/admin.php?p=/Area/index#tab=t2` | High
2 | File | `/admin/?setting-base.htm` | High
3 | File | `/admin/index2.html` | High
4 | File | `/admin/sql` | Medium
5 | File | `/admin/students.php` | High
6 | File | `/admin/students/manage.php` | High
7 | File | `/admin/system.html` | High
8 | File | `/adminPage/conf/reload` | High
9 | File | `/adminPage/www/addOver` | High
10 | File | `/api /v3/auth` | High
11 | File | `/application/index/controller/Icon.php` | High
12 | File | `/application/index/controller/Screen.php` | High
13 | File | `/bin/ate` | Medium
14 | File | `/boaform/device_reset.cgi` | High
15 | File | `/cgi-bin/cstecgi.cgi` | High
16 | File | `/dataSet/testTransform;swagger-ui` | High
17 | File | `/dayrui/Fcms/View/system_log.html` | High
18 | File | `/dayrui/My/View/main.html` | High
19 | File | `/general/meeting/manage/delete.php` | High
20 | File | `/goform/execCommand` | High
21 | File | `/goform/goform_get_cmd_process` | High
22 | File | `/goform/SetRebootTimer` | High
23 | File | `/goform/WriteFacMac` | High
24 | File | `/index.php` | Medium
25 | File | `/index.php/admin` | High
26 | File | `/index/ajax/lang` | High
27 | ... | ... | ...

There are 228 more IOA items available (file, library, argument, input value, pattern, network port). Please use our online service to access the data.

## References

The following list contains _external sources_ which discuss the campaign and the associated activities:

* https://blog.reversinglabs.com/hubfs/Blog/IOC%20list/Campaign_1_IOC.txt

## Literature

The following _articles_ explain our unique predictive cyber threat intelligence:

* [VulDB Cyber Threat Intelligence Documentation](https://vuldb.com/?kb.cti)
* [Cyber Threat Intelligence - Early Anticipation of Attacks](https://www.scip.ch/en/?labs.20201022)

## License

(c) [1997-2024](https://vuldb.com/?kb.changelog) by [vuldb.com](https://vuldb.com/?kb.about). All data on this page is shared under the license [CC BY-NC-SA 4.0](https://creativecommons.org/licenses/by-nc-sa/4.0/). Questions? Check the [FAQ](https://vuldb.com/?kb.faq), read the [documentation](https://vuldb.com/?kb) or [contact us](https://vuldb.com/?contact)!
