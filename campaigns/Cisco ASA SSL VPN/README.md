# Cisco ASA SSL VPN - Cyber Threat Intelligence

These _indicators_ were reported, collected, and generated during the [VulDB CTI analysis](https://vuldb.com/?kb.cti) of the campaign known as _Cisco ASA SSL VPN_. The _activity monitoring_ correlates data from social media, forums, chat rooms, and darknet markets. It helps to determine associated actors, specific activities, expected intentions, emerging research, and ongoing attacks. Our unique _predictive model_ uses _big data_ to forecast activities and their characteristics.

_Live data_ and more _analysis capabilities_ are available at [https://vuldb.com/?actor](https://vuldb.com/?actor)

## Countries

These _countries_ are directly (e.g. origin of attacks) or indirectly (e.g. access by proxy) associated with Cisco ASA SSL VPN:

* [US](https://vuldb.com/?country.us)
* [CN](https://vuldb.com/?country.cn)
* [GB](https://vuldb.com/?country.gb)
* ...

There are 23 more country items available. Please use our online service to access the data.

## Actors

These _actors_ are associated with Cisco ASA SSL VPN or other actors linked to the campaign.

ID | Actor | Confidence
-- | ----- | ----------
1 | [Unknown](https://vuldb.com/?actor.unknown) | High

## IOC - Indicator of Compromise

These _indicators of compromise_ (IOC) indicate associated network resources which are known to be part of research and attack activities of Cisco ASA SSL VPN.

ID | IP address | Hostname | Actor | Confidence
-- | ---------- | -------- | ----- | ----------
1 | [5.61.43.231](https://vuldb.com/?ip.5.61.43.231) | - | [Unknown](https://vuldb.com/?actor.unknown) | High
2 | [5.183.253.129](https://vuldb.com/?ip.5.183.253.129) | - | [Unknown](https://vuldb.com/?actor.unknown) | High
3 | [31.184.236.63](https://vuldb.com/?ip.31.184.236.63) | zemal.kiprises.net | [Unknown](https://vuldb.com/?actor.unknown) | High
4 | [31.184.236.71](https://vuldb.com/?ip.31.184.236.71) | miseria.independentbookstores.net | [Unknown](https://vuldb.com/?actor.unknown) | High
5 | [31.184.236.79](https://vuldb.com/?ip.31.184.236.79) | - | [Unknown](https://vuldb.com/?actor.unknown) | High
6 | [45.66.209.122](https://vuldb.com/?ip.45.66.209.122) | - | [Unknown](https://vuldb.com/?actor.unknown) | High
7 | [45.80.107.220](https://vuldb.com/?ip.45.80.107.220) | - | [Unknown](https://vuldb.com/?actor.unknown) | High
8 | [45.227.252.237](https://vuldb.com/?ip.45.227.252.237) | - | [Unknown](https://vuldb.com/?actor.unknown) | High
9 | [45.227.255.51](https://vuldb.com/?ip.45.227.255.51) | - | [Unknown](https://vuldb.com/?actor.unknown) | High
10 | [46.161.27.123](https://vuldb.com/?ip.46.161.27.123) | - | [Unknown](https://vuldb.com/?actor.unknown) | High
11 | [62.233.50.11](https://vuldb.com/?ip.62.233.50.11) | - | [Unknown](https://vuldb.com/?actor.unknown) | High
12 | [62.233.50.13](https://vuldb.com/?ip.62.233.50.13) | - | [Unknown](https://vuldb.com/?actor.unknown) | High
13 | ... | ... | ... | ...

There are 50 more IOC items available. Please use our online service to access the data.

## TTP - Tactics, Techniques, Procedures

_Tactics, techniques, and procedures_ (TTP) summarize the suspected MITRE ATT&CK techniques used within Cisco ASA SSL VPN. This data is unique as it uses our predictive model for actor profiling.

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

These _indicators of attack_ (IOA) list the potential fragments used for technical activities like reconnaissance, exploitation, privilege escalation, and exfiltration during Cisco ASA SSL VPN. This data is unique as it uses our predictive model for actor profiling.

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
10 | File | `/catalog/admin/categories.php?cPath=&action=new_product` | High
11 | File | `/category.php` | High
12 | File | `/categorypage.php` | High
13 | File | `/cgi-bin/luci/api/wireless` | High
14 | File | `/cgi-bin/vitogate.cgi` | High
15 | File | `/cgi-bin/wlogin.cgi` | High
16 | File | `/change-language/de_DE` | High
17 | File | `/company/store` | High
18 | File | `/Content/Template/root/reverse-shell.aspx` | High
19 | File | `/Controller/Ajaxfileupload.ashx` | High
20 | File | `/core/conditions/AbstractWrapper.java` | High
21 | File | `/debug/pprof` | Medium
22 | File | `/dist/index.js` | High
23 | File | `/Duty/AjaxHandle/UploadFloodPlanFileUpdate.ashx` | High
24 | File | `/etc/passwd` | Medium
25 | File | `/fcgi/scrut_fcgi.fcgi` | High
26 | File | `/forum/away.php` | High
27 | File | `/geoserver/gwc/rest.html` | High
28 | File | `/goform/formSysCmd` | High
29 | File | `/HNAP1` | Low
30 | File | `/hosts/firewall/ip` | High
31 | File | `/index.php/ccm/system/file/upload` | High
32 | File | `/jeecg-boot/sys/common/upload` | High
33 | File | `/load.php` | Medium
34 | File | `/log/decodmail.php` | High
35 | File | `/oauth/idp/.well-known/openid-configuration` | High
36 | File | `/OA_HTML/cabo/jsps/a.jsp` | High
37 | File | `/php/ping.php` | High
38 | File | `/proxy` | Low
39 | File | `/recipe-result` | High
40 | File | `/register.do` | Medium
41 | File | `/RPS2019Service/status.html` | High
42 | File | `/s/index.php?action=statistics` | High
43 | File | `/Service/ImageStationDataService.asmx` | High
44 | File | `/setting` | Medium
45 | File | `/sicweb-ajax/tmproot/` | High
46 | ... | ... | ...

There are 400 more IOA items available (file, library, argument, input value, pattern, network port). Please use our online service to access the data.

## References

The following list contains _external sources_ which discuss the campaign and the associated activities:

* https://www.rapid7.com/blog/post/2023/08/29/under-siege-rapid7-observed-exploitation-of-cisco-asa-ssl-vpns/

## Literature

The following _articles_ explain our unique predictive cyber threat intelligence:

* [VulDB Cyber Threat Intelligence Documentation](https://vuldb.com/?kb.cti)
* [Cyber Threat Intelligence - Early Anticipation of Attacks](https://www.scip.ch/en/?labs.20201022)

## License

(c) [1997-2024](https://vuldb.com/?kb.changelog) by [vuldb.com](https://vuldb.com/?kb.about). All data on this page is shared under the license [CC BY-NC-SA 4.0](https://creativecommons.org/licenses/by-nc-sa/4.0/). Questions? Check the [FAQ](https://vuldb.com/?kb.faq), read the [documentation](https://vuldb.com/?kb) or [contact us](https://vuldb.com/?contact)!
