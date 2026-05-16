# Fallchill - Cyber Threat Intelligence

These _indicators_ were reported, collected, and generated during the [VulDB CTI analysis](https://vuldb.com/kb/cti) of the campaign known as _Fallchill_. The _activity monitoring_ correlates data from social media, forums, chat rooms, and darknet markets. It helps to determine associated actors, specific activities, expected intentions, emerging research, and ongoing attacks. Our unique _predictive model_ uses _big data_ to forecast activities and their characteristics.

_Live data_ and more _analysis capabilities_ are available at [https://vuldb.com/actor](https://vuldb.com/actor)

## Countries

These _countries_ are directly (e.g. origin of attacks) or indirectly (e.g. access by proxy) associated with Fallchill:

* [VN](https://vuldb.com/country/vn)

## Actors

These _actors_ are associated with Fallchill or other actors linked to the campaign.

ID | Actor | Confidence
-- | ----- | ----------
1 | [Lazarus](https://vuldb.com/actor/lazarus) | High

## IOC - Indicator of Compromise

These _indicators of compromise_ (IOC) indicate associated network resources which are known to be part of research and attack activities of Fallchill.

ID | IP address | Hostname | Actor | Confidence
-- | ---------- | -------- | ----- | ----------
1 | [5.79.99.169](https://vuldb.com/ip/5.79.99.169) | nsg037-19.divide.nl | [Lazarus](https://vuldb.com/actor/lazarus) | High
2 | [27.123.221.66](https://vuldb.com/ip/27.123.221.66) | 66-221.fiber.net.id | [Lazarus](https://vuldb.com/actor/lazarus) | High
3 | [36.71.90.4](https://vuldb.com/ip/36.71.90.4) | - | [Lazarus](https://vuldb.com/actor/lazarus) | High
4 | [41.92.208.194](https://vuldb.com/ip/41.92.208.194) | - | [Lazarus](https://vuldb.com/actor/lazarus) | High
5 | [41.92.208.196](https://vuldb.com/ip/41.92.208.196) | - | [Lazarus](https://vuldb.com/actor/lazarus) | High
6 | [41.92.208.197](https://vuldb.com/ip/41.92.208.197) | - | [Lazarus](https://vuldb.com/actor/lazarus) | High
7 | [50.62.168.157](https://vuldb.com/ip/50.62.168.157) | p3nwvpweb145.shr.prod.phx3.secureserver.net | [Lazarus](https://vuldb.com/actor/lazarus) | High
8 | [59.90.93.138](https://vuldb.com/ip/59.90.93.138) | static.bb.knl.59.90.93.138.bsnl.in | [Lazarus](https://vuldb.com/actor/lazarus) | High
9 | [62.243.45.227](https://vuldb.com/ip/62.243.45.227) | - | [Lazarus](https://vuldb.com/actor/lazarus) | High
10 | [64.29.144.201](https://vuldb.com/ip/64.29.144.201) | ntfw1c25.carrierzone.com | [Lazarus](https://vuldb.com/actor/lazarus) | High
11 | [66.175.41.191](https://vuldb.com/ip/66.175.41.191) | winVIPnatfl.hostopia.com | [Lazarus](https://vuldb.com/actor/lazarus) | High
12 | [66.232.121.65](https://vuldb.com/ip/66.232.121.65) | 66-232-121-65.static.hvvc.us | [Lazarus](https://vuldb.com/actor/lazarus) | High
13 | [66.242.128.11](https://vuldb.com/ip/66.242.128.11) | hdflns11.fl.hostdepot.net | [Lazarus](https://vuldb.com/actor/lazarus) | High
14 | [66.242.128.12](https://vuldb.com/ip/66.242.128.12) | hdflns12.fl.hostdepot.net | [Lazarus](https://vuldb.com/actor/lazarus) | High
15 | [66.242.128.13](https://vuldb.com/ip/66.242.128.13) | hdflns13.fl.hostdepot.net | [Lazarus](https://vuldb.com/actor/lazarus) | High
16 | [66.242.128.134](https://vuldb.com/ip/66.242.128.134) | hdflsf03.fl.hostdepot.net | [Lazarus](https://vuldb.com/actor/lazarus) | High
17 | [66.242.128.140](https://vuldb.com/ip/66.242.128.140) | hdflsf01.fl.hostdepot.net | [Lazarus](https://vuldb.com/actor/lazarus) | High
18 | ... | ... | ... | ...

There are 69 more IOC items available. Please use our online service to access the data.

## TTP - Tactics, Techniques, Procedures

_Tactics, techniques, and procedures_ (TTP) summarize the suspected MITRE ATT&CK techniques used within Fallchill. This data is unique as it uses our predictive model for actor profiling.

ID | Technique | Weakness | Description | Confidence
-- | --------- | -------- | ----------- | ----------
1 | T1006 | CWE-22, CWE-23, CWE-24, CWE-36 | Path Traversal | High
2 | T1055 | CWE-74 | Improper Neutralization of Data within XPath Expressions | High
3 | T1059 | CWE-88, CWE-94, CWE-1321 | Argument Injection | High
4 | T1059.007 | CWE-79, CWE-80 | Basic Cross Site Scripting | High
5 | ... | ... | ... | ...

There are 18 more TTP items available. Please use our online service to access the data.

## IOA - Indicator of Attack

These _indicators of attack_ (IOA) list the potential fragments used for technical activities like reconnaissance, exploitation, privilege escalation, and exfiltration during Fallchill. This data is unique as it uses our predictive model for actor profiling.

ID | Type | Indicator | Confidence
-- | ---- | --------- | ----------
1 | File | `/add-computer.php` | High
2 | File | `/add-customer.php` | High
3 | File | `/addcompany.php` | High
4 | File | `/addfriend.php` | High
5 | File | `/addproduct.php` | High
6 | File | `/admin-api/bpm/model/deploy` | High
7 | File | `/admin-profile.php` | High
8 | File | `/admin.php` | Medium
9 | File | `/admin/?page=inventory/view_inventory&id=2` | High
10 | File | `/admin/about_edit.php?action=modify` | High
11 | File | `/admin/actions/check-attendance.php` | High
12 | File | `/admin/actions/remove-announcement.php` | High
13 | File | `/admin/add-services.php` | High
14 | File | `/admin/add_account.php` | High
15 | File | `/admin/add_candidate_modal.php.` | High
16 | File | `/admin/add_sundaysch.php` | High
17 | File | `/admin/admin-profile.php` | High
18 | File | `/admin/admin/save` | High
19 | File | `/admin/adminHome.php` | High
20 | File | `/admin/admin_feature.php` | High
21 | File | `/admin/admin_index.php` | High
22 | File | `/admin/ajax.php?action=login2` | High
23 | File | `/admin/api/theme-edit/` | High
24 | File | `/admin/approve.php` | High
25 | File | `/admin/category.php` | High
26 | File | `/admin/category_save.php` | High
27 | File | `/admin/check_availability.php` | High
28 | File | `/admin/class.php` | High
29 | File | `/admin/class.php?dowhat=modifyclass` | High
30 | File | `/admin/config/list.html` | High
31 | File | `/admin/deleteitem.php` | High
32 | File | `/admin/delete_account.php` | High
33 | File | `/admin/delete_activity.php` | High
34 | File | `/admin/department/add` | High
35 | File | `/admin/doctors.php` | High
36 | File | `/admin/edit-art-medium-detail.php` | High
37 | File | `/admin/edit-art-product-detail.php?editid=2` | High
38 | File | `/admin/edit-category.php` | High
39 | File | `/admin/edit-pass-detail.php` | High
40 | File | `/admin/edit-subcategory.php` | High
41 | File | `/admin/edit-user-profile.php` | High
42 | File | `/admin/edit.php` | High
43 | File | `/admin/edit_admin.php` | High
44 | File | `/admin/edit_room.php` | High
45 | File | `/admin/employee/index.php?view=edit` | High
46 | File | `/admin/extend/list.html` | High
47 | File | `/admin/fields/manage_field.php` | High
48 | File | `/admin/freelist_main.php` | High
49 | File | `/admin/general-setting` | High
50 | File | `/admin/group/list/` | High
51 | File | `/admin/index.php` | High
52 | File | `/admin/inquiries/view_inquiry.php` | High
53 | File | `/admin/login.php` | High
54 | File | `/admin/manage-users.php` | High
55 | File | `/admin/manage_theater.php` | High
56 | File | `/admin/Member/index.html` | High
57 | File | `/admin/options-theme.php` | High
58 | File | `/admin/orders/update_status.php` | High
59 | File | `/admin/save_student.php` | High
60 | File | `/admin/search-appointment.php` | High
61 | File | `/admin/search-booking-request.php` | High
62 | File | `/admin/search-maid.php` | High
63 | File | `/admin/subcategory.php` | High
64 | File | `/admin/templets_one_edit.php` | High
65 | File | `/admin/update-image1.php` | High
66 | File | `/admin/update_s3.php` | High
67 | File | `/admin/update_student.php` | High
68 | File | `/admin/update_user.php` | High
69 | File | `/admin/user.php` | High
70 | File | `/administrator/addcategory.php` | High
71 | File | `/administrator/index.php` | High
72 | File | `/admin_class.php` | High
73 | File | `/admin_system/api.php` | High
74 | File | `/agent/act` | Medium
75 | File | `/ajax.php?action=delete_loan` | High
76 | File | `/ajax.php?action=delete_sales` | High
77 | File | `/ajax.php?action=delete_trainer` | High
78 | File | `/ajax.php?action=save_customer` | High
79 | File | `/ajax.php?action=save_plan` | High
80 | File | `/ajax.php?action=save_student` | High
81 | File | `/ajax/action.php` | High
82 | File | `/ajax/loadShopInfo.php` | High
83 | File | `/aloneReport/index.do/../../aloneReport/download.do;othersusrlogout.do` | High
84 | File | `/api/config/list` | High
85 | File | `/app/sms.php` | Medium
86 | File | `/App/Tpl/Admin/Default/Channel/index.html.Attackers` | High
87 | File | `/application/index/controller/Pay.php` | High
88 | File | `/apps/system/router/upload.go` | High
89 | File | `/assets/uploadNotes.php` | High
90 | File | `/assets/uploadSllyabus.php` | High
91 | File | `/att_add.php` | Medium
92 | File | `/Auth.php` | Medium
93 | File | `/b2c/package-information` | High
94 | File | `/billaction.php` | High
95 | File | `/bin/httpd` | Medium
96 | File | `/boafrm/formDosCfg` | High
97 | File | `/boafrm/formPortFw` | High
98 | File | `/brand/queryAll` | High
99 | File | `/bwdates-reports-details.php` | High
100 | File | `/C6/JHSoft.Web.AcceptAip/AcceptShow.aspx/` | High
101 | File | `/calculate` | Medium
102 | File | `/categorywise-products.php` | High
103 | File | `/CDGServer3/workflowE/useractivate/updateorg.jsp` | High
104 | File | `/cgi-bin/cstecgi.cgi` | High
105 | File | `/cgi-bin/cstecgi.cgi?action=save&setting` | High
106 | File | `/cgi-bin/firewall.cgi` | High
107 | File | `/cgi-bin/JSONAPI` | High
108 | ... | ... | ...

There are 953 more IOA items available (file, library, argument, input value, pattern, network port). Please use our online service to access the data.

## References

The following list contains _external sources_ which discuss the campaign and the associated activities:

* https://us-cert.cisa.gov/ncas/alerts/TA17-318A

## Literature

The following _articles_ explain our unique predictive cyber threat intelligence:

* [VulDB Cyber Threat Intelligence Documentation](https://vuldb.com/kb/cti)
* [Cyber Threat Intelligence - Early Anticipation of Attacks](https://www.scip.ch/en/?labs.20201022)

## License

(c) [1997-2026](https://vuldb.com/kb/changelog) by [vuldb.com](https://vuldb.com/kb/about). All data on this page is shared under the license [CC BY-NC-SA 4.0](https://creativecommons.org/licenses/by-nc-sa/4.0/). Questions? Check the [FAQ](https://vuldb.com/kb/faq), read the [documentation](https://vuldb.com/kb) or [contact us](https://vuldb.com/contact)!
