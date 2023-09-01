# Guinea Unknown - Cyber Threat Intelligence

These _indicators_ were reported, collected, and generated during the [VulDB CTI analysis](https://vuldb.com/?kb.cti) of the actor known as [Guinea Unknown](https://vuldb.com/?actor.guinea_unknown). The _activity monitoring_ correlates data from social media, forums, chat rooms, and darknet markets. It helps to determine associated actors, specific activities, expected intentions, emerging research, and ongoing attacks. Our unique _predictive model_ uses _big data_ to forecast activities and their characteristics.

_Live data_ and more _analysis capabilities_ are available at [https://vuldb.com/?actor.guinea_unknown](https://vuldb.com/?actor.guinea_unknown)

## Countries

These _countries_ are directly (e.g. origin of attacks) or indirectly (e.g. access by proxy) associated with Guinea Unknown:

* [US](https://vuldb.com/?country.us)
* [FR](https://vuldb.com/?country.fr)
* [ES](https://vuldb.com/?country.es)
* ...

There are 19 more country items available. Please use our online service to access the data.

## IOC - Indicator of Compromise

These _indicators of compromise_ (IOC) indicate associated network resources which are known to be part of research and attack activities of Guinea Unknown.

ID | IP address | Hostname | Campaign | Confidence
-- | ---------- | -------- | -------- | ----------
1 | [5.62.60.172](https://vuldb.com/?ip.5.62.60.172) | r-172-60-62-5.consumer-pool.prcdn.net | - | High
2 | [5.62.62.164](https://vuldb.com/?ip.5.62.62.164) | r-164-62-62-5.consumer-pool.prcdn.net | - | High
3 | [41.77.184.0](https://vuldb.com/?ip.41.77.184.0) | - | - | High
4 | [41.79.200.0](https://vuldb.com/?ip.41.79.200.0) | - | - | High
5 | [41.79.236.0](https://vuldb.com/?ip.41.79.236.0) | - | - | High
6 | [41.191.220.0](https://vuldb.com/?ip.41.191.220.0) | - | - | High
7 | [41.223.48.0](https://vuldb.com/?ip.41.223.48.0) | - | - | High
8 | [41.242.88.0](https://vuldb.com/?ip.41.242.88.0) | - | - | High
9 | [45.12.70.87](https://vuldb.com/?ip.45.12.70.87) | capitate.yourbandinc.com | - | High
10 | [45.12.71.87](https://vuldb.com/?ip.45.12.71.87) | - | - | High
11 | [45.59.154.0](https://vuldb.com/?ip.45.59.154.0) | - | - | High
12 | [45.220.52.0](https://vuldb.com/?ip.45.220.52.0) | - | - | High
13 | [57.82.160.0](https://vuldb.com/?ip.57.82.160.0) | - | - | High
14 | ... | ... | ... | ...

There are 54 more IOC items available. Please use our online service to access the data.

## TTP - Tactics, Techniques, Procedures

_Tactics, techniques, and procedures_ (TTP) summarize the suspected MITRE ATT&CK techniques used by _Guinea Unknown_. This data is unique as it uses our predictive model for actor profiling.

ID | Technique | Weakness | Description | Confidence
-- | --------- | -------- | ----------- | ----------
1 | T1006 | CWE-21, CWE-22 | Pathname Traversal | High
2 | T1055 | CWE-74 | Injection | High
3 | T1059 | CWE-94 | Cross Site Scripting | High
4 | T1059.007 | CWE-79, CWE-80 | Cross Site Scripting | High
5 | ... | ... | ... | ...

There are 16 more TTP items available. Please use our online service to access the data.

## IOA - Indicator of Attack

These _indicators of attack_ (IOA) list the potential fragments used for technical activities like reconnaissance, exploitation, privilege escalation, and exfiltration by Guinea Unknown. This data is unique as it uses our predictive model for actor profiling.

ID | Type | Indicator | Confidence
-- | ---- | --------- | ----------
1 | File | `/.env` | Low
2 | File | `/?Page=Node/OBJ=/System/DeviceFolder/DeviceFolder/DateTime/Action=Submit` | High
3 | File | `/acms/admin/cargo_types/manage_cargo_type.php` | High
4 | File | `/admin/ajax/avatar.php` | High
5 | File | `/admin/forgot-password.php` | High
6 | File | `/admin/index.php` | High
7 | File | `/admin/lab.php` | High
8 | File | `/admin/payment.php` | High
9 | File | `/admin/show.php` | High
10 | File | `/default.php?idx=17` | High
11 | File | `/download` | Medium
12 | File | `/env` | Low
13 | File | `/forum/away.php` | High
14 | File | `/index.php` | Medium
15 | File | `/nova/bin/traceroute` | High
16 | File | `/opt/bin/cli` | Medium
17 | File | `/p` | Low
18 | File | `/patient/doctors.php` | High
19 | File | `/phpinventory/editcategory.php` | High
20 | File | `/php_action/createUser.php` | High
21 | File | `/product-list.php` | High
22 | File | `/spip.php` | Medium
23 | File | `/uncpath/` | Medium
24 | File | `/updown/upload.cgi` | High
25 | File | `/user/del.php` | High
26 | File | `/_next` | Low
27 | File | `123flashchat.php` | High
28 | File | `act.php` | Low
29 | File | `admin.php` | Medium
30 | File | `admin/bad.php` | High
31 | File | `admin/index.php` | High
32 | File | `admin/index.php/user/del/1` | High
33 | File | `admin/index.php?id=themes&action=edit_chunk` | High
34 | File | `administrator/index.php` | High
35 | File | `agenda.php` | Medium
36 | File | `ajax/autocompletion.php` | High
37 | File | `ajax/render/widget_php` | High
38 | ... | ... | ...

There are 331 more IOA items available (file, library, argument, input value, pattern, network port). Please use our online service to access the data.

## References

The following list contains _external sources_ which discuss the actor and the associated activities:

* https://github.com/firehol/blocklist-ipsets/blob/master/geolite2_country/country_gn.netset
* https://github.com/firehol/blocklist-ipsets/blob/master/ip2location_country/ip2location_country_gn.netset
* https://github.com/firehol/blocklist-ipsets/blob/master/ipip_country/ipip_country_gn.netset

## Literature

The following _articles_ explain our unique predictive cyber threat intelligence:

* [VulDB Cyber Threat Intelligence Documentation](https://vuldb.com/?kb.cti)
* [Cyber Threat Intelligence - Early Anticipation of Attacks](https://www.scip.ch/en/?labs.20201022)

## License

(c) [1997-2023](https://vuldb.com/?kb.changelog) by [vuldb.com](https://vuldb.com/?kb.about). All data on this page is shared under the license [CC BY-NC-SA 4.0](https://creativecommons.org/licenses/by-nc-sa/4.0/). Questions? Check the [FAQ](https://vuldb.com/?kb.faq), read the [documentation](https://vuldb.com/?kb) or [contact us](https://vuldb.com/?contact)!
