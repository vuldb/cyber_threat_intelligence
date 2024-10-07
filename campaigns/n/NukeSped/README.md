# NukeSped - Cyber Threat Intelligence

These _indicators_ were reported, collected, and generated during the [VulDB CTI analysis](https://vuldb.com/?kb.cti) of the campaign known as _NukeSped_. The _activity monitoring_ correlates data from social media, forums, chat rooms, and darknet markets. It helps to determine associated actors, specific activities, expected intentions, emerging research, and ongoing attacks. Our unique _predictive model_ uses _big data_ to forecast activities and their characteristics.

_Live data_ and more _analysis capabilities_ are available at [https://vuldb.com/?actor](https://vuldb.com/?actor)

## Countries

These _countries_ are directly (e.g. origin of attacks) or indirectly (e.g. access by proxy) associated with NukeSped:

* [HK](https://vuldb.com/?country.hk)
* [US](https://vuldb.com/?country.us)
* [CN](https://vuldb.com/?country.cn)
* ...

There are 4 more country items available. Please use our online service to access the data.

## Actors

These _actors_ are associated with NukeSped or other actors linked to the campaign.

ID | Actor | Confidence
-- | ----- | ----------
1 | [Lazarus](https://vuldb.com/?actor.lazarus) | High
2 | [NukeSped](https://vuldb.com/?actor.nukesped) | High
3 | [Nukesped](https://vuldb.com/?actor.nukesped) | High
4 | ... | ...

There are 1 more actor items available. Please use our online service to access the data.

## IOC - Indicator of Compromise

These _indicators of compromise_ (IOC) indicate associated network resources which are known to be part of research and attack activities of NukeSped.

ID | IP address | Hostname | Actor | Confidence
-- | ---------- | -------- | ----- | ----------
1 | [6.43.51.17](https://vuldb.com/?ip.6.43.51.17) | - | [Nukesped](https://vuldb.com/?actor.nukesped) | High
2 | [27.102.114.215](https://vuldb.com/?ip.27.102.114.215) | - | [Andariel](https://vuldb.com/?actor.andariel) | High
3 | [46.105.57.169](https://vuldb.com/?ip.46.105.57.169) | cluster020.hosting.ovh.net | [NukeSped](https://vuldb.com/?actor.nukesped) | High
4 | [50.192.28.29](https://vuldb.com/?ip.50.192.28.29) | speed-stream.com | [NukeSped](https://vuldb.com/?actor.nukesped) | High
5 | ... | ... | ... | ...

There are 14 more IOC items available. Please use our online service to access the data.

## TTP - Tactics, Techniques, Procedures

_Tactics, techniques, and procedures_ (TTP) summarize the suspected MITRE ATT&CK techniques used within NukeSped. This data is unique as it uses our predictive model for actor profiling.

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

These _indicators of attack_ (IOA) list the potential fragments used for technical activities like reconnaissance, exploitation, privilege escalation, and exfiltration during NukeSped. This data is unique as it uses our predictive model for actor profiling.

ID | Type | Indicator | Confidence
-- | ---- | --------- | ----------
1 | File | `/?g=net_pro_keyword_import_save` | High
2 | File | `/admin-panel1.php` | High
3 | File | `/admin/academic/studenview_left.php` | High
4 | File | `/admin/ajax.php` | High
5 | File | `/admin/ajax.php?action=confirm_order` | High
6 | File | `/admin/controller/JobLogController.java` | High
7 | File | `/admin/login.php` | High
8 | File | `/ad_js.php` | Medium
9 | File | `/alerts/alertConfigField.php` | High
10 | File | `/api/blade-log/api/list` | High
11 | File | `/api/v1/terminal/sessions/?limit=1` | High
12 | File | `/blog` | Low
13 | File | `/cgi-bin/nas_sharing.cgi` | High
14 | File | `/config/myfield/test.php` | High
15 | File | `/context/%2e/WEB-INF/web.xml` | High
16 | File | `/core/conditions/AbstractWrapper.java` | High
17 | File | `/data/remove` | Medium
18 | File | `/debug/pprof` | Medium
19 | File | `/etc/passwd` | Medium
20 | File | `/face-recognition-php/facepay-master/camera.php` | High
21 | File | `/forms/doLogin` | High
22 | File | `/forum/away.php` | High
23 | File | `/fuel/index.php/fuel/logs/items` | High
24 | File | `/fuel/index.php/fuel/pages/items` | High
25 | File | `/goform/aspForm` | High
26 | File | `/index.php` | Medium
27 | File | `/lists/index.php` | High
28 | File | `/mkshop/Men/profile.php` | High
29 | ... | ... | ...

There are 250 more IOA items available (file, library, argument, input value, pattern, network port). Please use our online service to access the data.

## References

The following list contains _external sources_ which discuss the campaign and the associated activities:

* https://asec.ahnlab.com/en/34461/
* https://asec.ahnlab.com/en/59318/
* https://github.com/eset/malware-ioc/tree/master/nukesped_lazarus
* https://www.fortinet.com/blog/threat-research/deep-analysis-nukesped-rat.html

## Literature

The following _articles_ explain our unique predictive cyber threat intelligence:

* [VulDB Cyber Threat Intelligence Documentation](https://vuldb.com/?kb.cti)
* [Cyber Threat Intelligence - Early Anticipation of Attacks](https://www.scip.ch/en/?labs.20201022)

## License

(c) [1997-2024](https://vuldb.com/?kb.changelog) by [vuldb.com](https://vuldb.com/?kb.about). All data on this page is shared under the license [CC BY-NC-SA 4.0](https://creativecommons.org/licenses/by-nc-sa/4.0/). Questions? Check the [FAQ](https://vuldb.com/?kb.faq), read the [documentation](https://vuldb.com/?kb) or [contact us](https://vuldb.com/?contact)!
