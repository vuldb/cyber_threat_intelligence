# Dealply - Cyber Threat Intelligence

These _indicators_ were reported, collected, and generated during the [VulDB CTI analysis](https://vuldb.com/?kb.cti) of the actor known as [Dealply](https://vuldb.com/?actor.dealply). The _activity monitoring_ correlates data from social media, forums, chat rooms, and darknet markets. It helps to determine associated actors, specific activities, expected intentions, emerging research, and ongoing attacks. Our unique _predictive model_ uses _big data_ to forecast activities and their characteristics.

_Live data_ and more _analysis capabilities_ are available at [https://vuldb.com/?actor.dealply](https://vuldb.com/?actor.dealply)

## Countries

These _countries_ are directly (e.g. origin of attacks) or indirectly (e.g. access by proxy) associated with Dealply:

* [IT](https://vuldb.com/?country.it)
* [US](https://vuldb.com/?country.us)
* [CN](https://vuldb.com/?country.cn)

## IOC - Indicator of Compromise

These _indicators of compromise_ (IOC) indicate associated network resources which are known to be part of research and attack activities of Dealply.

ID | IP address | Hostname | Campaign | Confidence
-- | ---------- | -------- | -------- | ----------
1 | [5.9.9.18](https://vuldb.com/?ip.5.9.9.18) | static.18.9.9.5.clients.your-server.de | - | High
2 | [13.248.196.204](https://vuldb.com/?ip.13.248.196.204) | a64c2b794233c60a6.awsglobalaccelerator.com | - | High
3 | [23.0.52.194](https://vuldb.com/?ip.23.0.52.194) | a23-0-52-194.deploy.static.akamaitechnologies.com | - | High
4 | [23.3.126.219](https://vuldb.com/?ip.23.3.126.219) | a23-3-126-219.deploy.static.akamaitechnologies.com | - | High
5 | [23.54.219.51](https://vuldb.com/?ip.23.54.219.51) | a23-54-219-51.deploy.static.akamaitechnologies.com | - | High
6 | [23.221.50.122](https://vuldb.com/?ip.23.221.50.122) | a23-221-50-122.deploy.static.akamaitechnologies.com | - | High
7 | [34.231.131.84](https://vuldb.com/?ip.34.231.131.84) | ec2-34-231-131-84.compute-1.amazonaws.com | - | Medium
8 | ... | ... | ... | ...

There are 29 more IOC items available. Please use our online service to access the data.

## TTP - Tactics, Techniques, Procedures

_Tactics, techniques, and procedures_ (TTP) summarize the suspected MITRE ATT&CK techniques used by _Dealply_. This data is unique as it uses our predictive model for actor profiling.

ID | Technique | Weakness | Description | Confidence
-- | --------- | -------- | ----------- | ----------
1 | T1006 | CWE-22, CWE-24, CWE-25, CWE-29, CWE-425 | Pathname Traversal | High
2 | T1040 | CWE-294, CWE-319 | Authentication Bypass by Capture-replay | High
3 | T1055 | CWE-74 | Injection | High
4 | T1059 | CWE-88, CWE-94, CWE-1321 | Cross Site Scripting | High
5 | T1059.007 | CWE-79, CWE-80 | Cross Site Scripting | High
6 | ... | ... | ... | ...

There are 19 more TTP items available. Please use our online service to access the data.

## IOA - Indicator of Attack

These _indicators of attack_ (IOA) list the potential fragments used for technical activities like reconnaissance, exploitation, privilege escalation, and exfiltration by Dealply. This data is unique as it uses our predictive model for actor profiling.

ID | Type | Indicator | Confidence
-- | ---- | --------- | ----------
1 | File | `/?r=email/api/mark&op=delFromSend` | High
2 | File | `/?r=report/api/getlist` | High
3 | File | `/accessory/picdel.html` | High
4 | File | `/admin` | Low
5 | File | `/admin.php/appcenter/local.html?type=addon` | High
6 | File | `/admin/?page=product/manage_product&id=2` | High
7 | File | `/admin/assign/assign.php` | High
8 | File | `/admin/casedetails.php` | High
9 | File | `/admin/fields/manage_field.php` | High
10 | File | `/admin/getallarticleinfo` | High
11 | File | `/admin/info_deal.php` | High
12 | File | `/admin/products/index.php` | High
13 | File | `/admin/reports/index.php` | High
14 | File | `/admin/robot/approval/list` | High
15 | File | `/admin/transactions/track_shipment.php` | High
16 | File | `/admin_system/api.php` | High
17 | File | `/alphaware/details.php` | High
18 | File | `/analysisProject/pagingQueryData` | High
19 | File | `/api/admin/store/product/list` | High
20 | File | `/api/admin/store/product/save` | High
21 | File | `/api/gen/clients/{language}` | High
22 | File | `/api/upload` | Medium
23 | File | `/articles/{id}` | High
24 | File | `/batm/app/admin/standalone/deployments` | High
25 | File | `/bilal final/edit_stud.php` | High
26 | File | `/bilal final/login.php` | High
27 | File | `/bsenordering/index.php` | High
28 | File | `/churchcrm/EventAttendance.php` | High
29 | File | `/classes/Master.php?f=save_position` | High
30 | File | `/common/sysFile/list` | High
31 | File | `/config/general/` | High
32 | File | `/database/sqldel.html` | High
33 | File | `/dev/infiniband/rdma_cm` | High
34 | File | `/ecommerce/admin/category/controller.php` | High
35 | File | `/ecommerce/admin/settings/setDiscount.php` | High
36 | File | `/ecommerce/admin/user/controller.php?action=edit` | High
37 | File | `/feeds/post/publish` | High
38 | File | `/files/list-file` | High
39 | File | `/geoserver/rest/about/status` | High
40 | File | `/goform/set_LimitClient_cfg` | High
41 | File | `/group1/uploa` | High
42 | File | `/NotrinosERP/sales/customer_delivery.php` | High
43 | File | `/officer/assigncase.php` | High
44 | File | `/plugins/focalboard/api/v2/users` | High
45 | File | `/PROD_ar/twbkwbis.P_FirstMenu` | High
46 | File | `/project/tasks/list` | High
47 | File | `/setting/setWanIeCfg` | High
48 | ... | ... | ...

There are 416 more IOA items available (file, library, argument, input value, pattern, network port). Please use our online service to access the data.

## References

The following list contains _external sources_ which discuss the actor and the associated activities:

* https://blog.talosintelligence.com/2020/01/threat-roundup-0124-0131.html
* https://blog.talosintelligence.com/2020/05/threat-roundup-0522-0529.html
* https://blog.talosintelligence.com/2020/08/threat-roundup-0821-0827.html

## Literature

The following _articles_ explain our unique predictive cyber threat intelligence:

* [VulDB Cyber Threat Intelligence Documentation](https://vuldb.com/?kb.cti)
* [Cyber Threat Intelligence - Early Anticipation of Attacks](https://www.scip.ch/en/?labs.20201022)

## License

(c) [1997-2023](https://vuldb.com/?kb.changelog) by [vuldb.com](https://vuldb.com/?kb.about). All data on this page is shared under the license [CC BY-NC-SA 4.0](https://creativecommons.org/licenses/by-nc-sa/4.0/). Questions? Check the [FAQ](https://vuldb.com/?kb.faq), read the [documentation](https://vuldb.com/?kb) or [contact us](https://vuldb.com/?contact)!
