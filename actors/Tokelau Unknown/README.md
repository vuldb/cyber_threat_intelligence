# Tokelau Unknown - Cyber Threat Intelligence

These _indicators_ were reported, collected, and generated during the [VulDB CTI analysis](https://vuldb.com/?kb.cti) of the actor known as [Tokelau Unknown](https://vuldb.com/?actor.tokelau_unknown). The _activity monitoring_ correlates data from social media, forums, chat rooms, and darknet markets. It helps to determine associated actors, specific activities, expected intentions, emerging research, and ongoing attacks. Our unique _predictive model_ uses _big data_ to forecast activities and their characteristics.

_Live data_ and more _analysis capabilities_ are available at [https://vuldb.com/?actor.tokelau_unknown](https://vuldb.com/?actor.tokelau_unknown)

## Countries

These _countries_ are directly (e.g. origin of attacks) or indirectly (e.g. access by proxy) associated with Tokelau Unknown:

* [US](https://vuldb.com/?country.us)
* [CN](https://vuldb.com/?country.cn)
* [GB](https://vuldb.com/?country.gb)
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
1 | T1006 | CWE-21, CWE-22, CWE-23, CWE-25, CWE-425 | Pathname Traversal | High
2 | T1040 | CWE-319 | Authentication Bypass by Capture-replay | High
3 | T1055 | CWE-74 | Injection | High
4 | T1059 | CWE-94, CWE-1321 | Cross Site Scripting | High
5 | T1059.007 | CWE-79, CWE-80 | Cross Site Scripting | High
6 | ... | ... | ... | ...

There are 22 more TTP items available. Please use our online service to access the data.

## IOA - Indicator of Attack

These _indicators of attack_ (IOA) list the potential fragments used for technical activities like reconnaissance, exploitation, privilege escalation, and exfiltration by Tokelau Unknown. This data is unique as it uses our predictive model for actor profiling.

ID | Type | Indicator | Confidence
-- | ---- | --------- | ----------
1 | File | `%SYSTEMDRIVE%\node_modules\.bin\wmic.exe` | High
2 | File | `/admin/manage_academic.php` | High
3 | File | `/admin/save.php` | High
4 | File | `/admin/sys_sql_query.php` | High
5 | File | `/admin/upload.php` | High
6 | File | `/api/baskets/{name}` | High
7 | File | `/api/download` | High
8 | File | `/api/v1/alerts` | High
9 | File | `/api/v1/terminal/sessions/?limit=1` | High
10 | File | `/b2b-supermarket/shopping-cart` | High
11 | File | `/bitrix/admin/ldap_server_edit.php` | High
12 | File | `/category.php` | High
13 | File | `/categorypage.php` | High
14 | File | `/cgi-bin/luci/api/wireless` | High
15 | File | `/cgi-bin/vitogate.cgi` | High
16 | File | `/change-language/de_DE` | High
17 | File | `/company/store` | High
18 | File | `/Content/Template/root/reverse-shell.aspx` | High
19 | File | `/Controller/Ajaxfileupload.ashx` | High
20 | File | `/core/conditions/AbstractWrapper.java` | High
21 | File | `/debug/pprof` | Medium
22 | File | `/devinfo` | Medium
23 | File | `/dist/index.js` | High
24 | File | `/etc/passwd` | Medium
25 | File | `/fcgi/scrut_fcgi.fcgi` | High
26 | File | `/forum/away.php` | High
27 | File | `/geoserver/gwc/rest.html` | High
28 | File | `/goform/formSysCmd` | High
29 | File | `/HNAP1` | Low
30 | File | `/hosts/firewall/ip` | High
31 | File | `/index.php/ccm/system/file/upload` | High
32 | File | `/jeecg-boot/sys/common/upload` | High
33 | File | `/log/decodmail.php` | High
34 | File | `/oauth/idp/.well-known/openid-configuration` | High
35 | File | `/OA_HTML/cabo/jsps/a.jsp` | High
36 | File | `/php/ping.php` | High
37 | File | `/proxy` | Low
38 | File | `/recipe-result` | High
39 | File | `/register.do` | Medium
40 | File | `/RPS2019Service/status.html` | High
41 | File | `/s/index.php?action=statistics` | High
42 | File | `/Service/ImageStationDataService.asmx` | High
43 | File | `/setting` | Medium
44 | File | `/sicweb-ajax/tmproot/` | High
45 | File | `/spip.php` | Medium
46 | File | `/student/bookdetails.php` | High
47 | ... | ... | ...

There are 411 more IOA items available (file, library, argument, input value, pattern, network port). Please use our online service to access the data.

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
