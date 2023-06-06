# Agent Tesla - Cyber Threat Intelligence

These _indicators_ were reported, collected, and generated during the [VulDB CTI analysis](https://vuldb.com/?kb.cti) of the actor known as [Agent Tesla](https://vuldb.com/?actor.agent_tesla). The _activity monitoring_ correlates data from social media, forums, chat rooms, and darknet markets. It helps to determine associated actors, specific activities, expected intentions, emerging research, and ongoing attacks. Our unique _predictive model_ uses _big data_ to forecast activities and their characteristics.

_Live data_ and more _analysis capabilities_ are available at [https://vuldb.com/?actor.agent_tesla](https://vuldb.com/?actor.agent_tesla)

## Campaigns

The following _campaigns_ are known and can be associated with Agent Tesla:

* Phishing Korea

## Countries

These _countries_ are directly (e.g. origin of attacks) or indirectly (e.g. access by proxy) associated with Agent Tesla:

* [US](https://vuldb.com/?country.us)
* [CN](https://vuldb.com/?country.cn)
* [CL](https://vuldb.com/?country.cl)
* ...

There are 23 more country items available. Please use our online service to access the data.

## IOC - Indicator of Compromise

These _indicators of compromise_ (IOC) indicate associated network resources which are known to be part of research and attack activities of Agent Tesla.

ID | IP address | Hostname | Campaign | Confidence
-- | ---------- | -------- | -------- | ----------
1 | [3.93.18.244](https://vuldb.com/?ip.3.93.18.244) | ec2-3-93-18-244.compute-1.amazonaws.com | - | Medium
2 | [3.217.248.28](https://vuldb.com/?ip.3.217.248.28) | ec2-3-217-248-28.compute-1.amazonaws.com | - | Medium
3 | [23.95.85.181](https://vuldb.com/?ip.23.95.85.181) | 23-95-85-181-host.colocrossing.com | - | High
4 | [31.3.251.197](https://vuldb.com/?ip.31.3.251.197) | h31-3-251-197.host.redstation.co.uk | - | High
5 | [31.209.137.12](https://vuldb.com/?ip.31.209.137.12) | smtp.vivaldi.net | - | High
6 | [34.200.207.31](https://vuldb.com/?ip.34.200.207.31) | ec2-34-200-207-31.compute-1.amazonaws.com | - | Medium
7 | [37.19.196.108](https://vuldb.com/?ip.37.19.196.108) | unn-37-19-196-108.datapacket.com | - | High
8 | [45.142.215.180](https://vuldb.com/?ip.45.142.215.180) | connectoms.host | - | High
9 | [45.156.25.78](https://vuldb.com/?ip.45.156.25.78) | - | - | High
10 | [50.17.5.224](https://vuldb.com/?ip.50.17.5.224) | ec2-50-17-5-224.compute-1.amazonaws.com | - | Medium
11 | [51.68.128.171](https://vuldb.com/?ip.51.68.128.171) | ip171.ip-51-68-128.eu | - | High
12 | [51.89.183.99](https://vuldb.com/?ip.51.89.183.99) | 90.eri1.ovh.abcd.network | - | High
13 | [62.182.156.179](https://vuldb.com/?ip.62.182.156.179) | - | - | High
14 | ... | ... | ... | ...

There are 52 more IOC items available. Please use our online service to access the data.

## TTP - Tactics, Techniques, Procedures

_Tactics, techniques, and procedures_ (TTP) summarize the suspected MITRE ATT&CK techniques used by _Agent Tesla_. This data is unique as it uses our predictive model for actor profiling.

ID | Technique | Weakness | Description | Confidence
-- | --------- | -------- | ----------- | ----------
1 | T1006 | CWE-21, CWE-22 | Pathname Traversal | High
2 | T1040 | CWE-294, CWE-319 | Authentication Bypass by Capture-replay | High
3 | T1055 | CWE-74 | Injection | High
4 | T1059 | CWE-88, CWE-94, CWE-1321 | Cross Site Scripting | High
5 | T1059.007 | CWE-79, CWE-80 | Cross Site Scripting | High
6 | ... | ... | ... | ...

There are 18 more TTP items available. Please use our online service to access the data.

## IOA - Indicator of Attack

These _indicators of attack_ (IOA) list the potential fragments used for technical activities like reconnaissance, exploitation, privilege escalation, and exfiltration by Agent Tesla. This data is unique as it uses our predictive model for actor profiling.

ID | Type | Indicator | Confidence
-- | ---- | --------- | ----------
1 | File | `/+CSCOE+/logon.html` | High
2 | File | `/admin/ajax.php?action=save_window` | High
3 | File | `/api/addusers` | High
4 | File | `/app/options.py` | High
5 | File | `/cgi-bin/wapopen` | High
6 | File | `/controller/Index.php` | High
7 | File | `/dashboard/add-portfolio.php` | High
8 | File | `/etc/ajenti/config.yml` | High
9 | File | `/etc/gsissh/sshd_config` | High
10 | File | `/etc/sudoers` | Medium
11 | File | `/forum/away.php` | High
12 | File | `/goform/telnet` | High
13 | File | `/include/chart_generator.php` | High
14 | File | `/lilac/main.php` | High
15 | File | `/manager?action=getlogcat` | High
16 | File | `/mc` | Low
17 | File | `/mims/login.php` | High
18 | File | `/module/admin_bp/add_application.php` | High
19 | File | `/module/report_event/index.php` | High
20 | File | `/modules/profile/index.php` | High
21 | File | `/out.php` | Medium
22 | File | `/proc/sys/vm/cmm_timeout` | High
23 | File | `/public/launchNewWindow.jsp` | High
24 | File | `/public/login.htm` | High
25 | File | `/RestAPI` | Medium
26 | File | `/rom-0` | Low
27 | File | `/server-status` | High
28 | File | `/spip.php` | Medium
29 | File | `/Status/wan_button_action.asp` | High
30 | File | `/tmp/connlicj.bin` | High
31 | File | `/uncpath/` | Medium
32 | File | `/usr/local/nagiosxi/html/includes/configwizards/windowswmi/windowswmi.inc.php` | High
33 | File | `/var/log/nginx` | High
34 | File | `/var/tmp/sess_*` | High
35 | File | `/wp-admin/options.php` | High
36 | File | `/youthappam/add-food.php` | High
37 | File | `/youthappam/editclient.php` | High
38 | File | `4.2.0.CP09` | Medium
39 | File | `actionphp/download.File.php` | High
40 | File | `add_comment.php` | High
41 | File | `admin.a6mambocredits.php` | High
42 | File | `admin.php` | Medium
43 | File | `admin.php3` | Medium
44 | File | `admin.php?m=backup&c=backup&a=doback` | High
45 | File | `admin/admin.php` | High
46 | File | `admin/content.php` | High
47 | File | `admin/import/class-import-settings.php` | High
48 | File | `admin/index.php?id=users/action=edit/user_id=1` | High
49 | File | `admin/sitesettings.php` | High
50 | ... | ... | ...

There are 430 more IOA items available (file, library, argument, input value, pattern, network port). Please use our online service to access the data.

## References

The following list contains _external sources_ which discuss the actor and the associated activities:

* https://1275.ru/ioc/254/gs-002-agent-tesla-spyware-iocs/
* https://1275.ru/ioc/310/gs-032-agent-tesla-spyware-iocs/
* https://asec.ahnlab.com/en/31083/
* https://blog.talosintelligence.com/2020/07/threat-roundup-0724-0731.html
* https://blog.talosintelligence.com/2022/09/threat-roundup-0826-0902.html
* https://blogs.blackberry.com/en/2020/04/threat-spotlight-secret-agent-tesla
* https://community.blueliv.com/#!/s/5f7de53d82df413eb5350fba
* https://github.com/executemalware/Malware-IOCs/blob/main/2021-08-20%20Agent%20Tesla%20IOCs
* https://github.com/executemalware/Malware-IOCs/blob/main/2021-08-24%20Agent%20Tesla%20IOCs
* https://github.com/executemalware/Malware-IOCs/blob/main/2021-08-27%20Agent%20Tesla%20IOCs
* https://github.com/executemalware/Malware-IOCs/blob/main/2021-09-07%20Agent%20Tesla%20IOCs
* https://github.com/executemalware/Malware-IOCs/blob/main/2021-09-17%20Agent%20Tesla%20IOCs
* https://github.com/executemalware/Malware-IOCs/blob/main/2021-09-20%20Agent%20Tesla%20IOCs
* https://github.com/executemalware/Malware-IOCs/blob/main/2021-10-14%20Agent%20Tesla%20IOCs
* https://github.com/executemalware/Malware-IOCs/blob/main/2022-04-22%20AgentTesla%20IOCs
* https://github.com/executemalware/Malware-IOCs/blob/main/2022-04-22%20AgentTesla%20IOCs%20Rd2
* https://github.com/executemalware/Malware-IOCs/blob/main/2022-05-20%20Agent%20Tesla%20IOCs
* https://github.com/netskopeoss/NetskopeThreatLabsIOCs/tree/main/AgentTesla/IOCs
* https://services.global.ntt/en-us/insights/blog/discovering-a-new-agent-tesla-malware-sample
* https://threatfox.abuse.ch
* https://tracker.viriback.com/index.php?q=95.214.27.98
* https://tracker.viriback.com/index.php?q=185.225.74.69
* https://tracker.viriback.com/index.php?q=185.246.220.133
* https://tracker.viriback.com/index.php?q=198.98.55.114
* https://tracker.viriback.com/index.php?q=209.141.53.247
* https://tria.ge/210823-fk5y59ln7a
* https://tria.ge/211109-bxk6qsbdfn
* https://tria.ge/221206-z6p32sgh4s
* https://twitter.com/Tac_Mangusta/status/1659190159789916160
* https://www.fortinet.com/blog/threat-research/phishing-campaign-targeting-korean-to-deliver-agent-tesla-new-variant
* https://www.zscaler.com/blogs/security-research/agent-tesla-rat-delivered-quantum-builder-new-ttps

## Literature

The following _articles_ explain our unique predictive cyber threat intelligence:

* [VulDB Cyber Threat Intelligence Documentation](https://vuldb.com/?kb.cti)
* [Cyber Threat Intelligence - Early Anticipation of Attacks](https://www.scip.ch/en/?labs.20201022)

## License

(c) [1997-2023](https://vuldb.com/?kb.changelog) by [vuldb.com](https://vuldb.com/?kb.about). All data on this page is shared under the license [CC BY-NC-SA 4.0](https://creativecommons.org/licenses/by-nc-sa/4.0/). Questions? Check the [FAQ](https://vuldb.com/?kb.faq), read the [documentation](https://vuldb.com/?kb) or [contact us](https://vuldb.com/?contact)!
