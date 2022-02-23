# m8220 - Cyber Threat Intelligence

These _indicators_ were collected during the [VulDB CTI analysis](https://vuldb.com/?kb.cti) of the actor known as [m8220](https://vuldb.com/?actor.m8220). The _activity monitoring_ correlates data from social media, forums, chat rooms, and darknet markets. It helps to determine associated actors, specific activities, expected intentions, emerging research, and ongoing attacks. Our unique _predictive model_ is able to forecast activities and their characteristics.

_Live data_ and more _analysis capabilities_ are available at [https://vuldb.com/?actor.m8220](https://vuldb.com/?actor.m8220)

## Campaigns

The following _campaigns_ are known and can be associated with m8220:

* Log4Shell

## Countries

These _countries_ are directly (e.g. origin of attacks) or indirectly (e.g. access by proxy) associated with m8220:

* US
* CN
* IN

## IOC - Indicator of Compromise

These _indicators of compromise_ (IOC) indicate associated network resources which are known to be part of research and attack activities of m8220.

ID | IP address | Hostname | Campaign | Confidence
-- | ---------- | -------- | -------- | ----------
1 | 205.185.113.59 | - | Log4Shell | High

## TTP - Tactics, Techniques, Procedures

_Tactics, techniques, and procedures_ (TTP) summarize the suspected ATT&CK techniques used by m8220. This data is unique as it uses our predictive model for actor profiling.

ID | Technique | Weakness | Description | Confidence
-- | --------- | -------- | ----------- | ----------
1 | T1059.007 | CWE-79, CWE-80 | Cross Site Scripting | High
2 | T1068 | CWE-264, CWE-284 | Execution with Unnecessary Privileges | High
3 | T1110.001 | CWE-798 | Improper Restriction of Excessive Authentication Attempts | High
4 | ... | ... | ... | ...

There are 6 more TTP items available. Please use our online service to access the data.

## IOA - Indicator of Attack

These _indicators of attack_ (IOA) list the potential fragments used for technical activities like reconnaissance, exploitation, privilege escalation, and exfiltration by m8220. This data is unique as it uses our predictive model for actor profiling.

ID | Type | Indicator | Confidence
-- | ---- | --------- | ----------
1 | File | `/category_view.php` | High
2 | File | `/frontend/x3/cpanelpro/filelist-thumbs.html` | High
3 | File | `/fs/cifs/file.c` | High
4 | File | `/highlight/index.html` | High
5 | File | `/hotel.php` | Medium
6 | File | `/Login.do` | Medium
7 | File | `/var/etc/shadow` | High
8 | File | `/var/log/cgred` | High
9 | File | `/var/run/hostapd` | High
10 | File | `add.php` | Low
11 | File | `AddEvent.php` | Medium
12 | File | `addlisting.asp` | High
13 | File | `add_tmsp.php` | Medium
14 | File | `admin.php` | Medium
15 | File | `admin/handlers.php` | High
16 | File | `admin/help.php` | High
17 | File | `admin/modules/system/app_user.php` | High
18 | File | `admin/tools/trackback/index.php` | High
19 | File | `admin/users_edit.php` | High
20 | File | `administrators/backups/` | High
21 | File | `afmparse.c` | Medium
22 | File | `ajax.php` | Medium
23 | File | `ajax_udf.php` | Medium
24 | File | `answers.php` | Medium
25 | File | `apsetup.php` | Medium
26 | File | `arch/powerpc/kernel/process.c` | High
27 | File | `arch/x86/kvm/vmx.c` | High
28 | File | `ArchiveUtil.java` | High
29 | File | `bmp.c` | Low
30 | File | `browse.php` | Medium
31 | File | `buy.php` | Low
32 | File | `calendar.class.php` | High
33 | File | `calendar/submit/` | High
34 | File | `category.php` | Medium
35 | File | `cc_guestbook.pl` | High
36 | File | `centipaid_class.php` | High
37 | File | `channel.c` | Medium
38 | File | `chetcpasswd.cgi` | High
39 | File | `clastree.htm` | Medium
40 | File | `client-assist.php` | High
41 | File | `coders/dds.c` | Medium
42 | File | `coders/webp.c` | High
43 | File | `CollabNetApp.java` | High
44 | File | `collection.class.php` | High
45 | ... | ... | ...

There are 387 more IOA items available (file, library, argument, input value, pattern, network port). Please use our online service to access the data.

## References

The following list contains _external sources_ which discuss the actor and the associated activities:

* https://blog.netlab.360.com/yi-jing-you-xxxge-jia-zu-de-botnetli-yong-log4shelllou-dong-chuan-bo-wei-da-bu-ding-de-gan-jin-liao/

## Literature

The following _articles_ explain our unique predictive cyber threat intelligence:

* [VulDB Cyber Threat Intelligence Documentation](https://vuldb.com/?kb.cti)
* [Cyber Threat Intelligence - Early Anticipation of Attacks](https://www.scip.ch/en/?labs.20201022)

## License

(c) [1997-2022](https://vuldb.com/?kb.changelog) by [vuldb.com](https://vuldb.com/?kb.about). All data on this page is shared under the license [CC BY-NC-SA 4.0](https://creativecommons.org/licenses/by-nc-sa/4.0/). Questions? Check the [FAQ](https://vuldb.com/?kb.faq), read the [documentation](https://vuldb.com/?kb) or [contact us](https://vuldb.com/?contact)!
