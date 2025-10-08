# Empire Downloader - Cyber Threat Intelligence

These _indicators_ were reported, collected, and generated during the [VulDB CTI analysis](https://vuldb.com/?kb.cti) of the actor known as [Empire Downloader](https://vuldb.com/?actor.empire_downloader). The _activity monitoring_ correlates data from social media, forums, chat rooms, and darknet markets. It helps to determine associated actors, specific activities, expected intentions, emerging research, and ongoing attacks. Our unique _predictive model_ uses _big data_ to forecast activities and their characteristics.

_Live data_ and more _analysis capabilities_ are available at [https://vuldb.com/?actor.empire_downloader](https://vuldb.com/?actor.empire_downloader)

## Countries

These _countries_ are directly (e.g. origin of attacks) or indirectly (e.g. access by proxy) associated with Empire Downloader:

* [DE](https://vuldb.com/?country.de)
* [US](https://vuldb.com/?country.us)
* [CN](https://vuldb.com/?country.cn)
* ...

There are 10 more country items available. Please use our online service to access the data.

## IOC - Indicator of Compromise

These _indicators of compromise_ (IOC) indicate associated network resources which are known to be part of research and attack activities of Empire Downloader.

ID | IP address | Hostname | Campaign | Confidence
-- | ---------- | -------- | -------- | ----------
1 | [3.10.19.221](https://vuldb.com/?ip.3.10.19.221) | ec2-3-10-19-221.eu-west-2.compute.amazonaws.com | - | Medium
2 | [8.211.5.170](https://vuldb.com/?ip.8.211.5.170) | - | - | High
3 | [13.48.48.93](https://vuldb.com/?ip.13.48.48.93) | ec2-13-48-48-93.eu-north-1.compute.amazonaws.com | - | Medium
4 | [13.52.36.101](https://vuldb.com/?ip.13.52.36.101) | ec2-13-52-36-101.us-west-1.compute.amazonaws.com | - | Medium
5 | [13.127.6.17](https://vuldb.com/?ip.13.127.6.17) | ec2-13-127-6-17.ap-south-1.compute.amazonaws.com | - | Medium
6 | [16.171.153.139](https://vuldb.com/?ip.16.171.153.139) | ec2-16-171-153-139.eu-north-1.compute.amazonaws.com | - | Medium
7 | [16.171.198.229](https://vuldb.com/?ip.16.171.198.229) | ec2-16-171-198-229.eu-north-1.compute.amazonaws.com | - | Medium
8 | [18.216.6.142](https://vuldb.com/?ip.18.216.6.142) | ec2-18-216-6-142.us-east-2.compute.amazonaws.com | - | Medium
9 | [18.221.226.193](https://vuldb.com/?ip.18.221.226.193) | ec2-18-221-226-193.us-east-2.compute.amazonaws.com | - | Medium
10 | [18.223.156.254](https://vuldb.com/?ip.18.223.156.254) | ec2-18-223-156-254.us-east-2.compute.amazonaws.com | - | Medium
11 | [20.102.61.215](https://vuldb.com/?ip.20.102.61.215) | - | - | High
12 | [20.234.166.219](https://vuldb.com/?ip.20.234.166.219) | - | - | High
13 | [23.96.53.135](https://vuldb.com/?ip.23.96.53.135) | - | - | High
14 | [27.106.96.167](https://vuldb.com/?ip.27.106.96.167) | - | - | High
15 | [34.32.121.27](https://vuldb.com/?ip.34.32.121.27) | 27.121.32.34.bc.googleusercontent.com | - | Medium
16 | [34.42.252.91](https://vuldb.com/?ip.34.42.252.91) | 91.252.42.34.bc.googleusercontent.com | - | Medium
17 | [34.209.255.185](https://vuldb.com/?ip.34.209.255.185) | ec2-34-209-255-185.us-west-2.compute.amazonaws.com | - | Medium
18 | ... | ... | ... | ...

There are 67 more IOC items available. Please use our online service to access the data.

## TTP - Tactics, Techniques, Procedures

_Tactics, techniques, and procedures_ (TTP) summarize the suspected MITRE ATT&CK techniques used by _Empire Downloader_. This data is unique as it uses our predictive model for actor profiling.

ID | Technique | Weakness | Description | Confidence
-- | --------- | -------- | ----------- | ----------
1 | T1006 | CWE-21, CWE-22, CWE-23, CWE-24, CWE-25, CWE-28, CWE-36 | Path Traversal | High
2 | T1040 | CWE-319 | Authentication Bypass by Capture-replay | High
3 | T1055 | CWE-74, CWE-643 | Improper Neutralization of Data within XPath Expressions | High
4 | T1059 | CWE-88, CWE-94 | Argument Injection | High
5 | T1059.007 | CWE-79, CWE-80 | Basic Cross Site Scripting | High
6 | T1068 | CWE-264, CWE-266, CWE-269, CWE-284 | Execution with Unnecessary Privileges | High
7 | ... | ... | ... | ...

There are 22 more TTP items available. Please use our online service to access the data.

## IOA - Indicator of Attack

These _indicators of attack_ (IOA) list the potential fragments used for technical activities like reconnaissance, exploitation, privilege escalation, and exfiltration by Empire Downloader. This data is unique as it uses our predictive model for actor profiling.

ID | Type | Indicator | Confidence
-- | ---- | --------- | ----------
1 | File | `.htaccess` | Medium
2 | File | `/?g=log_import_save` | High
3 | File | `/?g=net_pro_keyword_import_save` | High
4 | File | `/accounts_con/register_account` | High
5 | File | `/act/ActDao.xml` | High
6 | File | `/add-teacher.php` | High
7 | File | `/admin.php/update/getFile.html` | High
8 | File | `/admin.php?p=/Area/index#tab=t2` | High
9 | File | `/admin/` | Low
10 | File | `/admin/?page=product/manage_product&id=2` | High
11 | File | `/admin/add-category.php` | High
12 | File | `/admin/ajax.php?action=save_settings` | High
13 | File | `/admin/app/profile_crud.php` | High
14 | File | `/admin/applicants/index.php` | High
15 | File | `/admin/bookdate.php` | High
16 | File | `/admin/bwdates-report-details.php` | High
17 | File | `/admin/ca_deal.php?mudi=add&nohrefStr=close` | High
18 | File | `/admin/config_time_sync.php` | High
19 | File | `/admin/create_product.php` | High
20 | File | `/Admin/CustomerReport.php` | High
21 | File | `/admin/edit-services.php` | High
22 | File | `/admin/edit_customer.php` | High
23 | File | `/Admin/Http/Controllers/FileManagerController.php` | High
24 | File | `/admin/inquiries/view_inquiry.php` | High
25 | File | `/admin/judge` | Medium
26 | File | `/admin/login.php` | High
27 | File | `/admin/manage-users.php` | High
28 | File | `/admin/newsletter.php` | High
29 | File | `/admin/Operations/Role.php` | High
30 | File | `/admin/profile.php` | High
31 | File | `/admin/room.php` | High
32 | File | `/admin/search-appointment.php` | High
33 | File | `/admin/search-maid.php` | High
34 | File | `/admin/search-vehicle.php` | High
35 | File | `/ajax.php` | Medium
36 | File | `/ajax.php?action=delete_block` | High
37 | File | `/ajax.php?action=login` | High
38 | File | `/ajax.php?Ajax=GetModal_Sensor_Graph` | High
39 | File | `/ajax/chpwd.php` | High
40 | File | `/api/DataDictionary/GetItemList` | High
41 | File | `/api/system/dept/tree?sort=parentId%2Casc&sort=sort%2Casc` | High
42 | File | `/api/v1/snapshots` | High
43 | File | `/api/v4/teams//channels/deleted` | High
44 | File | `/apiclient/ember/index.jsp` | High
45 | File | `/app/control/byt_cv_manager` | High
46 | File | `/application/index/controller/Datament.php` | High
47 | File | `/App_Resource/UEditor/server/upload.aspx` | High
48 | File | `/auth/user/all.api` | High
49 | File | `/blog` | Low
50 | File | `/cgi-bin` | Medium
51 | File | `/cgi-bin/account_mgr.cgi?cmd=cgi_user_add` | High
52 | File | `/cgi-bin/cstecgi.cgi` | High
53 | File | `/cgi-bin/hd_config.cgi` | High
54 | File | `/cgi-bin/webdav_mgr.cgi` | High
55 | File | `/change-language/de_DE` | High
56 | File | `/classes/Master.php` | High
57 | File | `/classes/Master.php?f=delete_category` | High
58 | File | `/classes/Users.php?f=save` | High
59 | File | `/client/get_gis_fence.php` | High
60 | File | `/ClientArea/RuntimeInfoData.mwsl` | High
61 | File | `/com/esafenet/servlet/policy/HookService.java` | High
62 | File | `/control/activate_case.php` | High
63 | File | `/controllers/control.php` | High
64 | File | `/dash/update.php` | High
65 | File | `/dashboard/admin/submit_payments.php` | High
66 | File | `/dashboard/updatelogo.php` | High
67 | File | `/debug/pprof` | Medium
68 | File | `/debuginfo.htm` | High
69 | File | `/deletebird.php` | High
70 | File | `/depotHead/list` | High
71 | File | `/detail.php` | Medium
72 | File | `/dets/add-expense.php` | High
73 | File | `/dev-api/api/comment/add` | High
74 | File | `/device.rsp?opt=sys&cmd=___S_O_S_T_R_E_A_MAX___` | High
75 | File | `/diag_ping.cmd?action=test&interface=ppp0.1&ipaddr=8.8.8.8%26%26cat%20/etc/passwd&ipversion=4&sessionKey=test` | High
76 | File | `/E-mobile/App/System/File/downfile.php` | High
77 | File | `/edit-pig.php` | High
78 | File | `/edit_account.php` | High
79 | File | `/Employer/EditProfile.php` | High
80 | File | `/Employer/ManageJob.php` | High
81 | ... | ... | ...

There are 709 more IOA items available (file, library, argument, input value, pattern, network port). Please use our online service to access the data.

## References

The following list contains _external sources_ which discuss the actor and the associated activities:

* https://search.censys.io/hosts/8.211.5.170
* https://search.censys.io/hosts/13.127.6.17
* https://search.censys.io/hosts/18.216.6.142
* https://search.censys.io/hosts/18.223.156.254
* https://search.censys.io/hosts/20.234.166.219
* https://search.censys.io/hosts/27.106.96.167
* https://search.censys.io/hosts/34.32.121.27
* https://search.censys.io/hosts/34.42.252.91
* https://search.censys.io/hosts/34.209.255.185
* https://search.censys.io/hosts/34.229.188.97
* https://search.censys.io/hosts/40.113.165.132
* https://search.censys.io/hosts/45.112.73.47
* https://search.censys.io/hosts/45.137.70.250
* https://search.censys.io/hosts/47.100.87.118
* https://search.censys.io/hosts/49.13.51.178
* https://search.censys.io/hosts/52.205.143.192
* https://search.censys.io/hosts/62.84.179.62
* https://search.censys.io/hosts/66.175.209.161
* https://search.censys.io/hosts/67.223.117.247
* https://search.censys.io/hosts/74.50.66.203
* https://search.censys.io/hosts/79.110.49.15
* https://search.censys.io/hosts/80.15.141.250
* https://search.censys.io/hosts/81.70.172.120
* https://search.censys.io/hosts/82.29.165.81
* https://search.censys.io/hosts/83.255.8.92
* https://search.censys.io/hosts/88.99.192.212
* https://search.censys.io/hosts/89.58.40.80
* https://search.censys.io/hosts/89.110.81.103
* https://search.censys.io/hosts/100.27.212.26
* https://search.censys.io/hosts/108.61.252.113
* https://search.censys.io/hosts/111.118.149.38
* https://search.censys.io/hosts/123.56.43.176
* https://search.censys.io/hosts/123.249.16.132
* https://search.censys.io/hosts/137.59.231.46
* https://search.censys.io/hosts/147.135.92.77
* https://search.censys.io/hosts/148.244.217.200
* https://search.censys.io/hosts/152.42.156.19
* https://search.censys.io/hosts/152.42.156.214
* https://search.censys.io/hosts/161.97.87.37
* https://search.censys.io/hosts/165.22.209.134
* https://search.censys.io/hosts/165.22.210.161
* https://search.censys.io/hosts/167.99.57.129
* https://search.censys.io/hosts/167.99.188.167
* https://search.censys.io/hosts/168.100.8.8
* https://search.censys.io/hosts/170.64.207.117
* https://search.censys.io/hosts/173.255.233.249
* https://search.censys.io/hosts/185.227.152.100
* https://search.censys.io/hosts/194.79.46.110
* https://search.censys.io/hosts/207.180.246.14
* https://search.censys.io/hosts/217.154.202.181
* https://search.censys.io/hosts/217.154.237.203
* https://threatfox.abuse.ch
* https://twitter.com/Malwar3Ninja/status/1448234445920563200
* https://www.shodan.io/host/178.128.220.125#80

## Literature

The following _articles_ explain our unique predictive cyber threat intelligence:

* [VulDB Cyber Threat Intelligence Documentation](https://vuldb.com/?kb.cti)
* [Cyber Threat Intelligence - Early Anticipation of Attacks](https://www.scip.ch/en/?labs.20201022)

## License

(c) [1997-2025](https://vuldb.com/?kb.changelog) by [vuldb.com](https://vuldb.com/?kb.about). All data on this page is shared under the license [CC BY-NC-SA 4.0](https://creativecommons.org/licenses/by-nc-sa/4.0/). Questions? Check the [FAQ](https://vuldb.com/?kb.faq), read the [documentation](https://vuldb.com/?kb) or [contact us](https://vuldb.com/?contact)!
