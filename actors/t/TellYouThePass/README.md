# TellYouThePass - Cyber Threat Intelligence

These _indicators_ were reported, collected, and generated during the [VulDB CTI analysis](https://vuldb.com/?kb.cti) of the actor known as [TellYouThePass](https://vuldb.com/?actor.tellyouthepass). The _activity monitoring_ correlates data from social media, forums, chat rooms, and darknet markets. It helps to determine associated actors, specific activities, expected intentions, emerging research, and ongoing attacks. Our unique _predictive model_ uses _big data_ to forecast activities and their characteristics.

_Live data_ and more _analysis capabilities_ are available at [https://vuldb.com/?actor.tellyouthepass](https://vuldb.com/?actor.tellyouthepass)

## Campaigns

The following _campaigns_ are known and can be associated with TellYouThePass:

* CVE-2024-4577

## Countries

These _countries_ are directly (e.g. origin of attacks) or indirectly (e.g. access by proxy) associated with TellYouThePass:

* [VN](https://vuldb.com/?country.vn)
* [IT](https://vuldb.com/?country.it)
* [AR](https://vuldb.com/?country.ar)
* ...

There are 1 more country items available. Please use our online service to access the data.

## IOC - Indicator of Compromise

These _indicators of compromise_ (IOC) indicate associated network resources which are known to be part of research and attack activities of TellYouThePass.

ID | IP address | Hostname | Campaign | Confidence
-- | ---------- | -------- | -------- | ----------
1 | [14.116.254.172](https://vuldb.com/?ip.14.116.254.172) | - | CVE-2024-4577 | High
2 | [14.225.53.162](https://vuldb.com/?ip.14.225.53.162) | static.vnpt.vn | CVE-2024-4577 | High
3 | [39.97.209.211](https://vuldb.com/?ip.39.97.209.211) | - | CVE-2024-4577 | High
4 | ... | ... | ... | ...

There are 8 more IOC items available. Please use our online service to access the data.

## TTP - Tactics, Techniques, Procedures

_Tactics, techniques, and procedures_ (TTP) summarize the suspected MITRE ATT&CK techniques used by _TellYouThePass_. This data is unique as it uses our predictive model for actor profiling.

ID | Technique | Weakness | Description | Confidence
-- | --------- | -------- | ----------- | ----------
1 | T1006 | CWE-21, CWE-22, CWE-23, CWE-24 | Path Traversal | High
2 | T1040 | CWE-319 | Authentication Bypass by Capture-replay | High
3 | T1055 | CWE-74 | Improper Neutralization of Data within XPath Expressions | High
4 | T1059 | CWE-88, CWE-94, CWE-1321 | Argument Injection | High
5 | T1059.007 | CWE-79, CWE-80 | Cross Site Scripting | High
6 | ... | ... | ... | ...

There are 18 more TTP items available. Please use our online service to access the data.

## IOA - Indicator of Attack

These _indicators of attack_ (IOA) list the potential fragments used for technical activities like reconnaissance, exploitation, privilege escalation, and exfiltration by TellYouThePass. This data is unique as it uses our predictive model for actor profiling.

ID | Type | Indicator | Confidence
-- | ---- | --------- | ----------
1 | File | `/#/network?tab=network_node_list.html` | High
2 | File | `/.env` | Low
3 | File | `/admin/index.php` | High
4 | File | `/admin/list_localuser.php` | High
5 | File | `/admin/modules/product/controller.php?action=add` | High
6 | File | `/admin/orders/view_order.php` | High
7 | File | `/admin/suppliers/view_details.php` | High
8 | File | `/adminPage/main/upload` | High
9 | File | `/admin_ping.htm` | High
10 | File | `/api/sys/set_passwd` | High
11 | File | `/api/v1` | Low
12 | File | `/application/index/controller/Databasesource.php` | High
13 | File | `/application/index/controller/Icon.php` | High
14 | File | `/application/index/controller/Screen.php` | High
15 | File | `/application/plugins/controller/Upload.php` | High
16 | File | `/apps/reg_go.php` | High
17 | File | `/billing/bill/edit/` | High
18 | File | `/cgi-bin/cstecgi.cgi` | High
19 | File | `/cgi-bin/cstecgi.cgi?action=login&flag=1` | High
20 | File | `/cgi-bin/info.cgi` | High
21 | File | `/cgi-bin/mainfunction.cgi` | High
22 | File | `/cgi-bin/nas_sharing.cgi` | High
23 | File | `/cgi-bin/system_mgr.cgi` | High
24 | File | `/cgi-bin/wlogin.cgi` | High
25 | File | `/classes/Login.php` | High
26 | File | `/classes/Users.php` | High
27 | File | `/core/config-revisions` | High
28 | File | `/DesignTools/CssEditor.aspx` | High
29 | File | `/desktop_app/file.ajax.php?action=uploadfile` | High
30 | File | `/DXR.axd` | Medium
31 | File | `/ECT_Provider/` | High
32 | File | `/Employer/EditProfile.php` | High
33 | File | `/endpoint/delete-todo.php` | High
34 | File | `/EXCU_SHELL` | Medium
35 | File | `/fax/fax_send.php` | High
36 | File | `/files/list-file` | High
37 | File | `/finance/help/en/frameset.htm` | High
38 | File | `/forum/away.php` | High
39 | File | `/general/attendance/manage/ask_duty/delete.php` | High
40 | File | `/goform/` | Medium
41 | File | `/h/autoSaveDraft` | High
42 | File | `/home.php` | Medium
43 | File | `/Home/Index` | Medium
44 | File | `/hrm/leaverequest.php` | High
45 | File | `/inc/modules_install.php` | High
46 | File | `/index.php` | Medium
47 | File | `/index.php?app=main&func=passport&action=login` | High
48 | File | `/itbox_pi/vpn_quickset_service.php?a=set_vpn` | High
49 | File | `/loginVaLidation.php` | High
50 | ... | ... | ...

There are 436 more IOA items available (file, library, argument, input value, pattern, network port). Please use our online service to access the data.

## References

The following list contains _external sources_ which discuss the actor and the associated activities:

* https://cyble.com/blog/cve-2024-4577-ongoing-exploitation-of-a-critical-php-vulnerability/

## Literature

The following _articles_ explain our unique predictive cyber threat intelligence:

* [VulDB Cyber Threat Intelligence Documentation](https://vuldb.com/?kb.cti)
* [Cyber Threat Intelligence - Early Anticipation of Attacks](https://www.scip.ch/en/?labs.20201022)

## License

(c) [1997-2024](https://vuldb.com/?kb.changelog) by [vuldb.com](https://vuldb.com/?kb.about). All data on this page is shared under the license [CC BY-NC-SA 4.0](https://creativecommons.org/licenses/by-nc-sa/4.0/). Questions? Check the [FAQ](https://vuldb.com/?kb.faq), read the [documentation](https://vuldb.com/?kb) or [contact us](https://vuldb.com/?contact)!
