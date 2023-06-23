# pupy - Cyber Threat Intelligence

These _indicators_ were reported, collected, and generated during the [VulDB CTI analysis](https://vuldb.com/?kb.cti) of the actor known as [pupy](https://vuldb.com/?actor.pupy). The _activity monitoring_ correlates data from social media, forums, chat rooms, and darknet markets. It helps to determine associated actors, specific activities, expected intentions, emerging research, and ongoing attacks. Our unique _predictive model_ uses _big data_ to forecast activities and their characteristics.

_Live data_ and more _analysis capabilities_ are available at [https://vuldb.com/?actor.pupy](https://vuldb.com/?actor.pupy)

## Countries

These _countries_ are directly (e.g. origin of attacks) or indirectly (e.g. access by proxy) associated with pupy:

* [CN](https://vuldb.com/?country.cn)
* [US](https://vuldb.com/?country.us)
* [HK](https://vuldb.com/?country.hk)
* ...

There are 6 more country items available. Please use our online service to access the data.

## IOC - Indicator of Compromise

These _indicators of compromise_ (IOC) indicate associated network resources which are known to be part of research and attack activities of pupy.

ID | IP address | Hostname | Campaign | Confidence
-- | ---------- | -------- | -------- | ----------
1 | [1.12.69.102](https://vuldb.com/?ip.1.12.69.102) | - | - | High
2 | [8.210.107.120](https://vuldb.com/?ip.8.210.107.120) | - | - | High
3 | [8.210.141.104](https://vuldb.com/?ip.8.210.141.104) | - | - | High
4 | [13.215.175.44](https://vuldb.com/?ip.13.215.175.44) | ec2-13-215-175-44.ap-southeast-1.compute.amazonaws.com | - | Medium
5 | [16.163.43.4](https://vuldb.com/?ip.16.163.43.4) | ec2-16-163-43-4.ap-east-1.compute.amazonaws.com | - | Medium
6 | [18.163.105.206](https://vuldb.com/?ip.18.163.105.206) | ec2-18-163-105-206.ap-east-1.compute.amazonaws.com | - | Medium
7 | [18.163.180.135](https://vuldb.com/?ip.18.163.180.135) | ec2-18-163-180-135.ap-east-1.compute.amazonaws.com | - | Medium
8 | [18.167.13.235](https://vuldb.com/?ip.18.167.13.235) | ec2-18-167-13-235.ap-east-1.compute.amazonaws.com | - | Medium
9 | [34.84.185.40](https://vuldb.com/?ip.34.84.185.40) | 40.185.84.34.bc.googleusercontent.com | - | Medium
10 | [34.92.235.56](https://vuldb.com/?ip.34.92.235.56) | 56.235.92.34.bc.googleusercontent.com | - | Medium
11 | [35.201.196.246](https://vuldb.com/?ip.35.201.196.246) | 246.196.201.35.bc.googleusercontent.com | - | Medium
12 | [35.220.154.238](https://vuldb.com/?ip.35.220.154.238) | 238.154.220.35.bc.googleusercontent.com | - | Medium
13 | [35.241.106.118](https://vuldb.com/?ip.35.241.106.118) | 118.106.241.35.bc.googleusercontent.com | - | Medium
14 | [38.54.40.25](https://vuldb.com/?ip.38.54.40.25) | - | - | High
15 | [39.98.206.63](https://vuldb.com/?ip.39.98.206.63) | - | - | High
16 | [39.107.32.219](https://vuldb.com/?ip.39.107.32.219) | - | - | High
17 | [41.147.195.62](https://vuldb.com/?ip.41.147.195.62) | 8ta-147-195-62.telkomadsl.co.za | - | High
18 | ... | ... | ... | ...

There are 69 more IOC items available. Please use our online service to access the data.

## TTP - Tactics, Techniques, Procedures

_Tactics, techniques, and procedures_ (TTP) summarize the suspected MITRE ATT&CK techniques used by _pupy_. This data is unique as it uses our predictive model for actor profiling.

ID | Technique | Weakness | Description | Confidence
-- | --------- | -------- | ----------- | ----------
1 | T1006 | CWE-21, CWE-22, CWE-29 | Pathname Traversal | High
2 | T1040 | CWE-294 | Authentication Bypass by Capture-replay | High
3 | T1055 | CWE-74 | Injection | High
4 | T1059 | CWE-88, CWE-94, CWE-1321 | Cross Site Scripting | High
5 | T1059.007 | CWE-79, CWE-80 | Cross Site Scripting | High
6 | ... | ... | ... | ...

There are 20 more TTP items available. Please use our online service to access the data.

## IOA - Indicator of Attack

These _indicators of attack_ (IOA) list the potential fragments used for technical activities like reconnaissance, exploitation, privilege escalation, and exfiltration by pupy. This data is unique as it uses our predictive model for actor profiling.

ID | Type | Indicator | Confidence
-- | ---- | --------- | ----------
1 | File | `.kdbgrc` | Low
2 | File | `/admin.php?action=themeinstall` | High
3 | File | `/admin/?page=product/manage_product&id=2` | High
4 | File | `/admin/?setting-base.htm` | High
5 | File | `/admin/controller/JobLogController.java` | High
6 | File | `/admin/fst_upload.inc.php` | High
7 | File | `/admin/index2.html` | High
8 | File | `/admin/scripts/pi-hole/phpqueryads.php` | High
9 | File | `/admin/subnets/ripe-query.php` | High
10 | File | `/admin/update_currency.php` | High
11 | File | `/api/audits` | Medium
12 | File | `/api/resource/Item?fields` | High
13 | File | `/api/upload.php` | High
14 | File | `/api/v1/attack/token` | High
15 | File | `/application/common.php#action_log` | High
16 | File | `/APR/signup.php` | High
17 | File | `/baseOpLog.do` | High
18 | File | `/bin/ate` | Medium
19 | File | `/bitrix/admin/ldap_server_edit.php` | High
20 | File | `/cgi-bin/activate.cgi` | High
21 | File | `/cgi-bin/cstecgi.cgi` | High
22 | File | `/cgi-bin/kerbynet` | High
23 | File | `/cgi-bin/luci/api/wireless` | High
24 | File | `/cgi-bin/wapopen` | High
25 | File | `/classes/Users.php?f=save` | High
26 | File | `/controller/OnlinePreviewController.java` | High
27 | File | `/core/conditions/AbstractWrapper.java` | High
28 | File | `/crmeb/crmeb/services/UploadService.php` | High
29 | File | `/debug/pprof` | Medium
30 | File | `/etc/sudoers` | Medium
31 | File | `/export` | Low
32 | File | `/form/index.php?module=getjson` | High
33 | File | `/forum/away.php` | High
34 | File | `/fos/admin/index.php?page=menu` | High
35 | File | `/goform/addRouting` | High
36 | File | `/goForm/aspForm` | High
37 | File | `/goform/doReboot` | High
38 | File | `/goform/form2Wan.cgi` | High
39 | File | `/HNAP1` | Low
40 | File | `/hrm/controller/employee.php` | High
41 | File | `/IISADMPWD` | Medium
42 | File | `/includes/login.php` | High
43 | File | `/index.php/archives/1/comment` | High
44 | ... | ... | ...

There are 378 more IOA items available (file, library, argument, input value, pattern, network port). Please use our online service to access the data.

## References

The following list contains _external sources_ which discuss the actor and the associated activities:

* https://search.censys.io/hosts/1.12.69.102
* https://search.censys.io/hosts/8.210.107.120
* https://search.censys.io/hosts/8.210.141.104
* https://search.censys.io/hosts/13.215.175.44
* https://search.censys.io/hosts/16.163.43.4
* https://search.censys.io/hosts/18.163.105.206
* https://search.censys.io/hosts/18.163.180.135
* https://search.censys.io/hosts/18.167.13.235
* https://search.censys.io/hosts/34.84.185.40
* https://search.censys.io/hosts/34.92.235.56
* https://search.censys.io/hosts/35.201.196.246
* https://search.censys.io/hosts/35.220.154.238
* https://search.censys.io/hosts/35.241.106.118
* https://search.censys.io/hosts/38.54.40.25
* https://search.censys.io/hosts/39.98.206.63
* https://search.censys.io/hosts/39.107.32.219
* https://search.censys.io/hosts/41.147.195.62
* https://search.censys.io/hosts/41.147.198.28
* https://search.censys.io/hosts/43.139.167.131
* https://search.censys.io/hosts/43.154.112.87
* https://search.censys.io/hosts/43.155.117.195
* https://search.censys.io/hosts/45.8.159.245
* https://search.censys.io/hosts/45.77.41.141
* https://search.censys.io/hosts/45.79.134.104
* https://search.censys.io/hosts/45.156.185.125
* https://search.censys.io/hosts/49.233.9.106
* https://search.censys.io/hosts/52.70.252.57
* https://search.censys.io/hosts/54.156.169.56
* https://search.censys.io/hosts/62.234.32.192
* https://search.censys.io/hosts/65.20.66.221
* https://search.censys.io/hosts/66.42.59.191
* https://search.censys.io/hosts/92.118.189.178
* https://search.censys.io/hosts/93.90.72.13
* https://search.censys.io/hosts/95.216.206.17
* https://search.censys.io/hosts/102.248.4.140
* https://search.censys.io/hosts/103.13.229.67
* https://search.censys.io/hosts/103.13.231.34
* https://search.censys.io/hosts/103.27.186.185
* https://search.censys.io/hosts/103.51.145.45
* https://search.censys.io/hosts/103.79.76.40
* https://search.censys.io/hosts/103.140.187.137
* https://search.censys.io/hosts/104.156.232.19
* https://search.censys.io/hosts/104.168.163.200
* https://search.censys.io/hosts/107.152.44.191
* https://search.censys.io/hosts/108.61.242.65
* https://search.censys.io/hosts/111.9.220.114
* https://search.censys.io/hosts/111.230.42.99
* https://search.censys.io/hosts/111.231.2.20
* https://search.censys.io/hosts/116.204.126.15
* https://search.censys.io/hosts/120.55.170.180
* https://search.censys.io/hosts/121.37.191.11
* https://search.censys.io/hosts/124.221.75.139
* https://search.censys.io/hosts/134.122.39.118
* https://search.censys.io/hosts/134.209.101.105
* https://search.censys.io/hosts/136.244.65.241
* https://search.censys.io/hosts/136.244.98.14
* https://search.censys.io/hosts/137.184.219.41
* https://search.censys.io/hosts/139.84.140.110
* https://search.censys.io/hosts/139.84.140.157
* https://search.censys.io/hosts/139.84.142.187
* https://search.censys.io/hosts/139.180.131.241
* https://search.censys.io/hosts/139.180.188.45
* https://search.censys.io/hosts/143.42.74.25
* https://search.censys.io/hosts/149.28.19.155
* https://search.censys.io/hosts/149.248.34.178
* https://search.censys.io/hosts/154.3.34.146
* https://search.censys.io/hosts/154.202.59.51
* https://search.censys.io/hosts/154.202.59.107
* https://search.censys.io/hosts/154.202.59.148
* https://search.censys.io/hosts/154.202.59.194
* https://search.censys.io/hosts/157.245.155.179
* https://search.censys.io/hosts/165.22.185.138
* https://search.censys.io/hosts/165.232.160.68
* https://search.censys.io/hosts/168.100.11.126
* https://search.censys.io/hosts/172.104.122.152
* https://search.censys.io/hosts/181.215.68.173
* https://search.censys.io/hosts/192.169.7.17
* https://search.censys.io/hosts/195.80.151.57
* https://search.censys.io/hosts/199.247.24.153
* https://search.censys.io/hosts/202.102.36.252
* https://search.censys.io/hosts/202.182.106.252
* https://search.censys.io/hosts/203.86.236.93
* https://search.censys.io/hosts/206.189.44.250
* https://search.censys.io/hosts/207.148.99.121
* https://search.censys.io/hosts/212.115.55.53
* https://search.censys.io/hosts/217.195.153.13

## Literature

The following _articles_ explain our unique predictive cyber threat intelligence:

* [VulDB Cyber Threat Intelligence Documentation](https://vuldb.com/?kb.cti)
* [Cyber Threat Intelligence - Early Anticipation of Attacks](https://www.scip.ch/en/?labs.20201022)

## License

(c) [1997-2023](https://vuldb.com/?kb.changelog) by [vuldb.com](https://vuldb.com/?kb.about). All data on this page is shared under the license [CC BY-NC-SA 4.0](https://creativecommons.org/licenses/by-nc-sa/4.0/). Questions? Check the [FAQ](https://vuldb.com/?kb.faq), read the [documentation](https://vuldb.com/?kb) or [contact us](https://vuldb.com/?contact)!
