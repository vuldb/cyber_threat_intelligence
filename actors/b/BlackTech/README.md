# BlackTech - Cyber Threat Intelligence

These _indicators_ were reported, collected, and generated during the [VulDB CTI analysis](https://vuldb.com/?kb.cti) of the actor known as [BlackTech](https://vuldb.com/?actor.blacktech). The _activity monitoring_ correlates data from social media, forums, chat rooms, and darknet markets. It helps to determine associated actors, specific activities, expected intentions, emerging research, and ongoing attacks. Our unique _predictive model_ uses _big data_ to forecast activities and their characteristics.

_Live data_ and more _analysis capabilities_ are available at [https://vuldb.com/?actor.blacktech](https://vuldb.com/?actor.blacktech)

## Campaigns

The following _campaigns_ are known and can be associated with BlackTech:

* Taiwan Government Agencies
* TSCookie
* WaterBear

## Countries

These _countries_ are directly (e.g. origin of attacks) or indirectly (e.g. access by proxy) associated with BlackTech:

* [CN](https://vuldb.com/?country.cn)
* [US](https://vuldb.com/?country.us)
* [MS](https://vuldb.com/?country.ms)
* ...

There are 2 more country items available. Please use our online service to access the data.

## IOC - Indicator of Compromise

These _indicators of compromise_ (IOC) indicate associated network resources which are known to be part of research and attack activities of BlackTech.

ID | IP address | Hostname | Campaign | Confidence
-- | ---------- | -------- | -------- | ----------
1 | [10.0.0.211](https://vuldb.com/?ip.10.0.0.211) | - | WaterBear | High
2 | [43.240.12.81](https://vuldb.com/?ip.43.240.12.81) | mail.terascape.net | Taiwan Government Agencies | High
3 | [45.32.23.140](https://vuldb.com/?ip.45.32.23.140) | 45.32.23.140.vultrusercontent.com | - | Medium
4 | [45.76.102.145](https://vuldb.com/?ip.45.76.102.145) | 45.76.102.145.vultr.com | TSCookie | Medium
5 | [45.76.184.227](https://vuldb.com/?ip.45.76.184.227) | 45.76.184.227.vultrusercontent.com | - | Medium
6 | ... | ... | ... | ...

There are 18 more IOC items available. Please use our online service to access the data.

## TTP - Tactics, Techniques, Procedures

_Tactics, techniques, and procedures_ (TTP) summarize the suspected MITRE ATT&CK techniques used by _BlackTech_. This data is unique as it uses our predictive model for actor profiling.

ID | Technique | Weakness | Description | Confidence
-- | --------- | -------- | ----------- | ----------
1 | T1006 | CWE-21, CWE-22, CWE-23 | Path Traversal | High
2 | T1040 | CWE-319 | Authentication Bypass by Capture-replay | High
3 | T1055 | CWE-74 | Improper Neutralization of Data within XPath Expressions | High
4 | T1059 | CWE-94 | Argument Injection | High
5 | T1059.007 | CWE-79, CWE-80 | Cross Site Scripting | High
6 | ... | ... | ... | ...

There are 18 more TTP items available. Please use our online service to access the data.

## IOA - Indicator of Attack

These _indicators of attack_ (IOA) list the potential fragments used for technical activities like reconnaissance, exploitation, privilege escalation, and exfiltration by BlackTech. This data is unique as it uses our predictive model for actor profiling.

ID | Type | Indicator | Confidence
-- | ---- | --------- | ----------
1 | File | `/admin/foreigner-bwdates-reports-details.php` | High
2 | File | `/administration/theme.php` | High
3 | File | `/cdsms/classes/Master.php?f=delete_enrollment` | High
4 | File | `/cgi-bin/portal` | High
5 | File | `/cgi-mod/lookup.cgi` | High
6 | File | `/forum/away.php` | High
7 | File | `/mifs/c/i/reg/reg.html` | High
8 | File | `/modules/profile/index.php` | High
9 | File | `/pages/apply_vacancy.php` | High
10 | File | `/RPC2` | Low
11 | File | `/server-info` | Medium
12 | File | `/service/upload` | High
13 | File | `/services` | Medium
14 | File | `/system/dept/edit` | High
15 | File | `/tmp` | Low
16 | File | `/uncpath/` | Medium
17 | File | `/upload` | Low
18 | File | `/user/updatePwd` | High
19 | File | `/wp-json/oembed/1.0/embed?url` | High
20 | File | `a2billing/customer/iridium_threed.php` | High
21 | File | `additem.asp` | Medium
22 | File | `admin.php` | Medium
23 | File | `admin.php?s=/Channel/add.html` | High
24 | File | `admin/class-bulk-editor-list-table.php` | High
25 | ... | ... | ...

There are 214 more IOA items available (file, library, argument, input value, pattern, network port). Please use our online service to access the data.

## References

The following list contains _external sources_ which discuss the actor and the associated activities:

* https://blogs.jpcert.or.jp/en/2018/03/malware-tscooki-7aa0.html
* https://blogs.jpcert.or.jp/en/2021/10/gh0sttimes.html
* https://blogs.jpcert.or.jp/en/2022/09/bigip-exploit.html
* https://jp.security.ntt/tech_blog/102h7vx
* https://www.ithome.com.tw/news/139504
* https://www.lac.co.jp/lacwatch/people/20180425_001625.html
* https://www.trendmicro.com/en_us/research/17/f/following-trail-blacktech-cyber-espionage-campaigns.html
* https://www.trendmicro.com/en_us/research/19/l/waterbear-is-back-uses-api-hooking-to-evade-security-product-detection.html

## Literature

The following _articles_ explain our unique predictive cyber threat intelligence:

* [VulDB Cyber Threat Intelligence Documentation](https://vuldb.com/?kb.cti)
* [Cyber Threat Intelligence - Early Anticipation of Attacks](https://www.scip.ch/en/?labs.20201022)

## License

(c) [1997-2024](https://vuldb.com/?kb.changelog) by [vuldb.com](https://vuldb.com/?kb.about). All data on this page is shared under the license [CC BY-NC-SA 4.0](https://creativecommons.org/licenses/by-nc-sa/4.0/). Questions? Check the [FAQ](https://vuldb.com/?kb.faq), read the [documentation](https://vuldb.com/?kb) or [contact us](https://vuldb.com/?contact)!
