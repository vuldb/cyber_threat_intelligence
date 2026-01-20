# ResolverRAT - Cyber Threat Intelligence

These _indicators_ were reported, collected, and generated during the [VulDB CTI analysis](https://vuldb.com/?kb.cti) of the actor known as [ResolverRAT](https://vuldb.com/?actor.resolverrat). The _activity monitoring_ correlates data from social media, forums, chat rooms, and darknet markets. It helps to determine associated actors, specific activities, expected intentions, emerging research, and ongoing attacks. Our unique _predictive model_ uses _big data_ to forecast activities and their characteristics.

_Live data_ and more _analysis capabilities_ are available at [https://vuldb.com/?actor.resolverrat](https://vuldb.com/?actor.resolverrat)

## Countries

These _countries_ are directly (e.g. origin of attacks) or indirectly (e.g. access by proxy) associated with ResolverRAT:

* [SH](https://vuldb.com/?country.sh)
* [US](https://vuldb.com/?country.us)
* [RU](https://vuldb.com/?country.ru)
* ...

There are 10 more country items available. Please use our online service to access the data.

## IOC - Indicator of Compromise

These _indicators of compromise_ (IOC) indicate associated network resources which are known to be part of research and attack activities of ResolverRAT.

ID | IP address | Hostname | Campaign | Confidence
-- | ---------- | -------- | -------- | ----------
1 | [38.54.6.120](https://vuldb.com/?ip.38.54.6.120) | - | - | High
2 | [45.74.10.38](https://vuldb.com/?ip.45.74.10.38) | - | - | High
3 | [45.141.87.200](https://vuldb.com/?ip.45.141.87.200) | - | - | High
4 | [45.144.53.137](https://vuldb.com/?ip.45.144.53.137) | 108787.h2.nexus | - | High
5 | ... | ... | ... | ...

There are 18 more IOC items available. Please use our online service to access the data.

## TTP - Tactics, Techniques, Procedures

_Tactics, techniques, and procedures_ (TTP) summarize the suspected MITRE ATT&CK techniques used by _ResolverRAT_. This data is unique as it uses our predictive model for actor profiling.

ID | Technique | Weakness | Description | Confidence
-- | --------- | -------- | ----------- | ----------
1 | T1006 | CWE-21, CWE-22, CWE-36 | Path Traversal | High
2 | T1040 | CWE-319 | Authentication Bypass by Capture-replay | High
3 | T1055 | CWE-74 | Improper Neutralization of Data within XPath Expressions | High
4 | T1059 | CWE-94 | Argument Injection | High
5 | T1059.007 | CWE-79, CWE-80 | Basic Cross Site Scripting | High
6 | T1068 | CWE-250, CWE-264, CWE-269, CWE-284 | Execution with Unnecessary Privileges | High
7 | ... | ... | ... | ...

There are 22 more TTP items available. Please use our online service to access the data.

## IOA - Indicator of Attack

These _indicators of attack_ (IOA) list the potential fragments used for technical activities like reconnaissance, exploitation, privilege escalation, and exfiltration by ResolverRAT. This data is unique as it uses our predictive model for actor profiling.

ID | Type | Indicator | Confidence
-- | ---- | --------- | ----------
1 | File | `/addbill.php` | Medium
2 | File | `/admin/?page=system_info/contact_info` | High
3 | File | `/admin/about.php` | High
4 | File | `/admin/add-customer-services.php` | High
5 | File | `/admin/admin-profile.php` | High
6 | File | `/admin/ajax.php` | High
7 | File | `/admin/assets/plugins/DataTables/media/unit_testing/templates/complex_header_2.php` | High
8 | File | `/admin/assets/plugins/DataTables/media/unit_testing/templates/deferred_table.php` | High
9 | File | `/admin/assets/plugins/DataTables/media/unit_testing/templates/dom_data.php` | High
10 | File | `/admin/assets/plugins/DataTables/media/unit_testing/templates/dymanic_table.php` | High
11 | File | `/admin/assets/plugins/DataTables/media/unit_testing/templates/html_table.php` | High
12 | File | `/admin/assets/plugins/DataTables/media/unit_testing/templates/js_data.php` | High
13 | File | `/admin/change-emailid.php` | High
14 | File | `/admin/contact-us.php` | High
15 | File | `/admin/contactus.php` | High
16 | File | `/admin/customer-list.php` | High
17 | File | `/Admin/delete-fee.php` | High
18 | File | `/admin/edit-brand.php` | High
19 | File | `/admin/edit-user.php` | High
20 | File | `/admin/editsite.php` | High
21 | File | `/admin/menu.php` | High
22 | File | `/admin/quote-details.php` | High
23 | File | `/admin/sales-reports-detail.php` | High
24 | File | `/admin/search-property.php` | High
25 | File | `/admin/state.php` | High
26 | File | `/admin/student-registration.php` | High
27 | File | `/admin/transaction/deposit` | High
28 | File | `/admin/user-bookings.php` | High
29 | File | `/admin/yesterday-reg-users.php` | High
30 | File | `/ajax.php?action=calculate_payroll` | High
31 | File | `/anchor/admin/categories/delete/2` | High
32 | File | `/api/files/recipepictures/` | High
33 | File | `/api/wizard/getBasicInfo` | High
34 | File | `/bbdms/admin/update-contactinfo.php` | High
35 | File | `/binutils/debug.c` | High
36 | File | `/boafrm/formDdns` | High
37 | File | `/cgi-bin/cstecgi.cgi` | High
38 | File | `/cgi-bin/koha/catalogue/search.pl` | High
39 | File | `/cm/update_rows/page?id=2` | High
40 | File | `/cupseasylive/itemgroupcreate.php` | High
41 | File | `/data/data/com.phonepe.app/databases/` | High
42 | ... | ... | ...

There are 367 more IOA items available (file, library, argument, input value, pattern, network port). Please use our online service to access the data.

## References

The following list contains _external sources_ which discuss the actor and the associated activities:

* https://app.any.run/tasks/3052c0e6-3e7b-4ebb-8f7e-1ffbc6c714bc
* https://bazaar.abuse.ch/sample/376b605e1a1ab380b7c2a9b363e87e21388c9feeda32465adc177c330f019086/
* https://bazaar.abuse.ch/sample/a1513b4139c837ac01c3c494c312450ef50de51131a5e846498a7102d45e1065/
* https://bazaar.abuse.ch/sample/c1f249ec791d19b8b93f9a8f9473830db459d668d0ff1e25c8531612707c9f03/
* https://bazaar.abuse.ch/sample/ce6402ae264ace318eebc4214f061ecb7253a87482834fddd96bf297eb733d44/
* https://threatfox.abuse.ch
* https://urlhaus.abuse.ch/url/3591561/
* https://urlhaus.abuse.ch/url/3729964/
* https://www.joesandbox.com/analysis/1753154/0/html
* https://www.joesandbox.com/analysis/1754029/0/html
* https://www.morphisec.com/blog/new-malware-variant-identified-resolverrat-enters-the-maze/
* https://x.com/JAMESWT_WT/status/1955060839569870991

## Literature

The following _articles_ explain our unique predictive cyber threat intelligence:

* [VulDB Cyber Threat Intelligence Documentation](https://vuldb.com/?kb.cti)
* [Cyber Threat Intelligence - Early Anticipation of Attacks](https://www.scip.ch/en/?labs.20201022)

## License

(c) [1997-2026](https://vuldb.com/?kb.changelog) by [vuldb.com](https://vuldb.com/?kb.about). All data on this page is shared under the license [CC BY-NC-SA 4.0](https://creativecommons.org/licenses/by-nc-sa/4.0/). Questions? Check the [FAQ](https://vuldb.com/?kb.faq), read the [documentation](https://vuldb.com/?kb) or [contact us](https://vuldb.com/?contact)!
