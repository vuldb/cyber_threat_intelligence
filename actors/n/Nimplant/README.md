# Nimplant - Cyber Threat Intelligence

These _indicators_ were reported, collected, and generated during the [VulDB CTI analysis](https://vuldb.com/?kb.cti) of the actor known as [Nimplant](https://vuldb.com/?actor.nimplant). The _activity monitoring_ correlates data from social media, forums, chat rooms, and darknet markets. It helps to determine associated actors, specific activities, expected intentions, emerging research, and ongoing attacks. Our unique _predictive model_ uses _big data_ to forecast activities and their characteristics.

_Live data_ and more _analysis capabilities_ are available at [https://vuldb.com/?actor.nimplant](https://vuldb.com/?actor.nimplant)

## Countries

These _countries_ are directly (e.g. origin of attacks) or indirectly (e.g. access by proxy) associated with Nimplant:

* [VN](https://vuldb.com/?country.vn)
* [US](https://vuldb.com/?country.us)
* [MO](https://vuldb.com/?country.mo)
* ...

There are 1 more country items available. Please use our online service to access the data.

## IOC - Indicator of Compromise

These _indicators of compromise_ (IOC) indicate associated network resources which are known to be part of research and attack activities of Nimplant.

ID | IP address | Hostname | Campaign | Confidence
-- | ---------- | -------- | -------- | ----------
1 | [3.0.147.54](https://vuldb.com/?ip.3.0.147.54) | ec2-3-0-147-54.ap-southeast-1.compute.amazonaws.com | - | Medium
2 | [3.17.181.161](https://vuldb.com/?ip.3.17.181.161) | ec2-3-17-181-161.us-east-2.compute.amazonaws.com | - | Medium
3 | [3.226.6.113](https://vuldb.com/?ip.3.226.6.113) | ec2-3-226-6-113.compute-1.amazonaws.com | - | Medium
4 | [14.225.206.107](https://vuldb.com/?ip.14.225.206.107) | static.vnpt.vn | - | High
5 | [20.93.3.210](https://vuldb.com/?ip.20.93.3.210) | - | - | High
6 | [23.106.215.199](https://vuldb.com/?ip.23.106.215.199) | - | - | High
7 | ... | ... | ... | ...

There are 22 more IOC items available. Please use our online service to access the data.

## TTP - Tactics, Techniques, Procedures

_Tactics, techniques, and procedures_ (TTP) summarize the suspected MITRE ATT&CK techniques used by _Nimplant_. This data is unique as it uses our predictive model for actor profiling.

ID | Technique | Weakness | Description | Confidence
-- | --------- | -------- | ----------- | ----------
1 | T1006 | CWE-21, CWE-22, CWE-23, CWE-24 | Path Traversal | High
2 | T1040 | CWE-319 | Authentication Bypass by Capture-replay | High
3 | T1055 | CWE-74 | Improper Neutralization of Data within XPath Expressions | High
4 | T1059 | CWE-88, CWE-94, CWE-1321 | Argument Injection | High
5 | ... | ... | ... | ...

There are 17 more TTP items available. Please use our online service to access the data.

## IOA - Indicator of Attack

These _indicators of attack_ (IOA) list the potential fragments used for technical activities like reconnaissance, exploitation, privilege escalation, and exfiltration by Nimplant. This data is unique as it uses our predictive model for actor profiling.

ID | Type | Indicator | Confidence
-- | ---- | --------- | ----------
1 | File | `/#/network?tab=network_node_list.html` | High
2 | File | `/admin/config_time_sync.php` | High
3 | File | `/admin/forms/option_lists/edit.php` | High
4 | File | `/admin/index.php` | High
5 | File | `/admin/list_localuser.php` | High
6 | File | `/admin/modules/product/controller.php?action=add` | High
7 | File | `/admin/pages/list` | High
8 | File | `/admin/suppliers/view_details.php` | High
9 | File | `/adminPage/main/upload` | High
10 | File | `/api/swaggerui/static` | High
11 | File | `/api/sys/set_passwd` | High
12 | File | `/api/v1` | Low
13 | File | `/apps/reg_go.php` | High
14 | File | `/billing/bill/edit/` | High
15 | File | `/cgi-bin/alexserv` | High
16 | File | `/cgi-bin/cstecgi.cgi` | High
17 | File | `/cgi-bin/cstecgi.cgi?action=login&flag=1` | High
18 | File | `/cgi-bin/info.cgi` | High
19 | File | `/cgi-bin/nas_sharing.cgi` | High
20 | File | `/cgi-bin/system_mgr.cgi` | High
21 | File | `/cgi-bin/wlogin.cgi` | High
22 | File | `/classes/Login.php` | High
23 | File | `/classes/Master.php` | High
24 | File | `/classes/Users.php` | High
25 | File | `/core/config-revisions` | High
26 | File | `/dcim/power-ports/add/` | High
27 | File | `/debug/pprof` | Medium
28 | File | `/DesignTools/CssEditor.aspx` | High
29 | File | `/desktop_app/file.ajax.php?action=uploadfile` | High
30 | File | `/DXR.axd` | Medium
31 | File | `/edit/server` | Medium
32 | File | `/endpoint/delete-todo.php` | High
33 | File | `/EXCU_SHELL` | Medium
34 | File | `/finance/help/en/frameset.htm` | High
35 | File | `/forum/away.php` | High
36 | File | `/guestbook` | Medium
37 | File | `/hardware` | Medium
38 | File | `/home.php` | Medium
39 | File | `/Home/Index` | Medium
40 | File | `/hrm/leaverequest.php` | High
41 | File | `/inc/modules_install.php` | High
42 | File | `/index.php` | Medium
43 | File | `/index.php?app=main&inc=feature_phonebook&op=phonebook_list` | High
44 | File | `/index.php?pluginApp/to/yzOffice/getFile` | High
45 | File | `/itbox_pi/vpn_quickset_service.php?a=set_vpn` | High
46 | File | `/librarian/bookdetails.php` | High
47 | File | `/Maintain/sprog_upstatus.php` | High
48 | File | `/member/chat.php` | High
49 | File | `/member/member_edit.php` | High
50 | File | `/member/view.php` | High
51 | File | `/MobileHandler.ashx` | High
52 | File | `/movie.php` | Medium
53 | File | `/network_diagnostics.html` | High
54 | ... | ... | ...

There are 467 more IOA items available (file, library, argument, input value, pattern, network port). Please use our online service to access the data.

## References

The following list contains _external sources_ which discuss the actor and the associated activities:

* https://search.censys.io/hosts/3.226.6.113
* https://search.censys.io/hosts/14.225.206.107
* https://search.censys.io/hosts/20.93.3.210
* https://search.censys.io/hosts/23.106.215.199
* https://search.censys.io/hosts/54.202.46.22
* https://search.censys.io/hosts/89.73.53.34
* https://search.censys.io/hosts/142.93.226.220
* https://search.censys.io/hosts/167.88.160.211
* https://search.censys.io/hosts/167.88.170.172
* https://search.censys.io/hosts/185.196.10.245
* https://threatfox.abuse.ch

## Literature

The following _articles_ explain our unique predictive cyber threat intelligence:

* [VulDB Cyber Threat Intelligence Documentation](https://vuldb.com/?kb.cti)
* [Cyber Threat Intelligence - Early Anticipation of Attacks](https://www.scip.ch/en/?labs.20201022)

## License

(c) [1997-2024](https://vuldb.com/?kb.changelog) by [vuldb.com](https://vuldb.com/?kb.about). All data on this page is shared under the license [CC BY-NC-SA 4.0](https://creativecommons.org/licenses/by-nc-sa/4.0/). Questions? Check the [FAQ](https://vuldb.com/?kb.faq), read the [documentation](https://vuldb.com/?kb) or [contact us](https://vuldb.com/?contact)!
