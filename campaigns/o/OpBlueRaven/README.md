# OpBlueRaven - Cyber Threat Intelligence

These _indicators_ were reported, collected, and generated during the [VulDB CTI analysis](https://vuldb.com/?kb.cti) of the campaign known as _OpBlueRaven_. The _activity monitoring_ correlates data from social media, forums, chat rooms, and darknet markets. It helps to determine associated actors, specific activities, expected intentions, emerging research, and ongoing attacks. Our unique _predictive model_ uses _big data_ to forecast activities and their characteristics.

_Live data_ and more _analysis capabilities_ are available at [https://vuldb.com/?actor](https://vuldb.com/?actor)

## Countries

These _countries_ are directly (e.g. origin of attacks) or indirectly (e.g. access by proxy) associated with OpBlueRaven:

* [CN](https://vuldb.com/?country.cn)
* [US](https://vuldb.com/?country.us)
* [RU](https://vuldb.com/?country.ru)
* ...

There are 7 more country items available. Please use our online service to access the data.

## Actors

These _actors_ are associated with OpBlueRaven or other actors linked to the campaign.

ID | Actor | Confidence
-- | ----- | ----------
1 | [FIN7](https://vuldb.com/?actor.fin7) | High

## IOC - Indicator of Compromise

These _indicators of compromise_ (IOC) indicate associated network resources which are known to be part of research and attack activities of OpBlueRaven.

ID | IP address | Hostname | Actor | Confidence
-- | ---------- | -------- | ----- | ----------
1 | [5.252.177.23](https://vuldb.com/?ip.5.252.177.23) | 5-252-177-23.mivocloud.com | [FIN7](https://vuldb.com/?actor.fin7) | High
2 | [5.252.177.37](https://vuldb.com/?ip.5.252.177.37) | no-rdns.mivocloud.com | [FIN7](https://vuldb.com/?actor.fin7) | High
3 | [23.83.133.119](https://vuldb.com/?ip.23.83.133.119) | - | [FIN7](https://vuldb.com/?actor.fin7) | High
4 | [37.1.211.239](https://vuldb.com/?ip.37.1.211.239) | ourdrops.org | [FIN7](https://vuldb.com/?actor.fin7) | High
5 | [37.1.215.4](https://vuldb.com/?ip.37.1.215.4) | - | [FIN7](https://vuldb.com/?actor.fin7) | High
6 | [37.1.215.72](https://vuldb.com/?ip.37.1.215.72) | - | [FIN7](https://vuldb.com/?actor.fin7) | High
7 | [37.252.4.131](https://vuldb.com/?ip.37.252.4.131) | - | [FIN7](https://vuldb.com/?actor.fin7) | High
8 | [45.77.60.230](https://vuldb.com/?ip.45.77.60.230) | 45.77.60.230.vultr.com | [FIN7](https://vuldb.com/?actor.fin7) | Medium
9 | [45.77.204.130](https://vuldb.com/?ip.45.77.204.130) | 45.77.204.130.vultr.com | [FIN7](https://vuldb.com/?actor.fin7) | Medium
10 | [45.87.152.64](https://vuldb.com/?ip.45.87.152.64) | free.pq.hosting | [FIN7](https://vuldb.com/?actor.fin7) | High
11 | [45.133.216.25](https://vuldb.com/?ip.45.133.216.25) | lisulisimp.example.com | [FIN7](https://vuldb.com/?actor.fin7) | High
12 | ... | ... | ... | ...

There are 44 more IOC items available. Please use our online service to access the data.

## TTP - Tactics, Techniques, Procedures

_Tactics, techniques, and procedures_ (TTP) summarize the suspected MITRE ATT&CK techniques used within OpBlueRaven. This data is unique as it uses our predictive model for actor profiling.

ID | Technique | Weakness | Description | Confidence
-- | --------- | -------- | ----------- | ----------
1 | T1006 | CWE-21, CWE-22, CWE-23, CWE-37, CWE-44 | Path Traversal | High
2 | T1055 | CWE-74 | Improper Neutralization of Data within XPath Expressions | High
3 | T1059 | CWE-88, CWE-94, CWE-1321 | Argument Injection | High
4 | T1059.007 | CWE-79, CWE-80 | Basic Cross Site Scripting | High
5 | T1068 | CWE-250, CWE-264, CWE-269, CWE-271, CWE-284 | Execution with Unnecessary Privileges | High
6 | T1078.001 | CWE-259 | Use of Hard-coded Password | High
7 | ... | ... | ... | ...

There are 24 more TTP items available. Please use our online service to access the data.

## IOA - Indicator of Attack

These _indicators of attack_ (IOA) list the potential fragments used for technical activities like reconnaissance, exploitation, privilege escalation, and exfiltration during OpBlueRaven. This data is unique as it uses our predictive model for actor profiling.

ID | Type | Indicator | Confidence
-- | ---- | --------- | ----------
1 | File | `.travis.yml` | Medium
2 | File | `/Actions.php` | Medium
3 | File | `/actuator` | Medium
4 | File | `/adaddmed.php` | High
5 | File | `/addCatController.php` | High
6 | File | `/addcategory.php` | High
7 | File | `/addcompany.php` | High
8 | File | `/addelidetails.php` | High
9 | File | `/addelivery.php` | High
10 | File | `/add_achievement_details.php` | High
11 | File | `/adfs/ls` | Medium
12 | File | `/admin#article/edit?id=2` | High
13 | File | `/admin#themes` | High
14 | File | `/admin-inbox.php` | High
15 | File | `/admin.php?c=upload&f=zip&_noCache=0.1683794968` | High
16 | File | `/admin.php?p=/Area/index#tab=t2` | High
17 | File | `/admin/add-boat.php` | High
18 | File | `/admin/add-customer-services.php` | High
19 | File | `/admin/add_query_account.php` | High
20 | File | `/admin/admin_action.php` | High
21 | File | `/admin/ajax.php?action=login` | High
22 | File | `/admin/ajax.php?action=save_user` | High
23 | File | `/admin/approve_user.php` | High
24 | File | `/admin/borrow_add.php` | High
25 | File | `/admin/doctor-specilization.php` | High
26 | File | `/admin/email_setup.php` | High
27 | File | `/admin/index.php` | High
28 | File | `/admin/insert-product.php` | High
29 | File | `/admin/login.php` | High
30 | File | `/admin/network/diag_iperf` | High
31 | File | `/admin/network/diag_nslookup` | High
32 | File | `/admin/new-content` | High
33 | File | `/admin/operations/booking.php` | High
34 | File | `/admin/operations/currency.php` | High
35 | File | `/admin/operations/expense.php` | High
36 | File | `/admin/operations/payment.php` | High
37 | File | `/admin/operations/travellers.php` | High
38 | File | `/admin/page-login.php` | High
39 | File | `/admin/password-recovery.php` | High
40 | File | `/admin/profile.php` | High
41 | File | `/admin/regester.php` | High
42 | File | `/Admin/registration.php` | High
43 | File | `/admin/search-directory.php` | High
44 | File | `/admin/search-maid.php` | High
45 | File | `/admin/search-vehicle.php` | High
46 | File | `/admin/search.php` | High
47 | File | `/admin/session.php` | High
48 | File | `/admin/sms_setting.php` | High
49 | File | `/admin/system/dict/add.json?sqlid=system.dict.save` | High
50 | File | `/admin/tag/save` | High
51 | File | `/admin/topic/list` | High
52 | File | `/admin/twitter.php` | High
53 | File | `/admin/user-search.php` | High
54 | File | `/admin/view-appointment.php` | High
55 | File | `/admin/voters_add.php` | High
56 | File | `/admin/voters_delete.php` | High
57 | File | `/ajax.php?action=save_package` | High
58 | File | `/api/authentication/login` | High
59 | File | `/api/dept` | Medium
60 | File | `/api/role` | Medium
61 | File | `/api/user` | Medium
62 | File | `/api/v1/settings` | High
63 | File | `/api/v1/toolbox/device/update/swap` | High
64 | File | `/api/wechat/app_auth` | High
65 | File | `/app/zentao/module/repo/model.php` | High
66 | File | `/application/controller/Pengeluaran.php` | High
67 | File | `/authentication/logout.php` | High
68 | File | `/backend/admin/his_admin_register_patient.php` | High
69 | File | `/backend/register.php` | High
70 | File | `/bank/statements.php` | High
71 | File | `/bank/transfer.php` | High
72 | File | `/bin/httpd` | Medium
73 | File | `/book-appointment.php` | High
74 | File | `/book_car.php` | High
75 | File | `/browsemdcn.php` | High
76 | File | `/bwdates-report-result.php` | High
77 | File | `/cardo/api` | Medium
78 | File | `/cart_add.php` | High
79 | File | `/cgi-bin/cstecgi.cgi` | High
80 | File | `/cgi-bin/koha/opac-MARCdetail.pl` | High
81 | File | `/cgi-bin/nas_sharing.cgi` | High
82 | File | `/cgi-bin/wlogin.cgi` | High
83 | File | `/check_availability.php` | High
84 | File | `/clients` | Medium
85 | File | `/cloudstore/ecode/setup/ecology_dev.zip` | High
86 | File | `/com/esafenet/servlet/policy/HookService.java` | High
87 | File | `/controllers/postpublish.php` | High
88 | File | `/core/config-revisions` | High
89 | ... | ... | ...

There are 788 more IOA items available (file, library, argument, input value, pattern, network port). Please use our online service to access the data.

## References

The following list contains _external sources_ which discuss the campaign and the associated activities:

* https://github.com/prodaft/malware-ioc/tree/master/OpBlueRaven

## Literature

The following _articles_ explain our unique predictive cyber threat intelligence:

* [VulDB Cyber Threat Intelligence Documentation](https://vuldb.com/?kb.cti)
* [Cyber Threat Intelligence - Early Anticipation of Attacks](https://www.scip.ch/en/?labs.20201022)

## License

(c) [1997-2025](https://vuldb.com/?kb.changelog) by [vuldb.com](https://vuldb.com/?kb.about). All data on this page is shared under the license [CC BY-NC-SA 4.0](https://creativecommons.org/licenses/by-nc-sa/4.0/). Questions? Check the [FAQ](https://vuldb.com/?kb.faq), read the [documentation](https://vuldb.com/?kb) or [contact us](https://vuldb.com/?contact)!
