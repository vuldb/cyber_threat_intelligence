# Flax Typhoon - Cyber Threat Intelligence

These _indicators_ were reported, collected, and generated during the [VulDB CTI analysis](https://vuldb.com/?kb.cti) of the actor known as [Flax Typhoon](https://vuldb.com/?actor.flax_typhoon). The _activity monitoring_ correlates data from social media, forums, chat rooms, and darknet markets. It helps to determine associated actors, specific activities, expected intentions, emerging research, and ongoing attacks. Our unique _predictive model_ uses _big data_ to forecast activities and their characteristics.

_Live data_ and more _analysis capabilities_ are available at [https://vuldb.com/?actor.flax_typhoon](https://vuldb.com/?actor.flax_typhoon)

## Campaigns

The following _campaigns_ are known and can be associated with Flax Typhoon:

* Taiwanese Organizations

## Countries

These _countries_ are directly (e.g. origin of attacks) or indirectly (e.g. access by proxy) associated with Flax Typhoon:

* [CN](https://vuldb.com/?country.cn)
* [US](https://vuldb.com/?country.us)
* [GB](https://vuldb.com/?country.gb)
* ...

There are 2 more country items available. Please use our online service to access the data.

## IOC - Indicator of Compromise

These _indicators of compromise_ (IOC) indicate associated network resources which are known to be part of research and attack activities of Flax Typhoon.

ID | IP address | Hostname | Campaign | Confidence
-- | ---------- | -------- | -------- | ----------
1 | [39.98.208.61](https://vuldb.com/?ip.39.98.208.61) | - | Taiwanese Organizations | High
2 | [45.88.192.118](https://vuldb.com/?ip.45.88.192.118) | Host-By.DMIT.com | Taiwanese Organizations | High
3 | [45.195.149.224](https://vuldb.com/?ip.45.195.149.224) | - | Taiwanese Organizations | High
4 | ... | ... | ... | ...

There are 9 more IOC items available. Please use our online service to access the data.

## TTP - Tactics, Techniques, Procedures

_Tactics, techniques, and procedures_ (TTP) summarize the suspected MITRE ATT&CK techniques used by _Flax Typhoon_. This data is unique as it uses our predictive model for actor profiling.

ID | Technique | Weakness | Description | Confidence
-- | --------- | -------- | ----------- | ----------
1 | T1006 | CWE-21, CWE-22, CWE-23, CWE-24, CWE-29, CWE-425 | Pathname Traversal | High
2 | T1040 | CWE-294 | Authentication Bypass by Capture-replay | High
3 | T1055 | CWE-74 | Injection | High
4 | T1059 | CWE-88, CWE-94 | Cross Site Scripting | High
5 | T1059.007 | CWE-79, CWE-80 | Cross Site Scripting | High
6 | ... | ... | ... | ...

There are 18 more TTP items available. Please use our online service to access the data.

## IOA - Indicator of Attack

These _indicators of attack_ (IOA) list the potential fragments used for technical activities like reconnaissance, exploitation, privilege escalation, and exfiltration by Flax Typhoon. This data is unique as it uses our predictive model for actor profiling.

ID | Type | Indicator | Confidence
-- | ---- | --------- | ----------
1 | File | `/act/ActDao.xml` | High
2 | File | `/admin.php?action=themeinstall` | High
3 | File | `/admin/?page=product/manage_product&id=2` | High
4 | File | `/admin/?setting-base.htm` | High
5 | File | `/admin/bookings/manage_booking.php` | High
6 | File | `/admin/controller/JobLogController.java` | High
7 | File | `/admin/del_service.php` | High
8 | File | `/admin/index.php` | High
9 | File | `/admin/index2.html` | High
10 | File | `/admin/scripts/pi-hole/phpqueryads.php` | High
11 | File | `/api/authentication/login` | High
12 | File | `/api/resource/Item?fields` | High
13 | File | `/api/upload.php` | High
14 | File | `/api/v1/terminal/sessions/?limit=1` | High
15 | File | `/api /v3/auth` | High
16 | File | `/app/sys1.php` | High
17 | File | `/application/common.php#action_log` | High
18 | File | `/APR/signup.php` | High
19 | File | `/bin/ate` | Medium
20 | File | `/bin/rc4_crypt` | High
21 | File | `/bitrix/admin/ldap_server_edit.php` | High
22 | File | `/cgi-bin/activate.cgi` | High
23 | File | `/cgi-bin/kerbynet` | High
24 | File | `/cgi-bin/luci/api/switch` | High
25 | File | `/cgi-bin/luci/api/wireless` | High
26 | File | `/cgi-bin/luci;stok=/locale` | High
27 | File | `/cgi-bin/qcmap_auth` | High
28 | File | `/cgi-bin/wapopen` | High
29 | File | `/classes/Master.php?f=delete_category` | High
30 | File | `/classes/Master.php?f=delete_inquiry` | High
31 | File | `/classes/Master.php?f=delete_item` | High
32 | File | `/classes/Master.php?f=delete_service` | High
33 | File | `/classes/Master.php?f=save_service` | High
34 | File | `/classes/Users.php` | High
35 | File | `/classes/Users.php?f=save` | High
36 | File | `/CMD_ACCOUNT_ADMIN` | High
37 | File | `/conf/` | Low
38 | File | `/config/getuser` | High
39 | File | `/config/php.ini` | High
40 | File | `/Content/Plugins/uploader/FileChoose.html?fileUrl=/Upload/File/Pics/&parent` | High
41 | File | `/controller/OnlinePreviewController.java` | High
42 | File | `/core/admin/categories.php` | High
43 | File | `/dayrui/My/View/main.html` | High
44 | File | `/debug/pprof` | Medium
45 | File | `/etc/init.d/openfire` | High
46 | File | `/etc/sudoers` | Medium
47 | ... | ... | ...

There are 407 more IOA items available (file, library, argument, input value, pattern, network port). Please use our online service to access the data.

## References

The following list contains _external sources_ which discuss the actor and the associated activities:

* https://www.microsoft.com/en-us/security/blog/2023/08/24/flax-typhoon-using-legitimate-software-to-quietly-access-taiwanese-organizations/

## Literature

The following _articles_ explain our unique predictive cyber threat intelligence:

* [VulDB Cyber Threat Intelligence Documentation](https://vuldb.com/?kb.cti)
* [Cyber Threat Intelligence - Early Anticipation of Attacks](https://www.scip.ch/en/?labs.20201022)

## License

(c) [1997-2024](https://vuldb.com/?kb.changelog) by [vuldb.com](https://vuldb.com/?kb.about). All data on this page is shared under the license [CC BY-NC-SA 4.0](https://creativecommons.org/licenses/by-nc-sa/4.0/). Questions? Check the [FAQ](https://vuldb.com/?kb.faq), read the [documentation](https://vuldb.com/?kb) or [contact us](https://vuldb.com/?contact)!
