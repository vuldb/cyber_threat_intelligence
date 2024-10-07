# Sednit - Cyber Threat Intelligence

These _indicators_ were reported, collected, and generated during the [VulDB CTI analysis](https://vuldb.com/?kb.cti) of the campaign known as _Sednit_. The _activity monitoring_ correlates data from social media, forums, chat rooms, and darknet markets. It helps to determine associated actors, specific activities, expected intentions, emerging research, and ongoing attacks. Our unique _predictive model_ uses _big data_ to forecast activities and their characteristics.

_Live data_ and more _analysis capabilities_ are available at [https://vuldb.com/?actor](https://vuldb.com/?actor)

## Countries

These _countries_ are directly (e.g. origin of attacks) or indirectly (e.g. access by proxy) associated with Sednit:

* [US](https://vuldb.com/?country.us)
* [RU](https://vuldb.com/?country.ru)
* [GB](https://vuldb.com/?country.gb)
* ...

There are 15 more country items available. Please use our online service to access the data.

## Actors

These _actors_ are associated with Sednit or other actors linked to the campaign.

ID | Actor | Confidence
-- | ----- | ----------
1 | [APT28](https://vuldb.com/?actor.apt28) | High
2 | [Sednit](https://vuldb.com/?actor.sednit) | High

## IOC - Indicator of Compromise

These _indicators of compromise_ (IOC) indicate associated network resources which are known to be part of research and attack activities of Sednit.

ID | IP address | Hostname | Actor | Confidence
-- | ---------- | -------- | ----- | ----------
1 | [5.135.183.154](https://vuldb.com/?ip.5.135.183.154) | ns3290077.ip-5-135-183.eu | [Sednit](https://vuldb.com/?actor.sednit) | High
2 | [31.7.62.103](https://vuldb.com/?ip.31.7.62.103) | - | [Sednit](https://vuldb.com/?actor.sednit) | High
3 | [31.220.43.99](https://vuldb.com/?ip.31.220.43.99) | nl-2.sa-irc.com | [Sednit](https://vuldb.com/?actor.sednit) | High
4 | [46.102.152.127](https://vuldb.com/?ip.46.102.152.127) | mx8.facturation124596.site | [Sednit](https://vuldb.com/?actor.sednit) | High
5 | [46.183.223.227](https://vuldb.com/?ip.46.183.223.227) | mx3.vehiculosycasas.com | [Sednit](https://vuldb.com/?actor.sednit) | High
6 | [69.12.73.174](https://vuldb.com/?ip.69.12.73.174) | 69.12.73.174.static.quadranet.com | [Sednit](https://vuldb.com/?actor.sednit) | High
7 | [80.255.6.5](https://vuldb.com/?ip.80.255.6.5) | - | [Sednit](https://vuldb.com/?actor.sednit) | High
8 | ... | ... | ... | ...

There are 30 more IOC items available. Please use our online service to access the data.

## TTP - Tactics, Techniques, Procedures

_Tactics, techniques, and procedures_ (TTP) summarize the suspected MITRE ATT&CK techniques used within Sednit. This data is unique as it uses our predictive model for actor profiling.

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

These _indicators of attack_ (IOA) list the potential fragments used for technical activities like reconnaissance, exploitation, privilege escalation, and exfiltration during Sednit. This data is unique as it uses our predictive model for actor profiling.

ID | Type | Indicator | Confidence
-- | ---- | --------- | ----------
1 | File | `//proc/kcore` | Medium
2 | File | `/admin/about-us.php` | High
3 | File | `/admin/action/delete-vaccine.php` | High
4 | File | `/admin/article.php` | High
5 | File | `/admin/edit-post.php` | High
6 | File | `/admin/edit.php` | High
7 | File | `/admin/index2.html` | High
8 | File | `/admin/students/view_details.php` | High
9 | File | `/admin/uesrs.php&action=type&userrole=Admin&userid=3` | High
10 | File | `/admin/userprofile.php` | High
11 | File | `/api/baskets/{name}` | High
12 | File | `/app/index/controller/Common.php` | High
13 | File | `/applications/core/modules/admin/editor/toolbar.php` | High
14 | File | `/Applications/Google\ Drive.app/Contents/MacOS` | High
15 | File | `/applications/nexus/modules/front/store/store.php` | High
16 | File | `/apply.cgi` | Medium
17 | File | `/bitrix/admin/ldap_server_edit.php` | High
18 | File | `/cgi-bin/apkg_mgr.cgi` | High
19 | File | `/cgi-bin/cstecgi.cgi` | High
20 | File | `/cgi-bin/nas_sharing.cgi` | High
21 | File | `/cgi-bin/photocenter_mgr.cgi` | High
22 | File | `/cgi-bin/system_mgr.cgi` | High
23 | File | `/cgi-bin/wlogin.cgi` | High
24 | File | `/classes/Master.php` | High
25 | File | `/classes/master.php?f=delete_order` | High
26 | File | `/classes/Master.php?f=delete_record` | High
27 | File | `/classes/Master.php?f=save_category` | High
28 | File | `/classes/SystemSettings.php?f=update_settings` | High
29 | File | `/classes/Users.php?f=save` | High
30 | File | `/College/admin/teacher.php` | High
31 | File | `/Controls/Generic/EBMK/Handlers/EStatements/DownloadEStatement.ashx` | High
32 | File | `/dcim/rack-roles/` | High
33 | File | `/dtale/chart-data/1` | High
34 | File | `/etc/shadow.sample` | High
35 | File | `/fftools/ffmpeg_enc.c` | High
36 | File | `/forms/doLogin` | High
37 | File | `/formSysLog` | Medium
38 | File | `/forum/away.php` | High
39 | File | `/goform/addUserName` | High
40 | File | `/goform/aspForm` | High
41 | File | `/goform/delAd` | High
42 | File | `/goform/SetOnlineDevName` | High
43 | File | `/goform/wifiSSIDset` | High
44 | File | `/gpac/src/bifs/unquantize.c` | High
45 | File | `/h.php/page?ref=addtabs` | High
46 | File | `/h/autoSaveDraft` | High
47 | File | `/image.php` | Medium
48 | File | `/inc/topBarNav.php` | High
49 | File | `/includes/common/require_access_recovery.php` | High
50 | File | `/index.php` | Medium
51 | File | `/index.php?action=editPharmacist` | High
52 | File | `/index.php?app=main&func=passport&action=login` | High
53 | File | `/install/` | Medium
54 | File | `/kelas/data` | Medium
55 | ... | ... | ...

There are 483 more IOA items available (file, library, argument, input value, pattern, network port). Please use our online service to access the data.

## References

The following list contains _external sources_ which discuss the campaign and the associated activities:

* https://github.com/blackorbird/APT_REPORT/blob/master/APT28/history-report-pdf/eset-sednit-part-2.pdf
* https://github.com/blackorbird/APT_REPORT/blob/master/APT28/history-report-pdf/eset-sednit-part3.pdf
* https://github.com/blackorbird/APT_REPORT/blob/master/APT28/history-report-pdf/sednit-update-analysis-zebrocy_.pdf
* https://github.com/eset/malware-ioc/tree/master/quarterly_reports/2020_Q3
* https://www.welivesecurity.com/wp-content/uploads/2016/10/eset-sednit-part-2.pdf

## Literature

The following _articles_ explain our unique predictive cyber threat intelligence:

* [VulDB Cyber Threat Intelligence Documentation](https://vuldb.com/?kb.cti)
* [Cyber Threat Intelligence - Early Anticipation of Attacks](https://www.scip.ch/en/?labs.20201022)

## License

(c) [1997-2024](https://vuldb.com/?kb.changelog) by [vuldb.com](https://vuldb.com/?kb.about). All data on this page is shared under the license [CC BY-NC-SA 4.0](https://creativecommons.org/licenses/by-nc-sa/4.0/). Questions? Check the [FAQ](https://vuldb.com/?kb.faq), read the [documentation](https://vuldb.com/?kb) or [contact us](https://vuldb.com/?contact)!
