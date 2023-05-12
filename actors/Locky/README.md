# Locky - Cyber Threat Intelligence

These _indicators_ were reported, collected, and generated during the [VulDB CTI analysis](https://vuldb.com/?kb.cti) of the actor known as [Locky](https://vuldb.com/?actor.locky). The _activity monitoring_ correlates data from social media, forums, chat rooms, and darknet markets. It helps to determine associated actors, specific activities, expected intentions, emerging research, and ongoing attacks. Our unique _predictive model_ uses _big data_ to forecast activities and their characteristics.

_Live data_ and more _analysis capabilities_ are available at [https://vuldb.com/?actor.locky](https://vuldb.com/?actor.locky)

## Countries

These _countries_ are directly (e.g. origin of attacks) or indirectly (e.g. access by proxy) associated with Locky:

* [US](https://vuldb.com/?country.us)
* [RU](https://vuldb.com/?country.ru)
* [ES](https://vuldb.com/?country.es)
* ...

There are 11 more country items available. Please use our online service to access the data.

## IOC - Indicator of Compromise

These _indicators of compromise_ (IOC) indicate associated network resources which are known to be part of research and attack activities of Locky.

ID | IP address | Hostname | Campaign | Confidence
-- | ---------- | -------- | -------- | ----------
1 | [5.173.164.205](https://vuldb.com/?ip.5.173.164.205) | user-5-173-164-205.play-internet.pl | - | High
2 | [13.107.21.200](https://vuldb.com/?ip.13.107.21.200) | - | - | High
3 | [37.187.0.40](https://vuldb.com/?ip.37.187.0.40) | ns3108067.ip-37-187-0.eu | - | High
4 | [46.38.52.225](https://vuldb.com/?ip.46.38.52.225) | free.tel.ru | - | High
5 | [46.101.8.169](https://vuldb.com/?ip.46.101.8.169) | - | - | High
6 | [46.148.20.32](https://vuldb.com/?ip.46.148.20.32) | sa3.net.ua | - | High
7 | [46.183.165.45](https://vuldb.com/?ip.46.183.165.45) | - | - | High
8 | ... | ... | ... | ...

There are 27 more IOC items available. Please use our online service to access the data.

## TTP - Tactics, Techniques, Procedures

_Tactics, techniques, and procedures_ (TTP) summarize the suspected MITRE ATT&CK techniques used by _Locky_. This data is unique as it uses our predictive model for actor profiling.

ID | Technique | Weakness | Description | Confidence
-- | --------- | -------- | ----------- | ----------
1 | T1006 | CWE-21, CWE-22 | Pathname Traversal | High
2 | T1040 | CWE-319 | Authentication Bypass by Capture-replay | High
3 | T1055 | CWE-74 | Injection | High
4 | T1059 | CWE-88, CWE-94 | Cross Site Scripting | High
5 | T1059.007 | CWE-79, CWE-80 | Cross Site Scripting | High
6 | ... | ... | ... | ...

There are 21 more TTP items available. Please use our online service to access the data.

## IOA - Indicator of Attack

These _indicators of attack_ (IOA) list the potential fragments used for technical activities like reconnaissance, exploitation, privilege escalation, and exfiltration by Locky. This data is unique as it uses our predictive model for actor profiling.

ID | Type | Indicator | Confidence
-- | ---- | --------- | ----------
1 | File | `%PROGRAMDATA%\OpenVPN Connect\drivers\tap\amd64\win10` | High
2 | File | `%PROGRAMDATA%\Razer\Synapse3\Service\bin` | High
3 | File | `.authlie` | Medium
4 | File | `.htaccess` | Medium
5 | File | `/+CSCOE+/logon.html` | High
6 | File | `/admin/settings/sites/new` | High
7 | File | `/advanced/adv_dns.xgi` | High
8 | File | `/folder/list` | Medium
9 | File | `/forms/nslookupHandler` | High
10 | File | `/goform/GetNewDir` | High
11 | File | `/goform/right_now_d` | High
12 | File | `/group/comment` | High
13 | File | `/home/home_parent.xgi` | High
14 | File | `/inc/HTTPClient.php` | High
15 | File | `/index.php?controller=calendar&format=raw&cat[0]=SQLi&task=events` | High
16 | File | `/ISAPI/Security/users/1` | High
17 | File | `/lookin/info` | Medium
18 | File | `/out.php` | Medium
19 | File | `/plugins/servlet/jira-blockers/` | High
20 | File | `/sessions/sess_<sessionid>` | High
21 | File | `/status/status_log.sys` | High
22 | File | `/themes/<php_file_name>` | High
23 | File | `/tmp` | Low
24 | File | `/uncpath/` | Medium
25 | File | `/upload` | Low
26 | File | `adclick.php` | Medium
27 | File | `addentry.php` | Medium
28 | File | `admin-ajax.php` | High
29 | File | `admin.php` | Medium
30 | File | `admin/fm/` | Medium
31 | File | `admin/pages/*/edit` | High
32 | File | `admincp/attachment.php&do=rebuild&type` | High
33 | File | `administrator/index.php?option=com_pago&view=comments` | High
34 | File | `ajax_mod_security.php` | High
35 | File | `ajax_service.php` | High
36 | File | `appconfig.php` | High
37 | ... | ... | ...

There are 321 more IOA items available (file, library, argument, input value, pattern, network port). Please use our online service to access the data.

## References

The following list contains _external sources_ which discuss the actor and the associated activities:

* https://blog.talosintelligence.com/2022/08/threat-roundup-0812-0819.html
* https://blog.talosintelligence.com/threat-roundup-0217-0224/
* https://blog.talosintelligence.com/threat-roundup-0310-0317/
* https://blogs.blackberry.com/en/2017/11/threat-spotlight-locky-ransomware
* https://github.com/fl0x2208/IOCs-in-CSV-format/blob/6297513d672bd69f1bf488018035892e599e7a9c/locky%20ransomware.csv
* https://isc.sans.edu/forums/diary/Malspam+pushing+Locky+ransomware+tries+HoeflerText+notifications+for+Chrome+and+FireFox/22776/
* https://isc.sans.edu/forums/diary/Ongoing+Ykcol+Locky+campaign/22848/
* https://unit42.paloaltonetworks.com/locky-ransomware-installed-through-nuclear-ek/

## Literature

The following _articles_ explain our unique predictive cyber threat intelligence:

* [VulDB Cyber Threat Intelligence Documentation](https://vuldb.com/?kb.cti)
* [Cyber Threat Intelligence - Early Anticipation of Attacks](https://www.scip.ch/en/?labs.20201022)

## License

(c) [1997-2023](https://vuldb.com/?kb.changelog) by [vuldb.com](https://vuldb.com/?kb.about). All data on this page is shared under the license [CC BY-NC-SA 4.0](https://creativecommons.org/licenses/by-nc-sa/4.0/). Questions? Check the [FAQ](https://vuldb.com/?kb.faq), read the [documentation](https://vuldb.com/?kb) or [contact us](https://vuldb.com/?contact)!
