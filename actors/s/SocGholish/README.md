# SocGholish - Cyber Threat Intelligence

These _indicators_ were reported, collected, and generated during the [VulDB CTI analysis](https://vuldb.com/?kb.cti) of the actor known as [SocGholish](https://vuldb.com/?actor.socgholish). The _activity monitoring_ correlates data from social media, forums, chat rooms, and darknet markets. It helps to determine associated actors, specific activities, expected intentions, emerging research, and ongoing attacks. Our unique _predictive model_ uses _big data_ to forecast activities and their characteristics.

_Live data_ and more _analysis capabilities_ are available at [https://vuldb.com/?actor.socgholish](https://vuldb.com/?actor.socgholish)

## Countries

These _countries_ are directly (e.g. origin of attacks) or indirectly (e.g. access by proxy) associated with SocGholish:

* [US](https://vuldb.com/?country.us)
* [DE](https://vuldb.com/?country.de)
* [RU](https://vuldb.com/?country.ru)
* ...

There are 14 more country items available. Please use our online service to access the data.

## IOC - Indicator of Compromise

These _indicators of compromise_ (IOC) indicate associated network resources which are known to be part of research and attack activities of SocGholish.

ID | IP address | Hostname | Campaign | Confidence
-- | ---------- | -------- | -------- | ----------
1 | [5.42.199.146](https://vuldb.com/?ip.5.42.199.146) | - | - | High
2 | [5.53.125.173](https://vuldb.com/?ip.5.53.125.173) | authoremail.net | - | High
3 | [45.9.190.217](https://vuldb.com/?ip.45.9.190.217) | - | - | High
4 | [45.10.42.26](https://vuldb.com/?ip.45.10.42.26) | eggvpn.gw | - | High
5 | [45.10.43.78](https://vuldb.com/?ip.45.10.43.78) | v1940286.hosted-by-vdsina.ru | - | High
6 | [77.91.127.52](https://vuldb.com/?ip.77.91.127.52) | static.52.127.91.77.ip.webhost1.net | - | High
7 | [77.223.98.12](https://vuldb.com/?ip.77.223.98.12) | cloud12915.coteseuplano1.com.br | - | High
8 | [82.180.154.113](https://vuldb.com/?ip.82.180.154.113) | - | - | High
9 | [84.32.188.27](https://vuldb.com/?ip.84.32.188.27) | - | - | High
10 | [87.249.50.201](https://vuldb.com/?ip.87.249.50.201) | 832423-cv17319.tmweb.ru | - | High
11 | ... | ... | ... | ...

There are 38 more IOC items available. Please use our online service to access the data.

## TTP - Tactics, Techniques, Procedures

_Tactics, techniques, and procedures_ (TTP) summarize the suspected MITRE ATT&CK techniques used by _SocGholish_. This data is unique as it uses our predictive model for actor profiling.

ID | Technique | Weakness | Description | Confidence
-- | --------- | -------- | ----------- | ----------
1 | T1006 | CWE-22, CWE-425 | Path Traversal | High
2 | T1040 | CWE-294 | Authentication Bypass by Capture-replay | High
3 | T1055 | CWE-74 | Improper Neutralization of Data within XPath Expressions | High
4 | T1059 | CWE-88, CWE-94, CWE-1321 | Argument Injection | High
5 | T1059.007 | CWE-79, CWE-80 | Cross Site Scripting | High
6 | ... | ... | ... | ...

There are 18 more TTP items available. Please use our online service to access the data.

## IOA - Indicator of Attack

These _indicators of attack_ (IOA) list the potential fragments used for technical activities like reconnaissance, exploitation, privilege escalation, and exfiltration by SocGholish. This data is unique as it uses our predictive model for actor profiling.

ID | Type | Indicator | Confidence
-- | ---- | --------- | ----------
1 | File | `//proc/kcore` | Medium
2 | File | `/admin/` | Low
3 | File | `/admin/about-us.php` | High
4 | File | `/admin/action/delete-vaccine.php` | High
5 | File | `/admin/edit-post.php` | High
6 | File | `/admin/index2.html` | High
7 | File | `/api/baskets/{name}` | High
8 | File | `/app/index/controller/Common.php` | High
9 | File | `/applications/core/modules/admin/editor/toolbar.php` | High
10 | File | `/Applications/Google\ Drive.app/Contents/MacOS` | High
11 | File | `/applications/nexus/modules/front/store/store.php` | High
12 | File | `/backend/register.php` | High
13 | File | `/bitrix/admin/ldap_server_edit.php` | High
14 | File | `/cgi-bin/cstecgi.cgi` | High
15 | File | `/cgi-bin/nas_sharing.cgi` | High
16 | File | `/cgi-bin/system_mgr.cgi` | High
17 | File | `/classes/Master.php` | High
18 | File | `/classes/Master.php?f=save_category` | High
19 | File | `/classes/Users.php?f=save` | High
20 | File | `/dcim/rack-roles/` | High
21 | File | `/fftools/ffmpeg_enc.c` | High
22 | File | `/forms/doLogin` | High
23 | File | `/formSysLog` | Medium
24 | File | `/forum/away.php` | High
25 | File | `/goform/SetOnlineDevName` | High
26 | File | `/hotel.php` | Medium
27 | File | `/index.php` | Medium
28 | File | `/index.php?app=main&func=passport&action=login` | High
29 | File | `/install/` | Medium
30 | File | `/listplace/user/ticket/create` | High
31 | File | `/Main_Login.asp?flag=1&productname=RT-AC88U&url=/downloadmaster/task.asp` | High
32 | File | `/members/poster.php` | High
33 | File | `/mhds/clinic/view_details.php` | High
34 | File | `/MIME/INBOX-MM-1/` | High
35 | File | `/novel/author/list` | High
36 | ... | ... | ...

There are 304 more IOA items available (file, library, argument, input value, pattern, network port). Please use our online service to access the data.

## References

The following list contains _external sources_ which discuss the actor and the associated activities:

* https://www.cisecurity.org/insights/blog/ctas-leveraging-fake-browser-updates-in-malware-campaigns
* https://www.cybereason.com/blog/threat-analysis-report-socgholish-and-zloader-from-fake-updates-and-installers-to-owning-your-systems
* https://www.esentire.com/blog/socgholish-sets-sights-on-victim-peers
* https://www.gdatasoftware.com/blog/2024/07/37976-socgholish-fake-update
* https://www.proofpoint.com/us/blog/threat-insight/are-you-sure-your-browser-date-current-landscape-fake-browser-updates
* https://www.proofpoint.com/us/blog/threat-insight/ta569-socgholish-and-beyond

## Literature

The following _articles_ explain our unique predictive cyber threat intelligence:

* [VulDB Cyber Threat Intelligence Documentation](https://vuldb.com/?kb.cti)
* [Cyber Threat Intelligence - Early Anticipation of Attacks](https://www.scip.ch/en/?labs.20201022)

## License

(c) [1997-2024](https://vuldb.com/?kb.changelog) by [vuldb.com](https://vuldb.com/?kb.about). All data on this page is shared under the license [CC BY-NC-SA 4.0](https://creativecommons.org/licenses/by-nc-sa/4.0/). Questions? Check the [FAQ](https://vuldb.com/?kb.faq), read the [documentation](https://vuldb.com/?kb) or [contact us](https://vuldb.com/?contact)!
