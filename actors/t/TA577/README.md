# TA577 - Cyber Threat Intelligence

These _indicators_ were reported, collected, and generated during the [VulDB CTI analysis](https://vuldb.com/?kb.cti) of the actor known as [TA577](https://vuldb.com/?actor.ta577). The _activity monitoring_ correlates data from social media, forums, chat rooms, and darknet markets. It helps to determine associated actors, specific activities, expected intentions, emerging research, and ongoing attacks. Our unique _predictive model_ uses _big data_ to forecast activities and their characteristics.

_Live data_ and more _analysis capabilities_ are available at [https://vuldb.com/?actor.ta577](https://vuldb.com/?actor.ta577)

## Campaigns

The following _campaigns_ are known and can be associated with TA577:

* DarkGate
* Pikabot

## Countries

These _countries_ are directly (e.g. origin of attacks) or indirectly (e.g. access by proxy) associated with TA577:

* [US](https://vuldb.com/?country.us)
* [CN](https://vuldb.com/?country.cn)
* [RU](https://vuldb.com/?country.ru)
* ...

There are 16 more country items available. Please use our online service to access the data.

## IOC - Indicator of Compromise

These _indicators of compromise_ (IOC) indicate associated network resources which are known to be part of research and attack activities of TA577.

ID | IP address | Hostname | Campaign | Confidence
-- | ---------- | -------- | -------- | ----------
1 | [5.181.159.64](https://vuldb.com/?ip.5.181.159.64) | no-rdns.mivocloud.com | DarkGate | High
2 | [5.252.21.207](https://vuldb.com/?ip.5.252.21.207) | vm3152051.stark-industries.solutions | - | High
3 | [5.252.178.193](https://vuldb.com/?ip.5.252.178.193) | no-rdns.mivocloud.com | DarkGate | High
4 | [54.37.79.82](https://vuldb.com/?ip.54.37.79.82) | - | Pikabot | High
5 | [57.128.83.129](https://vuldb.com/?ip.57.128.83.129) | - | Pikabot | High
6 | [57.128.108.132](https://vuldb.com/?ip.57.128.108.132) | - | Pikabot | High
7 | [57.128.109.221](https://vuldb.com/?ip.57.128.109.221) | - | Pikabot | High
8 | [57.128.164.11](https://vuldb.com/?ip.57.128.164.11) | - | Pikabot | High
9 | [66.63.188.19](https://vuldb.com/?ip.66.63.188.19) | 19-node.tombody.com | - | High
10 | ... | ... | ... | ...

There are 35 more IOC items available. Please use our online service to access the data.

## TTP - Tactics, Techniques, Procedures

_Tactics, techniques, and procedures_ (TTP) summarize the suspected MITRE ATT&CK techniques used by _TA577_. This data is unique as it uses our predictive model for actor profiling.

ID | Technique | Weakness | Description | Confidence
-- | --------- | -------- | ----------- | ----------
1 | T1006 | CWE-21, CWE-22, CWE-23, CWE-24, CWE-36, CWE-37, CWE-425 | Path Traversal | High
2 | T1040 | CWE-294 | Authentication Bypass by Capture-replay | High
3 | T1055 | CWE-74 | Improper Neutralization of Data within XPath Expressions | High
4 | T1059 | CWE-94 | Argument Injection | High
5 | ... | ... | ... | ...

There are 18 more TTP items available. Please use our online service to access the data.

## IOA - Indicator of Attack

These _indicators of attack_ (IOA) list the potential fragments used for technical activities like reconnaissance, exploitation, privilege escalation, and exfiltration by TA577. This data is unique as it uses our predictive model for actor profiling.

ID | Type | Indicator | Confidence
-- | ---- | --------- | ----------
1 | File | `/?ajax-request=jnews` | High
2 | File | `/Account/login.php` | High
3 | File | `/admin/?page=reports` | High
4 | File | `/adminapi/system/crud` | High
5 | File | `/adminapi/system/file/openfile` | High
6 | File | `/api/RecordingList/DownloadRecord?file=` | High
7 | File | `/apply.cgi` | Medium
8 | File | `/b2b-supermarket/shopping-cart` | High
9 | File | `/cgi-bin/cstecgi.cgi` | High
10 | File | `/cgi-bin/luci/api/switch` | High
11 | File | `/controller/company/Index.php#sendCompanyLogo` | High
12 | File | `/dashboard/system/express/entities/forms/save_control/[GUID]` | High
13 | File | `/editor/index.php` | High
14 | File | `/EventEditor.php` | High
15 | File | `/forum/away.php` | High
16 | File | `/guest_auth/cfg/upLoadCfg.php` | High
17 | File | `/Interface/DevManage/VM.php` | High
18 | File | `/jsonrpc` | Medium
19 | File | `/listplace/user/ticket/create` | High
20 | File | `/login` | Low
21 | File | `/mims/login.php` | High
22 | File | `/modules/profile/index.php` | High
23 | File | `/netflow/jspui/selectDevice.jsp` | High
24 | File | `/nova/bin/dot1x` | High
25 | File | `/php/ajax.php` | High
26 | File | `/php/ping.php` | High
27 | File | `/rapi/read_url` | High
28 | File | `/scripts/unlock_tasks.php` | High
29 | File | `/services/config/config.xml` | High
30 | File | `/setSystemAdmin` | High
31 | File | `/SetTriggerWPS/PIN` | High
32 | File | `/signup.php` | Medium
33 | File | `/status/status_log.sys` | High
34 | File | `/sys/user/queryUserComponentData` | High
35 | File | `/SysInfo1.htm` | High
36 | File | `/sysinfo_json.cgi` | High
37 | File | `/system/dictData/loadDictItem` | High
38 | File | `/system/user/modules/mod_users/controller.php` | High
39 | File | `/uncpath/` | Medium
40 | File | `/update-image1.php` | High
41 | File | `/usr/bin/pkexec` | High
42 | File | `/vicidial/user_stats.php` | High
43 | File | `/view/all_teacher.php` | High
44 | File | `/view/networkConfig/ArpTable/arp_add_commit.php` | High
45 | File | `/view/vpn/autovpn/sub_commit.php` | High
46 | ... | ... | ...

There are 400 more IOA items available (file, library, argument, input value, pattern, network port). Please use our online service to access the data.

## References

The following list contains _external sources_ which discuss the actor and the associated activities:

* https://blog.eclecticiq.com/darkgate-opening-gates-for-financially-motivated-threat-actors
* https://exchange.xforce.ibmcloud.com/report/details/guid:b0c792eb9cb5f6b84ef7bca84f50c9f8
* https://exchange.xforce.ibmcloud.com/threats/guid:7f0659d266174b9a9ba40c618b853782
* https://www.malware-traffic-analysis.net/2024/02/08/index.html
* https://www.proofpoint.com/us/blog/threat-insight/latrodectus-spider-bytes-ice
* https://www.proofpoint.com/us/blog/threat-insight/ta577s-unusual-attack-chain-leads-ntlm-data-theft
* https://www.threatdown.com/blog/pikabot-distributed-via-malicious-ads/

## Literature

The following _articles_ explain our unique predictive cyber threat intelligence:

* [VulDB Cyber Threat Intelligence Documentation](https://vuldb.com/?kb.cti)
* [Cyber Threat Intelligence - Early Anticipation of Attacks](https://www.scip.ch/en/?labs.20201022)

## License

(c) [1997-2025](https://vuldb.com/?kb.changelog) by [vuldb.com](https://vuldb.com/?kb.about). All data on this page is shared under the license [CC BY-NC-SA 4.0](https://creativecommons.org/licenses/by-nc-sa/4.0/). Questions? Check the [FAQ](https://vuldb.com/?kb.faq), read the [documentation](https://vuldb.com/?kb) or [contact us](https://vuldb.com/?contact)!
