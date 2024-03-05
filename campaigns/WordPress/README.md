# WordPress - Cyber Threat Intelligence

These _indicators_ were reported, collected, and generated during the [VulDB CTI analysis](https://vuldb.com/?kb.cti) of the campaign known as _WordPress_. The _activity monitoring_ correlates data from social media, forums, chat rooms, and darknet markets. It helps to determine associated actors, specific activities, expected intentions, emerging research, and ongoing attacks. Our unique _predictive model_ uses _big data_ to forecast activities and their characteristics.

_Live data_ and more _analysis capabilities_ are available at [https://vuldb.com/?actor](https://vuldb.com/?actor)

## Countries

These _countries_ are directly (e.g. origin of attacks) or indirectly (e.g. access by proxy) associated with WordPress:

* [RU](https://vuldb.com/?country.ru)
* [US](https://vuldb.com/?country.us)
* [ES](https://vuldb.com/?country.es)
* ...

There are 1 more country items available. Please use our online service to access the data.

## Actors

These _actors_ are associated with WordPress or other actors linked to the campaign.

ID | Actor | Confidence
-- | ----- | ----------
1 | [Lock360](https://vuldb.com/?actor.lock360) | High
2 | [WordPress SMTP Exploit](https://vuldb.com/?actor.wordpress_smtp_exploit) | High

## IOC - Indicator of Compromise

These _indicators of compromise_ (IOC) indicate associated network resources which are known to be part of research and attack activities of WordPress.

ID | IP address | Hostname | Actor | Confidence
-- | ---------- | -------- | ----- | ----------
1 | [1.3.9.1](https://vuldb.com/?ip.1.3.9.1) | - | [WordPress SMTP Exploit](https://vuldb.com/?actor.wordpress_smtp_exploit) | High
2 | [3.5.33.11](https://vuldb.com/?ip.3.5.33.11) | - | [WordPress SMTP Exploit](https://vuldb.com/?actor.wordpress_smtp_exploit) | High
3 | [86.109.170.200](https://vuldb.com/?ip.86.109.170.200) | www02.dnsprimario.com | [WordPress SMTP Exploit](https://vuldb.com/?actor.wordpress_smtp_exploit) | High
4 | ... | ... | ... | ...

There are 6 more IOC items available. Please use our online service to access the data.

## TTP - Tactics, Techniques, Procedures

_Tactics, techniques, and procedures_ (TTP) summarize the suspected MITRE ATT&CK techniques used within WordPress. This data is unique as it uses our predictive model for actor profiling.

ID | Technique | Weakness | Description | Confidence
-- | --------- | -------- | ----------- | ----------
1 | T1059 | CWE-94 | Argument Injection | High
2 | T1059.007 | CWE-79, CWE-80 | Cross Site Scripting | High
3 | T1068 | CWE-264, CWE-269 | Execution with Unnecessary Privileges | High
4 | ... | ... | ... | ...

There are 7 more TTP items available. Please use our online service to access the data.

## IOA - Indicator of Attack

These _indicators of attack_ (IOA) list the potential fragments used for technical activities like reconnaissance, exploitation, privilege escalation, and exfiltration during WordPress. This data is unique as it uses our predictive model for actor profiling.

ID | Type | Indicator | Confidence
-- | ---- | --------- | ----------
1 | File | `/categorypage.php` | High
2 | File | `/usr/local/psa/admin/sbin/wrapper` | High
3 | File | `adclick.php` | Medium
4 | ... | ... | ...

There are 21 more IOA items available (file, library, argument, input value, pattern, network port). Please use our online service to access the data.

## References

The following list contains _external sources_ which discuss the campaign and the associated activities:

* https://www.claudiokuenzler.com/blog/1183/technical-analysis-hack-php-script-running-process-read-code-from-memory
* https://www.wordfence.com/blog/2019/03/hackers-abusing-recently-patched-vulnerability-in-easy-wp-smtp-plugin/

## Literature

The following _articles_ explain our unique predictive cyber threat intelligence:

* [VulDB Cyber Threat Intelligence Documentation](https://vuldb.com/?kb.cti)
* [Cyber Threat Intelligence - Early Anticipation of Attacks](https://www.scip.ch/en/?labs.20201022)

## License

(c) [1997-2024](https://vuldb.com/?kb.changelog) by [vuldb.com](https://vuldb.com/?kb.about). All data on this page is shared under the license [CC BY-NC-SA 4.0](https://creativecommons.org/licenses/by-nc-sa/4.0/). Questions? Check the [FAQ](https://vuldb.com/?kb.faq), read the [documentation](https://vuldb.com/?kb) or [contact us](https://vuldb.com/?contact)!
