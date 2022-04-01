# Zeroaccess - Cyber Threat Intelligence

These _indicators_ were reported, collected, and generated during the [VulDB CTI analysis](https://vuldb.com/?kb.cti) of the actor known as [Zeroaccess](https://vuldb.com/?actor.zeroaccess). The _activity monitoring_ correlates data from social media, forums, chat rooms, and darknet markets. It helps to determine associated actors, specific activities, expected intentions, emerging research, and ongoing attacks. Our unique _predictive model_ uses _big data_ to forecast activities and their characteristics.

_Live data_ and more _analysis capabilities_ are available at [https://vuldb.com/?actor.zeroaccess](https://vuldb.com/?actor.zeroaccess)

## Countries

These _countries_ are directly (e.g. origin of attacks) or indirectly (e.g. access by proxy) associated with Zeroaccess:

* [VN](https://vuldb.com/?country.vn)

## IOC - Indicator of Compromise

These _indicators of compromise_ (IOC) indicate associated network resources which are known to be part of research and attack activities of Zeroaccess.

ID | IP address | Hostname | Campaign | Confidence
-- | ---------- | -------- | -------- | ----------
1 | [13.107.21.200](https://vuldb.com/?ip.13.107.21.200) | - | - | High
2 | [13.107.213.70](https://vuldb.com/?ip.13.107.213.70) | - | - | High
3 | [13.107.246.70](https://vuldb.com/?ip.13.107.246.70) | - | - | High
4 | [20.36.253.92](https://vuldb.com/?ip.20.36.253.92) | - | - | High
5 | [23.36.85.183](https://vuldb.com/?ip.23.36.85.183) | a23-36-85-183.deploy.static.akamaitechnologies.com | - | High
6 | [23.78.173.83](https://vuldb.com/?ip.23.78.173.83) | a23-78-173-83.deploy.static.akamaitechnologies.com | - | High
7 | [24.112.60.78](https://vuldb.com/?ip.24.112.60.78) | host-24-112-60-78.vyvebroadband.net | - | High
8 | [27.252.253.254](https://vuldb.com/?ip.27.252.253.254) | 254.253.252.27.dyn.cust.vf.net.nz | - | High
9 | [31.19.213.221](https://vuldb.com/?ip.31.19.213.221) | ip1f13d5dd.dynamic.kabel-deutschland.de | - | High
10 | [36.3.96.243](https://vuldb.com/?ip.36.3.96.243) | static-36-3-96-243.xxxxx.svips.gol.ne.jp | - | High
11 | [38.121.20.199](https://vuldb.com/?ip.38.121.20.199) | - | - | High
12 | [40.91.78.9](https://vuldb.com/?ip.40.91.78.9) | - | - | High
13 | [46.47.98.47](https://vuldb.com/?ip.46.47.98.47) | - | - | High
14 | [46.246.253.254](https://vuldb.com/?ip.46.246.253.254) | 46.246.253.254.dsl.dyn.forthnet.gr | - | High
15 | [50.151.53.179](https://vuldb.com/?ip.50.151.53.179) | c-50-151-53-179.hsd1.il.comcast.net | - | High
16 | [52.24.23.122](https://vuldb.com/?ip.52.24.23.122) | ec2-52-24-23-122.us-west-2.compute.amazonaws.com | - | Medium
17 | [52.34.145.111](https://vuldb.com/?ip.52.34.145.111) | ec2-52-34-145-111.us-west-2.compute.amazonaws.com | - | Medium
18 | [52.85.144.35](https://vuldb.com/?ip.52.85.144.35) | server-52-85-144-35.iad89.r.cloudfront.net | - | High
19 | [54.81.163.76](https://vuldb.com/?ip.54.81.163.76) | ec2-54-81-163-76.compute-1.amazonaws.com | - | Medium
20 | [54.160.67.78](https://vuldb.com/?ip.54.160.67.78) | ec2-54-160-67-78.compute-1.amazonaws.com | - | Medium
21 | [64.4.54.254](https://vuldb.com/?ip.64.4.54.254) | - | - | High
22 | [64.210.151.32](https://vuldb.com/?ip.64.210.151.32) | - | - | High
23 | [65.55.44.109](https://vuldb.com/?ip.65.55.44.109) | - | - | High
24 | [66.233.105.136](https://vuldb.com/?ip.66.233.105.136) | - | - | High
25 | ... | ... | ... | ...

There are 96 more IOC items available. Please use our online service to access the data.

## TTP - Tactics, Techniques, Procedures

_Tactics, techniques, and procedures_ (TTP) summarize the suspected MITRE ATT&CK techniques used by _Zeroaccess_. This data is unique as it uses our predictive model for actor profiling.

ID | Technique | Weakness | Description | Confidence
-- | --------- | -------- | ----------- | ----------
1 | T1008 | CWE-757 | Algorithm Downgrade | High
2 | T1040 | CWE-294 | Authentication Bypass by Capture-replay | High
3 | T1059.007 | CWE-79, CWE-80 | Cross Site Scripting | High
4 | ... | ... | ... | ...

There are 7 more TTP items available. Please use our online service to access the data.

## IOA - Indicator of Attack

These _indicators of attack_ (IOA) list the potential fragments used for technical activities like reconnaissance, exploitation, privilege escalation, and exfiltration by Zeroaccess. This data is unique as it uses our predictive model for actor profiling.

ID | Type | Indicator | Confidence
-- | ---- | --------- | ----------
1 | File | `/admin.php/admin/plog/index.html` | High
2 | File | `/admin.php/admin/ulog/index.html` | High
3 | File | `/admin.php/admin/vod/data.html` | High
4 | File | `/admin.php/admin/website/data.html` | High
5 | File | `/admin/export/getcsv/article_db` | High
6 | File | `/admin/login.php` | High
7 | File | `/admin/show.php` | High
8 | File | `/api/V2/internal/TaskPermissions/CheckTaskAccess` | High
9 | File | `/cgi-bin/uploadAccessCodePic` | High
10 | File | `/cgi-bin/uploadWeiXinPic` | High
11 | File | `/config/list` | Medium
12 | File | `/data/sqldata` | High
13 | File | `/goform/delAd` | High
14 | File | `/goform/exeCommand` | High
15 | File | `/goform/setAdInfoDetail` | High
16 | File | `/goform/setFixTools` | High
17 | File | `/goform/SetInternetLanInfo` | High
18 | File | `/goform/SetLanInfo` | High
19 | ... | ... | ...

There are 160 more IOA items available (file, library, argument, input value, pattern, network port). Please use our online service to access the data.

## References

The following list contains _external sources_ which discuss the actor and the associated activities:

* https://blog.talosintelligence.com/2021/04/threat-roundup-0409-0416.html
* https://blog.talosintelligence.com/2021/04/threat-roundup-0423-0430.html
* https://blog.talosintelligence.com/2021/05/threat-roundup-0507-0514.html
* https://blog.talosintelligence.com/2021/05/threat-roundup-0521-0528.html
* https://blog.talosintelligence.com/2021/07/threat-roundup-0723-0730.html

## Literature

The following _articles_ explain our unique predictive cyber threat intelligence:

* [VulDB Cyber Threat Intelligence Documentation](https://vuldb.com/?kb.cti)
* [Cyber Threat Intelligence - Early Anticipation of Attacks](https://www.scip.ch/en/?labs.20201022)

## License

(c) [1997-2022](https://vuldb.com/?kb.changelog) by [vuldb.com](https://vuldb.com/?kb.about). All data on this page is shared under the license [CC BY-NC-SA 4.0](https://creativecommons.org/licenses/by-nc-sa/4.0/). Questions? Check the [FAQ](https://vuldb.com/?kb.faq), read the [documentation](https://vuldb.com/?kb) or [contact us](https://vuldb.com/?contact)!
