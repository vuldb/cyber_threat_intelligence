# RansomHub - Cyber Threat Intelligence

These _indicators_ were reported, collected, and generated during the [VulDB CTI analysis](https://vuldb.com/?kb.cti) of the campaign known as _RansomHub_. The _activity monitoring_ correlates data from social media, forums, chat rooms, and darknet markets. It helps to determine associated actors, specific activities, expected intentions, emerging research, and ongoing attacks. Our unique _predictive model_ uses _big data_ to forecast activities and their characteristics.

_Live data_ and more _analysis capabilities_ are available at [https://vuldb.com/?actor](https://vuldb.com/?actor)

## Countries

These _countries_ are directly (e.g. origin of attacks) or indirectly (e.g. access by proxy) associated with RansomHub:

* [CN](https://vuldb.com/?country.cn)
* [US](https://vuldb.com/?country.us)
* [RU](https://vuldb.com/?country.ru)
* ...

There are 3 more country items available. Please use our online service to access the data.

## Actors

These _actors_ are associated with RansomHub or other actors linked to the campaign.

ID | Actor | Confidence
-- | ----- | ----------
1 | [RansomHub](https://vuldb.com/?actor.ransomhub) | High
2 | [Scattered Spider](https://vuldb.com/?actor.scattered_spider) | High
3 | [ShadowSyndicate](https://vuldb.com/?actor.shadowsyndicate) | High

## IOC - Indicator of Compromise

These _indicators of compromise_ (IOC) indicate associated network resources which are known to be part of research and attack activities of RansomHub.

ID | IP address | Hostname | Actor | Confidence
-- | ---------- | -------- | ----- | ----------
1 | [5.8.63.178](https://vuldb.com/?ip.5.8.63.178) | 5-8-63-178.static.x5x.tech | [RansomHub](https://vuldb.com/?actor.ransomhub) | High
2 | [5.181.86.158](https://vuldb.com/?ip.5.181.86.158) | - | [RansomHub](https://vuldb.com/?actor.ransomhub) | High
3 | [8.211.2.97](https://vuldb.com/?ip.8.211.2.97) | - | [RansomHub](https://vuldb.com/?actor.ransomhub) | High
4 | [20.37.139.187](https://vuldb.com/?ip.20.37.139.187) | - | [Scattered Spider](https://vuldb.com/?actor.scattered_spider) | High
5 | [23.92.31.138](https://vuldb.com/?ip.23.92.31.138) | 23-92-31-138.ip.linodeusercontent.com | [RansomHub](https://vuldb.com/?actor.ransomhub) | High
6 | [23.227.193.172](https://vuldb.com/?ip.23.227.193.172) | 23-227-193-172.static.hvvc.us | [RansomHub](https://vuldb.com/?actor.ransomhub) | High
7 | [31.216.148.33](https://vuldb.com/?ip.31.216.148.33) | 31-216-148-33.ip.dclux.com | [ShadowSyndicate](https://vuldb.com/?actor.shadowsyndicate) | High
8 | [37.1.212.18](https://vuldb.com/?ip.37.1.212.18) | - | [RansomHub](https://vuldb.com/?actor.ransomhub) | High
9 | [37.120.143.202](https://vuldb.com/?ip.37.120.143.202) | - | [RansomHub](https://vuldb.com/?actor.ransomhub) | High
10 | [38.146.28.93](https://vuldb.com/?ip.38.146.28.93) | - | [RansomHub](https://vuldb.com/?actor.ransomhub) | High
11 | [38.180.81.153](https://vuldb.com/?ip.38.180.81.153) | - | [RansomHub](https://vuldb.com/?actor.ransomhub) | High
12 | [38.180.139.56](https://vuldb.com/?ip.38.180.139.56) | - | [RansomHub](https://vuldb.com/?actor.ransomhub) | High
13 | ... | ... | ... | ...

There are 46 more IOC items available. Please use our online service to access the data.

## TTP - Tactics, Techniques, Procedures

_Tactics, techniques, and procedures_ (TTP) summarize the suspected MITRE ATT&CK techniques used within RansomHub. This data is unique as it uses our predictive model for actor profiling.

ID | Technique | Weakness | Description | Confidence
-- | --------- | -------- | ----------- | ----------
1 | T1006 | CWE-21, CWE-22, CWE-23, CWE-44 | Path Traversal | High
2 | T1055 | CWE-74 | Improper Neutralization of Data within XPath Expressions | High
3 | T1059 | CWE-88, CWE-94, CWE-1321 | Argument Injection | High
4 | T1059.007 | CWE-79, CWE-80 | Basic Cross Site Scripting | High
5 | T1068 | CWE-250, CWE-264, CWE-269, CWE-284 | Execution with Unnecessary Privileges | High
6 | T1078.001 | CWE-259 | Use of Hard-coded Password | High
7 | ... | ... | ... | ...

There are 24 more TTP items available. Please use our online service to access the data.

## IOA - Indicator of Attack

These _indicators of attack_ (IOA) list the potential fragments used for technical activities like reconnaissance, exploitation, privilege escalation, and exfiltration during RansomHub. This data is unique as it uses our predictive model for actor profiling.

ID | Type | Indicator | Confidence
-- | ---- | --------- | ----------
1 | File | `.travis.yml` | Medium
2 | File | `/Actions.php` | Medium
3 | File | `/actuator` | Medium
4 | File | `/adaddmed.php` | High
5 | File | `/add-category.php` | High
6 | File | `/addCatController.php` | High
7 | File | `/addcategory.php` | High
8 | File | `/addcompany.php` | High
9 | File | `/addelidetails.php` | High
10 | File | `/addelivery.php` | High
11 | File | `/add_achievement_details.php` | High
12 | File | `/adfs/ls` | Medium
13 | File | `/admin#article/edit?id=2` | High
14 | File | `/admin#themes` | High
15 | File | `/admin-inbox.php` | High
16 | File | `/admin.php?c=upload&f=zip&_noCache=0.1683794968` | High
17 | File | `/admin.php?p=/Area/index#tab=t2` | High
18 | File | `/admin/aboutus.php` | High
19 | File | `/admin/add-boat.php` | High
20 | File | `/admin/add-customer-services.php` | High
21 | File | `/admin/add_query_account.php` | High
22 | File | `/admin/add_student.php` | High
23 | File | `/admin/admin_action.php` | High
24 | File | `/admin/ajax.php?action=login` | High
25 | File | `/admin/ajax.php?action=save_user` | High
26 | File | `/admin/approve_user.php` | High
27 | File | `/admin/borrow_add.php` | High
28 | File | `/admin/doctor-specilization.php` | High
29 | File | `/admin/email_setup.php` | High
30 | File | `/admin/index.php` | High
31 | File | `/admin/insert-product.php` | High
32 | File | `/admin/login.php` | High
33 | File | `/admin/manage-pages.php` | High
34 | File | `/admin/network/diag_iperf` | High
35 | File | `/admin/network/diag_nslookup` | High
36 | File | `/admin/new-content` | High
37 | File | `/admin/operations/booking.php` | High
38 | File | `/admin/operations/currency.php` | High
39 | File | `/admin/operations/expense.php` | High
40 | File | `/admin/operations/payment.php` | High
41 | File | `/admin/operations/travellers.php` | High
42 | File | `/admin/page-login.php` | High
43 | File | `/admin/password-recovery.php` | High
44 | File | `/admin/profile.php` | High
45 | File | `/admin/regester.php` | High
46 | File | `/Admin/registration.php` | High
47 | File | `/admin/search-maid.php` | High
48 | File | `/admin/search-vehicle.php` | High
49 | File | `/admin/search.php` | High
50 | File | `/admin/sms_setting.php` | High
51 | File | `/admin/system/dict/add.json?sqlid=system.dict.save` | High
52 | File | `/admin/topic/list` | High
53 | File | `/admin/twitter.php` | High
54 | File | `/admin/user-search.php` | High
55 | File | `/admin/view-appointment.php` | High
56 | File | `/admin/voters_add.php` | High
57 | File | `/admin/voters_delete.php` | High
58 | File | `/ajax.php?action=save_package` | High
59 | File | `/api/authentication/login` | High
60 | File | `/api/dept` | Medium
61 | File | `/api/role` | Medium
62 | File | `/api/user` | Medium
63 | File | `/api/v1/settings` | High
64 | File | `/api/v1/toolbox/device/update/swap` | High
65 | File | `/api/wechat/app_auth` | High
66 | File | `/app/zentao/module/repo/model.php` | High
67 | File | `/application/controller/Pengeluaran.php` | High
68 | File | `/authentication/logout.php` | High
69 | File | `/backend/admin/his_admin_add_lab_equipment.php` | High
70 | File | `/backend/admin/his_admin_register_patient.php` | High
71 | File | `/backend/register.php` | High
72 | File | `/bank/statements.php` | High
73 | File | `/bank/transfer.php` | High
74 | File | `/bin/httpd` | Medium
75 | File | `/book-appointment.php` | High
76 | File | `/book_car.php` | High
77 | File | `/browsemdcn.php` | High
78 | File | `/bwdates-report-result.php` | High
79 | File | `/cardo/api` | Medium
80 | File | `/cart_add.php` | High
81 | ... | ... | ...

There are 716 more IOA items available (file, library, argument, input value, pattern, network port). Please use our online service to access the data.

## References

The following list contains _external sources_ which discuss the campaign and the associated activities:

* https://darktrace.com/blog/ransomhub-ransomware-darktraces-investigation-of-the-newest-tool-in-shadowsyndicates-arsenal
* https://darktrace.com/blog/ransomhub-revisited-new-front-runner-in-the-ransomware-as-a-service-marketplace
* https://search.censys.io/hosts/162.252.173.12
* https://search.censys.io/hosts/185.33.86.15
* https://search.censys.io/hosts/185.219.220.175
* https://search.censys.io/hosts/193.203.49.90
* https://thedfirreport.com/2025/06/30/hide-your-rdp-password-spray-leads-to-ransomhub-deployment/
* https://threatfox.abuse.ch
* https://www.cisa.gov/news-events/cybersecurity-advisories/aa24-242a
* https://www.guidepointsecurity.com/blog/ransomhub-affiliate-leverage-python-based-backdoor/
* https://www.reliaquest.com/blog/scattered-spider-x-ransomhub-a-new-partnership/
* https://www.trendmicro.com/en_us/research/24/i/how-ransomhub-ransomware-uses-edrkillshifter-to-disable-edr-and-.html

## Literature

The following _articles_ explain our unique predictive cyber threat intelligence:

* [VulDB Cyber Threat Intelligence Documentation](https://vuldb.com/?kb.cti)
* [Cyber Threat Intelligence - Early Anticipation of Attacks](https://www.scip.ch/en/?labs.20201022)

## License

(c) [1997-2025](https://vuldb.com/?kb.changelog) by [vuldb.com](https://vuldb.com/?kb.about). All data on this page is shared under the license [CC BY-NC-SA 4.0](https://creativecommons.org/licenses/by-nc-sa/4.0/). Questions? Check the [FAQ](https://vuldb.com/?kb.faq), read the [documentation](https://vuldb.com/?kb) or [contact us](https://vuldb.com/?contact)!
