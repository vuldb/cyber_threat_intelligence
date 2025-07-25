# ZuRu - Cyber Threat Intelligence

These _indicators_ were reported, collected, and generated during the [VulDB CTI analysis](https://vuldb.com/?kb.cti) of the actor known as [ZuRu](https://vuldb.com/?actor.zuru). The _activity monitoring_ correlates data from social media, forums, chat rooms, and darknet markets. It helps to determine associated actors, specific activities, expected intentions, emerging research, and ongoing attacks. Our unique _predictive model_ uses _big data_ to forecast activities and their characteristics.

_Live data_ and more _analysis capabilities_ are available at [https://vuldb.com/?actor.zuru](https://vuldb.com/?actor.zuru)

## Campaigns

The following _campaigns_ are known and can be associated with ZuRu:

* Khepri

## Countries

These _countries_ are directly (e.g. origin of attacks) or indirectly (e.g. access by proxy) associated with ZuRu:

* [CN](https://vuldb.com/?country.cn)

## IOC - Indicator of Compromise

These _indicators of compromise_ (IOC) indicate associated network resources which are known to be part of research and attack activities of ZuRu.

ID | IP address | Hostname | Campaign | Confidence
-- | ---------- | -------- | -------- | ----------
1 | [8.217.132.190](https://vuldb.com/?ip.8.217.132.190) | - | - | High
2 | [46.137.201.254](https://vuldb.com/?ip.46.137.201.254) | ec2-46-137-201-254.ap-southeast-1.compute.amazonaws.com | - | Medium
3 | [47.238.28.21](https://vuldb.com/?ip.47.238.28.21) | - | Khepri | High

## TTP - Tactics, Techniques, Procedures

_Tactics, techniques, and procedures_ (TTP) summarize the suspected MITRE ATT&CK techniques used by _ZuRu_. This data is unique as it uses our predictive model for actor profiling.

ID | Technique | Weakness | Description | Confidence
-- | --------- | -------- | ----------- | ----------
1 | T1006 | CWE-22 | Path Traversal | High
2 | T1059.007 | CWE-79 | Basic Cross Site Scripting | High
3 | T1068 | CWE-284 | Execution with Unnecessary Privileges | High
4 | ... | ... | ... | ...

There are 1 more TTP items available. Please use our online service to access the data.

## IOA - Indicator of Attack

These _indicators of attack_ (IOA) list the potential fragments used for technical activities like reconnaissance, exploitation, privilege escalation, and exfiltration by ZuRu. This data is unique as it uses our predictive model for actor profiling.

ID | Type | Indicator | Confidence
-- | ---- | --------- | ----------
1 | File | `xmlrpc.php` | Medium
2 | Argument | `title` | Low

## References

The following list contains _external sources_ which discuss the actor and the associated activities:

* https://www.jamf.com/blog/jtl-malware-pirated-applications/
* https://www.sentinelone.com/blog/from-the-front-lines-new-macos-covid-malware-masquerades-as-apple-wears-face-of-apt/
* https://www.sentinelone.com/blog/macos-zuru-resurfaces-modified-khepri-c2-hides-inside-doctored-termius-app/

## Literature

The following _articles_ explain our unique predictive cyber threat intelligence:

* [VulDB Cyber Threat Intelligence Documentation](https://vuldb.com/?kb.cti)
* [Cyber Threat Intelligence - Early Anticipation of Attacks](https://www.scip.ch/en/?labs.20201022)

## License

(c) [1997-2025](https://vuldb.com/?kb.changelog) by [vuldb.com](https://vuldb.com/?kb.about). All data on this page is shared under the license [CC BY-NC-SA 4.0](https://creativecommons.org/licenses/by-nc-sa/4.0/). Questions? Check the [FAQ](https://vuldb.com/?kb.faq), read the [documentation](https://vuldb.com/?kb) or [contact us](https://vuldb.com/?contact)!
