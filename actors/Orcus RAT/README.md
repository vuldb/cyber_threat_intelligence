# Orcus RAT - Cyber Threat Intelligence

These _indicators_ were reported, collected, and generated during the [VulDB CTI analysis](https://vuldb.com/?kb.cti) of the actor known as [Orcus RAT](https://vuldb.com/?actor.orcus_rat). The _activity monitoring_ correlates data from social media, forums, chat rooms, and darknet markets. It helps to determine associated actors, specific activities, expected intentions, emerging research, and ongoing attacks. Our unique _predictive model_ uses _big data_ to forecast activities and their characteristics.

_Live data_ and more _analysis capabilities_ are available at [https://vuldb.com/?actor.orcus_rat](https://vuldb.com/?actor.orcus_rat)

## Countries

These _countries_ are directly (e.g. origin of attacks) or indirectly (e.g. access by proxy) associated with Orcus RAT:

* [SH](https://vuldb.com/?country.sh)
* [US](https://vuldb.com/?country.us)
* [CN](https://vuldb.com/?country.cn)
* ...

There are 13 more country items available. Please use our online service to access the data.

## IOC - Indicator of Compromise

These _indicators of compromise_ (IOC) indicate associated network resources which are known to be part of research and attack activities of Orcus RAT.

ID | IP address | Hostname | Campaign | Confidence
-- | ---------- | -------- | -------- | ----------
1 | [1.54.107.33](https://vuldb.com/?ip.1.54.107.33) | - | - | High
2 | [1.54.107.38](https://vuldb.com/?ip.1.54.107.38) | - | - | High
3 | [2.58.56.242](https://vuldb.com/?ip.2.58.56.242) | 2.58.56.242.powered.by.rdp.sh | - | High
4 | [3.129.187.220](https://vuldb.com/?ip.3.129.187.220) | ec2-3-129-187-220.us-east-2.compute.amazonaws.com | - | Medium
5 | [3.133.207.110](https://vuldb.com/?ip.3.133.207.110) | ec2-3-133-207-110.us-east-2.compute.amazonaws.com | - | Medium
6 | [3.137.146.78](https://vuldb.com/?ip.3.137.146.78) | ec2-3-137-146-78.us-east-2.compute.amazonaws.com | - | Medium
7 | [3.143.239.116](https://vuldb.com/?ip.3.143.239.116) | ec2-3-143-239-116.us-east-2.compute.amazonaws.com | - | Medium
8 | [13.53.37.168](https://vuldb.com/?ip.13.53.37.168) | ec2-13-53-37-168.eu-north-1.compute.amazonaws.com | - | Medium
9 | [16.170.253.123](https://vuldb.com/?ip.16.170.253.123) | ec2-16-170-253-123.eu-north-1.compute.amazonaws.com | - | Medium
10 | [18.117.142.49](https://vuldb.com/?ip.18.117.142.49) | ec2-18-117-142-49.us-east-2.compute.amazonaws.com | - | Medium
11 | [20.89.177.186](https://vuldb.com/?ip.20.89.177.186) | - | - | High
12 | [27.124.4.200](https://vuldb.com/?ip.27.124.4.200) | - | - | High
13 | [31.173.170.243](https://vuldb.com/?ip.31.173.170.243) | - | - | High
14 | [42.114.153.115](https://vuldb.com/?ip.42.114.153.115) | - | - | High
15 | [45.146.253.103](https://vuldb.com/?ip.45.146.253.103) | rs-zap868892-1.zap-srv.com | - | High
16 | [52.59.165.93](https://vuldb.com/?ip.52.59.165.93) | ec2-52-59-165-93.eu-central-1.compute.amazonaws.com | - | Medium
17 | [61.69.245.176](https://vuldb.com/?ip.61.69.245.176) | 61-69-245-176.static.tpgi.com.au | - | High
18 | ... | ... | ... | ...

There are 67 more IOC items available. Please use our online service to access the data.

## TTP - Tactics, Techniques, Procedures

_Tactics, techniques, and procedures_ (TTP) summarize the suspected MITRE ATT&CK techniques used by _Orcus RAT_. This data is unique as it uses our predictive model for actor profiling.

ID | Technique | Weakness | Description | Confidence
-- | --------- | -------- | ----------- | ----------
1 | T1006 | CWE-21, CWE-22, CWE-24, CWE-425 | Pathname Traversal | High
2 | T1040 | CWE-319 | Authentication Bypass by Capture-replay | High
3 | T1055 | CWE-74 | Injection | High
4 | T1059 | CWE-88, CWE-94 | Cross Site Scripting | High
5 | T1059.007 | CWE-79, CWE-80 | Cross Site Scripting | High
6 | T1068 | CWE-264, CWE-269, CWE-274, CWE-284 | J2EE Misconfiguration: Weak Access Permissions for EJB Methods | High
7 | ... | ... | ... | ...

There are 22 more TTP items available. Please use our online service to access the data.

## IOA - Indicator of Attack

These _indicators of attack_ (IOA) list the potential fragments used for technical activities like reconnaissance, exploitation, privilege escalation, and exfiltration by Orcus RAT. This data is unique as it uses our predictive model for actor profiling.

ID | Type | Indicator | Confidence
-- | ---- | --------- | ----------
1 | File | `/+CSCOE+/logon.html` | High
2 | File | `/?p=products` | Medium
3 | File | `/academy/home/courses` | High
4 | File | `/admin/?page=bike` | High
5 | File | `/admin/?page=product/manage_product&id=2` | High
6 | File | `/admin/?page=user/manage_user&id=3` | High
7 | File | `/admin/addproduct.php` | High
8 | File | `/admin/attendance_row.php` | High
9 | File | `/admin/maintenance/brand.php` | High
10 | File | `/admin/mechanics/manage_mechanic.php` | High
11 | File | `/admin/test_status.php` | High
12 | File | `/admin/voters_row.php` | High
13 | File | `/adv_resource` | High
14 | File | `/ad_js.php` | Medium
15 | File | `/ajax.php?action=save_company` | High
16 | File | `/alumni/admin/ajax.php?action=save_settings` | High
17 | File | `/api/database` | High
18 | File | `/api/upload.php` | High
19 | File | `/apply.cgi` | Medium
20 | File | `/App_Resource/UEditor/server/upload.aspx` | High
21 | File | `/APR/signup.php` | High
22 | File | `/aux` | Low
23 | File | `/c/PluginsController.php` | High
24 | File | `/cas/logout` | Medium
25 | File | `/categorypage.php` | High
26 | File | `/cgi-bin/nightled.cgi` | High
27 | File | `/cgi-bin/system_mgr.cgi` | High
28 | File | `/cha.php` | Medium
29 | File | `/chaincity/user/ticket/create` | High
30 | File | `/collection/all` | High
31 | File | `/College/admin/teacher.php` | High
32 | File | `/dayrui/Fcms/View/system_log.html` | High
33 | File | `/dev/cpu/*/msr` | High
34 | File | `/dipam/save-delegates.php` | High
35 | File | `/drivers/block/floppy.c` | High
36 | File | `/ecommerce/admin/category/controller.php` | High
37 | File | `/ecommerce/support_ticket` | High
38 | File | `/etc/shadow` | Medium
39 | File | `/files/` | Low
40 | File | `/fos/admin/ajax.php` | High
41 | File | `/friends/ajax_invite` | High
42 | File | `/goform/aspForm` | High
43 | File | `/goform/fast_setting_wifi_set` | High
44 | File | `/home/filter_listings` | High
45 | File | `/index.php` | Medium
46 | File | `/index.php/client/message/message_read/xxxxxxxx[random-msg-hash]` | High
47 | File | `/items/search` | High
48 | File | `/knowage/restful-services/dossier/importTemplateFile` | High
49 | File | `/login/index.php` | High
50 | File | `/mail.php` | Medium
51 | File | `/messageboard/view.php` | High
52 | File | `/multi-vendor-shopping-script/product-list.php` | High
53 | File | `/ordering/admin/orders/loaddata.php` | High
54 | File | `/ordering/admin/stockin/loaddata.php` | High
55 | File | `/philosophy/admin/login.php` | High
56 | File | `/php-opos/login.php` | High
57 | File | `/php_action/createProduct.php` | High
58 | File | `/priv_mgt.html` | High
59 | File | `/protocol/iscgwtunnel/uploadiscgwrouteconf.php` | High
60 | File | `/resources//../` | High
61 | File | `/scripts/unlock_tasks.php` | High
62 | File | `/see_more_details.php` | High
63 | File | `/services/indexing/preview` | High
64 | ... | ... | ...

There are 558 more IOA items available (file, library, argument, input value, pattern, network port). Please use our online service to access the data.

## References

The following list contains _external sources_ which discuss the actor and the associated activities:

* https://search.censys.io/hosts/1.54.107.38
* https://search.censys.io/hosts/16.170.253.123
* https://search.censys.io/hosts/42.114.153.115
* https://search.censys.io/hosts/85.209.176.26
* https://search.censys.io/hosts/88.119.171.56
* https://search.censys.io/hosts/89.208.105.120
* https://search.censys.io/hosts/104.168.163.193
* https://search.censys.io/hosts/116.103.214.233
* https://search.censys.io/hosts/138.197.66.62
* https://search.censys.io/hosts/150.107.2.102
* https://search.censys.io/hosts/154.244.248.129
* https://search.censys.io/hosts/154.245.132.20
* https://search.censys.io/hosts/154.245.216.63
* https://search.censys.io/hosts/154.245.225.202
* https://search.censys.io/hosts/183.80.186.171
* https://search.censys.io/hosts/188.27.189.65
* https://search.censys.io/hosts/194.87.216.52
* https://search.censys.io/hosts/194.233.31.117
* https://search.censys.io/search?resource=hosts&sort=RELEVANCE&per_page=25&virtual_hosts=EXCLUDE&q=services.software.product%3A+orcus+and+not+labels%3A+tarpit
* https://threatfox.abuse.ch
* https://www.virustotal.com/gui/file/07b742c9303e04be588f20f51d68828cae04a1af02cb6d09a9d935007dbb4906/detection

## Literature

The following _articles_ explain our unique predictive cyber threat intelligence:

* [VulDB Cyber Threat Intelligence Documentation](https://vuldb.com/?kb.cti)
* [Cyber Threat Intelligence - Early Anticipation of Attacks](https://www.scip.ch/en/?labs.20201022)

## License

(c) [1997-2023](https://vuldb.com/?kb.changelog) by [vuldb.com](https://vuldb.com/?kb.about). All data on this page is shared under the license [CC BY-NC-SA 4.0](https://creativecommons.org/licenses/by-nc-sa/4.0/). Questions? Check the [FAQ](https://vuldb.com/?kb.faq), read the [documentation](https://vuldb.com/?kb) or [contact us](https://vuldb.com/?contact)!
