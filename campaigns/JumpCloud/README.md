# JumpCloud - Cyber Threat Intelligence

These _indicators_ were reported, collected, and generated during the [VulDB CTI analysis](https://vuldb.com/?kb.cti) of the campaign known as _JumpCloud_. The _activity monitoring_ correlates data from social media, forums, chat rooms, and darknet markets. It helps to determine associated actors, specific activities, expected intentions, emerging research, and ongoing attacks. Our unique _predictive model_ uses _big data_ to forecast activities and their characteristics.

_Live data_ and more _analysis capabilities_ are available at [https://vuldb.com/?actor](https://vuldb.com/?actor)

## Countries

These _countries_ are directly (e.g. origin of attacks) or indirectly (e.g. access by proxy) associated with JumpCloud:

* [US](https://vuldb.com/?country.us)
* [CN](https://vuldb.com/?country.cn)
* [RU](https://vuldb.com/?country.ru)
* ...

There are 9 more country items available. Please use our online service to access the data.

## Actors

These _actors_ are associated with JumpCloud or other actors linked to the campaign.

ID | Actor | Confidence
-- | ----- | ----------
1 | [DPRK](https://vuldb.com/?actor.dprk) | High

## IOC - Indicator of Compromise

These _indicators of compromise_ (IOC) indicate associated network resources which are known to be part of research and attack activities of JumpCloud.

ID | IP address | Hostname | Actor | Confidence
-- | ---------- | -------- | ----- | ----------
1 | [23.29.115.171](https://vuldb.com/?ip.23.29.115.171) | 23-29-115-171.static.hvvc.us | [DPRK](https://vuldb.com/?actor.dprk) | High
2 | [23.95.182.5](https://vuldb.com/?ip.23.95.182.5) | 23-95-182-5-host.colocrossing.com | [DPRK](https://vuldb.com/?actor.dprk) | High
3 | [45.82.250.186](https://vuldb.com/?ip.45.82.250.186) | - | [DPRK](https://vuldb.com/?actor.dprk) | High
4 | [51.254.24.19](https://vuldb.com/?ip.51.254.24.19) | - | [DPRK](https://vuldb.com/?actor.dprk) | High
5 | ... | ... | ... | ...

There are 15 more IOC items available. Please use our online service to access the data.

## TTP - Tactics, Techniques, Procedures

_Tactics, techniques, and procedures_ (TTP) summarize the suspected MITRE ATT&CK techniques used within JumpCloud. This data is unique as it uses our predictive model for actor profiling.

ID | Technique | Weakness | Description | Confidence
-- | --------- | -------- | ----------- | ----------
1 | T1006 | CWE-22, CWE-24 | Pathname Traversal | High
2 | T1040 | CWE-294 | Authentication Bypass by Capture-replay | High
3 | T1055 | CWE-74 | Injection | High
4 | T1059 | CWE-94, CWE-1321 | Cross Site Scripting | High
5 | T1059.007 | CWE-79, CWE-80 | Cross Site Scripting | High
6 | ... | ... | ... | ...

There are 19 more TTP items available. Please use our online service to access the data.

## IOA - Indicator of Attack

These _indicators of attack_ (IOA) list the potential fragments used for technical activities like reconnaissance, exploitation, privilege escalation, and exfiltration during JumpCloud. This data is unique as it uses our predictive model for actor profiling.

ID | Type | Indicator | Confidence
-- | ---- | --------- | ----------
1 | File | `.github/workflows/comment.yml` | High
2 | File | `//proc/kcore` | Medium
3 | File | `/?r=recruit/resume/edit&op=status` | High
4 | File | `/addbill.php` | Medium
5 | File | `/admin` | Low
6 | File | `/admin/` | Low
7 | File | `/admin/?page=user/manage_user&id=3` | High
8 | File | `/admin/about-us.php` | High
9 | File | `/admin/action/delete-vaccine.php` | High
10 | File | `/admin/add-category.php` | High
11 | File | `/admin/add-services.php` | High
12 | File | `/admin/addproduct.php` | High
13 | File | `/admin/admin-profile.php` | High
14 | File | `/admin/admin_login_process.php` | High
15 | File | `/admin/book_add.php` | High
16 | File | `/admin/book_row.php` | High
17 | File | `/admin/borrow_add.php` | High
18 | File | `/admin/bwdates-report-details.php` | High
19 | File | `/admin/category_row.php` | High
20 | File | `/admin/clientview.php` | High
21 | File | `/admin/contacts/organizations/edit/2` | High
22 | File | `/admin/courses/manage_course.php` | High
23 | File | `/admin/courses/view_course.php` | High
24 | File | `/admin/del_category.php` | High
25 | File | `/admin/del_feedback.php` | High
26 | File | `/admin/del_service.php` | High
27 | File | `/admin/departments/manage_department.php` | High
28 | File | `/admin/edit-accepted-appointment.php` | High
29 | File | `/admin/edit-services.php` | High
30 | File | `/admin/edit_category.php` | High
31 | File | `/admin/edit_product.php` | High
32 | File | `/admin/edit_subject.php` | High
33 | File | `/admin/forgot-password.php` | High
34 | File | `/admin/index.php` | High
35 | File | `/admin/index2.html` | High
36 | File | `/admin/invoice.php` | High
37 | File | `/admin/list_addr_fwresource_ip.php` | High
38 | File | `/admin/manage-users.php` | High
39 | File | `/admin/modal_add_product.php` | High
40 | File | `/admin/order.php` | High
41 | File | `/admin/php/crud.php` | High
42 | File | `/admin/regester.php` | High
43 | File | `/admin/reportupload.aspx` | High
44 | File | `/admin/return_add.php` | High
45 | File | `/admin/save_teacher.php` | High
46 | File | `/admin/search-appointment.php` | High
47 | File | `/admin/service.php` | High
48 | File | `/admin/singlelogin.php?submit=1` | High
49 | File | `/admin/students/manage_academic.php` | High
50 | File | `/admin/students/update_status.php` | High
51 | File | `/admin/sys_sql_query.php` | High
52 | File | `/admin/update-clients.php` | High
53 | File | `/admin/update_s6.php` | High
54 | File | `/admin/upload/img` | High
55 | File | `/admin/vote_edit.php` | High
56 | File | `/ample/app/action/edit_product.php` | High
57 | File | `/api/` | Low
58 | File | `/api/baskets/{name}` | High
59 | File | `/api/es/admin/v3/security/user/1` | High
60 | File | `/api/sys/login` | High
61 | File | `/api/sys/set_passwd` | High
62 | File | `/api/v1/terminal/sessions/?limit=1` | High
63 | File | `/api /v3/auth` | High
64 | File | `/app/ajax/sell_return_data.php` | High
65 | File | `/app/index/controller/Common.php` | High
66 | File | `/app/sys1.php` | High
67 | File | `/application/pay/controller/Api.php` | High
68 | File | `/auth/auth.php?user=1` | High
69 | File | `/bitrix/admin/ldap_server_edit.php` | High
70 | File | `/booking/show_bookings/` | High
71 | File | `/cas/logout` | Medium
72 | File | `/cgi-bin/adm.cgi` | High
73 | File | `/cgi-bin/cstecgi.cgi?action=login` | High
74 | File | `/cgi-bin/cstecgi.cgi?action=login&flag=ie8` | High
75 | File | `/cgi-bin/jumpto.php?class=user&page=config_save&isphp=1` | High
76 | ... | ... | ...

There are 672 more IOA items available (file, library, argument, input value, pattern, network port). Please use our online service to access the data.

## References

The following list contains _external sources_ which discuss the campaign and the associated activities:

* https://jumpcloud.com/support/july-2023-iocs

## Literature

The following _articles_ explain our unique predictive cyber threat intelligence:

* [VulDB Cyber Threat Intelligence Documentation](https://vuldb.com/?kb.cti)
* [Cyber Threat Intelligence - Early Anticipation of Attacks](https://www.scip.ch/en/?labs.20201022)

## License

(c) [1997-2024](https://vuldb.com/?kb.changelog) by [vuldb.com](https://vuldb.com/?kb.about). All data on this page is shared under the license [CC BY-NC-SA 4.0](https://creativecommons.org/licenses/by-nc-sa/4.0/). Questions? Check the [FAQ](https://vuldb.com/?kb.faq), read the [documentation](https://vuldb.com/?kb) or [contact us](https://vuldb.com/?contact)!
