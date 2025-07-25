# TSCookie - Cyber Threat Intelligence

These _indicators_ were reported, collected, and generated during the [VulDB CTI analysis](https://vuldb.com/?kb.cti) of the campaign known as _TSCookie_. The _activity monitoring_ correlates data from social media, forums, chat rooms, and darknet markets. It helps to determine associated actors, specific activities, expected intentions, emerging research, and ongoing attacks. Our unique _predictive model_ uses _big data_ to forecast activities and their characteristics.

_Live data_ and more _analysis capabilities_ are available at [https://vuldb.com/?actor](https://vuldb.com/?actor)

## Countries

These _countries_ are directly (e.g. origin of attacks) or indirectly (e.g. access by proxy) associated with TSCookie:

* [CN](https://vuldb.com/?country.cn)
* [US](https://vuldb.com/?country.us)

## Actors

These _actors_ are associated with TSCookie or other actors linked to the campaign.

ID | Actor | Confidence
-- | ----- | ----------
1 | [BlackTech](https://vuldb.com/?actor.blacktech) | High
2 | [TSCookie](https://vuldb.com/?actor.tscookie) | High

## IOC - Indicator of Compromise

These _indicators of compromise_ (IOC) indicate associated network resources which are known to be part of research and attack activities of TSCookie.

ID | IP address | Hostname | Actor | Confidence
-- | ---------- | -------- | ----- | ----------
1 | [45.76.102.145](https://vuldb.com/?ip.45.76.102.145) | 45.76.102.145.vultrusercontent.com | [TSCookie](https://vuldb.com/?actor.tscookie) | Medium
2 | [60.244.52.29](https://vuldb.com/?ip.60.244.52.29) | 60-244-52-29.tinp.apol.com.tw | [TSCookie](https://vuldb.com/?actor.tscookie) | High
3 | [220.130.216.76](https://vuldb.com/?ip.220.130.216.76) | 220-130-216-76.hinet-ip.hinet.net | [TSCookie](https://vuldb.com/?actor.tscookie) | High

## TTP - Tactics, Techniques, Procedures

_Tactics, techniques, and procedures_ (TTP) summarize the suspected MITRE ATT&CK techniques used within TSCookie. This data is unique as it uses our predictive model for actor profiling.

ID | Technique | Weakness | Description | Confidence
-- | --------- | -------- | ----------- | ----------
1 | T1006 | CWE-22 | Path Traversal | High
2 | T1059.007 | CWE-79, CWE-80 | Basic Cross Site Scripting | High
3 | T1068 | CWE-284 | Execution with Unnecessary Privileges | High
4 | ... | ... | ... | ...

There are 2 more TTP items available. Please use our online service to access the data.

## IOA - Indicator of Attack

These _indicators of attack_ (IOA) list the potential fragments used for technical activities like reconnaissance, exploitation, privilege escalation, and exfiltration during TSCookie. This data is unique as it uses our predictive model for actor profiling.

ID | Type | Indicator | Confidence
-- | ---- | --------- | ----------
1 | File | `base/ErrorHandler.php` | High
2 | File | `goto.php` | Medium
3 | File | `suggest-listing.php` | High
4 | ... | ... | ...

There are 2 more IOA items available (file, library, argument, input value, pattern, network port). Please use our online service to access the data.

## References

The following list contains _external sources_ which discuss the campaign and the associated activities:

* https://blogs.jpcert.or.jp/en/2018/03/malware-tscooki-7aa0.html
* https://blogs.jpcert.or.jp/ja/2018/03/tscookie.html
* https://www.threatminer.org/report.php?q=JPCERT_CCBlog_MalwareTSCookie_JP-CERT.pdf&y=2018

## Literature

The following _articles_ explain our unique predictive cyber threat intelligence:

* [VulDB Cyber Threat Intelligence Documentation](https://vuldb.com/?kb.cti)
* [Cyber Threat Intelligence - Early Anticipation of Attacks](https://www.scip.ch/en/?labs.20201022)

## License

(c) [1997-2025](https://vuldb.com/?kb.changelog) by [vuldb.com](https://vuldb.com/?kb.about). All data on this page is shared under the license [CC BY-NC-SA 4.0](https://creativecommons.org/licenses/by-nc-sa/4.0/). Questions? Check the [FAQ](https://vuldb.com/?kb.faq), read the [documentation](https://vuldb.com/?kb) or [contact us](https://vuldb.com/?contact)!
