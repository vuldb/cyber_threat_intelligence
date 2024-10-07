# PsiXBot - Cyber Threat Intelligence

These _indicators_ were reported, collected, and generated during the [VulDB CTI analysis](https://vuldb.com/?kb.cti) of the actor known as [PsiXBot](https://vuldb.com/?actor.psixbot). The _activity monitoring_ correlates data from social media, forums, chat rooms, and darknet markets. It helps to determine associated actors, specific activities, expected intentions, emerging research, and ongoing attacks. Our unique _predictive model_ uses _big data_ to forecast activities and their characteristics.

_Live data_ and more _analysis capabilities_ are available at [https://vuldb.com/?actor.psixbot](https://vuldb.com/?actor.psixbot)

## Countries

These _countries_ are directly (e.g. origin of attacks) or indirectly (e.g. access by proxy) associated with PsiXBot:

* [US](https://vuldb.com/?country.us)
* [GB](https://vuldb.com/?country.gb)
* [CN](https://vuldb.com/?country.cn)
* ...

There are 10 more country items available. Please use our online service to access the data.

## IOC - Indicator of Compromise

These _indicators of compromise_ (IOC) indicate associated network resources which are known to be part of research and attack activities of PsiXBot.

ID | IP address | Hostname | Campaign | Confidence
-- | ---------- | -------- | -------- | ----------
1 | [2.15.835.1](https://vuldb.com/?ip.2.15.835.1) | - | - | High
2 | [5.135.183.146](https://vuldb.com/?ip.5.135.183.146) | freya.stelas.de | - | High
3 | [5.154.191.67](https://vuldb.com/?ip.5.154.191.67) | - | - | High
4 | [14.42.81.85](https://vuldb.com/?ip.14.42.81.85) | - | - | High
5 | [31.3.135.232](https://vuldb.com/?ip.31.3.135.232) | mirror.tillo.ch | - | High
6 | [31.148.220.69](https://vuldb.com/?ip.31.148.220.69) | - | - | High
7 | [31.171.251.118](https://vuldb.com/?ip.31.171.251.118) | ch.ns.mon0.li | - | High
8 | [37.44.212.194](https://vuldb.com/?ip.37.44.212.194) | - | - | High
9 | [37.44.213.26](https://vuldb.com/?ip.37.44.213.26) | - | - | High
10 | [37.44.213.27](https://vuldb.com/?ip.37.44.213.27) | - | - | High
11 | [37.44.213.98](https://vuldb.com/?ip.37.44.213.98) | - | - | High
12 | [37.44.213.187](https://vuldb.com/?ip.37.44.213.187) | - | - | High
13 | [37.44.213.188](https://vuldb.com/?ip.37.44.213.188) | - | - | High
14 | [37.44.213.189](https://vuldb.com/?ip.37.44.213.189) | - | - | High
15 | ... | ... | ... | ...

There are 55 more IOC items available. Please use our online service to access the data.

## TTP - Tactics, Techniques, Procedures

_Tactics, techniques, and procedures_ (TTP) summarize the suspected MITRE ATT&CK techniques used by _PsiXBot_. This data is unique as it uses our predictive model for actor profiling.

ID | Technique | Weakness | Description | Confidence
-- | --------- | -------- | ----------- | ----------
1 | T1006 | CWE-21, CWE-22, CWE-23, CWE-24, CWE-425 | Path Traversal | High
2 | T1040 | CWE-294 | Authentication Bypass by Capture-replay | High
3 | T1055 | CWE-74, CWE-643 | Improper Neutralization of Data within XPath Expressions | High
4 | T1059 | CWE-88, CWE-94, CWE-1321 | Argument Injection | High
5 | T1059.007 | CWE-79, CWE-80 | Cross Site Scripting | High
6 | ... | ... | ... | ...

There are 21 more TTP items available. Please use our online service to access the data.

## IOA - Indicator of Attack

These _indicators of attack_ (IOA) list the potential fragments used for technical activities like reconnaissance, exploitation, privilege escalation, and exfiltration by PsiXBot. This data is unique as it uses our predictive model for actor profiling.

ID | Type | Indicator | Confidence
-- | ---- | --------- | ----------
1 | File | `$HOME/.printers` | High
2 | File | `/abcd/opac/php/otros_sitios.php` | High
3 | File | `/admin.php?p=/Area/index#tab=t2` | High
4 | File | `/admin/?page=user/list` | High
5 | File | `/admin/action/edit_chicken.php` | High
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
18 | File | `/admin/edit-doc.php` | High
19 | File | `/admin/edit_teacher.php` | High
20 | File | `/admin/educloud/videobind.html` | High
21 | File | `/admin/employee/controller.php` | High
22 | File | `/admin/employee/index.php` | High
23 | File | `/admin/index.php` | High
24 | File | `/admin/index.php?page=categories` | High
25 | File | `/admin/index.php?page=manage_product` | High
26 | File | `/admin/ind_backstage.php` | High
27 | File | `/admin/login.php` | High
28 | File | `/admin/maintenance/view_designation.php` | High
29 | File | `/admin/pages/student-print.php` | High
30 | File | `/admin/pages/subjects.php` | High
31 | File | `/admin/return_add.php` | High
32 | File | `/admin/search.php` | High
33 | File | `/admin/service.php` | High
34 | File | `/admin/students.php` | High
35 | File | `/admin/system.html` | High
36 | File | `/admin/sys_sql_query.php` | High
37 | File | `/admin/update_s6.php` | High
38 | File | `/admin/users.php` | High
39 | File | `/admin/vacancy/index.php` | High
40 | File | `/admin/view_sendlist.php` | High
41 | File | `/adminpanel/admin/facebox_modal/updateCourse.php` | High
42 | File | `/adminpanel/admin/facebox_modal/updateExaminee.php` | High
43 | File | `/admin_ping.htm` | High
44 | File | `/adplanet/PlanetCommentList` | High
45 | File | `/ajax.php?action=read_msg` | High
46 | File | `/api/admin/store/product/list` | High
47 | File | `/api/client/editemedia.php` | High
48 | File | `/api/controllers/common/UploadsController.php` | High
49 | File | `/api/file/downloadUrl` | High
50 | File | `/api/files/recipepictures/` | High
51 | File | `/api/ping` | Medium
52 | File | `/api/plugin/uninstall` | High
53 | File | `/api/process.php` | High
54 | File | `/api /v3/auth` | High
55 | File | `/app/options.py` | High
56 | File | `/application/controller/Pengeluaran.php` | High
57 | File | `/application/index/controller/Databasesource.php` | High
58 | File | `/application/index/controller/Pay.php` | High
59 | File | `/application/index/controller/Screen.php` | High
60 | File | `/application/websocket/controller/Setting.php` | High
61 | File | `/apply/index.php` | High
62 | File | `/att_add.php` | Medium
63 | File | `/backend/register.php` | High
64 | File | `/blog` | Low
65 | File | `/blog-single.php` | High
66 | File | `/book-services.php` | High
67 | File | `/card_scan.php` | High
68 | File | `/cgi-bin/adm.cgi` | High
69 | File | `/cgi-bin/cstecgi.cgi` | High
70 | File | `/cgi-bin/jumpto.php?class=user&page=config_save&isphp=1` | High
71 | File | `/cgi-bin/koha/catalogue/search.pl` | High
72 | File | `/cgi-bin/nas_sharing.cgi` | High
73 | File | `/cgi-bin/qcmap_auth` | High
74 | File | `/cgi-bin/wlogin.cgi` | High
75 | File | `/check_availability.php` | High
76 | File | `/classes/Master.php?f=save_inquiry` | High
77 | File | `/classes/Master.php?f=save_reminder` | High
78 | File | `/classes/Users.php` | High
79 | File | `/classes/Users.php?f=save` | High
80 | File | `/collection/all` | High
81 | File | `/control/deactivate_case.php` | High
82 | File | `/cwc/login` | Medium
83 | ... | ... | ...

There are 734 more IOA items available (file, library, argument, input value, pattern, network port). Please use our online service to access the data.

## References

The following list contains _external sources_ which discuss the actor and the associated activities:

* https://github.com/fox-it/psixbot/blob/master/c2_ips.txt
* https://github.com/fox-it/psixbot/blob/master/dns_servers.txt

## Literature

The following _articles_ explain our unique predictive cyber threat intelligence:

* [VulDB Cyber Threat Intelligence Documentation](https://vuldb.com/?kb.cti)
* [Cyber Threat Intelligence - Early Anticipation of Attacks](https://www.scip.ch/en/?labs.20201022)

## License

(c) [1997-2024](https://vuldb.com/?kb.changelog) by [vuldb.com](https://vuldb.com/?kb.about). All data on this page is shared under the license [CC BY-NC-SA 4.0](https://creativecommons.org/licenses/by-nc-sa/4.0/). Questions? Check the [FAQ](https://vuldb.com/?kb.faq), read the [documentation](https://vuldb.com/?kb) or [contact us](https://vuldb.com/?contact)!
