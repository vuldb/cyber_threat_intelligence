# Zloader - Cyber Threat Intelligence

These _indicators_ were reported, collected, and generated during the [VulDB CTI analysis](https://vuldb.com/?kb.cti) of the actor known as [Zloader](https://vuldb.com/?actor.zloader). The _activity monitoring_ correlates data from social media, forums, chat rooms, and darknet markets. It helps to determine associated actors, specific activities, expected intentions, emerging research, and ongoing attacks. Our unique _predictive model_ uses _big data_ to forecast activities and their characteristics.

_Live data_ and more _analysis capabilities_ are available at [https://vuldb.com/?actor.zloader](https://vuldb.com/?actor.zloader)

## Campaigns

The following _campaigns_ are known and can be associated with Zloader:

* Microsoft Signature Verification

## Countries

These _countries_ are directly (e.g. origin of attacks) or indirectly (e.g. access by proxy) associated with Zloader:

* [GB](https://vuldb.com/?country.gb)
* [US](https://vuldb.com/?country.us)
* [CN](https://vuldb.com/?country.cn)
* ...

There are 7 more country items available. Please use our online service to access the data.

## IOC - Indicator of Compromise

These _indicators of compromise_ (IOC) indicate associated network resources which are known to be part of research and attack activities of Zloader.

ID | IP address | Hostname | Campaign | Confidence
-- | ---------- | -------- | -------- | ----------
1 | [31.3.135.232](https://vuldb.com/?ip.31.3.135.232) | mirror.tillo.ch | - | High
2 | [37.228.151.133](https://vuldb.com/?ip.37.228.151.133) | - | - | High
3 | [45.63.25.55](https://vuldb.com/?ip.45.63.25.55) | 45.63.25.55.vultr.com | - | Medium
4 | [51.83.216.232](https://vuldb.com/?ip.51.83.216.232) | a1c.s.cuk.pl | - | High
5 | [62.113.203.55](https://vuldb.com/?ip.62.113.203.55) | - | - | High
6 | [77.221.149.190](https://vuldb.com/?ip.77.221.149.190) | - | - | High
7 | ... | ... | ... | ...

There are 22 more IOC items available. Please use our online service to access the data.

## TTP - Tactics, Techniques, Procedures

_Tactics, techniques, and procedures_ (TTP) summarize the suspected MITRE ATT&CK techniques used by _Zloader_. This data is unique as it uses our predictive model for actor profiling.

ID | Technique | Weakness | Description | Confidence
-- | --------- | -------- | ----------- | ----------
1 | T1006 | CWE-21, CWE-22, CWE-23, CWE-24, CWE-425 | Path Traversal | High
2 | T1055 | CWE-74, CWE-643 | Improper Neutralization of Data within XPath Expressions | High
3 | T1059 | CWE-94, CWE-1321 | Argument Injection | High
4 | T1059.007 | CWE-79, CWE-80 | Basic Cross Site Scripting | High
5 | ... | ... | ... | ...

There are 17 more TTP items available. Please use our online service to access the data.

## IOA - Indicator of Attack

These _indicators of attack_ (IOA) list the potential fragments used for technical activities like reconnaissance, exploitation, privilege escalation, and exfiltration by Zloader. This data is unique as it uses our predictive model for actor profiling.

ID | Type | Indicator | Confidence
-- | ---- | --------- | ----------
1 | File | `/abcd/opac/php/otros_sitios.php` | High
2 | File | `/admin.php?p=/Area/index#tab=t2` | High
3 | File | `/admin/?page=user/list` | High
4 | File | `/admin/action/edit_chicken.php` | High
5 | File | `/Admin/add-admin.php` | High
6 | File | `/admin/add-services.php` | High
7 | File | `/admin/add_user_modal.php` | High
8 | File | `/admin/admin-profile.php` | High
9 | File | `/admin/admin_user.php` | High
10 | File | `/admin/ajax.php?action=confirm_order` | High
11 | File | `/admin/ajax.php?action=login` | High
12 | File | `/admin/applicants/controller.php` | High
13 | File | `/admin/book_add.php` | High
14 | File | `/admin/cms_content.php` | High
15 | File | `/admin/conferences/list/` | High
16 | File | `/admin/court` | Medium
17 | File | `/admin/div_data/delete?divId=9` | High
18 | File | `/admin/edit_teacher.php` | High
19 | File | `/admin/educloud/videobind.html` | High
20 | File | `/admin/employee/controller.php` | High
21 | File | `/admin/employee/index.php` | High
22 | File | `/admin/index.php` | High
23 | File | `/admin/index.php?page=categories` | High
24 | File | `/admin/ind_backstage.php` | High
25 | File | `/admin/login.php` | High
26 | File | `/admin/pages/student-print.php` | High
27 | File | `/admin/pages/subjects.php` | High
28 | File | `/admin/return_add.php` | High
29 | File | `/admin/search.php` | High
30 | File | `/admin/service.php` | High
31 | File | `/admin/students.php` | High
32 | File | `/admin/system.html` | High
33 | File | `/admin/sys_sql_query.php` | High
34 | File | `/admin/template/update` | High
35 | File | `/admin/update_s6.php` | High
36 | File | `/admin/user/team` | High
37 | File | `/admin/users.php` | High
38 | File | `/admin/vacancy/index.php` | High
39 | File | `/admin/view_sendlist.php` | High
40 | File | `/adminpanel/admin/facebox_modal/updateCourse.php` | High
41 | File | `/adminpanel/admin/facebox_modal/updateExaminee.php` | High
42 | File | `/admin_ping.htm` | High
43 | File | `/adplanet/PlanetCommentList` | High
44 | File | `/ajax.php?action=read_msg` | High
45 | File | `/api/client/editemedia.php` | High
46 | File | `/api/controllers/common/UploadsController.php` | High
47 | File | `/api/file/downloadUrl` | High
48 | File | `/api/files/recipepictures/` | High
49 | File | `/api/ping` | Medium
50 | File | `/api/process.php` | High
51 | File | `/application/controller/Pengeluaran.php` | High
52 | File | `/application/index/controller/Databasesource.php` | High
53 | File | `/application/index/controller/Pay.php` | High
54 | File | `/application/index/controller/Screen.php` | High
55 | File | `/application/websocket/controller/Setting.php` | High
56 | File | `/apply/index.php` | High
57 | File | `/att_add.php` | Medium
58 | File | `/backend/admin/his_admin_register_patient.php` | High
59 | File | `/backend/register.php` | High
60 | File | `/baseOpLog.do` | High
61 | File | `/bcms/admin/?page=user/list` | High
62 | File | `/blog` | Low
63 | File | `/blog-single.php` | High
64 | File | `/book-services.php` | High
65 | File | `/cgi-bin/adm.cgi` | High
66 | File | `/cgi-bin/cstecgi.cgi` | High
67 | File | `/cgi-bin/jumpto.php?class=user&page=config_save&isphp=1` | High
68 | File | `/cgi-bin/koha/catalogue/search.pl` | High
69 | File | `/classes/Master.php?f=save_inquiry` | High
70 | File | `/classes/Users.php` | High
71 | File | `/classes/Users.php?f=save` | High
72 | File | `/collection/all` | High
73 | File | `/control/deactivate_case.php` | High
74 | File | `/DataHandler/AM/AM_Handler.ashx` | High
75 | ... | ... | ...

There are 662 more IOA items available (file, library, argument, input value, pattern, network port). Please use our online service to access the data.

## References

The following list contains _external sources_ which discuss the actor and the associated activities:

* https://blogs.blackberry.com/en/2017/12/threat-spotlight-terdot-a-zloader-malicious-downloader
* https://community.blueliv.com/#!/s/6141e29b82df417a0032fc18
* https://github.com/eSentire/iocs/blob/main/Zloader/zloader-iocs.txt
* https://isc.sans.edu/forums/diary/German+malspam+pushes+ZLoader+malware/25996/
* https://isc.sans.edu/forums/diary/Job+applicationthemed+malspam+pushes+ZLoader/26222/
* https://isc.sans.edu/forums/diary/Polish+malspam+pushes+ZLoader+malware/26196/
* https://research.checkpoint.com/2022/can-you-trust-a-files-digital-signature-new-zloader-campaign-exploits-microsofts-signature-verification-putting-users-at-risk/
* https://threatfox.abuse.ch
* https://www.zscaler.com/blogs/security-research/inside-zloader-s-latest-trick-dns-tunneling

## Literature

The following _articles_ explain our unique predictive cyber threat intelligence:

* [VulDB Cyber Threat Intelligence Documentation](https://vuldb.com/?kb.cti)
* [Cyber Threat Intelligence - Early Anticipation of Attacks](https://www.scip.ch/en/?labs.20201022)

## License

(c) [1997-2025](https://vuldb.com/?kb.changelog) by [vuldb.com](https://vuldb.com/?kb.about). All data on this page is shared under the license [CC BY-NC-SA 4.0](https://creativecommons.org/licenses/by-nc-sa/4.0/). Questions? Check the [FAQ](https://vuldb.com/?kb.faq), read the [documentation](https://vuldb.com/?kb) or [contact us](https://vuldb.com/?contact)!
