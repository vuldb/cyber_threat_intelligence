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

There are 5 more country items available. Please use our online service to access the data.

## IOC - Indicator of Compromise

These _indicators of compromise_ (IOC) indicate associated network resources which are known to be part of research and attack activities of Zloader.

ID | IP address | Hostname | Campaign | Confidence
-- | ---------- | -------- | -------- | ----------
1 | [31.3.135.232](https://vuldb.com/?ip.31.3.135.232) | mirror.tillo.ch | - | High
2 | [37.228.151.133](https://vuldb.com/?ip.37.228.151.133) | - | - | High
3 | [45.63.25.55](https://vuldb.com/?ip.45.63.25.55) | 45.63.25.55.vultr.com | - | Medium
4 | [51.83.216.232](https://vuldb.com/?ip.51.83.216.232) | a1c.s.cuk.pl | - | High
5 | [62.113.203.55](https://vuldb.com/?ip.62.113.203.55) | - | - | High
6 | ... | ... | ... | ...

There are 18 more IOC items available. Please use our online service to access the data.

## TTP - Tactics, Techniques, Procedures

_Tactics, techniques, and procedures_ (TTP) summarize the suspected MITRE ATT&CK techniques used by _Zloader_. This data is unique as it uses our predictive model for actor profiling.

ID | Technique | Weakness | Description | Confidence
-- | --------- | -------- | ----------- | ----------
1 | T1006 | CWE-21, CWE-22, CWE-24 | Path Traversal | High
2 | T1055 | CWE-74, CWE-643 | Improper Neutralization of Data within XPath Expressions | High
3 | T1059 | CWE-94, CWE-1321 | Argument Injection | High
4 | T1059.007 | CWE-79, CWE-80 | Cross Site Scripting | High
5 | ... | ... | ... | ...

There are 15 more TTP items available. Please use our online service to access the data.

## IOA - Indicator of Attack

These _indicators of attack_ (IOA) list the potential fragments used for technical activities like reconnaissance, exploitation, privilege escalation, and exfiltration by Zloader. This data is unique as it uses our predictive model for actor profiling.

ID | Type | Indicator | Confidence
-- | ---- | --------- | ----------
1 | File | `/admin.php?p=/Area/index#tab=t2` | High
2 | File | `/admin/?page=user/list` | High
3 | File | `/admin/action/edit_chicken.php` | High
4 | File | `/admin/add-services.php` | High
5 | File | `/admin/add_user_modal.php` | High
6 | File | `/admin/admin-profile.php` | High
7 | File | `/admin/admin_user.php` | High
8 | File | `/admin/ajax.php?action=confirm_order` | High
9 | File | `/admin/applicants/controller.php` | High
10 | File | `/admin/book_add.php` | High
11 | File | `/admin/cms_content.php` | High
12 | File | `/admin/conferences/list/` | High
13 | File | `/admin/div_data/delete?divId=9` | High
14 | File | `/admin/edit_teacher.php` | High
15 | File | `/admin/employee/controller.php` | High
16 | File | `/admin/employee/index.php` | High
17 | File | `/admin/ind_backstage.php` | High
18 | File | `/admin/login.php` | High
19 | File | `/admin/pages/student-print.php` | High
20 | File | `/admin/pages/subjects.php` | High
21 | File | `/admin/return_add.php` | High
22 | File | `/admin/search.php` | High
23 | File | `/admin/service.php` | High
24 | File | `/admin/students.php` | High
25 | File | `/admin/sys_sql_query.php` | High
26 | File | `/admin/update_s6.php` | High
27 | File | `/admin/user/team` | High
28 | File | `/admin/users.php` | High
29 | File | `/admin/vacancy/index.php` | High
30 | File | `/admin/view_sendlist.php` | High
31 | File | `/adminpanel/admin/facebox_modal/updateCourse.php` | High
32 | File | `/adminpanel/admin/facebox_modal/updateExaminee.php` | High
33 | File | `/admin_ping.htm` | High
34 | File | `/adplanet/PlanetCommentList` | High
35 | File | `/ajax.php?action=read_msg` | High
36 | File | `/api/client/editemedia.php` | High
37 | File | `/api/controllers/common/UploadsController.php` | High
38 | File | `/api/ping` | Medium
39 | File | `/api/process.php` | High
40 | File | `/application/controller/Pengeluaran.php` | High
41 | File | `/application/index/controller/Databasesource.php` | High
42 | File | `/application/index/controller/Pay.php` | High
43 | File | `/application/index/controller/Screen.php` | High
44 | File | `/application/websocket/controller/Setting.php` | High
45 | File | `/apply/index.php` | High
46 | File | `/att_add.php` | Medium
47 | File | `/backend/register.php` | High
48 | File | `/baseOpLog.do` | High
49 | File | `/bcms/admin/?page=user/list` | High
50 | File | `/blog` | Low
51 | File | `/blog-single.php` | High
52 | File | `/book-services.php` | High
53 | File | `/cgi-bin/adm.cgi` | High
54 | File | `/cgi-bin/cstecgi.cgi` | High
55 | File | `/cgi-bin/jumpto.php?class=user&page=config_save&isphp=1` | High
56 | File | `/cgi-bin/koha/catalogue/search.pl` | High
57 | File | `/classes/Master.php?f=save_inquiry` | High
58 | File | `/classes/Users.php` | High
59 | ... | ... | ...

There are 519 more IOA items available (file, library, argument, input value, pattern, network port). Please use our online service to access the data.

## References

The following list contains _external sources_ which discuss the actor and the associated activities:

* https://blogs.blackberry.com/en/2017/12/threat-spotlight-terdot-a-zloader-malicious-downloader
* https://community.blueliv.com/#!/s/6141e29b82df417a0032fc18
* https://isc.sans.edu/forums/diary/German+malspam+pushes+ZLoader+malware/25996/
* https://isc.sans.edu/forums/diary/Job+applicationthemed+malspam+pushes+ZLoader/26222/
* https://isc.sans.edu/forums/diary/Polish+malspam+pushes+ZLoader+malware/26196/
* https://research.checkpoint.com/2022/can-you-trust-a-files-digital-signature-new-zloader-campaign-exploits-microsofts-signature-verification-putting-users-at-risk/

## Literature

The following _articles_ explain our unique predictive cyber threat intelligence:

* [VulDB Cyber Threat Intelligence Documentation](https://vuldb.com/?kb.cti)
* [Cyber Threat Intelligence - Early Anticipation of Attacks](https://www.scip.ch/en/?labs.20201022)

## License

(c) [1997-2024](https://vuldb.com/?kb.changelog) by [vuldb.com](https://vuldb.com/?kb.about). All data on this page is shared under the license [CC BY-NC-SA 4.0](https://creativecommons.org/licenses/by-nc-sa/4.0/). Questions? Check the [FAQ](https://vuldb.com/?kb.faq), read the [documentation](https://vuldb.com/?kb) or [contact us](https://vuldb.com/?contact)!
