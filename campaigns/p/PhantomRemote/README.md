# PhantomRemote - Cyber Threat Intelligence

These _indicators_ were reported, collected, and generated during the [VulDB CTI analysis](https://vuldb.com/?kb.cti) of the campaign known as _PhantomRemote_. The _activity monitoring_ correlates data from social media, forums, chat rooms, and darknet markets. It helps to determine associated actors, specific activities, expected intentions, emerging research, and ongoing attacks. Our unique _predictive model_ uses _big data_ to forecast activities and their characteristics.

_Live data_ and more _analysis capabilities_ are available at [https://vuldb.com/?actor](https://vuldb.com/?actor)

## Countries

These _countries_ are directly (e.g. origin of attacks) or indirectly (e.g. access by proxy) associated with PhantomRemote:

* [US](https://vuldb.com/?country.us)
* [CN](https://vuldb.com/?country.cn)
* [RU](https://vuldb.com/?country.ru)
* ...

There are 6 more country items available. Please use our online service to access the data.

## Actors

These _actors_ are associated with PhantomRemote or other actors linked to the campaign.

ID | Actor | Confidence
-- | ----- | ----------
1 | [Rainbow Hyena](https://vuldb.com/?actor.rainbow_hyena) | High

## IOC - Indicator of Compromise

These _indicators of compromise_ (IOC) indicate associated network resources which are known to be part of research and attack activities of PhantomRemote.

ID | IP address | Hostname | Actor | Confidence
-- | ---------- | -------- | ----- | ----------
1 | [91.239.148.21](https://vuldb.com/?ip.91.239.148.21) | - | [Rainbow Hyena](https://vuldb.com/?actor.rainbow_hyena) | High
2 | [185.225.17.104](https://vuldb.com/?ip.185.225.17.104) | no-rdns.mivocloud.com | [Rainbow Hyena](https://vuldb.com/?actor.rainbow_hyena) | High
3 | [188.127.254.44](https://vuldb.com/?ip.188.127.254.44) | s1210387.smartape-vps.com | [Rainbow Hyena](https://vuldb.com/?actor.rainbow_hyena) | High

## TTP - Tactics, Techniques, Procedures

_Tactics, techniques, and procedures_ (TTP) summarize the suspected MITRE ATT&CK techniques used within PhantomRemote. This data is unique as it uses our predictive model for actor profiling.

ID | Technique | Weakness | Description | Confidence
-- | --------- | -------- | ----------- | ----------
1 | T1006 | CWE-22, CWE-23, CWE-37 | Path Traversal | High
2 | T1055 | CWE-74 | Improper Neutralization of Data within XPath Expressions | High
3 | T1059 | CWE-94 | Argument Injection | High
4 | ... | ... | ... | ...

There are 13 more TTP items available. Please use our online service to access the data.

## IOA - Indicator of Attack

These _indicators of attack_ (IOA) list the potential fragments used for technical activities like reconnaissance, exploitation, privilege escalation, and exfiltration during PhantomRemote. This data is unique as it uses our predictive model for actor profiling.

ID | Type | Indicator | Confidence
-- | ---- | --------- | ----------
1 | File | `/api/RecordingList/DownloadRecord?file=` | High
2 | File | `/apply.cgi` | Medium
3 | File | `/cgi-bin/cstecgi.cgi` | High
4 | File | `/config/pw_changeusers.html` | High
5 | File | `/netflow/jspui/editProfile.jsp` | High
6 | File | `/php/ping.php` | High
7 | File | `/rapi/read_url` | High
8 | File | `/scripts/unlock_tasks.php` | High
9 | File | `/SysInfo1.htm` | High
10 | File | `/sysinfo_json.cgi` | High
11 | File | `/system/dictData/loadDictItem` | High
12 | File | `/system/user/modules/mod_users/controller.php` | High
13 | ... | ... | ...

There are 99 more IOA items available (file, library, argument, input value, pattern, network port). Please use our online service to access the data.

## References

The following list contains _external sources_ which discuss the campaign and the associated activities:

* https://bi.zone/eng/expertise/blog/rainbow-hyena-snova-atakuet-novyy-bekdor-i-smena-taktik/

## Literature

The following _articles_ explain our unique predictive cyber threat intelligence:

* [VulDB Cyber Threat Intelligence Documentation](https://vuldb.com/?kb.cti)
* [Cyber Threat Intelligence - Early Anticipation of Attacks](https://www.scip.ch/en/?labs.20201022)

## License

(c) [1997-2026](https://vuldb.com/?kb.changelog) by [vuldb.com](https://vuldb.com/?kb.about). All data on this page is shared under the license [CC BY-NC-SA 4.0](https://creativecommons.org/licenses/by-nc-sa/4.0/). Questions? Check the [FAQ](https://vuldb.com/?kb.faq), read the [documentation](https://vuldb.com/?kb) or [contact us](https://vuldb.com/?contact)!
