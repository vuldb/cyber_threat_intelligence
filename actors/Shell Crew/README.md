# Shell Crew - Cyber Threat Intelligence

These _indicators_ were reported, collected, and generated during the [VulDB CTI analysis](https://vuldb.com/?kb.cti) of the actor known as [Shell Crew](https://vuldb.com/?actor.shell_crew). The _activity monitoring_ correlates data from social media, forums, chat rooms, and darknet markets. It helps to determine associated actors, specific activities, expected intentions, emerging research, and ongoing attacks. Our unique _predictive model_ uses _big data_ to forecast activities and their characteristics.

_Live data_ and more _analysis capabilities_ are available at [https://vuldb.com/?actor.shell_crew](https://vuldb.com/?actor.shell_crew)

## Campaigns

The following _campaigns_ are known and can be associated with Shell Crew:

* StreamEx

## Countries

These _countries_ are directly (e.g. origin of attacks) or indirectly (e.g. access by proxy) associated with Shell Crew:

* [US](https://vuldb.com/?country.us)
* [CN](https://vuldb.com/?country.cn)
* [ES](https://vuldb.com/?country.es)
* ...

There are 25 more country items available. Please use our online service to access the data.

## IOC - Indicator of Compromise

These _indicators of compromise_ (IOC) indicate associated network resources which are known to be part of research and attack activities of Shell Crew.

ID | IP address | Hostname | Campaign | Confidence
-- | ---------- | -------- | -------- | ----------
1 | [12.0.742.112](https://vuldb.com/?ip.12.0.742.112) | - | - | High
2 | [31.210.102.210](https://vuldb.com/?ip.31.210.102.210) | . | StreamEx | High
3 | [43.249.81.209](https://vuldb.com/?ip.43.249.81.209) | - | StreamEx | High
4 | [43.249.81.210](https://vuldb.com/?ip.43.249.81.210) | - | - | High
5 | [50.115.138.215](https://vuldb.com/?ip.50.115.138.215) | 50-115-138-215.genericreverse.com | - | High
6 | ... | ... | ... | ...

There are 22 more IOC items available. Please use our online service to access the data.

## TTP - Tactics, Techniques, Procedures

_Tactics, techniques, and procedures_ (TTP) summarize the suspected MITRE ATT&CK techniques used by _Shell Crew_. This data is unique as it uses our predictive model for actor profiling.

ID | Technique | Weakness | Description | Confidence
-- | --------- | -------- | ----------- | ----------
1 | T1059.007 | CWE-79, CWE-80 | Cross Site Scripting | High
2 | T1068 | CWE-264, CWE-266, CWE-284 | Execution with Unnecessary Privileges | High
3 | T1110.001 | CWE-307, CWE-798 | Improper Restriction of Excessive Authentication Attempts | High
4 | ... | ... | ... | ...

There are 4 more TTP items available. Please use our online service to access the data.

## IOA - Indicator of Attack

These _indicators of attack_ (IOA) list the potential fragments used for technical activities like reconnaissance, exploitation, privilege escalation, and exfiltration by Shell Crew. This data is unique as it uses our predictive model for actor profiling.

ID | Type | Indicator | Confidence
-- | ---- | --------- | ----------
1 | File | `/+CSCOE+/logon.html` | High
2 | File | `/?module=users&section=cpanel&page=list` | High
3 | File | `/admin/powerline` | High
4 | File | `/admin/syslog` | High
5 | File | `/api/upload` | Medium
6 | File | `/cgi-bin` | Medium
7 | File | `/cgi-bin/kerbynet` | High
8 | File | `/context/%2e/WEB-INF/web.xml` | High
9 | File | `/dcim/sites/add/` | High
10 | File | `/EXCU_SHELL` | Medium
11 | File | `/forum/away.php` | High
12 | File | `/fudforum/adm/hlplist.php` | High
13 | File | `/login` | Low
14 | File | `/Main_Login.asp?flag=1&productname=RT-AC88U&url=/downloadmaster/task.asp` | High
15 | File | `/modules/profile/index.php` | High
16 | File | `/monitoring` | Medium
17 | File | `/new` | Low
18 | File | `/proc/<pid>/status` | High
19 | File | `/public/plugins/` | High
20 | File | `/rom` | Low
21 | File | `/scripts/killpvhost` | High
22 | File | `/secure/admin/InsightDefaultCustomFieldConfig.jspa` | High
23 | File | `/secure/QueryComponent!Default.jspa` | High
24 | File | `/src/main/java/com/dotmarketing/filters/CMSFilter.java` | High
25 | File | `/tmp` | Low
26 | File | `/tmp/redis.ds` | High
27 | File | `/uncpath/` | Medium
28 | File | `/ViewUserHover.jspa` | High
29 | File | `/wp-admin` | Medium
30 | File | `/wp-json/wc/v3/webhooks` | High
31 | File | `14all.cgi/14all-1.1.cgi/traffic.cgi/mrtg.cgi` | High
32 | File | `AccountManagerService.java` | High
33 | File | `actions/CompanyDetailsSave.php` | High
34 | File | `ActiveServices.java` | High
35 | File | `ActivityManagerService.java` | High
36 | File | `addlink.php` | Medium
37 | File | `addtocart.asp` | High
38 | ... | ... | ...

There are 329 more IOA items available (file, library, argument, input value, pattern, network port). Please use our online service to access the data.

## References

The following list contains _external sources_ which discuss the actor and the associated activities:

* https://blogs.blackberry.com/en/2017/02/shell-crew-variants-continue-to-fly-under-big-avs-radar
* https://www.threatminer.org/report.php?q=RSAIncidentResponseEmergingThreatProfile_ShellCrew.pdf&y=2014
* https://www.threatminer.org/report.php?q=ShellCrewVariantsContinuetoFlyUnderBigAV%E2%80%99sRadar-Cylance.pdf&y=2017

## Literature

The following _articles_ explain our unique predictive cyber threat intelligence:

* [VulDB Cyber Threat Intelligence Documentation](https://vuldb.com/?kb.cti)
* [Cyber Threat Intelligence - Early Anticipation of Attacks](https://www.scip.ch/en/?labs.20201022)

## License

(c) [1997-2022](https://vuldb.com/?kb.changelog) by [vuldb.com](https://vuldb.com/?kb.about). All data on this page is shared under the license [CC BY-NC-SA 4.0](https://creativecommons.org/licenses/by-nc-sa/4.0/). Questions? Check the [FAQ](https://vuldb.com/?kb.faq), read the [documentation](https://vuldb.com/?kb) or [contact us](https://vuldb.com/?contact)!
