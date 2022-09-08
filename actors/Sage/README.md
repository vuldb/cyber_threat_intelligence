# Sage - Cyber Threat Intelligence

These _indicators_ were reported, collected, and generated during the [VulDB CTI analysis](https://vuldb.com/?kb.cti) of the actor known as [Sage](https://vuldb.com/?actor.sage). The _activity monitoring_ correlates data from social media, forums, chat rooms, and darknet markets. It helps to determine associated actors, specific activities, expected intentions, emerging research, and ongoing attacks. Our unique _predictive model_ uses _big data_ to forecast activities and their characteristics.

_Live data_ and more _analysis capabilities_ are available at [https://vuldb.com/?actor.sage](https://vuldb.com/?actor.sage)

## IOC - Indicator of Compromise

These _indicators of compromise_ (IOC) indicate associated network resources which are known to be part of research and attack activities of Sage.

ID | IP address | Hostname | Campaign | Confidence
-- | ---------- | -------- | -------- | ----------
1 | [5.45.6.138](https://vuldb.com/?ip.5.45.6.138) | 138-006-045-005.ip-addr.inexio.net | - | High
2 | [5.45.17.36](https://vuldb.com/?ip.5.45.17.36) | - | - | High
3 | [5.45.24.236](https://vuldb.com/?ip.5.45.24.236) | - | - | High
4 | [5.45.100.133](https://vuldb.com/?ip.5.45.100.133) | domain-butler.com | - | High
5 | [5.45.107.161](https://vuldb.com/?ip.5.45.107.161) | nobody.yourvserver.net | - | High
6 | [5.45.107.167](https://vuldb.com/?ip.5.45.107.167) | v22014011960816232.yourvserver.net | - | High
7 | [5.45.129.52](https://vuldb.com/?ip.5.45.129.52) | - | - | High
8 | [5.45.140.6](https://vuldb.com/?ip.5.45.140.6) | - | - | High
9 | [5.45.159.19](https://vuldb.com/?ip.5.45.159.19) | - | - | High
10 | [5.45.208.36](https://vuldb.com/?ip.5.45.208.36) | proxy-minsk03.cdn.yandex.net | - | High
11 | ... | ... | ... | ...

There are 40 more IOC items available. Please use our online service to access the data.

## TTP - Tactics, Techniques, Procedures

_Tactics, techniques, and procedures_ (TTP) summarize the suspected MITRE ATT&CK techniques used by _Sage_. This data is unique as it uses our predictive model for actor profiling.

ID | Technique | Weakness | Description | Confidence
-- | --------- | -------- | ----------- | ----------
1 | T1006 | CWE-22 | Pathname Traversal | High
2 | T1059 | CWE-94, CWE-1321 | Cross Site Scripting | High
3 | T1059.007 | CWE-79, CWE-80 | Cross Site Scripting | High
4 | ... | ... | ... | ...

There are 8 more TTP items available. Please use our online service to access the data.

## IOA - Indicator of Attack

These _indicators of attack_ (IOA) list the potential fragments used for technical activities like reconnaissance, exploitation, privilege escalation, and exfiltration by Sage. This data is unique as it uses our predictive model for actor profiling.

ID | Type | Indicator | Confidence
-- | ---- | --------- | ----------
1 | File | `/admin/curltest.cgi` | High
2 | File | `/admin/vca/license/license_tok.cgi` | High
3 | File | `/api/storage/upload/PostImage` | High
4 | File | `/cgi-bin/mesh.cgi?page=upgrade` | High
5 | File | `/cgi-bin/nightled.cgi` | High
6 | File | `/cns/` | Low
7 | File | `/doping.asp` | Medium
8 | File | `/dotrace.asp` | Medium
9 | File | `/etc_ro/lighttpd/www/cgi-bin/ExportAllSettings.sh` | High
10 | File | `/frm/` | Low
11 | File | `/goform/aspForm` | High
12 | File | `/set_safety.shtml?r=52300` | High
13 | File | `/sql/` | Low
14 | File | `account_footer.php` | High
15 | File | `admin.php` | Medium
16 | File | `admin/editListing.php` | High
17 | File | `admin/header.php` | High
18 | File | `admin/membersearch.php` | High
19 | File | `admin/notices/perso.inc.php` | High
20 | File | `admin/plugin_manager.php` | High
21 | File | `admin/ServiceConfiguration.do` | High
22 | File | `admin_footer.php` | High
23 | File | `Albmgr.PHP` | Medium
24 | File | `albmgr.php` | Medium
25 | File | `autherror.cfm` | High
26 | File | `banners.php` | Medium
27 | File | `Base/Application.php` | High
28 | File | `begin.inc.php` | High
29 | File | `blog/include/common/comfinish.cfm` | High
30 | File | `browsecat.php` | High
31 | File | `browseSubCat.php` | High
32 | File | `browse_footer.php` | High
33 | File | `chat.php` | Medium
34 | File | `classRoom.php` | High
35 | File | `clp` | Low
36 | File | `cluster.php` | Medium
37 | File | `CodeWidgets.com` | High
38 | File | `comm.c` | Low
39 | File | `common.inc.php` | High
40 | File | `compose.php` | Medium
41 | File | `CONFIG/errmsg.inc.php` | High
42 | File | `connect/server` | High
43 | File | `connections.c` | High
44 | File | `contact/contact/index.php` | High
45 | File | `contactsList.asp` | High
46 | File | `core/support/_load.php` | High
47 | File | `cp.php` | Low
48 | File | `CVSROOT/passwd` | High
49 | File | `db_ecard.php` | Medium
50 | File | `development.php` | High
51 | File | `download.php` | Medium
52 | ... | ... | ...

There are 454 more IOA items available (file, library, argument, input value, pattern, network port). Please use our online service to access the data.

## References

The following list contains _external sources_ which discuss the actor and the associated activities:

* https://blog.talosintelligence.com/2019/06/threat-roundup-0531-0607.html
* https://blog.talosintelligence.com/2019/09/threat-roundup-0830-0906.html

## Literature

The following _articles_ explain our unique predictive cyber threat intelligence:

* [VulDB Cyber Threat Intelligence Documentation](https://vuldb.com/?kb.cti)
* [Cyber Threat Intelligence - Early Anticipation of Attacks](https://www.scip.ch/en/?labs.20201022)

## License

(c) [1997-2022](https://vuldb.com/?kb.changelog) by [vuldb.com](https://vuldb.com/?kb.about). All data on this page is shared under the license [CC BY-NC-SA 4.0](https://creativecommons.org/licenses/by-nc-sa/4.0/). Questions? Check the [FAQ](https://vuldb.com/?kb.faq), read the [documentation](https://vuldb.com/?kb) or [contact us](https://vuldb.com/?contact)!
