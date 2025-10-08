# HijackLoader - Cyber Threat Intelligence

These _indicators_ were reported, collected, and generated during the [VulDB CTI analysis](https://vuldb.com/?kb.cti) of the actor known as [HijackLoader](https://vuldb.com/?actor.hijackloader). The _activity monitoring_ correlates data from social media, forums, chat rooms, and darknet markets. It helps to determine associated actors, specific activities, expected intentions, emerging research, and ongoing attacks. Our unique _predictive model_ uses _big data_ to forecast activities and their characteristics.

_Live data_ and more _analysis capabilities_ are available at [https://vuldb.com/?actor.hijackloader](https://vuldb.com/?actor.hijackloader)

## Countries

These _countries_ are directly (e.g. origin of attacks) or indirectly (e.g. access by proxy) associated with HijackLoader:

* [US](https://vuldb.com/?country.us)
* [RU](https://vuldb.com/?country.ru)
* [TR](https://vuldb.com/?country.tr)
* ...

There are 18 more country items available. Please use our online service to access the data.

## IOC - Indicator of Compromise

These _indicators of compromise_ (IOC) indicate associated network resources which are known to be part of research and attack activities of HijackLoader.

ID | IP address | Hostname | Campaign | Confidence
-- | ---------- | -------- | -------- | ----------
1 | [45.141.233.196](https://vuldb.com/?ip.45.141.233.196) | - | - | High
2 | [62.60.234.80](https://vuldb.com/?ip.62.60.234.80) | susko.aho.cuata | - | High
3 | [77.83.207.69](https://vuldb.com/?ip.77.83.207.69) | - | - | High
4 | ... | ... | ... | ...

There are 8 more IOC items available. Please use our online service to access the data.

## TTP - Tactics, Techniques, Procedures

_Tactics, techniques, and procedures_ (TTP) summarize the suspected MITRE ATT&CK techniques used by _HijackLoader_. This data is unique as it uses our predictive model for actor profiling.

ID | Technique | Weakness | Description | Confidence
-- | --------- | -------- | ----------- | ----------
1 | T1006 | CWE-21, CWE-22, CWE-35, CWE-425 | Path Traversal | High
2 | T1040 | CWE-294 | Authentication Bypass by Capture-replay | High
3 | T1055 | CWE-74 | Improper Neutralization of Data within XPath Expressions | High
4 | T1059 | CWE-88, CWE-94, CWE-1321 | Argument Injection | High
5 | T1059.007 | CWE-79, CWE-80 | Basic Cross Site Scripting | High
6 | ... | ... | ... | ...

There are 20 more TTP items available. Please use our online service to access the data.

## IOA - Indicator of Attack

These _indicators of attack_ (IOA) list the potential fragments used for technical activities like reconnaissance, exploitation, privilege escalation, and exfiltration by HijackLoader. This data is unique as it uses our predictive model for actor profiling.

ID | Type | Indicator | Confidence
-- | ---- | --------- | ----------
1 | File | `//proc/kcore` | Medium
2 | File | `/add-subadmin.php` | High
3 | File | `/add_new_invoice.php` | High
4 | File | `/add_user.php` | High
5 | File | `/admin/about-us.php` | High
6 | File | `/admin/action/delete-vaccine.php` | High
7 | File | `/admin/admin_running.php` | High
8 | File | `/Admin/akun_edit.php` | High
9 | File | `/admin/apply.php` | High
10 | File | `/admin/content/editor` | High
11 | File | `/admin/create-package.php` | High
12 | File | `/admin/delete_s6.php` | High
13 | File | `/admin/doAdminAction.php?act=addCate` | High
14 | File | `/admin/edit-brand.php` | High
15 | File | `/admin/edit-post.php` | High
16 | File | `/admin/index2.html` | High
17 | File | `/admin/manage-ambulance.php` | High
18 | File | `/admin/modules/room/index.php` | High
19 | File | `/admin/profile.php` | High
20 | File | `/Admin/Proses_Edit_Akun.php` | High
21 | File | `/admin/robot.php` | High
22 | File | `/admin/search-invoices.php` | High
23 | File | `/admin/tags/save` | High
24 | File | `/admin/twitter.php` | High
25 | File | `/admin/userprofile.php` | High
26 | File | `/admin/yesterday-reg-users.php` | High
27 | File | `/api/baskets/{name}` | High
28 | File | `/api/settings` | High
29 | File | `/app/api/v1/openvpn.py` | High
30 | File | `/app/controller/Api.php` | High
31 | File | `/app/index/controller/Common.php` | High
32 | File | `/applications/core/modules/admin/editor/toolbar.php` | High
33 | File | `/Applications/Google\ Drive.app/Contents/MacOS` | High
34 | File | `/applications/nexus/modules/front/store/store.php` | High
35 | File | `/backend/doc/his_doc_update-account.php` | High
36 | File | `/bitrix/admin/ldap_server_edit.php` | High
37 | File | `/biurl_grou` | Medium
38 | File | `/cgi-bin/apkg_mgr.cgi` | High
39 | File | `/cgi-bin/cstecgi.cgi` | High
40 | File | `/cgi-bin/nas_sharing.cgi` | High
41 | File | `/cgi-bin/photocenter_mgr.cgi` | High
42 | File | `/cgi-bin/wlogin.cgi` | High
43 | File | `/classes/Master.php` | High
44 | File | `/classes/Master.php?f=delete_record` | High
45 | File | `/classes/Master.php?f=save_category` | High
46 | File | `/classes/SystemSettings.php?f=update_settings` | High
47 | File | `/classes/Users.php?f=save` | High
48 | File | `/College/admin/teacher.php` | High
49 | File | `/Controls/Generic/EBMK/Handlers/EStatements/DownloadEStatement.ashx` | High
50 | File | `/customnode/install` | High
51 | File | `/dcim/rack-roles/` | High
52 | File | `/deal/{note_id}/note` | High
53 | File | `/detailed.php` | High
54 | ... | ... | ...

There are 472 more IOA items available (file, library, argument, input value, pattern, network port). Please use our online service to access the data.

## References

The following list contains _external sources_ which discuss the actor and the associated activities:

* https://app.any.run/tasks/315bc97f-69e0-4346-9f68-973f46961f9c
* https://app.any.run/tasks/237209eb-af1a-47e5-a2d4-76012f2f33f0
* https://bazaar.abuse.ch/sample/16a0e939d42dbe39946c3a48bc07ec9b6ef565c0828f66be053d1320e5f7c4f7/
* https://bazaar.abuse.ch/sample/eec9b4769ab34844f5f6caa304bad459780fe72e337eb8d686f01fcfd3833ac0/
* https://threatfox.abuse.ch
* https://urlhaus.abuse.ch/url/3555651/
* https://urlhaus.abuse.ch/url/3573826/
* https://urlhaus.abuse.ch/url/3581742/
* https://urlhaus.abuse.ch/url/3590817/
* https://urlhaus.abuse.ch/url/3601321/
* https://urlhaus.abuse.ch/url/3611729/

## Literature

The following _articles_ explain our unique predictive cyber threat intelligence:

* [VulDB Cyber Threat Intelligence Documentation](https://vuldb.com/?kb.cti)
* [Cyber Threat Intelligence - Early Anticipation of Attacks](https://www.scip.ch/en/?labs.20201022)

## License

(c) [1997-2025](https://vuldb.com/?kb.changelog) by [vuldb.com](https://vuldb.com/?kb.about). All data on this page is shared under the license [CC BY-NC-SA 4.0](https://creativecommons.org/licenses/by-nc-sa/4.0/). Questions? Check the [FAQ](https://vuldb.com/?kb.faq), read the [documentation](https://vuldb.com/?kb) or [contact us](https://vuldb.com/?contact)!
