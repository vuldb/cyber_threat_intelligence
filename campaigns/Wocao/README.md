# Wocao - Cyber Threat Intelligence

These _indicators_ were reported, collected, and generated during the [VulDB CTI analysis](https://vuldb.com/?kb.cti) of the campaign known as _Wocao_. The _activity monitoring_ correlates data from social media, forums, chat rooms, and darknet markets. It helps to determine associated actors, specific activities, expected intentions, emerging research, and ongoing attacks. Our unique _predictive model_ uses _big data_ to forecast activities and their characteristics.

_Live data_ and more _analysis capabilities_ are available at [https://vuldb.com/?actor](https://vuldb.com/?actor)

## Countries

These _countries_ are directly (e.g. origin of attacks) or indirectly (e.g. access by proxy) associated with Wocao:

* [DE](https://vuldb.com/?country.de)
* [ES](https://vuldb.com/?country.es)
* [US](https://vuldb.com/?country.us)
* ...

There are 8 more country items available. Please use our online service to access the data.

## Actors

These _actors_ are associated with Wocao or other actors linked to the campaign.

ID | Actor | Confidence
-- | ----- | ----------
1 | [Wocao](https://vuldb.com/?actor.wocao) | High

## IOC - Indicator of Compromise

These _indicators of compromise_ (IOC) indicate associated network resources which are known to be part of research and attack activities of Wocao.

ID | IP address | Hostname | Actor | Confidence
-- | ---------- | -------- | ----- | ----------
1 | [23.254.211.108](https://vuldb.com/?ip.23.254.211.108) | hwsrv-871243.hostwindsdns.com | [Wocao](https://vuldb.com/?actor.wocao) | High
2 | [31.222.185.215](https://vuldb.com/?ip.31.222.185.215) | 31-222-185-215.static.cloud-ips.co.uk | [Wocao](https://vuldb.com/?actor.wocao) | High
3 | [45.77.229.10](https://vuldb.com/?ip.45.77.229.10) | 45.77.229.10.vultr.com | [Wocao](https://vuldb.com/?actor.wocao) | Medium
4 | ... | ... | ... | ...

There are 13 more IOC items available. Please use our online service to access the data.

## TTP - Tactics, Techniques, Procedures

_Tactics, techniques, and procedures_ (TTP) summarize the suspected MITRE ATT&CK techniques used within Wocao. This data is unique as it uses our predictive model for actor profiling.

ID | Technique | Weakness | Description | Confidence
-- | --------- | -------- | ----------- | ----------
1 | T1006 | CWE-21, CWE-22, CWE-24 | Pathname Traversal | High
2 | T1055 | CWE-74 | Injection | High
3 | T1059 | CWE-88, CWE-94, CWE-1321 | Cross Site Scripting | High
4 | T1059.007 | CWE-79, CWE-80 | Cross Site Scripting | High
5 | T1068 | CWE-264, CWE-269, CWE-274, CWE-284 | Execution with Unnecessary Privileges | High
6 | ... | ... | ... | ...

There are 22 more TTP items available. Please use our online service to access the data.

## IOA - Indicator of Attack

These _indicators of attack_ (IOA) list the potential fragments used for technical activities like reconnaissance, exploitation, privilege escalation, and exfiltration during Wocao. This data is unique as it uses our predictive model for actor profiling.

ID | Type | Indicator | Confidence
-- | ---- | --------- | ----------
1 | File | `.github/workflows/combine-prs.yml` | High
2 | File | `/admin/ajax.php?action=delete_user` | High
3 | File | `/admin/ajax.php?action=delete_window` | High
4 | File | `/admin/ajax.php?action=save_queue` | High
5 | File | `/admin/article_category.php` | High
6 | File | `/admin/manage_user.php` | High
7 | File | `/adminui/error_details.php` | High
8 | File | `/adminui/history_log.php` | High
9 | File | `/apply.cgi` | Medium
10 | File | `/classes/Master.php?f=delete_brand` | High
11 | File | `/classes/Master.php?f=delete_category` | High
12 | File | `/config/api/v1/reboot` | High
13 | File | `/etc/passwd` | Medium
14 | File | `/goform/dir_setWanWifi` | High
15 | File | `/goform/WifiBasicSet` | High
16 | File | `/hospital/hms/admin/patient-search.php` | High
17 | File | `/hss/admin/?page=client/manage_client` | High
18 | File | `/login/index.php` | High
19 | File | `/opt/Citrix/ICAClient/util/ctxwebhelper` | High
20 | File | `/output/outdbg.c` | High
21 | File | `/output/outieee.c` | High
22 | File | `/setNTP.cgi` | Medium
23 | File | `/system/site.php` | High
24 | File | `/tiki-importer.php` | High
25 | File | `/tmp` | Low
26 | File | `/tpts/manage_user.php` | High
27 | File | `/trufusionPortal/upDwModuleProxy` | High
28 | File | `/var/log/nginx` | High
29 | File | `/wp-admin/options-general.php` | High
30 | File | `/wp-json/wc/v3/webhooks` | High
31 | File | `0_change-gallery.php` | High
32 | File | `addToWishlist.asp` | High
33 | File | `admin/manage_user.php` | High
34 | File | `admin/page-login.php` | High
35 | ... | ... | ...

There are 304 more IOA items available (file, library, argument, input value, pattern, network port). Please use our online service to access the data.

## References

The following list contains _external sources_ which discuss the campaign and the associated activities:

* https://github.com/fox-it/operation-wocao

## Literature

The following _articles_ explain our unique predictive cyber threat intelligence:

* [VulDB Cyber Threat Intelligence Documentation](https://vuldb.com/?kb.cti)
* [Cyber Threat Intelligence - Early Anticipation of Attacks](https://www.scip.ch/en/?labs.20201022)

## License

(c) [1997-2023](https://vuldb.com/?kb.changelog) by [vuldb.com](https://vuldb.com/?kb.about). All data on this page is shared under the license [CC BY-NC-SA 4.0](https://creativecommons.org/licenses/by-nc-sa/4.0/). Questions? Check the [FAQ](https://vuldb.com/?kb.faq), read the [documentation](https://vuldb.com/?kb) or [contact us](https://vuldb.com/?contact)!
