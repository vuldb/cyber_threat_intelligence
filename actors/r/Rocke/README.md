# Rocke - Cyber Threat Intelligence

These _indicators_ were reported, collected, and generated during the [VulDB CTI analysis](https://vuldb.com/?kb.cti) of the actor known as [Rocke](https://vuldb.com/?actor.rocke). The _activity monitoring_ correlates data from social media, forums, chat rooms, and darknet markets. It helps to determine associated actors, specific activities, expected intentions, emerging research, and ongoing attacks. Our unique _predictive model_ uses _big data_ to forecast activities and their characteristics.

_Live data_ and more _analysis capabilities_ are available at [https://vuldb.com/?actor.rocke](https://vuldb.com/?actor.rocke)

## Countries

These _countries_ are directly (e.g. origin of attacks) or indirectly (e.g. access by proxy) associated with Rocke:

* [CN](https://vuldb.com/?country.cn)
* [US](https://vuldb.com/?country.us)

## IOC - Indicator of Compromise

These _indicators of compromise_ (IOC) indicate associated network resources which are known to be part of research and attack activities of Rocke.

ID | IP address | Hostname | Campaign | Confidence
-- | ---------- | -------- | -------- | ----------
1 | [23.234.4.151](https://vuldb.com/?ip.23.234.4.151) | - | - | High
2 | [23.234.4.153](https://vuldb.com/?ip.23.234.4.153) | - | - | High
3 | [27.193.180.224](https://vuldb.com/?ip.27.193.180.224) | - | - | High
4 | [27.210.170.197](https://vuldb.com/?ip.27.210.170.197) | - | - | High
5 | [27.221.28.231](https://vuldb.com/?ip.27.221.28.231) | - | - | High
6 | [27.221.54.252](https://vuldb.com/?ip.27.221.54.252) | - | - | High
7 | [36.103.236.221](https://vuldb.com/?ip.36.103.236.221) | - | - | High
8 | [36.103.247.121](https://vuldb.com/?ip.36.103.247.121) | - | - | High
9 | [36.248.26.205](https://vuldb.com/?ip.36.248.26.205) | - | - | High
10 | [42.56.76.104](https://vuldb.com/?ip.42.56.76.104) | - | - | High
11 | [42.202.141.230](https://vuldb.com/?ip.42.202.141.230) | - | - | High
12 | [42.236.125.84](https://vuldb.com/?ip.42.236.125.84) | hn.kd.ny.adsl | - | High
13 | [43.224.225.220](https://vuldb.com/?ip.43.224.225.220) | - | - | High
14 | [43.242.166.88](https://vuldb.com/?ip.43.242.166.88) | - | - | High
15 | [52.167.219.168](https://vuldb.com/?ip.52.167.219.168) | - | - | High
16 | [58.215.145.137](https://vuldb.com/?ip.58.215.145.137) | - | - | High
17 | [58.216.107.77](https://vuldb.com/?ip.58.216.107.77) | - | - | High
18 | ... | ... | ... | ...

There are 70 more IOC items available. Please use our online service to access the data.

## TTP - Tactics, Techniques, Procedures

_Tactics, techniques, and procedures_ (TTP) summarize the suspected MITRE ATT&CK techniques used by _Rocke_. This data is unique as it uses our predictive model for actor profiling.

ID | Technique | Weakness | Description | Confidence
-- | --------- | -------- | ----------- | ----------
1 | T1006 | CWE-21, CWE-22, CWE-23 | Path Traversal | High
2 | T1055 | CWE-74 | Improper Neutralization of Data within XPath Expressions | High
3 | T1059 | CWE-88, CWE-94, CWE-1321 | Argument Injection | High
4 | T1059.007 | CWE-79, CWE-80 | Cross Site Scripting | High
5 | ... | ... | ... | ...

There are 17 more TTP items available. Please use our online service to access the data.

## IOA - Indicator of Attack

These _indicators of attack_ (IOA) list the potential fragments used for technical activities like reconnaissance, exploitation, privilege escalation, and exfiltration by Rocke. This data is unique as it uses our predictive model for actor profiling.

ID | Type | Indicator | Confidence
-- | ---- | --------- | ----------
1 | File | `/admin.php?p=/Area/index#tab=t2` | High
2 | File | `/admin/?setting-base.htm` | High
3 | File | `/admin/index2.html` | High
4 | File | `/admin/sql` | Medium
5 | File | `/admin/students.php` | High
6 | File | `/admin/students/manage.php` | High
7 | File | `/admin/system.html` | High
8 | File | `/adminPage/conf/reload` | High
9 | File | `/adminPage/www/addOver` | High
10 | File | `/application/index/controller/Icon.php` | High
11 | File | `/application/index/controller/Screen.php` | High
12 | File | `/bin/ate` | Medium
13 | File | `/boaform/device_reset.cgi` | High
14 | File | `/cgi-bin/cstecgi.cgi` | High
15 | File | `/dataSet/testTransform;swagger-ui` | High
16 | File | `/dayrui/Fcms/View/system_log.html` | High
17 | File | `/dayrui/My/View/main.html` | High
18 | File | `/goform/execCommand` | High
19 | File | `/goform/goform_get_cmd_process` | High
20 | File | `/goform/SetRebootTimer` | High
21 | File | `/goform/WriteFacMac` | High
22 | File | `/index.php` | Medium
23 | File | `/index.php/admin` | High
24 | File | `/index/ajax/lang` | High
25 | ... | ... | ...

There are 209 more IOA items available (file, library, argument, input value, pattern, network port). Please use our online service to access the data.

## References

The following list contains _external sources_ which discuss the actor and the associated activities:

* https://blog.talosintelligence.com/2018/08/rocke-champion-of-monero-miners.html
* https://blog.talosintelligence.com/2018/12/cryptomining-campaigns-2018.html
* https://unit42.paloaltonetworks.com/malware-used-by-rocke-group-evolves-to-evade-detection-by-cloud-security-products/
* https://unit42.paloaltonetworks.com/rockein-the-netflow/
* https://www.anomali.com/blog/rocke-evolves-its-arsenal-with-a-new-malware-family-written-in-golang

## Literature

The following _articles_ explain our unique predictive cyber threat intelligence:

* [VulDB Cyber Threat Intelligence Documentation](https://vuldb.com/?kb.cti)
* [Cyber Threat Intelligence - Early Anticipation of Attacks](https://www.scip.ch/en/?labs.20201022)

## License

(c) [1997-2024](https://vuldb.com/?kb.changelog) by [vuldb.com](https://vuldb.com/?kb.about). All data on this page is shared under the license [CC BY-NC-SA 4.0](https://creativecommons.org/licenses/by-nc-sa/4.0/). Questions? Check the [FAQ](https://vuldb.com/?kb.faq), read the [documentation](https://vuldb.com/?kb) or [contact us](https://vuldb.com/?contact)!
