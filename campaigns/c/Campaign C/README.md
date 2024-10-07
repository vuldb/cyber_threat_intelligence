# Campaign C - Cyber Threat Intelligence

These _indicators_ were reported, collected, and generated during the [VulDB CTI analysis](https://vuldb.com/?kb.cti) of the campaign known as _Campaign C_. The _activity monitoring_ correlates data from social media, forums, chat rooms, and darknet markets. It helps to determine associated actors, specific activities, expected intentions, emerging research, and ongoing attacks. Our unique _predictive model_ uses _big data_ to forecast activities and their characteristics.

_Live data_ and more _analysis capabilities_ are available at [https://vuldb.com/?actor](https://vuldb.com/?actor)

## Countries

These _countries_ are directly (e.g. origin of attacks) or indirectly (e.g. access by proxy) associated with Campaign C:

* [CN](https://vuldb.com/?country.cn)
* [US](https://vuldb.com/?country.us)
* [RU](https://vuldb.com/?country.ru)
* ...

There are 10 more country items available. Please use our online service to access the data.

## Actors

These _actors_ are associated with Campaign C or other actors linked to the campaign.

ID | Actor | Confidence
-- | ----- | ----------
1 | [Kwampirs](https://vuldb.com/?actor.kwampirs) | High

## IOC - Indicator of Compromise

These _indicators of compromise_ (IOC) indicate associated network resources which are known to be part of research and attack activities of Campaign C.

ID | IP address | Hostname | Actor | Confidence
-- | ---------- | -------- | ----- | ----------
1 | [9.72.55.135](https://vuldb.com/?ip.9.72.55.135) | - | [Kwampirs](https://vuldb.com/?actor.kwampirs) | High
2 | [10.12.122.62](https://vuldb.com/?ip.10.12.122.62) | - | [Kwampirs](https://vuldb.com/?actor.kwampirs) | High
3 | [15.50.42.142](https://vuldb.com/?ip.15.50.42.142) | - | [Kwampirs](https://vuldb.com/?actor.kwampirs) | High
4 | [16.61.28.46](https://vuldb.com/?ip.16.61.28.46) | - | [Kwampirs](https://vuldb.com/?actor.kwampirs) | High
5 | [17.129.132.89](https://vuldb.com/?ip.17.129.132.89) | - | [Kwampirs](https://vuldb.com/?actor.kwampirs) | High
6 | [18.42.73.26](https://vuldb.com/?ip.18.42.73.26) | - | [Kwampirs](https://vuldb.com/?actor.kwampirs) | High
7 | [20.93.133.52](https://vuldb.com/?ip.20.93.133.52) | - | [Kwampirs](https://vuldb.com/?actor.kwampirs) | High
8 | [21.58.89.27](https://vuldb.com/?ip.21.58.89.27) | - | [Kwampirs](https://vuldb.com/?actor.kwampirs) | High
9 | [21.88.128.66](https://vuldb.com/?ip.21.88.128.66) | - | [Kwampirs](https://vuldb.com/?actor.kwampirs) | High
10 | ... | ... | ... | ...

There are 37 more IOC items available. Please use our online service to access the data.

## TTP - Tactics, Techniques, Procedures

_Tactics, techniques, and procedures_ (TTP) summarize the suspected MITRE ATT&CK techniques used within Campaign C. This data is unique as it uses our predictive model for actor profiling.

ID | Technique | Weakness | Description | Confidence
-- | --------- | -------- | ----------- | ----------
1 | T1006 | CWE-21, CWE-22, CWE-23, CWE-24, CWE-29, CWE-425 | Path Traversal | High
2 | T1055 | CWE-74 | Improper Neutralization of Data within XPath Expressions | High
3 | T1059 | CWE-94, CWE-1321 | Argument Injection | High
4 | T1059.007 | CWE-79, CWE-80 | Cross Site Scripting | High
5 | T1068 | CWE-250, CWE-264, CWE-269, CWE-273, CWE-284 | Execution with Unnecessary Privileges | High
6 | ... | ... | ... | ...

There are 19 more TTP items available. Please use our online service to access the data.

## IOA - Indicator of Attack

These _indicators of attack_ (IOA) list the potential fragments used for technical activities like reconnaissance, exploitation, privilege escalation, and exfiltration during Campaign C. This data is unique as it uses our predictive model for actor profiling.

ID | Type | Indicator | Confidence
-- | ---- | --------- | ----------
1 | File | `/?import` | Medium
2 | File | `/act/ActDao.xml` | High
3 | File | `/admin.php?p=/Area/index#tab=t2` | High
4 | File | `/admin/` | Low
5 | File | `/admin/admin-update-employee.php` | High
6 | File | `/admin/list_resource_icon.php?action=delete` | High
7 | File | `/admin/singlelogin.php` | High
8 | File | `/ajax.php?action=read_msg` | High
9 | File | `/ajax/check_medicine_name.php` | High
10 | File | `/api/clusters/local/topics/{topic}/messages` | High
11 | File | `/API/info` | Medium
12 | File | `/api/sys/login` | High
13 | File | `/bcms/admin/?page=user/manage_user` | High
14 | File | `/cgi-bin/ExportAllSettings.sh` | High
15 | File | `/cgi-bin/supervisor/adcommand.cgi` | High
16 | File | `/cgi-bin/tosei_kikai.php` | High
17 | File | `/cgi/networkDiag.cgi` | High
18 | File | `/debug/pprof` | Medium
19 | File | `/detailed.php` | High
20 | File | `/dist/index.js` | High
21 | File | `/DXR.axd` | Medium
22 | File | `/em/console/logon/logon` | High
23 | File | `/env` | Low
24 | File | `/EXCU_SHELL` | Medium
25 | File | `/forum/away.php` | High
26 | File | `/general/email/inbox/delete_webmail.php` | High
27 | File | `/goform/form2systime.cgi` | High
28 | File | `/goform/modifyDhcpRule` | High
29 | File | `/goform/ModifyPppAuthWhiteMac` | High
30 | File | `/goform/net\_Web\_get_value` | High
31 | File | `/goform/SetNetControlList` | High
32 | File | `/goform/setStaOffline` | High
33 | File | `/goform/WizardHandle` | High
34 | File | `/GponForm/usb_restore_Form?script/` | High
35 | File | `/group1/uploa` | High
36 | File | `/hedwig.cgi` | Medium
37 | File | `/list` | Low
38 | File | `/login.php?m=admin&c=Field&a=channel_edit` | High
39 | File | `/manage/IPSetup.php` | High
40 | File | `/modules/profile/index.php` | High
41 | File | `/nagiosxi/admin/banner_message-ajaxhelper.php` | High
42 | File | `/net/sched/cls_fw.c` | High
43 | File | `/patient/appointment.php` | High
44 | ... | ... | ...

There are 381 more IOA items available (file, library, argument, input value, pattern, network port). Please use our online service to access the data.

## References

The following list contains _external sources_ which discuss the campaign and the associated activities:

* https://blog.reversinglabs.com/hubfs/Blog/IOC%20list/Campaign_C_IOC.txt

## Literature

The following _articles_ explain our unique predictive cyber threat intelligence:

* [VulDB Cyber Threat Intelligence Documentation](https://vuldb.com/?kb.cti)
* [Cyber Threat Intelligence - Early Anticipation of Attacks](https://www.scip.ch/en/?labs.20201022)

## License

(c) [1997-2024](https://vuldb.com/?kb.changelog) by [vuldb.com](https://vuldb.com/?kb.about). All data on this page is shared under the license [CC BY-NC-SA 4.0](https://creativecommons.org/licenses/by-nc-sa/4.0/). Questions? Check the [FAQ](https://vuldb.com/?kb.faq), read the [documentation](https://vuldb.com/?kb) or [contact us](https://vuldb.com/?contact)!
