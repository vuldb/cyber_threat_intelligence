# Microcin - Cyber Threat Intelligence

These _indicators_ were reported, collected, and generated during the [VulDB CTI analysis](https://vuldb.com/?kb.cti) of the actor known as [Microcin](https://vuldb.com/?actor.microcin). The _activity monitoring_ correlates data from social media, forums, chat rooms, and darknet markets. It helps to determine associated actors, specific activities, expected intentions, emerging research, and ongoing attacks. Our unique _predictive model_ uses _big data_ to forecast activities and their characteristics.

_Live data_ and more _analysis capabilities_ are available at [https://vuldb.com/?actor.microcin](https://vuldb.com/?actor.microcin)

## Countries

These _countries_ are directly (e.g. origin of attacks) or indirectly (e.g. access by proxy) associated with Microcin:

* [US](https://vuldb.com/?country.us)
* [CN](https://vuldb.com/?country.cn)
* [RU](https://vuldb.com/?country.ru)
* ...

There are 25 more country items available. Please use our online service to access the data.

## IOC - Indicator of Compromise

These _indicators of compromise_ (IOC) indicate associated network resources which are known to be part of research and attack activities of Microcin.

ID | IP address | Hostname | Campaign | Confidence
-- | ---------- | -------- | -------- | ----------
1 | [2.4.17.15](https://vuldb.com/?ip.2.4.17.15) | lfbn-mon-1-592-15.w2-4.abo.wanadoo.fr | - | High
2 | [23.152.0.225](https://vuldb.com/?ip.23.152.0.225) | nordns.crowncloud.net | - | High
3 | [95.179.136.10](https://vuldb.com/?ip.95.179.136.10) | 95.179.136.10.vultrusercontent.com | - | High
4 | ... | ... | ... | ...

There are 1 more IOC items available. Please use our online service to access the data.

## TTP - Tactics, Techniques, Procedures

_Tactics, techniques, and procedures_ (TTP) summarize the suspected MITRE ATT&CK techniques used by _Microcin_. This data is unique as it uses our predictive model for actor profiling.

ID | Technique | Weakness | Description | Confidence
-- | --------- | -------- | ----------- | ----------
1 | T1006 | CWE-21, CWE-22, CWE-23, CWE-24 | Pathname Traversal | High
2 | T1040 | CWE-319 | Authentication Bypass by Capture-replay | High
3 | T1055 | CWE-74 | Injection | High
4 | T1059 | CWE-88, CWE-94, CWE-1321 | Cross Site Scripting | High
5 | T1059.007 | CWE-79, CWE-80 | Cross Site Scripting | High
6 | T1068 | CWE-250, CWE-264, CWE-266, CWE-269, CWE-284 | J2EE Misconfiguration: Weak Access Permissions for EJB Methods | High
7 | ... | ... | ... | ...

There are 22 more TTP items available. Please use our online service to access the data.

## IOA - Indicator of Attack

These _indicators of attack_ (IOA) list the potential fragments used for technical activities like reconnaissance, exploitation, privilege escalation, and exfiltration by Microcin. This data is unique as it uses our predictive model for actor profiling.

ID | Type | Indicator | Confidence
-- | ---- | --------- | ----------
1 | File | `/+CSCOE+/logon.html` | High
2 | File | `/ajax.php?action=read_msg` | High
3 | File | `/ajax/networking/get_netcfg.php` | High
4 | File | `/api/gen/clients/{language}` | High
5 | File | `/app/options.py` | High
6 | File | `/bin/httpd` | Medium
7 | File | `/cgi-bin/wapopen` | High
8 | File | `/ci_spms/admin/category` | High
9 | File | `/ci_spms/admin/search/searching/` | High
10 | File | `/classes/Master.php?f=delete_appointment` | High
11 | File | `/classes/Master.php?f=delete_train` | High
12 | File | `/cms/print.php` | High
13 | File | `/concat?/%2557EB-INF/web.xml` | High
14 | File | `/Content/Template/root/reverse-shell.aspx` | High
15 | File | `/ctcprotocol/Protocol` | High
16 | File | `/dashboard/menu-list.php` | High
17 | File | `/data/remove` | Medium
18 | File | `/ebics-server/ebics.aspx` | High
19 | File | `/ffos/classes/Master.php?f=save_category` | High
20 | File | `/forum/away.php` | High
21 | File | `/goforms/rlminfo` | High
22 | File | `/HNAP1` | Low
23 | File | `/HNAP1/SetClientInfo` | High
24 | File | `/Items/*/RemoteImages/Download` | High
25 | File | `/login/index.php` | High
26 | File | `/menu.html` | Medium
27 | File | `/modules/profile/index.php` | High
28 | File | `/navigate/navigate_download.php` | High
29 | File | `/ocwbs/admin/?page=user/manage_user` | High
30 | File | `/ofrs/admin/?page=user/manage_user` | High
31 | File | `/out.php` | Medium
32 | File | `/password.html` | High
33 | File | `/php_action/fetchSelectedUser.php` | High
34 | File | `/proc/ioports` | High
35 | File | `/property-list/property_view.php` | High
36 | File | `/ptms/classes/Users.php` | High
37 | File | `/resources//../` | High
38 | File | `/rest/api/2/search` | High
39 | File | `/s/` | Low
40 | File | `/scripts/cpan_config` | High
41 | File | `/secure/admin/InsightDefaultCustomFieldConfig.jspa` | High
42 | File | `/spip.php` | Medium
43 | File | `/squashfs-root/www/HNAP1/control/SetMasterWLanSettings.php` | High
44 | ... | ... | ...

There are 379 more IOA items available (file, library, argument, input value, pattern, network port). Please use our online service to access the data.

## References

The following list contains _external sources_ which discuss the actor and the associated activities:

* https://securelist.com/microcin-is-here/97353/

## Literature

The following _articles_ explain our unique predictive cyber threat intelligence:

* [VulDB Cyber Threat Intelligence Documentation](https://vuldb.com/?kb.cti)
* [Cyber Threat Intelligence - Early Anticipation of Attacks](https://www.scip.ch/en/?labs.20201022)

## License

(c) [1997-2023](https://vuldb.com/?kb.changelog) by [vuldb.com](https://vuldb.com/?kb.about). All data on this page is shared under the license [CC BY-NC-SA 4.0](https://creativecommons.org/licenses/by-nc-sa/4.0/). Questions? Check the [FAQ](https://vuldb.com/?kb.faq), read the [documentation](https://vuldb.com/?kb) or [contact us](https://vuldb.com/?contact)!
