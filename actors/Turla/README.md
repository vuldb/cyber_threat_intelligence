# Turla - Cyber Threat Intelligence

These _indicators_ were reported, collected, and generated during the [VulDB CTI analysis](https://vuldb.com/?kb.cti) of the actor known as [Turla](https://vuldb.com/?actor.turla). The _activity monitoring_ correlates data from social media, forums, chat rooms, and darknet markets. It helps to determine associated actors, specific activities, expected intentions, emerging research, and ongoing attacks. Our unique _predictive model_ uses _big data_ to forecast activities and their characteristics.

_Live data_ and more _analysis capabilities_ are available at [https://vuldb.com/?actor.turla](https://vuldb.com/?actor.turla)

## Campaigns

The following _campaigns_ are known and can be associated with Turla:

* Penquin
* Waterbug
* Whitebear

## Countries

These _countries_ are directly (e.g. origin of attacks) or indirectly (e.g. access by proxy) associated with Turla:

* [FR](https://vuldb.com/?country.fr)
* [US](https://vuldb.com/?country.us)
* [AT](https://vuldb.com/?country.at)
* ...

There are 6 more country items available. Please use our online service to access the data.

## IOC - Indicator of Compromise

These _indicators of compromise_ (IOC) indicate associated network resources which are known to be part of research and attack activities of Turla.

ID | IP address | Hostname | Campaign | Confidence
-- | ---------- | -------- | -------- | ----------
1 | [5.255.93.228](https://vuldb.com/?ip.5.255.93.228) | - | - | High
2 | [45.153.241.162](https://vuldb.com/?ip.45.153.241.162) | - | - | High
3 | [62.12.39.117](https://vuldb.com/?ip.62.12.39.117) | - | Waterbug | High
4 | [62.68.73.57](https://vuldb.com/?ip.62.68.73.57) | - | Waterbug | High
5 | [62.212.226.118](https://vuldb.com/?ip.62.212.226.118) | - | Waterbug | High
6 | [66.178.107.140](https://vuldb.com/?ip.66.178.107.140) | - | Whitebear | High
7 | [70.32.39.219](https://vuldb.com/?ip.70.32.39.219) | am-smartsales.com | - | High
8 | [72.232.222.58](https://vuldb.com/?ip.72.232.222.58) | HOST.MJSHOSTING.COM | Waterbug | High
9 | [77.232.99.77](https://vuldb.com/?ip.77.232.99.77) | - | - | High
10 | [79.110.52.218](https://vuldb.com/?ip.79.110.52.218) | - | - | High
11 | ... | ... | ... | ...

There are 38 more IOC items available. Please use our online service to access the data.

## TTP - Tactics, Techniques, Procedures

_Tactics, techniques, and procedures_ (TTP) summarize the suspected MITRE ATT&CK techniques used by _Turla_. This data is unique as it uses our predictive model for actor profiling.

ID | Technique | Weakness | Description | Confidence
-- | --------- | -------- | ----------- | ----------
1 | T1006 | CWE-21, CWE-22, CWE-23, CWE-425 | Pathname Traversal | High
2 | T1055 | CWE-74 | Injection | High
3 | T1059 | CWE-88, CWE-94 | Cross Site Scripting | High
4 | T1059.007 | CWE-79, CWE-80 | Cross Site Scripting | High
5 | T1068 | CWE-250, CWE-264, CWE-269, CWE-274, CWE-284 | Execution with Unnecessary Privileges | High
6 | ... | ... | ... | ...

There are 18 more TTP items available. Please use our online service to access the data.

## IOA - Indicator of Attack

These _indicators of attack_ (IOA) list the potential fragments used for technical activities like reconnaissance, exploitation, privilege escalation, and exfiltration by Turla. This data is unique as it uses our predictive model for actor profiling.

ID | Type | Indicator | Confidence
-- | ---- | --------- | ----------
1 | File | `%APPDATA%\Securepoint SSL VPN` | High
2 | File | `/Api/ASF` | Medium
3 | File | `/etc/shadow` | Medium
4 | File | `/etc/target/saveconfig.json` | High
5 | File | `/exec` | Low
6 | File | `/form/index.php?module=getjson` | High
7 | File | `/hcms/admin/index.php/language/ajax` | High
8 | File | `/jsonrpc` | Medium
9 | File | `/product.php` | Medium
10 | File | `/ram/pckg/advanced-tools/nova/bin/netwatch` | High
11 | File | `/redpass.cgi` | Medium
12 | File | `/registerCpe` | Medium
13 | File | `/rest/collectors/1.0/template/custom` | High
14 | File | `/system?action=ServiceAdmin` | High
15 | File | `/uncpath/` | Medium
16 | File | `/Uploads` | Medium
17 | File | `/User/saveUser` | High
18 | File | `/webapps/Bb-sites-user-profile-BBLEARN/profile.form` | High
19 | ... | ... | ...

There are 160 more IOA items available (file, library, argument, input value, pattern, network port). Please use our online service to access the data.

## References

The following list contains _external sources_ which discuss the actor and the associated activities:

* https://1275.ru/ioc/252/turla-apt-iocs/
* https://lab52.io/blog/looking-for-penquins-in-the-wild/
* https://securelist.com/introducing-whitebear/81638/
* https://symantec-enterprise-blogs.security.com/blogs/threat-intelligence/waterbug-espionage-governments
* https://www.recordedfuture.com/turla-apt-infrastructure/
* https://www.threatminer.org/report.php?q=TurlarenewsitsarsenalwithTopinambour_Securelist.pdf&y=2019
* https://www.threatminer.org/report.php?q=Turla_2_Penquin.pdf&y=2014
* https://www.threatminer.org/report.php?q=waterbug-attack-group.pdf&y=2015#gsc.tab=0&gsc.q=waterbug-attack-group.pdf&gsc.page=1
* https://www.threatminer.org/_reports/2016/Report_Ruag-Espionage-Case.pdf#viewer.action=download
* https://www.welivesecurity.com/2018/05/22/turla-mosquito-shift-towards-generic-tools/
* https://www.welivesecurity.com/wp-content/uploads/2017/08/eset-gazer.pdf

## Literature

The following _articles_ explain our unique predictive cyber threat intelligence:

* [VulDB Cyber Threat Intelligence Documentation](https://vuldb.com/?kb.cti)
* [Cyber Threat Intelligence - Early Anticipation of Attacks](https://www.scip.ch/en/?labs.20201022)

## License

(c) [1997-2023](https://vuldb.com/?kb.changelog) by [vuldb.com](https://vuldb.com/?kb.about). All data on this page is shared under the license [CC BY-NC-SA 4.0](https://creativecommons.org/licenses/by-nc-sa/4.0/). Questions? Check the [FAQ](https://vuldb.com/?kb.faq), read the [documentation](https://vuldb.com/?kb) or [contact us](https://vuldb.com/?contact)!
