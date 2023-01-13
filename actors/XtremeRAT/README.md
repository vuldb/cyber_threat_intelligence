# XtremeRAT - Cyber Threat Intelligence

These _indicators_ were reported, collected, and generated during the [VulDB CTI analysis](https://vuldb.com/?kb.cti) of the actor known as [XtremeRAT](https://vuldb.com/?actor.xtremerat). The _activity monitoring_ correlates data from social media, forums, chat rooms, and darknet markets. It helps to determine associated actors, specific activities, expected intentions, emerging research, and ongoing attacks. Our unique _predictive model_ uses _big data_ to forecast activities and their characteristics.

_Live data_ and more _analysis capabilities_ are available at [https://vuldb.com/?actor.xtremerat](https://vuldb.com/?actor.xtremerat)

## Countries

These _countries_ are directly (e.g. origin of attacks) or indirectly (e.g. access by proxy) associated with XtremeRAT:

* [US](https://vuldb.com/?country.us)
* [VN](https://vuldb.com/?country.vn)
* [CN](https://vuldb.com/?country.cn)
* ...

There are 3 more country items available. Please use our online service to access the data.

## IOC - Indicator of Compromise

These _indicators of compromise_ (IOC) indicate associated network resources which are known to be part of research and attack activities of XtremeRAT.

ID | IP address | Hostname | Campaign | Confidence
-- | ---------- | -------- | -------- | ----------
1 | [5.79.71.205](https://vuldb.com/?ip.5.79.71.205) | - | - | High
2 | [13.107.21.200](https://vuldb.com/?ip.13.107.21.200) | - | - | High
3 | [20.36.253.92](https://vuldb.com/?ip.20.36.253.92) | - | - | High
4 | [23.32.81.118](https://vuldb.com/?ip.23.32.81.118) | a23-32-81-118.deploy.static.akamaitechnologies.com | - | High
5 | [23.62.7.138](https://vuldb.com/?ip.23.62.7.138) | a23-62-7-138.deploy.static.akamaitechnologies.com | - | High
6 | [23.202.81.150](https://vuldb.com/?ip.23.202.81.150) | a23-202-81-150.deploy.static.akamaitechnologies.com | - | High
7 | [62.90.21.54](https://vuldb.com/?ip.62.90.21.54) | 62-90-21-54.barak.net.il | - | High
8 | [64.29.151.221](https://vuldb.com/?ip.64.29.151.221) | hostedc40.carrierzone.com | - | High
9 | [65.55.44.109](https://vuldb.com/?ip.65.55.44.109) | - | - | High
10 | [71.95.133.164](https://vuldb.com/?ip.71.95.133.164) | 071-095-133-164.res.spectrum.com | - | High
11 | [71.226.96.253](https://vuldb.com/?ip.71.226.96.253) | c-71-226-96-253.hsd1.sc.comcast.net | - | High
12 | ... | ... | ... | ...

There are 46 more IOC items available. Please use our online service to access the data.

## TTP - Tactics, Techniques, Procedures

_Tactics, techniques, and procedures_ (TTP) summarize the suspected MITRE ATT&CK techniques used by _XtremeRAT_. This data is unique as it uses our predictive model for actor profiling.

ID | Technique | Weakness | Description | Confidence
-- | --------- | -------- | ----------- | ----------
1 | T1006 | CWE-21, CWE-22, CWE-425 | Pathname Traversal | High
2 | T1040 | CWE-294, CWE-319 | Authentication Bypass by Capture-replay | High
3 | T1055 | CWE-74 | Injection | High
4 | T1059 | CWE-94, CWE-1321 | Cross Site Scripting | High
5 | T1059.007 | CWE-79, CWE-80 | Cross Site Scripting | High
6 | ... | ... | ... | ...

There are 19 more TTP items available. Please use our online service to access the data.

## IOA - Indicator of Attack

These _indicators of attack_ (IOA) list the potential fragments used for technical activities like reconnaissance, exploitation, privilege escalation, and exfiltration by XtremeRAT. This data is unique as it uses our predictive model for actor profiling.

ID | Type | Indicator | Confidence
-- | ---- | --------- | ----------
1 | File | `/+CSCOE+/logon.html` | High
2 | File | `/action/wirelessConnect` | High
3 | File | `/admin/upload/upload` | High
4 | File | `/admin/videoalbum/list` | High
5 | File | `/c/macho_reader.c` | High
6 | File | `/cgi-bin/DownloadFlash` | High
7 | File | `/cgi-bin/wlogin.cgi` | High
8 | File | `/cloud_config/router_post/check_reg_verify_code` | High
9 | File | `/conf/` | Low
10 | File | `/config/getuser` | High
11 | File | `/dashboard/contact` | High
12 | File | `/dev/bus` | Medium
13 | File | `/example/editor` | High
14 | File | `/files/$username/Myfolder/Mysubfolder/shared.txt` | High
15 | File | `/goform/L7Im` | Medium
16 | File | `/goform/setMacFilterCfg` | High
17 | File | `/HNAP1` | Low
18 | File | `/index` | Low
19 | File | `/iu-application/controllers/administration/auth.php` | High
20 | File | `/jerry-core/ecma/operations/ecma-objects.c` | High
21 | File | `/Kofax/KFS/ThinClient/document/upload/` | High
22 | File | `/leave_system/classes/Master.php?f=delete_department` | High
23 | File | `/module/module_frame/index.php` | High
24 | File | `/music/ajax.php` | High
25 | File | `/northstar/Admin/changePassword.jsp` | High
26 | File | `/orms/` | Low
27 | File | `/ossn/administrator/com_installer` | High
28 | File | `/pms/update_user.php?user_id=1` | High
29 | File | `/rest/api/1.0/render` | High
30 | File | `/sre/params.php` | High
31 | File | `/tensorflow/core/grappler/optimizers/arithmetic_optimizer.cc` | High
32 | File | `/tmp` | Low
33 | File | `/tmp/xbindkeysrc-tmp` | High
34 | File | `/user/upload/upload` | High
35 | File | `/Users` | Low
36 | File | `/var/spool/hylafax` | High
37 | File | `/vendor` | Low
38 | File | `/whbs/?page=my_bookings` | High
39 | File | `access_rules/rules_form` | High
40 | File | `accountrecoveryendpoint/recoverpassword.do` | High
41 | File | `action/addproject.php` | High
42 | ... | ... | ...

There are 361 more IOA items available (file, library, argument, input value, pattern, network port). Please use our online service to access the data.

## References

The following list contains _external sources_ which discuss the actor and the associated activities:

* https://blog.talosintelligence.com/2019/07/threat-roundup-0712-0719.html
* https://blog.talosintelligence.com/2019/07/threat-roundup-0719-0726.html
* https://blog.talosintelligence.com/2019/09/threat-roundup-0913-0920.html
* https://blog.talosintelligence.com/2020/05/threat-roundup-0424-0501.html
* https://blog.talosintelligence.com/2022/03/threat-roundup-0225-0304.html
* https://blog.talosintelligence.com/2022/05/threat-roundup-0429-0506.html
* https://blog.talosintelligence.com/2022/08/threat-roundup-0819-0826.html

## Literature

The following _articles_ explain our unique predictive cyber threat intelligence:

* [VulDB Cyber Threat Intelligence Documentation](https://vuldb.com/?kb.cti)
* [Cyber Threat Intelligence - Early Anticipation of Attacks](https://www.scip.ch/en/?labs.20201022)

## License

(c) [1997-2023](https://vuldb.com/?kb.changelog) by [vuldb.com](https://vuldb.com/?kb.about). All data on this page is shared under the license [CC BY-NC-SA 4.0](https://creativecommons.org/licenses/by-nc-sa/4.0/). Questions? Check the [FAQ](https://vuldb.com/?kb.faq), read the [documentation](https://vuldb.com/?kb) or [contact us](https://vuldb.com/?contact)!
