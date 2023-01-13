# NukeSped - Cyber Threat Intelligence

These _indicators_ were reported, collected, and generated during the [VulDB CTI analysis](https://vuldb.com/?kb.cti) of the campaign known as _NukeSped_. The _activity monitoring_ correlates data from social media, forums, chat rooms, and darknet markets. It helps to determine associated actors, specific activities, expected intentions, emerging research, and ongoing attacks. Our unique _predictive model_ uses _big data_ to forecast activities and their characteristics.

_Live data_ and more _analysis capabilities_ are available at [https://vuldb.com/?actor](https://vuldb.com/?actor)

## Countries

These _countries_ are directly (e.g. origin of attacks) or indirectly (e.g. access by proxy) associated with NukeSped:

* [US](https://vuldb.com/?country.us)

## Actors

These _actors_ are associated with NukeSped or other actors linked to the campaign.

ID | Actor | Confidence
-- | ----- | ----------
1 | [Lazarus](https://vuldb.com/?actor.lazarus) | High
2 | [NukeSped](https://vuldb.com/?actor.nukesped) | High

## IOC - Indicator of Compromise

These _indicators of compromise_ (IOC) indicate associated network resources which are known to be part of research and attack activities of NukeSped.

ID | IP address | Hostname | Actor | Confidence
-- | ---------- | -------- | ----- | ----------
1 | [84.38.133.16](https://vuldb.com/?ip.84.38.133.16) | - | [NukeSped](https://vuldb.com/?actor.nukesped) | High
2 | [84.38.133.145](https://vuldb.com/?ip.84.38.133.145) | - | [NukeSped](https://vuldb.com/?actor.nukesped) | High
3 | [185.29.8.18](https://vuldb.com/?ip.185.29.8.18) | ip-8-18.dataclub.info | [NukeSped](https://vuldb.com/?actor.nukesped) | High

## TTP - Tactics, Techniques, Procedures

_Tactics, techniques, and procedures_ (TTP) summarize the suspected MITRE ATT&CK techniques used within NukeSped. This data is unique as it uses our predictive model for actor profiling.

ID | Technique | Weakness | Description | Confidence
-- | --------- | -------- | ----------- | ----------
1 | T1006 | CWE-22 | Pathname Traversal | High
2 | T1055 | CWE-74 | Injection | High
3 | T1059 | CWE-94 | Cross Site Scripting | High
4 | T1059.007 | CWE-79, CWE-80 | Cross Site Scripting | High
5 | ... | ... | ... | ...

There are 15 more TTP items available. Please use our online service to access the data.

## IOA - Indicator of Attack

These _indicators of attack_ (IOA) list the potential fragments used for technical activities like reconnaissance, exploitation, privilege escalation, and exfiltration during NukeSped. This data is unique as it uses our predictive model for actor profiling.

ID | Type | Indicator | Confidence
-- | ---- | --------- | ----------
1 | File | `/admin/blog/blogcategory/add/?_to_field=id&_popup=1` | High
2 | File | `/api/users/admin/check` | High
3 | File | `/connectors/index.php` | High
4 | File | `/etc/init.d/opsview-reporting-module` | High
5 | File | `/get_getnetworkconf.cgi` | High
6 | File | `/goform/edit_lf_get_data` | High
7 | File | `/goform/form2userconfig.cgi` | High
8 | File | `/guest/index.html` | High
9 | File | `/include/logs` | High
10 | File | `/index.php?page=forums&action=search` | High
11 | File | `/index.php?page=signup` | High
12 | File | `/index.php?page=viewnews` | High
13 | File | `/member/pm.php` | High
14 | File | `/onvif/device_service` | High
15 | File | `/proc` | Low
16 | File | `/proc/asound` | Medium
17 | File | `/rapi/read_url` | High
18 | File | `/tab_tariffe.php` | High
19 | File | `/var/log/groonga` | High
20 | File | `/visualizza_tabelle.php` | High
21 | File | `/VPortal/mgtconsole/AdminAuthorisationFrame.jsp` | High
22 | File | `/VPortal/mgtconsole/Subscriptions.jsp` | High
23 | File | `acrord32.exe` | Medium
24 | File | `action/addproject.php` | High
25 | File | `action/add_user.php` | High
26 | File | `admin.php/user/add` | High
27 | File | `admin.php?m=Member&a=adminadd` | High
28 | File | `admin/content/search.html` | High
29 | File | `admin/index.php?lfj=member&action=addmember` | High
30 | File | `admin/tool/ShowPic.php` | High
31 | File | `admin/uploader/uploader_categories/edit` | High
32 | File | `adv_remotelog.asp` | High
33 | File | `AjaxApplication.java` | High
34 | File | `album_cat.php` | High
35 | File | `AndroidManifest.xml` | High
36 | File | `Annot.c` | Low
37 | File | `app/admin/controller/themecontroller.php` | High
38 | File | `app/index.php/accounts/default/details?id=2&kanbanBoard=1&openToTaskId=1` | High
39 | ... | ... | ...

There are 336 more IOA items available (file, library, argument, input value, pattern, network port). Please use our online service to access the data.

## References

The following list contains _external sources_ which discuss the campaign and the associated activities:

* https://asec.ahnlab.com/en/34461/

## Literature

The following _articles_ explain our unique predictive cyber threat intelligence:

* [VulDB Cyber Threat Intelligence Documentation](https://vuldb.com/?kb.cti)
* [Cyber Threat Intelligence - Early Anticipation of Attacks](https://www.scip.ch/en/?labs.20201022)

## License

(c) [1997-2023](https://vuldb.com/?kb.changelog) by [vuldb.com](https://vuldb.com/?kb.about). All data on this page is shared under the license [CC BY-NC-SA 4.0](https://creativecommons.org/licenses/by-nc-sa/4.0/). Questions? Check the [FAQ](https://vuldb.com/?kb.faq), read the [documentation](https://vuldb.com/?kb) or [contact us](https://vuldb.com/?contact)!
