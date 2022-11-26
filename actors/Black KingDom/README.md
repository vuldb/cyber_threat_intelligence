# Black KingDom - Cyber Threat Intelligence

These _indicators_ were reported, collected, and generated during the [VulDB CTI analysis](https://vuldb.com/?kb.cti) of the actor known as [Black KingDom](https://vuldb.com/?actor.black_kingdom). The _activity monitoring_ correlates data from social media, forums, chat rooms, and darknet markets. It helps to determine associated actors, specific activities, expected intentions, emerging research, and ongoing attacks. Our unique _predictive model_ uses _big data_ to forecast activities and their characteristics.

_Live data_ and more _analysis capabilities_ are available at [https://vuldb.com/?actor.black_kingdom](https://vuldb.com/?actor.black_kingdom)

## Countries

These _countries_ are directly (e.g. origin of attacks) or indirectly (e.g. access by proxy) associated with Black KingDom:

* [US](https://vuldb.com/?country.us)
* [GB](https://vuldb.com/?country.gb)
* [NO](https://vuldb.com/?country.no)

## IOC - Indicator of Compromise

These _indicators of compromise_ (IOC) indicate associated network resources which are known to be part of research and attack activities of Black KingDom.

ID | IP address | Hostname | Campaign | Confidence
-- | ---------- | -------- | -------- | ----------
1 | [104.21.89.10](https://vuldb.com/?ip.104.21.89.10) | - | - | High
2 | [172.64.80.0](https://vuldb.com/?ip.172.64.80.0) | - | - | High
3 | [185.220.101.204](https://vuldb.com/?ip.185.220.101.204) | tor-exit-204.relayon.org | - | High
4 | ... | ... | ... | ...

There are 1 more IOC items available. Please use our online service to access the data.

## TTP - Tactics, Techniques, Procedures

_Tactics, techniques, and procedures_ (TTP) summarize the suspected MITRE ATT&CK techniques used by _Black KingDom_. This data is unique as it uses our predictive model for actor profiling.

ID | Technique | Weakness | Description | Confidence
-- | --------- | -------- | ----------- | ----------
1 | T1006 | CWE-21, CWE-22, CWE-23, CWE-37 | Pathname Traversal | High
2 | T1040 | CWE-294, CWE-319 | Authentication Bypass by Capture-replay | High
3 | T1055 | CWE-74 | Injection | High
4 | T1059 | CWE-88, CWE-94, CWE-1321 | Cross Site Scripting | High
5 | T1059.007 | CWE-79, CWE-80 | Cross Site Scripting | High
6 | ... | ... | ... | ...

There are 21 more TTP items available. Please use our online service to access the data.

## IOA - Indicator of Attack

These _indicators of attack_ (IOA) list the potential fragments used for technical activities like reconnaissance, exploitation, privilege escalation, and exfiltration by Black KingDom. This data is unique as it uses our predictive model for actor profiling.

ID | Type | Indicator | Confidence
-- | ---- | --------- | ----------
1 | File | `/action/import_cert_file/` | High
2 | File | `/action/import_e2c_json_file/` | High
3 | File | `/action/import_file/` | High
4 | File | `/action/import_wireguard_cert_file/` | High
5 | File | `/action/import_xml_file/` | High
6 | File | `/action/ipcamRecordPost` | High
7 | File | `/action/ipcamSetParamPost` | High
8 | File | `/action/wirelessConnect` | High
9 | File | `/admin/?page=bookings/view_details` | High
10 | File | `/admin/?page=orders/manage_request` | High
11 | File | `/admin/?page=user/manage_user` | High
12 | File | `/admin/controller/JobLogController.java` | High
13 | File | `/Admin/createClass.php` | High
14 | File | `/admin/fst_upload.inc.php` | High
15 | File | `/admin/sign/out` | High
16 | File | `/admin/students/manage.php` | High
17 | File | `/api/common/ping` | High
18 | File | `/api/public/signup` | High
19 | File | `/api/v1/attack/falco` | High
20 | File | `/api/v1/bait/set` | High
21 | File | `/api/v1/nics/wifi/wlan0/ping` | High
22 | File | `/api/v2/cli/commands` | High
23 | File | `/asms/admin/?page=user/manage_user` | High
24 | File | `/attachments` | Medium
25 | File | `/bookings/update_status.php` | High
26 | File | `/cgi-bin/wlogin.cgi` | High
27 | File | `/classes/Master.php?f=delete_appointment` | High
28 | File | `/classes/Users.php?f=delete_client` | High
29 | File | `/clearance/clearance.php` | High
30 | File | `/depotHead/list` | High
31 | ... | ... | ...

There are 266 more IOA items available (file, library, argument, input value, pattern, network port). Please use our online service to access the data.

## References

The following list contains _external sources_ which discuss the actor and the associated activities:

* https://github.com/sophoslabs/IoCs/blob/master/Ransomware_BlackKingDom.csv

## Literature

The following _articles_ explain our unique predictive cyber threat intelligence:

* [VulDB Cyber Threat Intelligence Documentation](https://vuldb.com/?kb.cti)
* [Cyber Threat Intelligence - Early Anticipation of Attacks](https://www.scip.ch/en/?labs.20201022)

## License

(c) [1997-2022](https://vuldb.com/?kb.changelog) by [vuldb.com](https://vuldb.com/?kb.about). All data on this page is shared under the license [CC BY-NC-SA 4.0](https://creativecommons.org/licenses/by-nc-sa/4.0/). Questions? Check the [FAQ](https://vuldb.com/?kb.faq), read the [documentation](https://vuldb.com/?kb) or [contact us](https://vuldb.com/?contact)!
