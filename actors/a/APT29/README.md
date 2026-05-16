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

* [MY](https://vuldb.com//country/my)
* [LA](https://vuldb.com//country/la)
* [US](https://vuldb.com//country/us)
* ...

There are 10 more country items available. Please use our online service to access the data.

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
1 | T1006 | CWE-21, CWE-22, CWE-24, CWE-35 | Path Traversal | High
2 | T1055 | CWE-74 | Improper Neutralization of Data within XPath Expressions | High
3 | T1059 | CWE-88, CWE-94, CWE-1321 | Argument Injection | High
4 | T1059.007 | CWE-79, CWE-80 | Basic Cross Site Scripting | High
5 | ... | ... | ... | ...

There are 18 more TTP items available. Please use our online service to access the data.

## IOA - Indicator of Attack

These _indicators of attack_ (IOA) list the potential fragments used for technical activities like reconnaissance, exploitation, privilege escalation, and exfiltration by APT29. This data is unique as it uses our predictive model for actor profiling.

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
14 | File | `/admin.php` | Medium
15 | File | `/admin.php?id=inbox` | High
16 | File | `/admin/` | Low
17 | File | `/admin/?page=city` | High
18 | File | `/admin/?page=establishment` | High
19 | File | `/admin/?page=people` | High
20 | File | `/admin/?page=state` | High
21 | File | `/admin/?page=system_info` | High
22 | File | `/admin/?page=user` | High
23 | File | `/admin/?page=zone` | High
24 | File | `/admin/add-artist.php` | High
25 | File | `/admin/add-module.php` | High
26 | File | `/Admin/additems.php` | High
27 | File | `/admin/add_account.php` | High
28 | File | `/admin/add_admin.php` | High
29 | File | `/admin/add_area.php` | High
30 | File | `/admin/add_category.php` | High
31 | File | `/admin/add_distributor.php` | High
32 | File | `/admin/add_payroll.php` | High
33 | File | `/admin/add_product.php` | High
34 | File | `/admin/add_retailer.php` | High
35 | File | `/admin/add_unit.php` | High
36 | File | `/admin/admin-profile.php` | High
37 | File | `/admin/admin_feature.php` | High
38 | File | `/admin/admin_football.php` | High
39 | File | `/admin/admin_index.php` | High
40 | File | `/admin/admin_product.ph` | High
41 | File | `/admin/admin_running.php` | High
42 | File | `/admin/ajax.php?action=save_recruitment_status` | High
43 | File | `/admin/app/login_crud.php` | High
44 | File | `/admin/archives_add.php` | High
45 | File | `/admin/articles/add` | High
46 | File | `/admin/blog/comment/create` | High
47 | File | `/admin/bwdates-reports-details.php` | High
48 | File | `/Admin/changepassword.php` | High
49 | File | `/admin/checklogin.php` | High
50 | File | `/admin/cms/category/addtitle` | High
51 | File | `/admin/cms/material/add` | High
52 | File | `/admin/complaint-search.php` | High
53 | File | `/Admin/Controller/CustomController.class.php` | High
54 | File | `/admin/customer-list.php` | High
55 | File | `/admin/deletemanager.php` | High
56 | File | `/admin/deletemanagerclinic.php` | High
57 | File | `/admin/delete_student.php` | High
58 | File | `/admin/delete_user.php` | High
59 | File | `/admin/editsite.php` | High
60 | File | `/admin/edit_account.php` | High
61 | File | `/admin/edit_admin_query.php` | High
62 | File | `/admin/edit_class.php` | High
63 | File | `/admin/edit_department.php` | High
64 | File | `/admin/file_manager/export` | High
65 | File | `/admin/forget-password.php` | High
66 | File | `/admin/freelist_main.php` | High
67 | File | `/admin/index.php` | High
68 | File | `/admin/index.php/advtext/add` | High
69 | File | `/admin/index.php/datafile/delfile` | High
70 | File | `/admin/index.php/datafile/download` | High
71 | File | `/admin/index2.html` | High
72 | File | `/admin/invoiceprint.php` | High
73 | File | `/admin/login.php` | High
74 | File | `/admin/login_query.php` | High
75 | File | `/admin/newsletterdel.php` | High
76 | File | `/admin/process_category_add.php` | High
77 | File | `/admin/products/index.php?view=add` | High
78 | File | `/admin/products/index.php?view=edit` | High
79 | File | `/admin/quesadd.php` | High
80 | File | `/admin/receipt.php` | High
81 | File | `/admin/reservation.php` | High
82 | File | `/admin/reset-password.php` | High
83 | File | `/admin/roombook.php` | High
84 | File | `/admin/roomdel.php` | High
85 | File | `/admin/save_student.php` | High
86 | File | `/admin/save_user.php` | High
87 | File | `/admin/search-invoices.php` | High
88 | File | `/admin/search.php` | High
89 | File | `/admin/search1.php` | High
90 | File | `/admin/siteconfig.php` | High
91 | File | `/admin/spec_add.php` | High
92 | File | `/admin/stateadd.php` | High
93 | File | `/admin/templets_one_edit.php` | High
94 | File | `/admin/update-progress.php` | High
95 | File | `/admin/update_student.php` | High
96 | File | `/admin/update_user.php` | High
97 | File | `/admin/user-bookings.php` | High
98 | File | `/admin/user/index.php?view=edit` | High
99 | File | `/admin/useragentdelete.php` | High
100 | File | `/admin/userbuilderdelete.php` | High
101 | File | `/admin/userdelete.php` | High
102 | File | `/admin/usersetting.php` | High
103 | File | `/admin/usersettingdel.php` | High
104 | File | `/admin/view-appointment.php` | High
105 | File | `/admin/view-member-report.php` | High
106 | File | `/admin/view-progress-report.php` | High
107 | ... | ... | ...

There are 946 more IOA items available (file, library, argument, input value, pattern, network port). Please use our online service to access the data.

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

(c) [1997-2026](https://vuldb.com/?kb.changelog) by [vuldb.com](https://vuldb.com/?kb.about). All data on this page is shared under the license [CC BY-NC-SA 4.0](https://creativecommons.org/licenses/by-nc-sa/4.0/). Questions? Check the [FAQ](https://vuldb.com/?kb.faq), read the [documentation](https://vuldb.com/?kb) or [contact us](https://vuldb.com/?contact)!
