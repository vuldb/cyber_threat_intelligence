# Ares - Cyber Threat Intelligence

These _indicators_ were reported, collected, and generated during the [VulDB CTI analysis](https://vuldb.com/?kb.cti) of the actor known as [Ares](https://vuldb.com/?actor.ares). The _activity monitoring_ correlates data from social media, forums, chat rooms, and darknet markets. It helps to determine associated actors, specific activities, expected intentions, emerging research, and ongoing attacks. Our unique _predictive model_ uses _big data_ to forecast activities and their characteristics.

_Live data_ and more _analysis capabilities_ are available at [https://vuldb.com/?actor.ares](https://vuldb.com/?actor.ares)

## Countries

These _countries_ are directly (e.g. origin of attacks) or indirectly (e.g. access by proxy) associated with Ares:

* [DE](https://vuldb.com/?country.de)
* [US](https://vuldb.com/?country.us)
* [CN](https://vuldb.com/?country.cn)
* ...

There are 11 more country items available. Please use our online service to access the data.

## IOC - Indicator of Compromise

These _indicators of compromise_ (IOC) indicate associated network resources which are known to be part of research and attack activities of Ares.

ID | IP address | Hostname | Campaign | Confidence
-- | ---------- | -------- | -------- | ----------
1 | [2.58.113.190](https://vuldb.com/?ip.2.58.113.190) | tube-hosting.com | - | High
2 | [5.75.134.42](https://vuldb.com/?ip.5.75.134.42) | h90.wpherc.dev | - | High
3 | [5.149.252.227](https://vuldb.com/?ip.5.149.252.227) | - | - | High
4 | [5.161.104.72](https://vuldb.com/?ip.5.161.104.72) | h91.wpherc.dev | - | High
5 | [18.142.254.96](https://vuldb.com/?ip.18.142.254.96) | ec2-18-142-254-96.ap-southeast-1.compute.amazonaws.com | - | Medium
6 | [31.220.41.207](https://vuldb.com/?ip.31.220.41.207) | - | - | High
7 | [34.121.161.18](https://vuldb.com/?ip.34.121.161.18) | 18.161.121.34.bc.googleusercontent.com | - | Medium
8 | ... | ... | ... | ...

There are 27 more IOC items available. Please use our online service to access the data.

## TTP - Tactics, Techniques, Procedures

_Tactics, techniques, and procedures_ (TTP) summarize the suspected MITRE ATT&CK techniques used by _Ares_. This data is unique as it uses our predictive model for actor profiling.

ID | Technique | Weakness | Description | Confidence
-- | --------- | -------- | ----------- | ----------
1 | T1006 | CWE-21, CWE-22, CWE-425 | Path Traversal | High
2 | T1040 | CWE-319 | Authentication Bypass by Capture-replay | High
3 | T1055 | CWE-74 | Improper Neutralization of Data within XPath Expressions | High
4 | T1059 | CWE-88, CWE-94, CWE-1321 | Argument Injection | High
5 | T1059.007 | CWE-79, CWE-80 | Basic Cross Site Scripting | High
6 | ... | ... | ... | ...

There are 18 more TTP items available. Please use our online service to access the data.

## IOA - Indicator of Attack

These _indicators of attack_ (IOA) list the potential fragments used for technical activities like reconnaissance, exploitation, privilege escalation, and exfiltration by Ares. This data is unique as it uses our predictive model for actor profiling.

ID | Type | Indicator | Confidence
-- | ---- | --------- | ----------
1 | File | `/+CSCOE+/logon.html` | High
2 | File | `/admin/markdown` | High
3 | File | `/admin/modal_add_product.php` | High
4 | File | `/administrator/components/table_manager/` | High
5 | File | `/audimex/cgi-bin/wal.fcgi` | High
6 | File | `/auth_pic.cgi` | High
7 | File | `/blog` | Low
8 | File | `/cgi-bin/cstecgi.cgi` | High
9 | File | `/Content/Template/root/reverse-shell.aspx` | High
10 | File | `/expedit.php` | Medium
11 | File | `/export` | Low
12 | File | `/forum/away.php` | High
13 | File | `/friendprofile.php` | High
14 | File | `/goform/setsambacfg` | High
15 | File | `/goform/SysToolRestoreSet` | High
16 | File | `/large.php` | Medium
17 | File | `/MRcgi/MRchat.pl` | High
18 | File | `/panel/edit-services.php` | High
19 | File | `/profile.php` | Medium
20 | File | `/register.php` | High
21 | File | `/routers/add-ticket.php` | High
22 | File | `/school/model/get_events.php` | High
23 | File | `/sessions/sess_<sessionid>` | High
24 | File | `/spip.php` | Medium
25 | File | `/sys/user/queryUserComponentData` | High
26 | File | `/sysmanage/edit_manageadmin.php` | High
27 | File | `/tmp` | Low
28 | File | `/tool/gen/create` | High
29 | File | `/uncpath/` | Medium
30 | File | `/user/getAllList` | High
31 | ... | ... | ...

There are 261 more IOA items available (file, library, argument, input value, pattern, network port). Please use our online service to access the data.

## References

The following list contains _external sources_ which discuss the actor and the associated activities:

* https://search.censys.io/hosts/5.75.134.42
* https://search.censys.io/hosts/5.149.252.227
* https://search.censys.io/hosts/5.161.104.72
* https://search.censys.io/hosts/31.220.41.207
* https://search.censys.io/hosts/34.121.161.18
* https://search.censys.io/hosts/38.242.144.29
* https://search.censys.io/hosts/47.79.149.234
* https://search.censys.io/hosts/47.242.51.181
* https://search.censys.io/hosts/62.210.217.107
* https://search.censys.io/hosts/65.108.210.95
* https://search.censys.io/hosts/66.42.93.127
* https://search.censys.io/hosts/77.68.91.91
* https://search.censys.io/hosts/84.247.172.112
* https://search.censys.io/hosts/84.247.176.126
* https://search.censys.io/hosts/85.158.108.85
* https://search.censys.io/hosts/92.84.154.5
* https://search.censys.io/hosts/141.98.11.95
* https://search.censys.io/hosts/157.90.121.69
* https://search.censys.io/hosts/157.90.234.160
* https://search.censys.io/hosts/161.97.151.220
* https://search.censys.io/hosts/164.215.103.230
* https://search.censys.io/hosts/176.58.109.21
* https://search.censys.io/hosts/185.123.102.33
* https://search.censys.io/hosts/185.123.102.160
* https://search.censys.io/hosts/185.123.102.180
* https://search.censys.io/hosts/185.235.137.237
* https://search.censys.io/hosts/194.163.178.229
* https://search.censys.io/hosts/195.201.119.86
* https://search.censys.io/hosts/207.180.220.55
* https://search.censys.io/search?resource=hosts&sort=RELEVANCE&per_page=25&virtual_hosts=INCLUDE&q=name%3A+static.72.104.161.5.clients.your-server.de&ref=threatfox
* https://threatfox.abuse.ch
* https://www.zscaler.com/blogs/security-research/ares-banking-trojan-learns-old-tricks-adds-defunct-qakbot-dga
* https://x.com/PrakkiSathwik/status/1952682759555776979

## Literature

The following _articles_ explain our unique predictive cyber threat intelligence:

* [VulDB Cyber Threat Intelligence Documentation](https://vuldb.com/?kb.cti)
* [Cyber Threat Intelligence - Early Anticipation of Attacks](https://www.scip.ch/en/?labs.20201022)

## License

(c) [1997-2026](https://vuldb.com/?kb.changelog) by [vuldb.com](https://vuldb.com/?kb.about). All data on this page is shared under the license [CC BY-NC-SA 4.0](https://creativecommons.org/licenses/by-nc-sa/4.0/). Questions? Check the [FAQ](https://vuldb.com/?kb.faq), read the [documentation](https://vuldb.com/?kb) or [contact us](https://vuldb.com/?contact)!
