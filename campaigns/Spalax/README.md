# Spalax - Cyber Threat Intelligence

These _indicators_ were reported, collected, and generated during the [VulDB CTI analysis](https://vuldb.com/?kb.cti) of the campaign known as _Spalax_. The _activity monitoring_ correlates data from social media, forums, chat rooms, and darknet markets. It helps to determine associated actors, specific activities, expected intentions, emerging research, and ongoing attacks. Our unique _predictive model_ uses _big data_ to forecast activities and their characteristics.

_Live data_ and more _analysis capabilities_ are available at [https://vuldb.com/?actor](https://vuldb.com/?actor)

## Countries

These _countries_ are directly (e.g. origin of attacks) or indirectly (e.g. access by proxy) associated with Spalax:

* [US](https://vuldb.com/?country.us)
* [CN](https://vuldb.com/?country.cn)
* [GB](https://vuldb.com/?country.gb)
* ...

There are 19 more country items available. Please use our online service to access the data.

## Actors

These _actors_ are associated with Spalax or other actors linked to the campaign.

ID | Actor | Confidence
-- | ----- | ----------
1 | [Spalax](https://vuldb.com/?actor.spalax) | High

## IOC - Indicator of Compromise

These _indicators of compromise_ (IOC) indicate associated network resources which are known to be part of research and attack activities of Spalax.

ID | IP address | Hostname | Actor | Confidence
-- | ---------- | -------- | ----- | ----------
1 | [128.90.108.132](https://vuldb.com/?ip.128.90.108.132) | undefined.hostname.localhost | [Spalax](https://vuldb.com/?actor.spalax) | High
2 | [128.90.108.177](https://vuldb.com/?ip.128.90.108.177) | undefined.hostname.localhost | [Spalax](https://vuldb.com/?actor.spalax) | High
3 | [128.90.112.34](https://vuldb.com/?ip.128.90.112.34) | undefined.hostname.localhost | [Spalax](https://vuldb.com/?actor.spalax) | High
4 | [128.90.112.142](https://vuldb.com/?ip.128.90.112.142) | undefined.hostname.localhost | [Spalax](https://vuldb.com/?actor.spalax) | High
5 | [128.90.115.100](https://vuldb.com/?ip.128.90.115.100) | undefined.hostname.localhost | [Spalax](https://vuldb.com/?actor.spalax) | High
6 | [128.90.115.244](https://vuldb.com/?ip.128.90.115.244) | undefined.hostname.localhost | [Spalax](https://vuldb.com/?actor.spalax) | High
7 | [179.14.171.7](https://vuldb.com/?ip.179.14.171.7) | Dinamic-Tigo-179-14-171-7.tigo.com.co | [Spalax](https://vuldb.com/?actor.spalax) | High
8 | [179.14.173.93](https://vuldb.com/?ip.179.14.173.93) | Dinamic-Tigo-179-14-173-93.tigo.com.co | [Spalax](https://vuldb.com/?actor.spalax) | High
9 | [181.49.90.193](https://vuldb.com/?ip.181.49.90.193) | dynamic-ip-1814990193.cable.net.co | [Spalax](https://vuldb.com/?actor.spalax) | High
10 | [181.52.100.157](https://vuldb.com/?ip.181.52.100.157) | static-ip-cr181520100157.cable.net.co | [Spalax](https://vuldb.com/?actor.spalax) | High
11 | [181.52.102.87](https://vuldb.com/?ip.181.52.102.87) | static-ip-cr18152010287.cable.net.co | [Spalax](https://vuldb.com/?actor.spalax) | High
12 | [181.52.103.140](https://vuldb.com/?ip.181.52.103.140) | static-ip-cr181520103140.cable.net.co | [Spalax](https://vuldb.com/?actor.spalax) | High
13 | [181.52.104.2](https://vuldb.com/?ip.181.52.104.2) | static-ip-cr1815201042.cable.net.co | [Spalax](https://vuldb.com/?actor.spalax) | High
14 | ... | ... | ... | ...

There are 51 more IOC items available. Please use our online service to access the data.

## TTP - Tactics, Techniques, Procedures

_Tactics, techniques, and procedures_ (TTP) summarize the suspected MITRE ATT&CK techniques used within Spalax. This data is unique as it uses our predictive model for actor profiling.

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

These _indicators of attack_ (IOA) list the potential fragments used for technical activities like reconnaissance, exploitation, privilege escalation, and exfiltration during Spalax. This data is unique as it uses our predictive model for actor profiling.

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
15 | File | `/bitrix/admin/ldap_server_edit.php` | High
16 | File | `/category.php` | High
17 | File | `/categorypage.php` | High
18 | File | `/cgi-bin/cstecgi.cgi` | High
19 | File | `/cgi-bin/luci/api/wireless` | High
20 | File | `/cgi-bin/vitogate.cgi` | High
21 | File | `/change-language/de_DE` | High
22 | File | `/Content/Template/root/reverse-shell.aspx` | High
23 | File | `/core/conditions/AbstractWrapper.java` | High
24 | File | `/debug/pprof` | Medium
25 | File | `/devinfo` | Medium
26 | File | `/dist/index.js` | High
27 | File | `/etc/passwd` | Medium
28 | File | `/fcgi/scrut_fcgi.fcgi` | High
29 | File | `/forum/away.php` | High
30 | File | `/geoserver/gwc/rest.html` | High
31 | File | `/goform/formSysCmd` | High
32 | File | `/HNAP1` | Low
33 | File | `/hosts/firewall/ip` | High
34 | File | `/index.jsp#settings` | High
35 | File | `/index.php/ccm/system/file/upload` | High
36 | File | `/jeecg-boot/sys/common/upload` | High
37 | File | `/log/decodmail.php` | High
38 | File | `/oauth/idp/.well-known/openid-configuration` | High
39 | File | `/OA_HTML/cabo/jsps/a.jsp` | High
40 | File | `/php/ping.php` | High
41 | File | `/proxy` | Low
42 | File | `/recipe-result` | High
43 | File | `/register.do` | Medium
44 | File | `/RPS2019Service/status.html` | High
45 | File | `/s/index.php?action=statistics` | High
46 | File | `/setting` | Medium
47 | File | `/sicweb-ajax/tmproot/` | High
48 | File | `/signup.php` | Medium
49 | ... | ... | ...

There are 422 more IOA items available (file, library, argument, input value, pattern, network port). Please use our online service to access the data.

## References

The following list contains _external sources_ which discuss the campaign and the associated activities:

* https://github.com/eset/malware-ioc/tree/master/spalax

## Literature

The following _articles_ explain our unique predictive cyber threat intelligence:

* [VulDB Cyber Threat Intelligence Documentation](https://vuldb.com/?kb.cti)
* [Cyber Threat Intelligence - Early Anticipation of Attacks](https://www.scip.ch/en/?labs.20201022)

## License

(c) [1997-2024](https://vuldb.com/?kb.changelog) by [vuldb.com](https://vuldb.com/?kb.about). All data on this page is shared under the license [CC BY-NC-SA 4.0](https://creativecommons.org/licenses/by-nc-sa/4.0/). Questions? Check the [FAQ](https://vuldb.com/?kb.faq), read the [documentation](https://vuldb.com/?kb) or [contact us](https://vuldb.com/?contact)!
