# Magecart - Cyber Threat Intelligence

These _indicators_ were reported, collected, and generated during the [VulDB CTI analysis](https://vuldb.com/?kb.cti) of the actor known as [Magecart](https://vuldb.com/?actor.magecart). The _activity monitoring_ correlates data from social media, forums, chat rooms, and darknet markets. It helps to determine associated actors, specific activities, expected intentions, emerging research, and ongoing attacks. Our unique _predictive model_ uses _big data_ to forecast activities and their characteristics.

_Live data_ and more _analysis capabilities_ are available at [https://vuldb.com/?actor.magecart](https://vuldb.com/?actor.magecart)

## Countries

These _countries_ are directly (e.g. origin of attacks) or indirectly (e.g. access by proxy) associated with Magecart:

* [RU](https://vuldb.com/?country.ru)
* [CN](https://vuldb.com/?country.cn)
* [PT](https://vuldb.com/?country.pt)
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
1 | T1006 | CWE-21, CWE-22, CWE-23 | Pathname Traversal | High
2 | T1040 | CWE-294 | Authentication Bypass by Capture-replay | High
3 | T1055 | CWE-74 | Injection | High
4 | T1059 | CWE-88, CWE-94, CWE-1321 | Cross Site Scripting | High
5 | ... | ... | ... | ...

There are 18 more TTP items available. Please use our online service to access the data.

## IOA - Indicator of Attack

These _indicators of attack_ (IOA) list the potential fragments used for technical activities like reconnaissance, exploitation, privilege escalation, and exfiltration by Magecart. This data is unique as it uses our predictive model for actor profiling.

ID | Type | Indicator | Confidence
-- | ---- | --------- | ----------
1 | File | `/about.php` | Medium
2 | File | `/admin/changestock.php` | High
3 | File | `/admin/contact/list` | High
4 | File | `/admin/delete.php` | High
5 | File | `/admin/edit_visitor.php` | High
6 | File | `/admin/image.php` | High
7 | File | `/admin/modify.php` | High
8 | File | `/admin/settings/fields` | High
9 | File | `/ad_js.php` | Medium
10 | File | `/api/` | Low
11 | File | `/api/plugin/uninstall` | High
12 | File | `/bin/httpd` | Medium
13 | File | `/bin/png2swf` | Medium
14 | File | `/blogengine/api/posts` | High
15 | File | `/brand.php` | Medium
16 | File | `/cgi-bin/luci/api/wireless` | High
17 | File | `/classes/Master.php?f=delete_item` | High
18 | File | `/classes/Master.php?f=delete_stockin` | High
19 | File | `/classes/Master.php?f=delete_student` | High
20 | File | `/conf/users` | Medium
21 | File | `/controller/OnlinePreviewController.java` | High
22 | File | `/coreframe/app/attachment/admin/index.php` | High
23 | File | `/debian/patches/load_ppp_generic_if_needed` | High
24 | File | `/debug/pprof` | Medium
25 | File | `/etc/ciel.cfg` | High
26 | File | `/etc/init0.d/S80telnetd.sh` | High
27 | File | `/etc/shadow.sample` | High
28 | File | `/frm/` | Low
29 | File | `/goform/setmac` | High
30 | File | `/goform/WifiMacFilterSet` | High
31 | File | `/home/www/cgi-bin/diagnostics.cgi` | High
32 | File | `/htmldoc/htmldoc/html.cxx` | High
33 | File | `/include/comm_post.inc.php` | High
34 | File | `/index.php` | Medium
35 | File | `/jpeg-quantsmooth/jpegqs` | High
36 | File | `/linux/main.cpp` | High
37 | File | `/manage-apartment.php` | High
38 | File | `/pages/apply_vacancy.php` | High
39 | File | `/pages/class_sched.php` | High
40 | File | `/pages/processlogin.php` | High
41 | File | `/publiccms/admin/ueditor` | High
42 | File | `/release-x64/otfccdump` | High
43 | File | `/release-x64/otfccdump+0x6e420d` | High
44 | ... | ... | ...

There are 379 more IOA items available (file, library, argument, input value, pattern, network port). Please use our online service to access the data.

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

(c) [1997-2022](https://vuldb.com/?kb.changelog) by [vuldb.com](https://vuldb.com/?kb.about). All data on this page is shared under the license [CC BY-NC-SA 4.0](https://creativecommons.org/licenses/by-nc-sa/4.0/). Questions? Check the [FAQ](https://vuldb.com/?kb.faq), read the [documentation](https://vuldb.com/?kb) or [contact us](https://vuldb.com/?contact)!
