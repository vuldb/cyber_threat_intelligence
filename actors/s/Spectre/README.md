# Spectre - Cyber Threat Intelligence

These _indicators_ were reported, collected, and generated during the [VulDB CTI analysis](https://vuldb.com/?kb.cti) of the actor known as [Spectre](https://vuldb.com/?actor.spectre). The _activity monitoring_ correlates data from social media, forums, chat rooms, and darknet markets. It helps to determine associated actors, specific activities, expected intentions, emerging research, and ongoing attacks. Our unique _predictive model_ uses _big data_ to forecast activities and their characteristics.

_Live data_ and more _analysis capabilities_ are available at [https://vuldb.com/?actor.spectre](https://vuldb.com/?actor.spectre)

## Countries

These _countries_ are directly (e.g. origin of attacks) or indirectly (e.g. access by proxy) associated with Spectre:

* [US](https://vuldb.com/?country.us)
* [RU](https://vuldb.com/?country.ru)
* [CN](https://vuldb.com/?country.cn)
* ...

There are 13 more country items available. Please use our online service to access the data.

## IOC - Indicator of Compromise

These _indicators of compromise_ (IOC) indicate associated network resources which are known to be part of research and attack activities of Spectre.

ID | IP address | Hostname | Campaign | Confidence
-- | ---------- | -------- | -------- | ----------
1 | [91.92.240.40](https://vuldb.com/?ip.91.92.240.40) | - | - | High
2 | [91.92.241.187](https://vuldb.com/?ip.91.92.241.187) | - | - | High
3 | [91.92.243.158](https://vuldb.com/?ip.91.92.243.158) | - | - | High
4 | [91.92.244.110](https://vuldb.com/?ip.91.92.244.110) | - | - | High
5 | ... | ... | ... | ...

There are 14 more IOC items available. Please use our online service to access the data.

## TTP - Tactics, Techniques, Procedures

_Tactics, techniques, and procedures_ (TTP) summarize the suspected MITRE ATT&CK techniques used by _Spectre_. This data is unique as it uses our predictive model for actor profiling.

ID | Technique | Weakness | Description | Confidence
-- | --------- | -------- | ----------- | ----------
1 | T1006 | CWE-21, CWE-22, CWE-425 | Path Traversal | High
2 | T1040 | CWE-294 | Authentication Bypass by Capture-replay | High
3 | T1055 | CWE-74 | Improper Neutralization of Data within XPath Expressions | High
4 | T1059 | CWE-88, CWE-94, CWE-1321 | Argument Injection | High
5 | T1059.007 | CWE-79, CWE-80 | Cross Site Scripting | High
6 | ... | ... | ... | ...

There are 21 more TTP items available. Please use our online service to access the data.

## IOA - Indicator of Attack

These _indicators of attack_ (IOA) list the potential fragments used for technical activities like reconnaissance, exploitation, privilege escalation, and exfiltration by Spectre. This data is unique as it uses our predictive model for actor profiling.

ID | Type | Indicator | Confidence
-- | ---- | --------- | ----------
1 | File | `//proc/kcore` | Medium
2 | File | `/add_new_invoice.php` | High
3 | File | `/admin/` | Low
4 | File | `/admin/about-us.php` | High
5 | File | `/admin/action/delete-vaccine.php` | High
6 | File | `/admin/ajax.php?action=save_window` | High
7 | File | `/admin/apply.php` | High
8 | File | `/admin/create-package.php` | High
9 | File | `/admin/doAdminAction.php?act=addCate` | High
10 | File | `/admin/edit-brand.php` | High
11 | File | `/admin/edit-post.php` | High
12 | File | `/admin/index2.html` | High
13 | File | `/admin/login.php` | High
14 | File | `/admin/robot.php` | High
15 | File | `/admin/suppliers/view_details.php` | High
16 | File | `/admin/userprofile.php` | High
17 | File | `/ajax/getBasicInfo.php` | High
18 | File | `/api/baskets/{name}` | High
19 | File | `/app/index/controller/Common.php` | High
20 | File | `/applications/core/modules/admin/editor/toolbar.php` | High
21 | File | `/Applications/Google\ Drive.app/Contents/MacOS` | High
22 | File | `/applications/nexus/modules/front/store/store.php` | High
23 | File | `/apply.cgi` | Medium
24 | File | `/be/erpc.php` | Medium
25 | File | `/be/rpc.php` | Medium
26 | File | `/bitrix/admin/ldap_server_edit.php` | High
27 | File | `/cgi-bin-sdb/` | High
28 | File | `/cgi-bin/apkg_mgr.cgi` | High
29 | File | `/cgi-bin/cstecgi.cgi` | High
30 | File | `/cgi-bin/nas_sharing.cgi` | High
31 | File | `/cgi-bin/photocenter_mgr.cgi` | High
32 | File | `/cgi-bin/system_mgr.cgi` | High
33 | File | `/cgi-bin/wlogin.cgi` | High
34 | File | `/classes/Master.php` | High
35 | File | `/classes/Master.php?f=delete_record` | High
36 | File | `/classes/Master.php?f=save_category` | High
37 | File | `/classes/SystemSettings.php?f=update_settings` | High
38 | File | `/classes/Users.php?f=save` | High
39 | File | `/clearance/clearance.php` | High
40 | File | `/College/admin/teacher.php` | High
41 | File | `/Controls/Generic/EBMK/Handlers/EStatements/DownloadEStatement.ashx` | High
42 | File | `/dcim/rack-roles/` | High
43 | File | `/deal/{note_id}/note` | High
44 | File | `/detailed.php` | High
45 | File | `/dtale/chart-data/1` | High
46 | File | `/ecshop/admin/template.php` | High
47 | File | `/etc/shadow.sample` | High
48 | File | `/fftools/ffmpeg_enc.c` | High
49 | File | `/filter.php` | Medium
50 | File | `/foms/routers/place-order.php` | High
51 | File | `/forms/doLogin` | High
52 | File | `/formSysLog` | Medium
53 | File | `/forum/away.php` | High
54 | File | `/goform/aspForm` | High
55 | File | `/goform/ate` | Medium
56 | File | `/goform/delAd` | High
57 | File | `/goform/formSetWanNonLogin` | High
58 | File | `/goform/formWlanSetup` | High
59 | File | `/goform/SetOnlineDevName` | High
60 | File | `/guest/update.php` | High
61 | ... | ... | ...

There are 531 more IOA items available (file, library, argument, input value, pattern, network port). Please use our online service to access the data.

## References

The following list contains _external sources_ which discuss the actor and the associated activities:

* https://medium.com/walmartglobaltech/spectre-spc-v9-campaigns-and-upda

## Literature

The following _articles_ explain our unique predictive cyber threat intelligence:

* [VulDB Cyber Threat Intelligence Documentation](https://vuldb.com/?kb.cti)
* [Cyber Threat Intelligence - Early Anticipation of Attacks](https://www.scip.ch/en/?labs.20201022)

## License

(c) [1997-2024](https://vuldb.com/?kb.changelog) by [vuldb.com](https://vuldb.com/?kb.about). All data on this page is shared under the license [CC BY-NC-SA 4.0](https://creativecommons.org/licenses/by-nc-sa/4.0/). Questions? Check the [FAQ](https://vuldb.com/?kb.faq), read the [documentation](https://vuldb.com/?kb) or [contact us](https://vuldb.com/?contact)!
