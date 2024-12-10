# m8220 - Cyber Threat Intelligence

These _indicators_ were reported, collected, and generated during the [VulDB CTI analysis](https://vuldb.com/?kb.cti) of the actor known as [m8220](https://vuldb.com/?actor.m8220). The _activity monitoring_ correlates data from social media, forums, chat rooms, and darknet markets. It helps to determine associated actors, specific activities, expected intentions, emerging research, and ongoing attacks. Our unique _predictive model_ uses _big data_ to forecast activities and their characteristics.

_Live data_ and more _analysis capabilities_ are available at [https://vuldb.com/?actor.m8220](https://vuldb.com/?actor.m8220)

## Campaigns

The following _campaigns_ are known and can be associated with m8220:

* Log4Shell

## Countries

These _countries_ are directly (e.g. origin of attacks) or indirectly (e.g. access by proxy) associated with m8220:

* [US](https://vuldb.com/?country.us)
* [CN](https://vuldb.com/?country.cn)
* [TK](https://vuldb.com/?country.tk)
* ...

There are 1 more country items available. Please use our online service to access the data.

## IOC - Indicator of Compromise

These _indicators of compromise_ (IOC) indicate associated network resources which are known to be part of research and attack activities of m8220.

ID | IP address | Hostname | Campaign | Confidence
-- | ---------- | -------- | -------- | ----------
1 | [205.185.113.59](https://vuldb.com/?ip.205.185.113.59) | - | Log4Shell | High

## TTP - Tactics, Techniques, Procedures

_Tactics, techniques, and procedures_ (TTP) summarize the suspected MITRE ATT&CK techniques used by _m8220_. This data is unique as it uses our predictive model for actor profiling.

ID | Technique | Weakness | Description | Confidence
-- | --------- | -------- | ----------- | ----------
1 | T1006 | CWE-21, CWE-22, CWE-24, CWE-29 | Path Traversal | High
2 | T1055 | CWE-74 | Improper Neutralization of Data within XPath Expressions | High
3 | T1059 | CWE-88, CWE-94 | Argument Injection | High
4 | T1059.007 | CWE-79, CWE-80 | Basic Cross Site Scripting | High
5 | ... | ... | ... | ...

There are 17 more TTP items available. Please use our online service to access the data.

## IOA - Indicator of Attack

These _indicators of attack_ (IOA) list the potential fragments used for technical activities like reconnaissance, exploitation, privilege escalation, and exfiltration by m8220. This data is unique as it uses our predictive model for actor profiling.

ID | Type | Indicator | Confidence
-- | ---- | --------- | ----------
1 | File | `/adminpanel/admin/query/deleteCourseExe.php` | High
2 | File | `/apps/system/services/role_menu.go` | High
3 | File | `/cap.js` | Low
4 | File | `/category_view.php` | High
5 | File | `/cgi-bin/account_mgr.cgi?cmd=cgi_user_add` | High
6 | File | `/cgi-bin/cgiServer.exx` | High
7 | File | `/cgi-bin/info.cgi` | High
8 | File | `/cgi-bin/nas_sharing.cgi` | High
9 | File | `/cgi-bin/system_mgr.cgi` | High
10 | File | `/device.rsp?opt=sys&cmd=___S_O_S_T_R_E_A_MAX___` | High
11 | File | `/devinfo` | Medium
12 | File | `/forum/away.php` | High
13 | File | `/general/meeting/manage/delete.php` | High
14 | File | `/goform/formSetWanPPPoE` | High
15 | File | `/goform/GetParentControlInfo` | High
16 | File | `/goform/SetNetControlList` | High
17 | File | `/goform/SysToolRestoreSet` | High
18 | File | `/highlight/index.html` | High
19 | File | `/hotel.php` | Medium
20 | File | `/Login.do` | Medium
21 | File | `/register.php` | High
22 | File | `/sys_verifies.php?action=view` | High
23 | File | `/var/etc/shadow` | High
24 | File | `/var/log/cgred` | High
25 | File | `/var/run/hostapd` | High
26 | File | `/version.js` | Medium
27 | File | `/view/student_exam_mark_insert_form1.php` | High
28 | File | `/xml/info.xml` | High
29 | File | `add.php` | Low
30 | File | `AddEvent.php` | Medium
31 | File | `addlisting.asp` | High
32 | File | `add_tmsp.php` | Medium
33 | File | `admin.php` | Medium
34 | File | `admin/handlers.php` | High
35 | File | `admin/help.php` | High
36 | File | `admin/modules/system/app_user.php` | High
37 | File | `admin/tools/trackback/index.php` | High
38 | File | `admin/update_room.php` | High
39 | File | `admin/users_edit.php` | High
40 | File | `administrators/backups/` | High
41 | File | `afmparse.c` | Medium
42 | File | `ajax.php` | Medium
43 | File | `answers.php` | Medium
44 | File | `apsetup.php` | Medium
45 | File | `arch/powerpc/kernel/process.c` | High
46 | File | `arch/x86/kvm/vmx.c` | High
47 | ... | ... | ...

There are 412 more IOA items available (file, library, argument, input value, pattern, network port). Please use our online service to access the data.

## References

The following list contains _external sources_ which discuss the actor and the associated activities:

* https://blog.netlab.360.com/yi-jing-you-xxxge-jia-zu-de-botnetli-yong-log4shelllou-dong-chuan-bo-wei-da-bu-ding-de-gan-jin-liao/

## Literature

The following _articles_ explain our unique predictive cyber threat intelligence:

* [VulDB Cyber Threat Intelligence Documentation](https://vuldb.com/?kb.cti)
* [Cyber Threat Intelligence - Early Anticipation of Attacks](https://www.scip.ch/en/?labs.20201022)

## License

(c) [1997-2024](https://vuldb.com/?kb.changelog) by [vuldb.com](https://vuldb.com/?kb.about). All data on this page is shared under the license [CC BY-NC-SA 4.0](https://creativecommons.org/licenses/by-nc-sa/4.0/). Questions? Check the [FAQ](https://vuldb.com/?kb.faq), read the [documentation](https://vuldb.com/?kb) or [contact us](https://vuldb.com/?contact)!
