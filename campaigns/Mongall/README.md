# Mongall - Cyber Threat Intelligence

These _indicators_ were reported, collected, and generated during the [VulDB CTI analysis](https://vuldb.com/?kb.cti) of the campaign known as _Mongall_. The _activity monitoring_ correlates data from social media, forums, chat rooms, and darknet markets. It helps to determine associated actors, specific activities, expected intentions, emerging research, and ongoing attacks. Our unique _predictive model_ uses _big data_ to forecast activities and their characteristics.

_Live data_ and more _analysis capabilities_ are available at [https://vuldb.com/?actor](https://vuldb.com/?actor)

## Countries

These _countries_ are directly (e.g. origin of attacks) or indirectly (e.g. access by proxy) associated with Mongall:

* [US](https://vuldb.com/?country.us)
* [CN](https://vuldb.com/?country.cn)

## Actors

These _actors_ are associated with Mongall or other actors linked to the campaign.

ID | Actor | Confidence
-- | ----- | ----------
1 | [Aoqin Dragon](https://vuldb.com/?actor.aoqin_dragon) | High

## IOC - Indicator of Compromise

These _indicators of compromise_ (IOC) indicate associated network resources which are known to be part of research and attack activities of Mongall.

ID | IP address | Hostname | Actor | Confidence
-- | ---------- | -------- | ----- | ----------
1 | [59.188.234.233](https://vuldb.com/?ip.59.188.234.233) | - | [Aoqin Dragon](https://vuldb.com/?actor.aoqin_dragon) | High
2 | [64.27.4.19](https://vuldb.com/?ip.64.27.4.19) | secure.link192.com | [Aoqin Dragon](https://vuldb.com/?actor.aoqin_dragon) | High
3 | [64.27.4.157](https://vuldb.com/?ip.64.27.4.157) | unassigned.calpop.com | [Aoqin Dragon](https://vuldb.com/?actor.aoqin_dragon) | High
4 | ... | ... | ... | ...

There are 2 more IOC items available. Please use our online service to access the data.

## TTP - Tactics, Techniques, Procedures

_Tactics, techniques, and procedures_ (TTP) summarize the suspected MITRE ATT&CK techniques used within Mongall. This data is unique as it uses our predictive model for actor profiling.

ID | Technique | Weakness | Description | Confidence
-- | --------- | -------- | ----------- | ----------
1 | T1059.007 | CWE-79, CWE-80 | Cross Site Scripting | High
2 | T1068 | CWE-264, CWE-284 | Execution with Unnecessary Privileges | High
3 | T1110.001 | CWE-798 | Improper Restriction of Excessive Authentication Attempts | High
4 | ... | ... | ... | ...

There are 6 more TTP items available. Please use our online service to access the data.

## IOA - Indicator of Attack

These _indicators of attack_ (IOA) list the potential fragments used for technical activities like reconnaissance, exploitation, privilege escalation, and exfiltration during Mongall. This data is unique as it uses our predictive model for actor profiling.

ID | Type | Indicator | Confidence
-- | ---- | --------- | ----------
1 | File | `#!/system` | Medium
2 | File | `%PROGRAMFILES%\Cylance\Desktop\log` | High
3 | File | `/admin/` | Low
4 | File | `/admin/AddNewState/Add_State` | High
5 | File | `/category.php` | High
6 | File | `/data/syslog.filter.json` | High
7 | File | `/details.php` | Medium
8 | File | `/etc/stunnel.key` | High
9 | File | `/FlexiCapture12/Login/Server/SevaUserProfile` | High
10 | File | `/help/lccon.nsf/` | High
11 | File | `/jsp/xmlhttp/AjaxResponse.jsp` | High
12 | File | `/login.html` | Medium
13 | File | `/member/settings_account.php` | High
14 | File | `/net/mac80211/mac80211/sta_info.c` | High
15 | File | `/otweb/OTPClientLogin` | High
16 | File | `/product.php` | Medium
17 | File | `/tests/add_duration_test.php` | High
18 | File | `/tests/all_tests.php` | High
19 | File | `/var/run/storage_account_root` | High
20 | File | `AccessPoint.aspx` | High
21 | File | `account.asp` | Medium
22 | File | `activate.php` | Medium
23 | File | `addevent.php` | Medium
24 | File | `adherents/cartes/carte.php` | High
25 | File | `admin.php` | Medium
26 | File | `admin/` | Low
27 | File | `admin/?/plugin/file_manager/upload` | High
28 | File | `admin/app/physical/physical.php` | High
29 | File | `admin/edit.php` | High
30 | File | `admin/eventlist.php` | High
31 | File | `admin/index.php` | High
32 | File | `admin/languages.php` | High
33 | File | `admin/manufacturers.php` | High
34 | File | `admin/newsletters.php` | High
35 | File | `admin/products_attributes.php` | High
36 | File | `admin/products_expected.php` | High
37 | File | `admin/reviews.php` | High
38 | File | `admin/worklist/worklist_edit.asp` | High
39 | File | `administrator/index.php` | High
40 | File | `ad_popup.php` | Medium
41 | File | `afd.sys` | Low
42 | File | `agent.exe` | Medium
43 | File | `apps/calendar/export.php` | High
44 | File | `archive.php` | Medium
45 | File | `ask_chat.php` | Medium
46 | File | `attachment.cgi` | High
47 | File | `basic.html#ipsettings` | High
48 | File | `block-forums.php` | High
49 | File | `bouncedcc.cpp` | High
50 | File | `BS.Player` | Medium
51 | ... | ... | ...

There are 446 more IOA items available (file, library, argument, input value, pattern, network port). Please use our online service to access the data.

## References

The following list contains _external sources_ which discuss the campaign and the associated activities:

* https://www.sentinelone.com/labs/aoqin-dragon-newly-discovered-chinese-linked-apt-has-been-quietly-spying-on-organizations-for-10-years/

## Literature

The following _articles_ explain our unique predictive cyber threat intelligence:

* [VulDB Cyber Threat Intelligence Documentation](https://vuldb.com/?kb.cti)
* [Cyber Threat Intelligence - Early Anticipation of Attacks](https://www.scip.ch/en/?labs.20201022)

## License

(c) [1997-2022](https://vuldb.com/?kb.changelog) by [vuldb.com](https://vuldb.com/?kb.about). All data on this page is shared under the license [CC BY-NC-SA 4.0](https://creativecommons.org/licenses/by-nc-sa/4.0/). Questions? Check the [FAQ](https://vuldb.com/?kb.faq), read the [documentation](https://vuldb.com/?kb) or [contact us](https://vuldb.com/?contact)!
