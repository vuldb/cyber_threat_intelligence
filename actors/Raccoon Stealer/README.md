# Raccoon Stealer - Cyber Threat Intelligence

These _indicators_ were reported, collected, and generated during the [VulDB CTI analysis](https://vuldb.com/?kb.cti) of the actor known as [Raccoon Stealer](https://vuldb.com/?actor.raccoon_stealer). The _activity monitoring_ correlates data from social media, forums, chat rooms, and darknet markets. It helps to determine associated actors, specific activities, expected intentions, emerging research, and ongoing attacks. Our unique _predictive model_ uses _big data_ to forecast activities and their characteristics.

_Live data_ and more _analysis capabilities_ are available at [https://vuldb.com/?actor.raccoon_stealer](https://vuldb.com/?actor.raccoon_stealer)

## Countries

These _countries_ are directly (e.g. origin of attacks) or indirectly (e.g. access by proxy) associated with Raccoon Stealer:

* [SH](https://vuldb.com/?country.sh)
* [US](https://vuldb.com/?country.us)
* [CN](https://vuldb.com/?country.cn)
* ...

There are 6 more country items available. Please use our online service to access the data.

## IOC - Indicator of Compromise

These _indicators of compromise_ (IOC) indicate associated network resources which are known to be part of research and attack activities of Raccoon Stealer.

ID | IP address | Hostname | Campaign | Confidence
-- | ---------- | -------- | -------- | ----------
1 | [2.58.56.247](https://vuldb.com/?ip.2.58.56.247) | powered.by.rdp.sh | - | High
2 | [5.42.199.87](https://vuldb.com/?ip.5.42.199.87) | - | - | High
3 | [5.252.22.62](https://vuldb.com/?ip.5.252.22.62) | vm523526.stark-industries.solutions | - | High
4 | [5.252.22.66](https://vuldb.com/?ip.5.252.22.66) | s-germany.rocks | - | High
5 | [5.252.22.107](https://vuldb.com/?ip.5.252.22.107) | ns3.pacehost.de | - | High
6 | [23.88.55.150](https://vuldb.com/?ip.23.88.55.150) | static.150.55.88.23.clients.your-server.de | - | High
7 | [31.13.195.44](https://vuldb.com/?ip.31.13.195.44) | - | - | High
8 | [45.61.136.191](https://vuldb.com/?ip.45.61.136.191) | - | - | High
9 | [45.67.34.152](https://vuldb.com/?ip.45.67.34.152) | vm749292.stark-industries.solutions | - | High
10 | [45.67.34.234](https://vuldb.com/?ip.45.67.34.234) | server.ga2.so-net.ne.jp | - | High
11 | [45.67.35.251](https://vuldb.com/?ip.45.67.35.251) | vm684273.stark-industries.solutions | - | High
12 | [45.84.0.80](https://vuldb.com/?ip.45.84.0.80) | sfixbfc.cn | - | High
13 | [45.92.156.52](https://vuldb.com/?ip.45.92.156.52) | - | - | High
14 | [45.92.156.53](https://vuldb.com/?ip.45.92.156.53) | - | - | High
15 | [45.133.216.145](https://vuldb.com/?ip.45.133.216.145) | mail.axiknh.top | - | High
16 | [45.133.216.170](https://vuldb.com/?ip.45.133.216.170) | wireguard.vasilchenko.dev | - | High
17 | [45.133.216.249](https://vuldb.com/?ip.45.133.216.249) | vm699942.stark-industries.solutions | - | High
18 | [45.138.74.104](https://vuldb.com/?ip.45.138.74.104) | descriptive-servant.aeza.network | - | High
19 | [45.142.212.100](https://vuldb.com/?ip.45.142.212.100) | pikpik.top | - | High
20 | [45.142.215.50](https://vuldb.com/?ip.45.142.215.50) | vm700900.stark-industries.solutions | - | High
21 | [45.142.215.92](https://vuldb.com/?ip.45.142.215.92) | vm586875.stark-industries.solutions | - | High
22 | ... | ... | ... | ...

There are 83 more IOC items available. Please use our online service to access the data.

## TTP - Tactics, Techniques, Procedures

_Tactics, techniques, and procedures_ (TTP) summarize the suspected MITRE ATT&CK techniques used by _Raccoon Stealer_. This data is unique as it uses our predictive model for actor profiling.

ID | Technique | Weakness | Description | Confidence
-- | --------- | -------- | ----------- | ----------
1 | T1006 | CWE-21, CWE-22, CWE-23, CWE-24 | Pathname Traversal | High
2 | T1040 | CWE-319 | Authentication Bypass by Capture-replay | High
3 | T1055 | CWE-74 | Injection | High
4 | T1059 | CWE-88, CWE-94 | Cross Site Scripting | High
5 | T1059.007 | CWE-79, CWE-80 | Cross Site Scripting | High
6 | ... | ... | ... | ...

There are 21 more TTP items available. Please use our online service to access the data.

## IOA - Indicator of Attack

These _indicators of attack_ (IOA) list the potential fragments used for technical activities like reconnaissance, exploitation, privilege escalation, and exfiltration by Raccoon Stealer. This data is unique as it uses our predictive model for actor profiling.

ID | Type | Indicator | Confidence
-- | ---- | --------- | ----------
1 | File | `/?p=products` | Medium
2 | File | `/admin/?page=product/manage_product&id=2` | High
3 | File | `/admin/ajax.php?action=delete_window` | High
4 | File | `/admin/api/theme-edit/` | High
5 | File | `/admin/casedetails.php` | High
6 | File | `/admin/maintenance/brand.php` | High
7 | File | `/admin/mechanics/manage_mechanic.php` | High
8 | File | `/admin/userprofile.php` | High
9 | File | `/admin/voters_row.php` | High
10 | File | `/ad_js.php` | Medium
11 | File | `/agc/vicidial.php` | High
12 | File | `/ajax/myshop` | Medium
13 | File | `/alumni/admin/ajax.php?action=save_settings` | High
14 | File | `/api/gen/clients/{language}` | High
15 | File | `/apply.cgi` | Medium
16 | File | `/APR/signup.php` | High
17 | File | `/aux` | Low
18 | File | `/categorypage.php` | High
19 | File | `/cgi-bin/system_mgr.cgi` | High
20 | File | `/cgi-bin/wlogin.cgi` | High
21 | File | `/cha.php` | Medium
22 | File | `/College/admin/teacher.php` | High
23 | File | `/Controls/Generic/EBMK/Handlers/EStatements/DownloadEStatement.ashx` | High
24 | File | `/dayrui/Fcms/View/system_log.html` | High
25 | File | `/dev/mem` | Medium
26 | File | `/drivers/block/floppy.c` | High
27 | File | `/ecommerce/admin/category/controller.php` | High
28 | File | `/etc/config/product.ini` | High
29 | File | `/etc/crash` | Medium
30 | File | `/etc/shadow` | Medium
31 | File | `/fos/admin/ajax.php` | High
32 | File | `/goform/aspForm` | High
33 | File | `/goform/delAd` | High
34 | File | `/goform/WifiBasicSet` | High
35 | File | `/inc/topBarNav.php` | High
36 | File | `/index.php` | Medium
37 | File | `/login/index.php` | High
38 | File | `/medicines/profile.php` | High
39 | File | `/menu.html` | Medium
40 | File | `/Moosikay/order.php` | High
41 | File | `/multi-vendor-shopping-script/product-list.php` | High
42 | File | `/nasm/nasm-parse.c` | High
43 | File | `/ordering/admin/orders/loaddata.php` | High
44 | File | `/ordering/admin/stockin/loaddata.php` | High
45 | File | `/philosophy/admin/login.php` | High
46 | File | `/php-opos/login.php` | High
47 | File | `/priv_mgt.html` | High
48 | File | `/queuing/index.php?page=display` | High
49 | File | `/resources//../` | High
50 | File | `/tmp/app/.env` | High
51 | File | `/ui/cbpc/login` | High
52 | File | `/user/updatePwd` | High
53 | File | `/users/delete/2` | High
54 | File | `/usr/sbin/nagios` | High
55 | File | `/var/tmp/audacity-$USER` | High
56 | File | `/webman/info.cgi` | High
57 | File | `/wp-json/wc/v3/webhooks` | High
58 | File | `3G/UMTS` | Low
59 | File | `account_change.php` | High
60 | File | `acloudCosAction.php.SQL` | High
61 | File | `ActiveServices.java` | High
62 | File | `ad.php` | Low
63 | ... | ... | ...

There are 554 more IOA items available (file, library, argument, input value, pattern, network port). Please use our online service to access the data.

## References

The following list contains _external sources_ which discuss the actor and the associated activities:

* https://community.blueliv.com/#!/s/610bc7b082df417ed032f5f1
* https://github.com/SEKOIA-IO/Community/blob/main/IOCs/raccoonstealer/raccoon_stealer_iocs_20220628.csv
* https://www.zerofox.com/blog/brief-raccoon-stealer-version-2-0/

## Literature

The following _articles_ explain our unique predictive cyber threat intelligence:

* [VulDB Cyber Threat Intelligence Documentation](https://vuldb.com/?kb.cti)
* [Cyber Threat Intelligence - Early Anticipation of Attacks](https://www.scip.ch/en/?labs.20201022)

## License

(c) [1997-2023](https://vuldb.com/?kb.changelog) by [vuldb.com](https://vuldb.com/?kb.about). All data on this page is shared under the license [CC BY-NC-SA 4.0](https://creativecommons.org/licenses/by-nc-sa/4.0/). Questions? Check the [FAQ](https://vuldb.com/?kb.faq), read the [documentation](https://vuldb.com/?kb) or [contact us](https://vuldb.com/?contact)!
