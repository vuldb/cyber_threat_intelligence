# Cisco ASA SSL VPN - Cyber Threat Intelligence

These _indicators_ were reported, collected, and generated during the [VulDB CTI analysis](https://vuldb.com/?kb.cti) of the campaign known as _Cisco ASA SSL VPN_. The _activity monitoring_ correlates data from social media, forums, chat rooms, and darknet markets. It helps to determine associated actors, specific activities, expected intentions, emerging research, and ongoing attacks. Our unique _predictive model_ uses _big data_ to forecast activities and their characteristics.

_Live data_ and more _analysis capabilities_ are available at [https://vuldb.com/?actor](https://vuldb.com/?actor)

## Countries

These _countries_ are directly (e.g. origin of attacks) or indirectly (e.g. access by proxy) associated with Cisco ASA SSL VPN:

* [US](https://vuldb.com/?country.us)
* [CN](https://vuldb.com/?country.cn)
* [TR](https://vuldb.com/?country.tr)
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
1 | T1006 | CWE-21, CWE-22, CWE-23, CWE-25, CWE-36, CWE-425 | Path Traversal | High
2 | T1040 | CWE-319 | Authentication Bypass by Capture-replay | High
3 | T1055 | CWE-74 | Improper Neutralization of Data within XPath Expressions | High
4 | T1059 | CWE-88, CWE-94, CWE-1321 | Argument Injection | High
5 | T1059.007 | CWE-79, CWE-80 | Cross Site Scripting | High
6 | ... | ... | ... | ...

There are 20 more TTP items available. Please use our online service to access the data.

## IOA - Indicator of Attack

These _indicators of attack_ (IOA) list the potential fragments used for technical activities like reconnaissance, exploitation, privilege escalation, and exfiltration during Cisco ASA SSL VPN. This data is unique as it uses our predictive model for actor profiling.

ID | Type | Indicator | Confidence
-- | ---- | --------- | ----------
1 | File | `%SYSTEMDRIVE%\node_modules\.bin\wmic.exe` | High
2 | File | `/#ilang=DE&b=c_smartenergy_swgroups` | High
3 | File | `/#ProductSerie/view/` | High
4 | File | `/?ajax-request=jnews` | High
5 | File | `/Account/login.php` | High
6 | File | `/admin/` | Low
7 | File | `/Admin/changepassword.php` | High
8 | File | `/admin/general-setting` | High
9 | File | `/admin/service` | High
10 | File | `/adminapi/system/crud` | High
11 | File | `/adminapi/system/file/openfile` | High
12 | File | `/admin_route/dec_service_credits.php` | High
13 | File | `/api/v1/alerts` | High
14 | File | `/api/v1/custom_component` | High
15 | File | `/api/v4/teams//channels/deleted` | High
16 | File | `/api/wechat/app_auth` | High
17 | File | `/b2b-supermarket/shopping-cart` | High
18 | File | `/cancel.php` | Medium
19 | File | `/catalog/admin/categories.php?cPath=&action=new_product` | High
20 | File | `/category.php` | High
21 | File | `/cgi-bin/cstecgi.cgi` | High
22 | File | `/cgi-bin/nas_sharing.cgi` | High
23 | File | `/cgi-bin/wlogin.cgi` | High
24 | File | `/change-language/de_DE` | High
25 | File | `/classes/Users.php?f=delete` | High
26 | File | `/control/register_case.php` | High
27 | File | `/debug/pprof` | Medium
28 | File | `/devinfo` | Medium
29 | File | `/dist/index.js` | High
30 | File | `/download` | Medium
31 | File | `/Duty/AjaxHandle/UploadFloodPlanFileUpdate.ashx` | High
32 | File | `/fcgi/scrut_fcgi.fcgi` | High
33 | File | `/forum/away.php` | High
34 | File | `/geoserver/gwc/rest.html` | High
35 | File | `/goform/formSysCmd` | High
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
46 | File | `/ows-bin` | Medium
47 | File | `/php/ping.php` | High
48 | File | `/proxy` | Low
49 | File | `/register.php` | High
50 | ... | ... | ...

There are 430 more IOA items available (file, library, argument, input value, pattern, network port). Please use our online service to access the data.

## References

The following list contains _external sources_ which discuss the campaign and the associated activities:

* https://www.rapid7.com/blog/post/2023/08/29/under-siege-rapid7-observed-exploitation-of-cisco-asa-ssl-vpns/

## Literature

The following _articles_ explain our unique predictive cyber threat intelligence:

* [VulDB Cyber Threat Intelligence Documentation](https://vuldb.com/?kb.cti)
* [Cyber Threat Intelligence - Early Anticipation of Attacks](https://www.scip.ch/en/?labs.20201022)

## License

(c) [1997-2024](https://vuldb.com/?kb.changelog) by [vuldb.com](https://vuldb.com/?kb.about). All data on this page is shared under the license [CC BY-NC-SA 4.0](https://creativecommons.org/licenses/by-nc-sa/4.0/). Questions? Check the [FAQ](https://vuldb.com/?kb.faq), read the [documentation](https://vuldb.com/?kb) or [contact us](https://vuldb.com/?contact)!
