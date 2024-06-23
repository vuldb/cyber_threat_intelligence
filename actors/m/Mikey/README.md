# Mikey - Cyber Threat Intelligence

These _indicators_ were reported, collected, and generated during the [VulDB CTI analysis](https://vuldb.com/?kb.cti) of the actor known as [Mikey](https://vuldb.com/?actor.mikey). The _activity monitoring_ correlates data from social media, forums, chat rooms, and darknet markets. It helps to determine associated actors, specific activities, expected intentions, emerging research, and ongoing attacks. Our unique _predictive model_ uses _big data_ to forecast activities and their characteristics.

_Live data_ and more _analysis capabilities_ are available at [https://vuldb.com/?actor.mikey](https://vuldb.com/?actor.mikey)

## Countries

These _countries_ are directly (e.g. origin of attacks) or indirectly (e.g. access by proxy) associated with Mikey:

* [IN](https://vuldb.com/?country.in)
* [CN](https://vuldb.com/?country.cn)
* [US](https://vuldb.com/?country.us)
* ...

There are 3 more country items available. Please use our online service to access the data.

## IOC - Indicator of Compromise

These _indicators of compromise_ (IOC) indicate associated network resources which are known to be part of research and attack activities of Mikey.

ID | IP address | Hostname | Campaign | Confidence
-- | ---------- | -------- | -------- | ----------
1 | [8.208.22.49](https://vuldb.com/?ip.8.208.22.49) | - | - | High
2 | [20.45.1.107](https://vuldb.com/?ip.20.45.1.107) | - | - | High
3 | [24.35.232.189](https://vuldb.com/?ip.24.35.232.189) | 24-35-232-189.fidnet.com | - | High
4 | [24.42.115.69](https://vuldb.com/?ip.24.42.115.69) | - | - | High
5 | [40.67.189.14](https://vuldb.com/?ip.40.67.189.14) | - | - | High
6 | [40.90.247.210](https://vuldb.com/?ip.40.90.247.210) | - | - | High
7 | [40.91.124.111](https://vuldb.com/?ip.40.91.124.111) | - | - | High
8 | [43.231.4.7](https://vuldb.com/?ip.43.231.4.7) | - | - | High
9 | [43.241.73.221](https://vuldb.com/?ip.43.241.73.221) | kt-spk-a917.pointdnshere.com | - | High
10 | [46.4.52.109](https://vuldb.com/?ip.46.4.52.109) | witntech.dev | - | High
11 | [46.29.160.26](https://vuldb.com/?ip.46.29.160.26) | savewindow.ru | - | High
12 | [46.128.161.129](https://vuldb.com/?ip.46.128.161.129) | 46.128.161.129.dyn.pyur.net | - | High
13 | [46.249.59.122](https://vuldb.com/?ip.46.249.59.122) | mailer.abbbccc.com | - | High
14 | [49.124.15.147](https://vuldb.com/?ip.49.124.15.147) | - | - | High
15 | [52.1.22.171](https://vuldb.com/?ip.52.1.22.171) | ec2-52-1-22-171.compute-1.amazonaws.com | - | Medium
16 | [52.36.131.229](https://vuldb.com/?ip.52.36.131.229) | ec2-52-36-131-229.us-west-2.compute.amazonaws.com | - | Medium
17 | [54.183.102.22](https://vuldb.com/?ip.54.183.102.22) | ec2-54-183-102-22.us-west-1.compute.amazonaws.com | - | Medium
18 | [54.248.125.247](https://vuldb.com/?ip.54.248.125.247) | ec2-54-248-125-247.ap-northeast-1.compute.amazonaws.com | - | Medium
19 | ... | ... | ... | ...

There are 70 more IOC items available. Please use our online service to access the data.

## TTP - Tactics, Techniques, Procedures

_Tactics, techniques, and procedures_ (TTP) summarize the suspected MITRE ATT&CK techniques used by _Mikey_. This data is unique as it uses our predictive model for actor profiling.

ID | Technique | Weakness | Description | Confidence
-- | --------- | -------- | ----------- | ----------
1 | T1006 | CWE-21, CWE-22, CWE-23, CWE-24 | Path Traversal | High
2 | T1040 | CWE-319 | Authentication Bypass by Capture-replay | High
3 | T1055 | CWE-74 | Improper Neutralization of Data within XPath Expressions | High
4 | T1059 | CWE-88, CWE-94, CWE-1321 | Argument Injection | High
5 | T1059.007 | CWE-79, CWE-80 | Cross Site Scripting | High
6 | ... | ... | ... | ...

There are 20 more TTP items available. Please use our online service to access the data.

## IOA - Indicator of Attack

These _indicators of attack_ (IOA) list the potential fragments used for technical activities like reconnaissance, exploitation, privilege escalation, and exfiltration by Mikey. This data is unique as it uses our predictive model for actor profiling.

ID | Type | Indicator | Confidence
-- | ---- | --------- | ----------
1 | File | `.FBCIndex` | Medium
2 | File | `/.vnc/sesman_${username}_passwd` | High
3 | File | `/admin/` | Low
4 | File | `/admin/addemployee.php` | High
5 | File | `/admin/add_exercises.php` | High
6 | File | `/admin/add_trainers.php` | High
7 | File | `/admin/admin-profile.php` | High
8 | File | `/admin/admin_user.php` | High
9 | File | `/admin/api/admin/articles/` | High
10 | File | `/admin/api/theme-edit/` | High
11 | File | `/admin/borrow_add.php` | High
12 | File | `/admin/category_row.php` | High
13 | File | `/admin/communitymanagement.php` | High
14 | File | `/Admin/createClass.php` | High
15 | File | `/admin/div_data/delete?divId=9` | High
16 | File | `/admin/edit.php` | High
17 | File | `/admin/index.php?page=categories` | High
18 | File | `/admin/login.php` | High
19 | File | `/admin/request-received-bydonar.php` | High
20 | File | `/admin/settings.php` | High
21 | File | `/admin/students/manage.php` | High
22 | File | `/admin/success_story.php` | High
23 | File | `/api/public/signup` | High
24 | File | `/api/v1/attack` | High
25 | File | `/api/v1/bait/set` | High
26 | File | `/api/v2/open/tablesInfo` | High
27 | File | `/boaform/device_reset.cgi` | High
28 | File | `/boaform/wlan_basic_set.cgi` | High
29 | File | `/category.php` | High
30 | File | `/cgi-bin/nas_sharing.cgi` | High
31 | File | `/classes/Users.php?f=save` | High
32 | File | `/course/filterRecords/` | High
33 | File | `/csms/?page=contact_us` | High
34 | File | `/csms/admin/?page=user/list` | High
35 | File | `/cwms/classes/Master.php?f=save_contact` | High
36 | File | `/ebics-server/ebics.aspx` | High
37 | File | `/edituser.php` | High
38 | File | `/employeeview.php` | High
39 | File | `/Employer/EditProfile.php` | High
40 | File | `/Employer/ManageJob.php` | High
41 | File | `/endpoint/update-computer.php` | High
42 | File | `/forum/away.php` | High
43 | File | `/FuguHub/cmsdocs/` | High
44 | File | `/goform/SetSysTimeCfg` | High
45 | File | `/inc/jquery/uploadify/uploadify.php` | High
46 | File | `/index.jsp#settings` | High
47 | File | `/inquiries/view_inquiry.php` | High
48 | File | `/install/` | Medium
49 | File | `/intern/controller.php` | High
50 | File | `/investigation/delete/` | High
51 | File | `/leave_system/classes/SystemSettings.php?f=update_settings` | High
52 | File | `/login.php` | Medium
53 | File | `/loginVaLidation.php` | High
54 | File | `/member/member_edit.php` | High
55 | File | `/mims/app/addcustomerHandler.php` | High
56 | File | `/mkshope/login.php` | High
57 | File | `/myprofile.php` | High
58 | File | `/nagiosxi/admin/banner_message-ajaxhelper.php` | High
59 | ... | ... | ...

There are 512 more IOA items available (file, library, argument, input value, pattern, network port). Please use our online service to access the data.

## References

The following list contains _external sources_ which discuss the actor and the associated activities:

* https://blog.talosintelligence.com/2018/10/threat-roundup-1012-1019.html
* https://blog.talosintelligence.com/2018/11/threat-roundup-1019-1102.html
* https://blog.talosintelligence.com/2019/02/threat-roundup-0125-0201.html
* https://blog.talosintelligence.com/2019/04/threat-roundup-0419-to-0426.html
* https://blog.talosintelligence.com/2020/02/threat-roundup-0214-0221.html
* https://blog.talosintelligence.com/2020/05/threat-roundup-0522-0529.html
* https://blog.talosintelligence.com/2020/06/threat-roundup-0529-0605.html
* https://blog.talosintelligence.com/threat-roundup-1028-1104/

## Literature

The following _articles_ explain our unique predictive cyber threat intelligence:

* [VulDB Cyber Threat Intelligence Documentation](https://vuldb.com/?kb.cti)
* [Cyber Threat Intelligence - Early Anticipation of Attacks](https://www.scip.ch/en/?labs.20201022)

## License

(c) [1997-2024](https://vuldb.com/?kb.changelog) by [vuldb.com](https://vuldb.com/?kb.about). All data on this page is shared under the license [CC BY-NC-SA 4.0](https://creativecommons.org/licenses/by-nc-sa/4.0/). Questions? Check the [FAQ](https://vuldb.com/?kb.faq), read the [documentation](https://vuldb.com/?kb) or [contact us](https://vuldb.com/?contact)!
