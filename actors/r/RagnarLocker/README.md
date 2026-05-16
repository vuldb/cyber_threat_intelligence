# RagnarLocker - Cyber Threat Intelligence

These _indicators_ were reported, collected, and generated during the [VulDB CTI analysis](https://vuldb.com/?kb.cti) of the actor known as [RagnarLocker](https://vuldb.com/?actor.ragnarlocker). The _activity monitoring_ correlates data from social media, forums, chat rooms, and darknet markets. It helps to determine associated actors, specific activities, expected intentions, emerging research, and ongoing attacks. Our unique _predictive model_ uses _big data_ to forecast activities and their characteristics.

_Live data_ and more _analysis capabilities_ are available at [https://vuldb.com/?actor.ragnarlocker](https://vuldb.com/?actor.ragnarlocker)

## Countries

These _countries_ are directly (e.g. origin of attacks) or indirectly (e.g. access by proxy) associated with RagnarLocker:

* [US](https://vuldb.com/?country.us)
* [DE](https://vuldb.com/?country.de)
* [RU](https://vuldb.com/?country.ru)
* ...

There are 15 more country items available. Please use our online service to access the data.

## IOC - Indicator of Compromise

These _indicators of compromise_ (IOC) indicate associated network resources which are known to be part of research and attack activities of RagnarLocker.

ID | IP address | Hostname | Campaign | Confidence
-- | ---------- | -------- | -------- | ----------
1 | [5.45.65.52](https://vuldb.com/?ip.5.45.65.52) | - | - | High
2 | [23.106.122.192](https://vuldb.com/?ip.23.106.122.192) | - | - | High
3 | [23.227.202.72](https://vuldb.com/?ip.23.227.202.72) | 23-227-202-72.static.hvvc.us | - | High
4 | [37.120.238.107](https://vuldb.com/?ip.37.120.238.107) | - | - | High
5 | [45.63.89.250](https://vuldb.com/?ip.45.63.89.250) | 45.63.89.250.vultr.com | - | Medium
6 | [45.90.59.131](https://vuldb.com/?ip.45.90.59.131) | unallocated.layer6.net | - | High
7 | [45.91.93.75](https://vuldb.com/?ip.45.91.93.75) | mnbbim4.uniteq.xyz | - | High
8 | ... | ... | ... | ...

There are 26 more IOC items available. Please use our online service to access the data.

## TTP - Tactics, Techniques, Procedures

_Tactics, techniques, and procedures_ (TTP) summarize the suspected MITRE ATT&CK techniques used by _RagnarLocker_. This data is unique as it uses our predictive model for actor profiling.

ID | Technique | Weakness | Description | Confidence
-- | --------- | -------- | ----------- | ----------
1 | T1006 | CWE-21, CWE-22, CWE-36 | Path Traversal | High
2 | T1040 | CWE-319 | Authentication Bypass by Capture-replay | High
3 | T1055 | CWE-74 | Improper Neutralization of Data within XPath Expressions | High
4 | T1059 | CWE-88, CWE-94 | Argument Injection | High
5 | T1059.007 | CWE-79, CWE-80 | Basic Cross Site Scripting | High
6 | ... | ... | ... | ...

There are 18 more TTP items available. Please use our online service to access the data.

## IOA - Indicator of Attack

These _indicators of attack_ (IOA) list the potential fragments used for technical activities like reconnaissance, exploitation, privilege escalation, and exfiltration by RagnarLocker. This data is unique as it uses our predictive model for actor profiling.

ID | Type | Indicator | Confidence
-- | ---- | --------- | ----------
1 | File | `/+CSCOE+/logon.html` | High
2 | File | `/admin` | Low
3 | File | `/admin/delete_activity.php` | High
4 | File | `/adminapi/system/file/openfile` | High
5 | File | `/adminlogin.asp` | High
6 | File | `/api/File/downloadFile` | High
7 | File | `/app/index/controller/Common.php` | High
8 | File | `/backend/admin/his_admin_add_lab_equipment.php` | High
9 | File | `/backend/admin/his_admin_register_patient.php` | High
10 | File | `/bitrix/admin/ldap_server_edit.php` | High
11 | File | `/category_view.php` | High
12 | File | `/dipam/athlete-profile.php` | High
13 | File | `/dtale/chart-data/1` | High
14 | File | `/enroll.php` | Medium
15 | File | `/exam/user/profile.php` | High
16 | File | `/filter.php` | Medium
17 | File | `/forum/away.php` | High
18 | File | `/goform/delAd` | High
19 | File | `/HNAP1` | Low
20 | File | `/includes/fileReceive.php` | High
21 | File | `/index.jsp#settings` | High
22 | File | `/mc-admin/post.php?state=delete&delete` | High
23 | File | `/mkshop/Men/profile.php` | High
24 | File | `/pharmacy-sales-and-inventory-system/manage_user.php` | High
25 | File | `/php-jms/review_se_result.php` | High
26 | File | `/public/install/controllers/DefaultController.php` | High
27 | File | `/public/login.htm` | High
28 | File | `/Side.php` | Medium
29 | File | `/signup.php` | Medium
30 | File | `/spip.php` | Medium
31 | File | `/student/bookdetails.php` | High
32 | File | `/textpattern/index.php` | High
33 | File | `/user/profile` | High
34 | File | `/usr/bin/pkexec` | High
35 | File | `/usr/ucb/mail` | High
36 | File | `/vicidial/AST_agent_time_sheet.php` | High
37 | File | `/wp-content/plugins/updraftplus/admin.php` | High
38 | File | `?page=attendance&class_id=1` | High
39 | File | `account.asp` | Medium
40 | File | `adclick.php` | Medium
41 | File | `addmember.php` | High
42 | File | `addtocart.asp` | High
43 | File | `addtomylist.asp` | High
44 | ... | ... | ...

There are 379 more IOA items available (file, library, argument, input value, pattern, network port). Please use our online service to access the data.

## References

The following list contains _external sources_ which discuss the actor and the associated activities:

* https://threatfox.abuse.ch
* https://www.ic3.gov/Media/News/2022/220307.pdf

## Literature

The following _articles_ explain our unique predictive cyber threat intelligence:

* [VulDB Cyber Threat Intelligence Documentation](https://vuldb.com/?kb.cti)
* [Cyber Threat Intelligence - Early Anticipation of Attacks](https://www.scip.ch/en/?labs.20201022)

## License

(c) [1997-2026](https://vuldb.com/?kb.changelog) by [vuldb.com](https://vuldb.com/?kb.about). All data on this page is shared under the license [CC BY-NC-SA 4.0](https://creativecommons.org/licenses/by-nc-sa/4.0/). Questions? Check the [FAQ](https://vuldb.com/?kb.faq), read the [documentation](https://vuldb.com/?kb) or [contact us](https://vuldb.com/?contact)!
