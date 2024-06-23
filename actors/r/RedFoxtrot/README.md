# RedFoxtrot - Cyber Threat Intelligence

These _indicators_ were reported, collected, and generated during the [VulDB CTI analysis](https://vuldb.com/?kb.cti) of the actor known as [RedFoxtrot](https://vuldb.com/?actor.redfoxtrot). The _activity monitoring_ correlates data from social media, forums, chat rooms, and darknet markets. It helps to determine associated actors, specific activities, expected intentions, emerging research, and ongoing attacks. Our unique _predictive model_ uses _big data_ to forecast activities and their characteristics.

_Live data_ and more _analysis capabilities_ are available at [https://vuldb.com/?actor.redfoxtrot](https://vuldb.com/?actor.redfoxtrot)

## Countries

These _countries_ are directly (e.g. origin of attacks) or indirectly (e.g. access by proxy) associated with RedFoxtrot:

* [CN](https://vuldb.com/?country.cn)
* [US](https://vuldb.com/?country.us)
* [GB](https://vuldb.com/?country.gb)
* ...

There are 6 more country items available. Please use our online service to access the data.

## IOC - Indicator of Compromise

These _indicators of compromise_ (IOC) indicate associated network resources which are known to be part of research and attack activities of RedFoxtrot.

ID | IP address | Hostname | Campaign | Confidence
-- | ---------- | -------- | -------- | ----------
1 | [45.32.22.220](https://vuldb.com/?ip.45.32.22.220) | 45.32.22.220.vultrusercontent.com | - | Medium
2 | [45.32.146.174](https://vuldb.com/?ip.45.32.146.174) | 45.32.146.174.vultrusercontent.com | - | Medium
3 | [45.76.216.62](https://vuldb.com/?ip.45.76.216.62) | 45.76.216.62.vultrusercontent.com | - | Medium
4 | [45.77.178.76](https://vuldb.com/?ip.45.77.178.76) | thematrix.dev | - | High
5 | ... | ... | ... | ...

There are 18 more IOC items available. Please use our online service to access the data.

## TTP - Tactics, Techniques, Procedures

_Tactics, techniques, and procedures_ (TTP) summarize the suspected MITRE ATT&CK techniques used by _RedFoxtrot_. This data is unique as it uses our predictive model for actor profiling.

ID | Technique | Weakness | Description | Confidence
-- | --------- | -------- | ----------- | ----------
1 | T1006 | CWE-21, CWE-22, CWE-24 | Path Traversal | High
2 | T1040 | CWE-294, CWE-319 | Authentication Bypass by Capture-replay | High
3 | T1055 | CWE-74 | Improper Neutralization of Data within XPath Expressions | High
4 | T1059 | CWE-94 | Argument Injection | High
5 | ... | ... | ... | ...

There are 17 more TTP items available. Please use our online service to access the data.

## IOA - Indicator of Attack

These _indicators of attack_ (IOA) list the potential fragments used for technical activities like reconnaissance, exploitation, privilege escalation, and exfiltration by RedFoxtrot. This data is unique as it uses our predictive model for actor profiling.

ID | Type | Indicator | Confidence
-- | ---- | --------- | ----------
1 | File | `/admin/maintenance/view_designation.php` | High
2 | File | `/admin/sys_sql_query.php` | High
3 | File | `/app/Http/Controllers/Admin/NEditorController.php` | High
4 | File | `/cgi-bin/luci/api/wireless` | High
5 | File | `/cgi-bin/vitogate.cgi` | High
6 | File | `/forum/away.php` | High
7 | File | `/getcfg.php` | Medium
8 | File | `/group1/uploa` | High
9 | File | `/importexport.php` | High
10 | File | `/inc/lists/csvexport.php` | High
11 | File | `/server-status` | High
12 | File | `/sgmi/` | Low
13 | File | `/system/user/resetPwd` | High
14 | File | `/tos/index.php?editor/fileGet` | High
15 | File | `/uncpath/` | Medium
16 | File | `/user/updatePwd` | High
17 | File | `/var/log/nginx` | High
18 | File | `addentry.php` | Medium
19 | File | `admin-ajax.php?action=get_wdtable order[0][dir]` | High
20 | File | `admin/plib/api-rpc/Agent.php` | High
21 | File | `applications/core/modules/front/system/content.php` | High
22 | File | `att_protocol.cc` | High
23 | ... | ... | ...

There are 192 more IOA items available (file, library, argument, input value, pattern, network port). Please use our online service to access the data.

## References

The following list contains _external sources_ which discuss the actor and the associated activities:

* https://github.com/blackorbird/APT_REPORT/blob/master/International%20Strategic/China/RedFoxtrot_group.pdf

## Literature

The following _articles_ explain our unique predictive cyber threat intelligence:

* [VulDB Cyber Threat Intelligence Documentation](https://vuldb.com/?kb.cti)
* [Cyber Threat Intelligence - Early Anticipation of Attacks](https://www.scip.ch/en/?labs.20201022)

## License

(c) [1997-2024](https://vuldb.com/?kb.changelog) by [vuldb.com](https://vuldb.com/?kb.about). All data on this page is shared under the license [CC BY-NC-SA 4.0](https://creativecommons.org/licenses/by-nc-sa/4.0/). Questions? Check the [FAQ](https://vuldb.com/?kb.faq), read the [documentation](https://vuldb.com/?kb) or [contact us](https://vuldb.com/?contact)!
