# AppleJeus - Cyber Threat Intelligence

These _indicators_ were reported, collected, and generated during the [VulDB CTI analysis](https://vuldb.com/?kb.cti) of the campaign known as _AppleJeus_. The _activity monitoring_ correlates data from social media, forums, chat rooms, and darknet markets. It helps to determine associated actors, specific activities, expected intentions, emerging research, and ongoing attacks. Our unique _predictive model_ uses _big data_ to forecast activities and their characteristics.

_Live data_ and more _analysis capabilities_ are available at [https://vuldb.com/?actor](https://vuldb.com/?actor)

## Countries

These _countries_ are directly (e.g. origin of attacks) or indirectly (e.g. access by proxy) associated with AppleJeus:

* [US](https://vuldb.com/?country.us)
* [VN](https://vuldb.com/?country.vn)
* [CN](https://vuldb.com/?country.cn)
* ...

There are 6 more country items available. Please use our online service to access the data.

## Actors

These _actors_ are associated with AppleJeus or other actors linked to the campaign.

ID | Actor | Confidence
-- | ----- | ----------
1 | [Applejeus](https://vuldb.com/?actor.applejeus) | High
2 | [AppleJeus](https://vuldb.com/?actor.applejeus) | High
3 | [DPRK](https://vuldb.com/?actor.dprk) | High
4 | ... | ...

There are 1 more actor items available. Please use our online service to access the data.

## IOC - Indicator of Compromise

These _indicators of compromise_ (IOC) indicate associated network resources which are known to be part of research and attack activities of AppleJeus.

ID | IP address | Hostname | Actor | Confidence
-- | ---------- | -------- | ----- | ----------
1 | [23.254.217.53](https://vuldb.com/?ip.23.254.217.53) | client-23-254-217-53.hostwindsdns.com | [Applejeus](https://vuldb.com/?actor.applejeus) | High
2 | [45.33.2.79](https://vuldb.com/?ip.45.33.2.79) | li956-79.members.linode.com | [Lazarus](https://vuldb.com/?actor.lazarus) | High
3 | [45.33.23.183](https://vuldb.com/?ip.45.33.23.183) | li977-183.members.linode.com | [Lazarus](https://vuldb.com/?actor.lazarus) | High
4 | [45.56.79.23](https://vuldb.com/?ip.45.56.79.23) | li929-23.members.linode.com | [Lazarus](https://vuldb.com/?actor.lazarus) | High
5 | [45.79.19.196](https://vuldb.com/?ip.45.79.19.196) | li1118-196.members.linode.com | [Lazarus](https://vuldb.com/?actor.lazarus) | High
6 | [45.199.63.220](https://vuldb.com/?ip.45.199.63.220) | - | [Lazarus](https://vuldb.com/?actor.lazarus) | High
7 | [80.82.64.91](https://vuldb.com/?ip.80.82.64.91) | - | [AppleJeus](https://vuldb.com/?actor.applejeus) | High
8 | ... | ... | ... | ...

There are 29 more IOC items available. Please use our online service to access the data.

## TTP - Tactics, Techniques, Procedures

_Tactics, techniques, and procedures_ (TTP) summarize the suspected MITRE ATT&CK techniques used within AppleJeus. This data is unique as it uses our predictive model for actor profiling.

ID | Technique | Weakness | Description | Confidence
-- | --------- | -------- | ----------- | ----------
1 | T1006 | CWE-21, CWE-22, CWE-24, CWE-36, CWE-40, CWE-44 | Path Traversal | High
2 | T1055 | CWE-74 | Improper Neutralization of Data within XPath Expressions | High
3 | T1059 | CWE-88, CWE-94 | Argument Injection | High
4 | T1059.007 | CWE-79, CWE-80, CWE-84 | Basic Cross Site Scripting | High
5 | T1068 | CWE-264, CWE-269, CWE-273, CWE-284 | Execution with Unnecessary Privileges | High
6 | T1078.001 | CWE-259 | Use of Hard-coded Password | High
7 | ... | ... | ... | ...

There are 23 more TTP items available. Please use our online service to access the data.

## IOA - Indicator of Attack

These _indicators of attack_ (IOA) list the potential fragments used for technical activities like reconnaissance, exploitation, privilege escalation, and exfiltration during AppleJeus. This data is unique as it uses our predictive model for actor profiling.

ID | Type | Indicator | Confidence
-- | ---- | --------- | ----------
1 | File | `%PROGRAMDATA%\3CXPhone for Windows\PhoneApp` | High
2 | File | `%PROGRAMDATA%\WrData\PKG` | High
3 | File | `/addcompany.php` | High
4 | File | `/admin.php/appcenter/local.html?type=addon` | High
5 | File | `/admin/add-property.php` | High
6 | File | `/admin/admin_editor.php` | High
7 | File | `/admin/admin_user.php` | High
8 | File | `/admin/ad_list.php?action=pass` | High
9 | File | `/admin/booking-bwdates-reports-details.php` | High
10 | File | `/admin/case-status` | High
11 | File | `/admin/category.php` | High
12 | File | `/admin/category/add.do` | High
13 | File | `/admin/change-password.php` | High
14 | File | `/admin/check_admin.php` | High
15 | File | `/admin/company/index.php` | High
16 | File | `/admin/create_product.php` | High
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
29 | File | `/admin/salary_slip.php` | High
30 | File | `/admin/sales/index.php` | High
31 | File | `/admin/search.php` | High
32 | File | `/admin/team_update.php` | High
33 | File | `/admin/updatestudent.php` | High
34 | File | `/admin/user/manage_user.php` | High
35 | File | `/admin/user_save.php` | High
36 | File | `/adpweb/wechat/verifyToken/` | High
37 | File | `/ajax.php?action=login` | High
38 | File | `/ajax.php?action=save_membership` | High
39 | File | `/api/client/editemedia.php` | High
40 | File | `/api/comment/add` | High
41 | File | `/api/Common/uploadFile` | High
42 | File | `/Api/FileUpload.ashx?method=DoUpload` | High
43 | File | `/api/mjkj-chat/chat/mng/update/questionCou` | High
44 | File | `/api/wizard/setsyncpppoecfg` | High
45 | File | `/apps/system/router/upload.go` | High
46 | File | `/auth/userkey/logout.php` | High
47 | File | `/bin/boa` | Medium
48 | File | `/bin/goahead` | Medium
49 | File | `/boafrm/formFilter` | High
50 | File | `/boafrm/formReflashClientTbl` | High
51 | File | `/book_edit_do.html` | High
52 | File | `/bsenordering/index.php` | High
53 | File | `/bwdates-reports-details.php` | High
54 | File | `/cgi-bin/cstecgi.cgi` | High
55 | File | `/cgi-bin/cstecgi.cgi?action=login` | High
56 | File | `/cgi-bin/touchlist_sync.cgi` | High
57 | File | `/checkout` | Medium
58 | File | `/classes/Login.php` | High
59 | File | `/cms/smf/Sources/ManageMembers.php` | High
60 | File | `/company/service/increment/add/im` | High
61 | File | `/confirmbooking.php` | High
62 | File | `/contract` | Medium
63 | File | `/control/login.php` | High
64 | File | `/currentsetting.htm` | High
65 | File | `/Default/Bd` | Medium
66 | File | `/download-medical-cards.php` | High
67 | File | `/Employee/edit-profile.php` | High
68 | ... | ... | ...

There are 597 more IOA items available (file, library, argument, input value, pattern, network port). Please use our online service to access the data.

## References

The following list contains _external sources_ which discuss the campaign and the associated activities:

* https://securelist.com/operation-applejeus-sequel/95596/
* https://us-cert.cisa.gov/ncas/alerts/aa21-048a
* https://us-cert.cisa.gov/ncas/analysis-reports/ar21-048c
* https://www.cyber45.com

## Literature

The following _articles_ explain our unique predictive cyber threat intelligence:

* [VulDB Cyber Threat Intelligence Documentation](https://vuldb.com/?kb.cti)
* [Cyber Threat Intelligence - Early Anticipation of Attacks](https://www.scip.ch/en/?labs.20201022)

## License

(c) [1997-2025](https://vuldb.com/?kb.changelog) by [vuldb.com](https://vuldb.com/?kb.about). All data on this page is shared under the license [CC BY-NC-SA 4.0](https://creativecommons.org/licenses/by-nc-sa/4.0/). Questions? Check the [FAQ](https://vuldb.com/?kb.faq), read the [documentation](https://vuldb.com/?kb) or [contact us](https://vuldb.com/?contact)!
