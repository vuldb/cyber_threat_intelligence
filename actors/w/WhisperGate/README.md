# WhisperGate - Cyber Threat Intelligence

These _indicators_ were reported, collected, and generated during the [VulDB CTI analysis](https://vuldb.com/?kb.cti) of the actor known as [WhisperGate](https://vuldb.com/?actor.whispergate). The _activity monitoring_ correlates data from social media, forums, chat rooms, and darknet markets. It helps to determine associated actors, specific activities, expected intentions, emerging research, and ongoing attacks. Our unique _predictive model_ uses _big data_ to forecast activities and their characteristics.

_Live data_ and more _analysis capabilities_ are available at [https://vuldb.com/?actor.whispergate](https://vuldb.com/?actor.whispergate)

## Countries

These _countries_ are directly (e.g. origin of attacks) or indirectly (e.g. access by proxy) associated with WhisperGate:

* [US](https://vuldb.com/?country.us)
* [RU](https://vuldb.com/?country.ru)
* [GB](https://vuldb.com/?country.gb)
* ...

There are 24 more country items available. Please use our online service to access the data.

## IOC - Indicator of Compromise

These _indicators of compromise_ (IOC) indicate associated network resources which are known to be part of research and attack activities of WhisperGate.

ID | IP address | Hostname | Campaign | Confidence
-- | ---------- | -------- | -------- | ----------
1 | [5.226.139.66](https://vuldb.com/?ip.5.226.139.66) | 66.139.226.5.baremetal.zare.com | - | High
2 | [45.141.87.11](https://vuldb.com/?ip.45.141.87.11) | - | - | High
3 | [46.101.242.222](https://vuldb.com/?ip.46.101.242.222) | kukij.com | - | High
4 | [62.173.140.223](https://vuldb.com/?ip.62.173.140.223) | vserver.tbits.ru | - | High
5 | [79.124.8.66](https://vuldb.com/?ip.79.124.8.66) | - | - | High
6 | ... | ... | ... | ...

There are 20 more IOC items available. Please use our online service to access the data.

## TTP - Tactics, Techniques, Procedures

_Tactics, techniques, and procedures_ (TTP) summarize the suspected MITRE ATT&CK techniques used by _WhisperGate_. This data is unique as it uses our predictive model for actor profiling.

ID | Technique | Weakness | Description | Confidence
-- | --------- | -------- | ----------- | ----------
1 | T1006 | CWE-21, CWE-22, CWE-425 | Path Traversal | High
2 | T1055 | CWE-74 | Improper Neutralization of Data within XPath Expressions | High
3 | T1059 | CWE-88, CWE-94, CWE-1321 | Argument Injection | High
4 | T1059.007 | CWE-79, CWE-80 | Cross Site Scripting | High
5 | T1068 | CWE-250, CWE-264, CWE-269, CWE-284 | Execution with Unnecessary Privileges | High
6 | ... | ... | ... | ...

There are 19 more TTP items available. Please use our online service to access the data.

## IOA - Indicator of Attack

These _indicators of attack_ (IOA) list the potential fragments used for technical activities like reconnaissance, exploitation, privilege escalation, and exfiltration by WhisperGate. This data is unique as it uses our predictive model for actor profiling.

ID | Type | Indicator | Confidence
-- | ---- | --------- | ----------
1 | File | `/.env` | Low
2 | File | `//proc/kcore` | Medium
3 | File | `/?r=recruit/resume/edit&op=status` | High
4 | File | `/add-students.php` | High
5 | File | `/admin/?page=user/list` | High
6 | File | `/admin/?page=user/manage_user&id=3` | High
7 | File | `/admin/about-us.php` | High
8 | File | `/admin/action/delete-vaccine.php` | High
9 | File | `/admin/action/new-father.php` | High
10 | File | `/admin/app/service_crud.php` | High
11 | File | `/admin/del_category.php` | High
12 | File | `/admin/del_service.php` | High
13 | File | `/admin/doAdminAction.php?act=addCate` | High
14 | File | `/admin/edit-accepted-appointment.php` | High
15 | File | `/admin/edit-admin.php` | High
16 | File | `/admin/edit-post.php` | High
17 | File | `/admin/edit-services.php` | High
18 | File | `/admin/edit_category.php` | High
19 | File | `/admin/forgot-password.php` | High
20 | File | `/admin/index.php` | High
21 | File | `/admin/index2.html` | High
22 | File | `/admin/list_crl_conf` | High
23 | File | `/Admin/login.php` | High
24 | File | `/admin/manage_user.php` | High
25 | File | `/admin/pages/list` | High
26 | File | `/admin/reg.php` | High
27 | File | `/admin/search-appointment.php` | High
28 | File | `/admin/search.php` | High
29 | File | `/admin/system.html` | High
30 | File | `/admin/sys_sql_query.php` | High
31 | File | `/api/baskets/{name}` | High
32 | File | `/api/v4/teams//channels/deleted` | High
33 | File | `/app/admin/controller/Upload.php` | High
34 | File | `/app/ajax/search_sales_report.php` | High
35 | File | `/app/controller/Setup.php` | High
36 | File | `/app/index/controller/Common.php` | High
37 | File | `/app/middleware/TokenVerify.php` | High
38 | File | `/appliance/users?action=edit` | High
39 | File | `/application/index/controller/Screen.php` | High
40 | File | `/application/websocket/controller/Setting.php` | High
41 | File | `/applications/core/modules/admin/editor/toolbar.php` | High
42 | File | `/Applications/Google\ Drive.app/Contents/MacOS` | High
43 | File | `/applications/nexus/modules/front/store/store.php` | High
44 | File | `/apply/index.php` | High
45 | File | `/bin/boa` | Medium
46 | File | `/bitrix/admin/ldap_server_edit.php` | High
47 | File | `/blog` | Low
48 | File | `/boafrm/formMapDelDevice` | High
49 | File | `/booking/show_bookings/` | High
50 | File | `/cgi-bin/apkg_mgr.cgi` | High
51 | File | `/cgi-bin/cstecgi.cgi` | High
52 | File | `/cgi-bin/cstecgi.cgi?action=login` | High
53 | File | `/cgi-bin/myMusic.cgi` | High
54 | File | `/cgi-bin/nas_sharing.cgi` | High
55 | File | `/cgi-bin/photocenter_mgr.cgi` | High
56 | File | `/classes/Master.php` | High
57 | File | `/classes/Master.php?f=delete_record` | High
58 | File | `/classes/Master.php?f=save_category` | High
59 | File | `/classes/Master.php?f=save_medicine` | High
60 | File | `/classes/SystemSettings.php?f=update_settings` | High
61 | File | `/classes/Users.php?f=save` | High
62 | File | `/collection/all` | High
63 | File | `/description.php` | High
64 | File | `/detailed.php` | High
65 | File | `/dipam/athlete-profile.php` | High
66 | File | `/dtale/chart-data/1` | High
67 | File | `/emap/devicePoint_addImgIco?hasSubsystem=true` | High
68 | File | `/Employer/ManageWalkin.php` | High
69 | File | `/endpoint/add-faq.php` | High
70 | File | `/endpoint/delete-account.php` | High
71 | File | `/endpoint/delete-computer.php` | High
72 | ... | ... | ...

There are 628 more IOA items available (file, library, argument, input value, pattern, network port). Please use our online service to access the data.

## References

The following list contains _external sources_ which discuss the actor and the associated activities:

* https://blog.cyble.com/2022/02/01/whispergate-malware-deep-dive-analysis/
* https://blogs.blackberry.com/en/2022/01/threat-thursday-whispergate-wiper
* https://www.cisa.gov/news-events/cybersecurity-advisories/aa24-249a

## Literature

The following _articles_ explain our unique predictive cyber threat intelligence:

* [VulDB Cyber Threat Intelligence Documentation](https://vuldb.com/?kb.cti)
* [Cyber Threat Intelligence - Early Anticipation of Attacks](https://www.scip.ch/en/?labs.20201022)

## License

(c) [1997-2024](https://vuldb.com/?kb.changelog) by [vuldb.com](https://vuldb.com/?kb.about). All data on this page is shared under the license [CC BY-NC-SA 4.0](https://creativecommons.org/licenses/by-nc-sa/4.0/). Questions? Check the [FAQ](https://vuldb.com/?kb.faq), read the [documentation](https://vuldb.com/?kb) or [contact us](https://vuldb.com/?contact)!
