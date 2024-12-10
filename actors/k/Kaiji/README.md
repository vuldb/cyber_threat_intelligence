# Kaiji - Cyber Threat Intelligence

These _indicators_ were reported, collected, and generated during the [VulDB CTI analysis](https://vuldb.com/?kb.cti) of the actor known as [Kaiji](https://vuldb.com/?actor.kaiji). The _activity monitoring_ correlates data from social media, forums, chat rooms, and darknet markets. It helps to determine associated actors, specific activities, expected intentions, emerging research, and ongoing attacks. Our unique _predictive model_ uses _big data_ to forecast activities and their characteristics.

_Live data_ and more _analysis capabilities_ are available at [https://vuldb.com/?actor.kaiji](https://vuldb.com/?actor.kaiji)

## Countries

These _countries_ are directly (e.g. origin of attacks) or indirectly (e.g. access by proxy) associated with Kaiji:

* [US](https://vuldb.com/?country.us)
* [CN](https://vuldb.com/?country.cn)
* [LU](https://vuldb.com/?country.lu)
* ...

There are 25 more country items available. Please use our online service to access the data.

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
13 | [39.134.69.79](https://vuldb.com/?ip.39.134.69.79) | - | - | High
14 | [42.194.196.162](https://vuldb.com/?ip.42.194.196.162) | - | - | High
15 | ... | ... | ... | ...

There are 54 more IOC items available. Please use our online service to access the data.

## TTP - Tactics, Techniques, Procedures

_Tactics, techniques, and procedures_ (TTP) summarize the suspected MITRE ATT&CK techniques used by _Kaiji_. This data is unique as it uses our predictive model for actor profiling.

ID | Technique | Weakness | Description | Confidence
-- | --------- | -------- | ----------- | ----------
1 | T1006 | CWE-22, CWE-23, CWE-24, CWE-29, CWE-36, CWE-425 | Path Traversal | High
2 | T1055 | CWE-74, CWE-643 | Improper Neutralization of Data within XPath Expressions | High
3 | T1059 | CWE-88, CWE-94 | Argument Injection | High
4 | T1059.007 | CWE-79, CWE-80 | Cross Site Scripting | High
5 | T1068 | CWE-250, CWE-264, CWE-266, CWE-269, CWE-284 | Execution with Unnecessary Privileges | High
6 | ... | ... | ... | ...

There are 18 more TTP items available. Please use our online service to access the data.

## IOA - Indicator of Attack

These _indicators of attack_ (IOA) list the potential fragments used for technical activities like reconnaissance, exploitation, privilege escalation, and exfiltration by Kaiji. This data is unique as it uses our predictive model for actor profiling.

ID | Type | Indicator | Confidence
-- | ---- | --------- | ----------
1 | File | `/#ilang=DE&b=c_smartenergy_swgroups` | High
2 | File | `/.pomerium` | Medium
3 | File | `/?import` | Medium
4 | File | `/Account/login.php` | High
5 | File | `/admin/` | Low
6 | File | `/admin/?page=bike` | High
7 | File | `/admin/?page=musics/manage_music` | High
8 | File | `/admin/ajax.php?action=delete_user` | High
9 | File | `/admin/apply.php` | High
10 | File | `/admin/book-details.php` | High
11 | File | `/admin/booking-bwdates-reports-details.php` | High
12 | File | `/admin/bwdates-report-details.php` | High
13 | File | `/Admin/changepassword.php` | High
14 | File | `/admin/cms_content.php` | High
15 | File | `/admin/emp-profile-avatar.php` | High
16 | File | `/admin/forms/option_lists/edit.php` | High
17 | File | `/admin/general-setting` | High
18 | File | `/admin/inquiries/view_inquiry.php` | High
19 | File | `/admin/maintenance/manage_brand.php` | High
20 | File | `/admin/order.php` | High
21 | File | `/admin/products/index.php` | High
22 | File | `/admin/profile.php` | High
23 | File | `/admin/projects/{projectname}/skills/{skillname}/video` | High
24 | File | `/admin/service` | High
25 | File | `/admin/sou.php` | High
26 | File | `/Admin/user-record.php` | High
27 | File | `/admin/users.php` | High
28 | File | `/adminapi/system/crud` | High
29 | File | `/adminapi/system/file/openfile` | High
30 | File | `/admin_route/dec_service_credits.php` | High
31 | File | `/ajax.php?action=signup` | High
32 | File | `/api/admin/user?id` | High
33 | File | `/api/v1/custom_component` | High
34 | File | `/api/v4/teams//channels/deleted` | High
35 | File | `/api/wechat/app_auth` | High
36 | File | `/application/index/common.php` | High
37 | File | `/apps/system/router/upload.go` | High
38 | File | `/cancel.php` | Medium
39 | File | `/car-rental-management-system/admin/index.php?page=manage_car` | High
40 | File | `/category.php` | High
41 | File | `/cgi-bin/cstecgi.cgi` | High
42 | File | `/cgi-bin/nas_sharing.cgi` | High
43 | File | `/classes/Master.php` | High
44 | File | `/classes/Master.php?f=delete_category` | High
45 | File | `/classes/Master.php?f=save_medicine` | High
46 | File | `/classes/SystemSettings.php?f=update_settings` | High
47 | File | `/classes/Users.php?f=delete` | High
48 | File | `/control/register_case.php` | High
49 | File | `/Controllers/ClientController.php` | High
50 | File | `/curd/table/list` | High
51 | File | `/de2api/engine/getEngine.js` | High
52 | File | `/deleteTicket.php` | High
53 | File | `/devinfo` | Medium
54 | File | `/download` | Medium
55 | File | `/downloadFile.php` | High
56 | File | `/dtale/chart-data/1` | High
57 | File | `/DXR.axd` | Medium
58 | File | `/endpoint/add-folder.php` | High
59 | File | `/etc/shadow` | Medium
60 | ... | ... | ...

There are 529 more IOA items available (file, library, argument, input value, pattern, network port). Please use our online service to access the data.

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
* https://search.censys.io/hosts/103.135.101.188
* https://search.censys.io/hosts/103.178.57.159
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
* https://search.censys.io/hosts/154.12.95.219
* https://search.censys.io/hosts/154.37.152.123
* https://search.censys.io/hosts/154.55.139.35
* https://search.censys.io/hosts/154.82.95.210
* https://search.censys.io/hosts/154.213.192.24
* https://search.censys.io/hosts/158.101.74.227
* https://search.censys.io/hosts/172.247.194.226
* https://search.censys.io/hosts/172.247.194.227
* https://search.censys.io/hosts/172.247.194.228
* https://search.censys.io/hosts/172.247.194.229
* https://search.censys.io/hosts/172.247.194.230
* https://search.censys.io/hosts/173.249.198.97
* https://search.censys.io/hosts/175.24.197.196
* https://search.censys.io/hosts/182.106.149.83
* https://search.censys.io/hosts/183.249.20.106
* https://search.censys.io/hosts/192.227.146.253
* https://search.censys.io/hosts/198.98.60.49
* https://search.censys.io/hosts/199.119.138.85
* https://search.censys.io/hosts/207.211.144.153
* https://search.censys.io/hosts/209.141.35.151
* https://search.censys.io/hosts/209.141.58.104
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
