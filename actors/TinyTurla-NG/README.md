# TinyTurla-NG - Cyber Threat Intelligence

These _indicators_ were reported, collected, and generated during the [VulDB CTI analysis](https://vuldb.com/?kb.cti) of the actor known as [TinyTurla-NG](https://vuldb.com/?actor.tinyturla-ng). The _activity monitoring_ correlates data from social media, forums, chat rooms, and darknet markets. It helps to determine associated actors, specific activities, expected intentions, emerging research, and ongoing attacks. Our unique _predictive model_ uses _big data_ to forecast activities and their characteristics.

_Live data_ and more _analysis capabilities_ are available at [https://vuldb.com/?actor.tinyturla-ng](https://vuldb.com/?actor.tinyturla-ng)

## Countries

These _countries_ are directly (e.g. origin of attacks) or indirectly (e.g. access by proxy) associated with TinyTurla-NG:

* [US](https://vuldb.com/?country.us)
* [VN](https://vuldb.com/?country.vn)
* [CN](https://vuldb.com/?country.cn)
* ...

There are 8 more country items available. Please use our online service to access the data.

## IOC - Indicator of Compromise

These _indicators of compromise_ (IOC) indicate associated network resources which are known to be part of research and attack activities of TinyTurla-NG.

ID | IP address | Hostname | Campaign | Confidence
-- | ---------- | -------- | -------- | ----------
1 | [34.135.1.100](https://vuldb.com/?ip.34.135.1.100) | 100.1.135.34.bc.googleusercontent.com | - | Medium
2 | [91.193.18.120](https://vuldb.com/?ip.91.193.18.120) | cadenceelementary.info | - | High
3 | [127.0.0.1](https://vuldb.com/?ip.127.0.0.1) | localhost | - | High

## TTP - Tactics, Techniques, Procedures

_Tactics, techniques, and procedures_ (TTP) summarize the suspected MITRE ATT&CK techniques used by _TinyTurla-NG_. This data is unique as it uses our predictive model for actor profiling.

ID | Technique | Weakness | Description | Confidence
-- | --------- | -------- | ----------- | ----------
1 | T1006 | CWE-22, CWE-23, CWE-24, CWE-36 | Path Traversal | High
2 | T1055 | CWE-74 | Injection | High
3 | T1059 | CWE-94, CWE-1321 | Argument Injection | High
4 | T1059.007 | CWE-79, CWE-80 | Cross Site Scripting | High
5 | T1068 | CWE-264, CWE-266, CWE-269, CWE-284 | Execution with Unnecessary Privileges | High
6 | ... | ... | ... | ...

There are 21 more TTP items available. Please use our online service to access the data.

## IOA - Indicator of Attack

These _indicators of attack_ (IOA) list the potential fragments used for technical activities like reconnaissance, exploitation, privilege escalation, and exfiltration by TinyTurla-NG. This data is unique as it uses our predictive model for actor profiling.

ID | Type | Indicator | Confidence
-- | ---- | --------- | ----------
1 | File | `$HOME/.terminfo` | High
2 | File | `/admin/` | Low
3 | File | `/admin/admin_user.php` | High
4 | File | `/admin/category/save` | High
5 | File | `/admin/subject.php` | High
6 | File | `/auth/auth.php?user=1` | High
7 | File | `/bin/login` | Medium
8 | File | `/bin/mini_upnpd` | High
9 | File | `/boaform/device_reset.cgi` | High
10 | File | `/cgi-bin/cstecgi.cgi` | High
11 | File | `/cgi-bin/cstecgi.cgi?action=login` | High
12 | File | `/cgi-bin/cstecgi.cgi?action=login&flag=1` | High
13 | File | `/cgi-bin/wlogin.cgi` | High
14 | File | `/cgi/cpaddons_report.pl` | High
15 | File | `/debug/pprof` | Medium
16 | File | `/DXR.axd` | Medium
17 | File | `/forum/away.php` | High
18 | File | `/goform/goform_get_cmd_process` | High
19 | File | `/h/autoSaveDraft` | High
20 | File | `/h/search?action` | High
21 | File | `/HNAP1/` | Low
22 | File | `/importexport.php` | High
23 | File | `/index.php?app=main&func=passport&action=login` | High
24 | File | `/main/doctype.php` | High
25 | File | `/main/webservices/additional_webservices.php` | High
26 | File | `/mc` | Low
27 | File | `/me` | Low
28 | File | `/mgmt/` | Low
29 | File | `/net/bluetooth/rfcomm/core.C` | High
30 | File | `/oauth/idp/.well-known/openid-configuration` | High
31 | File | `/opt/zimbra/jetty/webapps/zimbra/public` | High
32 | File | `/preview.php` | Medium
33 | File | `/register.php` | High
34 | File | `/secure/ViewCollectors` | High
35 | File | `/server-status` | High
36 | File | `/setting/NTPSyncWithHost` | High
37 | File | `/spip.php` | Medium
38 | File | `/squashfs-root/etc_ro/custom.conf` | High
39 | ... | ... | ...

There are 338 more IOA items available (file, library, argument, input value, pattern, network port). Please use our online service to access the data.

## References

The following list contains _external sources_ which discuss the actor and the associated activities:

* https://blog.talosintelligence.com/tinyturla-ng-tooling-and-c2/

## Literature

The following _articles_ explain our unique predictive cyber threat intelligence:

* [VulDB Cyber Threat Intelligence Documentation](https://vuldb.com/?kb.cti)
* [Cyber Threat Intelligence - Early Anticipation of Attacks](https://www.scip.ch/en/?labs.20201022)

## License

(c) [1997-2024](https://vuldb.com/?kb.changelog) by [vuldb.com](https://vuldb.com/?kb.about). All data on this page is shared under the license [CC BY-NC-SA 4.0](https://creativecommons.org/licenses/by-nc-sa/4.0/). Questions? Check the [FAQ](https://vuldb.com/?kb.faq), read the [documentation](https://vuldb.com/?kb) or [contact us](https://vuldb.com/?contact)!
