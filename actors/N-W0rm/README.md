# N-W0rm - Cyber Threat Intelligence

These _indicators_ were reported, collected, and generated during the [VulDB CTI analysis](https://vuldb.com/?kb.cti) of the actor known as [N-W0rm](https://vuldb.com/?actor.n-w0rm). The _activity monitoring_ correlates data from social media, forums, chat rooms, and darknet markets. It helps to determine associated actors, specific activities, expected intentions, emerging research, and ongoing attacks. Our unique _predictive model_ uses _big data_ to forecast activities and their characteristics.

_Live data_ and more _analysis capabilities_ are available at [https://vuldb.com/?actor.n-w0rm](https://vuldb.com/?actor.n-w0rm)

## Countries

These _countries_ are directly (e.g. origin of attacks) or indirectly (e.g. access by proxy) associated with N-W0rm:

* [CN](https://vuldb.com/?country.cn)
* [US](https://vuldb.com/?country.us)
* [GB](https://vuldb.com/?country.gb)
* ...

There are 19 more country items available. Please use our online service to access the data.

## IOC - Indicator of Compromise

These _indicators of compromise_ (IOC) indicate associated network resources which are known to be part of research and attack activities of N-W0rm.

ID | IP address | Hostname | Campaign | Confidence
-- | ---------- | -------- | -------- | ----------
1 | [2.56.254.54](https://vuldb.com/?ip.2.56.254.54) | - | - | High
2 | [5.188.159.44](https://vuldb.com/?ip.5.188.159.44) | - | - | High
3 | [20.48.21.149](https://vuldb.com/?ip.20.48.21.149) | - | - | High
4 | [23.7.53.229](https://vuldb.com/?ip.23.7.53.229) | a23-7-53-229.deploy.static.akamaitechnologies.com | - | High
5 | [23.8.82.173](https://vuldb.com/?ip.23.8.82.173) | a23-8-82-173.deploy.static.akamaitechnologies.com | - | High
6 | [23.9.169.37](https://vuldb.com/?ip.23.9.169.37) | a23-9-169-37.deploy.static.akamaitechnologies.com | - | High
7 | [23.204.189.35](https://vuldb.com/?ip.23.204.189.35) | a23-204-189-35.deploy.static.akamaitechnologies.com | - | High
8 | [35.83.156.201](https://vuldb.com/?ip.35.83.156.201) | ec2-35-83-156-201.us-west-2.compute.amazonaws.com | - | Medium
9 | [35.168.183.178](https://vuldb.com/?ip.35.168.183.178) | ec2-35-168-183-178.compute-1.amazonaws.com | - | Medium
10 | [37.113.171.12](https://vuldb.com/?ip.37.113.171.12) | dynamicip-37-113-171-12.pppoe.chel.ertelecom.ru | - | High
11 | [37.120.141.147](https://vuldb.com/?ip.37.120.141.147) | - | - | High
12 | [37.120.141.190](https://vuldb.com/?ip.37.120.141.190) | - | - | High
13 | [37.139.129.243](https://vuldb.com/?ip.37.139.129.243) | - | - | High
14 | ... | ... | ... | ...

There are 52 more IOC items available. Please use our online service to access the data.

## TTP - Tactics, Techniques, Procedures

_Tactics, techniques, and procedures_ (TTP) summarize the suspected MITRE ATT&CK techniques used by _N-W0rm_. This data is unique as it uses our predictive model for actor profiling.

ID | Technique | Weakness | Description | Confidence
-- | --------- | -------- | ----------- | ----------
1 | T1006 | CWE-21, CWE-22, CWE-23, CWE-425 | Pathname Traversal | High
2 | T1040 | CWE-319 | Authentication Bypass by Capture-replay | High
3 | T1055 | CWE-74 | Injection | High
4 | T1059 | CWE-94, CWE-1321 | Cross Site Scripting | High
5 | T1059.007 | CWE-79, CWE-80 | Cross Site Scripting | High
6 | T1068 | CWE-264, CWE-269, CWE-284 | J2EE Misconfiguration: Weak Access Permissions for EJB Methods | High
7 | ... | ... | ... | ...

There are 23 more TTP items available. Please use our online service to access the data.

## IOA - Indicator of Attack

These _indicators of attack_ (IOA) list the potential fragments used for technical activities like reconnaissance, exploitation, privilege escalation, and exfiltration by N-W0rm. This data is unique as it uses our predictive model for actor profiling.

ID | Type | Indicator | Confidence
-- | ---- | --------- | ----------
1 | File | `%SYSTEMDRIVE%\node_modules\.bin\wmic.exe` | High
2 | File | `//proc/kcore` | Medium
3 | File | `/admin/action/delete-vaccine.php` | High
4 | File | `/admin/controller/JobLogController.java` | High
5 | File | `/admin/index2.html` | High
6 | File | `/admin/save.php` | High
7 | File | `/api/download` | High
8 | File | `/api/sys/login` | High
9 | File | `/api/sys/set_passwd` | High
10 | File | `/api/trackedEntityInstances` | High
11 | File | `/api/v1/alerts` | High
12 | File | `/api/v1/terminal/sessions/?limit=1` | High
13 | File | `/app/index/controller/Common.php` | High
14 | File | `/aux` | Low
15 | File | `/b2b-supermarket/shopping-cart` | High
16 | File | `/bitrix/admin/ldap_server_edit.php` | High
17 | File | `/category.php` | High
18 | File | `/categorypage.php` | High
19 | File | `/cgi-bin/vitogate.cgi` | High
20 | File | `/change-language/de_DE` | High
21 | File | `/changePassword` | High
22 | File | `/course/filterRecords/` | High
23 | File | `/data/remove` | Medium
24 | File | `/debug/pprof` | Medium
25 | File | `/dist/index.js` | High
26 | File | `/download/image` | High
27 | File | `/ecshop/admin/template.php` | High
28 | File | `/fcgi/scrut_fcgi.fcgi` | High
29 | File | `/forms/doLogin` | High
30 | File | `/forum/away.php` | High
31 | File | `/geoserver/gwc/rest.html` | High
32 | File | `/goform/formSysCmd` | High
33 | File | `/HNAP1` | Low
34 | File | `/hosts/firewall/ip` | High
35 | File | `/index.php` | Medium
36 | File | `/index.php/ccm/system/file/upload` | High
37 | File | `/listplace/user/ticket/create` | High
38 | File | `/log/decodmail.php` | High
39 | File | `/nagiosxi/admin/banner_message-ajaxhelper.php` | High
40 | File | `/oauth/idp/.well-known/openid-configuration` | High
41 | File | `/OA_HTML/cabo/jsps/a.jsp` | High
42 | File | `/php/ping.php` | High
43 | File | `/proxy` | Low
44 | File | `/RPS2019Service/status.html` | High
45 | File | `/s/index.php?action=statistics` | High
46 | File | `/setting` | Medium
47 | ... | ... | ...

There are 409 more IOA items available (file, library, argument, input value, pattern, network port). Please use our online service to access the data.

## References

The following list contains _external sources_ which discuss the actor and the associated activities:

* https://threatfox.abuse.ch

## Literature

The following _articles_ explain our unique predictive cyber threat intelligence:

* [VulDB Cyber Threat Intelligence Documentation](https://vuldb.com/?kb.cti)
* [Cyber Threat Intelligence - Early Anticipation of Attacks](https://www.scip.ch/en/?labs.20201022)

## License

(c) [1997-2024](https://vuldb.com/?kb.changelog) by [vuldb.com](https://vuldb.com/?kb.about). All data on this page is shared under the license [CC BY-NC-SA 4.0](https://creativecommons.org/licenses/by-nc-sa/4.0/). Questions? Check the [FAQ](https://vuldb.com/?kb.faq), read the [documentation](https://vuldb.com/?kb) or [contact us](https://vuldb.com/?contact)!
