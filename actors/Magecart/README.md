# Magecart - Cyber Threat Intelligence

These _indicators_ were reported, collected, and generated during the [VulDB CTI analysis](https://vuldb.com/?kb.cti) of the actor known as [Magecart](https://vuldb.com/?actor.magecart). The _activity monitoring_ correlates data from social media, forums, chat rooms, and darknet markets. It helps to determine associated actors, specific activities, expected intentions, emerging research, and ongoing attacks. Our unique _predictive model_ uses _big data_ to forecast activities and their characteristics.

_Live data_ and more _analysis capabilities_ are available at [https://vuldb.com/?actor.magecart](https://vuldb.com/?actor.magecart)

## Countries

These _countries_ are directly (e.g. origin of attacks) or indirectly (e.g. access by proxy) associated with Magecart:

* [ES](https://vuldb.com/?country.es)
* [CN](https://vuldb.com/?country.cn)
* [RU](https://vuldb.com/?country.ru)
* ...

There are 13 more country items available. Please use our online service to access the data.

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
2 | T1055 | CWE-74 | Injection | High
3 | T1059 | CWE-88, CWE-94 | Cross Site Scripting | High
4 | T1059.007 | CWE-79, CWE-80 | Cross Site Scripting | High
5 | T1068 | CWE-264, CWE-269, CWE-272, CWE-284 | Execution with Unnecessary Privileges | High
6 | ... | ... | ... | ...

There are 18 more TTP items available. Please use our online service to access the data.

## IOA - Indicator of Attack

These _indicators of attack_ (IOA) list the potential fragments used for technical activities like reconnaissance, exploitation, privilege escalation, and exfiltration by Magecart. This data is unique as it uses our predictive model for actor profiling.

ID | Type | Indicator | Confidence
-- | ---- | --------- | ----------
1 | File | `/admin/image.php` | High
2 | File | `/admin/js` | Medium
3 | File | `/ad_js.php` | Medium
4 | File | `/app/options.py` | High
5 | File | `/bin/png2swf` | Medium
6 | File | `/bin/posix/src/ports/POSIX/OpENer` | High
7 | File | `/conf/` | Low
8 | File | `/dashboard/reports/logs/view` | High
9 | File | `/debian/patches/load_ppp_generic_if_needed` | High
10 | File | `/etc/hosts` | Medium
11 | File | `/frm/` | Low
12 | File | `/goform/WifiMacFilterSet` | High
13 | File | `/home/www/cgi-bin/diagnostics.cgi` | High
14 | File | `/htmldoc/htmldoc/html.cxx` | High
15 | File | `/include/comm_post.inc.php` | High
16 | File | `/index.php` | Medium
17 | File | `/jpeg-quantsmooth/jpegqs` | High
18 | File | `/linux/main.cpp` | High
19 | File | `/modules/caddyhttp/rewrite/rewrite.go` | High
20 | File | `/pages/class_sched.php` | High
21 | File | `/php_action/createUser.php` | High
22 | File | `/pkg/util` | Medium
23 | File | `/pms/index.php` | High
24 | File | `/proc/<PID>/mem` | High
25 | File | `/release-x64/otfccdump` | High
26 | File | `/secure/ViewCollectors` | High
27 | File | `/services/v4/invoiceImg` | High
28 | File | `/stdio-common/vfprintf.c` | High
29 | File | `/tmp/tardiff-$` | High
30 | File | `/upload` | Low
31 | File | `/usr/local/sbin/webproject/set_param.cgi` | High
32 | File | `/var/log/qualys/qualys-cloud-agent-scan.log` | High
33 | File | `/vendor/views/add_product.php` | High
34 | File | `/wabt/bin/poc.wasm` | High
35 | File | `/xpdf/Stream.cc` | High
36 | File | `addinterviewsform.php` | High
37 | File | `addmembioform.php` | High
38 | File | `adm.cgi` | Low
39 | File | `admin.php` | Medium
40 | File | `admin.php3` | Medium
41 | File | `admin/detay_yorum.asp` | High
42 | File | `admin/header.php` | High
43 | File | `admin/manufacturers.php` | High
44 | File | `Admin/Staff` | Medium
45 | ... | ... | ...

There are 392 more IOA items available (file, library, argument, input value, pattern, network port). Please use our online service to access the data.

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
