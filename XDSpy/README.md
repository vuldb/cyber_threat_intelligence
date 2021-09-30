# XDSpy - Cyber Threat Intelligence

The indicators are related to [VulDB CTI analysis](https://vuldb.com/?doc.cti) of the actor known as [XDSpy](https://vuldb.com/?actor.xdspy). The activity monitoring correlates data from social media, forums, chat rooms, and darknet markets. It helps to determine associated actors, activities, intentions, emerging research, and attacks. Our unique predictive model is able to forecast activities and their characteristics.

Live data and more analysis capabilities are available at [https://vuldb.com/?actor.xdspy](https://vuldb.com/?actor.xdspy)

## Countries

These countries are directly (e.g. origin of attacks) or indirectly (e.g. access by proxy) associated with XDSpy:

* US
* ES
* GB

## IOC - Indicator of Compromise

These indicators of compromise indicate associated network ressources which are known to be part of research and attack activities of XDSpy.

ID | IP address | Hostname | Confidence
-- | ---------- | -------- | ----------
1 | 62.213.213.170 | 62-213-213-170.ip.stuart.be | High
2 | 93.63.198.40 | 93-63-198-40.ip352.fastwebnet.it | High
3 | 95.215.60.53 | 53-60-215-95.cust.briod.net | High

## TTP - Tactics, Techniques, Procedures

Tactics, techniques, and procedures summarize the suspected ATT&CK techniques used by XDSpy. This data is unique as it uses our predictive model for actor profiling.

ID | Technique | Description | Confidence
-- | --------- | ----------- | ----------
1 | T1059.007 | Cross Site Scripting | High
2 | T1068 | Execution with Unnecessary Privileges | High

## IOA - Indicator of Attack

These indicators of attack list the potential fragments used for technical activities like reconnaissance, exploitation, privilege escalation, and exfiltration by XDSpy. This data is unique as it uses our predictive model for actor profiling.

ID | Type | Indicator | Confidence
-- | ---- | --------- | ----------
1 | File | `data/gbconfiguration.dat` | High
2 | File | `functions.inc.php` | High
3 | File | `inc/config.php` | High
4 | File | `text.ctrl.php` | High
5 | Argument | `basePath` | Medium
6 | Argument | `Content-Length` | High
7 | Argument | `level` | Low
8 | Argument | `show_alias` | Medium
9 | Pattern | `Content-Length|3A|` | High

## References

The following list contains external sources which discuss the actor and the associated activities:

* https://github.com/eset/malware-ioc/tree/master/xdspy

## Literature

The following articles explain our unique predictive cyber threat intelligence:

* [VulDB Cyber Threat Intelligence Documentation](https://vuldb.com/?doc.cti)
* [Cyber Threat Intelligence - Early Anticipation of Attacks](https://www.scip.ch/en/?labs.20201022)

## License

(c) [1997-2021](https://vuldb.com/?doc.changelog) by [vuldb.com](https://vuldb.com/?doc.about). All data on this page is shared under the license [CC BY-NC-SA 4.0](https://creativecommons.org/licenses/by-nc-sa/4.0/). Questions? Check the [FAQ](https://vuldb.com/?doc.faq), read the [documentation](https://vuldb.com/?doc) or [contact us](https://vuldb.com/?contact)!
