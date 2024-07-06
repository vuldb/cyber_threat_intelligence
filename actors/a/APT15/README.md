# APT15 - Cyber Threat Intelligence

These _indicators_ were reported, collected, and generated during the [VulDB CTI analysis](https://vuldb.com/?kb.cti) of the actor known as [APT15](https://vuldb.com/?actor.apt15). The _activity monitoring_ correlates data from social media, forums, chat rooms, and darknet markets. It helps to determine associated actors, specific activities, expected intentions, emerging research, and ongoing attacks. Our unique _predictive model_ uses _big data_ to forecast activities and their characteristics.

_Live data_ and more _analysis capabilities_ are available at [https://vuldb.com/?actor.apt15](https://vuldb.com/?actor.apt15)

## Campaigns

The following _campaigns_ are known and can be associated with APT15:

* Ke3chang

## Countries

These _countries_ are directly (e.g. origin of attacks) or indirectly (e.g. access by proxy) associated with APT15:

* [CN](https://vuldb.com/?country.cn)

## IOC - Indicator of Compromise

These _indicators of compromise_ (IOC) indicate associated network resources which are known to be part of research and attack activities of APT15.

ID | IP address | Hostname | Campaign | Confidence
-- | ---------- | -------- | -------- | ----------
1 | [45.56.84.25](https://vuldb.com/?ip.45.56.84.25) | 45-56-84-25.ip.linodeusercontent.com | - | High
2 | [61.128.110.38](https://vuldb.com/?ip.61.128.110.38) | - | Ke3chang | High
3 | [180.149.252.181](https://vuldb.com/?ip.180.149.252.181) | - | Ke3chang | High

## TTP - Tactics, Techniques, Procedures

_Tactics, techniques, and procedures_ (TTP) summarize the suspected MITRE ATT&CK techniques used by _APT15_. This data is unique as it uses our predictive model for actor profiling.

ID | Technique | Weakness | Description | Confidence
-- | --------- | -------- | ----------- | ----------
1 | T1068 | CWE-264 | Execution with Unnecessary Privileges | High
2 | T1202 | CWE-77 | Command Shell in Externally Accessible Directory | High
3 | T1592 | CWE-200 | Invocation of Process Using Visible Sensitive Information | High

## IOA - Indicator of Attack

These _indicators of attack_ (IOA) list the potential fragments used for technical activities like reconnaissance, exploitation, privilege escalation, and exfiltration by APT15. This data is unique as it uses our predictive model for actor profiling.

ID | Type | Indicator | Confidence
-- | ---- | --------- | ----------
1 | Library | `idq.dll` | Low
2 | Library | `webapps/ROOT/WEB-INF/lib/commons-collections-*.jar` | High

## References

The following list contains _external sources_ which discuss the actor and the associated activities:

* https://intezer.com/blog/research/the-evolution-of-apt15s-codebase-2020/
* https://www.threatminer.org/report.php?q=XSLCmd_OSX.pdf&y=2014

## Literature

The following _articles_ explain our unique predictive cyber threat intelligence:

* [VulDB Cyber Threat Intelligence Documentation](https://vuldb.com/?kb.cti)
* [Cyber Threat Intelligence - Early Anticipation of Attacks](https://www.scip.ch/en/?labs.20201022)

## License

(c) [1997-2024](https://vuldb.com/?kb.changelog) by [vuldb.com](https://vuldb.com/?kb.about). All data on this page is shared under the license [CC BY-NC-SA 4.0](https://creativecommons.org/licenses/by-nc-sa/4.0/). Questions? Check the [FAQ](https://vuldb.com/?kb.faq), read the [documentation](https://vuldb.com/?kb) or [contact us](https://vuldb.com/?contact)!
