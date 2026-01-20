# P2Pinfect - Cyber Threat Intelligence

These _indicators_ were reported, collected, and generated during the [VulDB CTI analysis](https://vuldb.com/?kb.cti) of the actor known as [P2Pinfect](https://vuldb.com/?actor.p2pinfect). The _activity monitoring_ correlates data from social media, forums, chat rooms, and darknet markets. It helps to determine associated actors, specific activities, expected intentions, emerging research, and ongoing attacks. Our unique _predictive model_ uses _big data_ to forecast activities and their characteristics.

_Live data_ and more _analysis capabilities_ are available at [https://vuldb.com/?actor.p2pinfect](https://vuldb.com/?actor.p2pinfect)

## Countries

These _countries_ are directly (e.g. origin of attacks) or indirectly (e.g. access by proxy) associated with P2Pinfect:

* [CN](https://vuldb.com/?country.cn)
* [US](https://vuldb.com/?country.us)

## IOC - Indicator of Compromise

These _indicators of compromise_ (IOC) indicate associated network resources which are known to be part of research and attack activities of P2Pinfect.

ID | IP address | Hostname | Campaign | Confidence
-- | ---------- | -------- | -------- | ----------
1 | [8.209.252.153](https://vuldb.com/?ip.8.209.252.153) | - | - | High
2 | [8.210.11.81](https://vuldb.com/?ip.8.210.11.81) | - | - | High
3 | [8.210.122.125](https://vuldb.com/?ip.8.210.122.125) | - | - | High
4 | [8.217.21.175](https://vuldb.com/?ip.8.217.21.175) | - | - | High
5 | [8.218.125.202](https://vuldb.com/?ip.8.218.125.202) | - | - | High
6 | ... | ... | ... | ...

There are 20 more IOC items available. Please use our online service to access the data.

## TTP - Tactics, Techniques, Procedures

_Tactics, techniques, and procedures_ (TTP) summarize the suspected MITRE ATT&CK techniques used by _P2Pinfect_. This data is unique as it uses our predictive model for actor profiling.

ID | Technique | Weakness | Description | Confidence
-- | --------- | -------- | ----------- | ----------
1 | T1006 | CWE-21, CWE-22, CWE-24, CWE-25, CWE-35 | Path Traversal | High
2 | T1040 | CWE-319 | Authentication Bypass by Capture-replay | High
3 | T1055 | CWE-74 | Improper Neutralization of Data within XPath Expressions | High
4 | T1059 | CWE-94, CWE-1321 | Argument Injection | High
5 | T1059.007 | CWE-79, CWE-80, CWE-84 | Basic Cross Site Scripting | High
6 | T1068 | CWE-264, CWE-267, CWE-269, CWE-284 | Execution with Unnecessary Privileges | High
7 | ... | ... | ... | ...

There are 24 more TTP items available. Please use our online service to access the data.

## IOA - Indicator of Attack

These _indicators of attack_ (IOA) list the potential fragments used for technical activities like reconnaissance, exploitation, privilege escalation, and exfiltration by P2Pinfect. This data is unique as it uses our predictive model for actor profiling.

ID | Type | Indicator | Confidence
-- | ---- | --------- | ----------
1 | File | `/?route=extension/live_search/module/live_search.searchresults` | High
2 | File | `/add-phlebotomist.php` | High
3 | File | `/addpayment.php` | High
4 | File | `/add_patient.php` | High
5 | File | `/admin-profile.php` | High
6 | File | `/admin/add-animals.php` | High
7 | File | `/admin/add-class.php` | High
8 | File | `/admin/add-teacher.php` | High
9 | File | `/admin/add_ikev2.php` | High
10 | File | `/admin/admin-profile.php` | High
11 | File | `/admin/ajax.php?action=confirm_order` | High
12 | File | `/admin/ajax.php?action=save_vacancy` | High
13 | File | `/admin/change-image.php` | High
14 | File | `/admin/check_availability.php` | High
15 | File | `/admin/comment/list` | High
16 | File | `/admin/contactus.php` | High
17 | File | `/admin/controller/faculty_controller.php` | High
18 | File | `/admin/court-type` | High
19 | File | `/admin/deletegallery.php` | High
20 | File | `/admin/edit-admin.php` | High
21 | File | `/admin/edit-course.php` | High
22 | File | `/admin/edit-doc.php` | High
23 | File | `/admin/edit-state.php` | High
24 | File | `/admin/edit_product.php` | High
25 | File | `/admin/edit_room.php` | High
26 | File | `/admin/leancloud.php` | High
27 | File | `/admin/manage-pages.php` | High
28 | File | `/admin/manage-scdetails.php` | High
29 | File | `/admin/print1.php` | High
30 | File | `/admin/profile.php` | High
31 | File | `/admin/report.php` | High
32 | File | `/admin/search-medicalcard.php` | High
33 | File | `/admin/state.php` | High
34 | File | `/admin/students/manage.php` | High
35 | File | `/admin/student_edit_photo.php` | High
36 | File | `/admin/twitter.php` | High
37 | File | `/admin/update_student.php` | High
38 | File | `/admin/update_users.php` | High
39 | File | `/admin/users.php` | High
40 | File | `/admin/view-request.php` | High
41 | File | `/admin/voters_edit.php` | High
42 | File | `/adminUser/updateImg` | High
43 | File | `/admin_class.php` | High
44 | File | `/adv_macbypass.php` | High
45 | File | `/ajax.php` | Medium
46 | File | `/ajax.php?action=save_membership` | High
47 | File | `/ajax.php?action=save_payroll` | High
48 | File | `/api.php` | Medium
49 | File | `/api/` | Low
50 | File | `/api/advanced-search` | High
51 | File | `/api/database/testConnect` | High
52 | File | `/api/File/downloadFile` | High
53 | File | `/api/system/dept/update` | High
54 | File | `/api/v1/editor/sql/run` | High
55 | File | `/api/wizard/getCapabilityWeb` | High
56 | File | `/api/wizard/getsyncpppoecfg` | High
57 | File | `/app/api/controller/collect.php` | High
58 | File | `/auth/soup-auth-digest.c` | High
59 | File | `/BBfile/Blood/o+.php` | High
60 | File | `/bigquery` | Medium
61 | File | `/bin/boa` | Medium
62 | File | `/bin/goahead` | Medium
63 | File | `/bin/webs` | Medium
64 | File | `/boafrm/formParentControl` | High
65 | File | `/boafrm/formPortFw` | High
66 | File | `/boafrm/formStats` | High
67 | File | `/book-appointment.php` | High
68 | File | `/bookingconfirm.php` | High
69 | File | `/cache/` | Low
70 | File | `/cancel.php` | Medium
71 | File | `/CDGServer3/logManagement/ClientSortLog.jsp` | High
72 | File | `/CDGServer3/workflowE/useractivate/updateorg.jsp` | High
73 | File | `/cgi-bin/cstecgi.cgi` | High
74 | File | `/change-password.php` | High
75 | ... | ... | ...

There are 663 more IOA items available (file, library, argument, input value, pattern, network port). Please use our online service to access the data.

## References

The following list contains _external sources_ which discuss the actor and the associated activities:

* https://urlhaus.abuse.ch/url/3525742/
* https://urlhaus.abuse.ch/url/3525743/
* https://urlhaus.abuse.ch/url/3525744/
* https://urlhaus.abuse.ch/url/3525745/
* https://urlhaus.abuse.ch/url/3525747/
* https://urlhaus.abuse.ch/url/3525782/
* https://urlhaus.abuse.ch/url/3529896/
* https://urlhaus.abuse.ch/url/3529932/
* https://urlhaus.abuse.ch/url/3537479/
* https://urlhaus.abuse.ch/url/3540422/
* https://urlhaus.abuse.ch/url/3540424/
* https://urlhaus.abuse.ch/url/3540425/
* https://urlhaus.abuse.ch/url/3540426/
* https://urlhaus.abuse.ch/url/3553384/
* https://urlhaus.abuse.ch/url/3553385/
* https://urlhaus.abuse.ch/url/3553386/
* https://urlhaus.abuse.ch/url/3553387/
* https://urlhaus.abuse.ch/url/3553388/
* https://urlhaus.abuse.ch/url/3556765/
* https://urlhaus.abuse.ch/url/3559291/
* https://urlhaus.abuse.ch/url/3562166/
* https://www.cadosecurity.com/blog/from-dormant-to-dangerous-p2pinfect-evolves-to-deploy-new-ransomware-and-cryptominer

## Literature

The following _articles_ explain our unique predictive cyber threat intelligence:

* [VulDB Cyber Threat Intelligence Documentation](https://vuldb.com/?kb.cti)
* [Cyber Threat Intelligence - Early Anticipation of Attacks](https://www.scip.ch/en/?labs.20201022)

## License

(c) [1997-2026](https://vuldb.com/?kb.changelog) by [vuldb.com](https://vuldb.com/?kb.about). All data on this page is shared under the license [CC BY-NC-SA 4.0](https://creativecommons.org/licenses/by-nc-sa/4.0/). Questions? Check the [FAQ](https://vuldb.com/?kb.faq), read the [documentation](https://vuldb.com/?kb) or [contact us](https://vuldb.com/?contact)!
