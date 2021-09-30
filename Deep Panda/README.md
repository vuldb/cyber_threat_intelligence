# Deep Panda - Cyber Threat Intelligence

The indicators are related to [VulDB CTI analysis](https://vuldb.com/?doc.cti) of the actor known as [Deep Panda](https://vuldb.com/?actor.deep_panda). The activity monitoring correlates data from social media, forums, chat rooms, and darknet markets. It helps to determine associated actors, activities, intentions, emerging research, and attacks. Our unique predictive model is able to forecast activities and their characteristics.

Live data and more analysis capabilities are available at [https://vuldb.com/?actor.deep_panda](https://vuldb.com/?actor.deep_panda)

## Countries

These countries are directly (e.g. origin of attacks) or indirectly (e.g. access by proxy) associated with Deep Panda:

* CA
* US

## IOC - Indicator of Compromise

These indicators of compromise indicate associated network ressources which are known to be part of research and attack activities of Deep Panda.

ID | IP address | Hostname | Confidence
-- | ---------- | -------- | ----------
1 | 1.9.5.38 | - | High
2 | 142.91.76.134 | mx3.29v.info | High
3 | 184.71.210.4 | - | High
4 | ... | ... | ...

There are 3 more IOC items available. Please use our online service to access the data.

## TTP - Tactics, Techniques, Procedures

Tactics, techniques, and procedures summarize the suspected ATT&CK techniques used by Deep Panda. This data is unique as it uses our predictive model for actor profiling.

ID | Technique | Description | Confidence
-- | --------- | ----------- | ----------
1 | T1068 | Execution with Unnecessary Privileges | High
2 | T1222 | Permission Issues | High

## IOA - Indicator of Attack

These indicators of attack list the potential fragments used for technical activities like reconnaissance, exploitation, privilege escalation, and exfiltration by Deep Panda. This data is unique as it uses our predictive model for actor profiling.

ID | Type | Indicator | Confidence
-- | ---- | --------- | ----------
1 | File | `fs/aio.c` | Medium
2 | File | `index.php?mod=main&opt=personal` | High
3 | File | `pkg/tool/path.go` | High
4 | File | `receiver.c` | Medium
5 | File | `routes/api/v1/api.go` | High
6 | Argument | `avatar_file` | Medium
7 | Argument | `m1_idlist` | Medium

## References

The following list contains external sources which discuss the actor and the associated activities:

* https://threatconnect.com/blog/the-anthem-hack-all-roads-lead-to-china/
* https://www.rsa.com/content/dam/en/white-paper/rsa-incident-response-emerging-threat-profile-shell-crew.pdf
* https://www.threatminer.org/report.php?q=AdversaryIntelligenceReport_DeepPanda_01.pdf&y=2014
* https://www.threatminer.org/report.php?q=DEEP_PANDA_Sakula.pdf&y=2014

## Literature

The following articles explain our unique predictive cyber threat intelligence:

* [VulDB Cyber Threat Intelligence Documentation](https://vuldb.com/?doc.cti)
* [Cyber Threat Intelligence - Early Anticipation of Attacks](https://www.scip.ch/en/?labs.20201022)

## License

(c) [1997-2021](https://vuldb.com/?doc.changelog) by [vuldb.com](https://vuldb.com/?doc.about). All data on this page is shared under the license [CC BY-NC-SA 4.0](https://creativecommons.org/licenses/by-nc-sa/4.0/). Questions? Check the [FAQ](https://vuldb.com/?doc.faq), read the [documentation](https://vuldb.com/?doc) or [contact us](https://vuldb.com/?contact)!
