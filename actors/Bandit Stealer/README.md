# Bandit Stealer - Cyber Threat Intelligence

These _indicators_ were reported, collected, and generated during the [VulDB CTI analysis](https://vuldb.com/?kb.cti) of the actor known as [Bandit Stealer](https://vuldb.com/?actor.bandit_stealer). The _activity monitoring_ correlates data from social media, forums, chat rooms, and darknet markets. It helps to determine associated actors, specific activities, expected intentions, emerging research, and ongoing attacks. Our unique _predictive model_ uses _big data_ to forecast activities and their characteristics.

_Live data_ and more _analysis capabilities_ are available at [https://vuldb.com/?actor.bandit_stealer](https://vuldb.com/?actor.bandit_stealer)

## Countries

These _countries_ are directly (e.g. origin of attacks) or indirectly (e.g. access by proxy) associated with Bandit Stealer:

* [SH](https://vuldb.com/?country.sh)
* [US](https://vuldb.com/?country.us)
* [CN](https://vuldb.com/?country.cn)
* ...

There are 8 more country items available. Please use our online service to access the data.

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
1 | T1006 | CWE-22, CWE-23, CWE-24, CWE-36 | Path Traversal | High
2 | T1055 | CWE-74 | Improper Neutralization of Data within XPath Expressions | High
3 | T1059 | CWE-94, CWE-1321 | Argument Injection | High
4 | T1059.007 | CWE-79, CWE-80 | Cross Site Scripting | High
5 | T1068 | CWE-264, CWE-269, CWE-272, CWE-284 | Execution with Unnecessary Privileges | High
6 | ... | ... | ... | ...

There are 21 more TTP items available. Please use our online service to access the data.

## IOA - Indicator of Attack

These _indicators of attack_ (IOA) list the potential fragments used for technical activities like reconnaissance, exploitation, privilege escalation, and exfiltration by Bandit Stealer. This data is unique as it uses our predictive model for actor profiling.

ID | Type | Indicator | Confidence
-- | ---- | --------- | ----------
1 | File | `/3g/index.php` | High
2 | File | `/accounts/login` | High
3 | File | `/accounts_con/register_account` | High
4 | File | `/add_members.php` | High
5 | File | `/admin.php` | Medium
6 | File | `/admin/` | Low
7 | File | `/admin/action/new-feed.php` | High
8 | File | `/admin/add_ikev2.php` | High
9 | File | `/admin/adminHome.php` | High
10 | File | `/admin/book_add.php` | High
11 | File | `/Admin/changepassword.php` | High
12 | File | `/admin/content/data` | High
13 | File | `/admin/court` | Medium
14 | File | `/admin/database/backup` | High
15 | File | `/Admin/edit_profile.php` | High
16 | File | `/admin/file/edit.do` | High
17 | File | `/admin/general-setting` | High
18 | File | `/admin/index.php?act=reset_admin_psw` | High
19 | File | `/admin/item/view_item.php` | High
20 | File | `/admin/list_crl_conf` | High
21 | File | `/admin/list_onlineuser.php` | High
22 | File | `/Admin/login.php` | High
23 | File | `/admin/reports/index.php` | High
24 | File | `/admin/role` | Medium
25 | File | `/admin/suppliers/view_details.php` | High
26 | File | `/admin/users.php` | High
27 | File | `/admin/users_photo.php` | High
28 | File | `/admin/vendor` | High
29 | File | `/adminapi/system/crud` | High
30 | File | `/adminpanel/admin/facebox_modal/updateExaminee.php` | High
31 | File | `/api.php` | Medium
32 | File | `/api/admin` | Medium
33 | File | `/api/blade-user/export-user` | High
34 | File | `/api/email/update` | High
35 | File | `/api/proxy` | Medium
36 | File | `/application/index/controller/File.php` | High
37 | File | `/application/index/controller/Icon.php` | High
38 | File | `/application/websocket/controller/Setting.php` | High
39 | File | `/apps/system/router/upload.go` | High
40 | File | `/Attachment/fromImageUrl` | High
41 | File | `/b2b-supermarket/catalog/all-products` | High
42 | File | `/b2b-supermarket/shopping-cart` | High
43 | File | `/bin/boa` | Medium
44 | File | `/cap.js` | Low
45 | File | `/cgi-bin/cstecgi.cgi` | High
46 | File | `/cgi-bin/cstecgi.cgi?action=login` | High
47 | File | `/cgi-bin/info.cgi` | High
48 | File | `/cgi-bin/nas_sharing.cgi` | High
49 | File | `/cgi-bin/wlogin.cgi` | High
50 | File | `/classes/Master.php? f=save_medicine` | High
51 | File | `/classes/Users.php?f=save` | High
52 | File | `/content/list.do` | High
53 | File | `/controller/company/Index.php#sendCompanyLogo` | High
54 | File | `/cupseasylive/costcentermodify.php` | High
55 | File | `/cupseasylive/itemmodify.php` | High
56 | File | `/cupseasylive/statelist.php` | High
57 | ... | ... | ...

There are 497 more IOA items available (file, library, argument, input value, pattern, network port). Please use our online service to access the data.

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
