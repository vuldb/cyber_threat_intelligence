# N-W0rm - Cyber Threat Intelligence

These _indicators_ were reported, collected, and generated during the [VulDB CTI analysis](https://vuldb.com/?kb.cti) of the actor known as [N-W0rm](https://vuldb.com/?actor.n-w0rm). The _activity monitoring_ correlates data from social media, forums, chat rooms, and darknet markets. It helps to determine associated actors, specific activities, expected intentions, emerging research, and ongoing attacks. Our unique _predictive model_ uses _big data_ to forecast activities and their characteristics.

_Live data_ and more _analysis capabilities_ are available at [https://vuldb.com/?actor.n-w0rm](https://vuldb.com/?actor.n-w0rm)

## Countries

These _countries_ are directly (e.g. origin of attacks) or indirectly (e.g. access by proxy) associated with N-W0rm:

* [VN](https://vuldb.com/?country.vn)
* [CN](https://vuldb.com/?country.cn)
* [US](https://vuldb.com/?country.us)
* ...

There are 2 more country items available. Please use our online service to access the data.

## IOC - Indicator of Compromise

These _indicators of compromise_ (IOC) indicate associated network resources which are known to be part of research and attack activities of N-W0rm.

ID | IP address | Hostname | Campaign | Confidence
-- | ---------- | -------- | -------- | ----------
1 | [2.56.254.54](https://vuldb.com/?ip.2.56.254.54) | - | - | High
2 | [5.188.159.44](https://vuldb.com/?ip.5.188.159.44) | - | - | High
3 | [14.241.58.222](https://vuldb.com/?ip.14.241.58.222) | static.vnpt.vn | - | High
4 | [20.48.21.149](https://vuldb.com/?ip.20.48.21.149) | - | - | High
5 | [23.7.53.229](https://vuldb.com/?ip.23.7.53.229) | a23-7-53-229.deploy.static.akamaitechnologies.com | - | High
6 | [23.8.82.173](https://vuldb.com/?ip.23.8.82.173) | a23-8-82-173.deploy.static.akamaitechnologies.com | - | High
7 | [23.9.169.37](https://vuldb.com/?ip.23.9.169.37) | a23-9-169-37.deploy.static.akamaitechnologies.com | - | High
8 | [23.204.189.35](https://vuldb.com/?ip.23.204.189.35) | a23-204-189-35.deploy.static.akamaitechnologies.com | - | High
9 | [35.83.156.201](https://vuldb.com/?ip.35.83.156.201) | ec2-35-83-156-201.us-west-2.compute.amazonaws.com | - | Medium
10 | [35.168.183.178](https://vuldb.com/?ip.35.168.183.178) | ec2-35-168-183-178.compute-1.amazonaws.com | - | Medium
11 | [37.113.171.12](https://vuldb.com/?ip.37.113.171.12) | dynamicip-37-113-171-12.pppoe.chel.ertelecom.ru | - | High
12 | [37.120.141.147](https://vuldb.com/?ip.37.120.141.147) | - | - | High
13 | [37.120.141.190](https://vuldb.com/?ip.37.120.141.190) | - | - | High
14 | [37.139.129.243](https://vuldb.com/?ip.37.139.129.243) | - | - | High
15 | [42.157.128.69](https://vuldb.com/?ip.42.157.128.69) | - | - | High
16 | [43.248.98.121](https://vuldb.com/?ip.43.248.98.121) | - | - | High
17 | [43.248.129.34](https://vuldb.com/?ip.43.248.129.34) | - | - | High
18 | [43.248.129.49](https://vuldb.com/?ip.43.248.129.49) | - | - | High
19 | [43.248.130.253](https://vuldb.com/?ip.43.248.130.253) | - | - | High
20 | [43.249.193.230](https://vuldb.com/?ip.43.249.193.230) | - | - | High
21 | ... | ... | ... | ...

There are 81 more IOC items available. Please use our online service to access the data.

## TTP - Tactics, Techniques, Procedures

_Tactics, techniques, and procedures_ (TTP) summarize the suspected MITRE ATT&CK techniques used by _N-W0rm_. This data is unique as it uses our predictive model for actor profiling.

ID | Technique | Weakness | Description | Confidence
-- | --------- | -------- | ----------- | ----------
1 | T1006 | CWE-21, CWE-22, CWE-23, CWE-24, CWE-36, CWE-425 | Path Traversal | High
2 | T1055 | CWE-74 | Improper Neutralization of Data within XPath Expressions | High
3 | T1059 | CWE-88, CWE-94, CWE-1321 | Argument Injection | High
4 | T1059.007 | CWE-79, CWE-80 | Basic Cross Site Scripting | High
5 | T1068 | CWE-250, CWE-264, CWE-269, CWE-284 | Execution with Unnecessary Privileges | High
6 | ... | ... | ... | ...

There are 22 more TTP items available. Please use our online service to access the data.

## IOA - Indicator of Attack

These _indicators of attack_ (IOA) list the potential fragments used for technical activities like reconnaissance, exploitation, privilege escalation, and exfiltration by N-W0rm. This data is unique as it uses our predictive model for actor profiling.

ID | Type | Indicator | Confidence
-- | ---- | --------- | ----------
1 | File | `/#ProductSerie/view/` | High
2 | File | `/aboutus.php` | Medium
3 | File | `/action.php` | Medium
4 | File | `/Actions.php?a=login` | High
5 | File | `/add-notes.php` | High
6 | File | `/addCatController.php` | High
7 | File | `/addelidetails.php` | High
8 | File | `/add_achievement_details.php` | High
9 | File | `/add_classes.php` | High
10 | File | `/admin#themes` | High
11 | File | `/admin.php/addon/index` | High
12 | File | `/admin/` | Low
13 | File | `/admin/aboutus.php` | High
14 | File | `/admin/add_postlogin.php` | High
15 | File | `/admin/admin-profile.php` | High
16 | File | `/admin/admin-update-employee.php` | High
17 | File | `/admin/admin_action.php` | High
18 | File | `/admin/admin_index.php` | High
19 | File | `/admin/ajax.php?action=login` | High
20 | File | `/admin/ajax_products_list.php` | High
21 | File | `/admin/app/product.php` | High
22 | File | `/admin/app/profile_crud.php` | High
23 | File | `/admin/archives_add.php` | High
24 | File | `/admin/assets/plugins/DataTables/media/unit_testing/templates/dom_data_th.php` | High
25 | File | `/admin/assets/plugins/DataTables/media/unit_testing/templates/two_tables.php` | High
26 | File | `/admin/book_row.php` | High
27 | File | `/admin/bwdates-request-report-details.php` | High
28 | File | `/admin/categories/save` | High
29 | File | `/admin/cmsVote/save` | High
30 | File | `/admin/create_product.php` | High
31 | File | `/admin/edit-category.php` | High
32 | File | `/admin/edit_product.php` | High
33 | File | `/admin/edit_user.php` | High
34 | File | `/admin/index.php` | High
35 | File | `/admin/index.php?language=en&nv=upload` | High
36 | File | `/admin/login.php` | High
37 | File | `/admin/manage_theater.php` | High
38 | File | `/admin/plan/examExportPDF` | High
39 | File | `/admin/positions_row.php` | High
40 | File | `/admin/posts.php?source=add_post` | High
41 | File | `/admin/products/index.php?view=add` | High
42 | File | `/admin/readenq.php` | High
43 | File | `/Admin/registration.php` | High
44 | File | `/admin/search-vehicle.php` | High
45 | File | `/admin/sensitive_word/list` | High
46 | File | `/admin/sn_package/sn_https` | High
47 | File | `/admin/update-rooms.php` | High
48 | File | `/admin/update-users.php` | High
49 | File | `/admin/update_s8.php` | High
50 | File | `/admin/uploads/` | High
51 | File | `/admin/user-bookings.php` | High
52 | File | `/admin/user-search.php` | High
53 | File | `/admin/user/edit.do` | High
54 | File | `/admin/userlist.php` | High
55 | File | `/admin/userprofile.php` | High
56 | File | `/admin/view-appointment.php` | High
57 | File | `/admin/voters_row.php` | High
58 | File | `/ajax.php?action=save_payment` | High
59 | File | `/ajax.php?action=save_plan` | High
60 | File | `/alphaware/summary.php` | High
61 | File | `/api/` | Low
62 | File | `/api/client/editemedia.php` | High
63 | File | `/api/config/list` | High
64 | File | `/Api/FileUploadApi.ashx` | High
65 | File | `/api/v1/toolbox/device/update/swap` | High
66 | File | `/api/wechat/app_auth` | High
67 | File | `/app/ConfirmSmsCode` | High
68 | File | `/Applications/Steal/main.cpp` | High
69 | File | `/apps/system/router/upload.go` | High
70 | File | `/bank/statements.php` | High
71 | File | `/boafrm/formFilter` | High
72 | File | `/boafrm/formMapDelDevice` | High
73 | File | `/boafrm/formParentControl` | High
74 | File | `/boafrm/formPortFw` | High
75 | File | `/bookingconfirm.php` | High
76 | File | `/borrow.php` | Medium
77 | File | `/cart/index.php` | High
78 | File | `/cart_remove.php` | High
79 | File | `/cgi-bin/` | Medium
80 | File | `/cgi-bin/account_mgr.cgi?cmd=cgi_user_add` | High
81 | File | `/cgi-bin/cstecgi.cgi` | High
82 | File | `/cgi-bin/editBookmark` | High
83 | File | `/cgi-bin/hd_config.cgi` | High
84 | File | `/cgi-bin/nas_sharing.cgi` | High
85 | File | `/cgi-bin/sysconf.cgi` | High
86 | ... | ... | ...

There are 755 more IOA items available (file, library, argument, input value, pattern, network port). Please use our online service to access the data.

## References

The following list contains _external sources_ which discuss the actor and the associated activities:

* https://threatfox.abuse.ch
* https://urlhaus.abuse.ch/url/3602383/
* https://urlhaus.abuse.ch/url/3607222/
* https://urlhaus.abuse.ch/url/3607417/

## Literature

The following _articles_ explain our unique predictive cyber threat intelligence:

* [VulDB Cyber Threat Intelligence Documentation](https://vuldb.com/?kb.cti)
* [Cyber Threat Intelligence - Early Anticipation of Attacks](https://www.scip.ch/en/?labs.20201022)

## License

(c) [1997-2025](https://vuldb.com/?kb.changelog) by [vuldb.com](https://vuldb.com/?kb.about). All data on this page is shared under the license [CC BY-NC-SA 4.0](https://creativecommons.org/licenses/by-nc-sa/4.0/). Questions? Check the [FAQ](https://vuldb.com/?kb.faq), read the [documentation](https://vuldb.com/?kb) or [contact us](https://vuldb.com/?contact)!
