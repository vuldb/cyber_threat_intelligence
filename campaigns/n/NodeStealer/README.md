# NodeStealer - Cyber Threat Intelligence

These _indicators_ were reported, collected, and generated during the [VulDB CTI analysis](https://vuldb.com/?kb.cti) of the campaign known as _NodeStealer_. The _activity monitoring_ correlates data from social media, forums, chat rooms, and darknet markets. It helps to determine associated actors, specific activities, expected intentions, emerging research, and ongoing attacks. Our unique _predictive model_ uses _big data_ to forecast activities and their characteristics.

_Live data_ and more _analysis capabilities_ are available at [https://vuldb.com/?actor](https://vuldb.com/?actor)

## Countries

These _countries_ are directly (e.g. origin of attacks) or indirectly (e.g. access by proxy) associated with NodeStealer:

* [US](https://vuldb.com/?country.us)
* [TT](https://vuldb.com/?country.tt)
* [ES](https://vuldb.com/?country.es)

## Actors

These _actors_ are associated with NodeStealer or other actors linked to the campaign.

ID | Actor | Confidence
-- | ----- | ----------
1 | [NodeStealer](https://vuldb.com/?actor.nodestealer) | High
2 | [Vietnam Unknown](https://vuldb.com/?actor.vietnam_unknown) | High

## IOC - Indicator of Compromise

These _indicators of compromise_ (IOC) indicate associated network resources which are known to be part of research and attack activities of NodeStealer.

ID | IP address | Hostname | Actor | Confidence
-- | ---------- | -------- | ----- | ----------
1 | [34.82.20.84](https://vuldb.com/?ip.34.82.20.84) | 84.20.82.34.bc.googleusercontent.com | [NodeStealer](https://vuldb.com/?actor.nodestealer) | Medium
2 | [88.216.99.5](https://vuldb.com/?ip.88.216.99.5) | - | [Vietnam Unknown](https://vuldb.com/?actor.vietnam_unknown) | High

## TTP - Tactics, Techniques, Procedures

_Tactics, techniques, and procedures_ (TTP) summarize the suspected MITRE ATT&CK techniques used within NodeStealer. This data is unique as it uses our predictive model for actor profiling.

ID | Technique | Weakness | Description | Confidence
-- | --------- | -------- | ----------- | ----------
1 | T1059.007 | CWE-79 | Basic Cross Site Scripting | High
2 | T1202 | CWE-77 | Command Shell in Externally Accessible Directory | High
3 | T1211 | CWE-254 | 7PK Security Features | High
4 | ... | ... | ... | ...

There are 2 more TTP items available. Please use our online service to access the data.

## IOA - Indicator of Attack

These _indicators of attack_ (IOA) list the potential fragments used for technical activities like reconnaissance, exploitation, privilege escalation, and exfiltration during NodeStealer. This data is unique as it uses our predictive model for actor profiling.

ID | Type | Indicator | Confidence
-- | ---- | --------- | ----------
1 | File | `drivers/net/slip/slip.c` | High
2 | File | `libvncclient/rfbproto.c` | High
3 | File | `low-level/imap/mailimap_types.c` | High
4 | ... | ... | ...

There are 7 more IOA items available (file, library, argument, input value, pattern, network port). Please use our online service to access the data.

## References

The following list contains _external sources_ which discuss the campaign and the associated activities:

* https://www.bitdefender.com/blog/labs/nodestealer-attacks-on-facebook-take-a-provocative-turn-threat-actors-deploy-malvertising-campaigns-to-hijack-users-accounts/
* https://www.trendmicro.com/en_us/research/24/l/python-based-nodestealer.html

## Literature

The following _articles_ explain our unique predictive cyber threat intelligence:

* [VulDB Cyber Threat Intelligence Documentation](https://vuldb.com/?kb.cti)
* [Cyber Threat Intelligence - Early Anticipation of Attacks](https://www.scip.ch/en/?labs.20201022)

## License

(c) [1997-2025](https://vuldb.com/?kb.changelog) by [vuldb.com](https://vuldb.com/?kb.about). All data on this page is shared under the license [CC BY-NC-SA 4.0](https://creativecommons.org/licenses/by-nc-sa/4.0/). Questions? Check the [FAQ](https://vuldb.com/?kb.faq), read the [documentation](https://vuldb.com/?kb) or [contact us](https://vuldb.com/?contact)!
