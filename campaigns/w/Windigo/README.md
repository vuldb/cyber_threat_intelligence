# Windigo - Cyber Threat Intelligence

These _indicators_ were reported, collected, and generated during the [VulDB CTI analysis](https://vuldb.com/?kb.cti) of the campaign known as _Windigo_. The _activity monitoring_ correlates data from social media, forums, chat rooms, and darknet markets. It helps to determine associated actors, specific activities, expected intentions, emerging research, and ongoing attacks. Our unique _predictive model_ uses _big data_ to forecast activities and their characteristics.

_Live data_ and more _analysis capabilities_ are available at [https://vuldb.com/?actor](https://vuldb.com/?actor)

## Countries

These _countries_ are directly (e.g. origin of attacks) or indirectly (e.g. access by proxy) associated with Windigo:

* [US](https://vuldb.com/?country.us)
* [RU](https://vuldb.com/?country.ru)
* [PL](https://vuldb.com/?country.pl)
* ...

There are 16 more country items available. Please use our online service to access the data.

## Actors

These _actors_ are associated with Windigo or other actors linked to the campaign.

ID | Actor | Confidence
-- | ----- | ----------
1 | [Windigo](https://vuldb.com/?actor.windigo) | High

## IOC - Indicator of Compromise

These _indicators of compromise_ (IOC) indicate associated network resources which are known to be part of research and attack activities of Windigo.

ID | IP address | Hostname | Actor | Confidence
-- | ---------- | -------- | ----- | ----------
1 | [45.59.120.146](https://vuldb.com/?ip.45.59.120.146) | 146.120.59.45.static.cloudzy.com | [Windigo](https://vuldb.com/?actor.windigo) | High
2 | [77.67.80.31](https://vuldb.com/?ip.77.67.80.31) | - | [Windigo](https://vuldb.com/?actor.windigo) | High
3 | [85.214.80.4](https://vuldb.com/?ip.85.214.80.4) | h2463956.stratoserver.net | [Windigo](https://vuldb.com/?actor.windigo) | High
4 | ... | ... | ... | ...

There are 9 more IOC items available. Please use our online service to access the data.

## TTP - Tactics, Techniques, Procedures

_Tactics, techniques, and procedures_ (TTP) summarize the suspected MITRE ATT&CK techniques used within Windigo. This data is unique as it uses our predictive model for actor profiling.

ID | Technique | Weakness | Description | Confidence
-- | --------- | -------- | ----------- | ----------
1 | T1006 | CWE-21, CWE-22, CWE-37, CWE-425 | Path Traversal | High
2 | T1040 | CWE-294 | Authentication Bypass by Capture-replay | High
3 | T1055 | CWE-74 | Improper Neutralization of Data within XPath Expressions | High
4 | T1059 | CWE-88, CWE-94, CWE-1321 | Argument Injection | High
5 | T1059.007 | CWE-79, CWE-80 | Cross Site Scripting | High
6 | ... | ... | ... | ...

There are 20 more TTP items available. Please use our online service to access the data.

## IOA - Indicator of Attack

These _indicators of attack_ (IOA) list the potential fragments used for technical activities like reconnaissance, exploitation, privilege escalation, and exfiltration during Windigo. This data is unique as it uses our predictive model for actor profiling.

ID | Type | Indicator | Confidence
-- | ---- | --------- | ----------
1 | File | `//proc/kcore` | Medium
2 | File | `/?ajax-request=jnews` | High
3 | File | `/admin/about-us.php` | High
4 | File | `/admin/action/delete-vaccine.php` | High
5 | File | `/admin/div_data/delete?divId=9` | High
6 | File | `/admin/edit-post.php` | High
7 | File | `/admin/index2.html` | High
8 | File | `/admin/scripts/pi-hole/phpqueryads.php` | High
9 | File | `/admin/userprofile.php` | High
10 | File | `/api/baskets/{name}` | High
11 | File | `/app/index/controller/Common.php` | High
12 | File | `/applications/core/modules/admin/editor/toolbar.php` | High
13 | File | `/Applications/Google\ Drive.app/Contents/MacOS` | High
14 | File | `/applications/nexus/modules/front/store/store.php` | High
15 | File | `/apply.cgi` | Medium
16 | File | `/bitrix/admin/ldap_server_edit.php` | High
17 | File | `/cgi-bin/cstecgi.cgi` | High
18 | File | `/cgi-bin/nas_sharing.cgi` | High
19 | File | `/cgi-bin/wlogin.cgi` | High
20 | File | `/classes/Master.php` | High
21 | File | `/classes/Master.php?f=save_category` | High
22 | File | `/classes/Users.php?f=save` | High
23 | File | `/College/admin/teacher.php` | High
24 | File | `/Controls/Generic/EBMK/Handlers/EStatements/DownloadEStatement.ashx` | High
25 | File | `/dcim/rack-roles/` | High
26 | File | `/Electron/download` | High
27 | File | `/endpoint/update-computer.php` | High
28 | File | `/fftools/ffmpeg_enc.c` | High
29 | File | `/forms/doLogin` | High
30 | File | `/formSysLog` | Medium
31 | File | `/forum/away.php` | High
32 | File | `/goform/aspForm` | High
33 | File | `/goform/delAd` | High
34 | File | `/goform/SetOnlineDevName` | High
35 | File | `/inc/topBarNav.php` | High
36 | File | `/index.php` | Medium
37 | File | `/index.php?app=main&func=passport&action=login` | High
38 | File | `/install/` | Medium
39 | File | `/kelas/data` | Medium
40 | File | `/listplace/user/ticket/create` | High
41 | File | `/lua/set-passwd.lua` | High
42 | File | `/Main_Login.asp?flag=1&productname=RT-AC88U&url=/downloadmaster/task.asp` | High
43 | File | `/MIME/INBOX-MM-1/` | High
44 | File | `/Moosikay/order.php` | High
45 | File | `/novel/author/list` | High
46 | File | `/pages/animals.php` | High
47 | ... | ... | ...

There are 407 more IOA items available (file, library, argument, input value, pattern, network port). Please use our online service to access the data.

## References

The following list contains _external sources_ which discuss the campaign and the associated activities:

* https://github.com/eset/malware-ioc/tree/master/windigo

## Literature

The following _articles_ explain our unique predictive cyber threat intelligence:

* [VulDB Cyber Threat Intelligence Documentation](https://vuldb.com/?kb.cti)
* [Cyber Threat Intelligence - Early Anticipation of Attacks](https://www.scip.ch/en/?labs.20201022)

## License

(c) [1997-2024](https://vuldb.com/?kb.changelog) by [vuldb.com](https://vuldb.com/?kb.about). All data on this page is shared under the license [CC BY-NC-SA 4.0](https://creativecommons.org/licenses/by-nc-sa/4.0/). Questions? Check the [FAQ](https://vuldb.com/?kb.faq), read the [documentation](https://vuldb.com/?kb) or [contact us](https://vuldb.com/?contact)!
