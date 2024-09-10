# Grabit - Cyber Threat Intelligence

These _indicators_ were reported, collected, and generated during the [VulDB CTI analysis](https://vuldb.com/?kb.cti) of the actor known as [Grabit](https://vuldb.com/?actor.grabit). The _activity monitoring_ correlates data from social media, forums, chat rooms, and darknet markets. It helps to determine associated actors, specific activities, expected intentions, emerging research, and ongoing attacks. Our unique _predictive model_ uses _big data_ to forecast activities and their characteristics.

_Live data_ and more _analysis capabilities_ are available at [https://vuldb.com/?actor.grabit](https://vuldb.com/?actor.grabit)

## Countries

These _countries_ are directly (e.g. origin of attacks) or indirectly (e.g. access by proxy) associated with Grabit:

* [US](https://vuldb.com/?country.us)
* [CN](https://vuldb.com/?country.cn)
* [TR](https://vuldb.com/?country.tr)
* ...

There are 21 more country items available. Please use our online service to access the data.

## IOC - Indicator of Compromise

These _indicators of compromise_ (IOC) indicate associated network resources which are known to be part of research and attack activities of Grabit.

ID | IP address | Hostname | Campaign | Confidence
-- | ---------- | -------- | -------- | ----------
1 | [31.170.163.242](https://vuldb.com/?ip.31.170.163.242) | mx1.main-hosting.com | - | High
2 | [31.170.164.81](https://vuldb.com/?ip.31.170.164.81) | - | - | High
3 | [31.220.16.147](https://vuldb.com/?ip.31.220.16.147) | - | - | High
4 | ... | ... | ... | ...

There are 5 more IOC items available. Please use our online service to access the data.

## TTP - Tactics, Techniques, Procedures

_Tactics, techniques, and procedures_ (TTP) summarize the suspected MITRE ATT&CK techniques used by _Grabit_. This data is unique as it uses our predictive model for actor profiling.

ID | Technique | Weakness | Description | Confidence
-- | --------- | -------- | ----------- | ----------
1 | T1006 | CWE-21, CWE-22, CWE-23, CWE-25, CWE-29, CWE-36, CWE-425 | Path Traversal | High
2 | T1040 | CWE-319 | Authentication Bypass by Capture-replay | High
3 | T1055 | CWE-74, CWE-643 | Improper Neutralization of Data within XPath Expressions | High
4 | T1059 | CWE-88, CWE-94, CWE-1321 | Argument Injection | High
5 | T1059.007 | CWE-79, CWE-80 | Cross Site Scripting | High
6 | ... | ... | ... | ...

There are 21 more TTP items available. Please use our online service to access the data.

## IOA - Indicator of Attack

These _indicators of attack_ (IOA) list the potential fragments used for technical activities like reconnaissance, exploitation, privilege escalation, and exfiltration by Grabit. This data is unique as it uses our predictive model for actor profiling.

ID | Type | Indicator | Confidence
-- | ---- | --------- | ----------
1 | File | `%SYSTEMDRIVE%\node_modules\.bin\wmic.exe` | High
2 | File | `/#ilang=DE&b=c_smartenergy_swgroups` | High
3 | File | `/.pomerium` | Medium
4 | File | `/Account/login.php` | High
5 | File | `/admin/` | Low
6 | File | `/admin/ajax.php?action=delete_user` | High
7 | File | `/Admin/changepassword.php` | High
8 | File | `/admin/emp-profile-avatar.php` | High
9 | File | `/admin/general-setting` | High
10 | File | `/admin/inquiries/view_inquiry.php` | High
11 | File | `/admin/projects/{projectname}/skills/{skillname}/video` | High
12 | File | `/admin/service` | High
13 | File | `/adminapi/system/crud` | High
14 | File | `/adminapi/system/file/openfile` | High
15 | File | `/admin_route/dec_service_credits.php` | High
16 | File | `/api/v1/custom_component` | High
17 | File | `/api/v4/teams//channels/deleted` | High
18 | File | `/api/wechat/app_auth` | High
19 | File | `/b2b-supermarket/shopping-cart` | High
20 | File | `/cancel.php` | Medium
21 | File | `/category.php` | High
22 | File | `/cgi-bin/cstecgi.cgi` | High
23 | File | `/cgi-bin/nas_sharing.cgi` | High
24 | File | `/change-language/de_DE` | High
25 | File | `/classes/Master.php` | High
26 | File | `/classes/Master.php?f=delete_category` | High
27 | File | `/classes/Master.php?f=save_medicine` | High
28 | File | `/classes/Users.php?f=delete` | High
29 | File | `/control/register_case.php` | High
30 | File | `/debug/pprof` | Medium
31 | File | `/devinfo` | Medium
32 | File | `/dist/index.js` | High
33 | File | `/download` | Medium
34 | File | `/DXR.axd` | Medium
35 | File | `/etc/shadow` | Medium
36 | File | `/forum/away.php` | High
37 | File | `/goform/formSysCmd` | High
38 | File | `/goform/SetIpMacBind` | High
39 | File | `/goform/WifiExtraSet` | High
40 | File | `/guestbook` | Medium
41 | File | `/hosts/firewall/ip` | High
42 | File | `/index.jsp#settings` | High
43 | File | `/index.php` | Medium
44 | File | `/index.php/ccm/system/file/upload` | High
45 | File | `/js/player/dmplayer/dmku/?ac=edit` | High
46 | File | `/labvantage/rc?command=page&page=SampleHistoricalList&_iframename=list&__crc=crc_1701669816260` | High
47 | File | `/labvantage/rc?command=page&page=SampleList&_iframename=list` | High
48 | File | `/librarian/bookdetails.php` | High
49 | ... | ... | ...

There are 421 more IOA items available (file, library, argument, input value, pattern, network port). Please use our online service to access the data.

## References

The following list contains _external sources_ which discuss the actor and the associated activities:

* https://www.threatminer.org/report.php?q=Grabit.pdf&y=2015

## Literature

The following _articles_ explain our unique predictive cyber threat intelligence:

* [VulDB Cyber Threat Intelligence Documentation](https://vuldb.com/?kb.cti)
* [Cyber Threat Intelligence - Early Anticipation of Attacks](https://www.scip.ch/en/?labs.20201022)

## License

(c) [1997-2024](https://vuldb.com/?kb.changelog) by [vuldb.com](https://vuldb.com/?kb.about). All data on this page is shared under the license [CC BY-NC-SA 4.0](https://creativecommons.org/licenses/by-nc-sa/4.0/). Questions? Check the [FAQ](https://vuldb.com/?kb.faq), read the [documentation](https://vuldb.com/?kb) or [contact us](https://vuldb.com/?contact)!
