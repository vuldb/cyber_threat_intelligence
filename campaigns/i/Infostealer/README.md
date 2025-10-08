# Infostealer - Cyber Threat Intelligence

These _indicators_ were reported, collected, and generated during the [VulDB CTI analysis](https://vuldb.com/?kb.cti) of the campaign known as _Infostealer_. The _activity monitoring_ correlates data from social media, forums, chat rooms, and darknet markets. It helps to determine associated actors, specific activities, expected intentions, emerging research, and ongoing attacks. Our unique _predictive model_ uses _big data_ to forecast activities and their characteristics.

_Live data_ and more _analysis capabilities_ are available at [https://vuldb.com/?actor](https://vuldb.com/?actor)

## Countries

These _countries_ are directly (e.g. origin of attacks) or indirectly (e.g. access by proxy) associated with Infostealer:

* [US](https://vuldb.com/?country.us)
* [CN](https://vuldb.com/?country.cn)
* [VN](https://vuldb.com/?country.vn)
* ...

There are 7 more country items available. Please use our online service to access the data.

## Actors

These _actors_ are associated with Infostealer or other actors linked to the campaign.

ID | Actor | Confidence
-- | ----- | ----------
1 | [Vietnam Unknown](https://vuldb.com/?actor.vietnam_unknown) | High

## IOC - Indicator of Compromise

These _indicators of compromise_ (IOC) indicate associated network resources which are known to be part of research and attack activities of Infostealer.

ID | IP address | Hostname | Actor | Confidence
-- | ---------- | -------- | ----- | ----------
1 | [5.34.178.21](https://vuldb.com/?ip.5.34.178.21) | node240816.us | [Vietnam Unknown](https://vuldb.com/?actor.vietnam_unknown) | High
2 | [5.188.87.58](https://vuldb.com/?ip.5.188.87.58) | - | [Vietnam Unknown](https://vuldb.com/?actor.vietnam_unknown) | High
3 | [46.173.215.132](https://vuldb.com/?ip.46.173.215.132) | - | [Vietnam Unknown](https://vuldb.com/?actor.vietnam_unknown) | High
4 | [66.42.63.27](https://vuldb.com/?ip.66.42.63.27) | 66.42.63.27.vultrusercontent.com | [Vietnam Unknown](https://vuldb.com/?actor.vietnam_unknown) | Medium
5 | ... | ... | ... | ...

There are 15 more IOC items available. Please use our online service to access the data.

## TTP - Tactics, Techniques, Procedures

_Tactics, techniques, and procedures_ (TTP) summarize the suspected MITRE ATT&CK techniques used within Infostealer. This data is unique as it uses our predictive model for actor profiling.

ID | Technique | Weakness | Description | Confidence
-- | --------- | -------- | ----------- | ----------
1 | T1006 | CWE-21, CWE-22, CWE-24 | Path Traversal | High
2 | T1040 | CWE-294 | Authentication Bypass by Capture-replay | High
3 | T1055 | CWE-74 | Improper Neutralization of Data within XPath Expressions | High
4 | T1059 | CWE-94, CWE-1321 | Argument Injection | High
5 | T1059.007 | CWE-79, CWE-80 | Basic Cross Site Scripting | High
6 | T1068 | CWE-264, CWE-269, CWE-284 | Execution with Unnecessary Privileges | High
7 | ... | ... | ... | ...

There are 23 more TTP items available. Please use our online service to access the data.

## IOA - Indicator of Attack

These _indicators of attack_ (IOA) list the potential fragments used for technical activities like reconnaissance, exploitation, privilege escalation, and exfiltration during Infostealer. This data is unique as it uses our predictive model for actor profiling.

ID | Type | Indicator | Confidence
-- | ---- | --------- | ----------
1 | File | `/a/sys/user/save` | High
2 | File | `/accessory/picdel.html` | High
3 | File | `/Account/login.php` | High
4 | File | `/Actions.php` | Medium
5 | File | `/add-phlebotomist.php` | High
6 | File | `/addcompany.php` | High
7 | File | `/add_members.php` | High
8 | File | `/admin.php?c=upload&f=zip&_noCache=0.1683794968` | High
9 | File | `/admin/?page=back_order/view_bo` | High
10 | File | `/admin/?page=inventory/view_inventory&id=2` | High
11 | File | `/admin/about_edit.php?action=modify` | High
12 | File | `/admin/add-services.php` | High
13 | File | `/admin/admin-profile.php` | High
14 | File | `/admin/ajax.php?action=login` | High
15 | File | `/admin/all-request.php` | High
16 | File | `/admin/app/profile_crud.php` | High
17 | File | `/admin/approve.php` | High
18 | File | `/admin/approve_user.php` | High
19 | File | `/admin/attachment/download` | High
20 | File | `/admin/booking_report.php` | High
21 | File | `/admin/book_add.php` | High
22 | File | `/admin/bwdates-passreports-details.php` | High
23 | File | `/admin/candidates_add.php` | High
24 | File | `/admin/changeimage1.php` | High
25 | File | `/admin/chip/add.do` | High
26 | File | `/admin/client_user` | High
27 | File | `/admin/course_action.php` | High
28 | File | `/admin/deleteroom.php` | High
29 | File | `/admin/disapprove_user.php` | High
30 | File | `/admin/edit-accepted-appointment.php` | High
31 | File | `/admin/edit-card-detail.php` | High
32 | File | `/admin/edit-doctor.php` | High
33 | File | `/admin/edit-vehicle.php` | High
34 | File | `/admin/editorder.php` | High
35 | File | `/admin/email_setup.php` | High
36 | File | `/admin/expense_report.php` | High
37 | File | `/admin/general-setting` | High
38 | File | `/admin/manage_seat.php` | High
39 | File | `/Admin/match.php` | High
40 | File | `/admin/model/addOrUpdate` | High
41 | File | `/admin/network/ajax_getChannelList` | High
42 | File | `/admin/network/diag_iperf` | High
43 | File | `/admin/network/diag_nslookup` | High
44 | File | `/admin/newsletter.php` | High
45 | File | `/admin/operations/currency.php` | High
46 | File | `/admin/operations/expense_category.php` | High
47 | File | `/admin/operations/tax.php` | High
48 | File | `/admin/page-login.php` | High
49 | File | `/admin/pages/update_go.php` | High
50 | File | `/admin/request-received-bydonar.php` | High
51 | File | `/admin/search-directory.php` | High
52 | File | `/admin/sou.php` | High
53 | File | `/admin/tags/save` | High
54 | File | `/admin/update_s1.php` | High
55 | File | `/admin/update_s8.php` | High
56 | File | `/admin/update_user.php` | High
57 | File | `/admin/upload/img` | High
58 | File | `/admin/view_reserved.php` | High
59 | File | `/adminPage/main/upload` | High
60 | File | `/adminpanel/admin/facebox_modal/updateExaminee.php` | High
61 | File | `/admin_system/api.php` | High
62 | File | `/adphar.php` | Medium
63 | File | `/ajax.php?action=delete_allowances` | High
64 | File | `/alunos/search_autocomplete` | High
65 | File | `/api/dept/build` | High
66 | File | `/api/process.php` | High
67 | File | `/api/request-token` | High
68 | File | `/api/role` | Medium
69 | File | `/api/user` | Medium
70 | File | `/api/v1/attack/token` | High
71 | File | `/application/index/controller/Unity.php` | High
72 | File | `/apply/index.php` | High
73 | File | `/apps/api/views/deploy_api.py` | High
74 | File | `/auth/list_projects` | High
75 | File | `/backend/doc/his_doc_update-account.php` | High
76 | File | `/backend/register.php` | High
77 | File | `/backups/` | Medium
78 | File | `/bank/statements.php` | High
79 | File | `/bin/main` | Medium
80 | File | `/blog/comment` | High
81 | File | `/boafrm/formFilter` | High
82 | File | `/boafrm/formMapDel` | High
83 | File | `/booking/show_bookings/` | High
84 | File | `/bookingconfirm.php` | High
85 | File | `/browsemdcn.php` | High
86 | File | `/bwdates-report-result.php` | High
87 | File | `/cart/index.php` | High
88 | File | `/categoryvalue.php` | High
89 | File | `/cgi-bin/cstecgi.cgi` | High
90 | File | `/cgi-bin/hd_config.cgi` | High
91 | File | `/cgi-bin/luci/admin/opsw/Dual_freq_un_apple` | High
92 | File | `/cgi-bin/nas_sharing.cgi` | High
93 | File | `/cgi-bin/nightled.cgi` | High
94 | File | `/cgi-bin/touchlist_sync.cgi` | High
95 | File | `/check_availability.php` | High
96 | File | `/classes/Master.php?f=save_inquiry` | High
97 | File | `/classes/Master.php?f=save_position` | High
98 | File | `/collect/getArticle` | High
99 | File | `/com/esafenet/servlet/document/CDGAuthoriseTempletService.java` | High
100 | File | `/common/show_image.php` | High
101 | File | `/commons/attachment/upload` | High
102 | File | `/contactus1.php` | High
103 | File | `/control/add_act.php` | High
104 | ... | ... | ...

There are 920 more IOA items available (file, library, argument, input value, pattern, network port). Please use our online service to access the data.

## References

The following list contains _external sources_ which discuss the campaign and the associated activities:

* https://labs.withsecure.com/publications/darkgate-malware-campaign

## Literature

The following _articles_ explain our unique predictive cyber threat intelligence:

* [VulDB Cyber Threat Intelligence Documentation](https://vuldb.com/?kb.cti)
* [Cyber Threat Intelligence - Early Anticipation of Attacks](https://www.scip.ch/en/?labs.20201022)

## License

(c) [1997-2025](https://vuldb.com/?kb.changelog) by [vuldb.com](https://vuldb.com/?kb.about). All data on this page is shared under the license [CC BY-NC-SA 4.0](https://creativecommons.org/licenses/by-nc-sa/4.0/). Questions? Check the [FAQ](https://vuldb.com/?kb.faq), read the [documentation](https://vuldb.com/?kb) or [contact us](https://vuldb.com/?contact)!
