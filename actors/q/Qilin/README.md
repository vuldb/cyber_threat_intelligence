# Qilin - Cyber Threat Intelligence

These _indicators_ were reported, collected, and generated during the [VulDB CTI analysis](https://vuldb.com/?kb.cti) of the actor known as [Qilin](https://vuldb.com/?actor.qilin). The _activity monitoring_ correlates data from social media, forums, chat rooms, and darknet markets. It helps to determine associated actors, specific activities, expected intentions, emerging research, and ongoing attacks. Our unique _predictive model_ uses _big data_ to forecast activities and their characteristics.

_Live data_ and more _analysis capabilities_ are available at [https://vuldb.com/?actor.qilin](https://vuldb.com/?actor.qilin)

## Countries

These _countries_ are directly (e.g. origin of attacks) or indirectly (e.g. access by proxy) associated with Qilin:

* [US](https://vuldb.com/?country.us)
* [CN](https://vuldb.com/?country.cn)
* [NL](https://vuldb.com/?country.nl)
* ...

There are 19 more country items available. Please use our online service to access the data.

## IOC - Indicator of Compromise

These _indicators of compromise_ (IOC) indicate associated network resources which are known to be part of research and attack activities of Qilin.

ID | IP address | Hostname | Campaign | Confidence
-- | ---------- | -------- | -------- | ----------
1 | [31.41.244.100](https://vuldb.com/?ip.31.41.244.100) | - | - | High
2 | [91.238.181.230](https://vuldb.com/?ip.91.238.181.230) | - | - | High
3 | [93.115.25.139](https://vuldb.com/?ip.93.115.25.139) | - | - | High
4 | ... | ... | ... | ...

There are 11 more IOC items available. Please use our online service to access the data.

## TTP - Tactics, Techniques, Procedures

_Tactics, techniques, and procedures_ (TTP) summarize the suspected MITRE ATT&CK techniques used by _Qilin_. This data is unique as it uses our predictive model for actor profiling.

ID | Technique | Weakness | Description | Confidence
-- | --------- | -------- | ----------- | ----------
1 | T1006 | CWE-21, CWE-22, CWE-28, CWE-35, CWE-36 | Path Traversal | High
2 | T1059 | CWE-94 | Argument Injection | High
3 | T1059.007 | CWE-79, CWE-80 | Cross Site Scripting | High
4 | T1068 | CWE-264, CWE-266, CWE-269, CWE-284 | Execution with Unnecessary Privileges | High
5 | ... | ... | ... | ...

There are 18 more TTP items available. Please use our online service to access the data.

## IOA - Indicator of Attack

These _indicators of attack_ (IOA) list the potential fragments used for technical activities like reconnaissance, exploitation, privilege escalation, and exfiltration by Qilin. This data is unique as it uses our predictive model for actor profiling.

ID | Type | Indicator | Confidence
-- | ---- | --------- | ----------
1 | File | `/Account/login.php` | High
2 | File | `/admin/` | Low
3 | File | `/admin/?page=categories/view_category` | High
4 | File | `/Admin/changepassword.php` | High
5 | File | `/admin/court` | Medium
6 | File | `/Admin/createClass.php` | High
7 | File | `/admin/div_data/data` | High
8 | File | `/admin/edit_manufacturer.php` | High
9 | File | `/admin/login.php` | High
10 | File | `/admin/maintenance/manage_brand.php` | High
11 | File | `/admin/maintenance/view_designation.php` | High
12 | File | `/admin/media_folders` | High
13 | File | `/admin/memberOnline_deal.php?mudi=del&dataType=&dataID=6` | High
14 | File | `/admin/orders/view_order.php` | High
15 | File | `/admin/problem_judge.php` | High
16 | File | `/admin/robot.php` | High
17 | File | `/admin/SysModule/upload/ajaxmodel/upload/uploadfilepath/sysmodule_1` | High
18 | File | `/admin/users.php` | High
19 | File | `/ajax.php` | Medium
20 | File | `/api/controllers/merchant/shop/PosterController.php` | High
21 | File | `/APR/signup.php` | High
22 | File | `/AttendanceMonitoring/report/index.php` | High
23 | File | `/authMonitCallcenter` | High
24 | File | `/backend/register.php` | High
25 | File | `/blog/blog.php` | High
26 | File | `/bloodrequest.php` | High
27 | File | `/catalog/admin/categories.php?cPath=&action=new_product` | High
28 | File | `/cgi-bin/cstecgi.cgi` | High
29 | File | `/cgi-bin/hd_config.cgi` | High
30 | File | `/cgi-bin/nas_sharing.cgi` | High
31 | File | `/cgi-bin/photocenter_mgr.cgi` | High
32 | File | `/cgi-bin/wlogin.cgi` | High
33 | File | `/classes/Master.php` | High
34 | File | `/classes/Master.php?f=delete_category` | High
35 | File | `/classes/Master.php?f=log_employee` | High
36 | File | `/classes/Master.php?f=save_medicine` | High
37 | File | `/classes/Master.php?f=save_package` | High
38 | File | `/classes/SystemSettings.php?f=update_settings` | High
39 | File | `/classes/Users.php?f=save` | High
40 | File | `/College/admin/teacher.php` | High
41 | File | `/conf/app.conf` | High
42 | File | `/E-mobile/App/System/File/downfile.php` | High
43 | File | `/Electron/download` | High
44 | File | `/endpoint/add-task.php` | High
45 | File | `/endpoint/delete-calorie.php` | High
46 | File | `/file/upload/1` | High
47 | File | `/filter.php` | Medium
48 | File | `/forum/away.php` | High
49 | File | `/goform/formdumpeasysetup` | High
50 | File | `/goform/formSetWanL2TP` | High
51 | File | `/goform/SetIpMacBind` | High
52 | File | `/goform/VirtualSer` | High
53 | File | `/goform/wifiSSIDset` | High
54 | File | `/index.php` | Medium
55 | File | `/index.php?action=profile;u=2;area=showalerts;do=read` | High
56 | File | `/js/player/dmplayer/dmku/?ac=edit` | High
57 | ... | ... | ...

There are 498 more IOA items available (file, library, argument, input value, pattern, network port). Please use our online service to access the data.

## References

The following list contains _external sources_ which discuss the actor and the associated activities:

* https://blog.bushidotoken.net/2024/06/tracking-adversaries-qilin-raas.html
* https://darktrace.com/blog/a-busy-agenda-darktraces-detection-of-qilin-ransomware-as-a-service-operator

## Literature

The following _articles_ explain our unique predictive cyber threat intelligence:

* [VulDB Cyber Threat Intelligence Documentation](https://vuldb.com/?kb.cti)
* [Cyber Threat Intelligence - Early Anticipation of Attacks](https://www.scip.ch/en/?labs.20201022)

## License

(c) [1997-2024](https://vuldb.com/?kb.changelog) by [vuldb.com](https://vuldb.com/?kb.about). All data on this page is shared under the license [CC BY-NC-SA 4.0](https://creativecommons.org/licenses/by-nc-sa/4.0/). Questions? Check the [FAQ](https://vuldb.com/?kb.faq), read the [documentation](https://vuldb.com/?kb) or [contact us](https://vuldb.com/?contact)!
