# Panda - Cyber Threat Intelligence

These _indicators_ were reported, collected, and generated during the [VulDB CTI analysis](https://vuldb.com/?kb.cti) of the actor known as [Panda](https://vuldb.com/?actor.panda). The _activity monitoring_ correlates data from social media, forums, chat rooms, and darknet markets. It helps to determine associated actors, specific activities, expected intentions, emerging research, and ongoing attacks. Our unique _predictive model_ uses _big data_ to forecast activities and their characteristics.

_Live data_ and more _analysis capabilities_ are available at [https://vuldb.com/?actor.panda](https://vuldb.com/?actor.panda)

## IOC - Indicator of Compromise

These _indicators of compromise_ (IOC) indicate associated network resources which are known to be part of research and attack activities of Panda.

ID | IP address | Hostname | Campaign | Confidence
-- | ---------- | -------- | -------- | ----------
1 | [3.123.17.223](https://vuldb.com/?ip.3.123.17.223) | ec2-3-123-17-223.eu-central-1.compute.amazonaws.com | - | Medium
2 | [5.56.133.246](https://vuldb.com/?ip.5.56.133.246) | 5-56-133-246.static.karizanta.com | - | High
3 | [13.62.0.0](https://vuldb.com/?ip.13.62.0.0) | - | - | High
4 | [45.77.45.228](https://vuldb.com/?ip.45.77.45.228) | 45.77.45.228.vultrusercontent.com | - | Medium
5 | [46.173.217.80](https://vuldb.com/?ip.46.173.217.80) | - | - | High
6 | ... | ... | ... | ...

There are 18 more IOC items available. Please use our online service to access the data.

## TTP - Tactics, Techniques, Procedures

_Tactics, techniques, and procedures_ (TTP) summarize the suspected MITRE ATT&CK techniques used by _Panda_. This data is unique as it uses our predictive model for actor profiling.

ID | Technique | Weakness | Description | Confidence
-- | --------- | -------- | ----------- | ----------
1 | T1006 | CWE-21, CWE-22, CWE-24, CWE-425 | Path Traversal | High
2 | T1040 | CWE-319 | Authentication Bypass by Capture-replay | High
3 | T1055 | CWE-74 | Improper Neutralization of Data within XPath Expressions | High
4 | T1059 | CWE-88, CWE-94, CWE-1321 | Argument Injection | High
5 | T1059.007 | CWE-79, CWE-80 | Basic Cross Site Scripting | High
6 | ... | ... | ... | ...

There are 22 more TTP items available. Please use our online service to access the data.

## IOA - Indicator of Attack

These _indicators of attack_ (IOA) list the potential fragments used for technical activities like reconnaissance, exploitation, privilege escalation, and exfiltration by Panda. This data is unique as it uses our predictive model for actor profiling.

ID | Type | Indicator | Confidence
-- | ---- | --------- | ----------
1 | File | `/?g=log_import_save` | High
2 | File | `/?page=reserve` | High
3 | File | `/?r=recruit/resume/edit&op=status` | High
4 | File | `/academy/home/courses` | High
5 | File | `/academy/tutor/filter` | High
6 | File | `/account/delivery` | High
7 | File | `/accounts_con/register_account` | High
8 | File | `/actuator/heapdump` | High
9 | File | `/add-students.php` | High
10 | File | `/addbill.php` | Medium
11 | File | `/addcategory.php` | High
12 | File | `/addclient1.php` | High
13 | File | `/addcompany.php` | High
14 | File | `/admin` | Low
15 | File | `/admin-cp/theme/editor/default` | High
16 | File | `/admin.php?m=Acquisi&a=testcj&lid=1` | High
17 | File | `/admin/` | Low
18 | File | `/admin/?action=home&do=shop:index&keyword=&kind=all` | High
19 | File | `/admin/?page=musics/manage_music` | High
20 | File | `/admin/?page=reports` | High
21 | File | `/admin/?page=system_info/contact_info` | High
22 | File | `/admin/about-us.php` | High
23 | File | `/admin/about_edit.php?action=modify` | High
24 | File | `/admin/add-category.php` | High
25 | File | `/admin/add-services.php` | High
26 | File | `/admin/add_sundaysch.php` | High
27 | File | `/admin/admin-profile.php` | High
28 | File | `/admin/admin_invt2.php` | High
29 | File | `/admin/ajax.php?action=confirm_order` | High
30 | File | `/admin/ajax.php?action=save_settings` | High
31 | File | `/admin/ajax.php?action=save_student` | High
32 | File | `/admin/api/admin/articles/` | High
33 | File | `/admin/api/admin/v2_products` | High
34 | File | `/admin/api/theme-edit/` | High
35 | File | `/admin/article/article-add.php` | High
36 | File | `/admin/article/article-edit-run.php` | High
37 | File | `/admin/assets/` | High
38 | File | `/admin/blood/update/B+.php` | High
39 | File | `/admin/category/cate-edit-run.php` | High
40 | File | `/Admin/changepassword.php` | High
41 | File | `/admin/class.php?dowhat=modifyclass` | High
42 | File | `/admin/clients` | High
43 | File | `/admin/client_user` | High
44 | File | `/admin/cms_content.php` | High
45 | File | `/admin/content` | High
46 | File | `/admin/court-type` | High
47 | File | `/Admin/createClass.php` | High
48 | File | `/admin/del_category.php` | High
49 | File | `/admin/del_feedback.php` | High
50 | File | `/admin/dialog/select_images_post.php` | High
51 | File | `/admin/edit-accepted-appointment.php` | High
52 | File | `/admin/edit-services.php` | High
53 | File | `/admin/edit_category.php` | High
54 | File | `/admin/edit_product.php` | High
55 | File | `/admin/File/fileUpload` | High
56 | File | `/admin/file_manager/files` | High
57 | File | `/admin/foreigner-search.php` | High
58 | File | `/admin/forgot-password.php` | High
59 | File | `/admin/general-setting` | High
60 | File | `/admin/index.php` | High
61 | File | `/admin/index.php?page=categories` | High
62 | File | `/admin/index.php?page=manage_product` | High
63 | File | `/admin/index.php?r=banner%2Fbanner-create` | High
64 | File | `/admin/index.php?r=friendly-link%2Fupdate` | High
65 | File | `/admin/index/index.html#/admin/mall.goods/index.html` | High
66 | File | `/admin/invoice.php` | High
67 | File | `/admin/leancloud.php` | High
68 | File | `/admin/list_addr_fwresource_ip.php` | High
69 | File | `/admin/list_onlineuser.php` | High
70 | File | `/admin/login.php` | High
71 | File | `/admin/maintenance/manage_department.php` | High
72 | File | `/admin/manage-users.php` | High
73 | File | `/admin/modules/product/controller.php?action=add` | High
74 | File | `/admin/normal-bwdates-reports-details.php` | High
75 | File | `/admin/normal-search.php` | High
76 | File | `/admin/order.php` | High
77 | File | `/admin/pages/` | High
78 | File | `/admin/regester.php` | High
79 | File | `/admin/role` | Medium
80 | File | `/admin/save.php` | High
81 | File | `/admin/search-appointment.php` | High
82 | File | `/admin/singlelogin.php?submit=1` | High
83 | File | `/admin/system.php` | High
84 | File | `/admin/system/dict/add.json?sqlid=system.dict.save` | High
85 | File | `/admin/sys_sql_query.php` | High
86 | File | `/admin/tag.php` | High
87 | File | `/admin/tasks` | Medium
88 | File | `/admin/tax` | Medium
89 | File | `/admin/template` | High
90 | File | `/admin/template/edit` | High
91 | File | `/admin/test_status.php` | High
92 | File | `/admin/twitter.php` | High
93 | File | `/Admin/user-record.php` | High
94 | File | `/admin/user/user-move-run.php` | High
95 | File | `/admin/vendor` | High
96 | File | `/admin/vote_edit.php` | High
97 | File | `/adminPage/conf/reload` | High
98 | File | `/adminPage/main/upload` | High
99 | File | `/adminPage/www/addOver` | High
100 | File | `/adplanet/PlanetCommentList` | High
101 | File | `/ajax.php?action=update_account` | High
102 | File | `/ajax/check_medicine_name.php` | High
103 | File | `/api/browserextension/UpdatePassword/` | High
104 | File | `/api/dept` | Medium
105 | File | `/api/dept/build` | High
106 | File | `/api/discoveries/` | High
107 | File | `/api/es/admin/v3/security/user/1` | High
108 | File | `/api/log/killJob` | High
109 | File | `/api/public/signup` | High
110 | File | `/api/role` | Medium
111 | File | `/api/sys/set_passwd` | High
112 | File | `/api/user` | Medium
113 | File | `/api/v1/attack` | High
114 | File | `/api/v1/attack/token` | High
115 | File | `/api/v2/maps` | Medium
116 | File | `/api/v2/open/rowsInfo` | High
117 | File | `/api/v2/open/tablesInfo` | High
118 | File | `/app/admin/controller/file/File.php` | High
119 | File | `/apply.cgi` | Medium
120 | File | `/article/DelectArticleById/` | High
121 | File | `/auth/user/all.api` | High
122 | File | `/autheditpwd.php` | High
123 | File | `/back/index.php/user/User/?1` | High
124 | File | `/bin/boa` | Medium
125 | File | `/blog-single.php` | High
126 | File | `/blog/comment` | High
127 | File | `/boaform/device_reset.cgi` | High
128 | File | `/book-services.php` | High
129 | File | `/bsms_ci/index.php/user/edit_user/` | High
130 | File | `/bwdate-report-details.php` | High
131 | File | `/catalog/all-products` | High
132 | File | `/CDGServer3/document/Catelogs;logindojojs?command=DelCatelogs` | High
133 | File | `/cgi-bin/cstecgi.cgi` | High
134 | File | `/cgi-bin/cstecgi.cgi?action=login&flag=1` | High
135 | File | `/cgi-bin/discovery.cgi` | High
136 | File | `/cgi-bin/myMusic.cgi` | High
137 | File | `/cgi-bin/p1_ftpserver.php` | High
138 | File | `/cgi-bin/photocenter_mgr.cgi` | High
139 | File | `/cgi-bin/tosei_kikai.php` | High
140 | File | `/cgi-bin/vitogate.cgi` | High
141 | File | `/cgi-bin/webdav_mgr.cgi` | High
142 | File | `/cgi-bin/webfile_mgr.cgi` | High
143 | File | `/cgi-bin/widget_api.cgi` | High
144 | File | `/checkout` | Medium
145 | File | `/classes/Master.php?f=load_registration` | High
146 | File | `/classes/Master.php?f=log_employee` | High
147 | File | `/classes/Master.php? f=save_medicine` | High
148 | File | `/classes/Users.php` | High
149 | File | `/cloudstore/ecode/setup/ecology_dev.zip` | High
150 | File | `/cm/update_rows/page?id=2` | High
151 | File | `/cms/category/list` | High
152 | File | `/cms/classes/Users.php?f=delete_client` | High
153 | File | `/company/store` | High
154 | File | `/conf/app.conf` | High
155 | File | `/config,admin.jsp` | High
156 | File | `/config-manager/save` | High
157 | File | `/control/activate_case.php` | High
158 | File | `/control/adds.php` | High
159 | File | `/control/add_act.php` | High
160 | ... | ... | ...

There are 1423 more IOA items available (file, library, argument, input value, pattern, network port). Please use our online service to access the data.

## References

The following list contains _external sources_ which discuss the actor and the associated activities:

* https://blog.talosintelligence.com/2019/09/panda-evolution.html
* https://jp.security.ntt/tech_blog/102glv5
* https://www.welivesecurity.com/2023/04/26/evasive-panda-apt-group-malware-updates-popular-chinese-software/

## Literature

The following _articles_ explain our unique predictive cyber threat intelligence:

* [VulDB Cyber Threat Intelligence Documentation](https://vuldb.com/?kb.cti)
* [Cyber Threat Intelligence - Early Anticipation of Attacks](https://www.scip.ch/en/?labs.20201022)

## License

(c) [1997-2026](https://vuldb.com/?kb.changelog) by [vuldb.com](https://vuldb.com/?kb.about). All data on this page is shared under the license [CC BY-NC-SA 4.0](https://creativecommons.org/licenses/by-nc-sa/4.0/). Questions? Check the [FAQ](https://vuldb.com/?kb.faq), read the [documentation](https://vuldb.com/?kb) or [contact us](https://vuldb.com/?contact)!
