# NetWire - Cyber Threat Intelligence

These _indicators_ were reported, collected, and generated during the [VulDB CTI analysis](https://vuldb.com/?kb.cti) of the actor known as [NetWire](https://vuldb.com/?actor.netwire). The _activity monitoring_ correlates data from social media, forums, chat rooms, and darknet markets. It helps to determine associated actors, specific activities, expected intentions, emerging research, and ongoing attacks. Our unique _predictive model_ uses _big data_ to forecast activities and their characteristics.

_Live data_ and more _analysis capabilities_ are available at [https://vuldb.com/?actor.netwire](https://vuldb.com/?actor.netwire)

## Campaigns

The following _campaigns_ are known and can be associated with NetWire:

* Phishing

## Countries

These _countries_ are directly (e.g. origin of attacks) or indirectly (e.g. access by proxy) associated with NetWire:

* [US](https://vuldb.com/?country.us)
* [RU](https://vuldb.com/?country.ru)
* [GB](https://vuldb.com/?country.gb)
* ...

There are 28 more country items available. Please use our online service to access the data.

## IOC - Indicator of Compromise

These _indicators of compromise_ (IOC) indicate associated network resources which are known to be part of research and attack activities of NetWire.

ID | IP address | Hostname | Campaign | Confidence
-- | ---------- | -------- | -------- | ----------
1 | [3.129.252.224](https://vuldb.com/?ip.3.129.252.224) | ec2-3-129-252-224.us-east-2.compute.amazonaws.com | - | Medium
2 | [3.134.22.63](https://vuldb.com/?ip.3.134.22.63) | ec2-3-134-22-63.us-east-2.compute.amazonaws.com | - | Medium
3 | [5.56.133.55](https://vuldb.com/?ip.5.56.133.55) | 5-56-133-55.static.karizanta.com | - | High
4 | [5.56.133.98](https://vuldb.com/?ip.5.56.133.98) | 5-56-133-98.static.karizanta.com | - | High
5 | [5.254.112.53](https://vuldb.com/?ip.5.254.112.53) | - | - | High
6 | [23.20.239.12](https://vuldb.com/?ip.23.20.239.12) | ec2-23-20-239-12.compute-1.amazonaws.com | - | Medium
7 | [23.227.38.64](https://vuldb.com/?ip.23.227.38.64) | shops.myshopify.com | - | High
8 | [23.227.199.214](https://vuldb.com/?ip.23.227.199.214) | 23-227-199-214.static.hvvc.us | - | High
9 | [23.254.202.192](https://vuldb.com/?ip.23.254.202.192) | hwsrv-738718.hostwindsdns.com | - | High
10 | [37.0.11.206](https://vuldb.com/?ip.37.0.11.206) | - | - | High
11 | [37.46.114.246](https://vuldb.com/?ip.37.46.114.246) | yjnimw.yyngy4.reversedigital.radio.am | - | High
12 | [37.46.150.139](https://vuldb.com/?ip.37.46.150.139) | - | - | High
13 | [37.48.80.173](https://vuldb.com/?ip.37.48.80.173) | - | - | High
14 | [37.139.64.106](https://vuldb.com/?ip.37.139.64.106) | - | - | High
15 | [39.108.116.125](https://vuldb.com/?ip.39.108.116.125) | - | - | High
16 | [45.144.225.219](https://vuldb.com/?ip.45.144.225.219) | - | - | High
17 | [46.244.18.141](https://vuldb.com/?ip.46.244.18.141) | 141-18-244-46.a2b-internet.com | - | High
18 | [46.246.126.193](https://vuldb.com/?ip.46.246.126.193) | 193-126-246-46.static.edis.at | - | High
19 | [52.40.240.30](https://vuldb.com/?ip.52.40.240.30) | ec2-52-40-240-30.us-west-2.compute.amazonaws.com | - | Medium
20 | [66.154.113.239](https://vuldb.com/?ip.66.154.113.239) | 66.154.113.239.static.quadranet.com | - | High
21 | [67.214.175.69](https://vuldb.com/?ip.67.214.175.69) | box6.dnsexit.com | - | High
22 | ... | ... | ... | ...

There are 84 more IOC items available. Please use our online service to access the data.

## TTP - Tactics, Techniques, Procedures

_Tactics, techniques, and procedures_ (TTP) summarize the suspected MITRE ATT&CK techniques used by _NetWire_. This data is unique as it uses our predictive model for actor profiling.

ID | Technique | Weakness | Description | Confidence
-- | --------- | -------- | ----------- | ----------
1 | T1059.007 | CWE-79, CWE-80 | Cross Site Scripting | High
2 | T1068 | CWE-264, CWE-284 | Execution with Unnecessary Privileges | High
3 | T1110.001 | CWE-798 | Improper Restriction of Excessive Authentication Attempts | High
4 | ... | ... | ... | ...

There are 8 more TTP items available. Please use our online service to access the data.

## IOA - Indicator of Attack

These _indicators of attack_ (IOA) list the potential fragments used for technical activities like reconnaissance, exploitation, privilege escalation, and exfiltration by NetWire. This data is unique as it uses our predictive model for actor profiling.

ID | Type | Indicator | Confidence
-- | ---- | --------- | ----------
1 | File | `%PROGRAMDATA%\Razer\Synapse3\Service\bin` | High
2 | File | `/../../conf/template/uhttpd.json` | High
3 | File | `/admin/contenttemp` | High
4 | File | `/admin/modules/system/custom_field.php` | High
5 | File | `/api/crontab` | Medium
6 | File | `/bin/boa` | Medium
7 | File | `/cgi-bin/qcmap_auth` | High
8 | File | `/cgi-bin/wapopen` | High
9 | File | `/cgi-mod/lookup.cgi` | High
10 | File | `/dev/dri/card1` | High
11 | File | `/etc/sudoers` | Medium
12 | File | `/export` | Low
13 | File | `/forum/away.php` | High
14 | File | `/getcfg.php` | Medium
15 | File | `/iissamples` | Medium
16 | File | `/index.php` | Medium
17 | File | `/index.php?controller=calendar&format=raw&cat[0]=SQLi&task=events` | High
18 | File | `/j_security_check` | High
19 | File | `/login` | Low
20 | File | `/osm/REGISTER.cmd` | High
21 | File | `/public/plugins/` | High
22 | File | `/rom-0` | Low
23 | File | `/servlet/webacc` | High
24 | File | `/uncpath/` | Medium
25 | File | `/usr/bin/pkexec` | High
26 | File | `/usr/sbin/suexec` | High
27 | File | `/webconsole/Controller` | High
28 | File | `/webman/info.cgi` | High
29 | File | `/wp-admin/admin-ajax.php` | High
30 | File | `14all.cgi/14all-1.1.cgi/traffic.cgi/mrtg.cgi` | High
31 | File | `AAclAuthz.java` | High
32 | File | `ABuffer.cpp` | Medium
33 | File | `adclick.php` | Medium
34 | File | `admin.php` | Medium
35 | File | `admin.php?page=languages` | High
36 | File | `admin/conf_users_edit.php` | High
37 | File | `admin/dashboard.php` | High
38 | File | `admin\db\DoSql.php` | High
39 | ... | ... | ...

There are 337 more IOA items available (file, library, argument, input value, pattern, network port). Please use our online service to access the data.

## References

The following list contains _external sources_ which discuss the actor and the associated activities:

* https://blog.bushidotoken.net/2021/01/analysis-of-netwire-rat-campaign.html
* https://blog.talosintelligence.com/2019/03/threat-roundup-0315-0322.html
* https://blog.talosintelligence.com/2019/12/threat-roundup-1213-1220.html
* https://blog.talosintelligence.com/2020/02/threat-roundup-0221-0228.html
* https://blog.talosintelligence.com/2020/05/threat-roundup-0508-0515.html
* https://blog.talosintelligence.com/2020/06/threat-roundup-0619-0626.html
* https://blog.talosintelligence.com/2020/08/tru-0731-0807.html
* https://blog.talosintelligence.com/2020/10/threat-roundup-1023-1030.html
* https://blog.talosintelligence.com/2020/11/threat-roundup-1113-1120.html
* https://blog.talosintelligence.com/2021/04/threat-roundup-0416-0423.html
* https://blog.talosintelligence.com/2021/04/threat-roundup-0423-0430.html
* https://blog.talosintelligence.com/2021/07/threat-roundup-0625-0702.html
* https://blog.talosintelligence.com/2021/07/threat-roundup-0723-0730.html
* https://blog.talosintelligence.com/2021/08/threat-roundup-0813-0820.html
* https://blog.talosintelligence.com/2021/09/threat-roundup-0910-0917.html
* https://blog.talosintelligence.com/2021/09/threat-roundup-0917-0924.html
* https://blog.talosintelligence.com/2021/10/threat-roundup-1022-1029.html
* https://unit42.paloaltonetworks.jp/guloader-installing-netwire-rat/
* https://www.mandiant.com/resources/dissecting-netwire-phishing-campaigns-usage-process-hollowing

## Literature

The following _articles_ explain our unique predictive cyber threat intelligence:

* [VulDB Cyber Threat Intelligence Documentation](https://vuldb.com/?kb.cti)
* [Cyber Threat Intelligence - Early Anticipation of Attacks](https://www.scip.ch/en/?labs.20201022)

## License

(c) [1997-2022](https://vuldb.com/?kb.changelog) by [vuldb.com](https://vuldb.com/?kb.about). All data on this page is shared under the license [CC BY-NC-SA 4.0](https://creativecommons.org/licenses/by-nc-sa/4.0/). Questions? Check the [FAQ](https://vuldb.com/?kb.faq), read the [documentation](https://vuldb.com/?kb) or [contact us](https://vuldb.com/?contact)!
