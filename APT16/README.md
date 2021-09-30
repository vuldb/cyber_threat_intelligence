# APT16 - Cyber Threat Intelligence

The indicators are related to [VulDB CTI analysis](https://vuldb.com/?doc.cti) of the actor known as [APT16](https://vuldb.com/?actor.apt16). The activity monitoring correlates data from social media, forums, chat rooms, and darknet markets. It helps to determine associated actors, activities, intentions, emerging research, and attacks. Our unique predictive model is able to forecast activities and their characteristics.

Live data and more analysis capabilities are available at [https://vuldb.com/?actor.apt16](https://vuldb.com/?actor.apt16)

## Countries

These countries are directly (e.g. origin of attacks) or indirectly (e.g. access by proxy) associated with APT16:

* US
* CN

## IOC - Indicator of Compromise

These indicators of compromise indicate associated network ressources which are known to be part of research and attack activities of APT16.

ID | IP address | Hostname | Confidence
-- | ---------- | -------- | ----------
1 | 121.127.249.74 | - | High

## TTP - Tactics, Techniques, Procedures

Tactics, techniques, and procedures summarize the suspected ATT&CK techniques used by APT16. This data is unique as it uses our predictive model for actor profiling.

ID | Technique | Description | Confidence
-- | --------- | ----------- | ----------
1 | T1059.007 | Cross Site Scripting | High
2 | T1068 | Execution with Unnecessary Privileges | High

## IOA - Indicator of Attack

These indicators of attack list the potential fragments used for technical activities like reconnaissance, exploitation, privilege escalation, and exfiltration by APT16. This data is unique as it uses our predictive model for actor profiling.

ID | Type | Indicator | Confidence
-- | ---- | --------- | ----------
1 | File | `/download` | Medium
2 | File | `comment_add.asp` | High
3 | File | `data/gbconfiguration.dat` | High
4 | File | `email.php` | Medium
5 | File | `inc/config.php` | High
6 | File | `inc/filebrowser/browser.php` | High
7 | File | `ogp_show.php` | Medium
8 | File | `register.php` | Medium
9 | Argument | `basePath` | Medium
10 | Argument | `display` | Low
11 | ... | ... | ...

There are 4 more IOA items available. Please use our online service to access the data.

## References

The following list contains external sources which discuss the actor and the associated activities:

* https://www.fireeye.com/blog/threat-research/2015/12/the-eps-awakens-part-two.html

## Literature

The following articles explain our unique predictive cyber threat intelligence:

* [VulDB Cyber Threat Intelligence Documentation](https://vuldb.com/?doc.cti)
* [Cyber Threat Intelligence - Early Anticipation of Attacks](https://www.scip.ch/en/?labs.20201022)

## License

(c) [1997-2021](https://vuldb.com/?doc.changelog) by [vuldb.com](https://vuldb.com/?doc.about). All data on this page is shared under the license [CC BY-NC-SA 4.0](https://creativecommons.org/licenses/by-nc-sa/4.0/). Questions? Check the [FAQ](https://vuldb.com/?doc.faq), read the [documentation](https://vuldb.com/?doc) or [contact us](https://vuldb.com/?contact)!
