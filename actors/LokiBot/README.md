# LokiBot - Cyber Threat Intelligence

These _indicators_ were reported, collected, and generated during the [VulDB CTI analysis](https://vuldb.com/?kb.cti) of the actor known as [LokiBot](https://vuldb.com/?actor.lokibot). The _activity monitoring_ correlates data from social media, forums, chat rooms, and darknet markets. It helps to determine associated actors, specific activities, expected intentions, emerging research, and ongoing attacks. Our unique _predictive model_ uses _big data_ to forecast activities and their characteristics.

_Live data_ and more _analysis capabilities_ are available at [https://vuldb.com/?actor.lokibot](https://vuldb.com/?actor.lokibot)

## Countries

These _countries_ are directly (e.g. origin of attacks) or indirectly (e.g. access by proxy) associated with LokiBot:

* [US](https://vuldb.com/?country.us)
* [VN](https://vuldb.com/?country.vn)
* [CN](https://vuldb.com/?country.cn)
* ...

There are 10 more country items available. Please use our online service to access the data.

## IOC - Indicator of Compromise

These _indicators of compromise_ (IOC) indicate associated network resources which are known to be part of research and attack activities of LokiBot.

ID | IP address | Hostname | Campaign | Confidence
-- | ---------- | -------- | -------- | ----------
1 | [2.57.186.170](https://vuldb.com/?ip.2.57.186.170) | - | - | High
2 | [13.107.21.200](https://vuldb.com/?ip.13.107.21.200) | - | - | High
3 | [15.197.142.173](https://vuldb.com/?ip.15.197.142.173) | a4ec4c6ea1c92e2e6.awsglobalaccelerator.com | - | High
4 | [20.189.173.20](https://vuldb.com/?ip.20.189.173.20) | - | - | High
5 | [23.21.173.155](https://vuldb.com/?ip.23.21.173.155) | ec2-23-21-173-155.compute-1.amazonaws.com | - | Medium
6 | [23.21.211.162](https://vuldb.com/?ip.23.21.211.162) | ec2-23-21-211-162.compute-1.amazonaws.com | - | Medium
7 | [23.95.132.48](https://vuldb.com/?ip.23.95.132.48) | 23-95-132-48-host.colocrossing.com | - | High
8 | [23.205.105.153](https://vuldb.com/?ip.23.205.105.153) | a23-205-105-153.deploy.static.akamaitechnologies.com | - | High
9 | [23.205.105.157](https://vuldb.com/?ip.23.205.105.157) | a23-205-105-157.deploy.static.akamaitechnologies.com | - | High
10 | [23.222.5.37](https://vuldb.com/?ip.23.222.5.37) | a23-222-5-37.deploy.static.akamaitechnologies.com | - | High
11 | [31.41.46.120](https://vuldb.com/?ip.31.41.46.120) | maldova873.example.com | - | High
12 | [31.220.52.219](https://vuldb.com/?ip.31.220.52.219) | workshop.piguno.com | - | High
13 | [34.102.136.180](https://vuldb.com/?ip.34.102.136.180) | 180.136.102.34.bc.googleusercontent.com | - | Medium
14 | [35.247.234.230](https://vuldb.com/?ip.35.247.234.230) | 230.234.247.35.bc.googleusercontent.com | - | Medium
15 | [37.235.1.174](https://vuldb.com/?ip.37.235.1.174) | resolver1.freedns.zone.powered.by.virtexxa.com | - | High
16 | [37.235.1.177](https://vuldb.com/?ip.37.235.1.177) | resolver2.freedns.zone.powered.by.virtexxa.com | - | High
17 | [45.33.83.75](https://vuldb.com/?ip.45.33.83.75) | li1029-75.members.linode.com | - | High
18 | [45.128.184.132](https://vuldb.com/?ip.45.128.184.132) | vds107519.mgn-host.ru | - | High
19 | [45.147.229.85](https://vuldb.com/?ip.45.147.229.85) | - | - | High
20 | [45.154.253.150](https://vuldb.com/?ip.45.154.253.150) | shared04.cust05.proxy.is | - | High
21 | [45.154.253.152](https://vuldb.com/?ip.45.154.253.152) | shared06.cust05.proxy.is | - | High
22 | [50.16.216.118](https://vuldb.com/?ip.50.16.216.118) | ec2-50-16-216-118.compute-1.amazonaws.com | - | Medium
23 | [50.19.92.227](https://vuldb.com/?ip.50.19.92.227) | ec2-50-19-92-227.compute-1.amazonaws.com | - | Medium
24 | ... | ... | ... | ...

There are 91 more IOC items available. Please use our online service to access the data.

## TTP - Tactics, Techniques, Procedures

_Tactics, techniques, and procedures_ (TTP) summarize the suspected MITRE ATT&CK techniques used by _LokiBot_. This data is unique as it uses our predictive model for actor profiling.

ID | Technique | Weakness | Description | Confidence
-- | --------- | -------- | ----------- | ----------
1 | T1059.007 | CWE-79, CWE-80 | Cross Site Scripting | High
2 | T1068 | CWE-264, CWE-266, CWE-284 | Execution with Unnecessary Privileges | High
3 | T1110.001 | CWE-307, CWE-798 | Improper Restriction of Excessive Authentication Attempts | High
4 | ... | ... | ... | ...

There are 5 more TTP items available. Please use our online service to access the data.

## IOA - Indicator of Attack

These _indicators of attack_ (IOA) list the potential fragments used for technical activities like reconnaissance, exploitation, privilege escalation, and exfiltration by LokiBot. This data is unique as it uses our predictive model for actor profiling.

ID | Type | Indicator | Confidence
-- | ---- | --------- | ----------
1 | File | `/.env` | Low
2 | File | `/.ssh/authorized_keys` | High
3 | File | `/car.php` | Medium
4 | File | `/CMD_ACCOUNT_ADMIN` | High
5 | File | `/config/getuser` | High
6 | File | `/context/%2e/WEB-INF/web.xml` | High
7 | File | `/core/admin/categories.php` | High
8 | File | `/dashboards/#` | High
9 | File | `/etc/controller-agent/agent.conf` | High
10 | File | `/etc/postfix/sender_login` | High
11 | File | `/etc/sudoers` | Medium
12 | File | `/etc/tomcat8/Catalina/attack` | High
13 | File | `/filemanager/php/connector.php` | High
14 | File | `/forum/away.php` | High
15 | File | `/fudforum/adm/hlplist.php` | High
16 | File | `/GponForm/fsetup_Form` | High
17 | File | `/log_download.cgi` | High
18 | File | `/modules/profile/index.php` | High
19 | File | `/MTFWU` | Low
20 | File | `/out.php` | Medium
21 | File | `/public/plugins/` | High
22 | File | `/s/` | Low
23 | File | `/secure/QueryComponent!Default.jspa` | High
24 | File | `/server-info` | Medium
25 | File | `/tmp` | Low
26 | File | `/tmp/app/.env` | High
27 | File | `/tmp/kamailio_ctl` | High
28 | File | `/tmp/kamailio_fifo` | High
29 | File | `/uncpath/` | Medium
30 | File | `/updown/upload.cgi` | High
31 | File | `/usr/bin/at` | Medium
32 | File | `/usr/bin/pkexec` | High
33 | ... | ... | ...

There are 282 more IOA items available (file, library, argument, input value, pattern, network port). Please use our online service to access the data.

## References

The following list contains _external sources_ which discuss the actor and the associated activities:

* https://blog.talosintelligence.com/2021/04/threat-roundup-0423-0430.html
* https://blog.talosintelligence.com/2021/06/threat-roundup-0604-0611.html
* https://blog.talosintelligence.com/2021/07/threat-roundup-0716-0723.html
* https://blog.talosintelligence.com/2021/08/threat-roundup-0820-0827.html
* https://blog.talosintelligence.com/2021/09/threat-roundup-0827-0903.html
* https://blog.talosintelligence.com/2021/09/threat-roundup-0910-0917.html
* https://blog.talosintelligence.com/2021/10/threat-roundup-1001-1008.html
* https://blog.talosintelligence.com/2021/11/threat-roundup-1029-1105.html
* https://blog.talosintelligence.com/2021/11/threat-roundup-1112-1119.html
* https://blog.talosintelligence.com/2022/01/threat-roundup-0121-0128.html
* https://blog.talosintelligence.com/2022/02/threat-roundup-0204-0211.html
* https://blog.talosintelligence.com/2022/03/threat-roundup-0304-0311.html
* https://vxug.fakedoma.in/archive/APTs/2021/2021.01.06(1)/LokiBot%20Infection%20Chain.pdf

## Literature

The following _articles_ explain our unique predictive cyber threat intelligence:

* [VulDB Cyber Threat Intelligence Documentation](https://vuldb.com/?kb.cti)
* [Cyber Threat Intelligence - Early Anticipation of Attacks](https://www.scip.ch/en/?labs.20201022)

## License

(c) [1997-2022](https://vuldb.com/?kb.changelog) by [vuldb.com](https://vuldb.com/?kb.about). All data on this page is shared under the license [CC BY-NC-SA 4.0](https://creativecommons.org/licenses/by-nc-sa/4.0/). Questions? Check the [FAQ](https://vuldb.com/?kb.faq), read the [documentation](https://vuldb.com/?kb) or [contact us](https://vuldb.com/?contact)!
