# Sneaky 2FA - Cyber Threat Intelligence

These _indicators_ were reported, collected, and generated during the [VulDB CTI analysis](https://vuldb.com/?kb.cti) of the campaign known as _Sneaky 2FA_. The _activity monitoring_ correlates data from social media, forums, chat rooms, and darknet markets. It helps to determine associated actors, specific activities, expected intentions, emerging research, and ongoing attacks. Our unique _predictive model_ uses _big data_ to forecast activities and their characteristics.

_Live data_ and more _analysis capabilities_ are available at [https://vuldb.com/?actor](https://vuldb.com/?actor)

## Countries

These _countries_ are directly (e.g. origin of attacks) or indirectly (e.g. access by proxy) associated with Sneaky 2FA:

* [LA](https://vuldb.com/?country.la)

## Actors

These _actors_ are associated with Sneaky 2FA or other actors linked to the campaign.

ID | Actor | Confidence
-- | ----- | ----------
1 | [Unknown](https://vuldb.com/?actor.unknown) | High

## IOC - Indicator of Compromise

These _indicators of compromise_ (IOC) indicate associated network resources which are known to be part of research and attack activities of Sneaky 2FA.

ID | IP address | Hostname | Actor | Confidence
-- | ---------- | -------- | ----- | ----------
1 | [101.99.92.124](https://vuldb.com/?ip.101.99.92.124) | server1.kamon.la | [Unknown](https://vuldb.com/?actor.unknown) | High

## TTP - Tactics, Techniques, Procedures

_Tactics, techniques, and procedures_ (TTP) summarize the suspected MITRE ATT&CK techniques used within Sneaky 2FA. This data is unique as it uses our predictive model for actor profiling.

ID | Technique | Weakness | Description | Confidence
-- | --------- | -------- | ----------- | ----------
1 | T1006 | CWE-21, CWE-22, CWE-24 | Path Traversal | High
2 | T1055 | CWE-74 | Improper Neutralization of Data within XPath Expressions | High
3 | T1059 | CWE-88, CWE-94, CWE-1321 | Argument Injection | High
4 | T1059.007 | CWE-79, CWE-80 | Basic Cross Site Scripting | High
5 | ... | ... | ... | ...

There are 16 more TTP items available. Please use our online service to access the data.

## IOA - Indicator of Attack

These _indicators of attack_ (IOA) list the potential fragments used for technical activities like reconnaissance, exploitation, privilege escalation, and exfiltration during Sneaky 2FA. This data is unique as it uses our predictive model for actor profiling.

ID | Type | Indicator | Confidence
-- | ---- | --------- | ----------
1 | File | `/admin/dl_sendmail.php` | High
2 | File | `/admin/file_manager/export` | High
3 | File | `/admin/index2.html` | High
4 | File | `/adminPage/conf/reload` | High
5 | File | `/admin_topic.php?action=delall` | High
6 | File | `/api/baskets/{name}` | High
7 | File | `/api/cron/settings/setJob/` | High
8 | File | `/api/v2/cli/commands` | High
9 | File | `/api2/html/` | Medium
10 | File | `/bitrix/admin/ldap_server_edit.php` | High
11 | File | `/cgi-bin/cstecgi.cgi` | High
12 | File | `/cgi-bin/koha/catalogue/search.pl` | High
13 | File | `/Device/Device/GetDeviceInfoList?deviceCode=&searchField=&deviceState=` | High
14 | File | `/DXR.axd` | Medium
15 | File | `/forum/away.php` | High
16 | File | `/h/rest` | Low
17 | File | `/index/ajax/lang` | High
18 | File | `/log/decodmail.php` | High
19 | File | `/login.php?m=admin&c=Field&a=channel_edit` | High
20 | File | `/log_proxy` | Medium
21 | ... | ... | ...

There are 170 more IOA items available (file, library, argument, input value, pattern, network port). Please use our online service to access the data.

## References

The following list contains _external sources_ which discuss the campaign and the associated activities:

* https://circleid.com/posts/sneaking-a-peek-into-the-inner-dns-workings-of-sneaky-2fa

## Literature

The following _articles_ explain our unique predictive cyber threat intelligence:

* [VulDB Cyber Threat Intelligence Documentation](https://vuldb.com/?kb.cti)
* [Cyber Threat Intelligence - Early Anticipation of Attacks](https://www.scip.ch/en/?labs.20201022)

## License

(c) [1997-2025](https://vuldb.com/?kb.changelog) by [vuldb.com](https://vuldb.com/?kb.about). All data on this page is shared under the license [CC BY-NC-SA 4.0](https://creativecommons.org/licenses/by-nc-sa/4.0/). Questions? Check the [FAQ](https://vuldb.com/?kb.faq), read the [documentation](https://vuldb.com/?kb) or [contact us](https://vuldb.com/?contact)!
