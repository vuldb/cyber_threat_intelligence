# ShinyHunters - Cyber Threat Intelligence

These _indicators_ were reported, collected, and generated during the [VulDB CTI analysis](https://vuldb.com/kb/cti) of the actor known as [ShinyHunters](https://vuldb.com/actor/shinyhunters). The _activity monitoring_ correlates data from social media, forums, chat rooms, and darknet markets. It helps to determine associated actors, specific activities, expected intentions, emerging research, and ongoing attacks. Our unique _predictive model_ uses _big data_ to forecast activities and their characteristics.

_Live data_ and more _analysis capabilities_ are available at [https://vuldb.com/actor/shinyhunters](https://vuldb.com/actor/shinyhunters)

## Campaigns

The following _campaigns_ are known and can be associated with ShinyHunters:

* Salesforce Experience Cloud Site

## Countries

These _countries_ are directly (e.g. origin of attacks) or indirectly (e.g. access by proxy) associated with ShinyHunters:

* [VN](https://vuldb.com/country/vn)
* [SG](https://vuldb.com/country/sg)
* [DE](https://vuldb.com/country/de)
* ...

There are 10 more country items available. Please use our online service to access the data.

## IOC - Indicator of Compromise

These _indicators of compromise_ (IOC) indicate associated network resources which are known to be part of research and attack activities of ShinyHunters.

ID | IP address | Hostname | Campaign | Confidence
-- | ---------- | -------- | -------- | ----------
1 | [5.47.87.202](https://vuldb.com/ip/5.47.87.202) | - | - | High
2 | [37.19.210.21](https://vuldb.com/ip/37.19.210.21) | unn-37-19-210-21.datapacket.com | - | High
3 | [37.19.210.34](https://vuldb.com/ip/37.19.210.34) | unn-37-19-210-34.datapacket.com | - | High
4 | [45.86.221.146](https://vuldb.com/ip/45.86.221.146) | - | - | High
5 | [45.134.140.144](https://vuldb.com/ip/45.134.140.144) | unn-45-134-140-144.datapacket.com | - | High
6 | [45.134.142.200](https://vuldb.com/ip/45.134.142.200) | unn-45-134-142-200.datapacket.com | - | High
7 | [45.155.91.99](https://vuldb.com/ip/45.155.91.99) | - | - | High
8 | [54.251.184.9](https://vuldb.com/ip/54.251.184.9) | ec2-54-251-184-9.ap-southeast-1.compute.amazonaws.com | Salesforce Experience Cloud Site | Medium
9 | [66.63.167.147](https://vuldb.com/ip/66.63.167.147) | 66.63.167.147.static.quadranet.com | - | High
10 | [66.115.189.247](https://vuldb.com/ip/66.115.189.247) | - | - | High
11 | [79.127.217.44](https://vuldb.com/ip/79.127.217.44) | unn-79-127-217-44.datapacket.com | - | High
12 | [87.249.134.11](https://vuldb.com/ip/87.249.134.11) | unn-87-249-134-11.datapacket.com | - | High
13 | [88.216.68.137](https://vuldb.com/ip/88.216.68.137) | ip-88-216-68-137.010.ptr.cherryservers.net | Salesforce Experience Cloud Site | High
14 | [93.115.0.49](https://vuldb.com/ip/93.115.0.49) | - | - | High
15 | ... | ... | ... | ...

There are 56 more IOC items available. Please use our online service to access the data.

## TTP - Tactics, Techniques, Procedures

_Tactics, techniques, and procedures_ (TTP) summarize the suspected MITRE ATT&CK techniques used by _ShinyHunters_. This data is unique as it uses our predictive model for actor profiling.

ID | Technique | Weakness | Description | Confidence
-- | --------- | -------- | ----------- | ----------
1 | T1006 | CWE-22, CWE-24 | Path Traversal | High
2 | T1055 | CWE-74 | Improper Neutralization of Data within XPath Expressions | High
3 | T1059 | CWE-88, CWE-94, CWE-1321 | Argument Injection | High
4 | T1059.007 | CWE-79, CWE-80 | Basic Cross Site Scripting | High
5 | ... | ... | ... | ...

There are 16 more TTP items available. Please use our online service to access the data.

## IOA - Indicator of Attack

These _indicators of attack_ (IOA) list the potential fragments used for technical activities like reconnaissance, exploitation, privilege escalation, and exfiltration by ShinyHunters. This data is unique as it uses our predictive model for actor profiling.

ID | Type | Indicator | Confidence
-- | ---- | --------- | ----------
1 | File | `/add-computer.php` | High
2 | File | `/add-customer.php` | High
3 | File | `/addcat.php` | Medium
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
22 | File | `/admin/approve.php` | High
23 | File | `/admin/category.php` | High
24 | File | `/admin/category_save.php` | High
25 | File | `/admin/check_availability.php` | High
26 | File | `/admin/class.php` | High
27 | File | `/admin/class.php?dowhat=modifyclass` | High
28 | File | `/admin/config/list.html` | High
29 | File | `/admin/deleteitem.php` | High
30 | File | `/admin/delete_account.php` | High
31 | File | `/admin/delete_activity.php` | High
32 | File | `/admin/doctors.php` | High
33 | File | `/admin/edit-art-medium-detail.php` | High
34 | File | `/admin/edit-art-product-detail.php?editid=2` | High
35 | File | `/admin/edit-category.php` | High
36 | File | `/admin/edit-pass-detail.php` | High
37 | File | `/admin/edit-subcategory.php` | High
38 | File | `/admin/edit-user-profile.php` | High
39 | File | `/admin/edit_room.php` | High
40 | File | `/admin/employee/index.php?view=edit` | High
41 | File | `/admin/extend/list.html` | High
42 | File | `/admin/freelist_main.php` | High
43 | File | `/admin/general-setting` | High
44 | File | `/admin/group/list/` | High
45 | File | `/admin/index.php` | High
46 | File | `/admin/inquiries/view_inquiry.php` | High
47 | File | `/admin/login.php` | High
48 | File | `/admin/manage-users.php` | High
49 | File | `/admin/manage_theater.php` | High
50 | File | `/admin/Member/index.html` | High
51 | File | `/admin/options-theme.php` | High
52 | File | `/admin/orders/update_status.php` | High
53 | File | `/admin/save_student.php` | High
54 | File | `/admin/search-appointment.php` | High
55 | File | `/admin/search-booking-request.php` | High
56 | File | `/admin/search-maid.php` | High
57 | File | `/admin/subcategory.php` | High
58 | File | `/admin/transaction/deposit` | High
59 | File | `/admin/update-image1.php` | High
60 | File | `/admin/update_s3.php` | High
61 | File | `/admin/update_student.php` | High
62 | File | `/admin/update_user.php` | High
63 | File | `/admin/user.php` | High
64 | File | `/admin/user/updatePwd` | High
65 | File | `/administrator/addcategory.php` | High
66 | File | `/admin_class.php` | High
67 | File | `/admin_system/api.php` | High
68 | File | `/agent/act` | Medium
69 | File | `/ajax.php?action=delete_loan` | High
70 | File | `/ajax.php?action=delete_trainer` | High
71 | File | `/ajax.php?action=save_customer` | High
72 | File | `/ajax.php?action=save_plan` | High
73 | File | `/ajax.php?action=save_student` | High
74 | File | `/ajax/action.php` | High
75 | File | `/ajax/loadShopInfo.php` | High
76 | File | `/aloneReport/index.do/../../aloneReport/download.do;othersusrlogout.do` | High
77 | File | `/api/config/list` | High
78 | File | `/app/sms.php` | Medium
79 | File | `/App/Tpl/Admin/Default/Channel/index.html.Attackers` | High
80 | File | `/application/index/controller/Pay.php` | High
81 | File | `/apps/system/router/upload.go` | High
82 | File | `/assets/uploadNotes.php` | High
83 | File | `/assets/uploadSllyabus.php` | High
84 | File | `/att_add.php` | Medium
85 | File | `/Auth.php` | Medium
86 | File | `/b2c/package-information` | High
87 | File | `/billaction.php` | High
88 | File | `/bin/httpd` | Medium
89 | File | `/boaform/admin/formUserTracert` | High
90 | File | `/boafrm/formDosCfg` | High
91 | File | `/boafrm/formPortFw` | High
92 | File | `/brand/queryAll` | High
93 | File | `/bwdates-reports-details.php` | High
94 | File | `/C6/JHSoft.Web.AcceptAip/AcceptShow.aspx/` | High
95 | File | `/calculate` | Medium
96 | File | `/categorywise-products.php` | High
97 | File | `/CDGServer3/workflowE/useractivate/updateorg.jsp` | High
98 | File | `/cgi-bin/cstecgi.cgi` | High
99 | File | `/cgi-bin/cstecgi.cgi?action=save&setting` | High
100 | File | `/cgi-bin/firewall.cgi` | High
101 | File | `/cgi-bin/JSONAPI` | High
102 | File | `/cgi-bin/webproc?getpage=html/index.html&var:menu=24gwlan&var:page=24G_basic` | High
103 | File | `/cgi-bin/wireless.cgi` | High
104 | File | `/cgi/sshcheck.cgi` | High
105 | File | `/check_profile_old.php` | High
106 | ... | ... | ...

There are 942 more IOA items available (file, library, argument, input value, pattern, network port). Please use our online service to access the data.

## References

The following list contains _external sources_ which discuss the actor and the associated activities:

* https://www.reco.ai/blog/inside-the-shinyhunters-experience-cloud-campaign-iocs-detection-logic-and-whats-at-risk
* https://www.trustwave.com/en-us/resources/blogs/spiderlabs-blog/threat-advisory-snowflake-data-breach-impacts-its-clients/

## Literature

The following _articles_ explain our unique predictive cyber threat intelligence:

* [VulDB Cyber Threat Intelligence Documentation](https://vuldb.com/kb/cti
* [Cyber Threat Intelligence - Early Anticipation of Attacks](https://www.scip.ch/en/?labs.20201022)

## License

(c) [1997-2026](https://vuldb.com/kb/changelog) by [vuldb.com](https://vuldb.com/kb/about). All data on this page is shared under the license [CC BY-NC-SA 4.0](https://creativecommons.org/licenses/by-nc-sa/4.0/). Questions? Check the [FAQ](https://vuldb.com/kb/faq), read the [documentation](https://vuldb.com/kb) or [contact us](https://vuldb.com/contact)!
