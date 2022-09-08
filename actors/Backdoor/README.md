# Backdoor - Cyber Threat Intelligence

These _indicators_ were reported, collected, and generated during the [VulDB CTI analysis](https://vuldb.com/?kb.cti) of the actor known as [Backdoor](https://vuldb.com/?actor.backdoor). The _activity monitoring_ correlates data from social media, forums, chat rooms, and darknet markets. It helps to determine associated actors, specific activities, expected intentions, emerging research, and ongoing attacks. Our unique _predictive model_ uses _big data_ to forecast activities and their characteristics.

_Live data_ and more _analysis capabilities_ are available at [https://vuldb.com/?actor.backdoor](https://vuldb.com/?actor.backdoor)

## Countries

These _countries_ are directly (e.g. origin of attacks) or indirectly (e.g. access by proxy) associated with Backdoor:

* [US](https://vuldb.com/?country.us)
* [CN](https://vuldb.com/?country.cn)
* [FR](https://vuldb.com/?country.fr)
* ...

There are 15 more country items available. Please use our online service to access the data.

## IOC - Indicator of Compromise

These _indicators of compromise_ (IOC) indicate associated network resources which are known to be part of research and attack activities of Backdoor.

ID | IP address | Hostname | Campaign | Confidence
-- | ---------- | -------- | -------- | ----------
1 | [5.135.230.136](https://vuldb.com/?ip.5.135.230.136) | - | - | High
2 | [23.19.58.114](https://vuldb.com/?ip.23.19.58.114) | - | - | High
3 | [45.11.181.37](https://vuldb.com/?ip.45.11.181.37) | - | - | High
4 | [80.85.155.80](https://vuldb.com/?ip.80.85.155.80) | svr4.pcloud.ru.g.kwwwy.com | - | High
5 | ... | ... | ... | ...

There are 14 more IOC items available. Please use our online service to access the data.

## TTP - Tactics, Techniques, Procedures

_Tactics, techniques, and procedures_ (TTP) summarize the suspected MITRE ATT&CK techniques used by _Backdoor_. This data is unique as it uses our predictive model for actor profiling.

ID | Technique | Weakness | Description | Confidence
-- | --------- | -------- | ----------- | ----------
1 | T1006 | CWE-21, CWE-22, CWE-23 | Pathname Traversal | High
2 | T1040 | CWE-294 | Authentication Bypass by Capture-replay | High
3 | T1055 | CWE-74 | Injection | High
4 | T1059 | CWE-88, CWE-94 | Cross Site Scripting | High
5 | T1059.007 | CWE-79, CWE-80 | Cross Site Scripting | High
6 | ... | ... | ... | ...

There are 18 more TTP items available. Please use our online service to access the data.

## IOA - Indicator of Attack

These _indicators of attack_ (IOA) list the potential fragments used for technical activities like reconnaissance, exploitation, privilege escalation, and exfiltration by Backdoor. This data is unique as it uses our predictive model for actor profiling.

ID | Type | Indicator | Confidence
-- | ---- | --------- | ----------
1 | File | `/admin/access` | High
2 | File | `/admin/index.html` | High
3 | File | `/admin/index.php?id=themes&action=edit_template&filename=blog` | High
4 | File | `/admin/posts.php` | High
5 | File | `/ci_ssms/index.php/orders/create` | High
6 | File | `/download` | Medium
7 | File | `/etc/shadow` | Medium
8 | File | `/fw.login.php` | High
9 | File | `/inc/extensions.php` | High
10 | File | `/index.php` | Medium
11 | File | `/membres/modif_profil.php` | High
12 | File | `/mgmt/tm/util/bash` | High
13 | File | `/nova/bin/console` | High
14 | File | `/ordering/admin/category/index.php?view=edit` | High
15 | File | `/out.php` | Medium
16 | File | `/pms/index.php` | High
17 | File | `/pms/update_user.php?user_id=1` | High
18 | File | `/req_password_user.php` | High
19 | File | `/secure/QueryComponent!Default.jspa` | High
20 | File | `/server-status` | High
21 | File | `/SimpleBusTicket/index.php` | High
22 | File | `/tmp` | Low
23 | File | `/uncpath/` | Medium
24 | File | `/updown/upload.cgi` | High
25 | File | `/usr/bin/pkexec` | High
26 | File | `/usr/syno/etc/mount.conf` | High
27 | File | `/WEB-INF/web.xml` | High
28 | File | `/wp-admin/admin-ajax.php` | High
29 | File | `/wp-json` | Medium
30 | File | `14all.cgi/14all-1.1.cgi/traffic.cgi/mrtg.cgi` | High
31 | File | `addpost_newpoll.php` | High
32 | File | `adm-index.php` | High
33 | File | `Admin.PHP` | Medium
34 | File | `admin.php` | Medium
35 | File | `admin/content.php` | High
36 | File | `admin/index.php` | High
37 | File | `admin/ops/reports/ops/forum.php` | High
38 | File | `admincp/attachment.php` | High
39 | File | `adminedit.pl` | Medium
40 | File | `administration/comments.php` | High
41 | File | `ajax/api/hook/getHookList` | High
42 | File | `archive/index.php` | High
43 | File | `auth-gss2.c` | Medium
44 | File | `backend/groups/index.php` | High
45 | File | `bbs/member_confirm.php` | High
46 | File | `bottom.php` | Medium
47 | File | `breadcrumbs_create.php` | High
48 | File | `C:\Program Files\FileZilla FTP Client\uninstall.exe` | High
49 | File | `cds-fpdf.php` | Medium
50 | File | `cgi-bin/zysh-cgi` | High
51 | ... | ... | ...

There are 446 more IOA items available (file, library, argument, input value, pattern, network port). Please use our online service to access the data.

## References

The following list contains _external sources_ which discuss the actor and the associated activities:

* https://community.blueliv.com/#!/s/5fb2b31882df413eaf344afe
* https://community.blueliv.com/#!/s/5fbfdbfc82df413eaf344d9b
* https://community.blueliv.com/#!/s/604b97cd82df413eb2353abd
* https://community.blueliv.com/#!/s/608ab9ff82df413eb53560a5
* https://community.blueliv.com/#!/s/6268e54d82df417a00331629
* https://community.blueliv.com/#!/s/6278b6fd82df413eb5359112
* https://community.blueliv.com/#!/s/60537fb882df413eb5355cf3
* https://community.blueliv.com/#!/s/6126488882df413eb5357d9e

## Literature

The following _articles_ explain our unique predictive cyber threat intelligence:

* [VulDB Cyber Threat Intelligence Documentation](https://vuldb.com/?kb.cti)
* [Cyber Threat Intelligence - Early Anticipation of Attacks](https://www.scip.ch/en/?labs.20201022)

## License

(c) [1997-2022](https://vuldb.com/?kb.changelog) by [vuldb.com](https://vuldb.com/?kb.about). All data on this page is shared under the license [CC BY-NC-SA 4.0](https://creativecommons.org/licenses/by-nc-sa/4.0/). Questions? Check the [FAQ](https://vuldb.com/?kb.faq), read the [documentation](https://vuldb.com/?kb) or [contact us](https://vuldb.com/?contact)!
