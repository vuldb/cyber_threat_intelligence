# Kaiji - Cyber Threat Intelligence

These _indicators_ were reported, collected, and generated during the [VulDB CTI analysis](https://vuldb.com/?kb.cti) of the actor known as [Kaiji](https://vuldb.com/?actor.kaiji). The _activity monitoring_ correlates data from social media, forums, chat rooms, and darknet markets. It helps to determine associated actors, specific activities, expected intentions, emerging research, and ongoing attacks. Our unique _predictive model_ uses _big data_ to forecast activities and their characteristics.

_Live data_ and more _analysis capabilities_ are available at [https://vuldb.com/?actor.kaiji](https://vuldb.com/?actor.kaiji)

## Countries

These _countries_ are directly (e.g. origin of attacks) or indirectly (e.g. access by proxy) associated with Kaiji:

* [US](https://vuldb.com/?country.us)
* [LU](https://vuldb.com/?country.lu)
* [CN](https://vuldb.com/?country.cn)
* ...

There are 15 more country items available. Please use our online service to access the data.

## IOC - Indicator of Compromise

These _indicators of compromise_ (IOC) indicate associated network resources which are known to be part of research and attack activities of Kaiji.

ID | IP address | Hostname | Campaign | Confidence
-- | ---------- | -------- | -------- | ----------
1 | [5.255.111.128](https://vuldb.com/?ip.5.255.111.128) | - | - | High
2 | [13.228.173.120](https://vuldb.com/?ip.13.228.173.120) | ec2-13-228-173-120.ap-southeast-1.compute.amazonaws.com | - | Medium
3 | [20.2.144.116](https://vuldb.com/?ip.20.2.144.116) | - | - | High
4 | [20.187.86.47](https://vuldb.com/?ip.20.187.86.47) | - | - | High
5 | [20.239.156.147](https://vuldb.com/?ip.20.239.156.147) | - | - | High
6 | [23.94.57.167](https://vuldb.com/?ip.23.94.57.167) | 23-94-57-167-host.colocrossing.com | - | High
7 | [23.224.85.39](https://vuldb.com/?ip.23.224.85.39) | - | - | High
8 | [23.224.121.29](https://vuldb.com/?ip.23.224.121.29) | - | - | High
9 | [23.224.143.170](https://vuldb.com/?ip.23.224.143.170) | - | - | High
10 | [36.152.201.67](https://vuldb.com/?ip.36.152.201.67) | - | - | High
11 | [38.150.13.6](https://vuldb.com/?ip.38.150.13.6) | - | - | High
12 | [38.242.220.166](https://vuldb.com/?ip.38.242.220.166) | vmi1390334.contaboserver.net | - | High
13 | ... | ... | ... | ...

There are 47 more IOC items available. Please use our online service to access the data.

## TTP - Tactics, Techniques, Procedures

_Tactics, techniques, and procedures_ (TTP) summarize the suspected MITRE ATT&CK techniques used by _Kaiji_. This data is unique as it uses our predictive model for actor profiling.

ID | Technique | Weakness | Description | Confidence
-- | --------- | -------- | ----------- | ----------
1 | T1006 | CWE-21, CWE-22, CWE-23, CWE-24, CWE-425 | Path Traversal | High
2 | T1040 | CWE-319 | Authentication Bypass by Capture-replay | High
3 | T1055 | CWE-74 | Improper Neutralization of Data within XPath Expressions | High
4 | T1059 | CWE-88, CWE-94 | Argument Injection | High
5 | T1059.007 | CWE-79, CWE-80 | Cross Site Scripting | High
6 | ... | ... | ... | ...

There are 21 more TTP items available. Please use our online service to access the data.

## IOA - Indicator of Attack

These _indicators of attack_ (IOA) list the potential fragments used for technical activities like reconnaissance, exploitation, privilege escalation, and exfiltration by Kaiji. This data is unique as it uses our predictive model for actor profiling.

ID | Type | Indicator | Confidence
-- | ---- | --------- | ----------
1 | File | `./clients/client` | High
2 | File | `/?import` | Medium
3 | File | `/addNotifyServlet` | High
4 | File | `/admin/ajax.php?action=delete_user` | High
5 | File | `/admin/booking-bwdates-reports-details.php` | High
6 | File | `/Admin/createClass.php` | High
7 | File | `/admin/maintenance/manage_brand.php` | High
8 | File | `/admin/manage-users.php` | High
9 | File | `/Admin/user-record.php` | High
10 | File | `/alsdemo/ss/mediam.cgi` | High
11 | File | `/api/admin/user?id` | High
12 | File | `/api/authentication/login` | High
13 | File | `/api/document/<DocumentID>/attachments` | High
14 | File | `/api/notify.php` | High
15 | File | `/api/v1/terminal/sessions/?limit=1` | High
16 | File | `/api/v2/cli/commands` | High
17 | File | `/application/index/common.php` | High
18 | File | `/apply.cgi` | Medium
19 | File | `/apps/system/router/upload.go` | High
20 | File | `/asan/asan_interceptors_memintrinsics.cpp` | High
21 | File | `/boaform/admin/formPing` | High
22 | File | `/bsms_ci/index.php/book` | High
23 | File | `/card_scan.php` | High
24 | File | `/cgi-bin/touchlist_sync.cgi` | High
25 | File | `/cgi-bin/uploadAccessCodePic` | High
26 | File | `/classes/conf/db.properties&config=filemanager.config.js` | High
27 | File | `/classes/Login.php` | High
28 | File | `/classes/Users.php?f=delete` | High
29 | File | `/config/getuser` | High
30 | File | `/Controllers/ClientController.php` | High
31 | File | `/cupseasylive/stockissuancelist.php` | High
32 | File | `/cupseasylive/unitofmeasurementmodify.php` | High
33 | File | `/dashboard/add-service.php` | High
34 | File | `/de2api/engine/getEngine.js` | High
35 | File | `/debug/pprof` | Medium
36 | File | `/deleteTicket.php` | High
37 | File | `/Electron/download` | High
38 | File | `/expense_action.php` | High
39 | File | `/filemanager/php/connector.php` | High
40 | File | `/forum/away.php` | High
41 | File | `/gasmark/assets/myimages/oneWord.php` | High
42 | File | `/goform/aspForm` | High
43 | File | `/goform/exeCommand` | High
44 | File | `/goform/fromRouteStatic` | High
45 | File | `/goform/setUsbUnload` | High
46 | ... | ... | ...

There are 400 more IOA items available (file, library, argument, input value, pattern, network port). Please use our online service to access the data.

## References

The following list contains _external sources_ which discuss the actor and the associated activities:

* https://bazaar.abuse.ch/sample/0defd338d2eccc8b865398e038696a1138743631a25b3627b48db3ea40d99460/
* https://bazaar.abuse.ch/sample/0594136e357031978dc6e51bffcf41c7d85c7004be527b0777ca5623c8dc03d9/
* https://bazaar.abuse.ch/sample/7da8f553216859d9f582f69f5183373a61bf02dad9dd3fe466312bcce1a207d6/
* https://bazaar.abuse.ch/sample/7504cc47a4f678a063114be7299971ae8a016e9c520fe4243e30513844dfee69/
* https://bazaar.abuse.ch/sample/da647646cd36a3acb716b4266e9032f9c1caf555b7667e1dbe5bef89e7d2fdbb/
* https://search.censys.io/hosts/13.228.173.120
* https://search.censys.io/hosts/20.2.144.116
* https://search.censys.io/hosts/23.224.85.39
* https://search.censys.io/hosts/36.152.201.67
* https://search.censys.io/hosts/39.134.69.79
* https://search.censys.io/hosts/42.194.196.162
* https://search.censys.io/hosts/83.229.120.164
* https://search.censys.io/hosts/98.159.100.118
* https://search.censys.io/hosts/103.124.105.246
* https://search.censys.io/hosts/108.181.228.101
* https://search.censys.io/hosts/117.158.206.150
* https://search.censys.io/hosts/119.6.239.18
* https://search.censys.io/hosts/119.6.239.68
* https://search.censys.io/hosts/119.6.239.80
* https://search.censys.io/hosts/119.6.239.81
* https://search.censys.io/hosts/119.6.239.82
* https://search.censys.io/hosts/119.6.239.83
* https://search.censys.io/hosts/123.99.201.37
* https://search.censys.io/hosts/123.249.86.77
* https://search.censys.io/hosts/123.249.104.74
* https://search.censys.io/hosts/149.115.234.35
* https://search.censys.io/hosts/149.115.234.54
* https://search.censys.io/hosts/149.115.234.80
* https://search.censys.io/hosts/154.37.152.123
* https://search.censys.io/hosts/154.55.139.35
* https://search.censys.io/hosts/154.82.95.210
* https://search.censys.io/hosts/154.213.192.24
* https://search.censys.io/hosts/158.101.74.227
* https://search.censys.io/hosts/173.249.198.97
* https://search.censys.io/hosts/175.24.197.196
* https://search.censys.io/hosts/182.106.149.83
* https://search.censys.io/hosts/183.249.20.106
* https://search.censys.io/hosts/192.227.146.253
* https://search.censys.io/hosts/198.98.60.49
* https://search.censys.io/hosts/199.119.138.85
* https://search.censys.io/hosts/207.211.144.153
* https://search.censys.io/hosts/209.141.35.151
* https://search.censys.io/hosts/219.128.25.2
* https://search.censys.io/hosts/223.87.225.90
* https://threatfox.abuse.ch
* https://tracker.viriback.com/index.php?q=38.150.13.6
* https://tracker.viriback.com/index.php?q=172.247.44.218
* https://urlhaus.abuse.ch/host/1.92.146.107/
* https://www.virustotal.com/gui/file/9645299e58c7521d811fbdcdbd57db45160191db7c7b73eae5d97e4530136da8/detection

## Literature

The following _articles_ explain our unique predictive cyber threat intelligence:

* [VulDB Cyber Threat Intelligence Documentation](https://vuldb.com/?kb.cti)
* [Cyber Threat Intelligence - Early Anticipation of Attacks](https://www.scip.ch/en/?labs.20201022)

## License

(c) [1997-2024](https://vuldb.com/?kb.changelog) by [vuldb.com](https://vuldb.com/?kb.about). All data on this page is shared under the license [CC BY-NC-SA 4.0](https://creativecommons.org/licenses/by-nc-sa/4.0/). Questions? Check the [FAQ](https://vuldb.com/?kb.faq), read the [documentation](https://vuldb.com/?kb) or [contact us](https://vuldb.com/?contact)!
