# MuddyWater - Cyber Threat Intelligence

These _indicators_ were reported, collected, and generated during the [VulDB CTI analysis](https://vuldb.com/?kb.cti) of the actor known as [MuddyWater](https://vuldb.com/?actor.muddywater). The _activity monitoring_ correlates data from social media, forums, chat rooms, and darknet markets. It helps to determine associated actors, specific activities, expected intentions, emerging research, and ongoing attacks. Our unique _predictive model_ uses _big data_ to forecast activities and their characteristics.

_Live data_ and more _analysis capabilities_ are available at [https://vuldb.com/?actor.muddywater](https://vuldb.com/?actor.muddywater)

## Campaigns

The following _campaigns_ are known and can be associated with MuddyWater:

* BlackWater
* Ligolo
* Log4j
* ...

There are 2 more campaign items available. Please use our online service to access the data.

## Countries

These _countries_ are directly (e.g. origin of attacks) or indirectly (e.g. access by proxy) associated with MuddyWater:

* [US](https://vuldb.com/?country.us)
* [JP](https://vuldb.com/?country.jp)
* [ES](https://vuldb.com/?country.es)
* ...

There are 26 more country items available. Please use our online service to access the data.

## IOC - Indicator of Compromise

These _indicators of compromise_ (IOC) indicate associated network resources which are known to be part of research and attack activities of MuddyWater.

ID | IP address | Hostname | Campaign | Confidence
-- | ---------- | -------- | -------- | ----------
1 | [1.5.1.1](https://vuldb.com/?ip.1.5.1.1) | - | - | High
2 | [5.9.0.155](https://vuldb.com/?ip.5.9.0.155) | static.155.0.9.5.clients.your-server.de | - | High
3 | [5.199.133.149](https://vuldb.com/?ip.5.199.133.149) | ve958.venus.servdiscount-customer.com | - | High
4 | [7.236.212.22](https://vuldb.com/?ip.7.236.212.22) | - | - | High
5 | [31.171.154.67](https://vuldb.com/?ip.31.171.154.67) | - | Seedworm | High
6 | [38.132.99.167](https://vuldb.com/?ip.38.132.99.167) | - | BlackWater | High
7 | [45.142.212.61](https://vuldb.com/?ip.45.142.212.61) | vm218389.pq.hosting | - | High
8 | [45.142.213.17](https://vuldb.com/?ip.45.142.213.17) | vm218393.pq.hosting | - | High
9 | [45.153.231.104](https://vuldb.com/?ip.45.153.231.104) | vm218397.pq.hosting | - | High
10 | [46.99.148.96](https://vuldb.com/?ip.46.99.148.96) | - | Seedworm | High
11 | [46.166.129.159](https://vuldb.com/?ip.46.166.129.159) | gcn.warrirge.com | - | High
12 | [51.77.97.65](https://vuldb.com/?ip.51.77.97.65) | ip65.ip-51-77-97.eu | - | High
13 | [66.219.22.235](https://vuldb.com/?ip.66.219.22.235) | core96.hostingmadeeasy.com | - | High
14 | [78.129.139.131](https://vuldb.com/?ip.78.129.139.131) | - | - | High
15 | [78.129.139.134](https://vuldb.com/?ip.78.129.139.134) | der134.creditloanlenders.com | - | High
16 | [78.129.139.147](https://vuldb.com/?ip.78.129.139.147) | - | - | High
17 | [78.129.139.148](https://vuldb.com/?ip.78.129.139.148) | - | Seedworm | High
18 | ... | ... | ... | ...

There are 66 more IOC items available. Please use our online service to access the data.

## TTP - Tactics, Techniques, Procedures

_Tactics, techniques, and procedures_ (TTP) summarize the suspected MITRE ATT&CK techniques used by _MuddyWater_. This data is unique as it uses our predictive model for actor profiling.

ID | Technique | Weakness | Description | Confidence
-- | --------- | -------- | ----------- | ----------
1 | T1006 | CWE-22, CWE-23, CWE-24, CWE-28, CWE-29, CWE-425 | Pathname Traversal | High
2 | T1040 | CWE-294, CWE-319 | Authentication Bypass by Capture-replay | High
3 | T1055 | CWE-74 | Injection | High
4 | T1059 | CWE-88, CWE-94, CWE-1321 | Cross Site Scripting | High
5 | T1059.007 | CWE-79, CWE-80 | Cross Site Scripting | High
6 | ... | ... | ... | ...

There are 21 more TTP items available. Please use our online service to access the data.

## IOA - Indicator of Attack

These _indicators of attack_ (IOA) list the potential fragments used for technical activities like reconnaissance, exploitation, privilege escalation, and exfiltration by MuddyWater. This data is unique as it uses our predictive model for actor profiling.

ID | Type | Indicator | Confidence
-- | ---- | --------- | ----------
1 | File | `/?p=products` | Medium
2 | File | `/admin.php/appcenter/local.html?type=addon` | High
3 | File | `/admin/?page=product/manage_product&id=2` | High
4 | File | `/admin/?page=reminders/view_reminder` | High
5 | File | `/admin/?page=user` | High
6 | File | `/admin/assign/assign.php` | High
7 | File | `/admin/attendance_row.php` | High
8 | File | `/admin/ballot_down.php` | High
9 | File | `/admin/ballot_up.php` | High
10 | File | `/admin/bookings/view_booking.php` | High
11 | File | `/admin/candidates_row.php` | High
12 | File | `/admin/casedetails.php` | High
13 | File | `/admin/cashadvance_row.php` | High
14 | File | `/admin/categories/view_category.php` | High
15 | File | `/admin/curriculum/view_curriculum.php` | High
16 | File | `/admin/deduction_row.php` | High
17 | File | `/admin/departments/view_department.php` | High
18 | File | `/admin/employee_add.php` | High
19 | File | `/admin/employee_edit.php` | High
20 | File | `/admin/employee_row.php` | High
21 | File | `/admin/fields/manage_field.php` | High
22 | File | `/admin/forgot-password.php` | High
23 | File | `/admin/getallarticleinfo` | High
24 | File | `/admin/index.php` | High
25 | File | `/admin/info_deal.php` | High
26 | File | `/admin/inquiries/view_inquiry.php` | High
27 | File | `/admin/login.php` | High
28 | File | `/admin/maintenance/brand.php` | High
29 | File | `/admin/maintenance/manage_category.php` | High
30 | File | `/admin/misc/script-proxy` | High
31 | File | `/admin/offenses/view_details.php` | High
32 | File | `/admin/orders/update_status.php` | High
33 | File | `/admin/positions_add.php` | High
34 | File | `/admin/positions_delete.php` | High
35 | File | `/admin/positions_row.php` | High
36 | File | `/admin/product/manage.php` | High
37 | File | `/admin/products/index.php` | High
38 | File | `/admin/products/manage_product.php` | High
39 | File | `/admin/reports/index.php` | High
40 | File | `/admin/robot/approval/list` | High
41 | File | `/admin/sales/index.php` | High
42 | File | `/admin/sales/view_details.php` | High
43 | File | `/admin/services/manage_service.php` | High
44 | File | `/admin/transactions/track_shipment.php` | High
45 | File | `/admin/user/manage_user.php` | High
46 | File | `/admin/voters_row.php` | High
47 | File | `/alphaware/details.php` | High
48 | File | `/analysisProject/pagingQueryData` | High
49 | File | `/api/admin/store/product/list` | High
50 | File | `/batm/app/admin/standalone/deployments` | High
51 | File | `/bilal final/edit_stud.php` | High
52 | File | `/bilal final/login.php` | High
53 | File | `/category/list?limit=10&offset=0&order=desc` | High
54 | File | `/cgi-bin/downloadFile.cgi` | High
55 | ... | ... | ...

There are 484 more IOA items available (file, library, argument, input value, pattern, network port). Please use our online service to access the data.

## References

The following list contains _external sources_ which discuss the actor and the associated activities:

* https://blog.talosintelligence.com/2019/05/recent-muddywater-associated-blackwater.html
* https://blog.talosintelligence.com/2022/01/iranian-apt-muddywater-targets-turkey.html
* https://blog.talosintelligence.com/2022/03/iranian-supergroup-muddywater.html
* https://github.com/blackorbird/APT_REPORT/blob/master/muddywater/wp_new_muddywater_findings_uncovered.pdf
* https://reaqta.com/2017/11/muddywater-apt-targeting-middle-east/
* https://securelist.com/muddywater/88059/
* https://symantec-enterprise-blogs.security.com/blogs/threat-intelligence/seedworm-espionage-group
* https://twitter.com/ShadowChasing1/status/1481621068255137794
* https://unit42.paloaltonetworks.com/unit42-muddying-the-water-targeted-attacks-in-the-middle-east/
* https://www.cisa.gov/uscert/ncas/alerts/aa22-055a
* https://www.clearskysec.com/wp-content/uploads/2019/06/Clearsky-Iranian-APT-group-%E2%80%98MuddyWater%E2%80%99-Adds-Exploits-to-Their-Arsenal.pdf
* https://www.mandiant.com/resources/telegram-malware-iranian-espionage
* https://www.microsoft.com/security/blog/2022/08/25/mercury-leveraging-log4j-2-vulnerabilities-in-unpatched-systems-to-target-israeli-organizations/
* https://www.threatminer.org/_reports/2019/TheMuddyWatersofAPTAttacks-CheckPointResearch.pdf#viewer.action=download

## Literature

The following _articles_ explain our unique predictive cyber threat intelligence:

* [VulDB Cyber Threat Intelligence Documentation](https://vuldb.com/?kb.cti)
* [Cyber Threat Intelligence - Early Anticipation of Attacks](https://www.scip.ch/en/?labs.20201022)

## License

(c) [1997-2023](https://vuldb.com/?kb.changelog) by [vuldb.com](https://vuldb.com/?kb.about). All data on this page is shared under the license [CC BY-NC-SA 4.0](https://creativecommons.org/licenses/by-nc-sa/4.0/). Questions? Check the [FAQ](https://vuldb.com/?kb.faq), read the [documentation](https://vuldb.com/?kb) or [contact us](https://vuldb.com/?contact)!
