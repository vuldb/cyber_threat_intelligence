# Penquin - Cyber Threat Intelligence

These _indicators_ were reported, collected, and generated during the [VulDB CTI analysis](https://vuldb.com/?kb.cti) of the campaign known as _Penquin_. The _activity monitoring_ correlates data from social media, forums, chat rooms, and darknet markets. It helps to determine associated actors, specific activities, expected intentions, emerging research, and ongoing attacks. Our unique _predictive model_ uses _big data_ to forecast activities and their characteristics.

_Live data_ and more _analysis capabilities_ are available at [https://vuldb.com/?actor](https://vuldb.com/?actor)

## Countries

These _countries_ are directly (e.g. origin of attacks) or indirectly (e.g. access by proxy) associated with Penquin:

* [US](https://vuldb.com/?country.us)
* [IR](https://vuldb.com/?country.ir)
* [GB](https://vuldb.com/?country.gb)

## Actors

These _actors_ are associated with Penquin or other actors linked to the campaign.

ID | Actor | Confidence
-- | ----- | ----------
1 | [Turla](https://vuldb.com/?actor.turla) | High

## IOC - Indicator of Compromise

These _indicators of compromise_ (IOC) indicate associated network resources which are known to be part of research and attack activities of Penquin.

ID | IP address | Hostname | Actor | Confidence
-- | ---------- | -------- | ----- | ----------
1 | [85.25.95.16](https://vuldb.com/?ip.85.25.95.16) | luna112.startdedicated.com | [Turla](https://vuldb.com/?actor.turla) | High
2 | [162.223.94.14](https://vuldb.com/?ip.162.223.94.14) | amniran.org | [Turla](https://vuldb.com/?actor.turla) | High

## TTP - Tactics, Techniques, Procedures

_Tactics, techniques, and procedures_ (TTP) summarize the suspected MITRE ATT&CK techniques used within Penquin. This data is unique as it uses our predictive model for actor profiling.

ID | Technique | Weakness | Description | Confidence
-- | --------- | -------- | ----------- | ----------
1 | T1059.007 | CWE-79, CWE-80 | Cross Site Scripting | High
2 | T1505 | CWE-89 | SQL Injection | High
3 | T1587.003 | CWE-295 | Improper Certificate Validation | High
4 | ... | ... | ... | ...

There are 1 more TTP items available. Please use our online service to access the data.

## IOA - Indicator of Attack

These _indicators of attack_ (IOA) list the potential fragments used for technical activities like reconnaissance, exploitation, privilege escalation, and exfiltration during Penquin. This data is unique as it uses our predictive model for actor profiling.

ID | Type | Indicator | Confidence
-- | ---- | --------- | ----------
1 | File | `/uncpath/` | Medium
2 | File | `/webapps/Bb-sites-user-profile-BBLEARN/profile.form` | High
3 | File | `custom/run.cgi` | High
4 | ... | ... | ...

There are 8 more IOA items available (file, library, argument, input value, pattern, network port). Please use our online service to access the data.

## References

The following list contains _external sources_ which discuss the campaign and the associated activities:

* https://lab52.io/blog/looking-for-penquins-in-the-wild/

## Literature

The following _articles_ explain our unique predictive cyber threat intelligence:

* [VulDB Cyber Threat Intelligence Documentation](https://vuldb.com/?kb.cti)
* [Cyber Threat Intelligence - Early Anticipation of Attacks](https://www.scip.ch/en/?labs.20201022)

## License

(c) [1997-2024](https://vuldb.com/?kb.changelog) by [vuldb.com](https://vuldb.com/?kb.about). All data on this page is shared under the license [CC BY-NC-SA 4.0](https://creativecommons.org/licenses/by-nc-sa/4.0/). Questions? Check the [FAQ](https://vuldb.com/?kb.faq), read the [documentation](https://vuldb.com/?kb) or [contact us](https://vuldb.com/?contact)!
