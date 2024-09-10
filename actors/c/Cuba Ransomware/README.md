# Cuba Ransomware - Cyber Threat Intelligence

These _indicators_ were reported, collected, and generated during the [VulDB CTI analysis](https://vuldb.com/?kb.cti) of the actor known as [Cuba Ransomware](https://vuldb.com/?actor.cuba_ransomware). The _activity monitoring_ correlates data from social media, forums, chat rooms, and darknet markets. It helps to determine associated actors, specific activities, expected intentions, emerging research, and ongoing attacks. Our unique _predictive model_ uses _big data_ to forecast activities and their characteristics.

_Live data_ and more _analysis capabilities_ are available at [https://vuldb.com/?actor.cuba_ransomware](https://vuldb.com/?actor.cuba_ransomware)

## Countries

These _countries_ are directly (e.g. origin of attacks) or indirectly (e.g. access by proxy) associated with Cuba Ransomware:

* [VN](https://vuldb.com/?country.vn)
* [US](https://vuldb.com/?country.us)
* [LU](https://vuldb.com/?country.lu)
* ...

There are 2 more country items available. Please use our online service to access the data.

## IOC - Indicator of Compromise

These _indicators of compromise_ (IOC) indicate associated network resources which are known to be part of research and attack activities of Cuba Ransomware.

ID | IP address | Hostname | Campaign | Confidence
-- | ---------- | -------- | -------- | ----------
1 | [10.13.102.1](https://vuldb.com/?ip.10.13.102.1) | - | - | High
2 | [10.13.102.58](https://vuldb.com/?ip.10.13.102.58) | - | - | High
3 | [10.14.100.20](https://vuldb.com/?ip.10.14.100.20) | - | - | High
4 | [10.133.78.41](https://vuldb.com/?ip.10.133.78.41) | - | - | High
5 | [23.160.193.145](https://vuldb.com/?ip.23.160.193.145) | server1.wlook.com | - | High
6 | [23.227.198.246](https://vuldb.com/?ip.23.227.198.246) | 23-227-198-246.static.hvvc.us | - | High
7 | [31.44.184.84](https://vuldb.com/?ip.31.44.184.84) | - | - | High
8 | [31.44.184.100](https://vuldb.com/?ip.31.44.184.100) | - | - | High
9 | [31.184.192.44](https://vuldb.com/?ip.31.184.192.44) | - | - | High
10 | [31.184.194.42](https://vuldb.com/?ip.31.184.194.42) | - | - | High
11 | [31.184.198.74](https://vuldb.com/?ip.31.184.198.74) | - | - | High
12 | [31.184.198.80](https://vuldb.com/?ip.31.184.198.80) | directingme.com | - | High
13 | [31.184.198.82](https://vuldb.com/?ip.31.184.198.82) | harms.directingme.com | - | High
14 | [31.184.198.83](https://vuldb.com/?ip.31.184.198.83) | - | - | High
15 | [31.184.198.84](https://vuldb.com/?ip.31.184.198.84) | - | - | High
16 | ... | ... | ... | ...

There are 60 more IOC items available. Please use our online service to access the data.

## TTP - Tactics, Techniques, Procedures

_Tactics, techniques, and procedures_ (TTP) summarize the suspected MITRE ATT&CK techniques used by _Cuba Ransomware_. This data is unique as it uses our predictive model for actor profiling.

ID | Technique | Weakness | Description | Confidence
-- | --------- | -------- | ----------- | ----------
1 | T1006 | CWE-21, CWE-22, CWE-23, CWE-24 | Path Traversal | High
2 | T1040 | CWE-319 | Authentication Bypass by Capture-replay | High
3 | T1055 | CWE-74, CWE-643 | Improper Neutralization of Data within XPath Expressions | High
4 | T1059 | CWE-88, CWE-94, CWE-1321 | Argument Injection | High
5 | T1059.007 | CWE-79, CWE-80 | Cross Site Scripting | High
6 | ... | ... | ... | ...

There are 18 more TTP items available. Please use our online service to access the data.

## IOA - Indicator of Attack

These _indicators of attack_ (IOA) list the potential fragments used for technical activities like reconnaissance, exploitation, privilege escalation, and exfiltration by Cuba Ransomware. This data is unique as it uses our predictive model for actor profiling.

ID | Type | Indicator | Confidence
-- | ---- | --------- | ----------
1 | File | `/#/network?tab=network_node_list.html` | High
2 | File | `/admin/config_time_sync.php` | High
3 | File | `/admin/index.php` | High
4 | File | `/admin/list_localuser.php` | High
5 | File | `/admin/member_save.php` | High
6 | File | `/admin/modules/product/controller.php?action=add` | High
7 | File | `/admin/normal-bwdates-reports-details.php` | High
8 | File | `/admin/suppliers/view_details.php` | High
9 | File | `/adminPage/main/upload` | High
10 | File | `/api/swaggerui/static` | High
11 | File | `/api/sys/set_passwd` | High
12 | File | `/api/user` | Medium
13 | File | `/api/v1` | Low
14 | File | `/apps/reg_go.php` | High
15 | File | `/billing/bill/edit/` | High
16 | File | `/cgi-bin/cstecgi.cgi` | High
17 | File | `/cgi-bin/cstecgi.cgi?action=login&flag=1` | High
18 | File | `/cgi-bin/cstecgi.cgi?action=save&setting` | High
19 | File | `/cgi-bin/info.cgi` | High
20 | File | `/cgi-bin/nas_sharing.cgi` | High
21 | File | `/cgi-bin/system_mgr.cgi` | High
22 | File | `/classes/Login.php` | High
23 | File | `/classes/Master.php` | High
24 | File | `/classes/Users.php` | High
25 | File | `/classes/Users.php?f=delete` | High
26 | File | `/core/config-revisions` | High
27 | File | `/dcim/power-ports/add/` | High
28 | File | `/debug/pprof` | Medium
29 | File | `/DesignTools/CssEditor.aspx` | High
30 | File | `/desktop_app/file.ajax.php?action=uploadfile` | High
31 | File | `/DXR.axd` | Medium
32 | File | `/edit-subject.php` | High
33 | File | `/edit/server` | Medium
34 | File | `/endpoint/delete-todo.php` | High
35 | File | `/EXCU_SHELL` | Medium
36 | File | `/finance/help/en/frameset.htm` | High
37 | File | `/forum/away.php` | High
38 | File | `/goform/DhcpSetSe` | High
39 | File | `/goform/setUplinkInfo` | High
40 | File | `/guestbook` | Medium
41 | File | `/hardware` | Medium
42 | File | `/home.php` | Medium
43 | File | `/Home/Index` | Medium
44 | File | `/hrm/leaverequest.php` | High
45 | File | `/improve/home.php` | High
46 | File | `/inc/modules_install.php` | High
47 | File | `/index.php` | Medium
48 | File | `/index.php?app=main&inc=feature_firewall&op=firewall_list` | High
49 | File | `/index.php?app=main&inc=feature_phonebook&op=phonebook_list` | High
50 | File | `/index.php?pluginApp/to/yzOffice/getFile` | High
51 | File | `/itbox_pi/vpn_quickset_service.php?a=set_vpn` | High
52 | File | `/js/player/dmplayer/dmku/?ac=edit` | High
53 | File | `/labvantage/rc?command=page&page=SampleHistoricalList&_iframename=list&__crc=crc_1701669816260` | High
54 | File | `/librarian/bookdetails.php` | High
55 | File | `/Maintain/sprog_upstatus.php` | High
56 | File | `/manage_user.php` | High
57 | File | `/member/chat.php` | High
58 | ... | ... | ...

There are 503 more IOA items available (file, library, argument, input value, pattern, network port). Please use our online service to access the data.

## References

The following list contains _external sources_ which discuss the actor and the associated activities:

* https://securelist.com/cuba-ransomware/110533/
* https://www.cisa.gov/uscert/ncas/alerts/aa22-335a

## Literature

The following _articles_ explain our unique predictive cyber threat intelligence:

* [VulDB Cyber Threat Intelligence Documentation](https://vuldb.com/?kb.cti)
* [Cyber Threat Intelligence - Early Anticipation of Attacks](https://www.scip.ch/en/?labs.20201022)

## License

(c) [1997-2024](https://vuldb.com/?kb.changelog) by [vuldb.com](https://vuldb.com/?kb.about). All data on this page is shared under the license [CC BY-NC-SA 4.0](https://creativecommons.org/licenses/by-nc-sa/4.0/). Questions? Check the [FAQ](https://vuldb.com/?kb.faq), read the [documentation](https://vuldb.com/?kb) or [contact us](https://vuldb.com/?contact)!
