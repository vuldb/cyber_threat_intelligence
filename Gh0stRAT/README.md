# Gh0stRAT - Cyber Threat Intelligence

These _indicators_ were reported, collected, and generated during the [VulDB CTI analysis](https://vuldb.com/?kb.cti) of the actor known as [Gh0stRAT](https://vuldb.com/?actor.gh0strat). The _activity monitoring_ correlates data from social media, forums, chat rooms, and darknet markets. It helps to determine associated actors, specific activities, expected intentions, emerging research, and ongoing attacks. Our unique _predictive model_ uses _big data_ to forecast activities and their characteristics.

_Live data_ and more _analysis capabilities_ are available at [https://vuldb.com/?actor.gh0strat](https://vuldb.com/?actor.gh0strat)

## Countries

These _countries_ are directly (e.g. origin of attacks) or indirectly (e.g. access by proxy) associated with Gh0stRAT:

* [US](https://vuldb.com/?country.us)
* [VN](https://vuldb.com/?country.vn)
* [CN](https://vuldb.com/?country.cn)
* ...

There are 16 more country items available. Please use our online service to access the data.

## IOC - Indicator of Compromise

These _indicators of compromise_ (IOC) indicate associated network resources which are known to be part of research and attack activities of Gh0stRAT.

ID | IP address | Hostname | Campaign | Confidence
-- | ---------- | -------- | -------- | ----------
1 | [13.249.38.69](https://vuldb.com/?ip.13.249.38.69) | server-13-249-38-69.iad89.r.cloudfront.net | - | High
2 | [20.42.65.92](https://vuldb.com/?ip.20.42.65.92) | - | - | High
3 | [20.189.173.22](https://vuldb.com/?ip.20.189.173.22) | - | - | High
4 | [36.43.74.215](https://vuldb.com/?ip.36.43.74.215) | - | - | High
5 | [36.46.114.54](https://vuldb.com/?ip.36.46.114.54) | - | - | High
6 | [39.109.1.246](https://vuldb.com/?ip.39.109.1.246) | - | - | High
7 | [42.51.192.3](https://vuldb.com/?ip.42.51.192.3) | - | - | High
8 | [43.226.152.12](https://vuldb.com/?ip.43.226.152.12) | - | - | High
9 | [43.226.159.201](https://vuldb.com/?ip.43.226.159.201) | - | - | High
10 | [45.119.125.223](https://vuldb.com/?ip.45.119.125.223) | - | - | High
11 | [45.195.203.97](https://vuldb.com/?ip.45.195.203.97) | - | - | High
12 | [45.253.67.78](https://vuldb.com/?ip.45.253.67.78) | - | - | High
13 | [47.93.52.188](https://vuldb.com/?ip.47.93.52.188) | - | - | High
14 | [47.93.245.163](https://vuldb.com/?ip.47.93.245.163) | - | - | High
15 | [47.95.233.18](https://vuldb.com/?ip.47.95.233.18) | - | - | High
16 | [47.111.82.157](https://vuldb.com/?ip.47.111.82.157) | - | - | High
17 | [47.112.30.91](https://vuldb.com/?ip.47.112.30.91) | - | - | High
18 | [52.168.117.173](https://vuldb.com/?ip.52.168.117.173) | - | - | High
19 | [52.182.143.212](https://vuldb.com/?ip.52.182.143.212) | - | - | High
20 | [58.218.66.21](https://vuldb.com/?ip.58.218.66.21) | - | - | High
21 | [58.218.67.245](https://vuldb.com/?ip.58.218.67.245) | - | - | High
22 | [58.218.199.225](https://vuldb.com/?ip.58.218.199.225) | - | - | High
23 | [58.221.47.41](https://vuldb.com/?ip.58.221.47.41) | - | - | High
24 | [58.221.47.47](https://vuldb.com/?ip.58.221.47.47) | - | - | High
25 | ... | ... | ... | ...

There are 94 more IOC items available. Please use our online service to access the data.

## TTP - Tactics, Techniques, Procedures

_Tactics, techniques, and procedures_ (TTP) summarize the suspected ATT&CK techniques used by Gh0stRAT. This data is unique as it uses our predictive model for actor profiling.

ID | Technique | Weakness | Description | Confidence
-- | --------- | -------- | ----------- | ----------
1 | T1059.007 | CWE-79, CWE-80 | Cross Site Scripting | High
2 | T1068 | CWE-250, CWE-264, CWE-266, CWE-284 | Execution with Unnecessary Privileges | High
3 | T1110.001 | CWE-307, CWE-798 | Improper Restriction of Excessive Authentication Attempts | High
4 | ... | ... | ... | ...

There are 7 more TTP items available. Please use our online service to access the data.

## IOA - Indicator of Attack

These _indicators of attack_ (IOA) list the potential fragments used for technical activities like reconnaissance, exploitation, privilege escalation, and exfiltration by Gh0stRAT. This data is unique as it uses our predictive model for actor profiling.

ID | Type | Indicator | Confidence
-- | ---- | --------- | ----------
1 | File | `/+CSCOE+/logon.html` | High
2 | File | `/.env` | Low
3 | File | `/.ssh/authorized_keys` | High
4 | File | `/admin.php?&m=Public&a=login` | High
5 | File | `/ajax/networking/get_netcfg.php` | High
6 | File | `/car.php` | Medium
7 | File | `/CMD_ACCOUNT_ADMIN` | High
8 | File | `/concat?/%2557EB-INF/web.xml` | High
9 | File | `/config/getuser` | High
10 | File | `/core/admin/categories.php` | High
11 | File | `/dashboards/#` | High
12 | File | `/data/remove` | Medium
13 | File | `/etc/controller-agent/agent.conf` | High
14 | File | `/etc/postfix/sender_login` | High
15 | File | `/etc/sudoers` | Medium
16 | File | `/etc/tomcat8/Catalina/attack` | High
17 | File | `/filemanager/php/connector.php` | High
18 | File | `/forum/away.php` | High
19 | File | `/fudforum/adm/hlplist.php` | High
20 | File | `/GponForm/fsetup_Form` | High
21 | File | `/log_download.cgi` | High
22 | File | `/modules/profile/index.php` | High
23 | File | `/navigate/navigate_download.php` | High
24 | File | `/out.php` | Medium
25 | File | `/password.html` | High
26 | File | `/property-list/property_view.php` | High
27 | File | `/public/plugins/` | High
28 | File | `/rest/api/2/search` | High
29 | File | `/s/` | Low
30 | File | `/scripts/cpan_config` | High
31 | File | `/secure/admin/InsightDefaultCustomFieldConfig.jspa` | High
32 | File | `/secure/QueryComponent!Default.jspa` | High
33 | File | `/server-info` | Medium
34 | File | `/tmp` | Low
35 | File | `/tmp/app/.env` | High
36 | File | `/tmp/kamailio_ctl` | High
37 | ... | ... | ...

There are 322 more IOA items available (file, library, argument, input value, pattern, network port). Please use our online service to access the data.

## References

The following list contains _external sources_ which discuss the actor and the associated activities:

* https://blog.talosintelligence.com/2021/01/threat-roundup-0122.html
* https://blog.talosintelligence.com/2021/02/threat-roundup-0205-0212.html
* https://blog.talosintelligence.com/2021/02/threat-roundup-0212-0219.html
* https://blog.talosintelligence.com/2021/03/threat-roundup-0305-0312.html
* https://blog.talosintelligence.com/2021/04/threat-roundup-0326-0402.html
* https://blog.talosintelligence.com/2021/06/threat-roundup-0611-0617.html
* https://blog.talosintelligence.com/2021/07/threat-roundup-0716-0723.html
* https://blog.talosintelligence.com/2021/08/threat-roundup-0730-0806.html
* https://blog.talosintelligence.com/2021/09/threat-roundup-0910-0917.html
* https://blog.talosintelligence.com/2021/09/threat-roundup-0917-0924.html
* https://blog.talosintelligence.com/2021/10/threat-roundup-0924-1001.html
* https://blog.talosintelligence.com/2021/10/threat-roundup-1001-1008.html
* https://blog.talosintelligence.com/2022/01/threat-roundup-0107-0114.html
* https://blog.talosintelligence.com/2022/01/threat-roundup-0121-0128.html
* https://blog.talosintelligence.com/2022/01/threat-roundup-1231-0107.html
* https://blog.talosintelligence.com/2022/02/threat-roundup-0128-0204.html
* https://blog.talosintelligence.com/2022/02/threat-roundup-0204-0211.html
* https://blog.talosintelligence.com/2022/02/threat-roundup-0218-0225.html

## Literature

The following _articles_ explain our unique predictive cyber threat intelligence:

* [VulDB Cyber Threat Intelligence Documentation](https://vuldb.com/?kb.cti)
* [Cyber Threat Intelligence - Early Anticipation of Attacks](https://www.scip.ch/en/?labs.20201022)

## License

(c) [1997-2022](https://vuldb.com/?kb.changelog) by [vuldb.com](https://vuldb.com/?kb.about). All data on this page is shared under the license [CC BY-NC-SA 4.0](https://creativecommons.org/licenses/by-nc-sa/4.0/). Questions? Check the [FAQ](https://vuldb.com/?kb.faq), read the [documentation](https://vuldb.com/?kb) or [contact us](https://vuldb.com/?contact)!
