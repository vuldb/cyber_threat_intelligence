# VMware - Cyber Threat Intelligence

These _indicators_ were reported, collected, and generated during the [VulDB CTI analysis](https://vuldb.com/?kb.cti) of the campaign known as _VMware_. The _activity monitoring_ correlates data from social media, forums, chat rooms, and darknet markets. It helps to determine associated actors, specific activities, expected intentions, emerging research, and ongoing attacks. Our unique _predictive model_ uses _big data_ to forecast activities and their characteristics.

_Live data_ and more _analysis capabilities_ are available at [https://vuldb.com/?actor](https://vuldb.com/?actor)

## Countries

These _countries_ are directly (e.g. origin of attacks) or indirectly (e.g. access by proxy) associated with VMware:

* [US](https://vuldb.com/?country.us)
* [CN](https://vuldb.com/?country.cn)
* [GB](https://vuldb.com/?country.gb)
* ...

There are 12 more country items available. Please use our online service to access the data.

## Actors

These _actors_ are associated with VMware or other actors linked to the campaign.

ID | Actor | Confidence
-- | ----- | ----------
1 | [Unknown](https://vuldb.com/?actor.unknown) | High

## IOC - Indicator of Compromise

These _indicators of compromise_ (IOC) indicate associated network resources which are known to be part of research and attack activities of VMware.

ID | IP address | Hostname | Actor | Confidence
-- | ---------- | -------- | ----- | ----------
1 | [20.232.97.189](https://vuldb.com/?ip.20.232.97.189) | - | [Unknown](https://vuldb.com/?actor.unknown) | High
2 | [45.72.85.172](https://vuldb.com/?ip.45.72.85.172) | - | [Unknown](https://vuldb.com/?actor.unknown) | High
3 | [45.72.112.245](https://vuldb.com/?ip.45.72.112.245) | fkcoqootrd.pottspsychic.site | [Unknown](https://vuldb.com/?actor.unknown) | High
4 | [51.79.171.53](https://vuldb.com/?ip.51.79.171.53) | ip53.ip-51-79-171.net | [Unknown](https://vuldb.com/?actor.unknown) | High
5 | ... | ... | ... | ...

There are 16 more IOC items available. Please use our online service to access the data.

## TTP - Tactics, Techniques, Procedures

_Tactics, techniques, and procedures_ (TTP) summarize the suspected MITRE ATT&CK techniques used within VMware. This data is unique as it uses our predictive model for actor profiling.

ID | Technique | Weakness | Description | Confidence
-- | --------- | -------- | ----------- | ----------
1 | T1006 | CWE-22, CWE-37 | Pathname Traversal | High
2 | T1055 | CWE-74 | Injection | High
3 | T1059 | CWE-94 | Cross Site Scripting | High
4 | T1059.007 | CWE-79, CWE-80 | Cross Site Scripting | High
5 | ... | ... | ... | ...

There are 18 more TTP items available. Please use our online service to access the data.

## IOA - Indicator of Attack

These _indicators of attack_ (IOA) list the potential fragments used for technical activities like reconnaissance, exploitation, privilege escalation, and exfiltration during VMware. This data is unique as it uses our predictive model for actor profiling.

ID | Type | Indicator | Confidence
-- | ---- | --------- | ----------
1 | File | `/admin/blog/blogcategory/add/?_to_field=id&_popup=1` | High
2 | File | `/admin/maintenance/brand.php` | High
3 | File | `/api/baskets/{name}` | High
4 | File | `/api/users/admin/check` | High
5 | File | `/category_view.php` | High
6 | File | `/config/getuser` | High
7 | File | `/connectors/index.php` | High
8 | File | `/etc/init.d/opsview-reporting-module` | High
9 | File | `/etc/passwd` | Medium
10 | File | `/forum/away.php` | High
11 | File | `/getcfg.php` | Medium
12 | File | `/goform/aspForm` | High
13 | File | `/goform/form2userconfig.cgi` | High
14 | File | `/gracemedia-media-player/templates/files/ajax_controller.php` | High
15 | File | `/guest/index.html` | High
16 | File | `/HNAP1` | Low
17 | File | `/include/logs` | High
18 | File | `/index.php` | Medium
19 | File | `/index.php?page=forums&action=search` | High
20 | File | `/index.php?page=signup` | High
21 | File | `/index.php?page=viewnews` | High
22 | File | `/job-details` | Medium
23 | File | `/list-gitolite` | High
24 | File | `/login` | Low
25 | File | `/member/pm.php` | High
26 | File | `/objects/getSpiritsFromVideo.php` | High
27 | File | `/onvif/device_service` | High
28 | File | `/rapi/read_url` | High
29 | File | `/secure/QueryComponent!Default.jspa` | High
30 | File | `/SetTriggerWPS/PIN` | High
31 | File | `/tab_tariffe.php` | High
32 | File | `/var/log/drachtio` | High
33 | File | `/var/log/groonga` | High
34 | File | `/visualizza_tabelle.php` | High
35 | File | `/wp-admin/admin-ajax.php` | High
36 | File | `/wp-json/wc/v3/webhooks` | High
37 | File | `acrord32.exe` | Medium
38 | File | `admin.php/user/add` | High
39 | File | `admin.php?m=Member&a=adminadd` | High
40 | File | `admin/conf_users_edit.php` | High
41 | File | `admin/content.php` | High
42 | File | `admin/content/search.html` | High
43 | ... | ... | ...

There are 370 more IOA items available (file, library, argument, input value, pattern, network port). Please use our online service to access the data.

## References

The following list contains _external sources_ which discuss the campaign and the associated activities:

* https://blog.morphisec.com/vmware-identity-manager-attack-backdoor
* https://www.cisa.gov/uscert/ncas/alerts/aa22-138b

## Literature

The following _articles_ explain our unique predictive cyber threat intelligence:

* [VulDB Cyber Threat Intelligence Documentation](https://vuldb.com/?kb.cti)
* [Cyber Threat Intelligence - Early Anticipation of Attacks](https://www.scip.ch/en/?labs.20201022)

## License

(c) [1997-2024](https://vuldb.com/?kb.changelog) by [vuldb.com](https://vuldb.com/?kb.about). All data on this page is shared under the license [CC BY-NC-SA 4.0](https://creativecommons.org/licenses/by-nc-sa/4.0/). Questions? Check the [FAQ](https://vuldb.com/?kb.faq), read the [documentation](https://vuldb.com/?kb) or [contact us](https://vuldb.com/?contact)!
