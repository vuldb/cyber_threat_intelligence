# APT27 - Cyber Threat Intelligence

These _indicators_ were reported, collected, and generated during the [VulDB CTI analysis](https://vuldb.com/?kb.cti) of the actor known as [APT27](https://vuldb.com/?actor.apt27). The _activity monitoring_ correlates data from social media, forums, chat rooms, and darknet markets. It helps to determine associated actors, specific activities, expected intentions, emerging research, and ongoing attacks. Our unique _predictive model_ uses _big data_ to forecast activities and their characteristics.

_Live data_ and more _analysis capabilities_ are available at [https://vuldb.com/?actor.apt27](https://vuldb.com/?actor.apt27)

## Campaigns

The following _campaigns_ are known and can be associated with APT27:

* SysUpdate

## Countries

These _countries_ are directly (e.g. origin of attacks) or indirectly (e.g. access by proxy) associated with APT27:

* [US](https://vuldb.com/?country.us)
* [CN](https://vuldb.com/?country.cn)
* [GB](https://vuldb.com/?country.gb)
* ...

There are 22 more country items available. Please use our online service to access the data.

## IOC - Indicator of Compromise

These _indicators of compromise_ (IOC) indicate associated network resources which are known to be part of research and attack activities of APT27.

ID | IP address | Hostname | Campaign | Confidence
-- | ---------- | -------- | -------- | ----------
1 | [34.90.207.23](https://vuldb.com/?ip.34.90.207.23) | 23.207.90.34.bc.googleusercontent.com | - | Medium
2 | [34.93.247.126](https://vuldb.com/?ip.34.93.247.126) | 126.247.93.34.bc.googleusercontent.com | SysUpdate | Medium
3 | [35.187.148.253](https://vuldb.com/?ip.35.187.148.253) | 253.148.187.35.bc.googleusercontent.com | SysUpdate | Medium
4 | [35.220.135.85](https://vuldb.com/?ip.35.220.135.85) | 85.135.220.35.bc.googleusercontent.com | SysUpdate | Medium
5 | [45.77.250.141](https://vuldb.com/?ip.45.77.250.141) | 45.77.250.141.vultr.com | - | Medium
6 | [45.142.214.188](https://vuldb.com/?ip.45.142.214.188) | vm309132.pq.hosting | SysUpdate | High
7 | [47.75.49.32](https://vuldb.com/?ip.47.75.49.32) | - | SysUpdate | High
8 | [49.143.192.221](https://vuldb.com/?ip.49.143.192.221) | - | - | High
9 | [49.143.205.30](https://vuldb.com/?ip.49.143.205.30) | - | - | High
10 | ... | ... | ... | ...

There are 35 more IOC items available. Please use our online service to access the data.

## TTP - Tactics, Techniques, Procedures

_Tactics, techniques, and procedures_ (TTP) summarize the suspected MITRE ATT&CK techniques used by _APT27_. This data is unique as it uses our predictive model for actor profiling.

ID | Technique | Weakness | Description | Confidence
-- | --------- | -------- | ----------- | ----------
1 | T1006 | CWE-21, CWE-22, CWE-23, CWE-24, CWE-25, CWE-425 | Path Traversal | High
2 | T1040 | CWE-319 | Authentication Bypass by Capture-replay | High
3 | T1055 | CWE-74 | Improper Neutralization of Data within XPath Expressions | High
4 | T1059 | CWE-88, CWE-94 | Argument Injection | High
5 | T1059.007 | CWE-79, CWE-80, CWE-85 | Basic Cross Site Scripting | High
6 | T1068 | CWE-264, CWE-269, CWE-284 | Execution with Unnecessary Privileges | High
7 | ... | ... | ... | ...

There are 22 more TTP items available. Please use our online service to access the data.

## IOA - Indicator of Attack

These _indicators of attack_ (IOA) list the potential fragments used for technical activities like reconnaissance, exploitation, privilege escalation, and exfiltration by APT27. This data is unique as it uses our predictive model for actor profiling.

ID | Type | Indicator | Confidence
-- | ---- | --------- | ----------
1 | File | `/+CSCOE+/logon.html` | High
2 | File | `/addProduct.php` | High
3 | File | `/admin/add-module.php` | High
4 | File | `/admin/add_expenses.php` | High
5 | File | `/admin/archives_add.php` | High
6 | File | `/admin/categories/save` | High
7 | File | `/admin/contact-us.php` | High
8 | File | `/admin/delete_user.php` | High
9 | File | `/admin/index.php` | High
10 | File | `/admin/newsletterdel.php` | High
11 | File | `/admin/pages/` | High
12 | File | `/admin/positions.php` | High
13 | File | `/admin/powerline` | High
14 | File | `/admin/receipt.php` | High
15 | File | `/admind45f74adbd95.php?c=field&m=add&rname=site&rid=1&page=0` | High
16 | File | `/admind45f74adbd95.php?c=field&m=add&rname=site&rid=1&page=1` | High
17 | File | `/Administrator/PHP/AdminDeleteUser.php` | High
18 | File | `/Administrator/PHP/AdminEditUser.php` | High
19 | File | `/Administrator/PHP/AdminReply.php` | High
20 | File | `/admins` | Low
21 | File | `/adv_mac_filter.php` | High
22 | File | `/ajax.php?action=login` | High
23 | File | `/ajax/getBasicInfo.php` | High
24 | File | `/api/admin/system/store/order/list` | High
25 | File | `/api/files/recipepictures/` | High
26 | File | `/app/register.php?action=reg` | High
27 | File | `/authentication.cgi` | High
28 | File | `/boaform/formSamba` | High
29 | File | `/boafrm/formDdns` | High
30 | File | `/boafrm/formTracerouteDiagnosticRun` | High
31 | File | `/boafrm/formVpnConfigSetup` | High
32 | File | `/cgi-bin/cstecgi.cgi` | High
33 | File | `/cgi-bin/wlogin.cgi` | High
34 | File | `/clientdetails/admin/regester.php` | High
35 | File | `/config/getuser` | High
36 | File | `/csms/?page=contact_us` | High
37 | File | `/detailtransac.php` | High
38 | File | `/dev/ptpX` | Medium
39 | File | `/downloadmaster/dm_apply.cgi?action_mode=initial&download_type=General&special_cgi=get_language` | High
40 | File | `/editeddonor.php` | High
41 | File | `/editprofile.php` | High
42 | File | `/etc/shadow` | Medium
43 | File | `/farm/product.php` | High
44 | File | `/foreigner-search.php` | High
45 | File | `/forum/away.php` | High
46 | File | `/FrontEnd/Albums.php` | High
47 | File | `/function.php` | High
48 | File | `/gallery/api/status/` | High
49 | File | `/goform/AdvSetLanip` | High
50 | File | `/goform/AdvSetMacMtuWa` | High
51 | File | `/goform/AdvSetMacMtuWan` | High
52 | File | `/goform/aspForm` | High
53 | File | `/goform/ConfigExceptAli` | High
54 | File | `/goform/ConfigExceptMSN` | High
55 | File | `/goform/DhcpListClient` | High
56 | File | `/goform/exeCommand` | High
57 | File | `/goform/formConfigFastDirectionW` | High
58 | File | `/goform/formFireWall` | High
59 | ... | ... | ...

There are 513 more IOA items available (file, library, argument, input value, pattern, network port). Please use our online service to access the data.

## References

The following list contains _external sources_ which discuss the actor and the associated activities:

* https://github.com/hvs-consulting/ioc_signatures/blob/main/Emissary_Panda_APT27/HvS_APT27_2021-10_IOCs.csv
* https://unit42.paloaltonetworks.com/emissary-panda-attacks-middle-east-government-sharepoint-servers/
* https://vxug.fakedoma.in/archive/APTs/2021/2021.04.09/Iron%20Tiger.pdf
* https://www.secureworks.com/research/threat-group-3390-targets-organizations-for-cyberespionage
* https://www.welivesecurity.com/2021/03/10/exchange-servers-under-siege-10-apt-groups/

## Literature

The following _articles_ explain our unique predictive cyber threat intelligence:

* [VulDB Cyber Threat Intelligence Documentation](https://vuldb.com/?kb.cti)
* [Cyber Threat Intelligence - Early Anticipation of Attacks](https://www.scip.ch/en/?labs.20201022)

## License

(c) [1997-2026](https://vuldb.com/?kb.changelog) by [vuldb.com](https://vuldb.com/?kb.about). All data on this page is shared under the license [CC BY-NC-SA 4.0](https://creativecommons.org/licenses/by-nc-sa/4.0/). Questions? Check the [FAQ](https://vuldb.com/?kb.faq), read the [documentation](https://vuldb.com/?kb) or [contact us](https://vuldb.com/?contact)!
