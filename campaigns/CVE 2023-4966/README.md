# CVE 2023-4966 - Cyber Threat Intelligence

These _indicators_ were reported, collected, and generated during the [VulDB CTI analysis](https://vuldb.com/?kb.cti) of the campaign known as _CVE 2023-4966_. The _activity monitoring_ correlates data from social media, forums, chat rooms, and darknet markets. It helps to determine associated actors, specific activities, expected intentions, emerging research, and ongoing attacks. Our unique _predictive model_ uses _big data_ to forecast activities and their characteristics.

_Live data_ and more _analysis capabilities_ are available at [https://vuldb.com/?actor](https://vuldb.com/?actor)

## Countries

These _countries_ are directly (e.g. origin of attacks) or indirectly (e.g. access by proxy) associated with CVE 2023-4966:

* [US](https://vuldb.com/?country.us)
* [CN](https://vuldb.com/?country.cn)
* [GB](https://vuldb.com/?country.gb)
* ...

There are 20 more country items available. Please use our online service to access the data.

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
1 | T1006 | CWE-21, CWE-22, CWE-23, CWE-25, CWE-36, CWE-425 | Path Traversal | High
2 | T1040 | CWE-319 | Authentication Bypass by Capture-replay | High
3 | T1055 | CWE-74 | Injection | High
4 | T1059 | CWE-94, CWE-1321 | Argument Injection | High
5 | T1059.007 | CWE-79, CWE-80 | Cross Site Scripting | High
6 | ... | ... | ... | ...

There are 21 more TTP items available. Please use our online service to access the data.

## IOA - Indicator of Attack

These _indicators of attack_ (IOA) list the potential fragments used for technical activities like reconnaissance, exploitation, privilege escalation, and exfiltration during CVE 2023-4966. This data is unique as it uses our predictive model for actor profiling.

ID | Type | Indicator | Confidence
-- | ---- | --------- | ----------
1 | File | `%SYSTEMDRIVE%\node_modules\.bin\wmic.exe` | High
2 | File | `/#ilang=DE&b=c_smartenergy_swgroups` | High
3 | File | `/Account/login.php` | High
4 | File | `/admin/` | Low
5 | File | `/admin/save.php` | High
6 | File | `/adminapi/system/crud` | High
7 | File | `/adminapi/system/file/openfile` | High
8 | File | `/admin_route/dec_service_credits.php` | High
9 | File | `/api/baskets/{name}` | High
10 | File | `/api/download` | High
11 | File | `/api/v1/alerts` | High
12 | File | `/api/v1/terminal/sessions/?limit=1` | High
13 | File | `/api/v4/teams//channels/deleted` | High
14 | File | `/b2b-supermarket/shopping-cart` | High
15 | File | `/category.php` | High
16 | File | `/categorypage.php` | High
17 | File | `/cgi-bin/cstecgi.cgi` | High
18 | File | `/cgi-bin/luci/api/wireless` | High
19 | File | `/cgi-bin/vitogate.cgi` | High
20 | File | `/change-language/de_DE` | High
21 | File | `/Content/Template/root/reverse-shell.aspx` | High
22 | File | `/core/conditions/AbstractWrapper.java` | High
23 | File | `/debug/pprof` | Medium
24 | File | `/devinfo` | Medium
25 | File | `/dist/index.js` | High
26 | File | `/Duty/AjaxHandle/UploadFloodPlanFileUpdate.ashx` | High
27 | File | `/fcgi/scrut_fcgi.fcgi` | High
28 | File | `/forum/away.php` | High
29 | File | `/geoserver/gwc/rest.html` | High
30 | File | `/goform/formSysCmd` | High
31 | File | `/HNAP1` | Low
32 | File | `/hosts/firewall/ip` | High
33 | File | `/index.jsp#settings` | High
34 | File | `/index.php/ccm/system/file/upload` | High
35 | File | `/jeecg-boot/sys/common/upload` | High
36 | File | `/log/decodmail.php` | High
37 | File | `/oauth/idp/.well-known/openid-configuration` | High
38 | File | `/OA_HTML/cabo/jsps/a.jsp` | High
39 | File | `/php/ping.php` | High
40 | File | `/proxy` | Low
41 | File | `/register.do` | Medium
42 | File | `/RPS2019Service/status.html` | High
43 | File | `/s/index.php?action=statistics` | High
44 | File | `/setting` | Medium
45 | File | `/Setting/change_password_save` | High
46 | File | `/sicweb-ajax/tmproot/` | High
47 | File | `/signup.php` | Medium
48 | File | `/spip.php` | Medium
49 | ... | ... | ...

There are 424 more IOA items available (file, library, argument, input value, pattern, network port). Please use our online service to access the data.

## References

The following list contains _external sources_ which discuss the campaign and the associated activities:

* https://www.cisa.gov/news-events/cybersecurity-advisories/aa23-325a

## Literature

The following _articles_ explain our unique predictive cyber threat intelligence:

* [VulDB Cyber Threat Intelligence Documentation](https://vuldb.com/?kb.cti)
* [Cyber Threat Intelligence - Early Anticipation of Attacks](https://www.scip.ch/en/?labs.20201022)

## License

(c) [1997-2024](https://vuldb.com/?kb.changelog) by [vuldb.com](https://vuldb.com/?kb.about). All data on this page is shared under the license [CC BY-NC-SA 4.0](https://creativecommons.org/licenses/by-nc-sa/4.0/). Questions? Check the [FAQ](https://vuldb.com/?kb.faq), read the [documentation](https://vuldb.com/?kb) or [contact us](https://vuldb.com/?contact)!
