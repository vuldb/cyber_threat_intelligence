# Nimplant - Cyber Threat Intelligence

These _indicators_ were reported, collected, and generated during the [VulDB CTI analysis](https://vuldb.com/?kb.cti) of the actor known as [Nimplant](https://vuldb.com/?actor.nimplant). The _activity monitoring_ correlates data from social media, forums, chat rooms, and darknet markets. It helps to determine associated actors, specific activities, expected intentions, emerging research, and ongoing attacks. Our unique _predictive model_ uses _big data_ to forecast activities and their characteristics.

_Live data_ and more _analysis capabilities_ are available at [https://vuldb.com/?actor.nimplant](https://vuldb.com/?actor.nimplant)

## Countries

These _countries_ are directly (e.g. origin of attacks) or indirectly (e.g. access by proxy) associated with Nimplant:

* [VN](https://vuldb.com/?country.vn)

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
8 | [14.225.206.107](https://vuldb.com/?ip.14.225.206.107) | static.vnpt.vn | - | High
9 | [18.167.103.46](https://vuldb.com/?ip.18.167.103.46) | ec2-18-167-103-46.ap-east-1.compute.amazonaws.com | - | Medium
10 | [18.204.79.137](https://vuldb.com/?ip.18.204.79.137) | ec2-18-204-79-137.compute-1.amazonaws.com | - | Medium
11 | [18.211.169.218](https://vuldb.com/?ip.18.211.169.218) | ec2-18-211-169-218.compute-1.amazonaws.com | - | Medium
12 | [20.93.3.210](https://vuldb.com/?ip.20.93.3.210) | - | - | High
13 | [23.106.215.199](https://vuldb.com/?ip.23.106.215.199) | - | - | High
14 | [34.134.73.140](https://vuldb.com/?ip.34.134.73.140) | 140.73.134.34.bc.googleusercontent.com | - | Medium
15 | [34.230.185.98](https://vuldb.com/?ip.34.230.185.98) | ec2-34-230-185-98.compute-1.amazonaws.com | - | Medium
16 | [34.251.151.38](https://vuldb.com/?ip.34.251.151.38) | ec2-34-251-151-38.eu-west-1.compute.amazonaws.com | - | Medium
17 | [35.87.2.201](https://vuldb.com/?ip.35.87.2.201) | ec2-35-87-2-201.us-west-2.compute.amazonaws.com | - | Medium
18 | ... | ... | ... | ...

There are 67 more IOC items available. Please use our online service to access the data.

## TTP - Tactics, Techniques, Procedures

_Tactics, techniques, and procedures_ (TTP) summarize the suspected MITRE ATT&CK techniques used by _Nimplant_. This data is unique as it uses our predictive model for actor profiling.

ID | Technique | Weakness | Description | Confidence
-- | --------- | -------- | ----------- | ----------
1 | T1006 | CWE-21, CWE-22, CWE-23, CWE-24, CWE-425 | Path Traversal | High
2 | T1040 | CWE-319 | Authentication Bypass by Capture-replay | High
3 | T1055 | CWE-74 | Improper Neutralization of Data within XPath Expressions | High
4 | T1059 | CWE-94, CWE-1321 | Argument Injection | High
5 | T1059.007 | CWE-79, CWE-80 | Basic Cross Site Scripting | High
6 | ... | ... | ... | ...

There are 22 more TTP items available. Please use our online service to access the data.

## IOA - Indicator of Attack

These _indicators of attack_ (IOA) list the potential fragments used for technical activities like reconnaissance, exploitation, privilege escalation, and exfiltration by Nimplant. This data is unique as it uses our predictive model for actor profiling.

ID | Type | Indicator | Confidence
-- | ---- | --------- | ----------
1 | File | `/?g=net_pro_keyword_import_save` | High
2 | File | `/?r=report/api/getlist` | High
3 | File | `/academy/home/courses` | High
4 | File | `/AcceptZip.ashx` | High
5 | File | `/action.php` | Medium
6 | File | `/add-admin.php` | High
7 | File | `/addpayment.php` | High
8 | File | `/addrecord.php` | High
9 | File | `/add_new_invoice.php` | High
10 | File | `/admin-api/bpm/model/deploy` | High
11 | File | `/admin-cp/file-manager/upload` | High
12 | File | `/admin-cp/theme/install` | High
13 | File | `/admin-panel1.php` | High
14 | File | `/admin/aboutus.php` | High
15 | File | `/admin/add-directory.php` | High
16 | File | `/admin/add-team.php` | High
17 | File | `/admin/add_cars.php` | High
18 | File | `/admin/admin-profile.php` | High
19 | File | `/admin/AdminLogin.php` | High
20 | File | `/admin/admin_running.php` | High
21 | File | `/admin/ajax.php?action=login` | High
22 | File | `/admin/ajax.php?action=save_settings` | High
23 | File | `/admin/app/login_crud.php` | High
24 | File | `/admin/app/role_crud.php` | High
25 | File | `/admin/bookdate.php` | High
26 | File | `/admin/bookings/manage_booking.php` | High
27 | File | `/admin/cashadvance_row.php` | High
28 | File | `/admin/chart1.php` | High
29 | File | `/admin/clients/manage.php` | High
30 | File | `/admin/create_product.php` | High
31 | File | `/admin/department.php` | High
32 | File | `/admin/edit-accepted-appointment.php` | High
33 | File | `/admin/edit-category.php` | High
34 | File | `/admin/edit-subcategory.php` | High
35 | File | `/admin/edit-user-profile.php` | High
36 | File | `/admin/editsite.php` | High
37 | File | `/admin/edit_categories.php` | High
38 | File | `/admin/edit_member.php` | High
39 | File | `/admin/edit_student_query.php` | High
40 | File | `/admin/edit_supplier.php` | High
41 | File | `/admin/eligibility.php` | High
42 | File | `/admin/employee/index.php` | High
43 | File | `/admin/extensions/download.php` | High
44 | File | `/admin/freelist_main.php` | High
45 | File | `/admin/home/index.html` | High
46 | File | `/admin/index.php?language=en&nv=upload` | High
47 | File | `/admin/login.php` | High
48 | File | `/admin/manage_theater.php` | High
49 | File | `/admin/menus/view_menu.php` | High
50 | File | `/admin/newsletterdel.php` | High
51 | File | `/admin/offenses/view_details.php` | High
52 | File | `/admin/save_teacher.php` | High
53 | File | `/admin/search-vehicle.php` | High
54 | File | `/admin/search.php` | High
55 | File | `/admin/templets_one_edit.php` | High
56 | File | `/admin/test_status.php` | High
57 | File | `/admin/update_s5.php` | High
58 | File | `/admin/update_user.php` | High
59 | File | `/admin/upload/authorImg/` | High
60 | File | `/admin/v1/link/edit` | High
61 | File | `/admin/view_vacancy.php` | High
62 | File | `/adminac.php` | Medium
63 | File | `/admin_class.php` | High
64 | File | `/admin_link.php?action=delall` | High
65 | File | `/agenda_preferencias.php` | High
66 | File | `/ajax.php?action=delete_product` | High
67 | File | `/ajax.php?action=delete_receiving` | High
68 | File | `/ajax.php?action=delete_user` | High
69 | File | `/ajax.php?action=read_msg` | High
70 | File | `/ajax.php?action=save_payment` | High
71 | File | `/allocate_room.php` | High
72 | File | `/ample/app/action/edit_product.php` | High
73 | File | `/api/` | Low
74 | File | `/api/2.0/rest/aggregator/xml` | High
75 | File | `/api/backend/core/web-file-upload/upload` | High
76 | File | `/api/upload/image` | High
77 | File | `/api/v2.0/users` | High
78 | File | `/app/sae/design/desktop/flat` | High
79 | File | `/App/Tpl/Admin/Default/Log/index.html` | High
80 | File | `/Applications/Steal/main.cpp` | High
81 | File | `/b2b-supermarket/catalog/all-products` | High
82 | File | `/base/safe_setting/` | High
83 | File | `/boafrm/formDebugDiagnosticRun` | High
84 | File | `/boafrm/formIpQoS` | High
85 | File | `/boafrm/formMapDel` | High
86 | File | `/boafrm/formPortFw` | High
87 | File | `/boafrm/formReflashClientTbl` | High
88 | File | `/boafrm/formStaticDHCP` | High
89 | File | `/boafrm/formWlanMultipleAP` | High
90 | File | `/boafrm/formWsc` | High
91 | File | `/boat-details.php` | High
92 | ... | ... | ...

There are 814 more IOA items available (file, library, argument, input value, pattern, network port). Please use our online service to access the data.

## References

The following list contains _external sources_ which discuss the actor and the associated activities:

* https://search.censys.io/hosts/3.226.6.113
* https://search.censys.io/hosts/3.230.13.26
* https://search.censys.io/hosts/3.239.44.147
* https://search.censys.io/hosts/13.70.157.121
* https://search.censys.io/hosts/14.225.206.107
* https://search.censys.io/hosts/18.167.103.46
* https://search.censys.io/hosts/18.204.79.137
* https://search.censys.io/hosts/18.211.169.218
* https://search.censys.io/hosts/20.93.3.210
* https://search.censys.io/hosts/23.106.215.199
* https://search.censys.io/hosts/34.134.73.140
* https://search.censys.io/hosts/34.134.73.140+140.73.134.34.bc.googleusercontent.com
* https://search.censys.io/hosts/34.230.185.98
* https://search.censys.io/hosts/37.59.103.250
* https://search.censys.io/hosts/43.143.128.128
* https://search.censys.io/hosts/44.194.109.35
* https://search.censys.io/hosts/44.201.19.178
* https://search.censys.io/hosts/45.156.25.5
* https://search.censys.io/hosts/46.247.108.127
* https://search.censys.io/hosts/47.243.184.85
* https://search.censys.io/hosts/51.68.222.10
* https://search.censys.io/hosts/52.22.211.254
* https://search.censys.io/hosts/52.54.42.16
* https://search.censys.io/hosts/52.73.142.40
* https://search.censys.io/hosts/52.243.66.182
* https://search.censys.io/hosts/54.38.242.131
* https://search.censys.io/hosts/54.202.46.22
* https://search.censys.io/hosts/54.208.106.230
* https://search.censys.io/hosts/65.49.204.212
* https://search.censys.io/hosts/77.237.246.243
* https://search.censys.io/hosts/86.54.42.68
* https://search.censys.io/hosts/88.208.3.157
* https://search.censys.io/hosts/89.73.53.34
* https://search.censys.io/hosts/94.102.49.16
* https://search.censys.io/hosts/94.102.49.106
* https://search.censys.io/hosts/95.40.110.232
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
