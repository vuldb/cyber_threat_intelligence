# Nimplant - Cyber Threat Intelligence

These _indicators_ were reported, collected, and generated during the [VulDB CTI analysis](https://vuldb.com/?kb.cti) of the actor known as [Nimplant](https://vuldb.com/?actor.nimplant). The _activity monitoring_ correlates data from social media, forums, chat rooms, and darknet markets. It helps to determine associated actors, specific activities, expected intentions, emerging research, and ongoing attacks. Our unique _predictive model_ uses _big data_ to forecast activities and their characteristics.

_Live data_ and more _analysis capabilities_ are available at [https://vuldb.com/?actor.nimplant](https://vuldb.com/?actor.nimplant)

## Countries

These _countries_ are directly (e.g. origin of attacks) or indirectly (e.g. access by proxy) associated with Nimplant:

* [VN](https://vuldb.com/?country.vn)
* [CN](https://vuldb.com/?country.cn)

## IOC - Indicator of Compromise

These _indicators of compromise_ (IOC) indicate associated network resources which are known to be part of research and attack activities of Nimplant.

ID | IP address | Hostname | Campaign | Confidence
-- | ---------- | -------- | -------- | ----------
1 | [3.0.147.54](https://vuldb.com/?ip.3.0.147.54) | ec2-3-0-147-54.ap-southeast-1.compute.amazonaws.com | - | Medium
2 | [3.17.181.161](https://vuldb.com/?ip.3.17.181.161) | ec2-3-17-181-161.us-east-2.compute.amazonaws.com | - | Medium
3 | [3.226.6.113](https://vuldb.com/?ip.3.226.6.113) | ec2-3-226-6-113.compute-1.amazonaws.com | - | Medium
4 | [3.227.59.24](https://vuldb.com/?ip.3.227.59.24) | ec2-3-227-59-24.compute-1.amazonaws.com | - | Medium
5 | [3.230.13.26](https://vuldb.com/?ip.3.230.13.26) | ec2-3-230-13-26.compute-1.amazonaws.com | - | Medium
6 | [3.239.44.147](https://vuldb.com/?ip.3.239.44.147) | ec2-3-239-44-147.compute-1.amazonaws.com | - | Medium
7 | [13.70.157.121](https://vuldb.com/?ip.13.70.157.121) | - | - | High
8 | [13.223.172.177](https://vuldb.com/?ip.13.223.172.177) | ec2-13-223-172-177.compute-1.amazonaws.com | - | Medium
9 | [14.225.206.107](https://vuldb.com/?ip.14.225.206.107) | static.vnpt.vn | - | High
10 | [18.163.183.136](https://vuldb.com/?ip.18.163.183.136) | ec2-18-163-183-136.ap-east-1.compute.amazonaws.com | - | Medium
11 | [18.167.103.46](https://vuldb.com/?ip.18.167.103.46) | ec2-18-167-103-46.ap-east-1.compute.amazonaws.com | - | Medium
12 | [18.204.79.137](https://vuldb.com/?ip.18.204.79.137) | ec2-18-204-79-137.compute-1.amazonaws.com | - | Medium
13 | [18.211.169.218](https://vuldb.com/?ip.18.211.169.218) | ec2-18-211-169-218.compute-1.amazonaws.com | - | Medium
14 | [20.93.3.210](https://vuldb.com/?ip.20.93.3.210) | - | - | High
15 | [23.106.215.199](https://vuldb.com/?ip.23.106.215.199) | - | - | High
16 | [34.134.73.140](https://vuldb.com/?ip.34.134.73.140) | 140.73.134.34.bc.googleusercontent.com | - | Medium
17 | [34.230.185.98](https://vuldb.com/?ip.34.230.185.98) | ec2-34-230-185-98.compute-1.amazonaws.com | - | Medium
18 | [34.230.242.7](https://vuldb.com/?ip.34.230.242.7) | ec2-34-230-242-7.compute-1.amazonaws.com | - | Medium
19 | [34.251.151.38](https://vuldb.com/?ip.34.251.151.38) | ec2-34-251-151-38.eu-west-1.compute.amazonaws.com | - | Medium
20 | ... | ... | ... | ...

There are 76 more IOC items available. Please use our online service to access the data.

## TTP - Tactics, Techniques, Procedures

_Tactics, techniques, and procedures_ (TTP) summarize the suspected MITRE ATT&CK techniques used by _Nimplant_. This data is unique as it uses our predictive model for actor profiling.

ID | Technique | Weakness | Description | Confidence
-- | --------- | -------- | ----------- | ----------
1 | T1006 | CWE-22, CWE-24, CWE-27, CWE-425 | Path Traversal | High
2 | T1055 | CWE-74 | Improper Neutralization of Data within XPath Expressions | High
3 | T1059 | CWE-94, CWE-1321 | Argument Injection | High
4 | T1059.007 | CWE-79, CWE-80 | Basic Cross Site Scripting | High
5 | T1068 | CWE-269, CWE-284 | Execution with Unnecessary Privileges | High
6 | ... | ... | ... | ...

There are 20 more TTP items available. Please use our online service to access the data.

## IOA - Indicator of Attack

These _indicators of attack_ (IOA) list the potential fragments used for technical activities like reconnaissance, exploitation, privilege escalation, and exfiltration by Nimplant. This data is unique as it uses our predictive model for actor profiling.

ID | Type | Indicator | Confidence
-- | ---- | --------- | ----------
1 | File | `/99/ImportSQLTable` | High
2 | File | `/Account/EditProfile` | High
3 | File | `/account/_settings` | High
4 | File | `/add-courier.php` | High
5 | File | `/add-notes.php` | High
6 | File | `/addcategory.php` | High
7 | File | `/addproduct.php` | High
8 | File | `/admin#themes` | High
9 | File | `/admin-api/bpm/model/deploy` | High
10 | File | `/admin-api/mp/material/upload-permanent` | High
11 | File | `/admin.php` | Medium
12 | File | `/admin/` | Low
13 | File | `/admin/?page=back_order/view_bo` | High
14 | File | `/admin/?page=inventory/view_inventory&id=2` | High
15 | File | `/admin/aboutus.php` | High
16 | File | `/admin/actions/check-attendance.php` | High
17 | File | `/admin/add-admin.php` | High
18 | File | `/admin/add-boat.php` | High
19 | File | `/admin/add-directory.php` | High
20 | File | `/admin/add_postlogin.php` | High
21 | File | `/admin/add_trainers.php` | High
22 | File | `/admin/admin.php` | High
23 | File | `/Admin/adminlogin.php` | High
24 | File | `/admin/admin_football.php` | High
25 | File | `/admin/admin_index.php` | High
26 | File | `/admin/admin_login.php` | High
27 | File | `/admin/admin_user.php` | High
28 | File | `/admin/ajax.php` | High
29 | File | `/admin/ajax.php?action=save_area` | High
30 | File | `/admin/all-applied-leave.php` | High
31 | File | `/admin/announcement/index.php?view=add` | High
32 | File | `/admin/api/theme-edit/` | High
33 | File | `/admin/applicants/index.php` | High
34 | File | `/admin/appointment.php` | High
35 | File | `/admin/archives_add.php` | High
36 | File | `/admin/articles/add` | High
37 | File | `/admin/attendance_row.php` | High
38 | File | `/admin/backup/backups.php` | High
39 | File | `/admin/ballot_up.php` | High
40 | File | `/admin/candidates.php` | High
41 | File | `/admin/changeimage.php` | High
42 | File | `/admin/class.php?dowhat=modifyclass` | High
43 | File | `/admin/content/book` | High
44 | File | `/admin/delete_s2.php` | High
45 | File | `/admin/edit-art-product-detail.php?editid=2` | High
46 | File | `/admin/edit-class.php?cid=1` | High
47 | File | `/admin/edit-services.php` | High
48 | File | `/admin/edit-state.php` | High
49 | File | `/admin/edit-subadmin.php` | High
50 | File | `/admin/edit-subcategory.php` | High
51 | File | `/admin/edit-user.php` | High
52 | File | `/admin/edit_state.php` | High
53 | File | `/admin/fetch_product_details.php` | High
54 | File | `/admin/fields/manage_field.php` | High
55 | File | `/admin/images/add` | High
56 | File | `/admin/index.php` | High
57 | File | `/admin/index.php/news/edit` | High
58 | File | `/admin/indexConfigs/save` | High
59 | File | `/admin/insert-product.php` | High
60 | File | `/admin/inv-print.php` | High
61 | File | `/admin/list_localuser.php` | High
62 | File | `/admin/login.php` | High
63 | File | `/Admin/login.php` | High
64 | File | `/admin/manage-category.php` | High
65 | File | `/admin/manage-notices.php` | High
66 | File | `/admin/manage-tickets.php` | High
67 | File | `/admin/member_save.php` | High
68 | File | `/admin/menu_save.php` | High
69 | File | `/admin/offenses/view_details.php` | High
70 | File | `/admin/operations/travellers.php` | High
71 | File | `/admin/plan/examExportPDF` | High
72 | File | `/admin/positions.php` | High
73 | File | `/admin/posts.php?source=add_post` | High
74 | File | `/admin/print-payment.php` | High
75 | File | `/admin/print.php` | High
76 | File | `/admin/reg-users.php` | High
77 | File | `/Admin/resultdetails.php` | High
78 | File | `/admin/return_add.php` | High
79 | File | `/admin/sales/manage_sale.php` | High
80 | File | `/admin/save_student.php` | High
81 | File | `/admin/search-appointment.php` | High
82 | File | `/admin/search-directory.php` | High
83 | File | `/admin/search-maid.php` | High
84 | File | `/admin/search1.php` | High
85 | File | `/admin/services/manage.php` | High
86 | File | `/admin/services/manage_service.php` | High
87 | File | `/admin/spec_add.php` | High
88 | File | `/admin/sys/menu/list` | High
89 | File | `/admin/test_status.php` | High
90 | File | `/admin/user.php` | High
91 | File | `/admin/user/user-move-run.php` | High
92 | File | `/admin/users.php` | High
93 | File | `/admin/usersetting.php` | High
94 | File | `/adminprofile.php` | High
95 | File | `/admin_class.php` | High
96 | File | `/Admin_Dashboard/process/editemployee_process.php` | High
97 | File | `/adv_dhcps.php` | High
98 | File | `/agent/profile/edit` | High
99 | File | `/ajax.php` | Medium
100 | File | `/ajax.php?action=read_msg` | High
101 | File | `/ajax.php?action=save_product` | High
102 | File | `/ajax.php?action=save_student` | High
103 | File | `/all-orders.php` | High
104 | File | `/alphaware/summary.php` | High
105 | File | `/api/blade-system/menu/list?updatexml` | High
106 | File | `/api/blade-user/export-user` | High
107 | File | `/api/config/list` | High
108 | File | `/api/deploy/upload` | High
109 | File | `/api/deploy/upload /api/database/upload` | High
110 | File | `/api/login/auth` | High
111 | File | `/api/semantic/database/testConnect` | High
112 | File | `/Api/TinyMce/UploadAjaxAPI.ashx` | High
113 | File | `/api/v1/challenges//solves` | High
114 | File | `/api/v2/open/rowsInfo` | High
115 | ... | ... | ...

There are 1018 more IOA items available (file, library, argument, input value, pattern, network port). Please use our online service to access the data.

## References

The following list contains _external sources_ which discuss the actor and the associated activities:

* https://search.censys.io/hosts/3.226.6.113
* https://search.censys.io/hosts/3.230.13.26
* https://search.censys.io/hosts/3.239.44.147
* https://search.censys.io/hosts/13.70.157.121
* https://search.censys.io/hosts/13.223.172.177
* https://search.censys.io/hosts/14.225.206.107
* https://search.censys.io/hosts/18.163.183.136
* https://search.censys.io/hosts/18.167.103.46
* https://search.censys.io/hosts/18.204.79.137
* https://search.censys.io/hosts/18.211.169.218
* https://search.censys.io/hosts/20.93.3.210
* https://search.censys.io/hosts/23.106.215.199
* https://search.censys.io/hosts/34.134.73.140
* https://search.censys.io/hosts/34.134.73.140+140.73.134.34.bc.googleusercontent.com
* https://search.censys.io/hosts/34.230.185.98
* https://search.censys.io/hosts/34.230.242.7
* https://search.censys.io/hosts/37.59.103.250
* https://search.censys.io/hosts/43.143.128.128
* https://search.censys.io/hosts/44.194.109.35
* https://search.censys.io/hosts/44.195.207.182
* https://search.censys.io/hosts/44.201.19.178
* https://search.censys.io/hosts/44.221.193.28
* https://search.censys.io/hosts/45.156.25.5
* https://search.censys.io/hosts/46.247.108.127
* https://search.censys.io/hosts/47.243.184.85
* https://search.censys.io/hosts/51.68.222.10
* https://search.censys.io/hosts/52.5.18.208
* https://search.censys.io/hosts/52.22.211.254
* https://search.censys.io/hosts/52.54.42.16
* https://search.censys.io/hosts/52.73.142.40
* https://search.censys.io/hosts/52.243.66.182
* https://search.censys.io/hosts/54.38.242.131
* https://search.censys.io/hosts/54.202.46.22
* https://search.censys.io/hosts/54.204.117.176
* https://search.censys.io/hosts/54.208.106.230
* https://search.censys.io/hosts/54.226.241.245
* https://search.censys.io/hosts/65.49.204.212
* https://search.censys.io/hosts/77.237.246.243
* https://search.censys.io/hosts/86.54.42.68
* https://search.censys.io/hosts/88.208.3.157
* https://search.censys.io/hosts/89.73.53.34
* https://search.censys.io/hosts/94.102.49.16
* https://search.censys.io/hosts/94.102.49.106
* https://search.censys.io/hosts/95.40.110.232
* https://search.censys.io/hosts/98.89.171.225
* https://search.censys.io/hosts/100.26.7.35
* https://search.censys.io/hosts/100.51.239.164
* https://search.censys.io/hosts/124.156.166.6
* https://search.censys.io/hosts/136.144.243.50
* https://search.censys.io/hosts/136.243.23.163
* https://search.censys.io/hosts/139.180.217.224
* https://search.censys.io/hosts/142.93.226.220
* https://search.censys.io/hosts/146.190.109.188
* https://search.censys.io/hosts/146.190.241.166
* https://search.censys.io/hosts/147.50.231.86
* https://search.censys.io/hosts/149.248.79.215
* https://search.censys.io/hosts/156.244.1.13
* https://search.censys.io/hosts/156.244.13.120
* https://search.censys.io/hosts/159.69.214.72
* https://search.censys.io/hosts/159.69.214.72+static.72.214.69.159.clients.your-server.de
* https://search.censys.io/hosts/161.97.116.56
* https://search.censys.io/hosts/167.88.160.211
* https://search.censys.io/hosts/167.88.170.172
* https://search.censys.io/hosts/171.244.61.152
* https://search.censys.io/hosts/185.196.10.245
* https://search.censys.io/hosts/194.26.192.127
* https://search.censys.io/hosts/207.154.192.30
* https://search.censys.io/hosts/207.180.253.60
* https://search.censys.io/hosts/210.2.169.231
* https://search.censys.io/hosts/213.32.106.89
* https://threatfox.abuse.ch
* https://www.shodan.io/host/3.227.59.24#80
* https://www.shodan.io/host/45.60.11.228#9002
* https://www.shodan.io/host/52.3.69.115#80
* https://www.shodan.io/host/54.210.171.92#80
* https://www.shodan.io/host/54.237.179.121#80
* https://www.shodan.io/host/147.124.223.236#80
* https://www.shodan.io/host/188.245.84.67#2209

## Literature

The following _articles_ explain our unique predictive cyber threat intelligence:

* [VulDB Cyber Threat Intelligence Documentation](https://vuldb.com/?kb.cti)
* [Cyber Threat Intelligence - Early Anticipation of Attacks](https://www.scip.ch/en/?labs.20201022)

## License

(c) [1997-2026](https://vuldb.com/?kb.changelog) by [vuldb.com](https://vuldb.com/?kb.about). All data on this page is shared under the license [CC BY-NC-SA 4.0](https://creativecommons.org/licenses/by-nc-sa/4.0/). Questions? Check the [FAQ](https://vuldb.com/?kb.faq), read the [documentation](https://vuldb.com/?kb) or [contact us](https://vuldb.com/?contact)!
