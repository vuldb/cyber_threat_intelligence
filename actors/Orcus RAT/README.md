# Orcus RAT - Cyber Threat Intelligence

These _indicators_ were reported, collected, and generated during the [VulDB CTI analysis](https://vuldb.com/?kb.cti) of the actor known as [Orcus RAT](https://vuldb.com/?actor.orcus_rat). The _activity monitoring_ correlates data from social media, forums, chat rooms, and darknet markets. It helps to determine associated actors, specific activities, expected intentions, emerging research, and ongoing attacks. Our unique _predictive model_ uses _big data_ to forecast activities and their characteristics.

_Live data_ and more _analysis capabilities_ are available at [https://vuldb.com/?actor.orcus_rat](https://vuldb.com/?actor.orcus_rat)

## Countries

These _countries_ are directly (e.g. origin of attacks) or indirectly (e.g. access by proxy) associated with Orcus RAT:

* [US](https://vuldb.com/?country.us)
* [DE](https://vuldb.com/?country.de)
* [CN](https://vuldb.com/?country.cn)
* ...

There are 21 more country items available. Please use our online service to access the data.

## IOC - Indicator of Compromise

These _indicators of compromise_ (IOC) indicate associated network resources which are known to be part of research and attack activities of Orcus RAT.

ID | IP address | Hostname | Campaign | Confidence
-- | ---------- | -------- | -------- | ----------
1 | [3.129.187.220](https://vuldb.com/?ip.3.129.187.220) | ec2-3-129-187-220.us-east-2.compute.amazonaws.com | - | Medium
2 | [3.133.207.110](https://vuldb.com/?ip.3.133.207.110) | ec2-3-133-207-110.us-east-2.compute.amazonaws.com | - | Medium
3 | [3.137.146.78](https://vuldb.com/?ip.3.137.146.78) | ec2-3-137-146-78.us-east-2.compute.amazonaws.com | - | Medium
4 | [3.143.239.116](https://vuldb.com/?ip.3.143.239.116) | ec2-3-143-239-116.us-east-2.compute.amazonaws.com | - | Medium
5 | [13.53.37.168](https://vuldb.com/?ip.13.53.37.168) | ec2-13-53-37-168.eu-north-1.compute.amazonaws.com | - | Medium
6 | [18.117.142.49](https://vuldb.com/?ip.18.117.142.49) | ec2-18-117-142-49.us-east-2.compute.amazonaws.com | - | Medium
7 | [20.89.177.186](https://vuldb.com/?ip.20.89.177.186) | - | - | High
8 | [45.146.253.103](https://vuldb.com/?ip.45.146.253.103) | rs-zap868892-1.zap-srv.com | - | High
9 | [61.69.245.176](https://vuldb.com/?ip.61.69.245.176) | 61-69-245-176.static.tpgi.com.au | - | High
10 | [67.242.2.35](https://vuldb.com/?ip.67.242.2.35) | cpe-67-242-2-35.twcny.res.rr.com | - | High
11 | ... | ... | ... | ...

There are 38 more IOC items available. Please use our online service to access the data.

## TTP - Tactics, Techniques, Procedures

_Tactics, techniques, and procedures_ (TTP) summarize the suspected MITRE ATT&CK techniques used by _Orcus RAT_. This data is unique as it uses our predictive model for actor profiling.

ID | Technique | Weakness | Description | Confidence
-- | --------- | -------- | ----------- | ----------
1 | T1006 | CWE-21, CWE-22, CWE-23, CWE-24 | Pathname Traversal | High
2 | T1055 | CWE-74 | Injection | High
3 | T1059 | CWE-88, CWE-94 | Cross Site Scripting | High
4 | T1059.007 | CWE-79, CWE-80 | Cross Site Scripting | High
5 | T1068 | CWE-250, CWE-264, CWE-266, CWE-269, CWE-284 | J2EE Misconfiguration: Weak Access Permissions for EJB Methods | High
6 | ... | ... | ... | ...

There are 19 more TTP items available. Please use our online service to access the data.

## IOA - Indicator of Attack

These _indicators of attack_ (IOA) list the potential fragments used for technical activities like reconnaissance, exploitation, privilege escalation, and exfiltration by Orcus RAT. This data is unique as it uses our predictive model for actor profiling.

ID | Type | Indicator | Confidence
-- | ---- | --------- | ----------
1 | File | `.htaccess` | Medium
2 | File | `/?Key=PhoneRequestAuthorization` | High
3 | File | `/admin/access` | High
4 | File | `/admin/addproduct.php` | High
5 | File | `/admin/index.html` | High
6 | File | `/admin/new-content` | High
7 | File | `/admin/user/team` | High
8 | File | `/adv_resource` | High
9 | File | `/anony/mjpg.cgi` | High
10 | File | `/api/RecordingList/DownloadRecord?file=` | High
11 | File | `/apply.cgi` | Medium
12 | File | `/bin/login` | Medium
13 | File | `/configs/application.ini` | High
14 | File | `/dipam/save-delegates.php` | High
15 | File | `/etc/gsissh/sshd_config` | High
16 | File | `/etc/sudoers` | Medium
17 | File | `/goform/SetStaticRouteCfg` | High
18 | File | `/goform/wlanPrimaryNetwork` | High
19 | File | `/home` | Low
20 | File | `/index.php/album/add` | High
21 | File | `/my_photo_gallery/image.php` | High
22 | File | `/php_action/createProduct.php` | High
23 | File | `/plugins/Dashboard/Controller.php` | High
24 | File | `/public` | Low
25 | File | `/rapi/read_url` | High
26 | File | `/rest/api/latest/user/avatar/temporary` | High
27 | File | `/school/model/get_student_subject.php` | High
28 | File | `/scripts/unlock_tasks.php` | High
29 | File | `/show_news.php` | High
30 | File | `/system/user/modules/mod_users/controller.php` | High
31 | File | `/tcpedit/checksum.c` | High
32 | File | `/trx_addons/v2/get/sc_layout` | High
33 | File | `/uncpath/` | Medium
34 | File | `/users` | Low
35 | File | `/v2/_catalog` | Medium
36 | File | `/var/run/chrony` | High
37 | File | `/web/api/v1/upload/UploadHandler.php` | High
38 | File | `/weibo/publishdata` | High
39 | File | `/whbs/?page=manage_account` | High
40 | File | `/wp-admin/admin-post.php?es_skip=1&option_name` | High
41 | File | `aaa-idm-store-h2/src/main/java/org/opendaylight/aaa/datastore/h2/RoleStore.java` | High
42 | File | `admin.asp` | Medium
43 | File | `admin.php/comments/batchdel/` | High
44 | File | `admin.php/User/del/ucode/` | High
45 | File | `admin.php?c=a_adminuser&a=add&run=1` | High
46 | File | `admin.php?m=Member&a=adminaddsave` | High
47 | ... | ... | ...

There are 409 more IOA items available (file, library, argument, input value, pattern, network port). Please use our online service to access the data.

## References

The following list contains _external sources_ which discuss the actor and the associated activities:

* https://threatfox.abuse.ch
* https://www.virustotal.com/gui/file/07b742c9303e04be588f20f51d68828cae04a1af02cb6d09a9d935007dbb4906/detection

## Literature

The following _articles_ explain our unique predictive cyber threat intelligence:

* [VulDB Cyber Threat Intelligence Documentation](https://vuldb.com/?kb.cti)
* [Cyber Threat Intelligence - Early Anticipation of Attacks](https://www.scip.ch/en/?labs.20201022)

## License

(c) [1997-2023](https://vuldb.com/?kb.changelog) by [vuldb.com](https://vuldb.com/?kb.about). All data on this page is shared under the license [CC BY-NC-SA 4.0](https://creativecommons.org/licenses/by-nc-sa/4.0/). Questions? Check the [FAQ](https://vuldb.com/?kb.faq), read the [documentation](https://vuldb.com/?kb) or [contact us](https://vuldb.com/?contact)!
