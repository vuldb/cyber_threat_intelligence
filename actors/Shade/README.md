# Shade - Cyber Threat Intelligence

These _indicators_ were reported, collected, and generated during the [VulDB CTI analysis](https://vuldb.com/?kb.cti) of the actor known as [Shade](https://vuldb.com/?actor.shade). The _activity monitoring_ correlates data from social media, forums, chat rooms, and darknet markets. It helps to determine associated actors, specific activities, expected intentions, emerging research, and ongoing attacks. Our unique _predictive model_ uses _big data_ to forecast activities and their characteristics.

_Live data_ and more _analysis capabilities_ are available at [https://vuldb.com/?actor.shade](https://vuldb.com/?actor.shade)

## Countries

These _countries_ are directly (e.g. origin of attacks) or indirectly (e.g. access by proxy) associated with Shade:

* [US](https://vuldb.com/?country.us)
* [RU](https://vuldb.com/?country.ru)
* [GB](https://vuldb.com/?country.gb)
* ...

There are 19 more country items available. Please use our online service to access the data.

## IOC - Indicator of Compromise

These _indicators of compromise_ (IOC) indicate associated network resources which are known to be part of research and attack activities of Shade.

ID | IP address | Hostname | Campaign | Confidence
-- | ---------- | -------- | -------- | ----------
1 | [5.9.116.66](https://vuldb.com/?ip.5.9.116.66) | static.66.116.9.5.clients.your-server.de | - | High
2 | [5.9.158.75](https://vuldb.com/?ip.5.9.158.75) | static.75.158.9.5.clients.your-server.de | - | High
3 | [13.107.21.200](https://vuldb.com/?ip.13.107.21.200) | - | - | High
4 | [23.6.22.189](https://vuldb.com/?ip.23.6.22.189) | a23-6-22-189.deploy.static.akamaitechnologies.com | - | High
5 | [37.157.254.113](https://vuldb.com/?ip.37.157.254.113) | rs004106.root.server-hosting.expert | - | High
6 | [46.105.57.169](https://vuldb.com/?ip.46.105.57.169) | cluster020.hosting.ovh.net | - | High
7 | [46.166.182.20](https://vuldb.com/?ip.46.166.182.20) | - | - | High
8 | [47.101.49.13](https://vuldb.com/?ip.47.101.49.13) | - | - | High
9 | [51.68.204.139](https://vuldb.com/?ip.51.68.204.139) | ns3127231.ip-51-68-204.eu | - | High
10 | [51.68.206.28](https://vuldb.com/?ip.51.68.206.28) | ns3128207.ip-51-68-206.eu | - | High
11 | [62.151.180.62](https://vuldb.com/?ip.62.151.180.62) | mx18062.brandengager.info | - | High
12 | ... | ... | ... | ...

There are 46 more IOC items available. Please use our online service to access the data.

## TTP - Tactics, Techniques, Procedures

_Tactics, techniques, and procedures_ (TTP) summarize the suspected MITRE ATT&CK techniques used by _Shade_. This data is unique as it uses our predictive model for actor profiling.

ID | Technique | Weakness | Description | Confidence
-- | --------- | -------- | ----------- | ----------
1 | T1006 | CWE-21, CWE-22, CWE-23 | Pathname Traversal | High
2 | T1040 | CWE-319 | Authentication Bypass by Capture-replay | High
3 | T1055 | CWE-74 | Injection | High
4 | T1059 | CWE-94, CWE-1321 | Cross Site Scripting | High
5 | T1059.007 | CWE-79, CWE-80 | Cross Site Scripting | High
6 | ... | ... | ... | ...

There are 22 more TTP items available. Please use our online service to access the data.

## IOA - Indicator of Attack

These _indicators of attack_ (IOA) list the potential fragments used for technical activities like reconnaissance, exploitation, privilege escalation, and exfiltration by Shade. This data is unique as it uses our predictive model for actor profiling.

ID | Type | Indicator | Confidence
-- | ---- | --------- | ----------
1 | File | `/admin/api/theme-edit/` | High
2 | File | `/admin/attendance_row.php` | High
3 | File | `/admin/categories/manage_category.php` | High
4 | File | `/admin/categories/view_category.php` | High
5 | File | `/admin/del.php` | High
6 | File | `/admin/edit-services.php` | High
7 | File | `/admin/edit_subject.php` | High
8 | File | `/admin/employee_row.php` | High
9 | File | `/admin/folderrollpicture/list` | High
10 | File | `/admin/inquiries/view_details.php` | High
11 | File | `/Admin/login.php` | High
12 | File | `/admin/maintenance/brand.php` | High
13 | File | `/admin/maintenance/view_designation.php` | High
14 | File | `/admin/mechanics/manage_mechanic.php` | High
15 | File | `/admin/reportupload.aspx` | High
16 | File | `/admin/service.php` | High
17 | File | `/admin/transactions/track_shipment.php` | High
18 | File | `/admin/usermanagement.php` | High
19 | File | `/api/baskets/{name}` | High
20 | File | `/backup.pl` | Medium
21 | File | `/bibliography/marcsru.php` | High
22 | File | `/bin/httpd` | Medium
23 | File | `/blog/edit` | Medium
24 | File | `/card_scan.php` | High
25 | File | `/change-language/de_DE` | High
26 | File | `/classes/Master.php?f=save_item` | High
27 | File | `/dipam/save-delegates.php` | High
28 | File | `/editor/index.php` | High
29 | File | `/feegroups/tgrt_group.jsf` | High
30 | File | `/forum/away.php` | High
31 | File | `/forum/PostPrivateMessage` | High
32 | File | `/friends` | Medium
33 | File | `/goform/SetLEDCfg` | High
34 | File | `/goform/SystemCommand` | High
35 | File | `/goform/WifiBasicSet` | High
36 | File | `/hospital/hms/admin/patient-search.php` | High
37 | File | `/hrm/index.php?msg` | High
38 | File | `/hrm/state.php` | High
39 | File | `/index.php` | Medium
40 | File | `/index/user/user_edit.html` | High
41 | File | `/jerry-core/ecma/operations/ecma-get-put-value.c` | High
42 | File | `/lib` | Low
43 | File | `/librarian/lab.php` | High
44 | File | `/magick/quantize.c` | High
45 | File | `/mgmt/tm/util/bash` | High
46 | File | `/modules/caddyhttp/rewrite/rewrite.go` | High
47 | File | `/modules/projects/vw_files.php` | High
48 | File | `/net-banking/send_funds.php` | High
49 | File | `/odlms/?page=appointments/view_appointment` | High
50 | File | `/out.php` | Medium
51 | File | `/param.file.tgz` | High
52 | File | `/picturesPreview` | High
53 | File | `/preview.php` | Medium
54 | File | `/purchase_order/admin/?page=system_info` | High
55 | File | `/release-x64/otfccdump` | High
56 | File | `/royal_event/userregister.php` | High
57 | File | `/SASWebReportStudio/logonAndRender.do` | High
58 | ... | ... | ...

There are 504 more IOA items available (file, library, argument, input value, pattern, network port). Please use our online service to access the data.

## References

The following list contains _external sources_ which discuss the actor and the associated activities:

* https://blog.talosintelligence.com/2019/09/threat-roundup-0906-0913.html
* https://blog.talosintelligence.com/2019/09/threat-roundup-0920-0927.html
* https://blog.talosintelligence.com/2019/11/threat-roundup-1025-1101.html

## Literature

The following _articles_ explain our unique predictive cyber threat intelligence:

* [VulDB Cyber Threat Intelligence Documentation](https://vuldb.com/?kb.cti)
* [Cyber Threat Intelligence - Early Anticipation of Attacks](https://www.scip.ch/en/?labs.20201022)

## License

(c) [1997-2023](https://vuldb.com/?kb.changelog) by [vuldb.com](https://vuldb.com/?kb.about). All data on this page is shared under the license [CC BY-NC-SA 4.0](https://creativecommons.org/licenses/by-nc-sa/4.0/). Questions? Check the [FAQ](https://vuldb.com/?kb.faq), read the [documentation](https://vuldb.com/?kb) or [contact us](https://vuldb.com/?contact)!
