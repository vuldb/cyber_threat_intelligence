# Baldr - Cyber Threat Intelligence

These _indicators_ were reported, collected, and generated during the [VulDB CTI analysis](https://vuldb.com/?kb.cti) of the actor known as [Baldr](https://vuldb.com/?actor.baldr). The _activity monitoring_ correlates data from social media, forums, chat rooms, and darknet markets. It helps to determine associated actors, specific activities, expected intentions, emerging research, and ongoing attacks. Our unique _predictive model_ uses _big data_ to forecast activities and their characteristics.

_Live data_ and more _analysis capabilities_ are available at [https://vuldb.com/?actor.baldr](https://vuldb.com/?actor.baldr)

## Countries

These _countries_ are directly (e.g. origin of attacks) or indirectly (e.g. access by proxy) associated with Baldr:

* [NL](https://vuldb.com/?country.nl)
* [RU](https://vuldb.com/?country.ru)

## IOC - Indicator of Compromise

These _indicators of compromise_ (IOC) indicate associated network resources which are known to be part of research and attack activities of Baldr.

ID | IP address | Hostname | Campaign | Confidence
-- | ---------- | -------- | -------- | ----------
1 | [1.23.82.72](https://vuldb.com/?ip.1.23.82.72) | - | - | High
2 | [2.2.82.64](https://vuldb.com/?ip.2.2.82.64) | - | - | High
3 | [2.12.51.56](https://vuldb.com/?ip.2.12.51.56) | arennes-655-1-148-56.w2-12.abo.wanadoo.fr | - | High
4 | [3.95.29.25](https://vuldb.com/?ip.3.95.29.25) | ec2-3-95-29-25.compute-1.amazonaws.com | - | Medium
5 | [4.96.46.65](https://vuldb.com/?ip.4.96.46.65) | - | - | High
6 | [5.8.88.198](https://vuldb.com/?ip.5.8.88.198) | - | - | High
7 | [5.45.73.87](https://vuldb.com/?ip.5.45.73.87) | - | - | High
8 | [5.188.60.7](https://vuldb.com/?ip.5.188.60.7) | - | - | High
9 | [5.188.60.18](https://vuldb.com/?ip.5.188.60.18) | - | - | High
10 | [5.188.60.24](https://vuldb.com/?ip.5.188.60.24) | - | - | High
11 | [5.188.60.30](https://vuldb.com/?ip.5.188.60.30) | - | - | High
12 | [5.188.60.54](https://vuldb.com/?ip.5.188.60.54) | - | - | High
13 | [5.188.60.68](https://vuldb.com/?ip.5.188.60.68) | - | - | High
14 | [5.188.60.74](https://vuldb.com/?ip.5.188.60.74) | - | - | High
15 | [5.188.60.101](https://vuldb.com/?ip.5.188.60.101) | - | - | High
16 | [5.188.60.115](https://vuldb.com/?ip.5.188.60.115) | - | - | High
17 | [5.188.60.206](https://vuldb.com/?ip.5.188.60.206) | - | - | High
18 | [5.188.231.96](https://vuldb.com/?ip.5.188.231.96) | - | - | High
19 | [5.188.231.210](https://vuldb.com/?ip.5.188.231.210) | - | - | High
20 | [18.207.217.146](https://vuldb.com/?ip.18.207.217.146) | ec2-18-207-217-146.compute-1.amazonaws.com | - | Medium
21 | [18.221.49.166](https://vuldb.com/?ip.18.221.49.166) | ec2-18-221-49-166.us-east-2.compute.amazonaws.com | - | Medium
22 | [19.2.45.3](https://vuldb.com/?ip.19.2.45.3) | - | - | High
23 | [21.15.46.55](https://vuldb.com/?ip.21.15.46.55) | - | - | High
24 | [23.19.58.101](https://vuldb.com/?ip.23.19.58.101) | - | - | High
25 | [23.95.95.61](https://vuldb.com/?ip.23.95.95.61) | 23-95-95-61-host.colocrossing.com | - | High
26 | [23.254.217.112](https://vuldb.com/?ip.23.254.217.112) | hwsrv-930282.hostwindsdns.com | - | High
27 | ... | ... | ... | ...

There are 103 more IOC items available. Please use our online service to access the data.

## TTP - Tactics, Techniques, Procedures

_Tactics, techniques, and procedures_ (TTP) summarize the suspected MITRE ATT&CK techniques used by _Baldr_. This data is unique as it uses our predictive model for actor profiling.

ID | Technique | Weakness | Description | Confidence
-- | --------- | -------- | ----------- | ----------
1 | T1006 | CWE-22, CWE-23 | Path Traversal | High
2 | T1040 | CWE-294 | Authentication Bypass by Capture-replay | High
3 | T1055 | CWE-74 | Improper Neutralization of Data within XPath Expressions | High
4 | ... | ... | ... | ...

There are 14 more TTP items available. Please use our online service to access the data.

## IOA - Indicator of Attack

These _indicators of attack_ (IOA) list the potential fragments used for technical activities like reconnaissance, exploitation, privilege escalation, and exfiltration by Baldr. This data is unique as it uses our predictive model for actor profiling.

ID | Type | Indicator | Confidence
-- | ---- | --------- | ----------
1 | File | `/admin/subnets/ripe-query.php` | High
2 | File | `/api/front/search/books` | High
3 | File | `/api/mjkj-chat/chat/mng/update/questionCou` | High
4 | File | `/application/index/controller/Screen.php` | High
5 | File | `/apply.cgi` | Medium
6 | File | `/debug/pprof` | Medium
7 | File | `/export` | Low
8 | File | `/goform/aspForm` | High
9 | ... | ... | ...

There are 64 more IOA items available (file, library, argument, input value, pattern, network port). Please use our online service to access the data.

## References

The following list contains _external sources_ which discuss the actor and the associated activities:

* https://github.com/sophoslabs/IoCs/blob/master/Stealer-Baldr

## Literature

The following _articles_ explain our unique predictive cyber threat intelligence:

* [VulDB Cyber Threat Intelligence Documentation](https://vuldb.com/?kb.cti)
* [Cyber Threat Intelligence - Early Anticipation of Attacks](https://www.scip.ch/en/?labs.20201022)

## License

(c) [1997-2025](https://vuldb.com/?kb.changelog) by [vuldb.com](https://vuldb.com/?kb.about). All data on this page is shared under the license [CC BY-NC-SA 4.0](https://creativecommons.org/licenses/by-nc-sa/4.0/). Questions? Check the [FAQ](https://vuldb.com/?kb.faq), read the [documentation](https://vuldb.com/?kb) or [contact us](https://vuldb.com/?contact)!
