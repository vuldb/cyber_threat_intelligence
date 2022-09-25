# Nanocore - Cyber Threat Intelligence

These _indicators_ were reported, collected, and generated during the [VulDB CTI analysis](https://vuldb.com/?kb.cti) of the actor known as [Nanocore](https://vuldb.com/?actor.nanocore). The _activity monitoring_ correlates data from social media, forums, chat rooms, and darknet markets. It helps to determine associated actors, specific activities, expected intentions, emerging research, and ongoing attacks. Our unique _predictive model_ uses _big data_ to forecast activities and their characteristics.

_Live data_ and more _analysis capabilities_ are available at [https://vuldb.com/?actor.nanocore](https://vuldb.com/?actor.nanocore)

## Campaigns

The following _campaigns_ are known and can be associated with Nanocore:

* Tax-Themed Phishing

## Countries

These _countries_ are directly (e.g. origin of attacks) or indirectly (e.g. access by proxy) associated with Nanocore:

* [US](https://vuldb.com/?country.us)
* [FR](https://vuldb.com/?country.fr)
* [CN](https://vuldb.com/?country.cn)
* ...

There are 12 more country items available. Please use our online service to access the data.

## IOC - Indicator of Compromise

These _indicators of compromise_ (IOC) indicate associated network resources which are known to be part of research and attack activities of Nanocore.

ID | IP address | Hostname | Campaign | Confidence
-- | ---------- | -------- | -------- | ----------
1 | [8.8.8.8](https://vuldb.com/?ip.8.8.8.8) | dns.google | - | High
2 | [20.42.65.92](https://vuldb.com/?ip.20.42.65.92) | - | - | High
3 | [23.235.221.158](https://vuldb.com/?ip.23.235.221.158) | vps53141.inmotionhosting.com | Tax-Themed Phishing | High
4 | [45.133.174.131](https://vuldb.com/?ip.45.133.174.131) | - | - | High
5 | [74.139.80.187](https://vuldb.com/?ip.74.139.80.187) | cpe-74-139-80-187.kya.res.rr.com | - | High
6 | [79.134.225.101](https://vuldb.com/?ip.79.134.225.101) | - | - | High
7 | [79.172.242.25](https://vuldb.com/?ip.79.172.242.25) | hosted.realcapitol.com | - | High
8 | [87.120.37.96](https://vuldb.com/?ip.87.120.37.96) | - | - | High
9 | [95.140.125.64](https://vuldb.com/?ip.95.140.125.64) | free-125-64.mediaworksit.net | - | High
10 | [95.140.125.73](https://vuldb.com/?ip.95.140.125.73) | free-125-73.mediaworksit.net | - | High
11 | ... | ... | ... | ...

There are 38 more IOC items available. Please use our online service to access the data.

## TTP - Tactics, Techniques, Procedures

_Tactics, techniques, and procedures_ (TTP) summarize the suspected MITRE ATT&CK techniques used by _Nanocore_. This data is unique as it uses our predictive model for actor profiling.

ID | Technique | Weakness | Description | Confidence
-- | --------- | -------- | ----------- | ----------
1 | T1006 | CWE-22 | Pathname Traversal | High
2 | T1040 | CWE-319 | Authentication Bypass by Capture-replay | High
3 | T1055 | CWE-74 | Injection | High
4 | T1059 | CWE-88, CWE-94 | Cross Site Scripting | High
5 | ... | ... | ... | ...

There are 14 more TTP items available. Please use our online service to access the data.

## IOA - Indicator of Attack

These _indicators of attack_ (IOA) list the potential fragments used for technical activities like reconnaissance, exploitation, privilege escalation, and exfiltration by Nanocore. This data is unique as it uses our predictive model for actor profiling.

ID | Type | Indicator | Confidence
-- | ---- | --------- | ----------
1 | File | `/cgi-bin/kerbynet` | High
2 | File | `/cgi-bin/supervisor/CloudSetup.cgi` | High
3 | File | `/domain/add` | Medium
4 | File | `/etc/sudoers` | Medium
5 | File | `/forum/away.php` | High
6 | File | `/index.php/weblinks-categories` | High
7 | File | `/php_action/createUser.php` | High
8 | File | `/plain` | Low
9 | File | `/secure/admin/RestoreDefaults.jspa` | High
10 | File | `/services/details.asp` | High
11 | File | `/show_group_members.php` | High
12 | File | `/uncpath/` | Medium
13 | File | `/web/google_analytics.php` | High
14 | File | `/webapps/blogs-journals/execute/editBlogEntry` | High
15 | File | `adclick.php` | Medium
16 | File | `addentry.php` | Medium
17 | File | `additem.asp` | Medium
18 | File | `admin/password_forgotten.php` | High
19 | File | `agent/Core/Controller/SendRequest.cpp` | High
20 | File | `archive_endian.h` | High
21 | File | `bmp.c` | Low
22 | File | `browser.php` | Medium
23 | File | `browser/liferay/browser.html?Type` | High
24 | ... | ... | ...

There are 201 more IOA items available (file, library, argument, input value, pattern, network port). Please use our online service to access the data.

## References

The following list contains _external sources_ which discuss the actor and the associated activities:

* https://blog.talosintelligence.com/2019/09/threat-roundup-0913-0920.html
* https://blog.talosintelligence.com/2021/07/threat-roundup-0716-0723.html
* https://blog.talosintelligence.com/2021/12/threat-roundup-1126-1203.html
* https://blog.talosintelligence.com/2022/04/threat-roundup-0401-0408.html
* https://blog.talosintelligence.com/2022/07/threat-roundup-0715-0722.html
* https://blog.talosintelligence.com/2022/08/threat-roundup-0812-0819.html
* https://blog.talosintelligence.com/2022/09/threat-roundup-0826-0902.html
* https://blog.talosintelligence.com/2022/09/threat-roundup-0909-0916.html
* https://github.com/executemalware/Malware-IOCs/blob/main/2022-01-12%20Remcos%20IOCs
* https://github.com/executemalware/Malware-IOCs/blob/main/2022-02-15%20Nanocore%20IOCs
* https://isc.sans.edu/forums/diary/Malspam+delivers+NanoCore+RAT/21615/
* https://unit42.paloaltonetworks.com/nanocorerat-behind-an-increase-in-tax-themed-phishing-e-mails/

## Literature

The following _articles_ explain our unique predictive cyber threat intelligence:

* [VulDB Cyber Threat Intelligence Documentation](https://vuldb.com/?kb.cti)
* [Cyber Threat Intelligence - Early Anticipation of Attacks](https://www.scip.ch/en/?labs.20201022)

## License

(c) [1997-2022](https://vuldb.com/?kb.changelog) by [vuldb.com](https://vuldb.com/?kb.about). All data on this page is shared under the license [CC BY-NC-SA 4.0](https://creativecommons.org/licenses/by-nc-sa/4.0/). Questions? Check the [FAQ](https://vuldb.com/?kb.faq), read the [documentation](https://vuldb.com/?kb) or [contact us](https://vuldb.com/?contact)!
