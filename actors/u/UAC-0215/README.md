# UAC-0215 - Cyber Threat Intelligence

These _indicators_ were reported, collected, and generated during the [VulDB CTI analysis](https://vuldb.com/?kb.cti) of the actor known as [UAC-0215](https://vuldb.com/?actor.uac-0215). The _activity monitoring_ correlates data from social media, forums, chat rooms, and darknet markets. It helps to determine associated actors, specific activities, expected intentions, emerging research, and ongoing attacks. Our unique _predictive model_ uses _big data_ to forecast activities and their characteristics.

_Live data_ and more _analysis capabilities_ are available at [https://vuldb.com/?actor.uac-0215](https://vuldb.com/?actor.uac-0215)

## Countries

These _countries_ are directly (e.g. origin of attacks) or indirectly (e.g. access by proxy) associated with UAC-0215:

* [US](https://vuldb.com/?country.us)
* [CN](https://vuldb.com/?country.cn)
* [RU](https://vuldb.com/?country.ru)
* ...

There are 13 more country items available. Please use our online service to access the data.

## IOC - Indicator of Compromise

These _indicators of compromise_ (IOC) indicate associated network resources which are known to be part of research and attack activities of UAC-0215.

ID | IP address | Hostname | Campaign | Confidence
-- | ---------- | -------- | -------- | ----------
1 | [2.58.201.112](https://vuldb.com/?ip.2.58.201.112) | 112.201.58.2.us.kuroit.com | - | High
2 | [13.49.21.253](https://vuldb.com/?ip.13.49.21.253) | ec2-13-49-21-253.eu-north-1.compute.amazonaws.com | - | Medium
3 | [23.160.56.100](https://vuldb.com/?ip.23.160.56.100) | - | - | High
4 | [23.160.56.122](https://vuldb.com/?ip.23.160.56.122) | - | - | High
5 | [37.153.155.143](https://vuldb.com/?ip.37.153.155.143) | - | - | High
6 | [38.180.110.238](https://vuldb.com/?ip.38.180.110.238) | - | - | High
7 | [38.180.146.210](https://vuldb.com/?ip.38.180.146.210) | - | - | High
8 | [38.180.146.230](https://vuldb.com/?ip.38.180.146.230) | - | - | High
9 | [45.11.230.105](https://vuldb.com/?ip.45.11.230.105) | 105.230.11.45.us.kuroit.com | - | High
10 | ... | ... | ... | ...

There are 35 more IOC items available. Please use our online service to access the data.

## TTP - Tactics, Techniques, Procedures

_Tactics, techniques, and procedures_ (TTP) summarize the suspected MITRE ATT&CK techniques used by _UAC-0215_. This data is unique as it uses our predictive model for actor profiling.

ID | Technique | Weakness | Description | Confidence
-- | --------- | -------- | ----------- | ----------
1 | T1006 | CWE-21, CWE-22, CWE-425 | Path Traversal | High
2 | T1040 | CWE-294, CWE-319 | Authentication Bypass by Capture-replay | High
3 | T1055 | CWE-74 | Improper Neutralization of Data within XPath Expressions | High
4 | T1059 | CWE-88, CWE-94, CWE-1321 | Argument Injection | High
5 | T1059.007 | CWE-79, CWE-80 | Basic Cross Site Scripting | High
6 | ... | ... | ... | ...

There are 21 more TTP items available. Please use our online service to access the data.

## IOA - Indicator of Attack

These _indicators of attack_ (IOA) list the potential fragments used for technical activities like reconnaissance, exploitation, privilege escalation, and exfiltration by UAC-0215. This data is unique as it uses our predictive model for actor profiling.

ID | Type | Indicator | Confidence
-- | ---- | --------- | ----------
1 | File | `//proc/kcore` | Medium
2 | File | `/add_new_invoice.php` | High
3 | File | `/admin.php/Admin/adminadd.html` | High
4 | File | `/admin/about-us.php` | High
5 | File | `/admin/action/delete-vaccine.php` | High
6 | File | `/Admin/akun_edit.php` | High
7 | File | `/admin/apply.php` | High
8 | File | `/admin/category/view_category.php` | High
9 | File | `/admin/create-package.php` | High
10 | File | `/admin/doAdminAction.php?act=addCate` | High
11 | File | `/admin/edit-brand.php` | High
12 | File | `/admin/edit-post.php` | High
13 | File | `/admin/index2.html` | High
14 | File | `/Admin/Proses_Edit_Akun.php` | High
15 | File | `/admin/robot.php` | High
16 | File | `/admin/search-invoices.php` | High
17 | File | `/admin/settings/save.php` | High
18 | File | `/admin/userprofile.php` | High
19 | File | `/api/baskets/{name}` | High
20 | File | `/app/index/controller/Common.php` | High
21 | File | `/applications/core/modules/admin/editor/toolbar.php` | High
22 | File | `/Applications/Google\ Drive.app/Contents/MacOS` | High
23 | File | `/applications/nexus/modules/front/store/store.php` | High
24 | File | `/apply.cgi` | Medium
25 | File | `/bitrix/admin/ldap_server_edit.php` | High
26 | File | `/cgi-bin/apkg_mgr.cgi` | High
27 | File | `/cgi-bin/cstecgi.cgi` | High
28 | File | `/cgi-bin/nas_sharing.cgi` | High
29 | File | `/cgi-bin/photocenter_mgr.cgi` | High
30 | File | `/cgi-bin/wlogin.cgi` | High
31 | File | `/classes/Master.php` | High
32 | File | `/classes/Master.php?f=delete_record` | High
33 | File | `/classes/Master.php?f=save_category` | High
34 | File | `/classes/SystemSettings.php?f=update_settings` | High
35 | File | `/classes/Users.php?f=save` | High
36 | File | `/College/admin/teacher.php` | High
37 | File | `/Controls/Generic/EBMK/Handlers/EStatements/DownloadEStatement.ashx` | High
38 | File | `/dcim/rack-roles/` | High
39 | File | `/deal/{note_id}/note` | High
40 | File | `/detailed.php` | High
41 | File | `/dtale/chart-data/1` | High
42 | File | `/etc/shadow.sample` | High
43 | File | `/fftools/ffmpeg_enc.c` | High
44 | File | `/filter.php` | Medium
45 | File | `/forms/doLogin` | High
46 | File | `/formSysLog` | Medium
47 | File | `/forum/away.php` | High
48 | File | `/general/approve_center/query/list/input_form/delete_data_attach.php` | High
49 | File | `/goform/addUserName` | High
50 | File | `/goform/aspForm` | High
51 | File | `/goform/ate` | Medium
52 | ... | ... | ...

There are 452 more IOA items available (file, library, argument, input value, pattern, network port). Please use our online service to access the data.

## References

The following list contains _external sources_ which discuss the actor and the associated activities:

* https://cert.gov.ua/article/6281076

## Literature

The following _articles_ explain our unique predictive cyber threat intelligence:

* [VulDB Cyber Threat Intelligence Documentation](https://vuldb.com/?kb.cti)
* [Cyber Threat Intelligence - Early Anticipation of Attacks](https://www.scip.ch/en/?labs.20201022)

## License

(c) [1997-2024](https://vuldb.com/?kb.changelog) by [vuldb.com](https://vuldb.com/?kb.about). All data on this page is shared under the license [CC BY-NC-SA 4.0](https://creativecommons.org/licenses/by-nc-sa/4.0/). Questions? Check the [FAQ](https://vuldb.com/?kb.faq), read the [documentation](https://vuldb.com/?kb) or [contact us](https://vuldb.com/?contact)!