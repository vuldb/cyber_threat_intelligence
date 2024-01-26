# RevengeRAT - Cyber Threat Intelligence

These _indicators_ were reported, collected, and generated during the [VulDB CTI analysis](https://vuldb.com/?kb.cti) of the actor known as [RevengeRAT](https://vuldb.com/?actor.revengerat). The _activity monitoring_ correlates data from social media, forums, chat rooms, and darknet markets. It helps to determine associated actors, specific activities, expected intentions, emerging research, and ongoing attacks. Our unique _predictive model_ uses _big data_ to forecast activities and their characteristics.

_Live data_ and more _analysis capabilities_ are available at [https://vuldb.com/?actor.revengerat](https://vuldb.com/?actor.revengerat)

## Countries

These _countries_ are directly (e.g. origin of attacks) or indirectly (e.g. access by proxy) associated with RevengeRAT:

* [US](https://vuldb.com/?country.us)
* [VN](https://vuldb.com/?country.vn)
* [CN](https://vuldb.com/?country.cn)
* ...

There are 9 more country items available. Please use our online service to access the data.

## IOC - Indicator of Compromise

These _indicators of compromise_ (IOC) indicate associated network resources which are known to be part of research and attack activities of RevengeRAT.

ID | IP address | Hostname | Campaign | Confidence
-- | ---------- | -------- | -------- | ----------
1 | [6.43.51.17](https://vuldb.com/?ip.6.43.51.17) | - | - | High
2 | [10.0.2.15](https://vuldb.com/?ip.10.0.2.15) | - | - | High
3 | [45.147.230.231](https://vuldb.com/?ip.45.147.230.231) | - | - | High
4 | ... | ... | ... | ...

There are 14 more IOC items available. Please use our online service to access the data.

## TTP - Tactics, Techniques, Procedures

_Tactics, techniques, and procedures_ (TTP) summarize the suspected MITRE ATT&CK techniques used by _RevengeRAT_. This data is unique as it uses our predictive model for actor profiling.

ID | Technique | Weakness | Description | Confidence
-- | --------- | -------- | ----------- | ----------
1 | T1006 | CWE-22, CWE-23, CWE-24, CWE-36 | Pathname Traversal | High
2 | T1055 | CWE-74 | Injection | High
3 | T1059 | CWE-94, CWE-1321 | Cross Site Scripting | High
4 | T1059.007 | CWE-79, CWE-80 | Cross Site Scripting | High
5 | T1068 | CWE-264, CWE-266, CWE-269, CWE-284 | J2EE Misconfiguration: Weak Access Permissions for EJB Methods | High
6 | ... | ... | ... | ...

There are 21 more TTP items available. Please use our online service to access the data.

## IOA - Indicator of Attack

These _indicators of attack_ (IOA) list the potential fragments used for technical activities like reconnaissance, exploitation, privilege escalation, and exfiltration by RevengeRAT. This data is unique as it uses our predictive model for actor profiling.

ID | Type | Indicator | Confidence
-- | ---- | --------- | ----------
1 | File | `$HOME/.terminfo` | High
2 | File | `/admin/` | Low
3 | File | `/admin/admin_user.php` | High
4 | File | `/admin/category/save` | High
5 | File | `/admin/subject.php` | High
6 | File | `/api/baskets/{name}` | High
7 | File | `/auth/auth.php?user=1` | High
8 | File | `/bin/login` | Medium
9 | File | `/bin/mini_upnpd` | High
10 | File | `/boaform/device_reset.cgi` | High
11 | File | `/cgi-bin/cstecgi.cgi` | High
12 | File | `/cgi-bin/cstecgi.cgi?action=login` | High
13 | File | `/cgi-bin/cstecgi.cgi?action=login&flag=1` | High
14 | File | `/cgi-bin/wlogin.cgi` | High
15 | File | `/cgi/cpaddons_report.pl` | High
16 | File | `/debug/pprof` | Medium
17 | File | `/DXR.axd` | Medium
18 | File | `/forum/away.php` | High
19 | File | `/goform/goform_get_cmd_process` | High
20 | File | `/goform/set_LimitClient_cfg` | High
21 | File | `/h/autoSaveDraft` | High
22 | File | `/h/search?action` | High
23 | File | `/HNAP1/` | Low
24 | File | `/hss/admin/?page=products/view_product` | High
25 | File | `/importexport.php` | High
26 | File | `/index.php?app=main&func=passport&action=login` | High
27 | File | `/main/doctype.php` | High
28 | File | `/main/webservices/additional_webservices.php` | High
29 | File | `/mc` | Low
30 | File | `/mgmt/` | Low
31 | File | `/oauth/idp/.well-known/openid-configuration` | High
32 | File | `/opt/zimbra/jetty/webapps/zimbra/public` | High
33 | File | `/preview.php` | Medium
34 | File | `/register.php` | High
35 | File | `/secure/ViewCollectors` | High
36 | File | `/server-status` | High
37 | File | `/setting/NTPSyncWithHost` | High
38 | ... | ... | ...

There are 327 more IOA items available (file, library, argument, input value, pattern, network port). Please use our online service to access the data.

## References

The following list contains _external sources_ which discuss the actor and the associated activities:

* https://1275.ru/ioc/149/revengerat-iocs/
* https://blog.talosintelligence.com/2019/07/threat-roundup-0628-0705.html
* https://blog.talosintelligence.com/2019/08/rat-ratatouille-revrat-orcus.html
* https://blog.talosintelligence.com/threat-roundup-0616-0623-2/
* https://www.fortinet.com/blog/threat-research/malware-analysis-revenge-rat-sample.html

## Literature

The following _articles_ explain our unique predictive cyber threat intelligence:

* [VulDB Cyber Threat Intelligence Documentation](https://vuldb.com/?kb.cti)
* [Cyber Threat Intelligence - Early Anticipation of Attacks](https://www.scip.ch/en/?labs.20201022)

## License

(c) [1997-2024](https://vuldb.com/?kb.changelog) by [vuldb.com](https://vuldb.com/?kb.about). All data on this page is shared under the license [CC BY-NC-SA 4.0](https://creativecommons.org/licenses/by-nc-sa/4.0/). Questions? Check the [FAQ](https://vuldb.com/?kb.faq), read the [documentation](https://vuldb.com/?kb) or [contact us](https://vuldb.com/?contact)!
