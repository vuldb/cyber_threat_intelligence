# Coper - Cyber Threat Intelligence

These _indicators_ were reported, collected, and generated during the [VulDB CTI analysis](https://vuldb.com/?kb.cti) of the actor known as [Coper](https://vuldb.com/?actor.coper). The _activity monitoring_ correlates data from social media, forums, chat rooms, and darknet markets. It helps to determine associated actors, specific activities, expected intentions, emerging research, and ongoing attacks. Our unique _predictive model_ uses _big data_ to forecast activities and their characteristics.

_Live data_ and more _analysis capabilities_ are available at [https://vuldb.com/?actor.coper](https://vuldb.com/?actor.coper)

## Countries

These _countries_ are directly (e.g. origin of attacks) or indirectly (e.g. access by proxy) associated with Coper:

* [US](https://vuldb.com/?country.us)
* [RU](https://vuldb.com/?country.ru)
* [DE](https://vuldb.com/?country.de)
* ...

There are 16 more country items available. Please use our online service to access the data.

## IOC - Indicator of Compromise

These _indicators of compromise_ (IOC) indicate associated network resources which are known to be part of research and attack activities of Coper.

ID | IP address | Hostname | Campaign | Confidence
-- | ---------- | -------- | -------- | ----------
1 | [2.57.149.104](https://vuldb.com/?ip.2.57.149.104) | - | - | High
2 | [2.57.149.150](https://vuldb.com/?ip.2.57.149.150) | - | - | High
3 | [2.57.149.175](https://vuldb.com/?ip.2.57.149.175) | - | - | High
4 | [31.41.244.41](https://vuldb.com/?ip.31.41.244.41) | - | - | High
5 | [31.41.244.178](https://vuldb.com/?ip.31.41.244.178) | - | - | High
6 | [45.9.74.60](https://vuldb.com/?ip.45.9.74.60) | - | - | High
7 | [45.9.74.136](https://vuldb.com/?ip.45.9.74.136) | - | - | High
8 | [45.9.74.166](https://vuldb.com/?ip.45.9.74.166) | - | - | High
9 | [45.88.91.119](https://vuldb.com/?ip.45.88.91.119) | - | - | High
10 | [45.93.20.145](https://vuldb.com/?ip.45.93.20.145) | - | - | High
11 | [46.19.138.93](https://vuldb.com/?ip.46.19.138.93) | hostedby.privatelayer.com | - | High
12 | [62.122.184.165](https://vuldb.com/?ip.62.122.184.165) | - | - | High
13 | [62.233.50.113](https://vuldb.com/?ip.62.233.50.113) | - | - | High
14 | [83.97.73.39](https://vuldb.com/?ip.83.97.73.39) | - | - | High
15 | ... | ... | ... | ...

There are 56 more IOC items available. Please use our online service to access the data.

## TTP - Tactics, Techniques, Procedures

_Tactics, techniques, and procedures_ (TTP) summarize the suspected MITRE ATT&CK techniques used by _Coper_. This data is unique as it uses our predictive model for actor profiling.

ID | Technique | Weakness | Description | Confidence
-- | --------- | -------- | ----------- | ----------
1 | T1006 | CWE-21, CWE-22, CWE-23, CWE-29, CWE-425 | Path Traversal | High
2 | T1040 | CWE-294 | Authentication Bypass by Capture-replay | High
3 | T1055 | CWE-74 | Improper Neutralization of Data within XPath Expressions | High
4 | T1059 | CWE-88, CWE-94, CWE-1321 | Argument Injection | High
5 | T1059.007 | CWE-79, CWE-80 | Cross Site Scripting | High
6 | ... | ... | ... | ...

There are 22 more TTP items available. Please use our online service to access the data.

## IOA - Indicator of Attack

These _indicators of attack_ (IOA) list the potential fragments used for technical activities like reconnaissance, exploitation, privilege escalation, and exfiltration by Coper. This data is unique as it uses our predictive model for actor profiling.

ID | Type | Indicator | Confidence
-- | ---- | --------- | ----------
1 | File | `/+CSCOE+/logon.html` | High
2 | File | `//proc/kcore` | Medium
3 | File | `/admin/about-us.php` | High
4 | File | `/admin/action/delete-vaccine.php` | High
5 | File | `/admin/admin_user.php` | High
6 | File | `/admin/config/uploadicon.php` | High
7 | File | `/admin/edit-post.php` | High
8 | File | `/admin/index2.html` | High
9 | File | `/admin/manage_model.php` | High
10 | File | `/admin/manage_station.php` | High
11 | File | `/Admin/News.php` | High
12 | File | `/admin/searchview.php` | High
13 | File | `/admin/userprofile.php` | High
14 | File | `/ajax.php?action=save_establishment` | High
15 | File | `/api/baskets/{name}` | High
16 | File | `/app/index/controller/Common.php` | High
17 | File | `/applications/core/modules/admin/editor/toolbar.php` | High
18 | File | `/Applications/Google\ Drive.app/Contents/MacOS` | High
19 | File | `/applications/nexus/modules/front/store/store.php` | High
20 | File | `/bitrix/admin/ldap_server_edit.php` | High
21 | File | `/catalog/admin/categories.php?cPath=&action=new_product` | High
22 | File | `/cgi-bin/` | Medium
23 | File | `/cgi-bin/apkg_mgr.cgi` | High
24 | File | `/cgi-bin/cstecgi.cgi` | High
25 | File | `/cgi-bin/downloadFile.cgi` | High
26 | File | `/cgi-bin/nas_sharing.cgi` | High
27 | File | `/cgi-bin/photocenter_mgr.cgi` | High
28 | File | `/cgi-bin/wlogin.cgi` | High
29 | File | `/classes/Master.php` | High
30 | File | `/classes/Master.php?f=delete_record` | High
31 | File | `/classes/Master.php?f=save_category` | High
32 | File | `/classes/SystemSettings.php?f=update_settings` | High
33 | File | `/classes/Users.php?f=save` | High
34 | File | `/College/admin/teacher.php` | High
35 | File | `/Controls/Generic/EBMK/Handlers/EStatements/DownloadEStatement.ashx` | High
36 | File | `/dcim/rack-roles/` | High
37 | File | `/detailed.php` | High
38 | File | `/dtale/chart-data/1` | High
39 | File | `/Duty/AjaxHandle/UploadFloodPlanFileUpdate.ashx` | High
40 | File | `/etc/shadow.sample` | High
41 | File | `/fftools/ffmpeg_enc.c` | High
42 | File | `/foms/routers/place-order.php` | High
43 | File | `/forms/doLogin` | High
44 | File | `/formSysLog` | Medium
45 | File | `/forum/away.php` | High
46 | File | `/goform/aspForm` | High
47 | File | `/goform/SetOnlineDevName` | High
48 | File | `/h.php/page?ref=addtabs` | High
49 | File | `/image.php` | Medium
50 | File | `/inc/lists/edit-list.php` | High
51 | File | `/inc/lists/view-list.php` | High
52 | File | `/inc/topBarNav.php` | High
53 | File | `/includes/common/require_access_recovery.php` | High
54 | File | `/index.php` | Medium
55 | File | `/index.php?action=editPharmacist` | High
56 | ... | ... | ...

There are 485 more IOA items available (file, library, argument, input value, pattern, network port). Please use our online service to access the data.

## References

The following list contains _external sources_ which discuss the actor and the associated activities:

* https://threatfox.abuse.ch
* https://tracker.viriback.com/index.php?q=91.92.254.42

## Literature

The following _articles_ explain our unique predictive cyber threat intelligence:

* [VulDB Cyber Threat Intelligence Documentation](https://vuldb.com/?kb.cti)
* [Cyber Threat Intelligence - Early Anticipation of Attacks](https://www.scip.ch/en/?labs.20201022)

## License

(c) [1997-2024](https://vuldb.com/?kb.changelog) by [vuldb.com](https://vuldb.com/?kb.about). All data on this page is shared under the license [CC BY-NC-SA 4.0](https://creativecommons.org/licenses/by-nc-sa/4.0/). Questions? Check the [FAQ](https://vuldb.com/?kb.faq), read the [documentation](https://vuldb.com/?kb) or [contact us](https://vuldb.com/?contact)!
