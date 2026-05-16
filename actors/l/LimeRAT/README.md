# LimeRAT - Cyber Threat Intelligence

These _indicators_ were reported, collected, and generated during the [VulDB CTI analysis](https://vuldb.com/?kb.cti) of the actor known as [LimeRAT](https://vuldb.com/?actor.limerat). The _activity monitoring_ correlates data from social media, forums, chat rooms, and darknet markets. It helps to determine associated actors, specific activities, expected intentions, emerging research, and ongoing attacks. Our unique _predictive model_ uses _big data_ to forecast activities and their characteristics.

_Live data_ and more _analysis capabilities_ are available at [https://vuldb.com/?actor.limerat](https://vuldb.com/?actor.limerat)

## Countries

These _countries_ are directly (e.g. origin of attacks) or indirectly (e.g. access by proxy) associated with LimeRAT:

* [VN](https://vuldb.com/?country.vn)
* [FR](https://vuldb.com/?country.fr)

## IOC - Indicator of Compromise

These _indicators of compromise_ (IOC) indicate associated network resources which are known to be part of research and attack activities of LimeRAT.

ID | IP address | Hostname | Campaign | Confidence
-- | ---------- | -------- | -------- | ----------
1 | [2.56.212.39](https://vuldb.com/?ip.2.56.212.39) | ip-2-56-212-39-59599.vps.hosted-by-mvps.net | - | High
2 | [3.17.7.232](https://vuldb.com/?ip.3.17.7.232) | ec2-3-17-7-232.us-east-2.compute.amazonaws.com | - | Medium
3 | [3.22.30.40](https://vuldb.com/?ip.3.22.30.40) | ec2-3-22-30-40.us-east-2.compute.amazonaws.com | - | Medium
4 | [3.124.142.205](https://vuldb.com/?ip.3.124.142.205) | ec2-3-124-142-205.eu-central-1.compute.amazonaws.com | - | Medium
5 | [3.125.209.94](https://vuldb.com/?ip.3.125.209.94) | ec2-3-125-209-94.eu-central-1.compute.amazonaws.com | - | Medium
6 | [3.131.207.170](https://vuldb.com/?ip.3.131.207.170) | ec2-3-131-207-170.us-east-2.compute.amazonaws.com | - | Medium
7 | [3.141.177.1](https://vuldb.com/?ip.3.141.177.1) | ec2-3-141-177-1.us-east-2.compute.amazonaws.com | - | Medium
8 | [3.142.81.166](https://vuldb.com/?ip.3.142.81.166) | ec2-3-142-81-166.us-east-2.compute.amazonaws.com | - | Medium
9 | [3.142.167.4](https://vuldb.com/?ip.3.142.167.4) | ec2-3-142-167-4.us-east-2.compute.amazonaws.com | - | Medium
10 | [13.229.238.144](https://vuldb.com/?ip.13.229.238.144) | ec2-13-229-238-144.ap-southeast-1.compute.amazonaws.com | - | Medium
11 | [14.184.40.239](https://vuldb.com/?ip.14.184.40.239) | static.vnpt.vn | - | High
12 | [18.158.249.75](https://vuldb.com/?ip.18.158.249.75) | ec2-18-158-249-75.eu-central-1.compute.amazonaws.com | - | Medium
13 | [18.192.31.165](https://vuldb.com/?ip.18.192.31.165) | ec2-18-192-31-165.eu-central-1.compute.amazonaws.com | - | Medium
14 | [18.229.146.63](https://vuldb.com/?ip.18.229.146.63) | ec2-18-229-146-63.sa-east-1.compute.amazonaws.com | - | Medium
15 | [18.229.248.167](https://vuldb.com/?ip.18.229.248.167) | ec2-18-229-248-167.sa-east-1.compute.amazonaws.com | - | Medium
16 | [18.231.93.153](https://vuldb.com/?ip.18.231.93.153) | ec2-18-231-93-153.sa-east-1.compute.amazonaws.com | - | Medium
17 | [20.199.13.167](https://vuldb.com/?ip.20.199.13.167) | - | - | High
18 | [20.231.17.198](https://vuldb.com/?ip.20.231.17.198) | - | - | High
19 | ... | ... | ... | ...

There are 74 more IOC items available. Please use our online service to access the data.

## TTP - Tactics, Techniques, Procedures

_Tactics, techniques, and procedures_ (TTP) summarize the suspected MITRE ATT&CK techniques used by _LimeRAT_. This data is unique as it uses our predictive model for actor profiling.

ID | Technique | Weakness | Description | Confidence
-- | --------- | -------- | ----------- | ----------
1 | T1006 | CWE-22, CWE-24 | Path Traversal | High
2 | T1040 | CWE-319 | Authentication Bypass by Capture-replay | High
3 | T1055 | CWE-74 | Improper Neutralization of Data within XPath Expressions | High
4 | T1059 | CWE-88, CWE-94 | Argument Injection | High
5 | T1059.007 | CWE-79, CWE-80 | Basic Cross Site Scripting | High
6 | ... | ... | ... | ...

There are 18 more TTP items available. Please use our online service to access the data.

## IOA - Indicator of Attack

These _indicators of attack_ (IOA) list the potential fragments used for technical activities like reconnaissance, exploitation, privilege escalation, and exfiltration by LimeRAT. This data is unique as it uses our predictive model for actor profiling.

ID | Type | Indicator | Confidence
-- | ---- | --------- | ----------
1 | File | `/?explorer/index/zip` | High
2 | File | `/academic-calendar` | High
3 | File | `/account/forgotpassword` | High
4 | File | `/add-office.php` | High
5 | File | `/adduser-exec.php` | High
6 | File | `/add_librarian.php` | High
7 | File | `/add_overtime.php` | High
8 | File | `/add_student_grade.php` | High
9 | File | `/adm/ajax.php` | High
10 | File | `/admin-cp/imports` | High
11 | File | `/admin.php?id=inbox` | High
12 | File | `/admin/about-us.php` | High
13 | File | `/admin/aboutPost.php` | High
14 | File | `/Admin/add-admin.php` | High
15 | File | `/admin/add-animals.php` | High
16 | File | `/admin/add-art-type.php` | High
17 | File | `/admin/add-customer-services.php` | High
18 | File | `/admin/add-student.php` | High
19 | File | `/admin/adddoctorclinic.php` | High
20 | File | `/admin/add_content.php` | High
21 | File | `/admin/ajax.php?action=delete_vacancy` | High
22 | File | `/admin/all-appointment.php` | High
23 | File | `/admin/api/workspace/default/tool/debug` | High
24 | File | `/admin/archives_add.php` | High
25 | File | `/admin/assigned-requests.php` | High
26 | File | `/admin/backup/backups.php` | High
27 | File | `/admin/blood/update/o-.php` | High
28 | File | `/admin/booking-bwdates-reports-details.php` | High
29 | File | `/admin/bookings/view_details.php` | High
30 | File | `/Admin/Category.php` | High
31 | File | `/admin/category/controller.php` | High
32 | File | `/admin/category_save.php` | High
33 | File | `/admin/changeimage.php` | High
34 | File | `/admin/checklogin.php` | High
35 | File | `/admin/company/index.php` | High
36 | File | `/Admin/consulting_detail.php` | High
37 | File | `/admin/content` | High
38 | File | `/admin/customer-list.php` | High
39 | File | `/Admin/CustomerReport.php` | High
40 | File | `/admin/delete-user.php` | High
41 | File | `/admin/de_activate.php` | High
42 | File | `/admin/edit-category.php` | High
43 | File | `/admin/edit-class.php?cid=1` | High
44 | File | `/admin/edit-customer-detailed.php` | High
45 | File | `/admin/edit-user.php` | High
46 | File | `/admin/edit.php` | High
47 | File | `/admin/editorder.php` | High
48 | File | `/admin/edit_category.php` | High
49 | File | `/admin/edit_room.php` | High
50 | File | `/admin/edit_teacher.php` | High
51 | File | `/admin/file/rename.do` | High
52 | File | `/admin/finished.php` | High
53 | File | `/admin/index.php` | High
54 | File | `/admin/index/index.html#/admin/mall.goods/index.html` | High
55 | File | `/admin/inventory/manage_stock.php` | High
56 | File | `/admin/invoices.php` | High
57 | File | `/admin/login.php` | High
58 | File | `/admin/manage-admins.php` | High
59 | File | `/admin/manage-scdetails.php` | High
60 | File | `/admin/menu/toEdit` | High
61 | File | `/admin/network/diag_traceroute` | High
62 | File | `/admin/new-content` | High
63 | File | `/admin/newsletter.php` | High
64 | File | `/admin/offenses/view_details.php` | High
65 | File | `/admin/options-theme.php` | High
66 | File | `/admin/positions_add.php` | High
67 | File | `/admin/print_inv.php` | High
68 | File | `/admin/profile.php` | High
69 | File | `/admin/registration.php` | High
70 | File | `/admin/return_add.php` | High
71 | File | `/admin/role` | Medium
72 | File | `/admin/roombook.php` | High
73 | File | `/admin/roomdel.php` | High
74 | File | `/admin/sales-reports-detail.php` | High
75 | File | `/admin/search.php` | High
76 | File | `/admin/settings.php` | High
77 | File | `/admin/show.php` | High
78 | File | `/admin/sms_setting.php` | High
79 | File | `/admin/spec_add.php` | High
80 | File | `/admin/system.html` | High
81 | File | `/admin/template/edit` | High
82 | File | `/admin/transactions/track_shipment.php` | High
83 | File | `/admin/update-users.php` | High
84 | File | `/admin/update_user.php` | High
85 | File | `/admin/user/controller.php?action=photos` | High
86 | File | `/admin/user/manage_user.php` | High
87 | File | `/admin/userdelete.php` | High
88 | File | `/admin/users-applications.php` | High
89 | File | `/admin/view-appointment.php` | High
90 | File | `/admin/view-enquiry.php` | High
91 | File | `/admin/view-member-report.php` | High
92 | File | `/admin/view-progress-report.php` | High
93 | File | `/admin/voters_add.php` | High
94 | File | `/adminapi/product/product` | High
95 | File | `/admin_class.php` | High
96 | File | `/admin_topic.php?action=delall` | High
97 | File | `/aim/storage/query.py` | High
98 | File | `/ajax.php?action=delete_block` | High
99 | File | `/ajax.php?action=end_membership` | High
100 | File | `/ajax.php?action=save_category` | High
101 | File | `/ajax.php?action=save_customer` | High
102 | File | `/ajax.php?Ajax=GetModal_MQTTEdit` | High
103 | File | `/aloneReport/index.do/../../aloneReport/download.do;othersusrlogout.do` | High
104 | File | `/ample/app/action/edit_product.php` | High
105 | File | `/api/admin/question/edit` | High
106 | File | `/api/article/del` | High
107 | File | `/api/es/admin/v3/security/user/1` | High
108 | File | `/api/file/upload` | High
109 | File | `/Api/FileUpload.ashx?method=DoUpload` | High
110 | File | `/api/GylOperator/UpdatePasswordBatch` | High
111 | File | `/api/public/signup` | High
112 | File | `/api/upload` | Medium
113 | File | `/api/users/updateEmail/` | High
114 | File | `/api/v1/assignments/{assignment_id}/tasks/{task_id}/sub_file` | High
115 | File | `/api/v2/categories` | High
116 | File | `/app-api/v1/orders/` | High
117 | File | `/app/admin/view/web_user.html` | High
118 | File | `/app/ajax/search_sales_report.php` | High
119 | File | `/app/ConfirmSmsCode` | High
120 | File | `/approve.php` | Medium
121 | File | `/aqpg/users/login.php` | High
122 | File | `/assetsGroupReport/assetsService.j%73p` | High
123 | ... | ... | ...

There are 1094 more IOA items available (file, library, argument, input value, pattern, network port). Please use our online service to access the data.

## References

The following list contains _external sources_ which discuss the actor and the associated activities:

* https://bazaar.abuse.ch/sample/5ec2650940db1e24271b84e5553d8454f17a7c99cbb36579aa843aa09798efe3/
* https://bazaar.abuse.ch/sample/93a09a5ecefc75e6fda23d83deffeffddf544da2103a75422e768d26cfe9ee7f/
* https://lab52.io/blog/apt-c-36-from-njrat-to-apt-c-36/
* https://threatfox.abuse.ch
* https://urlhaus.abuse.ch/url/3633645/

## Literature

The following _articles_ explain our unique predictive cyber threat intelligence:

* [VulDB Cyber Threat Intelligence Documentation](https://vuldb.com/?kb.cti)
* [Cyber Threat Intelligence - Early Anticipation of Attacks](https://www.scip.ch/en/?labs.20201022)

## License

(c) [1997-2026](https://vuldb.com/?kb.changelog) by [vuldb.com](https://vuldb.com/?kb.about). All data on this page is shared under the license [CC BY-NC-SA 4.0](https://creativecommons.org/licenses/by-nc-sa/4.0/). Questions? Check the [FAQ](https://vuldb.com/?kb.faq), read the [documentation](https://vuldb.com/?kb) or [contact us](https://vuldb.com/?contact)!
