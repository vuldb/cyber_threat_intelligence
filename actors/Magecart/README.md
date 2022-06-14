# Magecart - Cyber Threat Intelligence

These _indicators_ were reported, collected, and generated during the [VulDB CTI analysis](https://vuldb.com/?kb.cti) of the actor known as [Magecart](https://vuldb.com/?actor.magecart). The _activity monitoring_ correlates data from social media, forums, chat rooms, and darknet markets. It helps to determine associated actors, specific activities, expected intentions, emerging research, and ongoing attacks. Our unique _predictive model_ uses _big data_ to forecast activities and their characteristics.

_Live data_ and more _analysis capabilities_ are available at [https://vuldb.com/?actor.magecart](https://vuldb.com/?actor.magecart)

## Countries

These _countries_ are directly (e.g. origin of attacks) or indirectly (e.g. access by proxy) associated with Magecart:

* [ES](https://vuldb.com/?country.es)
* [PL](https://vuldb.com/?country.pl)
* [IT](https://vuldb.com/?country.it)
* ...

There are 9 more country items available. Please use our online service to access the data.

## IOC - Indicator of Compromise

These _indicators of compromise_ (IOC) indicate associated network resources which are known to be part of research and attack activities of Magecart.

ID | IP address | Hostname | Campaign | Confidence
-- | ---------- | -------- | -------- | ----------
1 | [5.135.247.141](https://vuldb.com/?ip.5.135.247.141) | ip141.ip-5-135-247.eu | - | High
2 | [5.135.247.142](https://vuldb.com/?ip.5.135.247.142) | ip142.ip-5-135-247.eu | - | High
3 | [5.188.44.32](https://vuldb.com/?ip.5.188.44.32) | - | - | High
4 | [8.209.70.103](https://vuldb.com/?ip.8.209.70.103) | - | - | High
5 | [8.211.0.55](https://vuldb.com/?ip.8.211.0.55) | - | - | High
6 | [8.211.5.139](https://vuldb.com/?ip.8.211.5.139) | - | - | High
7 | [35.246.189.253](https://vuldb.com/?ip.35.246.189.253) | 253.189.246.35.bc.googleusercontent.com | - | Medium
8 | [37.59.47.208](https://vuldb.com/?ip.37.59.47.208) | ns3000975.ip-37-59-47.eu | - | High
9 | ... | ... | ... | ...

There are 33 more IOC items available. Please use our online service to access the data.

## TTP - Tactics, Techniques, Procedures

_Tactics, techniques, and procedures_ (TTP) summarize the suspected MITRE ATT&CK techniques used by _Magecart_. This data is unique as it uses our predictive model for actor profiling.

ID | Technique | Weakness | Description | Confidence
-- | --------- | -------- | ----------- | ----------
1 | T1059.007 | CWE-79, CWE-80 | Cross Site Scripting | High
2 | T1068 | CWE-250, CWE-264, CWE-266, CWE-284 | Execution with Unnecessary Privileges | High
3 | T1110.001 | CWE-798 | Improper Restriction of Excessive Authentication Attempts | High
4 | ... | ... | ... | ...

There are 6 more TTP items available. Please use our online service to access the data.

## IOA - Indicator of Attack

These _indicators of attack_ (IOA) list the potential fragments used for technical activities like reconnaissance, exploitation, privilege escalation, and exfiltration by Magecart. This data is unique as it uses our predictive model for actor profiling.

ID | Type | Indicator | Confidence
-- | ---- | --------- | ----------
1 | File | `../FILEDIR` | Medium
2 | File | `//proc/kcore` | Medium
3 | File | `/acms/admin/?page=transactions/manage_transaction` | High
4 | File | `/admin.php/pic/admin/type/del` | High
5 | File | `/admin.php/vod/admin/topic/del` | High
6 | File | `/admin.php?p=/User/index` | High
7 | File | `/admin/users.php?source=edit_user&id=1` | High
8 | File | `/admin/weixin.php` | High
9 | File | `/Ap4RtpAtom.cpp` | High
10 | File | `/apps/acs-commons/content/page-compare.html` | High
11 | File | `/assets/partials/_handleLogin.php` | High
12 | File | `/bcms/admin/?page=user/list` | High
13 | File | `/bcms/admin/?page=user/manage_user` | High
14 | File | `/bcms/admin/services/view_service.php` | High
15 | File | `/cardo/api` | Medium
16 | File | `/cgi-bin/editBookmark` | High
17 | File | `/cms/classes/Master.php?f=delete_designation` | High
18 | File | `/debug/pprof` | Medium
19 | File | `/ecrire` | Low
20 | File | `/eris/admin/applicants/index.php?view=view` | High
21 | File | `/etc/cron.daily/upstart` | High
22 | File | `/fuel/index.php/fuel/logs/items` | High
23 | File | `/fuel/sitevariables/delete/4` | High
24 | File | `/goform/aspForm` | High
25 | File | `/goform/setpptpservercfg` | High
26 | File | `/help/treecontent.jsp` | High
27 | File | `/insurance/editNominee.php` | High
28 | File | `/lists/admin/` | High
29 | File | `/mgmt/tm/util/bash` | High
30 | File | `/my/unicorn/uc.c` | High
31 | File | `/ordering/admin/category/index.php?view=edit` | High
32 | File | `/ordering/admin/stockin/index.php?view=edit` | High
33 | File | `/p1/p2/:name` | Medium
34 | File | `/php/ajax.php` | High
35 | ... | ... | ...

There are 298 more IOA items available (file, library, argument, input value, pattern, network port). Please use our online service to access the data.

## References

The following list contains _external sources_ which discuss the actor and the associated activities:

* https://blog.bushidotoken.net/2020/08/analysis-of-recent-magecart-campaign.html
* https://blog.bushidotoken.net/2020/12/analysis-of-meyhod-javascript-web.html
* https://blog.bushidotoken.net/2021/04/mo-money-mo-magecart.html
* https://blog.malwarebytes.com/threat-intelligence/2021/09/the-many-tentacles-of-magecart-group-8/
* https://github.com/blackorbird/APT_REPORT/tree/master/Magecart

## Literature

The following _articles_ explain our unique predictive cyber threat intelligence:

* [VulDB Cyber Threat Intelligence Documentation](https://vuldb.com/?kb.cti)
* [Cyber Threat Intelligence - Early Anticipation of Attacks](https://www.scip.ch/en/?labs.20201022)

## License

(c) [1997-2022](https://vuldb.com/?kb.changelog) by [vuldb.com](https://vuldb.com/?kb.about). All data on this page is shared under the license [CC BY-NC-SA 4.0](https://creativecommons.org/licenses/by-nc-sa/4.0/). Questions? Check the [FAQ](https://vuldb.com/?kb.faq), read the [documentation](https://vuldb.com/?kb) or [contact us](https://vuldb.com/?contact)!
