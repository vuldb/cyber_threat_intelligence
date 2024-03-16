# Volgmer - Cyber Threat Intelligence

These _indicators_ were reported, collected, and generated during the [VulDB CTI analysis](https://vuldb.com/?kb.cti) of the campaign known as _Volgmer_. The _activity monitoring_ correlates data from social media, forums, chat rooms, and darknet markets. It helps to determine associated actors, specific activities, expected intentions, emerging research, and ongoing attacks. Our unique _predictive model_ uses _big data_ to forecast activities and their characteristics.

_Live data_ and more _analysis capabilities_ are available at [https://vuldb.com/?actor](https://vuldb.com/?actor)

## Countries

These _countries_ are directly (e.g. origin of attacks) or indirectly (e.g. access by proxy) associated with Volgmer:

* [IN](https://vuldb.com/?country.in)
* [US](https://vuldb.com/?country.us)
* [IR](https://vuldb.com/?country.ir)

## Actors

These _actors_ are associated with Volgmer or other actors linked to the campaign.

ID | Actor | Confidence
-- | ----- | ----------
1 | [Lazarus](https://vuldb.com/?actor.lazarus) | High

## IOC - Indicator of Compromise

These _indicators of compromise_ (IOC) indicate associated network resources which are known to be part of research and attack activities of Volgmer.

ID | IP address | Hostname | Actor | Confidence
-- | ---------- | -------- | ----- | ----------
1 | [14.102.46.3](https://vuldb.com/?ip.14.102.46.3) | - | [Lazarus](https://vuldb.com/?actor.lazarus) | High
2 | [14.139.125.214](https://vuldb.com/?ip.14.139.125.214) | - | [Lazarus](https://vuldb.com/?actor.lazarus) | High
3 | [14.141.129.116](https://vuldb.com/?ip.14.141.129.116) | 14.141.129.116.static-Delhi.vsnl.net.in | [Lazarus](https://vuldb.com/?actor.lazarus) | High
4 | [27.114.187.37](https://vuldb.com/?ip.27.114.187.37) | - | [Lazarus](https://vuldb.com/?actor.lazarus) | High
5 | [31.146.82.22](https://vuldb.com/?ip.31.146.82.22) | 31-146-82-22.dsl.utg.ge | [Lazarus](https://vuldb.com/?actor.lazarus) | High
6 | [37.98.114.90](https://vuldb.com/?ip.37.98.114.90) | 90.mobinnet.net | [Lazarus](https://vuldb.com/?actor.lazarus) | High
7 | [37.216.67.155](https://vuldb.com/?ip.37.216.67.155) | - | [Lazarus](https://vuldb.com/?actor.lazarus) | High
8 | [37.235.21.166](https://vuldb.com/?ip.37.235.21.166) | - | [Lazarus](https://vuldb.com/?actor.lazarus) | High
9 | [43.249.216.6](https://vuldb.com/?ip.43.249.216.6) | - | [Lazarus](https://vuldb.com/?actor.lazarus) | High
10 | [45.118.34.215](https://vuldb.com/?ip.45.118.34.215) | - | [Lazarus](https://vuldb.com/?actor.lazarus) | High
11 | [45.124.169.36](https://vuldb.com/?ip.45.124.169.36) | - | [Lazarus](https://vuldb.com/?actor.lazarus) | High
12 | [58.82.155.98](https://vuldb.com/?ip.58.82.155.98) | 98.155.82.58.static-corp.jastel.co.th | [Lazarus](https://vuldb.com/?actor.lazarus) | High
13 | [58.185.197.210](https://vuldb.com/?ip.58.185.197.210) | - | [Lazarus](https://vuldb.com/?actor.lazarus) | High
14 | [61.91.47.142](https://vuldb.com/?ip.61.91.47.142) | 61-91-47-142.static.asianet.co.th | [Lazarus](https://vuldb.com/?actor.lazarus) | High
15 | [61.153.146.207](https://vuldb.com/?ip.61.153.146.207) | - | [Lazarus](https://vuldb.com/?actor.lazarus) | High
16 | [78.38.114.15](https://vuldb.com/?ip.78.38.114.15) | - | [Lazarus](https://vuldb.com/?actor.lazarus) | High
17 | [78.38.182.242](https://vuldb.com/?ip.78.38.182.242) | - | [Lazarus](https://vuldb.com/?actor.lazarus) | High
18 | [78.39.125.67](https://vuldb.com/?ip.78.39.125.67) | - | [Lazarus](https://vuldb.com/?actor.lazarus) | High
19 | [80.95.219.72](https://vuldb.com/?ip.80.95.219.72) | - | [Lazarus](https://vuldb.com/?actor.lazarus) | High
20 | [80.191.171.32](https://vuldb.com/?ip.80.191.171.32) | - | [Lazarus](https://vuldb.com/?actor.lazarus) | High
21 | [82.129.240.148](https://vuldb.com/?ip.82.129.240.148) | - | [Lazarus](https://vuldb.com/?actor.lazarus) | High
22 | [82.201.131.124](https://vuldb.com/?ip.82.201.131.124) | host-82-201-131-124.static.link.net | [Lazarus](https://vuldb.com/?actor.lazarus) | High
23 | ... | ... | ... | ...

There are 86 more IOC items available. Please use our online service to access the data.

## TTP - Tactics, Techniques, Procedures

_Tactics, techniques, and procedures_ (TTP) summarize the suspected MITRE ATT&CK techniques used within Volgmer. This data is unique as it uses our predictive model for actor profiling.

ID | Technique | Weakness | Description | Confidence
-- | --------- | -------- | ----------- | ----------
1 | T1006 | CWE-21, CWE-22, CWE-23, CWE-24 | Path Traversal | High
2 | T1040 | CWE-319 | Authentication Bypass by Capture-replay | High
3 | T1055 | CWE-74 | Injection | High
4 | T1059 | CWE-88, CWE-94, CWE-1321 | Argument Injection | High
5 | T1059.007 | CWE-79, CWE-80 | Cross Site Scripting | High
6 | ... | ... | ... | ...

There are 22 more TTP items available. Please use our online service to access the data.

## IOA - Indicator of Attack

These _indicators of attack_ (IOA) list the potential fragments used for technical activities like reconnaissance, exploitation, privilege escalation, and exfiltration during Volgmer. This data is unique as it uses our predictive model for actor profiling.

ID | Type | Indicator | Confidence
-- | ---- | --------- | ----------
1 | File | `$HOME/.terminfo` | High
2 | File | `/.env` | Low
3 | File | `/.vnc/sesman_${username}_passwd` | High
4 | File | `/admin/` | Low
5 | File | `/admin/addemployee.php` | High
6 | File | `/admin/add_exercises.php` | High
7 | File | `/admin/add_trainers.php` | High
8 | File | `/admin/admin_user.php` | High
9 | File | `/admin/api/admin/articles/` | High
10 | File | `/admin/api/theme-edit/` | High
11 | File | `/admin/borrow_add.php` | High
12 | File | `/admin/category_row.php` | High
13 | File | `/Admin/createClass.php` | High
14 | File | `/admin/edit.php` | High
15 | File | `/admin/login.php` | High
16 | File | `/admin/request-received-bydonar.php` | High
17 | File | `/admin/settings.php` | High
18 | File | `/admin/students/manage.php` | High
19 | File | `/api/public/signup` | High
20 | File | `/api/v1/attack` | High
21 | File | `/api/v1/bait/set` | High
22 | File | `/api/v2/open/tablesInfo` | High
23 | File | `/boaform/device_reset.cgi` | High
24 | File | `/boaform/wlan_basic_set.cgi` | High
25 | File | `/category.php` | High
26 | File | `/classes/Users.php?f=save` | High
27 | File | `/course/filterRecords/` | High
28 | File | `/csms/?page=contact_us` | High
29 | File | `/csms/admin/?page=user/list` | High
30 | File | `/cwms/classes/Master.php?f=save_contact` | High
31 | File | `/ebics-server/ebics.aspx` | High
32 | File | `/edituser.php` | High
33 | File | `/employeeview.php` | High
34 | File | `/Employer/EditProfile.php` | High
35 | File | `/Employer/ManageJob.php` | High
36 | File | `/forum/away.php` | High
37 | File | `/FuguHub/cmsdocs/` | High
38 | File | `/inc/jquery/uploadify/uploadify.php` | High
39 | File | `/index.jsp#settings` | High
40 | File | `/inquiries/view_inquiry.php` | High
41 | File | `/install/` | Medium
42 | File | `/investigation/delete/` | High
43 | File | `/leave_system/classes/SystemSettings.php?f=update_settings` | High
44 | File | `/login.php` | Medium
45 | File | `/loginVaLidation.php` | High
46 | File | `/member/member_edit.php` | High
47 | File | `/MicroStrategyWS/happyaxis.jsp` | High
48 | File | `/mims/app/addcustomerHandler.php` | High
49 | File | `/mkshope/login.php` | High
50 | File | `/myprofile.php` | High
51 | File | `/nagiosxi/admin/banner_message-ajaxhelper.php` | High
52 | File | `/oauth/idp/.well-known/openid-configuration` | High
53 | File | `/obs/bookPerPub.php` | High
54 | File | `/omos/admin/?page=user/list` | High
55 | File | `/one_church/churchprofile.php` | High
56 | ... | ... | ...

There are 493 more IOA items available (file, library, argument, input value, pattern, network port). Please use our online service to access the data.

## References

The following list contains _external sources_ which discuss the campaign and the associated activities:

* https://us-cert.cisa.gov/ncas/alerts/TA17-318B

## Literature

The following _articles_ explain our unique predictive cyber threat intelligence:

* [VulDB Cyber Threat Intelligence Documentation](https://vuldb.com/?kb.cti)
* [Cyber Threat Intelligence - Early Anticipation of Attacks](https://www.scip.ch/en/?labs.20201022)

## License

(c) [1997-2024](https://vuldb.com/?kb.changelog) by [vuldb.com](https://vuldb.com/?kb.about). All data on this page is shared under the license [CC BY-NC-SA 4.0](https://creativecommons.org/licenses/by-nc-sa/4.0/). Questions? Check the [FAQ](https://vuldb.com/?kb.faq), read the [documentation](https://vuldb.com/?kb) or [contact us](https://vuldb.com/?contact)!
