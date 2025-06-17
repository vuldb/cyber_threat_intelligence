# UAC-0173 - Cyber Threat Intelligence

These _indicators_ were reported, collected, and generated during the [VulDB CTI analysis](https://vuldb.com/?kb.cti) of the actor known as [UAC-0173](https://vuldb.com/?actor.uac-0173). The _activity monitoring_ correlates data from social media, forums, chat rooms, and darknet markets. It helps to determine associated actors, specific activities, expected intentions, emerging research, and ongoing attacks. Our unique _predictive model_ uses _big data_ to forecast activities and their characteristics.

_Live data_ and more _analysis capabilities_ are available at [https://vuldb.com/?actor.uac-0173](https://vuldb.com/?actor.uac-0173)

## Countries

These _countries_ are directly (e.g. origin of attacks) or indirectly (e.g. access by proxy) associated with UAC-0173:

* [US](https://vuldb.com/?country.us)
* [RU](https://vuldb.com/?country.ru)
* [CN](https://vuldb.com/?country.cn)
* ...

There are 16 more country items available. Please use our online service to access the data.

## IOC - Indicator of Compromise

These _indicators of compromise_ (IOC) indicate associated network resources which are known to be part of research and attack activities of UAC-0173.

ID | IP address | Hostname | Campaign | Confidence
-- | ---------- | -------- | -------- | ----------
1 | [87.120.126.48](https://vuldb.com/?ip.87.120.126.48) | - | - | High
2 | [89.105.201.98](https://vuldb.com/?ip.89.105.201.98) | vm78714.vps.client-server.site | - | High
3 | [91.92.246.18](https://vuldb.com/?ip.91.92.246.18) | revenue18.unefectual91.great-artistic.com | - | High
4 | ... | ... | ... | ...

There are 5 more IOC items available. Please use our online service to access the data.

## TTP - Tactics, Techniques, Procedures

_Tactics, techniques, and procedures_ (TTP) summarize the suspected MITRE ATT&CK techniques used by _UAC-0173_. This data is unique as it uses our predictive model for actor profiling.

ID | Technique | Weakness | Description | Confidence
-- | --------- | -------- | ----------- | ----------
1 | T1006 | CWE-21, CWE-22, CWE-24, CWE-35, CWE-425 | Path Traversal | High
2 | T1040 | CWE-294 | Authentication Bypass by Capture-replay | High
3 | T1055 | CWE-74 | Improper Neutralization of Data within XPath Expressions | High
4 | T1059 | CWE-88, CWE-94, CWE-1321 | Argument Injection | High
5 | T1059.007 | CWE-79, CWE-80 | Basic Cross Site Scripting | High
6 | ... | ... | ... | ...

There are 22 more TTP items available. Please use our online service to access the data.

## IOA - Indicator of Attack

These _indicators of attack_ (IOA) list the potential fragments used for technical activities like reconnaissance, exploitation, privilege escalation, and exfiltration by UAC-0173. This data is unique as it uses our predictive model for actor profiling.

ID | Type | Indicator | Confidence
-- | ---- | --------- | ----------
1 | File | `//proc/kcore` | Medium
2 | File | `/add_new_invoice.php` | High
3 | File | `/add_user.php` | High
4 | File | `/admin/about-us.php` | High
5 | File | `/admin/action/delete-vaccine.php` | High
6 | File | `/Admin/akun_edit.php` | High
7 | File | `/admin/apply.php` | High
8 | File | `/admin/content/editor` | High
9 | File | `/admin/create-package.php` | High
10 | File | `/admin/doAdminAction.php?act=addCate` | High
11 | File | `/admin/edit-brand.php` | High
12 | File | `/admin/edit-post.php` | High
13 | File | `/admin/index2.html` | High
14 | File | `/admin/profile.php` | High
15 | File | `/Admin/Proses_Edit_Akun.php` | High
16 | File | `/admin/robot.php` | High
17 | File | `/admin/search-invoices.php` | High
18 | File | `/admin/twitter.php` | High
19 | File | `/api/baskets/{name}` | High
20 | File | `/app/controller/Api.php` | High
21 | File | `/app/index/controller/Common.php` | High
22 | File | `/app/options.py` | High
23 | File | `/applications/core/modules/admin/editor/toolbar.php` | High
24 | File | `/Applications/Google\ Drive.app/Contents/MacOS` | High
25 | File | `/applications/nexus/modules/front/store/store.php` | High
26 | File | `/auth_files/photo/` | High
27 | File | `/backend/doc/his_doc_update-account.php` | High
28 | File | `/bitrix/admin/ldap_server_edit.php` | High
29 | File | `/cgi-bin/apkg_mgr.cgi` | High
30 | File | `/cgi-bin/cstecgi.cgi` | High
31 | File | `/cgi-bin/nas_sharing.cgi` | High
32 | File | `/cgi-bin/photocenter_mgr.cgi` | High
33 | File | `/classes/Master.php` | High
34 | File | `/classes/Master.php?f=delete_record` | High
35 | File | `/classes/Master.php?f=save_category` | High
36 | File | `/classes/SystemSettings.php?f=update_settings` | High
37 | File | `/classes/Users.php?f=save` | High
38 | File | `/cstecgi.cgi` | Medium
39 | File | `/customnode/install` | High
40 | File | `/dcim/rack-roles/` | High
41 | File | `/deal/{note_id}/note` | High
42 | File | `/debuginfo.htm` | High
43 | File | `/detailed.php` | High
44 | File | `/dtale/chart-data/1` | High
45 | File | `/etc/passwd` | Medium
46 | File | `/etc/shadow.sample` | High
47 | File | `/fftools/ffmpeg_enc.c` | High
48 | File | `/filter.php` | Medium
49 | File | `/fladmin/sysconfig_doedit.php` | High
50 | ... | ... | ...

There are 432 more IOA items available (file, library, argument, input value, pattern, network port). Please use our online service to access the data.

## References

The following list contains _external sources_ which discuss the actor and the associated activities:

* https://cert.gov.ua/article/5628441
* https://cyble.com/blog/uac-0173-targeted-cyberattacks-on-ua-notary/

## Literature

The following _articles_ explain our unique predictive cyber threat intelligence:

* [VulDB Cyber Threat Intelligence Documentation](https://vuldb.com/?kb.cti)
* [Cyber Threat Intelligence - Early Anticipation of Attacks](https://www.scip.ch/en/?labs.20201022)

## License

(c) [1997-2025](https://vuldb.com/?kb.changelog) by [vuldb.com](https://vuldb.com/?kb.about). All data on this page is shared under the license [CC BY-NC-SA 4.0](https://creativecommons.org/licenses/by-nc-sa/4.0/). Questions? Check the [FAQ](https://vuldb.com/?kb.faq), read the [documentation](https://vuldb.com/?kb) or [contact us](https://vuldb.com/?contact)!
