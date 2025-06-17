# MATA - Cyber Threat Intelligence

These _indicators_ were reported, collected, and generated during the [VulDB CTI analysis](https://vuldb.com/?kb.cti) of the actor known as [MATA](https://vuldb.com/?actor.mata). The _activity monitoring_ correlates data from social media, forums, chat rooms, and darknet markets. It helps to determine associated actors, specific activities, expected intentions, emerging research, and ongoing attacks. Our unique _predictive model_ uses _big data_ to forecast activities and their characteristics.

_Live data_ and more _analysis capabilities_ are available at [https://vuldb.com/?actor.mata](https://vuldb.com/?actor.mata)

## Countries

These _countries_ are directly (e.g. origin of attacks) or indirectly (e.g. access by proxy) associated with MATA:

* [LA](https://vuldb.com/?country.la)
* [US](https://vuldb.com/?country.us)
* [CN](https://vuldb.com/?country.cn)
* ...

There are 10 more country items available. Please use our online service to access the data.

## IOC - Indicator of Compromise

These _indicators of compromise_ (IOC) indicate associated network resources which are known to be part of research and attack activities of MATA.

ID | IP address | Hostname | Campaign | Confidence
-- | ---------- | -------- | -------- | ----------
1 | [2.4.17.15](https://vuldb.com/?ip.2.4.17.15) | lfbn-mon-1-592-15.w2-4.abo.wanadoo.fr | - | High
2 | [23.227.199.53](https://vuldb.com/?ip.23.227.199.53) | 23-227-199-53.static.hvvc.us | - | High
3 | [23.227.199.69](https://vuldb.com/?ip.23.227.199.69) | 23-227-199-69.static.hvvc.us | - | High
4 | [23.254.119.12](https://vuldb.com/?ip.23.254.119.12) | - | - | High
5 | [37.120.222.191](https://vuldb.com/?ip.37.120.222.191) | - | - | High
6 | ... | ... | ... | ...

There are 18 more IOC items available. Please use our online service to access the data.

## TTP - Tactics, Techniques, Procedures

_Tactics, techniques, and procedures_ (TTP) summarize the suspected MITRE ATT&CK techniques used by _MATA_. This data is unique as it uses our predictive model for actor profiling.

ID | Technique | Weakness | Description | Confidence
-- | --------- | -------- | ----------- | ----------
1 | T1006 | CWE-21, CWE-22, CWE-24, CWE-425 | Path Traversal | High
2 | T1055 | CWE-74 | Improper Neutralization of Data within XPath Expressions | High
3 | T1059 | CWE-88, CWE-94, CWE-1321 | Argument Injection | High
4 | T1059.007 | CWE-79, CWE-80 | Basic Cross Site Scripting | High
5 | ... | ... | ... | ...

There are 17 more TTP items available. Please use our online service to access the data.

## IOA - Indicator of Attack

These _indicators of attack_ (IOA) list the potential fragments used for technical activities like reconnaissance, exploitation, privilege escalation, and exfiltration by MATA. This data is unique as it uses our predictive model for actor profiling.

ID | Type | Indicator | Confidence
-- | ---- | --------- | ----------
1 | File | `.procmailrc` | Medium
2 | File | `/admin/dl_sendmail.php` | High
3 | File | `/admin/file_manager/export` | High
4 | File | `/admin/index2.html` | High
5 | File | `/adminPage/conf/reload` | High
6 | File | `/admin_topic.php?action=delall` | High
7 | File | `/api/baskets/{name}` | High
8 | File | `/api/cron/settings/setJob/` | High
9 | File | `/api/v2/cli/commands` | High
10 | File | `/api2/html/` | Medium
11 | File | `/auth_files/photo/` | High
12 | File | `/bitrix/admin/ldap_server_edit.php` | High
13 | File | `/cgi-bin/cstecgi.cgi` | High
14 | File | `/cgi-bin/koha/catalogue/search.pl` | High
15 | File | `/curd/index/delfile` | High
16 | File | `/Device/Device/GetDeviceInfoList?deviceCode=&searchField=&deviceState=` | High
17 | File | `/DXR.axd` | Medium
18 | File | `/forum/away.php` | High
19 | File | `/h/rest` | Low
20 | File | `/HNAP1/` | Low
21 | File | `/index/ajax/lang` | High
22 | File | `/log/decodmail.php` | High
23 | File | `/login.php?m=admin&c=Field&a=channel_edit` | High
24 | File | `/log_proxy` | Medium
25 | File | `/mailcleaner.php/getStats` | High
26 | File | `/mfsNotice/page` | High
27 | File | `/mgmt/tm/util/bash` | High
28 | File | `/novel/bookSetting/list` | High
29 | File | `/novel/userFeedback/list` | High
30 | ... | ... | ...

There are 253 more IOA items available (file, library, argument, input value, pattern, network port). Please use our online service to access the data.

## References

The following list contains _external sources_ which discuss the actor and the associated activities:

* https://github.com/blackorbird/APT_REPORT/blob/master/lazarus/MATA/Updated-MATA-attacks-Eastern-Europe_full-report_ENG.pdf
* https://securelist.com/mata-multi-platform-targeted-malware-framework/97746/

## Literature

The following _articles_ explain our unique predictive cyber threat intelligence:

* [VulDB Cyber Threat Intelligence Documentation](https://vuldb.com/?kb.cti)
* [Cyber Threat Intelligence - Early Anticipation of Attacks](https://www.scip.ch/en/?labs.20201022)

## License

(c) [1997-2025](https://vuldb.com/?kb.changelog) by [vuldb.com](https://vuldb.com/?kb.about). All data on this page is shared under the license [CC BY-NC-SA 4.0](https://creativecommons.org/licenses/by-nc-sa/4.0/). Questions? Check the [FAQ](https://vuldb.com/?kb.faq), read the [documentation](https://vuldb.com/?kb) or [contact us](https://vuldb.com/?contact)!
