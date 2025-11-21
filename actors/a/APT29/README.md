# APT29 - Cyber Threat Intelligence

These _indicators_ were reported, collected, and generated during the [VulDB CTI analysis](https://vuldb.com/?kb.cti) of the actor known as [APT29](https://vuldb.com/?actor.apt29). The _activity monitoring_ correlates data from social media, forums, chat rooms, and darknet markets. It helps to determine associated actors, specific activities, expected intentions, emerging research, and ongoing attacks. Our unique _predictive model_ uses _big data_ to forecast activities and their characteristics.

_Live data_ and more _analysis capabilities_ are available at [https://vuldb.com/?actor.apt29](https://vuldb.com/?actor.apt29)

## Campaigns

The following _campaigns_ are known and can be associated with APT29:

* Cobalt Strike
* COVID-19
* CVE-2023-42793
* ...

There are 3 more campaign items available. Please use our online service to access the data.

## Countries

These _countries_ are directly (e.g. origin of attacks) or indirectly (e.g. access by proxy) associated with APT29:

* [CN](https://vuldb.com/?country.cn)
* [US](https://vuldb.com/?country.us)
* [TR](https://vuldb.com/?country.tr)

## IOC - Indicator of Compromise

These _indicators of compromise_ (IOC) indicate associated network resources which are known to be part of research and attack activities of APT29.

ID | IP address | Hostname | Campaign | Confidence
-- | ---------- | -------- | -------- | ----------
1 | [3.64.163.50](https://vuldb.com/?ip.3.64.163.50) | ec2-3-64-163-50.eu-central-1.compute.amazonaws.com | - | Medium
2 | [5.45.66.134](https://vuldb.com/?ip.5.45.66.134) | - | - | High
3 | [5.199.174.164](https://vuldb.com/?ip.5.199.174.164) | - | - | High
4 | [13.248.169.48](https://vuldb.com/?ip.13.248.169.48) | a904c694c05102f30.awsglobalaccelerator.com | - | High
5 | [20.222.6.225](https://vuldb.com/?ip.20.222.6.225) | - | CVE-2023-42793 | High
6 | [23.29.115.180](https://vuldb.com/?ip.23.29.115.180) | 23-29-115-180.static.hvvc.us | StellarParticle | High
7 | [23.82.128.144](https://vuldb.com/?ip.23.82.128.144) | - | StellarParticle | High
8 | [23.227.38.32](https://vuldb.com/?ip.23.227.38.32) | myshopify.com | - | High
9 | [27.102.130.115](https://vuldb.com/?ip.27.102.130.115) | - | - | High
10 | [31.7.63.141](https://vuldb.com/?ip.31.7.63.141) | game.bignamegamereviewz.com | - | High
11 | [31.31.74.79](https://vuldb.com/?ip.31.31.74.79) | - | Cobalt Strike | High
12 | [31.170.107.186](https://vuldb.com/?ip.31.170.107.186) | ohra.supplrald.com | - | High
13 | [35.205.61.67](https://vuldb.com/?ip.35.205.61.67) | 67.61.205.35.bc.googleusercontent.com | - | Medium
14 | [43.248.34.77](https://vuldb.com/?ip.43.248.34.77) | - | CVE-2023-42793 | High
15 | [45.77.179.110](https://vuldb.com/?ip.45.77.179.110) | 45.77.179.110.vultrusercontent.com | - | Medium
16 | [45.120.156.69](https://vuldb.com/?ip.45.120.156.69) | - | - | High
17 | [45.123.190.167](https://vuldb.com/?ip.45.123.190.167) | - | COVID-19 | High
18 | [45.123.190.168](https://vuldb.com/?ip.45.123.190.168) | - | - | High
19 | [45.129.229.48](https://vuldb.com/?ip.45.129.229.48) | - | COVID-19 | High
20 | [45.133.7.124](https://vuldb.com/?ip.45.133.7.124) | - | CVE-2023-42793 | High
21 | [45.133.7.129](https://vuldb.com/?ip.45.133.7.129) | - | CVE-2023-42793 | High
22 | [45.133.7.154](https://vuldb.com/?ip.45.133.7.154) | - | CVE-2023-42793 | High
23 | [45.133.7.156](https://vuldb.com/?ip.45.133.7.156) | - | CVE-2023-42793 | High
24 | [45.152.84.57](https://vuldb.com/?ip.45.152.84.57) | - | - | High
25 | [46.19.143.69](https://vuldb.com/?ip.46.19.143.69) | - | - | High
26 | [46.246.120.178](https://vuldb.com/?ip.46.246.120.178) | - | - | High
27 | [50.7.192.146](https://vuldb.com/?ip.50.7.192.146) | - | - | High
28 | [51.75.210.218](https://vuldb.com/?ip.51.75.210.218) | ip218.ip-51-75-210.eu | - | High
29 | [64.18.143.66](https://vuldb.com/?ip.64.18.143.66) | - | - | High
30 | ... | ... | ... | ...

There are 115 more IOC items available. Please use our online service to access the data.

## TTP - Tactics, Techniques, Procedures

_Tactics, techniques, and procedures_ (TTP) summarize the suspected MITRE ATT&CK techniques used by _APT29_. This data is unique as it uses our predictive model for actor profiling.

ID | Technique | Weakness | Description | Confidence
-- | --------- | -------- | ----------- | ----------
1 | T1006 | CWE-22, CWE-24 | Path Traversal | High
2 | T1040 | CWE-319 | Authentication Bypass by Capture-replay | High
3 | T1055 | CWE-74 | Improper Neutralization of Data within XPath Expressions | High
4 | T1059 | CWE-94, CWE-1321 | Argument Injection | High
5 | T1059.007 | CWE-79, CWE-80 | Basic Cross Site Scripting | High
6 | ... | ... | ... | ...

There are 20 more TTP items available. Please use our online service to access the data.

## IOA - Indicator of Attack

These _indicators of attack_ (IOA) list the potential fragments used for technical activities like reconnaissance, exploitation, privilege escalation, and exfiltration by APT29. This data is unique as it uses our predictive model for actor profiling.

ID | Type | Indicator | Confidence
-- | ---- | --------- | ----------
1 | File | `/?page=tracks` | High
2 | File | `/aboutus.php` | Medium
3 | File | `/account.php` | Medium
4 | File | `/Actions.php` | Medium
5 | File | `/activation.php` | High
6 | File | `/ad-list` | Medium
7 | File | `/adaddmed.php` | High
8 | File | `/add-notes.php` | High
9 | File | `/add-phlebotomist.php` | High
10 | File | `/addCatController.php` | High
11 | File | `/addcategory.php` | High
12 | File | `/addcompany.php` | High
13 | File | `/addcustcom.php` | High
14 | File | `/addelivery.php` | High
15 | File | `/addstock.php` | High
16 | File | `/admin` | Low
17 | File | `/admin-dashboard` | High
18 | File | `/admin-manage-user.php` | High
19 | File | `/admin-profile.php` | High
20 | File | `/admin/` | Low
21 | File | `/admin/about-us.php` | High
22 | File | `/admin/add-admin.php` | High
23 | File | `/admin/add-ambulance.php` | High
24 | File | `/admin/add-art-medium.php` | High
25 | File | `/admin/add-category.php` | High
26 | File | `/admin/add-services.php` | High
27 | File | `/admin/admin-profile.php` | High
28 | File | `/admin/adminprofile.php` | High
29 | File | `/admin/ajax.php?action=login` | High
30 | File | `/admin/ajax.php?action=save_vacancy` | High
31 | File | `/admin/application-bwdates-reports-details.php` | High
32 | File | `/admin/assets/plugins/DataTables/media/unit_testing/templates/html_table.php` | High
33 | File | `/admin/assets/plugins/DataTables/media/unit_testing/templates/two_tables.php` | High
34 | File | `/admin/ballot_up.php` | High
35 | File | `/admin/bookdate.php` | High
36 | File | `/admin/bwdates-report-details.php` | High
37 | File | `/admin/bwdates-reports-details.php` | High
38 | File | `/admin/candidates_add.php` | High
39 | File | `/admin/candidates_row.php` | High
40 | File | `/admin/categories/save` | High
41 | File | `/admin/category.php` | High
42 | File | `/admin/change-emailid.php` | High
43 | File | `/admin/chatroom.php` | High
44 | File | `/admin/clients/manage.php` | High
45 | File | `/admin/content/book` | High
46 | File | `/admin/content/editor` | High
47 | File | `/admin/content/index` | High
48 | File | `/admin/delete_s2.php` | High
49 | File | `/admin/departments/manage_department.php` | High
50 | File | `/admin/doctor-specilization.php` | High
51 | File | `/admin/edit-category.php` | High
52 | File | `/admin/edit-doctor.php` | High
53 | File | `/admin/edit-nurse.php` | High
54 | File | `/Admin/edit-photo.php` | High
55 | File | `/admin/edit-services.php` | High
56 | File | `/admin/edit-subcategory.php` | High
57 | File | `/admin/editorder.php` | High
58 | File | `/admin/edit_product.php` | High
59 | File | `/admin/edit_room.php` | High
60 | File | `/admin/goods/update` | High
61 | File | `/admin/index.php` | High
62 | File | `/admin/index/index.html#/admin/mall.goods/index.html` | High
63 | File | `/admin/manage-foreigners-ticket.php` | High
64 | File | `/admin/manage-site.php` | High
65 | File | `/admin/manage-teams.php` | High
66 | File | `/admin/manage_complaint.php` | High
67 | File | `/Admin/match.php` | High
68 | File | `/admin/network/ajax_getChannelList` | High
69 | File | `/admin/network/diag_ping6` | High
70 | File | `/admin/network/diag_traceroute6` | High
71 | File | `/admin/Operation/User.php` | High
72 | File | `/admin/operations/booking.php` | High
73 | File | `/admin/operations/expense_category.php` | High
74 | File | `/admin/operations/payment.php` | High
75 | File | `/admin/page-login.php` | High
76 | File | `/admin/password-recovery.php` | High
77 | File | `/admin/print1.php` | High
78 | File | `/admin/profile.php` | High
79 | File | `/admin/regester.php` | High
80 | File | `/Admin/resultdetails.php` | High
81 | File | `/admin/room.php` | High
82 | File | `/admin/rules.php` | High
83 | File | `/admin/save_airlines.php` | High
84 | File | `/admin/search-directory.php` | High
85 | File | `/admin/search-invoices.php` | High
86 | File | `/admin/sensitive_word/list` | High
87 | File | `/admin/sign/out` | High
88 | File | `/admin/sms_setting.php` | High
89 | File | `/admin/tag/save` | High
90 | File | `/admin/update-users.php` | High
91 | File | `/admin/update_room.php` | High
92 | File | `/admin/update_s1.php` | High
93 | File | `/admin/update_s4.php` | High
94 | File | `/admin/update_s8.php` | High
95 | File | `/admin/update_users.php` | High
96 | File | `/admin/user.php` | High
97 | File | `/admin/user/manage_user.php` | High
98 | File | `/admin/users.php` | High
99 | File | `/admin?do=admin:user:editPost` | High
100 | File | `/adminprofile.php` | High
101 | File | `/adphar.php` | Medium
102 | File | `/adposition/queryAll` | High
103 | File | `/ajax.php?action=delete_allowances` | High
104 | File | `/ajax.php?action=delete_position` | High
105 | File | `/ajax.php?action=delete_user` | High
106 | File | `/ajax.php?action=save_borrower` | High
107 | File | `/ajax.php?action=save_schedule` | High
108 | File | `/animalsupdate.php` | High
109 | File | `/api/front/search/books` | High
110 | File | `/api/job/add/` | High
111 | File | `/api/role` | Medium
112 | File | `/api/sys/ng-alain/getDictItemsByTable/` | High
113 | File | `/api/upload` | Medium
114 | File | `/app/api/controller/Site.php` | High
115 | File | `/Applications/Steal/main.cpp` | High
116 | File | `/auth/info` | Medium
117 | File | `/backend/admin/his_admin_add_vendor.php` | High
118 | File | `/backend/admin/his_admin_register_patient.php` | High
119 | File | `/backend/register.php` | High
120 | File | `/bank/statements.php` | High
121 | File | `/bank/transfer.php` | High
122 | File | `/bbdms/admin/update-contactinfo.php` | High
123 | File | `/billaction.php` | High
124 | File | `/boafrm/formFilter` | High
125 | File | `/boafrm/formMapDelDevice` | High
126 | File | `/boafrm/formOneKeyAccessButton` | High
127 | File | `/boafrm/formRoute` | High
128 | File | `/boafrm/formTmultiAP` | High
129 | File | `/book-appointment.php` | High
130 | ... | ... | ...

There are 1155 more IOA items available (file, library, argument, input value, pattern, network port). Please use our online service to access the data.

## References

The following list contains _external sources_ which discuss the actor and the associated activities:

* https://blog-assets.f-secure.com/wp-content/uploads/2020/03/18122307/F-Secure_Dukes_Whitepaper.pdf
* https://circleid.com/posts/20231114-apt29-goes-from-targeted-attacks-to-phishing-via-nobelium-a-dns-deep-dive
* https://github.com/blackorbird/APT_REPORT/blob/master/APT29/APT29%20Adapts%20to%20Target%20Diplomatic%20Entities%20with%20GraphicalProton%20Malware.pdf
* https://github.com/blackorbird/APT_REPORT/blob/master/International%20Strategic/Russia/Advisory-APT29-targets-COVID-19-vaccine-development.pdf
* https://jp.security.ntt/tech_blog/102hojk
* https://unit42.paloaltonetworks.com/cloaked-ursa-online-storage-services-campaigns/
* https://us-cert.cisa.gov/ncas/alerts/aa21-148a
* https://us-cert.cisa.gov/ncas/analysis-reports/ar20-198c
* https://www.cisa.gov/news-events/cybersecurity-advisories/aa23-347a
* https://www.crowdstrike.com/blog/observations-from-the-stellarparticle-campaign/
* https://www.fortinet.com/blog/threat-research/teamcity-intrusion-saga-apt29-suspected-exploiting-cve-2023-42793
* https://www.microsoft.com/security/blog/2018/12/03/analysis-of-cyberattack-on-u-s-think-tanks-non-profits-public-sector-by-unidentified-attackers/
* https://www.ncsc.gov.uk/files/Advisory-APT29-targets-COVID-19-vaccine-development-V1-1.pdf
* https://www.volexity.com/blog/2016/11/09/powerduke-post-election-spear-phishing-campaigns-targeting-think-tanks-and-ngos/

## Literature

The following _articles_ explain our unique predictive cyber threat intelligence:

* [VulDB Cyber Threat Intelligence Documentation](https://vuldb.com/?kb.cti)
* [Cyber Threat Intelligence - Early Anticipation of Attacks](https://www.scip.ch/en/?labs.20201022)

## License

(c) [1997-2025](https://vuldb.com/?kb.changelog) by [vuldb.com](https://vuldb.com/?kb.about). All data on this page is shared under the license [CC BY-NC-SA 4.0](https://creativecommons.org/licenses/by-nc-sa/4.0/). Questions? Check the [FAQ](https://vuldb.com/?kb.faq), read the [documentation](https://vuldb.com/?kb) or [contact us](https://vuldb.com/?contact)!
