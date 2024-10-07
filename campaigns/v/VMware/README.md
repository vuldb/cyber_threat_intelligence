# VMware - Cyber Threat Intelligence

These _indicators_ were reported, collected, and generated during the [VulDB CTI analysis](https://vuldb.com/?kb.cti) of the campaign known as _VMware_. The _activity monitoring_ correlates data from social media, forums, chat rooms, and darknet markets. It helps to determine associated actors, specific activities, expected intentions, emerging research, and ongoing attacks. Our unique _predictive model_ uses _big data_ to forecast activities and their characteristics.

_Live data_ and more _analysis capabilities_ are available at [https://vuldb.com/?actor](https://vuldb.com/?actor)

## Countries

These _countries_ are directly (e.g. origin of attacks) or indirectly (e.g. access by proxy) associated with VMware:

* [US](https://vuldb.com/?country.us)
* [CN](https://vuldb.com/?country.cn)

## Actors

These _actors_ are associated with VMware or other actors linked to the campaign.

ID | Actor | Confidence
-- | ----- | ----------
1 | [Unknown](https://vuldb.com/?actor.unknown) | High

## IOC - Indicator of Compromise

These _indicators of compromise_ (IOC) indicate associated network resources which are known to be part of research and attack activities of VMware.

ID | IP address | Hostname | Actor | Confidence
-- | ---------- | -------- | ----- | ----------
1 | [20.232.97.189](https://vuldb.com/?ip.20.232.97.189) | - | [Unknown](https://vuldb.com/?actor.unknown) | High
2 | [45.72.85.172](https://vuldb.com/?ip.45.72.85.172) | - | [Unknown](https://vuldb.com/?actor.unknown) | High
3 | [45.72.112.245](https://vuldb.com/?ip.45.72.112.245) | fkcoqootrd.pottspsychic.site | [Unknown](https://vuldb.com/?actor.unknown) | High
4 | [51.79.171.53](https://vuldb.com/?ip.51.79.171.53) | ip53.ip-51-79-171.net | [Unknown](https://vuldb.com/?actor.unknown) | High
5 | ... | ... | ... | ...

There are 16 more IOC items available. Please use our online service to access the data.

## TTP - Tactics, Techniques, Procedures

_Tactics, techniques, and procedures_ (TTP) summarize the suspected MITRE ATT&CK techniques used within VMware. This data is unique as it uses our predictive model for actor profiling.

ID | Technique | Weakness | Description | Confidence
-- | --------- | -------- | ----------- | ----------
1 | T1006 | CWE-21, CWE-22, CWE-24, CWE-36 | Path Traversal | High
2 | T1040 | CWE-319 | Authentication Bypass by Capture-replay | High
3 | T1055 | CWE-74 | Improper Neutralization of Data within XPath Expressions | High
4 | T1059 | CWE-94, CWE-1321 | Argument Injection | High
5 | ... | ... | ... | ...

There are 18 more TTP items available. Please use our online service to access the data.

## IOA - Indicator of Attack

These _indicators of attack_ (IOA) list the potential fragments used for technical activities like reconnaissance, exploitation, privilege escalation, and exfiltration during VMware. This data is unique as it uses our predictive model for actor profiling.

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
15 | File | `/admin/admin_cl.php?mudi=revPwd` | High
16 | File | `/admin/app/profile_crud.php` | High
17 | File | `/admin/applicants/controller.php` | High
18 | File | `/admin/bookdate.php` | High
19 | File | `/admin/booking-search.php` | High
20 | File | `/admin/category/index.php` | High
21 | File | `/admin/communitymanagement.php` | High
22 | File | `/admin/conferences/get-all-status/` | High
23 | File | `/admin/conferences/list/` | High
24 | File | `/admin/court-type` | High
25 | File | `/admin/edit-services.php` | High
26 | File | `/admin/edit.php` | High
27 | File | `/admin/edit_admin_details.php?id=admin` | High
28 | File | `/admin/employee/controller.php` | High
29 | File | `/admin/employee/index.php` | High
30 | File | `/admin/extended` | High
31 | File | `/admin/featured.php` | High
32 | File | `/admin/forgot-password.php` | High
33 | File | `/admin/general-setting` | High
34 | File | `/admin/general/change-lang` | High
35 | File | `/admin/googleads.php` | High
36 | File | `/admin/group` | Medium
37 | File | `/Admin/login.php` | High
38 | File | `/admin/login.php` | High
39 | File | `/Admin/News.php` | High
40 | File | `/admin/newsletter1.php` | High
41 | File | `/admin/payment.php` | High
42 | File | `/admin/photo.php` | High
43 | File | `/admin/renewaldue.php` | High
44 | File | `/admin/rooms.php` | High
45 | File | `/admin/search.php` | High
46 | File | `/admin/searchview.php` | High
47 | File | `/admin/students/manage.php` | High
48 | File | `/admin/twitter.php` | High
49 | File | `/admin/update-rooms.php` | High
50 | File | `/admin/user-search.php` | High
51 | File | `/admin/usermanagement.php` | High
52 | File | `/admin/users.php` | High
53 | File | `/admin/vacancy/controller.php` | High
54 | File | `/admin/vendor` | High
55 | File | `/admin/view_sendlist.php` | High
56 | File | `/adminapi/system/crud` | High
57 | File | `/adminapi/system/file/openfile` | High
58 | File | `/adminPage/main/upload` | High
59 | File | `/adminPage/www/addOver` | High
60 | File | `/adminpanel/admin/facebox_modal/updateExaminee.php` | High
61 | File | `/adminpanel/admin/query/deleteCourseExe.php` | High
62 | File | `/adminpanel/admin/query/loginExe.php` | High
63 | File | `/admin_route/inc_service_credits.php` | High
64 | File | `/api/` | Low
65 | File | `/api/browserextension/UpdatePassword/` | High
66 | File | `/api/controllers/admin/app/AppController.php` | High
67 | File | `/api/controllers/admin/app/ComboController.php` | High
68 | File | `/api/controllers/common/UploadsController.php` | High
69 | File | `/api/controllers/merchant/app/ComboController.php` | High
70 | File | `/api/controllers/merchant/shop/PosterController.php` | High
71 | File | `/api/v1/bait/set` | High
72 | File | `/api/v2/open/tablesInfo` | High
73 | File | `/app/ajax/search_sales_report.php` | High
74 | File | `/app/Http/Controllers/ImageController.php` | High
75 | File | `/app/middleware/TokenVerify.php` | High
76 | File | `/application/index/controller/Databasesource.php` | High
77 | File | `/application/index/controller/Datament.php` | High
78 | File | `/application/index/controller/File.php` | High
79 | File | `/application/index/controller/Icon.php` | High
80 | File | `/application/index/controller/Pay.php` | High
81 | File | `/application/index/controller/Screen.php` | High
82 | File | `/application/index/controller/Unity.php` | High
83 | File | `/application/plugins/controller/Upload.php` | High
84 | File | `/application/websocket/controller/Setting.php` | High
85 | File | `/apps/reg_go.php` | High
86 | File | `/apps/system/router/upload.go` | High
87 | File | `/cardo/api` | Medium
88 | File | `/category.php` | High
89 | File | `/cgi-bin/cstecgi.cgi` | High
90 | File | `/cgi-bin/nas_sharing.cgi` | High
91 | File | `/cgi-bin/nightled.cgi` | High
92 | File | `/ci_hms/massage_room/edit/1` | High
93 | File | `/ci_hms/search` | High
94 | File | `/ci_spms/admin/category` | High
95 | File | `/ci_ssms/index.php/orders/create` | High
96 | File | `/claire_blake` | High
97 | File | `/classes/Users.php?f=save` | High
98 | File | `/control/deactivate_case.php` | High
99 | File | `/controller/company/Index.php#sendCompanyLogo` | High
100 | File | `/dashboard/add-portfolio.php` | High
101 | ... | ... | ...

There are 898 more IOA items available (file, library, argument, input value, pattern, network port). Please use our online service to access the data.

## References

The following list contains _external sources_ which discuss the campaign and the associated activities:

* https://blog.morphisec.com/vmware-identity-manager-attack-backdoor
* https://www.cisa.gov/uscert/ncas/alerts/aa22-138b

## Literature

The following _articles_ explain our unique predictive cyber threat intelligence:

* [VulDB Cyber Threat Intelligence Documentation](https://vuldb.com/?kb.cti)
* [Cyber Threat Intelligence - Early Anticipation of Attacks](https://www.scip.ch/en/?labs.20201022)

## License

(c) [1997-2024](https://vuldb.com/?kb.changelog) by [vuldb.com](https://vuldb.com/?kb.about). All data on this page is shared under the license [CC BY-NC-SA 4.0](https://creativecommons.org/licenses/by-nc-sa/4.0/). Questions? Check the [FAQ](https://vuldb.com/?kb.faq), read the [documentation](https://vuldb.com/?kb) or [contact us](https://vuldb.com/?contact)!
