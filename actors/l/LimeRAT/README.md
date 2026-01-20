# LimeRAT - Cyber Threat Intelligence

These _indicators_ were reported, collected, and generated during the [VulDB CTI analysis](https://vuldb.com/?kb.cti) of the actor known as [LimeRAT](https://vuldb.com/?actor.limerat). The _activity monitoring_ correlates data from social media, forums, chat rooms, and darknet markets. It helps to determine associated actors, specific activities, expected intentions, emerging research, and ongoing attacks. Our unique _predictive model_ uses _big data_ to forecast activities and their characteristics.

_Live data_ and more _analysis capabilities_ are available at [https://vuldb.com/?actor.limerat](https://vuldb.com/?actor.limerat)

## Countries

These _countries_ are directly (e.g. origin of attacks) or indirectly (e.g. access by proxy) associated with LimeRAT:

* [VN](https://vuldb.com/?country.vn)
* [CZ](https://vuldb.com/?country.cz)
* [US](https://vuldb.com/?country.us)

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
1 | T1006 | CWE-21, CWE-22, CWE-23, CWE-24, CWE-425 | Path Traversal | High
2 | T1040 | CWE-319 | Authentication Bypass by Capture-replay | High
3 | T1055 | CWE-74 | Improper Neutralization of Data within XPath Expressions | High
4 | T1059 | CWE-94, CWE-1321 | Argument Injection | High
5 | T1059.007 | CWE-79, CWE-80 | Basic Cross Site Scripting | High
6 | ... | ... | ... | ...

There are 22 more TTP items available. Please use our online service to access the data.

## IOA - Indicator of Attack

These _indicators of attack_ (IOA) list the potential fragments used for technical activities like reconnaissance, exploitation, privilege escalation, and exfiltration by LimeRAT. This data is unique as it uses our predictive model for actor profiling.

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
91 | ... | ... | ...

There are 806 more IOA items available (file, library, argument, input value, pattern, network port). Please use our online service to access the data.

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
