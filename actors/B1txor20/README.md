# B1txor20 - Cyber Threat Intelligence

These _indicators_ were reported, collected, and generated during the [VulDB CTI analysis](https://vuldb.com/?kb.cti) of the actor known as [B1txor20](https://vuldb.com/?actor.b1txor20). The _activity monitoring_ correlates data from social media, forums, chat rooms, and darknet markets. It helps to determine associated actors, specific activities, expected intentions, emerging research, and ongoing attacks. Our unique _predictive model_ uses _big data_ to forecast activities and their characteristics.

_Live data_ and more _analysis capabilities_ are available at [https://vuldb.com/?actor.b1txor20](https://vuldb.com/?actor.b1txor20)

## Countries

These _countries_ are directly (e.g. origin of attacks) or indirectly (e.g. access by proxy) associated with B1txor20:

* [CN](https://vuldb.com/?country.cn)
* [US](https://vuldb.com/?country.us)
* [LU](https://vuldb.com/?country.lu)
* ...

There are 9 more country items available. Please use our online service to access the data.

## IOC - Indicator of Compromise

These _indicators of compromise_ (IOC) indicate associated network resources which are known to be part of research and attack activities of B1txor20.

ID | IP address | Hostname | Campaign | Confidence
-- | ---------- | -------- | -------- | ----------
1 | [5.2.69.50](https://vuldb.com/?ip.5.2.69.50) | - | - | High
2 | [23.129.64.216](https://vuldb.com/?ip.23.129.64.216) | - | - | High
3 | [23.154.177.4](https://vuldb.com/?ip.23.154.177.4) | - | - | High
4 | [45.13.104.179](https://vuldb.com/?ip.45.13.104.179) | nosoignons.cust.milkywan.net | - | High
5 | [45.61.185.90](https://vuldb.com/?ip.45.61.185.90) | MiamiTor4.us | - | High
6 | [45.154.255.147](https://vuldb.com/?ip.45.154.255.147) | cust-147.keff.org | - | High
7 | [46.166.139.111](https://vuldb.com/?ip.46.166.139.111) | - | - | High
8 | [51.15.43.205](https://vuldb.com/?ip.51.15.43.205) | 205-43-15-51.instances.scw.cloud | - | High
9 | [62.102.148.68](https://vuldb.com/?ip.62.102.148.68) | - | - | High
10 | [62.102.148.69](https://vuldb.com/?ip.62.102.148.69) | - | - | High
11 | ... | ... | ... | ...

There are 40 more IOC items available. Please use our online service to access the data.

## TTP - Tactics, Techniques, Procedures

_Tactics, techniques, and procedures_ (TTP) summarize the suspected MITRE ATT&CK techniques used by _B1txor20_. This data is unique as it uses our predictive model for actor profiling.

ID | Technique | Weakness | Description | Confidence
-- | --------- | -------- | ----------- | ----------
1 | T1006 | CWE-21, CWE-22, CWE-23, CWE-24, CWE-36 | Path Traversal | High
2 | T1040 | CWE-319 | Authentication Bypass by Capture-replay | High
3 | T1055 | CWE-74, CWE-643 | Improper Neutralization of Data within XPath Expressions | High
4 | T1059 | CWE-94 | Argument Injection | High
5 | T1059.007 | CWE-79, CWE-80 | Cross Site Scripting | High
6 | ... | ... | ... | ...

There are 22 more TTP items available. Please use our online service to access the data.

## IOA - Indicator of Attack

These _indicators of attack_ (IOA) list the potential fragments used for technical activities like reconnaissance, exploitation, privilege escalation, and exfiltration by B1txor20. This data is unique as it uses our predictive model for actor profiling.

ID | Type | Indicator | Confidence
-- | ---- | --------- | ----------
1 | File | `/Account/login.php` | High
2 | File | `/add_members.php` | High
3 | File | `/admin-manage-user.php` | High
4 | File | `/admin/` | Low
5 | File | `/admin/admin-profile.php` | High
6 | File | `/admin/app/product.php` | High
7 | File | `/admin/app/profile_crud.php` | High
8 | File | `/admin/app/service_crud.php` | High
9 | File | `/admin/applicants/controller.php` | High
10 | File | `/admin/applicants/index.php` | High
11 | File | `/admin/bookdate.php` | High
12 | File | `/admin/booking-bwdates-reports-details.php` | High
13 | File | `/admin/booktime.php` | High
14 | File | `/admin/category/controller.php` | High
15 | File | `/admin/company/controller.php` | High
16 | File | `/admin/company/index.php` | High
17 | File | `/admin/div_data/delete?divId=9` | High
18 | File | `/admin/edit-admin.php` | High
19 | File | `/admin/edit_supplier.php` | High
20 | File | `/admin/employee/controller.php` | High
21 | File | `/admin/employee/index.php` | High
22 | File | `/admin/list_resource_icon.php?action=delete` | High
23 | File | `/admin/login.php` | High
24 | File | `/admin/maintenance/manage_category.php` | High
25 | File | `/admin/menu/toEdit` | High
26 | File | `/admin/operations/expense_category.php` | High
27 | File | `/admin/orders/view_order.php` | High
28 | File | `/admin/product/manage_product.php` | High
29 | File | `/admin/rooms.php` | High
30 | File | `/admin/search.php` | High
31 | File | `/admin/update-rooms.php` | High
32 | File | `/admin/update-users.php` | High
33 | File | `/admin/user-search.php` | High
34 | File | `/admin/user/controller.php` | High
35 | File | `/admin/users.php` | High
36 | File | `/adminapi/system/crud` | High
37 | File | `/adminapi/system/file/openfile` | High
38 | File | `/adminpanel/admin/facebox_modal/updateExaminee.php` | High
39 | File | `/adminpanel/admin/query/deleteExamExe.php` | High
40 | File | `/adminpanel/admin/query/loginExe.php` | High
41 | File | `/api/client/editemedia.php` | High
42 | File | `/api/controllers/admin/app/AppController.php` | High
43 | File | `/api/v1` | Low
44 | File | `/api/v1/policies/validation/condition/` | High
45 | File | `/api/v1/toolbox/device/update/swap` | High
46 | File | `/api/v1/vdeskintegration/todo/createorupdate` | High
47 | File | `/app/controller/Setup.php` | High
48 | File | `/app/middleware/TokenVerify.php` | High
49 | File | `/apps/system/api/user.go` | High
50 | File | `/apps/system/router/upload.go` | High
51 | File | `/apps/system/services/role_menu.go` | High
52 | File | `/att_add.php` | Medium
53 | File | `/billing/bill/edit/` | High
54 | File | `/bishe/register` | High
55 | File | `/bsenordering/index.php` | High
56 | File | `/cancel.php` | Medium
57 | File | `/cgi-bin/cstecgi.cgi` | High
58 | File | `/change-password.php` | High
59 | File | `/Cinema-Reservation/booking.php` | High
60 | ... | ... | ...

There are 527 more IOA items available (file, library, argument, input value, pattern, network port). Please use our online service to access the data.

## References

The following list contains _external sources_ which discuss the actor and the associated activities:

* https://blog.netlab.360.com/b1txor20-use-of-dns-tunneling_cn/

## Literature

The following _articles_ explain our unique predictive cyber threat intelligence:

* [VulDB Cyber Threat Intelligence Documentation](https://vuldb.com/?kb.cti)
* [Cyber Threat Intelligence - Early Anticipation of Attacks](https://www.scip.ch/en/?labs.20201022)

## License

(c) [1997-2024](https://vuldb.com/?kb.changelog) by [vuldb.com](https://vuldb.com/?kb.about). All data on this page is shared under the license [CC BY-NC-SA 4.0](https://creativecommons.org/licenses/by-nc-sa/4.0/). Questions? Check the [FAQ](https://vuldb.com/?kb.faq), read the [documentation](https://vuldb.com/?kb) or [contact us](https://vuldb.com/?contact)!
