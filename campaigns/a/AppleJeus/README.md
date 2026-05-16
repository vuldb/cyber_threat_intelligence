# AppleJeus - Cyber Threat Intelligence

These _indicators_ were reported, collected, and generated during the [VulDB CTI analysis](https://vuldb.com/kb/cti) of the campaign known as _AppleJeus_. The _activity monitoring_ correlates data from social media, forums, chat rooms, and darknet markets. It helps to determine associated actors, specific activities, expected intentions, emerging research, and ongoing attacks. Our unique _predictive model_ uses _big data_ to forecast activities and their characteristics.

_Live data_ and more _analysis capabilities_ are available at [https://vuldb.com/actor](https://vuldb.com/actor)

## Countries

These _countries_ are directly (e.g. origin of attacks) or indirectly (e.g. access by proxy) associated with AppleJeus:

* [VN](https://vuldb.com/country/vn)
* [CN](https://vuldb.com/country/cn)
* [UA](https://vuldb.com/country/ua)
* ...

There are 1 more country items available. Please use our online service to access the data.

## Actors

These _actors_ are associated with AppleJeus or other actors linked to the campaign.

ID | Actor | Confidence
-- | ----- | ----------
1 | [Applejeus](https://vuldb.com/actor/applejeus) | High
2 | [AppleJeus](https://vuldb.com/actor/applejeus) | High
3 | [DPRK](https://vuldb.com/actor/dprk) | High
4 | ... | ...

There are 1 more actor items available. Please use our online service to access the data.

## IOC - Indicator of Compromise

These _indicators of compromise_ (IOC) indicate associated network resources which are known to be part of research and attack activities of AppleJeus.

ID | IP address | Hostname | Actor | Confidence
-- | ---------- | -------- | ----- | ----------
1 | [23.254.217.53](https://vuldb.com/ip/23.254.217.53) | client-23-254-217-53.hostwindsdns.com | [Applejeus](https://vuldb.com/actor/applejeus) | High
2 | [45.33.2.79](https://vuldb.com/ip/45.33.2.79) | li956-79.members.linode.com | [Lazarus](https://vuldb.com/actor/lazarus) | High
3 | [45.33.23.183](https://vuldb.com/ip/45.33.23.183) | li977-183.members.linode.com | [Lazarus](https://vuldb.com/actor/lazarus) | High
4 | [45.56.79.23](https://vuldb.com/ip/45.56.79.23) | li929-23.members.linode.com | [Lazarus](https://vuldb.com/actor/lazarus) | High
5 | [45.79.19.196](https://vuldb.com/ip/45.79.19.196) | li1118-196.members.linode.com | [Lazarus](https://vuldb.com/actor/lazarus) | High
6 | [45.199.63.220](https://vuldb.com/ip/45.199.63.220) | - | [Lazarus](https://vuldb.com/actor/lazarus) | High
7 | [80.82.64.91](https://vuldb.com/ip/80.82.64.91) | - | [AppleJeus](https://vuldb.com/actor/applejeus) | High
8 | ... | ... | ... | ...

There are 29 more IOC items available. Please use our online service to access the data.

## TTP - Tactics, Techniques, Procedures

_Tactics, techniques, and procedures_ (TTP) summarize the suspected MITRE ATT&CK techniques used within AppleJeus. This data is unique as it uses our predictive model for actor profiling.

ID | Technique | Weakness | Description | Confidence
-- | --------- | -------- | ----------- | ----------
1 | T1006 | CWE-21, CWE-22, CWE-24, CWE-25 | Path Traversal | High
2 | T1040 | CWE-294, CWE-319 | Authentication Bypass by Capture-replay | High
3 | T1055 | CWE-74 | Improper Neutralization of Data within XPath Expressions | High
4 | T1059 | CWE-94, CWE-1321 | Argument Injection | High
5 | T1059.007 | CWE-79, CWE-80 | Basic Cross Site Scripting | High
6 | ... | ... | ... | ...

There are 19 more TTP items available. Please use our online service to access the data.

## IOA - Indicator of Attack

These _indicators of attack_ (IOA) list the potential fragments used for technical activities like reconnaissance, exploitation, privilege escalation, and exfiltration during AppleJeus. This data is unique as it uses our predictive model for actor profiling.

ID | Type | Indicator | Confidence
-- | ---- | --------- | ----------
1 | File | `/?explorer/index/zip` | High
2 | File | `/?page=reserve` | High
3 | File | `/?_route=settings/users-view/` | High
4 | File | `/about.php` | Medium
5 | File | `/academy/tutor/filter` | High
6 | File | `/actuator/heapdump` | High
7 | File | `/ad/queryAll` | Medium
8 | File | `/addCandidate.php` | High
9 | File | `/addcat.php` | Medium
10 | File | `/addproduct.php` | High
11 | File | `/add_contestant.php` | High
12 | File | `/admin.php?id=inbox` | High
13 | File | `/admin/?page=maintenance/brand` | High
14 | File | `/admin/?page=reports` | High
15 | File | `/admin/aboutus.php` | High
16 | File | `/admin/action/new-feed.php` | High
17 | File | `/admin/actions/check-attendance.php` | High
18 | File | `/admin/add-module.php` | High
19 | File | `/admin/add_account.php` | High
20 | File | `/admin/add_room.php` | High
21 | File | `/admin/admin-profile.php` | High
22 | File | `/admin/admin_product.ph` | High
23 | File | `/admin/all-applied-leave.php` | High
24 | File | `/admin/api/theme-edit/` | High
25 | File | `/admin/app/login_crud.php` | High
26 | File | `/admin/archives_add.php` | High
27 | File | `/admin/article.php?action=upload_cover` | High
28 | File | `/admin/asign-single-student-subjects.php` | High
29 | File | `/admin/bookings/manage_booking.php` | High
30 | File | `/admin/categories/view_category.php` | High
31 | File | `/admin/category.php` | High
32 | File | `/admin/category/add.do` | High
33 | File | `/admin/changeimage.php` | High
34 | File | `/admin/check_admin.php` | High
35 | File | `/admin/clientview.php` | High
36 | File | `/admin/communitymanagement.php` | High
37 | File | `/admin/contactus.php` | High
38 | File | `/admin/deleteitem.php` | High
39 | File | `/admin/delete_user.php` | High
40 | File | `/admin/departments/view_department.php` | High
41 | File | `/admin/edit-category.php` | High
42 | File | `/admin/edit-doc.php` | High
43 | File | `/admin/edit.php` | High
44 | File | `/admin/edit_content.php` | High
45 | File | `/admin/edit_posts.php` | High
46 | File | `/admin/edit_room.php` | High
47 | File | `/admin/fetch_product_details.php` | High
48 | File | `/admin/forgot-password.php` | High
49 | File | `/admin/freelist_main.php` | High
50 | File | `/admin/group/edit.do` | High
51 | File | `/admin/home.php` | High
52 | File | `/admin/index.php` | High
53 | File | `/admin/index.php/datafile/delfile` | High
54 | File | `/admin/index.php?act=reset_admin_psw` | High
55 | File | `/admin/inquiries/view_inquiry.php` | High
56 | File | `/admin/lab.php` | High
57 | File | `/admin/login.php` | High
58 | File | `/admin/manage-students.php` | High
59 | File | `/admin/manage_station.php` | High
60 | File | `/admin/modules/lesson/index.php` | High
61 | File | `/admin/modules/product/controller.php?action=add` | High
62 | File | `/admin/modules/room/index.php` | High
63 | File | `/admin/network/ajax_getChannelList` | High
64 | File | `/admin/newsletterdel.php` | High
65 | File | `/admin/productadd_back.php` | High
66 | File | `/admin/profile.php` | High
67 | File | `/admin/quote-details.php` | High
68 | File | `/admin/room.php` | High
69 | File | `/admin/sales-reports-detail.php` | High
70 | File | `/admin/search-appointment.php` | High
71 | File | `/admin/search-directory.php.` | High
72 | File | `/admin/search-invoices.php` | High
73 | File | `/admin/store/edit/` | High
74 | File | `/admin/system/dict/add.json?sqlid=system.dict.save` | High
75 | File | `/admin/tag.php` | High
76 | File | `/admin/teachers.php` | High
77 | File | `/admin/update-progress.php` | High
78 | File | `/admin/update-user.php` | High
79 | File | `/admin/user.php` | High
80 | File | `/admin/user/controller.php?action=photos` | High
81 | File | `/admin/user/manage_user.php` | High
82 | File | `/admin/users.php` | High
83 | File | `/Adminadd.php` | High
84 | File | `/Administrator/PHP/AdminAddAlbum.php` | High
85 | File | `/Administrator/PHP/AdminAddCategory.php` | High
86 | File | `/Administrator/PHP/AdminEditCategory.php` | High
87 | File | `/Administrator/PHP/AdminViewSongs.php` | High
88 | File | `/adminLogin.php` | High
89 | File | `/admin_class.php` | High
90 | File | `/ajax.php` | Medium
91 | File | `/ajax.php?action=delete_course` | High
92 | File | `/ajax.php?action=login` | High
93 | File | `/all-orders.php` | High
94 | File | `/api/advanced-search` | High
95 | File | `/api/article/del` | High
96 | File | `/api/client/editemedia.php` | High
97 | File | `/api/code/upload` | High
98 | File | `/api/course/enroll-course` | High
99 | File | `/api/file` | Medium
100 | File | `/api/public/signup` | High
101 | File | `/api/users/{id}/preferences` | High
102 | File | `/api/v1/assignments/{assignment_id}/tasks/{task_id}/sub_file` | High
103 | File | `/api/v1/getbaseconfig` | High
104 | File | `/api/v1/text-to-speech/generate` | High
105 | File | `/api/website/title` | High
106 | File | `/App/Tpl/Admin/Default/Channel/index.html.Attackers` | High
107 | File | `/application/index/common.php` | High
108 | File | `/application/index/controller/Datament.php` | High
109 | File | `/application/index/controller/Icon.php` | High
110 | File | `/application/pay/controller/Api.php` | High
111 | File | `/artist-display.php` | High
112 | File | `/att_single_view.php` | High
113 | File | `/b2c/package-information` | High
114 | File | `/backend/admin/his_admin_add_vendor.php` | High
115 | File | `/bin/httpd` | Medium
116 | File | `/boafrm/formIpQoS` | High
117 | File | `/boafrm/formOneKeyAccessButton` | High
118 | File | `/boafrm/formVlan` | High
119 | File | `/boafrm/formWanConfigSetup` | High
120 | File | `/boafrm/formWlanRedirect` | High
121 | File | `/BRS_top.html` | High
122 | ... | ... | ...

There are 1080 more IOA items available (file, library, argument, input value, pattern, network port). Please use our online service to access the data.

## References

The following list contains _external sources_ which discuss the campaign and the associated activities:

* https://securelist.com/operation-applejeus-sequel/95596/
* https://us-cert.cisa.gov/ncas/alerts/aa21-048a
* https://us-cert.cisa.gov/ncas/analysis-reports/ar21-048c
* https://www.cyber45.com

## Literature

The following _articles_ explain our unique predictive cyber threat intelligence:

* [VulDB Cyber Threat Intelligence Documentation](https://vuldb.com/kb/cti)
* [Cyber Threat Intelligence - Early Anticipation of Attacks](https://www.scip.ch/en/?labs.20201022)

## License

(c) [1997-2026](https://vuldb.com/kb/changelog) by [vuldb.com](https://vuldb.com/kb/about). All data on this page is shared under the license [CC BY-NC-SA 4.0](https://creativecommons.org/licenses/by-nc-sa/4.0/). Questions? Check the [FAQ](https://vuldb.com/kb/faq), read the [documentation](https://vuldb.com/kb) or [contact us](https://vuldb.com/contact)!
