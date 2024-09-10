# Pawn Storm - Cyber Threat Intelligence

These _indicators_ were reported, collected, and generated during the [VulDB CTI analysis](https://vuldb.com/?kb.cti) of the actor known as [Pawn Storm](https://vuldb.com/?actor.pawn_storm). The _activity monitoring_ correlates data from social media, forums, chat rooms, and darknet markets. It helps to determine associated actors, specific activities, expected intentions, emerging research, and ongoing attacks. Our unique _predictive model_ uses _big data_ to forecast activities and their characteristics.

_Live data_ and more _analysis capabilities_ are available at [https://vuldb.com/?actor.pawn_storm](https://vuldb.com/?actor.pawn_storm)

## Countries

These _countries_ are directly (e.g. origin of attacks) or indirectly (e.g. access by proxy) associated with Pawn Storm:

* [VN](https://vuldb.com/?country.vn)
* [US](https://vuldb.com/?country.us)
* [GB](https://vuldb.com/?country.gb)
* ...

There are 11 more country items available. Please use our online service to access the data.

## IOC - Indicator of Compromise

These _indicators of compromise_ (IOC) indicate associated network resources which are known to be part of research and attack activities of Pawn Storm.

ID | IP address | Hostname | Campaign | Confidence
-- | ---------- | -------- | -------- | ----------
1 | [14.198.168.140](https://vuldb.com/?ip.14.198.168.140) | 014198168140.ctinets.com | - | High
2 | [24.11.70.85](https://vuldb.com/?ip.24.11.70.85) | c-24-11-70-85.hsd1.ut.comcast.net | - | High
3 | [24.88.87.29](https://vuldb.com/?ip.24.88.87.29) | syn-024-088-087-029.res.spectrum.com | - | High
4 | [24.142.165.2](https://vuldb.com/?ip.24.142.165.2) | 024-142-165-002.biz.spectrum.com | - | High
5 | [32.143.50.222](https://vuldb.com/?ip.32.143.50.222) | - | - | High
6 | [42.98.5.225](https://vuldb.com/?ip.42.98.5.225) | 42-98-5-225.static.netvigator.com | - | High
7 | [45.83.90.11](https://vuldb.com/?ip.45.83.90.11) | - | - | High
8 | [45.91.95.181](https://vuldb.com/?ip.45.91.95.181) | sks3.simoxap.xyz | - | High
9 | [50.173.136.70](https://vuldb.com/?ip.50.173.136.70) | c-50-173-136-70.unallocated.comcastbusiness.net | - | High
10 | [61.14.68.33](https://vuldb.com/?ip.61.14.68.33) | - | - | High
11 | [62.4.36.126](https://vuldb.com/?ip.62.4.36.126) | - | - | High
12 | [68.76.150.97](https://vuldb.com/?ip.68.76.150.97) | 68-76-150-97.lightspeed.hstntx.sbcglobal.net | - | High
13 | ... | ... | ... | ...

There are 46 more IOC items available. Please use our online service to access the data.

## TTP - Tactics, Techniques, Procedures

_Tactics, techniques, and procedures_ (TTP) summarize the suspected MITRE ATT&CK techniques used by _Pawn Storm_. This data is unique as it uses our predictive model for actor profiling.

ID | Technique | Weakness | Description | Confidence
-- | --------- | -------- | ----------- | ----------
1 | T1006 | CWE-21, CWE-22, CWE-23, CWE-24, CWE-37 | Path Traversal | High
2 | T1040 | CWE-319 | Authentication Bypass by Capture-replay | High
3 | T1055 | CWE-74 | Improper Neutralization of Data within XPath Expressions | High
4 | T1059 | CWE-88, CWE-94, CWE-1321 | Argument Injection | High
5 | ... | ... | ... | ...

There are 17 more TTP items available. Please use our online service to access the data.

## IOA - Indicator of Attack

These _indicators of attack_ (IOA) list the potential fragments used for technical activities like reconnaissance, exploitation, privilege escalation, and exfiltration by Pawn Storm. This data is unique as it uses our predictive model for actor profiling.

ID | Type | Indicator | Confidence
-- | ---- | --------- | ----------
1 | File | `/#/network?tab=network_node_list.html` | High
2 | File | `/admin/config_time_sync.php` | High
3 | File | `/admin/list_localuser.php` | High
4 | File | `/admin/modules/product/controller.php?action=add` | High
5 | File | `/admin/suppliers/view_details.php` | High
6 | File | `/adminPage/main/upload` | High
7 | File | `/api/swaggerui/static` | High
8 | File | `/api/sys/set_passwd` | High
9 | File | `/api/v1` | Low
10 | File | `/billing/bill/edit/` | High
11 | File | `/cgi-bin/alexserv` | High
12 | File | `/cgi-bin/cstecgi.cgi` | High
13 | File | `/cgi-bin/cstecgi.cgi?action=login&flag=1` | High
14 | File | `/cgi-bin/info.cgi` | High
15 | File | `/cgi-bin/nas_sharing.cgi` | High
16 | File | `/cgi-bin/system_mgr.cgi` | High
17 | File | `/classes/Login.php` | High
18 | File | `/classes/Master.php` | High
19 | File | `/classes/Users.php` | High
20 | File | `/contact.php` | Medium
21 | File | `/core/config-revisions` | High
22 | File | `/dcim/power-ports/add/` | High
23 | File | `/debug/pprof` | Medium
24 | File | `/DesignTools/CssEditor.aspx` | High
25 | File | `/desktop_app/file.ajax.php?action=uploadfile` | High
26 | File | `/DXR.axd` | Medium
27 | File | `/edit/server` | Medium
28 | File | `/endpoint/delete-account.php` | High
29 | File | `/endpoint/delete-todo.php` | High
30 | File | `/EXCU_SHELL` | Medium
31 | File | `/finance/help/en/frameset.htm` | High
32 | File | `/forms/doLogin` | High
33 | File | `/forum/away.php` | High
34 | File | `/guestbook` | Medium
35 | File | `/hardware` | Medium
36 | File | `/hrm/leaverequest.php` | High
37 | File | `/inc/modules_install.php` | High
38 | File | `/index.php?app=main&inc=feature_phonebook&op=phonebook_list` | High
39 | File | `/index.php?pluginApp/to/yzOffice/getFile` | High
40 | File | `/itbox_pi/vpn_quickset_service.php?a=set_vpn` | High
41 | File | `/librarian/bookdetails.php` | High
42 | File | `/Maintain/sprog_upstatus.php` | High
43 | File | `/MobileHandler.ashx` | High
44 | File | `/movie.php` | Medium
45 | File | `/network_diagnostics.html` | High
46 | File | `/novel/bookSetting/list` | High
47 | File | `/one_church/churchprofile.php` | High
48 | File | `/one_church/userregister.php` | High
49 | File | `/pg_meta/default/query` | High
50 | File | `/php/ping.php` | High
51 | File | `/products/view_product.php` | High
52 | ... | ... | ...

There are 457 more IOA items available (file, library, argument, input value, pattern, network port). Please use our online service to access the data.

## References

The following list contains _external sources_ which discuss the actor and the associated activities:

* https://www.trendmicro.com/content/dam/trendmicro/global/en/research/23/l/pawn-storm-uses-brute-force-and-stealth-against-high-value-targets-/iocs-pawn-storm-uses-brute-force-and-stealth-against-high-value-targets.txt
* https://www.trendmicro.com/en_us/research/24/e/router-roulette.html

## Literature

The following _articles_ explain our unique predictive cyber threat intelligence:

* [VulDB Cyber Threat Intelligence Documentation](https://vuldb.com/?kb.cti)
* [Cyber Threat Intelligence - Early Anticipation of Attacks](https://www.scip.ch/en/?labs.20201022)

## License

(c) [1997-2024](https://vuldb.com/?kb.changelog) by [vuldb.com](https://vuldb.com/?kb.about). All data on this page is shared under the license [CC BY-NC-SA 4.0](https://creativecommons.org/licenses/by-nc-sa/4.0/). Questions? Check the [FAQ](https://vuldb.com/?kb.faq), read the [documentation](https://vuldb.com/?kb) or [contact us](https://vuldb.com/?contact)!
