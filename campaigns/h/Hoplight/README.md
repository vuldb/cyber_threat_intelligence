# HOPLIGHT - Cyber Threat Intelligence

These _indicators_ were reported, collected, and generated during the [VulDB CTI analysis](https://vuldb.com/?kb.cti) of the campaign known as _HOPLIGHT_. The _activity monitoring_ correlates data from social media, forums, chat rooms, and darknet markets. It helps to determine associated actors, specific activities, expected intentions, emerging research, and ongoing attacks. Our unique _predictive model_ uses _big data_ to forecast activities and their characteristics.

_Live data_ and more _analysis capabilities_ are available at [https://vuldb.com/?actor](https://vuldb.com/?actor)

## Countries

These _countries_ are directly (e.g. origin of attacks) or indirectly (e.g. access by proxy) associated with HOPLIGHT:

* [HK](https://vuldb.com/?country.hk)
* [US](https://vuldb.com/?country.us)
* [GB](https://vuldb.com/?country.gb)
* ...

There are 2 more country items available. Please use our online service to access the data.

## Actors

These _actors_ are associated with HOPLIGHT or other actors linked to the campaign.

ID | Actor | Confidence
-- | ----- | ----------
1 | [Lazarus](https://vuldb.com/?actor.lazarus) | High
2 | [DPRK](https://vuldb.com/?actor.dprk) | High
3 | [HopLight](https://vuldb.com/?actor.hoplight) | High

## IOC - Indicator of Compromise

These _indicators of compromise_ (IOC) indicate associated network resources which are known to be part of research and attack activities of HOPLIGHT.

ID | IP address | Hostname | Actor | Confidence
-- | ---------- | -------- | ----- | ----------
1 | [10.10.30.130](https://vuldb.com/?ip.10.10.30.130) | - | [HopLight](https://vuldb.com/?actor.hoplight) | High
2 | [14.140.116.172](https://vuldb.com/?ip.14.140.116.172) | 14-140-116-172-sapient.com | [HopLight](https://vuldb.com/?actor.hoplight) | High
3 | [21.0.0.0](https://vuldb.com/?ip.21.0.0.0) | - | [HopLight](https://vuldb.com/?actor.hoplight) | High
4 | [21.252.107.198](https://vuldb.com/?ip.21.252.107.198) | - | [HopLight](https://vuldb.com/?actor.hoplight) | High
5 | [21.255.255.255](https://vuldb.com/?ip.21.255.255.255) | - | [HopLight](https://vuldb.com/?actor.hoplight) | High
6 | [26.0.0.0](https://vuldb.com/?ip.26.0.0.0) | - | [HopLight](https://vuldb.com/?actor.hoplight) | High
7 | [26.165.218.44](https://vuldb.com/?ip.26.165.218.44) | - | [HopLight](https://vuldb.com/?actor.hoplight) | High
8 | [26.255.255.255](https://vuldb.com/?ip.26.255.255.255) | - | [HopLight](https://vuldb.com/?actor.hoplight) | High
9 | [47.206.4.145](https://vuldb.com/?ip.47.206.4.145) | static-47-206-4-145.srst.fl.frontiernet.net | [HopLight](https://vuldb.com/?actor.hoplight) | High
10 | ... | ... | ... | ...

There are 35 more IOC items available. Please use our online service to access the data.

## TTP - Tactics, Techniques, Procedures

_Tactics, techniques, and procedures_ (TTP) summarize the suspected MITRE ATT&CK techniques used within HOPLIGHT. This data is unique as it uses our predictive model for actor profiling.

ID | Technique | Weakness | Description | Confidence
-- | --------- | -------- | ----------- | ----------
1 | T1006 | CWE-21, CWE-22, CWE-23, CWE-24, CWE-425 | Path Traversal | High
2 | T1055 | CWE-74 | Improper Neutralization of Data within XPath Expressions | High
3 | T1059 | CWE-88, CWE-94, CWE-1321 | Argument Injection | High
4 | T1059.007 | CWE-79, CWE-80 | Cross Site Scripting | High
5 | T1068 | CWE-250, CWE-264, CWE-269, CWE-284 | Execution with Unnecessary Privileges | High
6 | ... | ... | ... | ...

There are 20 more TTP items available. Please use our online service to access the data.

## IOA - Indicator of Attack

These _indicators of attack_ (IOA) list the potential fragments used for technical activities like reconnaissance, exploitation, privilege escalation, and exfiltration during HOPLIGHT. This data is unique as it uses our predictive model for actor profiling.

ID | Type | Indicator | Confidence
-- | ---- | --------- | ----------
1 | File | `/?g=net_pro_keyword_import_save` | High
2 | File | `/admin-panel1.php` | High
3 | File | `/admin/academic/studenview_left.php` | High
4 | File | `/admin/ajax.php` | High
5 | File | `/admin/ajax.php?action=confirm_order` | High
6 | File | `/admin/bookings/view_details.php` | High
7 | File | `/admin/controller/JobLogController.java` | High
8 | File | `/admin/login.php` | High
9 | File | `/alerts/alertConfigField.php` | High
10 | File | `/api/blade-log/api/list` | High
11 | File | `/api/v1/terminal/sessions/?limit=1` | High
12 | File | `/cgi-bin/nas_sharing.cgi` | High
13 | File | `/config/myfield/test.php` | High
14 | File | `/context/%2e/WEB-INF/web.xml` | High
15 | File | `/core/conditions/AbstractWrapper.java` | High
16 | File | `/data/remove` | Medium
17 | File | `/debug/pprof` | Medium
18 | File | `/etc/passwd` | Medium
19 | File | `/face-recognition-php/facepay-master/camera.php` | High
20 | File | `/forms/doLogin` | High
21 | File | `/goform/aspForm` | High
22 | ... | ... | ...

There are 182 more IOA items available (file, library, argument, input value, pattern, network port). Please use our online service to access the data.

## References

The following list contains _external sources_ which discuss the campaign and the associated activities:

* https://us-cert.cisa.gov/ncas/analysis-reports/AR19-100A
* https://www.cisa.gov/uscert/ncas/analysis-reports/ar20-045g
* https://www.us-cert.gov/ncas/analysis-reports/ar20-045g

## Literature

The following _articles_ explain our unique predictive cyber threat intelligence:

* [VulDB Cyber Threat Intelligence Documentation](https://vuldb.com/?kb.cti)
* [Cyber Threat Intelligence - Early Anticipation of Attacks](https://www.scip.ch/en/?labs.20201022)

## License

(c) [1997-2024](https://vuldb.com/?kb.changelog) by [vuldb.com](https://vuldb.com/?kb.about). All data on this page is shared under the license [CC BY-NC-SA 4.0](https://creativecommons.org/licenses/by-nc-sa/4.0/). Questions? Check the [FAQ](https://vuldb.com/?kb.faq), read the [documentation](https://vuldb.com/?kb) or [contact us](https://vuldb.com/?contact)!
