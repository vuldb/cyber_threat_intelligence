# Fortra GoAnywhere - Cyber Threat Intelligence

These _indicators_ were reported, collected, and generated during the [VulDB CTI analysis](https://vuldb.com/?kb.cti) of the campaign known as _Fortra GoAnywhere_. The _activity monitoring_ correlates data from social media, forums, chat rooms, and darknet markets. It helps to determine associated actors, specific activities, expected intentions, emerging research, and ongoing attacks. Our unique _predictive model_ uses _big data_ to forecast activities and their characteristics.

_Live data_ and more _analysis capabilities_ are available at [https://vuldb.com/?actor](https://vuldb.com/?actor)

## Countries

These _countries_ are directly (e.g. origin of attacks) or indirectly (e.g. access by proxy) associated with Fortra GoAnywhere:

* [RU](https://vuldb.com/?country.ru)
* [US](https://vuldb.com/?country.us)
* [DE](https://vuldb.com/?country.de)
* ...

There are 7 more country items available. Please use our online service to access the data.

## Actors

These _actors_ are associated with Fortra GoAnywhere or other actors linked to the campaign.

ID | Actor | Confidence
-- | ----- | ----------
1 | [Clop](https://vuldb.com/?actor.clop) | High

## IOC - Indicator of Compromise

These _indicators of compromise_ (IOC) indicate associated network resources which are known to be part of research and attack activities of Fortra GoAnywhere.

ID | IP address | Hostname | Actor | Confidence
-- | ---------- | -------- | ----- | ----------
1 | [3.101.53.11](https://vuldb.com/?ip.3.101.53.11) | ec2-3-101-53-11.us-west-1.compute.amazonaws.com | [Clop](https://vuldb.com/?actor.clop) | Medium
2 | [5.34.178.28](https://vuldb.com/?ip.5.34.178.28) | s41.friendhosting.net | [Clop](https://vuldb.com/?actor.clop) | High
3 | [5.34.178.30](https://vuldb.com/?ip.5.34.178.30) | dedic-hghdgsjhdgjhgdj67tyu687uy-1209043.hosted-by-itldc.com | [Clop](https://vuldb.com/?actor.clop) | High
4 | [5.34.178.31](https://vuldb.com/?ip.5.34.178.31) | free.ds | [Clop](https://vuldb.com/?actor.clop) | High
5 | [5.34.180.48](https://vuldb.com/?ip.5.34.180.48) | mail.tube-plant.com | [Clop](https://vuldb.com/?actor.clop) | High
6 | [15.235.13.184](https://vuldb.com/?ip.15.235.13.184) | gollum.utwb.net | [Clop](https://vuldb.com/?actor.clop) | High
7 | [15.235.83.73](https://vuldb.com/?ip.15.235.83.73) | web0.meritusedu.ca | [Clop](https://vuldb.com/?actor.clop) | High
8 | [20.47.120.195](https://vuldb.com/?ip.20.47.120.195) | - | [Clop](https://vuldb.com/?actor.clop) | High
9 | [24.3.132.168](https://vuldb.com/?ip.24.3.132.168) | c-24-3-132-168.hsd1.pa.comcast.net | [Clop](https://vuldb.com/?actor.clop) | High
10 | ... | ... | ... | ...

There are 34 more IOC items available. Please use our online service to access the data.

## TTP - Tactics, Techniques, Procedures

_Tactics, techniques, and procedures_ (TTP) summarize the suspected MITRE ATT&CK techniques used within Fortra GoAnywhere. This data is unique as it uses our predictive model for actor profiling.

ID | Technique | Weakness | Description | Confidence
-- | --------- | -------- | ----------- | ----------
1 | T1006 | CWE-22, CWE-24, CWE-25 | Path Traversal | High
2 | T1059 | CWE-88, CWE-94 | Argument Injection | High
3 | T1059.007 | CWE-79, CWE-80 | Basic Cross Site Scripting | High
4 | ... | ... | ... | ...

There are 13 more TTP items available. Please use our online service to access the data.

## IOA - Indicator of Attack

These _indicators of attack_ (IOA) list the potential fragments used for technical activities like reconnaissance, exploitation, privilege escalation, and exfiltration during Fortra GoAnywhere. This data is unique as it uses our predictive model for actor profiling.

ID | Type | Indicator | Confidence
-- | ---- | --------- | ----------
1 | File | `../mtd/Config/Sha1Account1` | High
2 | File | `/;/admin/role/edit` | High
3 | File | `/aboutedit.php` | High
4 | File | `/abs.php` | Medium
5 | File | `/account.php` | Medium
6 | File | `/account.php?q=quiz&step=2` | High
7 | File | `/add.php` | Medium
8 | File | `/addCatController.php` | High
9 | File | `/addcustcom.php` | High
10 | File | `/addcustind.php` | High
11 | File | `/add_achievement_details.php` | High
12 | File | `/add_new_invoice.php` | High
13 | File | `/add_new_purchase.php?action=is_supplier` | High
14 | File | `/add_user.php` | High
15 | File | `/admin/?page=inventory/view_inventory&id=2` | High
16 | File | `/admin/about-us.php` | High
17 | File | `/admin/aboutus.php` | High
18 | File | `/admin/add-customer-services.php` | High
19 | File | `/admin/add-doctor.php` | High
20 | File | `/admin/add-propertytype.php` | High
21 | File | `/admin/admin-profile.php` | High
22 | File | `/Admin/adminlogin.php` | High
23 | File | `/admin/admin_action.php` | High
24 | File | `/admin/admin_login.php` | High
25 | File | `/admin/ad_list.php?action=pass` | High
26 | File | `/admin/ajax.php?action=login` | High
27 | File | `/admin/ajax_product.php` | High
28 | File | `/Admin/akun_edit.php` | High
29 | File | `/admin/all_users.php` | High
30 | File | `/admin/apply.php` | High
31 | File | `/admin/article.php` | High
32 | File | `/admin/assets/plugins/DataTables/media/unit_testing/templates/complex_header_2.php` | High
33 | File | `/admin/assets/plugins/DataTables/media/unit_testing/templates/deferred_table.php` | High
34 | File | `/admin/assets/plugins/DataTables/media/unit_testing/templates/dom_data.php` | High
35 | File | `/admin/assets/plugins/DataTables/media/unit_testing/templates/dom_data_th.php` | High
36 | File | `/admin/assets/plugins/DataTables/media/unit_testing/templates/dymanic_table.php` | High
37 | File | `/admin/assets/plugins/DataTables/media/unit_testing/templates/empty_table.php` | High
38 | File | `/admin/assets/plugins/DataTables/media/unit_testing/templates/html_table.php` | High
39 | File | `/admin/assets/plugins/DataTables/media/unit_testing/templates/js_data.php` | High
40 | File | `/admin/assets/plugins/DataTables/media/unit_testing/templates/two_tables.php` | High
41 | File | `/admin/blood/update/B-.php` | High
42 | File | `/admin/book-details.php` | High
43 | File | `/admin/bwdates-report-details.php` | High
44 | File | `/admin/campsdetails.php` | High
45 | File | `/admin/card-bwdates-reports-details.php` | High
46 | File | `/admin/categories/manage_category.php` | High
47 | File | `/admin/categories/update` | High
48 | File | `/admin/category.php` | High
49 | File | `/admin/chatroom.php` | High
50 | File | `/admin/cmsTagType/save` | High
51 | File | `/Admin/consulting_detail.php` | High
52 | File | `/admin/contactus.php` | High
53 | File | `/admin/content/editor` | High
54 | File | `/admin/course_action.php` | High
55 | File | `/admin/deleteBooking.php` | High
56 | File | `/Admin/detail.php` | High
57 | File | `/admin/edit-card-detail.php` | High
58 | File | `/admin/edit-category.php` | High
59 | File | `/admin/edit-customer-detailed.php` | High
60 | File | `/admin/edit-propertytype.php` | High
61 | File | `/admin/edit-subadmin.php` | High
62 | File | `/admin/edit_customer.php` | High
63 | File | `/admin/edit_fuel.php` | High
64 | File | `/admin/edit_role.php` | High
65 | File | `/admin/faculty_action.php` | High
66 | File | `/admin/File/fileUpload` | High
67 | File | `/admin/File/pictureUpload` | High
68 | File | `/admin/index.php` | High
69 | File | `/admin/link.php` | High
70 | File | `/admin/login.php` | High
71 | File | `/admin/login_process.php` | High
72 | File | `/admin/massage.php` | High
73 | File | `/admin/mod_room/controller.php?action=add` | High
74 | File | `/admin/msg.php` | High
75 | File | `/admin/network/ajax_getChannelList` | High
76 | File | `/admin/network/diag_iperf` | High
77 | File | `/admin/network/diag_nslookup` | High
78 | File | `/admin/network/diag_ping6` | High
79 | File | `/admin/network/diag_pinginterface` | High
80 | File | `/admin/network/diag_traceroute6` | High
81 | File | `/admin/network/wifi_schedule` | High
82 | File | `/admin/overtime_add.php` | High
83 | File | `/admin/overtime_row.php` | High
84 | File | `/admin/plugin.php` | High
85 | File | `/admin/print.php` | High
86 | File | `/admin/process_category_add.php` | High
87 | File | `/admin/process_category_edit.php` | High
88 | File | `/admin/profile.php` | High
89 | File | `/admin/property-details.php` | High
90 | File | `/Admin/Proses_Edit_Akun.php` | High
91 | File | `/admin/publishnews.php` | High
92 | File | `/admin/quote-details.php` | High
93 | File | `/admin/registration.php` | High
94 | File | `/admin/report.php` | High
95 | File | `/admin/reset-password.php` | High
96 | File | `/admin/room.php` | High
97 | File | `/admin/search-appointment.php` | High
98 | File | `/admin/search-invoices.php` | High
99 | File | `/admin/search-maid.php` | High
100 | File | `/admin/search-medicalcard.php` | High
101 | File | `/admin/search-property.php` | High
102 | File | `/admin/services/view_service.php` | High
103 | File | `/admin/sn_package/sn_https` | High
104 | File | `/admin/sou.php` | High
105 | ... | ... | ...

There are 926 more IOA items available (file, library, argument, input value, pattern, network port). Please use our online service to access the data.

## References

The following list contains _external sources_ which discuss the campaign and the associated activities:

* https://www.cisa.gov/news-events/cybersecurity-advisories/aa23-158a

## Literature

The following _articles_ explain our unique predictive cyber threat intelligence:

* [VulDB Cyber Threat Intelligence Documentation](https://vuldb.com/?kb.cti)
* [Cyber Threat Intelligence - Early Anticipation of Attacks](https://www.scip.ch/en/?labs.20201022)

## License

(c) [1997-2025](https://vuldb.com/?kb.changelog) by [vuldb.com](https://vuldb.com/?kb.about). All data on this page is shared under the license [CC BY-NC-SA 4.0](https://creativecommons.org/licenses/by-nc-sa/4.0/). Questions? Check the [FAQ](https://vuldb.com/?kb.faq), read the [documentation](https://vuldb.com/?kb) or [contact us](https://vuldb.com/?contact)!
