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

* [MS](https://vuldb.com/?country.ms)
* [CN](https://vuldb.com/?country.cn)
* [US](https://vuldb.com/?country.us)
* ...

There are 1 more country items available. Please use our online service to access the data.

## IOC - Indicator of Compromise

These _indicators of compromise_ (IOC) indicate associated network resources which are known to be part of research and attack activities of BlackTech.

ID | IP address | Hostname | Campaign | Confidence
-- | ---------- | -------- | -------- | ----------
1 | [10.0.0.211](https://vuldb.com/?ip.10.0.0.211) | - | WaterBear | High
2 | [43.240.12.81](https://vuldb.com/?ip.43.240.12.81) | mail.terascape.net | Taiwan Government Agencies | High
3 | [45.76.102.145](https://vuldb.com/?ip.45.76.102.145) | 45.76.102.145.vultr.com | TSCookie | Medium
4 | [45.124.25.31](https://vuldb.com/?ip.45.124.25.31) | hkhdc.laws.ms | Taiwan Government Agencies | High
5 | ... | ... | ... | ...

There are 14 more IOC items available. Please use our online service to access the data.

## TTP - Tactics, Techniques, Procedures

_Tactics, techniques, and procedures_ (TTP) summarize the suspected MITRE ATT&CK techniques used by _BlackTech_. This data is unique as it uses our predictive model for actor profiling.

ID | Technique | Weakness | Description | Confidence
-- | --------- | -------- | ----------- | ----------
1 | T1006 | CWE-21, CWE-22, CWE-23 | Pathname Traversal | High
2 | T1040 | CWE-319 | Authentication Bypass by Capture-replay | High
3 | T1055 | CWE-74 | Injection | High
4 | T1059 | CWE-94 | Cross Site Scripting | High
5 | ... | ... | ... | ...

There are 17 more TTP items available. Please use our online service to access the data.

## IOA - Indicator of Attack

These _indicators of attack_ (IOA) list the potential fragments used for technical activities like reconnaissance, exploitation, privilege escalation, and exfiltration by BlackTech. This data is unique as it uses our predictive model for actor profiling.

ID | Type | Indicator | Confidence
-- | ---- | --------- | ----------
1 | File | `/cdsms/classes/Master.php?f=delete_enrollment` | High
2 | File | `/cgi-bin/portal` | High
3 | File | `/cgi-mod/lookup.cgi` | High
4 | File | `/forum/away.php` | High
5 | File | `/mifs/c/i/reg/reg.html` | High
6 | File | `/modules/profile/index.php` | High
7 | File | `/RPC2` | Low
8 | File | `/server-info` | Medium
9 | File | `/service/upload` | High
10 | File | `/tmp` | Low
11 | File | `/uncpath/` | Medium
12 | File | `/wp-json/oembed/1.0/embed?url` | High
13 | File | `a2billing/customer/iridium_threed.php` | High
14 | File | `admin.php` | Medium
15 | File | `admin.php?s=/Channel/add.html` | High
16 | File | `admin/class-bulk-editor-list-table.php` | High
17 | File | `administrator/components/com_media/helpers/media.php` | High
18 | ... | ... | ...

There are 143 more IOA items available (file, library, argument, input value, pattern, network port). Please use our online service to access the data.

## References

The following list contains _external sources_ which discuss the actor and the associated activities:

* https://blogs.jpcert.or.jp/en/2018/03/malware-tscooki-7aa0.html
* https://blogs.jpcert.or.jp/en/2021/10/gh0sttimes.html
* https://blogs.jpcert.or.jp/en/2022/09/bigip-exploit.html
* https://www.ithome.com.tw/news/139504
* https://www.trendmicro.com/en_us/research/17/f/following-trail-blacktech-cyber-espionage-campaigns.html
* https://www.trendmicro.com/en_us/research/19/l/waterbear-is-back-uses-api-hooking-to-evade-security-product-detection.html

## Literature

The following _articles_ explain our unique predictive cyber threat intelligence:

* [VulDB Cyber Threat Intelligence Documentation](https://vuldb.com/?kb.cti)
* [Cyber Threat Intelligence - Early Anticipation of Attacks](https://www.scip.ch/en/?labs.20201022)

## License

(c) [1997-2022](https://vuldb.com/?kb.changelog) by [vuldb.com](https://vuldb.com/?kb.about). All data on this page is shared under the license [CC BY-NC-SA 4.0](https://creativecommons.org/licenses/by-nc-sa/4.0/). Questions? Check the [FAQ](https://vuldb.com/?kb.faq), read the [documentation](https://vuldb.com/?kb) or [contact us](https://vuldb.com/?contact)!
