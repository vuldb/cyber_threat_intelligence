# Nobelium - Cyber Threat Intelligence

The indicators are related to [VulDB CTI analysis](https://vuldb.com/?doc.cti) of the actor known as [Nobelium](https://vuldb.com/?actor.nobelium). The activity monitoring correlates data from social media, forums, chat rooms, and darknet markets. It helps to determine associated actors, activities, intentions, emerging research, and attacks. Our unique predictive model is able to forecast activities and their characteristics.

Live data and more analysis capabilities are available at [https://vuldb.com/?actor.nobelium](https://vuldb.com/?actor.nobelium)

## Countries

These countries are directly (e.g. origin of attacks) or indirectly (e.g. access by proxy) associated with Nobelium:

* CN
* US

## IOC - Indicator of Compromise

These indicators of compromise indicate associated network ressources which are known to be part of research and attack activities of Nobelium.

ID | IP address | Hostname | Confidence
-- | ---------- | -------- | ----------
1 | 83.171.237.173 | 83.171.237.173.static.as201206.net | High
2 | 192.99.221.77 | ip77.ip-192-99-221.net | High

## TTP - Tactics, Techniques, Procedures

Tactics, techniques, and procedures summarize the suspected ATT&CK techniques used by Nobelium. This data is unique as it uses our predictive model for actor profiling.

ID | Technique | Description | Confidence
-- | --------- | ----------- | ----------
1 | T1068 | Execution with Unnecessary Privileges | High

## IOA - Indicator of Attack

These indicators of attack list the potential fragments used for technical activities like reconnaissance, exploitation, privilege escalation, and exfiltration by Nobelium. This data is unique as it uses our predictive model for actor profiling.

ID | Type | Indicator | Confidence
-- | ---- | --------- | ----------
1 | File | `/notice-edit.php` | High
2 | File | `burl.c` | Low
3 | File | `http_auth.c` | Medium
4 | File | `ViewLog.asp` | Medium
5 | Argument | `aid` | Low
6 | Argument | `remote_host` | Medium
7 | Input Value | `%3bping+-c+3+10.0.99.102%3b%23` | High
8 | Input Value | `/%2F` | Low

## References

The following list contains external sources which discuss the actor and the associated activities:

* https://www.microsoft.com/security/blog/2021/05/27/new-sophisticated-email-based-attack-from-nobelium/

## Literature

The following articles explain our unique predictive cyber threat intelligence:

* [VulDB Cyber Threat Intelligence Documentation](https://vuldb.com/?doc.cti)
* [Cyber Threat Intelligence - Early Anticipation of Attacks](https://www.scip.ch/en/?labs.20201022)

## License

(c) [1997-2021](https://vuldb.com/?doc.changelog) by [vuldb.com](https://vuldb.com/?doc.about). All data on this page is shared under the license [CC BY-NC-SA 4.0](https://creativecommons.org/licenses/by-nc-sa/4.0/). Questions? Check the [FAQ](https://vuldb.com/?doc.faq), read the [documentation](https://vuldb.com/?doc) or [contact us](https://vuldb.com/?contact)!
