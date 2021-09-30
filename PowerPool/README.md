# PowerPool - Cyber Threat Intelligence

The indicators are related to [VulDB CTI analysis](https://vuldb.com/?doc.cti) of the actor known as [PowerPool](https://vuldb.com/?actor.powerpool). The activity monitoring correlates data from social media, forums, chat rooms, and darknet markets. It helps to determine associated actors, activities, intentions, emerging research, and attacks. Our unique predictive model is able to forecast activities and their characteristics.

Live data and more analysis capabilities are available at [https://vuldb.com/?actor.powerpool](https://vuldb.com/?actor.powerpool)

## Countries

These countries are directly (e.g. origin of attacks) or indirectly (e.g. access by proxy) associated with PowerPool:

* CN
* US
* KR

## IOC - Indicator of Compromise

These indicators of compromise indicate associated network ressources which are known to be part of research and attack activities of PowerPool.

ID | IP address | Hostname | Confidence
-- | ---------- | -------- | ----------
1 | 27.102.106.149 | - | High

## TTP - Tactics, Techniques, Procedures

Tactics, techniques, and procedures summarize the suspected ATT&CK techniques used by PowerPool. This data is unique as it uses our predictive model for actor profiling.

ID | Technique | Description | Confidence
-- | --------- | ----------- | ----------
1 | T1059.007 | Cross Site Scripting | High
2 | T1068 | Execution with Unnecessary Privileges | High
3 | T1600 | Cryptographic Issues | High

## IOA - Indicator of Attack

These indicators of attack list the potential fragments used for technical activities like reconnaissance, exploitation, privilege escalation, and exfiltration by PowerPool. This data is unique as it uses our predictive model for actor profiling.

ID | Type | Indicator | Confidence
-- | ---- | --------- | ----------
1 | File | `autologin.cgi` | High
2 | File | `command.php` | Medium
3 | File | `email.php` | Medium
4 | File | `html/install.php` | High
5 | File | `libpbc.a` | Medium
6 | File | `register/check/username?username` | High
7 | File | `SkSwizzler.cpp` | High
8 | Argument | `cmd` | Low
9 | Argument | `id` | Low
10 | Input Value | `.%00.../.%00.../` | High

## References

The following list contains external sources which discuss the actor and the associated activities:

* https://github.com/eset/malware-ioc/tree/master/powerpool

## Literature

The following articles explain our unique predictive cyber threat intelligence:

* [VulDB Cyber Threat Intelligence Documentation](https://vuldb.com/?doc.cti)
* [Cyber Threat Intelligence - Early Anticipation of Attacks](https://www.scip.ch/en/?labs.20201022)

## License

(c) [1997-2021](https://vuldb.com/?doc.changelog) by [vuldb.com](https://vuldb.com/?doc.about). All data on this page is shared under the license [CC BY-NC-SA 4.0](https://creativecommons.org/licenses/by-nc-sa/4.0/). Questions? Check the [FAQ](https://vuldb.com/?doc.faq), read the [documentation](https://vuldb.com/?doc) or [contact us](https://vuldb.com/?contact)!
