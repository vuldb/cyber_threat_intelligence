# Phobos - Cyber Threat Intelligence

These _indicators_ were reported, collected, and generated during the [VulDB CTI analysis](https://vuldb.com/?kb.cti) of the actor known as [Phobos](https://vuldb.com/?actor.phobos). The _activity monitoring_ correlates data from social media, forums, chat rooms, and darknet markets. It helps to determine associated actors, specific activities, expected intentions, emerging research, and ongoing attacks. Our unique _predictive model_ uses _big data_ to forecast activities and their characteristics.

_Live data_ and more _analysis capabilities_ are available at [https://vuldb.com/?actor.phobos](https://vuldb.com/?actor.phobos)

## Countries

These _countries_ are directly (e.g. origin of attacks) or indirectly (e.g. access by proxy) associated with Phobos:

* [US](https://vuldb.com/?country.us)
* [CN](https://vuldb.com/?country.cn)
* [TR](https://vuldb.com/?country.tr)
* ...

There are 24 more country items available. Please use our online service to access the data.

## IOC - Indicator of Compromise

These _indicators of compromise_ (IOC) indicate associated network resources which are known to be part of research and attack activities of Phobos.

ID | IP address | Hostname | Campaign | Confidence
-- | ---------- | -------- | -------- | ----------
1 | [45.9.74.14](https://vuldb.com/?ip.45.9.74.14) | - | - | High
2 | [147.78.47.224](https://vuldb.com/?ip.147.78.47.224) | undefined.hostname.localhost | - | High
3 | [179.43.140.168](https://vuldb.com/?ip.179.43.140.168) | securehosting.capital | - | High
4 | ... | ... | ... | ...

There are 3 more IOC items available. Please use our online service to access the data.

## TTP - Tactics, Techniques, Procedures

_Tactics, techniques, and procedures_ (TTP) summarize the suspected MITRE ATT&CK techniques used by _Phobos_. This data is unique as it uses our predictive model for actor profiling.

ID | Technique | Weakness | Description | Confidence
-- | --------- | -------- | ----------- | ----------
1 | T1006 | CWE-22, CWE-23, CWE-25, CWE-29, CWE-36, CWE-425 | Path Traversal | High
2 | T1055 | CWE-74, CWE-643 | Improper Neutralization of Data within XPath Expressions | High
3 | T1059 | CWE-88, CWE-94 | Argument Injection | High
4 | T1059.007 | CWE-79, CWE-80 | Basic Cross Site Scripting | High
5 | T1068 | CWE-250, CWE-264, CWE-269, CWE-284 | Execution with Unnecessary Privileges | High
6 | ... | ... | ... | ...

There are 18 more TTP items available. Please use our online service to access the data.

## IOA - Indicator of Attack

These _indicators of attack_ (IOA) list the potential fragments used for technical activities like reconnaissance, exploitation, privilege escalation, and exfiltration by Phobos. This data is unique as it uses our predictive model for actor profiling.

ID | Type | Indicator | Confidence
-- | ---- | --------- | ----------
1 | File | `/#ilang=DE&b=c_smartenergy_swgroups` | High
2 | File | `/.pomerium` | Medium
3 | File | `/Account/login.php` | High
4 | File | `/admin/` | Low
5 | File | `/admin/?page=bike` | High
6 | File | `/admin/?page=musics/manage_music` | High
7 | File | `/admin/ajax.php?action=delete_user` | High
8 | File | `/admin/apply.php` | High
9 | File | `/admin/book-details.php` | High
10 | File | `/admin/bwdates-report-details.php` | High
11 | File | `/Admin/changepassword.php` | High
12 | File | `/admin/cms_content.php` | High
13 | File | `/admin/emp-profile-avatar.php` | High
14 | File | `/admin/forms/option_lists/edit.php` | High
15 | File | `/admin/general-setting` | High
16 | File | `/admin/inquiries/view_inquiry.php` | High
17 | File | `/admin/order.php` | High
18 | File | `/admin/projects/{projectname}/skills/{skillname}/video` | High
19 | File | `/admin/service` | High
20 | File | `/admin/sou.php` | High
21 | File | `/admin/users.php` | High
22 | File | `/adminapi/system/crud` | High
23 | File | `/adminapi/system/file/openfile` | High
24 | File | `/admin_route/dec_service_credits.php` | High
25 | File | `/api/v1/custom_component` | High
26 | File | `/api/v4/teams//channels/deleted` | High
27 | File | `/api/wechat/app_auth` | High
28 | File | `/cancel.php` | Medium
29 | File | `/car-rental-management-system/admin/index.php?page=manage_car` | High
30 | File | `/category.php` | High
31 | File | `/cgi-bin/cstecgi.cgi` | High
32 | File | `/cgi-bin/nas_sharing.cgi` | High
33 | File | `/change-language/de_DE` | High
34 | File | `/classes/Master.php` | High
35 | File | `/classes/Master.php?f=delete_category` | High
36 | File | `/classes/Master.php?f=save_medicine` | High
37 | File | `/classes/SystemSettings.php?f=update_settings` | High
38 | File | `/classes/Users.php?f=delete` | High
39 | File | `/control/register_case.php` | High
40 | File | `/devinfo` | Medium
41 | File | `/dist/index.js` | High
42 | File | `/download` | Medium
43 | File | `/downloadFile.php` | High
44 | File | `/dtale/chart-data/1` | High
45 | File | `/DXR.axd` | Medium
46 | File | `/endpoint/add-folder.php` | High
47 | File | `/etc/shadow` | Medium
48 | File | `/filemanager/upload` | High
49 | File | `/file_manager/login.php` | High
50 | File | `/film-rating.php` | High
51 | File | `/foms/routers/place-order.php` | High
52 | File | `/forum/away.php` | High
53 | File | `/goform/SafeEmailFilter` | High
54 | File | `/goform/SetIpMacBind` | High
55 | File | `/goform/WifiExtraSet` | High
56 | File | `/guestbook` | Medium
57 | File | `/hosts/firewall/ip` | High
58 | File | `/index.jsp#settings` | High
59 | File | `/index.php` | Medium
60 | ... | ... | ...

There are 520 more IOA items available (file, library, argument, input value, pattern, network port). Please use our online service to access the data.

## References

The following list contains _external sources_ which discuss the actor and the associated activities:

* https://exchange.xforce.ibmcloud.com/threats/guid:71f873ec777c3c34917057ccd3b42ed9
* https://www.cisa.gov/news-events/cybersecurity-advisories/aa24-060a

## Literature

The following _articles_ explain our unique predictive cyber threat intelligence:

* [VulDB Cyber Threat Intelligence Documentation](https://vuldb.com/?kb.cti)
* [Cyber Threat Intelligence - Early Anticipation of Attacks](https://www.scip.ch/en/?labs.20201022)

## License

(c) [1997-2024](https://vuldb.com/?kb.changelog) by [vuldb.com](https://vuldb.com/?kb.about). All data on this page is shared under the license [CC BY-NC-SA 4.0](https://creativecommons.org/licenses/by-nc-sa/4.0/). Questions? Check the [FAQ](https://vuldb.com/?kb.faq), read the [documentation](https://vuldb.com/?kb) or [contact us](https://vuldb.com/?contact)!
