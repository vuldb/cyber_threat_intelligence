# S.O.V.A. - Cyber Threat Intelligence

These _indicators_ were reported, collected, and generated during the [VulDB CTI analysis](https://vuldb.com/?kb.cti) of the actor known as [S.O.V.A.](https://vuldb.com/?actor.s.o.v.a.). The _activity monitoring_ correlates data from social media, forums, chat rooms, and darknet markets. It helps to determine associated actors, specific activities, expected intentions, emerging research, and ongoing attacks. Our unique _predictive model_ uses _big data_ to forecast activities and their characteristics.

_Live data_ and more _analysis capabilities_ are available at [https://vuldb.com/?actor.s.o.v.a.](https://vuldb.com/?actor.s.o.v.a.)

## Countries

These _countries_ are directly (e.g. origin of attacks) or indirectly (e.g. access by proxy) associated with S.O.V.A.:

* [DE](https://vuldb.com/?country.de)
* [US](https://vuldb.com/?country.us)
* [RU](https://vuldb.com/?country.ru)

## IOC - Indicator of Compromise

These _indicators of compromise_ (IOC) indicate associated network resources which are known to be part of research and attack activities of S.O.V.A..

ID | IP address | Hostname | Campaign | Confidence
-- | ---------- | -------- | -------- | ----------
1 | [5.161.16.85](https://vuldb.com/?ip.5.161.16.85) | static.85.16.161.5.clients.your-server.de | - | High
2 | [5.161.22.241](https://vuldb.com/?ip.5.161.22.241) | static.241.22.161.5.clients.your-server.de | - | High
3 | [5.161.105.24](https://vuldb.com/?ip.5.161.105.24) | static.24.105.161.5.clients.your-server.de | - | High
4 | ... | ... | ... | ...

There are 11 more IOC items available. Please use our online service to access the data.

## TTP - Tactics, Techniques, Procedures

_Tactics, techniques, and procedures_ (TTP) summarize the suspected MITRE ATT&CK techniques used by _S.O.V.A._. This data is unique as it uses our predictive model for actor profiling.

ID | Technique | Weakness | Description | Confidence
-- | --------- | -------- | ----------- | ----------
1 | T1006 | CWE-21, CWE-22 | Path Traversal | High
2 | T1040 | CWE-294 | Authentication Bypass by Capture-replay | High
3 | T1055 | CWE-74 | Improper Neutralization of Data within XPath Expressions | High
4 | T1059 | CWE-94, CWE-1321 | Argument Injection | High
5 | T1059.007 | CWE-79, CWE-80 | Basic Cross Site Scripting | High
6 | ... | ... | ... | ...

There are 19 more TTP items available. Please use our online service to access the data.

## IOA - Indicator of Attack

These _indicators of attack_ (IOA) list the potential fragments used for technical activities like reconnaissance, exploitation, privilege escalation, and exfiltration by S.O.V.A.. This data is unique as it uses our predictive model for actor profiling.

ID | Type | Indicator | Confidence
-- | ---- | --------- | ----------
1 | File | `/admin/login.php` | High
2 | File | `/admin/mechanics/manage_mechanic.php` | High
3 | File | `/admin/payment.php` | High
4 | File | `/admin_route/dec_service_credits.php` | High
5 | File | `/aterm_httpif.cgi/negotiate` | High
6 | File | `/cgi-bin/kerbynet` | High
7 | File | `/churchcrm/WhyCameEditor.php` | High
8 | File | `/cmsms-2.1.6-install.php/index.php` | High
9 | File | `/ControlManager/cgi-bin/VA/isaNVWRequest.dll` | High
10 | File | `/coreframe/app/member/admin/group.php` | High
11 | File | `/forum/away.php` | High
12 | File | `/goform/GetNewDir` | High
13 | File | `/guestmanagement/front.php` | High
14 | File | `/index.php` | Medium
15 | File | `/Interface/DevManage/VM.php` | High
16 | File | `/isec/index.php` | High
17 | File | `/proc/self/environ` | High
18 | File | `/Pwrchute` | Medium
19 | File | `/recordings/index.php` | High
20 | File | `/royal_event/companyprofile.php` | High
21 | File | `/school/model/get_events.php` | High
22 | File | `/setting_hidden.asp` | High
23 | File | `/spip.php` | Medium
24 | File | `/staff_login.php` | High
25 | File | `/usr/bin/gxserve-update.sh` | High
26 | File | `active_appointments.asp` | High
27 | File | `adds.php` | Medium
28 | File | `add_edit_user.asp` | High
29 | File | `admin/versions.html` | High
30 | File | `admindocumentworker.jsp` | High
31 | File | `admin_class.php` | High
32 | File | `albums.php` | Medium
33 | File | `announcements.php` | High
34 | ... | ... | ...

There are 288 more IOA items available (file, library, argument, input value, pattern, network port). Please use our online service to access the data.

## References

The following list contains _external sources_ which discuss the actor and the associated activities:

* https://threatfox.abuse.ch

## Literature

The following _articles_ explain our unique predictive cyber threat intelligence:

* [VulDB Cyber Threat Intelligence Documentation](https://vuldb.com/?kb.cti)
* [Cyber Threat Intelligence - Early Anticipation of Attacks](https://www.scip.ch/en/?labs.20201022)

## License

(c) [1997-2025](https://vuldb.com/?kb.changelog) by [vuldb.com](https://vuldb.com/?kb.about). All data on this page is shared under the license [CC BY-NC-SA 4.0](https://creativecommons.org/licenses/by-nc-sa/4.0/). Questions? Check the [FAQ](https://vuldb.com/?kb.faq), read the [documentation](https://vuldb.com/?kb) or [contact us](https://vuldb.com/?contact)!
