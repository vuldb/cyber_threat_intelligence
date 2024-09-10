# Swisyn - Cyber Threat Intelligence

These _indicators_ were reported, collected, and generated during the [VulDB CTI analysis](https://vuldb.com/?kb.cti) of the actor known as [Swisyn](https://vuldb.com/?actor.swisyn). The _activity monitoring_ correlates data from social media, forums, chat rooms, and darknet markets. It helps to determine associated actors, specific activities, expected intentions, emerging research, and ongoing attacks. Our unique _predictive model_ uses _big data_ to forecast activities and their characteristics.

_Live data_ and more _analysis capabilities_ are available at [https://vuldb.com/?actor.swisyn](https://vuldb.com/?actor.swisyn)

## Countries

These _countries_ are directly (e.g. origin of attacks) or indirectly (e.g. access by proxy) associated with Swisyn:

* [US](https://vuldb.com/?country.us)
* [DE](https://vuldb.com/?country.de)
* [FR](https://vuldb.com/?country.fr)
* ...

There are 16 more country items available. Please use our online service to access the data.

## IOC - Indicator of Compromise

These _indicators of compromise_ (IOC) indicate associated network resources which are known to be part of research and attack activities of Swisyn.

ID | IP address | Hostname | Campaign | Confidence
-- | ---------- | -------- | -------- | ----------
1 | [5.39.72.2](https://vuldb.com/?ip.5.39.72.2) | ns3065363.ip-5-39-72.eu | - | High
2 | [13.107.21.200](https://vuldb.com/?ip.13.107.21.200) | - | - | High
3 | [20.42.65.92](https://vuldb.com/?ip.20.42.65.92) | - | - | High
4 | [51.91.73.194](https://vuldb.com/?ip.51.91.73.194) | ns3164589.ip-51-91-73.eu | - | High
5 | [51.254.45.43](https://vuldb.com/?ip.51.254.45.43) | ip-51-254-45-43.ddhosts.net | - | High
6 | [58.221.32.3](https://vuldb.com/?ip.58.221.32.3) | - | - | High
7 | [58.221.33.111](https://vuldb.com/?ip.58.221.33.111) | - | - | High
8 | [58.221.35.121](https://vuldb.com/?ip.58.221.35.121) | - | - | High
9 | [59.42.71.178](https://vuldb.com/?ip.59.42.71.178) | - | - | High
10 | [59.188.239.165](https://vuldb.com/?ip.59.188.239.165) | - | - | High
11 | [61.60.12.164](https://vuldb.com/?ip.61.60.12.164) | 61-60-12-164.GSN-IP.hinet.net | - | High
12 | ... | ... | ... | ...

There are 45 more IOC items available. Please use our online service to access the data.

## TTP - Tactics, Techniques, Procedures

_Tactics, techniques, and procedures_ (TTP) summarize the suspected MITRE ATT&CK techniques used by _Swisyn_. This data is unique as it uses our predictive model for actor profiling.

ID | Technique | Weakness | Description | Confidence
-- | --------- | -------- | ----------- | ----------
1 | T1006 | CWE-21, CWE-22, CWE-23 | Path Traversal | High
2 | T1055 | CWE-74 | Improper Neutralization of Data within XPath Expressions | High
3 | T1059 | CWE-94 | Argument Injection | High
4 | T1059.007 | CWE-79, CWE-80 | Cross Site Scripting | High
5 | T1068 | CWE-264, CWE-266, CWE-269, CWE-273, CWE-284 | Execution with Unnecessary Privileges | High
6 | ... | ... | ... | ...

There are 20 more TTP items available. Please use our online service to access the data.

## IOA - Indicator of Attack

These _indicators of attack_ (IOA) list the potential fragments used for technical activities like reconnaissance, exploitation, privilege escalation, and exfiltration by Swisyn. This data is unique as it uses our predictive model for actor profiling.

ID | Type | Indicator | Confidence
-- | ---- | --------- | ----------
1 | File | `/action/import_e2c_json_file/` | High
2 | File | `/admin.php/vod/admin/topic/del` | High
3 | File | `/admin.php?action=themeinstall` | High
4 | File | `/admin/admapi.php` | High
5 | File | `/admin/api/theme-edit/` | High
6 | File | `/admin/config.php?display=disa&view=form` | High
7 | File | `/admin/login.php` | High
8 | File | `/admin/posts.php&action=edit` | High
9 | File | `/admin/sysmon.php` | High
10 | File | `/admin/update_expense.php` | High
11 | File | `/api/v1/chat.getThreadsList` | High
12 | File | `/balance/service/list` | High
13 | File | `/base/ecma-helpers-string.c` | High
14 | File | `/blog/edit` | Medium
15 | File | `/cgi-bin/system_mgr.cgi` | High
16 | File | `/cimom` | Low
17 | File | `/ci_spms/admin/search/searching/` | High
18 | File | `/classes/Master.php?f=delete_student` | High
19 | File | `/dev/tty` | Medium
20 | File | `/EPOAGENTMETA/DisplayMSAPropsDetail.do` | High
21 | File | `/etc/sysconfig/tomcat` | High
22 | File | `/fantasticblog/single.php` | High
23 | File | `/goform/aspForm` | High
24 | File | `/goform/delIpMacBind/` | High
25 | File | `/goform/SetLEDCfg` | High
26 | File | `/home/iojs/build/ws/out/Release/obj.target/deps/openssl/openssl.cnf` | High
27 | File | `/htdocs/utils/Files.php` | High
28 | File | `/jpg/image.jpg` | High
29 | File | `/Main_AdmStatus_Content.asp` | High
30 | File | `/manage_user.php` | High
31 | ... | ... | ...

There are 262 more IOA items available (file, library, argument, input value, pattern, network port). Please use our online service to access the data.

## References

The following list contains _external sources_ which discuss the actor and the associated activities:

* https://blog.talosintelligence.com/2019/03/threat-roundup-for-mar-01-to-mar-08.html
* https://blog.talosintelligence.com/2019/05/threat-roundup-0517-0524.html
* https://blog.talosintelligence.com/2021/04/threat-roundup-0402-0409.html
* https://blog.talosintelligence.com/2021/08/threat-roundup-0806-0813.html
* https://blog.talosintelligence.com/2021/11/threat-roundup-1112-1119.html
* https://blog.talosintelligence.com/2022/01/threat-roundup-0121-0128.html
* https://blog.talosintelligence.com/2022/04/threat-roundup-0422-0429.html

## Literature

The following _articles_ explain our unique predictive cyber threat intelligence:

* [VulDB Cyber Threat Intelligence Documentation](https://vuldb.com/?kb.cti)
* [Cyber Threat Intelligence - Early Anticipation of Attacks](https://www.scip.ch/en/?labs.20201022)

## License

(c) [1997-2024](https://vuldb.com/?kb.changelog) by [vuldb.com](https://vuldb.com/?kb.about). All data on this page is shared under the license [CC BY-NC-SA 4.0](https://creativecommons.org/licenses/by-nc-sa/4.0/). Questions? Check the [FAQ](https://vuldb.com/?kb.faq), read the [documentation](https://vuldb.com/?kb) or [contact us](https://vuldb.com/?contact)!
