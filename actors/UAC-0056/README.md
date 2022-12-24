# UAC-0056 - Cyber Threat Intelligence

These _indicators_ were reported, collected, and generated during the [VulDB CTI analysis](https://vuldb.com/?kb.cti) of the actor known as [UAC-0056](https://vuldb.com/?actor.uac-0056). The _activity monitoring_ correlates data from social media, forums, chat rooms, and darknet markets. It helps to determine associated actors, specific activities, expected intentions, emerging research, and ongoing attacks. Our unique _predictive model_ uses _big data_ to forecast activities and their characteristics.

_Live data_ and more _analysis capabilities_ are available at [https://vuldb.com/?actor.uac-0056](https://vuldb.com/?actor.uac-0056)

## Campaigns

The following _campaigns_ are known and can be associated with UAC-0056:

* Cobalt Strike
* GraphSteel/GrimPlant
* Ukraine

## Countries

These _countries_ are directly (e.g. origin of attacks) or indirectly (e.g. access by proxy) associated with UAC-0056:

* [US](https://vuldb.com/?country.us)
* [RU](https://vuldb.com/?country.ru)
* [TR](https://vuldb.com/?country.tr)
* ...

There are 10 more country items available. Please use our online service to access the data.

## IOC - Indicator of Compromise

These _indicators of compromise_ (IOC) indicate associated network resources which are known to be part of research and attack activities of UAC-0056.

ID | IP address | Hostname | Campaign | Confidence
-- | ---------- | -------- | -------- | ----------
1 | [31.42.185.63](https://vuldb.com/?ip.31.42.185.63) | dedicated.vsys.host | Ukraine | High
2 | [45.84.0.116](https://vuldb.com/?ip.45.84.0.116) | n5336.md | - | High
3 | [45.146.164.37](https://vuldb.com/?ip.45.146.164.37) | - | Ukraine | High
4 | ... | ... | ... | ...

There are 11 more IOC items available. Please use our online service to access the data.

## TTP - Tactics, Techniques, Procedures

_Tactics, techniques, and procedures_ (TTP) summarize the suspected MITRE ATT&CK techniques used by _UAC-0056_. This data is unique as it uses our predictive model for actor profiling.

ID | Technique | Weakness | Description | Confidence
-- | --------- | -------- | ----------- | ----------
1 | T1006 | CWE-21, CWE-22, CWE-23, CWE-425 | Pathname Traversal | High
2 | T1040 | CWE-294 | Authentication Bypass by Capture-replay | High
3 | T1055 | CWE-74 | Injection | High
4 | T1059 | CWE-94 | Cross Site Scripting | High
5 | ... | ... | ... | ...

There are 16 more TTP items available. Please use our online service to access the data.

## IOA - Indicator of Attack

These _indicators of attack_ (IOA) list the potential fragments used for technical activities like reconnaissance, exploitation, privilege escalation, and exfiltration by UAC-0056. This data is unique as it uses our predictive model for actor profiling.

ID | Type | Indicator | Confidence
-- | ---- | --------- | ----------
1 | File | `/admin.php` | Medium
2 | File | `/admin/?page=system_info/contact_info` | High
3 | File | `/admin/doctors/view_doctor.php` | High
4 | File | `/admin/edit_user.php` | High
5 | File | `/admin/modules/bibliography/index.php` | High
6 | File | `/admin/question/edit` | High
7 | File | `/admin/students/manage.php` | High
8 | File | `/adminlogin.asp` | High
9 | File | `/api/` | Low
10 | File | `/app/controller/Books.php` | High
11 | File | `/bifs/field_decode.c` | High
12 | File | `/bin/proc.cgi` | High
13 | File | `/cgi/get_param.cgi` | High
14 | File | `/controller/Index.php` | High
15 | File | `/Core/Ap4File.cpp` | High
16 | File | `/csms/?page=contact_us` | High
17 | File | `/debug/pprof` | Medium
18 | File | `/DXR.axd` | Medium
19 | File | `/etc/master.passwd` | High
20 | File | `/etc/passwd` | Medium
21 | File | `/goform/AddSysLogRule` | High
22 | File | `/goform/aspForm` | High
23 | File | `/hocms/classes/Master.php?f=delete_collection` | High
24 | File | `/include/friends.inc.php` | High
25 | File | `/index.php` | Medium
26 | File | `/index.php?module=configuration/application` | High
27 | File | `/index.php?route=extension/module/so_filter_shop_by/filter_data` | High
28 | File | `/isomedia/box_funcs.c` | High
29 | File | `/isomedia/meta.c` | High
30 | File | `/members/view_member.php` | High
31 | File | `/php_action/editProductImage.php` | High
32 | File | `/plesk-site-preview/` | High
33 | File | `/project/PROJECTNAME/reports/` | High
34 | File | `/sacco_shield/manage_loan.php` | High
35 | File | `/scene_manager/scene_dump.c` | High
36 | File | `/school/model/get_admin_profile.php` | High
37 | File | `/services/view_service.php` | High
38 | File | `/servlet/webacc` | High
39 | File | `/shell` | Low
40 | File | `/spip.php` | Medium
41 | File | `/student-grading-system/rms.php?page=grade` | High
42 | File | `/timeline2.php` | High
43 | File | `/userui/ticket_list.php` | High
44 | File | `/user_operations/profile.php` | High
45 | File | `/usr/bin/pkexec` | High
46 | File | `/wp-admin/options-general.php` | High
47 | File | `/zm/index.php` | High
48 | File | `/_next` | Low
49 | File | `abook_database.php` | High
50 | File | `accounts/inc/include.php` | High
51 | File | `actionpack/lib/action_dispatch/middleware/templates/routes/_table.html.erb` | High
52 | File | `adaptive-images-script.php` | High
53 | File | `additem.asp` | Medium
54 | File | `adherents/subscription/info.php` | High
55 | File | `admin.asp` | Medium
56 | File | `admin.php` | Medium
57 | File | `admin/admin_users.php` | High
58 | File | `admin/article_save.php` | High
59 | File | `admin/header.php` | High
60 | File | `admin/index.php` | High
61 | File | `admin/login.asp` | High
62 | File | `admin/manage-comments.php` | High
63 | File | `admin/manage-news.php` | High
64 | File | `admin/plugin-settings.php` | High
65 | File | `admin/theme-edit.php` | High
66 | File | `adminer.php` | Medium
67 | File | `administrator/components/com_media/helpers/media.php` | High
68 | File | `administrator/index.php` | High
69 | File | `admin_login.asp` | High
70 | File | `ajax_calls.php` | High
71 | File | `al_initialize.php` | High
72 | ... | ... | ...

There are 629 more IOA items available (file, library, argument, input value, pattern, network port). Please use our online service to access the data.

## References

The following list contains _external sources_ which discuss the actor and the associated activities:

* https://1275.ru/ioc/533/unc2589-iocs/
* https://blog.malwarebytes.com/threat-intelligence/2022/07/cobalt-strikes-again-uac-0056-continues-to-target-ukraine-in-its-latest-campaign/
* https://cert.gov.ua/article/18419
* https://cert.gov.ua/article/37704
* https://cert.gov.ua/article/38374
* https://cert.gov.ua/article/39882
* https://community.blueliv.com/#!/s/624be71d82df413eb235593a
* https://unit42.paloaltonetworks.com/ukraine-targeted-outsteel-saintbot/
* https://www.sentinelone.com/blog/threat-actor-uac-0056-targeting-ukraine-with-fake-translation-software/

## Literature

The following _articles_ explain our unique predictive cyber threat intelligence:

* [VulDB Cyber Threat Intelligence Documentation](https://vuldb.com/?kb.cti)
* [Cyber Threat Intelligence - Early Anticipation of Attacks](https://www.scip.ch/en/?labs.20201022)

## License

(c) [1997-2022](https://vuldb.com/?kb.changelog) by [vuldb.com](https://vuldb.com/?kb.about). All data on this page is shared under the license [CC BY-NC-SA 4.0](https://creativecommons.org/licenses/by-nc-sa/4.0/). Questions? Check the [FAQ](https://vuldb.com/?kb.faq), read the [documentation](https://vuldb.com/?kb) or [contact us](https://vuldb.com/?contact)!
