# LookBack - Cyber Threat Intelligence

These _indicators_ were reported, collected, and generated during the [VulDB CTI analysis](https://vuldb.com/?kb.cti) of the campaign known as _LookBack_. The _activity monitoring_ correlates data from social media, forums, chat rooms, and darknet markets. It helps to determine associated actors, specific activities, expected intentions, emerging research, and ongoing attacks. Our unique _predictive model_ uses _big data_ to forecast activities and their characteristics.

_Live data_ and more _analysis capabilities_ are available at [https://vuldb.com/?actor](https://vuldb.com/?actor)

## Countries

These _countries_ are directly (e.g. origin of attacks) or indirectly (e.g. access by proxy) associated with LookBack:

* [CN](https://vuldb.com/?country.cn)
* [US](https://vuldb.com/?country.us)
* [VN](https://vuldb.com/?country.vn)
* ...

There are 15 more country items available. Please use our online service to access the data.

## Actors

These _actors_ are associated with LookBack or other actors linked to the campaign.

ID | Actor | Confidence
-- | ----- | ----------
1 | [Lookback](https://vuldb.com/?actor.lookback) | High
2 | [Witchetty](https://vuldb.com/?actor.witchetty) | High

## IOC - Indicator of Compromise

These _indicators of compromise_ (IOC) indicate associated network resources which are known to be part of research and attack activities of LookBack.

ID | IP address | Hostname | Actor | Confidence
-- | ---------- | -------- | ----- | ----------
1 | [5.252.176.3](https://vuldb.com/?ip.5.252.176.3) | no-rdns.mivocloud.com | [Witchetty](https://vuldb.com/?actor.witchetty) | High
2 | [79.141.168.137](https://vuldb.com/?ip.79.141.168.137) | nceess.com | [Lookback](https://vuldb.com/?actor.lookback) | High
3 | [103.253.41.45](https://vuldb.com/?ip.103.253.41.45) | mail.e-cigs-mart.com | [Lookback](https://vuldb.com/?actor.lookback) | High
4 | ... | ... | ... | ...

There are 1 more IOC items available. Please use our online service to access the data.

## TTP - Tactics, Techniques, Procedures

_Tactics, techniques, and procedures_ (TTP) summarize the suspected MITRE ATT&CK techniques used within LookBack. This data is unique as it uses our predictive model for actor profiling.

ID | Technique | Weakness | Description | Confidence
-- | --------- | -------- | ----------- | ----------
1 | T1006 | CWE-21, CWE-22, CWE-23, CWE-29, CWE-425 | Path Traversal | High
2 | T1040 | CWE-319 | Authentication Bypass by Capture-replay | High
3 | T1055 | CWE-74 | Improper Neutralization of Data within XPath Expressions | High
4 | T1059 | CWE-94 | Argument Injection | High
5 | T1059.007 | CWE-79, CWE-80 | Cross Site Scripting | High
6 | ... | ... | ... | ...

There are 22 more TTP items available. Please use our online service to access the data.

## IOA - Indicator of Attack

These _indicators of attack_ (IOA) list the potential fragments used for technical activities like reconnaissance, exploitation, privilege escalation, and exfiltration during LookBack. This data is unique as it uses our predictive model for actor profiling.

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
14 | File | `/cgi-bin/cstecgi.cgi` | High
15 | File | `/cgi-bin/kerbynet` | High
16 | File | `/cgi-bin/nas_sharing.cgi` | High
17 | File | `/cgi-bin/system_mgr.cgi` | High
18 | File | `/cgi-bin/wlogin.cgi` | High
19 | File | `/classes/SystemSettings.php?f=update_settings` | High
20 | File | `/common/dict/list` | High
21 | File | `/device.rsp?opt=sys&cmd=___S_O_S_T_R_E_A_MAX___` | High
22 | File | `/endpoint/add-calorie.php` | High
23 | File | `/endpoint/add-timesheet.php` | High
24 | File | `/etc/init.d/update_notifications.sh` | High
25 | File | `/foms/routers/place-order.php` | High
26 | File | `/forum/away.php` | High
27 | File | `/geoserver/gwc/rest.html` | High
28 | File | `/goform/DhcpListClient` | High
29 | File | `/hrm/leaverequest.php` | High
30 | File | `/index.php` | Medium
31 | File | `/index/ajax/lang` | High
32 | File | `/install/` | Medium
33 | File | `/Interface/DevManage/VM.php` | High
34 | File | `/logs` | Low
35 | File | `/main/webservices/additional_webservices.php` | High
36 | File | `/music/ajax.php?action=save_music` | High
37 | File | `/ndmComponents.js` | High
38 | File | `/net/bluetooth/rfcomm/core.C` | High
39 | File | `/PC/WebService.asmx` | High
40 | File | `/pdf` | Low
41 | File | `/php/ping.php` | High
42 | File | `/queue/join` | Medium
43 | File | `/register.php` | High
44 | File | `/registrar/` | Medium
45 | File | `/remote/put_file` | High
46 | File | `/routers/add-ticket.php` | High
47 | ... | ... | ...

There are 406 more IOA items available (file, library, argument, input value, pattern, network port). Please use our online service to access the data.

## References

The following list contains _external sources_ which discuss the campaign and the associated activities:

* https://symantec-enterprise-blogs.security.com/blogs/threat-intelligence/witchetty-steganography-espionage
* https://www.proofpoint.com/us/threat-insight/post/lookback-malware-targets-united-states-utilities-sector-phishing-attacks

## Literature

The following _articles_ explain our unique predictive cyber threat intelligence:

* [VulDB Cyber Threat Intelligence Documentation](https://vuldb.com/?kb.cti)
* [Cyber Threat Intelligence - Early Anticipation of Attacks](https://www.scip.ch/en/?labs.20201022)

## License

(c) [1997-2024](https://vuldb.com/?kb.changelog) by [vuldb.com](https://vuldb.com/?kb.about). All data on this page is shared under the license [CC BY-NC-SA 4.0](https://creativecommons.org/licenses/by-nc-sa/4.0/). Questions? Check the [FAQ](https://vuldb.com/?kb.faq), read the [documentation](https://vuldb.com/?kb) or [contact us](https://vuldb.com/?contact)!
