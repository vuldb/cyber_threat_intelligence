# JumpCloud - Cyber Threat Intelligence

These _indicators_ were reported, collected, and generated during the [VulDB CTI analysis](https://vuldb.com/?kb.cti) of the campaign known as _JumpCloud_. The _activity monitoring_ correlates data from social media, forums, chat rooms, and darknet markets. It helps to determine associated actors, specific activities, expected intentions, emerging research, and ongoing attacks. Our unique _predictive model_ uses _big data_ to forecast activities and their characteristics.

_Live data_ and more _analysis capabilities_ are available at [https://vuldb.com/?actor](https://vuldb.com/?actor)

## Countries

These _countries_ are directly (e.g. origin of attacks) or indirectly (e.g. access by proxy) associated with JumpCloud:

* [US](https://vuldb.com/?country.us)
* [RU](https://vuldb.com/?country.ru)
* [TR](https://vuldb.com/?country.tr)
* ...

There are 9 more country items available. Please use our online service to access the data.

## Actors

These _actors_ are associated with JumpCloud or other actors linked to the campaign.

ID | Actor | Confidence
-- | ----- | ----------
1 | [DPRK](https://vuldb.com/?actor.dprk) | High

## IOC - Indicator of Compromise

These _indicators of compromise_ (IOC) indicate associated network resources which are known to be part of research and attack activities of JumpCloud.

ID | IP address | Hostname | Actor | Confidence
-- | ---------- | -------- | ----- | ----------
1 | [23.29.115.171](https://vuldb.com/?ip.23.29.115.171) | 23-29-115-171.static.hvvc.us | [DPRK](https://vuldb.com/?actor.dprk) | High
2 | [23.95.182.5](https://vuldb.com/?ip.23.95.182.5) | 23-95-182-5-host.colocrossing.com | [DPRK](https://vuldb.com/?actor.dprk) | High
3 | [45.82.250.186](https://vuldb.com/?ip.45.82.250.186) | - | [DPRK](https://vuldb.com/?actor.dprk) | High
4 | [51.254.24.19](https://vuldb.com/?ip.51.254.24.19) | - | [DPRK](https://vuldb.com/?actor.dprk) | High
5 | ... | ... | ... | ...

There are 15 more IOC items available. Please use our online service to access the data.

## TTP - Tactics, Techniques, Procedures

_Tactics, techniques, and procedures_ (TTP) summarize the suspected MITRE ATT&CK techniques used within JumpCloud. This data is unique as it uses our predictive model for actor profiling.

ID | Technique | Weakness | Description | Confidence
-- | --------- | -------- | ----------- | ----------
1 | T1006 | CWE-21, CWE-22, CWE-24, CWE-28 | Pathname Traversal | High
2 | T1040 | CWE-294 | Authentication Bypass by Capture-replay | High
3 | T1055 | CWE-74 | Injection | High
4 | T1059 | CWE-88, CWE-94, CWE-1321 | Cross Site Scripting | High
5 | T1059.007 | CWE-79, CWE-80 | Cross Site Scripting | High
6 | ... | ... | ... | ...

There are 19 more TTP items available. Please use our online service to access the data.

## IOA - Indicator of Attack

These _indicators of attack_ (IOA) list the potential fragments used for technical activities like reconnaissance, exploitation, privilege escalation, and exfiltration during JumpCloud. This data is unique as it uses our predictive model for actor profiling.

ID | Type | Indicator | Confidence
-- | ---- | --------- | ----------
1 | File | `.github/workflows/comment.yml` | High
2 | File | `/?p=products` | Medium
3 | File | `/?r=email/api/mark&op=delFromSend` | High
4 | File | `/admin/?page=user` | High
5 | File | `/admin/addproduct.php` | High
6 | File | `/admin/ballot_down.php` | High
7 | File | `/admin/ballot_up.php` | High
8 | File | `/admin/bookings/manage_booking.php` | High
9 | File | `/admin/bookings/view_booking.php` | High
10 | File | `/admin/candidates_row.php` | High
11 | File | `/admin/casedetails.php` | High
12 | File | `/admin/config_save.php` | High
13 | File | `/admin/contacts/organizations/edit/2` | High
14 | File | `/admin/edit_product.php` | High
15 | File | `/admin/edit_subject.php` | High
16 | File | `/admin/fields/manage_field.php` | High
17 | File | `/admin/inquiries/view_inquiry.php` | High
18 | File | `/admin/inventory/manage_stock.php` | High
19 | File | `/admin/maintenance/brand.php` | High
20 | File | `/admin/manage_academic.php` | High
21 | File | `/admin/modal_add_product.php` | High
22 | File | `/admin/offenses/view_details.php` | High
23 | File | `/admin/orders/update_status.php` | High
24 | File | `/admin/positions_add.php` | High
25 | File | `/admin/positions_delete.php` | High
26 | File | `/admin/positions_row.php` | High
27 | File | `/admin/product/manage.php` | High
28 | File | `/admin/products/index.php` | High
29 | File | `/admin/reportupload.aspx` | High
30 | File | `/admin/sales/index.php` | High
31 | File | `/admin/save_teacher.php` | High
32 | File | `/admin/service.php` | High
33 | File | `/admin/services/view_service.php` | High
34 | File | `/admin/update_s6.php` | High
35 | File | `/admin/user/manage_user.php` | High
36 | File | `/admin/userprofile.php` | High
37 | File | `/admin/voters_row.php` | High
38 | File | `/api/baskets/{name}` | High
39 | File | `/apply.cgi` | Medium
40 | File | `/author/list?limit=10&offset=0&order=desc` | High
41 | File | `/booking/show_bookings/` | High
42 | File | `/cas/logout` | Medium
43 | File | `/category/list?limit=10&offset=0&order=desc` | High
44 | File | `/cgi-bin/adm.cgi` | High
45 | File | `/cgi-bin/jumpto.php?class=user&page=config_save&isphp=1` | High
46 | File | `/cgi-bin/wlogin.cgi` | High
47 | File | `/changeimage.php` | High
48 | File | `/classes/Master.php` | High
49 | File | `/classes/Master.php?f=delete_category` | High
50 | File | `/classes/Master.php?f=delete_img` | High
51 | File | `/classes/master.php?f=delete_order` | High
52 | File | `/classes/Master.php?f=delete_sub_category` | High
53 | File | `/classes/Master.php?f=save_brand` | High
54 | File | `/classes/Master.php?f=save_category` | High
55 | File | `/classes/Master.php?f=save_course` | High
56 | File | `/classes/Master.php?f=save_position` | High
57 | File | `/classes/Master.php?f=save_sub_category` | High
58 | File | `/classes/Master.php?f=update_order_status` | High
59 | File | `/classes/Users.phpp` | High
60 | File | `/cms/category/list` | High
61 | File | `/College/admin/teacher.php` | High
62 | File | `/contact/store` | High
63 | File | `/Controls/Generic/EBMK/Handlers/EStatements/DownloadEStatement.ashx` | High
64 | File | `/dcim/rack-roles/` | High
65 | File | `/dipam/athlete-profile.php` | High
66 | File | `/dipam/save-delegates.php` | High
67 | File | `/DocSystem/Repos/getReposAllUsers.do` | High
68 | File | `/ebics-server/ebics.aspx` | High
69 | File | `/ext/phar/phar_object.c` | High
70 | File | `/forum/away.php` | High
71 | File | `/goform/aspForm` | High
72 | File | `/group1/uploa` | High
73 | File | `/inc/topBarNav.php` | High
74 | File | `/index.php` | Medium
75 | File | `/index.php?app=main&func=passport&action=login` | High
76 | File | `/kelas/data` | Medium
77 | File | `/Moosikay/order.php` | High
78 | File | `/news/list?limit=10&offset=0&order=desc` | High
79 | ... | ... | ...

There are 692 more IOA items available (file, library, argument, input value, pattern, network port). Please use our online service to access the data.

## References

The following list contains _external sources_ which discuss the campaign and the associated activities:

* https://jumpcloud.com/support/july-2023-iocs

## Literature

The following _articles_ explain our unique predictive cyber threat intelligence:

* [VulDB Cyber Threat Intelligence Documentation](https://vuldb.com/?kb.cti)
* [Cyber Threat Intelligence - Early Anticipation of Attacks](https://www.scip.ch/en/?labs.20201022)

## License

(c) [1997-2023](https://vuldb.com/?kb.changelog) by [vuldb.com](https://vuldb.com/?kb.about). All data on this page is shared under the license [CC BY-NC-SA 4.0](https://creativecommons.org/licenses/by-nc-sa/4.0/). Questions? Check the [FAQ](https://vuldb.com/?kb.faq), read the [documentation](https://vuldb.com/?kb) or [contact us](https://vuldb.com/?contact)!
