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
1 | T1006 | CWE-22, CWE-23, CWE-24, CWE-27, CWE-29, CWE-35, CWE-41, CWE-425 | Path Traversal | High
2 | T1040 | CWE-294, CWE-319 | Authentication Bypass by Capture-replay | High
3 | T1055 | CWE-74 | Improper Neutralization of Data within XPath Expressions | High
4 | T1059 | CWE-88, CWE-94, CWE-1321 | Argument Injection | High
5 | T1059.007 | CWE-79, CWE-80 | Cross Site Scripting | High
6 | ... | ... | ... | ...

There are 20 more TTP items available. Please use our online service to access the data.

## IOA - Indicator of Attack

These _indicators of attack_ (IOA) list the potential fragments used for technical activities like reconnaissance, exploitation, privilege escalation, and exfiltration by Bandit Stealer. This data is unique as it uses our predictive model for actor profiling.

ID | Type | Indicator | Confidence
-- | ---- | --------- | ----------
1 | File | `/3g/index.php` | High
2 | File | `/?import` | Medium
3 | File | `/Admin/add-admin.php` | High
4 | File | `/admin/add_ikev2.php` | High
5 | File | `/admin/adminHome.php` | High
6 | File | `/admin/ajax.php?action=login` | High
7 | File | `/admin/category/view_category.php` | High
8 | File | `/Admin/changepassword.php` | High
9 | File | `/admin/cmsTemplate/replace` | High
10 | File | `/admin/cmsTemplate/savePlace` | High
11 | File | `/admin/cmsTemplate/savePlaceMetaData` | High
12 | File | `/admin/court` | Medium
13 | File | `/Admin/edit_profile.php` | High
14 | File | `/admin/emp-profile-avatar.php` | High
15 | File | `/admin/foreigner-search.php` | High
16 | File | `/admin/general-setting` | High
17 | File | `/admin/item/view_item.php` | High
18 | File | `/admin/list_crl_conf` | High
19 | File | `/Admin/login.php` | High
20 | File | `/admin/menu.php` | High
21 | File | `/admin/moneyRecord_deal.php?mudi=delRecord` | High
22 | File | `/admin/normal-search.php` | High
23 | File | `/admin/products/index.php` | High
24 | File | `/admin/role` | Medium
25 | File | `/admin/suppliers/view_details.php` | High
26 | File | `/admin/template` | High
27 | File | `/admin/template/update` | High
28 | File | `/admin/user/user-move-run.php` | High
29 | File | `/admin/userGroup_deal.php?mudi=del` | High
30 | File | `/admin/users.php` | High
31 | File | `/admin/vendor` | High
32 | File | `/adminpanel/admin/facebox_modal/updateExaminee.php` | High
33 | File | `/adminpanel/admin/query/addCourseExe.php` | High
34 | File | `/api/admin` | Medium
35 | File | `/api/admin/user?id` | High
36 | File | `/api/blade-user/export-user` | High
37 | File | `/api/deploy/upload` | High
38 | File | `/api/deploy/upload /api/database/upload` | High
39 | File | `/api/dept/build` | High
40 | File | `/api/proxy` | Medium
41 | File | `/app/uploading/upload-mp3.php` | High
42 | File | `/application/websocket/controller/Setting.php` | High
43 | File | `/audio/transcriptions` | High
44 | File | `/authMonitCallcenter` | High
45 | File | `/b2b-supermarket/shopping-cart` | High
46 | File | `/cap.js` | Low
47 | File | `/cgi-bin/cstecgi.cgi` | High
48 | File | `/cgi-bin/cstecgi.cgi?action=save&setting` | High
49 | File | `/cgi-bin/ExportSettings.sh` | High
50 | File | `/cgi-bin/hd_config.cgi` | High
51 | File | `/cgi-bin/info.cgi` | High
52 | File | `/cgi-bin/nas_sharing.cgi` | High
53 | File | `/cgi-bin/photocenter_mgr.cgi` | High
54 | File | `/cgi-bin/tosei_kikai.php` | High
55 | File | `/cgi-bin/webdav_mgr.cgi` | High
56 | File | `/change_password.php` | High
57 | File | `/checkout` | Medium
58 | File | `/classes/Master.php` | High
59 | File | `/classes/Master.php?f=log_visitor` | High
60 | File | `/classes/Master.php?f=view_category` | High
61 | File | `/classes/SystemSettings.php?f=update_settings` | High
62 | File | `/classes/Users.php?f=save` | High
63 | File | `/classes/Users.php?f=save_client` | High
64 | File | `/cm/update_rows/page?id=2` | High
65 | ... | ... | ...

There are 568 more IOA items available (file, library, argument, input value, pattern, network port). Please use our online service to access the data.

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
