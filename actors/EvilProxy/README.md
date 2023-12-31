# EvilProxy - Cyber Threat Intelligence

These _indicators_ were reported, collected, and generated during the [VulDB CTI analysis](https://vuldb.com/?kb.cti) of the actor known as [EvilProxy](https://vuldb.com/?actor.evilproxy). The _activity monitoring_ correlates data from social media, forums, chat rooms, and darknet markets. It helps to determine associated actors, specific activities, expected intentions, emerging research, and ongoing attacks. Our unique _predictive model_ uses _big data_ to forecast activities and their characteristics.

_Live data_ and more _analysis capabilities_ are available at [https://vuldb.com/?actor.evilproxy](https://vuldb.com/?actor.evilproxy)

## Countries

These _countries_ are directly (e.g. origin of attacks) or indirectly (e.g. access by proxy) associated with EvilProxy:

* [US](https://vuldb.com/?country.us)
* [CN](https://vuldb.com/?country.cn)
* [GB](https://vuldb.com/?country.gb)
* ...

There are 19 more country items available. Please use our online service to access the data.

## IOC - Indicator of Compromise

These _indicators of compromise_ (IOC) indicate associated network resources which are known to be part of research and attack activities of EvilProxy.

ID | IP address | Hostname | Campaign | Confidence
-- | ---------- | -------- | -------- | ----------
1 | [45.8.191.17](https://vuldb.com/?ip.45.8.191.17) | - | - | High
2 | [45.8.191.151](https://vuldb.com/?ip.45.8.191.151) | - | - | High
3 | [74.208.49.213](https://vuldb.com/?ip.74.208.49.213) | - | - | High
4 | [77.91.84.52](https://vuldb.com/?ip.77.91.84.52) | bijiboy.aeza.network | - | High
5 | [78.153.130.178](https://vuldb.com/?ip.78.153.130.178) | fit-butter.aeza.network | - | High
6 | ... | ... | ... | ...

There are 21 more IOC items available. Please use our online service to access the data.

## TTP - Tactics, Techniques, Procedures

_Tactics, techniques, and procedures_ (TTP) summarize the suspected MITRE ATT&CK techniques used by _EvilProxy_. This data is unique as it uses our predictive model for actor profiling.

ID | Technique | Weakness | Description | Confidence
-- | --------- | -------- | ----------- | ----------
1 | T1006 | CWE-21, CWE-22, CWE-23, CWE-425 | Pathname Traversal | High
2 | T1040 | CWE-319 | Authentication Bypass by Capture-replay | High
3 | T1055 | CWE-74 | Injection | High
4 | T1059 | CWE-88, CWE-94, CWE-1321 | Cross Site Scripting | High
5 | T1059.007 | CWE-79, CWE-80 | Cross Site Scripting | High
6 | ... | ... | ... | ...

There are 21 more TTP items available. Please use our online service to access the data.

## IOA - Indicator of Attack

These _indicators of attack_ (IOA) list the potential fragments used for technical activities like reconnaissance, exploitation, privilege escalation, and exfiltration by EvilProxy. This data is unique as it uses our predictive model for actor profiling.

ID | Type | Indicator | Confidence
-- | ---- | --------- | ----------
1 | File | `%SYSTEMDRIVE%\node_modules\.bin\wmic.exe` | High
2 | File | `//WEB-INF` | Medium
3 | File | `/about.php` | Medium
4 | File | `/admin.php/update/getFile.html` | High
5 | File | `/admin/save.php` | High
6 | File | `/admin/sys_sql_query.php` | High
7 | File | `/api/baskets/{name}` | High
8 | File | `/api/download` | High
9 | File | `/api/v1/alerts` | High
10 | File | `/api/v1/terminal/sessions/?limit=1` | High
11 | File | `/api/v2/cli/commands` | High
12 | File | `/bitrix/admin/ldap_server_edit.php` | High
13 | File | `/category.php` | High
14 | File | `/categorypage.php` | High
15 | File | `/cgi-bin/luci/api/wireless` | High
16 | File | `/cgi-bin/vitogate.cgi` | High
17 | File | `/company/store` | High
18 | File | `/Content/Template/root/reverse-shell.aspx` | High
19 | File | `/Controller/Ajaxfileupload.ashx` | High
20 | File | `/core/conditions/AbstractWrapper.java` | High
21 | File | `/debug/pprof` | Medium
22 | File | `/Duty/AjaxHandle/UploadHandler.ashx` | High
23 | File | `/Duty/AjaxHandle/Write/UploadFile.ashx` | High
24 | File | `/etc/passwd` | Medium
25 | File | `/fcgi/scrut_fcgi.fcgi` | High
26 | File | `/forum/away.php` | High
27 | File | `/geoserver/gwc/rest.html` | High
28 | File | `/h/` | Low
29 | File | `/HNAP1` | Low
30 | File | `/inc/jquery/uploadify/uploadify.php` | High
31 | File | `/index.php?app=main&func=passport&action=login` | High
32 | File | `/index.php?page=category_list` | High
33 | File | `/jeecg-boot/sys/common/upload` | High
34 | File | `/jobinfo/` | Medium
35 | File | `/librarian/bookdetails.php` | High
36 | File | `/Moosikay/order.php` | High
37 | File | `/OA_HTML/cabo/jsps/a.jsp` | High
38 | File | `/opac/Actions.php?a=login` | High
39 | File | `/PreviewHandler.ashx` | High
40 | File | `/proxy` | Low
41 | File | `/recipe-result` | High
42 | File | `/register.do` | Medium
43 | File | `/reservation/add_message.php` | High
44 | File | `/RPS2019Service/status.html` | High
45 | File | `/Service/ImageStationDataService.asmx` | High
46 | File | `/setting` | Medium
47 | ... | ... | ...

There are 409 more IOA items available (file, library, argument, input value, pattern, network port). Please use our online service to access the data.

## References

The following list contains _external sources_ which discuss the actor and the associated activities:

* https://community.blueliv.com/#!/s/6316ed0e82df417b923303f4
* https://www.menlosecurity.com/blog/evilproxy-phishing-attack-strikes-indeed/
* https://www.proofpoint.com/us/blog/email-and-cloud-threats/cloud-account-takeover-campaign-leveraging-evilproxy-targets-top-level

## Literature

The following _articles_ explain our unique predictive cyber threat intelligence:

* [VulDB Cyber Threat Intelligence Documentation](https://vuldb.com/?kb.cti)
* [Cyber Threat Intelligence - Early Anticipation of Attacks](https://www.scip.ch/en/?labs.20201022)

## License

(c) [1997-2023](https://vuldb.com/?kb.changelog) by [vuldb.com](https://vuldb.com/?kb.about). All data on this page is shared under the license [CC BY-NC-SA 4.0](https://creativecommons.org/licenses/by-nc-sa/4.0/). Questions? Check the [FAQ](https://vuldb.com/?kb.faq), read the [documentation](https://vuldb.com/?kb) or [contact us](https://vuldb.com/?contact)!
