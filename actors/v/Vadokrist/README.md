# Vadokrist - Cyber Threat Intelligence

These _indicators_ were reported, collected, and generated during the [VulDB CTI analysis](https://vuldb.com/?kb.cti) of the actor known as [Vadokrist](https://vuldb.com/?actor.vadokrist). The _activity monitoring_ correlates data from social media, forums, chat rooms, and darknet markets. It helps to determine associated actors, specific activities, expected intentions, emerging research, and ongoing attacks. Our unique _predictive model_ uses _big data_ to forecast activities and their characteristics.

_Live data_ and more _analysis capabilities_ are available at [https://vuldb.com/?actor.vadokrist](https://vuldb.com/?actor.vadokrist)

## Countries

These _countries_ are directly (e.g. origin of attacks) or indirectly (e.g. access by proxy) associated with Vadokrist:

* [BR](https://vuldb.com/?country.br)
* [US](https://vuldb.com/?country.us)
* [PT](https://vuldb.com/?country.pt)

## IOC - Indicator of Compromise

These _indicators of compromise_ (IOC) indicate associated network resources which are known to be part of research and attack activities of Vadokrist.

ID | IP address | Hostname | Campaign | Confidence
-- | ---------- | -------- | -------- | ----------
1 | [104.41.26.216](https://vuldb.com/?ip.104.41.26.216) | - | - | High
2 | [104.41.41.216](https://vuldb.com/?ip.104.41.41.216) | - | - | High
3 | [104.41.47.53](https://vuldb.com/?ip.104.41.47.53) | - | - | High
4 | ... | ... | ... | ...

There are 7 more IOC items available. Please use our online service to access the data.

## TTP - Tactics, Techniques, Procedures

_Tactics, techniques, and procedures_ (TTP) summarize the suspected MITRE ATT&CK techniques used by _Vadokrist_. This data is unique as it uses our predictive model for actor profiling.

ID | Technique | Weakness | Description | Confidence
-- | --------- | -------- | ----------- | ----------
1 | T1006 | CWE-22, CWE-23 | Path Traversal | High
2 | T1055 | CWE-74 | Improper Neutralization of Data within XPath Expressions | High
3 | T1059 | CWE-88, CWE-94 | Argument Injection | High
4 | T1059.007 | CWE-79, CWE-80 | Basic Cross Site Scripting | High
5 | T1068 | CWE-250, CWE-264, CWE-266, CWE-267, CWE-268, CWE-269, CWE-272, CWE-284 | Execution with Unnecessary Privileges | High
6 | ... | ... | ... | ...

There are 22 more TTP items available. Please use our online service to access the data.

## IOA - Indicator of Attack

These _indicators of attack_ (IOA) list the potential fragments used for technical activities like reconnaissance, exploitation, privilege escalation, and exfiltration by Vadokrist. This data is unique as it uses our predictive model for actor profiling.

ID | Type | Indicator | Confidence
-- | ---- | --------- | ----------
1 | File | `.claude/settings.json` | High
2 | File | `/api/global/users` | High
3 | File | `/api/v1/challenges//solves` | High
4 | File | `/api/v1/serve/awel/flow/import` | High
5 | File | `/api/w/{workspace}/workspaces/get_settings` | High
6 | File | `/api/wizard/getDualbandSync` | High
7 | File | `/auth/userkey/logout.php` | High
8 | File | `/backend/app/api/v1/module_common/file/controller.py` | High
9 | File | `/boafrm/formDdns` | High
10 | File | `/boafrm/formNtp` | High
11 | File | `/boafrm/formPortFw` | High
12 | File | `/boafrm/formSysLog` | High
13 | File | `/cgi-bin/cstecgi.cgi` | High
14 | File | `/cgi-bin/DownloadCfg/RouterCfm.jpg` | High
15 | File | `/daily-attendance-report.php` | High
16 | File | `/database?action=GetDatabaseAccess` | High
17 | ... | ... | ...

There are 140 more IOA items available (file, library, argument, input value, pattern, network port). Please use our online service to access the data.

## References

The following list contains _external sources_ which discuss the actor and the associated activities:

* https://github.com/eset/malware-ioc/tree/master/vadokrist

## Literature

The following _articles_ explain our unique predictive cyber threat intelligence:

* [VulDB Cyber Threat Intelligence Documentation](https://vuldb.com/?kb.cti)
* [Cyber Threat Intelligence - Early Anticipation of Attacks](https://www.scip.ch/en/?labs.20201022)

## License

(c) [1997-2026](https://vuldb.com/?kb.changelog) by [vuldb.com](https://vuldb.com/?kb.about). All data on this page is shared under the license [CC BY-NC-SA 4.0](https://creativecommons.org/licenses/by-nc-sa/4.0/). Questions? Check the [FAQ](https://vuldb.com/?kb.faq), read the [documentation](https://vuldb.com/?kb) or [contact us](https://vuldb.com/?contact)!
