# LockBit - Cyber Threat Intelligence

These _indicators_ were reported, collected, and generated during the [VulDB CTI analysis](https://vuldb.com/?kb.cti) of the actor known as [LockBit](https://vuldb.com/?actor.lockbit). The _activity monitoring_ correlates data from social media, forums, chat rooms, and darknet markets. It helps to determine associated actors, specific activities, expected intentions, emerging research, and ongoing attacks. Our unique _predictive model_ uses _big data_ to forecast activities and their characteristics.

_Live data_ and more _analysis capabilities_ are available at [https://vuldb.com/?actor.lockbit](https://vuldb.com/?actor.lockbit)

## Countries

These _countries_ are directly (e.g. origin of attacks) or indirectly (e.g. access by proxy) associated with LockBit:

* [RU](https://vuldb.com/?country.ru)
* [US](https://vuldb.com/?country.us)
* [CN](https://vuldb.com/?country.cn)
* ...

There are 15 more country items available. Please use our online service to access the data.

## IOC - Indicator of Compromise

These _indicators of compromise_ (IOC) indicate associated network resources which are known to be part of research and attack activities of LockBit.

ID | IP address | Hostname | Campaign | Confidence
-- | ---------- | -------- | -------- | ----------
1 | [45.32.108.54](https://vuldb.com/?ip.45.32.108.54) | 45.32.108.54.vultrusercontent.com | - | High
2 | [45.91.83.176](https://vuldb.com/?ip.45.91.83.176) | - | - | High
3 | [45.227.255.190](https://vuldb.com/?ip.45.227.255.190) | - | - | High
4 | [88.80.147.102](https://vuldb.com/?ip.88.80.147.102) | - | - | High
5 | ... | ... | ... | ...

There are 17 more IOC items available. Please use our online service to access the data.

## TTP - Tactics, Techniques, Procedures

_Tactics, techniques, and procedures_ (TTP) summarize the suspected MITRE ATT&CK techniques used by _LockBit_. This data is unique as it uses our predictive model for actor profiling.

ID | Technique | Weakness | Description | Confidence
-- | --------- | -------- | ----------- | ----------
1 | T1006 | CWE-21, CWE-22 | Pathname Traversal | High
2 | T1040 | CWE-319 | Authentication Bypass by Capture-replay | High
3 | T1055 | CWE-74 | Injection | High
4 | ... | ... | ... | ...

There are 13 more TTP items available. Please use our online service to access the data.

## IOA - Indicator of Attack

These _indicators of attack_ (IOA) list the potential fragments used for technical activities like reconnaissance, exploitation, privilege escalation, and exfiltration by LockBit. This data is unique as it uses our predictive model for actor profiling.

ID | Type | Indicator | Confidence
-- | ---- | --------- | ----------
1 | File | `/admin/config.php?display=disa&view=form` | High
2 | File | `/cgi-bin/admin/testserver.cgi` | High
3 | File | `/cgi-bin/supervisor/CloudSetup.cgi` | High
4 | File | `/export` | Low
5 | File | `/icingaweb2/navigation/add` | High
6 | File | `/recordings/index.php` | High
7 | File | `/secure/QueryComponent!Default.jspa` | High
8 | File | `/spip.php` | Medium
9 | File | `/student/bookdetails.php` | High
10 | File | `/uncpath/` | Medium
11 | File | `/wp-admin/admin-ajax.php` | High
12 | File | `adclick.php` | Medium
13 | File | `agent/Core/Controller/SendRequest.cpp` | High
14 | File | `api_poller.php` | High
15 | File | `arformcontroller.php` | High
16 | File | `attachmentlibrary.php` | High
17 | File | `backend/Login/load/` | High
18 | ... | ... | ...

There are 150 more IOA items available (file, library, argument, input value, pattern, network port). Please use our online service to access the data.

## References

The following list contains _external sources_ which discuss the actor and the associated activities:

* https://1275.ru/ioc/158/lockbit-ransomware-iocs/
* https://github.com/hvs-consulting/ioc_signatures/blob/main/Proxyshell/HvS_Proxyshell_2021_09_IOCs.csv
* https://github.com/sophoslabs/IoCs/blob/master/Ransomware-LockBit.csv
* https://thedfirreport.com/2020/06/10/lockbit-ransomware-why-you-no-spread/
* https://twitter.com/OscarAldana/status/1548457335852437506
* https://www.cybereason.com/blog/threat-analysis-report-lockbit-2.0-all-paths-lead-to-ransom
* https://www.ic3.gov/Media/News/2022/220204.pdf

## Literature

The following _articles_ explain our unique predictive cyber threat intelligence:

* [VulDB Cyber Threat Intelligence Documentation](https://vuldb.com/?kb.cti)
* [Cyber Threat Intelligence - Early Anticipation of Attacks](https://www.scip.ch/en/?labs.20201022)

## License

(c) [1997-2023](https://vuldb.com/?kb.changelog) by [vuldb.com](https://vuldb.com/?kb.about). All data on this page is shared under the license [CC BY-NC-SA 4.0](https://creativecommons.org/licenses/by-nc-sa/4.0/). Questions? Check the [FAQ](https://vuldb.com/?kb.faq), read the [documentation](https://vuldb.com/?kb) or [contact us](https://vuldb.com/?contact)!
