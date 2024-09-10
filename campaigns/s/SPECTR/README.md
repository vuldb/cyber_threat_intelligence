# SPECTR - Cyber Threat Intelligence

These _indicators_ were reported, collected, and generated during the [VulDB CTI analysis](https://vuldb.com/?kb.cti) of the campaign known as _SPECTR_. The _activity monitoring_ correlates data from social media, forums, chat rooms, and darknet markets. It helps to determine associated actors, specific activities, expected intentions, emerging research, and ongoing attacks. Our unique _predictive model_ uses _big data_ to forecast activities and their characteristics.

_Live data_ and more _analysis capabilities_ are available at [https://vuldb.com/?actor](https://vuldb.com/?actor)

## Countries

These _countries_ are directly (e.g. origin of attacks) or indirectly (e.g. access by proxy) associated with SPECTR:

* [US](https://vuldb.com/?country.us)
* [RU](https://vuldb.com/?country.ru)
* [TR](https://vuldb.com/?country.tr)
* ...

There are 12 more country items available. Please use our online service to access the data.

## Actors

These _actors_ are associated with SPECTR or other actors linked to the campaign.

ID | Actor | Confidence
-- | ----- | ----------
1 | [Vermin](https://vuldb.com/?actor.vermin) | High
2 | [Spectre](https://vuldb.com/?actor.spectre) | High

## IOC - Indicator of Compromise

These _indicators of compromise_ (IOC) indicate associated network resources which are known to be part of research and attack activities of SPECTR.

ID | IP address | Hostname | Actor | Confidence
-- | ---------- | -------- | ----- | ----------
1 | [91.92.240.40](https://vuldb.com/?ip.91.92.240.40) | - | [Spectre](https://vuldb.com/?actor.spectre) | High
2 | [91.92.241.187](https://vuldb.com/?ip.91.92.241.187) | - | [Spectre](https://vuldb.com/?actor.spectre) | High
3 | [91.92.243.158](https://vuldb.com/?ip.91.92.243.158) | - | [Spectre](https://vuldb.com/?actor.spectre) | High
4 | [91.92.244.110](https://vuldb.com/?ip.91.92.244.110) | - | [Spectre](https://vuldb.com/?actor.spectre) | High
5 | ... | ... | ... | ...

There are 18 more IOC items available. Please use our online service to access the data.

## TTP - Tactics, Techniques, Procedures

_Tactics, techniques, and procedures_ (TTP) summarize the suspected MITRE ATT&CK techniques used within SPECTR. This data is unique as it uses our predictive model for actor profiling.

ID | Technique | Weakness | Description | Confidence
-- | --------- | -------- | ----------- | ----------
1 | T1006 | CWE-21, CWE-22, CWE-425 | Path Traversal | High
2 | T1040 | CWE-294, CWE-319 | Authentication Bypass by Capture-replay | High
3 | T1055 | CWE-74 | Improper Neutralization of Data within XPath Expressions | High
4 | T1059 | CWE-88, CWE-94, CWE-1321 | Argument Injection | High
5 | T1059.007 | CWE-79, CWE-80 | Cross Site Scripting | High
6 | ... | ... | ... | ...

There are 21 more TTP items available. Please use our online service to access the data.

## IOA - Indicator of Attack

These _indicators of attack_ (IOA) list the potential fragments used for technical activities like reconnaissance, exploitation, privilege escalation, and exfiltration during SPECTR. This data is unique as it uses our predictive model for actor profiling.

ID | Type | Indicator | Confidence
-- | ---- | --------- | ----------
1 | File | `//proc/kcore` | Medium
2 | File | `/admin.php/Admin/adminadd.html` | High
3 | File | `/admin/about-us.php` | High
4 | File | `/admin/action/delete-vaccine.php` | High
5 | File | `/Admin/add-student.php` | High
6 | File | `/admin/ajax.php?action=save_window` | High
7 | File | `/admin/edit-post.php` | High
8 | File | `/admin/index2.html` | High
9 | File | `/admin/settings/save.php` | High
10 | File | `/admin/suppliers/view_details.php` | High
11 | File | `/admin/userprofile.php` | High
12 | File | `/api/baskets/{name}` | High
13 | File | `/app/index/controller/Common.php` | High
14 | File | `/applications/core/modules/admin/editor/toolbar.php` | High
15 | File | `/Applications/Google\ Drive.app/Contents/MacOS` | High
16 | File | `/applications/nexus/modules/front/store/store.php` | High
17 | File | `/apply.cgi` | Medium
18 | File | `/be/erpc.php` | Medium
19 | File | `/be/rpc.php` | Medium
20 | File | `/bitrix/admin/ldap_server_edit.php` | High
21 | File | `/cgi-bin-sdb/` | High
22 | File | `/cgi-bin/nas_sharing.cgi` | High
23 | File | `/cgi-bin/system_mgr.cgi` | High
24 | File | `/cgi-bin/wlogin.cgi` | High
25 | File | `/classes/Master.php` | High
26 | File | `/classes/Master.php?f=save_category` | High
27 | File | `/classes/Users.php?f=save` | High
28 | File | `/clearance/clearance.php` | High
29 | File | `/College/admin/teacher.php` | High
30 | File | `/Controls/Generic/EBMK/Handlers/EStatements/DownloadEStatement.ashx` | High
31 | File | `/dcim/rack-roles/` | High
32 | File | `/fftools/ffmpeg_enc.c` | High
33 | File | `/forms/doLogin` | High
34 | File | `/formSysLog` | Medium
35 | File | `/forum/away.php` | High
36 | File | `/goform/addUserName` | High
37 | File | `/goform/aspForm` | High
38 | File | `/goform/delAd` | High
39 | File | `/goform/SetOnlineDevName` | High
40 | File | `/goform/wifiSSIDset` | High
41 | File | `/gpac/src/bifs/unquantize.c` | High
42 | File | `/hospital/hms/admin/patient-search.php` | High
43 | File | `/inc/topBarNav.php` | High
44 | File | `/index.asp` | Medium
45 | File | `/index.php` | Medium
46 | File | `/index.php?app=main&func=passport&action=login` | High
47 | File | `/install/` | Medium
48 | File | `/jfinal_cms/system/role/list` | High
49 | File | `/kelas/data` | Medium
50 | File | `/listplace/user/ticket/create` | High
51 | File | `/Main_Login.asp?flag=1&productname=RT-AC88U&url=/downloadmaster/task.asp` | High
52 | File | `/MIME/INBOX-MM-1/` | High
53 | File | `/Moosikay/order.php` | High
54 | File | `/novel/author/list` | High
55 | ... | ... | ...

There are 477 more IOA items available (file, library, argument, input value, pattern, network port). Please use our online service to access the data.

## References

The following list contains _external sources_ which discuss the campaign and the associated activities:

* https://cert.gov.ua/article/37815
* https://medium.com/walmartglobaltech/spectre-spc-v9-campaigns-and-upda

## Literature

The following _articles_ explain our unique predictive cyber threat intelligence:

* [VulDB Cyber Threat Intelligence Documentation](https://vuldb.com/?kb.cti)
* [Cyber Threat Intelligence - Early Anticipation of Attacks](https://www.scip.ch/en/?labs.20201022)

## License

(c) [1997-2024](https://vuldb.com/?kb.changelog) by [vuldb.com](https://vuldb.com/?kb.about). All data on this page is shared under the license [CC BY-NC-SA 4.0](https://creativecommons.org/licenses/by-nc-sa/4.0/). Questions? Check the [FAQ](https://vuldb.com/?kb.faq), read the [documentation](https://vuldb.com/?kb) or [contact us](https://vuldb.com/?contact)!
