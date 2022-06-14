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

There are 20 more country items available. Please use our online service to access the data.

## IOC - Indicator of Compromise

These _indicators of compromise_ (IOC) indicate associated network resources which are known to be part of research and attack activities of MyKings.

ID | IP address | Hostname | Campaign | Confidence
-- | ---------- | -------- | -------- | ----------
1 | [13.58.133.77](https://vuldb.com/?ip.13.58.133.77) | ec2-13-58-133-77.us-east-2.compute.amazonaws.com | - | Medium
2 | [13.59.110.123](https://vuldb.com/?ip.13.59.110.123) | ec2-13-59-110-123.us-east-2.compute.amazonaws.com | - | Medium
3 | [18.191.72.35](https://vuldb.com/?ip.18.191.72.35) | ec2-18-191-72-35.us-east-2.compute.amazonaws.com | - | Medium
4 | [18.218.14.96](https://vuldb.com/?ip.18.218.14.96) | ec2-18-218-14-96.us-east-2.compute.amazonaws.com | - | Medium
5 | [18.236.135.84](https://vuldb.com/?ip.18.236.135.84) | ec2-18-236-135-84.us-west-2.compute.amazonaws.com | - | Medium
6 | [23.27.127.254](https://vuldb.com/?ip.23.27.127.254) | - | - | High
7 | [23.236.69.114](https://vuldb.com/?ip.23.236.69.114) | - | - | High
8 | [35.182.171.137](https://vuldb.com/?ip.35.182.171.137) | ec2-35-182-171-137.ca-central-1.compute.amazonaws.com | - | Medium
9 | [45.58.133.10](https://vuldb.com/?ip.45.58.133.10) | depending-tcped.landweeks.com | - | High
10 | [45.58.135.106](https://vuldb.com/?ip.45.58.135.106) | - | - | High
11 | [45.58.140.194](https://vuldb.com/?ip.45.58.140.194) | vm194.ebouravi.com | - | High
12 | [45.116.13.219](https://vuldb.com/?ip.45.116.13.219) | 45.116.13.219.static.xtom.hk | - | High
13 | [54.255.141.50](https://vuldb.com/?ip.54.255.141.50) | ec2-54-255-141-50.ap-southeast-1.compute.amazonaws.com | - | Medium
14 | [60.250.76.52](https://vuldb.com/?ip.60.250.76.52) | 60-250-76-52.hinet-ip.hinet.net | - | High
15 | [64.32.3.186](https://vuldb.com/?ip.64.32.3.186) | - | - | High
16 | [66.117.2.182](https://vuldb.com/?ip.66.117.2.182) | crownwine.net | - | High
17 | ... | ... | ... | ...

There are 65 more IOC items available. Please use our online service to access the data.

## TTP - Tactics, Techniques, Procedures

_Tactics, techniques, and procedures_ (TTP) summarize the suspected MITRE ATT&CK techniques used by _MyKings_. This data is unique as it uses our predictive model for actor profiling.

ID | Technique | Weakness | Description | Confidence
-- | --------- | -------- | ----------- | ----------
1 | T1059.007 | CWE-79, CWE-80 | Cross Site Scripting | High
2 | T1068 | CWE-264, CWE-284 | Execution with Unnecessary Privileges | High
3 | T1110.001 | CWE-307, CWE-798 | Improper Restriction of Excessive Authentication Attempts | High
4 | ... | ... | ... | ...

There are 6 more TTP items available. Please use our online service to access the data.

## IOA - Indicator of Attack

These _indicators of attack_ (IOA) list the potential fragments used for technical activities like reconnaissance, exploitation, privilege escalation, and exfiltration by MyKings. This data is unique as it uses our predictive model for actor profiling.

ID | Type | Indicator | Confidence
-- | ---- | --------- | ----------
1 | File | `//` | Low
2 | File | `/admin/download_frame.php` | High
3 | File | `/admin/index.html` | High
4 | File | `/bin/boa` | Medium
5 | File | `/cgi-bin/supervisor/PwdGrp.cgi` | High
6 | File | `/cgi-bin/wapopen` | High
7 | File | `/dev/urandom` | Medium
8 | File | `/DroboAccess/enable_user` | High
9 | File | `/etc/quantum/quantum.conf` | High
10 | File | `/exec/` | Low
11 | File | `/getcfg.php` | Medium
12 | File | `/HNAP1` | Low
13 | File | `/jquery_file_upload/server/php/index.php` | High
14 | File | `/mgmt/tm/util/bash` | High
15 | File | `/modules/projects/vw_files.php` | High
16 | File | `/mysql/api/drobo.php` | High
17 | File | `/plain` | Low
18 | File | `/rating.php` | Medium
19 | File | `/rom-0` | Low
20 | File | `/secure/admin/ConfigureBatching!default.jspa` | High
21 | File | `/uncpath/` | Medium
22 | File | `/usr/local/WowzaStreamingEngine/bin/` | High
23 | File | `/var/log/nginx` | High
24 | File | `/wordpress/wp-admin/admin.php` | High
25 | File | `/xyhai.php?s=/Auth/editUser` | High
26 | File | `/_next` | Low
27 | File | `actionHandler/ajax_managed_services.php` | High
28 | File | `actions.hsp` | Medium
29 | File | `addtocart.asp` | High
30 | File | `admin/admin.shtml` | High
31 | ... | ... | ...

There are 268 more IOA items available (file, library, argument, input value, pattern, network port). Please use our online service to access the data.

## References

The following list contains _external sources_ which discuss the actor and the associated activities:

* https://github.com/sophoslabs/IoCs/blob/master/malware-MyKings
* https://github.com/sophoslabs/IoCs/blob/master/malware-MyKings-v2.csv

## Literature

The following _articles_ explain our unique predictive cyber threat intelligence:

* [VulDB Cyber Threat Intelligence Documentation](https://vuldb.com/?kb.cti)
* [Cyber Threat Intelligence - Early Anticipation of Attacks](https://www.scip.ch/en/?labs.20201022)

## License

(c) [1997-2022](https://vuldb.com/?kb.changelog) by [vuldb.com](https://vuldb.com/?kb.about). All data on this page is shared under the license [CC BY-NC-SA 4.0](https://creativecommons.org/licenses/by-nc-sa/4.0/). Questions? Check the [FAQ](https://vuldb.com/?kb.faq), read the [documentation](https://vuldb.com/?kb) or [contact us](https://vuldb.com/?contact)!
