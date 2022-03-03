# RedLine - Cyber Threat Intelligence

These _indicators_ were reported, collected, and generated during the [VulDB CTI analysis](https://vuldb.com/?kb.cti) of the actor known as [RedLine](https://vuldb.com/?actor.redline). The _activity monitoring_ correlates data from social media, forums, chat rooms, and darknet markets. It helps to determine associated actors, specific activities, expected intentions, emerging research, and ongoing attacks. Our unique _predictive model_ uses _big data_ to forecast activities and their characteristics.

_Live data_ and more _analysis capabilities_ are available at [https://vuldb.com/?actor.redline](https://vuldb.com/?actor.redline)

## Countries

These _countries_ are directly (e.g. origin of attacks) or indirectly (e.g. access by proxy) associated with RedLine:

* [US](https://vuldb.com/?country.us)
* [CN](https://vuldb.com/?country.cn)
* [FR](https://vuldb.com/?country.fr)
* ...

There are 9 more country items available. Please use our online service to access the data.

## IOC - Indicator of Compromise

These _indicators of compromise_ (IOC) indicate associated network resources which are known to be part of research and attack activities of RedLine.

ID | IP address | Hostname | Campaign | Confidence
-- | ---------- | -------- | -------- | ----------
1 | [8.249.227.254](https://vuldb.com/?ip.8.249.227.254) | - | - | High
2 | [8.249.241.254](https://vuldb.com/?ip.8.249.241.254) | - | - | High
3 | [8.253.45.248](https://vuldb.com/?ip.8.253.45.248) | - | - | High
4 | [8.253.132.120](https://vuldb.com/?ip.8.253.132.120) | - | - | High
5 | [13.52.79.131](https://vuldb.com/?ip.13.52.79.131) | ec2-13-52-79-131.us-west-1.compute.amazonaws.com | - | Medium
6 | [23.21.205.229](https://vuldb.com/?ip.23.21.205.229) | ec2-23-21-205-229.compute-1.amazonaws.com | - | Medium
7 | [23.21.224.49](https://vuldb.com/?ip.23.21.224.49) | ec2-23-21-224-49.compute-1.amazonaws.com | - | Medium
8 | [23.23.104.250](https://vuldb.com/?ip.23.23.104.250) | ec2-23-23-104-250.compute-1.amazonaws.com | - | Medium
9 | [23.46.238.194](https://vuldb.com/?ip.23.46.238.194) | a23-46-238-194.deploy.static.akamaitechnologies.com | - | High
10 | [34.76.8.115](https://vuldb.com/?ip.34.76.8.115) | 115.8.76.34.bc.googleusercontent.com | - | Medium
11 | [37.46.150.90](https://vuldb.com/?ip.37.46.150.90) | - | - | High
12 | [45.9.20.101](https://vuldb.com/?ip.45.9.20.101) | - | - | High
13 | [45.33.89.196](https://vuldb.com/?ip.45.33.89.196) | li1035-196.members.linode.com | - | High
14 | [45.66.9.155](https://vuldb.com/?ip.45.66.9.155) | vm3163203.24ssd.had.wf | - | High
15 | [45.67.228.119](https://vuldb.com/?ip.45.67.228.119) | vm231525.pq.hosting | - | High
16 | [45.67.228.152](https://vuldb.com/?ip.45.67.228.152) | smail.fun | - | High
17 | [45.67.231.50](https://vuldb.com/?ip.45.67.231.50) | licher.lone.example.com | - | High
18 | [45.84.0.108](https://vuldb.com/?ip.45.84.0.108) | pangeransosmed.vip | - | High
19 | [45.84.0.200](https://vuldb.com/?ip.45.84.0.200) | 1c.capricorn.md | - | High
20 | [45.87.3.177](https://vuldb.com/?ip.45.87.3.177) | vm3114026.43ssd.had.wf | - | High
21 | [45.128.150.68](https://vuldb.com/?ip.45.128.150.68) | dok.com | - | High
22 | [45.130.147.55](https://vuldb.com/?ip.45.130.147.55) | - | - | High
23 | ... | ... | ... | ...

There are 90 more IOC items available. Please use our online service to access the data.

## TTP - Tactics, Techniques, Procedures

_Tactics, techniques, and procedures_ (TTP) summarize the suspected ATT&CK techniques used by RedLine. This data is unique as it uses our predictive model for actor profiling.

ID | Technique | Weakness | Description | Confidence
-- | --------- | -------- | ----------- | ----------
1 | T1059.007 | CWE-79 | Cross Site Scripting | High
2 | T1068 | CWE-264, CWE-284 | Execution with Unnecessary Privileges | High
3 | T1110.001 | CWE-307, CWE-798 | Improper Restriction of Excessive Authentication Attempts | High
4 | ... | ... | ... | ...

There are 3 more TTP items available. Please use our online service to access the data.

## IOA - Indicator of Attack

These _indicators of attack_ (IOA) list the potential fragments used for technical activities like reconnaissance, exploitation, privilege escalation, and exfiltration by RedLine. This data is unique as it uses our predictive model for actor profiling.

ID | Type | Indicator | Confidence
-- | ---- | --------- | ----------
1 | File | `/.env` | Low
2 | File | `/category.php` | High
3 | File | `/cgi-bin/delete_CA` | High
4 | File | `/Config/SaveUploadedHotspotLogoFile` | High
5 | File | `/download` | Medium
6 | File | `/get_getnetworkconf.cgi` | High
7 | File | `/GponForm/device_Form?script/` | High
8 | File | `/includes/rrdtool.inc.php` | High
9 | File | `/Main_AdmStatus_Content.asp` | High
10 | File | `/NAGErrors` | Medium
11 | File | `/sgms/TreeControl` | High
12 | ... | ... | ...

There are 89 more IOA items available (file, library, argument, input value, pattern, network port). Please use our online service to access the data.

## References

The following list contains _external sources_ which discuss the actor and the associated activities:

* https://blog.talosintelligence.com/2021/02/threat-roundup-0212-0219.html
* https://blog.talosintelligence.com/2021/06/threat-roundup-0528-0604.html
* https://blog.talosintelligence.com/2021/06/threat-roundup-0604-0611.html
* https://blog.talosintelligence.com/2021/06/threat-roundup-0617-0624.html
* https://blog.talosintelligence.com/2021/07/threat-roundup-0625-0702.html
* https://blogs.blackberry.com/en/2021/07/threat-thursday-redline-infostealer
* https://blogs.blackberry.com/en/2021/10/threat-thursday-redline-infostealer-update

## Literature

The following _articles_ explain our unique predictive cyber threat intelligence:

* [VulDB Cyber Threat Intelligence Documentation](https://vuldb.com/?kb.cti)
* [Cyber Threat Intelligence - Early Anticipation of Attacks](https://www.scip.ch/en/?labs.20201022)

## License

(c) [1997-2022](https://vuldb.com/?kb.changelog) by [vuldb.com](https://vuldb.com/?kb.about). All data on this page is shared under the license [CC BY-NC-SA 4.0](https://creativecommons.org/licenses/by-nc-sa/4.0/). Questions? Check the [FAQ](https://vuldb.com/?kb.faq), read the [documentation](https://vuldb.com/?kb) or [contact us](https://vuldb.com/?contact)!
