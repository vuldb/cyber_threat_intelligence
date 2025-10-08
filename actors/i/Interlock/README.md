# Interlock - Cyber Threat Intelligence

These _indicators_ were reported, collected, and generated during the [VulDB CTI analysis](https://vuldb.com/?kb.cti) of the actor known as [Interlock](https://vuldb.com/?actor.interlock). The _activity monitoring_ correlates data from social media, forums, chat rooms, and darknet markets. It helps to determine associated actors, specific activities, expected intentions, emerging research, and ongoing attacks. Our unique _predictive model_ uses _big data_ to forecast activities and their characteristics.

_Live data_ and more _analysis capabilities_ are available at [https://vuldb.com/?actor.interlock](https://vuldb.com/?actor.interlock)

## Campaigns

The following _campaigns_ are known and can be associated with Interlock:

* ClickFix

## Countries

These _countries_ are directly (e.g. origin of attacks) or indirectly (e.g. access by proxy) associated with Interlock:

* [US](https://vuldb.com/?country.us)
* [DE](https://vuldb.com/?country.de)
* [CN](https://vuldb.com/?country.cn)
* ...

There are 6 more country items available. Please use our online service to access the data.

## IOC - Indicator of Compromise

These _indicators of compromise_ (IOC) indicate associated network resources which are known to be part of research and attack activities of Interlock.

ID | IP address | Hostname | Campaign | Confidence
-- | ---------- | -------- | -------- | ----------
1 | [5.161.225.197](https://vuldb.com/?ip.5.161.225.197) | static.197.225.161.5.clients.your-server.de | - | High
2 | [5.252.177.228](https://vuldb.com/?ip.5.252.177.228) | no-rdns.mivocloud.com | - | High
3 | [23.95.182.59](https://vuldb.com/?ip.23.95.182.59) | 23-95-182-59-host.colocrossing.com | - | High
4 | [23.227.203.162](https://vuldb.com/?ip.23.227.203.162) | 23-227-203-162.static.hvvc.us | - | High
5 | [45.61.136.202](https://vuldb.com/?ip.45.61.136.202) | - | - | High
6 | [49.12.69.80](https://vuldb.com/?ip.49.12.69.80) | static.80.69.12.49.clients.your-server.de | - | High
7 | [49.12.102.206](https://vuldb.com/?ip.49.12.102.206) | static.206.102.12.49.clients.your-server.de | - | High
8 | [64.94.84.85](https://vuldb.com/?ip.64.94.84.85) | - | - | High
9 | ... | ... | ... | ...

There are 32 more IOC items available. Please use our online service to access the data.

## TTP - Tactics, Techniques, Procedures

_Tactics, techniques, and procedures_ (TTP) summarize the suspected MITRE ATT&CK techniques used by _Interlock_. This data is unique as it uses our predictive model for actor profiling.

ID | Technique | Weakness | Description | Confidence
-- | --------- | -------- | ----------- | ----------
1 | T1006 | CWE-22, CWE-23, CWE-24, CWE-37 | Path Traversal | High
2 | T1055 | CWE-74 | Improper Neutralization of Data within XPath Expressions | High
3 | T1059 | CWE-94 | Argument Injection | High
4 | T1059.007 | CWE-79, CWE-80 | Basic Cross Site Scripting | High
5 | ... | ... | ... | ...

There are 15 more TTP items available. Please use our online service to access the data.

## IOA - Indicator of Attack

These _indicators of attack_ (IOA) list the potential fragments used for technical activities like reconnaissance, exploitation, privilege escalation, and exfiltration by Interlock. This data is unique as it uses our predictive model for actor profiling.

ID | Type | Indicator | Confidence
-- | ---- | --------- | ----------
1 | File | `/admin/create_product.php` | High
2 | File | `/admin/index2.html` | High
3 | File | `/admin/makehtml_freelist_action.php` | High
4 | File | `/admin/user/UserAdmin.do` | High
5 | File | `/admin/View_user.php` | High
6 | File | `/api/RecordingList/DownloadRecord?file=` | High
7 | File | `/api/wizard/setsyncpppoecfg` | High
8 | File | `/app/ajax/sell_return_data.php` | High
9 | File | `/app/index/controller/Common.php` | High
10 | File | `/application/index/controller/File.php` | High
11 | File | `/apply.cgi` | Medium
12 | File | `/auth/ariosa/login` | High
13 | File | `/cgi-bin/cstecgi.cgi` | High
14 | File | `/cgi-bin/cstecgi.cgi?action=login` | High
15 | File | `/ci_spms/admin/search/searching/` | High
16 | File | `/config-manager/save` | High
17 | File | `/device.rsp?opt=sys&cmd=___S_O_S_T_R_E_A_MAX___` | High
18 | File | `/forum/away.php` | High
19 | File | `/include/file.php` | High
20 | File | `/jeecg-boot/sys/common/upload` | High
21 | File | `/libxml2/SAX2.c` | High
22 | File | `/modules/profile/index.php` | High
23 | File | `/opt/IBM/es/lib/libffq.cryptionjni.so` | High
24 | File | `/php/ping.php` | High
25 | File | `/rapi/read_url` | High
26 | File | `/scripts/unlock_tasks.php` | High
27 | File | `/secure/QueryComponent!Default.jspa` | High
28 | File | `/spip.php` | Medium
29 | File | `/SysInfo1.htm` | High
30 | File | `/sysinfo_json.cgi` | High
31 | File | `/system/dictData/loadDictItem` | High
32 | File | `/system/user/modules/mod_users/controller.php` | High
33 | File | `/thruk/#cgi-bin/extinfo.cgi?type=2` | High
34 | File | `/ueditor/net/controller.ashx?action=catchimage` | High
35 | File | `/v1/pushConfig/detail/` | High
36 | ... | ... | ...

There are 306 more IOA items available (file, library, argument, input value, pattern, network port). Please use our online service to access the data.

## References

The following list contains _external sources_ which discuss the actor and the associated activities:

* https://arcticwolf.com/resources/blog/threat-actor-profile-interlock-ransomware/
* https://blog.sekoia.io/interlock-ransomware-evolving-under-the-radar/
* https://github.com/Cisco-Talos/IOCs/blob/main/2024/11/emerging-interlock-ransomware.txt
* https://rewterz.com/threat-advisory/interlock-ransomware-exploits-clickfix-active-iocs
* https://thedfirreport.com/2025/07/14/kongtuke-filefix-leads-to-new-interlock-rat-variant/

## Literature

The following _articles_ explain our unique predictive cyber threat intelligence:

* [VulDB Cyber Threat Intelligence Documentation](https://vuldb.com/?kb.cti)
* [Cyber Threat Intelligence - Early Anticipation of Attacks](https://www.scip.ch/en/?labs.20201022)

## License

(c) [1997-2025](https://vuldb.com/?kb.changelog) by [vuldb.com](https://vuldb.com/?kb.about). All data on this page is shared under the license [CC BY-NC-SA 4.0](https://creativecommons.org/licenses/by-nc-sa/4.0/). Questions? Check the [FAQ](https://vuldb.com/?kb.faq), read the [documentation](https://vuldb.com/?kb) or [contact us](https://vuldb.com/?contact)!
