# VMware - Cyber Threat Intelligence

These _indicators_ were reported, collected, and generated during the [VulDB CTI analysis](https://vuldb.com/?kb.cti) of the campaign known as _VMware_. The _activity monitoring_ correlates data from social media, forums, chat rooms, and darknet markets. It helps to determine associated actors, specific activities, expected intentions, emerging research, and ongoing attacks. Our unique _predictive model_ uses _big data_ to forecast activities and their characteristics.

_Live data_ and more _analysis capabilities_ are available at [https://vuldb.com/?actor](https://vuldb.com/?actor)

## Countries

These _countries_ are directly (e.g. origin of attacks) or indirectly (e.g. access by proxy) associated with VMware:

* [US](https://vuldb.com/?country.us)
* [CN](https://vuldb.com/?country.cn)
* [GB](https://vuldb.com/?country.gb)
* ...

There are 11 more country items available. Please use our online service to access the data.

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
1 | T1006 | CWE-22 | Pathname Traversal | High
2 | T1055 | CWE-74 | Injection | High
3 | T1059 | CWE-94 | Cross Site Scripting | High
4 | T1059.007 | CWE-79, CWE-80 | Cross Site Scripting | High
5 | T1068 | CWE-250, CWE-264, CWE-269, CWE-284 | J2EE Misconfiguration: Weak Access Permissions for EJB Methods | High
6 | ... | ... | ... | ...

There are 18 more TTP items available. Please use our online service to access the data.

## IOA - Indicator of Attack

These _indicators of attack_ (IOA) list the potential fragments used for technical activities like reconnaissance, exploitation, privilege escalation, and exfiltration during VMware. This data is unique as it uses our predictive model for actor profiling.

ID | Type | Indicator | Confidence
-- | ---- | --------- | ----------
1 | File | `/admin/blog/blogcategory/add/?_to_field=id&_popup=1` | High
2 | File | `/api/baskets/{name}` | High
3 | File | `/api/users/admin/check` | High
4 | File | `/category_view.php` | High
5 | File | `/config/getuser` | High
6 | File | `/connectors/index.php` | High
7 | File | `/etc/init.d/opsview-reporting-module` | High
8 | File | `/etc/passwd` | Medium
9 | File | `/goform/form2userconfig.cgi` | High
10 | File | `/gracemedia-media-player/templates/files/ajax_controller.php` | High
11 | File | `/guest/index.html` | High
12 | File | `/HNAP1` | Low
13 | File | `/include/logs` | High
14 | File | `/index.php` | Medium
15 | File | `/index.php?page=forums&action=search` | High
16 | File | `/index.php?page=signup` | High
17 | File | `/index.php?page=viewnews` | High
18 | File | `/job-details` | Medium
19 | File | `/list-gitolite` | High
20 | File | `/login` | Low
21 | File | `/member/pm.php` | High
22 | File | `/objects/getSpiritsFromVideo.php` | High
23 | File | `/onvif/device_service` | High
24 | File | `/rapi/read_url` | High
25 | File | `/secure/QueryComponent!Default.jspa` | High
26 | File | `/SetTriggerWPS/PIN` | High
27 | File | `/tab_tariffe.php` | High
28 | File | `/var/log/drachtio` | High
29 | File | `/var/log/groonga` | High
30 | File | `/visualizza_tabelle.php` | High
31 | File | `/wp-admin/admin-ajax.php` | High
32 | File | `/wp-json/wc/v3/webhooks` | High
33 | File | `acrord32.exe` | Medium
34 | File | `admin.php/user/add` | High
35 | File | `admin.php?m=Member&a=adminadd` | High
36 | File | `admin/conf_users_edit.php` | High
37 | File | `admin/content.php` | High
38 | File | `admin/content/search.html` | High
39 | File | `admin/index.php?lfj=member&action=addmember` | High
40 | File | `admin/tool/ShowPic.php` | High
41 | File | `admin/ueditor/uploadFile` | High
42 | ... | ... | ...

There are 363 more IOA items available (file, library, argument, input value, pattern, network port). Please use our online service to access the data.

## References

The following list contains _external sources_ which discuss the campaign and the associated activities:

* https://blog.morphisec.com/vmware-identity-manager-attack-backdoor
* https://www.cisa.gov/uscert/ncas/alerts/aa22-138b

## Literature

The following _articles_ explain our unique predictive cyber threat intelligence:

* [VulDB Cyber Threat Intelligence Documentation](https://vuldb.com/?kb.cti)
* [Cyber Threat Intelligence - Early Anticipation of Attacks](https://www.scip.ch/en/?labs.20201022)

## License

(c) [1997-2023](https://vuldb.com/?kb.changelog) by [vuldb.com](https://vuldb.com/?kb.about). All data on this page is shared under the license [CC BY-NC-SA 4.0](https://creativecommons.org/licenses/by-nc-sa/4.0/). Questions? Check the [FAQ](https://vuldb.com/?kb.faq), read the [documentation](https://vuldb.com/?kb) or [contact us](https://vuldb.com/?contact)!
