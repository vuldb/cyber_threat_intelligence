# Mars Stealer - Cyber Threat Intelligence

These _indicators_ were reported, collected, and generated during the [VulDB CTI analysis](https://vuldb.com/?kb.cti) of the actor known as [Mars Stealer](https://vuldb.com/?actor.mars_stealer). The _activity monitoring_ correlates data from social media, forums, chat rooms, and darknet markets. It helps to determine associated actors, specific activities, expected intentions, emerging research, and ongoing attacks. Our unique _predictive model_ uses _big data_ to forecast activities and their characteristics.

_Live data_ and more _analysis capabilities_ are available at [https://vuldb.com/?actor.mars_stealer](https://vuldb.com/?actor.mars_stealer)

## Countries

These _countries_ are directly (e.g. origin of attacks) or indirectly (e.g. access by proxy) associated with Mars Stealer:

* [US](https://vuldb.com/?country.us)
* [DE](https://vuldb.com/?country.de)
* [RU](https://vuldb.com/?country.ru)
* ...

There are 14 more country items available. Please use our online service to access the data.

## IOC - Indicator of Compromise

These _indicators of compromise_ (IOC) indicate associated network resources which are known to be part of research and attack activities of Mars Stealer.

ID | IP address | Hostname | Campaign | Confidence
-- | ---------- | -------- | -------- | ----------
1 | [5.45.84.214](https://vuldb.com/?ip.5.45.84.214) | - | - | High
2 | [5.63.155.126](https://vuldb.com/?ip.5.63.155.126) | 5-63-155-126.cloudvps.regruhosting.ru | - | High
3 | [5.181.80.130](https://vuldb.com/?ip.5.181.80.130) | ip-80-130-bullethost.net | - | High
4 | [13.58.70.215](https://vuldb.com/?ip.13.58.70.215) | ec2-13-58-70-215.us-east-2.compute.amazonaws.com | - | Medium
5 | [20.185.186.224](https://vuldb.com/?ip.20.185.186.224) | - | - | High
6 | [23.239.9.184](https://vuldb.com/?ip.23.239.9.184) | 23-239-9-184.ip.linodeusercontent.com | - | High
7 | [45.9.20.31](https://vuldb.com/?ip.45.9.20.31) | - | - | High
8 | [45.67.230.47](https://vuldb.com/?ip.45.67.230.47) | vm718000.stark-industries.solutions | - | High
9 | [45.77.112.250](https://vuldb.com/?ip.45.77.112.250) | 45.77.112.250.vultrusercontent.com | - | High
10 | [45.140.147.99](https://vuldb.com/?ip.45.140.147.99) | vm716958.stark-industries.solutions | - | High
11 | [62.3.12.9](https://vuldb.com/?ip.62.3.12.9) | zserg.ch | - | High
12 | [62.113.99.76](https://vuldb.com/?ip.62.113.99.76) | - | - | High
13 | ... | ... | ... | ...

There are 47 more IOC items available. Please use our online service to access the data.

## TTP - Tactics, Techniques, Procedures

_Tactics, techniques, and procedures_ (TTP) summarize the suspected MITRE ATT&CK techniques used by _Mars Stealer_. This data is unique as it uses our predictive model for actor profiling.

ID | Technique | Weakness | Description | Confidence
-- | --------- | -------- | ----------- | ----------
1 | T1006 | CWE-21, CWE-22 | Pathname Traversal | High
2 | T1055 | CWE-74 | Injection | High
3 | T1059 | CWE-94, CWE-1321 | Cross Site Scripting | High
4 | T1059.007 | CWE-79, CWE-80 | Cross Site Scripting | High
5 | ... | ... | ... | ...

There are 17 more TTP items available. Please use our online service to access the data.

## IOA - Indicator of Attack

These _indicators of attack_ (IOA) list the potential fragments used for technical activities like reconnaissance, exploitation, privilege escalation, and exfiltration by Mars Stealer. This data is unique as it uses our predictive model for actor profiling.

ID | Type | Indicator | Confidence
-- | ---- | --------- | ----------
1 | File | `/Admin/add-student.php` | High
2 | File | `/admin/api/theme-edit/` | High
3 | File | `/admin/communitymanagement.php` | High
4 | File | `/admin/generalsettings.php` | High
5 | File | `/admin/payment.php` | High
6 | File | `/admin/transactions/update_status.php` | High
7 | File | `/api/user/password/sent-reset-email` | High
8 | File | `/aqpg/users/login.php` | High
9 | File | `/bsms_ci/index.php/user/edit_user/` | High
10 | File | `/dashboard/add-service.php` | High
11 | File | `/dashboard/updatelogo.php` | High
12 | File | `/Default/Bd` | Medium
13 | File | `/download` | Medium
14 | File | `/event/admin/?page=user/list` | High
15 | File | `/face-recognition-php/facepay-master/camera.php` | High
16 | File | `/filemanager/upload/drop` | High
17 | File | `/forum/away.php` | High
18 | File | `/forum/PostPrivateMessage` | High
19 | File | `/getcfg.php` | Medium
20 | File | `/goform/RouteStatic` | High
21 | File | `/home/masterConsole` | High
22 | File | `/hrm/employeeadd.php` | High
23 | File | `/hrm/employeeview.php` | High
24 | File | `/htdocs/cgibin` | High
25 | File | `/lists/index.php` | High
26 | File | `/login.php` | Medium
27 | File | `/netflow/jspui/editProfile.jsp` | High
28 | File | `/spip.php` | Medium
29 | File | `/uncpath/` | Medium
30 | File | `/usr/www/ja/mnt_cmd.cgi` | High
31 | File | `/videotalk` | Medium
32 | ... | ... | ...

There are 273 more IOA items available (file, library, argument, input value, pattern, network port). Please use our online service to access the data.

## References

The following list contains _external sources_ which discuss the actor and the associated activities:

* https://blog.morphisec.com/threat-research-mars-stealer
* https://cert.gov.ua/article/38606
* https://community.blueliv.com/#!/s/628bf72a82df417b9232fc80
* https://gist.github.com/viriback/362a91ed9601ba906d8a17c8102a68bb
* https://github.com/SEKOIA-IO/Community/blob/main/IOCs/marsstealer/mars_stealer_iocs_20220407.csv
* https://isc.sans.edu/forums/diary/Arkei+Variants+From+Vidar+to+Mars+Stealer/28468/

## Literature

The following _articles_ explain our unique predictive cyber threat intelligence:

* [VulDB Cyber Threat Intelligence Documentation](https://vuldb.com/?kb.cti)
* [Cyber Threat Intelligence - Early Anticipation of Attacks](https://www.scip.ch/en/?labs.20201022)

## License

(c) [1997-2023](https://vuldb.com/?kb.changelog) by [vuldb.com](https://vuldb.com/?kb.about). All data on this page is shared under the license [CC BY-NC-SA 4.0](https://creativecommons.org/licenses/by-nc-sa/4.0/). Questions? Check the [FAQ](https://vuldb.com/?kb.faq), read the [documentation](https://vuldb.com/?kb) or [contact us](https://vuldb.com/?contact)!
