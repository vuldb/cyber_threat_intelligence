# CoinMiner - Cyber Threat Intelligence

These _indicators_ were reported, collected, and generated during the [VulDB CTI analysis](https://vuldb.com/?kb.cti) of the actor known as [CoinMiner](https://vuldb.com/?actor.coinminer). The _activity monitoring_ correlates data from social media, forums, chat rooms, and darknet markets. It helps to determine associated actors, specific activities, expected intentions, emerging research, and ongoing attacks. Our unique _predictive model_ uses _big data_ to forecast activities and their characteristics.

_Live data_ and more _analysis capabilities_ are available at [https://vuldb.com/?actor.coinminer](https://vuldb.com/?actor.coinminer)

## Countries

These _countries_ are directly (e.g. origin of attacks) or indirectly (e.g. access by proxy) associated with CoinMiner:

* [US](https://vuldb.com/?country.us)
* [CN](https://vuldb.com/?country.cn)

## IOC - Indicator of Compromise

These _indicators of compromise_ (IOC) indicate associated network resources which are known to be part of research and attack activities of CoinMiner.

ID | IP address | Hostname | Campaign | Confidence
-- | ---------- | -------- | -------- | ----------
1 | [2.58.149.237](https://vuldb.com/?ip.2.58.149.237) | - | - | High
2 | [4.4.0.0](https://vuldb.com/?ip.4.4.0.0) | - | - | High
3 | [5.9.157.2](https://vuldb.com/?ip.5.9.157.2) | static.2.157.9.5.clients.your-server.de | - | High
4 | [5.196.13.29](https://vuldb.com/?ip.5.196.13.29) | 29.ip-5-196-13.eu | - | High
5 | [5.196.23.240](https://vuldb.com/?ip.5.196.23.240) | 240.ip-5-196-23.eu | - | High
6 | [13.107.21.200](https://vuldb.com/?ip.13.107.21.200) | - | - | High
7 | [18.210.126.40](https://vuldb.com/?ip.18.210.126.40) | ec2-18-210-126-40.compute-1.amazonaws.com | - | Medium
8 | [23.21.48.44](https://vuldb.com/?ip.23.21.48.44) | ec2-23-21-48-44.compute-1.amazonaws.com | - | Medium
9 | [23.21.76.253](https://vuldb.com/?ip.23.21.76.253) | ec2-23-21-76-253.compute-1.amazonaws.com | - | Medium
10 | [23.21.126.66](https://vuldb.com/?ip.23.21.126.66) | ec2-23-21-126-66.compute-1.amazonaws.com | - | Medium
11 | [23.21.140.41](https://vuldb.com/?ip.23.21.140.41) | ec2-23-21-140-41.compute-1.amazonaws.com | - | Medium
12 | [23.21.252.4](https://vuldb.com/?ip.23.21.252.4) | ec2-23-21-252-4.compute-1.amazonaws.com | - | Medium
13 | [23.224.232.68](https://vuldb.com/?ip.23.224.232.68) | - | - | High
14 | [46.41.150.129](https://vuldb.com/?ip.46.41.150.129) | - | - | High
15 | [47.103.63.1](https://vuldb.com/?ip.47.103.63.1) | - | - | High
16 | [49.12.80.38](https://vuldb.com/?ip.49.12.80.38) | static.38.80.12.49.clients.your-server.de | - | High
17 | [49.12.80.40](https://vuldb.com/?ip.49.12.80.40) | static.40.80.12.49.clients.your-server.de | - | High
18 | [49.12.113.223](https://vuldb.com/?ip.49.12.113.223) | static.223.113.12.49.clients.your-server.de | - | High
19 | [50.19.48.59](https://vuldb.com/?ip.50.19.48.59) | ec2-50-19-48-59.compute-1.amazonaws.com | - | Medium
20 | [50.19.96.218](https://vuldb.com/?ip.50.19.96.218) | ec2-50-19-96-218.compute-1.amazonaws.com | - | Medium
21 | [50.19.252.36](https://vuldb.com/?ip.50.19.252.36) | ec2-50-19-252-36.compute-1.amazonaws.com | - | Medium
22 | [51.15.54.102](https://vuldb.com/?ip.51.15.54.102) | 102-54-15-51.instances.scw.cloud | - | High
23 | [51.15.58.224](https://vuldb.com/?ip.51.15.58.224) | 224-58-15-51.instances.scw.cloud | - | High
24 | ... | ... | ... | ...

There are 91 more IOC items available. Please use our online service to access the data.

## TTP - Tactics, Techniques, Procedures

_Tactics, techniques, and procedures_ (TTP) summarize the suspected MITRE ATT&CK techniques used by _CoinMiner_. This data is unique as it uses our predictive model for actor profiling.

ID | Technique | Weakness | Description | Confidence
-- | --------- | -------- | ----------- | ----------
1 | T1059 | CWE-94 | Argument Injection | High
2 | T1505 | CWE-89, CWE-90 | SQL Injection | High
3 | T1592 | CWE-200 | Invocation of Process Using Visible Sensitive Information | High

## IOA - Indicator of Attack

These _indicators of attack_ (IOA) list the potential fragments used for technical activities like reconnaissance, exploitation, privilege escalation, and exfiltration by CoinMiner. This data is unique as it uses our predictive model for actor profiling.

ID | Type | Indicator | Confidence
-- | ---- | --------- | ----------
1 | File | `inc/config.php` | High
2 | File | `ItemInfo.asp` | Medium
3 | File | `utilities/pspp-dump-sav.c` | High
4 | ... | ... | ...

There are 2 more IOA items available (file, library, argument, input value, pattern, network port). Please use our online service to access the data.

## References

The following list contains _external sources_ which discuss the actor and the associated activities:

* https://asec.ahnlab.com/en/40673/
* https://asec.ahnlab.com/en/45182/
* https://asec.ahnlab.com/en/46774/
* https://asec.ahnlab.com/en/51908/
* https://asec.ahnlab.com/en/60440/
* https://asec.ahnlab.com/en/61185/
* https://blog.talosintelligence.com/2018/09/threat-roundup-0914-0921.html
* https://blog.talosintelligence.com/2021/02/threat-roundup-0212-0219.html
* https://blog.talosintelligence.com/2021/02/threat-roundup-0219-0226.html
* https://blog.talosintelligence.com/2021/03/threat-roundup-0305-0312.html
* https://blog.talosintelligence.com/2021/04/threat-roundup-0416-0423.html
* https://blog.talosintelligence.com/2021/05/threat-roundup-0507-0514.html
* https://blog.talosintelligence.com/2021/06/threat-roundup-0604-0611.html
* https://blog.talosintelligence.com/2021/06/threat-roundup-0611-0617.html
* https://blog.talosintelligence.com/2021/06/threat-roundup-0617-0624.html
* https://blog.talosintelligence.com/2022/04/threat-roundup-0408-0415.html
* https://blog.talosintelligence.com/threat-roundup-1013-1020/
* https://blog.trendmicro.com/trendlabs-security-intelligence/zoomed-in-a-look-into-a-coinminer-bundled-with-zoom-installer/
* https://isc.sans.edu/forums/diary/CoinMiners+searching+for+hosts/24364/
* https://isc.sans.edu/forums/diary/From+Microtik+with+Love/23762/ https://isc.sans.edu/forums/diary/More+malspam+pushing+Lokibot/23754/
* https://isc.sans.edu/forums/diary/Pornographic+malspam+pushes+coin+miner+malware/23119/
* https://threatfox.abuse.ch
* https://tria.ge/220416-dv7casgchn
* https://tria.ge/240318-xddhfafd78/behavioral1
* https://urlhaus.abuse.ch/url/2739139/
* https://www.trendmicro.com/en_us/research/22/i/a-post-exploitation-look-at-coinminers-abusing-weblogic-vulnerab.html

## Literature

The following _articles_ explain our unique predictive cyber threat intelligence:

* [VulDB Cyber Threat Intelligence Documentation](https://vuldb.com/?kb.cti)
* [Cyber Threat Intelligence - Early Anticipation of Attacks](https://www.scip.ch/en/?labs.20201022)

## License

(c) [1997-2024](https://vuldb.com/?kb.changelog) by [vuldb.com](https://vuldb.com/?kb.about). All data on this page is shared under the license [CC BY-NC-SA 4.0](https://creativecommons.org/licenses/by-nc-sa/4.0/). Questions? Check the [FAQ](https://vuldb.com/?kb.faq), read the [documentation](https://vuldb.com/?kb) or [contact us](https://vuldb.com/?contact)!
