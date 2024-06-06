# CoralRaider - Cyber Threat Intelligence

These _indicators_ were reported, collected, and generated during the [VulDB CTI analysis](https://vuldb.com/?kb.cti) of the actor known as [CoralRaider](https://vuldb.com/?actor.coralraider). The _activity monitoring_ correlates data from social media, forums, chat rooms, and darknet markets. It helps to determine associated actors, specific activities, expected intentions, emerging research, and ongoing attacks. Our unique _predictive model_ uses _big data_ to forecast activities and their characteristics.

_Live data_ and more _analysis capabilities_ are available at [https://vuldb.com/?actor.coralraider](https://vuldb.com/?actor.coralraider)

## Countries

These _countries_ are directly (e.g. origin of attacks) or indirectly (e.g. access by proxy) associated with CoralRaider:

* [VN](https://vuldb.com/?country.vn)

## IOC - Indicator of Compromise

These _indicators of compromise_ (IOC) indicate associated network resources which are known to be part of research and attack activities of CoralRaider.

ID | IP address | Hostname | Campaign | Confidence
-- | ---------- | -------- | -------- | ----------
1 | [14.225.210.97](https://vuldb.com/?ip.14.225.210.97) | static.vnpt.vn | - | High
2 | [14.225.210.98](https://vuldb.com/?ip.14.225.210.98) | static.vnpt.vn | - | High
3 | [14.225.210.209](https://vuldb.com/?ip.14.225.210.209) | static.vnpt.vn | - | High
4 | ... | ... | ... | ...

There are 4 more IOC items available. Please use our online service to access the data.

## TTP - Tactics, Techniques, Procedures

_Tactics, techniques, and procedures_ (TTP) summarize the suspected MITRE ATT&CK techniques used by _CoralRaider_. This data is unique as it uses our predictive model for actor profiling.

ID | Technique | Weakness | Description | Confidence
-- | --------- | -------- | ----------- | ----------
1 | T1006 | CWE-22, CWE-23, CWE-24 | Path Traversal | High
2 | T1040 | CWE-319 | Authentication Bypass by Capture-replay | High
3 | T1055 | CWE-74 | Improper Neutralization of Data within XPath Expressions | High
4 | T1059 | CWE-94, CWE-1321 | Argument Injection | High
5 | T1059.007 | CWE-79, CWE-80 | Cross Site Scripting | High
6 | ... | ... | ... | ...

There are 18 more TTP items available. Please use our online service to access the data.

## IOA - Indicator of Attack

These _indicators of attack_ (IOA) list the potential fragments used for technical activities like reconnaissance, exploitation, privilege escalation, and exfiltration by CoralRaider. This data is unique as it uses our predictive model for actor profiling.

ID | Type | Indicator | Confidence
-- | ---- | --------- | ----------
1 | File | `/#/network?tab=network_node_list.html` | High
2 | File | `/.env` | Low
3 | File | `/admin/action/new-father.php` | High
4 | File | `/admin/edit_teacher.php` | High
5 | File | `/admin/fields/manage_field.php` | High
6 | File | `/admin/index.php` | High
7 | File | `/admin/list_localuser.php` | High
8 | File | `/admin/orders/view_order.php` | High
9 | File | `/admin/suppliers/view_details.php` | High
10 | File | `/adminPage/main/upload` | High
11 | File | `/admin_ping.htm` | High
12 | File | `/admin_route/dec_service_credits.php` | High
13 | File | `/admin_route/inc_service_credits.php` | High
14 | File | `/api/sys/set_passwd` | High
15 | File | `/app/api/controller/default/Sqlite.php` | High
16 | File | `/application/index/controller/Databasesource.php` | High
17 | File | `/application/index/controller/Icon.php` | High
18 | File | `/application/index/controller/Screen.php` | High
19 | File | `/application/plugins/controller/Upload.php` | High
20 | File | `/apps/reg_go.php` | High
21 | File | `/arch/x86/mm/cpu_entry_area.c` | High
22 | File | `/billing/bill/edit/` | High
23 | File | `/bin/boa` | Medium
24 | File | `/boafrm/formMapDelDevice` | High
25 | File | `/cgi-bin/cstecgi.cgi` | High
26 | File | `/cgi-bin/cstecgi.cgi?action=login&flag=1` | High
27 | File | `/cgi-bin/info.cgi` | High
28 | File | `/cgi-bin/koha/catalogue/search.pl` | High
29 | File | `/cgi-bin/mainfunction.cgi` | High
30 | File | `/cgi-bin/nas_sharing.cgi` | High
31 | File | `/cgi-bin/system_mgr.cgi` | High
32 | File | `/cgi-bin/wlogin.cgi` | High
33 | File | `/classes/Login.php` | High
34 | File | `/classes/Users.php` | High
35 | File | `/core/redirect` | High
36 | File | `/dashboard/snapshot/*?orgId=0` | High
37 | File | `/DesignTools/CssEditor.aspx` | High
38 | File | `/DXR.axd` | Medium
39 | File | `/ECT_Provider/` | High
40 | File | `/Employer/EditProfile.php` | High
41 | File | `/EXCU_SHELL` | Medium
42 | File | `/fax/fax_send.php` | High
43 | File | `/finance/help/en/frameset.htm` | High
44 | File | `/forum/away.php` | High
45 | File | `/general/attendance/manage/ask_duty/delete.php` | High
46 | File | `/goform/` | Medium
47 | File | `/goform/WifiMacFilterGet` | High
48 | File | `/goform/wifiSSIDset` | High
49 | File | `/h/autoSaveDraft` | High
50 | File | `/home.php` | Medium
51 | File | `/Home/Index` | Medium
52 | ... | ... | ...

There are 448 more IOA items available (file, library, argument, input value, pattern, network port). Please use our online service to access the data.

## References

The following list contains _external sources_ which discuss the actor and the associated activities:

* https://blog.talosintelligence.com/coralraider-targets-socialmedia-accounts/

## Literature

The following _articles_ explain our unique predictive cyber threat intelligence:

* [VulDB Cyber Threat Intelligence Documentation](https://vuldb.com/?kb.cti)
* [Cyber Threat Intelligence - Early Anticipation of Attacks](https://www.scip.ch/en/?labs.20201022)

## License

(c) [1997-2024](https://vuldb.com/?kb.changelog) by [vuldb.com](https://vuldb.com/?kb.about). All data on this page is shared under the license [CC BY-NC-SA 4.0](https://creativecommons.org/licenses/by-nc-sa/4.0/). Questions? Check the [FAQ](https://vuldb.com/?kb.faq), read the [documentation](https://vuldb.com/?kb) or [contact us](https://vuldb.com/?contact)!
