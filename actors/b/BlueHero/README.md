# BlueHero - Cyber Threat Intelligence

These _indicators_ were reported, collected, and generated during the [VulDB CTI analysis](https://vuldb.com/?kb.cti) of the actor known as [BlueHero](https://vuldb.com/?actor.bluehero). The _activity monitoring_ correlates data from social media, forums, chat rooms, and darknet markets. It helps to determine associated actors, specific activities, expected intentions, emerging research, and ongoing attacks. Our unique _predictive model_ uses _big data_ to forecast activities and their characteristics.

_Live data_ and more _analysis capabilities_ are available at [https://vuldb.com/?actor.bluehero](https://vuldb.com/?actor.bluehero)

## Countries

These _countries_ are directly (e.g. origin of attacks) or indirectly (e.g. access by proxy) associated with BlueHero:

* [IN](https://vuldb.com/?country.in)
* [CN](https://vuldb.com/?country.cn)

## IOC - Indicator of Compromise

These _indicators of compromise_ (IOC) indicate associated network resources which are known to be part of research and attack activities of BlueHero.

ID | IP address | Hostname | Campaign | Confidence
-- | ---------- | -------- | -------- | ----------
1 | [2.5.10.1](https://vuldb.com/?ip.2.5.10.1) | - | - | High
2 | [10.3.6.0](https://vuldb.com/?ip.10.3.6.0) | - | - | High
3 | [12.1.3.0](https://vuldb.com/?ip.12.1.3.0) | - | - | High
4 | ... | ... | ... | ...

There are 14 more IOC items available. Please use our online service to access the data.

## TTP - Tactics, Techniques, Procedures

_Tactics, techniques, and procedures_ (TTP) summarize the suspected MITRE ATT&CK techniques used by _BlueHero_. This data is unique as it uses our predictive model for actor profiling.

ID | Technique | Weakness | Description | Confidence
-- | --------- | -------- | ----------- | ----------
1 | T1006 | CWE-21, CWE-22, CWE-23 | Path Traversal | High
2 | T1040 | CWE-319 | Authentication Bypass by Capture-replay | High
3 | T1055 | CWE-74 | Improper Neutralization of Data within XPath Expressions | High
4 | T1059 | CWE-88, CWE-94, CWE-1321 | Argument Injection | High
5 | T1059.007 | CWE-79, CWE-80 | Cross Site Scripting | High
6 | ... | ... | ... | ...

There are 18 more TTP items available. Please use our online service to access the data.

## IOA - Indicator of Attack

These _indicators of attack_ (IOA) list the potential fragments used for technical activities like reconnaissance, exploitation, privilege escalation, and exfiltration by BlueHero. This data is unique as it uses our predictive model for actor profiling.

ID | Type | Indicator | Confidence
-- | ---- | --------- | ----------
1 | File | `%PROGRAMDATA%\Razer\Synapse3\Service\bin` | High
2 | File | `/.vnc/sesman_${username}_passwd` | High
3 | File | `/admin/` | Low
4 | File | `/admin/add_exercises.php` | High
5 | File | `/admin/add_ikev2.php` | High
6 | File | `/admin/add_trainers.php` | High
7 | File | `/admin/admin-profile.php` | High
8 | File | `/admin/admin_user.php` | High
9 | File | `/admin/api/theme-edit/` | High
10 | File | `/admin/borrow_add.php` | High
11 | File | `/admin/category_row.php` | High
12 | File | `/admin/communitymanagement.php` | High
13 | File | `/Admin/createClass.php` | High
14 | File | `/admin/edit.php` | High
15 | File | `/admin/emp-profile-avatar.php` | High
16 | File | `/admin/index.php?page=categories` | High
17 | File | `/admin/login.php` | High
18 | File | `/admin/project/update/2` | High
19 | File | `/admin/request-received-bydonar.php` | High
20 | File | `/admin/students/manage.php` | High
21 | File | `/admin/success_story.php` | High
22 | File | `/api/v2/cli/commands` | High
23 | File | `/boaform/device_reset.cgi` | High
24 | File | `/boaform/wlan_basic_set.cgi` | High
25 | File | `/cgi-bin/cstecgi.cgi` | High
26 | File | `/cgi-bin/nas_sharing.cgi` | High
27 | File | `/classes/Master.php` | High
28 | File | `/classes/Users.php?f=save` | High
29 | File | `/course/filterRecords/` | High
30 | File | `/cwms/classes/Master.php?f=save_contact` | High
31 | File | `/debug/pprof` | Medium
32 | File | `/download/image` | High
33 | File | `/edituser.php` | High
34 | File | `/Employer/EditProfile.php` | High
35 | File | `/Employer/ManageJob.php` | High
36 | File | `/firewall/policy/` | High
37 | File | `/forum/away.php` | High
38 | File | `/FuguHub/cmsdocs/` | High
39 | File | `/goform/SetSysTimeCfg` | High
40 | File | `/hedwig.cgi` | Medium
41 | File | `/ims/login.php` | High
42 | File | `/inc/jquery/uploadify/uploadify.php` | High
43 | File | `/includes/common/require_access_recovery.php` | High
44 | File | `/index.jsp#settings` | High
45 | File | `/index.php` | Medium
46 | ... | ... | ...

There are 399 more IOA items available (file, library, argument, input value, pattern, network port). Please use our online service to access the data.

## References

The following list contains _external sources_ which discuss the actor and the associated activities:

* https://s.tencent.com/research/report/675
* https://www.zscaler.com/blogs/research/recent-bulehero-botnet-payload

## Literature

The following _articles_ explain our unique predictive cyber threat intelligence:

* [VulDB Cyber Threat Intelligence Documentation](https://vuldb.com/?kb.cti)
* [Cyber Threat Intelligence - Early Anticipation of Attacks](https://www.scip.ch/en/?labs.20201022)

## License

(c) [1997-2024](https://vuldb.com/?kb.changelog) by [vuldb.com](https://vuldb.com/?kb.about). All data on this page is shared under the license [CC BY-NC-SA 4.0](https://creativecommons.org/licenses/by-nc-sa/4.0/). Questions? Check the [FAQ](https://vuldb.com/?kb.faq), read the [documentation](https://vuldb.com/?kb) or [contact us](https://vuldb.com/?contact)!
