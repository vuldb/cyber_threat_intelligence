# Powload - Cyber Threat Intelligence

These _indicators_ were reported, collected, and generated during the [VulDB CTI analysis](https://vuldb.com/?kb.cti) of the actor known as [Powload](https://vuldb.com/?actor.powload). The _activity monitoring_ correlates data from social media, forums, chat rooms, and darknet markets. It helps to determine associated actors, specific activities, expected intentions, emerging research, and ongoing attacks. Our unique _predictive model_ uses _big data_ to forecast activities and their characteristics.

_Live data_ and more _analysis capabilities_ are available at [https://vuldb.com/?actor.powload](https://vuldb.com/?actor.powload)

## Countries

These _countries_ are directly (e.g. origin of attacks) or indirectly (e.g. access by proxy) associated with Powload:

* [RU](https://vuldb.com/?country.ru)
* [ZA](https://vuldb.com/?country.za)
* [VN](https://vuldb.com/?country.vn)

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
2 | T1055 | CWE-74 | Injection | High
3 | T1059 | CWE-94, CWE-1321 | Cross Site Scripting | High
4 | T1059.007 | CWE-79, CWE-80 | Cross Site Scripting | High
5 | ... | ... | ... | ...

There are 17 more TTP items available. Please use our online service to access the data.

## IOA - Indicator of Attack

These _indicators of attack_ (IOA) list the potential fragments used for technical activities like reconnaissance, exploitation, privilege escalation, and exfiltration by Powload. This data is unique as it uses our predictive model for actor profiling.

ID | Type | Indicator | Confidence
-- | ---- | --------- | ----------
1 | File | `.github/workflows/combine-prs.yml` | High
2 | File | `/admin.php?c=upload&f=zip&_noCache=0.1683794968` | High
3 | File | `/admin/?page=user/list` | High
4 | File | `/admin/ajax.php?action=save_area` | High
5 | File | `/admin/bookings/manage_booking.php` | High
6 | File | `/admin/bookings/view_booking.php` | High
7 | File | `/admin/bookings/view_details.php` | High
8 | File | `/admin/budget/manage_budget.php` | High
9 | File | `/admin/contacts/organizations/edit/2` | High
10 | File | `/admin/edit_subject.php` | High
11 | File | `/admin/inquiries/view_inquiry.php` | High
12 | File | `/admin/manage_academic.php` | High
13 | File | `/admin/modal_add_product.php` | High
14 | File | `/admin/reportupload.aspx` | High
15 | File | `/admin/save_teacher.php` | High
16 | File | `/admin/service.php` | High
17 | File | `/admin/services/view_service.php` | High
18 | File | `/admin/update_s6.php` | High
19 | File | `/admin/user/manage_user.php` | High
20 | File | `/adms/admin/?page=vehicles/sell_vehicle` | High
21 | File | `/adms/admin/?page=vehicles/view_transaction` | High
22 | File | `/ajax.php?action=read_msg` | High
23 | File | `/ajax.php?action=save_company` | High
24 | File | `/api/stl/actions/search` | High
25 | File | `/backup.pl` | Medium
26 | File | `/bin/ate` | Medium
27 | File | `/bin/httpd` | Medium
28 | File | `/boafrm/formFilter` | High
29 | File | `/building/backmgr/urlpage/mobileurl/configfile/jx2_config.ini` | High
30 | File | `/cas/logout` | Medium
31 | File | `/cgi-bin/ping.cgi` | High
32 | File | `/classes/Master.php` | High
33 | File | `/classes/Master.php?f=delete_item` | High
34 | File | `/classes/Master.php?f=delete_service` | High
35 | File | `/classes/Master.php?f=save_course` | High
36 | File | `/cms/category/list` | High
37 | File | `/csms/?page=contact_us` | High
38 | File | `/csms/admin/?page=system_info` | High
39 | File | `/csms/admin/?page=user/list` | High
40 | File | `/DocSystem/Repos/getReposAllUsers.do` | High
41 | File | `/dosen/data` | Medium
42 | File | `/E-mobile/App/System/File/downfile.php` | High
43 | File | `/ecshop/admin/template.php` | High
44 | File | `/file_manager/admin/save_user.php` | High
45 | File | `/forum/PostPrivateMessage` | High
46 | File | `/fos/admin/ajax.php?action=login` | High
47 | File | `/fos/admin/index.php?page=menu` | High
48 | File | `/goForm/aspForm` | High
49 | File | `/home/cavesConsole` | High
50 | File | `/home/kickPlayer` | High
51 | File | `/home/masterConsole` | High
52 | File | `/home/sendBroadcast` | High
53 | File | `/hslist` | Low
54 | File | `/inc/jquery/uploadify/uploadify.php` | High
55 | File | `/index.php?app=main&func=passport&action=login` | High
56 | File | `/jurusan/data` | High
57 | File | `/jurusanmatkul/data` | High
58 | File | `/kelas/data` | Medium
59 | File | `/kelasdosen/data` | High
60 | File | `/Login/CheckLogin` | High
61 | File | `/mahasiswa/data` | High
62 | File | `/matkul/data` | Medium
63 | File | `/note/index/delete` | High
64 | File | `/oews/classes/Master.php?f=update_cart` | High
65 | File | `/param.file.tgz` | High
66 | File | `/php-opos/index.php` | High
67 | File | `/php-sms/admin/` | High
68 | File | `/picturesPreview` | High
69 | File | `/queuing/login.php` | High
70 | File | `/reviewer/system/system/admins/manage/users/user-update.php` | High
71 | File | `/royal_event/companyprofile.php` | High
72 | File | `/royal_event/userregister.php` | High
73 | File | `/send_order.cgi?parameter=access_detect` | High
74 | File | `/server/api/v1/login` | High
75 | File | `/squashfs-root/etc_ro/custom.conf` | High
76 | File | `/SystemManage/Organize/GetTreeGridJson?_search=false&nd=1681813520783&rows=10000&page=1&sidx=&sord=asc` | High
77 | File | `/SystemManage/Role/GetGridJson?keyword=&page=1&rows=20` | High
78 | File | `/SystemManage/User/GetGridJson?_search=false&nd=1680855479750&rows=50&page=1&sidx=F_CreatorTime+desc&sord=asc` | High
79 | File | `/user/s.php` | Medium
80 | File | `/user/updatePwd` | High
81 | File | `/v2/#/` | Low
82 | File | `/v2/#/add/department` | High
83 | File | `/webroot/inc/utility_all.php` | High
84 | File | `/wireless/basic.asp` | High
85 | File | `/wireless/guestnetwork.asp` | High
86 | File | `/wireless/security.asp` | High
87 | File | `01article.php` | High
88 | File | `14all.cgi/14all-1.1.cgi/traffic.cgi/mrtg.cgi` | High
89 | File | `action.php` | Medium
90 | File | `add-locker-form.php` | High
91 | File | `add_contestant.php` | High
92 | File | `admin/` | Low
93 | File | `admin/?page=categories/manage_category` | High
94 | File | `admin/?page=categories/view_category` | High
95 | File | `admin/?page=items/manage_item` | High
96 | File | `admin/?page=items/view_item` | High
97 | File | `admin/?page=user/manage_user` | High
98 | File | `admin/abc.php` | High
99 | ... | ... | ...

There are 880 more IOA items available (file, library, argument, input value, pattern, network port). Please use our online service to access the data.

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
