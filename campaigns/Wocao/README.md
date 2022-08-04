# Wocao - Cyber Threat Intelligence

These _indicators_ were reported, collected, and generated during the [VulDB CTI analysis](https://vuldb.com/?kb.cti) of the campaign known as _Wocao_. The _activity monitoring_ correlates data from social media, forums, chat rooms, and darknet markets. It helps to determine associated actors, specific activities, expected intentions, emerging research, and ongoing attacks. Our unique _predictive model_ uses _big data_ to forecast activities and their characteristics.

_Live data_ and more _analysis capabilities_ are available at [https://vuldb.com/?actor](https://vuldb.com/?actor)

## Countries

These _countries_ are directly (e.g. origin of attacks) or indirectly (e.g. access by proxy) associated with Wocao:

* [US](https://vuldb.com/?country.us)
* [AR](https://vuldb.com/?country.ar)
* [GB](https://vuldb.com/?country.gb)

## Actors

These _actors_ are associated with Wocao or other actors linked to the campaign.

ID | Actor | Confidence
-- | ----- | ----------
1 | [Wocao](https://vuldb.com/?actor.wocao) | High

## IOC - Indicator of Compromise

These _indicators of compromise_ (IOC) indicate associated network resources which are known to be part of research and attack activities of Wocao.

ID | IP address | Hostname | Actor | Confidence
-- | ---------- | -------- | ----- | ----------
1 | [23.254.211.108](https://vuldb.com/?ip.23.254.211.108) | hwsrv-871243.hostwindsdns.com | [Wocao](https://vuldb.com/?actor.wocao) | High
2 | [31.222.185.215](https://vuldb.com/?ip.31.222.185.215) | 31-222-185-215.static.cloud-ips.co.uk | [Wocao](https://vuldb.com/?actor.wocao) | High
3 | [45.77.229.10](https://vuldb.com/?ip.45.77.229.10) | 45.77.229.10.vultr.com | [Wocao](https://vuldb.com/?actor.wocao) | Medium
4 | ... | ... | ... | ...

There are 13 more IOC items available. Please use our online service to access the data.

## TTP - Tactics, Techniques, Procedures

_Tactics, techniques, and procedures_ (TTP) summarize the suspected MITRE ATT&CK techniques used within Wocao. This data is unique as it uses our predictive model for actor profiling.

ID | Technique | Weakness | Description | Confidence
-- | --------- | -------- | ----------- | ----------
1 | T1006 | CWE-21, CWE-22, CWE-23 | Pathname Traversal | High
2 | T1040 | CWE-319 | Authentication Bypass by Capture-replay | High
3 | T1055 | CWE-74 | Injection | High
4 | T1059 | CWE-94 | Cross Site Scripting | High
5 | T1059.007 | CWE-79, CWE-80 | Cross Site Scripting | High
6 | ... | ... | ... | ...

There are 21 more TTP items available. Please use our online service to access the data.

## IOA - Indicator of Attack

These _indicators of attack_ (IOA) list the potential fragments used for technical activities like reconnaissance, exploitation, privilege escalation, and exfiltration during Wocao. This data is unique as it uses our predictive model for actor profiling.

ID | Type | Indicator | Confidence
-- | ---- | --------- | ----------
1 | File | `/admin` | Low
2 | File | `/api/plugin/uninstall` | High
3 | File | `/artist-display.php` | High
4 | File | `/assets/partials/_handleLogin.php` | High
5 | File | `/bmis/pages/resident/resident.php` | High
6 | File | `/cgi-bin/mesh.cgi?page=upgrade` | High
7 | File | `/cgi-bin/nightled.cgi` | High
8 | File | `/context.json` | High
9 | File | `/editbrand.php` | High
10 | File | `/edituser.php` | High
11 | File | `/goform/aspForm` | High
12 | File | `/HMS/admin.php` | High
13 | File | `/htmldoc/htmldoc/html.cxx` | High
14 | File | `/login.php` | Medium
15 | File | `/LogoStore/search.php` | High
16 | File | `/modules/caddyhttp/rewrite/rewrite.go` | High
17 | File | `/pages/activity/activity.php` | High
18 | File | `/pages/permit/permit.php` | High
19 | File | `/php_action/createUser.php` | High
20 | File | `/school/view/student_grade_wise.php` | High
21 | File | `/show_news.php` | High
22 | ... | ... | ...

There are 187 more IOA items available (file, library, argument, input value, pattern, network port). Please use our online service to access the data.

## References

The following list contains _external sources_ which discuss the campaign and the associated activities:

* https://github.com/fox-it/operation-wocao

## Literature

The following _articles_ explain our unique predictive cyber threat intelligence:

* [VulDB Cyber Threat Intelligence Documentation](https://vuldb.com/?kb.cti)
* [Cyber Threat Intelligence - Early Anticipation of Attacks](https://www.scip.ch/en/?labs.20201022)

## License

(c) [1997-2022](https://vuldb.com/?kb.changelog) by [vuldb.com](https://vuldb.com/?kb.about). All data on this page is shared under the license [CC BY-NC-SA 4.0](https://creativecommons.org/licenses/by-nc-sa/4.0/). Questions? Check the [FAQ](https://vuldb.com/?kb.faq), read the [documentation](https://vuldb.com/?kb) or [contact us](https://vuldb.com/?contact)!
