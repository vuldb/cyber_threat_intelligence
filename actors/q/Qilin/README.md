# Qilin - Cyber Threat Intelligence

These _indicators_ were reported, collected, and generated during the [VulDB CTI analysis](https://vuldb.com/?kb.cti) of the actor known as [Qilin](https://vuldb.com/?actor.qilin). The _activity monitoring_ correlates data from social media, forums, chat rooms, and darknet markets. It helps to determine associated actors, specific activities, expected intentions, emerging research, and ongoing attacks. Our unique _predictive model_ uses _big data_ to forecast activities and their characteristics.

_Live data_ and more _analysis capabilities_ are available at [https://vuldb.com/?actor.qilin](https://vuldb.com/?actor.qilin)

## Campaigns

The following _campaigns_ are known and can be associated with Qilin:

* CVE-2025-31324

## Countries

These _countries_ are directly (e.g. origin of attacks) or indirectly (e.g. access by proxy) associated with Qilin:

* [US](https://vuldb.com/?country.us)
* [CN](https://vuldb.com/?country.cn)
* [GB](https://vuldb.com/?country.gb)
* ...

There are 21 more country items available. Please use our online service to access the data.

## IOC - Indicator of Compromise

These _indicators of compromise_ (IOC) indicate associated network resources which are known to be part of research and attack activities of Qilin.

ID | IP address | Hostname | Campaign | Confidence
-- | ---------- | -------- | -------- | ----------
1 | [31.41.244.100](https://vuldb.com/?ip.31.41.244.100) | - | - | High
2 | [91.238.181.230](https://vuldb.com/?ip.91.238.181.230) | - | - | High
3 | [93.115.25.139](https://vuldb.com/?ip.93.115.25.139) | - | - | High
4 | ... | ... | ... | ...

There are 14 more IOC items available. Please use our online service to access the data.

## TTP - Tactics, Techniques, Procedures

_Tactics, techniques, and procedures_ (TTP) summarize the suspected MITRE ATT&CK techniques used by _Qilin_. This data is unique as it uses our predictive model for actor profiling.

ID | Technique | Weakness | Description | Confidence
-- | --------- | -------- | ----------- | ----------
1 | T1006 | CWE-21, CWE-22, CWE-23, CWE-27, CWE-28, CWE-425 | Path Traversal | High
2 | T1055 | CWE-74 | Improper Neutralization of Data within XPath Expressions | High
3 | T1059 | CWE-88, CWE-94 | Argument Injection | High
4 | T1059.007 | CWE-79, CWE-80 | Basic Cross Site Scripting | High
5 | T1068 | CWE-264, CWE-266, CWE-269, CWE-284 | Execution with Unnecessary Privileges | High
6 | ... | ... | ... | ...

There are 18 more TTP items available. Please use our online service to access the data.

## IOA - Indicator of Attack

These _indicators of attack_ (IOA) list the potential fragments used for technical activities like reconnaissance, exploitation, privilege escalation, and exfiltration by Qilin. This data is unique as it uses our predictive model for actor profiling.

ID | Type | Indicator | Confidence
-- | ---- | --------- | ----------
1 | File | `/abs.php` | Medium
2 | File | `/Account/login.php` | High
3 | File | `/action/docker/open_subshell` | High
4 | File | `/activation.php` | High
5 | File | `/ad-list` | Medium
6 | File | `/add-admin.php` | High
7 | File | `/add-table.php` | High
8 | File | `/admin#themes` | High
9 | File | `/admin/?page=categories/view_category` | High
10 | File | `/admin/add-doctor.php` | High
11 | File | `/admin/admin_login.php` | High
12 | File | `/admin/ajax.php?action=login` | High
13 | File | `/admin/bookList?page=1&limit=10` | High
14 | File | `/admin/case-type` | High
15 | File | `/admin/contact-us.php` | High
16 | File | `/Admin/createClass.php` | High
17 | File | `/admin/create_product.php` | High
18 | File | `/admin/div_data/data` | High
19 | File | `/admin/edit_manufacturer.php` | High
20 | File | `/admin/index.php` | High
21 | File | `/admin/ind_backstage.php` | High
22 | File | `/admin/login.php` | High
23 | File | `/admin/manage-services.php` | High
24 | File | `/admin/media_folders` | High
25 | File | `/admin/memberOnline_deal.php?mudi=del&dataType=&dataID=6` | High
26 | File | `/admin/menu.php` | High
27 | File | `/admin/problem_judge.php` | High
28 | File | `/admin/robot.php` | High
29 | File | `/admin/SysModule/upload/ajaxmodel/upload/uploadfilepath/sysmodule_1` | High
30 | File | `/admin/users.php` | High
31 | File | `/admin/user_update.php` | High
32 | File | `/ajax.php` | Medium
33 | File | `/ajax.php?action=delete_tenant` | High
34 | File | `/api/controllers/merchant/shop/PosterController.php` | High
35 | File | `/api/system/other` | High
36 | File | `/api/wizard/getBasicInfo` | High
37 | File | `/app/platform/controllers/ResetpwdController.php` | High
38 | File | `/AttendanceMonitoring/report/index.php` | High
39 | File | `/authMonitCallcenter` | High
40 | File | `/backend/admin/his_admin_add_lab_equipment.php` | High
41 | File | `/backend/admin/his_admin_register_patient.php` | High
42 | File | `/backend/register.php` | High
43 | File | `/bin/boa` | Medium
44 | File | `/blog/blog.php` | High
45 | File | `/bloodrequest.php` | High
46 | File | `/boafrm/formFilter` | High
47 | File | `/booklist.php` | High
48 | File | `/catalog/admin/categories.php?cPath=&action=new_product` | High
49 | File | `/cgi-bin/cstecgi.cgi` | High
50 | File | `/cgi-bin/hd_config.cgi` | High
51 | File | `/cgi-bin/photocenter_mgr.cgi` | High
52 | File | `/cgi-bin/wapopen` | High
53 | File | `/classes/Master.php` | High
54 | ... | ... | ...

There are 475 more IOA items available (file, library, argument, input value, pattern, network port). Please use our online service to access the data.

## References

The following list contains _external sources_ which discuss the actor and the associated activities:

* https://blog.bushidotoken.net/2024/06/tracking-adversaries-qilin-raas.html
* https://darktrace.com/blog/a-busy-agenda-darktraces-detection-of-qilin-ransomware-as-a-service-operator
* https://op-c.net/blog/sap-cve-2025-31324-qilin-breach/

## Literature

The following _articles_ explain our unique predictive cyber threat intelligence:

* [VulDB Cyber Threat Intelligence Documentation](https://vuldb.com/?kb.cti)
* [Cyber Threat Intelligence - Early Anticipation of Attacks](https://www.scip.ch/en/?labs.20201022)

## License

(c) [1997-2025](https://vuldb.com/?kb.changelog) by [vuldb.com](https://vuldb.com/?kb.about). All data on this page is shared under the license [CC BY-NC-SA 4.0](https://creativecommons.org/licenses/by-nc-sa/4.0/). Questions? Check the [FAQ](https://vuldb.com/?kb.faq), read the [documentation](https://vuldb.com/?kb) or [contact us](https://vuldb.com/?contact)!
