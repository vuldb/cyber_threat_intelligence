# CredStealer - Cyber Threat Intelligence

These _indicators_ were reported, collected, and generated during the [VulDB CTI analysis](https://vuldb.com/?kb.cti) of the actor known as [CredStealer](https://vuldb.com/?actor.credstealer). The _activity monitoring_ correlates data from social media, forums, chat rooms, and darknet markets. It helps to determine associated actors, specific activities, expected intentions, emerging research, and ongoing attacks. Our unique _predictive model_ uses _big data_ to forecast activities and their characteristics.

_Live data_ and more _analysis capabilities_ are available at [https://vuldb.com/?actor.credstealer](https://vuldb.com/?actor.credstealer)

## Countries

These _countries_ are directly (e.g. origin of attacks) or indirectly (e.g. access by proxy) associated with CredStealer:

* [US](https://vuldb.com/?country.us)
* [CN](https://vuldb.com/?country.cn)
* [RU](https://vuldb.com/?country.ru)
* ...

There are 3 more country items available. Please use our online service to access the data.

## IOC - Indicator of Compromise

These _indicators of compromise_ (IOC) indicate associated network resources which are known to be part of research and attack activities of CredStealer.

ID | IP address | Hostname | Campaign | Confidence
-- | ---------- | -------- | -------- | ----------
1 | [45.9.148.108](https://vuldb.com/?ip.45.9.148.108) | mx1.dendrite.network | - | High
2 | [207.154.218.221](https://vuldb.com/?ip.207.154.218.221) | - | - | High

## TTP - Tactics, Techniques, Procedures

_Tactics, techniques, and procedures_ (TTP) summarize the suspected MITRE ATT&CK techniques used by _CredStealer_. This data is unique as it uses our predictive model for actor profiling.

ID | Technique | Weakness | Description | Confidence
-- | --------- | -------- | ----------- | ----------
1 | T1006 | CWE-22, CWE-24, CWE-28, CWE-425 | Path Traversal | High
2 | T1055 | CWE-74 | Improper Neutralization of Data within XPath Expressions | High
3 | T1059 | CWE-94 | Argument Injection | High
4 | T1059.007 | CWE-79, CWE-80 | Basic Cross Site Scripting | High
5 | ... | ... | ... | ...

There are 18 more TTP items available. Please use our online service to access the data.

## IOA - Indicator of Attack

These _indicators of attack_ (IOA) list the potential fragments used for technical activities like reconnaissance, exploitation, privilege escalation, and exfiltration by CredStealer. This data is unique as it uses our predictive model for actor profiling.

ID | Type | Indicator | Confidence
-- | ---- | --------- | ----------
1 | File | `/academy/tutor/filter` | High
2 | File | `/ad-list` | Medium
3 | File | `/admin/suppliers/view_details.php` | High
4 | File | `/ajax.php?action=read_msg` | High
5 | File | `/api/authentication/login` | High
6 | File | `/api/sys/login` | High
7 | File | `/api/sys/set_passwd` | High
8 | File | `/api/v2/open/rowsInfo` | High
9 | File | `/app/sys1.php` | High
10 | File | `/building/backmgr/urlpage/mobileurl/configfile/jx2_config.ini` | High
11 | File | `/cas/logout` | Medium
12 | File | `/catalog/all-products` | High
13 | File | `/cgi-bin/adm.cgi` | High
14 | File | `/cgi-bin/mesh.cgi?page=upgrade` | High
15 | File | `/cgi-bin/nas_sharing.cgi` | High
16 | File | `/cgi-bin/nightled.cgi` | High
17 | File | `/cgi-bin/touchlist_sync.cgi` | High
18 | File | `/cgi-bin/vitogate.cgi` | High
19 | File | `/debug/pprof` | Medium
20 | ... | ... | ...

There are 162 more IOA items available (file, library, argument, input value, pattern, network port). Please use our online service to access the data.

## References

The following list contains _external sources_ which discuss the actor and the associated activities:

* https://www.sentinelone.com/labs/cloudy-with-a-chance-of-credentials-aws-targeting-cred-stealer-expands-to-azure-gcp/

## Literature

The following _articles_ explain our unique predictive cyber threat intelligence:

* [VulDB Cyber Threat Intelligence Documentation](https://vuldb.com/?kb.cti)
* [Cyber Threat Intelligence - Early Anticipation of Attacks](https://www.scip.ch/en/?labs.20201022)

## License

(c) [1997-2025](https://vuldb.com/?kb.changelog) by [vuldb.com](https://vuldb.com/?kb.about). All data on this page is shared under the license [CC BY-NC-SA 4.0](https://creativecommons.org/licenses/by-nc-sa/4.0/). Questions? Check the [FAQ](https://vuldb.com/?kb.faq), read the [documentation](https://vuldb.com/?kb) or [contact us](https://vuldb.com/?contact)!
