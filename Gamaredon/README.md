# Gamaredon - Cyber Threat Intelligence

The indicators are related to [VulDB CTI analysis](https://vuldb.com/?doc.cti) of the actor known as [Gamaredon](https://vuldb.com/?actor.gamaredon). The activity monitoring correlates data from social media, forums, chat rooms, and darknet markets. It helps to determine associated actors, activities, intentions, emerging research, and attacks. Our unique predictive model is able to forecast activities and their characteristics.

Live data and more analysis capabilities are available at [https://vuldb.com/?actor.gamaredon](https://vuldb.com/?actor.gamaredon)

## Countries

These countries are directly (e.g. origin of attacks) or indirectly (e.g. access by proxy) associated with Gamaredon:

* RU
* LY
* US
* ...

There are 2 more country items available. Please use our online service to access the data.

## IOC - Indicator of Compromise

These indicators of compromise indicate associated network ressources which are known to be part of research and attack activities of Gamaredon.

ID | IP address | Hostname | Confidence
-- | ---------- | -------- | ----------
1 | 141.8.195.60 | ullir.from.sh | High
2 | 142.93.110.250 | - | High
3 | 176.57.215.115 | 296606-cl92049.tmweb.ru | High
4 | ... | ... | ...

There are 4 more IOC items available. Please use our online service to access the data.

## TTP - Tactics, Techniques, Procedures

Tactics, techniques, and procedures summarize the suspected ATT&CK techniques used by Gamaredon. This data is unique as it uses our predictive model for actor profiling.

ID | Technique | Description | Confidence
-- | --------- | ----------- | ----------
1 | T1059.007 | Cross Site Scripting | High
2 | T1068 | Execution with Unnecessary Privileges | High
3 | T1499 | Resource Consumption | High

## IOA - Indicator of Attack

These indicators of attack list the potential fragments used for technical activities like reconnaissance, exploitation, privilege escalation, and exfiltration by Gamaredon. This data is unique as it uses our predictive model for actor profiling.

ID | Type | Indicator | Confidence
-- | ---- | --------- | ----------
1 | File | `/manager?action=getlogcat` | High
2 | File | `/var/log/nginx` | High
3 | File | `index.php` | Medium
4 | File | `namazu.cgi` | Medium
5 | File | `wp-login.php` | Medium
6 | Library | `vpnapi.dll` | Medium
7 | Argument | `HOST` | Low
8 | Argument | `priority` | Medium
9 | Argument | `Referer` | Low
10 | Input Value | `1" onmouseover=prompt(947671) bad="` | High

## References

The following list contains external sources which discuss the actor and the associated activities:

* https://blog.trendmicro.com/trendlabs-security-intelligence/gamaredon-apt-group-use-covid-19-lure-in-campaigns/
* https://github.com/blackorbird/APT_REPORT/blob/master/Gamaredon/Gamaredon202102_ioc1000%2B.csv
* https://github.com/SentineLabs/Gamaredon-APT/blob/master/2020-02-04-gamaredon-blog-iocs-vk.misp.csv

## Literature

The following articles explain our unique predictive cyber threat intelligence:

* [VulDB Cyber Threat Intelligence Documentation](https://vuldb.com/?doc.cti)
* [Cyber Threat Intelligence - Early Anticipation of Attacks](https://www.scip.ch/en/?labs.20201022)

## License

(c) [1997-2021](https://vuldb.com/?doc.changelog) by [vuldb.com](https://vuldb.com/?doc.about). All data on this page is shared under the license [CC BY-NC-SA 4.0](https://creativecommons.org/licenses/by-nc-sa/4.0/). Questions? Check the [FAQ](https://vuldb.com/?doc.faq), read the [documentation](https://vuldb.com/?doc) or [contact us](https://vuldb.com/?contact)!
