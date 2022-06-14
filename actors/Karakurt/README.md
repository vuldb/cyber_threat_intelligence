# Karakurt - Cyber Threat Intelligence

These _indicators_ were reported, collected, and generated during the [VulDB CTI analysis](https://vuldb.com/?kb.cti) of the actor known as [Karakurt](https://vuldb.com/?actor.karakurt). The _activity monitoring_ correlates data from social media, forums, chat rooms, and darknet markets. It helps to determine associated actors, specific activities, expected intentions, emerging research, and ongoing attacks. Our unique _predictive model_ uses _big data_ to forecast activities and their characteristics.

_Live data_ and more _analysis capabilities_ are available at [https://vuldb.com/?actor.karakurt](https://vuldb.com/?actor.karakurt)

## Countries

These _countries_ are directly (e.g. origin of attacks) or indirectly (e.g. access by proxy) associated with Karakurt:

* [CN](https://vuldb.com/?country.cn)
* [US](https://vuldb.com/?country.us)
* [ES](https://vuldb.com/?country.es)
* ...

There are 25 more country items available. Please use our online service to access the data.

## IOC - Indicator of Compromise

These _indicators of compromise_ (IOC) indicate associated network resources which are known to be part of research and attack activities of Karakurt.

ID | IP address | Hostname | Campaign | Confidence
-- | ---------- | -------- | -------- | ----------
1 | [1.116.139.11](https://vuldb.com/?ip.1.116.139.11) | - | - | High
2 | [5.45.83.32](https://vuldb.com/?ip.5.45.83.32) | - | - | High
3 | [23.99.177.202](https://vuldb.com/?ip.23.99.177.202) | - | - | High
4 | [31.14.40.64](https://vuldb.com/?ip.31.14.40.64) | - | - | High
5 | [37.252.0.143](https://vuldb.com/?ip.37.252.0.143) | - | - | High
6 | ... | ... | ... | ...

There are 18 more IOC items available. Please use our online service to access the data.

## TTP - Tactics, Techniques, Procedures

_Tactics, techniques, and procedures_ (TTP) summarize the suspected MITRE ATT&CK techniques used by _Karakurt_. This data is unique as it uses our predictive model for actor profiling.

ID | Technique | Weakness | Description | Confidence
-- | --------- | -------- | ----------- | ----------
1 | T1059.007 | CWE-79, CWE-80 | Cross Site Scripting | High
2 | T1068 | CWE-264, CWE-266, CWE-284 | Execution with Unnecessary Privileges | High
3 | T1110.001 | CWE-798 | Improper Restriction of Excessive Authentication Attempts | High
4 | ... | ... | ... | ...

There are 5 more TTP items available. Please use our online service to access the data.

## IOA - Indicator of Attack

These _indicators of attack_ (IOA) list the potential fragments used for technical activities like reconnaissance, exploitation, privilege escalation, and exfiltration by Karakurt. This data is unique as it uses our predictive model for actor profiling.

ID | Type | Indicator | Confidence
-- | ---- | --------- | ----------
1 | File | `/?module=users&section=cpanel&page=list` | High
2 | File | `/admin/powerline` | High
3 | File | `/admin/syslog` | High
4 | File | `/api/upload` | Medium
5 | File | `/bcms/admin/?page=user/list` | High
6 | File | `/cgi-bin` | Medium
7 | File | `/cgi-bin/kerbynet` | High
8 | File | `/context/%2e/WEB-INF/web.xml` | High
9 | File | `/dcim/sites/add/` | High
10 | File | `/debug/pprof` | Medium
11 | File | `/EXCU_SHELL` | Medium
12 | File | `/forum/away.php` | High
13 | File | `/fudforum/adm/hlplist.php` | High
14 | File | `/fuel/index.php/fuel/logs/items` | High
15 | File | `/login` | Low
16 | File | `/Main_Login.asp?flag=1&productname=RT-AC88U&url=/downloadmaster/task.asp` | High
17 | File | `/mgmt/tm/util/bash` | High
18 | File | `/monitoring` | Medium
19 | File | `/new` | Low
20 | File | `/proc/<pid>/status` | High
21 | File | `/public/plugins/` | High
22 | File | `/rom` | Low
23 | File | `/s/` | Low
24 | File | `/scripts/killpvhost` | High
25 | File | `/secure/admin/InsightDefaultCustomFieldConfig.jspa` | High
26 | File | `/secure/QueryComponent!Default.jspa` | High
27 | File | `/simple_chat_bot/admin/?page=user/manage_user` | High
28 | File | `/src/main/java/com/dotmarketing/filters/CMSFilter.java` | High
29 | File | `/tmp` | Low
30 | File | `/tmp/redis.ds` | High
31 | File | `/uncpath/` | Medium
32 | File | `/views/directive/sys/SysConfigDataDirective.java` | High
33 | File | `/wp-admin` | Medium
34 | File | `/wp-json/wc/v3/webhooks` | High
35 | File | `14all.cgi/14all-1.1.cgi/traffic.cgi/mrtg.cgi` | High
36 | File | `AccountManagerService.java` | High
37 | ... | ... | ...

There are 317 more IOA items available (file, library, argument, input value, pattern, network port). Please use our online service to access the data.

## References

The following list contains _external sources_ which discuss the actor and the associated activities:

* https://github.com/infinitumitlabs/Karakurt-Hacking-Team-CTI
* https://www.bleepingcomputer.com/news/security/karakurt-revealed-as-data-extortion-arm-of-conti-cybercrime-syndicate/

## Literature

The following _articles_ explain our unique predictive cyber threat intelligence:

* [VulDB Cyber Threat Intelligence Documentation](https://vuldb.com/?kb.cti)
* [Cyber Threat Intelligence - Early Anticipation of Attacks](https://www.scip.ch/en/?labs.20201022)

## License

(c) [1997-2022](https://vuldb.com/?kb.changelog) by [vuldb.com](https://vuldb.com/?kb.about). All data on this page is shared under the license [CC BY-NC-SA 4.0](https://creativecommons.org/licenses/by-nc-sa/4.0/). Questions? Check the [FAQ](https://vuldb.com/?kb.faq), read the [documentation](https://vuldb.com/?kb) or [contact us](https://vuldb.com/?contact)!
