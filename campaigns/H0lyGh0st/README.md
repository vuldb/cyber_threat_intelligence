# H0lyGh0st - Cyber Threat Intelligence

These _indicators_ were reported, collected, and generated during the [VulDB CTI analysis](https://vuldb.com/?kb.cti) of the campaign known as _H0lyGh0st_. The _activity monitoring_ correlates data from social media, forums, chat rooms, and darknet markets. It helps to determine associated actors, specific activities, expected intentions, emerging research, and ongoing attacks. Our unique _predictive model_ uses _big data_ to forecast activities and their characteristics.

_Live data_ and more _analysis capabilities_ are available at [https://vuldb.com/?actor](https://vuldb.com/?actor)

## Countries

These _countries_ are directly (e.g. origin of attacks) or indirectly (e.g. access by proxy) associated with H0lyGh0st:

* [US](https://vuldb.com/?country.us)
* [VN](https://vuldb.com/?country.vn)
* [CN](https://vuldb.com/?country.cn)
* ...

There are 10 more country items available. Please use our online service to access the data.

## Actors

These _actors_ are associated with H0lyGh0st or other actors linked to the campaign.

ID | Actor | Confidence
-- | ----- | ----------
1 | [DEV-0530](https://vuldb.com/?actor.dev-0530) | High
2 | [H0lyGh0st](https://vuldb.com/?actor.h0lygh0st) | High

## IOC - Indicator of Compromise

These _indicators of compromise_ (IOC) indicate associated network resources which are known to be part of research and attack activities of H0lyGh0st.

ID | IP address | Hostname | Actor | Confidence
-- | ---------- | -------- | ----- | ----------
1 | [127.0.0.1](https://vuldb.com/?ip.127.0.0.1) | localhost | [H0lyGh0st](https://vuldb.com/?actor.h0lygh0st) | High
2 | [193.56.29.123](https://vuldb.com/?ip.193.56.29.123) | - | [H0lyGh0st](https://vuldb.com/?actor.h0lygh0st) | High

## TTP - Tactics, Techniques, Procedures

_Tactics, techniques, and procedures_ (TTP) summarize the suspected MITRE ATT&CK techniques used within H0lyGh0st. This data is unique as it uses our predictive model for actor profiling.

ID | Technique | Weakness | Description | Confidence
-- | --------- | -------- | ----------- | ----------
1 | T1006 | CWE-21, CWE-22, CWE-23 | Pathname Traversal | High
2 | T1040 | CWE-294 | Authentication Bypass by Capture-replay | High
3 | T1055 | CWE-74 | Injection | High
4 | T1059 | CWE-88, CWE-94 | Cross Site Scripting | High
5 | T1059.007 | CWE-79, CWE-80 | Cross Site Scripting | High
6 | ... | ... | ... | ...

There are 21 more TTP items available. Please use our online service to access the data.

## IOA - Indicator of Attack

These _indicators of attack_ (IOA) list the potential fragments used for technical activities like reconnaissance, exploitation, privilege escalation, and exfiltration during H0lyGh0st. This data is unique as it uses our predictive model for actor profiling.

ID | Type | Indicator | Confidence
-- | ---- | --------- | ----------
1 | File | `/adfs/ls` | Medium
2 | File | `/admin.php?page=batch_manager&mode=unit` | High
3 | File | `/admin/users_add.php` | High
4 | File | `/administration/settings_registration.php` | High
5 | File | `/appConfig/userDB.json` | High
6 | File | `/authUserAction!edit.action` | High
7 | File | `/bd_genie_create_account.cgi` | High
8 | File | `/c/macho_reader.c` | High
9 | File | `/cgi-bin/luci/api/auth` | High
10 | File | `/cgi-bin/luci/api/diagnose` | High
11 | File | `/claire_blake` | High
12 | File | `/debug/pprof` | Medium
13 | File | `/defaultui/player/modern.html` | High
14 | File | `/etc/config/image_sign` | High
15 | File | `/etc/groups` | Medium
16 | File | `/etc/init0.d/S80telnetd.sh` | High
17 | File | `/etc/shadow.sample` | High
18 | File | `/foms/place-order.php` | High
19 | File | `/forum/away.php` | High
20 | File | `/ghost/preview` | High
21 | File | `/goform/aspForm` | High
22 | File | `/goform/SetIpMacBind` | High
23 | File | `/htdocs/utils/Files.php` | High
24 | File | `/jfinal_cms/system/role/list` | High
25 | File | `/librarian/edit_book_details.php` | High
26 | File | `/Main_Login.asp?flag=1&productname=RT-AC88U&url=/downloadmaster/task.asp` | High
27 | File | `/master/index.php` | High
28 | File | `/mgmt/tm/util/bash` | High
29 | File | `/mkshop/Men/profile.php` | High
30 | File | `/omps/seller` | Medium
31 | File | `/opt/zimbra/jetty/webapps/zimbra/public` | High
32 | File | `/pages/faculty_sched.php` | High
33 | File | `/pages/processlogin.php` | High
34 | File | `/php/passport/index.php` | High
35 | ... | ... | ...

There are 297 more IOA items available (file, library, argument, input value, pattern, network port). Please use our online service to access the data.

## References

The following list contains _external sources_ which discuss the campaign and the associated activities:

* https://community.blueliv.com/#!/s/62d1143282df41552632f957
* https://www.microsoft.com/security/blog/2022/07/14/north-korean-threat-actor-targets-small-and-midsize-businesses-with-h0lygh0st-ransomware/

## Literature

The following _articles_ explain our unique predictive cyber threat intelligence:

* [VulDB Cyber Threat Intelligence Documentation](https://vuldb.com/?kb.cti)
* [Cyber Threat Intelligence - Early Anticipation of Attacks](https://www.scip.ch/en/?labs.20201022)

## License

(c) [1997-2022](https://vuldb.com/?kb.changelog) by [vuldb.com](https://vuldb.com/?kb.about). All data on this page is shared under the license [CC BY-NC-SA 4.0](https://creativecommons.org/licenses/by-nc-sa/4.0/). Questions? Check the [FAQ](https://vuldb.com/?kb.faq), read the [documentation](https://vuldb.com/?kb) or [contact us](https://vuldb.com/?contact)!
