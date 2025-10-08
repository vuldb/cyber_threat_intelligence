# GuLoader - Cyber Threat Intelligence

These _indicators_ were reported, collected, and generated during the [VulDB CTI analysis](https://vuldb.com/?kb.cti) of the actor known as [GuLoader](https://vuldb.com/?actor.guloader). The _activity monitoring_ correlates data from social media, forums, chat rooms, and darknet markets. It helps to determine associated actors, specific activities, expected intentions, emerging research, and ongoing attacks. Our unique _predictive model_ uses _big data_ to forecast activities and their characteristics.

_Live data_ and more _analysis capabilities_ are available at [https://vuldb.com/?actor.guloader](https://vuldb.com/?actor.guloader)

## Countries

These _countries_ are directly (e.g. origin of attacks) or indirectly (e.g. access by proxy) associated with GuLoader:

* [US](https://vuldb.com/?country.us)
* [LA](https://vuldb.com/?country.la)
* [CN](https://vuldb.com/?country.cn)
* ...

There are 12 more country items available. Please use our online service to access the data.

## IOC - Indicator of Compromise

These _indicators of compromise_ (IOC) indicate associated network resources which are known to be part of research and attack activities of GuLoader.

ID | IP address | Hostname | Campaign | Confidence
-- | ---------- | -------- | -------- | ----------
1 | [5.2.75.164](https://vuldb.com/?ip.5.2.75.164) | - | - | High
2 | [5.8.8.100](https://vuldb.com/?ip.5.8.8.100) | - | - | High
3 | [5.255.110.224](https://vuldb.com/?ip.5.255.110.224) | - | - | High
4 | [23.254.227.202](https://vuldb.com/?ip.23.254.227.202) | client-23-254-227-202.hostwindsdns.com | - | High
5 | [23.254.227.205](https://vuldb.com/?ip.23.254.227.205) | client-23-254-227-205.hostwindsdns.com | - | High
6 | [23.254.227.214](https://vuldb.com/?ip.23.254.227.214) | pornytop.com | - | High
7 | [34.138.169.8](https://vuldb.com/?ip.34.138.169.8) | 8.169.138.34.bc.googleusercontent.com | - | Medium
8 | [37.0.8.96](https://vuldb.com/?ip.37.0.8.96) | - | - | High
9 | [38.242.193.23](https://vuldb.com/?ip.38.242.193.23) | vmi1299973.contaboserver.net | - | High
10 | [45.137.22.92](https://vuldb.com/?ip.45.137.22.92) | hosted-by.rootlayer.net | - | High
11 | [45.137.22.248](https://vuldb.com/?ip.45.137.22.248) | hosted-by.rootlayer.net | - | High
12 | [45.137.117.184](https://vuldb.com/?ip.45.137.117.184) | - | - | High
13 | [46.183.222.51](https://vuldb.com/?ip.46.183.222.51) | ip-222-51.dataclub.info | - | High
14 | [46.183.223.21](https://vuldb.com/?ip.46.183.223.21) | nat1.gratezer.com | - | High
15 | [46.183.223.88](https://vuldb.com/?ip.46.183.223.88) | ip-223-88.dataclub.info | - | High
16 | [64.44.168.209](https://vuldb.com/?ip.64.44.168.209) | 209-168-44-64-.reverse-dns | - | High
17 | [67.21.33.181](https://vuldb.com/?ip.67.21.33.181) | - | - | High
18 | ... | ... | ... | ...

There are 67 more IOC items available. Please use our online service to access the data.

## TTP - Tactics, Techniques, Procedures

_Tactics, techniques, and procedures_ (TTP) summarize the suspected MITRE ATT&CK techniques used by _GuLoader_. This data is unique as it uses our predictive model for actor profiling.

ID | Technique | Weakness | Description | Confidence
-- | --------- | -------- | ----------- | ----------
1 | T1006 | CWE-21, CWE-22, CWE-23, CWE-24 | Path Traversal | High
2 | T1055 | CWE-74 | Improper Neutralization of Data within XPath Expressions | High
3 | T1059 | CWE-88, CWE-94, CWE-1321 | Argument Injection | High
4 | T1059.007 | CWE-79, CWE-80, CWE-85 | Basic Cross Site Scripting | High
5 | T1068 | CWE-264, CWE-269, CWE-284 | Execution with Unnecessary Privileges | High
6 | ... | ... | ... | ...

There are 20 more TTP items available. Please use our online service to access the data.

## IOA - Indicator of Attack

These _indicators of attack_ (IOA) list the potential fragments used for technical activities like reconnaissance, exploitation, privilege escalation, and exfiltration by GuLoader. This data is unique as it uses our predictive model for actor profiling.

ID | Type | Indicator | Confidence
-- | ---- | --------- | ----------
1 | File | `.jsp` | Low
2 | File | `/+CSCOE+/logon.html` | High
3 | File | `/admin/` | Low
4 | File | `/admin/action/new-feed.php` | High
5 | File | `/admin/ajax.php` | High
6 | File | `/admin/article.php` | High
7 | File | `/admin/edit.php` | High
8 | File | `/admin/file_manager/export` | High
9 | File | `/admin/index2.html` | High
10 | File | `/admin/Operations/Role.php` | High
11 | File | `/admin/pages/` | High
12 | File | `/admin/uesrs.php&action=type&userrole=Admin&userid=3` | High
13 | File | `/admin/user/manage_user.php` | High
14 | File | `/adminPage/conf/reload` | High
15 | File | `/admins` | Low
16 | File | `/admin_topic.php?action=delall` | High
17 | File | `/ajax.php?action=delete_deductions` | High
18 | File | `/ajax/getBasicInfo.php` | High
19 | File | `/api/admin/system/store/order/list` | High
20 | File | `/api/baskets/{name}` | High
21 | File | `/api/cron/settings/setJob/` | High
22 | File | `/api2/html/` | Medium
23 | File | `/backend/admin/his_admin_register_patient.php` | High
24 | File | `/bitrix/admin/ldap_server_edit.php` | High
25 | File | `/cgi-bin/cstecgi.cgi` | High
26 | File | `/cgi-bin/koha/catalogue/search.pl` | High
27 | File | `/cgi-bin/wlogin.cgi` | High
28 | File | `/check` | Low
29 | File | `/city.php` | Medium
30 | File | `/classes/Master.php?f=save_sub_category` | High
31 | File | `/ClickAndBanexDemo/admin/admin_dblayers.asp` | High
32 | File | `/client.php` | Medium
33 | File | `/clientdetails/admin/regester.php` | High
34 | File | `/CoinExchange_CryptoExchange_Java-master/00_framework/core/src/main/java/com/bizzan/bitrade/util/UploadFileUtil.java` | High
35 | File | `/config/myfield/test.php` | High
36 | File | `/controllers/add_user.php` | High
37 | File | `/csms/?page=contact_us` | High
38 | File | `/dayrui/Fcms/View/system_log.html` | High
39 | File | `/designation_viewmore.php` | High
40 | File | `/details.php` | Medium
41 | File | `/Device/Device/GetDeviceInfoList?deviceCode=&searchField=&deviceState=` | High
42 | File | `/DXR.axd` | Medium
43 | File | `/ecshop/admin/template.php` | High
44 | File | `/farm/product.php` | High
45 | File | `/forgot-password` | High
46 | File | `/formLoginAuth.htm` | High
47 | File | `/forum/away.php` | High
48 | File | `/goform/ate` | Medium
49 | File | `/goform/setDeviceSettings` | High
50 | File | `/goform/setMacFilterCfg` | High
51 | File | `/goform/SetNetControlList` | High
52 | File | `/goform/setWtpData` | High
53 | File | `/goform/WifiExtraSet` | High
54 | File | `/h/rest` | Low
55 | File | `/importexport.php` | High
56 | File | `/inc/topBarNav.php` | High
57 | File | `/includes/create_share.php` | High
58 | File | `/index.php` | Medium
59 | File | `/index/ajax/lang` | High
60 | File | `/log/decodmail.php` | High
61 | File | `/login.php?m=admin&c=Field&a=channel_edit` | High
62 | File | `/log_proxy` | Medium
63 | File | `/mailcleaner.php/getStats` | High
64 | File | `/manage_block.php` | High
65 | ... | ... | ...

There are 571 more IOA items available (file, library, argument, input value, pattern, network port). Please use our online service to access the data.

## References

The following list contains _external sources_ which discuss the actor and the associated activities:

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
* https://urlhaus.abuse.ch/url/3560461/
* https://urlhaus.abuse.ch/url/3561571/
* https://urlhaus.abuse.ch/url/3561754/
* https://urlhaus.abuse.ch/url/3562868/
* https://urlhaus.abuse.ch/url/3563019/
* https://urlhaus.abuse.ch/url/3569157/
* https://urlhaus.abuse.ch/url/3569848/
* https://urlhaus.abuse.ch/url/3570077/
* https://urlhaus.abuse.ch/url/3570785/
* https://urlhaus.abuse.ch/url/3572468/
* https://urlhaus.abuse.ch/url/3578236/
* https://urlhaus.abuse.ch/url/3578900/
* https://urlhaus.abuse.ch/url/3581757/
* https://urlhaus.abuse.ch/url/3581761/
* https://urlhaus.abuse.ch/url/3583765/
* https://urlhaus.abuse.ch/url/3583766/
* https://urlhaus.abuse.ch/url/3584976/
* https://urlhaus.abuse.ch/url/3586405/
* https://urlhaus.abuse.ch/url/3587478/
* https://urlhaus.abuse.ch/url/3593047/
* https://urlhaus.abuse.ch/url/3593048/
* https://www.elastic.co/security-labs/getting-gooey-with-guloader-downloader
* https://www.malware-traffic-analysis.net/2024/08/26/index.html

## Literature

The following _articles_ explain our unique predictive cyber threat intelligence:

* [VulDB Cyber Threat Intelligence Documentation](https://vuldb.com/?kb.cti)
* [Cyber Threat Intelligence - Early Anticipation of Attacks](https://www.scip.ch/en/?labs.20201022)

## License

(c) [1997-2025](https://vuldb.com/?kb.changelog) by [vuldb.com](https://vuldb.com/?kb.about). All data on this page is shared under the license [CC BY-NC-SA 4.0](https://creativecommons.org/licenses/by-nc-sa/4.0/). Questions? Check the [FAQ](https://vuldb.com/?kb.faq), read the [documentation](https://vuldb.com/?kb) or [contact us](https://vuldb.com/?contact)!
