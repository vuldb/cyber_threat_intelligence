# OnionDog - Cyber Threat Intelligence

The indicators are related to [VulDB CTI analysis](https://vuldb.com/?doc.cti) of the actor known as [OnionDog](https://vuldb.com/?actor.oniondog). The activity monitoring correlates data from social media, forums, chat rooms, and darknet markets. It helps to determine associated actors, activities, intentions, emerging research, and attacks. Our unique predictive model is able to forecast activities and their characteristics.

Live data and more analysis capabilities are available at [https://vuldb.com/?actor.oniondog](https://vuldb.com/?actor.oniondog)

## Countries

These countries are directly (e.g. origin of attacks) or indirectly (e.g. access by proxy) associated with OnionDog:

* KR
* US

## IOC - Indicator of Compromise

These indicators of compromise indicate associated network ressources which are known to be part of research and attack activities of OnionDog.

ID | IP address | Hostname | Confidence
-- | ---------- | -------- | ----------
1 | 112.169.154.65 | - | High
2 | 121.133.8.2 | - | High
3 | 218.145.131.1 | - | High
4 | 218.145.131.130 | - | High
5 | ... | ... | ...

There are 6 more IOC items available. Please use our online service to access the data.

## TTP - Tactics, Techniques, Procedures

Tactics, techniques, and procedures summarize the suspected ATT&CK techniques used by OnionDog. This data is unique as it uses our predictive model for actor profiling.

ID | Technique | Description | Confidence
-- | --------- | ----------- | ----------
1 | T1059.007 | Cross Site Scripting | High
2 | T1068 | Execution with Unnecessary Privileges | High
3 | T1110.001 | Improper Restriction of Excessive Authentication Attempts | High
4 | ... | ... | ...

There are 2 more TTP items available. Please use our online service to access the data.

## IOA - Indicator of Attack

These indicators of attack list the potential fragments used for technical activities like reconnaissance, exploitation, privilege escalation, and exfiltration by OnionDog. This data is unique as it uses our predictive model for actor profiling.

ID | Type | Indicator | Confidence
-- | ---- | --------- | ----------
1 | File | `/proc/<pid>/status` | High
2 | File | `/var/passwd` | Medium
3 | File | `ext/phar/phar_object.c` | High
4 | File | `htdocs/web/wpsacts.php` | High
5 | File | `kernel/events/core.c` | High
6 | File | `list.php` | Medium
7 | File | `nmconsole/login.asp` | High
8 | File | `pdf/pdf-xref.c` | High
9 | File | `view.php` | Medium
10 | Argument | `action` | Low
11 | ... | ... | ...

There are 6 more IOA items available. Please use our online service to access the data.

## References

The following list contains external sources which discuss the actor and the associated activities:

* https://www.threatminer.org/report.php?q=Operation_OnionDog-20160520-_360.pdf&y=2016
* https://www.threatminer.org/report.php?q=TrendLabsSecurityIntelligenceBlogOnionDogisnotaTargetedAttack%E2%80%94It%E2%80%99saCyberDrill-TrendLabsSecurityIntelligenceBlog.pdf&y=2017

## Literature

The following articles explain our unique predictive cyber threat intelligence:

* [VulDB Cyber Threat Intelligence Documentation](https://vuldb.com/?doc.cti)
* [Cyber Threat Intelligence - Early Anticipation of Attacks](https://www.scip.ch/en/?labs.20201022)

## License

(c) [1997-2021](https://vuldb.com/?doc.changelog) by [vuldb.com](https://vuldb.com/?doc.about). All data on this page is shared under the license [CC BY-NC-SA 4.0](https://creativecommons.org/licenses/by-nc-sa/4.0/). Questions? Check the [FAQ](https://vuldb.com/?doc.faq), read the [documentation](https://vuldb.com/?doc) or [contact us](https://vuldb.com/?contact)!
