# Magecart - Cyber Threat Intelligence

These _indicators_ were reported, collected, and generated during the [VulDB CTI analysis](https://vuldb.com/?kb.cti) of the actor known as [Magecart](https://vuldb.com/?actor.magecart). The _activity monitoring_ correlates data from social media, forums, chat rooms, and darknet markets. It helps to determine associated actors, specific activities, expected intentions, emerging research, and ongoing attacks. Our unique _predictive model_ uses _big data_ to forecast activities and their characteristics.

_Live data_ and more _analysis capabilities_ are available at [https://vuldb.com/?actor.magecart](https://vuldb.com/?actor.magecart)

## Countries

These _countries_ are directly (e.g. origin of attacks) or indirectly (e.g. access by proxy) associated with Magecart:

* [CN](https://vuldb.com/?country.cn)
* [US](https://vuldb.com/?country.us)
* [RU](https://vuldb.com/?country.ru)
* ...

There are 12 more country items available. Please use our online service to access the data.

## IOC - Indicator of Compromise

These _indicators of compromise_ (IOC) indicate associated network resources which are known to be part of research and attack activities of Magecart.

ID | IP address | Hostname | Campaign | Confidence
-- | ---------- | -------- | -------- | ----------
1 | [5.135.247.141](https://vuldb.com/?ip.5.135.247.141) | ip141.ip-5-135-247.eu | - | High
2 | [5.135.247.142](https://vuldb.com/?ip.5.135.247.142) | ip142.ip-5-135-247.eu | - | High
3 | [5.188.44.32](https://vuldb.com/?ip.5.188.44.32) | - | - | High
4 | [8.209.70.103](https://vuldb.com/?ip.8.209.70.103) | - | - | High
5 | [8.211.0.55](https://vuldb.com/?ip.8.211.0.55) | - | - | High
6 | [8.211.5.139](https://vuldb.com/?ip.8.211.5.139) | - | - | High
7 | [35.246.189.253](https://vuldb.com/?ip.35.246.189.253) | 253.189.246.35.bc.googleusercontent.com | - | Medium
8 | [37.59.47.208](https://vuldb.com/?ip.37.59.47.208) | ns3000975.ip-37-59-47.eu | - | High
9 | [45.197.141.250](https://vuldb.com/?ip.45.197.141.250) | - | - | High
10 | [47.254.169.212](https://vuldb.com/?ip.47.254.169.212) | - | - | High
11 | [47.254.170.245](https://vuldb.com/?ip.47.254.170.245) | - | - | High
12 | [47.254.175.211](https://vuldb.com/?ip.47.254.175.211) | - | - | High
13 | [51.83.209.11](https://vuldb.com/?ip.51.83.209.11) | ip11.ip-51-83-209.eu | - | High
14 | [54.38.49.244](https://vuldb.com/?ip.54.38.49.244) | ip244.ip-54-38-49.eu | - | High
15 | [62.133.58.60](https://vuldb.com/?ip.62.133.58.60) | - | - | High
16 | [74.119.239.234](https://vuldb.com/?ip.74.119.239.234) | - | - | High
17 | [76.119.1.112](https://vuldb.com/?ip.76.119.1.112) | c-76-119-1-112.hsd1.ct.comcast.net | - | High
18 | [77.246.157.133](https://vuldb.com/?ip.77.246.157.133) | test.com | - | High
19 | [80.78.249.78](https://vuldb.com/?ip.80.78.249.78) | - | - | High
20 | ... | ... | ... | ...

There are 75 more IOC items available. Please use our online service to access the data.

## TTP - Tactics, Techniques, Procedures

_Tactics, techniques, and procedures_ (TTP) summarize the suspected MITRE ATT&CK techniques used by _Magecart_. This data is unique as it uses our predictive model for actor profiling.

ID | Technique | Weakness | Description | Confidence
-- | --------- | -------- | ----------- | ----------
1 | T1006 | CWE-21, CWE-22, CWE-23, CWE-24, CWE-28, CWE-36 | Pathname Traversal | High
2 | T1040 | CWE-294, CWE-319 | Authentication Bypass by Capture-replay | High
3 | T1055 | CWE-74 | Injection | High
4 | T1059 | CWE-94 | Cross Site Scripting | High
5 | T1059.007 | CWE-79, CWE-80 | Cross Site Scripting | High
6 | ... | ... | ... | ...

There are 22 more TTP items available. Please use our online service to access the data.

## IOA - Indicator of Attack

These _indicators of attack_ (IOA) list the potential fragments used for technical activities like reconnaissance, exploitation, privilege escalation, and exfiltration by Magecart. This data is unique as it uses our predictive model for actor profiling.

ID | Type | Indicator | Confidence
-- | ---- | --------- | ----------
1 | File | `/?p=products` | Medium
2 | File | `/admin.php/accessory/filesdel.html` | High
3 | File | `/admin.php?c=upload&f=zip&_noCache=0.1683794968` | High
4 | File | `/admin/?page=user/manage` | High
5 | File | `/admin/add-new.php` | High
6 | File | `/admin/admin.php` | High
7 | File | `/admin/curriculum/view_curriculum.php` | High
8 | File | `/admin/doctors.php` | High
9 | File | `/admin/login.php` | High
10 | File | `/admin/products/manage_product.php` | High
11 | File | `/admin/products/view_product.php` | High
12 | File | `/admin/report/index.php` | High
13 | File | `/admin/sales/manage_sale.php` | High
14 | File | `/admin/suppliers/view_details.php` | High
15 | File | `/alphaware/summary.php` | High
16 | File | `/api/` | Low
17 | File | `/api/admin/store/product/list` | High
18 | File | `/api/stl/actions/search` | High
19 | File | `/api/v2/cli/commands` | High
20 | File | `/attachments` | Medium
21 | File | `/boat/login.php` | High
22 | File | `/bsms_ci/index.php/book` | High
23 | File | `/cgi-bin` | Medium
24 | File | `/cgi-bin/wlogin.cgi` | High
25 | File | `/classes/Master.php?f=delete_service` | High
26 | File | `/classes/Users.php` | High
27 | File | `/debug/pprof` | Medium
28 | File | `/E-mobile/App/System/File/downfile.php` | High
29 | File | `/etc/hosts` | Medium
30 | File | `/etc/os-release` | High
31 | File | `/forum/away.php` | High
32 | File | `/goform/addUserName` | High
33 | File | `/goForm/aspForm` | High
34 | File | `/goform/form2WizardStep4` | High
35 | File | `/goform/formSetEmail` | High
36 | File | `/goform/WifiBasicSet` | High
37 | File | `/hprms/admin/rooms/view_room.php` | High
38 | File | `/hrm/controller/employee.php` | High
39 | File | `/hrm/controller/login.php` | High
40 | File | `/hss/?page=categories` | High
41 | File | `/inc/parser/xhtml.php` | High
42 | File | `/inc/topBarNav.php` | High
43 | File | `/index.php?app=main&func=passport&action=login` | High
44 | File | `/index/user/upload_img.html` | High
45 | File | `/js/player/dmplayer/dmku/index.php` | High
46 | File | `/medicines/profile.php` | High
47 | File | `/mgm_dev_upgrade.asp` | High
48 | File | `/mgm_log_cfg.asp` | High
49 | ... | ... | ...

There are 428 more IOA items available (file, library, argument, input value, pattern, network port). Please use our online service to access the data.

## References

The following list contains _external sources_ which discuss the actor and the associated activities:

* https://blog.bushidotoken.net/2020/08/analysis-of-recent-magecart-campaign.html
* https://blog.bushidotoken.net/2020/12/analysis-of-meyhod-javascript-web.html
* https://blog.bushidotoken.net/2021/04/mo-money-mo-magecart.html
* https://blog.malwarebytes.com/threat-intelligence/2021/09/the-many-tentacles-of-magecart-group-8/
* https://blog.malwarebytes.com/threat-intelligence/2022/06/client-side-magecart-attacks-still-around-but-more-covert/
* https://community.blueliv.com/#!/s/614c62f382df414169331f64
* https://github.com/blackorbird/APT_REPORT/tree/master/Magecart

## Literature

The following _articles_ explain our unique predictive cyber threat intelligence:

* [VulDB Cyber Threat Intelligence Documentation](https://vuldb.com/?kb.cti)
* [Cyber Threat Intelligence - Early Anticipation of Attacks](https://www.scip.ch/en/?labs.20201022)

## License

(c) [1997-2023](https://vuldb.com/?kb.changelog) by [vuldb.com](https://vuldb.com/?kb.about). All data on this page is shared under the license [CC BY-NC-SA 4.0](https://creativecommons.org/licenses/by-nc-sa/4.0/). Questions? Check the [FAQ](https://vuldb.com/?kb.faq), read the [documentation](https://vuldb.com/?kb) or [contact us](https://vuldb.com/?contact)!
