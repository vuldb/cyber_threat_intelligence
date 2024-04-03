# Tokelau Unknown - Cyber Threat Intelligence

These _indicators_ were reported, collected, and generated during the [VulDB CTI analysis](https://vuldb.com/?kb.cti) of the actor known as [Tokelau Unknown](https://vuldb.com/?actor.tokelau_unknown). The _activity monitoring_ correlates data from social media, forums, chat rooms, and darknet markets. It helps to determine associated actors, specific activities, expected intentions, emerging research, and ongoing attacks. Our unique _predictive model_ uses _big data_ to forecast activities and their characteristics.

_Live data_ and more _analysis capabilities_ are available at [https://vuldb.com/?actor.tokelau_unknown](https://vuldb.com/?actor.tokelau_unknown)

## Countries

These _countries_ are directly (e.g. origin of attacks) or indirectly (e.g. access by proxy) associated with Tokelau Unknown:

* [US](https://vuldb.com/?country.us)
* [CN](https://vuldb.com/?country.cn)
* [TR](https://vuldb.com/?country.tr)
* ...

There are 21 more country items available. Please use our online service to access the data.

## IOC - Indicator of Compromise

These _indicators of compromise_ (IOC) indicate associated network resources which are known to be part of research and attack activities of Tokelau Unknown.

ID | IP address | Hostname | Campaign | Confidence
-- | ---------- | -------- | -------- | ----------
1 | [5.62.56.224](https://vuldb.com/?ip.5.62.56.224) | r-224-56-62-5.consumer-pool.prcdn.net | - | High
2 | [5.62.58.204](https://vuldb.com/?ip.5.62.58.204) | r-204-58-62-5.consumer-pool.prcdn.net | - | High
3 | [27.96.24.0](https://vuldb.com/?ip.27.96.24.0) | - | - | High
4 | ... | ... | ... | ...

There are 9 more IOC items available. Please use our online service to access the data.

## TTP - Tactics, Techniques, Procedures

_Tactics, techniques, and procedures_ (TTP) summarize the suspected MITRE ATT&CK techniques used by _Tokelau Unknown_. This data is unique as it uses our predictive model for actor profiling.

ID | Technique | Weakness | Description | Confidence
-- | --------- | -------- | ----------- | ----------
1 | T1006 | CWE-21, CWE-22, CWE-23, CWE-25, CWE-36, CWE-425 | Path Traversal | High
2 | T1040 | CWE-319 | Authentication Bypass by Capture-replay | High
3 | T1055 | CWE-74 | Improper Neutralization of Data within XPath Expressions | High
4 | T1059 | CWE-94, CWE-1321 | Argument Injection | High
5 | T1059.007 | CWE-79, CWE-80 | Cross Site Scripting | High
6 | ... | ... | ... | ...

There are 21 more TTP items available. Please use our online service to access the data.

## IOA - Indicator of Attack

These _indicators of attack_ (IOA) list the potential fragments used for technical activities like reconnaissance, exploitation, privilege escalation, and exfiltration by Tokelau Unknown. This data is unique as it uses our predictive model for actor profiling.

ID | Type | Indicator | Confidence
-- | ---- | --------- | ----------
1 | File | `%SYSTEMDRIVE%\node_modules\.bin\wmic.exe` | High
2 | File | `/#ilang=DE&b=c_smartenergy_swgroups` | High
3 | File | `/Account/login.php` | High
4 | File | `/admin/` | Low
5 | File | `/admin/manage_academic.php` | High
6 | File | `/admin/save.php` | High
7 | File | `/adminapi/system/crud` | High
8 | File | `/adminapi/system/file/openfile` | High
9 | File | `/admin_route/dec_service_credits.php` | High
10 | File | `/api/download` | High
11 | File | `/api/v1/alerts` | High
12 | File | `/api/v1/terminal/sessions/?limit=1` | High
13 | File | `/api/v4/teams//channels/deleted` | High
14 | File | `/b2b-supermarket/shopping-cart` | High
15 | File | `/cancel.php` | Medium
16 | File | `/category.php` | High
17 | File | `/categorypage.php` | High
18 | File | `/cgi-bin/cstecgi.cgi` | High
19 | File | `/cgi-bin/luci/api/wireless` | High
20 | File | `/cgi-bin/vitogate.cgi` | High
21 | File | `/change-language/de_DE` | High
22 | File | `/Content/Template/root/reverse-shell.aspx` | High
23 | File | `/debug/pprof` | Medium
24 | File | `/devinfo` | Medium
25 | File | `/dist/index.js` | High
26 | File | `/fcgi/scrut_fcgi.fcgi` | High
27 | File | `/forum/away.php` | High
28 | File | `/geoserver/gwc/rest.html` | High
29 | File | `/goform/formSysCmd` | High
30 | File | `/HNAP1` | Low
31 | File | `/hosts/firewall/ip` | High
32 | File | `/index.jsp#settings` | High
33 | File | `/index.php/ccm/system/file/upload` | High
34 | File | `/jeecg-boot/sys/common/upload` | High
35 | File | `/log/decodmail.php` | High
36 | File | `/oauth/idp/.well-known/openid-configuration` | High
37 | File | `/OA_HTML/cabo/jsps/a.jsp` | High
38 | File | `/php/ping.php` | High
39 | File | `/proxy` | Low
40 | File | `/RPS2019Service/status.html` | High
41 | File | `/s/index.php?action=statistics` | High
42 | File | `/setting` | Medium
43 | File | `/Setting/change_password_save` | High
44 | File | `/sicweb-ajax/tmproot/` | High
45 | File | `/signup.php` | Medium
46 | File | `/spip.php` | Medium
47 | File | `/student/bookdetails.php` | High
48 | File | `/st_reg.php` | Medium
49 | File | `/subsys/net/l2/wifi/wifi_shell.c` | High
50 | File | `/supplier.php` | High
51 | ... | ... | ...

There are 441 more IOA items available (file, library, argument, input value, pattern, network port). Please use our online service to access the data.

## References

The following list contains _external sources_ which discuss the actor and the associated activities:

* https://github.com/firehol/blocklist-ipsets/blob/master/geolite2_country/country_tk.netset
* https://github.com/firehol/blocklist-ipsets/blob/master/ip2location_country/ip2location_country_tk.netset
* https://github.com/firehol/blocklist-ipsets/blob/master/ipip_country/ipip_country_tk.netset

## Literature

The following _articles_ explain our unique predictive cyber threat intelligence:

* [VulDB Cyber Threat Intelligence Documentation](https://vuldb.com/?kb.cti)
* [Cyber Threat Intelligence - Early Anticipation of Attacks](https://www.scip.ch/en/?labs.20201022)

## License

(c) [1997-2024](https://vuldb.com/?kb.changelog) by [vuldb.com](https://vuldb.com/?kb.about). All data on this page is shared under the license [CC BY-NC-SA 4.0](https://creativecommons.org/licenses/by-nc-sa/4.0/). Questions? Check the [FAQ](https://vuldb.com/?kb.faq), read the [documentation](https://vuldb.com/?kb) or [contact us](https://vuldb.com/?contact)!
