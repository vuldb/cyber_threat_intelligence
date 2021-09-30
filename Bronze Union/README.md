# Bronze Union - Cyber Threat Intelligence

The indicators are related to [VulDB CTI analysis](https://vuldb.com/?doc.cti) of the actor known as [Bronze Union](https://vuldb.com/?actor.bronze_union). The activity monitoring correlates data from social media, forums, chat rooms, and darknet markets. It helps to determine associated actors, activities, intentions, emerging research, and attacks. Our unique predictive model is able to forecast activities and their characteristics.

Live data and more analysis capabilities are available at [https://vuldb.com/?actor.bronze_union](https://vuldb.com/?actor.bronze_union)

## Countries

These countries are directly (e.g. origin of attacks) or indirectly (e.g. access by proxy) associated with Bronze Union:

* CN
* US

## IOC - Indicator of Compromise

These indicators of compromise indicate associated network ressources which are known to be part of research and attack activities of Bronze Union.

ID | IP address | Hostname | Confidence
-- | ---------- | -------- | ----------
1 | 45.114.9.174 | - | High
2 | 96.90.63.57 | nleq.com | High
3 | 117.136.63.145 | - | High
4 | 198.56.185.179 | - | High
5 | ... | ... | ...

There are 6 more IOC items available. Please use our online service to access the data.

## TTP - Tactics, Techniques, Procedures

Tactics, techniques, and procedures summarize the suspected ATT&CK techniques used by Bronze Union. This data is unique as it uses our predictive model for actor profiling.

ID | Technique | Description | Confidence
-- | --------- | ----------- | ----------
1 | T1059.007 | Cross Site Scripting | High
2 | T1068 | Execution with Unnecessary Privileges | High
3 | T1548.002 | Improper Authorization | High

## IOA - Indicator of Attack

These indicators of attack list the potential fragments used for technical activities like reconnaissance, exploitation, privilege escalation, and exfiltration by Bronze Union. This data is unique as it uses our predictive model for actor profiling.

ID | Type | Indicator | Confidence
-- | ---- | --------- | ----------
1 | File | `/getcfg.php` | Medium
2 | File | `http_auth.c` | Medium
3 | File | `public/?s=index/\think\app/invokefunction&function=call_user_func_array&vars[0]=system&vars[1][]` | High
4 | File | `ticket.php` | Medium
5 | Argument | `SERVICES` | Medium
6 | Argument | `tid` | Low
7 | Input Value | `curl -d SERVICES=DEVICE.ACCOUNT http://192.168.0.1/getcfg.php` | High
8 | Network Port | `Web Server Port` | High

## References

The following list contains external sources which discuss the actor and the associated activities:

* https://www.threatminer.org/report.php?q=BRONZEUNIONCyberespionagePersistsDespiteDisclosures_SecureWorks.pdf&y=2017

## Literature

The following articles explain our unique predictive cyber threat intelligence:

* [VulDB Cyber Threat Intelligence Documentation](https://vuldb.com/?doc.cti)
* [Cyber Threat Intelligence - Early Anticipation of Attacks](https://www.scip.ch/en/?labs.20201022)

## License

(c) [1997-2021](https://vuldb.com/?doc.changelog) by [vuldb.com](https://vuldb.com/?doc.about). All data on this page is shared under the license [CC BY-NC-SA 4.0](https://creativecommons.org/licenses/by-nc-sa/4.0/). Questions? Check the [FAQ](https://vuldb.com/?doc.faq), read the [documentation](https://vuldb.com/?doc) or [contact us](https://vuldb.com/?contact)!
