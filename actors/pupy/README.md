# pupy - Cyber Threat Intelligence

These _indicators_ were reported, collected, and generated during the [VulDB CTI analysis](https://vuldb.com/?kb.cti) of the actor known as [pupy](https://vuldb.com/?actor.pupy). The _activity monitoring_ correlates data from social media, forums, chat rooms, and darknet markets. It helps to determine associated actors, specific activities, expected intentions, emerging research, and ongoing attacks. Our unique _predictive model_ uses _big data_ to forecast activities and their characteristics.

_Live data_ and more _analysis capabilities_ are available at [https://vuldb.com/?actor.pupy](https://vuldb.com/?actor.pupy)

## Countries

These _countries_ are directly (e.g. origin of attacks) or indirectly (e.g. access by proxy) associated with pupy:

* [CN](https://vuldb.com/?country.cn)
* [US](https://vuldb.com/?country.us)
* [DE](https://vuldb.com/?country.de)
* ...

There are 4 more country items available. Please use our online service to access the data.

## IOC - Indicator of Compromise

These _indicators of compromise_ (IOC) indicate associated network resources which are known to be part of research and attack activities of pupy.

ID | IP address | Hostname | Campaign | Confidence
-- | ---------- | -------- | -------- | ----------
1 | [8.210.107.120](https://vuldb.com/?ip.8.210.107.120) | - | - | High
2 | [8.210.141.104](https://vuldb.com/?ip.8.210.141.104) | - | - | High
3 | [13.215.175.44](https://vuldb.com/?ip.13.215.175.44) | ec2-13-215-175-44.ap-southeast-1.compute.amazonaws.com | - | Medium
4 | [16.163.43.4](https://vuldb.com/?ip.16.163.43.4) | ec2-16-163-43-4.ap-east-1.compute.amazonaws.com | - | Medium
5 | [18.167.13.235](https://vuldb.com/?ip.18.167.13.235) | ec2-18-167-13-235.ap-east-1.compute.amazonaws.com | - | Medium
6 | [34.84.185.40](https://vuldb.com/?ip.34.84.185.40) | 40.185.84.34.bc.googleusercontent.com | - | Medium
7 | [34.92.235.56](https://vuldb.com/?ip.34.92.235.56) | 56.235.92.34.bc.googleusercontent.com | - | Medium
8 | [35.201.196.246](https://vuldb.com/?ip.35.201.196.246) | 246.196.201.35.bc.googleusercontent.com | - | Medium
9 | [35.220.154.238](https://vuldb.com/?ip.35.220.154.238) | 238.154.220.35.bc.googleusercontent.com | - | Medium
10 | [35.241.106.118](https://vuldb.com/?ip.35.241.106.118) | 118.106.241.35.bc.googleusercontent.com | - | Medium
11 | [39.98.206.63](https://vuldb.com/?ip.39.98.206.63) | - | - | High
12 | [41.147.195.62](https://vuldb.com/?ip.41.147.195.62) | 8ta-147-195-62.telkomadsl.co.za | - | High
13 | ... | ... | ... | ...

There are 48 more IOC items available. Please use our online service to access the data.

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
5 | File | `/admin/addemployee.php` | High
6 | File | `/admin/controller/JobLogController.java` | High
7 | File | `/admin/index2.html` | High
8 | File | `/admin/scripts/pi-hole/phpqueryads.php` | High
9 | File | `/admin/subnets/ripe-query.php` | High
10 | File | `/admin/update_currency.php` | High
11 | File | `/api/` | Low
12 | File | `/api/audits` | Medium
13 | File | `/api/resource/Item?fields` | High
14 | File | `/api/v1/attack/token` | High
15 | File | `/Application/Admin/Controller/ConfigController.class.php` | High
16 | File | `/APR/signup.php` | High
17 | File | `/assets` | Low
18 | File | `/cgi-bin/activate.cgi` | High
19 | File | `/cgi-bin/kerbynet` | High
20 | File | `/cgi-bin/luci/api/wireless` | High
21 | File | `/cgi-bin/wapopen` | High
22 | File | `/cgi-bin/wlogin.cgi` | High
23 | File | `/context/%2e/WEB-INF/web.xml` | High
24 | File | `/controller/OnlinePreviewController.java` | High
25 | File | `/core/conditions/AbstractWrapper.java` | High
26 | File | `/crmeb/crmeb/services/UploadService.php` | High
27 | File | `/dashboard/snapshot/*?orgId=0` | High
28 | File | `/debug/pprof` | Medium
29 | File | `/etc/sudoers` | Medium
30 | File | `/export` | Low
31 | File | `/form/index.php?module=getjson` | High
32 | File | `/forum/away.php` | High
33 | File | `/fos/admin/index.php?page=menu` | High
34 | File | `/gaia-job-admin/user/add` | High
35 | File | `/goform/addRouting` | High
36 | File | `/goform/doReboot` | High
37 | File | `/goform/form2Wan.cgi` | High
38 | File | `/hrm/controller/employee.php` | High
39 | File | `/IISADMPWD` | Medium
40 | File | `/includes/login.php` | High
41 | ... | ... | ...

There are 349 more IOA items available (file, library, argument, input value, pattern, network port). Please use our online service to access the data.

## References

The following list contains _external sources_ which discuss the actor and the associated activities:

* https://search.censys.io/hosts/8.210.107.120
* https://search.censys.io/hosts/8.210.141.104
* https://search.censys.io/hosts/13.215.175.44
* https://search.censys.io/hosts/16.163.43.4
* https://search.censys.io/hosts/18.167.13.235
* https://search.censys.io/hosts/34.84.185.40
* https://search.censys.io/hosts/34.92.235.56
* https://search.censys.io/hosts/35.201.196.246
* https://search.censys.io/hosts/35.220.154.238
* https://search.censys.io/hosts/35.241.106.118
* https://search.censys.io/hosts/39.98.206.63
* https://search.censys.io/hosts/41.147.195.62
* https://search.censys.io/hosts/43.139.167.131
* https://search.censys.io/hosts/43.154.112.87
* https://search.censys.io/hosts/43.155.117.195
* https://search.censys.io/hosts/45.8.159.245
* https://search.censys.io/hosts/45.77.41.141
* https://search.censys.io/hosts/45.79.134.104
* https://search.censys.io/hosts/49.233.9.106
* https://search.censys.io/hosts/54.156.169.56
* https://search.censys.io/hosts/92.118.189.178
* https://search.censys.io/hosts/95.216.206.17
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
* https://search.censys.io/hosts/134.122.39.118
* https://search.censys.io/hosts/134.209.101.105
* https://search.censys.io/hosts/136.244.65.241
* https://search.censys.io/hosts/139.84.140.110
* https://search.censys.io/hosts/139.180.131.241
* https://search.censys.io/hosts/143.42.74.25
* https://search.censys.io/hosts/149.28.19.155
* https://search.censys.io/hosts/149.248.34.178
* https://search.censys.io/hosts/154.3.34.146
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
* https://search.censys.io/hosts/212.115.55.53
* https://search.censys.io/hosts/217.195.153.13

## Literature

The following _articles_ explain our unique predictive cyber threat intelligence:

* [VulDB Cyber Threat Intelligence Documentation](https://vuldb.com/?kb.cti)
* [Cyber Threat Intelligence - Early Anticipation of Attacks](https://www.scip.ch/en/?labs.20201022)

## License

(c) [1997-2023](https://vuldb.com/?kb.changelog) by [vuldb.com](https://vuldb.com/?kb.about). All data on this page is shared under the license [CC BY-NC-SA 4.0](https://creativecommons.org/licenses/by-nc-sa/4.0/). Questions? Check the [FAQ](https://vuldb.com/?kb.faq), read the [documentation](https://vuldb.com/?kb) or [contact us](https://vuldb.com/?contact)!
