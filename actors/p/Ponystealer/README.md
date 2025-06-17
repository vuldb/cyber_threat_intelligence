# Ponystealer - Cyber Threat Intelligence

These _indicators_ were reported, collected, and generated during the [VulDB CTI analysis](https://vuldb.com/?kb.cti) of the actor known as [Ponystealer](https://vuldb.com/?actor.ponystealer). The _activity monitoring_ correlates data from social media, forums, chat rooms, and darknet markets. It helps to determine associated actors, specific activities, expected intentions, emerging research, and ongoing attacks. Our unique _predictive model_ uses _big data_ to forecast activities and their characteristics.

_Live data_ and more _analysis capabilities_ are available at [https://vuldb.com/?actor.ponystealer](https://vuldb.com/?actor.ponystealer)

## Countries

These _countries_ are directly (e.g. origin of attacks) or indirectly (e.g. access by proxy) associated with Ponystealer:

* [US](https://vuldb.com/?country.us)
* [CN](https://vuldb.com/?country.cn)
* [RU](https://vuldb.com/?country.ru)
* ...

There are 16 more country items available. Please use our online service to access the data.

## IOC - Indicator of Compromise

These _indicators of compromise_ (IOC) indicate associated network resources which are known to be part of research and attack activities of Ponystealer.

ID | IP address | Hostname | Campaign | Confidence
-- | ---------- | -------- | -------- | ----------
1 | [20.42.73.29](https://vuldb.com/?ip.20.42.73.29) | - | - | High
2 | [23.40.30.30](https://vuldb.com/?ip.23.40.30.30) | a23-40-30-30.deploy.static.akamaitechnologies.com | - | High
3 | [23.56.9.181](https://vuldb.com/?ip.23.56.9.181) | a23-56-9-181.deploy.static.akamaitechnologies.com | - | High
4 | [23.227.38.65](https://vuldb.com/?ip.23.227.38.65) | myshopify.com | - | High
5 | [23.238.221.30](https://vuldb.com/?ip.23.238.221.30) | - | - | High
6 | [34.240.216.169](https://vuldb.com/?ip.34.240.216.169) | ec2-34-240-216-169.eu-west-1.compute.amazonaws.com | - | Medium
7 | [35.194.164.137](https://vuldb.com/?ip.35.194.164.137) | 137.164.194.35.bc.googleusercontent.com | - | Medium
8 | [45.76.142.81](https://vuldb.com/?ip.45.76.142.81) | 45.76.142.81.vultrusercontent.com | - | Medium
9 | [47.91.170.222](https://vuldb.com/?ip.47.91.170.222) | - | - | High
10 | [47.254.67.48](https://vuldb.com/?ip.47.254.67.48) | - | - | High
11 | [50.63.202.69](https://vuldb.com/?ip.50.63.202.69) | ip-50-63-202-69.ip.secureserver.net | - | High
12 | [50.63.202.89](https://vuldb.com/?ip.50.63.202.89) | ip-50-63-202-89.ip.secureserver.net | - | High
13 | [52.5.251.20](https://vuldb.com/?ip.52.5.251.20) | ec2-52-5-251-20.compute-1.amazonaws.com | - | Medium
14 | ... | ... | ... | ...

There are 52 more IOC items available. Please use our online service to access the data.

## TTP - Tactics, Techniques, Procedures

_Tactics, techniques, and procedures_ (TTP) summarize the suspected MITRE ATT&CK techniques used by _Ponystealer_. This data is unique as it uses our predictive model for actor profiling.

ID | Technique | Weakness | Description | Confidence
-- | --------- | -------- | ----------- | ----------
1 | T1006 | CWE-21, CWE-22, CWE-23, CWE-24, CWE-425 | Path Traversal | High
2 | T1055 | CWE-74 | Improper Neutralization of Data within XPath Expressions | High
3 | T1059 | CWE-88, CWE-94, CWE-1321 | Argument Injection | High
4 | T1059.007 | CWE-79, CWE-80 | Basic Cross Site Scripting | High
5 | T1068 | CWE-250, CWE-264, CWE-269, CWE-284 | Execution with Unnecessary Privileges | High
6 | ... | ... | ... | ...

There are 18 more TTP items available. Please use our online service to access the data.

## IOA - Indicator of Attack

These _indicators of attack_ (IOA) list the potential fragments used for technical activities like reconnaissance, exploitation, privilege escalation, and exfiltration by Ponystealer. This data is unique as it uses our predictive model for actor profiling.

ID | Type | Indicator | Confidence
-- | ---- | --------- | ----------
1 | File | `/+CSCOE+/logon.html` | High
2 | File | `/act/ActDao.xml` | High
3 | File | `/add-students.php` | High
4 | File | `/admin.php?p=/Area/index#tab=t2` | High
5 | File | `/admin/` | Low
6 | File | `/admin/admin-update-employee.php` | High
7 | File | `/admin/application-bwdates-reports-details.php` | High
8 | File | `/admin/booktime.php` | High
9 | File | `/admin/change-image.php` | High
10 | File | `/admin/index.php/web/ajax_all_lists` | High
11 | File | `/admin/login.php` | High
12 | File | `/ajax.php?action=read_msg` | High
13 | File | `/api/clusters/local/topics/{topic}/messages` | High
14 | File | `/api/gen/clients/{language}` | High
15 | File | `/API/info` | Medium
16 | File | `/app/options.py` | High
17 | File | `/bin/httpd` | Medium
18 | File | `/cdsms/classes/Master.php?f=delete_enrollment` | High
19 | File | `/cgi-bin/supervisor/adcommand.cgi` | High
20 | File | `/cgi-bin/system_mgr.cgi` | High
21 | File | `/cgi-bin/tosei_kikai.php` | High
22 | File | `/cgi-bin/wapopen` | High
23 | File | `/ci_spms/admin/category` | High
24 | File | `/ci_spms/admin/search/searching/` | High
25 | File | `/classes/Master.php?f=delete_appointment` | High
26 | File | `/classes/Master.php?f=delete_train` | High
27 | File | `/cov/triggerEnvCov` | High
28 | File | `/ctcprotocol/Protocol` | High
29 | File | `/dashboard/admin/del_plan.php` | High
30 | File | `/dashboard/approve-reject.php` | High
31 | File | `/dashboard/menu-list.php` | High
32 | File | `/debug/pprof` | Medium
33 | File | `/dede/file_manage_control.php` | High
34 | File | `/detailed.php` | High
35 | File | `/dist/index.js` | High
36 | File | `/DXR.axd` | Medium
37 | File | `/ebics-server/ebics.aspx` | High
38 | File | `/EXCU_SHELL` | Medium
39 | File | `/ffos/classes/Master.php?f=save_category` | High
40 | File | `/forum/away.php` | High
41 | File | `/general/address/private/address/query/delete.php` | High
42 | File | `/goform/ate` | Medium
43 | File | `/goform/form2systime.cgi` | High
44 | File | `/goform/formSetLog` | High
45 | File | `/goform/formWlanSetup_Wizard` | High
46 | ... | ... | ...

There are 395 more IOA items available (file, library, argument, input value, pattern, network port). Please use our online service to access the data.

## References

The following list contains _external sources_ which discuss the actor and the associated activities:

* https://blog.talosintelligence.com/2018/08/threat-roundup-0817-0824.html
* https://blog.talosintelligence.com/2018/08/threat-roundup-0824-0831.html
* https://blog.talosintelligence.com/2018/09/threat-roundup-0907-0914.html
* https://blog.talosintelligence.com/2019/04/threat-roundup-0412-0419.html
* https://blog.talosintelligence.com/2019/06/threat-roundup-0621-0628.html
* https://blog.talosintelligence.com/2020/09/threat-roundup-0828-0904.html
* https://blog.talosintelligence.com/2020/10/threat-roundup-1016-1023.html
* https://blog.talosintelligence.com/2020/11/threat-roundup-1113-1120.html
* https://blog.talosintelligence.com/2021/12/threat-roundup-1126-1203.html

## Literature

The following _articles_ explain our unique predictive cyber threat intelligence:

* [VulDB Cyber Threat Intelligence Documentation](https://vuldb.com/?kb.cti)
* [Cyber Threat Intelligence - Early Anticipation of Attacks](https://www.scip.ch/en/?labs.20201022)

## License

(c) [1997-2025](https://vuldb.com/?kb.changelog) by [vuldb.com](https://vuldb.com/?kb.about). All data on this page is shared under the license [CC BY-NC-SA 4.0](https://creativecommons.org/licenses/by-nc-sa/4.0/). Questions? Check the [FAQ](https://vuldb.com/?kb.faq), read the [documentation](https://vuldb.com/?kb) or [contact us](https://vuldb.com/?contact)!
