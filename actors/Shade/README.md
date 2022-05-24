# Shade - Cyber Threat Intelligence

These _indicators_ were reported, collected, and generated during the [VulDB CTI analysis](https://vuldb.com/?kb.cti) of the actor known as [Shade](https://vuldb.com/?actor.shade). The _activity monitoring_ correlates data from social media, forums, chat rooms, and darknet markets. It helps to determine associated actors, specific activities, expected intentions, emerging research, and ongoing attacks. Our unique _predictive model_ uses _big data_ to forecast activities and their characteristics.

_Live data_ and more _analysis capabilities_ are available at [https://vuldb.com/?actor.shade](https://vuldb.com/?actor.shade)

## Countries

These _countries_ are directly (e.g. origin of attacks) or indirectly (e.g. access by proxy) associated with Shade:

* [US](https://vuldb.com/?country.us)
* [RU](https://vuldb.com/?country.ru)
* [DE](https://vuldb.com/?country.de)
* ...

There are 3 more country items available. Please use our online service to access the data.

## IOC - Indicator of Compromise

These _indicators of compromise_ (IOC) indicate associated network resources which are known to be part of research and attack activities of Shade.

ID | IP address | Hostname | Campaign | Confidence
-- | ---------- | -------- | -------- | ----------
1 | [5.9.116.66](https://vuldb.com/?ip.5.9.116.66) | static.66.116.9.5.clients.your-server.de | - | High
2 | [5.9.158.75](https://vuldb.com/?ip.5.9.158.75) | static.75.158.9.5.clients.your-server.de | - | High
3 | [13.107.21.200](https://vuldb.com/?ip.13.107.21.200) | - | - | High
4 | [23.6.22.189](https://vuldb.com/?ip.23.6.22.189) | a23-6-22-189.deploy.static.akamaitechnologies.com | - | High
5 | [37.157.254.113](https://vuldb.com/?ip.37.157.254.113) | rs004106.root.server-hosting.expert | - | High
6 | [46.105.57.169](https://vuldb.com/?ip.46.105.57.169) | cluster020.hosting.ovh.net | - | High
7 | [46.166.182.20](https://vuldb.com/?ip.46.166.182.20) | - | - | High
8 | [47.101.49.13](https://vuldb.com/?ip.47.101.49.13) | - | - | High
9 | [51.68.204.139](https://vuldb.com/?ip.51.68.204.139) | ns3127231.ip-51-68-204.eu | - | High
10 | [51.68.206.28](https://vuldb.com/?ip.51.68.206.28) | ns3128207.ip-51-68-206.eu | - | High
11 | [62.151.180.62](https://vuldb.com/?ip.62.151.180.62) | mx18062.brandengager.info | - | High
12 | ... | ... | ... | ...

There are 46 more IOC items available. Please use our online service to access the data.

## TTP - Tactics, Techniques, Procedures

_Tactics, techniques, and procedures_ (TTP) summarize the suspected MITRE ATT&CK techniques used by _Shade_. This data is unique as it uses our predictive model for actor profiling.

ID | Technique | Weakness | Description | Confidence
-- | --------- | -------- | ----------- | ----------
1 | T1059.007 | CWE-79, CWE-80 | Cross Site Scripting | High
2 | T1068 | CWE-264, CWE-274, CWE-284 | Execution with Unnecessary Privileges | High
3 | T1110.001 | CWE-307, CWE-798 | Improper Restriction of Excessive Authentication Attempts | High
4 | ... | ... | ... | ...

There are 10 more TTP items available. Please use our online service to access the data.

## IOA - Indicator of Attack

These _indicators of attack_ (IOA) list the potential fragments used for technical activities like reconnaissance, exploitation, privilege escalation, and exfiltration by Shade. This data is unique as it uses our predictive model for actor profiling.

ID | Type | Indicator | Confidence
-- | ---- | --------- | ----------
1 | File | `%SYSTEMDRIVE%\totalcmd\TOTALCMD64.EXE` | High
2 | File | `//WEB-INF` | Medium
3 | File | `/acms/admin/?page=transactions/manage_transaction` | High
4 | File | `/admin/` | Low
5 | File | `/admin/index.php?id=themes&action=edit_template&filename=blog` | High
6 | File | `/admin/siteoptions.php&action=displaygoal&value=1&roleid=1` | High
7 | File | `/app/controller/Books.php` | High
8 | File | `/auth/v1/sso/config/` | High
9 | File | `/cdsms/classes/Master.php?f=delete_enrollment` | High
10 | File | `/cgi-bin/login.cgi` | High
11 | File | `/cgi/networkDiag.cgi` | High
12 | File | `/ctpms/admin/?page=applications/view_application` | High
13 | File | `/dev/cedar_dev` | High
14 | File | `/dev/ion` | Medium
15 | File | `/etc/hosts` | Medium
16 | File | `/etc/passwd` | Medium
17 | File | `/exponent_constants.php` | High
18 | File | `/gena.cgi` | Medium
19 | File | `/GetCopiedFile` | High
20 | File | `/goform/SetStaticRouteCfg` | High
21 | File | `/include/chart_generator.php` | High
22 | File | `/manager/files` | High
23 | File | `/mtms/admin/?page=transaction/send` | High
24 | File | `/nova/bin/detnet` | High
25 | File | `/nova/bin/igmp-proxy` | High
26 | File | `/nova/bin/lcdstat` | High
27 | File | `/pineapple/ui` | High
28 | File | `/preauth` | Medium
29 | File | `/proc/net/snmp` | High
30 | File | `/ram/pckg/advanced-tools/nova/bin/netwatch` | High
31 | ... | ... | ...

There are 262 more IOA items available (file, library, argument, input value, pattern, network port). Please use our online service to access the data.

## References

The following list contains _external sources_ which discuss the actor and the associated activities:

* https://blog.talosintelligence.com/2019/09/threat-roundup-0906-0913.html
* https://blog.talosintelligence.com/2019/09/threat-roundup-0920-0927.html
* https://blog.talosintelligence.com/2019/11/threat-roundup-1025-1101.html

## Literature

The following _articles_ explain our unique predictive cyber threat intelligence:

* [VulDB Cyber Threat Intelligence Documentation](https://vuldb.com/?kb.cti)
* [Cyber Threat Intelligence - Early Anticipation of Attacks](https://www.scip.ch/en/?labs.20201022)

## License

(c) [1997-2022](https://vuldb.com/?kb.changelog) by [vuldb.com](https://vuldb.com/?kb.about). All data on this page is shared under the license [CC BY-NC-SA 4.0](https://creativecommons.org/licenses/by-nc-sa/4.0/). Questions? Check the [FAQ](https://vuldb.com/?kb.faq), read the [documentation](https://vuldb.com/?kb) or [contact us](https://vuldb.com/?contact)!
