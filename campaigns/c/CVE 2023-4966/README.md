# CVE 2023-4966 - Cyber Threat Intelligence

These _indicators_ were reported, collected, and generated during the [VulDB CTI analysis](https://vuldb.com/?kb.cti) of the campaign known as _CVE 2023-4966_. The _activity monitoring_ correlates data from social media, forums, chat rooms, and darknet markets. It helps to determine associated actors, specific activities, expected intentions, emerging research, and ongoing attacks. Our unique _predictive model_ uses _big data_ to forecast activities and their characteristics.

_Live data_ and more _analysis capabilities_ are available at [https://vuldb.com/?actor](https://vuldb.com/?actor)

## Countries

These _countries_ are directly (e.g. origin of attacks) or indirectly (e.g. access by proxy) associated with CVE 2023-4966:

* [US](https://vuldb.com/?country.us)
* [CN](https://vuldb.com/?country.cn)
* [TR](https://vuldb.com/?country.tr)
* ...

There are 22 more country items available. Please use our online service to access the data.

## Actors

These _actors_ are associated with CVE 2023-4966 or other actors linked to the campaign.

ID | Actor | Confidence
-- | ----- | ----------
1 | [LockBit](https://vuldb.com/?actor.lockbit) | High
2 | [Unknown](https://vuldb.com/?actor.unknown) | High

## IOC - Indicator of Compromise

These _indicators of compromise_ (IOC) indicate associated network resources which are known to be part of research and attack activities of CVE 2023-4966.

ID | IP address | Hostname | Actor | Confidence
-- | ---------- | -------- | ----- | ----------
1 | [45.129.137.233](https://vuldb.com/?ip.45.129.137.233) | - | [LockBit](https://vuldb.com/?actor.lockbit) | High
2 | [54.84.248.205](https://vuldb.com/?ip.54.84.248.205) | ec2-54-84-248-205.compute-1.amazonaws.com | [LockBit](https://vuldb.com/?actor.lockbit) | Medium
3 | [62.233.50.25](https://vuldb.com/?ip.62.233.50.25) | - | [LockBit](https://vuldb.com/?actor.lockbit) | High
4 | [67.213.219.219](https://vuldb.com/?ip.67.213.219.219) | 33-win08.midphase.com | [Unknown](https://vuldb.com/?actor.unknown) | High
5 | [70.37.82.20](https://vuldb.com/?ip.70.37.82.20) | - | [LockBit](https://vuldb.com/?actor.lockbit) | High
6 | ... | ... | ... | ...

There are 22 more IOC items available. Please use our online service to access the data.

## TTP - Tactics, Techniques, Procedures

_Tactics, techniques, and procedures_ (TTP) summarize the suspected MITRE ATT&CK techniques used within CVE 2023-4966. This data is unique as it uses our predictive model for actor profiling.

ID | Technique | Weakness | Description | Confidence
-- | --------- | -------- | ----------- | ----------
1 | T1006 | CWE-21, CWE-22, CWE-23, CWE-25, CWE-36, CWE-425 | Path Traversal | High
2 | T1040 | CWE-319 | Authentication Bypass by Capture-replay | High
3 | T1055 | CWE-74 | Improper Neutralization of Data within XPath Expressions | High
4 | T1059 | CWE-88, CWE-94, CWE-1321 | Argument Injection | High
5 | T1059.007 | CWE-79, CWE-80 | Cross Site Scripting | High
6 | ... | ... | ... | ...

There are 20 more TTP items available. Please use our online service to access the data.

## IOA - Indicator of Attack

These _indicators of attack_ (IOA) list the potential fragments used for technical activities like reconnaissance, exploitation, privilege escalation, and exfiltration during CVE 2023-4966. This data is unique as it uses our predictive model for actor profiling.

ID | Type | Indicator | Confidence
-- | ---- | --------- | ----------
1 | File | `%SYSTEMDRIVE%\node_modules\.bin\wmic.exe` | High
2 | File | `/#ilang=DE&b=c_smartenergy_swgroups` | High
3 | File | `/Account/login.php` | High
4 | File | `/admin/` | Low
5 | File | `/Admin/changepassword.php` | High
6 | File | `/admin/general-setting` | High
7 | File | `/admin/service` | High
8 | File | `/adminapi/system/crud` | High
9 | File | `/adminapi/system/file/openfile` | High
10 | File | `/admin_route/dec_service_credits.php` | High
11 | File | `/api/v1/alerts` | High
12 | File | `/api/v1/custom_component` | High
13 | File | `/api/v4/teams//channels/deleted` | High
14 | File | `/api/wechat/app_auth` | High
15 | File | `/b2b-supermarket/shopping-cart` | High
16 | File | `/cancel.php` | Medium
17 | File | `/category.php` | High
18 | File | `/cgi-bin/cstecgi.cgi` | High
19 | File | `/change-language/de_DE` | High
20 | File | `/classes/Users.php?f=delete` | High
21 | File | `/control/register_case.php` | High
22 | File | `/debug/pprof` | Medium
23 | File | `/devinfo` | Medium
24 | File | `/dist/index.js` | High
25 | File | `/download` | Medium
26 | File | `/Duty/AjaxHandle/UploadFloodPlanFileUpdate.ashx` | High
27 | File | `/fcgi/scrut_fcgi.fcgi` | High
28 | File | `/forum/away.php` | High
29 | File | `/geoserver/gwc/rest.html` | High
30 | File | `/goform/formSysCmd` | High
31 | File | `/goform/WifiExtraSet` | High
32 | File | `/HNAP1` | Low
33 | File | `/hosts/firewall/ip` | High
34 | File | `/index.jsp#settings` | High
35 | File | `/index.php` | Medium
36 | File | `/index.php/ccm/system/file/upload` | High
37 | File | `/itbox_pi/vpn_quickset_service.php?a=set_vpn` | High
38 | File | `/labvantage/rc?command=page&page=SampleList&_iframename=list` | High
39 | File | `/log/decodmail.php` | High
40 | File | `/ndmComponents.js` | High
41 | File | `/oauth/idp/.well-known/openid-configuration` | High
42 | File | `/OA_HTML/cabo/jsps/a.jsp` | High
43 | File | `/one_church/churchprofile.php` | High
44 | File | `/php/ping.php` | High
45 | File | `/proxy` | Low
46 | File | `/register.php` | High
47 | File | `/s/index.php?action=statistics` | High
48 | File | `/setting` | Medium
49 | File | `/Setting/change_password_save` | High
50 | ... | ... | ...

There are 434 more IOA items available (file, library, argument, input value, pattern, network port). Please use our online service to access the data.

## References

The following list contains _external sources_ which discuss the campaign and the associated activities:

* https://cyble.com/blog/active-exploitation-of-big-ip-and-citrix-vulnerabilities-observed-by-cyble-global-sensor-intelligence-network/
* https://www.cisa.gov/news-events/cybersecurity-advisories/aa23-325a

## Literature

The following _articles_ explain our unique predictive cyber threat intelligence:

* [VulDB Cyber Threat Intelligence Documentation](https://vuldb.com/?kb.cti)
* [Cyber Threat Intelligence - Early Anticipation of Attacks](https://www.scip.ch/en/?labs.20201022)

## License

(c) [1997-2024](https://vuldb.com/?kb.changelog) by [vuldb.com](https://vuldb.com/?kb.about). All data on this page is shared under the license [CC BY-NC-SA 4.0](https://creativecommons.org/licenses/by-nc-sa/4.0/). Questions? Check the [FAQ](https://vuldb.com/?kb.faq), read the [documentation](https://vuldb.com/?kb) or [contact us](https://vuldb.com/?contact)!
