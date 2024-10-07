# Autoit - Cyber Threat Intelligence

These _indicators_ were reported, collected, and generated during the [VulDB CTI analysis](https://vuldb.com/?kb.cti) of the actor known as [Autoit](https://vuldb.com/?actor.autoit). The _activity monitoring_ correlates data from social media, forums, chat rooms, and darknet markets. It helps to determine associated actors, specific activities, expected intentions, emerging research, and ongoing attacks. Our unique _predictive model_ uses _big data_ to forecast activities and their characteristics.

_Live data_ and more _analysis capabilities_ are available at [https://vuldb.com/?actor.autoit](https://vuldb.com/?actor.autoit)

## Campaigns

The following _campaigns_ are known and can be associated with Autoit:

* StealC/Amadey/Credential Flusher

## Countries

These _countries_ are directly (e.g. origin of attacks) or indirectly (e.g. access by proxy) associated with Autoit:

* [US](https://vuldb.com/?country.us)
* [IO](https://vuldb.com/?country.io)
* [DE](https://vuldb.com/?country.de)
* ...

There are 6 more country items available. Please use our online service to access the data.

## IOC - Indicator of Compromise

These _indicators of compromise_ (IOC) indicate associated network resources which are known to be part of research and attack activities of Autoit.

ID | IP address | Hostname | Campaign | Confidence
-- | ---------- | -------- | -------- | ----------
1 | [5.206.225.104](https://vuldb.com/?ip.5.206.225.104) | hosted-by.blazingfast.io | - | High
2 | [8.248.165.254](https://vuldb.com/?ip.8.248.165.254) | - | - | High
3 | [8.249.217.254](https://vuldb.com/?ip.8.249.217.254) | - | - | High
4 | [8.253.131.121](https://vuldb.com/?ip.8.253.131.121) | - | - | High
5 | [13.56.128.67](https://vuldb.com/?ip.13.56.128.67) | screenconnect.medsphere.com | - | High
6 | [23.3.13.88](https://vuldb.com/?ip.23.3.13.88) | a23-3-13-88.deploy.static.akamaitechnologies.com | - | High
7 | [23.3.13.154](https://vuldb.com/?ip.23.3.13.154) | a23-3-13-154.deploy.static.akamaitechnologies.com | - | High
8 | [23.63.245.19](https://vuldb.com/?ip.23.63.245.19) | a23-63-245-19.deploy.static.akamaitechnologies.com | - | High
9 | [23.63.245.50](https://vuldb.com/?ip.23.63.245.50) | a23-63-245-50.deploy.static.akamaitechnologies.com | - | High
10 | [23.199.71.136](https://vuldb.com/?ip.23.199.71.136) | a23-199-71-136.deploy.static.akamaitechnologies.com | - | High
11 | ... | ... | ... | ...

There are 40 more IOC items available. Please use our online service to access the data.

## TTP - Tactics, Techniques, Procedures

_Tactics, techniques, and procedures_ (TTP) summarize the suspected MITRE ATT&CK techniques used by _Autoit_. This data is unique as it uses our predictive model for actor profiling.

ID | Technique | Weakness | Description | Confidence
-- | --------- | -------- | ----------- | ----------
1 | T1006 | CWE-21, CWE-22, CWE-23 | Path Traversal | High
2 | T1040 | CWE-319 | Authentication Bypass by Capture-replay | High
3 | T1055 | CWE-74 | Improper Neutralization of Data within XPath Expressions | High
4 | T1059 | CWE-88, CWE-94 | Argument Injection | High
5 | T1059.007 | CWE-79, CWE-80 | Cross Site Scripting | High
6 | ... | ... | ... | ...

There are 20 more TTP items available. Please use our online service to access the data.

## IOA - Indicator of Attack

These _indicators of attack_ (IOA) list the potential fragments used for technical activities like reconnaissance, exploitation, privilege escalation, and exfiltration by Autoit. This data is unique as it uses our predictive model for actor profiling.

ID | Type | Indicator | Confidence
-- | ---- | --------- | ----------
1 | File | `/appLms/ajax.server.php` | High
2 | File | `/apps/` | Low
3 | File | `/etc/shadow` | Medium
4 | File | `/mgmt/tm/util/bash` | High
5 | File | `/ofrs/admin/?page=reports` | High
6 | File | `/onlineordering/GPST/store/initiateorder.php` | High
7 | File | `/products/details.asp` | High
8 | File | `/public/login.htm` | High
9 | File | `/RPC2` | Low
10 | File | `/rup` | Low
11 | File | `/secure/QueryComponent!Default.jspa` | High
12 | File | `/show_news.php` | High
13 | File | `/var/hnap/timestamp` | High
14 | File | `Addons/file/mod.file.php` | High
15 | File | `admin-ajax.php` | High
16 | File | `admin.color.php` | High
17 | File | `admin.php` | Medium
18 | File | `admin/admin_login.php` | High
19 | File | `admin/index.php?page=manage_car` | High
20 | File | `admin/media.php` | High
21 | File | `admin_events.php` | High
22 | File | `affich.php` | Medium
23 | ... | ... | ...

There are 189 more IOA items available (file, library, argument, input value, pattern, network port). Please use our online service to access the data.

## References

The following list contains _external sources_ which discuss the actor and the associated activities:

* https://blog.talosintelligence.com/2019/03/threat-roundup-for-mar-01-to-mar-08.html
* https://blog.talosintelligence.com/2019/04/threat-roundup-0329-0405.html
* https://blog.talosintelligence.com/2020/02/threat-roundup-0214-0221.html
* https://blog.talosintelligence.com/2021/08/threat-roundup-0730-0806.html
* https://blog.talosintelligence.com/2021/09/threat-roundup-0827-0903.html
* https://blog.talosintelligence.com/2021/09/threat-roundup-0910-0917.html
* https://blog.talosintelligence.com/2022/03/threat-roundup-0318-0325.html
* https://de.darktrace.com/blog/growing-your-onion-autoit-malware-in-the-darktrace-kill-chain
* https://github.com/esThreatIntelligence/iocs/blob/main/AutoIT/AutoIT_VidarStealer-5-19-2024.txt
* https://isc.sans.edu/forums/diary/Brazilian+malspam+sends+Autoitbased+malware/22081/
* https://research.openanalysis.net/credflusher/kiosk/stealer/stealc/amadey/autoit/2024/09/11/cred-flusher.html

## Literature

The following _articles_ explain our unique predictive cyber threat intelligence:

* [VulDB Cyber Threat Intelligence Documentation](https://vuldb.com/?kb.cti)
* [Cyber Threat Intelligence - Early Anticipation of Attacks](https://www.scip.ch/en/?labs.20201022)

## License

(c) [1997-2024](https://vuldb.com/?kb.changelog) by [vuldb.com](https://vuldb.com/?kb.about). All data on this page is shared under the license [CC BY-NC-SA 4.0](https://creativecommons.org/licenses/by-nc-sa/4.0/). Questions? Check the [FAQ](https://vuldb.com/?kb.faq), read the [documentation](https://vuldb.com/?kb) or [contact us](https://vuldb.com/?contact)!
