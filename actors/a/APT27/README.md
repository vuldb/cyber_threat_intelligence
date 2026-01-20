# APT27 - Cyber Threat Intelligence

These _indicators_ were reported, collected, and generated during the [VulDB CTI analysis](https://vuldb.com/?kb.cti) of the actor known as [APT27](https://vuldb.com/?actor.apt27). The _activity monitoring_ correlates data from social media, forums, chat rooms, and darknet markets. It helps to determine associated actors, specific activities, expected intentions, emerging research, and ongoing attacks. Our unique _predictive model_ uses _big data_ to forecast activities and their characteristics.

_Live data_ and more _analysis capabilities_ are available at [https://vuldb.com/?actor.apt27](https://vuldb.com/?actor.apt27)

## Campaigns

The following _campaigns_ are known and can be associated with APT27:

* SysUpdate

## Countries

These _countries_ are directly (e.g. origin of attacks) or indirectly (e.g. access by proxy) associated with APT27:

* [CN](https://vuldb.com/?country.cn)
* [US](https://vuldb.com/?country.us)
* [GB](https://vuldb.com/?country.gb)
* ...

There are 21 more country items available. Please use our online service to access the data.

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
1 | T1006 | CWE-21, CWE-22, CWE-23, CWE-24, CWE-425 | Path Traversal | High
2 | T1040 | CWE-294, CWE-319 | Authentication Bypass by Capture-replay | High
3 | T1055 | CWE-74 | Improper Neutralization of Data within XPath Expressions | High
4 | T1059 | CWE-88, CWE-94 | Argument Injection | High
5 | T1059.007 | CWE-79, CWE-80, CWE-85 | Basic Cross Site Scripting | High
6 | T1068 | CWE-264, CWE-269, CWE-284 | Execution with Unnecessary Privileges | High
7 | ... | ... | ... | ...

There are 24 more TTP items available. Please use our online service to access the data.

## IOA - Indicator of Attack

These _indicators of attack_ (IOA) list the potential fragments used for technical activities like reconnaissance, exploitation, privilege escalation, and exfiltration by APT27. This data is unique as it uses our predictive model for actor profiling.

ID | Type | Indicator | Confidence
-- | ---- | --------- | ----------
1 | File | `/+CSCOE+/logon.html` | High
2 | File | `/addProduct.php` | High
3 | File | `/admin/add-module.php` | High
4 | File | `/admin/archives_add.php` | High
5 | File | `/admin/categories/save` | High
6 | File | `/admin/contact-us.php` | High
7 | File | `/admin/delete_user.php` | High
8 | File | `/admin/index.php` | High
9 | File | `/admin/newsletterdel.php` | High
10 | File | `/admin/pages/` | High
11 | File | `/admin/positions.php` | High
12 | File | `/admin/powerline` | High
13 | File | `/admin/receipt.php` | High
14 | File | `/admind45f74adbd95.php?c=field&m=add&rname=site&rid=1&page=0` | High
15 | File | `/admind45f74adbd95.php?c=field&m=add&rname=site&rid=1&page=1` | High
16 | File | `/admins` | Low
17 | File | `/ajax.php?action=login` | High
18 | File | `/ajax/getBasicInfo.php` | High
19 | File | `/api/admin/system/store/order/list` | High
20 | File | `/api/files/recipepictures/` | High
21 | File | `/app/register.php?action=reg` | High
22 | File | `/authentication.cgi` | High
23 | File | `/boafrm/formDdns` | High
24 | File | `/boafrm/formTracerouteDiagnosticRun` | High
25 | File | `/boafrm/formVpnConfigSetup` | High
26 | File | `/cgi-bin/cstecgi.cgi` | High
27 | File | `/cgi-bin/live_api.cgi` | High
28 | File | `/cgi-bin/wlogin.cgi` | High
29 | File | `/clientdetails/admin/regester.php` | High
30 | File | `/config/getuser` | High
31 | File | `/csms/?page=contact_us` | High
32 | File | `/detailtransac.php` | High
33 | File | `/dev/ptpX` | Medium
34 | File | `/downloadmaster/dm_apply.cgi?action_mode=initial&download_type=General&special_cgi=get_language` | High
35 | File | `/editeddonor.php` | High
36 | File | `/editprofile.php` | High
37 | File | `/etc/shadow` | Medium
38 | File | `/farm/product.php` | High
39 | File | `/foreigner-search.php` | High
40 | File | `/forum/away.php` | High
41 | File | `/function.php` | High
42 | File | `/gallery/api/status/` | High
43 | File | `/goform/AdvSetLanip` | High
44 | File | `/goform/AdvSetMacMtuWa` | High
45 | File | `/goform/aspForm` | High
46 | File | `/goform/DhcpListClient` | High
47 | File | `/goform/exeCommand` | High
48 | File | `/goform/formConfigFastDirectionW` | High
49 | File | `/goform/formFireWall` | High
50 | File | `/goform/formNatStaticMap` | High
51 | File | `/goform/formPictureUrl` | High
52 | File | `/goform/formWPS` | High
53 | File | `/goform/getOneApConfTempEntry` | High
54 | ... | ... | ...

There are 474 more IOA items available (file, library, argument, input value, pattern, network port). Please use our online service to access the data.

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
