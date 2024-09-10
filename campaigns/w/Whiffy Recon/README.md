# Whiffy Recon - Cyber Threat Intelligence

These _indicators_ were reported, collected, and generated during the [VulDB CTI analysis](https://vuldb.com/?kb.cti) of the campaign known as _Whiffy Recon_. The _activity monitoring_ correlates data from social media, forums, chat rooms, and darknet markets. It helps to determine associated actors, specific activities, expected intentions, emerging research, and ongoing attacks. Our unique _predictive model_ uses _big data_ to forecast activities and their characteristics.

_Live data_ and more _analysis capabilities_ are available at [https://vuldb.com/?actor](https://vuldb.com/?actor)

## Countries

These _countries_ are directly (e.g. origin of attacks) or indirectly (e.g. access by proxy) associated with Whiffy Recon:

* [US](https://vuldb.com/?country.us)
* [LV](https://vuldb.com/?country.lv)
* [CN](https://vuldb.com/?country.cn)
* ...

There are 4 more country items available. Please use our online service to access the data.

## Actors

These _actors_ are associated with Whiffy Recon or other actors linked to the campaign.

ID | Actor | Confidence
-- | ----- | ----------
1 | [SmokeLoader](https://vuldb.com/?actor.smokeloader) | High

## IOC - Indicator of Compromise

These _indicators of compromise_ (IOC) indicate associated network resources which are known to be part of research and attack activities of Whiffy Recon.

ID | IP address | Hostname | Actor | Confidence
-- | ---------- | -------- | ----- | ----------
1 | [194.87.32.20](https://vuldb.com/?ip.194.87.32.20) | - | [SmokeLoader](https://vuldb.com/?actor.smokeloader) | High
2 | [195.123.212.53](https://vuldb.com/?ip.195.123.212.53) | vds1166461.hosted-by-itldc.com | [SmokeLoader](https://vuldb.com/?actor.smokeloader) | High

## TTP - Tactics, Techniques, Procedures

_Tactics, techniques, and procedures_ (TTP) summarize the suspected MITRE ATT&CK techniques used within Whiffy Recon. This data is unique as it uses our predictive model for actor profiling.

ID | Technique | Weakness | Description | Confidence
-- | --------- | -------- | ----------- | ----------
1 | T1006 | CWE-21, CWE-22 | Path Traversal | High
2 | T1040 | CWE-294 | Authentication Bypass by Capture-replay | High
3 | T1055 | CWE-74 | Improper Neutralization of Data within XPath Expressions | High
4 | ... | ... | ... | ...

There are 13 more TTP items available. Please use our online service to access the data.

## IOA - Indicator of Attack

These _indicators of attack_ (IOA) list the potential fragments used for technical activities like reconnaissance, exploitation, privilege escalation, and exfiltration during Whiffy Recon. This data is unique as it uses our predictive model for actor profiling.

ID | Type | Indicator | Confidence
-- | ---- | --------- | ----------
1 | File | `/etc/passwd` | Medium
2 | File | `/goform/setmac` | High
3 | File | `/inc/extensions.php` | High
4 | File | `/MIME/INBOX-MM-1/` | High
5 | File | `/ServletAPI/accounts/login` | High
6 | File | `/uncpath/` | Medium
7 | File | `arch/x86/kvm/svm/sev.c` | High
8 | File | `bigdecimal.c` | Medium
9 | File | `calendar.php` | Medium
10 | File | `com/android/internal/telephony/cat/AppInterface.java` | High
11 | ... | ... | ...

There are 80 more IOA items available (file, library, argument, input value, pattern, network port). Please use our online service to access the data.

## References

The following list contains _external sources_ which discuss the campaign and the associated activities:

* https://www.secureworks.com/blog/smoke-loader-drops-whiffy-recon-wi-fi-scanning-and-geolocation-malware

## Literature

The following _articles_ explain our unique predictive cyber threat intelligence:

* [VulDB Cyber Threat Intelligence Documentation](https://vuldb.com/?kb.cti)
* [Cyber Threat Intelligence - Early Anticipation of Attacks](https://www.scip.ch/en/?labs.20201022)

## License

(c) [1997-2024](https://vuldb.com/?kb.changelog) by [vuldb.com](https://vuldb.com/?kb.about). All data on this page is shared under the license [CC BY-NC-SA 4.0](https://creativecommons.org/licenses/by-nc-sa/4.0/). Questions? Check the [FAQ](https://vuldb.com/?kb.faq), read the [documentation](https://vuldb.com/?kb) or [contact us](https://vuldb.com/?contact)!
