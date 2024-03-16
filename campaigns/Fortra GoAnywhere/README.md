# Fortra GoAnywhere - Cyber Threat Intelligence

These _indicators_ were reported, collected, and generated during the [VulDB CTI analysis](https://vuldb.com/?kb.cti) of the campaign known as _Fortra GoAnywhere_. The _activity monitoring_ correlates data from social media, forums, chat rooms, and darknet markets. It helps to determine associated actors, specific activities, expected intentions, emerging research, and ongoing attacks. Our unique _predictive model_ uses _big data_ to forecast activities and their characteristics.

_Live data_ and more _analysis capabilities_ are available at [https://vuldb.com/?actor](https://vuldb.com/?actor)

## Countries

These _countries_ are directly (e.g. origin of attacks) or indirectly (e.g. access by proxy) associated with Fortra GoAnywhere:

* [US](https://vuldb.com/?country.us)
* [RU](https://vuldb.com/?country.ru)
* [NL](https://vuldb.com/?country.nl)
* ...

There are 5 more country items available. Please use our online service to access the data.

## Actors

These _actors_ are associated with Fortra GoAnywhere or other actors linked to the campaign.

ID | Actor | Confidence
-- | ----- | ----------
1 | [Clop](https://vuldb.com/?actor.clop) | High

## IOC - Indicator of Compromise

These _indicators of compromise_ (IOC) indicate associated network resources which are known to be part of research and attack activities of Fortra GoAnywhere.

ID | IP address | Hostname | Actor | Confidence
-- | ---------- | -------- | ----- | ----------
1 | [3.101.53.11](https://vuldb.com/?ip.3.101.53.11) | ec2-3-101-53-11.us-west-1.compute.amazonaws.com | [Clop](https://vuldb.com/?actor.clop) | Medium
2 | [5.34.178.28](https://vuldb.com/?ip.5.34.178.28) | s41.friendhosting.net | [Clop](https://vuldb.com/?actor.clop) | High
3 | [5.34.178.30](https://vuldb.com/?ip.5.34.178.30) | dedic-hghdgsjhdgjhgdj67tyu687uy-1209043.hosted-by-itldc.com | [Clop](https://vuldb.com/?actor.clop) | High
4 | [5.34.178.31](https://vuldb.com/?ip.5.34.178.31) | free.ds | [Clop](https://vuldb.com/?actor.clop) | High
5 | [5.34.180.48](https://vuldb.com/?ip.5.34.180.48) | mail.tube-plant.com | [Clop](https://vuldb.com/?actor.clop) | High
6 | [15.235.13.184](https://vuldb.com/?ip.15.235.13.184) | gollum.utwb.net | [Clop](https://vuldb.com/?actor.clop) | High
7 | [15.235.83.73](https://vuldb.com/?ip.15.235.83.73) | web0.meritusedu.ca | [Clop](https://vuldb.com/?actor.clop) | High
8 | [20.47.120.195](https://vuldb.com/?ip.20.47.120.195) | - | [Clop](https://vuldb.com/?actor.clop) | High
9 | [24.3.132.168](https://vuldb.com/?ip.24.3.132.168) | c-24-3-132-168.hsd1.pa.comcast.net | [Clop](https://vuldb.com/?actor.clop) | High
10 | ... | ... | ... | ...

There are 34 more IOC items available. Please use our online service to access the data.

## TTP - Tactics, Techniques, Procedures

_Tactics, techniques, and procedures_ (TTP) summarize the suspected MITRE ATT&CK techniques used within Fortra GoAnywhere. This data is unique as it uses our predictive model for actor profiling.

ID | Technique | Weakness | Description | Confidence
-- | --------- | -------- | ----------- | ----------
1 | T1006 | CWE-22, CWE-23, CWE-24, CWE-36, CWE-425 | Path Traversal | High
2 | T1040 | CWE-319 | Authentication Bypass by Capture-replay | High
3 | T1055 | CWE-74 | Injection | High
4 | T1059 | CWE-94, CWE-1321 | Argument Injection | High
5 | T1059.007 | CWE-79, CWE-80 | Cross Site Scripting | High
6 | ... | ... | ... | ...

There are 18 more TTP items available. Please use our online service to access the data.

## IOA - Indicator of Attack

These _indicators of attack_ (IOA) list the potential fragments used for technical activities like reconnaissance, exploitation, privilege escalation, and exfiltration during Fortra GoAnywhere. This data is unique as it uses our predictive model for actor profiling.

ID | Type | Indicator | Confidence
-- | ---- | --------- | ----------
1 | File | `/?p=products` | Medium
2 | File | `/academy/tutor/filter` | High
3 | File | `/Account/login.php` | High
4 | File | `/accounts_con/register_account` | High
5 | File | `/addbill.php` | Medium
6 | File | `/add_classes.php` | High
7 | File | `/admin` | Low
8 | File | `/admin.php?p=/Area/index#tab=t2` | High
9 | File | `/admin/` | Low
10 | File | `/admin/?page=bike` | High
11 | File | `/admin/action/delete-vaccine.php` | High
12 | File | `/admin/action/edit_chicken.php` | High
13 | File | `/admin/admin_content_tag.php?action=save_content` | High
14 | File | `/admin/admin_user.php` | High
15 | File | `/admin/book_add.php` | High
16 | File | `/admin/borrow_add.php` | High
17 | File | `/admin/bwdates-report-details.php` | High
18 | File | `/admin/category_row.php` | High
19 | File | `/admin/clientview.php` | High
20 | File | `/admin/courses/manage_course.php` | High
21 | File | `/admin/courses/view_course.php` | High
22 | File | `/admin/edit-accepted-appointment.php` | High
23 | File | `/admin/edit_categories.php` | High
24 | File | `/admin/edit_supplier.php` | High
25 | File | `/admin/ind_backstage.php` | High
26 | File | `/admin/inquiries/view_inquiry.php` | High
27 | File | `/admin/leancloud.php` | High
28 | File | `/admin/list_addr_fwresource_ip.php` | High
29 | File | `/admin/list_ipAddressPolicy.php` | High
30 | File | `/admin/list_onlineuser.php` | High
31 | File | `/admin/login.php` | High
32 | File | `/admin/options-theme.php` | High
33 | File | `/admin/order.php` | High
34 | File | `/admin/pages/edit_chicken.php` | High
35 | File | `/admin/pages/update_go.php` | High
36 | File | `/admin/regester.php` | High
37 | File | `/admin/request-received-bydonar.php` | High
38 | File | `/admin/return_add.php` | High
39 | File | `/admin/settings/` | High
40 | File | `/admin/singlelogin.php?submit=1` | High
41 | File | `/admin/students/update_status.php` | High
42 | File | `/admin/subject.php` | High
43 | File | `/admin/theme-edit.php` | High
44 | File | `/admin/upload/img` | High
45 | File | `/admin/uploads/` | High
46 | File | `/adminapi/system/file/openfile` | High
47 | File | `/administration/setting_security.php` | High
48 | File | `/admin_route/dec_service_credits.php` | High
49 | File | `/adplanet/PlanetCommentList` | High
50 | File | `/ajax-api.php` | High
51 | File | `/ample/app/action/edit_product.php` | High
52 | File | `/ample/app/ajax/member_data.php` | High
53 | File | `/api/controllers/admin/app/AppController.php` | High
54 | File | `/api/controllers/merchant/app/ComboController.php` | High
55 | File | `/api/controllers/merchant/design/MaterialController.php` | High
56 | File | `/api/es/admin/v3/security/user/1` | High
57 | File | `/api/log/killJob` | High
58 | File | `/api/sys/login` | High
59 | File | `/app/ajax/search_sales_report.php` | High
60 | File | `/app/Http/Controllers/ImageController.php` | High
61 | File | `/application/index/controller/Datament.php` | High
62 | File | `/application/index/controller/File.php` | High
63 | File | `/application/index/controller/Icon.php` | High
64 | File | `/application/index/controller/Screen.php` | High
65 | File | `/application/index/controller/Unity.php` | High
66 | File | `/application/pay/controller/Api.php` | High
67 | File | `/application/plugins/controller/Upload.php` | High
68 | File | `/application/websocket/controller/Setting.php` | High
69 | File | `/apply/index.php` | High
70 | File | `/apps/login_auth.php` | High
71 | File | `/apps/reg_go.php` | High
72 | File | `/att_add.php` | Medium
73 | File | `/auth/auth.php?user=1` | High
74 | File | `/b2b-supermarket/catalog/all-products` | High
75 | File | `/b2b-supermarket/shopping-cart` | High
76 | File | `/boaform/device_reset.cgi` | High
77 | File | `/boaform/wlan_basic_set.cgi` | High
78 | File | `/cancel.php` | Medium
79 | File | `/catalog/compare` | High
80 | File | `/cgi-bin/` | Medium
81 | File | `/cgi-bin/cstecgi.cgi` | High
82 | File | `/cgi-bin/cstecgi.cgi?action=login` | High
83 | File | `/cgi-bin/koha/catalogue/search.pl` | High
84 | ... | ... | ...

There are 736 more IOA items available (file, library, argument, input value, pattern, network port). Please use our online service to access the data.

## References

The following list contains _external sources_ which discuss the campaign and the associated activities:

* https://www.cisa.gov/news-events/cybersecurity-advisories/aa23-158a

## Literature

The following _articles_ explain our unique predictive cyber threat intelligence:

* [VulDB Cyber Threat Intelligence Documentation](https://vuldb.com/?kb.cti)
* [Cyber Threat Intelligence - Early Anticipation of Attacks](https://www.scip.ch/en/?labs.20201022)

## License

(c) [1997-2024](https://vuldb.com/?kb.changelog) by [vuldb.com](https://vuldb.com/?kb.about). All data on this page is shared under the license [CC BY-NC-SA 4.0](https://creativecommons.org/licenses/by-nc-sa/4.0/). Questions? Check the [FAQ](https://vuldb.com/?kb.faq), read the [documentation](https://vuldb.com/?kb) or [contact us](https://vuldb.com/?contact)!
