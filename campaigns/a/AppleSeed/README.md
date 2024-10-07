# AppleSeed - Cyber Threat Intelligence

These _indicators_ were reported, collected, and generated during the [VulDB CTI analysis](https://vuldb.com/?kb.cti) of the campaign known as _AppleSeed_. The _activity monitoring_ correlates data from social media, forums, chat rooms, and darknet markets. It helps to determine associated actors, specific activities, expected intentions, emerging research, and ongoing attacks. Our unique _predictive model_ uses _big data_ to forecast activities and their characteristics.

_Live data_ and more _analysis capabilities_ are available at [https://vuldb.com/?actor](https://vuldb.com/?actor)

## Countries

These _countries_ are directly (e.g. origin of attacks) or indirectly (e.g. access by proxy) associated with AppleSeed:

* [CN](https://vuldb.com/?country.cn)
* [US](https://vuldb.com/?country.us)
* [JP](https://vuldb.com/?country.jp)
* ...

There are 1 more country items available. Please use our online service to access the data.

## Actors

These _actors_ are associated with AppleSeed or other actors linked to the campaign.

ID | Actor | Confidence
-- | ----- | ----------
1 | [Kimsuky](https://vuldb.com/?actor.kimsuky) | High

## IOC - Indicator of Compromise

These _indicators of compromise_ (IOC) indicate associated network resources which are known to be part of research and attack activities of AppleSeed.

ID | IP address | Hostname | Actor | Confidence
-- | ---------- | -------- | ----- | ----------
1 | [27.102.107.63](https://vuldb.com/?ip.27.102.107.63) | - | [Kimsuky](https://vuldb.com/?actor.kimsuky) | High
2 | [27.102.114.89](https://vuldb.com/?ip.27.102.114.89) | - | [Kimsuky](https://vuldb.com/?actor.kimsuky) | High
3 | [45.13.135.103](https://vuldb.com/?ip.45.13.135.103) | - | [Kimsuky](https://vuldb.com/?actor.kimsuky) | High
4 | ... | ... | ... | ...

There are 5 more IOC items available. Please use our online service to access the data.

## TTP - Tactics, Techniques, Procedures

_Tactics, techniques, and procedures_ (TTP) summarize the suspected MITRE ATT&CK techniques used within AppleSeed. This data is unique as it uses our predictive model for actor profiling.

ID | Technique | Weakness | Description | Confidence
-- | --------- | -------- | ----------- | ----------
1 | T1006 | CWE-21, CWE-22 | Path Traversal | High
2 | T1055 | CWE-74 | Improper Neutralization of Data within XPath Expressions | High
3 | T1059 | CWE-94 | Argument Injection | High
4 | T1059.007 | CWE-79, CWE-80 | Cross Site Scripting | High
5 | ... | ... | ... | ...

There are 14 more TTP items available. Please use our online service to access the data.

## IOA - Indicator of Attack

These _indicators of attack_ (IOA) list the potential fragments used for technical activities like reconnaissance, exploitation, privilege escalation, and exfiltration during AppleSeed. This data is unique as it uses our predictive model for actor profiling.

ID | Type | Indicator | Confidence
-- | ---- | --------- | ----------
1 | File | `/.env` | Low
2 | File | `/?/admin/snippet/add` | High
3 | File | `/admin/index2.html` | High
4 | File | `/bin/false` | Medium
5 | File | `/blog` | Low
6 | File | `/cgi-bin/webproc` | High
7 | File | `/expert_wizard.php` | High
8 | File | `/images/browserslide.jpg` | High
9 | File | `/includes/lib/get.php` | High
10 | File | `/lists/index.php` | High
11 | File | `/main?cmd=invalid_browser` | High
12 | File | `/manager?action=getlogcat` | High
13 | File | `/mc` | Low
14 | ... | ... | ...

There are 112 more IOA items available (file, library, argument, input value, pattern, network port). Please use our online service to access the data.

## References

The following list contains _external sources_ which discuss the campaign and the associated activities:

* https://blog.malwarebytes.com/threat-analysis/2021/06/kimsuky-apt-continues-to-target-south-korean-government-using-appleseed-backdoor/

## Literature

The following _articles_ explain our unique predictive cyber threat intelligence:

* [VulDB Cyber Threat Intelligence Documentation](https://vuldb.com/?kb.cti)
* [Cyber Threat Intelligence - Early Anticipation of Attacks](https://www.scip.ch/en/?labs.20201022)

## License

(c) [1997-2024](https://vuldb.com/?kb.changelog) by [vuldb.com](https://vuldb.com/?kb.about). All data on this page is shared under the license [CC BY-NC-SA 4.0](https://creativecommons.org/licenses/by-nc-sa/4.0/). Questions? Check the [FAQ](https://vuldb.com/?kb.faq), read the [documentation](https://vuldb.com/?kb) or [contact us](https://vuldb.com/?contact)!
