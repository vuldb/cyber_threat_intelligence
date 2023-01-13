# Dealply - Cyber Threat Intelligence

These _indicators_ were reported, collected, and generated during the [VulDB CTI analysis](https://vuldb.com/?kb.cti) of the actor known as [Dealply](https://vuldb.com/?actor.dealply). The _activity monitoring_ correlates data from social media, forums, chat rooms, and darknet markets. It helps to determine associated actors, specific activities, expected intentions, emerging research, and ongoing attacks. Our unique _predictive model_ uses _big data_ to forecast activities and their characteristics.

_Live data_ and more _analysis capabilities_ are available at [https://vuldb.com/?actor.dealply](https://vuldb.com/?actor.dealply)

## Countries

These _countries_ are directly (e.g. origin of attacks) or indirectly (e.g. access by proxy) associated with Dealply:

* [IT](https://vuldb.com/?country.it)
* [US](https://vuldb.com/?country.us)
* [FR](https://vuldb.com/?country.fr)
* ...

There are 5 more country items available. Please use our online service to access the data.

## IOC - Indicator of Compromise

These _indicators of compromise_ (IOC) indicate associated network resources which are known to be part of research and attack activities of Dealply.

ID | IP address | Hostname | Campaign | Confidence
-- | ---------- | -------- | -------- | ----------
1 | [5.9.9.18](https://vuldb.com/?ip.5.9.9.18) | static.18.9.9.5.clients.your-server.de | - | High
2 | [13.248.196.204](https://vuldb.com/?ip.13.248.196.204) | a64c2b794233c60a6.awsglobalaccelerator.com | - | High
3 | [23.0.52.194](https://vuldb.com/?ip.23.0.52.194) | a23-0-52-194.deploy.static.akamaitechnologies.com | - | High
4 | [23.3.126.219](https://vuldb.com/?ip.23.3.126.219) | a23-3-126-219.deploy.static.akamaitechnologies.com | - | High
5 | [23.54.219.51](https://vuldb.com/?ip.23.54.219.51) | a23-54-219-51.deploy.static.akamaitechnologies.com | - | High
6 | [23.221.50.122](https://vuldb.com/?ip.23.221.50.122) | a23-221-50-122.deploy.static.akamaitechnologies.com | - | High
7 | [34.231.131.84](https://vuldb.com/?ip.34.231.131.84) | ec2-34-231-131-84.compute-1.amazonaws.com | - | Medium
8 | ... | ... | ... | ...

There are 29 more IOC items available. Please use our online service to access the data.

## TTP - Tactics, Techniques, Procedures

_Tactics, techniques, and procedures_ (TTP) summarize the suspected MITRE ATT&CK techniques used by _Dealply_. This data is unique as it uses our predictive model for actor profiling.

ID | Technique | Weakness | Description | Confidence
-- | --------- | -------- | ----------- | ----------
1 | T1006 | CWE-21, CWE-22, CWE-35 | Pathname Traversal | High
2 | T1040 | CWE-294, CWE-319 | Authentication Bypass by Capture-replay | High
3 | T1055 | CWE-74 | Injection | High
4 | T1059 | CWE-88, CWE-94, CWE-1321 | Cross Site Scripting | High
5 | T1059.007 | CWE-79, CWE-80 | Cross Site Scripting | High
6 | ... | ... | ... | ...

There are 21 more TTP items available. Please use our online service to access the data.

## IOA - Indicator of Attack

These _indicators of attack_ (IOA) list the potential fragments used for technical activities like reconnaissance, exploitation, privilege escalation, and exfiltration by Dealply. This data is unique as it uses our predictive model for actor profiling.

ID | Type | Indicator | Confidence
-- | ---- | --------- | ----------
1 | File | `/acms/admin/?page=transactions/manage_transaction` | High
2 | File | `/acms/admin/cargo_types/manage_cargo_type.php` | High
3 | File | `/acms/admin/cargo_types/view_cargo_type.php` | High
4 | File | `/acms/classes/Master.php?f=delete_cargo` | High
5 | File | `/acms/classes/Master.php?f=delete_cargo_type` | High
6 | File | `/acms/classes/Master.php?f=delete_img` | High
7 | File | `/admin/?page=inmates/view_inmate` | High
8 | File | `/admin/?page=system_info` | High
9 | File | `/admin/?page=system_info/contact_info` | High
10 | File | `/admin/add_exercises.php` | High
11 | File | `/Admin/createClass.php` | High
12 | File | `/admin/edit.php` | High
13 | File | `/admin/lab.php` | High
14 | File | `/admin/new-content` | High
15 | File | `/apply.cgi` | Medium
16 | File | `/aqpg/users/login.php` | High
17 | File | `/back/index.php/user/User/?1` | High
18 | File | `/bcms/admin/?page=user/list` | High
19 | File | `/blog/comment` | High
20 | File | `/bsms_ci/index.php` | High
21 | File | `/bsms_ci/index.php/user/edit_user/` | High
22 | File | `/cgi-bin/login.cgi` | High
23 | File | `/ci_spms/admin/category` | High
24 | File | `/classes/Users.php?f=save` | High
25 | File | `/cms/admin/?page=invoice/manage_invoice` | High
26 | File | `/cms/admin/?page=invoice/view_invoice` | High
27 | File | `/cms/admin/?page=user/manage_user` | High
28 | File | `/cms/category/list` | High
29 | File | `/College_Management_System/admin/display-teacher.php` | High
30 | File | `/ctpms/admin/applications/update_status.php` | High
31 | File | `/ctpms/admin/individuals/update_status.php` | High
32 | File | `/ctpms/classes/Master.php?f=delete_application` | High
33 | File | `/ctpms/classes/Master.php?f=delete_img` | High
34 | File | `/cwms/admin/?page=articles/view_article/` | High
35 | File | `/cwms/classes/Master.php?f=save_contact` | High
36 | File | `/dashboard/add-blog.php` | High
37 | File | `/dashboard/add-portfolio.php` | High
38 | File | `/dashboard/settings` | High
39 | File | `/Default/Bd` | Medium
40 | File | `/event/admin/?page=user/list` | High
41 | File | `/face-recognition-php/facepay-master/camera.php` | High
42 | File | `/goform/SetSysTimeCfg` | High
43 | File | `/graphql` | Medium
44 | File | `/guestmanagement/front.php` | High
45 | File | `/horde/imp/search.php` | High
46 | File | `/hrm/controller/employee.php` | High
47 | File | `/hrm/employeeadd.php` | High
48 | File | `/hrm/employeeview.php` | High
49 | File | `/index.php` | Medium
50 | File | `/login.php` | Medium
51 | File | `/login/index.php` | High
52 | File | `/management/api/rcx_management/global_config_query` | High
53 | File | `/mims/app/addcustomerHandler.php` | High
54 | File | `/mims/login.php` | High
55 | File | `/mtms/admin/?page=user/manage_user` | High
56 | File | `/mygym/admin/index.php` | High
57 | ... | ... | ...

There are 497 more IOA items available (file, library, argument, input value, pattern, network port). Please use our online service to access the data.

## References

The following list contains _external sources_ which discuss the actor and the associated activities:

* https://blog.talosintelligence.com/2020/01/threat-roundup-0124-0131.html
* https://blog.talosintelligence.com/2020/05/threat-roundup-0522-0529.html
* https://blog.talosintelligence.com/2020/08/threat-roundup-0821-0827.html

## Literature

The following _articles_ explain our unique predictive cyber threat intelligence:

* [VulDB Cyber Threat Intelligence Documentation](https://vuldb.com/?kb.cti)
* [Cyber Threat Intelligence - Early Anticipation of Attacks](https://www.scip.ch/en/?labs.20201022)

## License

(c) [1997-2023](https://vuldb.com/?kb.changelog) by [vuldb.com](https://vuldb.com/?kb.about). All data on this page is shared under the license [CC BY-NC-SA 4.0](https://creativecommons.org/licenses/by-nc-sa/4.0/). Questions? Check the [FAQ](https://vuldb.com/?kb.faq), read the [documentation](https://vuldb.com/?kb) or [contact us](https://vuldb.com/?contact)!
