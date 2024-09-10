# Medical and Shipping - Cyber Threat Intelligence

These _indicators_ were reported, collected, and generated during the [VulDB CTI analysis](https://vuldb.com/?kb.cti) of the campaign known as _Medical and Shipping_. The _activity monitoring_ correlates data from social media, forums, chat rooms, and darknet markets. It helps to determine associated actors, specific activities, expected intentions, emerging research, and ongoing attacks. Our unique _predictive model_ uses _big data_ to forecast activities and their characteristics.

_Live data_ and more _analysis capabilities_ are available at [https://vuldb.com/?actor](https://vuldb.com/?actor)

## Countries

These _countries_ are directly (e.g. origin of attacks) or indirectly (e.g. access by proxy) associated with Medical and Shipping:

* [CN](https://vuldb.com/?country.cn)

## Actors

These _actors_ are associated with Medical and Shipping or other actors linked to the campaign.

ID | Actor | Confidence
-- | ----- | ----------
1 | [Hydrochasma](https://vuldb.com/?actor.hydrochasma) | High

## IOC - Indicator of Compromise

These _indicators of compromise_ (IOC) indicate associated network resources which are known to be part of research and attack activities of Medical and Shipping.

ID | IP address | Hostname | Actor | Confidence
-- | ---------- | -------- | ----- | ----------
1 | [39.101.194.61](https://vuldb.com/?ip.39.101.194.61) | - | [Hydrochasma](https://vuldb.com/?actor.hydrochasma) | High
2 | [47.92.138.241](https://vuldb.com/?ip.47.92.138.241) | - | [Hydrochasma](https://vuldb.com/?actor.hydrochasma) | High
3 | [106.14.184.148](https://vuldb.com/?ip.106.14.184.148) | - | [Hydrochasma](https://vuldb.com/?actor.hydrochasma) | High
4 | ... | ... | ... | ...

There are 1 more IOC items available. Please use our online service to access the data.

## TTP - Tactics, Techniques, Procedures

_Tactics, techniques, and procedures_ (TTP) summarize the suspected MITRE ATT&CK techniques used within Medical and Shipping. This data is unique as it uses our predictive model for actor profiling.

ID | Technique | Weakness | Description | Confidence
-- | --------- | -------- | ----------- | ----------
1 | T1078.001 | CWE-259 | Use of Hard-coded Password | High
2 | T1202 | CWE-78 | Command Shell in Externally Accessible Directory | High
3 | T1592 | CWE-200 | Invocation of Process Using Visible Sensitive Information | High

## IOA - Indicator of Attack

These _indicators of attack_ (IOA) list the potential fragments used for technical activities like reconnaissance, exploitation, privilege escalation, and exfiltration during Medical and Shipping. This data is unique as it uses our predictive model for actor profiling.

ID | Type | Indicator | Confidence
-- | ---- | --------- | ----------
1 | File | `/index.php?app=main&func=passport&action=login` | High
2 | File | `/ndmComponents.js` | High
3 | File | `app/Controller/JobsController.php` | High

## References

The following list contains _external sources_ which discuss the campaign and the associated activities:

* https://symantec-enterprise-blogs.security.com/blogs/threat-intelligence/hydrochasma-asia-medical-shipping-intelligence-gathering

## Literature

The following _articles_ explain our unique predictive cyber threat intelligence:

* [VulDB Cyber Threat Intelligence Documentation](https://vuldb.com/?kb.cti)
* [Cyber Threat Intelligence - Early Anticipation of Attacks](https://www.scip.ch/en/?labs.20201022)

## License

(c) [1997-2024](https://vuldb.com/?kb.changelog) by [vuldb.com](https://vuldb.com/?kb.about). All data on this page is shared under the license [CC BY-NC-SA 4.0](https://creativecommons.org/licenses/by-nc-sa/4.0/). Questions? Check the [FAQ](https://vuldb.com/?kb.faq), read the [documentation](https://vuldb.com/?kb) or [contact us](https://vuldb.com/?contact)!
