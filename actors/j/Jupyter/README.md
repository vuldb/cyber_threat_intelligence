# Jupyter - Cyber Threat Intelligence

These _indicators_ were reported, collected, and generated during the [VulDB CTI analysis](https://vuldb.com/?kb.cti) of the actor known as [Jupyter](https://vuldb.com/?actor.jupyter). The _activity monitoring_ correlates data from social media, forums, chat rooms, and darknet markets. It helps to determine associated actors, specific activities, expected intentions, emerging research, and ongoing attacks. Our unique _predictive model_ uses _big data_ to forecast activities and their characteristics.

_Live data_ and more _analysis capabilities_ are available at [https://vuldb.com/?actor.jupyter](https://vuldb.com/?actor.jupyter)

## Countries

These _countries_ are directly (e.g. origin of attacks) or indirectly (e.g. access by proxy) associated with Jupyter:

* [US](https://vuldb.com/?country.us)
* [GB](https://vuldb.com/?country.gb)
* [RU](https://vuldb.com/?country.ru)
* ...

There are 33 more country items available. Please use our online service to access the data.

## IOC - Indicator of Compromise

These _indicators of compromise_ (IOC) indicate associated network resources which are known to be part of research and attack activities of Jupyter.

ID | IP address | Hostname | Campaign | Confidence
-- | ---------- | -------- | -------- | ----------
1 | [5.254.118.226](https://vuldb.com/?ip.5.254.118.226) | - | - | High
2 | [23.29.115.175](https://vuldb.com/?ip.23.29.115.175) | 23-29-115-175.static.hvvc.us | - | High
3 | [37.120.237.251](https://vuldb.com/?ip.37.120.237.251) | - | - | High
4 | [37.120.247.199](https://vuldb.com/?ip.37.120.247.199) | - | - | High
5 | [37.221.113.115](https://vuldb.com/?ip.37.221.113.115) | - | - | High
6 | ... | ... | ... | ...

There are 19 more IOC items available. Please use our online service to access the data.

## TTP - Tactics, Techniques, Procedures

_Tactics, techniques, and procedures_ (TTP) summarize the suspected MITRE ATT&CK techniques used by _Jupyter_. This data is unique as it uses our predictive model for actor profiling.

ID | Technique | Weakness | Description | Confidence
-- | --------- | -------- | ----------- | ----------
1 | T1006 | CWE-22, CWE-24, CWE-36, CWE-37, CWE-425 | Path Traversal | High
2 | T1040 | CWE-319 | Authentication Bypass by Capture-replay | High
3 | T1055 | CWE-74 | Improper Neutralization of Data within XPath Expressions | High
4 | T1059 | CWE-88, CWE-94, CWE-1321 | Argument Injection | High
5 | T1059.007 | CWE-79, CWE-80 | Basic Cross Site Scripting | High
6 | ... | ... | ... | ...

There are 22 more TTP items available. Please use our online service to access the data.

## IOA - Indicator of Attack

These _indicators of attack_ (IOA) list the potential fragments used for technical activities like reconnaissance, exploitation, privilege escalation, and exfiltration by Jupyter. This data is unique as it uses our predictive model for actor profiling.

ID | Type | Indicator | Confidence
-- | ---- | --------- | ----------
1 | File | `/.env` | Low
2 | File | `/?ajax-request=jnews` | High
3 | File | `/?r=recruit/resume/edit&op=status` | High
4 | File | `/add-students.php` | High
5 | File | `/addstock.php` | High
6 | File | `/add_new_supplier.php` | High
7 | File | `/admin/?page=reports` | High
8 | File | `/admin/?page=system_info/contact_info` | High
9 | File | `/admin/?page=user/list` | High
10 | File | `/admin/?page=user/manage_user&id=3` | High
11 | File | `/admin/about-us.php` | High
12 | File | `/admin/action/new-father.php` | High
13 | File | `/admin/app/service_crud.php` | High
14 | File | `/admin/book-details.php` | High
15 | File | `/admin/create_product.php` | High
16 | File | `/admin/del_category.php` | High
17 | File | `/admin/del_service.php` | High
18 | File | `/admin/edit-accepted-appointment.php` | High
19 | File | `/admin/edit-admin.php` | High
20 | File | `/admin/edit-brand.php` | High
21 | File | `/admin/edit-services.php` | High
22 | File | `/admin/edit.php` | High
23 | File | `/admin/edit_category.php` | High
24 | File | `/admin/edit_subject.php` | High
25 | File | `/admin/forgot-password.php` | High
26 | File | `/admin/index.php` | High
27 | File | `/admin/list_crl_conf` | High
28 | File | `/Admin/login.php` | High
29 | File | `/admin/manage_user.php` | High
30 | File | `/admin/massage.php` | High
31 | File | `/admin/network/ajax_getChannelList` | High
32 | File | `/admin/pages/list` | High
33 | File | `/admin/password-recovery.php` | High
34 | File | `/admin/products/manage_product.php` | High
35 | File | `/admin/profile.php` | High
36 | File | `/admin/reg.php` | High
37 | File | `/admin/search-appointment.php` | High
38 | File | `/admin/search.php` | High
39 | File | `/admin/system.html` | High
40 | File | `/admin/sys_sql_query.php` | High
41 | File | `/admin/tag.php` | High
42 | File | `/animalsupdate.php` | High
43 | File | `/api/sys/ng-alain/getDictItemsByTable/` | High
44 | File | `/api/v4/teams//channels/deleted` | High
45 | File | `/api/wizard/networkSetup` | High
46 | File | `/app/admin/controller/api/Plugs.php` | High
47 | File | `/app/admin/controller/Upload.php` | High
48 | File | `/app/ajax/search_sales_report.php` | High
49 | File | `/app/controller/Setup.php` | High
50 | File | `/app/middleware/TokenVerify.php` | High
51 | File | `/appliance/users?action=edit` | High
52 | File | `/application/index/controller/Screen.php` | High
53 | File | `/application/websocket/controller/Setting.php` | High
54 | File | `/apply/index.php` | High
55 | File | `/b2b-supermarket/catalog/all-products` | High
56 | File | `/backend/admin/his_admin_register_patient.php` | High
57 | File | `/bin/boa` | Medium
58 | File | `/blog` | Low
59 | File | `/boafrm/formMapDelDevice` | High
60 | File | `/booking/show_bookings/` | High
61 | File | `/cgi-bin/cstecgi.cgi` | High
62 | File | `/cgi-bin/cstecgi.cgi?action=login` | High
63 | File | `/cgi-bin/myMusic.cgi` | High
64 | File | `/cgi-bin/nas_sharing.cgi` | High
65 | File | `/cgi-bin/photocenter_mgr.cgi` | High
66 | File | `/cgi-bin/system_mgr.cgi` | High
67 | File | `/classes/Master.php` | High
68 | File | `/classes/Master.php?f=save_medicine` | High
69 | File | `/classes/Users.php?f=save` | High
70 | File | `/collection/all` | High
71 | File | `/com/esafenet/servlet/ajax/MultiServerAjax.java` | High
72 | File | `/com/esafenet/servlet/ajax/NetSecPolicyAjax.java` | High
73 | File | `/com/esafenet/servlet/client/MailDecryptApplicationService.java` | High
74 | File | `/com/esafenet/servlet/policy/EncryptPolicyService.java` | High
75 | File | `/com/esafenet/servlet/policy/HookWhiteListService.java` | High
76 | File | `/course/modedit.php` | High
77 | ... | ... | ...

There are 673 more IOA items available (file, library, argument, input value, pattern, network port). Please use our online service to access the data.

## References

The following list contains _external sources_ which discuss the actor and the associated activities:

* https://blog.morphisec.com/new-jupyter-evasive-delivery-through-msi-installer
* https://blogs.blackberry.com/en/2022/01/threat-thursday-jupyter-infostealer-is-a-master-of-disguise
* https://community.blueliv.com/#!/s/62551fc782df417ed0330c79

## Literature

The following _articles_ explain our unique predictive cyber threat intelligence:

* [VulDB Cyber Threat Intelligence Documentation](https://vuldb.com/?kb.cti)
* [Cyber Threat Intelligence - Early Anticipation of Attacks](https://www.scip.ch/en/?labs.20201022)

## License

(c) [1997-2025](https://vuldb.com/?kb.changelog) by [vuldb.com](https://vuldb.com/?kb.about). All data on this page is shared under the license [CC BY-NC-SA 4.0](https://creativecommons.org/licenses/by-nc-sa/4.0/). Questions? Check the [FAQ](https://vuldb.com/?kb.faq), read the [documentation](https://vuldb.com/?kb) or [contact us](https://vuldb.com/?contact)!
