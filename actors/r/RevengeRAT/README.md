# RevengeRAT - Cyber Threat Intelligence

These _indicators_ were reported, collected, and generated during the [VulDB CTI analysis](https://vuldb.com/?kb.cti) of the actor known as [RevengeRAT](https://vuldb.com/?actor.revengerat). The _activity monitoring_ correlates data from social media, forums, chat rooms, and darknet markets. It helps to determine associated actors, specific activities, expected intentions, emerging research, and ongoing attacks. Our unique _predictive model_ uses _big data_ to forecast activities and their characteristics.

_Live data_ and more _analysis capabilities_ are available at [https://vuldb.com/?actor.revengerat](https://vuldb.com/?actor.revengerat)

## Countries

These _countries_ are directly (e.g. origin of attacks) or indirectly (e.g. access by proxy) associated with RevengeRAT:

* [US](https://vuldb.com/?country.us)
* [VN](https://vuldb.com/?country.vn)
* [CN](https://vuldb.com/?country.cn)
* ...

There are 6 more country items available. Please use our online service to access the data.

## IOC - Indicator of Compromise

These _indicators of compromise_ (IOC) indicate associated network resources which are known to be part of research and attack activities of RevengeRAT.

ID | IP address | Hostname | Campaign | Confidence
-- | ---------- | -------- | -------- | ----------
1 | [6.43.51.17](https://vuldb.com/?ip.6.43.51.17) | - | - | High
2 | [10.0.2.15](https://vuldb.com/?ip.10.0.2.15) | - | - | High
3 | [38.132.101.45](https://vuldb.com/?ip.38.132.101.45) | - | - | High
4 | [45.147.230.231](https://vuldb.com/?ip.45.147.230.231) | - | - | High
5 | ... | ... | ... | ...

There are 14 more IOC items available. Please use our online service to access the data.

## TTP - Tactics, Techniques, Procedures

_Tactics, techniques, and procedures_ (TTP) summarize the suspected MITRE ATT&CK techniques used by _RevengeRAT_. This data is unique as it uses our predictive model for actor profiling.

ID | Technique | Weakness | Description | Confidence
-- | --------- | -------- | ----------- | ----------
1 | T1006 | CWE-21, CWE-22, CWE-24, CWE-36, CWE-40 | Path Traversal | High
2 | T1055 | CWE-74 | Improper Neutralization of Data within XPath Expressions | High
3 | T1059 | CWE-88, CWE-94 | Argument Injection | High
4 | T1059.007 | CWE-79, CWE-80, CWE-84 | Basic Cross Site Scripting | High
5 | T1068 | CWE-264, CWE-269, CWE-273, CWE-284 | Execution with Unnecessary Privileges | High
6 | T1078.001 | CWE-259 | Use of Hard-coded Password | High
7 | ... | ... | ... | ...

There are 22 more TTP items available. Please use our online service to access the data.

## IOA - Indicator of Attack

These _indicators of attack_ (IOA) list the potential fragments used for technical activities like reconnaissance, exploitation, privilege escalation, and exfiltration by RevengeRAT. This data is unique as it uses our predictive model for actor profiling.

ID | Type | Indicator | Confidence
-- | ---- | --------- | ----------
1 | File | `%PROGRAMDATA%\3CXPhone for Windows\PhoneApp` | High
2 | File | `%PROGRAMDATA%\WrData\PKG` | High
3 | File | `/addcompany.php` | High
4 | File | `/admin-cp/plugin/install` | High
5 | File | `/admin.php/appcenter/local.html?type=addon` | High
6 | File | `/admin/?/login/forgot` | High
7 | File | `/admin/admin_user.php` | High
8 | File | `/admin/ad_list.php?action=pass` | High
9 | File | `/admin/booking-bwdates-reports-details.php` | High
10 | File | `/admin/case-status` | High
11 | File | `/admin/category.php` | High
12 | File | `/admin/category/add.do` | High
13 | File | `/admin/change-password.php` | High
14 | File | `/admin/check_admin.php` | High
15 | File | `/admin/company/index.php` | High
16 | File | `/Admin/createClass.php` | High
17 | File | `/Admin/CustomerReport.php` | High
18 | File | `/admin/edit-artist-detail.php?editid=1` | High
19 | File | `/admin/edit_area.php` | High
20 | File | `/admin/edit_role.php` | High
21 | File | `/admin/file/delete.do` | High
22 | File | `/admin/group` | Medium
23 | File | `/admin/index.php` | High
24 | File | `/admin/indexConfigs/update` | High
25 | File | `/admin/makehtml_freelist_action.php` | High
26 | File | `/admin/reports/index.php` | High
27 | File | `/admin/request-received-bydonar.php` | High
28 | File | `/admin/reservation_view.php` | High
29 | File | `/admin/sales/index.php` | High
30 | File | `/admin/search.php` | High
31 | File | `/admin/team_update.php` | High
32 | File | `/admin/updatestudent.php` | High
33 | File | `/admin/user/manage_user.php` | High
34 | File | `/admin/user_save.php` | High
35 | File | `/adpweb/wechat/verifyToken/` | High
36 | File | `/ajax.php?action=login` | High
37 | File | `/ajax.php?action=save_membership` | High
38 | File | `/api/comment/add` | High
39 | File | `/Api/FileUpload.ashx?method=DoUpload` | High
40 | File | `/api/mjkj-chat/chat/mng/update/questionCou` | High
41 | File | `/api/wizard/setsyncpppoecfg` | High
42 | File | `/apps/system/router/upload.go` | High
43 | File | `/auth/userkey/logout.php` | High
44 | File | `/bin/boa` | Medium
45 | File | `/boafrm/formFilter` | High
46 | File | `/boafrm/formIpQoS` | High
47 | File | `/boafrm/formReflashClientTbl` | High
48 | File | `/book_edit_do.html` | High
49 | File | `/bsenordering/index.php` | High
50 | File | `/bwdates-reports-details.php` | High
51 | File | `/cgi-bin/cstecgi.cgi` | High
52 | File | `/cgi-bin/cstecgi.cgi?action=login` | High
53 | File | `/cgi-bin/sessions/get-temp-file` | High
54 | File | `/cgi-bin/touchlist_sync.cgi` | High
55 | File | `/checkout` | Medium
56 | File | `/classes/Login.php` | High
57 | File | `/cms/smf/Sources/ManageMembers.php` | High
58 | File | `/company/service/increment/add/im` | High
59 | File | `/confirmbooking.php` | High
60 | File | `/contract` | Medium
61 | File | `/control/login.php` | High
62 | File | `/currentsetting.htm` | High
63 | File | `/dashboard/getData.php` | High
64 | File | `/Default/Bd` | Medium
65 | File | `/download-medical-cards.php` | High
66 | File | `/Employee/edit-profile.php` | High
67 | File | `/extensions/realestate/index.php/properties/list/list-with-sidebar/realties` | High
68 | File | `/film-rating.php` | High
69 | File | `/fladmin/user_recoverpwd.php` | High
70 | File | `/form2pingv6.cgi` | High
71 | ... | ... | ...

There are 619 more IOA items available (file, library, argument, input value, pattern, network port). Please use our online service to access the data.

## References

The following list contains _external sources_ which discuss the actor and the associated activities:

* https://1275.ru/ioc/149/revengerat-iocs/
* https://blog.talosintelligence.com/2019/07/threat-roundup-0628-0705.html
* https://blog.talosintelligence.com/2019/08/rat-ratatouille-revrat-orcus.html
* https://blog.talosintelligence.com/threat-roundup-0616-0623-2/
* https://www.fortinet.com/blog/threat-research/malware-analysis-revenge-rat-sample.html
* https://www.proofpoint.com/us/blog/threat-insight/reservations-requested-ta558-targets-hospitality-and-travel

## Literature

The following _articles_ explain our unique predictive cyber threat intelligence:

* [VulDB Cyber Threat Intelligence Documentation](https://vuldb.com/?kb.cti)
* [Cyber Threat Intelligence - Early Anticipation of Attacks](https://www.scip.ch/en/?labs.20201022)

## License

(c) [1997-2025](https://vuldb.com/?kb.changelog) by [vuldb.com](https://vuldb.com/?kb.about). All data on this page is shared under the license [CC BY-NC-SA 4.0](https://creativecommons.org/licenses/by-nc-sa/4.0/). Questions? Check the [FAQ](https://vuldb.com/?kb.faq), read the [documentation](https://vuldb.com/?kb) or [contact us](https://vuldb.com/?contact)!
