# Venom RAT - Cyber Threat Intelligence

These _indicators_ were reported, collected, and generated during the [VulDB CTI analysis](https://vuldb.com/?kb.cti) of the actor known as [Venom RAT](https://vuldb.com/?actor.venom_rat). The _activity monitoring_ correlates data from social media, forums, chat rooms, and darknet markets. It helps to determine associated actors, specific activities, expected intentions, emerging research, and ongoing attacks. Our unique _predictive model_ uses _big data_ to forecast activities and their characteristics.

_Live data_ and more _analysis capabilities_ are available at [https://vuldb.com/?actor.venom_rat](https://vuldb.com/?actor.venom_rat)

## Countries

These _countries_ are directly (e.g. origin of attacks) or indirectly (e.g. access by proxy) associated with Venom RAT:

* [HK](https://vuldb.com/?country.hk)
* [US](https://vuldb.com/?country.us)
* [FR](https://vuldb.com/?country.fr)
* ...

There are 1 more country items available. Please use our online service to access the data.

## IOC - Indicator of Compromise

These _indicators of compromise_ (IOC) indicate associated network resources which are known to be part of research and attack activities of Venom RAT.

ID | IP address | Hostname | Campaign | Confidence
-- | ---------- | -------- | -------- | ----------
1 | [2.59.255.190](https://vuldb.com/?ip.2.59.255.190) | - | - | High
2 | [2.224.144.191](https://vuldb.com/?ip.2.224.144.191) | 2-224-144-191.ip170.fastwebnet.it | - | High
3 | [3.64.4.198](https://vuldb.com/?ip.3.64.4.198) | ec2-3-64-4-198.eu-central-1.compute.amazonaws.com | - | Medium
4 | [3.67.161.133](https://vuldb.com/?ip.3.67.161.133) | ec2-3-67-161-133.eu-central-1.compute.amazonaws.com | - | Medium
5 | [3.124.67.191](https://vuldb.com/?ip.3.124.67.191) | ec2-3-124-67-191.eu-central-1.compute.amazonaws.com | - | Medium
6 | [3.126.37.18](https://vuldb.com/?ip.3.126.37.18) | ec2-3-126-37-18.eu-central-1.compute.amazonaws.com | - | Medium
7 | [3.127.138.57](https://vuldb.com/?ip.3.127.138.57) | ec2-3-127-138-57.eu-central-1.compute.amazonaws.com | - | Medium
8 | [5.83.190.86](https://vuldb.com/?ip.5.83.190.86) | - | - | High
9 | [16.16.29.185](https://vuldb.com/?ip.16.16.29.185) | ec2-16-16-29-185.eu-north-1.compute.amazonaws.com | - | Medium
10 | [18.156.13.209](https://vuldb.com/?ip.18.156.13.209) | ec2-18-156-13-209.eu-central-1.compute.amazonaws.com | - | Medium
11 | [18.157.68.73](https://vuldb.com/?ip.18.157.68.73) | ec2-18-157-68-73.eu-central-1.compute.amazonaws.com | - | Medium
12 | [18.158.249.75](https://vuldb.com/?ip.18.158.249.75) | ec2-18-158-249-75.eu-central-1.compute.amazonaws.com | - | Medium
13 | [18.192.93.86](https://vuldb.com/?ip.18.192.93.86) | ec2-18-192-93-86.eu-central-1.compute.amazonaws.com | - | Medium
14 | [18.197.239.5](https://vuldb.com/?ip.18.197.239.5) | ec2-18-197-239-5.eu-central-1.compute.amazonaws.com | - | Medium
15 | [18.198.77.177](https://vuldb.com/?ip.18.198.77.177) | ec2-18-198-77-177.eu-central-1.compute.amazonaws.com | - | Medium
16 | [20.206.160.43](https://vuldb.com/?ip.20.206.160.43) | - | - | High
17 | [24.241.229.173](https://vuldb.com/?ip.24.241.229.173) | 024-241-229-173.res.spectrum.com | - | High
18 | [25.48.43.42](https://vuldb.com/?ip.25.48.43.42) | - | - | High
19 | [27.3.194.101](https://vuldb.com/?ip.27.3.194.101) | - | - | High
20 | [31.201.66.248](https://vuldb.com/?ip.31.201.66.248) | 248-66-201-31.ftth.glasoperator.nl | - | High
21 | ... | ... | ... | ...

There are 81 more IOC items available. Please use our online service to access the data.

## TTP - Tactics, Techniques, Procedures

_Tactics, techniques, and procedures_ (TTP) summarize the suspected MITRE ATT&CK techniques used by _Venom RAT_. This data is unique as it uses our predictive model for actor profiling.

ID | Technique | Weakness | Description | Confidence
-- | --------- | -------- | ----------- | ----------
1 | T1006 | CWE-21, CWE-22 | Pathname Traversal | High
2 | T1040 | CWE-319 | Authentication Bypass by Capture-replay | High
3 | T1055 | CWE-74 | Injection | High
4 | ... | ... | ... | ...

There are 13 more TTP items available. Please use our online service to access the data.

## IOA - Indicator of Attack

These _indicators of attack_ (IOA) list the potential fragments used for technical activities like reconnaissance, exploitation, privilege escalation, and exfiltration by Venom RAT. This data is unique as it uses our predictive model for actor profiling.

ID | Type | Indicator | Confidence
-- | ---- | --------- | ----------
1 | File | `/.ssh/authorized_keys` | High
2 | File | `/baseOpLog.do` | High
3 | File | `/bitrix/admin/ldap_server_edit.php` | High
4 | File | `/cgi-bin/api-get_line_status` | High
5 | File | `/cgi-bin/wapopen` | High
6 | File | `/controller/OnlinePreviewController.java` | High
7 | ... | ... | ...

There are 52 more IOA items available (file, library, argument, input value, pattern, network port). Please use our online service to access the data.

## References

The following list contains _external sources_ which discuss the actor and the associated activities:

* https://github.com/pan-unit42/iocs/blob/master/venomrat_iocs.csv
* https://tria.ge/220715-x2rd7sehbq

## Literature

The following _articles_ explain our unique predictive cyber threat intelligence:

* [VulDB Cyber Threat Intelligence Documentation](https://vuldb.com/?kb.cti)
* [Cyber Threat Intelligence - Early Anticipation of Attacks](https://www.scip.ch/en/?labs.20201022)

## License

(c) [1997-2023](https://vuldb.com/?kb.changelog) by [vuldb.com](https://vuldb.com/?kb.about). All data on this page is shared under the license [CC BY-NC-SA 4.0](https://creativecommons.org/licenses/by-nc-sa/4.0/). Questions? Check the [FAQ](https://vuldb.com/?kb.faq), read the [documentation](https://vuldb.com/?kb) or [contact us](https://vuldb.com/?contact)!
