# Johnnie - Cyber Threat Intelligence

These _indicators_ were reported, collected, and generated during the [VulDB CTI analysis](https://vuldb.com/?kb.cti) of the actor known as [Johnnie](https://vuldb.com/?actor.johnnie). The _activity monitoring_ correlates data from social media, forums, chat rooms, and darknet markets. It helps to determine associated actors, specific activities, expected intentions, emerging research, and ongoing attacks. Our unique _predictive model_ uses _big data_ to forecast activities and their characteristics.

_Live data_ and more _analysis capabilities_ are available at [https://vuldb.com/?actor.johnnie](https://vuldb.com/?actor.johnnie)

## Countries

These _countries_ are directly (e.g. origin of attacks) or indirectly (e.g. access by proxy) associated with Johnnie:

* [US](https://vuldb.com/?country.us)
* [TM](https://vuldb.com/?country.tm)

## IOC - Indicator of Compromise

These _indicators of compromise_ (IOC) indicate associated network resources which are known to be part of research and attack activities of Johnnie.

ID | IP address | Hostname | Campaign | Confidence
-- | ---------- | -------- | -------- | ----------
1 | [20.36.253.92](https://vuldb.com/?ip.20.36.253.92) | - | - | High
2 | [23.1.236.9](https://vuldb.com/?ip.23.1.236.9) | a23-1-236-9.deploy.static.akamaitechnologies.com | - | High
3 | [23.6.69.99](https://vuldb.com/?ip.23.6.69.99) | a23-6-69-99.deploy.static.akamaitechnologies.com | - | High
4 | [23.46.150.48](https://vuldb.com/?ip.23.46.150.48) | a23-46-150-48.deploy.static.akamaitechnologies.com | - | High
5 | [23.46.150.72](https://vuldb.com/?ip.23.46.150.72) | a23-46-150-72.deploy.static.akamaitechnologies.com | - | High
6 | [23.105.131.235](https://vuldb.com/?ip.23.105.131.235) | - | - | High
7 | [23.218.140.208](https://vuldb.com/?ip.23.218.140.208) | a23-218-140-208.deploy.static.akamaitechnologies.com | - | High
8 | [23.221.72.10](https://vuldb.com/?ip.23.221.72.10) | a23-221-72-10.deploy.static.akamaitechnologies.com | - | High
9 | [23.221.72.16](https://vuldb.com/?ip.23.221.72.16) | a23-221-72-16.deploy.static.akamaitechnologies.com | - | High
10 | [23.221.72.27](https://vuldb.com/?ip.23.221.72.27) | a23-221-72-27.deploy.static.akamaitechnologies.com | - | High
11 | [23.221.73.32](https://vuldb.com/?ip.23.221.73.32) | a23-221-73-32.deploy.static.akamaitechnologies.com | - | High
12 | [34.107.221.82](https://vuldb.com/?ip.34.107.221.82) | 82.221.107.34.bc.googleusercontent.com | - | Medium
13 | ... | ... | ... | ...

There are 48 more IOC items available. Please use our online service to access the data.

## TTP - Tactics, Techniques, Procedures

_Tactics, techniques, and procedures_ (TTP) summarize the suspected MITRE ATT&CK techniques used by _Johnnie_. This data is unique as it uses our predictive model for actor profiling.

ID | Technique | Weakness | Description | Confidence
-- | --------- | -------- | ----------- | ----------
1 | T1006 | CWE-21, CWE-22, CWE-24, CWE-36 | Path Traversal | High
2 | T1040 | CWE-319 | Authentication Bypass by Capture-replay | High
3 | T1055 | CWE-74 | Improper Neutralization of Data within XPath Expressions | High
4 | T1059 | CWE-94, CWE-1321 | Argument Injection | High
5 | ... | ... | ... | ...

There are 18 more TTP items available. Please use our online service to access the data.

## IOA - Indicator of Attack

These _indicators of attack_ (IOA) list the potential fragments used for technical activities like reconnaissance, exploitation, privilege escalation, and exfiltration by Johnnie. This data is unique as it uses our predictive model for actor profiling.

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
9 | File | `/admin/?page=inmates/view_inmate` | High
10 | File | `/admin/aboutus.php` | High
11 | File | `/Admin/add-student.php` | High
12 | File | `/admin/addTithes.php` | High
13 | File | `/admin/add_exercises.php` | High
14 | File | `/admin/add_trainers.php` | High
15 | File | `/admin/adminHome.php` | High
16 | File | `/admin/admin_cl.php?mudi=revPwd` | High
17 | File | `/admin/app/profile_crud.php` | High
18 | File | `/admin/applicants/controller.php` | High
19 | File | `/admin/bookdate.php` | High
20 | File | `/admin/booking-search.php` | High
21 | File | `/admin/category/index.php` | High
22 | File | `/admin/communitymanagement.php` | High
23 | File | `/admin/company/index.php` | High
24 | File | `/admin/conferences/get-all-status/` | High
25 | File | `/admin/conferences/list/` | High
26 | File | `/admin/court-type` | High
27 | File | `/admin/edit-services.php` | High
28 | File | `/admin/edit.php` | High
29 | File | `/admin/edit_admin_details.php?id=admin` | High
30 | File | `/admin/employee/controller.php` | High
31 | File | `/admin/employee/index.php` | High
32 | File | `/admin/extended` | High
33 | File | `/admin/featured.php` | High
34 | File | `/admin/forgot-password.php` | High
35 | File | `/admin/general-setting` | High
36 | File | `/admin/general/change-lang` | High
37 | File | `/admin/googleads.php` | High
38 | File | `/admin/group` | Medium
39 | File | `/Admin/login.php` | High
40 | File | `/admin/login.php` | High
41 | File | `/Admin/News.php` | High
42 | File | `/admin/newsletter1.php` | High
43 | File | `/admin/payment.php` | High
44 | File | `/admin/photo.php` | High
45 | File | `/admin/receipt.php` | High
46 | File | `/admin/renewaldue.php` | High
47 | File | `/admin/rooms.php` | High
48 | File | `/admin/search.php` | High
49 | File | `/admin/searchview.php` | High
50 | File | `/admin/students/manage.php` | High
51 | File | `/admin/twitter.php` | High
52 | File | `/admin/update-rooms.php` | High
53 | File | `/admin/user-search.php` | High
54 | File | `/admin/usermanagement.php` | High
55 | File | `/admin/users.php` | High
56 | File | `/admin/vacancy/controller.php` | High
57 | File | `/admin/vendor` | High
58 | File | `/admin/view_sendlist.php` | High
59 | File | `/adminapi/system/crud` | High
60 | File | `/adminapi/system/file/openfile` | High
61 | File | `/adminPage/main/upload` | High
62 | File | `/adminPage/www/addOver` | High
63 | File | `/adminpanel/admin/facebox_modal/updateExaminee.php` | High
64 | File | `/adminpanel/admin/query/deleteCourseExe.php` | High
65 | File | `/adminpanel/admin/query/loginExe.php` | High
66 | File | `/admin_route/inc_service_credits.php` | High
67 | File | `/api/` | Low
68 | File | `/api/browserextension/UpdatePassword/` | High
69 | File | `/api/controllers/admin/app/AppController.php` | High
70 | File | `/api/controllers/admin/app/ComboController.php` | High
71 | File | `/api/controllers/common/UploadsController.php` | High
72 | File | `/api/controllers/merchant/app/ComboController.php` | High
73 | File | `/api/controllers/merchant/shop/PosterController.php` | High
74 | File | `/api/v1/bait/set` | High
75 | File | `/api/v2/open/tablesInfo` | High
76 | File | `/app/ajax/search_sales_report.php` | High
77 | File | `/app/Http/Controllers/ImageController.php` | High
78 | File | `/app/middleware/TokenVerify.php` | High
79 | File | `/application/index/controller/Databasesource.php` | High
80 | File | `/application/index/controller/Datament.php` | High
81 | File | `/application/index/controller/File.php` | High
82 | File | `/application/index/controller/Icon.php` | High
83 | File | `/application/index/controller/Pay.php` | High
84 | File | `/application/index/controller/Screen.php` | High
85 | File | `/application/index/controller/Unity.php` | High
86 | File | `/application/plugins/controller/Upload.php` | High
87 | File | `/application/websocket/controller/Setting.php` | High
88 | File | `/apps/reg_go.php` | High
89 | File | `/apps/system/router/upload.go` | High
90 | File | `/cardo/api` | Medium
91 | File | `/category.php` | High
92 | File | `/cgi-bin/cstecgi.cgi` | High
93 | File | `/cgi-bin/nas_sharing.cgi` | High
94 | File | `/cgi-bin/nightled.cgi` | High
95 | File | `/ci_hms/massage_room/edit/1` | High
96 | File | `/ci_hms/search` | High
97 | File | `/ci_spms/admin/category` | High
98 | File | `/ci_ssms/index.php/orders/create` | High
99 | File | `/claire_blake` | High
100 | File | `/classes/Users.php?f=save` | High
101 | File | `/control/deactivate_case.php` | High
102 | File | `/controller/company/Index.php#sendCompanyLogo` | High
103 | ... | ... | ...

There are 913 more IOA items available (file, library, argument, input value, pattern, network port). Please use our online service to access the data.

## References

The following list contains _external sources_ which discuss the actor and the associated activities:

* https://blog.talosintelligence.com/2018/06/threat-roundup-0601-0615.html
* https://blog.talosintelligence.com/2018/09/threat-roundup-0907-0914.html
* https://blog.talosintelligence.com/2019/01/threat-roundup-0111-0118.html
* https://blog.talosintelligence.com/2021/03/threat-roundup-0226-0305.html
* https://blog.talosintelligence.com/2021/03/threat-roundup-0305-0312.html
* https://blog.talosintelligence.com/2022/03/threat-roundup-0311-0318.html
* https://blog.talosintelligence.com/2022/06/threat-roundup-0610-0617.html

## Literature

The following _articles_ explain our unique predictive cyber threat intelligence:

* [VulDB Cyber Threat Intelligence Documentation](https://vuldb.com/?kb.cti)
* [Cyber Threat Intelligence - Early Anticipation of Attacks](https://www.scip.ch/en/?labs.20201022)

## License

(c) [1997-2024](https://vuldb.com/?kb.changelog) by [vuldb.com](https://vuldb.com/?kb.about). All data on this page is shared under the license [CC BY-NC-SA 4.0](https://creativecommons.org/licenses/by-nc-sa/4.0/). Questions? Check the [FAQ](https://vuldb.com/?kb.faq), read the [documentation](https://vuldb.com/?kb) or [contact us](https://vuldb.com/?contact)!