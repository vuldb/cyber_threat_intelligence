# BlueKeep - Cyber Threat Intelligence

These _indicators_ were reported, collected, and generated during the [VulDB CTI analysis](https://vuldb.com/?kb.cti) of the actor known as [BlueKeep](https://vuldb.com/?actor.bluekeep). The _activity monitoring_ correlates data from social media, forums, chat rooms, and darknet markets. It helps to determine associated actors, specific activities, expected intentions, emerging research, and ongoing attacks. Our unique _predictive model_ uses _big data_ to forecast activities and their characteristics.

_Live data_ and more _analysis capabilities_ are available at [https://vuldb.com/?actor.bluekeep](https://vuldb.com/?actor.bluekeep)

## Campaigns

The following _campaigns_ are known and can be associated with BlueKeep:

* CVE–2019-0708

## Countries

These _countries_ are directly (e.g. origin of attacks) or indirectly (e.g. access by proxy) associated with BlueKeep:

* [US](https://vuldb.com/?country.us)

## IOC - Indicator of Compromise

These _indicators of compromise_ (IOC) indicate associated network resources which are known to be part of research and attack activities of BlueKeep.

ID | IP address | Hostname | Campaign | Confidence
-- | ---------- | -------- | -------- | ----------
1 | [3.14.202.129](https://vuldb.com/?ip.3.14.202.129) | ec2-3-14-202-129.us-east-2.compute.amazonaws.com | CVE&ndash;2019-0708 | Medium
2 | [3.14.212.173](https://vuldb.com/?ip.3.14.212.173) | ec2-3-14-212-173.us-east-2.compute.amazonaws.com | CVE&ndash;2019-0708 | Medium
3 | [3.17.202.129](https://vuldb.com/?ip.3.17.202.129) | ec2-3-17-202-129.us-east-2.compute.amazonaws.com | CVE&ndash;2019-0708 | Medium
4 | ... | ... | ... | ...

There are 2 more IOC items available. Please use our online service to access the data.

## TTP - Tactics, Techniques, Procedures

_Tactics, techniques, and procedures_ (TTP) summarize the suspected MITRE ATT&CK techniques used by _BlueKeep_. This data is unique as it uses our predictive model for actor profiling.

ID | Technique | Weakness | Description | Confidence
-- | --------- | -------- | ----------- | ----------
1 | T1059.007 | CWE-79 | Cross Site Scripting | High
2 | T1505 | CWE-89 | SQL Injection | High

## IOA - Indicator of Attack

These _indicators of attack_ (IOA) list the potential fragments used for technical activities like reconnaissance, exploitation, privilege escalation, and exfiltration by BlueKeep. This data is unique as it uses our predictive model for actor profiling.

ID | Type | Indicator | Confidence
-- | ---- | --------- | ----------
1 | File | `logindbc.php` | Medium
2 | Argument | `email` | Low

## References

The following list contains _external sources_ which discuss the actor and the associated activities:

* https://intezer.com/blog/research/watching-the-watchbog-new-bluekeep-scanner-and-linux-exploits/

## Literature

The following _articles_ explain our unique predictive cyber threat intelligence:

* [VulDB Cyber Threat Intelligence Documentation](https://vuldb.com/?kb.cti)
* [Cyber Threat Intelligence - Early Anticipation of Attacks](https://www.scip.ch/en/?labs.20201022)

## License

(c) [1997-2024](https://vuldb.com/?kb.changelog) by [vuldb.com](https://vuldb.com/?kb.about). All data on this page is shared under the license [CC BY-NC-SA 4.0](https://creativecommons.org/licenses/by-nc-sa/4.0/). Questions? Check the [FAQ](https://vuldb.com/?kb.faq), read the [documentation](https://vuldb.com/?kb) or [contact us](https://vuldb.com/?contact)!
