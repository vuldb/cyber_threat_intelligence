# LabRat - Cyber Threat Intelligence

These _indicators_ were reported, collected, and generated during the [VulDB CTI analysis](https://vuldb.com/?kb.cti) of the actor known as [LabRat](https://vuldb.com/?actor.labrat). The _activity monitoring_ correlates data from social media, forums, chat rooms, and darknet markets. It helps to determine associated actors, specific activities, expected intentions, emerging research, and ongoing attacks. Our unique _predictive model_ uses _big data_ to forecast activities and their characteristics.

_Live data_ and more _analysis capabilities_ are available at [https://vuldb.com/?actor.labrat](https://vuldb.com/?actor.labrat)

## Countries

These _countries_ are directly (e.g. origin of attacks) or indirectly (e.g. access by proxy) associated with LabRat:

* [VN](https://vuldb.com/?country.vn)
* [CN](https://vuldb.com/?country.cn)

## IOC - Indicator of Compromise

These _indicators of compromise_ (IOC) indicate associated network resources which are known to be part of research and attack activities of LabRat.

ID | IP address | Hostname | Campaign | Confidence
-- | ---------- | -------- | -------- | ----------
1 | [1.234.16.54](https://vuldb.com/?ip.1.234.16.54) | - | - | High
2 | [23.94.204.157](https://vuldb.com/?ip.23.94.204.157) | 23-94-204-157-host.colocrossing.com | - | High
3 | [107.173.154.7](https://vuldb.com/?ip.107.173.154.7) | 107-173-154-7-host.colocrossing.com | - | High
4 | ... | ... | ... | ...

There are 3 more IOC items available. Please use our online service to access the data.

## TTP - Tactics, Techniques, Procedures

_Tactics, techniques, and procedures_ (TTP) summarize the suspected MITRE ATT&CK techniques used by _LabRat_. This data is unique as it uses our predictive model for actor profiling.

ID | Technique | Weakness | Description | Confidence
-- | --------- | -------- | ----------- | ----------
1 | T1006 | CWE-21, CWE-22, CWE-23, CWE-24, CWE-37 | Path Traversal | High
2 | T1040 | CWE-319 | Authentication Bypass by Capture-replay | High
3 | T1055 | CWE-74 | Improper Neutralization of Data within XPath Expressions | High
4 | T1059 | CWE-88, CWE-94, CWE-1321 | Argument Injection | High
5 | ... | ... | ... | ...

There are 17 more TTP items available. Please use our online service to access the data.

## IOA - Indicator of Attack

These _indicators of attack_ (IOA) list the potential fragments used for technical activities like reconnaissance, exploitation, privilege escalation, and exfiltration by LabRat. This data is unique as it uses our predictive model for actor profiling.

ID | Type | Indicator | Confidence
-- | ---- | --------- | ----------
1 | File | `/#/network?tab=network_node_list.html` | High
2 | File | `/admin/config_time_sync.php` | High
3 | File | `/admin/index.php` | High
4 | File | `/admin/list_localuser.php` | High
5 | File | `/admin/modules/product/controller.php?action=add` | High
6 | File | `/admin/suppliers/view_details.php` | High
7 | File | `/adminPage/main/upload` | High
8 | File | `/api/swaggerui/static` | High
9 | File | `/api/sys/set_passwd` | High
10 | File | `/api/v1` | Low
11 | File | `/apps/reg_go.php` | High
12 | File | `/billing/bill/edit/` | High
13 | File | `/cgi-bin/alexserv` | High
14 | File | `/cgi-bin/cstecgi.cgi` | High
15 | File | `/cgi-bin/cstecgi.cgi?action=login&flag=1` | High
16 | File | `/cgi-bin/info.cgi` | High
17 | File | `/cgi-bin/nas_sharing.cgi` | High
18 | File | `/cgi-bin/system_mgr.cgi` | High
19 | File | `/cgi-bin/wlogin.cgi` | High
20 | File | `/classes/Login.php` | High
21 | File | `/classes/Master.php` | High
22 | File | `/classes/Users.php` | High
23 | File | `/contact.php` | Medium
24 | File | `/core/config-revisions` | High
25 | File | `/dcim/power-ports/add/` | High
26 | File | `/debug/pprof` | Medium
27 | File | `/DesignTools/CssEditor.aspx` | High
28 | File | `/desktop_app/file.ajax.php?action=uploadfile` | High
29 | File | `/device.rsp?opt=sys&cmd=___S_O_S_T_R_E_A_MAX___` | High
30 | File | `/DXR.axd` | Medium
31 | File | `/edit/server` | Medium
32 | File | `/endpoint/delete-account.php` | High
33 | File | `/endpoint/delete-todo.php` | High
34 | File | `/EXCU_SHELL` | Medium
35 | File | `/finance/help/en/frameset.htm` | High
36 | File | `/forum/away.php` | High
37 | File | `/guestbook` | Medium
38 | File | `/hardware` | Medium
39 | File | `/home.php` | Medium
40 | File | `/Home/Index` | Medium
41 | File | `/hrm/leaverequest.php` | High
42 | File | `/inc/modules_install.php` | High
43 | File | `/index.php` | Medium
44 | File | `/index.php?app=main&inc=feature_phonebook&op=phonebook_list` | High
45 | File | `/index.php?pluginApp/to/yzOffice/getFile` | High
46 | File | `/itbox_pi/vpn_quickset_service.php?a=set_vpn` | High
47 | File | `/librarian/bookdetails.php` | High
48 | File | `/Maintain/sprog_upstatus.php` | High
49 | File | `/member/chat.php` | High
50 | File | `/member/member_edit.php` | High
51 | ... | ... | ...

There are 447 more IOA items available (file, library, argument, input value, pattern, network port). Please use our online service to access the data.

## References

The following list contains _external sources_ which discuss the actor and the associated activities:

* https://sysdig.com/blog/labrat-cryptojacking-proxyjacking-campaign/

## Literature

The following _articles_ explain our unique predictive cyber threat intelligence:

* [VulDB Cyber Threat Intelligence Documentation](https://vuldb.com/?kb.cti)
* [Cyber Threat Intelligence - Early Anticipation of Attacks](https://www.scip.ch/en/?labs.20201022)

## License

(c) [1997-2024](https://vuldb.com/?kb.changelog) by [vuldb.com](https://vuldb.com/?kb.about). All data on this page is shared under the license [CC BY-NC-SA 4.0](https://creativecommons.org/licenses/by-nc-sa/4.0/). Questions? Check the [FAQ](https://vuldb.com/?kb.faq), read the [documentation](https://vuldb.com/?kb) or [contact us](https://vuldb.com/?contact)!
