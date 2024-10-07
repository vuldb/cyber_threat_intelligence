# Netsuppport - Cyber Threat Intelligence

These _indicators_ were reported, collected, and generated during the [VulDB CTI analysis](https://vuldb.com/?kb.cti) of the actor known as [Netsuppport](https://vuldb.com/?actor.netsuppport). The _activity monitoring_ correlates data from social media, forums, chat rooms, and darknet markets. It helps to determine associated actors, specific activities, expected intentions, emerging research, and ongoing attacks. Our unique _predictive model_ uses _big data_ to forecast activities and their characteristics.

_Live data_ and more _analysis capabilities_ are available at [https://vuldb.com/?actor.netsuppport](https://vuldb.com/?actor.netsuppport)

## Countries

These _countries_ are directly (e.g. origin of attacks) or indirectly (e.g. access by proxy) associated with Netsuppport:

* [US](https://vuldb.com/?country.us)
* [RU](https://vuldb.com/?country.ru)
* [TR](https://vuldb.com/?country.tr)
* ...

There are 14 more country items available. Please use our online service to access the data.

## IOC - Indicator of Compromise

These _indicators of compromise_ (IOC) indicate associated network resources which are known to be part of research and attack activities of Netsuppport.

ID | IP address | Hostname | Campaign | Confidence
-- | ---------- | -------- | -------- | ----------
1 | [179.43.146.90](https://vuldb.com/?ip.179.43.146.90) | hostedby.privatelayer.com | - | High

## TTP - Tactics, Techniques, Procedures

_Tactics, techniques, and procedures_ (TTP) summarize the suspected MITRE ATT&CK techniques used by _Netsuppport_. This data is unique as it uses our predictive model for actor profiling.

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

These _indicators of attack_ (IOA) list the potential fragments used for technical activities like reconnaissance, exploitation, privilege escalation, and exfiltration by Netsuppport. This data is unique as it uses our predictive model for actor profiling.

ID | Type | Indicator | Confidence
-- | ---- | --------- | ----------
1 | File | `//proc/kcore` | Medium
2 | File | `/admin.php/Admin/adminadd.html` | High
3 | File | `/admin/about-us.php` | High
4 | File | `/admin/action/delete-vaccine.php` | High
5 | File | `/Admin/add-student.php` | High
6 | File | `/admin/edit-post.php` | High
7 | File | `/admin/index2.html` | High
8 | File | `/admin/settings/save.php` | High
9 | File | `/admin/userprofile.php` | High
10 | File | `/api/baskets/{name}` | High
11 | File | `/app/index/controller/Common.php` | High
12 | File | `/applications/core/modules/admin/editor/toolbar.php` | High
13 | File | `/Applications/Google\ Drive.app/Contents/MacOS` | High
14 | File | `/applications/nexus/modules/front/store/store.php` | High
15 | File | `/apply.cgi` | Medium
16 | File | `/bitrix/admin/ldap_server_edit.php` | High
17 | File | `/cgi-bin/apkg_mgr.cgi` | High
18 | File | `/cgi-bin/cstecgi.cgi` | High
19 | File | `/cgi-bin/nas_sharing.cgi` | High
20 | File | `/cgi-bin/photocenter_mgr.cgi` | High
21 | File | `/cgi-bin/wlogin.cgi` | High
22 | File | `/classes/Master.php` | High
23 | File | `/classes/Master.php?f=delete_record` | High
24 | File | `/classes/Master.php?f=save_category` | High
25 | File | `/classes/SystemSettings.php?f=update_settings` | High
26 | File | `/classes/Users.php?f=save` | High
27 | File | `/College/admin/teacher.php` | High
28 | File | `/Controls/Generic/EBMK/Handlers/EStatements/DownloadEStatement.ashx` | High
29 | File | `/dcim/rack-roles/` | High
30 | File | `/dtale/chart-data/1` | High
31 | File | `/etc/shadow.sample` | High
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
42 | File | `/h.php/page?ref=addtabs` | High
43 | File | `/image.php` | Medium
44 | File | `/inc/topBarNav.php` | High
45 | File | `/includes/common/require_access_recovery.php` | High
46 | File | `/index.asp` | Medium
47 | ... | ... | ...

There are 406 more IOA items available (file, library, argument, input value, pattern, network port). Please use our online service to access the data.

## References

The following list contains _external sources_ which discuss the actor and the associated activities:

* https://www.zscaler.com/blogs/research/netsupport-rat-installed-fake-update-notices

## Literature

The following _articles_ explain our unique predictive cyber threat intelligence:

* [VulDB Cyber Threat Intelligence Documentation](https://vuldb.com/?kb.cti)
* [Cyber Threat Intelligence - Early Anticipation of Attacks](https://www.scip.ch/en/?labs.20201022)

## License

(c) [1997-2024](https://vuldb.com/?kb.changelog) by [vuldb.com](https://vuldb.com/?kb.about). All data on this page is shared under the license [CC BY-NC-SA 4.0](https://creativecommons.org/licenses/by-nc-sa/4.0/). Questions? Check the [FAQ](https://vuldb.com/?kb.faq), read the [documentation](https://vuldb.com/?kb) or [contact us](https://vuldb.com/?contact)!
