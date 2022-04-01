# Cerber - Cyber Threat Intelligence

These _indicators_ were reported, collected, and generated during the [VulDB CTI analysis](https://vuldb.com/?kb.cti) of the actor known as [Cerber](https://vuldb.com/?actor.cerber). The _activity monitoring_ correlates data from social media, forums, chat rooms, and darknet markets. It helps to determine associated actors, specific activities, expected intentions, emerging research, and ongoing attacks. Our unique _predictive model_ uses _big data_ to forecast activities and their characteristics.

_Live data_ and more _analysis capabilities_ are available at [https://vuldb.com/?actor.cerber](https://vuldb.com/?actor.cerber)

## Countries

These _countries_ are directly (e.g. origin of attacks) or indirectly (e.g. access by proxy) associated with Cerber:

* [US](https://vuldb.com/?country.us)
* [CN](https://vuldb.com/?country.cn)
* [DE](https://vuldb.com/?country.de)
* ...

There are 1 more country items available. Please use our online service to access the data.

## IOC - Indicator of Compromise

These _indicators of compromise_ (IOC) indicate associated network resources which are known to be part of research and attack activities of Cerber.

ID | IP address | Hostname | Campaign | Confidence
-- | ---------- | -------- | -------- | ----------
1 | [5.9.49.12](https://vuldb.com/?ip.5.9.49.12) | static.12.49.9.5.clients.your-server.de | - | High
2 | [5.135.183.146](https://vuldb.com/?ip.5.135.183.146) | freya.stelas.de | - | High
3 | [5.196.159.173](https://vuldb.com/?ip.5.196.159.173) | - | - | High
4 | [13.107.21.200](https://vuldb.com/?ip.13.107.21.200) | - | - | High
5 | [23.94.5.133](https://vuldb.com/?ip.23.94.5.133) | 23-94-5-133-host.colocrossing.com | - | High
6 | [23.152.0.36](https://vuldb.com/?ip.23.152.0.36) | tcts-000036.techtrapes.com | - | High
7 | [34.199.22.139](https://vuldb.com/?ip.34.199.22.139) | ec2-34-199-22-139.compute-1.amazonaws.com | - | Medium
8 | [45.32.28.232](https://vuldb.com/?ip.45.32.28.232) | - | - | High
9 | [45.56.79.23](https://vuldb.com/?ip.45.56.79.23) | li929-23.members.linode.com | - | High
10 | [45.56.117.118](https://vuldb.com/?ip.45.56.117.118) | li935-118.members.linode.com | - | High
11 | [45.63.25.55](https://vuldb.com/?ip.45.63.25.55) | 45.63.25.55.vultr.com | - | Medium
12 | [45.63.99.180](https://vuldb.com/?ip.45.63.99.180) | 45.63.99.180.vultr.com | - | Medium
13 | [52.2.101.52](https://vuldb.com/?ip.52.2.101.52) | ec2-52-2-101-52.compute-1.amazonaws.com | - | Medium
14 | [52.21.132.24](https://vuldb.com/?ip.52.21.132.24) | ec2-52-21-132-24.compute-1.amazonaws.com | - | Medium
15 | [54.84.252.139](https://vuldb.com/?ip.54.84.252.139) | ec2-54-84-252-139.compute-1.amazonaws.com | - | Medium
16 | [54.87.5.88](https://vuldb.com/?ip.54.87.5.88) | ec2-54-87-5-88.compute-1.amazonaws.com | - | Medium
17 | [54.88.175.149](https://vuldb.com/?ip.54.88.175.149) | ec2-54-88-175-149.compute-1.amazonaws.com | - | Medium
18 | ... | ... | ... | ...

There are 66 more IOC items available. Please use our online service to access the data.

## TTP - Tactics, Techniques, Procedures

_Tactics, techniques, and procedures_ (TTP) summarize the suspected MITRE ATT&CK techniques used by _Cerber_. This data is unique as it uses our predictive model for actor profiling.

ID | Technique | Weakness | Description | Confidence
-- | --------- | -------- | ----------- | ----------
1 | T1059.007 | CWE-79, CWE-80 | Cross Site Scripting | High
2 | T1068 | CWE-264, CWE-284 | Execution with Unnecessary Privileges | High
3 | T1110.001 | CWE-798 | Improper Restriction of Excessive Authentication Attempts | High
4 | ... | ... | ... | ...

There are 5 more TTP items available. Please use our online service to access the data.

## IOA - Indicator of Attack

These _indicators of attack_ (IOA) list the potential fragments used for technical activities like reconnaissance, exploitation, privilege escalation, and exfiltration by Cerber. This data is unique as it uses our predictive model for actor profiling.

ID | Type | Indicator | Confidence
-- | ---- | --------- | ----------
1 | File | `/cgi-bin/login_action.cgi` | High
2 | File | `/DbXmlInfo.xml` | High
3 | File | `/forms/web_importTFTP` | High
4 | File | `/OA_HTML/cabo/jsps/a.jsp` | High
5 | File | `/plugin/extended-choice-parameter/js/` | High
6 | File | `/rest/api/1.0/render` | High
7 | File | `/sap/public/bc/abap` | High
8 | File | `/search.php` | Medium
9 | File | `/shell?cmd` | Medium
10 | File | `activateuser.aspx` | High
11 | File | `addentry.php` | Medium
12 | File | `AndroidManifest.xml` | High
13 | File | `application/admin/controller/Admin.php` | High
14 | File | `asm/preproc.c` | High
15 | File | `auth-gss2.c` | Medium
16 | File | `authent.php4` | Medium
17 | File | `bgp_packet.c` | Medium
18 | File | `catalog.asp` | Medium
19 | File | `Cgi/confirm.py` | High
20 | File | `cli/caff.c` | Medium
21 | File | `cli/dsdiff.c` | Medium
22 | File | `content/unity-api.js` | High
23 | ... | ... | ...

There are 191 more IOA items available (file, library, argument, input value, pattern, network port). Please use our online service to access the data.

## References

The following list contains _external sources_ which discuss the actor and the associated activities:

* https://blog.talosintelligence.com/2021/01/threat-roundup-0122.html
* https://blog.talosintelligence.com/2021/02/threat-roundup-0129-0205.html
* https://blog.talosintelligence.com/2021/02/threat-roundup-0205-0212.html
* https://blog.talosintelligence.com/2021/02/threat-roundup-0219-0226.html
* https://blog.talosintelligence.com/2021/03/threat-roundup-0305-0312.html
* https://blog.talosintelligence.com/2021/04/threat-roundup-0402-0409.html
* https://blog.talosintelligence.com/2021/09/threat-roundup-0917-0924.html
* https://blog.talosintelligence.com/2021/10/threat-roundup-0924-1001.html
* https://blog.talosintelligence.com/2021/11/threat-roundup-1029-1105.html
* https://blog.talosintelligence.com/2022/02/threat-roundup-0128-0204.html

## Literature

The following _articles_ explain our unique predictive cyber threat intelligence:

* [VulDB Cyber Threat Intelligence Documentation](https://vuldb.com/?kb.cti)
* [Cyber Threat Intelligence - Early Anticipation of Attacks](https://www.scip.ch/en/?labs.20201022)

## License

(c) [1997-2022](https://vuldb.com/?kb.changelog) by [vuldb.com](https://vuldb.com/?kb.about). All data on this page is shared under the license [CC BY-NC-SA 4.0](https://creativecommons.org/licenses/by-nc-sa/4.0/). Questions? Check the [FAQ](https://vuldb.com/?kb.faq), read the [documentation](https://vuldb.com/?kb) or [contact us](https://vuldb.com/?contact)!
