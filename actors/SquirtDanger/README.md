# SquirtDanger - Cyber Threat Intelligence

These _indicators_ were reported, collected, and generated during the [VulDB CTI analysis](https://vuldb.com/?kb.cti) of the actor known as [SquirtDanger](https://vuldb.com/?actor.squirtdanger). The _activity monitoring_ correlates data from social media, forums, chat rooms, and darknet markets. It helps to determine associated actors, specific activities, expected intentions, emerging research, and ongoing attacks. Our unique _predictive model_ uses _big data_ to forecast activities and their characteristics.

_Live data_ and more _analysis capabilities_ are available at [https://vuldb.com/?actor.squirtdanger](https://vuldb.com/?actor.squirtdanger)

## Countries

These _countries_ are directly (e.g. origin of attacks) or indirectly (e.g. access by proxy) associated with SquirtDanger:

* [CN](https://vuldb.com/?country.cn)
* [US](https://vuldb.com/?country.us)
* [ES](https://vuldb.com/?country.es)
* ...

There are 23 more country items available. Please use our online service to access the data.

## IOC - Indicator of Compromise

These _indicators of compromise_ (IOC) indicate associated network resources which are known to be part of research and attack activities of SquirtDanger.

ID | IP address | Hostname | Campaign | Confidence
-- | ---------- | -------- | -------- | ----------
1 | [5.188.231.107](https://vuldb.com/?ip.5.188.231.107) | - | - | High
2 | [5.188.231.246](https://vuldb.com/?ip.5.188.231.246) | - | - | High
3 | [37.252.14.159](https://vuldb.com/?ip.37.252.14.159) | - | - | High
4 | [62.141.42.190](https://vuldb.com/?ip.62.141.42.190) | mail.borengo.com | - | High
5 | [62.210.139.234](https://vuldb.com/?ip.62.210.139.234) | web3.groupe-nlcl.com | - | High
6 | [62.210.142.233](https://vuldb.com/?ip.62.210.142.233) | 62-210-142-233.rev.poneytelecom.eu | - | High
7 | [77.220.212.78](https://vuldb.com/?ip.77.220.212.78) | vm3071969.33ssd.had.wf | - | High
8 | [81.4.104.135](https://vuldb.com/?ip.81.4.104.135) | ramnode.schmidtie.net | - | High
9 | [81.177.139.248](https://vuldb.com/?ip.81.177.139.248) | - | - | High
10 | [82.202.231.21](https://vuldb.com/?ip.82.202.231.21) | - | - | High
11 | [86.110.118.102](https://vuldb.com/?ip.86.110.118.102) | - | - | High
12 | [92.53.90.11](https://vuldb.com/?ip.92.53.90.11) | - | - | High
13 | [92.63.197.19](https://vuldb.com/?ip.92.63.197.19) | - | - | High
14 | [93.171.138.195](https://vuldb.com/?ip.93.171.138.195) | host-195.primonet.com.ua | - | High
15 | [94.23.20.210](https://vuldb.com/?ip.94.23.20.210) | ovh7.siscomvigo.com | - | High
16 | [95.47.137.169](https://vuldb.com/?ip.95.47.137.169) | - | - | High
17 | [136.243.88.145](https://vuldb.com/?ip.136.243.88.145) | static.145.88.243.136.clients.your-server.de | - | High
18 | [136.243.94.27](https://vuldb.com/?ip.136.243.94.27) | static.27.94.243.136.clients.your-server.de | - | High
19 | [136.243.102.157](https://vuldb.com/?ip.136.243.102.157) | static.157.102.243.136.clients.your-server.de | - | High
20 | [151.236.30.50](https://vuldb.com/?ip.151.236.30.50) | 50.30.236.151.in-addr.arpa | - | High
21 | [176.9.0.89](https://vuldb.com/?ip.176.9.0.89) | static.89.0.9.176.clients.your-server.de | - | High
22 | [176.9.47.243](https://vuldb.com/?ip.176.9.47.243) | raphinida.de | - | High
23 | [178.158.17.134](https://vuldb.com/?ip.178.158.17.134) | - | - | High
24 | [185.48.56.223](https://vuldb.com/?ip.185.48.56.223) | - | - | High
25 | ... | ... | ... | ...

There are 95 more IOC items available. Please use our online service to access the data.

## TTP - Tactics, Techniques, Procedures

_Tactics, techniques, and procedures_ (TTP) summarize the suspected MITRE ATT&CK techniques used by _SquirtDanger_. This data is unique as it uses our predictive model for actor profiling.

ID | Technique | Weakness | Description | Confidence
-- | --------- | -------- | ----------- | ----------
1 | T1059.007 | CWE-79, CWE-80 | Cross Site Scripting | High
2 | T1068 | CWE-264, CWE-266, CWE-284 | Execution with Unnecessary Privileges | High
3 | T1110.001 | CWE-307, CWE-798 | Improper Restriction of Excessive Authentication Attempts | High
4 | ... | ... | ... | ...

There are 4 more TTP items available. Please use our online service to access the data.

## IOA - Indicator of Attack

These _indicators of attack_ (IOA) list the potential fragments used for technical activities like reconnaissance, exploitation, privilege escalation, and exfiltration by SquirtDanger. This data is unique as it uses our predictive model for actor profiling.

ID | Type | Indicator | Confidence
-- | ---- | --------- | ----------
1 | File | `//proc/kcore` | Medium
2 | File | `/?module=users&section=cpanel&page=list` | High
3 | File | `/admin/powerline` | High
4 | File | `/admin/syslog` | High
5 | File | `/Ap4RtpAtom.cpp` | High
6 | File | `/api/upload` | Medium
7 | File | `/app/Http/Controllers/Admin/NEditorController.php` | High
8 | File | `/bcms/admin/?page=user/list` | High
9 | File | `/cgi-bin` | Medium
10 | File | `/context/%2e/WEB-INF/web.xml` | High
11 | File | `/debug/pprof` | Medium
12 | File | `/fuel/index.php/fuel/logs/items` | High
13 | File | `/fuel/sitevariables/delete/4` | High
14 | File | `/login` | Low
15 | File | `/Main_Login.asp?flag=1&productname=RT-AC88U&url=/downloadmaster/task.asp` | High
16 | File | `/mgmt/tm/util/bash` | High
17 | File | `/monitoring` | Medium
18 | File | `/new` | Low
19 | File | `/proc/<pid>/status` | High
20 | File | `/public/plugins/` | High
21 | File | `/scripts/killpvhost` | High
22 | File | `/secure/admin/InsightDefaultCustomFieldConfig.jspa` | High
23 | File | `/secure/QueryComponent!Default.jspa` | High
24 | File | `/simple_chat_bot/admin/?page=user/manage_user` | High
25 | File | `/src/main/java/com/dotmarketing/filters/CMSFilter.java` | High
26 | File | `/tmp` | Low
27 | File | `/tmp/redis.ds` | High
28 | File | `/uncpath/` | Medium
29 | File | `/views/directive/sys/SysConfigDataDirective.java` | High
30 | File | `/wp-admin` | Medium
31 | File | `/wp-admin/admin.php?page=wp_file_manager_properties` | High
32 | File | `/wp-json/wc/v3/webhooks` | High
33 | File | `14all.cgi/14all-1.1.cgi/traffic.cgi/mrtg.cgi` | High
34 | File | `AccountManagerService.java` | High
35 | File | `actions/CompanyDetailsSave.php` | High
36 | File | `ActiveServices.java` | High
37 | ... | ... | ...

There are 313 more IOA items available (file, library, argument, input value, pattern, network port). Please use our online service to access the data.

## References

The following list contains _external sources_ which discuss the actor and the associated activities:

* https://unit42.paloaltonetworks.com/unit42-squirtdanger-swiss-army-knife-malware-veteran-malware-author-thebottle/

## Literature

The following _articles_ explain our unique predictive cyber threat intelligence:

* [VulDB Cyber Threat Intelligence Documentation](https://vuldb.com/?kb.cti)
* [Cyber Threat Intelligence - Early Anticipation of Attacks](https://www.scip.ch/en/?labs.20201022)

## License

(c) [1997-2022](https://vuldb.com/?kb.changelog) by [vuldb.com](https://vuldb.com/?kb.about). All data on this page is shared under the license [CC BY-NC-SA 4.0](https://creativecommons.org/licenses/by-nc-sa/4.0/). Questions? Check the [FAQ](https://vuldb.com/?kb.faq), read the [documentation](https://vuldb.com/?kb) or [contact us](https://vuldb.com/?contact)!
