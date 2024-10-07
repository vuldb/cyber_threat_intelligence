# H0lyGh0st - Cyber Threat Intelligence

These _indicators_ were reported, collected, and generated during the [VulDB CTI analysis](https://vuldb.com/?kb.cti) of the campaign known as _H0lyGh0st_. The _activity monitoring_ correlates data from social media, forums, chat rooms, and darknet markets. It helps to determine associated actors, specific activities, expected intentions, emerging research, and ongoing attacks. Our unique _predictive model_ uses _big data_ to forecast activities and their characteristics.

_Live data_ and more _analysis capabilities_ are available at [https://vuldb.com/?actor](https://vuldb.com/?actor)

## Countries

These _countries_ are directly (e.g. origin of attacks) or indirectly (e.g. access by proxy) associated with H0lyGh0st:

* [CN](https://vuldb.com/?country.cn)
* [US](https://vuldb.com/?country.us)
* [VN](https://vuldb.com/?country.vn)
* ...

There are 14 more country items available. Please use our online service to access the data.

## Actors

These _actors_ are associated with H0lyGh0st or other actors linked to the campaign.

ID | Actor | Confidence
-- | ----- | ----------
1 | [DEV-0530](https://vuldb.com/?actor.dev-0530) | High
2 | [H0lyGh0st](https://vuldb.com/?actor.h0lygh0st) | High
3 | [North Korea Unknown](https://vuldb.com/?actor.north_korea_unknown) | High

## IOC - Indicator of Compromise

These _indicators of compromise_ (IOC) indicate associated network resources which are known to be part of research and attack activities of H0lyGh0st.

ID | IP address | Hostname | Actor | Confidence
-- | ---------- | -------- | ----- | ----------
1 | [127.0.0.1](https://vuldb.com/?ip.127.0.0.1) | localhost | [H0lyGh0st](https://vuldb.com/?actor.h0lygh0st) | High
2 | [193.56.29.123](https://vuldb.com/?ip.193.56.29.123) | - | [North Korea Unknown](https://vuldb.com/?actor.north_korea_unknown) | High

## TTP - Tactics, Techniques, Procedures

_Tactics, techniques, and procedures_ (TTP) summarize the suspected MITRE ATT&CK techniques used within H0lyGh0st. This data is unique as it uses our predictive model for actor profiling.

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

These _indicators of attack_ (IOA) list the potential fragments used for technical activities like reconnaissance, exploitation, privilege escalation, and exfiltration during H0lyGh0st. This data is unique as it uses our predictive model for actor profiling.

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
27 | File | `/hrm/leaverequest.php` | High
28 | File | `/index.php` | Medium
29 | File | `/index/ajax/lang` | High
30 | File | `/install/` | Medium
31 | File | `/Interface/DevManage/VM.php` | High
32 | File | `/main/webservices/additional_webservices.php` | High
33 | File | `/music/ajax.php?action=save_music` | High
34 | File | `/ndmComponents.js` | High
35 | File | `/net/bluetooth/rfcomm/core.C` | High
36 | File | `/PC/WebService.asmx` | High
37 | File | `/pdf` | Low
38 | File | `/queue/join` | Medium
39 | File | `/register.php` | High
40 | File | `/registrar/` | Medium
41 | File | `/remote/put_file` | High
42 | File | `/routers/add-ticket.php` | High
43 | File | `/smsa/add_class_submit.php` | High
44 | File | `/smsa/admin_login.php` | High
45 | File | `/spip.php` | Medium
46 | ... | ... | ...

There are 398 more IOA items available (file, library, argument, input value, pattern, network port). Please use our online service to access the data.

## References

The following list contains _external sources_ which discuss the campaign and the associated activities:

* https://community.blueliv.com/#!/s/62d1143282df41552632f957
* https://www.microsoft.com/en-us/security/blog/2022/07/14/north-korean-threat-actor-targets-small-and-midsize-businesses-with-h0lygh0st-ransomware/
* https://www.microsoft.com/security/blog/2022/07/14/north-korean-threat-actor-targets-small-and-midsize-businesses-with-h0lygh0st-ransomware/

## Literature

The following _articles_ explain our unique predictive cyber threat intelligence:

* [VulDB Cyber Threat Intelligence Documentation](https://vuldb.com/?kb.cti)
* [Cyber Threat Intelligence - Early Anticipation of Attacks](https://www.scip.ch/en/?labs.20201022)

## License

(c) [1997-2024](https://vuldb.com/?kb.changelog) by [vuldb.com](https://vuldb.com/?kb.about). All data on this page is shared under the license [CC BY-NC-SA 4.0](https://creativecommons.org/licenses/by-nc-sa/4.0/). Questions? Check the [FAQ](https://vuldb.com/?kb.faq), read the [documentation](https://vuldb.com/?kb) or [contact us](https://vuldb.com/?contact)!
