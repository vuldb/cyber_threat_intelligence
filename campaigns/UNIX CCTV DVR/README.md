# UNIX CCTV DVR - Cyber Threat Intelligence

These _indicators_ were reported, collected, and generated during the [VulDB CTI analysis](https://vuldb.com/?kb.cti) of the campaign known as _UNIX CCTV DVR_. The _activity monitoring_ correlates data from social media, forums, chat rooms, and darknet markets. It helps to determine associated actors, specific activities, expected intentions, emerging research, and ongoing attacks. Our unique _predictive model_ uses _big data_ to forecast activities and their characteristics.

_Live data_ and more _analysis capabilities_ are available at [https://vuldb.com/?actor](https://vuldb.com/?actor)

## Countries

These _countries_ are directly (e.g. origin of attacks) or indirectly (e.g. access by proxy) associated with UNIX CCTV DVR:

* [US](https://vuldb.com/?country.us)
* [LU](https://vuldb.com/?country.lu)
* [CN](https://vuldb.com/?country.cn)
* ...

There are 21 more country items available. Please use our online service to access the data.

## Actors

These _actors_ are associated with UNIX CCTV DVR or other actors linked to the campaign.

ID | Actor | Confidence
-- | ----- | ----------
1 | [Moobot](https://vuldb.com/?actor.moobot) | High

## IOC - Indicator of Compromise

These _indicators of compromise_ (IOC) indicate associated network resources which are known to be part of research and attack activities of UNIX CCTV DVR.

ID | IP address | Hostname | Actor | Confidence
-- | ---------- | -------- | ----- | ----------
1 | [89.248.174.165](https://vuldb.com/?ip.89.248.174.165) | - | [Moobot](https://vuldb.com/?actor.moobot) | High
2 | [89.248.174.166](https://vuldb.com/?ip.89.248.174.166) | - | [Moobot](https://vuldb.com/?actor.moobot) | High
3 | [89.248.174.203](https://vuldb.com/?ip.89.248.174.203) | no-reverse-dns-configured.com | [Moobot](https://vuldb.com/?actor.moobot) | High
4 | [92.223.73.54](https://vuldb.com/?ip.92.223.73.54) | james050721.example.com | [Moobot](https://vuldb.com/?actor.moobot) | High
5 | ... | ... | ... | ...

There are 16 more IOC items available. Please use our online service to access the data.

## TTP - Tactics, Techniques, Procedures

_Tactics, techniques, and procedures_ (TTP) summarize the suspected MITRE ATT&CK techniques used within UNIX CCTV DVR. This data is unique as it uses our predictive model for actor profiling.

ID | Technique | Weakness | Description | Confidence
-- | --------- | -------- | ----------- | ----------
1 | T1006 | CWE-21, CWE-22, CWE-23, CWE-24 | Pathname Traversal | High
2 | T1040 | CWE-319 | Authentication Bypass by Capture-replay | High
3 | T1055 | CWE-74 | Injection | High
4 | T1059 | CWE-88, CWE-94 | Cross Site Scripting | High
5 | T1059.007 | CWE-79, CWE-80 | Cross Site Scripting | High
6 | T1068 | CWE-250, CWE-264, CWE-269, CWE-284 | J2EE Misconfiguration: Weak Access Permissions for EJB Methods | High
7 | ... | ... | ... | ...

There are 22 more TTP items available. Please use our online service to access the data.

## IOA - Indicator of Attack

These _indicators of attack_ (IOA) list the potential fragments used for technical activities like reconnaissance, exploitation, privilege escalation, and exfiltration during UNIX CCTV DVR. This data is unique as it uses our predictive model for actor profiling.

ID | Type | Indicator | Confidence
-- | ---- | --------- | ----------
1 | File | `/admin.php/singer/admin/lists/zhuan` | High
2 | File | `/admin.php/User/level_sort` | High
3 | File | `/admin/cloud.php` | High
4 | File | `/admin/login.php` | High
5 | File | `/admin/maintenance/view_designation.php` | High
6 | File | `/admin/siteoptions.php&action=displaygoal&value=1&roleid=1` | High
7 | File | `/admin/user/manage_user.php` | High
8 | File | `/blog/edit` | Medium
9 | File | `/cgi-bin/uploadWeiXinPic` | High
10 | File | `/cgi-bin/wlogin.cgi` | High
11 | File | `/classes/Master.php?f=delete_category` | High
12 | File | `/core/admin/categories.php` | High
13 | File | `/coreframe/app/order/admin/card.php` | High
14 | File | `/dms/admin/reports/daily_collection_report.php` | High
15 | File | `/eshop/products/json/aouCustomerAdresse` | High
16 | File | `/etc/config/cameo` | High
17 | File | `/extensionsinstruction` | High
18 | File | `/food/admin/all_users.php` | High
19 | File | `/goform/PowerSaveSet` | High
20 | File | `/goform/SetClientState` | High
21 | File | `/goform/SetFirewallCfg` | High
22 | File | `/goform/setWorkmode` | High
23 | File | `/goform/wizard_end` | High
24 | File | `/goods/getGoodsListByConditions/` | High
25 | File | `/index.php` | Medium
26 | File | `/isms/classes/Users.php` | High
27 | File | `/lists/index.php` | High
28 | File | `/member/index/login.html` | High
29 | File | `/members/view_member.php` | High
30 | File | `/messageboard/view.php` | High
31 | File | `/moddable/xs/sources/xsScript.c` | High
32 | File | `/moddable/xs/sources/xsSymbol.c` | High
33 | File | `/modules/projects/vw_files.php` | High
34 | File | `/nova/bin/lcdstat` | High
35 | File | `/ofrs/admin/?page=teams/view_team` | High
36 | File | `/ordering/index.php?q=category` | High
37 | File | `/owa/auth/logon.aspx` | High
38 | File | `/picturesPreview` | High
39 | File | `/rest/api/1.0/issues/{id}/ActionsAndOperations` | High
40 | File | `/rest/api/2/user/picker` | High
41 | File | `/secure/QueryComponent!Default.jspa` | High
42 | File | `/simple_chat_bot/classes/Master.php?f=delete_response` | High
43 | File | `/SiteServer/Ajax/ajaxOtherService.aspx` | High
44 | File | `/sns/classes/Master.php?f=delete_img` | High
45 | File | `/Source/C++/Core/Ap4Array.h` | High
46 | File | `/src/njs_vmcode.c` | High
47 | File | `/SSOPOST/metaAlias/%realm%/idpv2` | High
48 | File | `/syscmd.asp` | Medium
49 | ... | ... | ...

There are 427 more IOA items available (file, library, argument, input value, pattern, network port). Please use our online service to access the data.

## References

The following list contains _external sources_ which discuss the campaign and the associated activities:

* https://blog.netlab.360.com/moobot-0day-unixcctv-dvr-en/

## Literature

The following _articles_ explain our unique predictive cyber threat intelligence:

* [VulDB Cyber Threat Intelligence Documentation](https://vuldb.com/?kb.cti)
* [Cyber Threat Intelligence - Early Anticipation of Attacks](https://www.scip.ch/en/?labs.20201022)

## License

(c) [1997-2023](https://vuldb.com/?kb.changelog) by [vuldb.com](https://vuldb.com/?kb.about). All data on this page is shared under the license [CC BY-NC-SA 4.0](https://creativecommons.org/licenses/by-nc-sa/4.0/). Questions? Check the [FAQ](https://vuldb.com/?kb.faq), read the [documentation](https://vuldb.com/?kb) or [contact us](https://vuldb.com/?contact)!
