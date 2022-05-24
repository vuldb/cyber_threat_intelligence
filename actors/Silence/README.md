# Silence - Cyber Threat Intelligence

These _indicators_ were reported, collected, and generated during the [VulDB CTI analysis](https://vuldb.com/?kb.cti) of the actor known as [Silence](https://vuldb.com/?actor.silence). The _activity monitoring_ correlates data from social media, forums, chat rooms, and darknet markets. It helps to determine associated actors, specific activities, expected intentions, emerging research, and ongoing attacks. Our unique _predictive model_ uses _big data_ to forecast activities and their characteristics.

_Live data_ and more _analysis capabilities_ are available at [https://vuldb.com/?actor.silence](https://vuldb.com/?actor.silence)

## Countries

These _countries_ are directly (e.g. origin of attacks) or indirectly (e.g. access by proxy) associated with Silence:

* [CN](https://vuldb.com/?country.cn)
* [US](https://vuldb.com/?country.us)
* [ES](https://vuldb.com/?country.es)
* ...

There are 27 more country items available. Please use our online service to access the data.

## IOC - Indicator of Compromise

These _indicators of compromise_ (IOC) indicate associated network resources which are known to be part of research and attack activities of Silence.

ID | IP address | Hostname | Campaign | Confidence
-- | ---------- | -------- | -------- | ----------
1 | [5.8.88.254](https://vuldb.com/?ip.5.8.88.254) | - | - | High
2 | [5.39.30.110](https://vuldb.com/?ip.5.39.30.110) | ip110.ip-5-39-30.eu | - | High
3 | [5.39.218.162](https://vuldb.com/?ip.5.39.218.162) | - | - | High
4 | [5.39.218.205](https://vuldb.com/?ip.5.39.218.205) | - | - | High
5 | [5.39.218.210](https://vuldb.com/?ip.5.39.218.210) | mail.qbmail.biz | - | High
6 | [5.39.221.46](https://vuldb.com/?ip.5.39.221.46) | - | - | High
7 | [5.39.221.60](https://vuldb.com/?ip.5.39.221.60) | - | - | High
8 | [5.154.191.105](https://vuldb.com/?ip.5.154.191.105) | - | - | High
9 | [5.188.231.47](https://vuldb.com/?ip.5.188.231.47) | - | - | High
10 | [5.188.231.89](https://vuldb.com/?ip.5.188.231.89) | - | - | High
11 | [5.200.55.198](https://vuldb.com/?ip.5.200.55.198) | - | - | High
12 | [5.200.56.161](https://vuldb.com/?ip.5.200.56.161) | - | - | High
13 | [31.31.204.161](https://vuldb.com/?ip.31.31.204.161) | - | - | High
14 | [31.41.47.190](https://vuldb.com/?ip.31.41.47.190) | official.zzar.top | - | High
15 | [31.207.45.85](https://vuldb.com/?ip.31.207.45.85) | - | - | High
16 | [46.30.43.83](https://vuldb.com/?ip.46.30.43.83) | free.eurobyte.ru | - | High
17 | [46.170.125.222](https://vuldb.com/?ip.46.170.125.222) | 3.silopol.eu | - | High
18 | [46.183.221.37](https://vuldb.com/?ip.46.183.221.37) | ip-221-37.dataclub.info | - | High
19 | [46.183.221.89](https://vuldb.com/?ip.46.183.221.89) | ip-221-89.dataclub.info | - | High
20 | [51.255.200.161](https://vuldb.com/?ip.51.255.200.161) | 161.ip-51-255-200.eu | - | High
21 | [54.36.191.97](https://vuldb.com/?ip.54.36.191.97) | vps-58b2e5b8.vps.ovh.net | - | High
22 | [62.57.131.114](https://vuldb.com/?ip.62.57.131.114) | 62.57.131.114.dyn.user.ono.com | - | High
23 | [74.220.215.239](https://vuldb.com/?ip.74.220.215.239) | host239.hostmonster.com | - | High
24 | [77.246.145.82](https://vuldb.com/?ip.77.246.145.82) | skoderyaru2.e-vds.ru | - | High
25 | [77.246.145.86](https://vuldb.com/?ip.77.246.145.86) | znatokfinansov.ru | - | High
26 | ... | ... | ... | ...

There are 101 more IOC items available. Please use our online service to access the data.

## TTP - Tactics, Techniques, Procedures

_Tactics, techniques, and procedures_ (TTP) summarize the suspected MITRE ATT&CK techniques used by _Silence_. This data is unique as it uses our predictive model for actor profiling.

ID | Technique | Weakness | Description | Confidence
-- | --------- | -------- | ----------- | ----------
1 | T1059.007 | CWE-79, CWE-80 | Cross Site Scripting | High
2 | T1068 | CWE-264, CWE-266, CWE-284 | Execution with Unnecessary Privileges | High
3 | T1110.001 | CWE-798 | Improper Restriction of Excessive Authentication Attempts | High
4 | ... | ... | ... | ...

There are 5 more TTP items available. Please use our online service to access the data.

## IOA - Indicator of Attack

These _indicators of attack_ (IOA) list the potential fragments used for technical activities like reconnaissance, exploitation, privilege escalation, and exfiltration by Silence. This data is unique as it uses our predictive model for actor profiling.

ID | Type | Indicator | Confidence
-- | ---- | --------- | ----------
1 | File | `/?module=users&section=cpanel&page=list` | High
2 | File | `/admin/powerline` | High
3 | File | `/admin/syslog` | High
4 | File | `/api/upload` | Medium
5 | File | `/cgi-bin` | Medium
6 | File | `/cgi-bin/kerbynet` | High
7 | File | `/context/%2e/WEB-INF/web.xml` | High
8 | File | `/dcim/sites/add/` | High
9 | File | `/download` | Medium
10 | File | `/EXCU_SHELL` | Medium
11 | File | `/forum/away.php` | High
12 | File | `/fudforum/adm/hlplist.php` | High
13 | File | `/inc/extensions.php` | High
14 | File | `/login` | Low
15 | File | `/Main_Login.asp?flag=1&productname=RT-AC88U&url=/downloadmaster/task.asp` | High
16 | File | `/monitoring` | Medium
17 | File | `/new` | Low
18 | File | `/nova/bin/console` | High
19 | File | `/proc/<pid>/status` | High
20 | File | `/public/plugins/` | High
21 | File | `/req_password_user.php` | High
22 | File | `/rom` | Low
23 | File | `/scripts/killpvhost` | High
24 | File | `/secure/admin/InsightDefaultCustomFieldConfig.jspa` | High
25 | File | `/secure/QueryComponent!Default.jspa` | High
26 | File | `/src/main/java/com/dotmarketing/filters/CMSFilter.java` | High
27 | File | `/tmp` | Low
28 | File | `/tmp/redis.ds` | High
29 | File | `/uncpath/` | Medium
30 | File | `/ViewUserHover.jspa` | High
31 | File | `/WEB-INF/web.xml` | High
32 | File | `/wp-admin` | Medium
33 | File | `/wp-json/wc/v3/webhooks` | High
34 | File | `14all.cgi/14all-1.1.cgi/traffic.cgi/mrtg.cgi` | High
35 | File | `AccountManagerService.java` | High
36 | ... | ... | ...

There are 313 more IOA items available (file, library, argument, input value, pattern, network port). Please use our online service to access the data.

## References

The following list contains _external sources_ which discuss the actor and the associated activities:

* https://cyberforensicator.com/2019/01/20/silence-dissecting-malicious-chm-files-and-performing-forensic-analysis/
* https://securelist.com/the-silence/83009/
* https://www.group-ib.com/resources/threat-research/silence_2.0.going_global.pdf
* https://www.group-ib.com/resources/threat-research/silence_moving-into-the-darkside.pdf

## Literature

The following _articles_ explain our unique predictive cyber threat intelligence:

* [VulDB Cyber Threat Intelligence Documentation](https://vuldb.com/?kb.cti)
* [Cyber Threat Intelligence - Early Anticipation of Attacks](https://www.scip.ch/en/?labs.20201022)

## License

(c) [1997-2022](https://vuldb.com/?kb.changelog) by [vuldb.com](https://vuldb.com/?kb.about). All data on this page is shared under the license [CC BY-NC-SA 4.0](https://creativecommons.org/licenses/by-nc-sa/4.0/). Questions? Check the [FAQ](https://vuldb.com/?kb.faq), read the [documentation](https://vuldb.com/?kb) or [contact us](https://vuldb.com/?contact)!
