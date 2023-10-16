# MedusaLocker - Cyber Threat Intelligence

These _indicators_ were reported, collected, and generated during the [VulDB CTI analysis](https://vuldb.com/?kb.cti) of the actor known as [MedusaLocker](https://vuldb.com/?actor.medusalocker). The _activity monitoring_ correlates data from social media, forums, chat rooms, and darknet markets. It helps to determine associated actors, specific activities, expected intentions, emerging research, and ongoing attacks. Our unique _predictive model_ uses _big data_ to forecast activities and their characteristics.

_Live data_ and more _analysis capabilities_ are available at [https://vuldb.com/?actor.medusalocker](https://vuldb.com/?actor.medusalocker)

## Countries

These _countries_ are directly (e.g. origin of attacks) or indirectly (e.g. access by proxy) associated with MedusaLocker:

* [US](https://vuldb.com/?country.us)
* [ES](https://vuldb.com/?country.es)
* [IR](https://vuldb.com/?country.ir)
* ...

There are 6 more country items available. Please use our online service to access the data.

## IOC - Indicator of Compromise

These _indicators of compromise_ (IOC) indicate associated network resources which are known to be part of research and attack activities of MedusaLocker.

ID | IP address | Hostname | Campaign | Confidence
-- | ---------- | -------- | -------- | ----------
1 | [3.29.17.1](https://vuldb.com/?ip.3.29.17.1) | ec2-3-29-17-1.me-central-1.compute.amazonaws.com | - | Medium
2 | [40.92.90.105](https://vuldb.com/?ip.40.92.90.105) | mail-vi1eur05olkn2105.outbound.protection.outlook.com | - | High
3 | [45.146.164.141](https://vuldb.com/?ip.45.146.164.141) | - | - | High
4 | [50.80.219.149](https://vuldb.com/?ip.50.80.219.149) | 50-80-219-149.client.mchsi.com | - | High
5 | [84.38.189.52](https://vuldb.com/?ip.84.38.189.52) | wmw10.empresagozalez.miami | - | High
6 | ... | ... | ... | ...

There are 20 more IOC items available. Please use our online service to access the data.

## TTP - Tactics, Techniques, Procedures

_Tactics, techniques, and procedures_ (TTP) summarize the suspected MITRE ATT&CK techniques used by _MedusaLocker_. This data is unique as it uses our predictive model for actor profiling.

ID | Technique | Weakness | Description | Confidence
-- | --------- | -------- | ----------- | ----------
1 | T1006 | CWE-22, CWE-24, CWE-36, CWE-425 | Pathname Traversal | High
2 | T1040 | CWE-319 | Authentication Bypass by Capture-replay | High
3 | T1055 | CWE-74 | Injection | High
4 | T1059 | CWE-94 | Cross Site Scripting | High
5 | T1059.007 | CWE-79 | Cross Site Scripting | High
6 | ... | ... | ... | ...

There are 20 more TTP items available. Please use our online service to access the data.

## IOA - Indicator of Attack

These _indicators of attack_ (IOA) list the potential fragments used for technical activities like reconnaissance, exploitation, privilege escalation, and exfiltration by MedusaLocker. This data is unique as it uses our predictive model for actor profiling.

ID | Type | Indicator | Confidence
-- | ---- | --------- | ----------
1 | File | `.github/workflows/comment.yml` | High
2 | File | `/?r=recruit/resume/edit&op=status` | High
3 | File | `/academy/home/courses` | High
4 | File | `/ad-list` | Medium
5 | File | `/admin.php?c=upload&f=zip&_noCache=0.1683794968` | High
6 | File | `/admin/?page=user/list` | High
7 | File | `/admin/?page=user/manage_user&id=3` | High
8 | File | `/admin/addproduct.php` | High
9 | File | `/admin/article/article-edit-run.php` | High
10 | File | `/admin/attendance_row.php` | High
11 | File | `/admin/ballot_down.php` | High
12 | File | `/admin/ballot_up.php` | High
13 | File | `/admin/bookings/manage_booking.php` | High
14 | File | `/admin/bookings/view_booking.php` | High
15 | File | `/admin/budget/manage_budget.php` | High
16 | File | `/admin/cashadvance_row.php` | High
17 | File | `/admin/contacts/organizations/edit/2` | High
18 | File | `/admin/curriculum/view_curriculum.php` | High
19 | File | `/admin/deduction_row.php` | High
20 | File | `/admin/departments/view_department.php` | High
21 | File | `/admin/edit_product.php` | High
22 | File | `/admin/edit_subject.php` | High
23 | File | `/admin/employee_row.php` | High
24 | File | `/admin/index.php` | High
25 | File | `/admin/index/index.html#/admin/mall.goods/index.html` | High
26 | File | `/admin/inquiries/view_inquiry.php` | High
27 | File | `/admin/login.php` | High
28 | File | `/admin/maintenance/brand.php` | High
29 | File | `/admin/maintenance/manage_category.php` | High
30 | File | `/admin/maintenance/view_designation.php` | High
31 | File | `/admin/mechanics/manage_mechanic.php` | High
32 | File | `/admin/modal_add_product.php` | High
33 | File | `/admin/offenses/view_details.php` | High
34 | File | `/admin/orders/update_status.php` | High
35 | File | `/admin/positions_add.php` | High
36 | File | `/admin/positions_row.php` | High
37 | File | `/admin/products/manage_product.php` | High
38 | File | `/admin/products/view_product.php` | High
39 | File | `/admin/project/update/2` | High
40 | File | `/admin/read.php?mudi=getSignal` | High
41 | File | `/admin/reg.php` | High
42 | File | `/admin/reminders/manage_reminder.php` | High
43 | File | `/admin/report/index.php` | High
44 | File | `/admin/reportupload.aspx` | High
45 | File | `/admin/service.php` | High
46 | File | `/admin/services/manage_service.php` | High
47 | File | `/admin/services/view_service.php` | High
48 | File | `/admin/service_requests/manage_inventory.php` | High
49 | File | `/admin/sys_sql_query.php` | High
50 | File | `/admin/test_status.php` | High
51 | File | `/admin/upload.php` | High
52 | File | `/admin/user/manage_user.php` | High
53 | File | `/admin/userprofile.php` | High
54 | File | `/admin/voters_row.php` | High
55 | File | `/admin/vote_edit.php` | High
56 | File | `/ajax.php?action=read_msg` | High
57 | File | `/ajax.php?action=save_company` | High
58 | File | `/api/stl/actions/search` | High
59 | File | `/api/sys/login` | High
60 | File | `/apply.cgi` | Medium
61 | File | `/App_Resource/UEditor/server/upload.aspx` | High
62 | File | `/author/list?limit=10&offset=0&order=desc` | High
63 | File | `/author_posts.php` | High
64 | File | `/blog` | Low
65 | File | `/blog-single.php` | High
66 | File | `/booking/show_bookings/` | High
67 | File | `/browse` | Low
68 | File | `/bsms_ci/index.php/book` | High
69 | File | `/category/list?limit=10&offset=0&order=desc` | High
70 | File | `/cgi-bin/mesh.cgi?page=upgrade` | High
71 | File | `/cgi-bin/ping.cgi` | High
72 | File | `/cgi-bin/touchlist_sync.cgi` | High
73 | File | `/chaincity/user/ticket/create` | High
74 | File | `/changeimage.php` | High
75 | File | `/classes/Login.php` | High
76 | File | `/classes/Master.php` | High
77 | File | `/classes/Master.php?f=delete_category` | High
78 | File | `/classes/Master.php?f=delete_inquiry` | High
79 | File | `/classes/Master.php?f=delete_item` | High
80 | File | `/classes/Master.php?f=delete_service` | High
81 | File | `/classes/Master.php?f=delete_sub_category` | High
82 | File | `/classes/Master.php?f=save_course` | High
83 | File | `/classes/Master.php?f=save_inquiry` | High
84 | ... | ... | ...

There are 737 more IOA items available (file, library, argument, input value, pattern, network port). Please use our online service to access the data.

## References

The following list contains _external sources_ which discuss the actor and the associated activities:

* https://www.bleepingcomputer.com/news/security/medusalocker-ransomware-wants-its-share-of-your-money/
* https://www.cisa.gov/uscert/ncas/alerts/aa22-181a

## Literature

The following _articles_ explain our unique predictive cyber threat intelligence:

* [VulDB Cyber Threat Intelligence Documentation](https://vuldb.com/?kb.cti)
* [Cyber Threat Intelligence - Early Anticipation of Attacks](https://www.scip.ch/en/?labs.20201022)

## License

(c) [1997-2023](https://vuldb.com/?kb.changelog) by [vuldb.com](https://vuldb.com/?kb.about). All data on this page is shared under the license [CC BY-NC-SA 4.0](https://creativecommons.org/licenses/by-nc-sa/4.0/). Questions? Check the [FAQ](https://vuldb.com/?kb.faq), read the [documentation](https://vuldb.com/?kb) or [contact us](https://vuldb.com/?contact)!
