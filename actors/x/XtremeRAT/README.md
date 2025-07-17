# XtremeRAT - Cyber Threat Intelligence

These _indicators_ were reported, collected, and generated during the [VulDB CTI analysis](https://vuldb.com/?kb.cti) of the actor known as [XtremeRAT](https://vuldb.com/?actor.xtremerat). The _activity monitoring_ correlates data from social media, forums, chat rooms, and darknet markets. It helps to determine associated actors, specific activities, expected intentions, emerging research, and ongoing attacks. Our unique _predictive model_ uses _big data_ to forecast activities and their characteristics.

_Live data_ and more _analysis capabilities_ are available at [https://vuldb.com/?actor.xtremerat](https://vuldb.com/?actor.xtremerat)

## Countries

These _countries_ are directly (e.g. origin of attacks) or indirectly (e.g. access by proxy) associated with XtremeRAT:

* [US](https://vuldb.com/?country.us)
* [CN](https://vuldb.com/?country.cn)
* [VN](https://vuldb.com/?country.vn)
* ...

There are 4 more country items available. Please use our online service to access the data.

## IOC - Indicator of Compromise

These _indicators of compromise_ (IOC) indicate associated network resources which are known to be part of research and attack activities of XtremeRAT.

ID | IP address | Hostname | Campaign | Confidence
-- | ---------- | -------- | -------- | ----------
1 | [2.81.154.116](https://vuldb.com/?ip.2.81.154.116) | bl20-154-116.dsl.telepac.pt | - | High
2 | [5.79.71.205](https://vuldb.com/?ip.5.79.71.205) | - | - | High
3 | [13.107.21.200](https://vuldb.com/?ip.13.107.21.200) | - | - | High
4 | [20.36.253.92](https://vuldb.com/?ip.20.36.253.92) | - | - | High
5 | [20.72.235.82](https://vuldb.com/?ip.20.72.235.82) | - | - | High
6 | [23.7.178.157](https://vuldb.com/?ip.23.7.178.157) | a23-7-178-157.deploy.static.akamaitechnologies.com | - | High
7 | [23.32.81.118](https://vuldb.com/?ip.23.32.81.118) | a23-32-81-118.deploy.static.akamaitechnologies.com | - | High
8 | [23.62.7.138](https://vuldb.com/?ip.23.62.7.138) | a23-62-7-138.deploy.static.akamaitechnologies.com | - | High
9 | [23.62.230.159](https://vuldb.com/?ip.23.62.230.159) | a23-62-230-159.deploy.static.akamaitechnologies.com | - | High
10 | [23.202.2.105](https://vuldb.com/?ip.23.202.2.105) | a23-202-2-105.deploy.static.akamaitechnologies.com | - | High
11 | [23.202.81.150](https://vuldb.com/?ip.23.202.81.150) | a23-202-81-150.deploy.static.akamaitechnologies.com | - | High
12 | [52.8.126.80](https://vuldb.com/?ip.52.8.126.80) | ec2-52-8-126-80.us-west-1.compute.amazonaws.com | - | Medium
13 | [62.90.21.54](https://vuldb.com/?ip.62.90.21.54) | 62-90-21-54.barak.net.il | - | High
14 | [64.29.151.221](https://vuldb.com/?ip.64.29.151.221) | hostedc40.carrierzone.com | - | High
15 | [65.55.44.109](https://vuldb.com/?ip.65.55.44.109) | - | - | High
16 | ... | ... | ... | ...

There are 61 more IOC items available. Please use our online service to access the data.

## TTP - Tactics, Techniques, Procedures

_Tactics, techniques, and procedures_ (TTP) summarize the suspected MITRE ATT&CK techniques used by _XtremeRAT_. This data is unique as it uses our predictive model for actor profiling.

ID | Technique | Weakness | Description | Confidence
-- | --------- | -------- | ----------- | ----------
1 | T1006 | CWE-21, CWE-22, CWE-24, CWE-35, CWE-36, CWE-40 | Path Traversal | High
2 | T1055 | CWE-74 | Improper Neutralization of Data within XPath Expressions | High
3 | T1059 | CWE-88, CWE-94, CWE-1321 | Argument Injection | High
4 | T1059.007 | CWE-79, CWE-80, CWE-84 | Basic Cross Site Scripting | High
5 | T1068 | CWE-250, CWE-264, CWE-266, CWE-269, CWE-272, CWE-273, CWE-284 | Execution with Unnecessary Privileges | High
6 | T1078.001 | CWE-259 | Use of Hard-coded Password | High
7 | ... | ... | ... | ...

There are 23 more TTP items available. Please use our online service to access the data.

## IOA - Indicator of Attack

These _indicators of attack_ (IOA) list the potential fragments used for technical activities like reconnaissance, exploitation, privilege escalation, and exfiltration by XtremeRAT. This data is unique as it uses our predictive model for actor profiling.

ID | Type | Indicator | Confidence
-- | ---- | --------- | ----------
1 | File | `%PROGRAMDATA%\3CXPhone for Windows\PhoneApp` | High
2 | File | `%PROGRAMDATA%\WrData\PKG` | High
3 | File | `/addcompany.php` | High
4 | File | `/admin-cp/plugin/install` | High
5 | File | `/admin.php/appcenter/local.html?type=addon` | High
6 | File | `/admin/?/login/forgot` | High
7 | File | `/admin/ajax_products_list.php` | High
8 | File | `/admin/applicants/controller.php` | High
9 | File | `/admin/ballot_down.php` | High
10 | File | `/admin/case-status` | High
11 | File | `/admin/category.php` | High
12 | File | `/admin/category/add.do` | High
13 | File | `/admin/change-image.php` | High
14 | File | `/admin/change-password.php` | High
15 | File | `/admin/check_admin.php` | High
16 | File | `/admin/company/index.php` | High
17 | File | `/Admin/createClass.php` | High
18 | File | `/Admin/CustomerReport.php` | High
19 | File | `/admin/departments/manage_department.php` | High
20 | File | `/admin/edit-artist-detail.php?editid=1` | High
21 | File | `/admin/edit.php` | High
22 | File | `/admin/edit_area.php` | High
23 | File | `/admin/edit_role.php` | High
24 | File | `/admin/file/delete.do` | High
25 | File | `/admin/group` | Medium
26 | File | `/admin/indexConfigs/update` | High
27 | File | `/admin/makehtml_freelist_action.php` | High
28 | File | `/admin/newsletter1.php` | High
29 | File | `/admin/product/manage.php` | High
30 | File | `/admin/reports/index.php` | High
31 | File | `/admin/reservation_view.php` | High
32 | File | `/admin/search.php` | High
33 | File | `/admin/uesrs.php&action=display&value=Hide` | High
34 | File | `/admin/updatestudent.php` | High
35 | File | `/admin/user/manage_user.php` | High
36 | File | `/adpweb/wechat/verifyToken/` | High
37 | File | `/ajax.php?action=save_membership` | High
38 | File | `/api/comment/add` | High
39 | File | `/api/mjkj-chat/chat/mng/update/questionCou` | High
40 | File | `/application/index/controller/Databasesource.php` | High
41 | File | `/apps/system/router/upload.go` | High
42 | File | `/auth/userkey/logout.php` | High
43 | File | `/bin/boa` | Medium
44 | File | `/binutils/debug.c` | High
45 | File | `/boafrm/formFilter` | High
46 | File | `/boafrm/formIpQoS` | High
47 | File | `/boafrm/formTmultiAP` | High
48 | File | `/book_edit_do.html` | High
49 | File | `/bsenordering/index.php` | High
50 | File | `/bwdates-reports-details.php` | High
51 | File | `/cgi-bin/cstecgi.cgi` | High
52 | File | `/cgi-bin/discovery.cgi` | High
53 | File | `/cgi-bin/koha/catalogue/search.pl` | High
54 | File | `/cgi-bin/sessions/get-temp-file` | High
55 | File | `/cgi-bin/touchlist_sync.cgi` | High
56 | File | `/chart` | Low
57 | File | `/checkout` | Medium
58 | File | `/classes/Login.php` | High
59 | File | `/classes/Master.php?f=save_brand` | High
60 | File | `/cms/smf/Sources/ManageMembers.php` | High
61 | File | `/contract` | Medium
62 | File | `/dashboard/getData.php` | High
63 | File | `/doorgets/app/requests/user/configurationRequest.php` | High
64 | File | `/download-medical-cards.php` | High
65 | File | `/Employee/edit-profile.php` | High
66 | File | `/extensions/realestate/index.php/properties/list/list-with-sidebar/realties` | High
67 | ... | ... | ...

There are 592 more IOA items available (file, library, argument, input value, pattern, network port). Please use our online service to access the data.

## References

The following list contains _external sources_ which discuss the actor and the associated activities:

* https://blog.talosintelligence.com/2019/07/threat-roundup-0712-0719.html
* https://blog.talosintelligence.com/2019/07/threat-roundup-0719-0726.html
* https://blog.talosintelligence.com/2019/09/threat-roundup-0913-0920.html
* https://blog.talosintelligence.com/2020/05/threat-roundup-0424-0501.html
* https://blog.talosintelligence.com/2022/03/threat-roundup-0225-0304.html
* https://blog.talosintelligence.com/2022/05/threat-roundup-0429-0506.html
* https://blog.talosintelligence.com/2022/08/threat-roundup-0819-0826.html
* https://blog.talosintelligence.com/threat-roundup-0127-0203/
* https://blog.talosintelligence.com/threat-roundup-0407-0414/
* https://blog.talosintelligence.com/threat-roundup-0428-0505/

## Literature

The following _articles_ explain our unique predictive cyber threat intelligence:

* [VulDB Cyber Threat Intelligence Documentation](https://vuldb.com/?kb.cti)
* [Cyber Threat Intelligence - Early Anticipation of Attacks](https://www.scip.ch/en/?labs.20201022)

## License

(c) [1997-2025](https://vuldb.com/?kb.changelog) by [vuldb.com](https://vuldb.com/?kb.about). All data on this page is shared under the license [CC BY-NC-SA 4.0](https://creativecommons.org/licenses/by-nc-sa/4.0/). Questions? Check the [FAQ](https://vuldb.com/?kb.faq), read the [documentation](https://vuldb.com/?kb) or [contact us](https://vuldb.com/?contact)!
