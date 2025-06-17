# Domino - Cyber Threat Intelligence

These _indicators_ were reported, collected, and generated during the [VulDB CTI analysis](https://vuldb.com/?kb.cti) of the actor known as [Domino](https://vuldb.com/?actor.domino). The _activity monitoring_ correlates data from social media, forums, chat rooms, and darknet markets. It helps to determine associated actors, specific activities, expected intentions, emerging research, and ongoing attacks. Our unique _predictive model_ uses _big data_ to forecast activities and their characteristics.

_Live data_ and more _analysis capabilities_ are available at [https://vuldb.com/?actor.domino](https://vuldb.com/?actor.domino)

## Countries

These _countries_ are directly (e.g. origin of attacks) or indirectly (e.g. access by proxy) associated with Domino:

* [US](https://vuldb.com/?country.us)
* [CN](https://vuldb.com/?country.cn)
* [RU](https://vuldb.com/?country.ru)
* ...

There are 13 more country items available. Please use our online service to access the data.

## IOC - Indicator of Compromise

These _indicators of compromise_ (IOC) indicate associated network resources which are known to be part of research and attack activities of Domino.

ID | IP address | Hostname | Campaign | Confidence
-- | ---------- | -------- | -------- | ----------
1 | [5.182.37.118](https://vuldb.com/?ip.5.182.37.118) | vps.hostry.com | - | High
2 | [45.67.34.236](https://vuldb.com/?ip.45.67.34.236) | lixm3.servepics.com | - | High
3 | [88.119.175.124](https://vuldb.com/?ip.88.119.175.124) | 19872-33971.bacloud.info | - | High
4 | ... | ... | ... | ...

There are 4 more IOC items available. Please use our online service to access the data.

## TTP - Tactics, Techniques, Procedures

_Tactics, techniques, and procedures_ (TTP) summarize the suspected MITRE ATT&CK techniques used by _Domino_. This data is unique as it uses our predictive model for actor profiling.

ID | Technique | Weakness | Description | Confidence
-- | --------- | -------- | ----------- | ----------
1 | T1006 | CWE-21, CWE-22, CWE-23, CWE-24, CWE-37, CWE-425 | Path Traversal | High
2 | T1040 | CWE-294 | Authentication Bypass by Capture-replay | High
3 | T1055 | CWE-74 | Improper Neutralization of Data within XPath Expressions | High
4 | T1059 | CWE-88, CWE-94, CWE-1321 | Argument Injection | High
5 | T1059.007 | CWE-79, CWE-80 | Basic Cross Site Scripting | High
6 | ... | ... | ... | ...

There are 18 more TTP items available. Please use our online service to access the data.

## IOA - Indicator of Attack

These _indicators of attack_ (IOA) list the potential fragments used for technical activities like reconnaissance, exploitation, privilege escalation, and exfiltration by Domino. This data is unique as it uses our predictive model for actor profiling.

ID | Type | Indicator | Confidence
-- | ---- | --------- | ----------
1 | File | `/?ajax-request=jnews` | High
2 | File | `/api/RecordingList/DownloadRecord?file=` | High
3 | File | `/app/options.py` | High
4 | File | `/apply.cgi` | Medium
5 | File | `/auth_files/photo/` | High
6 | File | `/backend/admin/his_admin_add_lab_equipment.php` | High
7 | File | `/card_scan.php` | High
8 | File | `/cgi-bin/cstecgi.cgi` | High
9 | File | `/cgi-bin/wlogin.cgi` | High
10 | File | `/cwc/login` | Medium
11 | File | `/debuginfo.htm` | High
12 | File | `/download` | Medium
13 | File | `/etc/passwd` | Medium
14 | File | `/etc/quagga` | Medium
15 | File | `/etc/shadow` | Medium
16 | File | `/forms/doLogin` | High
17 | File | `/h/autoSaveDraft` | High
18 | File | `/h/calendar` | Medium
19 | File | `/inc/extensions.php` | High
20 | File | `/mhds/clinic/view_details.php` | High
21 | File | `/netflow/jspui/editProfile.jsp` | High
22 | File | `/nova/bin/console` | High
23 | File | `/nova/bin/detnet` | High
24 | File | `/out.php` | Medium
25 | File | `/php/ping.php` | High
26 | File | `/rapi/read_url` | High
27 | File | `/req_password_user.php` | High
28 | File | `/rom-0` | Low
29 | File | `/scripts/unlock_tasks.php` | High
30 | File | `/secure/QueryComponent!Default.jspa` | High
31 | File | `/ServletAPI/accounts/login` | High
32 | ... | ... | ...

There are 268 more IOA items available (file, library, argument, input value, pattern, network port). Please use our online service to access the data.

## References

The following list contains _external sources_ which discuss the actor and the associated activities:

* https://securityintelligence.com/posts/ex-conti-fin7-actors-collaborate-new-domino-backdoor/

## Literature

The following _articles_ explain our unique predictive cyber threat intelligence:

* [VulDB Cyber Threat Intelligence Documentation](https://vuldb.com/?kb.cti)
* [Cyber Threat Intelligence - Early Anticipation of Attacks](https://www.scip.ch/en/?labs.20201022)

## License

(c) [1997-2025](https://vuldb.com/?kb.changelog) by [vuldb.com](https://vuldb.com/?kb.about). All data on this page is shared under the license [CC BY-NC-SA 4.0](https://creativecommons.org/licenses/by-nc-sa/4.0/). Questions? Check the [FAQ](https://vuldb.com/?kb.faq), read the [documentation](https://vuldb.com/?kb) or [contact us](https://vuldb.com/?contact)!
