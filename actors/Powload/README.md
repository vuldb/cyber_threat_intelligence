# Powload - Cyber Threat Intelligence

These _indicators_ were reported, collected, and generated during the [VulDB CTI analysis](https://vuldb.com/?kb.cti) of the actor known as [Powload](https://vuldb.com/?actor.powload). The _activity monitoring_ correlates data from social media, forums, chat rooms, and darknet markets. It helps to determine associated actors, specific activities, expected intentions, emerging research, and ongoing attacks. Our unique _predictive model_ uses _big data_ to forecast activities and their characteristics.

_Live data_ and more _analysis capabilities_ are available at [https://vuldb.com/?actor.powload](https://vuldb.com/?actor.powload)

## Countries

These _countries_ are directly (e.g. origin of attacks) or indirectly (e.g. access by proxy) associated with Powload:

* [RU](https://vuldb.com/?country.ru)
* [CL](https://vuldb.com/?country.cl)
* [ZA](https://vuldb.com/?country.za)

## IOC - Indicator of Compromise

These _indicators of compromise_ (IOC) indicate associated network resources which are known to be part of research and attack activities of Powload.

ID | IP address | Hostname | Campaign | Confidence
-- | ---------- | -------- | -------- | ----------
1 | [5.61.29.155](https://vuldb.com/?ip.5.61.29.155) | 5-61-29-155.nrp.co | - | High
2 | [31.14.103.164](https://vuldb.com/?ip.31.14.103.164) | dns103164.phdns19.es | - | High
3 | [37.211.38.50](https://vuldb.com/?ip.37.211.38.50) | - | - | High
4 | [42.114.73.81](https://vuldb.com/?ip.42.114.73.81) | - | - | High
5 | [45.40.251.243](https://vuldb.com/?ip.45.40.251.243) | - | - | High
6 | [47.99.85.122](https://vuldb.com/?ip.47.99.85.122) | - | - | High
7 | [50.99.132.7](https://vuldb.com/?ip.50.99.132.7) | s50-99-132-7.ab.hsia.telus.net | - | High
8 | ... | ... | ... | ...

There are 26 more IOC items available. Please use our online service to access the data.

## TTP - Tactics, Techniques, Procedures

_Tactics, techniques, and procedures_ (TTP) summarize the suspected MITRE ATT&CK techniques used by _Powload_. This data is unique as it uses our predictive model for actor profiling.

ID | Technique | Weakness | Description | Confidence
-- | --------- | -------- | ----------- | ----------
1 | T1006 | CWE-21, CWE-22, CWE-24, CWE-36, CWE-425 | Pathname Traversal | High
2 | T1040 | CWE-319 | Authentication Bypass by Capture-replay | High
3 | T1055 | CWE-74 | Injection | High
4 | T1059 | CWE-94 | Cross Site Scripting | High
5 | T1059.007 | CWE-79, CWE-80 | Cross Site Scripting | High
6 | ... | ... | ... | ...

There are 18 more TTP items available. Please use our online service to access the data.

## IOA - Indicator of Attack

These _indicators of attack_ (IOA) list the potential fragments used for technical activities like reconnaissance, exploitation, privilege escalation, and exfiltration by Powload. This data is unique as it uses our predictive model for actor profiling.

ID | Type | Indicator | Confidence
-- | ---- | --------- | ----------
1 | File | `.github/workflows/comment.yml` | High
2 | File | `/?r=recruit/resume/edit&op=status` | High
3 | File | `/account/delivery` | High
4 | File | `/admin.php?c=upload&f=zip&_noCache=0.1683794968` | High
5 | File | `/admin/?page=user/list` | High
6 | File | `/admin/addproduct.php` | High
7 | File | `/admin/add_user_modal.php` | High
8 | File | `/admin/ajax.php?action=save_area` | High
9 | File | `/admin/bookings/manage_booking.php` | High
10 | File | `/admin/bookings/view_booking.php` | High
11 | File | `/admin/bookings/view_details.php` | High
12 | File | `/admin/budget/manage_budget.php` | High
13 | File | `/admin/contacts/organizations/edit/2` | High
14 | File | `/admin/edit_product.php` | High
15 | File | `/admin/edit_subject.php` | High
16 | File | `/admin/index.php` | High
17 | File | `/admin/index/index.html#/admin/mall.goods/index.html` | High
18 | File | `/admin/inquiries/view_inquiry.php` | High
19 | File | `/admin/manage_academic.php` | High
20 | File | `/admin/modal_add_product.php` | High
21 | File | `/admin/project/update/2` | High
22 | File | `/admin/read.php?mudi=announContent` | High
23 | File | `/admin/read.php?mudi=getSignal` | High
24 | File | `/admin/reg.php` | High
25 | File | `/admin/reportupload.aspx` | High
26 | File | `/admin/save_teacher.php` | High
27 | File | `/admin/service.php` | High
28 | File | `/admin/services/view_service.php` | High
29 | File | `/admin/sys_sql_query.php` | High
30 | File | `/admin/test_status.php` | High
31 | File | `/admin/update_s6.php` | High
32 | File | `/admin/user/manage_user.php` | High
33 | File | `/adms/admin/?page=vehicles/sell_vehicle` | High
34 | File | `/adms/admin/?page=vehicles/view_transaction` | High
35 | File | `/ajax.php?action=read_msg` | High
36 | File | `/ajax.php?action=save_company` | High
37 | File | `/api/ping` | Medium
38 | File | `/api/stl/actions/search` | High
39 | File | `/api/wechat/app_auth` | High
40 | File | `/App_Resource/UEditor/server/upload.aspx` | High
41 | File | `/author_posts.php` | High
42 | File | `/backup.pl` | Medium
43 | File | `/bin/ate` | Medium
44 | File | `/bin/httpd` | Medium
45 | File | `/blog` | Low
46 | File | `/boafrm/formFilter` | High
47 | File | `/booking/show_bookings/` | High
48 | File | `/browse` | Low
49 | File | `/building/backmgr/urlpage/mobileurl/configfile/jx2_config.ini` | High
50 | File | `/cas/logout` | Medium
51 | File | `/category.php` | High
52 | File | `/cgi-bin/adm.cgi` | High
53 | File | `/cgi-bin/jumpto.php?class=user&page=config_save&isphp=1` | High
54 | File | `/cgi-bin/ping.cgi` | High
55 | File | `/chaincity/user/ticket/create` | High
56 | File | `/change-language/de_DE` | High
57 | File | `/changeimage.php` | High
58 | File | `/classes/Master.php` | High
59 | File | `/classes/Master.php?f=delete_inquiry` | High
60 | File | `/classes/Master.php?f=delete_item` | High
61 | File | `/classes/Master.php?f=delete_service` | High
62 | File | `/classes/Master.php?f=save_course` | High
63 | File | `/classes/Master.php?f=save_inquiry` | High
64 | File | `/classes/Master.php?f=save_item` | High
65 | File | `/classes/Users.php?f=save` | High
66 | File | `/company/store` | High
67 | File | `/config` | Low
68 | File | `/contact.php` | Medium
69 | File | `/contact/store` | High
70 | File | `/Controller/Ajaxfileupload.ashx` | High
71 | File | `/dipam/athlete-profile.php` | High
72 | File | `/dipam/save-delegates.php` | High
73 | File | `/dosen/data` | Medium
74 | File | `/Duty/AjaxHandle/UpLoadFloodPlanFile.ashx` | High
75 | File | `/Duty/AjaxHandle/UploadFloodPlanFileUpdate.ashx` | High
76 | File | `/Duty/AjaxHandle/UploadHandler.ashx` | High
77 | File | `/Duty/AjaxHandle/Write/UploadFile.ashx` | High
78 | File | `/E-mobile/App/System/File/downfile.php` | High
79 | File | `/ecommerce/support_ticket` | High
80 | File | `/ecshop/admin/template.php` | High
81 | File | `/emap/devicePoint_addImgIco?hasSubsystem=true` | High
82 | File | `/en/blog-comment-4` | High
83 | File | `/EventBookingCalendar/load.php?controller=GzFront/action=checkout/cid=1/layout=calendar/show_header=T/local=3` | High
84 | File | `/file_manager/admin/save_user.php` | High
85 | File | `/forum/PostPrivateMessage` | High
86 | File | `/fos/admin/ajax.php?action=login` | High
87 | File | `/fos/admin/index.php?page=menu` | High
88 | File | `/goForm/aspForm` | High
89 | File | `/home/cavesConsole` | High
90 | File | `/home/courses` | High
91 | File | `/home/filter_listings` | High
92 | File | `/home/kickPlayer` | High
93 | File | `/home/masterConsole` | High
94 | File | `/home/search` | Medium
95 | File | `/home/sendBroadcast` | High
96 | File | `/hslist` | Low
97 | File | `/inc/jquery/uploadify/uploadify.php` | High
98 | ... | ... | ...

There are 870 more IOA items available (file, library, argument, input value, pattern, network port). Please use our online service to access the data.

## References

The following list contains _external sources_ which discuss the actor and the associated activities:

* https://blog.talosintelligence.com/2018/09/threat-roundup-0907-0914.html
* https://blog.talosintelligence.com/2018/09/threat-roundup-0921-0928.html
* https://blog.talosintelligence.com/2018/12/threat-roundup-1207-1214.html
* https://blog.talosintelligence.com/2019/01/threat-roundup-0111-0118.html
* https://blog.talosintelligence.com/2019/04/threat-roundup-0419-to-0426.html
* https://blog.talosintelligence.com/2019/05/threat-roundup-0503-0510.html

## Literature

The following _articles_ explain our unique predictive cyber threat intelligence:

* [VulDB Cyber Threat Intelligence Documentation](https://vuldb.com/?kb.cti)
* [Cyber Threat Intelligence - Early Anticipation of Attacks](https://www.scip.ch/en/?labs.20201022)

## License

(c) [1997-2023](https://vuldb.com/?kb.changelog) by [vuldb.com](https://vuldb.com/?kb.about). All data on this page is shared under the license [CC BY-NC-SA 4.0](https://creativecommons.org/licenses/by-nc-sa/4.0/). Questions? Check the [FAQ](https://vuldb.com/?kb.faq), read the [documentation](https://vuldb.com/?kb) or [contact us](https://vuldb.com/?contact)!
