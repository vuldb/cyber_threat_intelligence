# GuLoader - Cyber Threat Intelligence

These _indicators_ were reported, collected, and generated during the [VulDB CTI analysis](https://vuldb.com/?kb.cti) of the campaign known as _GuLoader_. The _activity monitoring_ correlates data from social media, forums, chat rooms, and darknet markets. It helps to determine associated actors, specific activities, expected intentions, emerging research, and ongoing attacks. Our unique _predictive model_ uses _big data_ to forecast activities and their characteristics.

_Live data_ and more _analysis capabilities_ are available at [https://vuldb.com/?actor](https://vuldb.com/?actor)

## Countries

These _countries_ are directly (e.g. origin of attacks) or indirectly (e.g. access by proxy) associated with GuLoader:

* [US](https://vuldb.com/?country.us)
* [LA](https://vuldb.com/?country.la)
* [RU](https://vuldb.com/?country.ru)
* ...

There are 13 more country items available. Please use our online service to access the data.

## Actors

These _actors_ are associated with GuLoader or other actors linked to the campaign.

ID | Actor | Confidence
-- | ----- | ----------
1 | [GuLoader](https://vuldb.com/?actor.guloader) | High
2 | [Unknown](https://vuldb.com/?actor.unknown) | High

## IOC - Indicator of Compromise

These _indicators of compromise_ (IOC) indicate associated network resources which are known to be part of research and attack activities of GuLoader.

ID | IP address | Hostname | Actor | Confidence
-- | ---------- | -------- | ----- | ----------
1 | [5.2.75.164](https://vuldb.com/?ip.5.2.75.164) | - | [GuLoader](https://vuldb.com/?actor.guloader) | High
2 | [5.8.8.100](https://vuldb.com/?ip.5.8.8.100) | - | [GuLoader](https://vuldb.com/?actor.guloader) | High
3 | [5.255.110.224](https://vuldb.com/?ip.5.255.110.224) | - | [GuLoader](https://vuldb.com/?actor.guloader) | High
4 | [23.254.227.202](https://vuldb.com/?ip.23.254.227.202) | client-23-254-227-202.hostwindsdns.com | [GuLoader](https://vuldb.com/?actor.guloader) | High
5 | [23.254.227.205](https://vuldb.com/?ip.23.254.227.205) | client-23-254-227-205.hostwindsdns.com | [GuLoader](https://vuldb.com/?actor.guloader) | High
6 | [23.254.227.214](https://vuldb.com/?ip.23.254.227.214) | pornytop.com | [GuLoader](https://vuldb.com/?actor.guloader) | High
7 | [34.138.169.8](https://vuldb.com/?ip.34.138.169.8) | 8.169.138.34.bc.googleusercontent.com | [GuLoader](https://vuldb.com/?actor.guloader) | Medium
8 | [37.0.8.96](https://vuldb.com/?ip.37.0.8.96) | - | [GuLoader](https://vuldb.com/?actor.guloader) | High
9 | [38.242.193.23](https://vuldb.com/?ip.38.242.193.23) | vmi1299973.contaboserver.net | [GuLoader](https://vuldb.com/?actor.guloader) | High
10 | [45.137.22.92](https://vuldb.com/?ip.45.137.22.92) | hosted-by.rootlayer.net | [GuLoader](https://vuldb.com/?actor.guloader) | High
11 | [45.137.22.248](https://vuldb.com/?ip.45.137.22.248) | hosted-by.rootlayer.net | [GuLoader](https://vuldb.com/?actor.guloader) | High
12 | [45.137.117.184](https://vuldb.com/?ip.45.137.117.184) | - | [GuLoader](https://vuldb.com/?actor.guloader) | High
13 | [46.183.222.51](https://vuldb.com/?ip.46.183.222.51) | ip-222-51.dataclub.info | [GuLoader](https://vuldb.com/?actor.guloader) | High
14 | ... | ... | ... | ...

There are 53 more IOC items available. Please use our online service to access the data.

## TTP - Tactics, Techniques, Procedures

_Tactics, techniques, and procedures_ (TTP) summarize the suspected MITRE ATT&CK techniques used within GuLoader. This data is unique as it uses our predictive model for actor profiling.

ID | Technique | Weakness | Description | Confidence
-- | --------- | -------- | ----------- | ----------
1 | T1006 | CWE-21, CWE-22, CWE-23, CWE-24 | Path Traversal | High
2 | T1040 | CWE-319 | Authentication Bypass by Capture-replay | High
3 | T1055 | CWE-74 | Improper Neutralization of Data within XPath Expressions | High
4 | T1059 | CWE-88, CWE-94, CWE-1321 | Argument Injection | High
5 | T1059.007 | CWE-79, CWE-80 | Basic Cross Site Scripting | High
6 | ... | ... | ... | ...

There are 20 more TTP items available. Please use our online service to access the data.

## IOA - Indicator of Attack

These _indicators of attack_ (IOA) list the potential fragments used for technical activities like reconnaissance, exploitation, privilege escalation, and exfiltration during GuLoader. This data is unique as it uses our predictive model for actor profiling.

ID | Type | Indicator | Confidence
-- | ---- | --------- | ----------
1 | File | `.jsp` | Low
2 | File | `/admin/ajax.php` | High
3 | File | `/admin/ajax.php?action=save_window` | High
4 | File | `/admin/categories/view_category.php` | High
5 | File | `/admin/edit.php` | High
6 | File | `/admin/file_manager/export` | High
7 | File | `/admin/index2.html` | High
8 | File | `/admin/inventory/manage_stock.php` | High
9 | File | `/admin/Operations/Role.php` | High
10 | File | `/admin/submit-articles` | High
11 | File | `/admin/user/manage_user.php` | High
12 | File | `/adminPage/conf/reload` | High
13 | File | `/admin_topic.php?action=delall` | High
14 | File | `/ajax.php?action=delete_deductions` | High
15 | File | `/api/baskets/{name}` | High
16 | File | `/api/cron/settings/setJob/` | High
17 | File | `/api/v2/cli/commands` | High
18 | File | `/api2/html/` | Medium
19 | File | `/app/controller/Books.php` | High
20 | File | `/backend/admin/his_admin_register_patient.php` | High
21 | File | `/bitrix/admin/ldap_server_edit.php` | High
22 | File | `/cgi-bin/cstecgi.cgi` | High
23 | File | `/cgi-bin/koha/catalogue/search.pl` | High
24 | File | `/check` | Low
25 | File | `/classes/Master.php` | High
26 | File | `/classes/Master.php?f=save_sub_category` | High
27 | File | `/CoinExchange_CryptoExchange_Java-master/00_framework/core/src/main/java/com/bizzan/bitrade/util/UploadFileUtil.java` | High
28 | File | `/common/run_cross_report.php` | High
29 | File | `/controllers/add_user.php` | High
30 | File | `/Device/Device/GetDeviceInfoList?deviceCode=&searchField=&deviceState=` | High
31 | File | `/DXR.axd` | Medium
32 | File | `/ecshop/admin/template.php` | High
33 | File | `/EXCU_SHELL` | Medium
34 | File | `/forgot-password` | High
35 | File | `/forum/away.php` | High
36 | File | `/ghost/preview` | High
37 | File | `/goform/addressNat` | High
38 | File | `/goform/NatStaticSetting` | High
39 | File | `/goform/setDeviceSettings` | High
40 | File | `/goform/SetNetControlList` | High
41 | File | `/h/rest` | Low
42 | File | `/importexport.php` | High
43 | File | `/includes/session.php` | High
44 | File | `/index.php/newsletter/subscriber/new/` | High
45 | File | `/index/ajax/lang` | High
46 | File | `/kajona/image.php` | High
47 | File | `/log/decodmail.php` | High
48 | File | `/login.php?m=admin&c=Field&a=channel_edit` | High
49 | File | `/log_proxy` | Medium
50 | File | `/mailcleaner.php/getStats` | High
51 | File | `/mfsNotice/page` | High
52 | File | `/nagiosxi/admin/banner_message-ajaxhelper.php` | High
53 | File | `/ndmComponents.js` | High
54 | File | `/net-banking/delete_customer.php` | High
55 | File | `/novel/bookSetting/list` | High
56 | File | `/novel/userFeedback/list` | High
57 | File | `/nssys/common/filehandle` | High
58 | File | `/oauth/idp/.well-known/openid-configuration` | High
59 | File | `/op/op.LockDocument.php` | High
60 | File | `/openvpn/pageswitch.htm` | High
61 | File | `/opt/vyatta/share/vyatta-cfg/templates/system/static-host-mapping/host-name/node.def` | High
62 | File | `/owa/auth/logon.aspx` | High
63 | File | `/page.php` | Medium
64 | ... | ... | ...

There are 563 more IOA items available (file, library, argument, input value, pattern, network port). Please use our online service to access the data.

## References

The following list contains _external sources_ which discuss the campaign and the associated activities:

* https://any.run/cybersecurity-blog/deobfuscating-guloader/
* https://asec.ahnlab.com/en/36042/
* https://asec.ahnlab.com/en/36294/
* https://asec.ahnlab.com/en/36785/
* https://asec.ahnlab.com/en/38942/
* https://asec.ahnlab.com/en/40283/
* https://asec.ahnlab.com/en/48640/
* https://asec.ahnlab.com/en/51274/
* https://asec.ahnlab.com/en/52488/
* https://blog.sekoia.io/webdav-as-a-service-uncovering-the-infrastructure-behind-emmenhtal-loader-distribution/
* https://github.com/sophoslabs/IoCs/blob/master/Troj_GuLoader.csv
* https://isc.sans.edu/diary/GuLoader+or+DBatLoaderModiLoaderstyle+infection+for+Remcos+RAT/29990
* https://research.checkpoint.com/2023/unveiling-the-shadows-the-dark-alliance-between-guloader-and-remcos/
* https://urlhaus.abuse.ch/url/3521978/
* https://urlhaus.abuse.ch/url/3523832/
* https://urlhaus.abuse.ch/url/3526314/
* https://urlhaus.abuse.ch/url/3527469/
* https://urlhaus.abuse.ch/url/3529641/
* https://urlhaus.abuse.ch/url/3530723/
* https://urlhaus.abuse.ch/url/3530849/
* https://urlhaus.abuse.ch/url/3530850/
* https://urlhaus.abuse.ch/url/3531651/
* https://urlhaus.abuse.ch/url/3537634/
* https://urlhaus.abuse.ch/url/3538348/
* https://urlhaus.abuse.ch/url/3538350/
* https://urlhaus.abuse.ch/url/3538657/
* https://urlhaus.abuse.ch/url/3541770/
* https://urlhaus.abuse.ch/url/3542084/
* https://urlhaus.abuse.ch/url/3543338/
* https://urlhaus.abuse.ch/url/3544048/
* https://urlhaus.abuse.ch/url/3544158/
* https://urlhaus.abuse.ch/url/3544537/
* https://urlhaus.abuse.ch/url/3544538/
* https://urlhaus.abuse.ch/url/3545537/
* https://urlhaus.abuse.ch/url/3548066/
* https://urlhaus.abuse.ch/url/3548067/
* https://urlhaus.abuse.ch/url/3549543/
* https://urlhaus.abuse.ch/url/3555523/
* https://urlhaus.abuse.ch/url/3555527/
* https://urlhaus.abuse.ch/url/3556613/
* https://urlhaus.abuse.ch/url/3556689/
* https://urlhaus.abuse.ch/url/3558722/
* https://www.cadosecurity.com/blog/guloader-targeting-european-industrial-companies
* https://www.elastic.co/security-labs/getting-gooey-with-guloader-downloader
* https://www.malware-traffic-analysis.net/2024/08/26/index.html

## Literature

The following _articles_ explain our unique predictive cyber threat intelligence:

* [VulDB Cyber Threat Intelligence Documentation](https://vuldb.com/?kb.cti)
* [Cyber Threat Intelligence - Early Anticipation of Attacks](https://www.scip.ch/en/?labs.20201022)

## License

(c) [1997-2025](https://vuldb.com/?kb.changelog) by [vuldb.com](https://vuldb.com/?kb.about). All data on this page is shared under the license [CC BY-NC-SA 4.0](https://creativecommons.org/licenses/by-nc-sa/4.0/). Questions? Check the [FAQ](https://vuldb.com/?kb.faq), read the [documentation](https://vuldb.com/?kb) or [contact us](https://vuldb.com/?contact)!
