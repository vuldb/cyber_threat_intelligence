# Windigo - Cyber Threat Intelligence

The indicators are related to [VulDB CTI analysis](https://vuldb.com/?doc.cti) of the actor known as [Windigo](https://vuldb.com/?actor.windigo). The activity monitoring correlates data from social media, forums, chat rooms, and darknet markets. It helps to determine associated actors, activities, intentions, emerging research, and attacks. Our unique predictive model is able to forecast activities and their characteristics.

Live data and more analysis capabilities are available at [https://vuldb.com/?actor.windigo](https://vuldb.com/?actor.windigo)

## Campaigns

The following campaigns are known and can be associated with Windigo:

* Windigo

## Countries

These countries are directly (e.g. origin of attacks) or indirectly (e.g. access by proxy) associated with Windigo:

* FR
* DE

## IOC - Indicator of Compromise

These indicators of compromise indicate associated network ressources which are known to be part of research and attack activities of Windigo.

ID | IP address | Hostname | Confidence
-- | ---------- | -------- | ----------
1 | 77.67.80.31 | - | High
2 | 85.214.80.4 | h2463956.stratoserver.net | High
3 | 94.23.208.20 | ns321476.ip-94-23-208.eu | High

## TTP - Tactics, Techniques, Procedures

Tactics, techniques, and procedures summarize the suspected ATT&CK techniques used by Windigo. This data is unique as it uses our predictive model for actor profiling.

ID | Technique | Description | Confidence
-- | --------- | ----------- | ----------
1 | T1059.007 | Cross Site Scripting | High
2 | T1068 | Execution with Unnecessary Privileges | High

## IOA - Indicator of Attack

These indicators of attack list the potential fragments used for technical activities like reconnaissance, exploitation, privilege escalation, and exfiltration by Windigo. This data is unique as it uses our predictive model for actor profiling.

ID | Type | Indicator | Confidence
-- | ---- | --------- | ----------
1 | File | `/uncpath/` | Medium
2 | File | `/var/log/restjavad.0.log` | High
3 | File | `init.php` | Medium
4 | File | `products.php` | Medium
5 | File | `virtualinput.cgi` | High
6 | Argument | `id` | Low
7 | Argument | `IEM_CookieLogin` | High
8 | Input Value | `[\w]*` | Low

## References

The following list contains external sources which discuss the actor and the associated activities:

* https://github.com/eset/malware-ioc/tree/master/windigo

## Literature

The following articles explain our unique predictive cyber threat intelligence:

* [VulDB Cyber Threat Intelligence Documentation](https://vuldb.com/?doc.cti)
* [Cyber Threat Intelligence - Early Anticipation of Attacks](https://www.scip.ch/en/?labs.20201022)

## License

(c) [1997-2021](https://vuldb.com/?doc.changelog) by [vuldb.com](https://vuldb.com/?doc.about). All data on this page is shared under the license [CC BY-NC-SA 4.0](https://creativecommons.org/licenses/by-nc-sa/4.0/). Questions? Check the [FAQ](https://vuldb.com/?doc.faq), read the [documentation](https://vuldb.com/?doc) or [contact us](https://vuldb.com/?contact)!
