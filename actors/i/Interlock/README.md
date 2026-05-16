# Interlock - Cyber Threat Intelligence

These _indicators_ were reported, collected, and generated during the [VulDB CTI analysis](https://vuldb.com/?kb.cti) of the actor known as [Interlock](https://vuldb.com/?actor.interlock). The _activity monitoring_ correlates data from social media, forums, chat rooms, and darknet markets. It helps to determine associated actors, specific activities, expected intentions, emerging research, and ongoing attacks. Our unique _predictive model_ uses _big data_ to forecast activities and their characteristics.

_Live data_ and more _analysis capabilities_ are available at [https://vuldb.com/?actor.interlock](https://vuldb.com/?actor.interlock)

## Campaigns

The following _campaigns_ are known and can be associated with Interlock:

* ClickFix

## Countries

These _countries_ are directly (e.g. origin of attacks) or indirectly (e.g. access by proxy) associated with Interlock:

* [US](https://vuldb.com/?country.us)
* [CN](https://vuldb.com/?country.cn)
* [DE](https://vuldb.com/?country.de)
* ...

There are 7 more country items available. Please use our online service to access the data.

## IOC - Indicator of Compromise

These _indicators of compromise_ (IOC) indicate associated network resources which are known to be part of research and attack activities of Interlock.

ID | IP address | Hostname | Campaign | Confidence
-- | ---------- | -------- | -------- | ----------
1 | [5.161.225.197](https://vuldb.com/?ip.5.161.225.197) | static.197.225.161.5.clients.your-server.de | - | High
2 | [5.252.177.228](https://vuldb.com/?ip.5.252.177.228) | no-rdns.mivocloud.com | - | High
3 | [23.95.182.59](https://vuldb.com/?ip.23.95.182.59) | 23-95-182-59-host.colocrossing.com | - | High
4 | [23.227.203.162](https://vuldb.com/?ip.23.227.203.162) | 23-227-203-162.static.hvvc.us | - | High
5 | [37.27.216.30](https://vuldb.com/?ip.37.27.216.30) | static.30.216.27.37.clients.your-server.de | - | High
6 | [45.61.136.109](https://vuldb.com/?ip.45.61.136.109) | - | - | High
7 | [45.61.136.202](https://vuldb.com/?ip.45.61.136.202) | - | - | High
8 | [49.12.69.80](https://vuldb.com/?ip.49.12.69.80) | static.80.69.12.49.clients.your-server.de | - | High
9 | [49.12.102.206](https://vuldb.com/?ip.49.12.102.206) | static.206.102.12.49.clients.your-server.de | - | High
10 | [64.94.84.85](https://vuldb.com/?ip.64.94.84.85) | - | - | High
11 | ... | ... | ... | ...

There are 39 more IOC items available. Please use our online service to access the data.

## TTP - Tactics, Techniques, Procedures

_Tactics, techniques, and procedures_ (TTP) summarize the suspected MITRE ATT&CK techniques used by _Interlock_. This data is unique as it uses our predictive model for actor profiling.

ID | Technique | Weakness | Description | Confidence
-- | --------- | -------- | ----------- | ----------
1 | T1006 | CWE-21, CWE-22, CWE-23, CWE-24, CWE-37 | Path Traversal | High
2 | T1040 | CWE-319 | Authentication Bypass by Capture-replay | High
3 | T1055 | CWE-74 | Improper Neutralization of Data within XPath Expressions | High
4 | T1059 | CWE-94 | Argument Injection | High
5 | ... | ... | ... | ...

There are 18 more TTP items available. Please use our online service to access the data.

## IOA - Indicator of Attack

These _indicators of attack_ (IOA) list the potential fragments used for technical activities like reconnaissance, exploitation, privilege escalation, and exfiltration by Interlock. This data is unique as it uses our predictive model for actor profiling.

ID | Type | Indicator | Confidence
-- | ---- | --------- | ----------
1 | File | `/admin/ajax.php` | High
2 | File | `/admin/create_product.php` | High
3 | File | `/admin/index2.html` | High
4 | File | `/admin/makehtml_freelist_action.php` | High
5 | File | `/admin/suppliers/view_details.php` | High
6 | File | `/admin/user/UserAdmin.do` | High
7 | File | `/admin/View_user.php` | High
8 | File | `/adminapi/system/crud` | High
9 | File | `/ajax/getBasicInfo.php` | High
10 | File | `/api/RecordingList/DownloadRecord?file=` | High
11 | File | `/api/wizard/setsyncpppoecfg` | High
12 | File | `/app/ajax/sell_return_data.php` | High
13 | File | `/app/index/controller/Common.php` | High
14 | File | `/application/index/controller/File.php` | High
15 | File | `/apply.cgi` | Medium
16 | File | `/auth/ariosa/login` | High
17 | File | `/cgi-bin/cstecgi.cgi` | High
18 | File | `/cgi-bin/cstecgi.cgi?action=login` | High
19 | File | `/cgi-bin/system_mgr.cgi` | High
20 | File | `/ci_spms/admin/search/searching/` | High
21 | File | `/clearance/clearance.php` | High
22 | File | `/com/esafenet/servlet/ajax/NetSecPolicyAjax.java` | High
23 | File | `/config-manager/save` | High
24 | File | `/config/pw_changeusers.html` | High
25 | File | `/device.rsp?opt=sys&cmd=___S_O_S_T_R_E_A_MAX___` | High
26 | File | `/forum/away.php` | High
27 | File | `/hospital/hms/admin/patient-search.php` | High
28 | File | `/include/file.php` | High
29 | File | `/jeecg-boot/sys/common/upload` | High
30 | File | `/libxml2/SAX2.c` | High
31 | File | `/modules/profile/index.php` | High
32 | File | `/one_church/churchprofile.php` | High
33 | File | `/opt/IBM/es/lib/libffq.cryptionjni.so` | High
34 | File | `/opt/vyatta/share/vyatta-cfg/templates/system/static-host-mapping/host-name/node.def` | High
35 | File | `/pet_shop/admin/orders/update_status.php` | High
36 | File | `/php/ping.php` | High
37 | File | `/profile/edit.php` | High
38 | File | `/rapi/read_url` | High
39 | File | `/reqproc/proc_post` | High
40 | File | `/scripts/unlock_tasks.php` | High
41 | File | `/secure/QueryComponent!Default.jspa` | High
42 | File | `/spip.php` | Medium
43 | File | `/SysInfo1.htm` | High
44 | ... | ... | ...

There are 382 more IOA items available (file, library, argument, input value, pattern, network port). Please use our online service to access the data.

## References

The following list contains _external sources_ which discuss the actor and the associated activities:

* https://arcticwolf.com/resources/blog/threat-actor-profile-interlock-ransomware/
* https://blog.sekoia.io/interlock-ransomware-evolving-under-the-radar/
* https://github.com/Cisco-Talos/IOCs/blob/main/2024/11/emerging-interlock-ransomware.txt
* https://rewterz.com/threat-advisory/interlock-ransomware-exploits-clickfix-active-iocs
* https://thedfirreport.com/2025/07/14/kongtuke-filefix-leads-to-new-interlock-rat-variant/
* https://www.fortinet.com/blog/threat-research/interlock-ransomware-new-techniques-same-old-tricks

## Literature

The following _articles_ explain our unique predictive cyber threat intelligence:

* [VulDB Cyber Threat Intelligence Documentation](https://vuldb.com/?kb.cti)
* [Cyber Threat Intelligence - Early Anticipation of Attacks](https://www.scip.ch/en/?labs.20201022)

## License

(c) [1997-2026](https://vuldb.com/?kb.changelog) by [vuldb.com](https://vuldb.com/?kb.about). All data on this page is shared under the license [CC BY-NC-SA 4.0](https://creativecommons.org/licenses/by-nc-sa/4.0/). Questions? Check the [FAQ](https://vuldb.com/?kb.faq), read the [documentation](https://vuldb.com/?kb) or [contact us](https://vuldb.com/?contact)!
