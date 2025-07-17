# PoshC2 - Cyber Threat Intelligence

These _indicators_ were reported, collected, and generated during the [VulDB CTI analysis](https://vuldb.com/?kb.cti) of the actor known as [PoshC2](https://vuldb.com/?actor.poshc2). The _activity monitoring_ correlates data from social media, forums, chat rooms, and darknet markets. It helps to determine associated actors, specific activities, expected intentions, emerging research, and ongoing attacks. Our unique _predictive model_ uses _big data_ to forecast activities and their characteristics.

_Live data_ and more _analysis capabilities_ are available at [https://vuldb.com/?actor.poshc2](https://vuldb.com/?actor.poshc2)

## Countries

These _countries_ are directly (e.g. origin of attacks) or indirectly (e.g. access by proxy) associated with PoshC2:

* [US](https://vuldb.com/?country.us)
* [CN](https://vuldb.com/?country.cn)
* [RU](https://vuldb.com/?country.ru)
* ...

There are 10 more country items available. Please use our online service to access the data.

## IOC - Indicator of Compromise

These _indicators of compromise_ (IOC) indicate associated network resources which are known to be part of research and attack activities of PoshC2.

ID | IP address | Hostname | Campaign | Confidence
-- | ---------- | -------- | -------- | ----------
1 | [3.111.63.221](https://vuldb.com/?ip.3.111.63.221) | ec2-3-111-63-221.ap-south-1.compute.amazonaws.com | - | Medium
2 | [3.120.209.174](https://vuldb.com/?ip.3.120.209.174) | ec2-3-120-209-174.eu-central-1.compute.amazonaws.com | - | Medium
3 | [3.121.42.179](https://vuldb.com/?ip.3.121.42.179) | ec2-3-121-42-179.eu-central-1.compute.amazonaws.com | - | Medium
4 | [3.253.77.60](https://vuldb.com/?ip.3.253.77.60) | ec2-3-253-77-60.eu-west-1.compute.amazonaws.com | - | Medium
5 | [13.48.77.144](https://vuldb.com/?ip.13.48.77.144) | ec2-13-48-77-144.eu-north-1.compute.amazonaws.com | - | Medium
6 | [13.49.46.253](https://vuldb.com/?ip.13.49.46.253) | ec2-13-49-46-253.eu-north-1.compute.amazonaws.com | - | Medium
7 | [13.61.7.218](https://vuldb.com/?ip.13.61.7.218) | ec2-13-61-7-218.eu-north-1.compute.amazonaws.com | - | Medium
8 | [13.78.10.244](https://vuldb.com/?ip.13.78.10.244) | - | - | High
9 | [13.86.108.33](https://vuldb.com/?ip.13.86.108.33) | - | - | High
10 | [15.237.162.48](https://vuldb.com/?ip.15.237.162.48) | ec2-15-237-162-48.eu-west-3.compute.amazonaws.com | - | Medium
11 | [18.133.253.38](https://vuldb.com/?ip.18.133.253.38) | ec2-18-133-253-38.eu-west-2.compute.amazonaws.com | - | Medium
12 | [18.134.14.164](https://vuldb.com/?ip.18.134.14.164) | ec2-18-134-14-164.eu-west-2.compute.amazonaws.com | - | Medium
13 | [18.171.35.225](https://vuldb.com/?ip.18.171.35.225) | ec2-18-171-35-225.eu-west-2.compute.amazonaws.com | - | Medium
14 | [34.27.146.70](https://vuldb.com/?ip.34.27.146.70) | 70.146.27.34.bc.googleusercontent.com | - | Medium
15 | [34.58.151.162](https://vuldb.com/?ip.34.58.151.162) | 162.151.58.34.bc.googleusercontent.com | - | Medium
16 | [34.170.235.99](https://vuldb.com/?ip.34.170.235.99) | 99.235.170.34.bc.googleusercontent.com | - | Medium
17 | [34.172.208.55](https://vuldb.com/?ip.34.172.208.55) | 55.208.172.34.bc.googleusercontent.com | - | Medium
18 | ... | ... | ... | ...

There are 69 more IOC items available. Please use our online service to access the data.

## TTP - Tactics, Techniques, Procedures

_Tactics, techniques, and procedures_ (TTP) summarize the suspected MITRE ATT&CK techniques used by _PoshC2_. This data is unique as it uses our predictive model for actor profiling.

ID | Technique | Weakness | Description | Confidence
-- | --------- | -------- | ----------- | ----------
1 | T1006 | CWE-21, CWE-22, CWE-23, CWE-24, CWE-425 | Path Traversal | High
2 | T1055 | CWE-74 | Improper Neutralization of Data within XPath Expressions | High
3 | T1059 | CWE-94, CWE-1321 | Argument Injection | High
4 | T1059.007 | CWE-79, CWE-80 | Basic Cross Site Scripting | High
5 | T1068 | CWE-250, CWE-264, CWE-269, CWE-284 | Execution with Unnecessary Privileges | High
6 | ... | ... | ... | ...

There are 20 more TTP items available. Please use our online service to access the data.

## IOA - Indicator of Attack

These _indicators of attack_ (IOA) list the potential fragments used for technical activities like reconnaissance, exploitation, privilege escalation, and exfiltration by PoshC2. This data is unique as it uses our predictive model for actor profiling.

ID | Type | Indicator | Confidence
-- | ---- | --------- | ----------
1 | File | `%PROGRAMFILES(X86)%\TSplus\Clients\www.` | High
2 | File | `/%61dmin/api/logs` | High
3 | File | `/;/admin/role/edit` | High
4 | File | `/?route=extension/live_search/module/live_search.searchresults` | High
5 | File | `/aboutedit.php` | High
6 | File | `/action/upload_file` | High
7 | File | `/add-pig.php` | Medium
8 | File | `/add-students.php` | High
9 | File | `/addclient1.php` | High
10 | File | `/addpayment.php` | High
11 | File | `/add_user.php` | High
12 | File | `/adicionar-cliente.php` | High
13 | File | `/admin#permissions` | High
14 | File | `/admin#themes` | High
15 | File | `/admin-api/bpm/model/deploy` | High
16 | File | `/admin-api/infra/file/upload` | High
17 | File | `/admin/` | Low
18 | File | `/admin/?page=inventory/view_inventory&id=2` | High
19 | File | `/admin/?page=system_info/contact_info` | High
20 | File | `/admin/?page=user/manage_user&id=3` | High
21 | File | `/admin/aboutus.php` | High
22 | File | `/Admin/add-admin.php` | High
23 | File | `/admin/add-customer.php` | High
24 | File | `/admin/admin-profile.php` | High
25 | File | `/Admin/adminlogin.php` | High
26 | File | `/admin/adminScoreUrl` | High
27 | File | `/admin/admin_login.php` | High
28 | File | `/admin/admin_members.php?ac=search` | High
29 | File | `/admin/ad_list.php?action=pass` | High
30 | File | `/admin/ajax.php?action=delete_user` | High
31 | File | `/Admin/akun_edit.php` | High
32 | File | `/admin/all_users.php` | High
33 | File | `/admin/app/profile_crud.php` | High
34 | File | `/admin/app/role_crud.php` | High
35 | File | `/admin/app/soulwinning_crud.php` | High
36 | File | `/admin/approve.php` | High
37 | File | `/admin/assets/` | High
38 | File | `/admin/assets/plugins/DataTables/media/unit_testing/templates/complex_header_2.php` | High
39 | File | `/admin/assets/plugins/DataTables/media/unit_testing/templates/deferred_table.php` | High
40 | File | `/admin/assets/plugins/DataTables/media/unit_testing/templates/dom_data_th.php` | High
41 | File | `/admin/assets/plugins/DataTables/media/unit_testing/templates/empty_table.php` | High
42 | File | `/admin/attendance_action.php` | High
43 | File | `/admin/blood/update/B+.php` | High
44 | File | `/admin/booking-details.php` | High
45 | File | `/admin/campsdetails.php` | High
46 | File | `/admin/categories/manage_category.php` | High
47 | File | `/admin/categories/save` | High
48 | File | `/admin/change-image.php` | High
49 | File | `/admin/clients/` | High
50 | File | `/admin/cmsTagType/save` | High
51 | File | `/admin/config/uploadicon.php` | High
52 | File | `/Admin/consulting_detail.php` | High
53 | File | `/admin/content/book` | High
54 | File | `/admin/content/editor` | High
55 | File | `/admin/delete_bloodGroup.php` | High
56 | File | `/admin/del_feedback.php` | High
57 | File | `/admin/dialog/select_images_post.php` | High
58 | File | `/admin/edit-brand.php` | High
59 | File | `/admin/edit-user.php` | High
60 | File | `/Admin/EditCategory` | High
61 | File | `/admin/edit_customer.php` | High
62 | File | `/admin/edit_fuel.php` | High
63 | File | `/admin/edit_manufacturer.php` | High
64 | File | `/admin/edit_state.php` | High
65 | File | `/admin/emp-profile-avatar.php` | High
66 | File | `/admin/fetch_product_details.php` | High
67 | File | `/admin/File/fileUpload` | High
68 | File | `/admin/File/pictureUpload` | High
69 | File | `/admin/file_manager/export` | High
70 | File | `/admin/forgot-password.php` | High
71 | File | `/admin/forms/add/step2.php?submission_type=direct` | High
72 | File | `/admin/forms/option_lists/edit.php` | High
73 | File | `/admin/index.php` | High
74 | File | `/admin/index2.html` | High
75 | File | `/admin/login.php` | High
76 | File | `/admin/maintenance/manage_department.php` | High
77 | File | `/admin/model/addOrUpdate` | High
78 | File | `/admin/mod_room/controller.php?action=add` | High
79 | File | `/admin/network/ajax_getChannelList` | High
80 | File | `/admin/network/diag_iperf` | High
81 | File | `/admin/network/diag_pinginterface` | High
82 | File | `/admin/network/diag_traceroute` | High
83 | File | `/admin/network/wifi_schedule` | High
84 | File | `/admin/newsletter.php` | High
85 | File | `/admin/normal-search.php` | High
86 | File | `/admin/overtime_add.php` | High
87 | File | `/admin/print1.php` | High
88 | File | `/admin/search-maid.php` | High
89 | File | `/admin/search-property.php` | High
90 | File | `/admin/search.php` | High
91 | File | `/admin/settings/index.php?page=accounts` | High
92 | File | `/admin/state.php` | High
93 | File | `/admin/sys/admin.html` | High
94 | File | `/admin/system.html` | High
95 | File | `/admin/tag.php` | High
96 | File | `/admin/update_room.php` | High
97 | File | `/admin/update_user.php` | High
98 | File | `/admin/upload/upimage.html` | High
99 | File | `/admin/user-search.php` | High
100 | File | `/admin/view-user-queries.php` | High
101 | File | `/admin/View_user.php` | High
102 | File | `/adplanet/PlanetUser` | High
103 | File | `/ajax.php?action=load_answered` | High
104 | File | `/ajax.php?action=login` | High
105 | File | `/ajax.php?action=read_msg` | High
106 | File | `/ajax.php?action=save_category` | High
107 | File | `/ajax.php?action=save_establishment` | High
108 | File | `/ajax/chpwd.php` | High
109 | File | `/ajax/get_patient_history.php` | High
110 | File | `/animalsupdate.php` | High
111 | File | `/api/admin/question/edit` | High
112 | File | `/api/deploy/upload` | High
113 | File | `/api/dept/build` | High
114 | File | `/api/file/downloadUrl` | High
115 | File | `/Api/FileUploadApi.ashx` | High
116 | File | `/api/login/auth` | High
117 | File | `/api/system/other` | High
118 | File | `/api/test/download` | High
119 | File | `/Api/TinyMce/UploadAjaxAPI.ashx` | High
120 | File | `/api/upload` | Medium
121 | File | `/api/upload/image` | High
122 | File | `/api/wizard/getNetworkConf` | High
123 | File | `/api/wizard/getNetworkStatus` | High
124 | File | `/api/wizard/getssidname` | High
125 | File | `/api/wizard/getWifiNeighbour` | High
126 | File | `/app/action/add_staff.php` | High
127 | File | `/app/admin/controller/file/File.php` | High
128 | File | `/app/admin/view/web_user.html` | High
129 | ... | ... | ...

There are 1149 more IOA items available (file, library, argument, input value, pattern, network port). Please use our online service to access the data.

## References

The following list contains _external sources_ which discuss the actor and the associated activities:

* https://search.censys.io/hosts/3.111.63.221
* https://search.censys.io/hosts/3.121.42.179
* https://search.censys.io/hosts/3.253.77.60
* https://search.censys.io/hosts/13.48.77.144
* https://search.censys.io/hosts/13.61.7.218
* https://search.censys.io/hosts/13.86.108.33
* https://search.censys.io/hosts/15.237.162.48
* https://search.censys.io/hosts/18.133.253.38
* https://search.censys.io/hosts/18.134.14.164
* https://search.censys.io/hosts/18.171.35.225
* https://search.censys.io/hosts/34.27.146.70
* https://search.censys.io/hosts/34.58.151.162
* https://search.censys.io/hosts/34.170.235.99
* https://search.censys.io/hosts/34.172.208.55
* https://search.censys.io/hosts/44.207.92.202
* https://search.censys.io/hosts/45.79.196.203
* https://search.censys.io/hosts/45.134.26.136
* https://search.censys.io/hosts/45.147.176.188
* https://search.censys.io/hosts/46.101.126.207
* https://search.censys.io/hosts/47.76.86.199
* https://search.censys.io/hosts/51.20.69.36
* https://search.censys.io/hosts/51.20.96.197
* https://search.censys.io/hosts/51.38.113.64
* https://search.censys.io/hosts/51.77.107.137
* https://search.censys.io/hosts/51.250.38.28
* https://search.censys.io/hosts/52.230.83.254
* https://search.censys.io/hosts/54.79.123.238
* https://search.censys.io/hosts/65.20.68.219
* https://search.censys.io/hosts/70.77.124.96
* https://search.censys.io/hosts/77.83.207.24
* https://search.censys.io/hosts/79.143.181.62
* https://search.censys.io/hosts/84.200.154.125
* https://search.censys.io/hosts/88.210.9.139
* https://search.censys.io/hosts/91.240.118.204
* https://search.censys.io/hosts/94.23.228.43
* https://search.censys.io/hosts/104.248.161.33
* https://search.censys.io/hosts/119.42.148.190
* https://search.censys.io/hosts/139.84.149.193
* https://search.censys.io/hosts/139.84.172.20
* https://search.censys.io/hosts/140.99.223.53
* https://search.censys.io/hosts/157.245.128.27
* https://search.censys.io/hosts/159.100.29.105
* https://search.censys.io/hosts/159.223.159.200
* https://search.censys.io/hosts/161.35.21.152
* https://search.censys.io/hosts/164.90.183.39
* https://search.censys.io/hosts/165.227.246.129
* https://search.censys.io/hosts/166.1.22.149
* https://search.censys.io/hosts/167.99.78.69
* https://search.censys.io/hosts/176.111.174.138
* https://search.censys.io/hosts/176.119.159.177
* https://search.censys.io/hosts/184.72.153.18
* https://search.censys.io/hosts/185.119.17.37
* https://search.censys.io/hosts/185.147.124.10
* https://search.censys.io/hosts/185.147.124.104
* https://search.censys.io/hosts/185.147.124.108
* https://search.censys.io/hosts/185.167.63.27
* https://search.censys.io/hosts/185.234.216.64
* https://search.censys.io/hosts/188.245.164.247
* https://search.censys.io/hosts/192.46.215.160
* https://search.censys.io/hosts/193.22.152.104
* https://search.censys.io/hosts/213.219.37.158
* https://search.censys.io/hosts/217.15.167.175
* https://search.censys.io/hosts/217.69.3.25
* https://search.censys.io/search?resource=hosts&sort=RELEVANCE&per_page=25&virtual_hosts=EXCLUDE&q=services.software.product%3A+poshc2+and+not+labels%3A+tarpit
* https://thedfirreport.com/2024/08/12/threat-actors-toolkit-leveraging-sliver-poshc2-batch-scripts/
* https://threatfox.abuse.ch
* https://twitter.com/1ZRR4H/status/1582068501036273665
* https://twitter.com/TheDFIRReport/status/1407322479664762890
* https://www.lac.co.jp/lacwatch/people/20190213_001770.html
* https://www.lac.co.jp/lacwatch/people/20200424_002177.html
* https://www.shodan.io/host/13.49.46.253#443
* https://www.shodan.io/host/95.182.122.252#80
* https://x.com/drb_ra/status/1735296172758069289?s=20

## Literature

The following _articles_ explain our unique predictive cyber threat intelligence:

* [VulDB Cyber Threat Intelligence Documentation](https://vuldb.com/?kb.cti)
* [Cyber Threat Intelligence - Early Anticipation of Attacks](https://www.scip.ch/en/?labs.20201022)

## License

(c) [1997-2025](https://vuldb.com/?kb.changelog) by [vuldb.com](https://vuldb.com/?kb.about). All data on this page is shared under the license [CC BY-NC-SA 4.0](https://creativecommons.org/licenses/by-nc-sa/4.0/). Questions? Check the [FAQ](https://vuldb.com/?kb.faq), read the [documentation](https://vuldb.com/?kb) or [contact us](https://vuldb.com/?contact)!
