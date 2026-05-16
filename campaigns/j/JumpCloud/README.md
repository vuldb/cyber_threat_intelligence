# JumpCloud - Cyber Threat Intelligence

These _indicators_ were reported, collected, and generated during the [VulDB CTI analysis](https://vuldb.com/?kb.cti) of the campaign known as _JumpCloud_. The _activity monitoring_ correlates data from social media, forums, chat rooms, and darknet markets. It helps to determine associated actors, specific activities, expected intentions, emerging research, and ongoing attacks. Our unique _predictive model_ uses _big data_ to forecast activities and their characteristics.

_Live data_ and more _analysis capabilities_ are available at [https://vuldb.com/?actor](https://vuldb.com/?actor)

## Countries

These _countries_ are directly (e.g. origin of attacks) or indirectly (e.g. access by proxy) associated with JumpCloud:

* [US](https://vuldb.com/?country.us)
* [CH](https://vuldb.com/?country.ch)
* [RU](https://vuldb.com/?country.ru)
* ...

There are 13 more country items available. Please use our online service to access the data.

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
1 | T1006 | CWE-22, CWE-24, CWE-35, CWE-36, CWE-37 | Path Traversal | High
2 | T1040 | CWE-319 | Authentication Bypass by Capture-replay | High
3 | T1055 | CWE-74 | Improper Neutralization of Data within XPath Expressions | High
4 | T1059 | CWE-94 | Argument Injection | High
5 | ... | ... | ... | ...

There are 18 more TTP items available. Please use our online service to access the data.

## IOA - Indicator of Attack

These _indicators of attack_ (IOA) list the potential fragments used for technical activities like reconnaissance, exploitation, privilege escalation, and exfiltration during JumpCloud. This data is unique as it uses our predictive model for actor profiling.

ID | Type | Indicator | Confidence
-- | ---- | --------- | ----------
1 | File | `/?explorer/index/zip` | High
2 | File | `/add-subadmin.php` | High
3 | File | `/addcustcom.php` | High
4 | File | `/addcustind.php` | High
5 | File | `/addmem.php` | Medium
6 | File | `/addProduct.php` | High
7 | File | `/addstock.php` | High
8 | File | `/add_new_invoice.php` | High
9 | File | `/add_user.php` | High
10 | File | `/admin.php` | Medium
11 | File | `/admin/?page=zone` | High
12 | File | `/admin/aboutus.php` | High
13 | File | `/admin/actions/check-attendance.php` | High
14 | File | `/admin/add-module.php` | High
15 | File | `/admin/add-table.php` | High
16 | File | `/admin/add_expenses.php` | High
17 | File | `/admin/add_subject.php` | High
18 | File | `/Admin/adminlogin.php` | High
19 | File | `/admin/admin_running.php` | High
20 | File | `/Admin/akun_edit.php` | High
21 | File | `/admin/changeimage.php` | High
22 | File | `/Admin/changepassword.php` | High
23 | File | `/admin/checklogin.php` | High
24 | File | `/admin/class.php` | High
25 | File | `/admin/completed-requests.php` | High
26 | File | `/admin/content/editor` | High
27 | File | `/admin/controller/faculty_controller.php` | High
28 | File | `/admin/deleteuser.php` | High
29 | File | `/admin/delete_s6.php` | High
30 | File | `/admin/delete_user.php` | High
31 | File | `/admin/edit-art-product-detail.php?editid=2` | High
32 | File | `/admin/edit-brand.php` | High
33 | File | `/admin/edit-card-detail.php` | High
34 | File | `/admin/edit-user.php` | High
35 | File | `/admin/edit_class.php` | High
36 | File | `/admin/edit_room.php` | High
37 | File | `/admin/edit_subject.php` | High
38 | File | `/admin/includes/edit_post.php` | High
39 | File | `/admin/index.php` | High
40 | File | `/admin/index.php?page=user-profile` | High
41 | File | `/admin/invoiceprint.php` | High
42 | File | `/Admin/login.php` | High
43 | File | `/admin/login.php` | High
44 | File | `/admin/mechanics/manage_mechanic.php` | High
45 | File | `/admin/modules/room/index.php` | High
46 | File | `/admin/process_category_edit.php` | High
47 | File | `/admin/profile.php` | High
48 | File | `/Admin/Proses_Edit_Akun.php` | High
49 | File | `/admin/receipt.php` | High
50 | File | `/Admin/resultdetails.php` | High
51 | File | `/admin/robot.php` | High
52 | File | `/admin/search-invoices.php` | High
53 | File | `/admin/search-medicalcard.php` | High
54 | File | `/admin/tags/save` | High
55 | File | `/admin/twitter.php` | High
56 | File | `/admin/user-bookings.php` | High
57 | File | `/admin/user/index.php?view=edit` | High
58 | File | `/admin/view-card-detail.php` | High
59 | File | `/admin/view-enquiry.php` | High
60 | File | `/admin/voters_delete.php` | High
61 | File | `/admin/yesterday-reg-users.php` | High
62 | File | `/adminapi/system/file/openfile` | High
63 | File | `/administrator/addcategory.php` | High
64 | File | `/Administrator/PHP/AdminAddUser.php` | High
65 | File | `/Administrator/PHP/AdminDeleteUser.php` | High
66 | File | `/Administrator/PHP/AdminEditUser.php` | High
67 | File | `/Administrator/PHP/AdminReply.php` | High
68 | File | `/Administrator/PHP/AdminUpdateUser.php` | High
69 | File | `/Administrator/PHP/AdminViewSongs.php` | High
70 | File | `/advancesearch.php` | High
71 | File | `/adv_mac_filter.php` | High
72 | File | `/ajax.php?action=delete_member` | High
73 | File | `/ajax.php?action=delete_product` | High
74 | File | `/ajax.php?action=delete_user` | High
75 | File | `/ajax.php?action=login` | High
76 | File | `/ajax.php?action=save_deductions` | High
77 | File | `/ajax.php?action=save_payroll` | High
78 | File | `/ajax.php?Ajax=GetModal_Sensor_Graph` | High
79 | File | `/alphaware/summary.php` | High
80 | File | `/animalsupdate.php` | High
81 | File | `/api/File/downloadFile` | High
82 | File | `/api/settings` | High
83 | File | `/api/sys/login` | High
84 | File | `/api/wizard/getCapability` | High
85 | File | `/api/wizard/getDualbandSync` | High
86 | File | `/api/workspace/:workspace-slug/update` | High
87 | File | `/app/api/controller/collect.php` | High
88 | File | `/app/api/v1/openvpn.py` | High
89 | File | `/app/controller/Api.php` | High
90 | File | `/app/register.php?action=reg` | High
91 | File | `/app/sys1.php` | High
92 | File | `/assetsGroupReport/assetsService.j%73p` | High
93 | File | `/auth.asp` | Medium
94 | File | `/authentication.cgi` | High
95 | File | `/backend/doc/his_doc_update-account.php` | High
96 | ... | ... | ...

There are 848 more IOA items available (file, library, argument, input value, pattern, network port). Please use our online service to access the data.

## References

The following list contains _external sources_ which discuss the campaign and the associated activities:

* https://jumpcloud.com/support/july-2023-iocs

## Literature

The following _articles_ explain our unique predictive cyber threat intelligence:

* [VulDB Cyber Threat Intelligence Documentation](https://vuldb.com/?kb.cti)
* [Cyber Threat Intelligence - Early Anticipation of Attacks](https://www.scip.ch/en/?labs.20201022)

## License

(c) [1997-2026](https://vuldb.com/?kb.changelog) by [vuldb.com](https://vuldb.com/?kb.about). All data on this page is shared under the license [CC BY-NC-SA 4.0](https://creativecommons.org/licenses/by-nc-sa/4.0/). Questions? Check the [FAQ](https://vuldb.com/?kb.faq), read the [documentation](https://vuldb.com/?kb) or [contact us](https://vuldb.com/?contact)!
