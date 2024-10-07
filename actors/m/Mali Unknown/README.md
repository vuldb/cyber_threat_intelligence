# Mali Unknown - Cyber Threat Intelligence

These _indicators_ were reported, collected, and generated during the [VulDB CTI analysis](https://vuldb.com/?kb.cti) of the actor known as [Mali Unknown](https://vuldb.com/?actor.mali_unknown). The _activity monitoring_ correlates data from social media, forums, chat rooms, and darknet markets. It helps to determine associated actors, specific activities, expected intentions, emerging research, and ongoing attacks. Our unique _predictive model_ uses _big data_ to forecast activities and their characteristics.

_Live data_ and more _analysis capabilities_ are available at [https://vuldb.com/?actor.mali_unknown](https://vuldb.com/?actor.mali_unknown)

## Countries

These _countries_ are directly (e.g. origin of attacks) or indirectly (e.g. access by proxy) associated with Mali Unknown:

* [US](https://vuldb.com/?country.us)
* [ES](https://vuldb.com/?country.es)
* [FR](https://vuldb.com/?country.fr)
* ...

There are 18 more country items available. Please use our online service to access the data.

## IOC - Indicator of Compromise

These _indicators of compromise_ (IOC) indicate associated network resources which are known to be part of research and attack activities of Mali Unknown.

ID | IP address | Hostname | Campaign | Confidence
-- | ---------- | -------- | -------- | ----------
1 | [5.62.61.4](https://vuldb.com/?ip.5.62.61.4) | r-4-61-62-5.consumer-pool.prcdn.net | - | High
2 | [5.62.62.252](https://vuldb.com/?ip.5.62.62.252) | r-252-62-62-5.consumer-pool.prcdn.net | - | High
3 | [41.73.96.0](https://vuldb.com/?ip.41.73.96.0) | - | - | High
4 | [41.203.192.0](https://vuldb.com/?ip.41.203.192.0) | - | - | High
5 | [41.221.176.0](https://vuldb.com/?ip.41.221.176.0) | - | - | High
6 | [45.12.70.146](https://vuldb.com/?ip.45.12.70.146) | mesure-whetted.alltieinc.com | - | High
7 | [45.12.71.146](https://vuldb.com/?ip.45.12.71.146) | - | - | High
8 | [45.42.129.0](https://vuldb.com/?ip.45.42.129.0) | - | - | High
9 | [45.61.37.0](https://vuldb.com/?ip.45.61.37.0) | - | - | High
10 | [57.82.154.0](https://vuldb.com/?ip.57.82.154.0) | - | - | High
11 | ... | ... | ... | ...

There are 38 more IOC items available. Please use our online service to access the data.

## TTP - Tactics, Techniques, Procedures

_Tactics, techniques, and procedures_ (TTP) summarize the suspected MITRE ATT&CK techniques used by _Mali Unknown_. This data is unique as it uses our predictive model for actor profiling.

ID | Technique | Weakness | Description | Confidence
-- | --------- | -------- | ----------- | ----------
1 | T1006 | CWE-21, CWE-22 | Path Traversal | High
2 | T1040 | CWE-294 | Authentication Bypass by Capture-replay | High
3 | T1055 | CWE-74 | Improper Neutralization of Data within XPath Expressions | High
4 | T1059 | CWE-94 | Argument Injection | High
5 | ... | ... | ... | ...

There are 14 more TTP items available. Please use our online service to access the data.

## IOA - Indicator of Attack

These _indicators of attack_ (IOA) list the potential fragments used for technical activities like reconnaissance, exploitation, privilege escalation, and exfiltration by Mali Unknown. This data is unique as it uses our predictive model for actor profiling.

ID | Type | Indicator | Confidence
-- | ---- | --------- | ----------
1 | File | `/?Page=Node/OBJ=/System/DeviceFolder/DeviceFolder/DateTime/Action=Submit` | High
2 | File | `/acms/admin/cargo_types/manage_cargo_type.php` | High
3 | File | `/admin/aboutus.php` | High
4 | File | `/admin/add-services.php` | High
5 | File | `/admin/addemployee.php` | High
6 | File | `/admin/ajax/avatar.php` | High
7 | File | `/admin/edit-services.php` | High
8 | File | `/admin/index.php` | High
9 | File | `/admin/login.php` | High
10 | File | `/admin/show.php` | High
11 | File | `/apilog.php` | Medium
12 | File | `/boat/login.php` | High
13 | File | `/clinic/disease_symptoms_view.php` | High
14 | File | `/default.php?idx=17` | High
15 | File | `/downloadFile.php` | High
16 | File | `/filemanager/upload.php` | High
17 | File | `/forum/away.php` | High
18 | File | `/healthcare/Admin/consulting_detail.php` | High
19 | File | `/I/list.php` | Medium
20 | File | `/index.php` | Medium
21 | File | `/member.php?action=chgpwdsubmit` | High
22 | File | `/mifs/c/i/reg/reg.html` | High
23 | File | `/models/management_model.php` | High
24 | File | `/opt/bin/cli` | Medium
25 | File | `/patient/doctors.php` | High
26 | File | `/phpinventory/editcategory.php` | High
27 | File | `/royal_event/userregister.php` | High
28 | File | `/signup.php` | Medium
29 | File | `/spip.php` | Medium
30 | File | `/uncpath/` | Medium
31 | File | `/update-employee.php` | High
32 | File | `/var/log/nginx` | High
33 | File | `/VPortal/mgtconsole/Subscriptions.jsp` | High
34 | File | `/wp-admin/admin-ajax.php` | High
35 | File | `/zm/index.php` | High
36 | File | `3/E_bak5.1/upload/eginfo.php` | High
37 | File | `admin` | Low
38 | File | `admin.php/pay` | High
39 | File | `admin/adminsignin.html` | High
40 | File | `admin/bad.php` | High
41 | File | `admin/index.php?id=themes&action=edit_chunk` | High
42 | File | `admin/movieview.php` | High
43 | File | `admin/products/controller.php?action=add` | High
44 | File | `admin/products/view_product.php` | High
45 | File | `admin/systempreferences.pl` | High
46 | File | `admin/versions.html` | High
47 | File | `admini/admin.php` | High
48 | ... | ... | ...

There are 420 more IOA items available (file, library, argument, input value, pattern, network port). Please use our online service to access the data.

## References

The following list contains _external sources_ which discuss the actor and the associated activities:

* https://github.com/firehol/blocklist-ipsets/blob/master/geolite2_country/country_ml.netset
* https://github.com/firehol/blocklist-ipsets/blob/master/ip2location_country/ip2location_country_ml.netset
* https://github.com/firehol/blocklist-ipsets/blob/master/ipip_country/ipip_country_ml.netset

## Literature

The following _articles_ explain our unique predictive cyber threat intelligence:

* [VulDB Cyber Threat Intelligence Documentation](https://vuldb.com/?kb.cti)
* [Cyber Threat Intelligence - Early Anticipation of Attacks](https://www.scip.ch/en/?labs.20201022)

## License

(c) [1997-2024](https://vuldb.com/?kb.changelog) by [vuldb.com](https://vuldb.com/?kb.about). All data on this page is shared under the license [CC BY-NC-SA 4.0](https://creativecommons.org/licenses/by-nc-sa/4.0/). Questions? Check the [FAQ](https://vuldb.com/?kb.faq), read the [documentation](https://vuldb.com/?kb) or [contact us](https://vuldb.com/?contact)!
