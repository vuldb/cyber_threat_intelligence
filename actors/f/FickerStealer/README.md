# FickerStealer - Cyber Threat Intelligence

These _indicators_ were reported, collected, and generated during the [VulDB CTI analysis](https://vuldb.com/?kb.cti) of the actor known as [FickerStealer](https://vuldb.com/?actor.fickerstealer). The _activity monitoring_ correlates data from social media, forums, chat rooms, and darknet markets. It helps to determine associated actors, specific activities, expected intentions, emerging research, and ongoing attacks. Our unique _predictive model_ uses _big data_ to forecast activities and their characteristics.

_Live data_ and more _analysis capabilities_ are available at [https://vuldb.com/?actor.fickerstealer](https://vuldb.com/?actor.fickerstealer)

## Countries

These _countries_ are directly (e.g. origin of attacks) or indirectly (e.g. access by proxy) associated with FickerStealer:

* [US](https://vuldb.com/?country.us)
* [RU](https://vuldb.com/?country.ru)
* [CN](https://vuldb.com/?country.cn)
* ...

There are 10 more country items available. Please use our online service to access the data.

## IOC - Indicator of Compromise

These _indicators of compromise_ (IOC) indicate associated network resources which are known to be part of research and attack activities of FickerStealer.

ID | IP address | Hostname | Campaign | Confidence
-- | ---------- | -------- | -------- | ----------
1 | [23.21.27.29](https://vuldb.com/?ip.23.21.27.29) | ec2-23-21-27-29.compute-1.amazonaws.com | - | Medium
2 | [23.21.42.25](https://vuldb.com/?ip.23.21.42.25) | ec2-23-21-42-25.compute-1.amazonaws.com | - | Medium
3 | [23.21.140.41](https://vuldb.com/?ip.23.21.140.41) | ec2-23-21-140-41.compute-1.amazonaws.com | - | Medium
4 | [50.19.243.236](https://vuldb.com/?ip.50.19.243.236) | ec2-50-19-243-236.compute-1.amazonaws.com | - | Medium
5 | [54.221.253.252](https://vuldb.com/?ip.54.221.253.252) | ec2-54-221-253-252.compute-1.amazonaws.com | - | Medium
6 | ... | ... | ... | ...

There are 20 more IOC items available. Please use our online service to access the data.

## TTP - Tactics, Techniques, Procedures

_Tactics, techniques, and procedures_ (TTP) summarize the suspected MITRE ATT&CK techniques used by _FickerStealer_. This data is unique as it uses our predictive model for actor profiling.

ID | Technique | Weakness | Description | Confidence
-- | --------- | -------- | ----------- | ----------
1 | T1006 | CWE-22 | Path Traversal | High
2 | T1040 | CWE-319 | Authentication Bypass by Capture-replay | High
3 | T1055 | CWE-74 | Improper Neutralization of Data within XPath Expressions | High
4 | T1059 | CWE-94 | Argument Injection | High
5 | ... | ... | ... | ...

There are 14 more TTP items available. Please use our online service to access the data.

## IOA - Indicator of Attack

These _indicators of attack_ (IOA) list the potential fragments used for technical activities like reconnaissance, exploitation, privilege escalation, and exfiltration by FickerStealer. This data is unique as it uses our predictive model for actor profiling.

ID | Type | Indicator | Confidence
-- | ---- | --------- | ----------
1 | File | `/.env` | Low
2 | File | `/admin/bookdate.php` | High
3 | File | `/admin/index.php` | High
4 | File | `/category.php` | High
5 | File | `/cgi-bin/delete_CA` | High
6 | File | `/cgi-bin/luci;stok=/locale` | High
7 | File | `/change-password.php` | High
8 | File | `/Config/SaveUploadedHotspotLogoFile` | High
9 | File | `/download` | Medium
10 | File | `/general/email/outbox/delete.php` | High
11 | File | `/getcfg.php` | Medium
12 | File | `/get_getnetworkconf.cgi` | High
13 | File | `/goform/formSetPassword` | High
14 | File | `/goform/setBlackRule` | High
15 | File | `/GponForm/device_Form?script/` | High
16 | File | `/includes/rrdtool.inc.php` | High
17 | ... | ... | ...

There are 134 more IOA items available (file, library, argument, input value, pattern, network port). Please use our online service to access the data.

## References

The following list contains _external sources_ which discuss the actor and the associated activities:

* https://blog.talosintelligence.com/2021/01/threat-roundup-0108-0115.html

## Literature

The following _articles_ explain our unique predictive cyber threat intelligence:

* [VulDB Cyber Threat Intelligence Documentation](https://vuldb.com/?kb.cti)
* [Cyber Threat Intelligence - Early Anticipation of Attacks](https://www.scip.ch/en/?labs.20201022)

## License

(c) [1997-2025](https://vuldb.com/?kb.changelog) by [vuldb.com](https://vuldb.com/?kb.about). All data on this page is shared under the license [CC BY-NC-SA 4.0](https://creativecommons.org/licenses/by-nc-sa/4.0/). Questions? Check the [FAQ](https://vuldb.com/?kb.faq), read the [documentation](https://vuldb.com/?kb) or [contact us](https://vuldb.com/?contact)!
