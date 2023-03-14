# Jupyter - Cyber Threat Intelligence

These _indicators_ were reported, collected, and generated during the [VulDB CTI analysis](https://vuldb.com/?kb.cti) of the actor known as [Jupyter](https://vuldb.com/?actor.jupyter). The _activity monitoring_ correlates data from social media, forums, chat rooms, and darknet markets. It helps to determine associated actors, specific activities, expected intentions, emerging research, and ongoing attacks. Our unique _predictive model_ uses _big data_ to forecast activities and their characteristics.

_Live data_ and more _analysis capabilities_ are available at [https://vuldb.com/?actor.jupyter](https://vuldb.com/?actor.jupyter)

## Countries

These _countries_ are directly (e.g. origin of attacks) or indirectly (e.g. access by proxy) associated with Jupyter:

* [US](https://vuldb.com/?country.us)
* [FR](https://vuldb.com/?country.fr)
* [RU](https://vuldb.com/?country.ru)
* ...

There are 32 more country items available. Please use our online service to access the data.

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
1 | T1006 | CWE-21, CWE-22, CWE-23 | Pathname Traversal | High
2 | T1040 | CWE-294 | Authentication Bypass by Capture-replay | High
3 | T1055 | CWE-74 | Injection | High
4 | T1059 | CWE-94, CWE-1321 | Cross Site Scripting | High
5 | T1059.007 | CWE-79, CWE-80, CWE-87 | Cross Site Scripting | High
6 | ... | ... | ... | ...

There are 22 more TTP items available. Please use our online service to access the data.

## IOA - Indicator of Attack

These _indicators of attack_ (IOA) list the potential fragments used for technical activities like reconnaissance, exploitation, privilege escalation, and exfiltration by Jupyter. This data is unique as it uses our predictive model for actor profiling.

ID | Type | Indicator | Confidence
-- | ---- | --------- | ----------
1 | File | `%PROGRAMDATA%\Razer\Synapse3\Service\bin` | High
2 | File | `.../gogo/` | Medium
3 | File | `.procmailrc` | Medium
4 | File | `/admin/` | Low
5 | File | `/admin/?page=system_info/contact_info` | High
6 | File | `/admin/communitymanagement.php` | High
7 | File | `/admin/contenttemp` | High
8 | File | `/admin/extended` | High
9 | File | `/admin/featured.php` | High
10 | File | `/admin/generalsettings.php` | High
11 | File | `/admin/login.php` | High
12 | File | `/admin/modules/system/custom_field.php` | High
13 | File | `/admin/newsletter1.php` | High
14 | File | `/admin/payment.php` | High
15 | File | `/admin/students/manage.php` | High
16 | File | `/admin/students/view_student.php` | High
17 | File | `/admin/usermanagement.php` | High
18 | File | `/api/addusers` | High
19 | File | `/api/crontab` | Medium
20 | File | `/api/user/upsert/<uuid>` | High
21 | File | `/api2/html/` | Medium
22 | File | `/apiadmin/notice/add` | High
23 | File | `/appliance/users?action=edit` | High
24 | File | `/backup.pl` | Medium
25 | File | `/cgi-bin/wapopen` | High
26 | File | `/cgi-bin/wlogin.cgi` | High
27 | File | `/cgi-mod/lookup.cgi` | High
28 | File | `/cloud_config/router_post/register` | High
29 | File | `/dashboard/updatelogo.php` | High
30 | File | `/designer/add/layout` | High
31 | File | `/etc/ldap.conf` | High
32 | File | `/etc/shadow` | Medium
33 | File | `/ext/phar/phar_object.c` | High
34 | File | `/filemanager/upload/drop` | High
35 | File | `/forum/away.php` | High
36 | File | `/forum/PostPrivateMessage` | High
37 | File | `/h/calendar` | Medium
38 | File | `/h/compose` | Medium
39 | File | `/h/search?action=voicemail&action=listen` | High
40 | File | `/home/cavesConsole` | High
41 | File | `/include/chart_generator.php` | High
42 | File | `/index.php` | Medium
43 | File | `/librarian/bookdetails.php` | High
44 | File | `/login/index.php` | High
45 | File | `/loginVaLidation.php` | High
46 | File | `/manage-apartment.php` | High
47 | File | `/manager/index.php` | High
48 | File | `/mgmt/tm/util/bash` | High
49 | File | `/mkshop/Men/profile.php` | High
50 | File | `/Noxen-master/users.php` | High
51 | File | `/opac/Actions.php?a=login` | High
52 | File | `/owa/auth/logon.aspx` | High
53 | File | `/p1/p2/:name` | Medium
54 | File | `/pages/animals.php` | High
55 | ... | ... | ...

There are 479 more IOA items available (file, library, argument, input value, pattern, network port). Please use our online service to access the data.

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

(c) [1997-2023](https://vuldb.com/?kb.changelog) by [vuldb.com](https://vuldb.com/?kb.about). All data on this page is shared under the license [CC BY-NC-SA 4.0](https://creativecommons.org/licenses/by-nc-sa/4.0/). Questions? Check the [FAQ](https://vuldb.com/?kb.faq), read the [documentation](https://vuldb.com/?kb) or [contact us](https://vuldb.com/?contact)!
