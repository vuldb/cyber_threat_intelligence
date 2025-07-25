# Windigo - Cyber Threat Intelligence

These _indicators_ were reported, collected, and generated during the [VulDB CTI analysis](https://vuldb.com/?kb.cti) of the campaign known as _Windigo_. The _activity monitoring_ correlates data from social media, forums, chat rooms, and darknet markets. It helps to determine associated actors, specific activities, expected intentions, emerging research, and ongoing attacks. Our unique _predictive model_ uses _big data_ to forecast activities and their characteristics.

_Live data_ and more _analysis capabilities_ are available at [https://vuldb.com/?actor](https://vuldb.com/?actor)

## Countries

These _countries_ are directly (e.g. origin of attacks) or indirectly (e.g. access by proxy) associated with Windigo:

* [US](https://vuldb.com/?country.us)
* [RU](https://vuldb.com/?country.ru)
* [GB](https://vuldb.com/?country.gb)
* ...

There are 17 more country items available. Please use our online service to access the data.

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
1 | T1006 | CWE-21, CWE-22, CWE-35, CWE-425 | Path Traversal | High
2 | T1040 | CWE-294 | Authentication Bypass by Capture-replay | High
3 | T1055 | CWE-74 | Improper Neutralization of Data within XPath Expressions | High
4 | T1059 | CWE-88, CWE-94, CWE-1321 | Argument Injection | High
5 | T1059.007 | CWE-79, CWE-80 | Basic Cross Site Scripting | High
6 | ... | ... | ... | ...

There are 18 more TTP items available. Please use our online service to access the data.

## IOA - Indicator of Attack

These _indicators of attack_ (IOA) list the potential fragments used for technical activities like reconnaissance, exploitation, privilege escalation, and exfiltration during Windigo. This data is unique as it uses our predictive model for actor profiling.

ID | Type | Indicator | Confidence
-- | ---- | --------- | ----------
1 | File | `//proc/kcore` | Medium
2 | File | `/add-subadmin.php` | High
3 | File | `/add_new_invoice.php` | High
4 | File | `/add_user.php` | High
5 | File | `/admin/about-us.php` | High
6 | File | `/admin/action/delete-vaccine.php` | High
7 | File | `/Admin/akun_edit.php` | High
8 | File | `/admin/apply.php` | High
9 | File | `/admin/attendance_action.php` | High
10 | File | `/admin/content/editor` | High
11 | File | `/admin/create-package.php` | High
12 | File | `/admin/div_data/delete?divId=9` | High
13 | File | `/admin/doAdminAction.php?act=addCate` | High
14 | File | `/admin/edit-brand.php` | High
15 | File | `/admin/edit-post.php` | High
16 | File | `/admin/index2.html` | High
17 | File | `/admin/login.php` | High
18 | File | `/admin/profile.php` | High
19 | File | `/Admin/Proses_Edit_Akun.php` | High
20 | File | `/admin/robot.php` | High
21 | File | `/admin/scripts/pi-hole/phpqueryads.php` | High
22 | File | `/admin/search-invoices.php` | High
23 | File | `/admin/twitter.php` | High
24 | File | `/api/baskets/{name}` | High
25 | File | `/app/controller/Api.php` | High
26 | File | `/app/index/controller/Common.php` | High
27 | File | `/applications/core/modules/admin/editor/toolbar.php` | High
28 | File | `/Applications/Google\ Drive.app/Contents/MacOS` | High
29 | File | `/applications/nexus/modules/front/store/store.php` | High
30 | File | `/backend/doc/his_doc_update-account.php` | High
31 | File | `/bitrix/admin/ldap_server_edit.php` | High
32 | File | `/cgi-bin/apkg_mgr.cgi` | High
33 | File | `/cgi-bin/cstecgi.cgi` | High
34 | File | `/cgi-bin/nas_sharing.cgi` | High
35 | File | `/cgi-bin/photocenter_mgr.cgi` | High
36 | File | `/classes/Master.php` | High
37 | File | `/classes/Master.php?f=delete_record` | High
38 | File | `/classes/Master.php?f=save_category` | High
39 | File | `/classes/SystemSettings.php?f=update_settings` | High
40 | File | `/classes/Users.php?f=save` | High
41 | File | `/customnode/install` | High
42 | File | `/deal/{note_id}/note` | High
43 | File | `/detailed.php` | High
44 | File | `/dtale/chart-data/1` | High
45 | File | `/Electron/download` | High
46 | File | `/endpoint/update-computer.php` | High
47 | File | `/etc/shadow.sample` | High
48 | File | `/fftools/ffmpeg_enc.c` | High
49 | File | `/filter.php` | Medium
50 | File | `/fladmin/sysconfig_doedit.php` | High
51 | File | `/forms/doLogin` | High
52 | File | `/formSysLog` | Medium
53 | ... | ... | ...

There are 461 more IOA items available (file, library, argument, input value, pattern, network port). Please use our online service to access the data.

## References

The following list contains _external sources_ which discuss the campaign and the associated activities:

* https://github.com/eset/malware-ioc/tree/master/windigo

## Literature

The following _articles_ explain our unique predictive cyber threat intelligence:

* [VulDB Cyber Threat Intelligence Documentation](https://vuldb.com/?kb.cti)
* [Cyber Threat Intelligence - Early Anticipation of Attacks](https://www.scip.ch/en/?labs.20201022)

## License

(c) [1997-2025](https://vuldb.com/?kb.changelog) by [vuldb.com](https://vuldb.com/?kb.about). All data on this page is shared under the license [CC BY-NC-SA 4.0](https://creativecommons.org/licenses/by-nc-sa/4.0/). Questions? Check the [FAQ](https://vuldb.com/?kb.faq), read the [documentation](https://vuldb.com/?kb) or [contact us](https://vuldb.com/?contact)!
