# Transparent Tribe - Cyber Threat Intelligence

These _indicators_ were reported, collected, and generated during the [VulDB CTI analysis](https://vuldb.com/?kb.cti) of the actor known as [Transparent Tribe](https://vuldb.com/?actor.transparent_tribe). The _activity monitoring_ correlates data from social media, forums, chat rooms, and darknet markets. It helps to determine associated actors, specific activities, expected intentions, emerging research, and ongoing attacks. Our unique _predictive model_ uses _big data_ to forecast activities and their characteristics.

_Live data_ and more _analysis capabilities_ are available at [https://vuldb.com/?actor.transparent_tribe](https://vuldb.com/?actor.transparent_tribe)

## Campaigns

The following _campaigns_ are known and can be associated with Transparent Tribe:

* COVID-19
* Education
* Indian Defense Officials

## Countries

These _countries_ are directly (e.g. origin of attacks) or indirectly (e.g. access by proxy) associated with Transparent Tribe:

* [US](https://vuldb.com/?country.us)
* [RU](https://vuldb.com/?country.ru)
* [IS](https://vuldb.com/?country.is)
* ...

There are 12 more country items available. Please use our online service to access the data.

## IOC - Indicator of Compromise

These _indicators of compromise_ (IOC) indicate associated network resources which are known to be part of research and attack activities of Transparent Tribe.

ID | IP address | Hostname | Campaign | Confidence
-- | ---------- | -------- | -------- | ----------
1 | [5.189.131.67](https://vuldb.com/?ip.5.189.131.67) | officetech.pkofficetech.pk | - | High
2 | [5.189.137.8](https://vuldb.com/?ip.5.189.137.8) | vending.softjourn.if.ua | - | High
3 | [5.189.143.225](https://vuldb.com/?ip.5.189.143.225) | - | - | High
4 | [5.189.145.248](https://vuldb.com/?ip.5.189.145.248) | ip-248-145-189-5.static.contabo.net | - | High
5 | [5.189.152.147](https://vuldb.com/?ip.5.189.152.147) | ccloud.armax.de | - | High
6 | [5.189.167.23](https://vuldb.com/?ip.5.189.167.23) | mltx.de | - | High
7 | [5.189.167.65](https://vuldb.com/?ip.5.189.167.65) | vmi437585.contaboserver.net | - | High
8 | [5.189.167.220](https://vuldb.com/?ip.5.189.167.220) | - | - | High
9 | ... | ... | ... | ...

There are 32 more IOC items available. Please use our online service to access the data.

## TTP - Tactics, Techniques, Procedures

_Tactics, techniques, and procedures_ (TTP) summarize the suspected MITRE ATT&CK techniques used by _Transparent Tribe_. This data is unique as it uses our predictive model for actor profiling.

ID | Technique | Weakness | Description | Confidence
-- | --------- | -------- | ----------- | ----------
1 | T1006 | CWE-22, CWE-23 | Pathname Traversal | High
2 | T1040 | CWE-319 | Authentication Bypass by Capture-replay | High
3 | T1055 | CWE-74 | Injection | High
4 | T1059 | CWE-88, CWE-94 | Cross Site Scripting | High
5 | T1059.007 | CWE-79, CWE-80 | Cross Site Scripting | High
6 | T1068 | CWE-264, CWE-269, CWE-284 | J2EE Misconfiguration: Weak Access Permissions for EJB Methods | High
7 | ... | ... | ... | ...

There are 23 more TTP items available. Please use our online service to access the data.

## IOA - Indicator of Attack

These _indicators of attack_ (IOA) list the potential fragments used for technical activities like reconnaissance, exploitation, privilege escalation, and exfiltration by Transparent Tribe. This data is unique as it uses our predictive model for actor profiling.

ID | Type | Indicator | Confidence
-- | ---- | --------- | ----------
1 | File | `/admin.php?action=editpage` | High
2 | File | `/admin/imagealbum/list` | High
3 | File | `/api/V2/internal/TaskPermissions/CheckTaskAccess` | High
4 | File | `/coders/pdf.c` | High
5 | File | `/download` | Medium
6 | File | `/etc/grafana/grafana.ini` | High
7 | File | `/exponentcms/administration/configure_site` | High
8 | File | `/export` | Low
9 | File | `/forgetpassword.php` | High
10 | File | `/forum/away.php` | High
11 | File | `/fos/admin/ajax.php` | High
12 | File | `/fudforum/index.php` | High
13 | File | `/goform/setVLAN` | High
14 | File | `/goform/WifiBasicSet` | High
15 | File | `/horde/util/go.php` | High
16 | File | `/hss/?page=view_product` | High
17 | File | `/index.php/ccm/system/file/upload` | High
18 | File | `/isms/admin/stocks/view_stock.php` | High
19 | File | `/lab.html` | Medium
20 | File | `/list/<path:folderpath>` | High
21 | File | `/out.php` | Medium
22 | File | `/php-jms/updateBlankTxtview.php` | High
23 | File | `/products/details.asp` | High
24 | File | `/RestAPI` | Medium
25 | File | `/sm/api/v1/firewall/zone/services` | High
26 | File | `/spacecom/login.php` | High
27 | File | `/strings/ctype-simple.c` | High
28 | File | `/sys/dict/queryTableData` | High
29 | File | `/uncpath/` | Medium
30 | File | `/user/dls_download.php` | High
31 | File | `/usr/local/WowzaStreamingEngine/bin/` | High
32 | File | `/v1/sql-runner` | High
33 | File | `/web/IndexController.java` | High
34 | File | `acknowledge.c` | High
35 | File | `actions/CompanyDetailsSave.php` | High
36 | File | `adclick.php` | Medium
37 | File | `add_comment.php` | High
38 | ... | ... | ...

There are 329 more IOA items available (file, library, argument, input value, pattern, network port). Please use our online service to access the data.

## References

The following list contains _external sources_ which discuss the actor and the associated activities:

* https://blog.cyble.com/2021/09/14/apt-group-targets-indian-defense-officials-through-enhanced-ttps/
* https://blog.talosintelligence.com/2022/03/transparent-tribe-new-campaign.html
* https://github.com/Cisco-Talos/IOCs/blob/main/2022/07/transparent-tribe-targets-education.txt
* https://lab52.io/blog/new-transparentribe-operation-targeting-india-with-weaponized-covid-19-lure-documents/
* https://mp.weixin.qq.com/s/xU7b3m-L2OlAi2bU7nBj0A
* https://www.threatminer.org/report.php?q=APTGroupSendsSpearPhishingEmailstoIndianGovernmentOfficials%C2%ABThreatResearchBlog_FireEyeInc.pdf&y=2016
* https://www.threatminer.org/report.php?q=MalwareActorsUsingNICCyberSecurityThemedSpearPhishingtoTargetIndianGovernmentOrganizations-Cysinfo.pdf&y=2016
* https://www.threatminer.org/report.php?q=proofpoint-operation-transparent-tribe-threat-insight-en.pdf&y=2016

## Literature

The following _articles_ explain our unique predictive cyber threat intelligence:

* [VulDB Cyber Threat Intelligence Documentation](https://vuldb.com/?kb.cti)
* [Cyber Threat Intelligence - Early Anticipation of Attacks](https://www.scip.ch/en/?labs.20201022)

## License

(c) [1997-2023](https://vuldb.com/?kb.changelog) by [vuldb.com](https://vuldb.com/?kb.about). All data on this page is shared under the license [CC BY-NC-SA 4.0](https://creativecommons.org/licenses/by-nc-sa/4.0/). Questions? Check the [FAQ](https://vuldb.com/?kb.faq), read the [documentation](https://vuldb.com/?kb) or [contact us](https://vuldb.com/?contact)!
