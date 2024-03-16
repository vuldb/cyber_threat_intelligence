# Rhysida - Cyber Threat Intelligence

These _indicators_ were reported, collected, and generated during the [VulDB CTI analysis](https://vuldb.com/?kb.cti) of the actor known as [Rhysida](https://vuldb.com/?actor.rhysida). The _activity monitoring_ correlates data from social media, forums, chat rooms, and darknet markets. It helps to determine associated actors, specific activities, expected intentions, emerging research, and ongoing attacks. Our unique _predictive model_ uses _big data_ to forecast activities and their characteristics.

_Live data_ and more _analysis capabilities_ are available at [https://vuldb.com/?actor.rhysida](https://vuldb.com/?actor.rhysida)

## Countries

These _countries_ are directly (e.g. origin of attacks) or indirectly (e.g. access by proxy) associated with Rhysida:

* [DE](https://vuldb.com/?country.de)
* [US](https://vuldb.com/?country.us)
* [GB](https://vuldb.com/?country.gb)
* ...

There are 14 more country items available. Please use our online service to access the data.

## IOC - Indicator of Compromise

These _indicators of compromise_ (IOC) indicate associated network resources which are known to be part of research and attack activities of Rhysida.

ID | IP address | Hostname | Campaign | Confidence
-- | ---------- | -------- | -------- | ----------
1 | [5.39.222.67](https://vuldb.com/?ip.5.39.222.67) | - | - | High
2 | [5.161.150.40](https://vuldb.com/?ip.5.161.150.40) | static.40.150.161.5.clients.your-server.de | - | High
3 | [5.226.141.196](https://vuldb.com/?ip.5.226.141.196) | 196.141.226.5.baremetal.zare.com | - | High
4 | [5.226.141.198](https://vuldb.com/?ip.5.226.141.198) | 198.141.226.5.baremetal.zare.com | - | High
5 | [5.255.99.59](https://vuldb.com/?ip.5.255.99.59) | - | - | High
6 | [5.255.100.101](https://vuldb.com/?ip.5.255.100.101) | - | - | High
7 | [5.255.101.30](https://vuldb.com/?ip.5.255.101.30) | - | - | High
8 | [5.255.103.7](https://vuldb.com/?ip.5.255.103.7) | - | - | High
9 | [5.255.103.142](https://vuldb.com/?ip.5.255.103.142) | - | - | High
10 | [5.255.104.237](https://vuldb.com/?ip.5.255.104.237) | - | - | High
11 | ... | ... | ... | ...

There are 40 more IOC items available. Please use our online service to access the data.

## TTP - Tactics, Techniques, Procedures

_Tactics, techniques, and procedures_ (TTP) summarize the suspected MITRE ATT&CK techniques used by _Rhysida_. This data is unique as it uses our predictive model for actor profiling.

ID | Technique | Weakness | Description | Confidence
-- | --------- | -------- | ----------- | ----------
1 | T1006 | CWE-21, CWE-22, CWE-23, CWE-36, CWE-37, CWE-425 | Path Traversal | High
2 | T1040 | CWE-319 | Authentication Bypass by Capture-replay | High
3 | T1055 | CWE-74 | Injection | High
4 | T1059 | CWE-88, CWE-94, CWE-1321 | Argument Injection | High
5 | T1059.007 | CWE-79, CWE-80 | Cross Site Scripting | High
6 | T1068 | CWE-250, CWE-264, CWE-269, CWE-284 | Execution with Unnecessary Privileges | High
7 | ... | ... | ... | ...

There are 23 more TTP items available. Please use our online service to access the data.

## IOA - Indicator of Attack

These _indicators of attack_ (IOA) list the potential fragments used for technical activities like reconnaissance, exploitation, privilege escalation, and exfiltration by Rhysida. This data is unique as it uses our predictive model for actor profiling.

ID | Type | Indicator | Confidence
-- | ---- | --------- | ----------
1 | File | `.rhosts` | Low
2 | File | `/+CSCOE+/logon.html` | High
3 | File | `/.vnc/sesman_${username}_passwd` | High
4 | File | `/?r=email/api/mark&op=delFromSend` | High
5 | File | `/admin/action/edit_chicken.php` | High
6 | File | `/admin/action/update-deworm.php` | High
7 | File | `/admin/invoice.php` | High
8 | File | `/admin/maintenance/view_designation.php` | High
9 | File | `/admin/pages/edit_chicken.php` | High
10 | File | `/admin/update-clients.php` | High
11 | File | `/api/baskets/{name}` | High
12 | File | `/api/plugin/uninstall` | High
13 | File | `/api2/html/` | Medium
14 | File | `/app/Http/Controllers/ImageController.php` | High
15 | File | `/application/index/controller/File.php` | High
16 | File | `/application/index/controller/Icon.php` | High
17 | File | `/application/index/controller/Screen.php` | High
18 | File | `/application/websocket/controller/Setting.php` | High
19 | File | `/Applications/Utilities/Terminal` | High
20 | File | `/Attachment/fromImageUrl` | High
21 | File | `/b2b-supermarket/shopping-cart` | High
22 | File | `/baseOpLog.do` | High
23 | File | `/bin/boa` | Medium
24 | File | `/cgi-bin/cstecgi.cgi` | High
25 | File | `/cgi-bin/cstecgi.cgi?action=login` | High
26 | File | `/cms/category/list` | High
27 | File | `/config.cgi?webmin` | High
28 | File | `/edit.php` | Medium
29 | File | `/edoc/doctor/patient.php` | High
30 | File | `/etc/passwd` | Medium
31 | File | `/filemanager/php/connector.php` | High
32 | File | `/Forms/tools_test_1` | High
33 | File | `/forum/away.php` | High
34 | File | `/forum/PostPrivateMessage` | High
35 | File | `/general/search.php?searchtype=simple` | High
36 | File | `/goform/setSnmpInfo` | High
37 | File | `/goform/WifiBasicSet` | High
38 | File | `/HNAP1` | Low
39 | File | `/home/cavesConsole` | High
40 | File | `/irj/portal/` | Medium
41 | File | `/log/download.php` | High
42 | File | `/login` | Low
43 | File | `/mgm_dev_reboot.asp` | High
44 | File | `/opt/tplink/EAPController/lib/eap-web-3.2.6.jar` | High
45 | File | `/param.file.tgz` | High
46 | File | `/patient/appointment.php` | High
47 | ... | ... | ...

There are 410 more IOA items available (file, library, argument, input value, pattern, network port). Please use our online service to access the data.

## References

The following list contains _external sources_ which discuss the actor and the associated activities:

* https://github.com/prodaft/malware-ioc/tree/master/ViceSociety
* https://research.checkpoint.com/2023/the-rhysida-ransomware-activity-analysis-and-ties-to-vice-society/
* https://www.cisa.gov/news-events/cybersecurity-advisories/aa23-319a

## Literature

The following _articles_ explain our unique predictive cyber threat intelligence:

* [VulDB Cyber Threat Intelligence Documentation](https://vuldb.com/?kb.cti)
* [Cyber Threat Intelligence - Early Anticipation of Attacks](https://www.scip.ch/en/?labs.20201022)

## License

(c) [1997-2024](https://vuldb.com/?kb.changelog) by [vuldb.com](https://vuldb.com/?kb.about). All data on this page is shared under the license [CC BY-NC-SA 4.0](https://creativecommons.org/licenses/by-nc-sa/4.0/). Questions? Check the [FAQ](https://vuldb.com/?kb.faq), read the [documentation](https://vuldb.com/?kb) or [contact us](https://vuldb.com/?contact)!
