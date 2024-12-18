# Spalax - Cyber Threat Intelligence

These _indicators_ were reported, collected, and generated during the [VulDB CTI analysis](https://vuldb.com/?kb.cti) of the campaign known as _Spalax_. The _activity monitoring_ correlates data from social media, forums, chat rooms, and darknet markets. It helps to determine associated actors, specific activities, expected intentions, emerging research, and ongoing attacks. Our unique _predictive model_ uses _big data_ to forecast activities and their characteristics.

_Live data_ and more _analysis capabilities_ are available at [https://vuldb.com/?actor](https://vuldb.com/?actor)

## Countries

These _countries_ are directly (e.g. origin of attacks) or indirectly (e.g. access by proxy) associated with Spalax:

* [US](https://vuldb.com/?country.us)
* [CN](https://vuldb.com/?country.cn)
* [TR](https://vuldb.com/?country.tr)
* ...

There are 25 more country items available. Please use our online service to access the data.

## Actors

These _actors_ are associated with Spalax or other actors linked to the campaign.

ID | Actor | Confidence
-- | ----- | ----------
1 | [Spalax](https://vuldb.com/?actor.spalax) | High

## IOC - Indicator of Compromise

These _indicators of compromise_ (IOC) indicate associated network resources which are known to be part of research and attack activities of Spalax.

ID | IP address | Hostname | Actor | Confidence
-- | ---------- | -------- | ----- | ----------
1 | [128.90.108.132](https://vuldb.com/?ip.128.90.108.132) | undefined.hostname.localhost | [Spalax](https://vuldb.com/?actor.spalax) | High
2 | [128.90.108.177](https://vuldb.com/?ip.128.90.108.177) | undefined.hostname.localhost | [Spalax](https://vuldb.com/?actor.spalax) | High
3 | [128.90.112.34](https://vuldb.com/?ip.128.90.112.34) | undefined.hostname.localhost | [Spalax](https://vuldb.com/?actor.spalax) | High
4 | [128.90.112.142](https://vuldb.com/?ip.128.90.112.142) | undefined.hostname.localhost | [Spalax](https://vuldb.com/?actor.spalax) | High
5 | [128.90.115.100](https://vuldb.com/?ip.128.90.115.100) | undefined.hostname.localhost | [Spalax](https://vuldb.com/?actor.spalax) | High
6 | [128.90.115.244](https://vuldb.com/?ip.128.90.115.244) | undefined.hostname.localhost | [Spalax](https://vuldb.com/?actor.spalax) | High
7 | [179.14.171.7](https://vuldb.com/?ip.179.14.171.7) | Dinamic-Tigo-179-14-171-7.tigo.com.co | [Spalax](https://vuldb.com/?actor.spalax) | High
8 | [179.14.173.93](https://vuldb.com/?ip.179.14.173.93) | Dinamic-Tigo-179-14-173-93.tigo.com.co | [Spalax](https://vuldb.com/?actor.spalax) | High
9 | [181.49.90.193](https://vuldb.com/?ip.181.49.90.193) | dynamic-ip-1814990193.cable.net.co | [Spalax](https://vuldb.com/?actor.spalax) | High
10 | [181.52.100.157](https://vuldb.com/?ip.181.52.100.157) | static-ip-cr181520100157.cable.net.co | [Spalax](https://vuldb.com/?actor.spalax) | High
11 | [181.52.102.87](https://vuldb.com/?ip.181.52.102.87) | static-ip-cr18152010287.cable.net.co | [Spalax](https://vuldb.com/?actor.spalax) | High
12 | [181.52.103.140](https://vuldb.com/?ip.181.52.103.140) | static-ip-cr181520103140.cable.net.co | [Spalax](https://vuldb.com/?actor.spalax) | High
13 | [181.52.104.2](https://vuldb.com/?ip.181.52.104.2) | static-ip-cr1815201042.cable.net.co | [Spalax](https://vuldb.com/?actor.spalax) | High
14 | ... | ... | ... | ...

There are 51 more IOC items available. Please use our online service to access the data.

## TTP - Tactics, Techniques, Procedures

_Tactics, techniques, and procedures_ (TTP) summarize the suspected MITRE ATT&CK techniques used within Spalax. This data is unique as it uses our predictive model for actor profiling.

ID | Technique | Weakness | Description | Confidence
-- | --------- | -------- | ----------- | ----------
1 | T1006 | CWE-22, CWE-23, CWE-25, CWE-29, CWE-36, CWE-425 | Path Traversal | High
2 | T1055 | CWE-74, CWE-643 | Improper Neutralization of Data within XPath Expressions | High
3 | T1059 | CWE-88, CWE-94 | Argument Injection | High
4 | T1059.007 | CWE-79, CWE-80 | Cross Site Scripting | High
5 | ... | ... | ... | ...

There are 18 more TTP items available. Please use our online service to access the data.

## IOA - Indicator of Attack

These _indicators of attack_ (IOA) list the potential fragments used for technical activities like reconnaissance, exploitation, privilege escalation, and exfiltration during Spalax. This data is unique as it uses our predictive model for actor profiling.

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
28 | File | `/b2b-supermarket/shopping-cart` | High
29 | File | `/cancel.php` | Medium
30 | File | `/car-rental-management-system/admin/index.php?page=manage_car` | High
31 | File | `/category.php` | High
32 | File | `/cgi-bin/cstecgi.cgi` | High
33 | File | `/cgi-bin/nas_sharing.cgi` | High
34 | File | `/change-language/de_DE` | High
35 | File | `/classes/Master.php` | High
36 | File | `/classes/Master.php?f=delete_category` | High
37 | File | `/classes/Master.php?f=save_medicine` | High
38 | File | `/classes/SystemSettings.php?f=update_settings` | High
39 | File | `/classes/Users.php?f=delete` | High
40 | File | `/control/register_case.php` | High
41 | File | `/devinfo` | Medium
42 | File | `/dist/index.js` | High
43 | File | `/download` | Medium
44 | File | `/downloadFile.php` | High
45 | File | `/dtale/chart-data/1` | High
46 | File | `/DXR.axd` | Medium
47 | File | `/endpoint/add-folder.php` | High
48 | File | `/etc/shadow` | Medium
49 | File | `/file_manager/login.php` | High
50 | File | `/film-rating.php` | High
51 | File | `/foms/routers/place-order.php` | High
52 | File | `/forum/away.php` | High
53 | File | `/goform/SetIpMacBind` | High
54 | File | `/goform/WifiExtraSet` | High
55 | File | `/guestbook` | Medium
56 | File | `/hosts/firewall/ip` | High
57 | File | `/index.jsp#settings` | High
58 | File | `/index.php` | Medium
59 | ... | ... | ...

There are 519 more IOA items available (file, library, argument, input value, pattern, network port). Please use our online service to access the data.

## References

The following list contains _external sources_ which discuss the campaign and the associated activities:

* https://github.com/eset/malware-ioc/tree/master/spalax

## Literature

The following _articles_ explain our unique predictive cyber threat intelligence:

* [VulDB Cyber Threat Intelligence Documentation](https://vuldb.com/?kb.cti)
* [Cyber Threat Intelligence - Early Anticipation of Attacks](https://www.scip.ch/en/?labs.20201022)

## License

(c) [1997-2024](https://vuldb.com/?kb.changelog) by [vuldb.com](https://vuldb.com/?kb.about). All data on this page is shared under the license [CC BY-NC-SA 4.0](https://creativecommons.org/licenses/by-nc-sa/4.0/). Questions? Check the [FAQ](https://vuldb.com/?kb.faq), read the [documentation](https://vuldb.com/?kb) or [contact us](https://vuldb.com/?contact)!
