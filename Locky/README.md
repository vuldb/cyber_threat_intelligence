# Locky - Cyber Threat Intelligence

The indicators are related to [VulDB CTI analysis](https://vuldb.com/?doc.cti) of the actor known as [Locky](https://vuldb.com/?actor.locky). The activity monitoring correlates data from social media, forums, chat rooms, and darknet markets. It helps to determine associated actors, activities, intentions, emerging research, and attacks. Our unique predictive model is able to forecast activities and their characteristics.

Live data and more analysis capabilities are available at [https://vuldb.com/?actor.locky](https://vuldb.com/?actor.locky)

## Countries

These countries are directly (e.g. origin of attacks) or indirectly (e.g. access by proxy) associated with Locky:

* US
* RU
* UA

## IOC - Indicator of Compromise

These indicators of compromise indicate associated network ressources which are known to be part of research and attack activities of Locky.

ID | IP address | Hostname | Confidence
-- | ---------- | -------- | ----------
1 | 5.173.164.205 | user-5-173-164-205.play-internet.pl | High
2 | 46.38.52.225 | free.tel.ru | High
3 | 46.101.8.169 | - | High
4 | 46.148.20.32 | sa3.net.ua | High
5 | 51.254.181.122 | mail2.asiaecampaign.com | High
6 | ... | ... | ...

There are 10 more IOC items available. Please use our online service to access the data.

## TTP - Tactics, Techniques, Procedures

Tactics, techniques, and procedures summarize the suspected ATT&CK techniques used by Locky. This data is unique as it uses our predictive model for actor profiling.

ID | Technique | Description | Confidence
-- | --------- | ----------- | ----------
1 | T1059.007 | Cross Site Scripting | High
2 | T1068 | Execution with Unnecessary Privileges | High
3 | T1499 | Resource Consumption | High
4 | ... | ... | ...

There are 1 more TTP items available. Please use our online service to access the data.

## IOA - Indicator of Attack

These indicators of attack list the potential fragments used for technical activities like reconnaissance, exploitation, privilege escalation, and exfiltration by Locky. This data is unique as it uses our predictive model for actor profiling.

ID | Type | Indicator | Confidence
-- | ---- | --------- | ----------
1 | File | `/dev/fd` | Low
2 | File | `/inc/HTTPClient.php` | High
3 | File | `/index.php?controller=calendar&format=raw&cat[0]=SQLi&task=events` | High
4 | File | `/ISAPI/Security/users/1` | High
5 | File | `addentry.php` | Medium
6 | File | `data/gbconfiguration.dat` | High
7 | File | `email.php` | Medium
8 | File | `flac.c` | Low
9 | File | `inc/config.php` | High
10 | File | `inc/filebrowser/browser.php` | High
11 | ... | ... | ...

There are 43 more IOA items available. Please use our online service to access the data.

## References

The following list contains external sources which discuss the actor and the associated activities:

* https://github.com/fl0x2208/IOCs-in-CSV-format/blob/6297513d672bd69f1bf488018035892e599e7a9c/locky%20ransomware.csv
* https://unit42.paloaltonetworks.com/locky-ransomware-installed-through-nuclear-ek/

## Literature

The following articles explain our unique predictive cyber threat intelligence:

* [VulDB Cyber Threat Intelligence Documentation](https://vuldb.com/?doc.cti)
* [Cyber Threat Intelligence - Early Anticipation of Attacks](https://www.scip.ch/en/?labs.20201022)

## License

(c) [1997-2021](https://vuldb.com/?doc.changelog) by [vuldb.com](https://vuldb.com/?doc.about). All data on this page is shared under the license [CC BY-NC-SA 4.0](https://creativecommons.org/licenses/by-nc-sa/4.0/). Questions? Check the [FAQ](https://vuldb.com/?doc.faq), read the [documentation](https://vuldb.com/?doc) or [contact us](https://vuldb.com/?contact)!
