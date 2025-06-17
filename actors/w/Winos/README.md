# Winos - Cyber Threat Intelligence

These _indicators_ were reported, collected, and generated during the [VulDB CTI analysis](https://vuldb.com/?kb.cti) of the actor known as [Winos](https://vuldb.com/?actor.winos). The _activity monitoring_ correlates data from social media, forums, chat rooms, and darknet markets. It helps to determine associated actors, specific activities, expected intentions, emerging research, and ongoing attacks. Our unique _predictive model_ uses _big data_ to forecast activities and their characteristics.

_Live data_ and more _analysis capabilities_ are available at [https://vuldb.com/?actor.winos](https://vuldb.com/?actor.winos)

## Campaigns

The following _campaigns_ are known and can be associated with Winos:

* Catena

## Countries

These _countries_ are directly (e.g. origin of attacks) or indirectly (e.g. access by proxy) associated with Winos:

* [US](https://vuldb.com/?country.us)
* [CN](https://vuldb.com/?country.cn)
* [ES](https://vuldb.com/?country.es)
* ...

There are 20 more country items available. Please use our online service to access the data.

## IOC - Indicator of Compromise

These _indicators of compromise_ (IOC) indicate associated network resources which are known to be part of research and attack activities of Winos.

ID | IP address | Hostname | Campaign | Confidence
-- | ---------- | -------- | -------- | ----------
1 | [27.122.59.71](https://vuldb.com/?ip.27.122.59.71) | - | - | High
2 | [43.226.125.44](https://vuldb.com/?ip.43.226.125.44) | - | - | High
3 | [47.83.184.193](https://vuldb.com/?ip.47.83.184.193) | - | - | High
4 | [47.86.28.28](https://vuldb.com/?ip.47.86.28.28) | - | - | High
5 | ... | ... | ... | ...

There are 17 more IOC items available. Please use our online service to access the data.

## TTP - Tactics, Techniques, Procedures

_Tactics, techniques, and procedures_ (TTP) summarize the suspected MITRE ATT&CK techniques used by _Winos_. This data is unique as it uses our predictive model for actor profiling.

ID | Technique | Weakness | Description | Confidence
-- | --------- | -------- | ----------- | ----------
1 | T1006 | CWE-21, CWE-22, CWE-23, CWE-24 | Path Traversal | High
2 | T1040 | CWE-319 | Authentication Bypass by Capture-replay | High
3 | T1055 | CWE-74 | Improper Neutralization of Data within XPath Expressions | High
4 | T1059 | CWE-88, CWE-94, CWE-1321 | Argument Injection | High
5 | ... | ... | ... | ...

There are 17 more TTP items available. Please use our online service to access the data.

## IOA - Indicator of Attack

These _indicators of attack_ (IOA) list the potential fragments used for technical activities like reconnaissance, exploitation, privilege escalation, and exfiltration by Winos. This data is unique as it uses our predictive model for actor profiling.

ID | Type | Indicator | Confidence
-- | ---- | --------- | ----------
1 | File | `/add_deductions.php` | High
2 | File | `/adfs/ls` | Medium
3 | File | `/admin.php?p=/Area/index#tab=t2` | High
4 | File | `/admin/assets/plugins/DataTables/media/unit_testing/templates/empty_table.php` | High
5 | File | `/admin/bookList?page=1&limit=10` | High
6 | File | `/admin/bwdates-report-details.php` | High
7 | File | `/admin/chatroom.php` | High
8 | File | `/admin/cmsVote/save` | High
9 | File | `/admin/create_product.php` | High
10 | File | `/admin/edit-products.php` | High
11 | File | `/admin/enrollment-details.php` | High
12 | File | `/admin/getallarticleinfo` | High
13 | File | `/Admin/Http/Controllers/FileManagerController.php` | High
14 | File | `/admin/index.php` | High
15 | File | `/admin/login.php` | High
16 | File | `/admin/normal-search.php` | High
17 | File | `/admin/operations/expense_category.php` | High
18 | File | `/admin/orders/view_order.php` | High
19 | File | `/admin/print.php` | High
20 | File | `/admin/product/manage_product.php` | High
21 | File | `/admin/salary_slip.php` | High
22 | File | `/admin/template/update` | High
23 | File | `/admin/user-search.php` | High
24 | File | `/adminPage/main/upload` | High
25 | File | `/adminpanel/admin/query/addCourseExe.php` | High
26 | File | `/api/mjkj-chat/chat/ai/delete/chat` | High
27 | File | `/api/semantic/database/testConnect` | High
28 | File | `/api/swaggerui/static` | High
29 | File | `/api/sys/set_passwd` | High
30 | File | `/Api/TinyMce/UploadAjaxAPI.ashx` | High
31 | File | `/api/wizard/setsyncpppoecfg` | High
32 | File | `/app/controller/Api.php` | High
33 | File | `/auth.asp` | Medium
34 | File | `/auth/register` | High
35 | File | `/backend/admin/his_admin_add_lab_equipment.php` | High
36 | File | `/backend/admin/his_admin_add_vendor.php` | High
37 | File | `/backend/admin/his_admin_register_patient.php` | High
38 | File | `/boafrm/formFilter` | High
39 | File | `/catalog/compare` | High
40 | File | `/cgi-bin/cstecgi.cgi` | High
41 | File | `/cgi-bin/hd_config.cgi` | High
42 | File | `/cgi-bin/mainfunction.cgi` | High
43 | File | `/cgi-bin/mainfunction.cgi/apmcfgupload` | High
44 | File | `/change-password.php` | High
45 | File | `/classes/Master.php?f=save_course` | High
46 | File | `/classes/Master.php?f=save_position` | High
47 | File | `/config/config.properties` | High
48 | File | `/coreframe/app/guestbook/myissue.php` | High
49 | File | `/cupseasylive/locationcreate.php` | High
50 | ... | ... | ...

There are 434 more IOA items available (file, library, argument, input value, pattern, network port). Please use our online service to access the data.

## References

The following list contains _external sources_ which discuss the actor and the associated activities:

* https://github.com/rapid7/Rapid7-Labs/blob/main/IOCs/nsis-abuse-srdi-winos4/iocs.txt
* https://www.rapid7.com/blog/post/2025/05/22/nsis-abuse-and-srdi-shellcode-anatomy-of-the-winos-4-0-campaign/

## Literature

The following _articles_ explain our unique predictive cyber threat intelligence:

* [VulDB Cyber Threat Intelligence Documentation](https://vuldb.com/?kb.cti)
* [Cyber Threat Intelligence - Early Anticipation of Attacks](https://www.scip.ch/en/?labs.20201022)

## License

(c) [1997-2025](https://vuldb.com/?kb.changelog) by [vuldb.com](https://vuldb.com/?kb.about). All data on this page is shared under the license [CC BY-NC-SA 4.0](https://creativecommons.org/licenses/by-nc-sa/4.0/). Questions? Check the [FAQ](https://vuldb.com/?kb.faq), read the [documentation](https://vuldb.com/?kb) or [contact us](https://vuldb.com/?contact)!
