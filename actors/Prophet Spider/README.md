# Prophet Spider - Cyber Threat Intelligence

These _indicators_ were reported, collected, and generated during the [VulDB CTI analysis](https://vuldb.com/?kb.cti) of the actor known as [Prophet Spider](https://vuldb.com/?actor.prophet_spider). The _activity monitoring_ correlates data from social media, forums, chat rooms, and darknet markets. It helps to determine associated actors, specific activities, expected intentions, emerging research, and ongoing attacks. Our unique _predictive model_ uses _big data_ to forecast activities and their characteristics.

_Live data_ and more _analysis capabilities_ are available at [https://vuldb.com/?actor.prophet_spider](https://vuldb.com/?actor.prophet_spider)

## Campaigns

The following _campaigns_ are known and can be associated with Prophet Spider:

* Log4Shell

## Countries

These _countries_ are directly (e.g. origin of attacks) or indirectly (e.g. access by proxy) associated with Prophet Spider:

* [US](https://vuldb.com/?country.us)
* [SC](https://vuldb.com/?country.sc)
* [RU](https://vuldb.com/?country.ru)
* ...

There are 2 more country items available. Please use our online service to access the data.

## IOC - Indicator of Compromise

These _indicators of compromise_ (IOC) indicate associated network resources which are known to be part of research and attack activities of Prophet Spider.

ID | IP address | Hostname | Campaign | Confidence
-- | ---------- | -------- | -------- | ----------
1 | [5.157.38.50](https://vuldb.com/?ip.5.157.38.50) | - | Log4Shell | High
2 | [23.129.64.218](https://vuldb.com/?ip.23.129.64.218) | - | Log4Shell | High
3 | [23.236.146.162](https://vuldb.com/?ip.23.236.146.162) | - | Log4Shell | High
4 | [45.61.146.242](https://vuldb.com/?ip.45.61.146.242) | - | Log4Shell | High
5 | [45.146.165.168](https://vuldb.com/?ip.45.146.165.168) | - | Log4Shell | High
6 | [45.154.255.147](https://vuldb.com/?ip.45.154.255.147) | cust-147.keff.org | Log4Shell | High
7 | [51.79.175.139](https://vuldb.com/?ip.51.79.175.139) | vps-dc8b0481.vps.ovh.ca | Log4Shell | High
8 | [51.222.121.180](https://vuldb.com/?ip.51.222.121.180) | ip180.ip-51-222-121.net | Log4Shell | High
9 | [62.102.148.68](https://vuldb.com/?ip.62.102.148.68) | - | Log4Shell | High
10 | ... | ... | ... | ...

There are 35 more IOC items available. Please use our online service to access the data.

## TTP - Tactics, Techniques, Procedures

_Tactics, techniques, and procedures_ (TTP) summarize the suspected MITRE ATT&CK techniques used by _Prophet Spider_. This data is unique as it uses our predictive model for actor profiling.

ID | Technique | Weakness | Description | Confidence
-- | --------- | -------- | ----------- | ----------
1 | T1006 | CWE-21, CWE-22, CWE-40 | Pathname Traversal | High
2 | T1040 | CWE-319 | Authentication Bypass by Capture-replay | High
3 | T1055 | CWE-74 | Injection | High
4 | T1059 | CWE-88, CWE-94 | Cross Site Scripting | High
5 | T1059.007 | CWE-79, CWE-80, CWE-85 | Cross Site Scripting | High
6 | ... | ... | ... | ...

There are 22 more TTP items available. Please use our online service to access the data.

## IOA - Indicator of Attack

These _indicators of attack_ (IOA) list the potential fragments used for technical activities like reconnaissance, exploitation, privilege escalation, and exfiltration by Prophet Spider. This data is unique as it uses our predictive model for actor profiling.

ID | Type | Indicator | Confidence
-- | ---- | --------- | ----------
1 | File | `/admin.php/Admin/adminadd.html` | High
2 | File | `/Admin/add-student.php` | High
3 | File | `/Admin/createClass.php` | High
4 | File | `/Admin/dashboard.php` | High
5 | File | `/admin/edit_members.php` | High
6 | File | `/admin/pages/sections_save.php` | High
7 | File | `/admin/problem_judge.php` | High
8 | File | `/admin/transactions/update_status.php` | High
9 | File | `/admin/users/index.php` | High
10 | File | `/apiv1/` | Low
11 | File | `/asms/admin/products/manage_product.php` | High
12 | File | `/asms/products/view_product.php` | High
13 | File | `/avms/index.php` | High
14 | File | `/bsms_ci/index.php` | High
15 | File | `/bsms_ci/index.php/user/edit_user/` | High
16 | File | `/calendar/viewcalendar.php` | High
17 | File | `/clients/listclients.php` | High
18 | File | `/College/admin/teacher.php` | High
19 | File | `/dashboard/add-service.php` | High
20 | File | `/device/` | Medium
21 | File | `/event/admin/?page=user/list` | High
22 | File | `/forums/editforum.php` | High
23 | File | `/garage/php_action/createBrand.php` | High
24 | File | `/general/search.php?searchtype=simple` | High
25 | File | `/goform/AddSysLogRule` | High
26 | File | `/goform/setDiagnoseInfo` | High
27 | File | `/goform/SetIpMacBind` | High
28 | File | `/goform/setSnmpInfo` | High
29 | File | `/goform/setUplinkInfo` | High
30 | File | `/hrm/controller/employee.php` | High
31 | File | `/hrm/employeeadd.php` | High
32 | File | `/hrm/employeeview.php` | High
33 | File | `/ims/login.php` | High
34 | File | `/index.php/admins/Fields/get_fields.html` | High
35 | File | `/index.php?module=configuration/application` | High
36 | File | `/index.php?module=entities/fields&entities_id=24` | High
37 | File | `/index.php?module=entities/forms&entities_id=24` | High
38 | File | `/index.php?module=entities/listing_types&entities_id=24` | High
39 | ... | ... | ...

There are 334 more IOA items available (file, library, argument, input value, pattern, network port). Please use our online service to access the data.

## References

The following list contains _external sources_ which discuss the actor and the associated activities:

* https://blogs.blackberry.com/en/2022/01/log4u-shell4me

## Literature

The following _articles_ explain our unique predictive cyber threat intelligence:

* [VulDB Cyber Threat Intelligence Documentation](https://vuldb.com/?kb.cti)
* [Cyber Threat Intelligence - Early Anticipation of Attacks](https://www.scip.ch/en/?labs.20201022)

## License

(c) [1997-2022](https://vuldb.com/?kb.changelog) by [vuldb.com](https://vuldb.com/?kb.about). All data on this page is shared under the license [CC BY-NC-SA 4.0](https://creativecommons.org/licenses/by-nc-sa/4.0/). Questions? Check the [FAQ](https://vuldb.com/?kb.faq), read the [documentation](https://vuldb.com/?kb) or [contact us](https://vuldb.com/?contact)!
