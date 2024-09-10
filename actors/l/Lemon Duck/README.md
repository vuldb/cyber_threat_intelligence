# Lemon Duck - Cyber Threat Intelligence

These _indicators_ were reported, collected, and generated during the [VulDB CTI analysis](https://vuldb.com/?kb.cti) of the actor known as [Lemon Duck](https://vuldb.com/?actor.lemon_duck). The _activity monitoring_ correlates data from social media, forums, chat rooms, and darknet markets. It helps to determine associated actors, specific activities, expected intentions, emerging research, and ongoing attacks. Our unique _predictive model_ uses _big data_ to forecast activities and their characteristics.

_Live data_ and more _analysis capabilities_ are available at [https://vuldb.com/?actor.lemon_duck](https://vuldb.com/?actor.lemon_duck)

## Countries

These _countries_ are directly (e.g. origin of attacks) or indirectly (e.g. access by proxy) associated with Lemon Duck:

* [VN](https://vuldb.com/?country.vn)
* [CN](https://vuldb.com/?country.cn)
* [US](https://vuldb.com/?country.us)

## IOC - Indicator of Compromise

These _indicators of compromise_ (IOC) indicate associated network resources which are known to be part of research and attack activities of Lemon Duck.

ID | IP address | Hostname | Campaign | Confidence
-- | ---------- | -------- | -------- | ----------
1 | [1.202.15.246](https://vuldb.com/?ip.1.202.15.246) | 246.15.202.1.static.bjtelecom.net | - | High
2 | [27.195.157.70](https://vuldb.com/?ip.27.195.157.70) | - | - | High
3 | [36.48.94.254](https://vuldb.com/?ip.36.48.94.254) | - | - | High
4 | [36.110.1.222](https://vuldb.com/?ip.36.110.1.222) | 222.1.110.36.static.bjtelecom.net | - | High
5 | [40.68.42.171](https://vuldb.com/?ip.40.68.42.171) | - | - | High
6 | [42.7.4.88](https://vuldb.com/?ip.42.7.4.88) | - | - | High
7 | [42.7.31.243](https://vuldb.com/?ip.42.7.31.243) | - | - | High
8 | [42.176.133.183](https://vuldb.com/?ip.42.176.133.183) | - | - | High
9 | [49.71.208.124](https://vuldb.com/?ip.49.71.208.124) | - | - | High
10 | [49.147.72.67](https://vuldb.com/?ip.49.147.72.67) | dsl.49.148.72.67.pldt.net | - | High
11 | [51.36.170.221](https://vuldb.com/?ip.51.36.170.221) | - | - | High
12 | [58.56.135.198](https://vuldb.com/?ip.58.56.135.198) | - | - | High
13 | [58.62.125.245](https://vuldb.com/?ip.58.62.125.245) | - | - | High
14 | [58.221.24.178](https://vuldb.com/?ip.58.221.24.178) | - | - | High
15 | [58.251.2.115](https://vuldb.com/?ip.58.251.2.115) | reverse.gdsz.cncnet.net | - | High
16 | [59.111.181.116](https://vuldb.com/?ip.59.111.181.116) | - | - | High
17 | [59.175.154.97](https://vuldb.com/?ip.59.175.154.97) | - | - | High
18 | [60.10.56.169](https://vuldb.com/?ip.60.10.56.169) | hebei.10.60.in-addr.arpa | - | High
19 | [60.10.134.93](https://vuldb.com/?ip.60.10.134.93) | hebei.10.60.in-addr.arpa | - | High
20 | [60.19.236.50](https://vuldb.com/?ip.60.19.236.50) | - | - | High
21 | ... | ... | ... | ...

There are 78 more IOC items available. Please use our online service to access the data.

## TTP - Tactics, Techniques, Procedures

_Tactics, techniques, and procedures_ (TTP) summarize the suspected MITRE ATT&CK techniques used by _Lemon Duck_. This data is unique as it uses our predictive model for actor profiling.

ID | Technique | Weakness | Description | Confidence
-- | --------- | -------- | ----------- | ----------
1 | T1006 | CWE-21, CWE-22, CWE-23, CWE-24, CWE-37 | Path Traversal | High
2 | T1040 | CWE-319 | Authentication Bypass by Capture-replay | High
3 | T1055 | CWE-74 | Improper Neutralization of Data within XPath Expressions | High
4 | T1059 | CWE-88, CWE-94, CWE-1321 | Argument Injection | High
5 | T1059.007 | CWE-79, CWE-80 | Cross Site Scripting | High
6 | ... | ... | ... | ...

There are 18 more TTP items available. Please use our online service to access the data.

## IOA - Indicator of Attack

These _indicators of attack_ (IOA) list the potential fragments used for technical activities like reconnaissance, exploitation, privilege escalation, and exfiltration by Lemon Duck. This data is unique as it uses our predictive model for actor profiling.

ID | Type | Indicator | Confidence
-- | ---- | --------- | ----------
1 | File | `/#/network?tab=network_node_list.html` | High
2 | File | `/admin/config_time_sync.php` | High
3 | File | `/admin/contacts/organizations/edit/2` | High
4 | File | `/admin/list_localuser.php` | High
5 | File | `/admin/modules/product/controller.php?action=add` | High
6 | File | `/admin/suppliers/view_details.php` | High
7 | File | `/adminPage/main/upload` | High
8 | File | `/api/swaggerui/static` | High
9 | File | `/api/sys/set_passwd` | High
10 | File | `/api/v1` | Low
11 | File | `/cgi-bin/alexserv` | High
12 | File | `/cgi-bin/cstecgi.cgi` | High
13 | File | `/cgi-bin/info.cgi` | High
14 | File | `/cgi-bin/nas_sharing.cgi` | High
15 | File | `/cgi-bin/system_mgr.cgi` | High
16 | File | `/classes/Master.php` | High
17 | File | `/classes/Users.php` | High
18 | File | `/contact.php` | Medium
19 | File | `/core/config-revisions` | High
20 | File | `/dcim/power-ports/add/` | High
21 | File | `/debug/pprof` | Medium
22 | File | `/DesignTools/CssEditor.aspx` | High
23 | File | `/desktop_app/file.ajax.php?action=uploadfile` | High
24 | File | `/DXR.axd` | Medium
25 | File | `/edit/server` | Medium
26 | File | `/endpoint/delete-account.php` | High
27 | File | `/endpoint/delete-todo.php` | High
28 | File | `/EXCU_SHELL` | Medium
29 | File | `/finance/help/en/frameset.htm` | High
30 | File | `/forum/away.php` | High
31 | File | `/group1/uploa` | High
32 | File | `/guestbook` | Medium
33 | File | `/hardware` | Medium
34 | File | `/hrm/leaverequest.php` | High
35 | File | `/inc/modules_install.php` | High
36 | File | `/index.php?app=main&func=passport&action=login` | High
37 | File | `/index.php?app=main&inc=feature_phonebook&op=phonebook_list` | High
38 | File | `/index.php?pluginApp/to/yzOffice/getFile` | High
39 | File | `/index/ajax/lang` | High
40 | File | `/itbox_pi/vpn_quickset_service.php?a=set_vpn` | High
41 | File | `/librarian/bookdetails.php` | High
42 | File | `/login` | Low
43 | File | `/login.php?m=admin&c=Field&a=channel_edit` | High
44 | File | `/Maintain/sprog_upstatus.php` | High
45 | File | `/MobileHandler.ashx` | High
46 | File | `/movie.php` | Medium
47 | File | `/network_diagnostics.html` | High
48 | File | `/novel/bookSetting/list` | High
49 | File | `/one_church/churchprofile.php` | High
50 | ... | ... | ...

There are 432 more IOA items available (file, library, argument, input value, pattern, network port). Please use our online service to access the data.

## References

The following list contains _external sources_ which discuss the actor and the associated activities:

* https://blog.talosintelligence.com/2020/10/lemon-duck-brings-cryptocurrency-miners.html
* https://github.com/guardicore/labs_campaigns/tree/master/Lemon_Duck

## Literature

The following _articles_ explain our unique predictive cyber threat intelligence:

* [VulDB Cyber Threat Intelligence Documentation](https://vuldb.com/?kb.cti)
* [Cyber Threat Intelligence - Early Anticipation of Attacks](https://www.scip.ch/en/?labs.20201022)

## License

(c) [1997-2024](https://vuldb.com/?kb.changelog) by [vuldb.com](https://vuldb.com/?kb.about). All data on this page is shared under the license [CC BY-NC-SA 4.0](https://creativecommons.org/licenses/by-nc-sa/4.0/). Questions? Check the [FAQ](https://vuldb.com/?kb.faq), read the [documentation](https://vuldb.com/?kb) or [contact us](https://vuldb.com/?contact)!
