# Jupyter - Cyber Threat Intelligence

These _indicators_ were reported, collected, and generated during the [VulDB CTI analysis](https://vuldb.com/?kb.cti) of the actor known as [Jupyter](https://vuldb.com/?actor.jupyter). The _activity monitoring_ correlates data from social media, forums, chat rooms, and darknet markets. It helps to determine associated actors, specific activities, expected intentions, emerging research, and ongoing attacks. Our unique _predictive model_ uses _big data_ to forecast activities and their characteristics.

_Live data_ and more _analysis capabilities_ are available at [https://vuldb.com/?actor.jupyter](https://vuldb.com/?actor.jupyter)

## Countries

These _countries_ are directly (e.g. origin of attacks) or indirectly (e.g. access by proxy) associated with Jupyter:

* [US](https://vuldb.com/?country.us)
* [GB](https://vuldb.com/?country.gb)
* [DE](https://vuldb.com/?country.de)
* ...

There are 28 more country items available. Please use our online service to access the data.

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
1 | T1006 | CWE-21, CWE-22, CWE-23, CWE-24, CWE-36, CWE-37 | Path Traversal | High
2 | T1040 | CWE-294, CWE-319 | Authentication Bypass by Capture-replay | High
3 | T1055 | CWE-74 | Injection | High
4 | T1059 | CWE-88, CWE-94, CWE-1321 | Argument Injection | High
5 | T1059.007 | CWE-79, CWE-80, CWE-87 | Cross Site Scripting | High
6 | T1068 | CWE-264, CWE-269, CWE-284 | Execution with Unnecessary Privileges | High
7 | ... | ... | ... | ...

There are 22 more TTP items available. Please use our online service to access the data.

## IOA - Indicator of Attack

These _indicators of attack_ (IOA) list the potential fragments used for technical activities like reconnaissance, exploitation, privilege escalation, and exfiltration by Jupyter. This data is unique as it uses our predictive model for actor profiling.

ID | Type | Indicator | Confidence
-- | ---- | --------- | ----------
1 | File | `.../gogo/` | Medium
2 | File | `/.env` | Low
3 | File | `/?ajax-request=jnews` | High
4 | File | `/?r=recruit/resume/edit&op=status` | High
5 | File | `/admin/?page=user/list` | High
6 | File | `/admin/?page=user/manage_user&id=3` | High
7 | File | `/admin/about-us.php` | High
8 | File | `/admin/action/new-father.php` | High
9 | File | `/admin/del_category.php` | High
10 | File | `/admin/del_service.php` | High
11 | File | `/admin/edit-accepted-appointment.php` | High
12 | File | `/admin/edit-services.php` | High
13 | File | `/admin/edit.php` | High
14 | File | `/admin/edit_category.php` | High
15 | File | `/admin/edit_subject.php` | High
16 | File | `/admin/forgot-password.php` | High
17 | File | `/admin/index.php` | High
18 | File | `/admin/products/manage_product.php` | High
19 | File | `/admin/reg.php` | High
20 | File | `/admin/search-appointment.php` | High
21 | File | `/admin/students/manage.php` | High
22 | File | `/admin/sys_sql_query.php` | High
23 | File | `/api/user/upsert/<uuid>` | High
24 | File | `/api/v4/teams//channels/deleted` | High
25 | File | `/api2/html/` | Medium
26 | File | `/apiadmin/notice/add` | High
27 | File | `/appliance/users?action=edit` | High
28 | File | `/application/index/controller/Screen.php` | High
29 | File | `/application/websocket/controller/Setting.php` | High
30 | File | `/backup.pl` | Medium
31 | File | `/bin/boa` | Medium
32 | File | `/blog` | Low
33 | File | `/boafrm/formMapDelDevice` | High
34 | File | `/booking/show_bookings/` | High
35 | File | `/cgi-bin/cstecgi.cgi` | High
36 | File | `/cgi-bin/cstecgi.cgi?action=login` | High
37 | File | `/collection/all` | High
38 | File | `/dipam/athlete-profile.php` | High
39 | File | `/E-mobile/App/System/File/downfile.php` | High
40 | File | `/ecommerce/support_ticket` | High
41 | File | `/edoc/doctor/patient.php` | High
42 | File | `/emap/devicePoint_addImgIco?hasSubsystem=true` | High
43 | File | `/endpoint/delete-computer.php` | High
44 | File | `/endpoint/update-tracker.php` | High
45 | File | `/etc/ldap.conf` | High
46 | File | `/etc/shadow` | Medium
47 | File | `/ext/phar/phar_object.c` | High
48 | File | `/forum/away.php` | High
49 | File | `/forum/PostPrivateMessage` | High
50 | File | `/fusion/portal/action/Link` | High
51 | File | `/h/calendar` | Medium
52 | File | `/h/compose` | Medium
53 | File | `/h/search?action=voicemail&action=listen` | High
54 | File | `/hedwig.cgi` | Medium
55 | File | `/HNAP1/` | Low
56 | File | `/home/cavesConsole` | High
57 | File | `/importexport.php` | High
58 | File | `/include/file.php` | High
59 | File | `/index.php` | Medium
60 | File | `/index.php?app=main&func=passport&action=login` | High
61 | File | `/kelasdosen/data` | High
62 | File | `/listplace/user/coverPhotoUpdate` | High
63 | File | `/login/index.php` | High
64 | File | `/manager/index.php` | High
65 | File | `/nagiosxi/admin/banner_message-ajaxhelper.php` | High
66 | File | `/opac/Actions.php?a=login` | High
67 | File | `/osm/REGISTER.cmd` | High
68 | ... | ... | ...

There are 592 more IOA items available (file, library, argument, input value, pattern, network port). Please use our online service to access the data.

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

(c) [1997-2024](https://vuldb.com/?kb.changelog) by [vuldb.com](https://vuldb.com/?kb.about). All data on this page is shared under the license [CC BY-NC-SA 4.0](https://creativecommons.org/licenses/by-nc-sa/4.0/). Questions? Check the [FAQ](https://vuldb.com/?kb.faq), read the [documentation](https://vuldb.com/?kb) or [contact us](https://vuldb.com/?contact)!
