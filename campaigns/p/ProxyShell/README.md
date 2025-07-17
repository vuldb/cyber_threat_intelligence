# ProxyShell - Cyber Threat Intelligence

These _indicators_ were reported, collected, and generated during the [VulDB CTI analysis](https://vuldb.com/?kb.cti) of the campaign known as _ProxyShell_. The _activity monitoring_ correlates data from social media, forums, chat rooms, and darknet markets. It helps to determine associated actors, specific activities, expected intentions, emerging research, and ongoing attacks. Our unique _predictive model_ uses _big data_ to forecast activities and their characteristics.

_Live data_ and more _analysis capabilities_ are available at [https://vuldb.com/?actor](https://vuldb.com/?actor)

## Countries

These _countries_ are directly (e.g. origin of attacks) or indirectly (e.g. access by proxy) associated with ProxyShell:

* [CN](https://vuldb.com/?country.cn)
* [US](https://vuldb.com/?country.us)
* [RU](https://vuldb.com/?country.ru)
* ...

There are 19 more country items available. Please use our online service to access the data.

## Actors

These _actors_ are associated with ProxyShell or other actors linked to the campaign.

ID | Actor | Confidence
-- | ----- | ----------
1 | [Squirrelwaffle](https://vuldb.com/?actor.squirrelwaffle) | High
2 | [Unknown](https://vuldb.com/?actor.unknown) | High

## IOC - Indicator of Compromise

These _indicators of compromise_ (IOC) indicate associated network resources which are known to be part of research and attack activities of ProxyShell.

ID | IP address | Hostname | Actor | Confidence
-- | ---------- | -------- | ----- | ----------
1 | [23.111.163.242](https://vuldb.com/?ip.23.111.163.242) | 23-111-163-242.static.hvvc.us | [Squirrelwaffle](https://vuldb.com/?actor.squirrelwaffle) | High
2 | [24.229.150.54](https://vuldb.com/?ip.24.229.150.54) | 24.229.150.54.cmts-static.sm.ptd.net | [Squirrelwaffle](https://vuldb.com/?actor.squirrelwaffle) | High
3 | [69.192.185.238](https://vuldb.com/?ip.69.192.185.238) | a69-192-185-238.deploy.static.akamaitechnologies.com | [Squirrelwaffle](https://vuldb.com/?actor.squirrelwaffle) | High
4 | ... | ... | ... | ...

There are 6 more IOC items available. Please use our online service to access the data.

## TTP - Tactics, Techniques, Procedures

_Tactics, techniques, and procedures_ (TTP) summarize the suspected MITRE ATT&CK techniques used within ProxyShell. This data is unique as it uses our predictive model for actor profiling.

ID | Technique | Weakness | Description | Confidence
-- | --------- | -------- | ----------- | ----------
1 | T1006 | CWE-21, CWE-22, CWE-23, CWE-24, CWE-425 | Path Traversal | High
2 | T1055 | CWE-74 | Improper Neutralization of Data within XPath Expressions | High
3 | T1059 | CWE-88, CWE-94, CWE-1321 | Argument Injection | High
4 | T1059.007 | CWE-79, CWE-80 | Basic Cross Site Scripting | High
5 | T1068 | CWE-250, CWE-264, CWE-269, CWE-284 | Execution with Unnecessary Privileges | High
6 | ... | ... | ... | ...

There are 20 more TTP items available. Please use our online service to access the data.

## IOA - Indicator of Attack

These _indicators of attack_ (IOA) list the potential fragments used for technical activities like reconnaissance, exploitation, privilege escalation, and exfiltration during ProxyShell. This data is unique as it uses our predictive model for actor profiling.

ID | Type | Indicator | Confidence
-- | ---- | --------- | ----------
1 | File | `/+CSCOE+/logon.html` | High
2 | File | `/act/ActDao.xml` | High
3 | File | `/add-students.php` | High
4 | File | `/admin-api/mp/material/upload-permanent` | High
5 | File | `/admin.php?p=/Area/index#tab=t2` | High
6 | File | `/admin/` | Low
7 | File | `/admin/admin-update-employee.php` | High
8 | File | `/admin/booktime.php` | High
9 | File | `/admin/change-image.php` | High
10 | File | `/admin/index.php/web/ajax_all_lists` | High
11 | File | `/admin/login.php` | High
12 | File | `/admin/member_save.php` | High
13 | File | `/admin/search-vehicle.php` | High
14 | File | `/admin/voters_row.php` | High
15 | File | `/ajax.php?action=read_msg` | High
16 | File | `/api/authentication/login` | High
17 | File | `/api/clusters/local/topics/{topic}/messages` | High
18 | File | `/api/gen/clients/{language}` | High
19 | File | `/API/info` | Medium
20 | File | `/app/options.py` | High
21 | File | `/applyleave.php` | High
22 | File | `/bin/httpd` | Medium
23 | File | `/cgi-bin/cstecgi.cgi` | High
24 | File | `/cgi-bin/myMusic.cgi` | High
25 | File | `/cgi-bin/supervisor/adcommand.cgi` | High
26 | File | `/cgi-bin/tosei_kikai.php` | High
27 | File | `/cgi-bin/wapopen` | High
28 | File | `/ci_spms/admin/category` | High
29 | File | `/ci_spms/admin/search/searching/` | High
30 | File | `/classes/Master.php?f=delete_appointment` | High
31 | File | `/classes/Master.php?f=delete_train` | High
32 | File | `/Content/Template/root/reverse-shell.aspx` | High
33 | File | `/cov/triggerEnvCov` | High
34 | File | `/ctcprotocol/Protocol` | High
35 | File | `/dashboard/admin/del_plan.php` | High
36 | File | `/dashboard/approve-reject.php` | High
37 | File | `/dashboard/menu-list.php` | High
38 | File | `/debug/pprof` | Medium
39 | File | `/dede/file_manage_control.php` | High
40 | File | `/detailed.php` | High
41 | File | `/device.rsp?opt=sys&cmd=___S_O_S_T_R_E_A_MAX___` | High
42 | File | `/dist/index.js` | High
43 | File | `/doctor/search.php` | High
44 | File | `/DXR.axd` | Medium
45 | File | `/ebics-server/ebics.aspx` | High
46 | File | `/empty_rooms.php` | High
47 | File | `/EXCU_SHELL` | Medium
48 | File | `/ffos/classes/Master.php?f=save_category` | High
49 | File | `/forum/away.php` | High
50 | File | `/general/address/private/address/query/delete.php` | High
51 | File | `/goform/ate` | Medium
52 | ... | ... | ...

There are 453 more IOA items available (file, library, argument, input value, pattern, network port). Please use our online service to access the data.

## References

The following list contains _external sources_ which discuss the campaign and the associated activities:

* https://www.trendmicro.com/content/dam/trendmicro/global/en/research/21/k/squirrelwaffle-exploits-proxyshell-and-proxylogon-vulnerabilities-in-microsoft-exchange-to-hijack-email-chains/IOCs-squirrelwaffle-exploits-proxyshell-and-proxylogon-to-hijack-email
* https://www.trendmicro.com/en_us/research/21/k/analyzing-proxyshell-related-incidents-via-trend-micro-managed-x.html

## Literature

The following _articles_ explain our unique predictive cyber threat intelligence:

* [VulDB Cyber Threat Intelligence Documentation](https://vuldb.com/?kb.cti)
* [Cyber Threat Intelligence - Early Anticipation of Attacks](https://www.scip.ch/en/?labs.20201022)

## License

(c) [1997-2025](https://vuldb.com/?kb.changelog) by [vuldb.com](https://vuldb.com/?kb.about). All data on this page is shared under the license [CC BY-NC-SA 4.0](https://creativecommons.org/licenses/by-nc-sa/4.0/). Questions? Check the [FAQ](https://vuldb.com/?kb.faq), read the [documentation](https://vuldb.com/?kb) or [contact us](https://vuldb.com/?contact)!
