# Chimera - Cyber Threat Intelligence

These _indicators_ were reported, collected, and generated during the [VulDB CTI analysis](https://vuldb.com/?kb.cti) of the actor known as [Chimera](https://vuldb.com/?actor.chimera). The _activity monitoring_ correlates data from social media, forums, chat rooms, and darknet markets. It helps to determine associated actors, specific activities, expected intentions, emerging research, and ongoing attacks. Our unique _predictive model_ uses _big data_ to forecast activities and their characteristics.

_Live data_ and more _analysis capabilities_ are available at [https://vuldb.com/?actor.chimera](https://vuldb.com/?actor.chimera)

## Countries

These _countries_ are directly (e.g. origin of attacks) or indirectly (e.g. access by proxy) associated with Chimera:

* [VN](https://vuldb.com/?country.vn)
* [CN](https://vuldb.com/?country.cn)
* [US](https://vuldb.com/?country.us)

## IOC - Indicator of Compromise

These _indicators of compromise_ (IOC) indicate associated network resources which are known to be part of research and attack activities of Chimera.

ID | IP address | Hostname | Campaign | Confidence
-- | ---------- | -------- | -------- | ----------
1 | [1.3.35.342](https://vuldb.com/?ip.1.3.35.342) | - | - | High
2 | [5.254.64.234](https://vuldb.com/?ip.5.254.64.234) | - | - | High
3 | [5.254.112.226](https://vuldb.com/?ip.5.254.112.226) | - | - | High
4 | [14.229.140.66](https://vuldb.com/?ip.14.229.140.66) | static.vnpt.vn | - | High
5 | ... | ... | ... | ...

There are 16 more IOC items available. Please use our online service to access the data.

## TTP - Tactics, Techniques, Procedures

_Tactics, techniques, and procedures_ (TTP) summarize the suspected MITRE ATT&CK techniques used by _Chimera_. This data is unique as it uses our predictive model for actor profiling.

ID | Technique | Weakness | Description | Confidence
-- | --------- | -------- | ----------- | ----------
1 | T1006 | CWE-21, CWE-22, CWE-23, CWE-24, CWE-37 | Path Traversal | High
2 | T1040 | CWE-319 | Authentication Bypass by Capture-replay | High
3 | T1055 | CWE-74 | Improper Neutralization of Data within XPath Expressions | High
4 | T1059 | CWE-88, CWE-94, CWE-1321 | Argument Injection | High
5 | ... | ... | ... | ...

There are 17 more TTP items available. Please use our online service to access the data.

## IOA - Indicator of Attack

These _indicators of attack_ (IOA) list the potential fragments used for technical activities like reconnaissance, exploitation, privilege escalation, and exfiltration by Chimera. This data is unique as it uses our predictive model for actor profiling.

ID | Type | Indicator | Confidence
-- | ---- | --------- | ----------
1 | File | `/#/network?tab=network_node_list.html` | High
2 | File | `/admin.php?p=/Area/index#tab=t2` | High
3 | File | `/admin/config_time_sync.php` | High
4 | File | `/admin/index.php` | High
5 | File | `/admin/list_localuser.php` | High
6 | File | `/admin/modules/product/controller.php?action=add` | High
7 | File | `/admin/suppliers/view_details.php` | High
8 | File | `/adminPage/main/upload` | High
9 | File | `/api/swaggerui/static` | High
10 | File | `/api/sys/set_passwd` | High
11 | File | `/api/v1` | Low
12 | File | `/apps/reg_go.php` | High
13 | File | `/billing/bill/edit/` | High
14 | File | `/cgi-bin/alexserv` | High
15 | File | `/cgi-bin/cstecgi.cgi` | High
16 | File | `/cgi-bin/cstecgi.cgi?action=login&flag=1` | High
17 | File | `/cgi-bin/info.cgi` | High
18 | File | `/cgi-bin/nas_sharing.cgi` | High
19 | File | `/cgi-bin/system_mgr.cgi` | High
20 | File | `/cgi-bin/wlogin.cgi` | High
21 | File | `/classes/Login.php` | High
22 | File | `/classes/Master.php` | High
23 | File | `/classes/Users.php` | High
24 | File | `/contact.php` | Medium
25 | File | `/core/config-revisions` | High
26 | File | `/dayrui/Fcms/View/system_log.html` | High
27 | File | `/dcim/power-ports/add/` | High
28 | File | `/debug/pprof` | Medium
29 | File | `/DesignTools/CssEditor.aspx` | High
30 | File | `/desktop_app/file.ajax.php?action=uploadfile` | High
31 | File | `/DXR.axd` | Medium
32 | File | `/edit/server` | Medium
33 | File | `/endpoint/delete-account.php` | High
34 | File | `/endpoint/delete-todo.php` | High
35 | File | `/EXCU_SHELL` | Medium
36 | File | `/finance/help/en/frameset.htm` | High
37 | File | `/forum/away.php` | High
38 | File | `/guestbook` | Medium
39 | File | `/hardware` | Medium
40 | File | `/home.php` | Medium
41 | File | `/Home/Index` | Medium
42 | File | `/hrm/leaverequest.php` | High
43 | File | `/inc/modules_install.php` | High
44 | File | `/index.php` | Medium
45 | File | `/index.php?app=main&inc=feature_phonebook&op=phonebook_list` | High
46 | File | `/index.php?pluginApp/to/yzOffice/getFile` | High
47 | File | `/itbox_pi/vpn_quickset_service.php?a=set_vpn` | High
48 | File | `/librarian/bookdetails.php` | High
49 | File | `/Maintain/sprog_upstatus.php` | High
50 | File | `/member/chat.php` | High
51 | File | `/member/member_edit.php` | High
52 | ... | ... | ...

There are 449 more IOA items available (file, library, argument, input value, pattern, network port). Please use our online service to access the data.

## References

The following list contains _external sources_ which discuss the actor and the associated activities:

* https://cycraft.com/download/%5BTLP-White%5D20200415%20Chimera_V4.1.pdf
* https://vxug.fakedoma.in/archive/APTs/2021/2021.01.12/Chimera.pdf

## Literature

The following _articles_ explain our unique predictive cyber threat intelligence:

* [VulDB Cyber Threat Intelligence Documentation](https://vuldb.com/?kb.cti)
* [Cyber Threat Intelligence - Early Anticipation of Attacks](https://www.scip.ch/en/?labs.20201022)

## License

(c) [1997-2024](https://vuldb.com/?kb.changelog) by [vuldb.com](https://vuldb.com/?kb.about). All data on this page is shared under the license [CC BY-NC-SA 4.0](https://creativecommons.org/licenses/by-nc-sa/4.0/). Questions? Check the [FAQ](https://vuldb.com/?kb.faq), read the [documentation](https://vuldb.com/?kb) or [contact us](https://vuldb.com/?contact)!
