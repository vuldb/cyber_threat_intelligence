# MoonBounce - Cyber Threat Intelligence

These _indicators_ were reported, collected, and generated during the [VulDB CTI analysis](https://vuldb.com/?kb.cti) of the campaign known as _MoonBounce_. The _activity monitoring_ correlates data from social media, forums, chat rooms, and darknet markets. It helps to determine associated actors, specific activities, expected intentions, emerging research, and ongoing attacks. Our unique _predictive model_ uses _big data_ to forecast activities and their characteristics.

_Live data_ and more _analysis capabilities_ are available at [https://vuldb.com/?actor](https://vuldb.com/?actor)

## Countries

These _countries_ are directly (e.g. origin of attacks) or indirectly (e.g. access by proxy) associated with MoonBounce:

* [US](https://vuldb.com/?country.us)
* [CN](https://vuldb.com/?country.cn)
* [RU](https://vuldb.com/?country.ru)
* ...

There are 11 more country items available. Please use our online service to access the data.

## Actors

These _actors_ are associated with MoonBounce or other actors linked to the campaign.

ID | Actor | Confidence
-- | ----- | ----------
1 | [APT41](https://vuldb.com/?actor.apt41) | High

## IOC - Indicator of Compromise

These _indicators of compromise_ (IOC) indicate associated network resources which are known to be part of research and attack activities of MoonBounce.

ID | IP address | Hostname | Actor | Confidence
-- | ---------- | -------- | ----- | ----------
1 | [5.183.101.21](https://vuldb.com/?ip.5.183.101.21) | bestofgy.co.uk | [APT41](https://vuldb.com/?actor.apt41) | High
2 | [5.183.101.114](https://vuldb.com/?ip.5.183.101.114) | - | [APT41](https://vuldb.com/?actor.apt41) | High
3 | [5.183.103.122](https://vuldb.com/?ip.5.183.103.122) | - | [APT41](https://vuldb.com/?actor.apt41) | High
4 | [5.188.93.132](https://vuldb.com/?ip.5.188.93.132) | gcorelabs.paris.vpn015 | [APT41](https://vuldb.com/?actor.apt41) | High
5 | ... | ... | ... | ...

There are 14 more IOC items available. Please use our online service to access the data.

## TTP - Tactics, Techniques, Procedures

_Tactics, techniques, and procedures_ (TTP) summarize the suspected MITRE ATT&CK techniques used within MoonBounce. This data is unique as it uses our predictive model for actor profiling.

ID | Technique | Weakness | Description | Confidence
-- | --------- | -------- | ----------- | ----------
1 | T1006 | CWE-22, CWE-23 | Path Traversal | High
2 | T1055 | CWE-74 | Improper Neutralization of Data within XPath Expressions | High
3 | T1059 | CWE-94 | Argument Injection | High
4 | T1059.007 | CWE-79, CWE-80 | Cross Site Scripting | High
5 | ... | ... | ... | ...

There are 14 more TTP items available. Please use our online service to access the data.

## IOA - Indicator of Attack

These _indicators of attack_ (IOA) list the potential fragments used for technical activities like reconnaissance, exploitation, privilege escalation, and exfiltration during MoonBounce. This data is unique as it uses our predictive model for actor profiling.

ID | Type | Indicator | Confidence
-- | ---- | --------- | ----------
1 | File | `/common/info.cgi` | High
2 | File | `/forum/away.php` | High
3 | File | `/hedwig.cgi` | Medium
4 | File | `/medical/inventories.php` | High
5 | File | `/module/admin_logs` | High
6 | File | `/nova/bin/console` | High
7 | File | `/public/plugins/` | High
8 | File | `/replication` | Medium
9 | File | `/start-stop` | Medium
10 | File | `/subnet-masks/popup.php` | High
11 | File | `/uncpath/` | Medium
12 | File | `/usr/bin/pkexec` | High
13 | File | `/WEB-INF/web.xml` | High
14 | File | `adclick.php` | Medium
15 | File | `addrating.php` | High
16 | File | `adm.cgi` | Low
17 | ... | ... | ...

There are 139 more IOA items available (file, library, argument, input value, pattern, network port). Please use our online service to access the data.

## References

The following list contains _external sources_ which discuss the campaign and the associated activities:

* https://securelist.com/moonbounce-the-dark-side-of-uefi-firmware/105468/

## Literature

The following _articles_ explain our unique predictive cyber threat intelligence:

* [VulDB Cyber Threat Intelligence Documentation](https://vuldb.com/?kb.cti)
* [Cyber Threat Intelligence - Early Anticipation of Attacks](https://www.scip.ch/en/?labs.20201022)

## License

(c) [1997-2024](https://vuldb.com/?kb.changelog) by [vuldb.com](https://vuldb.com/?kb.about). All data on this page is shared under the license [CC BY-NC-SA 4.0](https://creativecommons.org/licenses/by-nc-sa/4.0/). Questions? Check the [FAQ](https://vuldb.com/?kb.faq), read the [documentation](https://vuldb.com/?kb) or [contact us](https://vuldb.com/?contact)!
