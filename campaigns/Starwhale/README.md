# Starwhale - Cyber Threat Intelligence

These _indicators_ were reported, collected, and generated during the [VulDB CTI analysis](https://vuldb.com/?kb.cti) of the campaign known as _Starwhale_. The _activity monitoring_ correlates data from social media, forums, chat rooms, and darknet markets. It helps to determine associated actors, specific activities, expected intentions, emerging research, and ongoing attacks. Our unique _predictive model_ uses _big data_ to forecast activities and their characteristics.

_Live data_ and more _analysis capabilities_ are available at [https://vuldb.com/?actor](https://vuldb.com/?actor)

## Countries

These _countries_ are directly (e.g. origin of attacks) or indirectly (e.g. access by proxy) associated with Starwhale:

* [US](https://vuldb.com/?country.us)
* [NL](https://vuldb.com/?country.nl)
* [IR](https://vuldb.com/?country.ir)

## Actors

These _actors_ are associated with Starwhale or other actors linked to the campaign.

ID | Actor | Confidence
-- | ----- | ----------
1 | [MuddyWater](https://vuldb.com/?actor.muddywater) | High

## IOC - Indicator of Compromise

These _indicators of compromise_ (IOC) indicate associated network resources which are known to be part of research and attack activities of Starwhale.

ID | IP address | Hostname | Actor | Confidence
-- | ---------- | -------- | ----- | ----------
1 | [87.236.212.184](https://vuldb.com/?ip.87.236.212.184) | - | [MuddyWater](https://vuldb.com/?actor.muddywater) | High

## TTP - Tactics, Techniques, Procedures

_Tactics, techniques, and procedures_ (TTP) summarize the suspected ATT&CK techniques used within Starwhale. This data is unique as it uses our predictive model for actor profiling.

ID | Technique | Weakness | Description | Confidence
-- | --------- | -------- | ----------- | ----------
1 | T1059.007 | CWE-79, CWE-80 | Cross Site Scripting | High
2 | T1222 | CWE-275 | Permission Issues | High
3 | T1552 | CWE-319 | Unprotected Storage of Credentials | High

## IOA - Indicator of Attack

These _indicators of attack_ (IOA) list the potential fragments used for technical activities like reconnaissance, exploitation, privilege escalation, and exfiltration during Starwhale. This data is unique as it uses our predictive model for actor profiling.

ID | Type | Indicator | Confidence
-- | ---- | --------- | ----------
1 | File | `/dana/nc/ncrun.cgi` | High
2 | File | `/jsonrpc` | Medium
3 | File | `admin.php?mod=user&act=del` | High
4 | File | `ajax/render/widget_php` | High
5 | File | `arch/s390/kvm/kvm-s390.c` | High
6 | File | `auth.inc.php` | Medium
7 | File | `certs/blacklist.c` | High
8 | File | `com/wavemaker/studio/StudioService.java` | High
9 | ... | ... | ...

There are 67 more IOA items available (file, library, argument, input value, pattern, network port). Please use our online service to access the data.

## References

The following list contains _external sources_ which discuss the campaign and the associated activities:

* https://www.mandiant.com/resources/telegram-malware-iranian-espionage

## Literature

The following _articles_ explain our unique predictive cyber threat intelligence:

* [VulDB Cyber Threat Intelligence Documentation](https://vuldb.com/?kb.cti)
* [Cyber Threat Intelligence - Early Anticipation of Attacks](https://www.scip.ch/en/?labs.20201022)

## License

(c) [1997-2022](https://vuldb.com/?kb.changelog) by [vuldb.com](https://vuldb.com/?kb.about). All data on this page is shared under the license [CC BY-NC-SA 4.0](https://creativecommons.org/licenses/by-nc-sa/4.0/). Questions? Check the [FAQ](https://vuldb.com/?kb.faq), read the [documentation](https://vuldb.com/?kb) or [contact us](https://vuldb.com/?contact)!
