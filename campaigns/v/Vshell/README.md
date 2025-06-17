# Vshell - Cyber Threat Intelligence

These _indicators_ were reported, collected, and generated during the [VulDB CTI analysis](https://vuldb.com/?kb.cti) of the campaign known as _Vshell_. The _activity monitoring_ correlates data from social media, forums, chat rooms, and darknet markets. It helps to determine associated actors, specific activities, expected intentions, emerging research, and ongoing attacks. Our unique _predictive model_ uses _big data_ to forecast activities and their characteristics.

_Live data_ and more _analysis capabilities_ are available at [https://vuldb.com/?actor](https://vuldb.com/?actor)

## Countries

These _countries_ are directly (e.g. origin of attacks) or indirectly (e.g. access by proxy) associated with Vshell:

* [CN](https://vuldb.com/?country.cn)
* [DE](https://vuldb.com/?country.de)
* [SV](https://vuldb.com/?country.sv)
* ...

There are 9 more country items available. Please use our online service to access the data.

## Actors

These _actors_ are associated with Vshell or other actors linked to the campaign.

ID | Actor | Confidence
-- | ----- | ----------
1 | [Earth Lamia](https://vuldb.com/?actor.earth_lamia) | High
2 | [Vshell](https://vuldb.com/?actor.vshell) | High

## IOC - Indicator of Compromise

These _indicators of compromise_ (IOC) indicate associated network resources which are known to be part of research and attack activities of Vshell.

ID | IP address | Hostname | Actor | Confidence
-- | ---------- | -------- | ----- | ----------
1 | [38.207.178.156](https://vuldb.com/?ip.38.207.178.156) | - | [Vshell](https://vuldb.com/?actor.vshell) | High
2 | [47.74.4.13](https://vuldb.com/?ip.47.74.4.13) | - | [Vshell](https://vuldb.com/?actor.vshell) | High
3 | [47.109.178.63](https://vuldb.com/?ip.47.109.178.63) | - | [Vshell](https://vuldb.com/?actor.vshell) | High
4 | [47.116.123.8](https://vuldb.com/?ip.47.116.123.8) | - | [Vshell](https://vuldb.com/?actor.vshell) | High
5 | [47.121.30.118](https://vuldb.com/?ip.47.121.30.118) | - | [Vshell](https://vuldb.com/?actor.vshell) | High
6 | [64.69.34.217](https://vuldb.com/?ip.64.69.34.217) | - | [Vshell](https://vuldb.com/?actor.vshell) | High
7 | [103.30.76.206](https://vuldb.com/?ip.103.30.76.206) | - | [Earth Lamia](https://vuldb.com/?actor.earth_lamia) | High
8 | ... | ... | ... | ...

There are 26 more IOC items available. Please use our online service to access the data.

## TTP - Tactics, Techniques, Procedures

_Tactics, techniques, and procedures_ (TTP) summarize the suspected MITRE ATT&CK techniques used within Vshell. This data is unique as it uses our predictive model for actor profiling.

ID | Technique | Weakness | Description | Confidence
-- | --------- | -------- | ----------- | ----------
1 | T1006 | CWE-21, CWE-22, CWE-23, CWE-36 | Path Traversal | High
2 | T1040 | CWE-294 | Authentication Bypass by Capture-replay | High
3 | T1055 | CWE-74 | Improper Neutralization of Data within XPath Expressions | High
4 | T1059 | CWE-94, CWE-1321 | Argument Injection | High
5 | ... | ... | ... | ...

There are 17 more TTP items available. Please use our online service to access the data.

## IOA - Indicator of Attack

These _indicators of attack_ (IOA) list the potential fragments used for technical activities like reconnaissance, exploitation, privilege escalation, and exfiltration during Vshell. This data is unique as it uses our predictive model for actor profiling.

ID | Type | Indicator | Confidence
-- | ---- | --------- | ----------
1 | File | `/admin/admintools/tool.php` | High
2 | File | `/admin/ajax.php?action=confirm_order` | High
3 | File | `/admin/ajax.php?action=save_area` | High
4 | File | `/admin/company/index.php` | High
5 | File | `/admin/contactus.php` | High
6 | File | `/admin/index2.html` | High
7 | File | `/admin/settings.php` | High
8 | File | `/Ant_Suxin.php` | High
9 | File | `/api/Common/uploadFile` | High
10 | File | `/api/sys/login` | High
11 | File | `/api/sys/set_passwd` | High
12 | File | `/api/v1/attack/falco` | High
13 | File | `/app/ajax/search_sales_report.php` | High
14 | File | `/bin/boa` | Medium
15 | File | `/boaform/wlan_basic_set.cgi` | High
16 | File | `/cgi-bin/mesh.cgi?page=upgrade` | High
17 | File | `/classes/Users.php` | High
18 | File | `/CMD_ACCOUNT_ADMIN` | High
19 | File | `/E-mobile/App/System/File/downfile.php` | High
20 | File | `/HNAP1/` | Low
21 | ... | ... | ...

There are 177 more IOA items available (file, library, argument, input value, pattern, network port). Please use our online service to access the data.

## References

The following list contains _external sources_ which discuss the campaign and the associated activities:

* https://documents.trendmicro.com/assets/txt/earth_lamia_iocs_v2CeWlPie.txt
* https://search.censys.io/hosts/47.109.178.63
* https://search.censys.io/hosts/47.121.30.118
* https://search.censys.io/hosts/64.69.34.217
* https://search.censys.io/hosts/106.15.6.181
* https://search.censys.io/hosts/110.41.53.51
* https://search.censys.io/hosts/114.132.226.247
* https://search.censys.io/hosts/118.31.70.79
* https://search.censys.io/hosts/119.45.71.218
* https://search.censys.io/hosts/123.60.135.200
* https://search.censys.io/hosts/124.223.71.152
* https://search.censys.io/hosts/125.65.28.180
* https://search.censys.io/hosts/156.245.12.209
* https://search.censys.io/hosts/156.245.12.210
* https://search.censys.io/hosts/156.245.12.216
* https://search.censys.io/hosts/166.108.226.235
* https://threatfox.abuse.ch

## Literature

The following _articles_ explain our unique predictive cyber threat intelligence:

* [VulDB Cyber Threat Intelligence Documentation](https://vuldb.com/?kb.cti)
* [Cyber Threat Intelligence - Early Anticipation of Attacks](https://www.scip.ch/en/?labs.20201022)

## License

(c) [1997-2025](https://vuldb.com/?kb.changelog) by [vuldb.com](https://vuldb.com/?kb.about). All data on this page is shared under the license [CC BY-NC-SA 4.0](https://creativecommons.org/licenses/by-nc-sa/4.0/). Questions? Check the [FAQ](https://vuldb.com/?kb.faq), read the [documentation](https://vuldb.com/?kb) or [contact us](https://vuldb.com/?contact)!
