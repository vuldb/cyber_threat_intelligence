# GroundPeony - Cyber Threat Intelligence

These _indicators_ were reported, collected, and generated during the [VulDB CTI analysis](https://vuldb.com/?kb.cti) of the actor known as [GroundPeony](https://vuldb.com/?actor.groundpeony). The _activity monitoring_ correlates data from social media, forums, chat rooms, and darknet markets. It helps to determine associated actors, specific activities, expected intentions, emerging research, and ongoing attacks. Our unique _predictive model_ uses _big data_ to forecast activities and their characteristics.

_Live data_ and more _analysis capabilities_ are available at [https://vuldb.com/?actor.groundpeony](https://vuldb.com/?actor.groundpeony)

## Campaigns

The following _campaigns_ are known and can be associated with GroundPeony:

* CVE-2022-30190

## IOC - Indicator of Compromise

These _indicators of compromise_ (IOC) indicate associated network resources which are known to be part of research and attack activities of GroundPeony.

ID | IP address | Hostname | Campaign | Confidence
-- | ---------- | -------- | -------- | ----------
1 | [103.199.17.184](https://vuldb.com/?ip.103.199.17.184) | - | CVE-2022-30190 | High
2 | [160.20.145.111](https://vuldb.com/?ip.160.20.145.111) | 111.145.20.160 | CVE-2022-30190 | High
3 | [172.93.189.239](https://vuldb.com/?ip.172.93.189.239) | - | CVE-2022-30190 | High

## TTP - Tactics, Techniques, Procedures

_Tactics, techniques, and procedures_ (TTP) summarize the suspected MITRE ATT&CK techniques used by _GroundPeony_. This data is unique as it uses our predictive model for actor profiling.

ID | Technique | Weakness | Description | Confidence
-- | --------- | -------- | ----------- | ----------
1 | T1006 | CWE-22, CWE-24, CWE-36 | Path Traversal | High
2 | T1040 | CWE-319 | Authentication Bypass by Capture-replay | High
3 | T1055 | CWE-74 | Improper Neutralization of Data within XPath Expressions | High
4 | T1059 | CWE-94, CWE-1321 | Argument Injection | High
5 | ... | ... | ... | ...

There are 17 more TTP items available. Please use our online service to access the data.

## IOA - Indicator of Attack

These _indicators of attack_ (IOA) list the potential fragments used for technical activities like reconnaissance, exploitation, privilege escalation, and exfiltration by GroundPeony. This data is unique as it uses our predictive model for actor profiling.

ID | Type | Indicator | Confidence
-- | ---- | --------- | ----------
1 | File | `/?p=products` | Medium
2 | File | `/Account/login.php` | High
3 | File | `/actuator/heapdump` | High
4 | File | `/add_classes.php` | High
5 | File | `/add_members.php` | High
6 | File | `/admin-api/upload_image` | High
7 | File | `/admin.php?p=/Area/index#tab=t2` | High
8 | File | `/admin/` | Low
9 | File | `/admin/aboutus.php` | High
10 | File | `/admin/addTithes.php` | High
11 | File | `/admin/admin-profile.php` | High
12 | File | `/admin/admin.php` | High
13 | File | `/admin/adminHome.php` | High
14 | File | `/admin/admin_cl.php?mudi=revPwd` | High
15 | File | `/admin/app/product.php` | High
16 | File | `/admin/app/profile_crud.php` | High
17 | File | `/admin/app/service_crud.php` | High
18 | File | `/admin/applicants/controller.php` | High
19 | File | `/admin/bookdate.php` | High
20 | File | `/admin/booking-bwdates-reports-details.php` | High
21 | File | `/admin/booking-search.php` | High
22 | File | `/admin/booktime.php` | High
23 | File | `/admin/category/index.php` | High
24 | File | `/admin/communitymanagement.php` | High
25 | File | `/admin/company/index.php` | High
26 | File | `/admin/conferences/get-all-status/` | High
27 | File | `/admin/conferences/list/` | High
28 | File | `/admin/contactus.php` | High
29 | File | `/admin/court-type` | High
30 | File | `/admin/div_data/delete?divId=9` | High
31 | File | `/admin/edit-services.php` | High
32 | File | `/admin/employee/controller.php` | High
33 | File | `/admin/employee/index.php` | High
34 | File | `/admin/extended` | High
35 | File | `/admin/featured.php` | High
36 | File | `/admin/forgot-password.php` | High
37 | File | `/admin/general-setting` | High
38 | File | `/admin/general/change-lang` | High
39 | File | `/admin/googleads.php` | High
40 | File | `/admin/group` | Medium
41 | File | `/Admin/login.php` | High
42 | File | `/admin/login.php` | High
43 | File | `/admin/maintenance/manage_category.php` | High
44 | File | `/Admin/News.php` | High
45 | File | `/admin/newsletter1.php` | High
46 | File | `/admin/operations/expense_category.php` | High
47 | File | `/admin/pages/edit_chicken.php` | High
48 | File | `/admin/pages/update_go.php` | High
49 | File | `/admin/payment.php` | High
50 | File | `/admin/photo.php` | High
51 | File | `/admin/receipt.php` | High
52 | File | `/admin/renewaldue.php` | High
53 | File | `/admin/request-received-bydonar.php` | High
54 | File | `/admin/rooms.php` | High
55 | File | `/admin/search.php` | High
56 | File | `/admin/searchview.php` | High
57 | File | `/admin/twitter.php` | High
58 | File | `/admin/update-rooms.php` | High
59 | File | `/admin/update-users.php` | High
60 | File | `/admin/user-search.php` | High
61 | File | `/admin/usermanagement.php` | High
62 | File | `/admin/users.php` | High
63 | File | `/admin/vacancy/controller.php` | High
64 | File | `/admin/vendor` | High
65 | File | `/admin/view_sendlist.php` | High
66 | File | `/adminapi/system/crud` | High
67 | File | `/adminapi/system/file/openfile` | High
68 | File | `/adminPage/main/upload` | High
69 | File | `/adminPage/www/addOver` | High
70 | File | `/adminpanel/admin/facebox_modal/updateExaminee.php` | High
71 | File | `/adminpanel/admin/query/deleteCourseExe.php` | High
72 | File | `/adminpanel/admin/query/loginExe.php` | High
73 | File | `/admin_route/inc_service_credits.php` | High
74 | File | `/api/controllers/admin/app/AppController.php` | High
75 | File | `/api/controllers/admin/app/ComboController.php` | High
76 | File | `/api/controllers/common/UploadsController.php` | High
77 | File | `/api/controllers/merchant/app/ComboController.php` | High
78 | File | `/api/controllers/merchant/shop/PosterController.php` | High
79 | File | `/app/ajax/search_sales_report.php` | High
80 | File | `/app/Http/Controllers/ImageController.php` | High
81 | File | `/app/index/controller/Common.php` | High
82 | File | `/app/middleware/TokenVerify.php` | High
83 | File | `/application/index/controller/Databasesource.php` | High
84 | File | `/application/index/controller/Datament.php` | High
85 | File | `/application/index/controller/File.php` | High
86 | File | `/application/index/controller/Icon.php` | High
87 | File | `/application/index/controller/Pay.php` | High
88 | File | `/application/index/controller/Screen.php` | High
89 | File | `/application/index/controller/Unity.php` | High
90 | File | `/application/plugins/controller/Upload.php` | High
91 | File | `/application/websocket/controller/Setting.php` | High
92 | File | `/apps/reg_go.php` | High
93 | File | `/apps/system/router/upload.go` | High
94 | File | `/cardo/api` | Medium
95 | File | `/category.php` | High
96 | File | `/cgi-bin/cstecgi.cgi` | High
97 | File | `/cgi-bin/nas_sharing.cgi` | High
98 | ... | ... | ...

There are 865 more IOA items available (file, library, argument, input value, pattern, network port). Please use our online service to access the data.

## References

The following list contains _external sources_ which discuss the actor and the associated activities:

* https://nao-sec.org/2023/08/groundpeony-crawling-with-malice.html

## Literature

The following _articles_ explain our unique predictive cyber threat intelligence:

* [VulDB Cyber Threat Intelligence Documentation](https://vuldb.com/?kb.cti)
* [Cyber Threat Intelligence - Early Anticipation of Attacks](https://www.scip.ch/en/?labs.20201022)

## License

(c) [1997-2024](https://vuldb.com/?kb.changelog) by [vuldb.com](https://vuldb.com/?kb.about). All data on this page is shared under the license [CC BY-NC-SA 4.0](https://creativecommons.org/licenses/by-nc-sa/4.0/). Questions? Check the [FAQ](https://vuldb.com/?kb.faq), read the [documentation](https://vuldb.com/?kb) or [contact us](https://vuldb.com/?contact)!
