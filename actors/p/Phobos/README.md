# Phobos - Cyber Threat Intelligence

These _indicators_ were reported, collected, and generated during the [VulDB CTI analysis](https://vuldb.com/?kb.cti) of the actor known as [Phobos](https://vuldb.com/?actor.phobos). The _activity monitoring_ correlates data from social media, forums, chat rooms, and darknet markets. It helps to determine associated actors, specific activities, expected intentions, emerging research, and ongoing attacks. Our unique _predictive model_ uses _big data_ to forecast activities and their characteristics.

_Live data_ and more _analysis capabilities_ are available at [https://vuldb.com/?actor.phobos](https://vuldb.com/?actor.phobos)

## Countries

These _countries_ are directly (e.g. origin of attacks) or indirectly (e.g. access by proxy) associated with Phobos:

* [US](https://vuldb.com/?country.us)
* [CN](https://vuldb.com/?country.cn)
* [TR](https://vuldb.com/?country.tr)
* ...

There are 21 more country items available. Please use our online service to access the data.

## IOC - Indicator of Compromise

These _indicators of compromise_ (IOC) indicate associated network resources which are known to be part of research and attack activities of Phobos.

ID | IP address | Hostname | Campaign | Confidence
-- | ---------- | -------- | -------- | ----------
1 | [45.9.74.14](https://vuldb.com/?ip.45.9.74.14) | - | - | High
2 | [147.78.47.224](https://vuldb.com/?ip.147.78.47.224) | undefined.hostname.localhost | - | High
3 | [179.43.140.168](https://vuldb.com/?ip.179.43.140.168) | securehosting.capital | - | High
4 | ... | ... | ... | ...

There are 3 more IOC items available. Please use our online service to access the data.

## TTP - Tactics, Techniques, Procedures

_Tactics, techniques, and procedures_ (TTP) summarize the suspected MITRE ATT&CK techniques used by _Phobos_. This data is unique as it uses our predictive model for actor profiling.

ID | Technique | Weakness | Description | Confidence
-- | --------- | -------- | ----------- | ----------
1 | T1006 | CWE-21, CWE-22, CWE-23, CWE-25, CWE-36, CWE-425 | Path Traversal | High
2 | T1040 | CWE-319 | Authentication Bypass by Capture-replay | High
3 | T1055 | CWE-74 | Improper Neutralization of Data within XPath Expressions | High
4 | T1059 | CWE-94, CWE-1321 | Argument Injection | High
5 | T1059.007 | CWE-79, CWE-80 | Cross Site Scripting | High
6 | ... | ... | ... | ...

There are 20 more TTP items available. Please use our online service to access the data.

## IOA - Indicator of Attack

These _indicators of attack_ (IOA) list the potential fragments used for technical activities like reconnaissance, exploitation, privilege escalation, and exfiltration by Phobos. This data is unique as it uses our predictive model for actor profiling.

ID | Type | Indicator | Confidence
-- | ---- | --------- | ----------
1 | File | `%SYSTEMDRIVE%\node_modules\.bin\wmic.exe` | High
2 | File | `/#ilang=DE&b=c_smartenergy_swgroups` | High
3 | File | `/Account/login.php` | High
4 | File | `/admin/` | Low
5 | File | `/Admin/changepassword.php` | High
6 | File | `/admin/general-setting` | High
7 | File | `/admin/save.php` | High
8 | File | `/admin/service` | High
9 | File | `/adminapi/system/crud` | High
10 | File | `/adminapi/system/file/openfile` | High
11 | File | `/admin_route/dec_service_credits.php` | High
12 | File | `/api/download` | High
13 | File | `/api/v1/alerts` | High
14 | File | `/api/v1/custom_component` | High
15 | File | `/api/v1/terminal/sessions/?limit=1` | High
16 | File | `/api/v4/teams//channels/deleted` | High
17 | File | `/api/wechat/app_auth` | High
18 | File | `/b2b-supermarket/shopping-cart` | High
19 | File | `/cancel.php` | Medium
20 | File | `/category.php` | High
21 | File | `/categorypage.php` | High
22 | File | `/cgi-bin/cstecgi.cgi` | High
23 | File | `/cgi-bin/vitogate.cgi` | High
24 | File | `/change-language/de_DE` | High
25 | File | `/classes/Users.php?f=delete` | High
26 | File | `/control/register_case.php` | High
27 | File | `/debug/pprof` | Medium
28 | File | `/devinfo` | Medium
29 | File | `/dist/index.js` | High
30 | File | `/download` | Medium
31 | File | `/fcgi/scrut_fcgi.fcgi` | High
32 | File | `/forum/away.php` | High
33 | File | `/geoserver/gwc/rest.html` | High
34 | File | `/goform/formSysCmd` | High
35 | File | `/HNAP1` | Low
36 | File | `/hosts/firewall/ip` | High
37 | File | `/index.jsp#settings` | High
38 | File | `/index.php` | Medium
39 | File | `/index.php/ccm/system/file/upload` | High
40 | File | `/labvantage/rc?command=page&page=SampleList&_iframename=list` | High
41 | File | `/log/decodmail.php` | High
42 | File | `/ndmComponents.js` | High
43 | File | `/oauth/idp/.well-known/openid-configuration` | High
44 | File | `/OA_HTML/cabo/jsps/a.jsp` | High
45 | File | `/one_church/churchprofile.php` | High
46 | File | `/php/ping.php` | High
47 | File | `/proxy` | Low
48 | File | `/register.php` | High
49 | File | `/RPS2019Service/status.html` | High
50 | ... | ... | ...

There are 436 more IOA items available (file, library, argument, input value, pattern, network port). Please use our online service to access the data.

## References

The following list contains _external sources_ which discuss the actor and the associated activities:

* https://exchange.xforce.ibmcloud.com/threats/guid:71f873ec777c3c34917057ccd3b42ed9
* https://www.cisa.gov/news-events/cybersecurity-advisories/aa24-060a

## Literature

The following _articles_ explain our unique predictive cyber threat intelligence:

* [VulDB Cyber Threat Intelligence Documentation](https://vuldb.com/?kb.cti)
* [Cyber Threat Intelligence - Early Anticipation of Attacks](https://www.scip.ch/en/?labs.20201022)

## License

(c) [1997-2024](https://vuldb.com/?kb.changelog) by [vuldb.com](https://vuldb.com/?kb.about). All data on this page is shared under the license [CC BY-NC-SA 4.0](https://creativecommons.org/licenses/by-nc-sa/4.0/). Questions? Check the [FAQ](https://vuldb.com/?kb.faq), read the [documentation](https://vuldb.com/?kb) or [contact us](https://vuldb.com/?contact)!
