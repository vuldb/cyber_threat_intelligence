# COVID-19 - Cyber Threat Intelligence

These _indicators_ were reported, collected, and generated during the [VulDB CTI analysis](https://vuldb.com/?kb.cti) of the campaign known as _COVID-19_. The _activity monitoring_ correlates data from social media, forums, chat rooms, and darknet markets. It helps to determine associated actors, specific activities, expected intentions, emerging research, and ongoing attacks. Our unique _predictive model_ uses _big data_ to forecast activities and their characteristics.

_Live data_ and more _analysis capabilities_ are available at [https://vuldb.com/?actor](https://vuldb.com/?actor)

## Countries

These _countries_ are directly (e.g. origin of attacks) or indirectly (e.g. access by proxy) associated with COVID-19:

* [US](https://vuldb.com/?country.us)
* [CN](https://vuldb.com/?country.cn)
* [VN](https://vuldb.com/?country.vn)
* ...

There are 2 more country items available. Please use our online service to access the data.

## Actors

These _actors_ are associated with COVID-19 or other actors linked to the campaign.

ID | Actor | Confidence
-- | ----- | ----------
1 | [APT29](https://vuldb.com/?actor.apt29) | High
2 | [Unknown](https://vuldb.com/?actor.unknown) | High
3 | [Vicious Panda](https://vuldb.com/?actor.vicious_panda) | High

## IOC - Indicator of Compromise

These _indicators of compromise_ (IOC) indicate associated network resources which are known to be part of research and attack activities of COVID-19.

ID | IP address | Hostname | Actor | Confidence
-- | ---------- | -------- | ----- | ----------
1 | [45.123.190.167](https://vuldb.com/?ip.45.123.190.167) | - | [APT29](https://vuldb.com/?actor.apt29) | High
2 | [45.129.229.48](https://vuldb.com/?ip.45.129.229.48) | - | [APT29](https://vuldb.com/?actor.apt29) | High
3 | [95.179.156.97](https://vuldb.com/?ip.95.179.156.97) | 95.179.156.97.vultr.com | [Vicious Panda](https://vuldb.com/?actor.vicious_panda) | Medium
4 | ... | ... | ... | ...

There are 7 more IOC items available. Please use our online service to access the data.

## TTP - Tactics, Techniques, Procedures

_Tactics, techniques, and procedures_ (TTP) summarize the suspected MITRE ATT&CK techniques used within COVID-19. This data is unique as it uses our predictive model for actor profiling.

ID | Technique | Weakness | Description | Confidence
-- | --------- | -------- | ----------- | ----------
1 | T1059.007 | CWE-79 | Cross Site Scripting | High
2 | T1068 | CWE-264 | Execution with Unnecessary Privileges | High

## IOA - Indicator of Attack

These _indicators of attack_ (IOA) list the potential fragments used for technical activities like reconnaissance, exploitation, privilege escalation, and exfiltration during COVID-19. This data is unique as it uses our predictive model for actor profiling.

ID | Type | Indicator | Confidence
-- | ---- | --------- | ----------
1 | File | `/pages/systemcall.php?command={COMMAND}` | High
2 | File | `/phppath/php` | Medium
3 | File | `/uncpath/` | Medium
4 | File | `/WEB-INF/web.xml` | High
5 | File | `abook_database.php` | High
6 | File | `adclick.php` | Medium
7 | ... | ... | ...

There are 50 more IOA items available (file, library, argument, input value, pattern, network port). Please use our online service to access the data.

## References

The following list contains _external sources_ which discuss the campaign and the associated activities:

* https://github.com/blackorbird/APT_REPORT/blob/master/International%20Strategic/Russia/Advisory-APT29-targets-COVID-19-vaccine-development.pdf
* https://research.checkpoint.com/2020/vicious-panda-the-covid-campaign/
* https://us-cert.cisa.gov/ncas/alerts/aa20-225a

## Literature

The following _articles_ explain our unique predictive cyber threat intelligence:

* [VulDB Cyber Threat Intelligence Documentation](https://vuldb.com/?kb.cti)
* [Cyber Threat Intelligence - Early Anticipation of Attacks](https://www.scip.ch/en/?labs.20201022)

## License

(c) [1997-2022](https://vuldb.com/?kb.changelog) by [vuldb.com](https://vuldb.com/?kb.about). All data on this page is shared under the license [CC BY-NC-SA 4.0](https://creativecommons.org/licenses/by-nc-sa/4.0/). Questions? Check the [FAQ](https://vuldb.com/?kb.faq), read the [documentation](https://vuldb.com/?kb) or [contact us](https://vuldb.com/?contact)!
