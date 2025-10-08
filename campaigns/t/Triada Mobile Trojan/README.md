# Triada Mobile Trojan - Cyber Threat Intelligence

These _indicators_ were reported, collected, and generated during the [VulDB CTI analysis](https://vuldb.com/?kb.cti) of the campaign known as _Triada Mobile Trojan_. The _activity monitoring_ correlates data from social media, forums, chat rooms, and darknet markets. It helps to determine associated actors, specific activities, expected intentions, emerging research, and ongoing attacks. Our unique _predictive model_ uses _big data_ to forecast activities and their characteristics.

_Live data_ and more _analysis capabilities_ are available at [https://vuldb.com/?actor](https://vuldb.com/?actor)

## Countries

These _countries_ are directly (e.g. origin of attacks) or indirectly (e.g. access by proxy) associated with Triada Mobile Trojan:

* [IT](https://vuldb.com/?country.it)
* [PT](https://vuldb.com/?country.pt)
* [DE](https://vuldb.com/?country.de)
* ...

There are 8 more country items available. Please use our online service to access the data.

## Actors

These _actors_ are associated with Triada Mobile Trojan or other actors linked to the campaign.

ID | Actor | Confidence
-- | ----- | ----------
1 | [Unknown](https://vuldb.com/?actor.unknown) | High

## IOC - Indicator of Compromise

These _indicators of compromise_ (IOC) indicate associated network resources which are known to be part of research and attack activities of Triada Mobile Trojan.

ID | IP address | Hostname | Actor | Confidence
-- | ---------- | -------- | ----- | ----------
1 | [8.219.123.139](https://vuldb.com/?ip.8.219.123.139) | - | [Unknown](https://vuldb.com/?actor.unknown) | High
2 | [8.219.196.124](https://vuldb.com/?ip.8.219.196.124) | - | [Unknown](https://vuldb.com/?actor.unknown) | High
3 | [8.222.194.254](https://vuldb.com/?ip.8.222.194.254) | - | [Unknown](https://vuldb.com/?actor.unknown) | High
4 | ... | ... | ... | ...

There are 12 more IOC items available. Please use our online service to access the data.

## TTP - Tactics, Techniques, Procedures

_Tactics, techniques, and procedures_ (TTP) summarize the suspected MITRE ATT&CK techniques used within Triada Mobile Trojan. This data is unique as it uses our predictive model for actor profiling.

ID | Technique | Weakness | Description | Confidence
-- | --------- | -------- | ----------- | ----------
1 | T1006 | CWE-22, CWE-24, CWE-25, CWE-425 | Path Traversal | High
2 | T1040 | CWE-319 | Authentication Bypass by Capture-replay | High
3 | T1055 | CWE-74 | Improper Neutralization of Data within XPath Expressions | High
4 | T1059 | CWE-88, CWE-94, CWE-1321 | Argument Injection | High
5 | T1059.007 | CWE-79, CWE-80 | Basic Cross Site Scripting | High
6 | T1068 | CWE-250, CWE-264, CWE-269, CWE-271, CWE-284 | Execution with Unnecessary Privileges | High
7 | ... | ... | ... | ...

There are 23 more TTP items available. Please use our online service to access the data.

## IOA - Indicator of Attack

These _indicators of attack_ (IOA) list the potential fragments used for technical activities like reconnaissance, exploitation, privilege escalation, and exfiltration during Triada Mobile Trojan. This data is unique as it uses our predictive model for actor profiling.

ID | Type | Indicator | Confidence
-- | ---- | --------- | ----------
1 | File | `/admin` | Low
2 | File | `/admin/` | Low
3 | File | `/admin/aboutus.php` | High
4 | File | `/admin/admin-profile.php` | High
5 | File | `/admin/admin_login_process.php` | High
6 | File | `/admin/api/admin/articles/` | High
7 | File | `/admin/applicants/index.php` | High
8 | File | `/admin/article/article-edit-run.php` | High
9 | File | `/admin/booking-bwdates-reports-details.php` | High
10 | File | `/admin/booking-search.php` | High
11 | File | `/admin/company/controller.php` | High
12 | File | `/admin/configure.php` | High
13 | File | `/admin/contactus.php` | High
14 | File | `/admin/edit-services.php` | High
15 | File | `/admin/employee/controller.php` | High
16 | File | `/admin/employee/index.php` | High
17 | File | `/admin/file_manage_control.php` | High
18 | File | `/admin/index.php` | High
19 | File | `/admin/info_deal.php` | High
20 | File | `/admin/manage-pages.php` | High
21 | File | `/admin/regester.php` | High
22 | File | `/admin/search.php` | High
23 | File | `/admin/sign/out` | High
24 | File | `/admin/students.php` | High
25 | File | `/admin/update-clients.php` | High
26 | File | `/admin/user/index.php` | High
27 | File | `/admin/users_add.php` | High
28 | File | `/admin/vote_edit.php` | High
29 | File | `/adminpanel/admin/query/deleteExamExe.php` | High
30 | File | `/adminpanel/admin/query/loginExe.php` | High
31 | File | `/adplanet/PlanetCommentList` | High
32 | File | `/adplanet/PlanetUser` | High
33 | File | `/api/es/admin/v3/security/user/1` | High
34 | File | `/api/log/killJob` | High
35 | File | `/app/api/controller/caiji.php` | High
36 | File | `/app/api/controller/default/File.php` | High
37 | File | `/app/api/controller/default/Sqlite.php` | High
38 | File | `/apps/reg_go.php` | High
39 | File | `/boaform/device_reset.cgi` | High
40 | File | `/boafrm/formMapDelDevice` | High
41 | File | `/bsms_ci/index.php/user/edit_user/` | High
42 | File | `/building/backmgr/urlpage/mobileurl/configfile/jx2_config.ini` | High
43 | File | `/buspassms/download-pass.php` | High
44 | File | `/cart.php` | Medium
45 | File | `/cgi-bin/cstecgi.cgi` | High
46 | File | `/cgi-bin/login.cgi` | High
47 | File | `/cgi-bin/nightled.cgi` | High
48 | File | `/cgi-bin/supervisor/adcommand.cgi` | High
49 | File | `/cgi-bin/supervisor/PwdGrp.cgi` | High
50 | File | `/claire_blake` | High
51 | File | `/classes/Master.php?f=delete_item` | High
52 | File | `/classes/Master.php?f=save_inquiry` | High
53 | File | `/classes/Master.php?f=save_sub_category` | High
54 | File | `/clientLogin` | Medium
55 | File | `/collection/all` | High
56 | File | `/dashboard?controller=UserCollection::createUser` | High
57 | File | `/data/0/admin.txt` | High
58 | File | `/deletefile.php` | High
59 | File | `/Device/Device/GetDeviceInfoList?deviceCode=&searchField=&deviceState=` | High
60 | File | `/diagnostic/login.php` | High
61 | File | `/DocSystem/Repos/getReposAllUsers.do` | High
62 | File | `/Duty/AjaxHandle/UpLoadFloodPlanFile.ashx` | High
63 | File | `/Duty/AjaxHandle/UploadFloodPlanFileUpdate.ashx` | High
64 | File | `/edit-task.php` | High
65 | ... | ... | ...

There are 572 more IOA items available (file, library, argument, input value, pattern, network port). Please use our online service to access the data.

## References

The following list contains _external sources_ which discuss the campaign and the associated activities:

* https://darktrace.com/blog/triaging-triada-understanding-an-advanced-mobile-trojan-and-how-it-targets-communication-and-banking-applications

## Literature

The following _articles_ explain our unique predictive cyber threat intelligence:

* [VulDB Cyber Threat Intelligence Documentation](https://vuldb.com/?kb.cti)
* [Cyber Threat Intelligence - Early Anticipation of Attacks](https://www.scip.ch/en/?labs.20201022)

## License

(c) [1997-2025](https://vuldb.com/?kb.changelog) by [vuldb.com](https://vuldb.com/?kb.about). All data on this page is shared under the license [CC BY-NC-SA 4.0](https://creativecommons.org/licenses/by-nc-sa/4.0/). Questions? Check the [FAQ](https://vuldb.com/?kb.faq), read the [documentation](https://vuldb.com/?kb) or [contact us](https://vuldb.com/?contact)!
