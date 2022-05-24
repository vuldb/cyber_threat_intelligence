# Mirai - Cyber Threat Intelligence

These _indicators_ were reported, collected, and generated during the [VulDB CTI analysis](https://vuldb.com/?kb.cti) of the actor known as [Mirai](https://vuldb.com/?actor.mirai). The _activity monitoring_ correlates data from social media, forums, chat rooms, and darknet markets. It helps to determine associated actors, specific activities, expected intentions, emerging research, and ongoing attacks. Our unique _predictive model_ uses _big data_ to forecast activities and their characteristics.

_Live data_ and more _analysis capabilities_ are available at [https://vuldb.com/?actor.mirai](https://vuldb.com/?actor.mirai)

## Campaigns

The following _campaigns_ are known and can be associated with Mirai:

* CVE-2020-9054
* DDoS Ukraine
* Log4Shell

## Countries

These _countries_ are directly (e.g. origin of attacks) or indirectly (e.g. access by proxy) associated with Mirai:

* [US](https://vuldb.com/?country.us)
* [ES](https://vuldb.com/?country.es)
* [CN](https://vuldb.com/?country.cn)
* ...

There are 2 more country items available. Please use our online service to access the data.

## IOC - Indicator of Compromise

These _indicators of compromise_ (IOC) indicate associated network resources which are known to be part of research and attack activities of Mirai.

ID | IP address | Hostname | Campaign | Confidence
-- | ---------- | -------- | -------- | ----------
1 | [2.56.56.78](https://vuldb.com/?ip.2.56.56.78) | - | - | High
2 | [5.2.69.50](https://vuldb.com/?ip.5.2.69.50) | - | - | High
3 | [5.182.211.5](https://vuldb.com/?ip.5.182.211.5) | - | - | High
4 | [23.128.248.12](https://vuldb.com/?ip.23.128.248.12) | tor-exit03.stormycloud.org | - | High
5 | [23.128.248.24](https://vuldb.com/?ip.23.128.248.24) | tor-exit15.stormycloud.org | - | High
6 | [34.80.131.135](https://vuldb.com/?ip.34.80.131.135) | 135.131.80.34.bc.googleusercontent.com | - | Medium
7 | [37.187.18.212](https://vuldb.com/?ip.37.187.18.212) | ns3110317.ip-37-187-18.eu | - | High
8 | [45.61.136.130](https://vuldb.com/?ip.45.61.136.130) | - | DDoS Ukraine | High
9 | [45.61.186.13](https://vuldb.com/?ip.45.61.186.13) | - | DDoS Ukraine | High
10 | ... | ... | ... | ...

There are 35 more IOC items available. Please use our online service to access the data.

## TTP - Tactics, Techniques, Procedures

_Tactics, techniques, and procedures_ (TTP) summarize the suspected MITRE ATT&CK techniques used by _Mirai_. This data is unique as it uses our predictive model for actor profiling.

ID | Technique | Weakness | Description | Confidence
-- | --------- | -------- | ----------- | ----------
1 | T1059.007 | CWE-79, CWE-80 | Cross Site Scripting | High
2 | T1068 | CWE-264, CWE-266, CWE-274, CWE-284 | Execution with Unnecessary Privileges | High
3 | T1110.001 | CWE-307, CWE-798 | Improper Restriction of Excessive Authentication Attempts | High
4 | ... | ... | ... | ...

There are 8 more TTP items available. Please use our online service to access the data.

## IOA - Indicator of Attack

These _indicators of attack_ (IOA) list the potential fragments used for technical activities like reconnaissance, exploitation, privilege escalation, and exfiltration by Mirai. This data is unique as it uses our predictive model for actor profiling.

ID | Type | Indicator | Confidence
-- | ---- | --------- | ----------
1 | File | `/adm/setmain.php` | High
2 | File | `/admin.php/Plugins/update.html` | High
3 | File | `/admin/new-content` | High
4 | File | `/api/students/me/courses/` | High
5 | File | `/Applications/Utilities/Terminal` | High
6 | File | `/classes/master.php?f=delete_facility` | High
7 | File | `/College_Management_System/admin/display-teacher.php` | High
8 | File | `/common/info.cgi` | High
9 | File | `/coreframe/app/member/admin/group.php` | High
10 | File | `/ctpms/admin/?page=applications/view_application` | High
11 | File | `/ctpms/admin/?page=individuals/view_individual` | High
12 | File | `/ctpms/admin/applications/update_status.php` | High
13 | File | `/ctpms/admin/individuals/update_status.php` | High
14 | File | `/ctpms/classes/Master.php?f=delete_application` | High
15 | File | `/default.php?idx=17` | High
16 | File | `/ecrire` | Low
17 | File | `/eris/index.php?q=result&searchfor=advancesearch` | High
18 | File | `/exports/export.php` | High
19 | File | `/fuel/index.php/fuel/logs/items` | High
20 | File | `/goform/setDeviceSettings` | High
21 | File | `/goform/setMacFilterCfg` | High
22 | File | `/html/Solar_Ftp.php` | High
23 | File | `/include/chart_generator.php` | High
24 | File | `/includes/login.php` | High
25 | File | `/index.php?p=admin/actions/users/send-password-reset-email` | High
26 | File | `/insurance/editPayment.php` | High
27 | File | `/mgmt/tm/util/bash` | High
28 | File | `/page.php` | Medium
29 | File | `/public/admin/index.php?add_product` | High
30 | File | `/scbs/classes/Users.php?f=save_client` | High
31 | ... | ... | ...

There are 262 more IOA items available (file, library, argument, input value, pattern, network port). Please use our online service to access the data.

## References

The following list contains _external sources_ which discuss the actor and the associated activities:

* https://blog.cyble.com/2022/04/12/springshell-remote-code-execution-vulnerability/
* https://blog.netlab.360.com/early-warning-a-new-mirai-variant-is-spreading-quickly-on-port-23-and-2323-en/
* https://blog.netlab.360.com/emptiness-a-new-evolving-botnet/
* https://blog.netlab.360.com/gpon-exploit-in-the-wild-iii-mettle-hajime-mirai-omni-imgay/
* https://blog.netlab.360.com/some_details_of_the_ddos_attacks_targeting_ukraine_and_russia_in_recent_days/
* https://blog.netlab.360.com/wei-xie-kuai-xun-log4jlou-dong-yi-jing-bei-yong-lai-zu-jian-botnet-zhen-dui-linuxshe-bei/
* https://blog.netlab.360.com/what-our-honeypot-sees-just-one-day-after-the-spring4shell-advisory-en/
* https://blog.netlab.360.com/wo-men-kan-dao-de-wu-ke-lan-bei-ddosgong-ji-xi-jie/
* https://blogs.infoblox.com/cyber-threat-intelligence/cyber-campaign-briefs/log4j-indicators-of-compromise-to-date/
* https://isc.sans.edu/forums/diary/Mirai+Botnet+Activity/26234/
* https://isc.sans.edu/forums/diary/Scanning+Activity+end+Goal+is+to+add+Hosts+to+Mirai+Botnet/24450/
* https://isc.sans.edu/forums/diary/Zyxel+Network+Storage+Devices+Hunted+By+Mirai+Variant/28324/
* https://urlhaus.abuse.ch/host/185.243.56.167/

## Literature

The following _articles_ explain our unique predictive cyber threat intelligence:

* [VulDB Cyber Threat Intelligence Documentation](https://vuldb.com/?kb.cti)
* [Cyber Threat Intelligence - Early Anticipation of Attacks](https://www.scip.ch/en/?labs.20201022)

## License

(c) [1997-2022](https://vuldb.com/?kb.changelog) by [vuldb.com](https://vuldb.com/?kb.about). All data on this page is shared under the license [CC BY-NC-SA 4.0](https://creativecommons.org/licenses/by-nc-sa/4.0/). Questions? Check the [FAQ](https://vuldb.com/?kb.faq), read the [documentation](https://vuldb.com/?kb) or [contact us](https://vuldb.com/?contact)!
