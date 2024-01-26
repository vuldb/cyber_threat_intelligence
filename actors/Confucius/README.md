# Confucius - Cyber Threat Intelligence

These _indicators_ were reported, collected, and generated during the [VulDB CTI analysis](https://vuldb.com/?kb.cti) of the actor known as [Confucius](https://vuldb.com/?actor.confucius). The _activity monitoring_ correlates data from social media, forums, chat rooms, and darknet markets. It helps to determine associated actors, specific activities, expected intentions, emerging research, and ongoing attacks. Our unique _predictive model_ uses _big data_ to forecast activities and their characteristics.

_Live data_ and more _analysis capabilities_ are available at [https://vuldb.com/?actor.confucius](https://vuldb.com/?actor.confucius)

## Campaigns

The following _campaigns_ are known and can be associated with Confucius:

* Tibbar

## Countries

These _countries_ are directly (e.g. origin of attacks) or indirectly (e.g. access by proxy) associated with Confucius:

* [US](https://vuldb.com/?country.us)
* [CN](https://vuldb.com/?country.cn)
* [GB](https://vuldb.com/?country.gb)
* ...

There are 21 more country items available. Please use our online service to access the data.

## IOC - Indicator of Compromise

These _indicators of compromise_ (IOC) indicate associated network resources which are known to be part of research and attack activities of Confucius.

ID | IP address | Hostname | Campaign | Confidence
-- | ---------- | -------- | -------- | ----------
1 | [5.39.23.192](https://vuldb.com/?ip.5.39.23.192) | ip192.ip-5-39-23.eu | - | High
2 | [5.135.85.16](https://vuldb.com/?ip.5.135.85.16) | flotweb-o20.bestonthenet.fr | - | High
3 | [23.81.246.170](https://vuldb.com/?ip.23.81.246.170) | - | - | High
4 | [46.165.207.98](https://vuldb.com/?ip.46.165.207.98) | - | - | High
5 | [46.165.207.99](https://vuldb.com/?ip.46.165.207.99) | - | - | High
6 | [46.165.207.108](https://vuldb.com/?ip.46.165.207.108) | - | - | High
7 | [46.165.207.109](https://vuldb.com/?ip.46.165.207.109) | - | - | High
8 | [46.165.207.112](https://vuldb.com/?ip.46.165.207.112) | - | - | High
9 | ... | ... | ... | ...

There are 34 more IOC items available. Please use our online service to access the data.

## TTP - Tactics, Techniques, Procedures

_Tactics, techniques, and procedures_ (TTP) summarize the suspected MITRE ATT&CK techniques used by _Confucius_. This data is unique as it uses our predictive model for actor profiling.

ID | Technique | Weakness | Description | Confidence
-- | --------- | -------- | ----------- | ----------
1 | T1006 | CWE-21, CWE-22, CWE-23, CWE-425 | Pathname Traversal | High
2 | T1040 | CWE-319 | Authentication Bypass by Capture-replay | High
3 | T1055 | CWE-74 | Injection | High
4 | T1059 | CWE-94, CWE-1321 | Cross Site Scripting | High
5 | T1059.007 | CWE-79, CWE-80 | Cross Site Scripting | High
6 | ... | ... | ... | ...

There are 22 more TTP items available. Please use our online service to access the data.

## IOA - Indicator of Attack

These _indicators of attack_ (IOA) list the potential fragments used for technical activities like reconnaissance, exploitation, privilege escalation, and exfiltration by Confucius. This data is unique as it uses our predictive model for actor profiling.

ID | Type | Indicator | Confidence
-- | ---- | --------- | ----------
1 | File | `%SYSTEMDRIVE%\node_modules\.bin\wmic.exe` | High
2 | File | `/admin/save.php` | High
3 | File | `/admin/sys_sql_query.php` | High
4 | File | `/api/baskets/{name}` | High
5 | File | `/api/download` | High
6 | File | `/api/v1/alerts` | High
7 | File | `/api/v1/terminal/sessions/?limit=1` | High
8 | File | `/b2b-supermarket/shopping-cart` | High
9 | File | `/bitrix/admin/ldap_server_edit.php` | High
10 | File | `/category.php` | High
11 | File | `/categorypage.php` | High
12 | File | `/cgi-bin/luci/api/wireless` | High
13 | File | `/cgi-bin/vitogate.cgi` | High
14 | File | `/change-language/de_DE` | High
15 | File | `/company/store` | High
16 | File | `/Content/Template/root/reverse-shell.aspx` | High
17 | File | `/Controller/Ajaxfileupload.ashx` | High
18 | File | `/core/conditions/AbstractWrapper.java` | High
19 | File | `/debug/pprof` | Medium
20 | File | `/dist/index.js` | High
21 | File | `/etc/passwd` | Medium
22 | File | `/fcgi/scrut_fcgi.fcgi` | High
23 | File | `/forum/away.php` | High
24 | File | `/geoserver/gwc/rest.html` | High
25 | File | `/goform/formSysCmd` | High
26 | File | `/h/` | Low
27 | File | `/HNAP1` | Low
28 | File | `/hosts/firewall/ip` | High
29 | File | `/index.php/ccm/system/file/upload` | High
30 | File | `/jeecg-boot/sys/common/upload` | High
31 | File | `/log/decodmail.php` | High
32 | File | `/oauth/idp/.well-known/openid-configuration` | High
33 | File | `/OA_HTML/cabo/jsps/a.jsp` | High
34 | File | `/php/ping.php` | High
35 | File | `/proxy` | Low
36 | File | `/recipe-result` | High
37 | File | `/register.do` | Medium
38 | File | `/RPS2019Service/status.html` | High
39 | File | `/s/index.php?action=statistics` | High
40 | File | `/Service/ImageStationDataService.asmx` | High
41 | File | `/setting` | Medium
42 | File | `/sicweb-ajax/tmproot/` | High
43 | File | `/spip.php` | Medium
44 | File | `/student/bookdetails.php` | High
45 | ... | ... | ...

There are 386 more IOA items available (file, library, argument, input value, pattern, network port). Please use our online service to access the data.

## References

The following list contains _external sources_ which discuss the actor and the associated activities:

* https://github.com/blackorbird/APT_REPORT/blob/master/Confucius/OperationTibbar-A-retaliatory-targeted-attack-from-SouthAsian-APT-Group-Confucius.pdf
* https://nsfocusglobal.com/analysis-of-cyber-attack-of-apt-organization-confucius-against-pakistans-intelligence-based-operation/
* https://twitter.com/ShadowChasing1/status/1449172597816455170
* https://www.threatminer.org/report.php?q=Confucius%C2%A0Says%E2%80%A6Malware%C2%A0Families%C2%A0Get%C2%A0Further-PaloAltoNetworks.pdf&y=2016

## Literature

The following _articles_ explain our unique predictive cyber threat intelligence:

* [VulDB Cyber Threat Intelligence Documentation](https://vuldb.com/?kb.cti)
* [Cyber Threat Intelligence - Early Anticipation of Attacks](https://www.scip.ch/en/?labs.20201022)

## License

(c) [1997-2024](https://vuldb.com/?kb.changelog) by [vuldb.com](https://vuldb.com/?kb.about). All data on this page is shared under the license [CC BY-NC-SA 4.0](https://creativecommons.org/licenses/by-nc-sa/4.0/). Questions? Check the [FAQ](https://vuldb.com/?kb.faq), read the [documentation](https://vuldb.com/?kb) or [contact us](https://vuldb.com/?contact)!
