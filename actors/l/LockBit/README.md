# LockBit - Cyber Threat Intelligence

These _indicators_ were reported, collected, and generated during the [VulDB CTI analysis](https://vuldb.com/?kb.cti) of the actor known as [LockBit](https://vuldb.com/?actor.lockbit). The _activity monitoring_ correlates data from social media, forums, chat rooms, and darknet markets. It helps to determine associated actors, specific activities, expected intentions, emerging research, and ongoing attacks. Our unique _predictive model_ uses _big data_ to forecast activities and their characteristics.

_Live data_ and more _analysis capabilities_ are available at [https://vuldb.com/?actor.lockbit](https://vuldb.com/?actor.lockbit)

## Campaigns

The following _campaigns_ are known and can be associated with LockBit:

* CVE-2023-4966
* CVE-2023-38831
* South Korea

## Countries

These _countries_ are directly (e.g. origin of attacks) or indirectly (e.g. access by proxy) associated with LockBit:

* [US](https://vuldb.com/?country.us)
* [CN](https://vuldb.com/?country.cn)
* [RU](https://vuldb.com/?country.ru)
* ...

There are 21 more country items available. Please use our online service to access the data.

## IOC - Indicator of Compromise

These _indicators of compromise_ (IOC) indicate associated network resources which are known to be part of research and attack activities of LockBit.

ID | IP address | Hostname | Campaign | Confidence
-- | ---------- | -------- | -------- | ----------
1 | [5.252.176.47](https://vuldb.com/?ip.5.252.176.47) | no-rdns.mivocloud.com | CVE-2023-38831 | High
2 | [35.194.251.0](https://vuldb.com/?ip.35.194.251.0) | 0.251.194.35.bc.googleusercontent.com | - | Medium
3 | [45.11.27.232](https://vuldb.com/?ip.45.11.27.232) | - | CVE-2023-38831 | High
4 | [45.32.108.54](https://vuldb.com/?ip.45.32.108.54) | 45.32.108.54.vultrusercontent.com | - | Medium
5 | [45.87.245.30](https://vuldb.com/?ip.45.87.245.30) | - | CVE-2023-38831 | High
6 | [45.87.246.169](https://vuldb.com/?ip.45.87.246.169) | prod.andvo.ru | CVE-2023-38831 | High
7 | [45.91.83.176](https://vuldb.com/?ip.45.91.83.176) | - | - | High
8 | [45.129.137.233](https://vuldb.com/?ip.45.129.137.233) | - | CVE-2023-4966 | High
9 | [45.227.255.190](https://vuldb.com/?ip.45.227.255.190) | - | - | High
10 | [51.15.18.180](https://vuldb.com/?ip.51.15.18.180) | 51-15-18-180.rev.poneytelecom.eu | - | High
11 | [51.89.134.150](https://vuldb.com/?ip.51.89.134.150) | postal.sendovo.net | - | High
12 | [52.237.96.13](https://vuldb.com/?ip.52.237.96.13) | - | - | High
13 | [54.38.212.197](https://vuldb.com/?ip.54.38.212.197) | connect.eaglemarine.co.uk | - | High
14 | [54.84.248.205](https://vuldb.com/?ip.54.84.248.205) | ec2-54-84-248-205.compute-1.amazonaws.com | CVE-2023-4966 | Medium
15 | ... | ... | ... | ...

There are 55 more IOC items available. Please use our online service to access the data.

## TTP - Tactics, Techniques, Procedures

_Tactics, techniques, and procedures_ (TTP) summarize the suspected MITRE ATT&CK techniques used by _LockBit_. This data is unique as it uses our predictive model for actor profiling.

ID | Technique | Weakness | Description | Confidence
-- | --------- | -------- | ----------- | ----------
1 | T1006 | CWE-22, CWE-23, CWE-25, CWE-29, CWE-36, CWE-425 | Path Traversal | High
2 | T1055 | CWE-74, CWE-643 | Improper Neutralization of Data within XPath Expressions | High
3 | T1059 | CWE-88, CWE-94 | Argument Injection | High
4 | T1059.007 | CWE-79, CWE-80 | Cross Site Scripting | High
5 | ... | ... | ... | ...

There are 16 more TTP items available. Please use our online service to access the data.

## IOA - Indicator of Attack

These _indicators of attack_ (IOA) list the potential fragments used for technical activities like reconnaissance, exploitation, privilege escalation, and exfiltration by LockBit. This data is unique as it uses our predictive model for actor profiling.

ID | Type | Indicator | Confidence
-- | ---- | --------- | ----------
1 | File | `/#ilang=DE&b=c_smartenergy_swgroups` | High
2 | File | `/.pomerium` | Medium
3 | File | `/Account/login.php` | High
4 | File | `/admin/` | Low
5 | File | `/admin/?page=bike` | High
6 | File | `/admin/?page=musics/manage_music` | High
7 | File | `/admin/ajax.php?action=delete_user` | High
8 | File | `/Admin/changepassword.php` | High
9 | File | `/admin/cms_content.php` | High
10 | File | `/admin/emp-profile-avatar.php` | High
11 | File | `/admin/general-setting` | High
12 | File | `/admin/general/change-lang` | High
13 | File | `/admin/inquiries/view_inquiry.php` | High
14 | File | `/admin/order.php` | High
15 | File | `/admin/projects/{projectname}/skills/{skillname}/video` | High
16 | File | `/admin/service` | High
17 | File | `/adminapi/system/crud` | High
18 | File | `/adminapi/system/file/openfile` | High
19 | File | `/admin_route/dec_service_credits.php` | High
20 | File | `/api/v1/custom_component` | High
21 | File | `/api/v4/teams//channels/deleted` | High
22 | File | `/api/wechat/app_auth` | High
23 | File | `/api2/html/` | Medium
24 | File | `/cancel.php` | Medium
25 | File | `/car-rental-management-system/admin/index.php?page=manage_car` | High
26 | File | `/category.php` | High
27 | File | `/cgi-bin/cstecgi.cgi` | High
28 | File | `/cgi-bin/hd_config.cgi` | High
29 | File | `/cgi-bin/nas_sharing.cgi` | High
30 | File | `/cgi-bin/system_mgr.cgi` | High
31 | File | `/cgi-bin/wlogin.cgi` | High
32 | File | `/change-language/de_DE` | High
33 | File | `/classes/Master.php` | High
34 | File | `/classes/Master.php?f=delete_category` | High
35 | File | `/classes/Master.php?f=save_medicine` | High
36 | File | `/classes/SystemSettings.php?f=update_settings` | High
37 | File | `/classes/Users.php?f=delete` | High
38 | File | `/control/register_case.php` | High
39 | File | `/dev/nbdX` | Medium
40 | File | `/devinfo` | Medium
41 | File | `/dist/index.js` | High
42 | File | `/download` | Medium
43 | File | `/downloadFile.php` | High
44 | File | `/dtale/chart-data/1` | High
45 | File | `/DXR.axd` | Medium
46 | File | `/endpoint/add-folder.php` | High
47 | File | `/etc/shadow` | Medium
48 | File | `/file_manager/login.php` | High
49 | File | `/film-rating.php` | High
50 | File | `/foms/routers/place-order.php` | High
51 | File | `/forum/away.php` | High
52 | File | `/goform/SetIpMacBind` | High
53 | File | `/goform/WifiExtraSet` | High
54 | File | `/guestbook` | Medium
55 | File | `/index.jsp#settings` | High
56 | File | `/index.php` | Medium
57 | File | `/index.php/ccm/system/file/upload` | High
58 | ... | ... | ...

There are 504 more IOA items available (file, library, argument, input value, pattern, network port). Please use our online service to access the data.

## References

The following list contains _external sources_ which discuss the actor and the associated activities:

* https://1275.ru/ioc/158/lockbit-ransomware-iocs/
* https://asec.ahnlab.com/en/41450/
* https://asec.ahnlab.com/en/58750/
* https://blog.cyble.com/2023/06/06/lockbit-2-0-ransomware-resurfaces/
* https://cyble.com/blog/the-rise-of-head-mare-a-geopolitical-and-cybersecurity-analysis/
* https://github.com/hvs-consulting/ioc_signatures/blob/main/Proxyshell/HvS_Proxyshell_2021_09_IOCs.csv
* https://github.com/sophoslabs/IoCs/blob/master/Ransomware-LockBit.csv
* https://symantec-enterprise-blogs.security.com/blogs/threat-intelligence/3am-ransomware-lockbit
* https://thedfirreport.com/2020/06/10/lockbit-ransomware-why-you-no-spread/
* https://threatfox.abuse.ch
* https://twitter.com/OscarAldana/status/1548457335852437506
* https://www.cisa.gov/news-events/cybersecurity-advisories/aa23-325a
* https://www.cybereason.com/blog/threat-analysis-report-lockbit-2.0-all-paths-lead-to-ransom
* https://www.ic3.gov/Media/News/2022/220204.pdf
* https://www.mcafee.com/blogs/other-blogs/mcafee-labs/tales-from-the-trenches-a-lockbit-ransomware-story/
* https://www.proofpoint.com/us/blog/threat-insight/security-brief-millions-messages-distribute-lockbit-black-ransomware
* https://www.sentinelone.com/blog/living-off-windows-defender-lockbit-ransomware-sideloads-cobalt-strike-through-microsoft-security-tool/

## Literature

The following _articles_ explain our unique predictive cyber threat intelligence:

* [VulDB Cyber Threat Intelligence Documentation](https://vuldb.com/?kb.cti)
* [Cyber Threat Intelligence - Early Anticipation of Attacks](https://www.scip.ch/en/?labs.20201022)

## License

(c) [1997-2024](https://vuldb.com/?kb.changelog) by [vuldb.com](https://vuldb.com/?kb.about). All data on this page is shared under the license [CC BY-NC-SA 4.0](https://creativecommons.org/licenses/by-nc-sa/4.0/). Questions? Check the [FAQ](https://vuldb.com/?kb.faq), read the [documentation](https://vuldb.com/?kb) or [contact us](https://vuldb.com/?contact)!
