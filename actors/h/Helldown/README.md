# Helldown - Cyber Threat Intelligence

These _indicators_ were reported, collected, and generated during the [VulDB CTI analysis](https://vuldb.com/?kb.cti) of the actor known as [Helldown](https://vuldb.com/?actor.helldown). The _activity monitoring_ correlates data from social media, forums, chat rooms, and darknet markets. It helps to determine associated actors, specific activities, expected intentions, emerging research, and ongoing attacks. Our unique _predictive model_ uses _big data_ to forecast activities and their characteristics.

_Live data_ and more _analysis capabilities_ are available at [https://vuldb.com/?actor.helldown](https://vuldb.com/?actor.helldown)

## Campaigns

The following _campaigns_ are known and can be associated with Helldown:

* Zyxel Vulnerability Exploitation

## Countries

These _countries_ are directly (e.g. origin of attacks) or indirectly (e.g. access by proxy) associated with Helldown:

* [US](https://vuldb.com/?country.us)
* [CN](https://vuldb.com/?country.cn)
* [IT](https://vuldb.com/?country.it)
* ...

There are 24 more country items available. Please use our online service to access the data.

## IOC - Indicator of Compromise

These _indicators of compromise_ (IOC) indicate associated network resources which are known to be part of research and attack activities of Helldown.

ID | IP address | Hostname | Campaign | Confidence
-- | ---------- | -------- | -------- | ----------
1 | [85.190.232.139](https://vuldb.com/?ip.85.190.232.139) | - | Zyxel Vulnerability Exploitation | High
2 | [178.249.211.103](https://vuldb.com/?ip.178.249.211.103) | unn-178-249-211-103.datapacket.com | Zyxel Vulnerability Exploitation | High
3 | [193.37.32.55](https://vuldb.com/?ip.193.37.32.55) | - | Zyxel Vulnerability Exploitation | High
4 | ... | ... | ... | ...

There are 6 more IOC items available. Please use our online service to access the data.

## TTP - Tactics, Techniques, Procedures

_Tactics, techniques, and procedures_ (TTP) summarize the suspected MITRE ATT&CK techniques used by _Helldown_. This data is unique as it uses our predictive model for actor profiling.

ID | Technique | Weakness | Description | Confidence
-- | --------- | -------- | ----------- | ----------
1 | T1006 | CWE-21, CWE-22, CWE-23, CWE-24, CWE-28 | Path Traversal | High
2 | T1040 | CWE-319 | Authentication Bypass by Capture-replay | High
3 | T1055 | CWE-74 | Improper Neutralization of Data within XPath Expressions | High
4 | T1059 | CWE-88, CWE-94, CWE-1321 | Argument Injection | High
5 | T1059.007 | CWE-79, CWE-80 | Basic Cross Site Scripting | High
6 | ... | ... | ... | ...

There are 21 more TTP items available. Please use our online service to access the data.

## IOA - Indicator of Attack

These _indicators of attack_ (IOA) list the potential fragments used for technical activities like reconnaissance, exploitation, privilege escalation, and exfiltration by Helldown. This data is unique as it uses our predictive model for actor profiling.

ID | Type | Indicator | Confidence
-- | ---- | --------- | ----------
1 | File | `/+CSCOE+/logon.html` | High
2 | File | `/admin.php?c=upload&f=zip&_noCache=0.1683794968` | High
3 | File | `/admin.php?p=/Area/index#tab=t2` | High
4 | File | `/admin/about-us.php` | High
5 | File | `/admin/admin-profile.php` | High
6 | File | `/admin/ajax.php` | High
7 | File | `/admin/budget/manage_budget.php` | High
8 | File | `/admin/contacts/organizations/edit/2` | High
9 | File | `/admin/del_category.php` | High
10 | File | `/admin/del_service.php` | High
11 | File | `/admin/edit-accepted-appointment.php` | High
12 | File | `/admin/edit-services.php` | High
13 | File | `/admin/edit_category.php` | High
14 | File | `/admin/index.php` | High
15 | File | `/admin/read.php?mudi=announContent` | High
16 | File | `/admin/reg.php` | High
17 | File | `/admin/reportupload.aspx` | High
18 | File | `/admin/search-appointment.php` | High
19 | File | `/adpweb/wechat/verifyToken/` | High
20 | File | `/ajax.php?action=read_msg` | High
21 | File | `/api/RecordingList/DownloadRecord?file=` | High
22 | File | `/api/stl/actions/search` | High
23 | File | `/api/upload.php` | High
24 | File | `/api/wechat/app_auth` | High
25 | File | `/application/common.php#action_log` | High
26 | File | `/building/backmgr/urlpage/mobileurl/configfile/jx2_config.ini` | High
27 | File | `/calendar/minimizer/index.php` | High
28 | File | `/cgi-bin/adm.cgi` | High
29 | File | `/cgi-bin/nas_sharing.cgi` | High
30 | File | `/cgi-bin/ping.cgi` | High
31 | File | `/cgi-bin/wlogin.cgi` | High
32 | File | `/classes/Master.php?f=delete_category` | High
33 | File | `/classes/Master.php?f=delete_service` | High
34 | File | `/classes/Users.php?f=save` | High
35 | File | `/config/myfield/test.php` | High
36 | File | `/debug/pprof` | Medium
37 | File | `/dipam/athlete-profile.php` | High
38 | File | `/dipam/save-delegates.php` | High
39 | File | `/doping.asp` | Medium
40 | File | `/DXR.axd` | Medium
41 | File | `/export` | Low
42 | File | `/fhconf/umconfig.txt` | High
43 | File | `/file_manager/admin/save_user.php` | High
44 | File | `/forum/away.php` | High
45 | File | `/goForm/aspForm` | High
46 | File | `/goform/execCommand` | High
47 | File | `/goform/SetDDNSCfg` | High
48 | ... | ... | ...

There are 415 more IOA items available (file, library, argument, input value, pattern, network port). Please use our online service to access the data.

## References

The following list contains _external sources_ which discuss the actor and the associated activities:

* https://labs.yarix.com/2025/01/zyxel-vulnerability-exploited-by-helldown-ransomware-group/

## Literature

The following _articles_ explain our unique predictive cyber threat intelligence:

* [VulDB Cyber Threat Intelligence Documentation](https://vuldb.com/?kb.cti)
* [Cyber Threat Intelligence - Early Anticipation of Attacks](https://www.scip.ch/en/?labs.20201022)

## License

(c) [1997-2025](https://vuldb.com/?kb.changelog) by [vuldb.com](https://vuldb.com/?kb.about). All data on this page is shared under the license [CC BY-NC-SA 4.0](https://creativecommons.org/licenses/by-nc-sa/4.0/). Questions? Check the [FAQ](https://vuldb.com/?kb.faq), read the [documentation](https://vuldb.com/?kb) or [contact us](https://vuldb.com/?contact)!
