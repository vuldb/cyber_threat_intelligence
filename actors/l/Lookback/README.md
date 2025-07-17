# Lookback - Cyber Threat Intelligence

These _indicators_ were reported, collected, and generated during the [VulDB CTI analysis](https://vuldb.com/?kb.cti) of the actor known as [Lookback](https://vuldb.com/?actor.lookback). The _activity monitoring_ correlates data from social media, forums, chat rooms, and darknet markets. It helps to determine associated actors, specific activities, expected intentions, emerging research, and ongoing attacks. Our unique _predictive model_ uses _big data_ to forecast activities and their characteristics.

_Live data_ and more _analysis capabilities_ are available at [https://vuldb.com/?actor.lookback](https://vuldb.com/?actor.lookback)

## Countries

These _countries_ are directly (e.g. origin of attacks) or indirectly (e.g. access by proxy) associated with Lookback:

* [US](https://vuldb.com/?country.us)
* [CN](https://vuldb.com/?country.cn)
* [VN](https://vuldb.com/?country.vn)
* ...

There are 5 more country items available. Please use our online service to access the data.

## IOC - Indicator of Compromise

These _indicators of compromise_ (IOC) indicate associated network resources which are known to be part of research and attack activities of Lookback.

ID | IP address | Hostname | Campaign | Confidence
-- | ---------- | -------- | -------- | ----------
1 | [79.141.168.137](https://vuldb.com/?ip.79.141.168.137) | nceess.com | - | High
2 | [103.253.41.45](https://vuldb.com/?ip.103.253.41.45) | mail.e-cigs-mart.com | - | High
3 | [127.0.0.1](https://vuldb.com/?ip.127.0.0.1) | localhost | - | High

## TTP - Tactics, Techniques, Procedures

_Tactics, techniques, and procedures_ (TTP) summarize the suspected MITRE ATT&CK techniques used by _Lookback_. This data is unique as it uses our predictive model for actor profiling.

ID | Technique | Weakness | Description | Confidence
-- | --------- | -------- | ----------- | ----------
1 | T1006 | CWE-21, CWE-22, CWE-24, CWE-36, CWE-40 | Path Traversal | High
2 | T1055 | CWE-74 | Improper Neutralization of Data within XPath Expressions | High
3 | T1059 | CWE-88, CWE-94, CWE-1321 | Argument Injection | High
4 | T1059.007 | CWE-79, CWE-80, CWE-84 | Basic Cross Site Scripting | High
5 | T1068 | CWE-264, CWE-266, CWE-269, CWE-273, CWE-284 | Execution with Unnecessary Privileges | High
6 | T1078.001 | CWE-259 | Use of Hard-coded Password | High
7 | ... | ... | ... | ...

There are 23 more TTP items available. Please use our online service to access the data.

## IOA - Indicator of Attack

These _indicators of attack_ (IOA) list the potential fragments used for technical activities like reconnaissance, exploitation, privilege escalation, and exfiltration by Lookback. This data is unique as it uses our predictive model for actor profiling.

ID | Type | Indicator | Confidence
-- | ---- | --------- | ----------
1 | File | `%PROGRAMDATA%\3CXPhone for Windows\PhoneApp` | High
2 | File | `%PROGRAMDATA%\WrData\PKG` | High
3 | File | `/addcompany.php` | High
4 | File | `/admin-cp/plugin/install` | High
5 | File | `/admin.php/appcenter/local.html?type=addon` | High
6 | File | `/admin/?/login/forgot` | High
7 | File | `/admin/admin_user.php` | High
8 | File | `/admin/applicants/controller.php` | High
9 | File | `/admin/case-status` | High
10 | File | `/admin/category.php` | High
11 | File | `/admin/category/add.do` | High
12 | File | `/admin/change-image.php` | High
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
23 | File | `/admin/indexConfigs/update` | High
24 | File | `/admin/makehtml_freelist_action.php` | High
25 | File | `/admin/product/manage.php` | High
26 | File | `/admin/reports/index.php` | High
27 | File | `/admin/reservation_view.php` | High
28 | File | `/admin/search.php` | High
29 | File | `/admin/team_update.php` | High
30 | File | `/admin/updatestudent.php` | High
31 | File | `/admin/user/manage_user.php` | High
32 | File | `/admin/user_save.php` | High
33 | File | `/adpweb/wechat/verifyToken/` | High
34 | File | `/ajax.php?action=login` | High
35 | File | `/ajax.php?action=save_membership` | High
36 | File | `/api/comment/add` | High
37 | File | `/api/mjkj-chat/chat/mng/update/questionCou` | High
38 | File | `/apps/system/router/upload.go` | High
39 | File | `/auth/userkey/logout.php` | High
40 | File | `/bin/boa` | Medium
41 | File | `/boafrm/formFilter` | High
42 | File | `/boafrm/formIpQoS` | High
43 | File | `/boafrm/formReflashClientTbl` | High
44 | File | `/book_edit_do.html` | High
45 | File | `/bsenordering/index.php` | High
46 | File | `/bwdates-reports-details.php` | High
47 | File | `/cgi-bin/cstecgi.cgi` | High
48 | File | `/cgi-bin/cstecgi.cgi?action=login` | High
49 | File | `/cgi-bin/sessions/get-temp-file` | High
50 | File | `/cgi-bin/touchlist_sync.cgi` | High
51 | File | `/chart` | Low
52 | File | `/checkout` | Medium
53 | File | `/classes/Login.php` | High
54 | File | `/cms/smf/Sources/ManageMembers.php` | High
55 | File | `/company/service/increment/add/im` | High
56 | File | `/contract` | Medium
57 | File | `/control/login.php` | High
58 | File | `/currentsetting.htm` | High
59 | File | `/dashboard/getData.php` | High
60 | File | `/doorgets/app/requests/user/configurationRequest.php` | High
61 | File | `/download-medical-cards.php` | High
62 | File | `/Employee/edit-profile.php` | High
63 | File | `/extensions/realestate/index.php/properties/list/list-with-sidebar/realties` | High
64 | File | `/fhconf/umconfig.txt` | High
65 | File | `/film-rating.php` | High
66 | File | `/form2pingv6.cgi` | High
67 | File | `/forum/away.php` | High
68 | File | `/fossasia/open-event-server/blob/development/app/api/helpers/mail.py` | High
69 | File | `/front/admin/tenancyDetail.php` | High
70 | ... | ... | ...

There are 611 more IOA items available (file, library, argument, input value, pattern, network port). Please use our online service to access the data.

## References

The following list contains _external sources_ which discuss the actor and the associated activities:

* https://www.proofpoint.com/us/threat-insight/post/lookback-malware-targets-united-states-utilities-sector-phishing-attacks

## Literature

The following _articles_ explain our unique predictive cyber threat intelligence:

* [VulDB Cyber Threat Intelligence Documentation](https://vuldb.com/?kb.cti)
* [Cyber Threat Intelligence - Early Anticipation of Attacks](https://www.scip.ch/en/?labs.20201022)

## License

(c) [1997-2025](https://vuldb.com/?kb.changelog) by [vuldb.com](https://vuldb.com/?kb.about). All data on this page is shared under the license [CC BY-NC-SA 4.0](https://creativecommons.org/licenses/by-nc-sa/4.0/). Questions? Check the [FAQ](https://vuldb.com/?kb.faq), read the [documentation](https://vuldb.com/?kb) or [contact us](https://vuldb.com/?contact)!
