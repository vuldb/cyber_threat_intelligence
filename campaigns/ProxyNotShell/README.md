# ProxyNotShell - Cyber Threat Intelligence

These _indicators_ were reported, collected, and generated during the [VulDB CTI analysis](https://vuldb.com/?kb.cti) of the campaign known as _ProxyNotShell_. The _activity monitoring_ correlates data from social media, forums, chat rooms, and darknet markets. It helps to determine associated actors, specific activities, expected intentions, emerging research, and ongoing attacks. Our unique _predictive model_ uses _big data_ to forecast activities and their characteristics.

_Live data_ and more _analysis capabilities_ are available at [https://vuldb.com/?actor](https://vuldb.com/?actor)

## Countries

These _countries_ are directly (e.g. origin of attacks) or indirectly (e.g. access by proxy) associated with ProxyNotShell:

* [US](https://vuldb.com/?country.us)
* [LU](https://vuldb.com/?country.lu)
* [CN](https://vuldb.com/?country.cn)
* ...

There are 16 more country items available. Please use our online service to access the data.

## Actors

These _actors_ are associated with ProxyNotShell or other actors linked to the campaign.

ID | Actor | Confidence
-- | ----- | ----------
1 | [China Unknown](https://vuldb.com/?actor.china_unknown) | High

## IOC - Indicator of Compromise

These _indicators of compromise_ (IOC) indicate associated network resources which are known to be part of research and attack activities of ProxyNotShell.

ID | IP address | Hostname | Actor | Confidence
-- | ---------- | -------- | ----- | ----------
1 | [5.180.61.17](https://vuldb.com/?ip.5.180.61.17) | - | [China Unknown](https://vuldb.com/?actor.china_unknown) | High
2 | [47.242.39.92](https://vuldb.com/?ip.47.242.39.92) | - | [China Unknown](https://vuldb.com/?actor.china_unknown) | High
3 | [61.244.94.85](https://vuldb.com/?ip.61.244.94.85) | 061244094085.ctinets.com | [China Unknown](https://vuldb.com/?actor.china_unknown) | High
4 | [86.48.6.69](https://vuldb.com/?ip.86.48.6.69) | - | [China Unknown](https://vuldb.com/?actor.china_unknown) | High
5 | ... | ... | ... | ...

There are 15 more IOC items available. Please use our online service to access the data.

## TTP - Tactics, Techniques, Procedures

_Tactics, techniques, and procedures_ (TTP) summarize the suspected MITRE ATT&CK techniques used within ProxyNotShell. This data is unique as it uses our predictive model for actor profiling.

ID | Technique | Weakness | Description | Confidence
-- | --------- | -------- | ----------- | ----------
1 | T1006 | CWE-22, CWE-24, CWE-36, CWE-425 | Pathname Traversal | High
2 | T1040 | CWE-294, CWE-319 | Authentication Bypass by Capture-replay | High
3 | T1055 | CWE-74 | Injection | High
4 | T1059 | CWE-94 | Cross Site Scripting | High
5 | T1059.007 | CWE-79, CWE-80 | Cross Site Scripting | High
6 | ... | ... | ... | ...

There are 22 more TTP items available. Please use our online service to access the data.

## IOA - Indicator of Attack

These _indicators of attack_ (IOA) list the potential fragments used for technical activities like reconnaissance, exploitation, privilege escalation, and exfiltration during ProxyNotShell. This data is unique as it uses our predictive model for actor profiling.

ID | Type | Indicator | Confidence
-- | ---- | --------- | ----------
1 | File | `.github/workflows/comment.yml` | High
2 | File | `/?r=recruit/resume/edit&op=status` | High
3 | File | `/academy/home/courses` | High
4 | File | `/admin.php?c=upload&f=zip&_noCache=0.1683794968` | High
5 | File | `/admin/?page=user/list` | High
6 | File | `/admin/?page=user/manage_user&id=3` | High
7 | File | `/admin/addproduct.php` | High
8 | File | `/admin/add_user_modal.php` | High
9 | File | `/admin/admin-profile.php` | High
10 | File | `/admin/ajax.php?action=confirm_order` | High
11 | File | `/admin/article/article-add.php` | High
12 | File | `/admin/article/article-edit-run.php` | High
13 | File | `/admin/bookings/manage_booking.php` | High
14 | File | `/admin/bookings/view_booking.php` | High
15 | File | `/admin/budget/manage_budget.php` | High
16 | File | `/admin/category/cate-edit-run.php` | High
17 | File | `/admin/cms_admin.php` | High
18 | File | `/admin/contacts/organizations/edit/2` | High
19 | File | `/admin/curriculum/view_curriculum.php` | High
20 | File | `/admin/departments/view_department.php` | High
21 | File | `/admin/edit_product.php` | High
22 | File | `/admin/edit_subject.php` | High
23 | File | `/admin/index.php` | High
24 | File | `/admin/index/index.html#/admin/mall.goods/index.html` | High
25 | File | `/admin/inquiries/view_inquiry.php` | High
26 | File | `/admin/leancloud.php` | High
27 | File | `/admin/modal_add_product.php` | High
28 | File | `/admin/project/update/2` | High
29 | File | `/admin/read.php?mudi=announContent` | High
30 | File | `/admin/read.php?mudi=getSignal` | High
31 | File | `/admin/reg.php` | High
32 | File | `/admin/service.php` | High
33 | File | `/admin/services/manage_service.php` | High
34 | File | `/admin/services/view_service.php` | High
35 | File | `/admin/suppliers/view_details.php` | High
36 | File | `/admin/sys_sql_query.php` | High
37 | File | `/admin/test_status.php` | High
38 | File | `/admin/transactions/track_shipment.php` | High
39 | File | `/admin/upload.php` | High
40 | File | `/admin/user/manage_user.php` | High
41 | File | `/admin/userprofile.php` | High
42 | File | `/admin/vote_edit.php` | High
43 | File | `/ajax/myshop` | Medium
44 | File | `/api/es/admin/v3/security/user/1` | High
45 | File | `/api/ping` | Medium
46 | File | `/api/runscript` | High
47 | File | `/api/stl/actions/search` | High
48 | File | `/api/sys/login` | High
49 | File | `/api/sys/set_passwd` | High
50 | File | `/App_Resource/UEditor/server/upload.aspx` | High
51 | File | `/autheditpwd.php` | High
52 | File | `/author_posts.php` | High
53 | File | `/blog` | Low
54 | File | `/blog-single.php` | High
55 | File | `/booking/show_bookings/` | High
56 | File | `/browse` | Low
57 | File | `/building/backmgr/urlpage/mobileurl/configfile/jx2_config.ini` | High
58 | File | `/cgi-bin/ping.cgi` | High
59 | File | `/chaincity/user/ticket/create` | High
60 | File | `/changeimage.php` | High
61 | File | `/classes/Master.php?f=delete_category` | High
62 | File | `/classes/Master.php?f=delete_inquiry` | High
63 | File | `/classes/Master.php?f=delete_item` | High
64 | File | `/classes/Master.php?f=delete_service` | High
65 | File | `/classes/Master.php?f=save_course` | High
66 | File | `/classes/Master.php?f=save_inquiry` | High
67 | File | `/classes/Master.php?f=save_item` | High
68 | File | `/classes/Users.php?f=save` | High
69 | File | `/collection/all` | High
70 | File | `/company/store` | High
71 | File | `/config` | Low
72 | File | `/contact.php` | Medium
73 | File | `/Controller/Ajaxfileupload.ashx` | High
74 | File | `/course/filterRecords/` | High
75 | File | `/dipam/save-delegates.php` | High
76 | File | `/dosen/data` | Medium
77 | File | `/Duty/AjaxHandle/UploadFloodPlanFileUpdate.ashx` | High
78 | File | `/Duty/AjaxHandle/UploadHandler.ashx` | High
79 | File | `/E-mobile/App/System/File/downfile.php` | High
80 | File | `/ecommerce/support_ticket` | High
81 | File | `/emap/devicePoint_addImgIco?hasSubsystem=true` | High
82 | File | `/EventBookingCalendar/load.php?controller=GzFront/action=checkout/cid=1/layout=calendar/show_header=T/local=3` | High
83 | File | `/export` | Low
84 | File | `/file_manager/admin/save_user.php` | High
85 | File | `/find-a-match` | High
86 | ... | ... | ...

There are 756 more IOA items available (file, library, argument, input value, pattern, network port). Please use our online service to access the data.

## References

The following list contains _external sources_ which discuss the campaign and the associated activities:

* https://www.gteltsc.vn/blog/warning-new-attack-campaign-utilized-a-new-0day-rce-vulnerability-on-microsoft-exchange-server-12715.html

## Literature

The following _articles_ explain our unique predictive cyber threat intelligence:

* [VulDB Cyber Threat Intelligence Documentation](https://vuldb.com/?kb.cti)
* [Cyber Threat Intelligence - Early Anticipation of Attacks](https://www.scip.ch/en/?labs.20201022)

## License

(c) [1997-2023](https://vuldb.com/?kb.changelog) by [vuldb.com](https://vuldb.com/?kb.about). All data on this page is shared under the license [CC BY-NC-SA 4.0](https://creativecommons.org/licenses/by-nc-sa/4.0/). Questions? Check the [FAQ](https://vuldb.com/?kb.faq), read the [documentation](https://vuldb.com/?kb) or [contact us](https://vuldb.com/?contact)!
