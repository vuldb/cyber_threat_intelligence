# Snake - Cyber Threat Intelligence

These _indicators_ were reported, collected, and generated during the [VulDB CTI analysis](https://vuldb.com/?kb.cti) of the actor known as [Snake](https://vuldb.com/?actor.snake). The _activity monitoring_ correlates data from social media, forums, chat rooms, and darknet markets. It helps to determine associated actors, specific activities, expected intentions, emerging research, and ongoing attacks. Our unique _predictive model_ uses _big data_ to forecast activities and their characteristics.

_Live data_ and more _analysis capabilities_ are available at [https://vuldb.com/?actor.snake](https://vuldb.com/?actor.snake)

## Campaigns

The following _campaigns_ are known and can be associated with Snake:

* Snake

## Countries

These _countries_ are directly (e.g. origin of attacks) or indirectly (e.g. access by proxy) associated with Snake:

* [CH](https://vuldb.com/?country.ch)
* [DE](https://vuldb.com/?country.de)
* [US](https://vuldb.com/?country.us)
* ...

There are 9 more country items available. Please use our online service to access the data.

## IOC - Indicator of Compromise

These _indicators of compromise_ (IOC) indicate associated network resources which are known to be part of research and attack activities of Snake.

ID | IP address | Hostname | Campaign | Confidence
-- | ---------- | -------- | -------- | ----------
1 | [1.254.1.255](https://vuldb.com/?ip.1.254.1.255) | - | - | High
2 | [31.170.161.136](https://vuldb.com/?ip.31.170.161.136) | cpl02.main-hosting.eu | Snake | High
3 | [31.170.164.249](https://vuldb.com/?ip.31.170.164.249) | ns4.hostinger.com | Snake | High
4 | [34.122.197.93](https://vuldb.com/?ip.34.122.197.93) | 93.197.122.34.bc.googleusercontent.com | - | Medium
5 | ... | ... | ... | ...

There are 15 more IOC items available. Please use our online service to access the data.

## TTP - Tactics, Techniques, Procedures

_Tactics, techniques, and procedures_ (TTP) summarize the suspected MITRE ATT&CK techniques used by _Snake_. This data is unique as it uses our predictive model for actor profiling.

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

These _indicators of attack_ (IOA) list the potential fragments used for technical activities like reconnaissance, exploitation, privilege escalation, and exfiltration by Snake. This data is unique as it uses our predictive model for actor profiling.

ID | Type | Indicator | Confidence
-- | ---- | --------- | ----------
1 | File | `.github/workflows/combine-prs.yml` | High
2 | File | `/admin/ajax.php?action=delete_user` | High
3 | File | `/admin/ajax.php?action=delete_window` | High
4 | File | `/admin/ajax.php?action=save_queue` | High
5 | File | `/admin/article_category.php` | High
6 | File | `/admin/manage_user.php` | High
7 | File | `/adminui/history_log.php` | High
8 | File | `/apply.cgi` | Medium
9 | File | `/classes/Master.php?f=delete_brand` | High
10 | File | `/classes/Master.php?f=delete_category` | High
11 | File | `/config/api/v1/reboot` | High
12 | File | `/etc/passwd` | Medium
13 | File | `/goform/WifiBasicSet` | High
14 | File | `/hss/admin/?page=client/manage_client` | High
15 | File | `/login/index.php` | High
16 | File | `/opt/Citrix/ICAClient/util/ctxwebhelper` | High
17 | File | `/output/outdbg.c` | High
18 | File | `/output/outieee.c` | High
19 | File | `/picturesPreview` | High
20 | File | `/setNTP.cgi` | Medium
21 | File | `/system/site.php` | High
22 | File | `/tiki-importer.php` | High
23 | File | `/tmp` | Low
24 | File | `/tpts/manage_user.php` | High
25 | File | `/trufusionPortal/upDwModuleProxy` | High
26 | File | `/var/log/nginx` | High
27 | File | `/wp-admin/options-general.php` | High
28 | File | `/wp-json/wc/v3/webhooks` | High
29 | File | `0_change-gallery.php` | High
30 | File | `addToWishlist.asp` | High
31 | File | `admin/manage_user.php` | High
32 | File | `admin/page-login.php` | High
33 | File | `admin/panels/entry/admin.entry.list.php` | High
34 | File | `admin/panels/uploader/admin.uploader.php` | High
35 | File | `admin/plugin-preferences.php` | High
36 | File | `administrative` | High
37 | File | `admin_class.php` | High
38 | File | `agent/listener/templates/tail.html` | High
39 | File | `announce.php` | Medium
40 | ... | ... | ...

There are 342 more IOA items available (file, library, argument, input value, pattern, network port). Please use our online service to access the data.

## References

The following list contains _external sources_ which discuss the actor and the associated activities:

* https://1275.ru/ioc/246/snake-keylogger-iocs/
* https://community.blueliv.com/#!/s/60db363c82df413ea934d2d0
* https://www.threatminer.org/report.php?q=snake_whitepaper.pdf&y=2014

## Literature

The following _articles_ explain our unique predictive cyber threat intelligence:

* [VulDB Cyber Threat Intelligence Documentation](https://vuldb.com/?kb.cti)
* [Cyber Threat Intelligence - Early Anticipation of Attacks](https://www.scip.ch/en/?labs.20201022)

## License

(c) [1997-2023](https://vuldb.com/?kb.changelog) by [vuldb.com](https://vuldb.com/?kb.about). All data on this page is shared under the license [CC BY-NC-SA 4.0](https://creativecommons.org/licenses/by-nc-sa/4.0/). Questions? Check the [FAQ](https://vuldb.com/?kb.faq), read the [documentation](https://vuldb.com/?kb) or [contact us](https://vuldb.com/?contact)!
