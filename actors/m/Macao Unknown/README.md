# Macao Unknown - Cyber Threat Intelligence

These _indicators_ were reported, collected, and generated during the [VulDB CTI analysis](https://vuldb.com/?kb.cti) of the actor known as [Macao Unknown](https://vuldb.com/?actor.macao_unknown). The _activity monitoring_ correlates data from social media, forums, chat rooms, and darknet markets. It helps to determine associated actors, specific activities, expected intentions, emerging research, and ongoing attacks. Our unique _predictive model_ uses _big data_ to forecast activities and their characteristics.

_Live data_ and more _analysis capabilities_ are available at [https://vuldb.com/?actor.macao_unknown](https://vuldb.com/?actor.macao_unknown)

## Countries

These _countries_ are directly (e.g. origin of attacks) or indirectly (e.g. access by proxy) associated with Macao Unknown:

* [US](https://vuldb.com/?country.us)
* [CN](https://vuldb.com/?country.cn)
* [TR](https://vuldb.com/?country.tr)
* ...

There are 21 more country items available. Please use our online service to access the data.

## IOC - Indicator of Compromise

These _indicators of compromise_ (IOC) indicate associated network resources which are known to be part of research and attack activities of Macao Unknown.

ID | IP address | Hostname | Campaign | Confidence
-- | ---------- | -------- | -------- | ----------
1 | [5.62.60.240](https://vuldb.com/?ip.5.62.60.240) | r-240-60-62-5.consumer-pool.prcdn.net | - | High
2 | [5.62.62.232](https://vuldb.com/?ip.5.62.62.232) | r-232-62-62-5.consumer-pool.prcdn.net | - | High
3 | [17.91.136.0](https://vuldb.com/?ip.17.91.136.0) | - | - | High
4 | [17.91.232.0](https://vuldb.com/?ip.17.91.232.0) | - | - | High
5 | [17.255.252.160](https://vuldb.com/?ip.17.255.252.160) | - | - | High
6 | [23.36.128.0](https://vuldb.com/?ip.23.36.128.0) | a23-36-128-0.deploy.static.akamaitechnologies.com | - | High
7 | [23.67.62.0](https://vuldb.com/?ip.23.67.62.0) | a23-67-62-0.deploy.static.akamaitechnologies.com | - | High
8 | [27.100.20.0](https://vuldb.com/?ip.27.100.20.0) | - | - | High
9 | [27.100.21.0](https://vuldb.com/?ip.27.100.21.0) | - | - | High
10 | [27.100.22.0](https://vuldb.com/?ip.27.100.22.0) | - | - | High
11 | [27.109.128.0](https://vuldb.com/?ip.27.109.128.0) | nz128l0.bb27109.ctm.net | - | High
12 | [42.247.5.192](https://vuldb.com/?ip.42.247.5.192) | - | - | High
13 | [42.247.5.200](https://vuldb.com/?ip.42.247.5.200) | - | - | High
14 | [43.152.149.0](https://vuldb.com/?ip.43.152.149.0) | - | - | High
15 | [43.224.88.0](https://vuldb.com/?ip.43.224.88.0) | - | - | High
16 | [43.247.24.0](https://vuldb.com/?ip.43.247.24.0) | m002424743.mtel.net.mo | - | High
17 | [43.249.215.0](https://vuldb.com/?ip.43.249.215.0) | - | - | High
18 | [45.12.70.149](https://vuldb.com/?ip.45.12.70.149) | 3051-anyway.alltieinc.com | - | High
19 | [45.12.71.149](https://vuldb.com/?ip.45.12.71.149) | - | - | High
20 | [45.64.20.0](https://vuldb.com/?ip.45.64.20.0) | n4564z20l0.static.ctmip.net | - | High
21 | [45.123.200.0](https://vuldb.com/?ip.45.123.200.0) | m0020012345.mtel.net.mo | - | High
22 | [46.244.29.112](https://vuldb.com/?ip.46.244.29.112) | - | - | High
23 | [60.246.0.0](https://vuldb.com/?ip.60.246.0.0) | nz0l0.bb60246.ctm.net | - | High
24 | [64.64.121.112](https://vuldb.com/?ip.64.64.121.112) | - | - | High
25 | [84.252.92.0](https://vuldb.com/?ip.84.252.92.0) | - | - | High
26 | ... | ... | ... | ...

There are 102 more IOC items available. Please use our online service to access the data.

## TTP - Tactics, Techniques, Procedures

_Tactics, techniques, and procedures_ (TTP) summarize the suspected MITRE ATT&CK techniques used by _Macao Unknown_. This data is unique as it uses our predictive model for actor profiling.

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

These _indicators of attack_ (IOA) list the potential fragments used for technical activities like reconnaissance, exploitation, privilege escalation, and exfiltration by Macao Unknown. This data is unique as it uses our predictive model for actor profiling.

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
14 | File | `/api/v1/terminal/sessions/?limit=1` | High
15 | File | `/api/v4/teams//channels/deleted` | High
16 | File | `/api/wechat/app_auth` | High
17 | File | `/b2b-supermarket/shopping-cart` | High
18 | File | `/cancel.php` | Medium
19 | File | `/category.php` | High
20 | File | `/categorypage.php` | High
21 | File | `/cgi-bin/cstecgi.cgi` | High
22 | File | `/cgi-bin/vitogate.cgi` | High
23 | File | `/change-language/de_DE` | High
24 | File | `/control/register_case.php` | High
25 | File | `/debug/pprof` | Medium
26 | File | `/devinfo` | Medium
27 | File | `/dist/index.js` | High
28 | File | `/download` | Medium
29 | File | `/fcgi/scrut_fcgi.fcgi` | High
30 | File | `/forum/away.php` | High
31 | File | `/geoserver/gwc/rest.html` | High
32 | File | `/goform/formSysCmd` | High
33 | File | `/HNAP1` | Low
34 | File | `/hosts/firewall/ip` | High
35 | File | `/index.jsp#settings` | High
36 | File | `/index.php` | Medium
37 | File | `/index.php/ccm/system/file/upload` | High
38 | File | `/labvantage/rc?command=page&page=SampleList&_iframename=list` | High
39 | File | `/log/decodmail.php` | High
40 | File | `/ndmComponents.js` | High
41 | File | `/oauth/idp/.well-known/openid-configuration` | High
42 | File | `/OA_HTML/cabo/jsps/a.jsp` | High
43 | File | `/one_church/churchprofile.php` | High
44 | File | `/php/ping.php` | High
45 | File | `/proxy` | Low
46 | File | `/register.php` | High
47 | File | `/RPS2019Service/status.html` | High
48 | File | `/s/index.php?action=statistics` | High
49 | File | `/setting` | Medium
50 | ... | ... | ...

There are 434 more IOA items available (file, library, argument, input value, pattern, network port). Please use our online service to access the data.

## References

The following list contains _external sources_ which discuss the actor and the associated activities:

* https://github.com/firehol/blocklist-ipsets/blob/master/geolite2_country/country_mo.netset
* https://github.com/firehol/blocklist-ipsets/blob/master/ip2location_country/ip2location_country_mo.netset
* https://github.com/firehol/blocklist-ipsets/blob/master/ipip_country/ipip_country_mo.netset
* https://github.com/scriptzteam/Private-Internet-Access-VPN-Servers/blob/main/export.csv

## Literature

The following _articles_ explain our unique predictive cyber threat intelligence:

* [VulDB Cyber Threat Intelligence Documentation](https://vuldb.com/?kb.cti)
* [Cyber Threat Intelligence - Early Anticipation of Attacks](https://www.scip.ch/en/?labs.20201022)

## License

(c) [1997-2024](https://vuldb.com/?kb.changelog) by [vuldb.com](https://vuldb.com/?kb.about). All data on this page is shared under the license [CC BY-NC-SA 4.0](https://creativecommons.org/licenses/by-nc-sa/4.0/). Questions? Check the [FAQ](https://vuldb.com/?kb.faq), read the [documentation](https://vuldb.com/?kb) or [contact us](https://vuldb.com/?contact)!
