# Squirrelwaffle - Cyber Threat Intelligence

These _indicators_ were reported, collected, and generated during the [VulDB CTI analysis](https://vuldb.com/?kb.cti) of the actor known as [Squirrelwaffle](https://vuldb.com/?actor.squirrelwaffle). The _activity monitoring_ correlates data from social media, forums, chat rooms, and darknet markets. It helps to determine associated actors, specific activities, expected intentions, emerging research, and ongoing attacks. Our unique _predictive model_ uses _big data_ to forecast activities and their characteristics.

_Live data_ and more _analysis capabilities_ are available at [https://vuldb.com/?actor.squirrelwaffle](https://vuldb.com/?actor.squirrelwaffle)

## Campaigns

The following _campaigns_ are known and can be associated with Squirrelwaffle:

* ProxyShell/ProxyLogon

## Countries

These _countries_ are directly (e.g. origin of attacks) or indirectly (e.g. access by proxy) associated with Squirrelwaffle:

* [BR](https://vuldb.com/?country.br)
* [US](https://vuldb.com/?country.us)
* [ES](https://vuldb.com/?country.es)
* ...

There are 11 more country items available. Please use our online service to access the data.

## IOC - Indicator of Compromise

These _indicators of compromise_ (IOC) indicate associated network resources which are known to be part of research and attack activities of Squirrelwaffle.

ID | IP address | Hostname | Campaign | Confidence
-- | ---------- | -------- | -------- | ----------
1 | [23.111.163.242](https://vuldb.com/?ip.23.111.163.242) | 23-111-163-242.static.hvvc.us | ProxyShell/ProxyLogon | High
2 | [24.55.112.61](https://vuldb.com/?ip.24.55.112.61) | dynamic.libertypr.net | - | High
3 | [24.229.150.54](https://vuldb.com/?ip.24.229.150.54) | 24.229.150.54.cmts-static.sm.ptd.net | ProxyShell/ProxyLogon | High
4 | [45.46.53.140](https://vuldb.com/?ip.45.46.53.140) | cpe-45-46-53-140.maine.res.rr.com | - | High
5 | [47.22.148.6](https://vuldb.com/?ip.47.22.148.6) | ool-2f169406.static.optonline.net | - | High
6 | ... | ... | ... | ...

There are 20 more IOC items available. Please use our online service to access the data.

## TTP - Tactics, Techniques, Procedures

_Tactics, techniques, and procedures_ (TTP) summarize the suspected MITRE ATT&CK techniques used by _Squirrelwaffle_. This data is unique as it uses our predictive model for actor profiling.

ID | Technique | Weakness | Description | Confidence
-- | --------- | -------- | ----------- | ----------
1 | T1006 | CWE-21, CWE-22, CWE-23, CWE-24, CWE-36 | Path Traversal | High
2 | T1040 | CWE-319 | Authentication Bypass by Capture-replay | High
3 | T1055 | CWE-74 | Improper Neutralization of Data within XPath Expressions | High
4 | T1059 | CWE-94 | Argument Injection | High
5 | T1059.007 | CWE-79, CWE-80 | Basic Cross Site Scripting | High
6 | ... | ... | ... | ...

There are 20 more TTP items available. Please use our online service to access the data.

## IOA - Indicator of Attack

These _indicators of attack_ (IOA) list the potential fragments used for technical activities like reconnaissance, exploitation, privilege escalation, and exfiltration by Squirrelwaffle. This data is unique as it uses our predictive model for actor profiling.

ID | Type | Indicator | Confidence
-- | ---- | --------- | ----------
1 | File | `.procmailrc` | Medium
2 | File | `/admin/` | Low
3 | File | `/admin/add_course.php` | High
4 | File | `/admin/category_row.php` | High
5 | File | `/admin/changeimage2.php` | High
6 | File | `/admin/gallery.php` | High
7 | File | `/admin/mechanics/manage_mechanic.php` | High
8 | File | `/admin/sign/out` | High
9 | File | `/admin/students/manage_academic.php` | High
10 | File | `/admin/suppliercontroller.php` | High
11 | File | `/admin/update_s6.php` | High
12 | File | `/ajax.php?Ajax=GetModal_Sensor_Graph` | High
13 | File | `/api/GylOperator/LoadData` | High
14 | File | `/api/public/signup` | High
15 | File | `/boafrm/formFilter` | High
16 | File | `/boafrm/formMapDel` | High
17 | File | `/boafrm/formNtp` | High
18 | File | `/bsenordering/index.php` | High
19 | File | `/cgi-bin/cstecgi.cgi` | High
20 | File | `/cgi-bin/ExportALLSettings.sh` | High
21 | File | `/cgi-bin/ExportAllSettings.sh` | High
22 | File | `/cgi-bin/mainfunction.cgi/apmcfgupload` | High
23 | File | `/cgi-bin/sessions/get-temp-file` | High
24 | File | `/classes/Master.php?f=delete_img` | High
25 | File | `/config/getuser` | High
26 | File | `/contrib/cssgen.php` | High
27 | File | `/core/config-revisions` | High
28 | File | `/detail.php` | Medium
29 | File | `/Doctor/chat.php` | High
30 | File | `/ebics-server/ebics.aspx` | High
31 | File | `/employeeview.php` | High
32 | File | `/endpoint/add-computer.php` | High
33 | File | `/etc/passwd` | Medium
34 | File | `/file/cancel.php` | High
35 | File | `/generateController.do?dogenerate` | High
36 | File | `/goform/formSetMuti` | High
37 | File | `/goform/form_portforwarding` | High
38 | File | `/goform/telnet` | High
39 | File | `/goform/WifiWpsStart` | High
40 | File | `/home/kickPlayer` | High
41 | File | `/include/chart_generator.php` | High
42 | ... | ... | ...

There are 358 more IOA items available (file, library, argument, input value, pattern, network port). Please use our online service to access the data.

## References

The following list contains _external sources_ which discuss the actor and the associated activities:

* https://blogs.blackberry.com/en/2021/11/threat-thursday-squirrelwaffle-loader
* https://github.com/executemalware/Malware-IOCs/blob/main/2021-09-28%20Squirrel%20Waffle%20IOCs
* https://www.trendmicro.com/content/dam/trendmicro/global/en/research/21/k/squirrelwaffle-exploits-proxyshell-and-proxylogon-vulnerabilities-in-microsoft-exchange-to-hijack-email-chains/IOCs-squirrelwaffle-exploits-proxyshell-and-proxylogon-to-hijack-email

## Literature

The following _articles_ explain our unique predictive cyber threat intelligence:

* [VulDB Cyber Threat Intelligence Documentation](https://vuldb.com/?kb.cti)
* [Cyber Threat Intelligence - Early Anticipation of Attacks](https://www.scip.ch/en/?labs.20201022)

## License

(c) [1997-2025](https://vuldb.com/?kb.changelog) by [vuldb.com](https://vuldb.com/?kb.about). All data on this page is shared under the license [CC BY-NC-SA 4.0](https://creativecommons.org/licenses/by-nc-sa/4.0/). Questions? Check the [FAQ](https://vuldb.com/?kb.faq), read the [documentation](https://vuldb.com/?kb) or [contact us](https://vuldb.com/?contact)!
