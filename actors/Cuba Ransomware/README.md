# Cuba Ransomware - Cyber Threat Intelligence

These _indicators_ were reported, collected, and generated during the [VulDB CTI analysis](https://vuldb.com/?kb.cti) of the actor known as [Cuba Ransomware](https://vuldb.com/?actor.cuba_ransomware). The _activity monitoring_ correlates data from social media, forums, chat rooms, and darknet markets. It helps to determine associated actors, specific activities, expected intentions, emerging research, and ongoing attacks. Our unique _predictive model_ uses _big data_ to forecast activities and their characteristics.

_Live data_ and more _analysis capabilities_ are available at [https://vuldb.com/?actor.cuba_ransomware](https://vuldb.com/?actor.cuba_ransomware)

## Countries

These _countries_ are directly (e.g. origin of attacks) or indirectly (e.g. access by proxy) associated with Cuba Ransomware:

* [VN](https://vuldb.com/?country.vn)
* [LU](https://vuldb.com/?country.lu)
* [US](https://vuldb.com/?country.us)
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
2 | File | `/.env` | Low
3 | File | `/admin/index.php` | High
4 | File | `/admin/list_localuser.php` | High
5 | File | `/admin/normal-bwdates-reports-details.php` | High
6 | File | `/admin/orders/view_order.php` | High
7 | File | `/admin/suppliers/view_details.php` | High
8 | File | `/adminPage/main/upload` | High
9 | File | `/admin_ping.htm` | High
10 | File | `/api/controllers/merchant/shop/PosterController.php` | High
11 | File | `/api/v1` | Low
12 | File | `/app/controller/Setup.php` | High
13 | File | `/application/index/controller/Databasesource.php` | High
14 | File | `/application/index/controller/Icon.php` | High
15 | File | `/application/index/controller/Screen.php` | High
16 | File | `/application/plugins/controller/Upload.php` | High
17 | File | `/apps/reg_go.php` | High
18 | File | `/billing/bill/edit/` | High
19 | File | `/cgi-bin/cstecgi.cgi` | High
20 | File | `/cgi-bin/cstecgi.cgi?action=login&flag=1` | High
21 | File | `/cgi-bin/info.cgi` | High
22 | File | `/cgi-bin/mainfunction.cgi` | High
23 | File | `/cgi-bin/nas_sharing.cgi` | High
24 | File | `/cgi-bin/system_mgr.cgi` | High
25 | File | `/cgi-bin/wlogin.cgi` | High
26 | File | `/classes/Login.php` | High
27 | File | `/classes/Users.php` | High
28 | File | `/core/config-revisions` | High
29 | File | `/core/redirect` | High
30 | File | `/debuginfo.htm` | High
31 | File | `/DesignTools/CssEditor.aspx` | High
32 | File | `/desktop_app/file.ajax.php?action=uploadfile` | High
33 | File | `/DXR.axd` | Medium
34 | File | `/ECT_Provider/` | High
35 | File | `/edit-subject.php` | High
36 | File | `/Employer/EditProfile.php` | High
37 | File | `/EXCU_SHELL` | Medium
38 | File | `/fax/fax_send.php` | High
39 | File | `/finance/help/en/frameset.htm` | High
40 | File | `/forum/away.php` | High
41 | File | `/general/attendance/manage/ask_duty/delete.php` | High
42 | File | `/goform/` | Medium
43 | File | `/goform/DhcpSetSe` | High
44 | File | `/goform/setUplinkInfo` | High
45 | File | `/goform/WifiMacFilterGet` | High
46 | File | `/goform/wifiSSIDset` | High
47 | File | `/h/autoSaveDraft` | High
48 | File | `/home.php` | Medium
49 | File | `/Home/Index` | Medium
50 | File | `/hrm/leaverequest.php` | High
51 | File | `/improve/home.php` | High
52 | File | `/inc/modules_install.php` | High
53 | ... | ... | ...

There are 466 more IOA items available (file, library, argument, input value, pattern, network port). Please use our online service to access the data.

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
