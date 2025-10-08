# LookBack - Cyber Threat Intelligence

These _indicators_ were reported, collected, and generated during the [VulDB CTI analysis](https://vuldb.com/?kb.cti) of the campaign known as _LookBack_. The _activity monitoring_ correlates data from social media, forums, chat rooms, and darknet markets. It helps to determine associated actors, specific activities, expected intentions, emerging research, and ongoing attacks. Our unique _predictive model_ uses _big data_ to forecast activities and their characteristics.

_Live data_ and more _analysis capabilities_ are available at [https://vuldb.com/?actor](https://vuldb.com/?actor)

## Countries

These _countries_ are directly (e.g. origin of attacks) or indirectly (e.g. access by proxy) associated with LookBack:

* [CN](https://vuldb.com/?country.cn)
* [US](https://vuldb.com/?country.us)
* [VN](https://vuldb.com/?country.vn)
* ...

There are 3 more country items available. Please use our online service to access the data.

## Actors

These _actors_ are associated with LookBack or other actors linked to the campaign.

ID | Actor | Confidence
-- | ----- | ----------
1 | [Lookback](https://vuldb.com/?actor.lookback) | High
2 | [Witchetty](https://vuldb.com/?actor.witchetty) | High

## IOC - Indicator of Compromise

These _indicators of compromise_ (IOC) indicate associated network resources which are known to be part of research and attack activities of LookBack.

ID | IP address | Hostname | Actor | Confidence
-- | ---------- | -------- | ----- | ----------
1 | [5.252.176.3](https://vuldb.com/?ip.5.252.176.3) | no-rdns.mivocloud.com | [Witchetty](https://vuldb.com/?actor.witchetty) | High
2 | [79.141.168.137](https://vuldb.com/?ip.79.141.168.137) | nceess.com | [Lookback](https://vuldb.com/?actor.lookback) | High
3 | [103.253.41.45](https://vuldb.com/?ip.103.253.41.45) | mail.e-cigs-mart.com | [Lookback](https://vuldb.com/?actor.lookback) | High
4 | ... | ... | ... | ...

There are 1 more IOC items available. Please use our online service to access the data.

## TTP - Tactics, Techniques, Procedures

_Tactics, techniques, and procedures_ (TTP) summarize the suspected MITRE ATT&CK techniques used within LookBack. This data is unique as it uses our predictive model for actor profiling.

ID | Technique | Weakness | Description | Confidence
-- | --------- | -------- | ----------- | ----------
1 | T1006 | CWE-21, CWE-22, CWE-24 | Path Traversal | High
2 | T1040 | CWE-294 | Authentication Bypass by Capture-replay | High
3 | T1055 | CWE-74 | Improper Neutralization of Data within XPath Expressions | High
4 | T1059 | CWE-94, CWE-1321 | Argument Injection | High
5 | T1059.007 | CWE-79, CWE-80 | Basic Cross Site Scripting | High
6 | T1068 | CWE-264, CWE-269, CWE-284 | Execution with Unnecessary Privileges | High
7 | ... | ... | ... | ...

There are 24 more TTP items available. Please use our online service to access the data.

## IOA - Indicator of Attack

These _indicators of attack_ (IOA) list the potential fragments used for technical activities like reconnaissance, exploitation, privilege escalation, and exfiltration during LookBack. This data is unique as it uses our predictive model for actor profiling.

ID | Type | Indicator | Confidence
-- | ---- | --------- | ----------
1 | File | `/accessory/picdel.html` | High
2 | File | `/Actions.php` | Medium
3 | File | `/activation.php` | High
4 | File | `/add-phlebotomist.php` | High
5 | File | `/addcompany.php` | High
6 | File | `/adicionar-cliente.php` | High
7 | File | `/admin.php?c=upload&f=zip&_noCache=0.1683794968` | High
8 | File | `/admin/` | Low
9 | File | `/admin/?page=back_order/view_bo` | High
10 | File | `/admin/aboutus.php` | High
11 | File | `/admin/about_edit.php?action=modify` | High
12 | File | `/admin/add-services.php` | High
13 | File | `/admin/add_cars.php` | High
14 | File | `/admin/ajax.php?action=login` | High
15 | File | `/admin/all-request.php` | High
16 | File | `/admin/approve_user.php` | High
17 | File | `/admin/attachment/download` | High
18 | File | `/admin/booking_report.php` | High
19 | File | `/admin/bwdates-passreports-details.php` | High
20 | File | `/admin/candidates_add.php` | High
21 | File | `/admin/client_user` | High
22 | File | `/admin/cmsTagType/save` | High
23 | File | `/admin/course_action.php` | High
24 | File | `/admin/disapprove_user.php` | High
25 | File | `/admin/edit-doctor.php` | High
26 | File | `/admin/edit-services.php` | High
27 | File | `/admin/edit-vehicle.php` | High
28 | File | `/admin/editempeducation.php` | High
29 | File | `/admin/editorder.php` | High
30 | File | `/admin/email_setup.php` | High
31 | File | `/admin/expense_report.php` | High
32 | File | `/admin/getallarticleinfo` | High
33 | File | `/admin/manage-foreigners-ticket.php` | High
34 | File | `/Admin/match.php` | High
35 | File | `/admin/model/addOrUpdate` | High
36 | File | `/admin/network/ajax_getChannelList` | High
37 | File | `/admin/network/diag_iperf` | High
38 | File | `/admin/network/diag_nslookup` | High
39 | File | `/admin/newsletter.php` | High
40 | File | `/admin/operations/currency.php` | High
41 | File | `/admin/operations/expense_category.php` | High
42 | File | `/admin/operations/tax.php` | High
43 | File | `/admin/options/update` | High
44 | File | `/admin/page-login.php` | High
45 | File | `/admin/pages/update_go.php` | High
46 | File | `/admin/profile.php` | High
47 | File | `/admin/request-received-bydonar.php` | High
48 | File | `/admin/search-directory.php` | High
49 | File | `/admin/search-invoices.php` | High
50 | File | `/admin/tags/save` | High
51 | File | `/admin/update_s1.php` | High
52 | File | `/admin/update_s8.php` | High
53 | File | `/admin/update_user.php` | High
54 | File | `/admin/user/list` | High
55 | File | `/adminPage/main/upload` | High
56 | File | `/admin_system/api.php` | High
57 | File | `/adms/admin/?page=vehicles/view_transaction` | High
58 | File | `/adphar.php` | Medium
59 | File | `/alunos/search_autocomplete` | High
60 | File | `/api/admin/system/store/order/list` | High
61 | File | `/api/dept/build` | High
62 | File | `/api/request-token` | High
63 | File | `/api/role` | Medium
64 | File | `/api/upload` | Medium
65 | File | `/api/user` | Medium
66 | File | `/apply/index.php` | High
67 | File | `/apps/api/views/deploy_api.py` | High
68 | File | `/App_Resource/UEditor/server/upload.aspx` | High
69 | File | `/auth/list_projects` | High
70 | File | `/backend/register.php` | High
71 | File | `/backups/` | Medium
72 | File | `/bank/statements.php` | High
73 | File | `/bin/main` | Medium
74 | File | `/blog/comment` | High
75 | File | `/boafrm/formMapDel` | High
76 | File | `/boafrm/formTmultiAP` | High
77 | File | `/boat/login.php` | High
78 | File | `/booking/show_bookings/` | High
79 | File | `/bookingconfirm.php` | High
80 | File | `/browsemdcn.php` | High
81 | File | `/bwdates-report-result.php` | High
82 | File | `/cart/index.php` | High
83 | File | `/categoryvalue.php` | High
84 | File | `/cgi-bin/cstecgi.cgi` | High
85 | File | `/cgi-bin/hd_config.cgi` | High
86 | File | `/cgi-bin/luci/admin/opsw/Dual_freq_un_apple` | High
87 | File | `/cgi-bin/nas_sharing.cgi` | High
88 | File | `/cgi-bin/nightled.cgi` | High
89 | File | `/check_availability.php` | High
90 | File | `/classes/Master.php?f=save_inquiry` | High
91 | File | `/classes/Master.php?f=save_sub_category` | High
92 | File | `/collect/getArticle` | High
93 | File | `/commons/attachment/upload` | High
94 | File | `/config` | Low
95 | File | `/contactus1.php` | High
96 | File | `/controllers/postpublish.php` | High
97 | File | `/controllers/regcontrol.php` | High
98 | File | `/core/config-revisions` | High
99 | File | `/crm/data/pdf.php` | High
100 | File | `/cussignup.php` | High
101 | ... | ... | ...

There are 891 more IOA items available (file, library, argument, input value, pattern, network port). Please use our online service to access the data.

## References

The following list contains _external sources_ which discuss the campaign and the associated activities:

* https://symantec-enterprise-blogs.security.com/blogs/threat-intelligence/witchetty-steganography-espionage
* https://www.proofpoint.com/us/threat-insight/post/lookback-malware-targets-united-states-utilities-sector-phishing-attacks

## Literature

The following _articles_ explain our unique predictive cyber threat intelligence:

* [VulDB Cyber Threat Intelligence Documentation](https://vuldb.com/?kb.cti)
* [Cyber Threat Intelligence - Early Anticipation of Attacks](https://www.scip.ch/en/?labs.20201022)

## License

(c) [1997-2025](https://vuldb.com/?kb.changelog) by [vuldb.com](https://vuldb.com/?kb.about). All data on this page is shared under the license [CC BY-NC-SA 4.0](https://creativecommons.org/licenses/by-nc-sa/4.0/). Questions? Check the [FAQ](https://vuldb.com/?kb.faq), read the [documentation](https://vuldb.com/?kb) or [contact us](https://vuldb.com/?contact)!
