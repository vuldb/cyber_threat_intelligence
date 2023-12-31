# APT-C-36 - Cyber Threat Intelligence

These _indicators_ were reported, collected, and generated during the [VulDB CTI analysis](https://vuldb.com/?kb.cti) of the actor known as [APT-C-36](https://vuldb.com/?actor.apt-c-36). The _activity monitoring_ correlates data from social media, forums, chat rooms, and darknet markets. It helps to determine associated actors, specific activities, expected intentions, emerging research, and ongoing attacks. Our unique _predictive model_ uses _big data_ to forecast activities and their characteristics.

_Live data_ and more _analysis capabilities_ are available at [https://vuldb.com/?actor.apt-c-36](https://vuldb.com/?actor.apt-c-36)

## Countries

These _countries_ are directly (e.g. origin of attacks) or indirectly (e.g. access by proxy) associated with APT-C-36:

* [US](https://vuldb.com/?country.us)
* [CN](https://vuldb.com/?country.cn)
* [GB](https://vuldb.com/?country.gb)
* ...

There are 20 more country items available. Please use our online service to access the data.

## IOC - Indicator of Compromise

These _indicators of compromise_ (IOC) indicate associated network resources which are known to be part of research and attack activities of APT-C-36.

ID | IP address | Hostname | Campaign | Confidence
-- | ---------- | -------- | -------- | ----------
1 | [46.246.12.6](https://vuldb.com/?ip.46.246.12.6) | c-46-246-12-6.ip4.frootvpn.com | - | High
2 | [46.246.86.3](https://vuldb.com/?ip.46.246.86.3) | c-46-246-86-3.ip4.frootvpn.com | - | High
3 | [128.90.106.22](https://vuldb.com/?ip.128.90.106.22) | undefined.hostname.localhost | - | High
4 | ... | ... | ... | ...

There are 8 more IOC items available. Please use our online service to access the data.

## TTP - Tactics, Techniques, Procedures

_Tactics, techniques, and procedures_ (TTP) summarize the suspected MITRE ATT&CK techniques used by _APT-C-36_. This data is unique as it uses our predictive model for actor profiling.

ID | Technique | Weakness | Description | Confidence
-- | --------- | -------- | ----------- | ----------
1 | T1006 | CWE-21, CWE-22, CWE-23, CWE-425 | Pathname Traversal | High
2 | T1040 | CWE-319 | Authentication Bypass by Capture-replay | High
3 | T1055 | CWE-74 | Injection | High
4 | T1059 | CWE-88, CWE-94, CWE-1321 | Cross Site Scripting | High
5 | T1059.007 | CWE-79, CWE-80 | Cross Site Scripting | High
6 | ... | ... | ... | ...

There are 22 more TTP items available. Please use our online service to access the data.

## IOA - Indicator of Attack

These _indicators of attack_ (IOA) list the potential fragments used for technical activities like reconnaissance, exploitation, privilege escalation, and exfiltration by APT-C-36. This data is unique as it uses our predictive model for actor profiling.

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
10 | File | `/category.php` | High
11 | File | `/categorypage.php` | High
12 | File | `/cgi-bin/luci/api/wireless` | High
13 | File | `/cgi-bin/vitogate.cgi` | High
14 | File | `/company/store` | High
15 | File | `/Content/Template/root/reverse-shell.aspx` | High
16 | File | `/Controller/Ajaxfileupload.ashx` | High
17 | File | `/core/conditions/AbstractWrapper.java` | High
18 | File | `/debug/pprof` | Medium
19 | File | `/etc/passwd` | Medium
20 | File | `/fcgi/scrut_fcgi.fcgi` | High
21 | File | `/forum/away.php` | High
22 | File | `/geoserver/gwc/rest.html` | High
23 | File | `/goform/formSysCmd` | High
24 | File | `/h/` | Low
25 | File | `/HNAP1` | Low
26 | File | `/hosts/firewall/ip` | High
27 | File | `/inc/jquery/uploadify/uploadify.php` | High
28 | File | `/index.php/ccm/system/file/upload` | High
29 | File | `/index.php?app=main&func=passport&action=login` | High
30 | File | `/index.php?page=category_list` | High
31 | File | `/jeecg-boot/sys/common/upload` | High
32 | File | `/jobinfo/` | Medium
33 | File | `/oauth/idp/.well-known/openid-configuration` | High
34 | File | `/OA_HTML/cabo/jsps/a.jsp` | High
35 | File | `/php/ping.php` | High
36 | File | `/PreviewHandler.ashx` | High
37 | File | `/proxy` | Low
38 | File | `/recipe-result` | High
39 | File | `/register.do` | Medium
40 | File | `/RPS2019Service/status.html` | High
41 | File | `/Service/ImageStationDataService.asmx` | High
42 | File | `/setting` | Medium
43 | File | `/sicweb-ajax/tmproot/` | High
44 | ... | ... | ...

There are 382 more IOA items available (file, library, argument, input value, pattern, network port). Please use our online service to access the data.

## References

The following list contains _external sources_ which discuss the actor and the associated activities:

* https://blogs.blackberry.com/en/2023/02/blind-eagle-apt-c-36-targets-colombia
* https://web.archive.org/web/20190625182633if_/https://ti.360.net/blog/articles/apt-c-36-continuous-attacks-targeting-colombian-government-institutions-and-corporations-en/

## Literature

The following _articles_ explain our unique predictive cyber threat intelligence:

* [VulDB Cyber Threat Intelligence Documentation](https://vuldb.com/?kb.cti)
* [Cyber Threat Intelligence - Early Anticipation of Attacks](https://www.scip.ch/en/?labs.20201022)

## License

(c) [1997-2023](https://vuldb.com/?kb.changelog) by [vuldb.com](https://vuldb.com/?kb.about). All data on this page is shared under the license [CC BY-NC-SA 4.0](https://creativecommons.org/licenses/by-nc-sa/4.0/). Questions? Check the [FAQ](https://vuldb.com/?kb.faq), read the [documentation](https://vuldb.com/?kb) or [contact us](https://vuldb.com/?contact)!
