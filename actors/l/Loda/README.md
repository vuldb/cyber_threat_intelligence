# Loda - Cyber Threat Intelligence

These _indicators_ were reported, collected, and generated during the [VulDB CTI analysis](https://vuldb.com/?kb.cti) of the actor known as [Loda](https://vuldb.com/?actor.loda). The _activity monitoring_ correlates data from social media, forums, chat rooms, and darknet markets. It helps to determine associated actors, specific activities, expected intentions, emerging research, and ongoing attacks. Our unique _predictive model_ uses _big data_ to forecast activities and their characteristics.

_Live data_ and more _analysis capabilities_ are available at [https://vuldb.com/?actor.loda](https://vuldb.com/?actor.loda)

## Countries

These _countries_ are directly (e.g. origin of attacks) or indirectly (e.g. access by proxy) associated with Loda:

* [VN](https://vuldb.com/?country.vn)
* [SH](https://vuldb.com/?country.sh)
* [US](https://vuldb.com/?country.us)
* ...

There are 9 more country items available. Please use our online service to access the data.

## IOC - Indicator of Compromise

These _indicators of compromise_ (IOC) indicate associated network resources which are known to be part of research and attack activities of Loda.

ID | IP address | Hostname | Campaign | Confidence
-- | ---------- | -------- | -------- | ----------
1 | [2.58.56.188](https://vuldb.com/?ip.2.58.56.188) | powered.by.rdp.sh | - | High
2 | [3.141.204.47](https://vuldb.com/?ip.3.141.204.47) | ec2-3-141-204-47.us-east-2.compute.amazonaws.com | - | Medium
3 | [13.40.105.36](https://vuldb.com/?ip.13.40.105.36) | ec2-13-40-105-36.eu-west-2.compute.amazonaws.com | - | Medium
4 | [34.174.95.150](https://vuldb.com/?ip.34.174.95.150) | 150.95.174.34.bc.googleusercontent.com | - | Medium
5 | [37.0.14.214](https://vuldb.com/?ip.37.0.14.214) | - | - | High
6 | [45.155.249.183](https://vuldb.com/?ip.45.155.249.183) | - | - | High
7 | [46.105.113.84](https://vuldb.com/?ip.46.105.113.84) | ns320209.ip-46-105-113.eu | - | High
8 | ... | ... | ... | ...

There are 27 more IOC items available. Please use our online service to access the data.

## TTP - Tactics, Techniques, Procedures

_Tactics, techniques, and procedures_ (TTP) summarize the suspected MITRE ATT&CK techniques used by _Loda_. This data is unique as it uses our predictive model for actor profiling.

ID | Technique | Weakness | Description | Confidence
-- | --------- | -------- | ----------- | ----------
1 | T1006 | CWE-21, CWE-22, CWE-23, CWE-24, CWE-25, CWE-36, CWE-425 | Path Traversal | High
2 | T1040 | CWE-294, CWE-319 | Authentication Bypass by Capture-replay | High
3 | T1055 | CWE-74 | Improper Neutralization of Data within XPath Expressions | High
4 | T1059 | CWE-94, CWE-1321 | Argument Injection | High
5 | T1059.007 | CWE-79, CWE-80 | Cross Site Scripting | High
6 | T1068 | CWE-264, CWE-269, CWE-284 | Execution with Unnecessary Privileges | High
7 | ... | ... | ... | ...

There are 26 more TTP items available. Please use our online service to access the data.

## IOA - Indicator of Attack

These _indicators of attack_ (IOA) list the potential fragments used for technical activities like reconnaissance, exploitation, privilege escalation, and exfiltration by Loda. This data is unique as it uses our predictive model for actor profiling.

ID | Type | Indicator | Confidence
-- | ---- | --------- | ----------
1 | File | `/?g=net_pro_keyword_import_save` | High
2 | File | `/admin/admin.php` | High
3 | File | `/admin/applicants/index.php` | High
4 | File | `/admin/blood/update/B+.php` | High
5 | File | `/admin/booking-bwdates-reports-details.php` | High
6 | File | `/admin/category/index.php` | High
7 | File | `/admin/CloudAccounts` | High
8 | File | `/admin/cmsTemplate/savePlace` | High
9 | File | `/admin/cmsWebFile/doUpload` | High
10 | File | `/admin/config_ISCGroupNoCache.php` | High
11 | File | `/admin/config_time_sync.php` | High
12 | File | `/admin/edit_area.php` | High
13 | File | `/admin/index.php` | High
14 | File | `/admin/infoSys_deal.php?mudi=deal` | High
15 | File | `/admin/item/view_item.php` | High
16 | File | `/admin/list_resource_icon.php?action=delete` | High
17 | File | `/admin/login.php` | High
18 | File | `/admin/orders/view_order.php` | High
19 | File | `/admin/pages/list` | High
20 | File | `/admin/search.php` | High
21 | File | `/admin/service_requests/manage_inventory.php` | High
22 | File | `/admin/student.php` | High
23 | File | `/admin/twitter.php` | High
24 | File | `/adminPage/conf/saveCmd` | High
25 | File | `/adminPage/main/upload` | High
26 | File | `/alogin.html` | Medium
27 | File | `/api/Cdn/GetFile` | High
28 | File | `/api/user` | Medium
29 | File | `/api/v1/dashboards/export` | High
30 | File | `/api/v2/maps` | Medium
31 | File | `/api/{org_id}/users/{email_id}` | High
32 | File | `/app/zentao/module/repo/model.php` | High
33 | File | `/application/index/controller/Pay.php` | High
34 | File | `/category/list?limit=10&offset=0&order=desc` | High
35 | File | `/cgi-bin/cstecgi.cgi` | High
36 | File | `/cgi-bin/hd_config.cgi` | High
37 | File | `/cgi-bin/koha/opac-MARCdetail.pl` | High
38 | File | `/cgi-bin/nas_sharing.cgi` | High
39 | File | `/cgi-bin/s3.cgi` | High
40 | File | `/charts/api/charts/v1/` | High
41 | File | `/classes/Master.php` | High
42 | File | `/classes/Master.php?f=delete_category` | High
43 | File | `/classes/Master.php?f=log_employee` | High
44 | File | `/classes/SystemSettings.php?f=update_settings` | High
45 | File | `/classes/Users.php?f=save` | High
46 | File | `/classes/Users.php?f=save_client` | High
47 | File | `/cm/update_rows/page?id=2` | High
48 | File | `/configs/application.ini` | High
49 | File | `/control/forgot_pass.php` | High
50 | File | `/control/register_case.php` | High
51 | File | `/dcim/console-ports/add` | High
52 | File | `/dede/freelist_edit.php` | High
53 | File | `/deleteTicket.php` | High
54 | File | `/detalheIdUra` | High
55 | ... | ... | ...

There are 482 more IOA items available (file, library, argument, input value, pattern, network port). Please use our online service to access the data.

## References

The following list contains _external sources_ which discuss the actor and the associated activities:

* https://app.any.run/tasks/0370524d-75ee-4ea2-ad99-01e40a8d6b4a
* https://github.com/Cisco-Talos/IOCs/blob/main/2022/11/get-a-loda-this.txt
* https://threatfox.abuse.ch
* https://www.virustotal.com/gui/file/052fba70767b01cb674b9311a220181a87bdf47161280bb6335c6024e163139c/detection

## Literature

The following _articles_ explain our unique predictive cyber threat intelligence:

* [VulDB Cyber Threat Intelligence Documentation](https://vuldb.com/?kb.cti)
* [Cyber Threat Intelligence - Early Anticipation of Attacks](https://www.scip.ch/en/?labs.20201022)

## License

(c) [1997-2024](https://vuldb.com/?kb.changelog) by [vuldb.com](https://vuldb.com/?kb.about). All data on this page is shared under the license [CC BY-NC-SA 4.0](https://creativecommons.org/licenses/by-nc-sa/4.0/). Questions? Check the [FAQ](https://vuldb.com/?kb.faq), read the [documentation](https://vuldb.com/?kb) or [contact us](https://vuldb.com/?contact)!
