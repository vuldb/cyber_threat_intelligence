# Bandit Stealer - Cyber Threat Intelligence

These _indicators_ were reported, collected, and generated during the [VulDB CTI analysis](https://vuldb.com/?kb.cti) of the actor known as [Bandit Stealer](https://vuldb.com/?actor.bandit_stealer). The _activity monitoring_ correlates data from social media, forums, chat rooms, and darknet markets. It helps to determine associated actors, specific activities, expected intentions, emerging research, and ongoing attacks. Our unique _predictive model_ uses _big data_ to forecast activities and their characteristics.

_Live data_ and more _analysis capabilities_ are available at [https://vuldb.com/?actor.bandit_stealer](https://vuldb.com/?actor.bandit_stealer)

## Countries

These _countries_ are directly (e.g. origin of attacks) or indirectly (e.g. access by proxy) associated with Bandit Stealer:

* [US](https://vuldb.com/?country.us)
* [SH](https://vuldb.com/?country.sh)
* [RU](https://vuldb.com/?country.ru)
* ...

There are 7 more country items available. Please use our online service to access the data.

## IOC - Indicator of Compromise

These _indicators of compromise_ (IOC) indicate associated network resources which are known to be part of research and attack activities of Bandit Stealer.

ID | IP address | Hostname | Campaign | Confidence
-- | ---------- | -------- | -------- | ----------
1 | [3.92.209.204](https://vuldb.com/?ip.3.92.209.204) | ec2-3-92-209-204.compute-1.amazonaws.com | - | Medium
2 | [20.102.80.176](https://vuldb.com/?ip.20.102.80.176) | - | - | High
3 | [20.150.218.195](https://vuldb.com/?ip.20.150.218.195) | - | - | High
4 | [24.199.107.85](https://vuldb.com/?ip.24.199.107.85) | - | - | High
5 | [41.216.183.23](https://vuldb.com/?ip.41.216.183.23) | - | - | High
6 | [41.216.183.94](https://vuldb.com/?ip.41.216.183.94) | - | - | High
7 | [45.42.45.10](https://vuldb.com/?ip.45.42.45.10) | web9-redirect.me | - | High
8 | ... | ... | ... | ...

There are 30 more IOC items available. Please use our online service to access the data.

## TTP - Tactics, Techniques, Procedures

_Tactics, techniques, and procedures_ (TTP) summarize the suspected MITRE ATT&CK techniques used by _Bandit Stealer_. This data is unique as it uses our predictive model for actor profiling.

ID | Technique | Weakness | Description | Confidence
-- | --------- | -------- | ----------- | ----------
1 | T1006 | CWE-21, CWE-22, CWE-35, CWE-36 | Path Traversal | High
2 | T1040 | CWE-294, CWE-319 | Authentication Bypass by Capture-replay | High
3 | T1055 | CWE-74 | Injection | High
4 | T1059 | CWE-94, CWE-1321 | Argument Injection | High
5 | T1059.007 | CWE-79, CWE-80 | Cross Site Scripting | High
6 | ... | ... | ... | ...

There are 20 more TTP items available. Please use our online service to access the data.

## IOA - Indicator of Attack

These _indicators of attack_ (IOA) list the potential fragments used for technical activities like reconnaissance, exploitation, privilege escalation, and exfiltration by Bandit Stealer. This data is unique as it uses our predictive model for actor profiling.

ID | Type | Indicator | Confidence
-- | ---- | --------- | ----------
1 | File | `.vscode/cody.json` | High
2 | File | `/?r=email/api/mark&op=delFromSend` | High
3 | File | `/accounts/login` | High
4 | File | `/accounts_con/register_account` | High
5 | File | `/admin.php` | Medium
6 | File | `/admin/` | Low
7 | File | `/admin/action/new-feed.php` | High
8 | File | `/admin/book_add.php` | High
9 | File | `/admin/content/data` | High
10 | File | `/admin/courses/view_course.php` | High
11 | File | `/admin/database/backup` | High
12 | File | `/admin/file/edit.do` | High
13 | File | `/admin/index.php?act=reset_admin_psw` | High
14 | File | `/admin/list_onlineuser.php` | High
15 | File | `/admin/sales/view_details.php` | High
16 | File | `/admin/students/view_details.php` | High
17 | File | `/adminapi/system/crud` | High
18 | File | `/ajax/ajax_login.ashx` | High
19 | File | `/api.php` | Medium
20 | File | `/api/email/update` | High
21 | File | `/application/index/controller/File.php` | High
22 | File | `/application/index/controller/Icon.php` | High
23 | File | `/Attachment/fromImageUrl` | High
24 | File | `/b2b-supermarket/catalog/all-products` | High
25 | File | `/b2b-supermarket/shopping-cart` | High
26 | File | `/bin/boa` | Medium
27 | File | `/catalog/compare` | High
28 | File | `/cgi-bin/cstecgi.cgi` | High
29 | File | `/cgi-bin/cstecgi.cgi?action=login` | High
30 | File | `/cgi-bin/wlogin.cgi` | High
31 | File | `/classes/Master.php? f=save_medicine` | High
32 | File | `/classes/Users.php?f=save` | High
33 | File | `/clinic/disease_symptoms_view.php` | High
34 | File | `/common/log/list` | High
35 | File | `/content/list.do` | High
36 | File | `/cupseasylive/costcentermodify.php` | High
37 | File | `/cupseasylive/itemmodify.php` | High
38 | File | `/cupseasylive/statelist.php` | High
39 | File | `/cupseasylive/stockissuancecreate.php` | High
40 | File | `/cupseasylive/taxstructurelinecreate.php` | High
41 | File | `/dataset/new` | Medium
42 | File | `/devinfo` | Medium
43 | File | `/edit_branch.php` | High
44 | File | `/endpoint/add-user.php` | High
45 | File | `/fcgi/scrut_fcgi.fcgi` | High
46 | File | `/file` | Low
47 | File | `/front/admin/tenancyDetail.php` | High
48 | File | `/goform/setAutoPing` | High
49 | File | `/goform/SetNetControlList` | High
50 | File | `/goform/SetOnlineDevName` | High
51 | File | `/index.php?c=install&m=index&step=2&is_install_db=0` | High
52 | ... | ... | ...

There are 456 more IOA items available (file, library, argument, input value, pattern, network port). Please use our online service to access the data.

## References

The following list contains _external sources_ which discuss the actor and the associated activities:

* https://search.censys.io/hosts/41.216.183.23
* https://search.censys.io/hosts/41.216.183.94
* https://search.censys.io/hosts/45.42.45.10
* https://threatfox.abuse.ch

## Literature

The following _articles_ explain our unique predictive cyber threat intelligence:

* [VulDB Cyber Threat Intelligence Documentation](https://vuldb.com/?kb.cti)
* [Cyber Threat Intelligence - Early Anticipation of Attacks](https://www.scip.ch/en/?labs.20201022)

## License

(c) [1997-2024](https://vuldb.com/?kb.changelog) by [vuldb.com](https://vuldb.com/?kb.about). All data on this page is shared under the license [CC BY-NC-SA 4.0](https://creativecommons.org/licenses/by-nc-sa/4.0/). Questions? Check the [FAQ](https://vuldb.com/?kb.faq), read the [documentation](https://vuldb.com/?kb) or [contact us](https://vuldb.com/?contact)!
