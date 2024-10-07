# PhonyC2 - Cyber Threat Intelligence

These _indicators_ were reported, collected, and generated during the [VulDB CTI analysis](https://vuldb.com/?kb.cti) of the campaign known as _PhonyC2_. The _activity monitoring_ correlates data from social media, forums, chat rooms, and darknet markets. It helps to determine associated actors, specific activities, expected intentions, emerging research, and ongoing attacks. Our unique _predictive model_ uses _big data_ to forecast activities and their characteristics.

_Live data_ and more _analysis capabilities_ are available at [https://vuldb.com/?actor](https://vuldb.com/?actor)

## Countries

These _countries_ are directly (e.g. origin of attacks) or indirectly (e.g. access by proxy) associated with PhonyC2:

* [DE](https://vuldb.com/?country.de)
* [US](https://vuldb.com/?country.us)
* [HU](https://vuldb.com/?country.hu)
* ...

There are 4 more country items available. Please use our online service to access the data.

## Actors

These _actors_ are associated with PhonyC2 or other actors linked to the campaign.

ID | Actor | Confidence
-- | ----- | ----------
1 | [MuddyWater](https://vuldb.com/?actor.muddywater) | High

## IOC - Indicator of Compromise

These _indicators of compromise_ (IOC) indicate associated network resources which are known to be part of research and attack activities of PhonyC2.

ID | IP address | Hostname | Actor | Confidence
-- | ---------- | -------- | ----- | ----------
1 | [45.86.230.20](https://vuldb.com/?ip.45.86.230.20) | mta0.officeportal-centers.gq | [MuddyWater](https://vuldb.com/?actor.muddywater) | High
2 | [45.159.248.244](https://vuldb.com/?ip.45.159.248.244) | vm1355757.stark-industries.solutions | [MuddyWater](https://vuldb.com/?actor.muddywater) | High
3 | [46.249.35.243](https://vuldb.com/?ip.46.249.35.243) | uhteronia.xyz | [MuddyWater](https://vuldb.com/?actor.muddywater) | High
4 | ... | ... | ... | ...

There are 9 more IOC items available. Please use our online service to access the data.

## TTP - Tactics, Techniques, Procedures

_Tactics, techniques, and procedures_ (TTP) summarize the suspected MITRE ATT&CK techniques used within PhonyC2. This data is unique as it uses our predictive model for actor profiling.

ID | Technique | Weakness | Description | Confidence
-- | --------- | -------- | ----------- | ----------
1 | T1006 | CWE-22, CWE-23, CWE-24, CWE-35, CWE-36, CWE-37 | Path Traversal | High
2 | T1040 | CWE-319 | Authentication Bypass by Capture-replay | High
3 | T1055 | CWE-74 | Improper Neutralization of Data within XPath Expressions | High
4 | T1059 | CWE-88, CWE-94, CWE-1321 | Argument Injection | High
5 | T1059.007 | CWE-79, CWE-80 | Cross Site Scripting | High
6 | T1068 | CWE-264, CWE-269, CWE-284 | Execution with Unnecessary Privileges | High
7 | ... | ... | ... | ...

There are 23 more TTP items available. Please use our online service to access the data.

## IOA - Indicator of Attack

These _indicators of attack_ (IOA) list the potential fragments used for technical activities like reconnaissance, exploitation, privilege escalation, and exfiltration during PhonyC2. This data is unique as it uses our predictive model for actor profiling.

ID | Type | Indicator | Confidence
-- | ---- | --------- | ----------
1 | File | `.github/workflows/comment.yml` | High
2 | File | `/?r=recruit/resume/edit&op=status` | High
3 | File | `/academy/tutor/filter` | High
4 | File | `/admin.php` | Medium
5 | File | `/admin.php?c=upload&f=zip&_noCache=0.1683794968` | High
6 | File | `/admin/?page=orders/view_order` | High
7 | File | `/admin/addemployee.php` | High
8 | File | `/admin/bookings/manage_booking.php` | High
9 | File | `/admin/bookings/view_booking.php` | High
10 | File | `/admin/categories/view_category.php` | High
11 | File | `/admin/conferences/get-all-status/` | High
12 | File | `/admin/conferences/list/` | High
13 | File | `/admin/general/change-lang` | High
14 | File | `/admin/group` | Medium
15 | File | `/admin/group/list/` | High
16 | File | `/admin/inquiries/view_inquiry.php` | High
17 | File | `/admin/modal_add_product.php` | High
18 | File | `/admin/orders/update_status.php` | High
19 | File | `/admin/pages/sections_save.php` | High
20 | File | `/admin/read.php?mudi=announContent` | High
21 | File | `/admin/service/stop/` | High
22 | File | `/admin/sys_sql_query.php` | High
23 | File | `/admin/transactions/update_status.php` | High
24 | File | `/admin/update_s6.php` | High
25 | File | `/admin/upload.php` | High
26 | File | `/admin/user/manage_user.php` | High
27 | File | `/admin/vote_edit.php` | High
28 | File | `/api/sys/login` | High
29 | File | `/asms/admin/products/manage_product.php` | High
30 | File | `/balance/service/list` | High
31 | File | `/bin/ate` | Medium
32 | File | `/blog` | Low
33 | File | `/blog-single.php` | High
34 | File | `/blog/comment` | High
35 | File | `/boafrm/formFilter` | High
36 | File | `/bsms_ci/index.php/book` | High
37 | File | `/cgi-bin/adm.cgi` | High
38 | File | `/change-language/de_DE` | High
39 | File | `/classes/Master.php` | High
40 | File | `/classes/Master.php?f=delete_category` | High
41 | File | `/classes/Master.php?f=delete_inquiry` | High
42 | File | `/classes/Master.php?f=delete_item` | High
43 | File | `/classes/Master.php?f=delete_service` | High
44 | File | `/classes/Master.php?f=save_course` | High
45 | File | `/classes/Master.php?f=save_inquiry` | High
46 | File | `/classes/Master.php?f=save_item` | High
47 | File | `/cms/category/list` | High
48 | File | `/collection/all` | High
49 | File | `/company/store` | High
50 | File | `/confirm` | Medium
51 | File | `/depotHead/list` | High
52 | File | `/dipam/athlete-profile.php` | High
53 | File | `/emap/devicePoint_addImgIco?hasSubsystem=true` | High
54 | File | `/etc/shadow.sample` | High
55 | File | `/file_manager/admin/save_user.php` | High
56 | File | `/find-a-match` | High
57 | File | `/friends` | Medium
58 | File | `/friends/ajax_invite` | High
59 | File | `/front/roomtype-details.php` | High
60 | File | `/garage/editorder.php` | High
61 | File | `/goform/addressNat` | High
62 | File | `/goform/AdvSetWrlsafeset` | High
63 | File | `/goForm/aspForm` | High
64 | File | `/goform/CertListInfo` | High
65 | File | `/goform/delFileName` | High
66 | File | `/goform/editFileName` | High
67 | File | `/goform/editUserName` | High
68 | ... | ... | ...

There are 596 more IOA items available (file, library, argument, input value, pattern, network port). Please use our online service to access the data.

## References

The following list contains _external sources_ which discuss the campaign and the associated activities:

* https://www.deepinstinct.com/blog/phonyc2-revealing-a-new-malicious-command-control-framework-by-muddywater

## Literature

The following _articles_ explain our unique predictive cyber threat intelligence:

* [VulDB Cyber Threat Intelligence Documentation](https://vuldb.com/?kb.cti)
* [Cyber Threat Intelligence - Early Anticipation of Attacks](https://www.scip.ch/en/?labs.20201022)

## License

(c) [1997-2024](https://vuldb.com/?kb.changelog) by [vuldb.com](https://vuldb.com/?kb.about). All data on this page is shared under the license [CC BY-NC-SA 4.0](https://creativecommons.org/licenses/by-nc-sa/4.0/). Questions? Check the [FAQ](https://vuldb.com/?kb.faq), read the [documentation](https://vuldb.com/?kb) or [contact us](https://vuldb.com/?contact)!
