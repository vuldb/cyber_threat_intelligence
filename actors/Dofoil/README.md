# Dofoil - Cyber Threat Intelligence

These _indicators_ were reported, collected, and generated during the [VulDB CTI analysis](https://vuldb.com/?kb.cti) of the actor known as [Dofoil](https://vuldb.com/?actor.dofoil). The _activity monitoring_ correlates data from social media, forums, chat rooms, and darknet markets. It helps to determine associated actors, specific activities, expected intentions, emerging research, and ongoing attacks. Our unique _predictive model_ uses _big data_ to forecast activities and their characteristics.

_Live data_ and more _analysis capabilities_ are available at [https://vuldb.com/?actor.dofoil](https://vuldb.com/?actor.dofoil)

## Countries

These _countries_ are directly (e.g. origin of attacks) or indirectly (e.g. access by proxy) associated with Dofoil:

* [US](https://vuldb.com/?country.us)
* [CN](https://vuldb.com/?country.cn)
* [RU](https://vuldb.com/?country.ru)
* ...

There are 3 more country items available. Please use our online service to access the data.

## IOC - Indicator of Compromise

These _indicators of compromise_ (IOC) indicate associated network resources which are known to be part of research and attack activities of Dofoil.

ID | IP address | Hostname | Campaign | Confidence
-- | ---------- | -------- | -------- | ----------
1 | [5.149.253.100](https://vuldb.com/?ip.5.149.253.100) | enappiv.com | - | High
2 | [8.110.105.136](https://vuldb.com/?ip.8.110.105.136) | - | - | High
3 | [8.123.232.109](https://vuldb.com/?ip.8.123.232.109) | - | - | High
4 | [13.107.21.200](https://vuldb.com/?ip.13.107.21.200) | - | - | High
5 | [23.3.13.137](https://vuldb.com/?ip.23.3.13.137) | a23-3-13-137.deploy.static.akamaitechnologies.com | - | High
6 | [23.6.24.15](https://vuldb.com/?ip.23.6.24.15) | a23-6-24-15.deploy.static.akamaitechnologies.com | - | High
7 | [23.6.65.194](https://vuldb.com/?ip.23.6.65.194) | a23-6-65-194.deploy.static.akamaitechnologies.com | - | High
8 | [23.209.185.159](https://vuldb.com/?ip.23.209.185.159) | a23-209-185-159.deploy.static.akamaitechnologies.com | - | High
9 | [27.100.36.191](https://vuldb.com/?ip.27.100.36.191) | - | - | High
10 | [37.230.112.146](https://vuldb.com/?ip.37.230.112.146) | audiotop.ru | - | High
11 | [45.63.25.55](https://vuldb.com/?ip.45.63.25.55) | 45.63.25.55.vultr.com | - | Medium
12 | [50.3.75.246](https://vuldb.com/?ip.50.3.75.246) | web.netkolik.org | - | High
13 | ... | ... | ... | ...

There are 49 more IOC items available. Please use our online service to access the data.

## TTP - Tactics, Techniques, Procedures

_Tactics, techniques, and procedures_ (TTP) summarize the suspected MITRE ATT&CK techniques used by _Dofoil_. This data is unique as it uses our predictive model for actor profiling.

ID | Technique | Weakness | Description | Confidence
-- | --------- | -------- | ----------- | ----------
1 | T1006 | CWE-21, CWE-22 | Path Traversal | High
2 | T1040 | CWE-319 | Authentication Bypass by Capture-replay | High
3 | T1055 | CWE-74 | Injection | High
4 | T1059 | CWE-94 | Argument Injection | High
5 | ... | ... | ... | ...

There are 16 more TTP items available. Please use our online service to access the data.

## IOA - Indicator of Attack

These _indicators of attack_ (IOA) list the potential fragments used for technical activities like reconnaissance, exploitation, privilege escalation, and exfiltration by Dofoil. This data is unique as it uses our predictive model for actor profiling.

ID | Type | Indicator | Confidence
-- | ---- | --------- | ----------
1 | File | `/act/ActDao.xml` | High
2 | File | `/api/clusters/local/topics/{topic}/messages` | High
3 | File | `/api/trackedEntityInstances` | High
4 | File | `/aux` | Low
5 | File | `/dashboard/system/basics/name` | High
6 | File | `/data/remove` | Medium
7 | File | `/debug/pprof` | Medium
8 | File | `/etc/passwd` | Medium
9 | File | `/forum/away.php` | High
10 | File | `/index.php` | Medium
11 | File | `/nagiosxi/admin/banner_message-ajaxhelper.php` | High
12 | File | `/tmp/ppd.trace` | High
13 | File | `/user/inc/workidajax.php` | High
14 | File | `/userLogin.asp` | High
15 | File | `Access.app/Contents/Resources/kcproxy` | High
16 | File | `act.php` | Low
17 | File | `addressbook.update.php` | High
18 | File | `admin.php` | Medium
19 | File | `admin/index.php` | High
20 | File | `admin/password_reset.lua` | High
21 | File | `apexec.pl` | Medium
22 | File | `arch/arm/p2m.c` | High
23 | File | `arch/arm64/kernel/sys.c` | High
24 | File | `arch/x86/include/asm/uaccess.h` | High
25 | File | `arch/x86/kernel/cpu/microcode/intel_early.c` | High
26 | File | `Certificates.java` | High
27 | File | `cloud.php` | Medium
28 | File | `com_android_bluetooth_btservice_AdapterService.cpp` | High
29 | File | `devices.common.ibm.atm.rte` | High
30 | File | `download.php` | Medium
31 | ... | ... | ...

There are 268 more IOA items available (file, library, argument, input value, pattern, network port). Please use our online service to access the data.

## References

The following list contains _external sources_ which discuss the actor and the associated activities:

* https://blog.talosintelligence.com/2018/09/threat-roundup-0914-0921.html
* https://blog.talosintelligence.com/2018/10/threat-roundup-1005-1012.html
* https://blog.talosintelligence.com/2019/03/threat-roundup-0308-0315.html
* https://blog.talosintelligence.com/2021/04/threat-roundup-0326-0402.html
* https://blogs.blackberry.com/en/2018/07/threat-spotlight-resurgent-smoke-loader-malware-dissected

## Literature

The following _articles_ explain our unique predictive cyber threat intelligence:

* [VulDB Cyber Threat Intelligence Documentation](https://vuldb.com/?kb.cti)
* [Cyber Threat Intelligence - Early Anticipation of Attacks](https://www.scip.ch/en/?labs.20201022)

## License

(c) [1997-2024](https://vuldb.com/?kb.changelog) by [vuldb.com](https://vuldb.com/?kb.about). All data on this page is shared under the license [CC BY-NC-SA 4.0](https://creativecommons.org/licenses/by-nc-sa/4.0/). Questions? Check the [FAQ](https://vuldb.com/?kb.faq), read the [documentation](https://vuldb.com/?kb) or [contact us](https://vuldb.com/?contact)!
