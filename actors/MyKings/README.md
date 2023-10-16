# MyKings - Cyber Threat Intelligence

These _indicators_ were reported, collected, and generated during the [VulDB CTI analysis](https://vuldb.com/?kb.cti) of the actor known as [MyKings](https://vuldb.com/?actor.mykings). The _activity monitoring_ correlates data from social media, forums, chat rooms, and darknet markets. It helps to determine associated actors, specific activities, expected intentions, emerging research, and ongoing attacks. Our unique _predictive model_ uses _big data_ to forecast activities and their characteristics.

_Live data_ and more _analysis capabilities_ are available at [https://vuldb.com/?actor.mykings](https://vuldb.com/?actor.mykings)

## Campaigns

The following _campaigns_ are known and can be associated with MyKings:

* v2

## Countries

These _countries_ are directly (e.g. origin of attacks) or indirectly (e.g. access by proxy) associated with MyKings:

* [US](https://vuldb.com/?country.us)
* [CN](https://vuldb.com/?country.cn)
* [RU](https://vuldb.com/?country.ru)
* ...

There are 24 more country items available. Please use our online service to access the data.

## IOC - Indicator of Compromise

These _indicators of compromise_ (IOC) indicate associated network resources which are known to be part of research and attack activities of MyKings.

ID | IP address | Hostname | Campaign | Confidence
-- | ---------- | -------- | -------- | ----------
1 | [5.39.222.134](https://vuldb.com/?ip.5.39.222.134) | - | - | High
2 | [13.58.133.77](https://vuldb.com/?ip.13.58.133.77) | ec2-13-58-133-77.us-east-2.compute.amazonaws.com | - | Medium
3 | [13.59.110.123](https://vuldb.com/?ip.13.59.110.123) | ec2-13-59-110-123.us-east-2.compute.amazonaws.com | - | Medium
4 | [18.191.72.35](https://vuldb.com/?ip.18.191.72.35) | ec2-18-191-72-35.us-east-2.compute.amazonaws.com | - | Medium
5 | [18.218.14.96](https://vuldb.com/?ip.18.218.14.96) | ec2-18-218-14-96.us-east-2.compute.amazonaws.com | - | Medium
6 | [18.236.135.84](https://vuldb.com/?ip.18.236.135.84) | ec2-18-236-135-84.us-west-2.compute.amazonaws.com | - | Medium
7 | [23.27.127.254](https://vuldb.com/?ip.23.27.127.254) | - | - | High
8 | [23.236.69.114](https://vuldb.com/?ip.23.236.69.114) | - | - | High
9 | [35.182.171.137](https://vuldb.com/?ip.35.182.171.137) | ec2-35-182-171-137.ca-central-1.compute.amazonaws.com | - | Medium
10 | [45.58.133.10](https://vuldb.com/?ip.45.58.133.10) | depending-tcped.landweeks.com | - | High
11 | [45.58.135.106](https://vuldb.com/?ip.45.58.135.106) | - | - | High
12 | [45.58.140.194](https://vuldb.com/?ip.45.58.140.194) | vm194.ebouravi.com | - | High
13 | [45.116.13.219](https://vuldb.com/?ip.45.116.13.219) | 45.116.13.219.static.xtom.hk | - | High
14 | [54.255.141.50](https://vuldb.com/?ip.54.255.141.50) | ec2-54-255-141-50.ap-southeast-1.compute.amazonaws.com | - | Medium
15 | [60.250.76.52](https://vuldb.com/?ip.60.250.76.52) | 60-250-76-52.hinet-ip.hinet.net | - | High
16 | [64.32.3.186](https://vuldb.com/?ip.64.32.3.186) | - | - | High
17 | ... | ... | ... | ...

There are 66 more IOC items available. Please use our online service to access the data.

## TTP - Tactics, Techniques, Procedures

_Tactics, techniques, and procedures_ (TTP) summarize the suspected MITRE ATT&CK techniques used by _MyKings_. This data is unique as it uses our predictive model for actor profiling.

ID | Technique | Weakness | Description | Confidence
-- | --------- | -------- | ----------- | ----------
1 | T1006 | CWE-21, CWE-22, CWE-23 | Pathname Traversal | High
2 | T1040 | CWE-319 | Authentication Bypass by Capture-replay | High
3 | T1055 | CWE-74 | Injection | High
4 | T1059 | CWE-88, CWE-94 | Cross Site Scripting | High
5 | T1059.007 | CWE-79, CWE-80 | Cross Site Scripting | High
6 | ... | ... | ... | ...

There are 21 more TTP items available. Please use our online service to access the data.

## IOA - Indicator of Attack

These _indicators of attack_ (IOA) list the potential fragments used for technical activities like reconnaissance, exploitation, privilege escalation, and exfiltration by MyKings. This data is unique as it uses our predictive model for actor profiling.

ID | Type | Indicator | Confidence
-- | ---- | --------- | ----------
1 | File | `//` | Low
2 | File | `/admin/download_frame.php` | High
3 | File | `/admin/index.html` | High
4 | File | `/api/sys/set_passwd` | High
5 | File | `/bin/boa` | Medium
6 | File | `/cgi-bin/luci/admin/network/wireless/status` | High
7 | File | `/cgi-bin/supervisor/PwdGrp.cgi` | High
8 | File | `/cgi-bin/wapopen` | High
9 | File | `/dev/urandom` | Medium
10 | File | `/DroboAccess/enable_user` | High
11 | File | `/etc/quantum/quantum.conf` | High
12 | File | `/exec/` | Low
13 | File | `/getcfg.php` | Medium
14 | File | `/HNAP1` | Low
15 | File | `/jquery_file_upload/server/php/index.php` | High
16 | File | `/mgmt/tm/util/bash` | High
17 | File | `/modules/projects/vw_files.php` | High
18 | File | `/mysql/api/drobo.php` | High
19 | File | `/plain` | Low
20 | File | `/rating.php` | Medium
21 | File | `/rom-0` | Low
22 | File | `/secure/admin/ConfigureBatching!default.jspa` | High
23 | File | `/staff/tools/custom-fields` | High
24 | File | `/uncpath/` | Medium
25 | File | `/usr/local/WowzaStreamingEngine/bin/` | High
26 | File | `/var/log/nginx` | High
27 | File | `/wordpress/wp-admin/admin.php` | High
28 | File | `/xyhai.php?s=/Auth/editUser` | High
29 | File | `/_next` | Low
30 | File | `actionHandler/ajax_managed_services.php` | High
31 | File | `actions.hsp` | Medium
32 | File | `addtocart.asp` | High
33 | File | `admin.jcomments.php` | High
34 | File | `admin/admin.shtml` | High
35 | File | `admin/shophelp.php` | High
36 | File | `ajax-actions.php` | High
37 | File | `ajax/api/hook/decodeArguments` | High
38 | ... | ... | ...

There are 322 more IOA items available (file, library, argument, input value, pattern, network port). Please use our online service to access the data.

## References

The following list contains _external sources_ which discuss the actor and the associated activities:

* https://github.com/sophoslabs/IoCs/blob/master/malware-MyKings
* https://github.com/sophoslabs/IoCs/blob/master/malware-MyKings-v2.csv

## Literature

The following _articles_ explain our unique predictive cyber threat intelligence:

* [VulDB Cyber Threat Intelligence Documentation](https://vuldb.com/?kb.cti)
* [Cyber Threat Intelligence - Early Anticipation of Attacks](https://www.scip.ch/en/?labs.20201022)

## License

(c) [1997-2023](https://vuldb.com/?kb.changelog) by [vuldb.com](https://vuldb.com/?kb.about). All data on this page is shared under the license [CC BY-NC-SA 4.0](https://creativecommons.org/licenses/by-nc-sa/4.0/). Questions? Check the [FAQ](https://vuldb.com/?kb.faq), read the [documentation](https://vuldb.com/?kb) or [contact us](https://vuldb.com/?contact)!
