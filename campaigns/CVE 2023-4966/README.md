# CVE 2023-4966 - Cyber Threat Intelligence

These _indicators_ were reported, collected, and generated during the [VulDB CTI analysis](https://vuldb.com/?kb.cti) of the campaign known as _CVE 2023-4966_. The _activity monitoring_ correlates data from social media, forums, chat rooms, and darknet markets. It helps to determine associated actors, specific activities, expected intentions, emerging research, and ongoing attacks. Our unique _predictive model_ uses _big data_ to forecast activities and their characteristics.

_Live data_ and more _analysis capabilities_ are available at [https://vuldb.com/?actor](https://vuldb.com/?actor)

## Countries

These _countries_ are directly (e.g. origin of attacks) or indirectly (e.g. access by proxy) associated with CVE 2023-4966:

* [US](https://vuldb.com/?country.us)
* [CN](https://vuldb.com/?country.cn)
* [GB](https://vuldb.com/?country.gb)
* ...

There are 22 more country items available. Please use our online service to access the data.

## Actors

These _actors_ are associated with CVE 2023-4966 or other actors linked to the campaign.

ID | Actor | Confidence
-- | ----- | ----------
1 | [LockBit](https://vuldb.com/?actor.lockbit) | High

## IOC - Indicator of Compromise

These _indicators of compromise_ (IOC) indicate associated network resources which are known to be part of research and attack activities of CVE 2023-4966.

ID | IP address | Hostname | Actor | Confidence
-- | ---------- | -------- | ----- | ----------
1 | [45.129.137.233](https://vuldb.com/?ip.45.129.137.233) | - | [LockBit](https://vuldb.com/?actor.lockbit) | High
2 | [54.84.248.205](https://vuldb.com/?ip.54.84.248.205) | ec2-54-84-248-205.compute-1.amazonaws.com | [LockBit](https://vuldb.com/?actor.lockbit) | Medium
3 | [62.233.50.25](https://vuldb.com/?ip.62.233.50.25) | - | [LockBit](https://vuldb.com/?actor.lockbit) | High
4 | [70.37.82.20](https://vuldb.com/?ip.70.37.82.20) | - | [LockBit](https://vuldb.com/?actor.lockbit) | High
5 | ... | ... | ... | ...

There are 15 more IOC items available. Please use our online service to access the data.

## TTP - Tactics, Techniques, Procedures

_Tactics, techniques, and procedures_ (TTP) summarize the suspected MITRE ATT&CK techniques used within CVE 2023-4966. This data is unique as it uses our predictive model for actor profiling.

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

These _indicators of attack_ (IOA) list the potential fragments used for technical activities like reconnaissance, exploitation, privilege escalation, and exfiltration during CVE 2023-4966. This data is unique as it uses our predictive model for actor profiling.

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
21 | File | `/Duty/AjaxHandle/UploadFloodPlanFileUpdate.ashx` | High
22 | File | `/etc/passwd` | Medium
23 | File | `/fcgi/scrut_fcgi.fcgi` | High
24 | File | `/forum/away.php` | High
25 | File | `/geoserver/gwc/rest.html` | High
26 | File | `/goform/formSysCmd` | High
27 | File | `/h/` | Low
28 | File | `/HNAP1` | Low
29 | File | `/hosts/firewall/ip` | High
30 | File | `/index.php/ccm/system/file/upload` | High
31 | File | `/jeecg-boot/sys/common/upload` | High
32 | File | `/log/decodmail.php` | High
33 | File | `/oauth/idp/.well-known/openid-configuration` | High
34 | File | `/OA_HTML/cabo/jsps/a.jsp` | High
35 | File | `/php/ping.php` | High
36 | File | `/proxy` | Low
37 | File | `/recipe-result` | High
38 | File | `/register.do` | Medium
39 | File | `/RPS2019Service/status.html` | High
40 | File | `/s/index.php?action=statistics` | High
41 | File | `/Service/ImageStationDataService.asmx` | High
42 | File | `/setting` | Medium
43 | File | `/sicweb-ajax/tmproot/` | High
44 | File | `/spip.php` | Medium
45 | File | `/student/bookdetails.php` | High
46 | ... | ... | ...

There are 394 more IOA items available (file, library, argument, input value, pattern, network port). Please use our online service to access the data.

## References

The following list contains _external sources_ which discuss the campaign and the associated activities:

* https://www.cisa.gov/news-events/cybersecurity-advisories/aa23-325a

## Literature

The following _articles_ explain our unique predictive cyber threat intelligence:

* [VulDB Cyber Threat Intelligence Documentation](https://vuldb.com/?kb.cti)
* [Cyber Threat Intelligence - Early Anticipation of Attacks](https://www.scip.ch/en/?labs.20201022)

## License

(c) [1997-2024](https://vuldb.com/?kb.changelog) by [vuldb.com](https://vuldb.com/?kb.about). All data on this page is shared under the license [CC BY-NC-SA 4.0](https://creativecommons.org/licenses/by-nc-sa/4.0/). Questions? Check the [FAQ](https://vuldb.com/?kb.faq), read the [documentation](https://vuldb.com/?kb) or [contact us](https://vuldb.com/?contact)!
