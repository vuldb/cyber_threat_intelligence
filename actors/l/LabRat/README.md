# LabRat - Cyber Threat Intelligence

These _indicators_ were reported, collected, and generated during the [VulDB CTI analysis](https://vuldb.com/?kb.cti) of the actor known as [LabRat](https://vuldb.com/?actor.labrat). The _activity monitoring_ correlates data from social media, forums, chat rooms, and darknet markets. It helps to determine associated actors, specific activities, expected intentions, emerging research, and ongoing attacks. Our unique _predictive model_ uses _big data_ to forecast activities and their characteristics.

_Live data_ and more _analysis capabilities_ are available at [https://vuldb.com/?actor.labrat](https://vuldb.com/?actor.labrat)

## Countries

These _countries_ are directly (e.g. origin of attacks) or indirectly (e.g. access by proxy) associated with LabRat:

* [VN](https://vuldb.com/?country.vn)

## IOC - Indicator of Compromise

These _indicators of compromise_ (IOC) indicate associated network resources which are known to be part of research and attack activities of LabRat.

ID | IP address | Hostname | Campaign | Confidence
-- | ---------- | -------- | -------- | ----------
1 | [1.234.16.54](https://vuldb.com/?ip.1.234.16.54) | - | - | High
2 | [23.94.204.157](https://vuldb.com/?ip.23.94.204.157) | 23-94-204-157-host.colocrossing.com | - | High
3 | [107.173.154.7](https://vuldb.com/?ip.107.173.154.7) | 107-173-154-7-host.colocrossing.com | - | High
4 | ... | ... | ... | ...

There are 3 more IOC items available. Please use our online service to access the data.

## TTP - Tactics, Techniques, Procedures

_Tactics, techniques, and procedures_ (TTP) summarize the suspected MITRE ATT&CK techniques used by _LabRat_. This data is unique as it uses our predictive model for actor profiling.

ID | Technique | Weakness | Description | Confidence
-- | --------- | -------- | ----------- | ----------
1 | T1006 | CWE-21, CWE-22, CWE-23, CWE-24, CWE-36, CWE-425 | Path Traversal | High
2 | T1055 | CWE-74 | Improper Neutralization of Data within XPath Expressions | High
3 | T1059 | CWE-94, CWE-1321 | Argument Injection | High
4 | T1059.007 | CWE-79, CWE-80 | Basic Cross Site Scripting | High
5 | T1068 | CWE-264, CWE-266, CWE-269, CWE-284 | Execution with Unnecessary Privileges | High
6 | ... | ... | ... | ...

There are 20 more TTP items available. Please use our online service to access the data.

## IOA - Indicator of Attack

These _indicators of attack_ (IOA) list the potential fragments used for technical activities like reconnaissance, exploitation, privilege escalation, and exfiltration by LabRat. This data is unique as it uses our predictive model for actor profiling.

ID | Type | Indicator | Confidence
-- | ---- | --------- | ----------
1 | File | `%PROGRAMDATA%\checkmk\agent\local` | High
2 | File | `/accounts_con/register_account` | High
3 | File | `/admin/action/edit_chicken.php` | High
4 | File | `/admin/add-new.php` | High
5 | File | `/admin/addgiving.php` | High
6 | File | `/admin/addTithes.php` | High
7 | File | `/admin/add_trainers.php` | High
8 | File | `/admin/admin-profile.php` | High
9 | File | `/admin/admin_addnew_product.php` | High
10 | File | `/admin/all-applications.php` | High
11 | File | `/admin/appointment.php` | High
12 | File | `/admin/blood/update/B+.php` | High
13 | File | `/admin/blood/update/o-.php` | High
14 | File | `/admin/bwdates-report-details.php` | High
15 | File | `/admin/bwdates-reports-details.php` | High
16 | File | `/admin/casedetails.php` | High
17 | File | `/admin/courses/view_course.php` | High
18 | File | `/admin/login.php` | High
19 | File | `/Admin/login.php` | High
20 | File | `/admin/manage-scdetails.php` | High
21 | File | `/admin/manage_academic.php` | High
22 | File | `/admin/menu_save.php` | High
23 | File | `/admin/modal_add_product.php` | High
24 | File | `/Admin/registration.php` | High
25 | File | `/admin/reminders/manage_reminder.php` | High
26 | File | `/admin/reports.php` | High
27 | File | `/admin/search-invoices.php` | High
28 | File | `/admin/search-vehicle.php` | High
29 | File | `/admin/service/stop/` | High
30 | File | `/admin/setup.cgi` | High
31 | File | `/admin/update-clients.php` | High
32 | File | `/admin/update_s6.php` | High
33 | File | `/admin/user/manage_user.php` | High
34 | File | `/adminPage/www/addOver` | High
35 | File | `/admin_class.php` | High
36 | File | `/admin_ping.htm` | High
37 | File | `/adplanet/PlanetUser` | High
38 | File | `/ajax.php?action=read_msg` | High
39 | File | `/ajax.php?action=save_establishment` | High
40 | File | `/api/` | Low
41 | File | `/api/authentication/login` | High
42 | File | `/api/contents` | High
43 | File | `/api/v1/attack` | High
44 | File | `/app/uploading/upload-mp3.php` | High
45 | File | `/appinfo/save` | High
46 | File | `/application/controller/Transaki.php` | High
47 | File | `/application/controllers/Users.php` | High
48 | File | `/application/index/controller/Datament.php` | High
49 | File | `/application/index/controller/Screen.php` | High
50 | File | `/application/models/ApplicationDataObject.class.php` | High
51 | File | `/application/pay/controller/Api.php` | High
52 | File | `/bin/boa` | Medium
53 | File | `/bin/httpd` | Medium
54 | File | `/blog` | Low
55 | File | `/Blood/A-.php` | High
56 | File | `/boafrm/formPortFw` | High
57 | File | `/boafrm/formSysLog` | High
58 | File | `/book` | Low
59 | File | `/book-services.php` | High
60 | File | `/bwdates-reports-details.php` | High
61 | File | `/cgi-bin/cstecgi.cgi` | High
62 | File | `/cgi-bin/nas_sharing.cgi` | High
63 | File | `/cgi-bin/touchlist_sync.cgi` | High
64 | File | `/chaincity/user/ticket/create` | High
65 | File | `/claire_blake` | High
66 | File | `/classes/Master.php` | High
67 | File | `/classes/Master.php?f=delete_category` | High
68 | File | `/classes/Master.php?f=save_brand` | High
69 | File | `/com/esafenet/servlet/client/CDGRenewApplicationService.java` | High
70 | File | `/com/esafenet/servlet/policy/HookWhiteListService.java` | High
71 | File | `/com/esafenet/servlet/user/ReUserOrganiseService.java` | High
72 | File | `/config,admin.jsp` | High
73 | File | `/config/myfield/test.php` | High
74 | File | `/controllers/control.php` | High
75 | File | `/Default/Bd` | Medium
76 | File | `/deletebird.php` | High
77 | File | `/department_viewmore.php` | High
78 | File | `/designer/add/layout` | High
79 | File | `/detail.php` | Medium
80 | File | `/details.php` | Medium
81 | File | `/dev/cpu/*/msr` | High
82 | File | `/dws/api/` | Medium
83 | File | `/easy-team-manager/inc/easy_team_manager_desc_edit.php` | High
84 | File | `/ecommerce/support_ticket` | High
85 | ... | ... | ...

There are 747 more IOA items available (file, library, argument, input value, pattern, network port). Please use our online service to access the data.

## References

The following list contains _external sources_ which discuss the actor and the associated activities:

* https://sysdig.com/blog/labrat-cryptojacking-proxyjacking-campaign/

## Literature

The following _articles_ explain our unique predictive cyber threat intelligence:

* [VulDB Cyber Threat Intelligence Documentation](https://vuldb.com/?kb.cti)
* [Cyber Threat Intelligence - Early Anticipation of Attacks](https://www.scip.ch/en/?labs.20201022)

## License

(c) [1997-2025](https://vuldb.com/?kb.changelog) by [vuldb.com](https://vuldb.com/?kb.about). All data on this page is shared under the license [CC BY-NC-SA 4.0](https://creativecommons.org/licenses/by-nc-sa/4.0/). Questions? Check the [FAQ](https://vuldb.com/?kb.faq), read the [documentation](https://vuldb.com/?kb) or [contact us](https://vuldb.com/?contact)!
