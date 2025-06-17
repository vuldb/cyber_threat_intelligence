# ValleyRAT - Cyber Threat Intelligence

These _indicators_ were reported, collected, and generated during the [VulDB CTI analysis](https://vuldb.com/?kb.cti) of the actor known as [ValleyRAT](https://vuldb.com/?actor.valleyrat). The _activity monitoring_ correlates data from social media, forums, chat rooms, and darknet markets. It helps to determine associated actors, specific activities, expected intentions, emerging research, and ongoing attacks. Our unique _predictive model_ uses _big data_ to forecast activities and their characteristics.

_Live data_ and more _analysis capabilities_ are available at [https://vuldb.com/?actor.valleyrat](https://vuldb.com/?actor.valleyrat)

## Countries

These _countries_ are directly (e.g. origin of attacks) or indirectly (e.g. access by proxy) associated with ValleyRAT:

* [US](https://vuldb.com/?country.us)

## IOC - Indicator of Compromise

These _indicators of compromise_ (IOC) indicate associated network resources which are known to be part of research and attack activities of ValleyRAT.

ID | IP address | Hostname | Campaign | Confidence
-- | ---------- | -------- | -------- | ----------
1 | [1.15.156.66](https://vuldb.com/?ip.1.15.156.66) | - | - | High
2 | [8.212.101.195](https://vuldb.com/?ip.8.212.101.195) | - | - | High
3 | [8.217.85.20](https://vuldb.com/?ip.8.217.85.20) | - | - | High
4 | [8.218.163.62](https://vuldb.com/?ip.8.218.163.62) | - | - | High
5 | [8.218.163.85](https://vuldb.com/?ip.8.218.163.85) | - | - | High
6 | [15.197.64.127](https://vuldb.com/?ip.15.197.64.127) | a666405ef1e20e2cd.awsglobalaccelerator.com | - | High
7 | [18.167.52.240](https://vuldb.com/?ip.18.167.52.240) | ec2-18-167-52-240.ap-east-1.compute.amazonaws.com | - | Medium
8 | [23.226.57.67](https://vuldb.com/?ip.23.226.57.67) | - | - | High
9 | [23.235.165.5](https://vuldb.com/?ip.23.235.165.5) | - | - | High
10 | [23.235.165.54](https://vuldb.com/?ip.23.235.165.54) | - | - | High
11 | [27.25.158.108](https://vuldb.com/?ip.27.25.158.108) | - | - | High
12 | [27.50.63.8](https://vuldb.com/?ip.27.50.63.8) | - | - | High
13 | [27.124.4.60](https://vuldb.com/?ip.27.124.4.60) | - | - | High
14 | [27.124.21.211](https://vuldb.com/?ip.27.124.21.211) | - | - | High
15 | [27.124.34.140](https://vuldb.com/?ip.27.124.34.140) | - | - | High
16 | [27.124.42.200](https://vuldb.com/?ip.27.124.42.200) | - | - | High
17 | [34.1.142.70](https://vuldb.com/?ip.34.1.142.70) | 70.142.1.34.bc.googleusercontent.com | - | Medium
18 | [38.181.20.23](https://vuldb.com/?ip.38.181.20.23) | - | - | High
19 | [38.181.22.44](https://vuldb.com/?ip.38.181.22.44) | - | - | High
20 | [43.128.141.78](https://vuldb.com/?ip.43.128.141.78) | - | - | High
21 | [43.129.233.99](https://vuldb.com/?ip.43.129.233.99) | - | - | High
22 | [43.129.233.146](https://vuldb.com/?ip.43.129.233.146) | - | - | High
23 | [43.132.212.111](https://vuldb.com/?ip.43.132.212.111) | - | - | High
24 | [43.132.235.4](https://vuldb.com/?ip.43.132.235.4) | - | - | High
25 | [43.154.172.193](https://vuldb.com/?ip.43.154.172.193) | - | - | High
26 | [43.226.125.44](https://vuldb.com/?ip.43.226.125.44) | - | - | High
27 | [43.250.172.42](https://vuldb.com/?ip.43.250.172.42) | - | - | High
28 | [45.192.168.4](https://vuldb.com/?ip.45.192.168.4) | - | - | High
29 | ... | ... | ... | ...

There are 113 more IOC items available. Please use our online service to access the data.

## TTP - Tactics, Techniques, Procedures

_Tactics, techniques, and procedures_ (TTP) summarize the suspected MITRE ATT&CK techniques used by _ValleyRAT_. This data is unique as it uses our predictive model for actor profiling.

ID | Technique | Weakness | Description | Confidence
-- | --------- | -------- | ----------- | ----------
1 | T1059.007 | CWE-79 | Basic Cross Site Scripting | High
2 | T1202 | CWE-77 | Command Shell in Externally Accessible Directory | High
3 | T1505 | CWE-89 | SQL Injection | High

## IOA - Indicator of Attack

These _indicators of attack_ (IOA) list the potential fragments used for technical activities like reconnaissance, exploitation, privilege escalation, and exfiltration by ValleyRAT. This data is unique as it uses our predictive model for actor profiling.

ID | Type | Indicator | Confidence
-- | ---- | --------- | ----------
1 | File | `/ecommerce/admin/settings/setDiscount.php` | High
2 | File | `/wireless/guestnetwork.asp` | High
3 | File | `/wireless/security.asp` | High
4 | ... | ... | ...

There are 19 more IOA items available (file, library, argument, input value, pattern, network port). Please use our online service to access the data.

## References

The following list contains _external sources_ which discuss the actor and the associated activities:

* https://asec.ahnlab.com/en/82707/
* https://bazaar.abuse.ch/sample/27780a53d6d31c511e7824b89e8a436f62d11df26855f1ef6168a0bc84935898/
* https://bazaar.abuse.ch/sample/bb1d91e8f93a1b08b098969e48a12d2f2b8203a30de0c3d85ec8cd36a3fa8049/
* https://threatfox.abuse.ch
* https://urlhaus.abuse.ch/host/43.128.141.78/
* https://www.splunk.com/en_us/blog/security/valleyrat-insights-tactics-techniques-and-detection-methods.html
* https://www.zscaler.com/blogs/security-research/technical-analysis-latest-variant-valleyrat

## Literature

The following _articles_ explain our unique predictive cyber threat intelligence:

* [VulDB Cyber Threat Intelligence Documentation](https://vuldb.com/?kb.cti)
* [Cyber Threat Intelligence - Early Anticipation of Attacks](https://www.scip.ch/en/?labs.20201022)

## License

(c) [1997-2025](https://vuldb.com/?kb.changelog) by [vuldb.com](https://vuldb.com/?kb.about). All data on this page is shared under the license [CC BY-NC-SA 4.0](https://creativecommons.org/licenses/by-nc-sa/4.0/). Questions? Check the [FAQ](https://vuldb.com/?kb.faq), read the [documentation](https://vuldb.com/?kb) or [contact us](https://vuldb.com/?contact)!
