# ProLock - Cyber Threat Intelligence

The indicators are related to [VulDB CTI analysis](https://vuldb.com/?doc.cti) of the actor known as [ProLock](https://vuldb.com/?actor.prolock). The activity monitoring correlates data from social media, forums, chat rooms, and darknet markets. It helps to determine associated actors, activities, intentions, emerging research, and attacks. Our unique predictive model is able to forecast activities and their characteristics.

Live data and more analysis capabilities are available at [https://vuldb.com/?actor.prolock](https://vuldb.com/?actor.prolock)

## Countries

These countries are directly (e.g. origin of attacks) or indirectly (e.g. access by proxy) associated with ProLock:

* RU

## IOC - Indicator of Compromise

These indicators of compromise indicate associated network ressources which are known to be part of research and attack activities of ProLock.

ID | IP address | Hostname | Confidence
-- | ---------- | -------- | ----------
1 | 185.212.128.8 | alpha.casino | High

## TTP - Tactics, Techniques, Procedures

Tactics, techniques, and procedures summarize the suspected ATT&CK techniques used by ProLock. This data is unique as it uses our predictive model for actor profiling.

ID | Technique | Description | Confidence
-- | --------- | ----------- | ----------
1 | T1068 | Execution with Unnecessary Privileges | High

## IOA - Indicator of Attack

These indicators of attack list the potential fragments used for technical activities like reconnaissance, exploitation, privilege escalation, and exfiltration by ProLock. This data is unique as it uses our predictive model for actor profiling.

ID | Type | Indicator | Confidence
-- | ---- | --------- | ----------
1 | File | `category.php` | Medium
2 | File | `Unlock.exe` | Medium
3 | File | `wp-admin/media-upload.php` | High
4 | File | `wp-content/uploads` | High
5 | File | `wp-content/uploads/tmm_db_migrate/wp_users.dat` | High
6 | Argument | `post_id` | Low
7 | Argument | `site` | Low
8 | Argument | `user_login/user_pass/user_email` | High

## References

The following list contains external sources which discuss the actor and the associated activities:

* https://github.com/sophoslabs/IoCs/blob/master/Ransomware-ProLock.csv

## Literature

The following articles explain our unique predictive cyber threat intelligence:

* [VulDB Cyber Threat Intelligence Documentation](https://vuldb.com/?doc.cti)
* [Cyber Threat Intelligence - Early Anticipation of Attacks](https://www.scip.ch/en/?labs.20201022)

## License

(c) [1997-2021](https://vuldb.com/?doc.changelog) by [vuldb.com](https://vuldb.com/?doc.about). All data on this page is shared under the license [CC BY-NC-SA 4.0](https://creativecommons.org/licenses/by-nc-sa/4.0/). Questions? Check the [FAQ](https://vuldb.com/?doc.faq), read the [documentation](https://vuldb.com/?doc) or [contact us](https://vuldb.com/?contact)!
