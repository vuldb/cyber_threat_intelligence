# NetSupport - Cyber Threat Intelligence

These _indicators_ were reported, collected, and generated during the [VulDB CTI analysis](https://vuldb.com/?kb.cti) of the actor known as [NetSupport](https://vuldb.com/?actor.netsupport). The _activity monitoring_ correlates data from social media, forums, chat rooms, and darknet markets. It helps to determine associated actors, specific activities, expected intentions, emerging research, and ongoing attacks. Our unique _predictive model_ uses _big data_ to forecast activities and their characteristics.

_Live data_ and more _analysis capabilities_ are available at [https://vuldb.com/?actor.netsupport](https://vuldb.com/?actor.netsupport)

## Campaigns

The following _campaigns_ are known and can be associated with NetSupport:

* ClickFix

## Countries

These _countries_ are directly (e.g. origin of attacks) or indirectly (e.g. access by proxy) associated with NetSupport:

* [MY](https://vuldb.com/?country.my)
* [LA](https://vuldb.com/?country.la)
* [US](https://vuldb.com/?country.us)
* ...

There are 9 more country items available. Please use our online service to access the data.

## IOC - Indicator of Compromise

These _indicators of compromise_ (IOC) indicate associated network resources which are known to be part of research and attack activities of NetSupport.

ID | IP address | Hostname | Campaign | Confidence
-- | ---------- | -------- | -------- | ----------
1 | [5.181.156.60](https://vuldb.com/?ip.5.181.156.60) | no-rdns.mivocloud.com | - | High
2 | [5.181.159.28](https://vuldb.com/?ip.5.181.159.28) | no-rdns.mivocloud.com | - | High
3 | [5.181.159.137](https://vuldb.com/?ip.5.181.159.137) | 5-181-159-137.mivocloud.com | - | High
4 | [23.23.49.179](https://vuldb.com/?ip.23.23.49.179) | ec2-23-23-49-179.compute-1.amazonaws.com | ClickFix | Medium
5 | [50.87.146.66](https://vuldb.com/?ip.50.87.146.66) | 50-87-146-66.unifiedlayer.com | ClickFix | High
6 | [64.95.12.162](https://vuldb.com/?ip.64.95.12.162) | - | - | High
7 | [67.217.228.168](https://vuldb.com/?ip.67.217.228.168) | - | - | High
8 | [77.83.199.34](https://vuldb.com/?ip.77.83.199.34) | vo-196-he.thetimesworld.club | ClickFix | High
9 | [77.90.60.32](https://vuldb.com/?ip.77.90.60.32) | threatoff.eu | - | High
10 | [79.141.173.158](https://vuldb.com/?ip.79.141.173.158) | - | ClickFix | High
11 | ... | ... | ... | ...

There are 40 more IOC items available. Please use our online service to access the data.

## TTP - Tactics, Techniques, Procedures

_Tactics, techniques, and procedures_ (TTP) summarize the suspected MITRE ATT&CK techniques used by _NetSupport_. This data is unique as it uses our predictive model for actor profiling.

ID | Technique | Weakness | Description | Confidence
-- | --------- | -------- | ----------- | ----------
1 | T1006 | CWE-21, CWE-22, CWE-24, CWE-37 | Path Traversal | High
2 | T1040 | CWE-294 | Authentication Bypass by Capture-replay | High
3 | T1055 | CWE-74 | Improper Neutralization of Data within XPath Expressions | High
4 | T1059 | CWE-88, CWE-94, CWE-1321 | Argument Injection | High
5 | T1059.007 | CWE-79, CWE-80 | Basic Cross Site Scripting | High
6 | ... | ... | ... | ...

There are 18 more TTP items available. Please use our online service to access the data.

## IOA - Indicator of Attack

These _indicators of attack_ (IOA) list the potential fragments used for technical activities like reconnaissance, exploitation, privilege escalation, and exfiltration by NetSupport. This data is unique as it uses our predictive model for actor profiling.

ID | Type | Indicator | Confidence
-- | ---- | --------- | ----------
1 | File | `/.well-known/oauth-authorization-server` | High
2 | File | `/?page=user` | Medium
3 | File | `/action.php` | Medium
4 | File | `/add-new-officer.php` | High
5 | File | `/add-office.php` | High
6 | File | `/addCandidate.php` | High
7 | File | `/addmem.php` | Medium
8 | File | `/addProduct.php` | High
9 | File | `/addrecord.php` | High
10 | File | `/add_librarian.php` | High
11 | File | `/add_member.php` | High
12 | File | `/add_query_reserve.php` | High
13 | File | `/add_to_cart` | Medium
14 | File | `/admin#themes` | High
15 | File | `/admin.php` | Medium
16 | File | `/admin.php?id=inbox` | High
17 | File | `/admin/` | Low
18 | File | `/admin/?page=city` | High
19 | File | `/admin/?page=establishment` | High
20 | File | `/admin/?page=people` | High
21 | File | `/admin/?page=state` | High
22 | File | `/admin/?page=system_info` | High
23 | File | `/admin/?page=system_info/contact_info` | High
24 | File | `/admin/?page=user` | High
25 | File | `/admin/?page=zone` | High
26 | File | `/admin/add-module.php` | High
27 | File | `/Admin/additems.php` | High
28 | File | `/admin/add_account.php` | High
29 | File | `/admin/add_admin.php` | High
30 | File | `/admin/add_area.php` | High
31 | File | `/admin/add_category.php` | High
32 | File | `/admin/add_distributor.php` | High
33 | File | `/admin/add_payroll.php` | High
34 | File | `/admin/add_product.php` | High
35 | File | `/admin/add_retailer.php` | High
36 | File | `/admin/add_unit.php` | High
37 | File | `/admin/admin_feature.php` | High
38 | File | `/admin/admin_football.php` | High
39 | File | `/admin/admin_index.php` | High
40 | File | `/admin/admin_product.ph` | High
41 | File | `/admin/admin_running.php` | High
42 | File | `/admin/app/login_crud.php` | High
43 | File | `/admin/archives_add.php` | High
44 | File | `/admin/articles/add` | High
45 | File | `/admin/blog/comment/create` | High
46 | File | `/admin/bwdates-reports-details.php` | High
47 | File | `/Admin/changepassword.php` | High
48 | File | `/admin/checklogin.php` | High
49 | File | `/admin/client_user` | High
50 | File | `/admin/cms/category/addtitle` | High
51 | File | `/admin/cms/material/add` | High
52 | File | `/Admin/Controller/CustomController.class.php` | High
53 | File | `/admin/customer-list.php` | High
54 | File | `/admin/deletemanager.php` | High
55 | File | `/admin/deletemanagerclinic.php` | High
56 | File | `/admin/delete_student.php` | High
57 | File | `/admin/delete_user.php` | High
58 | File | `/admin/editsite.php` | High
59 | File | `/admin/edit_account.php` | High
60 | File | `/admin/edit_admin_query.php` | High
61 | File | `/admin/edit_subject.php` | High
62 | File | `/admin/file_manager/export` | High
63 | File | `/admin/freelist_main.php` | High
64 | File | `/admin/index.php` | High
65 | File | `/admin/index.php/advtext/add` | High
66 | File | `/admin/index.php/datafile/delfile` | High
67 | File | `/admin/index.php/datafile/download` | High
68 | File | `/admin/index2.html` | High
69 | File | `/admin/invoiceprint.php` | High
70 | File | `/admin/login.php` | High
71 | File | `/admin/login_query.php` | High
72 | File | `/admin/maintenance/view_designation.php` | High
73 | File | `/admin/newsletterdel.php` | High
74 | File | `/admin/products/index.php?view=add` | High
75 | File | `/admin/products/index.php?view=edit` | High
76 | File | `/admin/quesadd.php` | High
77 | File | `/admin/receipt.php` | High
78 | File | `/admin/reservation.php` | High
79 | File | `/admin/reset-password.php` | High
80 | File | `/admin/roombook.php` | High
81 | File | `/admin/roomdel.php` | High
82 | File | `/admin/save_student.php` | High
83 | File | `/admin/save_user.php` | High
84 | File | `/admin/search-invoices.php` | High
85 | File | `/admin/search.php` | High
86 | File | `/admin/search1.php` | High
87 | File | `/admin/siteconfig.php` | High
88 | File | `/admin/spec_add.php` | High
89 | File | `/admin/stateadd.php` | High
90 | File | `/admin/templets_one_edit.php` | High
91 | File | `/admin/update-progress.php` | High
92 | File | `/admin/update_student.php` | High
93 | File | `/admin/update_user.php` | High
94 | File | `/admin/user-bookings.php` | High
95 | File | `/admin/user/index.php?view=edit` | High
96 | File | `/admin/user/manage_user.php` | High
97 | File | `/admin/useragentdelete.php` | High
98 | File | `/admin/userbuilderdelete.php` | High
99 | File | `/admin/userdelete.php` | High
100 | File | `/admin/usersetting.php` | High
101 | File | `/admin/usersettingdel.php` | High
102 | File | `/admin/view-appointment.php` | High
103 | File | `/admin/view-member-report.php` | High
104 | File | `/admin/view-progress-report.php` | High
105 | File | `/admin/view_products.php` | High
106 | File | `/admin/view_unit.php` | High
107 | ... | ... | ...

There are 949 more IOA items available (file, library, argument, input value, pattern, network port). Please use our online service to access the data.

## References

The following list contains _external sources_ which discuss the actor and the associated activities:

* https://isc.sans.edu/diary/32474
* https://pastebin.com/iqcg0Ys7
* https://unit42.paloaltonetworks.com/preventing-clickfix-attack-vector/
* https://urlhaus.abuse.ch/url/3519140/
* https://urlhaus.abuse.ch/url/3519203/
* https://urlhaus.abuse.ch/url/3536229/
* https://urlhaus.abuse.ch/url/3543173/
* https://urlhaus.abuse.ch/url/3543176/
* https://urlhaus.abuse.ch/url/3646355/
* https://urlhaus.abuse.ch/url/3661121/
* https://urlhaus.abuse.ch/url/3677859/
* https://urlhaus.abuse.ch/url/3691013/
* https://urlhaus.abuse.ch/url/3703037/
* https://urlhaus.abuse.ch/url/3729395/
* https://urlhaus.abuse.ch/url/3740905/
* https://urlhaus.abuse.ch/url/3759771/
* https://urlhaus.abuse.ch/url/3784159/
* https://urlhaus.abuse.ch/url/3785601/
* https://www.cybereason.com/blog/net-support-rat-wordpress-clickfix
* https://www.domaintools.com/resources/blog/a-website-attacked/
* https://www.malware-traffic-analysis.net/2025/06/18/index.html
* https://www.malware-traffic-analysis.net/2025/12/29/index.html
* https://www.securonix.com/blog/jssmuggler-multi-stage-hidden-iframes-obfuscated-javascript-silent-redirectors-netsupport-rat-delivery/

## Literature

The following _articles_ explain our unique predictive cyber threat intelligence:

* [VulDB Cyber Threat Intelligence Documentation](https://vuldb.com/?kb.cti)
* [Cyber Threat Intelligence - Early Anticipation of Attacks](https://www.scip.ch/en/?labs.20201022)

## License

(c) [1997-2026](https://vuldb.com/?kb.changelog) by [vuldb.com](https://vuldb.com/?kb.about). All data on this page is shared under the license [CC BY-NC-SA 4.0](https://creativecommons.org/licenses/by-nc-sa/4.0/). Questions? Check the [FAQ](https://vuldb.com/?kb.faq), read the [documentation](https://vuldb.com/?kb) or [contact us](https://vuldb.com/?contact)!
