# Game of Emperor - Cyber Threat Intelligence

These _indicators_ were reported, collected, and generated during the [VulDB CTI analysis](https://vuldb.com/?kb.cti) of the campaign known as _Game of Emperor_. The _activity monitoring_ correlates data from social media, forums, chat rooms, and darknet markets. It helps to determine associated actors, specific activities, expected intentions, emerging research, and ongoing attacks. Our unique _predictive model_ uses _big data_ to forecast activities and their characteristics.

_Live data_ and more _analysis capabilities_ are available at [https://vuldb.com/?actor](https://vuldb.com/?actor)

## Countries

These _countries_ are directly (e.g. origin of attacks) or indirectly (e.g. access by proxy) associated with Game of Emperor:

* [US](https://vuldb.com/?country.us)
* [RU](https://vuldb.com/?country.ru)
* [TR](https://vuldb.com/?country.tr)
* ...

There are 14 more country items available. Please use our online service to access the data.

## Actors

These _actors_ are associated with Game of Emperor or other actors linked to the campaign.

ID | Actor | Confidence
-- | ----- | ----------
1 | [Earth Estries](https://vuldb.com/?actor.earth_estries) | High

## IOC - Indicator of Compromise

These _indicators of compromise_ (IOC) indicate associated network resources which are known to be part of research and attack activities of Game of Emperor.

ID | IP address | Hostname | Actor | Confidence
-- | ---------- | -------- | ----- | ----------
1 | [23.81.41.166](https://vuldb.com/?ip.23.81.41.166) | - | [Earth Estries](https://vuldb.com/?actor.earth_estries) | High
2 | [103.159.133.251](https://vuldb.com/?ip.103.159.133.251) | - | [Earth Estries](https://vuldb.com/?actor.earth_estries) | High
3 | [141.255.164.98](https://vuldb.com/?ip.141.255.164.98) | hostedby.privatelayer.com | [Earth Estries](https://vuldb.com/?actor.earth_estries) | High

## TTP - Tactics, Techniques, Procedures

_Tactics, techniques, and procedures_ (TTP) summarize the suspected MITRE ATT&CK techniques used within Game of Emperor. This data is unique as it uses our predictive model for actor profiling.

ID | Technique | Weakness | Description | Confidence
-- | --------- | -------- | ----------- | ----------
1 | T1006 | CWE-21, CWE-22, CWE-35, CWE-425 | Path Traversal | High
2 | T1040 | CWE-294 | Authentication Bypass by Capture-replay | High
3 | T1055 | CWE-74 | Improper Neutralization of Data within XPath Expressions | High
4 | T1059 | CWE-88, CWE-94, CWE-1321 | Argument Injection | High
5 | T1059.007 | CWE-79, CWE-80 | Basic Cross Site Scripting | High
6 | ... | ... | ... | ...

There are 21 more TTP items available. Please use our online service to access the data.

## IOA - Indicator of Attack

These _indicators of attack_ (IOA) list the potential fragments used for technical activities like reconnaissance, exploitation, privilege escalation, and exfiltration during Game of Emperor. This data is unique as it uses our predictive model for actor profiling.

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
9 | File | `/admin/content/editor` | High
10 | File | `/admin/create-package.php` | High
11 | File | `/admin/doAdminAction.php?act=addCate` | High
12 | File | `/admin/edit-brand.php` | High
13 | File | `/admin/edit-post.php` | High
14 | File | `/admin/index2.html` | High
15 | File | `/admin/profile.php` | High
16 | File | `/Admin/Proses_Edit_Akun.php` | High
17 | File | `/admin/robot.php` | High
18 | File | `/admin/search-invoices.php` | High
19 | File | `/admin/twitter.php` | High
20 | File | `/admin/userprofile.php` | High
21 | File | `/api/baskets/{name}` | High
22 | File | `/app/controller/Api.php` | High
23 | File | `/app/index/controller/Common.php` | High
24 | File | `/applications/core/modules/admin/editor/toolbar.php` | High
25 | File | `/Applications/Google\ Drive.app/Contents/MacOS` | High
26 | File | `/applications/nexus/modules/front/store/store.php` | High
27 | File | `/apply.cgi` | Medium
28 | File | `/backend/doc/his_doc_update-account.php` | High
29 | File | `/bitrix/admin/ldap_server_edit.php` | High
30 | File | `/cgi-bin/apkg_mgr.cgi` | High
31 | File | `/cgi-bin/cstecgi.cgi` | High
32 | File | `/cgi-bin/nas_sharing.cgi` | High
33 | File | `/cgi-bin/photocenter_mgr.cgi` | High
34 | File | `/cgi-bin/wlogin.cgi` | High
35 | File | `/classes/Master.php` | High
36 | File | `/classes/Master.php?f=delete_record` | High
37 | File | `/classes/Master.php?f=save_category` | High
38 | File | `/classes/SystemSettings.php?f=update_settings` | High
39 | File | `/classes/Users.php?f=save` | High
40 | File | `/College/admin/teacher.php` | High
41 | File | `/Controls/Generic/EBMK/Handlers/EStatements/DownloadEStatement.ashx` | High
42 | File | `/customnode/install` | High
43 | File | `/dcim/rack-roles/` | High
44 | File | `/deal/{note_id}/note` | High
45 | File | `/detailed.php` | High
46 | File | `/dtale/chart-data/1` | High
47 | File | `/etc/shadow.sample` | High
48 | File | `/fftools/ffmpeg_enc.c` | High
49 | File | `/filter.php` | Medium
50 | File | `/fladmin/sysconfig_doedit.php` | High
51 | File | `/forms/doLogin` | High
52 | ... | ... | ...

There are 456 more IOA items available (file, library, argument, input value, pattern, network port). Please use our online service to access the data.

## References

The following list contains _external sources_ which discuss the campaign and the associated activities:

* https://www.trendmicro.com/en_us/research/24/k/earth-estries.html

## Literature

The following _articles_ explain our unique predictive cyber threat intelligence:

* [VulDB Cyber Threat Intelligence Documentation](https://vuldb.com/?kb.cti)
* [Cyber Threat Intelligence - Early Anticipation of Attacks](https://www.scip.ch/en/?labs.20201022)

## License

(c) [1997-2025](https://vuldb.com/?kb.changelog) by [vuldb.com](https://vuldb.com/?kb.about). All data on this page is shared under the license [CC BY-NC-SA 4.0](https://creativecommons.org/licenses/by-nc-sa/4.0/). Questions? Check the [FAQ](https://vuldb.com/?kb.faq), read the [documentation](https://vuldb.com/?kb) or [contact us](https://vuldb.com/?contact)!
