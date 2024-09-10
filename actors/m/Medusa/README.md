# Medusa - Cyber Threat Intelligence

These _indicators_ were reported, collected, and generated during the [VulDB CTI analysis](https://vuldb.com/?kb.cti) of the actor known as [Medusa](https://vuldb.com/?actor.medusa). The _activity monitoring_ correlates data from social media, forums, chat rooms, and darknet markets. It helps to determine associated actors, specific activities, expected intentions, emerging research, and ongoing attacks. Our unique _predictive model_ uses _big data_ to forecast activities and their characteristics.

_Live data_ and more _analysis capabilities_ are available at [https://vuldb.com/?actor.medusa](https://vuldb.com/?actor.medusa)

## Countries

These _countries_ are directly (e.g. origin of attacks) or indirectly (e.g. access by proxy) associated with Medusa:

* [US](https://vuldb.com/?country.us)
* [RU](https://vuldb.com/?country.ru)
* [CN](https://vuldb.com/?country.cn)
* ...

There are 14 more country items available. Please use our online service to access the data.

## IOC - Indicator of Compromise

These _indicators of compromise_ (IOC) indicate associated network resources which are known to be part of research and attack activities of Medusa.

ID | IP address | Hostname | Campaign | Confidence
-- | ---------- | -------- | -------- | ----------
1 | [5.42.78.61](https://vuldb.com/?ip.5.42.78.61) | - | - | High
2 | [5.61.49.177](https://vuldb.com/?ip.5.61.49.177) | - | - | High
3 | [5.182.87.27](https://vuldb.com/?ip.5.182.87.27) | - | - | High
4 | [8.217.23.144](https://vuldb.com/?ip.8.217.23.144) | - | - | High
5 | [20.0.25.177](https://vuldb.com/?ip.20.0.25.177) | - | - | High
6 | [45.15.157.16](https://vuldb.com/?ip.45.15.157.16) | scientific-group.aeza.network | - | High
7 | [45.145.167.117](https://vuldb.com/?ip.45.145.167.117) | hms16304.hostmyservers.me | - | High
8 | [45.150.65.121](https://vuldb.com/?ip.45.150.65.121) | vm1757649.stark-industries.solutions | - | High
9 | [64.52.80.13](https://vuldb.com/?ip.64.52.80.13) | - | - | High
10 | ... | ... | ... | ...

There are 34 more IOC items available. Please use our online service to access the data.

## TTP - Tactics, Techniques, Procedures

_Tactics, techniques, and procedures_ (TTP) summarize the suspected MITRE ATT&CK techniques used by _Medusa_. This data is unique as it uses our predictive model for actor profiling.

ID | Technique | Weakness | Description | Confidence
-- | --------- | -------- | ----------- | ----------
1 | T1006 | CWE-21, CWE-22, CWE-425 | Path Traversal | High
2 | T1055 | CWE-74 | Improper Neutralization of Data within XPath Expressions | High
3 | T1059 | CWE-88, CWE-94 | Argument Injection | High
4 | T1059.007 | CWE-79, CWE-80 | Cross Site Scripting | High
5 | ... | ... | ... | ...

There are 15 more TTP items available. Please use our online service to access the data.

## IOA - Indicator of Attack

These _indicators of attack_ (IOA) list the potential fragments used for technical activities like reconnaissance, exploitation, privilege escalation, and exfiltration by Medusa. This data is unique as it uses our predictive model for actor profiling.

ID | Type | Indicator | Confidence
-- | ---- | --------- | ----------
1 | File | `/admin/app/product.php` | High
2 | File | `/admin/delete_user.php` | High
3 | File | `/admin/index.php` | High
4 | File | `/admin/index2.html` | High
5 | File | `/admin/maintenance/view_designation.php` | High
6 | File | `/admin/pages/list` | High
7 | File | `/admin/sales/view_details.php` | High
8 | File | `/admin_class.php` | High
9 | File | `/alphaware/summary.php` | High
10 | File | `/api/baskets/{name}` | High
11 | File | `/api/swaggerui/static` | High
12 | File | `/cas/logout` | Medium
13 | File | `/cgi-bin/cstecgi.cgi?action=login` | High
14 | File | `/cgi-bin/cstecgi.cgi?action=save&setting` | High
15 | File | `/cgi-bin/supervisor/PwdGrp.cgi` | High
16 | File | `/classes/Master.php` | High
17 | File | `/collection/all` | High
18 | File | `/common/info.cgi` | High
19 | File | `/cupseasylive/countrymodify.php` | High
20 | File | `/cupseasylive/taxstructurelist.php` | High
21 | File | `/filex/read-raw` | High
22 | File | `/forum/away.php` | High
23 | File | `/hardware` | Medium
24 | File | `/jeecg-boot/jmreport/show` | High
25 | File | `/librarian/bookdetails.php` | High
26 | File | `/login` | Low
27 | File | `/LoginRegistration.php` | High
28 | File | `/manage_person.php` | High
29 | File | `/member/ad.php?action=ad` | High
30 | File | `/oauth/idp/.well-known/openid-configuration` | High
31 | ... | ... | ...

There are 268 more IOA items available (file, library, argument, input value, pattern, network port). Please use our online service to access the data.

## References

The following list contains _external sources_ which discuss the actor and the associated activities:

* https://cyble.com/blog/new-medusa-botnet-emerging-via-mirai-botnet-targeting-linux-users/
* https://threatfox.abuse.ch
* https://tracker.viriback.com/index.php?q=5.42.78.61
* https://tracker.viriback.com/index.php?q=5.61.49.177
* https://tracker.viriback.com/index.php?q=45.15.157.16
* https://tracker.viriback.com/index.php?q=64.52.80.13
* https://tracker.viriback.com/index.php?q=77.105.146.254
* https://tracker.viriback.com/index.php?q=77.105.147.1
* https://tracker.viriback.com/index.php?q=77.105.147.136
* https://tracker.viriback.com/index.php?q=79.137.199.199
* https://tracker.viriback.com/index.php?q=79.137.202.24
* https://tracker.viriback.com/index.php?q=79.137.207.226
* https://tracker.viriback.com/index.php?q=85.192.63.65
* https://tracker.viriback.com/index.php?q=89.185.85.34
* https://tracker.viriback.com/index.php?q=89.185.85.132
* https://tracker.viriback.com/index.php?q=89.208.103.72
* https://tracker.viriback.com/index.php?q=89.208.107.158
* https://tracker.viriback.com/index.php?q=95.181.173.8
* https://tracker.viriback.com/index.php?q=95.181.173.233
* https://tracker.viriback.com/index.php?q=95.181.173.235
* https://tracker.viriback.com/index.php?q=146.70.161.13
* https://tracker.viriback.com/index.php?q=162.33.179.114
* https://tracker.viriback.com/index.php?q=185.46.46.133
* https://tracker.viriback.com/index.php?q=185.106.94.31
* https://tracker.viriback.com/index.php?q=185.112.83.36
* https://tracker.viriback.com/index.php?q=193.233.133.81
* https://tracker.viriback.com/index.php?q=193.233.133.97
* https://tracker.viriback.com/index.php?q=193.233.133.153
* https://tracker.viriback.com/index.php?q=193.233.133.198
* https://tracker.viriback.com/index.php?q=193.233.133.243
* https://tracker.viriback.com/index.php?q=212.113.116.56
* https://twitter.com/Jane_0sint/status/1670048531665518592

## Literature

The following _articles_ explain our unique predictive cyber threat intelligence:

* [VulDB Cyber Threat Intelligence Documentation](https://vuldb.com/?kb.cti)
* [Cyber Threat Intelligence - Early Anticipation of Attacks](https://www.scip.ch/en/?labs.20201022)

## License

(c) [1997-2024](https://vuldb.com/?kb.changelog) by [vuldb.com](https://vuldb.com/?kb.about). All data on this page is shared under the license [CC BY-NC-SA 4.0](https://creativecommons.org/licenses/by-nc-sa/4.0/). Questions? Check the [FAQ](https://vuldb.com/?kb.faq), read the [documentation](https://vuldb.com/?kb) or [contact us](https://vuldb.com/?contact)!
