# Latrodectus - Cyber Threat Intelligence

These _indicators_ were reported, collected, and generated during the [VulDB CTI analysis](https://vuldb.com/?kb.cti) of the actor known as [Latrodectus](https://vuldb.com/?actor.latrodectus). The _activity monitoring_ correlates data from social media, forums, chat rooms, and darknet markets. It helps to determine associated actors, specific activities, expected intentions, emerging research, and ongoing attacks. Our unique _predictive model_ uses _big data_ to forecast activities and their characteristics.

_Live data_ and more _analysis capabilities_ are available at [https://vuldb.com/?actor.latrodectus](https://vuldb.com/?actor.latrodectus)

## Countries

These _countries_ are directly (e.g. origin of attacks) or indirectly (e.g. access by proxy) associated with Latrodectus:

* [US](https://vuldb.com/?country.us)
* [CN](https://vuldb.com/?country.cn)
* [RU](https://vuldb.com/?country.ru)
* ...

There are 18 more country items available. Please use our online service to access the data.

## IOC - Indicator of Compromise

These _indicators of compromise_ (IOC) indicate associated network resources which are known to be part of research and attack activities of Latrodectus.

ID | IP address | Hostname | Campaign | Confidence
-- | ---------- | -------- | -------- | ----------
1 | [5.8.47.86](https://vuldb.com/?ip.5.8.47.86) | rtuyrt.com | - | High
2 | [5.149.248.166](https://vuldb.com/?ip.5.149.248.166) | - | - | High
3 | [5.181.159.53](https://vuldb.com/?ip.5.181.159.53) | 5-181-159-53.mivocloud.com | - | High
4 | [5.252.21.207](https://vuldb.com/?ip.5.252.21.207) | vm2259505.stark-industries.solutions | - | High
5 | [5.255.101.33](https://vuldb.com/?ip.5.255.101.33) | - | - | High
6 | [23.227.202.187](https://vuldb.com/?ip.23.227.202.187) | 23-227-202-187.static.hvvc.us | - | High
7 | [23.227.203.161](https://vuldb.com/?ip.23.227.203.161) | 23-227-203-161.static.hvvc.us | - | High
8 | [23.254.201.238](https://vuldb.com/?ip.23.254.201.238) | hwsrv-1235958.hostwindsdns.com | - | High
9 | [23.254.230.8](https://vuldb.com/?ip.23.254.230.8) | hwsrv-1234109.hostwindsdns.com | - | High
10 | [45.143.166.66](https://vuldb.com/?ip.45.143.166.66) | - | - | High
11 | [45.143.166.85](https://vuldb.com/?ip.45.143.166.85) | - | - | High
12 | [45.143.166.95](https://vuldb.com/?ip.45.143.166.95) | - | - | High
13 | ... | ... | ... | ...

There are 50 more IOC items available. Please use our online service to access the data.

## TTP - Tactics, Techniques, Procedures

_Tactics, techniques, and procedures_ (TTP) summarize the suspected MITRE ATT&CK techniques used by _Latrodectus_. This data is unique as it uses our predictive model for actor profiling.

ID | Technique | Weakness | Description | Confidence
-- | --------- | -------- | ----------- | ----------
1 | T1006 | CWE-21, CWE-22, CWE-425 | Path Traversal | High
2 | T1040 | CWE-294 | Authentication Bypass by Capture-replay | High
3 | T1055 | CWE-74 | Improper Neutralization of Data within XPath Expressions | High
4 | T1059 | CWE-88, CWE-94, CWE-1321 | Argument Injection | High
5 | T1059.007 | CWE-79, CWE-80 | Cross Site Scripting | High
6 | T1068 | CWE-264, CWE-269, CWE-284 | Execution with Unnecessary Privileges | High
7 | ... | ... | ... | ...

There are 22 more TTP items available. Please use our online service to access the data.

## IOA - Indicator of Attack

These _indicators of attack_ (IOA) list the potential fragments used for technical activities like reconnaissance, exploitation, privilege escalation, and exfiltration by Latrodectus. This data is unique as it uses our predictive model for actor profiling.

ID | Type | Indicator | Confidence
-- | ---- | --------- | ----------
1 | File | `//proc/kcore` | Medium
2 | File | `/admin/about-us.php` | High
3 | File | `/admin/action/delete-vaccine.php` | High
4 | File | `/admin/edit-post.php` | High
5 | File | `/admin/index2.html` | High
6 | File | `/admin/userprofile.php` | High
7 | File | `/ajax/openvpn/activate_ovpncfg.php` | High
8 | File | `/api/baskets/{name}` | High
9 | File | `/app/Http/Controllers/ImageController.php` | High
10 | File | `/app/index/controller/Common.php` | High
11 | File | `/applications/core/modules/admin/editor/toolbar.php` | High
12 | File | `/Applications/Google\ Drive.app/Contents/MacOS` | High
13 | File | `/applications/nexus/modules/front/store/store.php` | High
14 | File | `/apply.cgi` | Medium
15 | File | `/bitrix/admin/ldap_server_edit.php` | High
16 | File | `/books` | Low
17 | File | `/cgi-bin/cstecgi.cgi` | High
18 | File | `/cgi-bin/nas_sharing.cgi` | High
19 | File | `/cgi-bin/wlogin.cgi` | High
20 | File | `/classes/Master.php` | High
21 | File | `/classes/Master.php?f=save_category` | High
22 | File | `/classes/Users.php?f=save` | High
23 | File | `/College/admin/teacher.php` | High
24 | File | `/Controls/Generic/EBMK/Handlers/EStatements/DownloadEStatement.ashx` | High
25 | File | `/dcim/rack-roles/` | High
26 | File | `/dipam/athlete-profile.php` | High
27 | File | `/fftools/ffmpeg_enc.c` | High
28 | File | `/forms/doLogin` | High
29 | File | `/formSysLog` | Medium
30 | File | `/forum/away.php` | High
31 | File | `/goform/aspForm` | High
32 | File | `/goform/SetOnlineDevName` | High
33 | File | `/inc/topBarNav.php` | High
34 | File | `/includes/common/require_access_recovery.php` | High
35 | File | `/index.php` | Medium
36 | File | `/index.php?app=main&func=passport&action=login` | High
37 | File | `/install/` | Medium
38 | File | `/kelas/data` | Medium
39 | File | `/listplace/user/ticket/create` | High
40 | File | `/Main_Login.asp?flag=1&productname=RT-AC88U&url=/downloadmaster/task.asp` | High
41 | ... | ... | ...

There are 350 more IOA items available (file, library, argument, input value, pattern, network port). Please use our online service to access the data.

## References

The following list contains _external sources_ which discuss the actor and the associated activities:

* https://blog.reveng.ai/latrodectus-distribution-via-brc4/
* https://threatfox.abuse.ch
* https://www.proofpoint.com/us/blog/threat-insight/latrodectus-spider-bytes-ice
* https://www.rapid7.com/blog/post/2024/07/24/malware-campaign-lures-users-with-fake-w2-form/

## Literature

The following _articles_ explain our unique predictive cyber threat intelligence:

* [VulDB Cyber Threat Intelligence Documentation](https://vuldb.com/?kb.cti)
* [Cyber Threat Intelligence - Early Anticipation of Attacks](https://www.scip.ch/en/?labs.20201022)

## License

(c) [1997-2024](https://vuldb.com/?kb.changelog) by [vuldb.com](https://vuldb.com/?kb.about). All data on this page is shared under the license [CC BY-NC-SA 4.0](https://creativecommons.org/licenses/by-nc-sa/4.0/). Questions? Check the [FAQ](https://vuldb.com/?kb.faq), read the [documentation](https://vuldb.com/?kb) or [contact us](https://vuldb.com/?contact)!
