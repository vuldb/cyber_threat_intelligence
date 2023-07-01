# Mustang Panda - Cyber Threat Intelligence

These _indicators_ were reported, collected, and generated during the [VulDB CTI analysis](https://vuldb.com/?kb.cti) of the actor known as [Mustang Panda](https://vuldb.com/?actor.mustang_panda). The _activity monitoring_ correlates data from social media, forums, chat rooms, and darknet markets. It helps to determine associated actors, specific activities, expected intentions, emerging research, and ongoing attacks. Our unique _predictive model_ uses _big data_ to forecast activities and their characteristics.

_Live data_ and more _analysis capabilities_ are available at [https://vuldb.com/?actor.mustang_panda](https://vuldb.com/?actor.mustang_panda)

## Campaigns

The following _campaigns_ are known and can be associated with Mustang Panda:

* Diànxùn
* Europe
* Europe and Asia Pacific
* ...

There are 2 more campaign items available. Please use our online service to access the data.

## Countries

These _countries_ are directly (e.g. origin of attacks) or indirectly (e.g. access by proxy) associated with Mustang Panda:

* [US](https://vuldb.com/?country.us)
* [DE](https://vuldb.com/?country.de)
* [CN](https://vuldb.com/?country.cn)
* ...

There are 9 more country items available. Please use our online service to access the data.

## IOC - Indicator of Compromise

These _indicators of compromise_ (IOC) indicate associated network resources which are known to be part of research and attack activities of Mustang Panda.

ID | IP address | Hostname | Campaign | Confidence
-- | ---------- | -------- | -------- | ----------
1 | [3.228.54.173](https://vuldb.com/?ip.3.228.54.173) | ec2-3-228-54-173.compute-1.amazonaws.com | - | Medium
2 | [5.34.178.156](https://vuldb.com/?ip.5.34.178.156) | paulojohnjerick.pserver.ru | Europe and Asia Pacific | High
3 | [5.206.224.167](https://vuldb.com/?ip.5.206.224.167) | hardsysi | Europe | High
4 | [18.138.107.235](https://vuldb.com/?ip.18.138.107.235) | ec2-18-138-107-235.ap-southeast-1.compute.amazonaws.com | Europe | Medium
5 | [42.99.117.95](https://vuldb.com/?ip.42.99.117.95) | - | - | High
6 | [43.254.217.67](https://vuldb.com/?ip.43.254.217.67) | - | - | High
7 | [43.254.218.42](https://vuldb.com/?ip.43.254.218.42) | - | Hodur | High
8 | [43.254.218.128](https://vuldb.com/?ip.43.254.218.128) | - | Europe and Asia Pacific | High
9 | [45.32.50.150](https://vuldb.com/?ip.45.32.50.150) | 45.32.50.150.vultr.com | - | Medium
10 | [45.32.101.7](https://vuldb.com/?ip.45.32.101.7) | 45.32.101.7.vultrusercontent.com | Europe and Asia Pacific | High
11 | [45.43.50.197](https://vuldb.com/?ip.45.43.50.197) | - | Europe | High
12 | [45.77.184.12](https://vuldb.com/?ip.45.77.184.12) | comm.phiu.pw | - | High
13 | [45.131.179.179](https://vuldb.com/?ip.45.131.179.179) | - | Hodur | High
14 | [45.134.83.4](https://vuldb.com/?ip.45.134.83.4) | - | - | High
15 | [45.134.83.41](https://vuldb.com/?ip.45.134.83.41) | - | PlugX | High
16 | [45.147.26.45](https://vuldb.com/?ip.45.147.26.45) | - | Europe and Asia Pacific | High
17 | [45.154.14.235](https://vuldb.com/?ip.45.154.14.235) | - | Hodur | High
18 | ... | ... | ... | ...

There are 69 more IOC items available. Please use our online service to access the data.

## TTP - Tactics, Techniques, Procedures

_Tactics, techniques, and procedures_ (TTP) summarize the suspected MITRE ATT&CK techniques used by _Mustang Panda_. This data is unique as it uses our predictive model for actor profiling.

ID | Technique | Weakness | Description | Confidence
-- | --------- | -------- | ----------- | ----------
1 | T1006 | CWE-21, CWE-22, CWE-23, CWE-24, CWE-36 | Pathname Traversal | High
2 | T1040 | CWE-294, CWE-319 | Authentication Bypass by Capture-replay | High
3 | T1055 | CWE-74 | Injection | High
4 | T1059 | CWE-88, CWE-94 | Cross Site Scripting | High
5 | T1059.007 | CWE-79, CWE-80 | Cross Site Scripting | High
6 | T1068 | CWE-264, CWE-266, CWE-269, CWE-284 | J2EE Misconfiguration: Weak Access Permissions for EJB Methods | High
7 | ... | ... | ... | ...

There are 22 more TTP items available. Please use our online service to access the data.

## IOA - Indicator of Attack

These _indicators of attack_ (IOA) list the potential fragments used for technical activities like reconnaissance, exploitation, privilege escalation, and exfiltration by Mustang Panda. This data is unique as it uses our predictive model for actor profiling.

ID | Type | Indicator | Confidence
-- | ---- | --------- | ----------
1 | File | `.github/workflows/combine-prs.yml` | High
2 | File | `/?r=report/api/getlist` | High
3 | File | `/admin.php/appcenter/local.html?type=addon` | High
4 | File | `/admin.php?c=upload&f=zip&_noCache=0.1683794968` | High
5 | File | `/admin/?page=orders/manage_request` | High
6 | File | `/admin/?page=product/manage_product&id=2` | High
7 | File | `/admin/?page=reminders/view_reminder` | High
8 | File | `/admin/?page=system_info` | High
9 | File | `/admin/assign/assign.php` | High
10 | File | `/admin/budget/manage_budget.php` | High
11 | File | `/admin/candidates_row.php` | High
12 | File | `/admin/categories/manage_category.php` | High
13 | File | `/admin/categories/view_category.php` | High
14 | File | `/admin/contacts/organizations/edit/2` | High
15 | File | `/admin/content/index` | High
16 | File | `/admin/employee_add.php` | High
17 | File | `/admin/employee_edit.php` | High
18 | File | `/admin/forgot-password.php` | High
19 | File | `/admin/index3.php` | High
20 | File | `/admin/inventory/manage_stock.php` | High
21 | File | `/admin/manage_academic.php` | High
22 | File | `/admin/mechanics/manage_mechanic.php` | High
23 | File | `/admin/modal_add_product.php` | High
24 | File | `/admin/offenses/view_details.php` | High
25 | File | `/admin/positions_row.php` | High
26 | File | `/admin/product/manage.php` | High
27 | File | `/admin/read.php?mudi=announContent` | High
28 | File | `/admin/report/index.php` | High
29 | File | `/admin/reports/index.php` | High
30 | File | `/admin/robot/approval/list` | High
31 | File | `/admin/service_requests/manage_inventory.php` | High
32 | File | `/admin/settings.php` | High
33 | File | `/admin/students/view_details.php` | High
34 | File | `/admin/uploads.php` | High
35 | File | `/admin/user/manage_user.php` | High
36 | File | `/admin/userprofile.php` | High
37 | File | `/adms/admin/?page=user/manage_user` | High
38 | File | `/adms/classes/Users.php` | High
39 | File | `/ajax.php?action=read_msg` | High
40 | File | `/api/admin/system/store/order/list` | High
41 | File | `/api/geojson` | Medium
42 | File | `/api/upload` | Medium
43 | File | `/api/user/password/sent-reset-email` | High
44 | File | `/api/v1/attack` | High
45 | File | `/author/list?limit=10&offset=0&order=desc` | High
46 | File | `/bilal final/login.php` | High
47 | File | `/boat/login.php` | High
48 | File | `/cgi-bin/portal` | High
49 | File | `/classes/Login.php` | High
50 | File | `/classes/Master.php` | High
51 | File | `/classes/Master.php?f=delete_img` | High
52 | File | `/classes/Master.php?f=save_category` | High
53 | File | `/classes/Master.php?f=save_sub_category` | High
54 | File | `/classes/Master.php?f=update_order_status` | High
55 | File | `/classes/Users.php` | High
56 | File | `/Config/service/initModel?` | High
57 | File | `/data/config.ftp.php` | High
58 | File | `/ecommerce/admin/category/controller.php` | High
59 | File | `/edoc/doctor/patient.php` | High
60 | File | `/etc/shadow` | Medium
61 | File | `/export` | Low
62 | File | `/file/upload/1` | High
63 | File | `/files/list-file` | High
64 | File | `/file_manager/login.php` | High
65 | File | `/forum/PostPrivateMessage` | High
66 | File | `/fos/admin/ajax.php?action=save_settings` | High
67 | File | `/goform/NTPSyncWithHost` | High
68 | File | `/goform/SetVirtualServerCfg` | High
69 | File | `/group1/uploa` | High
70 | File | `/HNAP1/SetAccessPointMode` | High
71 | File | `/home/<user>/SecurityOnion/setup/so-setup` | High
72 | File | `/home/www/cgi-bin/diagnostics.cgi` | High
73 | ... | ... | ...

There are 646 more IOA items available (file, library, argument, input value, pattern, network port). Please use our online service to access the data.

## References

The following list contains _external sources_ which discuss the actor and the associated activities:

* https://blog.talosintelligence.com/2022/05/mustang-panda-targets-europe.html
* https://blogs.blackberry.com/en/2022/10/mustang-panda-abuses-legitimate-apps-to-target-myanmar-based-victims
* https://blogs.blackberry.com/en/2022/12/mustang-panda-uses-the-russian-ukrainian-war-to-attack-europe-and-asia-pacific-targets
* https://github.com/eset/malware-ioc/tree/master/quarterly_reports/2020_Q2
* https://twitter.com/ESETresearch/status/1400165861973966854
* https://twitter.com/xorhex/status/1406496693735067650
* https://twitter.com/xorhex/status/1422815329684758537
* https://www.anomali.com/blog/china-based-apt-mustang-panda-targets-minority-groups-public-and-private-sector-organizations
* https://www.anomali.com/blog/china-based-apt-mustang-panda-targets-minority-groups-public-and-private-sector-organizations#When:17:14:00Z
* https://www.mcafee.com/enterprise/en-us/assets/reports/rp-operation-dianxun.pdf
* https://www.secureworks.com/blog/bronze-president-targets-russian-speakers-with-updated-plugx
* https://www.welivesecurity.com/2022/03/23/mustang-panda-hodur-old-tricks-new-korplug-variant/
* https://www.welivesecurity.com/2023/03/02/mqsttang-mustang-panda-latest-backdoor-treads-new-ground-qt-mqtt/

## Literature

The following _articles_ explain our unique predictive cyber threat intelligence:

* [VulDB Cyber Threat Intelligence Documentation](https://vuldb.com/?kb.cti)
* [Cyber Threat Intelligence - Early Anticipation of Attacks](https://www.scip.ch/en/?labs.20201022)

## License

(c) [1997-2023](https://vuldb.com/?kb.changelog) by [vuldb.com](https://vuldb.com/?kb.about). All data on this page is shared under the license [CC BY-NC-SA 4.0](https://creativecommons.org/licenses/by-nc-sa/4.0/). Questions? Check the [FAQ](https://vuldb.com/?kb.faq), read the [documentation](https://vuldb.com/?kb) or [contact us](https://vuldb.com/?contact)!
