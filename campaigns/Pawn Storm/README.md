# Pawn Storm - Cyber Threat Intelligence

These _indicators_ were reported, collected, and generated during the [VulDB CTI analysis](https://vuldb.com/?kb.cti) of the campaign known as _Pawn Storm_. The _activity monitoring_ correlates data from social media, forums, chat rooms, and darknet markets. It helps to determine associated actors, specific activities, expected intentions, emerging research, and ongoing attacks. Our unique _predictive model_ uses _big data_ to forecast activities and their characteristics.

_Live data_ and more _analysis capabilities_ are available at [https://vuldb.com/?actor](https://vuldb.com/?actor)

## Countries

These _countries_ are directly (e.g. origin of attacks) or indirectly (e.g. access by proxy) associated with Pawn Storm:

* [VN](https://vuldb.com/?country.vn)
* [US](https://vuldb.com/?country.us)
* [TR](https://vuldb.com/?country.tr)
* ...

There are 12 more country items available. Please use our online service to access the data.

## Actors

These _actors_ are associated with Pawn Storm or other actors linked to the campaign.

ID | Actor | Confidence
-- | ----- | ----------
1 | [APT28](https://vuldb.com/?actor.apt28) | High
2 | [Pawn Storm](https://vuldb.com/?actor.pawn_storm) | High

## IOC - Indicator of Compromise

These _indicators of compromise_ (IOC) indicate associated network resources which are known to be part of research and attack activities of Pawn Storm.

ID | IP address | Hostname | Actor | Confidence
-- | ---------- | -------- | ----- | ----------
1 | [14.198.168.140](https://vuldb.com/?ip.14.198.168.140) | 014198168140.ctinets.com | [Pawn Storm](https://vuldb.com/?actor.pawn_storm) | High
2 | [24.11.70.85](https://vuldb.com/?ip.24.11.70.85) | c-24-11-70-85.hsd1.ut.comcast.net | [Pawn Storm](https://vuldb.com/?actor.pawn_storm) | High
3 | [24.88.87.29](https://vuldb.com/?ip.24.88.87.29) | syn-024-088-087-029.res.spectrum.com | [Pawn Storm](https://vuldb.com/?actor.pawn_storm) | High
4 | [24.142.165.2](https://vuldb.com/?ip.24.142.165.2) | 024-142-165-002.biz.spectrum.com | [Pawn Storm](https://vuldb.com/?actor.pawn_storm) | High
5 | [32.143.50.222](https://vuldb.com/?ip.32.143.50.222) | - | [Pawn Storm](https://vuldb.com/?actor.pawn_storm) | High
6 | [42.98.5.225](https://vuldb.com/?ip.42.98.5.225) | 42-98-5-225.static.netvigator.com | [Pawn Storm](https://vuldb.com/?actor.pawn_storm) | High
7 | [45.83.90.11](https://vuldb.com/?ip.45.83.90.11) | - | [Pawn Storm](https://vuldb.com/?actor.pawn_storm) | High
8 | [45.91.95.181](https://vuldb.com/?ip.45.91.95.181) | sks3.simoxap.xyz | [Pawn Storm](https://vuldb.com/?actor.pawn_storm) | High
9 | [46.166.162.90](https://vuldb.com/?ip.46.166.162.90) | - | [APT28](https://vuldb.com/?actor.apt28) | High
10 | [46.183.217.74](https://vuldb.com/?ip.46.183.217.74) | ip-217-74.dataclub.info | [APT28](https://vuldb.com/?actor.apt28) | High
11 | [50.173.136.70](https://vuldb.com/?ip.50.173.136.70) | c-50-173-136-70.unallocated.comcastbusiness.net | [Pawn Storm](https://vuldb.com/?actor.pawn_storm) | High
12 | [61.14.68.33](https://vuldb.com/?ip.61.14.68.33) | - | [Pawn Storm](https://vuldb.com/?actor.pawn_storm) | High
13 | [62.4.36.126](https://vuldb.com/?ip.62.4.36.126) | - | [Pawn Storm](https://vuldb.com/?actor.pawn_storm) | High
14 | ... | ... | ... | ...

There are 52 more IOC items available. Please use our online service to access the data.

## TTP - Tactics, Techniques, Procedures

_Tactics, techniques, and procedures_ (TTP) summarize the suspected MITRE ATT&CK techniques used within Pawn Storm. This data is unique as it uses our predictive model for actor profiling.

ID | Technique | Weakness | Description | Confidence
-- | --------- | -------- | ----------- | ----------
1 | T1006 | CWE-21, CWE-22, CWE-23, CWE-24 | Path Traversal | High
2 | T1040 | CWE-319 | Authentication Bypass by Capture-replay | High
3 | T1055 | CWE-74 | Improper Neutralization of Data within XPath Expressions | High
4 | T1059 | CWE-88, CWE-94, CWE-1321 | Argument Injection | High
5 | T1059.007 | CWE-79, CWE-80 | Cross Site Scripting | High
6 | ... | ... | ... | ...

There are 20 more TTP items available. Please use our online service to access the data.

## IOA - Indicator of Attack

These _indicators of attack_ (IOA) list the potential fragments used for technical activities like reconnaissance, exploitation, privilege escalation, and exfiltration during Pawn Storm. This data is unique as it uses our predictive model for actor profiling.

ID | Type | Indicator | Confidence
-- | ---- | --------- | ----------
1 | File | `/#/network?tab=network_node_list.html` | High
2 | File | `/+CSCOE+/logon.html` | High
3 | File | `/.env` | Low
4 | File | `/adm/syscmd.asp` | High
5 | File | `/admin/index.php` | High
6 | File | `/admin/list_localuser.php` | High
7 | File | `/Admin/News.php` | High
8 | File | `/admin/orders/view_order.php` | High
9 | File | `/admin/suppliers/view_details.php` | High
10 | File | `/adminPage/main/upload` | High
11 | File | `/admin_ping.htm` | High
12 | File | `/api/v1` | Low
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
28 | File | `/config/getuser` | High
29 | File | `/core/config-revisions` | High
30 | File | `/core/redirect` | High
31 | File | `/DesignTools/CssEditor.aspx` | High
32 | File | `/desktop_app/file.ajax.php?action=uploadfile` | High
33 | File | `/DXR.axd` | Medium
34 | File | `/ECT_Provider/` | High
35 | File | `/Employer/EditProfile.php` | High
36 | File | `/EXCU_SHELL` | Medium
37 | File | `/fax/fax_send.php` | High
38 | File | `/finance/help/en/frameset.htm` | High
39 | File | `/forum/away.php` | High
40 | File | `/general/attendance/manage/ask_duty/delete.php` | High
41 | File | `/goform/` | Medium
42 | File | `/h/autoSaveDraft` | High
43 | File | `/home.php` | Medium
44 | File | `/Home/Index` | Medium
45 | File | `/hrm/leaverequest.php` | High
46 | File | `/inc/modules_install.php` | High
47 | File | `/index.php` | Medium
48 | File | `/index.php?app=main&func=passport&action=login` | High
49 | File | `/itbox_pi/vpn_quickset_service.php?a=set_vpn` | High
50 | File | `/Maintain/sprog_upstatus.php` | High
51 | File | `/member/chat.php` | High
52 | ... | ... | ...

There are 451 more IOA items available (file, library, argument, input value, pattern, network port). Please use our online service to access the data.

## References

The following list contains _external sources_ which discuss the campaign and the associated activities:

* https://documents.trendmicro.com/assets/wp/wp-two-years-of-pawn-storm.pdf
* https://www.threatminer.org/report.php?q=wp-operation-pawn-storm.pdf&y=2014
* https://www.trendmicro.com/content/dam/trendmicro/global/en/research/23/l/pawn-storm-uses-brute-force-and-stealth-against-high-value-targets-/iocs-pawn-storm-uses-brute-force-and-stealth-against-high-value-targets.txt
* https://www.trendmicro.com/en_us/research/24/e/router-roulette.html

## Literature

The following _articles_ explain our unique predictive cyber threat intelligence:

* [VulDB Cyber Threat Intelligence Documentation](https://vuldb.com/?kb.cti)
* [Cyber Threat Intelligence - Early Anticipation of Attacks](https://www.scip.ch/en/?labs.20201022)

## License

(c) [1997-2024](https://vuldb.com/?kb.changelog) by [vuldb.com](https://vuldb.com/?kb.about). All data on this page is shared under the license [CC BY-NC-SA 4.0](https://creativecommons.org/licenses/by-nc-sa/4.0/). Questions? Check the [FAQ](https://vuldb.com/?kb.faq), read the [documentation](https://vuldb.com/?kb) or [contact us](https://vuldb.com/?contact)!
