# SystemBC - Cyber Threat Intelligence

These _indicators_ were reported, collected, and generated during the [VulDB CTI analysis](https://vuldb.com/?kb.cti) of the actor known as [SystemBC](https://vuldb.com/?actor.systembc). The _activity monitoring_ correlates data from social media, forums, chat rooms, and darknet markets. It helps to determine associated actors, specific activities, expected intentions, emerging research, and ongoing attacks. Our unique _predictive model_ uses _big data_ to forecast activities and their characteristics.

_Live data_ and more _analysis capabilities_ are available at [https://vuldb.com/?actor.systembc](https://vuldb.com/?actor.systembc)

## Countries

These _countries_ are directly (e.g. origin of attacks) or indirectly (e.g. access by proxy) associated with SystemBC:

* [US](https://vuldb.com/?country.us)
* [RU](https://vuldb.com/?country.ru)
* [CN](https://vuldb.com/?country.cn)
* ...

There are 22 more country items available. Please use our online service to access the data.

## IOC - Indicator of Compromise

These _indicators of compromise_ (IOC) indicate associated network resources which are known to be part of research and attack activities of SystemBC.

ID | IP address | Hostname | Campaign | Confidence
-- | ---------- | -------- | -------- | ----------
1 | [5.39.221.47](https://vuldb.com/?ip.5.39.221.47) | - | - | High
2 | [5.61.41.136](https://vuldb.com/?ip.5.61.41.136) | - | - | High
3 | [5.101.78.2](https://vuldb.com/?ip.5.101.78.2) | - | - | High
4 | [5.183.95.197](https://vuldb.com/?ip.5.183.95.197) | - | - | High
5 | [5.199.174.179](https://vuldb.com/?ip.5.199.174.179) | - | - | High
6 | [5.199.174.223](https://vuldb.com/?ip.5.199.174.223) | - | - | High
7 | [20.115.47.118](https://vuldb.com/?ip.20.115.47.118) | - | - | High
8 | [23.137.249.215](https://vuldb.com/?ip.23.137.249.215) | - | - | High
9 | [23.227.202.22](https://vuldb.com/?ip.23.227.202.22) | 23-227-202-22.static.hvvc.us | - | High
10 | [31.41.244.183](https://vuldb.com/?ip.31.41.244.183) | - | - | High
11 | [31.44.185.6](https://vuldb.com/?ip.31.44.185.6) | - | - | High
12 | [34.171.171.32](https://vuldb.com/?ip.34.171.171.32) | 32.171.171.34.bc.googleusercontent.com | - | Medium
13 | [45.11.57.142](https://vuldb.com/?ip.45.11.57.142) | dedicated.vsys.host | - | High
14 | [45.15.156.48](https://vuldb.com/?ip.45.15.156.48) | - | - | High
15 | [45.32.132.182](https://vuldb.com/?ip.45.32.132.182) | 45.32.132.182.vultrusercontent.com | - | High
16 | [45.81.225.72](https://vuldb.com/?ip.45.81.225.72) | vm3618662.24ssd.had.wf | - | High
17 | ... | ... | ... | ...

There are 62 more IOC items available. Please use our online service to access the data.

## TTP - Tactics, Techniques, Procedures

_Tactics, techniques, and procedures_ (TTP) summarize the suspected MITRE ATT&CK techniques used by _SystemBC_. This data is unique as it uses our predictive model for actor profiling.

ID | Technique | Weakness | Description | Confidence
-- | --------- | -------- | ----------- | ----------
1 | T1006 | CWE-21, CWE-22, CWE-425 | Pathname Traversal | High
2 | T1040 | CWE-294, CWE-319 | Authentication Bypass by Capture-replay | High
3 | T1055 | CWE-74 | Injection | High
4 | T1059 | CWE-88, CWE-94 | Cross Site Scripting | High
5 | T1059.007 | CWE-79, CWE-80 | Cross Site Scripting | High
6 | ... | ... | ... | ...

There are 22 more TTP items available. Please use our online service to access the data.

## IOA - Indicator of Attack

These _indicators of attack_ (IOA) list the potential fragments used for technical activities like reconnaissance, exploitation, privilege escalation, and exfiltration by SystemBC. This data is unique as it uses our predictive model for actor profiling.

ID | Type | Indicator | Confidence
-- | ---- | --------- | ----------
1 | File | `/+CSCOE+/logon.html` | High
2 | File | `/admin/` | Low
3 | File | `/admin/?page=system_info/contact_info` | High
4 | File | `/admin/departments/view_department.php` | High
5 | File | `/admin/login.php` | High
6 | File | `/admin/produts/controller.php` | High
7 | File | `/admin/user/team` | High
8 | File | `/admin/video/list` | High
9 | File | `/api/v1/attack/token` | High
10 | File | `/cgi-bin/supervisor/PwdGrp.cgi` | High
11 | File | `/cgi-bin/system_mgr.cgi` | High
12 | File | `/cgi-bin/wlogin.cgi` | High
13 | File | `/common/logViewer/logViewer.jsf` | High
14 | File | `/core/conditions/AbstractWrapper.java` | High
15 | File | `/crmeb/app/admin/controller/store/CopyTaobao.php` | High
16 | File | `/export` | Low
17 | File | `/forum/away.php` | High
18 | File | `/forum/PostPrivateMessage` | High
19 | File | `/get_getnetworkconf.cgi` | High
20 | File | `/goform/aspForm` | High
21 | File | `/goForm/aspForm` | High
22 | File | `/goform/SysToolRestoreSet` | High
23 | File | `/goform/WifiBasicSet` | High
24 | File | `/hocms/classes/Master.php?f=delete_collection` | High
25 | File | `/home/cavesConsole` | High
26 | File | `/hrm/controller/employee.php` | High
27 | File | `/htdocs/cgibin` | High
28 | File | `/info.asp` | Medium
29 | File | `/jurusanmatkul/data` | High
30 | File | `/login.html__passwd1` | High
31 | File | `/modules/profile/index.php` | High
32 | File | `/ms/cms/content/list.do` | High
33 | File | `/news-portal-script/information.php` | High
34 | File | `/opt/zimbra/jetty/webapps/zimbra/public` | High
35 | File | `/orms/` | Low
36 | File | `/p1/p2/:name` | Medium
37 | File | `/param.file.tgz` | High
38 | File | `/php-jms/review_se_result.php` | High
39 | File | `/plesk-site-preview/` | High
40 | File | `/project/PROJECTNAME/reports/` | High
41 | File | `/school/model/get_admin_profile.php` | High
42 | File | `/services/prefs.php` | High
43 | File | `/spip.php` | Medium
44 | File | `/Status/wan_button_action.asp` | High
45 | File | `/student-grading-system/rms.php?page=grade` | High
46 | File | `/template/edit` | High
47 | File | `/text/pdf/PdfReader.java` | High
48 | File | `/timeline2.php` | High
49 | File | `/ucms/chk.php` | High
50 | ... | ... | ...

There are 435 more IOA items available (file, library, argument, input value, pattern, network port). Please use our online service to access the data.

## References

The following list contains _external sources_ which discuss the actor and the associated activities:

* https://bazaar.abuse.ch/sample/040aa152e739826874a268f4ffb8be80dd256e7817cdb2c25329d25a5264671e/
* https://bazaar.abuse.ch/sample/2a1ba880f0cacda99db3eed861bc738a3f8ec6cac2518da431c446851fb4f923/
* https://bazaar.abuse.ch/sample/4aec64f64812b8ed41eebe2d561d166b6dc9c16f2a856f7d10408ec83f493c06/
* https://bazaar.abuse.ch/sample/4c95b642310f82c6a7779a2b561b6cb9a27ca22db74c66378d8a61ee8d32f758/
* https://bazaar.abuse.ch/sample/7dd44d3b3df4f14474d20ffa23e2fb20dcf22ed3a1458b345a1bd85563ac4a62/
* https://bazaar.abuse.ch/sample/22a6e850b9deb9d6682f795349d23c1f660ba5253028a99a62a43a64f2950fc3/
* https://bazaar.abuse.ch/sample/36a101b5a13436dd67e2b33c2abbae7cdd86a7ed951185a1914c12685339ad74/
* https://bazaar.abuse.ch/sample/45b9e820b3ab997c498a28d59601b1b72fbbf3b9415f8c75843ff24c2b250193/
* https://bazaar.abuse.ch/sample/120fa0aa63598735bd316759edc1de341d089f391adf67b356039f1e706655e7/
* https://bazaar.abuse.ch/sample/553dbdc0da9fac50f5ce3e8006e060ac0c6d8fef73d4942df4fa02202ecd5616/
* https://bazaar.abuse.ch/sample/742a97dbebd3f760b215186d04655dfcaf3846b40d3390a2db9bd7ee5f3d3266/
* https://bazaar.abuse.ch/sample/998b16d93ed1043b616cddfcae2cbe10b6f4ae05b9bbd1abed4a99ad11205444/
* https://bazaar.abuse.ch/sample/49763b5871eae34139060e486a62817242212a549593a1875a5221655b510334/
* https://bazaar.abuse.ch/sample/a2bf4098b65e0efb8bc9cba70cfb5e36d01de5f591d100bb429a5dc3ef6c3bc3/
* https://bazaar.abuse.ch/sample/ca958072c2483f5cfab83972b3e5a25a163eed2d0d6df7d310ddf200a6fec53c/
* https://bazaar.abuse.ch/sample/f0c40cd7b07913d9ed925ebc130d4263850aeb2e16c32c47214d2b5989bbf4f5/
* https://bazaar.abuse.ch/sample/f84a10e65b8b479c09668202550f40f3f7ccc5e3343e1a8ed6173e0873aefd11/
* https://blogs.blackberry.com/en/2021/06/threat-thursday-systembc-a-rat-in-the-pipeline
* https://github.com/prodaft/malware-ioc/tree/master/ViceSociety
* https://threatfox.abuse.ch
* https://twitter.com/0xrb/status/1516651127944941568
* https://twitter.com/0xrb/status/1518499002681282560
* https://twitter.com/0xrb/status/1572547656257511424
* https://twitter.com/benkow_/status/1430851571491954690

## Literature

The following _articles_ explain our unique predictive cyber threat intelligence:

* [VulDB Cyber Threat Intelligence Documentation](https://vuldb.com/?kb.cti)
* [Cyber Threat Intelligence - Early Anticipation of Attacks](https://www.scip.ch/en/?labs.20201022)

## License

(c) [1997-2023](https://vuldb.com/?kb.changelog) by [vuldb.com](https://vuldb.com/?kb.about). All data on this page is shared under the license [CC BY-NC-SA 4.0](https://creativecommons.org/licenses/by-nc-sa/4.0/). Questions? Check the [FAQ](https://vuldb.com/?kb.faq), read the [documentation](https://vuldb.com/?kb) or [contact us](https://vuldb.com/?contact)!
