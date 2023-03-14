# Black KingDom - Cyber Threat Intelligence

These _indicators_ were reported, collected, and generated during the [VulDB CTI analysis](https://vuldb.com/?kb.cti) of the actor known as [Black KingDom](https://vuldb.com/?actor.black_kingdom). The _activity monitoring_ correlates data from social media, forums, chat rooms, and darknet markets. It helps to determine associated actors, specific activities, expected intentions, emerging research, and ongoing attacks. Our unique _predictive model_ uses _big data_ to forecast activities and their characteristics.

_Live data_ and more _analysis capabilities_ are available at [https://vuldb.com/?actor.black_kingdom](https://vuldb.com/?actor.black_kingdom)

## Countries

These _countries_ are directly (e.g. origin of attacks) or indirectly (e.g. access by proxy) associated with Black KingDom:

* [US](https://vuldb.com/?country.us)
* [IR](https://vuldb.com/?country.ir)

## IOC - Indicator of Compromise

These _indicators of compromise_ (IOC) indicate associated network resources which are known to be part of research and attack activities of Black KingDom.

ID | IP address | Hostname | Campaign | Confidence
-- | ---------- | -------- | -------- | ----------
1 | [104.21.89.10](https://vuldb.com/?ip.104.21.89.10) | - | - | High
2 | [172.64.80.0](https://vuldb.com/?ip.172.64.80.0) | - | - | High
3 | [185.220.101.204](https://vuldb.com/?ip.185.220.101.204) | tor-exit-204.relayon.org | - | High
4 | ... | ... | ... | ...

There are 1 more IOC items available. Please use our online service to access the data.

## TTP - Tactics, Techniques, Procedures

_Tactics, techniques, and procedures_ (TTP) summarize the suspected MITRE ATT&CK techniques used by _Black KingDom_. This data is unique as it uses our predictive model for actor profiling.

ID | Technique | Weakness | Description | Confidence
-- | --------- | -------- | ----------- | ----------
1 | T1006 | CWE-21, CWE-22 | Pathname Traversal | High
2 | T1040 | CWE-319 | Authentication Bypass by Capture-replay | High
3 | T1055 | CWE-74 | Injection | High
4 | T1059 | CWE-94, CWE-1321 | Cross Site Scripting | High
5 | T1059.007 | CWE-79, CWE-80 | Cross Site Scripting | High
6 | ... | ... | ... | ...

There are 22 more TTP items available. Please use our online service to access the data.

## IOA - Indicator of Attack

These _indicators of attack_ (IOA) list the potential fragments used for technical activities like reconnaissance, exploitation, privilege escalation, and exfiltration by Black KingDom. This data is unique as it uses our predictive model for actor profiling.

ID | Type | Indicator | Confidence
-- | ---- | --------- | ----------
1 | File | `.authlie` | Medium
2 | File | `/admin/ajax.php?action=delete_user` | High
3 | File | `/admin/ajax.php?action=delete_window` | High
4 | File | `/admin/ajax.php?action=save_queue` | High
5 | File | `/admin/article_category.php` | High
6 | File | `/admin/manage_user.php` | High
7 | File | `/apply.cgi` | Medium
8 | File | `/bsms_ci/index.php/book` | High
9 | File | `/classes/Master.php?f=delete_brand` | High
10 | File | `/classes/Master.php?f=delete_category` | High
11 | File | `/config/api/v1/reboot` | High
12 | File | `/etc/shadow` | Medium
13 | File | `/forums.php?action=post` | High
14 | File | `/goform/WifiBasicSet` | High
15 | File | `/hss/admin/?page=client/manage_client` | High
16 | File | `/index.php` | Medium
17 | File | `/inxedu/demo_inxedu_open/src/main/resources/mybatis/inxedu/website/WebsiteImagesMapper.xml` | High
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
28 | File | `/uncpath/` | Medium
29 | File | `/usr/etc/restore0.9` | High
30 | ... | ... | ...

There are 251 more IOA items available (file, library, argument, input value, pattern, network port). Please use our online service to access the data.

## References

The following list contains _external sources_ which discuss the actor and the associated activities:

* https://github.com/sophoslabs/IoCs/blob/master/Ransomware_BlackKingDom.csv

## Literature

The following _articles_ explain our unique predictive cyber threat intelligence:

* [VulDB Cyber Threat Intelligence Documentation](https://vuldb.com/?kb.cti)
* [Cyber Threat Intelligence - Early Anticipation of Attacks](https://www.scip.ch/en/?labs.20201022)

## License

(c) [1997-2023](https://vuldb.com/?kb.changelog) by [vuldb.com](https://vuldb.com/?kb.about). All data on this page is shared under the license [CC BY-NC-SA 4.0](https://creativecommons.org/licenses/by-nc-sa/4.0/). Questions? Check the [FAQ](https://vuldb.com/?kb.faq), read the [documentation](https://vuldb.com/?kb) or [contact us](https://vuldb.com/?contact)!
