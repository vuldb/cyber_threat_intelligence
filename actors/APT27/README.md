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
* [ES](https://vuldb.com/?country.es)
* ...

There are 13 more country items available. Please use our online service to access the data.

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
1 | T1006 | CWE-21, CWE-22, CWE-23 | Pathname Traversal | High
2 | T1040 | CWE-294, CWE-319 | Authentication Bypass by Capture-replay | High
3 | T1055 | CWE-74 | Injection | High
4 | T1059 | CWE-88, CWE-94 | Cross Site Scripting | High
5 | T1059.007 | CWE-79, CWE-80 | Cross Site Scripting | High
6 | ... | ... | ... | ...

There are 21 more TTP items available. Please use our online service to access the data.

## IOA - Indicator of Attack

These _indicators of attack_ (IOA) list the potential fragments used for technical activities like reconnaissance, exploitation, privilege escalation, and exfiltration by APT27. This data is unique as it uses our predictive model for actor profiling.

ID | Type | Indicator | Confidence
-- | ---- | --------- | ----------
1 | File | `/+CSCOE+/logon.html` | High
2 | File | `/cgi-bin/live_api.cgi` | High
3 | File | `/cgi-bin/wapopen` | High
4 | File | `/cgi-bin/wlogin.cgi` | High
5 | File | `/config/getuser` | High
6 | File | `/etc/ajenti/config.yml` | High
7 | File | `/etc/shadow` | Medium
8 | File | `/goform/telnet` | High
9 | File | `/infusions/shoutbox_panel/shoutbox_admin.php` | High
10 | File | `/lan.asp` | Medium
11 | File | `/modules/profile/index.php` | High
12 | File | `/opt/zimbra/jetty/webapps/zimbra/public` | High
13 | File | `/oscommerce/admin/currencies.php` | High
14 | File | `/proc/pid/syscall` | High
15 | File | `/rapi/read_url` | High
16 | File | `/rom-0` | Low
17 | File | `/session/list/allActiveSession` | High
18 | File | `/SysInfo.htm` | Medium
19 | File | `/syslog_rules` | High
20 | File | `/uncpath/` | Medium
21 | File | `/upload` | Low
22 | File | `/users/{id}` | Medium
23 | File | `/var/tmp/sess_*` | High
24 | File | `/var/WEB-GUI/cgi-bin/telnet.cgi` | High
25 | File | `/video` | Low
26 | File | `actionphp/download.File.php` | High
27 | File | `ActivityManagerService.java` | High
28 | File | `adaptmap_reg.c` | High
29 | File | `add_comment.php` | High
30 | File | `admin.cgi` | Medium
31 | File | `admin.php` | Medium
32 | File | `admin.php?action=files` | High
33 | File | `admin/admin.php` | High
34 | File | `admin/content.php` | High
35 | File | `admin/index.php?id=users/action=edit/user_id=1` | High
36 | File | `admin/modules/master_file/rda_cmc.php?keywords` | High
37 | File | `admin_gallery.php3` | High
38 | File | `affich.php` | Medium
39 | File | `agent/Core/Controller/SendRequest.cpp` | High
40 | ... | ... | ...

There are 342 more IOA items available (file, library, argument, input value, pattern, network port). Please use our online service to access the data.

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

(c) [1997-2023](https://vuldb.com/?kb.changelog) by [vuldb.com](https://vuldb.com/?kb.about). All data on this page is shared under the license [CC BY-NC-SA 4.0](https://creativecommons.org/licenses/by-nc-sa/4.0/). Questions? Check the [FAQ](https://vuldb.com/?kb.faq), read the [documentation](https://vuldb.com/?kb) or [contact us](https://vuldb.com/?contact)!
