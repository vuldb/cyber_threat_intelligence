# hailBot - Cyber Threat Intelligence

These _indicators_ were reported, collected, and generated during the [VulDB CTI analysis](https://vuldb.com/?kb.cti) of the actor known as [hailBot](https://vuldb.com/?actor.hailbot). The _activity monitoring_ correlates data from social media, forums, chat rooms, and darknet markets. It helps to determine associated actors, specific activities, expected intentions, emerging research, and ongoing attacks. Our unique _predictive model_ uses _big data_ to forecast activities and their characteristics.

_Live data_ and more _analysis capabilities_ are available at [https://vuldb.com/?actor.hailbot](https://vuldb.com/?actor.hailbot)

## Countries

These _countries_ are directly (e.g. origin of attacks) or indirectly (e.g. access by proxy) associated with hailBot:

* [GB](https://vuldb.com/?country.gb)

## IOC - Indicator of Compromise

These _indicators of compromise_ (IOC) indicate associated network resources which are known to be part of research and attack activities of hailBot.

ID | IP address | Hostname | Campaign | Confidence
-- | ---------- | -------- | -------- | ----------
1 | [5.181.80.70](https://vuldb.com/?ip.5.181.80.70) | ip-80-70-bullethost.net | - | High
2 | [5.181.80.71](https://vuldb.com/?ip.5.181.80.71) | - | - | High
3 | [5.181.80.115](https://vuldb.com/?ip.5.181.80.115) | unweighted.bhajiwalababu.com | - | High
4 | ... | ... | ... | ...

There are 8 more IOC items available. Please use our online service to access the data.

## TTP - Tactics, Techniques, Procedures

_Tactics, techniques, and procedures_ (TTP) summarize the suspected MITRE ATT&CK techniques used by _hailBot_. This data is unique as it uses our predictive model for actor profiling.

ID | Technique | Weakness | Description | Confidence
-- | --------- | -------- | ----------- | ----------
1 | T1006 | CWE-22, CWE-24, CWE-36, CWE-425 | Path Traversal | High
2 | T1040 | CWE-319 | Authentication Bypass by Capture-replay | High
3 | T1055 | CWE-74 | Improper Neutralization of Data within XPath Expressions | High
4 | T1059 | CWE-94, CWE-1321 | Argument Injection | High
5 | ... | ... | ... | ...

There are 15 more TTP items available. Please use our online service to access the data.

## IOA - Indicator of Attack

These _indicators of attack_ (IOA) list the potential fragments used for technical activities like reconnaissance, exploitation, privilege escalation, and exfiltration by hailBot. This data is unique as it uses our predictive model for actor profiling.

ID | Type | Indicator | Confidence
-- | ---- | --------- | ----------
1 | File | `/?r=email/api/mark&op=delFromSend` | High
2 | File | `/admin.php/update/getFile.html` | High
3 | File | `/admin/?page=maintenance/brand` | High
4 | File | `/admin/?page=reminders/view_reminder` | High
5 | File | `/admin/add-category.php` | High
6 | File | `/admin/admin_content_tag.php?action=save_content` | High
7 | File | `/admin/ajax.php` | High
8 | File | `/admin/article/article-add.php` | High
9 | File | `/admin/assign/assign.php` | High
10 | File | `/admin/bookings/view_booking.php` | High
11 | File | `/admin/casedetails.php` | High
12 | File | `/admin/categories/manage_category.php` | High
13 | File | `/admin/conferences/get-all-status/` | High
14 | File | `/admin/conferences/list/` | High
15 | File | `/admin/config_save.php` | High
16 | File | `/Admin/createClass.php` | High
17 | File | `/admin/deduction_row.php` | High
18 | File | `/admin/del_service.php` | High
19 | File | `/admin/departments/manage_department.php` | High
20 | File | `/admin/edit-services.php` | High
21 | File | `/admin/edit.php` | High
22 | File | `/admin/edit_category.php` | High
23 | File | `/admin/edit_subject.php` | High
24 | File | `/admin/forgot-password.php` | High
25 | File | `/admin/list_addr_fwresource_ip.php` | High
26 | File | `/admin/list_onlineuser.php` | High
27 | File | `/admin/login.php` | High
28 | File | `/admin/maintenance/brand.php` | High
29 | File | `/admin/manage-users.php` | High
30 | File | `/admin/modal_add_product.php` | High
31 | File | `/admin/new-content` | High
32 | File | `/admin/payment.php` | High
33 | File | `/admin/positions_delete.php` | High
34 | File | `/admin/products/view_product.php` | High
35 | File | `/admin/reminders/manage_reminder.php` | High
36 | File | `/admin/report/index.php` | High
37 | File | `/admin/reports/index.php` | High
38 | File | `/admin/searchview.php` | High
39 | File | `/admin/services/view_service.php` | High
40 | File | `/admin/students/update_status.php` | High
41 | File | `/admin/subject.php` | High
42 | File | `/admin/suppliers/view_details.php` | High
43 | File | `/admin/transactions/track_shipment.php` | High
44 | File | `/admin/user/manage_user.php` | High
45 | File | `/admin_system/api.php` | High
46 | File | `/alphaware/summary.php` | High
47 | File | `/analysisProject/pagingQueryData` | High
48 | File | `/api/stl/actions/search` | High
49 | File | `/api/sys/set_passwd` | High
50 | File | `/api/v1/bait/set` | High
51 | File | `/api/wechat/app_auth` | High
52 | File | `/App_Resource/UEditor/server/upload.aspx` | High
53 | File | `/auth/auth.php?user=1` | High
54 | File | `/author_posts.php` | High
55 | File | `/blog` | Low
56 | File | `/book-services.php` | High
57 | File | `/browse` | Low
58 | File | `/bsms_ci/index.php` | High
59 | File | `/category.php` | High
60 | File | `/category/order/hits/copyright/46/finish/1/list/1` | High
61 | File | `/cgi-bin/jumpto.php?class=user&page=config_save&isphp=1` | High
62 | File | `/cgi-bin/nightled.cgi` | High
63 | File | `/cgi-bin/photocenter_mgr.cgi` | High
64 | File | `/classes/Master.php` | High
65 | File | `/classes/Master.php?f=delete_item` | High
66 | File | `/classes/master.php?f=delete_order` | High
67 | File | `/classes/Master.php?f=delete_service` | High
68 | File | `/classes/Master.php?f=save_inquiry` | High
69 | File | `/classes/Master.php?f=save_sub_category` | High
70 | File | `/classes/Users.php` | High
71 | File | `/cms/category/list` | High
72 | File | `/collection/all` | High
73 | File | `/config` | Low
74 | File | `/config-manager/save` | High
75 | File | `/config/myfield/test.php` | High
76 | File | `/contact.php` | Medium
77 | File | `/course/filterRecords/` | High
78 | File | `/cwms/classes/Master.php?f=save_contact` | High
79 | ... | ... | ...

There are 695 more IOA items available (file, library, argument, input value, pattern, network port). Please use our online service to access the data.

## References

The following list contains _external sources_ which discuss the actor and the associated activities:

* https://securityboulevard.com/2023/10/mirai-botnets-new-wave-hailbotkiraibot-catddos-and-their-fierce-onslaught/

## Literature

The following _articles_ explain our unique predictive cyber threat intelligence:

* [VulDB Cyber Threat Intelligence Documentation](https://vuldb.com/?kb.cti)
* [Cyber Threat Intelligence - Early Anticipation of Attacks](https://www.scip.ch/en/?labs.20201022)

## License

(c) [1997-2024](https://vuldb.com/?kb.changelog) by [vuldb.com](https://vuldb.com/?kb.about). All data on this page is shared under the license [CC BY-NC-SA 4.0](https://creativecommons.org/licenses/by-nc-sa/4.0/). Questions? Check the [FAQ](https://vuldb.com/?kb.faq), read the [documentation](https://vuldb.com/?kb) or [contact us](https://vuldb.com/?contact)!
