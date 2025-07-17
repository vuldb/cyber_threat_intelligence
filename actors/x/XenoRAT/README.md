# XenoRAT - Cyber Threat Intelligence

These _indicators_ were reported, collected, and generated during the [VulDB CTI analysis](https://vuldb.com/?kb.cti) of the actor known as [XenoRAT](https://vuldb.com/?actor.xenorat). The _activity monitoring_ correlates data from social media, forums, chat rooms, and darknet markets. It helps to determine associated actors, specific activities, expected intentions, emerging research, and ongoing attacks. Our unique _predictive model_ uses _big data_ to forecast activities and their characteristics.

_Live data_ and more _analysis capabilities_ are available at [https://vuldb.com/?actor.xenorat](https://vuldb.com/?actor.xenorat)

## Countries

These _countries_ are directly (e.g. origin of attacks) or indirectly (e.g. access by proxy) associated with XenoRAT:

* [US](https://vuldb.com/?country.us)
* [LA](https://vuldb.com/?country.la)
* [RU](https://vuldb.com/?country.ru)
* ...

There are 6 more country items available. Please use our online service to access the data.

## IOC - Indicator of Compromise

These _indicators of compromise_ (IOC) indicate associated network resources which are known to be part of research and attack activities of XenoRAT.

ID | IP address | Hostname | Campaign | Confidence
-- | ---------- | -------- | -------- | ----------
1 | [2.58.85.196](https://vuldb.com/?ip.2.58.85.196) | sunucuduragi.com | - | High
2 | [5.14.110.90](https://vuldb.com/?ip.5.14.110.90) | 5-14-110-90.residential.rdsnet.ro | - | High
3 | [34.229.235.165](https://vuldb.com/?ip.34.229.235.165) | ec2-34-229-235-165.compute-1.amazonaws.com | - | Medium
4 | [45.66.231.63](https://vuldb.com/?ip.45.66.231.63) | - | - | High
5 | [45.133.174.133](https://vuldb.com/?ip.45.133.174.133) | - | - | High
6 | [49.194.29.240](https://vuldb.com/?ip.49.194.29.240) | n49-194-29-240.per2.wa.optusnet.com.au | - | High
7 | [51.38.196.118](https://vuldb.com/?ip.51.38.196.118) | server25.mentality.cloud | - | High
8 | ... | ... | ... | ...

There are 29 more IOC items available. Please use our online service to access the data.

## TTP - Tactics, Techniques, Procedures

_Tactics, techniques, and procedures_ (TTP) summarize the suspected MITRE ATT&CK techniques used by _XenoRAT_. This data is unique as it uses our predictive model for actor profiling.

ID | Technique | Weakness | Description | Confidence
-- | --------- | -------- | ----------- | ----------
1 | T1006 | CWE-21, CWE-22, CWE-24 | Path Traversal | High
2 | T1055 | CWE-74 | Improper Neutralization of Data within XPath Expressions | High
3 | T1059 | CWE-88, CWE-94, CWE-1321 | Argument Injection | High
4 | T1059.007 | CWE-79, CWE-80 | Basic Cross Site Scripting | High
5 | T1068 | CWE-264, CWE-269, CWE-284 | Execution with Unnecessary Privileges | High
6 | ... | ... | ... | ...

There are 19 more TTP items available. Please use our online service to access the data.

## IOA - Indicator of Attack

These _indicators of attack_ (IOA) list the potential fragments used for technical activities like reconnaissance, exploitation, privilege escalation, and exfiltration by XenoRAT. This data is unique as it uses our predictive model for actor profiling.

ID | Type | Indicator | Confidence
-- | ---- | --------- | ----------
1 | File | `/accounts_con/register_account` | High
2 | File | `/admin/category/controller.php` | High
3 | File | `/admin/create_product.php` | High
4 | File | `/admin/file_manager/export` | High
5 | File | `/admin/general.cgi` | High
6 | File | `/admin/index2.html` | High
7 | File | `/admin/info_deal.php` | High
8 | File | `/admin/reminders/manage_reminder.php` | High
9 | File | `/admin/user/manage_user.php` | High
10 | File | `/adminPage/conf/reload` | High
11 | File | `/admin_topic.php?action=delall` | High
12 | File | `/api/baskets/{name}` | High
13 | File | `/api/cron/settings/setJob/` | High
14 | File | `/API/info` | Medium
15 | File | `/api/stl/actions/search` | High
16 | File | `/api2/html/` | Medium
17 | File | `/app/ajax/sell_return_data.php` | High
18 | File | `/backend/admin/his_admin_add_lab_equipment.php` | High
19 | File | `/backend/admin/his_admin_register_patient.php` | High
20 | File | `/be/rpc.php` | Medium
21 | File | `/bitrix/admin/ldap_server_edit.php` | High
22 | File | `/Bloodgroop_process.php` | High
23 | File | `/CCMAdmin/serverlist.asp` | High
24 | File | `/cgi-bin/cstecgi.cgi` | High
25 | File | `/cgi-bin/jumpto.php?class=user&page=config_save&isphp=1` | High
26 | File | `/cgi-bin/koha/catalogue/search.pl` | High
27 | File | `/cgi/get_param.cgi` | High
28 | File | `/classes/Master.php?f=delete_inquiry` | High
29 | File | `/classes/SystemSettings.php?f=update_settings` | High
30 | File | `/conf/app.conf` | High
31 | File | `/csms/admin/inquiries/view_details.php` | High
32 | File | `/cstecgi.cgi` | Medium
33 | File | `/desktop_app/file.ajax.php?action=uploadfile` | High
34 | File | `/Device/Device/GetDeviceInfoList?deviceCode=&searchField=&deviceState=` | High
35 | File | `/DXR.axd` | Medium
36 | File | `/ecommerce/support_ticket` | High
37 | File | `/forum/away.php` | High
38 | File | `/goform/RGFirewallEL` | High
39 | File | `/goform/wirelessAdvancedHidden` | High
40 | File | `/h/rest` | Low
41 | File | `/home/search` | Medium
42 | File | `/include/chart_generator.php` | High
43 | File | `/index.php?menu=asterisk_cli` | High
44 | File | `/index/ajax/lang` | High
45 | File | `/item/item_con` | High
46 | File | `/jsoa/hntdCustomDesktopActionContent` | High
47 | File | `/lists/index.php` | High
48 | File | `/log/decodmail.php` | High
49 | File | `/login.php?m=admin&c=Field&a=channel_edit` | High
50 | File | `/log_proxy` | Medium
51 | File | `/mailcleaner.php/getStats` | High
52 | ... | ... | ...

There are 448 more IOA items available (file, library, argument, input value, pattern, network port). Please use our online service to access the data.

## References

The following list contains _external sources_ which discuss the actor and the associated activities:

* https://threatfox.abuse.ch
* https://urlhaus.abuse.ch/url/3522571/
* https://x.com/malwrhunterteam/status/1891402914024882374

## Literature

The following _articles_ explain our unique predictive cyber threat intelligence:

* [VulDB Cyber Threat Intelligence Documentation](https://vuldb.com/?kb.cti)
* [Cyber Threat Intelligence - Early Anticipation of Attacks](https://www.scip.ch/en/?labs.20201022)

## License

(c) [1997-2025](https://vuldb.com/?kb.changelog) by [vuldb.com](https://vuldb.com/?kb.about). All data on this page is shared under the license [CC BY-NC-SA 4.0](https://creativecommons.org/licenses/by-nc-sa/4.0/). Questions? Check the [FAQ](https://vuldb.com/?kb.faq), read the [documentation](https://vuldb.com/?kb) or [contact us](https://vuldb.com/?contact)!
