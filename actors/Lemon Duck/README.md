# Lemon Duck - Cyber Threat Intelligence

These _indicators_ were collected during the [VulDB CTI analysis](https://vuldb.com/?kb.cti) of the actor known as [Lemon Duck](https://vuldb.com/?actor.lemon_duck). The _activity monitoring_ correlates data from social media, forums, chat rooms, and darknet markets. It helps to determine associated actors, specific activities, expected intentions, emerging research, and ongoing attacks. Our unique _predictive model_ is able to forecast activities and their characteristics.

_Live data_ and more _analysis capabilities_ are available at [https://vuldb.com/?actor.lemon_duck](https://vuldb.com/?actor.lemon_duck)

## Countries

These _countries_ are directly (e.g. origin of attacks) or indirectly (e.g. access by proxy) associated with Lemon Duck:

* VN
* CN
* US

## IOC - Indicator of Compromise

These _indicators of compromise_ (IOC) indicate associated network resources which are known to be part of research and attack activities of Lemon Duck.

ID | IP address | Hostname | Campaign | Confidence
-- | ---------- | -------- | -------- | ----------
1 | 1.202.15.246 | 246.15.202.1.static.bjtelecom.net | - | High
2 | 27.195.157.70 | - | - | High
3 | 36.48.94.254 | - | - | High
4 | 36.110.1.222 | 222.1.110.36.static.bjtelecom.net | - | High
5 | 40.68.42.171 | - | - | High
6 | 42.7.4.88 | - | - | High
7 | 42.7.31.243 | - | - | High
8 | 42.176.133.183 | - | - | High
9 | 49.71.208.124 | - | - | High
10 | 49.147.72.67 | dsl.49.148.72.67.pldt.net | - | High
11 | 51.36.170.221 | - | - | High
12 | 58.56.135.198 | - | - | High
13 | 58.62.125.245 | - | - | High
14 | 58.221.24.178 | - | - | High
15 | 58.251.2.115 | reverse.gdsz.cncnet.net | - | High
16 | 59.111.181.116 | - | - | High
17 | 59.175.154.97 | - | - | High
18 | 60.10.56.169 | hebei.10.60.in-addr.arpa | - | High
19 | ... | ... | ... | ...

There are 71 more IOC items available. Please use our online service to access the data.

## TTP - Tactics, Techniques, Procedures

_Tactics, techniques, and procedures_ (TTP) summarize the suspected ATT&CK techniques used by Lemon Duck. This data is unique as it uses our predictive model for actor profiling.

ID | Technique | Weakness | Description | Confidence
-- | --------- | -------- | ----------- | ----------
1 | T1059.007 | CWE-79, CWE-80 | Cross Site Scripting | High
2 | T1068 | CWE-264, CWE-284 | Execution with Unnecessary Privileges | High
3 | T1110.001 | CWE-798 | Improper Restriction of Excessive Authentication Attempts | High
4 | ... | ... | ... | ...

There are 7 more TTP items available. Please use our online service to access the data.

## IOA - Indicator of Attack

These _indicators of attack_ (IOA) list the potential fragments used for technical activities like reconnaissance, exploitation, privilege escalation, and exfiltration by Lemon Duck. This data is unique as it uses our predictive model for actor profiling.

ID | Type | Indicator | Confidence
-- | ---- | --------- | ----------
1 | File | `./clients/client` | High
2 | File | `/alumni/admin/ajax.php?action=save_settings` | High
3 | File | `/assets/ctx` | Medium
4 | File | `/cgi-bin/luci` | High
5 | File | `/cimom` | Low
6 | File | `/config/getuser` | High
7 | File | `/export` | Low
8 | File | `/gcp/roleset/*` | High
9 | File | `/hostapd` | Medium
10 | File | `/iisadmpwd` | Medium
11 | File | `/IISADMPWD` | Medium
12 | File | `/include/chart_generator.php` | High
13 | File | `/pro/repo-create.html` | High
14 | File | `/proc/sysvipc/sem` | High
15 | File | `/public/login.htm` | High
16 | File | `/public/plugins/` | High
17 | File | `/rest/api/1.0/render` | High
18 | File | `/rest/api/latest/user/avatar/temporary` | High
19 | File | `/secure/admin/ConfigureBatching!default.jspa` | High
20 | File | `/sm/api/v1/firewall/zone/services` | High
21 | File | `/sys/attachment/uploaderServlet` | High
22 | File | `/uncpath/` | Medium
23 | File | `/userRpm/popupSiteSurveyRpm.html` | High
24 | File | `/users/{id}` | Medium
25 | ... | ... | ...

There are 206 more IOA items available (file, library, argument, input value, pattern, network port). Please use our online service to access the data.

## References

The following list contains _external sources_ which discuss the actor and the associated activities:

* https://github.com/guardicore/labs_campaigns/tree/master/Lemon_Duck

## Literature

The following _articles_ explain our unique predictive cyber threat intelligence:

* [VulDB Cyber Threat Intelligence Documentation](https://vuldb.com/?kb.cti)
* [Cyber Threat Intelligence - Early Anticipation of Attacks](https://www.scip.ch/en/?labs.20201022)

## License

(c) [1997-2022](https://vuldb.com/?kb.changelog) by [vuldb.com](https://vuldb.com/?kb.about). All data on this page is shared under the license [CC BY-NC-SA 4.0](https://creativecommons.org/licenses/by-nc-sa/4.0/). Questions? Check the [FAQ](https://vuldb.com/?kb.faq), read the [documentation](https://vuldb.com/?kb) or [contact us](https://vuldb.com/?contact)!