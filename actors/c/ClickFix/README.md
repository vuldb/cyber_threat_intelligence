# ClickFix - Cyber Threat Intelligence

These _indicators_ were reported, collected, and generated during the [VulDB CTI analysis](https://vuldb.com/?kb.cti) of the actor known as [ClickFix](https://vuldb.com/?actor.clickfix). The _activity monitoring_ correlates data from social media, forums, chat rooms, and darknet markets. It helps to determine associated actors, specific activities, expected intentions, emerging research, and ongoing attacks. Our unique _predictive model_ uses _big data_ to forecast activities and their characteristics.

_Live data_ and more _analysis capabilities_ are available at [https://vuldb.com/?actor.clickfix](https://vuldb.com/?actor.clickfix)

## Campaigns

The following _campaigns_ are known and can be associated with ClickFix:

* Ghostpulse
* Russia

## Countries

These _countries_ are directly (e.g. origin of attacks) or indirectly (e.g. access by proxy) associated with ClickFix:

* [US](https://vuldb.com/?country.us)
* [RU](https://vuldb.com/?country.ru)
* [UA](https://vuldb.com/?country.ua)
* ...

There are 3 more country items available. Please use our online service to access the data.

## IOC - Indicator of Compromise

These _indicators of compromise_ (IOC) indicate associated network resources which are known to be part of research and attack activities of ClickFix.

ID | IP address | Hostname | Campaign | Confidence
-- | ---------- | -------- | -------- | ----------
1 | [23.227.203.162](https://vuldb.com/?ip.23.227.203.162) | 23-227-203-162.static.hvvc.us | - | High
2 | [23.254.144.106](https://vuldb.com/?ip.23.254.144.106) | andrixdesign.com | - | High
3 | [38.134.148.74](https://vuldb.com/?ip.38.134.148.74) | - | - | High
4 | [45.77.154.115](https://vuldb.com/?ip.45.77.154.115) | 45.77.154.115.vultrusercontent.com | Ghostpulse | Medium
5 | [45.94.47.164](https://vuldb.com/?ip.45.94.47.164) | - | Ghostpulse | High
6 | [45.118.248.29](https://vuldb.com/?ip.45.118.248.29) | - | Ghostpulse | High
7 | [45.141.86.82](https://vuldb.com/?ip.45.141.86.82) | - | Ghostpulse | High
8 | [45.141.86.149](https://vuldb.com/?ip.45.141.86.149) | - | Ghostpulse | High
9 | [45.141.86.159](https://vuldb.com/?ip.45.141.86.159) | - | Ghostpulse | High
10 | [45.141.87.7](https://vuldb.com/?ip.45.141.87.7) | - | Ghostpulse | High
11 | [45.141.87.212](https://vuldb.com/?ip.45.141.87.212) | - | Ghostpulse | High
12 | [45.141.87.249](https://vuldb.com/?ip.45.141.87.249) | - | Ghostpulse | High
13 | [62.60.247.154](https://vuldb.com/?ip.62.60.247.154) | knownveil.aeza.network | Ghostpulse | High
14 | [64.94.84.217](https://vuldb.com/?ip.64.94.84.217) | - | - | High
15 | [65.38.120.47](https://vuldb.com/?ip.65.38.120.47) | - | - | High
16 | [65.109.226.176](https://vuldb.com/?ip.65.109.226.176) | static.176.226.109.65.clients.your-server.de | - | High
17 | [66.63.187.22](https://vuldb.com/?ip.66.63.187.22) | - | Ghostpulse | High
18 | [67.220.72.124](https://vuldb.com/?ip.67.220.72.124) | 20261.us | Ghostpulse | High
19 | [77.237.247.182](https://vuldb.com/?ip.77.237.247.182) | ip-182-247-237-77.static.contabo.net | - | High
20 | [79.124.62.10](https://vuldb.com/?ip.79.124.62.10) | hosting-by.4cloud.mobi | Ghostpulse | High
21 | [80.71.229.25](https://vuldb.com/?ip.80.71.229.25) | - | - | High
22 | [82.117.87.103](https://vuldb.com/?ip.82.117.87.103) | - | Russia | High
23 | [82.117.242.178](https://vuldb.com/?ip.82.117.242.178) | - | Ghostpulse | High
24 | [82.117.255.225](https://vuldb.com/?ip.82.117.255.225) | vds1429036.hosted-by-itldc.com | Ghostpulse | High
25 | [84.200.17.129](https://vuldb.com/?ip.84.200.17.129) | - | Ghostpulse | High
26 | [85.158.110.179](https://vuldb.com/?ip.85.158.110.179) | - | Ghostpulse | High
27 | [91.184.242.37](https://vuldb.com/?ip.91.184.242.37) | divinecopper.aeza.network | Ghostpulse | High
28 | ... | ... | ... | ...

There are 106 more IOC items available. Please use our online service to access the data.

## TTP - Tactics, Techniques, Procedures

_Tactics, techniques, and procedures_ (TTP) summarize the suspected MITRE ATT&CK techniques used by _ClickFix_. This data is unique as it uses our predictive model for actor profiling.

ID | Technique | Weakness | Description | Confidence
-- | --------- | -------- | ----------- | ----------
1 | T1006 | CWE-22, CWE-37 | Path Traversal | High
2 | T1059 | CWE-94 | Argument Injection | High
3 | T1059.007 | CWE-79 | Basic Cross Site Scripting | High
4 | ... | ... | ... | ...

There are 8 more TTP items available. Please use our online service to access the data.

## IOA - Indicator of Attack

These _indicators of attack_ (IOA) list the potential fragments used for technical activities like reconnaissance, exploitation, privilege escalation, and exfiltration by ClickFix. This data is unique as it uses our predictive model for actor profiling.

ID | Type | Indicator | Confidence
-- | ---- | --------- | ----------
1 | File | `/cgi-bin/cstecgi.cgi` | High
2 | File | `/config/pw_changeusers.html` | High
3 | File | `/php/ping.php` | High
4 | File | `/SysInfo1.htm` | High
5 | ... | ... | ...

There are 25 more IOA items available (file, library, argument, input value, pattern, network port). Please use our online service to access the data.

## References

The following list contains _external sources_ which discuss the actor and the associated activities:

* https://bi.zone/eng/expertise/blog/proydite-proverku-i-poluchite-vpo-clickfix-dobralas-do-rossii/
* https://labs.jumpsec.com/malware-as-a-smart-contract-part-1-weaponising-bsc-to-target-windows-users-via-wordpress/
* https://r0ttenbeef.github.io/ClickFix-Malware-Campaign-Analysis/
* https://urlhaus.abuse.ch/url/3559110/
* https://urlhaus.abuse.ch/url/3559114/
* https://urlhaus.abuse.ch/url/3559115/
* https://urlhaus.abuse.ch/url/3559116/
* https://urlhaus.abuse.ch/url/3589402/
* https://urlhaus.abuse.ch/url/3602890/
* https://urlhaus.abuse.ch/url/3606681/
* https://urlhaus.abuse.ch/url/3608216/
* https://urlhaus.abuse.ch/url/3610821/
* https://urlhaus.abuse.ch/url/3610822/
* https://urlhaus.abuse.ch/url/3616698/
* https://urlhaus.abuse.ch/url/3631737/
* https://urlhaus.abuse.ch/url/3696205/
* https://urlhaus.abuse.ch/url/3711137/
* https://www.darktrace.com/blog/unpacking-clickfix-darktraces-detection-of-a-prolific-social-engineering-tactic
* https://www.elastic.co/security-labs/a-wretch-client
* https://www.huntress.com/blog/fake-anydesk-clickfix-metastealer-malware
* https://www.sentinelone.com/blog/how-clickfix-is-weaponizing-verification-fatigue-to-deliver-rats-infostealers/

## Literature

The following _articles_ explain our unique predictive cyber threat intelligence:

* [VulDB Cyber Threat Intelligence Documentation](https://vuldb.com/?kb.cti)
* [Cyber Threat Intelligence - Early Anticipation of Attacks](https://www.scip.ch/en/?labs.20201022)

## License

(c) [1997-2025](https://vuldb.com/?kb.changelog) by [vuldb.com](https://vuldb.com/?kb.about). All data on this page is shared under the license [CC BY-NC-SA 4.0](https://creativecommons.org/licenses/by-nc-sa/4.0/). Questions? Check the [FAQ](https://vuldb.com/?kb.faq), read the [documentation](https://vuldb.com/?kb) or [contact us](https://vuldb.com/?contact)!
