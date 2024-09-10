# Tokelau Unknown - Cyber Threat Intelligence

These _indicators_ were reported, collected, and generated during the [VulDB CTI analysis](https://vuldb.com/?kb.cti) of the actor known as [Tokelau Unknown](https://vuldb.com/?actor.tokelau_unknown). The _activity monitoring_ correlates data from social media, forums, chat rooms, and darknet markets. It helps to determine associated actors, specific activities, expected intentions, emerging research, and ongoing attacks. Our unique _predictive model_ uses _big data_ to forecast activities and their characteristics.

_Live data_ and more _analysis capabilities_ are available at [https://vuldb.com/?actor.tokelau_unknown](https://vuldb.com/?actor.tokelau_unknown)

## Countries

These _countries_ are directly (e.g. origin of attacks) or indirectly (e.g. access by proxy) associated with Tokelau Unknown:

* [US](https://vuldb.com/?country.us)
* [CN](https://vuldb.com/?country.cn)
* [TR](https://vuldb.com/?country.tr)
* ...

There are 21 more country items available. Please use our online service to access the data.

## IOC - Indicator of Compromise

These _indicators of compromise_ (IOC) indicate associated network resources which are known to be part of research and attack activities of Tokelau Unknown.

ID | IP address | Hostname | Campaign | Confidence
-- | ---------- | -------- | -------- | ----------
1 | [5.62.56.224](https://vuldb.com/?ip.5.62.56.224) | r-224-56-62-5.consumer-pool.prcdn.net | - | High
2 | [5.62.58.204](https://vuldb.com/?ip.5.62.58.204) | r-204-58-62-5.consumer-pool.prcdn.net | - | High
3 | [27.96.24.0](https://vuldb.com/?ip.27.96.24.0) | - | - | High
4 | ... | ... | ... | ...

There are 9 more IOC items available. Please use our online service to access the data.

## TTP - Tactics, Techniques, Procedures

_Tactics, techniques, and procedures_ (TTP) summarize the suspected MITRE ATT&CK techniques used by _Tokelau Unknown_. This data is unique as it uses our predictive model for actor profiling.

ID | Technique | Weakness | Description | Confidence
-- | --------- | -------- | ----------- | ----------
1 | T1006 | CWE-21, CWE-22, CWE-23, CWE-25, CWE-29, CWE-36, CWE-425 | Path Traversal | High
2 | T1040 | CWE-319 | Authentication Bypass by Capture-replay | High
3 | T1055 | CWE-74, CWE-643 | Improper Neutralization of Data within XPath Expressions | High
4 | T1059 | CWE-88, CWE-94, CWE-1321 | Argument Injection | High
5 | T1059.007 | CWE-79, CWE-80 | Cross Site Scripting | High
6 | ... | ... | ... | ...

There are 20 more TTP items available. Please use our online service to access the data.

## IOA - Indicator of Attack

These _indicators of attack_ (IOA) list the potential fragments used for technical activities like reconnaissance, exploitation, privilege escalation, and exfiltration by Tokelau Unknown. This data is unique as it uses our predictive model for actor profiling.

ID | Type | Indicator | Confidence
-- | ---- | --------- | ----------
1 | File | `%SYSTEMDRIVE%\node_modules\.bin\wmic.exe` | High
2 | File | `/#ilang=DE&b=c_smartenergy_swgroups` | High
3 | File | `/.pomerium` | Medium
4 | File | `/Account/login.php` | High
5 | File | `/admin/` | Low
6 | File | `/admin/ajax.php?action=delete_user` | High
7 | File | `/Admin/changepassword.php` | High
8 | File | `/admin/general-setting` | High
9 | File | `/admin/inquiries/view_inquiry.php` | High
10 | File | `/admin/projects/{projectname}/skills/{skillname}/video` | High
11 | File | `/admin/service` | High
12 | File | `/adminapi/system/crud` | High
13 | File | `/adminapi/system/file/openfile` | High
14 | File | `/admin_route/dec_service_credits.php` | High
15 | File | `/api/v1/custom_component` | High
16 | File | `/api/v4/teams//channels/deleted` | High
17 | File | `/api/wechat/app_auth` | High
18 | File | `/b2b-supermarket/shopping-cart` | High
19 | File | `/cancel.php` | Medium
20 | File | `/category.php` | High
21 | File | `/cgi-bin/cstecgi.cgi` | High
22 | File | `/cgi-bin/nas_sharing.cgi` | High
23 | File | `/change-language/de_DE` | High
24 | File | `/classes/Master.php` | High
25 | File | `/classes/Master.php?f=delete_category` | High
26 | File | `/classes/Master.php?f=save_medicine` | High
27 | File | `/classes/Users.php?f=delete` | High
28 | File | `/control/register_case.php` | High
29 | File | `/debug/pprof` | Medium
30 | File | `/devinfo` | Medium
31 | File | `/dist/index.js` | High
32 | File | `/download` | Medium
33 | File | `/DXR.axd` | Medium
34 | File | `/etc/shadow` | Medium
35 | File | `/forum/away.php` | High
36 | File | `/goform/formSysCmd` | High
37 | File | `/goform/SetIpMacBind` | High
38 | File | `/goform/WifiExtraSet` | High
39 | File | `/guestbook` | Medium
40 | File | `/hosts/firewall/ip` | High
41 | File | `/index.jsp#settings` | High
42 | File | `/index.php` | Medium
43 | File | `/index.php/ccm/system/file/upload` | High
44 | File | `/js/player/dmplayer/dmku/?ac=edit` | High
45 | File | `/labvantage/rc?command=page&page=SampleHistoricalList&_iframename=list&__crc=crc_1701669816260` | High
46 | File | `/labvantage/rc?command=page&page=SampleList&_iframename=list` | High
47 | File | `/librarian/bookdetails.php` | High
48 | File | `/log/decodmail.php` | High
49 | ... | ... | ...

There are 430 more IOA items available (file, library, argument, input value, pattern, network port). Please use our online service to access the data.

## References

The following list contains _external sources_ which discuss the actor and the associated activities:

* https://github.com/firehol/blocklist-ipsets/blob/master/geolite2_country/country_tk.netset
* https://github.com/firehol/blocklist-ipsets/blob/master/ip2location_country/ip2location_country_tk.netset
* https://github.com/firehol/blocklist-ipsets/blob/master/ipip_country/ipip_country_tk.netset

## Literature

The following _articles_ explain our unique predictive cyber threat intelligence:

* [VulDB Cyber Threat Intelligence Documentation](https://vuldb.com/?kb.cti)
* [Cyber Threat Intelligence - Early Anticipation of Attacks](https://www.scip.ch/en/?labs.20201022)

## License

(c) [1997-2024](https://vuldb.com/?kb.changelog) by [vuldb.com](https://vuldb.com/?kb.about). All data on this page is shared under the license [CC BY-NC-SA 4.0](https://creativecommons.org/licenses/by-nc-sa/4.0/). Questions? Check the [FAQ](https://vuldb.com/?kb.faq), read the [documentation](https://vuldb.com/?kb) or [contact us](https://vuldb.com/?contact)!
