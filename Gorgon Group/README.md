# Gorgon Group - Cyber Threat Intelligence

The indicators are related to [VulDB CTI analysis](https://vuldb.com/?doc.cti) of the actor known as [Gorgon Group](https://vuldb.com/?actor.gorgon_group). The activity monitoring correlates data from social media, forums, chat rooms, and darknet markets. It helps to determine associated actors, activities, intentions, emerging research, and attacks. Our unique predictive model is able to forecast activities and their characteristics.

Live data and more analysis capabilities are available at [https://vuldb.com/?actor.gorgon_group](https://vuldb.com/?actor.gorgon_group)

## Countries

These countries are directly (e.g. origin of attacks) or indirectly (e.g. access by proxy) associated with Gorgon Group:

* PK

## IOC - Indicator of Compromise

These indicators of compromise indicate associated network ressources which are known to be part of research and attack activities of Gorgon Group.

ID | IP address | Hostname | Confidence
-- | ---------- | -------- | ----------
1 | 115.186.136.237 | 115-186-136-237.nayatel.pk | High

## TTP - Tactics, Techniques, Procedures

Tactics, techniques, and procedures summarize the suspected ATT&CK techniques used by Gorgon Group. This data is unique as it uses our predictive model for actor profiling.

ID | Technique | Description | Confidence
-- | --------- | ----------- | ----------
1 | T1059.007 | Cross Site Scripting | High
2 | T1068 | Execution with Unnecessary Privileges | High
3 | T1600 | Cryptographic Issues | High

## IOA - Indicator of Attack

These indicators of attack list the potential fragments used for technical activities like reconnaissance, exploitation, privilege escalation, and exfiltration by Gorgon Group. This data is unique as it uses our predictive model for actor profiling.

ID | Type | Indicator | Confidence
-- | ---- | --------- | ----------
1 | File | `/uncpath/` | Medium
2 | File | `app/controllers/frontend/PostController.php` | High
3 | File | `www/soap/application/MCSoap/Logs.php` | High
4 | Argument | `score` | Low
5 | Input Value | `%00` | Low
6 | Input Value | `::$Index_Allocation` | High
7 | Network Port | `Web Server Port` | High

## References

The following list contains external sources which discuss the actor and the associated activities:

* https://unit42.paloaltonetworks.com/unit42-gorgon-group-slithering-nation-state-cybercrime/

## Literature

The following articles explain our unique predictive cyber threat intelligence:

* [VulDB Cyber Threat Intelligence Documentation](https://vuldb.com/?doc.cti)
* [Cyber Threat Intelligence - Early Anticipation of Attacks](https://www.scip.ch/en/?labs.20201022)

## License

(c) [1997-2021](https://vuldb.com/?doc.changelog) by [vuldb.com](https://vuldb.com/?doc.about). All data on this page is shared under the license [CC BY-NC-SA 4.0](https://creativecommons.org/licenses/by-nc-sa/4.0/). Questions? Check the [FAQ](https://vuldb.com/?doc.faq), read the [documentation](https://vuldb.com/?doc) or [contact us](https://vuldb.com/?contact)!
