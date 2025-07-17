# Revenge RAT - Cyber Threat Intelligence

These _indicators_ were reported, collected, and generated during the [VulDB CTI analysis](https://vuldb.com/?kb.cti) of the actor known as [Revenge RAT](https://vuldb.com/?actor.revenge_rat). The _activity monitoring_ correlates data from social media, forums, chat rooms, and darknet markets. It helps to determine associated actors, specific activities, expected intentions, emerging research, and ongoing attacks. Our unique _predictive model_ uses _big data_ to forecast activities and their characteristics.

_Live data_ and more _analysis capabilities_ are available at [https://vuldb.com/?actor.revenge_rat](https://vuldb.com/?actor.revenge_rat)

## Countries

These _countries_ are directly (e.g. origin of attacks) or indirectly (e.g. access by proxy) associated with Revenge RAT:

* [BR](https://vuldb.com/?country.br)
* [US](https://vuldb.com/?country.us)
* [CN](https://vuldb.com/?country.cn)
* ...

There are 11 more country items available. Please use our online service to access the data.

## IOC - Indicator of Compromise

These _indicators of compromise_ (IOC) indicate associated network resources which are known to be part of research and attack activities of Revenge RAT.

ID | IP address | Hostname | Campaign | Confidence
-- | ---------- | -------- | -------- | ----------
1 | [3.138.180.119](https://vuldb.com/?ip.3.138.180.119) | ec2-3-138-180-119.us-east-2.compute.amazonaws.com | - | Medium
2 | [5.39.19.8](https://vuldb.com/?ip.5.39.19.8) | - | - | High
3 | [5.79.71.205](https://vuldb.com/?ip.5.79.71.205) | - | - | High
4 | [5.79.71.225](https://vuldb.com/?ip.5.79.71.225) | - | - | High
5 | [13.49.66.229](https://vuldb.com/?ip.13.49.66.229) | ec2-13-49-66-229.eu-north-1.compute.amazonaws.com | - | Medium
6 | [16.171.35.35](https://vuldb.com/?ip.16.171.35.35) | ec2-16-171-35-35.eu-north-1.compute.amazonaws.com | - | Medium
7 | [18.228.165.84](https://vuldb.com/?ip.18.228.165.84) | ec2-18-228-165-84.sa-east-1.compute.amazonaws.com | - | Medium
8 | [18.228.173.171](https://vuldb.com/?ip.18.228.173.171) | ec2-18-228-173-171.sa-east-1.compute.amazonaws.com | - | Medium
9 | [18.228.214.231](https://vuldb.com/?ip.18.228.214.231) | ec2-18-228-214-231.sa-east-1.compute.amazonaws.com | - | Medium
10 | [18.231.106.232](https://vuldb.com/?ip.18.231.106.232) | ec2-18-231-106-232.sa-east-1.compute.amazonaws.com | - | Medium
11 | [18.231.150.177](https://vuldb.com/?ip.18.231.150.177) | ec2-18-231-150-177.sa-east-1.compute.amazonaws.com | - | Medium
12 | [18.231.151.211](https://vuldb.com/?ip.18.231.151.211) | ec2-18-231-151-211.sa-east-1.compute.amazonaws.com | - | Medium
13 | [23.237.25.123](https://vuldb.com/?ip.23.237.25.123) | - | - | High
14 | [37.0.11.45](https://vuldb.com/?ip.37.0.11.45) | - | - | High
15 | [38.51.135.44](https://vuldb.com/?ip.38.51.135.44) | - | - | High
16 | ... | ... | ... | ...

There are 58 more IOC items available. Please use our online service to access the data.

## TTP - Tactics, Techniques, Procedures

_Tactics, techniques, and procedures_ (TTP) summarize the suspected MITRE ATT&CK techniques used by _Revenge RAT_. This data is unique as it uses our predictive model for actor profiling.

ID | Technique | Weakness | Description | Confidence
-- | --------- | -------- | ----------- | ----------
1 | T1006 | CWE-22, CWE-23, CWE-35 | Path Traversal | High
2 | T1040 | CWE-294 | Authentication Bypass by Capture-replay | High
3 | T1055 | CWE-74 | Improper Neutralization of Data within XPath Expressions | High
4 | T1059 | CWE-94, CWE-1321 | Argument Injection | High
5 | ... | ... | ... | ...

There are 17 more TTP items available. Please use our online service to access the data.

## IOA - Indicator of Attack

These _indicators of attack_ (IOA) list the potential fragments used for technical activities like reconnaissance, exploitation, privilege escalation, and exfiltration by Revenge RAT. This data is unique as it uses our predictive model for actor profiling.

ID | Type | Indicator | Confidence
-- | ---- | --------- | ----------
1 | File | `/admin/?/layout/add` | High
2 | File | `/admin/assets/plugins/DataTables/media/unit_testing/templates/deferred_table.php` | High
3 | File | `/admin/dialog/select_images_post.php` | High
4 | File | `/admin/edit-vehicle.php` | High
5 | File | `/admin/overtime_add.php` | High
6 | File | `/admin/pass-bwdates-reports-details.php` | High
7 | File | `/admin/property-details.php` | High
8 | File | `/Admin/Proses_Edit_Akun.php` | High
9 | File | `/admin/search-medicalcard.php` | High
10 | File | `/admin/tag/save` | High
11 | File | `/ajax.php` | Medium
12 | File | `/api/controllers/merchant/shop/PosterController.php` | High
13 | File | `/boafrm/formMapReboot` | High
14 | File | `/cgi-bin/cstecgi.cgi` | High
15 | File | `/cgi-bin/hd_config.cgi` | High
16 | File | `/cgi-bin/mainfunction.cgi` | High
17 | File | `/cgi-bin/photocenter_mgr.cgi` | High
18 | File | `/cgi-bin/tosei_kikai.php` | High
19 | File | `/cgi-bin/webfile_mgr.cgi` | High
20 | File | `/classes/Master.php` | High
21 | File | `/classes/Master.php?f=delete_category` | High
22 | File | `/control/forgot_pass.php` | High
23 | File | `/course/filterRecords/` | High
24 | File | `/dataSet/resolveSql` | High
25 | File | `/details.php` | Medium
26 | File | `/download/image` | High
27 | File | `/DXR.axd` | Medium
28 | File | `/endpoint/delete.php` | High
29 | File | `/etc/shadow` | Medium
30 | File | `/file/accept.php` | High
31 | File | `/forum/away.php` | High
32 | File | `/fos/admin/ajax.php?action=save_settings` | High
33 | ... | ... | ...

There are 280 more IOA items available (file, library, argument, input value, pattern, network port). Please use our online service to access the data.

## References

The following list contains _external sources_ which discuss the actor and the associated activities:

* https://bazaar.abuse.ch/sample/013fefe1917cdeedc66a5e4bee5417894491591296a91a507224ae5af9618cda/
* https://threatfox.abuse.ch
* https://tria.ge/231218-shv6tscgh3

## Literature

The following _articles_ explain our unique predictive cyber threat intelligence:

* [VulDB Cyber Threat Intelligence Documentation](https://vuldb.com/?kb.cti)
* [Cyber Threat Intelligence - Early Anticipation of Attacks](https://www.scip.ch/en/?labs.20201022)

## License

(c) [1997-2025](https://vuldb.com/?kb.changelog) by [vuldb.com](https://vuldb.com/?kb.about). All data on this page is shared under the license [CC BY-NC-SA 4.0](https://creativecommons.org/licenses/by-nc-sa/4.0/). Questions? Check the [FAQ](https://vuldb.com/?kb.faq), read the [documentation](https://vuldb.com/?kb) or [contact us](https://vuldb.com/?contact)!
