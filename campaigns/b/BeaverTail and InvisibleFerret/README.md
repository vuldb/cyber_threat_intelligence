# BeaverTail and InvisibleFerret - Cyber Threat Intelligence

These _indicators_ were reported, collected, and generated during the [VulDB CTI analysis](https://vuldb.com/?kb.cti) of the campaign known as _BeaverTail and InvisibleFerret_. The _activity monitoring_ correlates data from social media, forums, chat rooms, and darknet markets. It helps to determine associated actors, specific activities, expected intentions, emerging research, and ongoing attacks. Our unique _predictive model_ uses _big data_ to forecast activities and their characteristics.

_Live data_ and more _analysis capabilities_ are available at [https://vuldb.com/?actor](https://vuldb.com/?actor)

## Countries

These _countries_ are directly (e.g. origin of attacks) or indirectly (e.g. access by proxy) associated with BeaverTail and InvisibleFerret:

* [US](https://vuldb.com/?country.us)
* [CN](https://vuldb.com/?country.cn)
* [AE](https://vuldb.com/?country.ae)
* ...

There are 15 more country items available. Please use our online service to access the data.

## Actors

These _actors_ are associated with BeaverTail and InvisibleFerret or other actors linked to the campaign.

ID | Actor | Confidence
-- | ----- | ----------
1 | [DPRK](https://vuldb.com/?actor.dprk) | High

## IOC - Indicator of Compromise

These _indicators of compromise_ (IOC) indicate associated network resources which are known to be part of research and attack activities of BeaverTail and InvisibleFerret.

ID | IP address | Hostname | Actor | Confidence
-- | ---------- | -------- | ----- | ----------
1 | [5.253.43.122](https://vuldb.com/?ip.5.253.43.122) | vm15273327.example.com | [DPRK](https://vuldb.com/?actor.dprk) | High
2 | [23.106.70.154](https://vuldb.com/?ip.23.106.70.154) | - | [DPRK](https://vuldb.com/?actor.dprk) | High
3 | [23.106.253.194](https://vuldb.com/?ip.23.106.253.194) | - | [DPRK](https://vuldb.com/?actor.dprk) | High
4 | [23.106.253.215](https://vuldb.com/?ip.23.106.253.215) | - | [DPRK](https://vuldb.com/?actor.dprk) | High
5 | [23.106.253.221](https://vuldb.com/?ip.23.106.253.221) | - | [DPRK](https://vuldb.com/?actor.dprk) | High
6 | [23.106.253.242](https://vuldb.com/?ip.23.106.253.242) | - | [DPRK](https://vuldb.com/?actor.dprk) | High
7 | [23.227.202.242](https://vuldb.com/?ip.23.227.202.242) | 23-227-202-242.static.hvvc.us | [DPRK](https://vuldb.com/?actor.dprk) | High
8 | [23.227.202.244](https://vuldb.com/?ip.23.227.202.244) | 23-227-202-244.static.hvvc.us | [DPRK](https://vuldb.com/?actor.dprk) | High
9 | [23.254.164.156](https://vuldb.com/?ip.23.254.164.156) | hwsrv-1275092.hostwindsdns.com | [DPRK](https://vuldb.com/?actor.dprk) | High
10 | [38.92.47.85](https://vuldb.com/?ip.38.92.47.85) | - | [DPRK](https://vuldb.com/?actor.dprk) | High
11 | ... | ... | ... | ...

There are 38 more IOC items available. Please use our online service to access the data.

## TTP - Tactics, Techniques, Procedures

_Tactics, techniques, and procedures_ (TTP) summarize the suspected MITRE ATT&CK techniques used within BeaverTail and InvisibleFerret. This data is unique as it uses our predictive model for actor profiling.

ID | Technique | Weakness | Description | Confidence
-- | --------- | -------- | ----------- | ----------
1 | T1006 | CWE-22 | Path Traversal | High
2 | T1055 | CWE-74 | Improper Neutralization of Data within XPath Expressions | High
3 | T1059 | CWE-88, CWE-94, CWE-1321 | Argument Injection | High
4 | T1059.007 | CWE-79, CWE-80 | Basic Cross Site Scripting | High
5 | ... | ... | ... | ...

There are 14 more TTP items available. Please use our online service to access the data.

## IOA - Indicator of Attack

These _indicators of attack_ (IOA) list the potential fragments used for technical activities like reconnaissance, exploitation, privilege escalation, and exfiltration during BeaverTail and InvisibleFerret. This data is unique as it uses our predictive model for actor profiling.

ID | Type | Indicator | Confidence
-- | ---- | --------- | ----------
1 | File | `.user` | Low
2 | File | `/admin-api/mp/material/upload-permanent` | High
3 | File | `/admin.php/appcenter/local.html?type=addon` | High
4 | File | `/admin/?page=system_info` | High
5 | File | `/admin/create_product.php` | High
6 | File | `/admin/invoice.php` | High
7 | File | `/api/ServiceAgent/start_service` | High
8 | File | `/backend/admin/his_admin_add_lab_equipment.php` | High
9 | File | `/category_view.php` | High
10 | File | `/cgi-bin/cstecgi.cgi` | High
11 | File | `/cgi-bin/wlogin.cgi` | High
12 | File | `/classes/Master.php` | High
13 | File | `/druid/index.html` | High
14 | File | `/film-rating.php` | High
15 | File | `/forum/away.php` | High
16 | File | `/hospital/hms/admin/manage-doctors.php` | High
17 | File | `/index.php/Login/login` | High
18 | File | `/index.php?r=admin/database/index/updatesurveylocalesettings_generalsettings` | High
19 | File | `/index/ajax/lang` | High
20 | File | `/librarian/bookdetails.php` | High
21 | File | `/login.php` | Medium
22 | File | `/modules/profile/index.php` | High
23 | File | `/opt/tms/bin/cli` | High
24 | File | `/out.php` | Medium
25 | File | `/owa/auth/logon.aspx` | High
26 | File | `/php-jms/review_se_result.php` | High
27 | ... | ... | ...

There are 227 more IOA items available (file, library, argument, input value, pattern, network port). Please use our online service to access the data.

## References

The following list contains _external sources_ which discuss the campaign and the associated activities:

* https://blog.nviso.eu/2025/11/13/contagious-interview-actors-now-utilize-json-storage-services-for-malware-delivery/

## Literature

The following _articles_ explain our unique predictive cyber threat intelligence:

* [VulDB Cyber Threat Intelligence Documentation](https://vuldb.com/?kb.cti)
* [Cyber Threat Intelligence - Early Anticipation of Attacks](https://www.scip.ch/en/?labs.20201022)

## License

(c) [1997-2026](https://vuldb.com/?kb.changelog) by [vuldb.com](https://vuldb.com/?kb.about). All data on this page is shared under the license [CC BY-NC-SA 4.0](https://creativecommons.org/licenses/by-nc-sa/4.0/). Questions? Check the [FAQ](https://vuldb.com/?kb.faq), read the [documentation](https://vuldb.com/?kb) or [contact us](https://vuldb.com/?contact)!
