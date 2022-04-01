# Candiru - Cyber Threat Intelligence

These _indicators_ were reported, collected, and generated during the [VulDB CTI analysis](https://vuldb.com/?kb.cti) of the actor known as [Candiru](https://vuldb.com/?actor.candiru). The _activity monitoring_ correlates data from social media, forums, chat rooms, and darknet markets. It helps to determine associated actors, specific activities, expected intentions, emerging research, and ongoing attacks. Our unique _predictive model_ uses _big data_ to forecast activities and their characteristics.

_Live data_ and more _analysis capabilities_ are available at [https://vuldb.com/?actor.candiru](https://vuldb.com/?actor.candiru)

## Countries

These _countries_ are directly (e.g. origin of attacks) or indirectly (e.g. access by proxy) associated with Candiru:

* [US](https://vuldb.com/?country.us)
* [SC](https://vuldb.com/?country.sc)
* [TR](https://vuldb.com/?country.tr)
* ...

There are 14 more country items available. Please use our online service to access the data.

## IOC - Indicator of Compromise

These _indicators of compromise_ (IOC) indicate associated network resources which are known to be part of research and attack activities of Candiru.

ID | IP address | Hostname | Campaign | Confidence
-- | ---------- | -------- | -------- | ----------
1 | [5.2.67.82](https://vuldb.com/?ip.5.2.67.82) | xanthium.astrotrain.xyz | - | High
2 | [5.2.75.217](https://vuldb.com/?ip.5.2.75.217) | mq.is | - | High
3 | [5.206.224.54](https://vuldb.com/?ip.5.206.224.54) | - | - | High
4 | [5.206.224.197](https://vuldb.com/?ip.5.206.224.197) | - | - | High
5 | [5.206.224.226](https://vuldb.com/?ip.5.206.224.226) | gofast | - | High
6 | [5.206.227.93](https://vuldb.com/?ip.5.206.227.93) | noos-proxy | - | High
7 | ... | ... | ... | ...

There are 23 more IOC items available. Please use our online service to access the data.

## TTP - Tactics, Techniques, Procedures

_Tactics, techniques, and procedures_ (TTP) summarize the suspected MITRE ATT&CK techniques used by _Candiru_. This data is unique as it uses our predictive model for actor profiling.

ID | Technique | Weakness | Description | Confidence
-- | --------- | -------- | ----------- | ----------
1 | T1059.007 | CWE-79, CWE-80 | Cross Site Scripting | High
2 | T1068 | CWE-264, CWE-266, CWE-284 | Execution with Unnecessary Privileges | High
3 | T1110.001 | CWE-798 | Improper Restriction of Excessive Authentication Attempts | High
4 | ... | ... | ... | ...

There are 9 more TTP items available. Please use our online service to access the data.

## IOA - Indicator of Attack

These _indicators of attack_ (IOA) list the potential fragments used for technical activities like reconnaissance, exploitation, privilege escalation, and exfiltration by Candiru. This data is unique as it uses our predictive model for actor profiling.

ID | Type | Indicator | Confidence
-- | ---- | --------- | ----------
1 | File | `%PROGRAMDATA%\OpenVPN Connect\drivers\tap\amd64\win10` | High
2 | File | `/.vnc/sesman_${username}_passwd` | High
3 | File | `/addsrv` | Low
4 | File | `/Admin/Views/FileEditor/` | High
5 | File | `/api/user/{ID}` | High
6 | File | `/article/add` | Medium
7 | File | `/cgi-bin/editBookmark` | High
8 | File | `/cgi-bin/uploadWeiXinPic` | High
9 | File | `/computer/(agent-name)/api` | High
10 | File | `/controller/pay.class.php` | High
11 | File | `/dev/block/mmcblk0rpmb` | High
12 | File | `/dev/kmem` | Medium
13 | File | `/dev/shm` | Medium
14 | File | `/dev/snd/seq` | Medium
15 | File | `/device/device=140/tab=wifi/view` | High
16 | File | `/dl/dl_print.php` | High
17 | File | `/getcfg.php` | Medium
18 | File | `/goform/addressNat` | High
19 | File | `/htdocs/admin/dict.php?id=3` | High
20 | File | `/include/menu_v.inc.php` | High
21 | File | `/includes/rrdtool.inc.php` | High
22 | File | `/irj/servlet/prt/portal/prtroot/com.sap.portal.usermanagement.admin.UserMapping` | High
23 | File | `/jerry-core/ecma/base/ecma-gc.c` | High
24 | File | `/jerry-core/ecma/base/ecma-helpers-conversion.c` | High
25 | File | `/login` | Low
26 | File | `/module/module_frame/index.php` | High
27 | File | `/notice-edit.php` | High
28 | File | `/nova/bin/sniffer` | High
29 | File | `/proc/pid/syscall` | High
30 | File | `/product_list.php` | High
31 | File | `/rest/api/2/user/picker` | High
32 | File | `/rukovoditel_2.4.1/index.php?module=configuration/save&redirect_to=configuration/application` | High
33 | File | `/services/details.asp` | High
34 | File | `/src/core/controllers/cm.php` | High
35 | File | `/storage/app/media/evil.svg` | High
36 | File | `/transmission/web/` | High
37 | ... | ... | ...

There are 318 more IOA items available (file, library, argument, input value, pattern, network port). Please use our online service to access the data.

## References

The following list contains _external sources_ which discuss the actor and the associated activities:

* https://github.com/eset/malware-ioc/tree/master/swc-candiru

## Literature

The following _articles_ explain our unique predictive cyber threat intelligence:

* [VulDB Cyber Threat Intelligence Documentation](https://vuldb.com/?kb.cti)
* [Cyber Threat Intelligence - Early Anticipation of Attacks](https://www.scip.ch/en/?labs.20201022)

## License

(c) [1997-2022](https://vuldb.com/?kb.changelog) by [vuldb.com](https://vuldb.com/?kb.about). All data on this page is shared under the license [CC BY-NC-SA 4.0](https://creativecommons.org/licenses/by-nc-sa/4.0/). Questions? Check the [FAQ](https://vuldb.com/?kb.faq), read the [documentation](https://vuldb.com/?kb) or [contact us](https://vuldb.com/?contact)!
