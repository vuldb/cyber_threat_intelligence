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
1 | [5.161.150.40](https://vuldb.com/?ip.5.161.150.40) | static.40.150.161.5.clients.your-server.de | - | High
2 | [5.226.141.196](https://vuldb.com/?ip.5.226.141.196) | 196.141.226.5.baremetal.zare.com | - | High
3 | [5.226.141.198](https://vuldb.com/?ip.5.226.141.198) | 198.141.226.5.baremetal.zare.com | - | High
4 | [5.255.100.101](https://vuldb.com/?ip.5.255.100.101) | - | - | High
5 | [5.255.101.30](https://vuldb.com/?ip.5.255.101.30) | - | - | High
6 | [5.255.103.7](https://vuldb.com/?ip.5.255.103.7) | - | - | High
7 | [5.255.103.142](https://vuldb.com/?ip.5.255.103.142) | - | - | High
8 | [5.255.104.237](https://vuldb.com/?ip.5.255.104.237) | - | - | High
9 | [23.19.58.57](https://vuldb.com/?ip.23.19.58.57) | - | - | High
10 | ... | ... | ... | ...

There are 37 more IOC items available. Please use our online service to access the data.

## TTP - Tactics, Techniques, Procedures

_Tactics, techniques, and procedures_ (TTP) summarize the suspected MITRE ATT&CK techniques used by _Rhysida_. This data is unique as it uses our predictive model for actor profiling.

ID | Technique | Weakness | Description | Confidence
-- | --------- | -------- | ----------- | ----------
1 | T1006 | CWE-21, CWE-22, CWE-23, CWE-36, CWE-37, CWE-425 | Pathname Traversal | High
2 | T1040 | CWE-319 | Authentication Bypass by Capture-replay | High
3 | T1055 | CWE-74 | Injection | High
4 | T1059 | CWE-88, CWE-94, CWE-1321 | Cross Site Scripting | High
5 | T1059.007 | CWE-79, CWE-80 | Cross Site Scripting | High
6 | T1068 | CWE-250, CWE-264, CWE-269, CWE-284 | J2EE Misconfiguration: Weak Access Permissions for EJB Methods | High
7 | ... | ... | ... | ...

There are 23 more TTP items available. Please use our online service to access the data.

## IOA - Indicator of Attack

These _indicators of attack_ (IOA) list the potential fragments used for technical activities like reconnaissance, exploitation, privilege escalation, and exfiltration by Rhysida. This data is unique as it uses our predictive model for actor profiling.

ID | Type | Indicator | Confidence
-- | ---- | --------- | ----------
1 | File | `%PROGRAMFILES%\1E\Client\Tachyon.Performance.Metrics.exe` | High
2 | File | `.rhosts` | Low
3 | File | `/+CSCOE+/logon.html` | High
4 | File | `/.vnc/sesman_${username}_passwd` | High
5 | File | `/admin/maintenance/view_designation.php` | High
6 | File | `/api/baskets/{name}` | High
7 | File | `/api/plugin/uninstall` | High
8 | File | `/api2/html/` | Medium
9 | File | `/Applications/Utilities/Terminal` | High
10 | File | `/baseOpLog.do` | High
11 | File | `/config.cgi?webmin` | High
12 | File | `/Core/Ap4File.cpp` | High
13 | File | `/edoc/doctor/patient.php` | High
14 | File | `/etc/passwd` | Medium
15 | File | `/filemanager/php/connector.php` | High
16 | File | `/Forms/tools_test_1` | High
17 | File | `/forum/away.php` | High
18 | File | `/forum/PostPrivateMessage` | High
19 | File | `/general/search.php?searchtype=simple` | High
20 | File | `/HNAP1` | Low
21 | File | `/home/cavesConsole` | High
22 | File | `/irj/portal/` | Medium
23 | File | `/login` | Low
24 | File | `/mgm_dev_reboot.asp` | High
25 | File | `/opt/tplink/EAPController/lib/eap-web-3.2.6.jar` | High
26 | File | `/param.file.tgz` | High
27 | File | `/patient/appointment.php` | High
28 | File | `/product.php` | Medium
29 | File | `/public/launchNewWindow.jsp` | High
30 | File | `/spip.php` | Medium
31 | File | `/Status/wan_button_action.asp` | High
32 | File | `/sys/user/putRecycleBin` | High
33 | File | `/template/edit` | High
34 | File | `/tmp` | Low
35 | File | `/user/s.php` | Medium
36 | File | `/usr/bin/lua` | Medium
37 | File | `/var/log/drachtio` | High
38 | File | `/wp-json/oembed/1.0/embed?url` | High
39 | File | `?r=recruit/bgchecks/export&checkids=x` | High
40 | File | `?r=weibo/comment/addcomment` | High
41 | File | `adclick.php` | Medium
42 | File | `add-patient.php` | High
43 | ... | ... | ...

There are 368 more IOA items available (file, library, argument, input value, pattern, network port). Please use our online service to access the data.

## References

The following list contains _external sources_ which discuss the actor and the associated activities:

* https://github.com/prodaft/malware-ioc/tree/master/ViceSociety
* https://research.checkpoint.com/2023/the-rhysida-ransomware-activity-analysis-and-ties-to-vice-society/

## Literature

The following _articles_ explain our unique predictive cyber threat intelligence:

* [VulDB Cyber Threat Intelligence Documentation](https://vuldb.com/?kb.cti)
* [Cyber Threat Intelligence - Early Anticipation of Attacks](https://www.scip.ch/en/?labs.20201022)

## License

(c) [1997-2023](https://vuldb.com/?kb.changelog) by [vuldb.com](https://vuldb.com/?kb.about). All data on this page is shared under the license [CC BY-NC-SA 4.0](https://creativecommons.org/licenses/by-nc-sa/4.0/). Questions? Check the [FAQ](https://vuldb.com/?kb.faq), read the [documentation](https://vuldb.com/?kb) or [contact us](https://vuldb.com/?contact)!
