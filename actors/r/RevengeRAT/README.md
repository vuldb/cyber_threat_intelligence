# RevengeRAT - Cyber Threat Intelligence

These _indicators_ were reported, collected, and generated during the [VulDB CTI analysis](https://vuldb.com/?kb.cti) of the actor known as [RevengeRAT](https://vuldb.com/?actor.revengerat). The _activity monitoring_ correlates data from social media, forums, chat rooms, and darknet markets. It helps to determine associated actors, specific activities, expected intentions, emerging research, and ongoing attacks. Our unique _predictive model_ uses _big data_ to forecast activities and their characteristics.

_Live data_ and more _analysis capabilities_ are available at [https://vuldb.com/?actor.revengerat](https://vuldb.com/?actor.revengerat)

## Countries

These _countries_ are directly (e.g. origin of attacks) or indirectly (e.g. access by proxy) associated with RevengeRAT:

* [CN](https://vuldb.com/?country.cn)
* [US](https://vuldb.com/?country.us)
* [VN](https://vuldb.com/?country.vn)
* ...

There are 14 more country items available. Please use our online service to access the data.

## IOC - Indicator of Compromise

These _indicators of compromise_ (IOC) indicate associated network resources which are known to be part of research and attack activities of RevengeRAT.

ID | IP address | Hostname | Campaign | Confidence
-- | ---------- | -------- | -------- | ----------
1 | [6.43.51.17](https://vuldb.com/?ip.6.43.51.17) | - | - | High
2 | [10.0.2.15](https://vuldb.com/?ip.10.0.2.15) | - | - | High
3 | [38.132.101.45](https://vuldb.com/?ip.38.132.101.45) | - | - | High
4 | [45.147.230.231](https://vuldb.com/?ip.45.147.230.231) | - | - | High
5 | ... | ... | ... | ...

There are 14 more IOC items available. Please use our online service to access the data.

## TTP - Tactics, Techniques, Procedures

_Tactics, techniques, and procedures_ (TTP) summarize the suspected MITRE ATT&CK techniques used by _RevengeRAT_. This data is unique as it uses our predictive model for actor profiling.

ID | Technique | Weakness | Description | Confidence
-- | --------- | -------- | ----------- | ----------
1 | T1006 | CWE-21, CWE-22, CWE-23, CWE-29, CWE-425 | Path Traversal | High
2 | T1040 | CWE-319 | Authentication Bypass by Capture-replay | High
3 | T1055 | CWE-74 | Improper Neutralization of Data within XPath Expressions | High
4 | T1059 | CWE-94 | Argument Injection | High
5 | T1059.007 | CWE-79, CWE-80 | Cross Site Scripting | High
6 | ... | ... | ... | ...

There are 21 more TTP items available. Please use our online service to access the data.

## IOA - Indicator of Attack

These _indicators of attack_ (IOA) list the potential fragments used for technical activities like reconnaissance, exploitation, privilege escalation, and exfiltration by RevengeRAT. This data is unique as it uses our predictive model for actor profiling.

ID | Type | Indicator | Confidence
-- | ---- | --------- | ----------
1 | File | `/admin/admin_widgets.php?action=remove/widget=Statistics` | High
2 | File | `/admin/ajax.php?action=login` | High
3 | File | `/admin/forgot-password.php` | High
4 | File | `/admin/index.php?r=banner%2Fbanner-create` | High
5 | File | `/admin/index2.html` | High
6 | File | `/admin/list_ipAddressPolicy.php` | High
7 | File | `/adminPage/conf/reload` | High
8 | File | `/api/runscript` | High
9 | File | `/api/snapshots/` | High
10 | File | `/api/v1/snapshots` | High
11 | File | `/api/v2/maps` | Medium
12 | File | `/apply/index.php` | High
13 | File | `/candidate/index.php` | High
14 | File | `/cgi-bin/nas_sharing.cgi` | High
15 | File | `/cgi-bin/system_mgr.cgi` | High
16 | File | `/cgi-bin/wlogin.cgi` | High
17 | File | `/cgi/cpaddons_report.pl` | High
18 | File | `/classes/SystemSettings.php?f=update_settings` | High
19 | File | `/common/dict/list` | High
20 | File | `/debug/pprof` | Medium
21 | File | `/device.rsp?opt=sys&cmd=___S_O_S_T_R_E_A_MAX___` | High
22 | File | `/endpoint/add-calorie.php` | High
23 | File | `/etc/init.d/update_notifications.sh` | High
24 | File | `/foms/routers/place-order.php` | High
25 | File | `/forum/away.php` | High
26 | File | `/goform/DhcpListClient` | High
27 | File | `/goform/SetNetControlList` | High
28 | File | `/hrm/leaverequest.php` | High
29 | File | `/index.php` | Medium
30 | File | `/index/ajax/lang` | High
31 | File | `/install/` | Medium
32 | File | `/Interface/DevManage/VM.php` | High
33 | File | `/main/webservices/additional_webservices.php` | High
34 | File | `/music/ajax.php?action=save_music` | High
35 | File | `/ndmComponents.js` | High
36 | File | `/net/bluetooth/rfcomm/core.C` | High
37 | File | `/PC/WebService.asmx` | High
38 | File | `/pdf` | Low
39 | File | `/queue/join` | Medium
40 | File | `/register.php` | High
41 | File | `/registrar/` | Medium
42 | File | `/remote/put_file` | High
43 | File | `/routers/add-ticket.php` | High
44 | File | `/smsa/add_class_submit.php` | High
45 | File | `/smsa/admin_login.php` | High
46 | ... | ... | ...

There are 398 more IOA items available (file, library, argument, input value, pattern, network port). Please use our online service to access the data.

## References

The following list contains _external sources_ which discuss the actor and the associated activities:

* https://1275.ru/ioc/149/revengerat-iocs/
* https://blog.talosintelligence.com/2019/07/threat-roundup-0628-0705.html
* https://blog.talosintelligence.com/2019/08/rat-ratatouille-revrat-orcus.html
* https://blog.talosintelligence.com/threat-roundup-0616-0623-2/
* https://www.fortinet.com/blog/threat-research/malware-analysis-revenge-rat-sample.html
* https://www.proofpoint.com/us/blog/threat-insight/reservations-requested-ta558-targets-hospitality-and-travel

## Literature

The following _articles_ explain our unique predictive cyber threat intelligence:

* [VulDB Cyber Threat Intelligence Documentation](https://vuldb.com/?kb.cti)
* [Cyber Threat Intelligence - Early Anticipation of Attacks](https://www.scip.ch/en/?labs.20201022)

## License

(c) [1997-2024](https://vuldb.com/?kb.changelog) by [vuldb.com](https://vuldb.com/?kb.about). All data on this page is shared under the license [CC BY-NC-SA 4.0](https://creativecommons.org/licenses/by-nc-sa/4.0/). Questions? Check the [FAQ](https://vuldb.com/?kb.faq), read the [documentation](https://vuldb.com/?kb) or [contact us](https://vuldb.com/?contact)!
