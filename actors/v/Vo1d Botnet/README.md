# Vo1d Botnet - Cyber Threat Intelligence

These _indicators_ were reported, collected, and generated during the [VulDB CTI analysis](https://vuldb.com/?kb.cti) of the actor known as [Vo1d Botnet](https://vuldb.com/?actor.vo1d_botnet). The _activity monitoring_ correlates data from social media, forums, chat rooms, and darknet markets. It helps to determine associated actors, specific activities, expected intentions, emerging research, and ongoing attacks. Our unique _predictive model_ uses _big data_ to forecast activities and their characteristics.

_Live data_ and more _analysis capabilities_ are available at [https://vuldb.com/?actor.vo1d_botnet](https://vuldb.com/?actor.vo1d_botnet)

## Countries

These _countries_ are directly (e.g. origin of attacks) or indirectly (e.g. access by proxy) associated with Vo1d Botnet:

* [PT](https://vuldb.com/?country.pt)
* [DE](https://vuldb.com/?country.de)
* [PL](https://vuldb.com/?country.pl)
* ...

There are 8 more country items available. Please use our online service to access the data.

## IOC - Indicator of Compromise

These _indicators of compromise_ (IOC) indicate associated network resources which are known to be part of research and attack activities of Vo1d Botnet.

ID | IP address | Hostname | Campaign | Confidence
-- | ---------- | -------- | -------- | ----------
1 | [8.219.89.234](https://vuldb.com/?ip.8.219.89.234) | - | - | High
2 | [38.46.218.36](https://vuldb.com/?ip.38.46.218.36) | - | - | High
3 | [38.46.218.37](https://vuldb.com/?ip.38.46.218.37) | - | - | High
4 | [38.46.218.38](https://vuldb.com/?ip.38.46.218.38) | - | - | High
5 | [38.46.218.39](https://vuldb.com/?ip.38.46.218.39) | - | - | High
6 | ... | ... | ... | ...

There are 20 more IOC items available. Please use our online service to access the data.

## TTP - Tactics, Techniques, Procedures

_Tactics, techniques, and procedures_ (TTP) summarize the suspected MITRE ATT&CK techniques used by _Vo1d Botnet_. This data is unique as it uses our predictive model for actor profiling.

ID | Technique | Weakness | Description | Confidence
-- | --------- | -------- | ----------- | ----------
1 | T1006 | CWE-21, CWE-22, CWE-23, CWE-24, CWE-425 | Path Traversal | High
2 | T1040 | CWE-294 | Authentication Bypass by Capture-replay | High
3 | T1055 | CWE-74 | Improper Neutralization of Data within XPath Expressions | High
4 | T1059 | CWE-94, CWE-1321 | Argument Injection | High
5 | T1059.007 | CWE-79, CWE-80 | Basic Cross Site Scripting | High
6 | T1068 | CWE-250, CWE-264, CWE-269, CWE-270, CWE-284 | Execution with Unnecessary Privileges | High
7 | ... | ... | ... | ...

There are 23 more TTP items available. Please use our online service to access the data.

## IOA - Indicator of Attack

These _indicators of attack_ (IOA) list the potential fragments used for technical activities like reconnaissance, exploitation, privilege escalation, and exfiltration by Vo1d Botnet. This data is unique as it uses our predictive model for actor profiling.

ID | Type | Indicator | Confidence
-- | ---- | --------- | ----------
1 | File | `/?r=email/api/mark&op=delFromSend` | High
2 | File | `/?r=report/api/getlist` | High
3 | File | `/about.php` | Medium
4 | File | `/admin` | Low
5 | File | `/admin.php/accessory/filesdel.html` | High
6 | File | `/admin/` | Low
7 | File | `/admin/?page=system_info` | High
8 | File | `/admin/?page=user` | High
9 | File | `/admin/about-us.php` | High
10 | File | `/admin/add-category.php` | High
11 | File | `/admin/add-services.php` | High
12 | File | `/Admin/add-student.php` | High
13 | File | `/admin/addemployee.php` | High
14 | File | `/admin/admin-profile.php` | High
15 | File | `/admin/api/theme-edit/` | High
16 | File | `/admin/application-bwdates-reports-details.php` | High
17 | File | `/admin/attendance_row.php` | High
18 | File | `/admin/ballot_up.php` | High
19 | File | `/admin/bookings/view_booking.php` | High
20 | File | `/admin/cashadvance_row.php` | High
21 | File | `/admin/categories/view_category.php` | High
22 | File | `/admin/category/cate-edit-run.php` | High
23 | File | `/admin/contacts/organizations/edit/2` | High
24 | File | `/admin/del_category.php` | High
25 | File | `/admin/del_feedback.php` | High
26 | File | `/admin/edit_category.php` | High
27 | File | `/admin/edit_product.php` | High
28 | File | `/admin/emp-profile-avatar.php` | High
29 | File | `/admin/employee/controller.php` | High
30 | File | `/admin/forgot-password.php` | High
31 | File | `/admin/inquiries/view_inquiry.php` | High
32 | File | `/admin/list_addr_fwresource_ip.php` | High
33 | File | `/admin/modal_add_product.php` | High
34 | File | `/admin/read.php?mudi=announContent` | High
35 | File | `/admin/regester.php` | High
36 | File | `/admin/save_teacher.php` | High
37 | File | `/admin/search.php` | High
38 | File | `/admin/services/view_service.php` | High
39 | File | `/admin/sign/out` | High
40 | File | `/admin/sys_sql_query.php` | High
41 | File | `/admin/transactions/track_shipment.php` | High
42 | File | `/admin/user/manage_user.php` | High
43 | File | `/admin/userprofile.php` | High
44 | File | `/admin/vacancy/controller.php` | High
45 | File | `/adminpanel/admin/query/deleteCourseExe.php` | High
46 | File | `/adms/admin/?page=vehicles/sell_vehicle` | High
47 | File | `/ample/app/action/edit_product.php` | High
48 | File | `/api/admin/store/product/list` | High
49 | File | `/api/ping` | Medium
50 | File | `/api/wizard/setsyncpppoecfg` | High
51 | File | `/app/api/controller/caiji.php` | High
52 | File | `/bilal final/edit_stud.php` | High
53 | File | `/bin/ate` | Medium
54 | File | `/blog/comment` | High
55 | File | `/cardo/api` | Medium
56 | File | `/category/controller.php?action=edit` | High
57 | File | `/cgi-bin/cstecgi.cgi` | High
58 | File | `/cgi-bin/nightled.cgi` | High
59 | File | `/cgi-bin/p1_ftpserver.php` | High
60 | File | `/cgi-bin/supervisor/PwdGrp.cgi` | High
61 | File | `/classes/Login.php` | High
62 | File | `/classes/Master.php?f=delete_service` | High
63 | File | `/classes/Master.php?f=save_category` | High
64 | File | `/classes/Master.php?f=save_position` | High
65 | File | `/classes/Users.php` | High
66 | File | `/classes/Users.php?f=save` | High
67 | File | `/coreframe/app/content/admin/content.php` | High
68 | File | `/csms/?page=contact_us` | High
69 | File | `/dashboard/add-service.php` | High
70 | File | `/dayrui/Fcms/View/system_log.html` | High
71 | File | `/ecommerce/support_ticket` | High
72 | File | `/finance/help/en/frameset.htm` | High
73 | File | `/find-a-match` | High
74 | File | `/forum/away.php` | High
75 | File | `/forum/PostPrivateMessage` | High
76 | File | `/fusion/portal/action/Link` | High
77 | File | `/goform/aspForm` | High
78 | File | `/goform/execCommand` | High
79 | File | `/goform/fromRouteStatic` | High
80 | File | `/goform/GetParentControlInfo` | High
81 | File | `/goform/NatStaticSetting` | High
82 | File | `/goform/QuickIndex` | High
83 | File | `/goform/RgDhcp` | High
84 | File | `/goform/RGFirewallEL` | High
85 | ... | ... | ...

There are 754 more IOA items available (file, library, argument, input value, pattern, network port). Please use our online service to access the data.

## References

The following list contains _external sources_ which discuss the actor and the associated activities:

* https://blog.xlab.qianxin.com/long-live-the-vo1d_botnet/

## Literature

The following _articles_ explain our unique predictive cyber threat intelligence:

* [VulDB Cyber Threat Intelligence Documentation](https://vuldb.com/?kb.cti)
* [Cyber Threat Intelligence - Early Anticipation of Attacks](https://www.scip.ch/en/?labs.20201022)

## License

(c) [1997-2025](https://vuldb.com/?kb.changelog) by [vuldb.com](https://vuldb.com/?kb.about). All data on this page is shared under the license [CC BY-NC-SA 4.0](https://creativecommons.org/licenses/by-nc-sa/4.0/). Questions? Check the [FAQ](https://vuldb.com/?kb.faq), read the [documentation](https://vuldb.com/?kb) or [contact us](https://vuldb.com/?contact)!
