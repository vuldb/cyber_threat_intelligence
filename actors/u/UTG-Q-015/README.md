# UTG-Q-015 - Cyber Threat Intelligence

These _indicators_ were reported, collected, and generated during the [VulDB CTI analysis](https://vuldb.com/?kb.cti) of the actor known as [UTG-Q-015](https://vuldb.com/?actor.utg-q-015). The _activity monitoring_ correlates data from social media, forums, chat rooms, and darknet markets. It helps to determine associated actors, specific activities, expected intentions, emerging research, and ongoing attacks. Our unique _predictive model_ uses _big data_ to forecast activities and their characteristics.

_Live data_ and more _analysis capabilities_ are available at [https://vuldb.com/?actor.utg-q-015](https://vuldb.com/?actor.utg-q-015)

## Campaigns

The following _campaigns_ are known and can be associated with UTG-Q-015:

* Run

## Countries

These _countries_ are directly (e.g. origin of attacks) or indirectly (e.g. access by proxy) associated with UTG-Q-015:

* [CN](https://vuldb.com/?country.cn)
* [IR](https://vuldb.com/?country.ir)
* [US](https://vuldb.com/?country.us)

## IOC - Indicator of Compromise

These _indicators of compromise_ (IOC) indicate associated network resources which are known to be part of research and attack activities of UTG-Q-015.

ID | IP address | Hostname | Campaign | Confidence
-- | ---------- | -------- | -------- | ----------
1 | [13.229.89.211](https://vuldb.com/?ip.13.229.89.211) | ec2-13-229-89-211.ap-southeast-1.compute.amazonaws.com | Run | Medium
2 | [209.250.254.130](https://vuldb.com/?ip.209.250.254.130) | 209.250.254.130.vultrusercontent.com | Run | Medium

## TTP - Tactics, Techniques, Procedures

_Tactics, techniques, and procedures_ (TTP) summarize the suspected MITRE ATT&CK techniques used by _UTG-Q-015_. This data is unique as it uses our predictive model for actor profiling.

ID | Technique | Weakness | Description | Confidence
-- | --------- | -------- | ----------- | ----------
1 | T1505 | CWE-89 | SQL Injection | High
2 | T1592 | CWE-200 | Invocation of Process Using Visible Sensitive Information | High
3 | T1608.002 | CWE-434 | Incomplete Identification of Uploaded File Variables | High

## IOA - Indicator of Attack

These _indicators of attack_ (IOA) list the potential fragments used for technical activities like reconnaissance, exploitation, privilege escalation, and exfiltration by UTG-Q-015. This data is unique as it uses our predictive model for actor profiling.

ID | Type | Indicator | Confidence
-- | ---- | --------- | ----------
1 | File | `strload.php` | Medium
2 | File | `view_all_set.php` | High
3 | Argument | `LangFile` | Medium
4 | ... | ... | ...

There are 1 more IOA items available (file, library, argument, input value, pattern, network port). Please use our online service to access the data.

## References

The following list contains _external sources_ which discuss the actor and the associated activities:

* https://ti.qianxin.com/blog/articles/operation-run-the-cyber-carnival-of-offshore-patriots-en/

## Literature

The following _articles_ explain our unique predictive cyber threat intelligence:

* [VulDB Cyber Threat Intelligence Documentation](https://vuldb.com/?kb.cti)
* [Cyber Threat Intelligence - Early Anticipation of Attacks](https://www.scip.ch/en/?labs.20201022)

## License

(c) [1997-2025](https://vuldb.com/?kb.changelog) by [vuldb.com](https://vuldb.com/?kb.about). All data on this page is shared under the license [CC BY-NC-SA 4.0](https://creativecommons.org/licenses/by-nc-sa/4.0/). Questions? Check the [FAQ](https://vuldb.com/?kb.faq), read the [documentation](https://vuldb.com/?kb) or [contact us](https://vuldb.com/?contact)!
