# UNIX CCTV DVR - Cyber Threat Intelligence

These _indicators_ were reported, collected, and generated during the [VulDB CTI analysis](https://vuldb.com/?kb.cti) of the campaign known as _UNIX CCTV DVR_. The _activity monitoring_ correlates data from social media, forums, chat rooms, and darknet markets. It helps to determine associated actors, specific activities, expected intentions, emerging research, and ongoing attacks. Our unique _predictive model_ uses _big data_ to forecast activities and their characteristics.

_Live data_ and more _analysis capabilities_ are available at [https://vuldb.com/?actor](https://vuldb.com/?actor)

## Countries

These _countries_ are directly (e.g. origin of attacks) or indirectly (e.g. access by proxy) associated with UNIX CCTV DVR:

* [LU](https://vuldb.com/?country.lu)
* [US](https://vuldb.com/?country.us)
* [CN](https://vuldb.com/?country.cn)
* ...

There are 19 more country items available. Please use our online service to access the data.

## Actors

These _actors_ are associated with UNIX CCTV DVR or other actors linked to the campaign.

ID | Actor | Confidence
-- | ----- | ----------
1 | [Moobot](https://vuldb.com/?actor.moobot) | High

## IOC - Indicator of Compromise

These _indicators of compromise_ (IOC) indicate associated network resources which are known to be part of research and attack activities of UNIX CCTV DVR.

ID | IP address | Hostname | Actor | Confidence
-- | ---------- | -------- | ----- | ----------
1 | [89.248.174.165](https://vuldb.com/?ip.89.248.174.165) | - | [Moobot](https://vuldb.com/?actor.moobot) | High
2 | [89.248.174.166](https://vuldb.com/?ip.89.248.174.166) | - | [Moobot](https://vuldb.com/?actor.moobot) | High
3 | [89.248.174.203](https://vuldb.com/?ip.89.248.174.203) | no-reverse-dns-configured.com | [Moobot](https://vuldb.com/?actor.moobot) | High
4 | [92.223.73.54](https://vuldb.com/?ip.92.223.73.54) | james050721.example.com | [Moobot](https://vuldb.com/?actor.moobot) | High
5 | ... | ... | ... | ...

There are 16 more IOC items available. Please use our online service to access the data.

## TTP - Tactics, Techniques, Procedures

_Tactics, techniques, and procedures_ (TTP) summarize the suspected MITRE ATT&CK techniques used within UNIX CCTV DVR. This data is unique as it uses our predictive model for actor profiling.

ID | Technique | Weakness | Description | Confidence
-- | --------- | -------- | ----------- | ----------
1 | T1006 | CWE-21, CWE-22, CWE-24, CWE-35, CWE-425 | Path Traversal | High
2 | T1040 | CWE-319 | Authentication Bypass by Capture-replay | High
3 | T1055 | CWE-74 | Improper Neutralization of Data within XPath Expressions | High
4 | T1059 | CWE-94, CWE-1321 | Argument Injection | High
5 | T1059.007 | CWE-79, CWE-80 | Basic Cross Site Scripting | High
6 | T1068 | CWE-250, CWE-264, CWE-266, CWE-269, CWE-284 | Execution with Unnecessary Privileges | High
7 | ... | ... | ... | ...

There are 22 more TTP items available. Please use our online service to access the data.

## IOA - Indicator of Attack

These _indicators of attack_ (IOA) list the potential fragments used for technical activities like reconnaissance, exploitation, privilege escalation, and exfiltration during UNIX CCTV DVR. This data is unique as it uses our predictive model for actor profiling.

ID | Type | Indicator | Confidence
-- | ---- | --------- | ----------
1 | File | `%PROGRAMFILES(X86)%\TSplus\UserDesktop\themes.` | High
2 | File | `/activate_hook.php` | High
3 | File | `/add_new_supplier.php` | High
4 | File | `/add_post_sql.php` | High
5 | File | `/admin/book_row.php` | High
6 | File | `/admin/categories/update` | High
7 | File | `/admin/del_service.php` | High
8 | File | `/admin/edit-subadmin.php` | High
9 | File | `/admin/index.php` | High
10 | File | `/admin/maintenance/view_designation.php` | High
11 | File | `/admin/process_category_add.php` | High
12 | File | `/admin/quizquestion.php` | High
13 | File | `/admin/search-appointment.php` | High
14 | File | `/admin/tag/delete` | High
15 | File | `/admin/user/manage_user.php` | High
16 | File | `/ajax.php?action=login` | High
17 | File | `/ajax.php?action=read_msg` | High
18 | File | `/ajax.php?action=save_category` | High
19 | File | `/api/baskets/{name}` | High
20 | File | `/app/api/controller/caiji.php` | High
21 | File | `/bitrix/admin/ldap_server_edit.php` | High
22 | File | `/blog/edit` | Medium
23 | File | `/buscar_integrada.php` | High
24 | File | `/cgi-bin/wlogin.cgi` | High
25 | File | `/classes/Master.php` | High
26 | File | `/classes/Master.php?f=delete_category` | High
27 | File | `/classes/Master.php?f=save_item` | High
28 | File | `/config/php.ini` | High
29 | File | `/data/remove` | Medium
30 | File | `/debug/pprof` | Medium
31 | File | `/desktop_app/file.ajax.php?action=uploadfile` | High
32 | File | `/details.php` | Medium
33 | File | `/editprofile.php` | High
34 | File | `/Employer/ManageWalkin.php` | High
35 | File | `/endpoint/add-calorie.php` | High
36 | File | `/endpoint/delete-computer.php` | High
37 | File | `/endpoint/update.php` | High
38 | File | `/expedit.php` | Medium
39 | File | `/export` | Low
40 | File | `/formLoginAuth.htm` | High
41 | File | `/forum/away.php` | High
42 | File | `/goform/PowerSaveSet` | High
43 | File | `/goform/wizard_end` | High
44 | File | `/guest/update.php` | High
45 | File | `/home/get_tasks_list` | High
46 | File | `/importexport.php` | High
47 | File | `/index.php` | Medium
48 | File | `/isms/classes/Users.php` | High
49 | File | `/jobportal/index.php` | High
50 | File | `/lists/index.php` | High
51 | File | `/MailAdmin_dll.htm` | High
52 | File | `/manage_supplier.php` | High
53 | File | `/members/view_member.php` | High
54 | File | `/messageboard/view.php` | High
55 | File | `/mhds/clinic/view_details.php` | High
56 | File | `/modules/projects/vw_files.php` | High
57 | File | `/myprofile.php` | High
58 | File | `/net/tls/tls_sw.c` | High
59 | File | `/newdriver.php` | High
60 | ... | ... | ...

There are 524 more IOA items available (file, library, argument, input value, pattern, network port). Please use our online service to access the data.

## References

The following list contains _external sources_ which discuss the campaign and the associated activities:

* https://blog.netlab.360.com/moobot-0day-unixcctv-dvr-en/

## Literature

The following _articles_ explain our unique predictive cyber threat intelligence:

* [VulDB Cyber Threat Intelligence Documentation](https://vuldb.com/?kb.cti)
* [Cyber Threat Intelligence - Early Anticipation of Attacks](https://www.scip.ch/en/?labs.20201022)

## License

(c) [1997-2025](https://vuldb.com/?kb.changelog) by [vuldb.com](https://vuldb.com/?kb.about). All data on this page is shared under the license [CC BY-NC-SA 4.0](https://creativecommons.org/licenses/by-nc-sa/4.0/). Questions? Check the [FAQ](https://vuldb.com/?kb.faq), read the [documentation](https://vuldb.com/?kb) or [contact us](https://vuldb.com/?contact)!
