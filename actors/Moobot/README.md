# Moobot - Cyber Threat Intelligence

These _indicators_ were reported, collected, and generated during the [VulDB CTI analysis](https://vuldb.com/?kb.cti) of the actor known as [Moobot](https://vuldb.com/?actor.moobot). The _activity monitoring_ correlates data from social media, forums, chat rooms, and darknet markets. It helps to determine associated actors, specific activities, expected intentions, emerging research, and ongoing attacks. Our unique _predictive model_ uses _big data_ to forecast activities and their characteristics.

_Live data_ and more _analysis capabilities_ are available at [https://vuldb.com/?actor.moobot](https://vuldb.com/?actor.moobot)

## Campaigns

The following _campaigns_ are known and can be associated with Moobot:

* DDoS Ukraine
* UNIX CCTV DVR

## Countries

These _countries_ are directly (e.g. origin of attacks) or indirectly (e.g. access by proxy) associated with Moobot:

* [US](https://vuldb.com/?country.us)
* [LU](https://vuldb.com/?country.lu)
* [CN](https://vuldb.com/?country.cn)
* ...

There are 15 more country items available. Please use our online service to access the data.

## IOC - Indicator of Compromise

These _indicators of compromise_ (IOC) indicate associated network resources which are known to be part of research and attack activities of Moobot.

ID | IP address | Hostname | Campaign | Confidence
-- | ---------- | -------- | -------- | ----------
1 | [31.13.195.56](https://vuldb.com/?ip.31.13.195.56) | - | - | High
2 | [37.49.226.216](https://vuldb.com/?ip.37.49.226.216) | - | - | High
3 | [45.95.168.90](https://vuldb.com/?ip.45.95.168.90) | - | - | High
4 | [89.248.174.165](https://vuldb.com/?ip.89.248.174.165) | - | UNIX CCTV DVR | High
5 | [89.248.174.166](https://vuldb.com/?ip.89.248.174.166) | - | UNIX CCTV DVR | High
6 | [89.248.174.198](https://vuldb.com/?ip.89.248.174.198) | - | - | High
7 | ... | ... | ... | ...

There are 25 more IOC items available. Please use our online service to access the data.

## TTP - Tactics, Techniques, Procedures

_Tactics, techniques, and procedures_ (TTP) summarize the suspected MITRE ATT&CK techniques used by _Moobot_. This data is unique as it uses our predictive model for actor profiling.

ID | Technique | Weakness | Description | Confidence
-- | --------- | -------- | ----------- | ----------
1 | T1006 | CWE-21, CWE-22, CWE-24 | Pathname Traversal | High
2 | T1040 | CWE-319 | Authentication Bypass by Capture-replay | High
3 | T1055 | CWE-74 | Injection | High
4 | T1059 | CWE-88, CWE-94, CWE-1321 | Cross Site Scripting | High
5 | T1059.007 | CWE-79, CWE-80 | Cross Site Scripting | High
6 | T1068 | CWE-264, CWE-269, CWE-284 | J2EE Misconfiguration: Weak Access Permissions for EJB Methods | High
7 | ... | ... | ... | ...

There are 23 more TTP items available. Please use our online service to access the data.

## IOA - Indicator of Attack

These _indicators of attack_ (IOA) list the potential fragments used for technical activities like reconnaissance, exploitation, privilege escalation, and exfiltration by Moobot. This data is unique as it uses our predictive model for actor profiling.

ID | Type | Indicator | Confidence
-- | ---- | --------- | ----------
1 | File | `//` | Low
2 | File | `/admin.php/pic/admin/pic/del` | High
3 | File | `/admin.php/singer/admin/lists/zhuan` | High
4 | File | `/admin.php/User/level_sort` | High
5 | File | `/admin/communitymanagement.php` | High
6 | File | `/admin/generalsettings.php` | High
7 | File | `/admin/maintenance/view_designation.php` | High
8 | File | `/admin/payment.php` | High
9 | File | `/admin/siteoptions.php&action=displaygoal&value=1&roleid=1` | High
10 | File | `/admin/user/manage_user.php` | High
11 | File | `/aqpg/users/login.php` | High
12 | File | `/blog/edit` | Medium
13 | File | `/bsms_ci/index.php/user/edit_user/` | High
14 | File | `/cgi-bin/uploadWeiXinPic` | High
15 | File | `/cgi-bin/wlogin.cgi` | High
16 | File | `/classes/Master.php?f=delete_category` | High
17 | File | `/Default/Bd` | Medium
18 | File | `/dms/admin/reports/daily_collection_report.php` | High
19 | File | `/DsaDataTest` | Medium
20 | File | `/etc/networkd-dispatcher` | High
21 | File | `/event/admin/?page=user/list` | High
22 | File | `/filemanager/upload/drop` | High
23 | File | `/food/admin/all_users.php` | High
24 | File | `/forum/away.php` | High
25 | File | `/getcfg.php` | Medium
26 | File | `/goform/PowerSaveSet` | High
27 | File | `/goform/SetClientState` | High
28 | File | `/goform/SetFirewallCfg` | High
29 | File | `/goform/setWorkmode` | High
30 | File | `/goform/wizard_end` | High
31 | File | `/hrm/employeeview.php` | High
32 | File | `/index.php` | Medium
33 | File | `/isms/classes/Users.php` | High
34 | File | `/lists/index.php` | High
35 | File | `/members/view_member.php` | High
36 | File | `/messageboard/view.php` | High
37 | File | `/mgmt/tm/util/bash` | High
38 | File | `/modules/projects/vw_files.php` | High
39 | File | `/ofrs/admin/?page=teams/view_team` | High
40 | File | `/ordering/index.php?q=category` | High
41 | File | `/owa/auth/logon.aspx` | High
42 | File | `/picturesPreview` | High
43 | File | `/public_html/animals` | High
44 | File | `/public_html/apply_vacancy` | High
45 | File | `/purchase_order/admin/?page=user` | High
46 | File | `/purchase_order/classes/Master.php?f=delete_supplier` | High
47 | File | `/SAP_Information_System/controllers/add_admin.php` | High
48 | File | `/simple_chat_bot/classes/Master.php?f=delete_response` | High
49 | ... | ... | ...

There are 424 more IOA items available (file, library, argument, input value, pattern, network port). Please use our online service to access the data.

## References

The following list contains _external sources_ which discuss the actor and the associated activities:

* https://blog.netlab.360.com/ddos-botnet-moobot-en/
* https://blog.netlab.360.com/moobot-0day-unixcctv-dvr-en/
* https://blog.netlab.360.com/some_details_of_the_ddos_attacks_targeting_ukraine_and_russia_in_recent_days/
* https://blog.netlab.360.com/the-botnet-cluster-on-185-244-25-0-24-en/

## Literature

The following _articles_ explain our unique predictive cyber threat intelligence:

* [VulDB Cyber Threat Intelligence Documentation](https://vuldb.com/?kb.cti)
* [Cyber Threat Intelligence - Early Anticipation of Attacks](https://www.scip.ch/en/?labs.20201022)

## License

(c) [1997-2023](https://vuldb.com/?kb.changelog) by [vuldb.com](https://vuldb.com/?kb.about). All data on this page is shared under the license [CC BY-NC-SA 4.0](https://creativecommons.org/licenses/by-nc-sa/4.0/). Questions? Check the [FAQ](https://vuldb.com/?kb.faq), read the [documentation](https://vuldb.com/?kb) or [contact us](https://vuldb.com/?contact)!
