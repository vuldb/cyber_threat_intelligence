# GoMet - Cyber Threat Intelligence

These _indicators_ were reported, collected, and generated during the [VulDB CTI analysis](https://vuldb.com/?kb.cti) of the actor known as [GoMet](https://vuldb.com/?actor.gomet). The _activity monitoring_ correlates data from social media, forums, chat rooms, and darknet markets. It helps to determine associated actors, specific activities, expected intentions, emerging research, and ongoing attacks. Our unique _predictive model_ uses _big data_ to forecast activities and their characteristics.

_Live data_ and more _analysis capabilities_ are available at [https://vuldb.com/?actor.gomet](https://vuldb.com/?actor.gomet)

## Campaigns

The following _campaigns_ are known and can be associated with GoMet:

* Ukraine

## Countries

These _countries_ are directly (e.g. origin of attacks) or indirectly (e.g. access by proxy) associated with GoMet:

* [LA](https://vuldb.com/?country.la)
* [US](https://vuldb.com/?country.us)
* [GB](https://vuldb.com/?country.gb)

## IOC - Indicator of Compromise

These _indicators of compromise_ (IOC) indicate associated network resources which are known to be part of research and attack activities of GoMet.

ID | IP address | Hostname | Campaign | Confidence
-- | ---------- | -------- | -------- | ----------
1 | [111.90.139.122](https://vuldb.com/?ip.111.90.139.122) | server1.kamon.la | Ukraine | High

## TTP - Tactics, Techniques, Procedures

_Tactics, techniques, and procedures_ (TTP) summarize the suspected MITRE ATT&CK techniques used by _GoMet_. This data is unique as it uses our predictive model for actor profiling.

ID | Technique | Weakness | Description | Confidence
-- | --------- | -------- | ----------- | ----------
1 | T1006 | CWE-21, CWE-22, CWE-24 | Path Traversal | High
2 | T1055 | CWE-74 | Improper Neutralization of Data within XPath Expressions | High
3 | T1059 | CWE-88, CWE-94, CWE-1321 | Argument Injection | High
4 | T1059.007 | CWE-79, CWE-80 | Cross Site Scripting | High
5 | ... | ... | ... | ...

There are 16 more TTP items available. Please use our online service to access the data.

## IOA - Indicator of Attack

These _indicators of attack_ (IOA) list the potential fragments used for technical activities like reconnaissance, exploitation, privilege escalation, and exfiltration by GoMet. This data is unique as it uses our predictive model for actor profiling.

ID | Type | Indicator | Confidence
-- | ---- | --------- | ----------
1 | File | `/admin/dl_sendmail.php` | High
2 | File | `/admin/index2.html` | High
3 | File | `/adminPage/conf/reload` | High
4 | File | `/api/baskets/{name}` | High
5 | File | `/api/v2/cli/commands` | High
6 | File | `/cgi-bin/koha/catalogue/search.pl` | High
7 | File | `/Device/Device/GetDeviceInfoList?deviceCode=&searchField=&deviceState=` | High
8 | File | `/DXR.axd` | Medium
9 | File | `/forum/away.php` | High
10 | File | `/index/ajax/lang` | High
11 | File | `/log/decodmail.php` | High
12 | File | `/mfsNotice/page` | High
13 | File | `/novel/bookSetting/list` | High
14 | File | `/novel/userFeedback/list` | High
15 | File | `/owa/auth/logon.aspx` | High
16 | File | `/register.php` | High
17 | File | `/spip.php` | Medium
18 | ... | ... | ...

There are 143 more IOA items available (file, library, argument, input value, pattern, network port). Please use our online service to access the data.

## References

The following list contains _external sources_ which discuss the actor and the associated activities:

* https://blog.talosintelligence.com/2022/07/attackers-target-ukraine-using-gomet.html

## Literature

The following _articles_ explain our unique predictive cyber threat intelligence:

* [VulDB Cyber Threat Intelligence Documentation](https://vuldb.com/?kb.cti)
* [Cyber Threat Intelligence - Early Anticipation of Attacks](https://www.scip.ch/en/?labs.20201022)

## License

(c) [1997-2024](https://vuldb.com/?kb.changelog) by [vuldb.com](https://vuldb.com/?kb.about). All data on this page is shared under the license [CC BY-NC-SA 4.0](https://creativecommons.org/licenses/by-nc-sa/4.0/). Questions? Check the [FAQ](https://vuldb.com/?kb.faq), read the [documentation](https://vuldb.com/?kb) or [contact us](https://vuldb.com/?contact)!
