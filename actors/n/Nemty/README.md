# Nemty - Cyber Threat Intelligence

These _indicators_ were reported, collected, and generated during the [VulDB CTI analysis](https://vuldb.com/?kb.cti) of the actor known as [Nemty](https://vuldb.com/?actor.nemty). The _activity monitoring_ correlates data from social media, forums, chat rooms, and darknet markets. It helps to determine associated actors, specific activities, expected intentions, emerging research, and ongoing attacks. Our unique _predictive model_ uses _big data_ to forecast activities and their characteristics.

_Live data_ and more _analysis capabilities_ are available at [https://vuldb.com/?actor.nemty](https://vuldb.com/?actor.nemty)

## Countries

These _countries_ are directly (e.g. origin of attacks) or indirectly (e.g. access by proxy) associated with Nemty:

* [CN](https://vuldb.com/?country.cn)
* [US](https://vuldb.com/?country.us)
* [VN](https://vuldb.com/?country.vn)
* ...

There are 14 more country items available. Please use our online service to access the data.

## IOC - Indicator of Compromise

These _indicators of compromise_ (IOC) indicate associated network resources which are known to be part of research and attack activities of Nemty.

ID | IP address | Hostname | Campaign | Confidence
-- | ---------- | -------- | -------- | ----------
1 | [3.234.181.234](https://vuldb.com/?ip.3.234.181.234) | ec2-3-234-181-234.compute-1.amazonaws.com | - | Medium
2 | [6.43.51.17](https://vuldb.com/?ip.6.43.51.17) | - | - | High
3 | [13.107.42.12](https://vuldb.com/?ip.13.107.42.12) | 1drv.ms | - | High
4 | [23.20.239.12](https://vuldb.com/?ip.23.20.239.12) | ec2-23-20-239-12.compute-1.amazonaws.com | - | Medium
5 | [23.21.50.37](https://vuldb.com/?ip.23.21.50.37) | ec2-23-21-50-37.compute-1.amazonaws.com | - | Medium
6 | [31.220.121.73](https://vuldb.com/?ip.31.220.121.73) | - | - | High
7 | ... | ... | ... | ...

There are 22 more IOC items available. Please use our online service to access the data.

## TTP - Tactics, Techniques, Procedures

_Tactics, techniques, and procedures_ (TTP) summarize the suspected MITRE ATT&CK techniques used by _Nemty_. This data is unique as it uses our predictive model for actor profiling.

ID | Technique | Weakness | Description | Confidence
-- | --------- | -------- | ----------- | ----------
1 | T1006 | CWE-21, CWE-22, CWE-23, CWE-29, CWE-425 | Path Traversal | High
2 | T1040 | CWE-319 | Authentication Bypass by Capture-replay | High
3 | T1055 | CWE-74 | Improper Neutralization of Data within XPath Expressions | High
4 | T1059 | CWE-94 | Argument Injection | High
5 | T1059.007 | CWE-79, CWE-80 | Cross Site Scripting | High
6 | ... | ... | ... | ...

There are 20 more TTP items available. Please use our online service to access the data.

## IOA - Indicator of Attack

These _indicators of attack_ (IOA) list the potential fragments used for technical activities like reconnaissance, exploitation, privilege escalation, and exfiltration by Nemty. This data is unique as it uses our predictive model for actor profiling.

ID | Type | Indicator | Confidence
-- | ---- | --------- | ----------
1 | File | `/admin/` | Low
2 | File | `/admin/admin_user.php` | High
3 | File | `/admin/admin_widgets.php?action=remove/widget=Statistics` | High
4 | File | `/admin/ajax.php?action=login` | High
5 | File | `/admin/forgot-password.php` | High
6 | File | `/admin/index2.html` | High
7 | File | `/admin/list_ipAddressPolicy.php` | High
8 | File | `/adminPage/conf/reload` | High
9 | File | `/api/runscript` | High
10 | File | `/api/snapshots/` | High
11 | File | `/api/v1/snapshots` | High
12 | File | `/api/v2/maps` | Medium
13 | File | `/apply/index.php` | High
14 | File | `/cgi-bin/cstecgi.cgi` | High
15 | File | `/cgi-bin/cstecgi.cgi?action=login` | High
16 | File | `/cgi-bin/cstecgi.cgi?action=login&flag=1` | High
17 | File | `/cgi-bin/nas_sharing.cgi` | High
18 | File | `/cgi-bin/system_mgr.cgi` | High
19 | File | `/cgi-bin/wlogin.cgi` | High
20 | File | `/cgi/cpaddons_report.pl` | High
21 | File | `/classes/SystemSettings.php?f=update_settings` | High
22 | File | `/common/dict/list` | High
23 | File | `/debug/pprof` | Medium
24 | File | `/device.rsp?opt=sys&cmd=___S_O_S_T_R_E_A_MAX___` | High
25 | File | `/endpoint/add-calorie.php` | High
26 | File | `/etc/init.d/update_notifications.sh` | High
27 | File | `/foms/routers/place-order.php` | High
28 | File | `/forum/away.php` | High
29 | File | `/goform/DhcpListClient` | High
30 | File | `/hrm/leaverequest.php` | High
31 | File | `/index.php` | Medium
32 | File | `/index/ajax/lang` | High
33 | File | `/install/` | Medium
34 | File | `/Interface/DevManage/VM.php` | High
35 | File | `/main/webservices/additional_webservices.php` | High
36 | File | `/music/ajax.php?action=save_music` | High
37 | File | `/ndmComponents.js` | High
38 | File | `/net/bluetooth/rfcomm/core.C` | High
39 | File | `/PC/WebService.asmx` | High
40 | File | `/pdf` | Low
41 | File | `/register.php` | High
42 | File | `/registrar/` | Medium
43 | File | `/remote/put_file` | High
44 | File | `/routers/add-ticket.php` | High
45 | File | `/smsa/add_class_submit.php` | High
46 | File | `/smsa/admin_login.php` | High
47 | ... | ... | ...

There are 405 more IOA items available (file, library, argument, input value, pattern, network port). Please use our online service to access the data.

## References

The following list contains _external sources_ which discuss the actor and the associated activities:

* https://blog.talosintelligence.com/2020/03/threat-roundup-0228-0306.html
* https://s.tencent.com/research/report/793
* https://www.fortinet.com/blog/threat-research/nemty-ransomware-early-stage-threat.html

## Literature

The following _articles_ explain our unique predictive cyber threat intelligence:

* [VulDB Cyber Threat Intelligence Documentation](https://vuldb.com/?kb.cti)
* [Cyber Threat Intelligence - Early Anticipation of Attacks](https://www.scip.ch/en/?labs.20201022)

## License

(c) [1997-2024](https://vuldb.com/?kb.changelog) by [vuldb.com](https://vuldb.com/?kb.about). All data on this page is shared under the license [CC BY-NC-SA 4.0](https://creativecommons.org/licenses/by-nc-sa/4.0/). Questions? Check the [FAQ](https://vuldb.com/?kb.faq), read the [documentation](https://vuldb.com/?kb) or [contact us](https://vuldb.com/?contact)!
