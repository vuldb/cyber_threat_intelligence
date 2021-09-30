# Konni - Cyber Threat Intelligence

The indicators are related to [VulDB CTI analysis](https://vuldb.com/?doc.cti) of the actor known as [Konni](https://vuldb.com/?actor.konni). The activity monitoring correlates data from social media, forums, chat rooms, and darknet markets. It helps to determine associated actors, activities, intentions, emerging research, and attacks. Our unique predictive model is able to forecast activities and their characteristics.

Live data and more analysis capabilities are available at [https://vuldb.com/?actor.konni](https://vuldb.com/?actor.konni)

## Countries

These countries are directly (e.g. origin of attacks) or indirectly (e.g. access by proxy) associated with Konni:

* US
* CN

## IOC - Indicator of Compromise

These indicators of compromise indicate associated network ressources which are known to be part of research and attack activities of Konni.

ID | IP address | Hostname | Confidence
-- | ---------- | -------- | ----------
1 | 31.170.160.129 | - | High
2 | 31.170.162.63 | - | High
3 | 31.170.163.30 | cpl07.main-hosting.eu | High
4 | ... | ... | ...

There are 4 more IOC items available. Please use our online service to access the data.

## TTP - Tactics, Techniques, Procedures

Tactics, techniques, and procedures summarize the suspected ATT&CK techniques used by Konni. This data is unique as it uses our predictive model for actor profiling.

ID | Technique | Description | Confidence
-- | --------- | ----------- | ----------
1 | T1600 | Cryptographic Issues | High

## IOA - Indicator of Attack

These indicators of attack list the potential fragments used for technical activities like reconnaissance, exploitation, privilege escalation, and exfiltration by Konni. This data is unique as it uses our predictive model for actor profiling.

ID | Type | Indicator | Confidence
-- | ---- | --------- | ----------
1 | File | `application\User\Controller\ProfileController.class.php` | High
2 | File | `banner-edit.php` | High
3 | File | `tmUnblock.cgi` | High
4 | File | `wallet.dat` | Medium
5 | Argument | `imgurl` | Low
6 | Argument | `ttcp_ip` | Low
7 | Input Value | `..\` | Low
8 | Network Port | `tcp/8080` | Medium

## References

The following list contains external sources which discuss the actor and the associated activities:

* https://www.threatminer.org/report.php?q=NewKONNIMalwareattackingEurasiaandSoutheastAsia-PaloAltoNetworksBlog.pdf&y=2018
* https://www.threatminer.org/report.php?q=ThreatSpotlight-KONNI%E2%80%93AStealthyRemoteAccessTrojan-Cylance.pdf&y=2017

## Literature

The following articles explain our unique predictive cyber threat intelligence:

* [VulDB Cyber Threat Intelligence Documentation](https://vuldb.com/?doc.cti)
* [Cyber Threat Intelligence - Early Anticipation of Attacks](https://www.scip.ch/en/?labs.20201022)

## License

(c) [1997-2021](https://vuldb.com/?doc.changelog) by [vuldb.com](https://vuldb.com/?doc.about). All data on this page is shared under the license [CC BY-NC-SA 4.0](https://creativecommons.org/licenses/by-nc-sa/4.0/). Questions? Check the [FAQ](https://vuldb.com/?doc.faq), read the [documentation](https://vuldb.com/?doc) or [contact us](https://vuldb.com/?contact)!
