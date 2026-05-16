# Salesforce Experience Cloud Site - Cyber Threat Intelligence

These _indicators_ were reported, collected, and generated during the [VulDB CTI analysis](https://vuldb.com/kb/cti) of the campaign known as _Salesforce Experience Cloud Site_. The _activity monitoring_ correlates data from social media, forums, chat rooms, and darknet markets. It helps to determine associated actors, specific activities, expected intentions, emerging research, and ongoing attacks. Our unique _predictive model_ uses _big data_ to forecast activities and their characteristics.

_Live data_ and more _analysis capabilities_ are available at [https://vuldb.com/actor](https://vuldb.com/actor)

## Countries

These _countries_ are directly (e.g. origin of attacks) or indirectly (e.g. access by proxy) associated with Salesforce Experience Cloud Site:

* [VN](https://vuldb.com/country/vn)
* [SG](https://vuldb.com/country/sg)

## Actors

These _actors_ are associated with Salesforce Experience Cloud Site or other actors linked to the campaign.

ID | Actor | Confidence
-- | ----- | ----------
1 | [ShinyHunters](https://vuldb.com/actor/shinyhunters) | High

## IOC - Indicator of Compromise

These _indicators of compromise_ (IOC) indicate associated network resources which are known to be part of research and attack activities of Salesforce Experience Cloud Site.

ID | IP address | Hostname | Actor | Confidence
-- | ---------- | -------- | ----- | ----------
1 | [54.251.184.9](https://vuldb.com/ip/54.251.184.9) | ec2-54-251-184-9.ap-southeast-1.compute.amazonaws.com | [ShinyHunters](https://vuldb.com/actor/shinyhunters) | Medium
2 | [88.216.68.137](https://vuldb.com/ip/88.216.68.137) | ip-88-216-68-137.010.ptr.cherryservers.net | [ShinyHunters](https://vuldb.com/actor/shinyhunters) | High
3 | [138.199.60.10](https://vuldb.com/ip/138.199.60.10) | - | [ShinyHunters](https://vuldb.com/actor/shinyhunters) | High
4 | ... | ... | ... | ...

There are 1 more IOC items available. Please use our online service to access the data.

## TTP - Tactics, Techniques, Procedures

_Tactics, techniques, and procedures_ (TTP) summarize the suspected MITRE ATT&CK techniques used within Salesforce Experience Cloud Site. This data is unique as it uses our predictive model for actor profiling.

ID | Technique | Weakness | Description | Confidence
-- | --------- | -------- | ----------- | ----------
1 | T1006 | CWE-22, CWE-24 | Path Traversal | High
2 | T1055 | CWE-74 | Improper Neutralization of Data within XPath Expressions | High
3 | T1059 | CWE-88, CWE-94, CWE-1321 | Argument Injection | High
4 | T1059.007 | CWE-79, CWE-80 | Basic Cross Site Scripting | High
5 | ... | ... | ... | ...

There are 15 more TTP items available. Please use our online service to access the data.

## IOA - Indicator of Attack

These _indicators of attack_ (IOA) list the potential fragments used for technical activities like reconnaissance, exploitation, privilege escalation, and exfiltration during Salesforce Experience Cloud Site. This data is unique as it uses our predictive model for actor profiling.

ID | Type | Indicator | Confidence
-- | ---- | --------- | ----------
1 | File | `/acceptoffres.php` | High
2 | File | `/add-computer.php` | High
3 | File | `/add-customer.php` | High
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
20 | File | `/admin/admin_class.php` | High
21 | File | `/admin/admin_feature.php` | High
22 | File | `/admin/admin_index.php` | High
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
66 | File | `/admin/update-progress.php` | High
67 | File | `/admin/update_s3.php` | High
68 | File | `/admin/update_student.php` | High
69 | File | `/admin/update_user.php` | High
70 | File | `/admin/user.php` | High
71 | File | `/admin/user/updatePwd` | High
72 | File | `/administrator/addcategory.php` | High
73 | File | `/administrator/index.php` | High
74 | File | `/admin_class.php` | High
75 | File | `/admin_system/api.php` | High
76 | File | `/agent/act` | Medium
77 | File | `/ajax.php?action=delete_loan` | High
78 | File | `/ajax.php?action=delete_trainer` | High
79 | File | `/ajax.php?action=save_customer` | High
80 | File | `/ajax.php?action=save_plan` | High
81 | File | `/ajax.php?action=save_student` | High
82 | File | `/ajax/action.php` | High
83 | File | `/ajax/loadShopInfo.php` | High
84 | File | `/aloneReport/index.do/../../aloneReport/download.do;othersusrlogout.do` | High
85 | File | `/api/config/list` | High
86 | File | `/app/sms.php` | Medium
87 | File | `/App/Tpl/Admin/Default/Channel/index.html.Attackers` | High
88 | File | `/application/index/controller/Pay.php` | High
89 | File | `/apps/system/router/upload.go` | High
90 | File | `/assets/uploadNotes.php` | High
91 | File | `/assets/uploadSllyabus.php` | High
92 | File | `/att_add.php` | Medium
93 | File | `/Auth.php` | Medium
94 | File | `/b2c/package-information` | High
95 | File | `/billaction.php` | High
96 | File | `/bin/httpd` | Medium
97 | File | `/boafrm/formDosCfg` | High
98 | File | `/boafrm/formPortFw` | High
99 | File | `/brand/queryAll` | High
100 | File | `/bwdates-reports-details.php` | High
101 | File | `/C6/JHSoft.Web.AcceptAip/AcceptShow.aspx/` | High
102 | File | `/calculate` | Medium
103 | File | `/categorywise-products.php` | High
104 | File | `/CDGServer3/workflowE/useractivate/updateorg.jsp` | High
105 | File | `/cgi-bin/cstecgi.cgi` | High
106 | File | `/cgi-bin/cstecgi.cgi?action=save&setting` | High
107 | File | `/cgi-bin/firewall.cgi` | High
108 | File | `/cgi-bin/JSONAPI` | High
109 | ... | ... | ...

There are 970 more IOA items available (file, library, argument, input value, pattern, network port). Please use our online service to access the data.

## References

The following list contains _external sources_ which discuss the campaign and the associated activities:

* https://www.reco.ai/blog/inside-the-shinyhunters-experience-cloud-campaign-iocs-detection-logic-and-whats-at-risk

## Literature

The following _articles_ explain our unique predictive cyber threat intelligence:

* [VulDB Cyber Threat Intelligence Documentation](https://vuldb.com/kb/cti)
* [Cyber Threat Intelligence - Early Anticipation of Attacks](https://www.scip.ch/en/?labs.20201022)

## License

(c) [1997-2026](https://vuldb.com/kb/changelog) by [vuldb.com](https://vuldb.com/kb/about). All data on this page is shared under the license [CC BY-NC-SA 4.0](https://creativecommons.org/licenses/by-nc-sa/4.0/). Questions? Check the [FAQ](https://vuldb.com/kb/faq), read the [documentation](https://vuldb.com/kb) or [contact us](https://vuldb.com/contact)!
