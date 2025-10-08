# WatchDog - Cyber Threat Intelligence

These _indicators_ were reported, collected, and generated during the [VulDB CTI analysis](https://vuldb.com/?kb.cti) of the actor known as [WatchDog](https://vuldb.com/?actor.watchdog). The _activity monitoring_ correlates data from social media, forums, chat rooms, and darknet markets. It helps to determine associated actors, specific activities, expected intentions, emerging research, and ongoing attacks. Our unique _predictive model_ uses _big data_ to forecast activities and their characteristics.

_Live data_ and more _analysis capabilities_ are available at [https://vuldb.com/?actor.watchdog](https://vuldb.com/?actor.watchdog)

## Countries

These _countries_ are directly (e.g. origin of attacks) or indirectly (e.g. access by proxy) associated with WatchDog:

* [US](https://vuldb.com/?country.us)
* [SC](https://vuldb.com/?country.sc)
* [CN](https://vuldb.com/?country.cn)
* ...

There are 14 more country items available. Please use our online service to access the data.

## IOC - Indicator of Compromise

These _indicators of compromise_ (IOC) indicate associated network resources which are known to be part of research and attack activities of WatchDog.

ID | IP address | Hostname | Campaign | Confidence
-- | ---------- | -------- | -------- | ----------
1 | [39.100.33.209](https://vuldb.com/?ip.39.100.33.209) | - | - | High
2 | [45.9.148.37](https://vuldb.com/?ip.45.9.148.37) | - | - | High
3 | [45.153.240.58](https://vuldb.com/?ip.45.153.240.58) | - | - | High
4 | [47.253.42.213](https://vuldb.com/?ip.47.253.42.213) | - | - | High
5 | [80.211.206.105](https://vuldb.com/?ip.80.211.206.105) | 105.206.forpsi.net | - | High
6 | ... | ... | ... | ...

There are 19 more IOC items available. Please use our online service to access the data.

## TTP - Tactics, Techniques, Procedures

_Tactics, techniques, and procedures_ (TTP) summarize the suspected MITRE ATT&CK techniques used by _WatchDog_. This data is unique as it uses our predictive model for actor profiling.

ID | Technique | Weakness | Description | Confidence
-- | --------- | -------- | ----------- | ----------
1 | T1006 | CWE-22, CWE-23, CWE-24, CWE-28, CWE-425 | Path Traversal | High
2 | T1040 | CWE-319 | Authentication Bypass by Capture-replay | High
3 | T1055 | CWE-74 | Improper Neutralization of Data within XPath Expressions | High
4 | T1059 | CWE-88, CWE-94 | Argument Injection | High
5 | T1059.007 | CWE-79, CWE-80 | Basic Cross Site Scripting | High
6 | ... | ... | ... | ...

There are 21 more TTP items available. Please use our online service to access the data.

## IOA - Indicator of Attack

These _indicators of attack_ (IOA) list the potential fragments used for technical activities like reconnaissance, exploitation, privilege escalation, and exfiltration by WatchDog. This data is unique as it uses our predictive model for actor profiling.

ID | Type | Indicator | Confidence
-- | ---- | --------- | ----------
1 | File | `/.vnc/sesman_${username}_passwd` | High
2 | File | `/academy/tutor/filter` | High
3 | File | `/ad-list` | Medium
4 | File | `/admin` | Low
5 | File | `/admin/index2.html` | High
6 | File | `/admin/normal-search.php` | High
7 | File | `/admin/suppliers/view_details.php` | High
8 | File | `/admin/uesrs.php&action=display&value=Hide` | High
9 | File | `/ajax.php?action=read_msg` | High
10 | File | `/api/authentication/login` | High
11 | File | `/api/discoveries/` | High
12 | File | `/api/sys/login` | High
13 | File | `/api/sys/set_passwd` | High
14 | File | `/api/v2/open/rowsInfo` | High
15 | File | `/app/sys1.php` | High
16 | File | `/asms/classes/Master.php?f=delete_transaction` | High
17 | File | `/building/backmgr/urlpage/mobileurl/configfile/jx2_config.ini` | High
18 | File | `/cas/logout` | Medium
19 | File | `/catalog/admin/categories.php?cPath=&action=new_product` | High
20 | File | `/catalog/all-products` | High
21 | File | `/cgi-bin/adm.cgi` | High
22 | File | `/cgi-bin/editBookmark` | High
23 | File | `/cgi-bin/mesh.cgi?page=upgrade` | High
24 | File | `/cgi-bin/nas_sharing.cgi` | High
25 | File | `/cgi-bin/nightled.cgi` | High
26 | File | `/cgi-bin/nobody` | High
27 | File | `/cgi-bin/nobody/Search.cgi` | High
28 | File | `/cgi-bin/supervisor/PwdGrp.cgi` | High
29 | File | `/cgi-bin/touchlist_sync.cgi` | High
30 | File | `/cgi-bin/user/Config.cgi` | High
31 | File | `/cgi-bin/vitogate.cgi` | High
32 | File | `/chat_im/chat_window.php` | High
33 | File | `/classes/Master.php` | High
34 | File | `/cloud_config/router_post/get_reg_verify_code` | High
35 | File | `/controllers/updatesettings.php` | High
36 | File | `/data/edit_type.php` | High
37 | File | `/debug/pprof` | Medium
38 | File | `/designer/add/layout` | High
39 | File | `/desktop_app/file.ajax.php?action=uploadfile` | High
40 | File | `/downloadFile.php` | High
41 | File | `/emap/devicePoint_addImgIco?hasSubsystem=true` | High
42 | File | `/env` | Low
43 | File | `/etc/openstack-dashboard/local_settings` | High
44 | File | `/etc/passwd` | Medium
45 | File | `/filemanager/upload.php` | High
46 | File | `/find-a-match` | High
47 | ... | ... | ...

There are 404 more IOA items available (file, library, argument, input value, pattern, network port). Please use our online service to access the data.

## References

The following list contains _external sources_ which discuss the actor and the associated activities:

* https://unit42.paloaltonetworks.com/watchdog-cryptojacking/

## Literature

The following _articles_ explain our unique predictive cyber threat intelligence:

* [VulDB Cyber Threat Intelligence Documentation](https://vuldb.com/?kb.cti)
* [Cyber Threat Intelligence - Early Anticipation of Attacks](https://www.scip.ch/en/?labs.20201022)

## License

(c) [1997-2025](https://vuldb.com/?kb.changelog) by [vuldb.com](https://vuldb.com/?kb.about). All data on this page is shared under the license [CC BY-NC-SA 4.0](https://creativecommons.org/licenses/by-nc-sa/4.0/). Questions? Check the [FAQ](https://vuldb.com/?kb.faq), read the [documentation](https://vuldb.com/?kb) or [contact us](https://vuldb.com/?contact)!
