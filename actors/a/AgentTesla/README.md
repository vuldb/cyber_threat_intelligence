# AgentTesla - Cyber Threat Intelligence

These _indicators_ were reported, collected, and generated during the [VulDB CTI analysis](https://vuldb.com/?kb.cti) of the actor known as [AgentTesla](https://vuldb.com/?actor.agenttesla). The _activity monitoring_ correlates data from social media, forums, chat rooms, and darknet markets. It helps to determine associated actors, specific activities, expected intentions, emerging research, and ongoing attacks. Our unique _predictive model_ uses _big data_ to forecast activities and their characteristics.

_Live data_ and more _analysis capabilities_ are available at [https://vuldb.com/?actor.agenttesla](https://vuldb.com/?actor.agenttesla)

## Countries

These _countries_ are directly (e.g. origin of attacks) or indirectly (e.g. access by proxy) associated with AgentTesla:

* [US](https://vuldb.com/?country.us)
* [CN](https://vuldb.com/?country.cn)
* [RU](https://vuldb.com/?country.ru)
* ...

There are 12 more country items available. Please use our online service to access the data.

## IOC - Indicator of Compromise

These _indicators of compromise_ (IOC) indicate associated network resources which are known to be part of research and attack activities of AgentTesla.

ID | IP address | Hostname | Campaign | Confidence
-- | ---------- | -------- | -------- | ----------
1 | [3.4.1.4](https://vuldb.com/?ip.3.4.1.4) | - | - | High
2 | [3.148.232.49](https://vuldb.com/?ip.3.148.232.49) | ec2-3-148-232-49.us-east-2.compute.amazonaws.com | - | Medium
3 | [23.94.239.89](https://vuldb.com/?ip.23.94.239.89) | 23-94-239-89-host.colocrossing.com | - | High
4 | [43.229.135.199](https://vuldb.com/?ip.43.229.135.199) | - | - | High
5 | [45.67.228.51](https://vuldb.com/?ip.45.67.228.51) | vm1700022.stark-industries.solutions | - | High
6 | [66.63.187.170](https://vuldb.com/?ip.66.63.187.170) | - | - | High
7 | [75.127.7.164](https://vuldb.com/?ip.75.127.7.164) | 75-127-7-164-host.colocrossing.com | - | High
8 | [82.115.209.180](https://vuldb.com/?ip.82.115.209.180) | - | - | High
9 | [89.47.1.10](https://vuldb.com/?ip.89.47.1.10) | - | - | High
10 | [94.156.65.197](https://vuldb.com/?ip.94.156.65.197) | - | - | High
11 | [96.44.154.198](https://vuldb.com/?ip.96.44.154.198) | - | - | High
12 | ... | ... | ... | ...

There are 46 more IOC items available. Please use our online service to access the data.

## TTP - Tactics, Techniques, Procedures

_Tactics, techniques, and procedures_ (TTP) summarize the suspected MITRE ATT&CK techniques used by _AgentTesla_. This data is unique as it uses our predictive model for actor profiling.

ID | Technique | Weakness | Description | Confidence
-- | --------- | -------- | ----------- | ----------
1 | T1006 | CWE-22, CWE-24 | Path Traversal | High
2 | T1055 | CWE-74 | Improper Neutralization of Data within XPath Expressions | High
3 | T1059 | CWE-88, CWE-94 | Argument Injection | High
4 | T1059.007 | CWE-79, CWE-80, CWE-85 | Basic Cross Site Scripting | High
5 | ... | ... | ... | ...

There are 16 more TTP items available. Please use our online service to access the data.

## IOA - Indicator of Attack

These _indicators of attack_ (IOA) list the potential fragments used for technical activities like reconnaissance, exploitation, privilege escalation, and exfiltration by AgentTesla. This data is unique as it uses our predictive model for actor profiling.

ID | Type | Indicator | Confidence
-- | ---- | --------- | ----------
1 | File | `/academic-calendar` | High
2 | File | `/action.php` | Medium
3 | File | `/add_personal_details.php` | High
4 | File | `/admin/add-team.php` | High
5 | File | `/admin/admin_feature.php` | High
6 | File | `/admin/between-date-userreport.php` | High
7 | File | `/admin/delete_user.php` | High
8 | File | `/admin/edit-customer-detailed.php` | High
9 | File | `/admin/edit-subcategory.php` | High
10 | File | `/admin/edit_slider.php` | High
11 | File | `/admin/emp-profile-avatar.php` | High
12 | File | `/admin/manage_complaint.php` | High
13 | File | `/admin/pages/` | High
14 | File | `/admin/patient-search.php` | High
15 | File | `/admin/positions.php` | High
16 | File | `/admin/profile.php` | High
17 | File | `/admin/report.php` | High
18 | File | `/admin/student_edit_photo.php` | High
19 | File | `/adminapi/system/crud` | High
20 | File | `/admins` | Low
21 | File | `/ajax.php?action=delete_package` | High
22 | File | `/ajax/getBasicInfo.php` | High
23 | File | `/api/admin/system/store/order/list` | High
24 | File | `/api/v1/attack/falco` | High
25 | File | `/arp_sys.asp` | Medium
26 | File | `/backend/register.php` | High
27 | File | `/boafrm/formDMZ` | High
28 | File | `/boafrm/formDosCfg` | High
29 | File | `/boafrm/formStats` | High
30 | File | `/boafrm/formWirelessTbl` | High
31 | File | `/CDGServer3/logManagement/ClientSortLog.jsp` | High
32 | File | `/cgi-bin/cstecgi.cgi` | High
33 | File | `/cgi-bin/luci/api/cmd` | High
34 | File | `/cgi-bin/nas_sharing.cgi` | High
35 | File | `/cgi-bin/sessions/get-temp-file` | High
36 | File | `/cgi-bin/wlogin.cgi` | High
37 | File | `/classes/Master.php` | High
38 | File | `/classes/Master.php?f=delete_category` | High
39 | File | `/classes/SystemSettings.php?f=update_settings` | High
40 | File | `/classes/Users.php?f=save` | High
41 | ... | ... | ...

There are 356 more IOA items available (file, library, argument, input value, pattern, network port). Please use our online service to access the data.

## References

The following list contains _external sources_ which discuss the actor and the associated activities:

* https://blog.malwarebytes.com/threat-analysis/2020/04/new-agenttesla-variant-steals-wifi-credentials/
* https://blog.talosintelligence.com/threat-roundup-1013-1020/
* https://cyble.com/blog/agenttesla-spreads-through-chm-and-pdf-files-in-recent-attacks/
* https://cyble.com/blog/threat-actor-employs-powershell-backed-steganography-in-recent-spam-campaigns/
* https://exchange.xforce.ibmcloud.com/
* https://urlhaus.abuse.ch/url/3518493/
* https://urlhaus.abuse.ch/url/3526261/
* https://urlhaus.abuse.ch/url/3528091/
* https://urlhaus.abuse.ch/url/3535589/
* https://urlhaus.abuse.ch/url/3543271/
* https://urlhaus.abuse.ch/url/3544158/
* https://urlhaus.abuse.ch/url/3545537/
* https://urlhaus.abuse.ch/url/3545546/
* https://urlhaus.abuse.ch/url/3547882/
* https://urlhaus.abuse.ch/url/3549509/
* https://urlhaus.abuse.ch/url/3549543/
* https://urlhaus.abuse.ch/url/3551995/
* https://urlhaus.abuse.ch/url/3553696/
* https://urlhaus.abuse.ch/url/3555541/
* https://urlhaus.abuse.ch/url/3556364/
* https://urlhaus.abuse.ch/url/3559206/
* https://urlhaus.abuse.ch/url/3561489/
* https://urlhaus.abuse.ch/url/3562540/
* https://urlhaus.abuse.ch/url/3562583/
* https://urlhaus.abuse.ch/url/3569922/
* https://urlhaus.abuse.ch/url/3572468/
* https://urlhaus.abuse.ch/url/3578900/
* https://urlhaus.abuse.ch/url/3586405/
* https://urlhaus.abuse.ch/url/3587562/
* https://urlhaus.abuse.ch/url/3591517/
* https://urlhaus.abuse.ch/url/3591583/
* https://urlhaus.abuse.ch/url/3593047/
* https://urlhaus.abuse.ch/url/3599564/
* https://urlhaus.abuse.ch/url/3602933/
* https://urlhaus.abuse.ch/url/3611143/
* https://urlhaus.abuse.ch/url/3611346/
* https://urlhaus.abuse.ch/url/3622733/
* https://urlhaus.abuse.ch/url/3633041/
* https://urlhaus.abuse.ch/url/3639282/
* https://www.mcafee.com/blogs/other-blogs/mcafee-labs/from-email-to-rat-deciphering-a-vb-script-driven-campaign/

## Literature

The following _articles_ explain our unique predictive cyber threat intelligence:

* [VulDB Cyber Threat Intelligence Documentation](https://vuldb.com/?kb.cti)
* [Cyber Threat Intelligence - Early Anticipation of Attacks](https://www.scip.ch/en/?labs.20201022)

## License

(c) [1997-2025](https://vuldb.com/?kb.changelog) by [vuldb.com](https://vuldb.com/?kb.about). All data on this page is shared under the license [CC BY-NC-SA 4.0](https://creativecommons.org/licenses/by-nc-sa/4.0/). Questions? Check the [FAQ](https://vuldb.com/?kb.faq), read the [documentation](https://vuldb.com/?kb) or [contact us](https://vuldb.com/?contact)!
