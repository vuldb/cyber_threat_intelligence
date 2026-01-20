# FatalRAT - Cyber Threat Intelligence

These _indicators_ were reported, collected, and generated during the [VulDB CTI analysis](https://vuldb.com/?kb.cti) of the actor known as [FatalRAT](https://vuldb.com/?actor.fatalrat). The _activity monitoring_ correlates data from social media, forums, chat rooms, and darknet markets. It helps to determine associated actors, specific activities, expected intentions, emerging research, and ongoing attacks. Our unique _predictive model_ uses _big data_ to forecast activities and their characteristics.

_Live data_ and more _analysis capabilities_ are available at [https://vuldb.com/?actor.fatalrat](https://vuldb.com/?actor.fatalrat)

## Countries

These _countries_ are directly (e.g. origin of attacks) or indirectly (e.g. access by proxy) associated with FatalRAT:

* [US](https://vuldb.com/?country.us)
* [CN](https://vuldb.com/?country.cn)
* [HK](https://vuldb.com/?country.hk)

## IOC - Indicator of Compromise

These _indicators of compromise_ (IOC) indicate associated network resources which are known to be part of research and attack activities of FatalRAT.

ID | IP address | Hostname | Campaign | Confidence
-- | ---------- | -------- | -------- | ----------
1 | [8.217.100.203](https://vuldb.com/?ip.8.217.100.203) | - | - | High
2 | [8.217.237.123](https://vuldb.com/?ip.8.217.237.123) | - | - | High
3 | [27.124.44.137](https://vuldb.com/?ip.27.124.44.137) | - | - | High
4 | [38.14.248.187](https://vuldb.com/?ip.38.14.248.187) | - | - | High
5 | [38.181.20.30](https://vuldb.com/?ip.38.181.20.30) | - | - | High
6 | [43.132.231.144](https://vuldb.com/?ip.43.132.231.144) | - | - | High
7 | [43.154.91.3](https://vuldb.com/?ip.43.154.91.3) | - | - | High
8 | [43.248.173.156](https://vuldb.com/?ip.43.248.173.156) | - | - | High
9 | [43.250.173.179](https://vuldb.com/?ip.43.250.173.179) | - | - | High
10 | [45.119.55.16](https://vuldb.com/?ip.45.119.55.16) | - | - | High
11 | ... | ... | ... | ...

There are 39 more IOC items available. Please use our online service to access the data.

## TTP - Tactics, Techniques, Procedures

_Tactics, techniques, and procedures_ (TTP) summarize the suspected MITRE ATT&CK techniques used by _FatalRAT_. This data is unique as it uses our predictive model for actor profiling.

ID | Technique | Weakness | Description | Confidence
-- | --------- | -------- | ----------- | ----------
1 | T1006 | CWE-21, CWE-22, CWE-24, CWE-27, CWE-36 | Path Traversal | High
2 | T1055 | CWE-74 | Improper Neutralization of Data within XPath Expressions | High
3 | T1059 | CWE-94 | Argument Injection | High
4 | T1059.007 | CWE-79, CWE-80 | Basic Cross Site Scripting | High
5 | ... | ... | ... | ...

There are 15 more TTP items available. Please use our online service to access the data.

## IOA - Indicator of Attack

These _indicators of attack_ (IOA) list the potential fragments used for technical activities like reconnaissance, exploitation, privilege escalation, and exfiltration by FatalRAT. This data is unique as it uses our predictive model for actor profiling.

ID | Type | Indicator | Confidence
-- | ---- | --------- | ----------
1 | File | `/admin` | Low
2 | File | `/admin.php?p=/Area/index#tab=t2` | High
3 | File | `/admin/about-us.php` | High
4 | File | `/admin/add_account.php` | High
5 | File | `/admin/approve.php` | High
6 | File | `/admin/contact-us.php` | High
7 | File | `/admin/forgot-password.php` | High
8 | File | `/admin/info_deal.php` | High
9 | File | `/admin/manage_station.php` | High
10 | File | `/admin/products/view_product.php` | High
11 | File | `/admin/publishnews.php` | High
12 | File | `/admin/user-search.php` | High
13 | File | `/admin_pay.php` | High
14 | File | `/ajax/get_patient_history.php` | High
15 | File | `/api/deploy/upload` | High
16 | File | `/api/deploy/upload /api/database/upload` | High
17 | File | `/api/dept` | Medium
18 | File | `/api/log/killJob` | High
19 | File | `/api/upload.php` | High
20 | File | `/app/ajax/sell_return_data.php` | High
21 | File | `/apps/system/router/upload.go` | High
22 | File | `/bin/httpd` | Medium
23 | File | `/birthing_pending.php` | High
24 | File | `/boafrm/formFilter` | High
25 | File | `/boafrm/formMapReboot` | High
26 | File | `/bwdates-reports-details.php` | High
27 | File | `/cgi-bin/cstecgi.cgi` | High
28 | File | `/cgi-bin/webproc?getpage=html/index.html&var:menu=24gwlan&var:page=24G_basic` | High
29 | File | `/contact-back.php` | High
30 | File | `/contact.php` | Medium
31 | File | `/dosen/data` | Medium
32 | ... | ... | ...

There are 268 more IOA items available (file, library, argument, input value, pattern, network port). Please use our online service to access the data.

## References

The following list contains _external sources_ which discuss the actor and the associated activities:

* https://1275.ru/ioc/66/fatalrat-backdoor-ioc/
* https://bazaar.abuse.ch/sample/1924b09ff1e25fe9d39bad70f094766863f366543658627fe94f435b07da6109/
* https://community.blueliv.com/#!/s/6107d20982df4141693319a7
* https://threatfox.abuse.ch
* https://tria.ge/241112-fvt33swbrg/behavioral1
* https://www.welivesecurity.com/2023/02/16/these-arent-apps-youre-looking-for-fake-installers/

## Literature

The following _articles_ explain our unique predictive cyber threat intelligence:

* [VulDB Cyber Threat Intelligence Documentation](https://vuldb.com/?kb.cti)
* [Cyber Threat Intelligence - Early Anticipation of Attacks](https://www.scip.ch/en/?labs.20201022)

## License

(c) [1997-2026](https://vuldb.com/?kb.changelog) by [vuldb.com](https://vuldb.com/?kb.about). All data on this page is shared under the license [CC BY-NC-SA 4.0](https://creativecommons.org/licenses/by-nc-sa/4.0/). Questions? Check the [FAQ](https://vuldb.com/?kb.faq), read the [documentation](https://vuldb.com/?kb) or [contact us](https://vuldb.com/?contact)!
