# TA551 - Cyber Threat Intelligence

These _indicators_ were reported, collected, and generated during the [VulDB CTI analysis](https://vuldb.com/?kb.cti) of the actor known as [TA551](https://vuldb.com/?actor.ta551). The _activity monitoring_ correlates data from social media, forums, chat rooms, and darknet markets. It helps to determine associated actors, specific activities, expected intentions, emerging research, and ongoing attacks. Our unique _predictive model_ uses _big data_ to forecast activities and their characteristics.

_Live data_ and more _analysis capabilities_ are available at [https://vuldb.com/?actor.ta551](https://vuldb.com/?actor.ta551)

## Campaigns

The following _campaigns_ are known and can be associated with TA551:

* Cobalt Strike
* DarkVNC
* Hancitor
* ...

There are 1 more campaign items available. Please use our online service to access the data.

## Countries

These _countries_ are directly (e.g. origin of attacks) or indirectly (e.g. access by proxy) associated with TA551:

* [ES](https://vuldb.com/?country.es)
* [DE](https://vuldb.com/?country.de)
* [FR](https://vuldb.com/?country.fr)
* ...

There are 9 more country items available. Please use our online service to access the data.

## IOC - Indicator of Compromise

These _indicators of compromise_ (IOC) indicate associated network resources which are known to be part of research and attack activities of TA551.

ID | IP address | Hostname | Campaign | Confidence
-- | ---------- | -------- | -------- | ----------
1 | [8.209.76.110](https://vuldb.com/?ip.8.209.76.110) | - | Hancitor | High
2 | [23.82.141.241](https://vuldb.com/?ip.23.82.141.241) | - | Cobalt Strike | High
3 | [23.106.223.174](https://vuldb.com/?ip.23.106.223.174) | - | - | High
4 | [43.128.225.230](https://vuldb.com/?ip.43.128.225.230) | - | Hancitor | High
5 | [43.128.229.136](https://vuldb.com/?ip.43.128.229.136) | - | Hancitor | High
6 | [43.128.232.152](https://vuldb.com/?ip.43.128.232.152) | - | Hancitor | High
7 | [43.129.239.78](https://vuldb.com/?ip.43.129.239.78) | - | Hancitor | High
8 | [43.133.160.144](https://vuldb.com/?ip.43.133.160.144) | - | Hancitor | High
9 | [45.8.146.139](https://vuldb.com/?ip.45.8.146.139) | vm580483.stark-industries.solutions | IcedID | High
10 | [45.89.67.166](https://vuldb.com/?ip.45.89.67.166) | srbtv.ru | - | High
11 | [45.95.11.151](https://vuldb.com/?ip.45.95.11.151) | vm220095.pq.hosting | - | High
12 | [45.95.11.153](https://vuldb.com/?ip.45.95.11.153) | vm284420.pq.hosting | - | High
13 | [45.95.11.154](https://vuldb.com/?ip.45.95.11.154) | 4ser-1640356836.4server.su | - | High
14 | [45.95.11.155](https://vuldb.com/?ip.45.95.11.155) | slfk.lz | - | High
15 | ... | ... | ... | ...

There are 58 more IOC items available. Please use our online service to access the data.

## TTP - Tactics, Techniques, Procedures

_Tactics, techniques, and procedures_ (TTP) summarize the suspected MITRE ATT&CK techniques used by _TA551_. This data is unique as it uses our predictive model for actor profiling.

ID | Technique | Weakness | Description | Confidence
-- | --------- | -------- | ----------- | ----------
1 | T1006 | CWE-21, CWE-22, CWE-23, CWE-36 | Pathname Traversal | High
2 | T1040 | CWE-294 | Authentication Bypass by Capture-replay | High
3 | T1055 | CWE-74 | Injection | High
4 | T1059 | CWE-94, CWE-1321 | Cross Site Scripting | High
5 | T1059.007 | CWE-79 | Cross Site Scripting | High
6 | ... | ... | ... | ...

There are 19 more TTP items available. Please use our online service to access the data.

## IOA - Indicator of Attack

These _indicators of attack_ (IOA) list the potential fragments used for technical activities like reconnaissance, exploitation, privilege escalation, and exfiltration by TA551. This data is unique as it uses our predictive model for actor profiling.

ID | Type | Indicator | Confidence
-- | ---- | --------- | ----------
1 | File | `/admin/api/admin/articles/` | High
2 | File | `/admin/api/theme-edit/` | High
3 | File | `/Admin/createClass.php` | High
4 | File | `/admin/curriculum/view_curriculum.php` | High
5 | File | `/admin/departments/view_department.php` | High
6 | File | `/admin/problem_judge.php` | High
7 | File | `/admin/suppliers/view_details.php` | High
8 | File | `/admin/userprofile.php` | High
9 | File | `/api/browserextension/UpdatePassword/` | High
10 | File | `/application/views/themeOptions/update.php` | High
11 | File | `/attachments` | Medium
12 | File | `/balance/service/list` | High
13 | File | `/classes/Users.php` | High
14 | File | `/config/myfield/test.php` | High
15 | File | `/data/app` | Medium
16 | File | `/dev/snd/seq` | Medium
17 | File | `/diagnostic/login.php` | High
18 | File | `/etc/gsissh/sshd_config` | High
19 | File | `/etc/master.passwd` | High
20 | File | `/etc/passwd` | Medium
21 | File | `/goform/WifiBasicSet` | High
22 | File | `/hrm/controller/login.php` | High
23 | File | `/login` | Low
24 | File | `/logs/sql-error.log` | High
25 | File | `/mogu-picture/file/uploadPicsByUrl` | High
26 | File | `/pages/save_user.php` | High
27 | File | `/password/reset` | High
28 | File | `/plugin/getList` | High
29 | File | `/register/abort` | High
30 | File | `/rukovoditel/index.php?module=logs/view&type=php` | High
31 | File | `/webservices/download/index.php` | High
32 | File | `actions.hsp` | Medium
33 | File | `adclick.php` | Medium
34 | File | `AddAppNetworksActivity.java` | High
35 | File | `AddAppNetworksFragment.java` | High
36 | File | `admin.php` | Medium
37 | File | `admin/ajax.attachment.php` | High
38 | File | `admin/article_save.php` | High
39 | File | `admin/make_payments.php` | High
40 | File | `admin/panels/uploader/admin.uploader.php` | High
41 | File | `admin/stat.main.php` | High
42 | File | `aiff.c` | Low
43 | File | `alaw.c` | Low
44 | File | `Ap4StdCFileByteStream.cpp` | High
45 | File | `api/src/main/java/org/openmrs/module/appointmentscheduling/validator/AppointmentTypeValidator.java` | High
46 | File | `app/controllers/code_caller_controller.php` | High
47 | File | `app/helpers/queries_helper.rb` | High
48 | File | `app/View/Helper/CommandHelper.php` | High
49 | ... | ... | ...

There are 423 more IOA items available (file, library, argument, input value, pattern, network port). Please use our online service to access the data.

## References

The following list contains _external sources_ which discuss the actor and the associated activities:

* https://isc.sans.edu/diary/28092
* https://isc.sans.edu/diary/IcedID+%28Bokbot%29+with+Dark+VNC+and+Cobalt+Strike/28884
* https://isc.sans.edu/diary/Monster+Libra+%28TA551Shathak%29+--%3E+IcedID+%28Bokbot%29+--%3E+Cobalt+Strike+%26+DarkVNC/28974
* https://isc.sans.edu/diary/Monster+Libra+%28TA551Shathak%29+pushes+IcedID+%28Bokbot%29+with+Dark+VNC+and+Cobalt+Strike/28934
* https://isc.sans.edu/diary/rss/27738
* https://isc.sans.edu/forums/diary/More+TA551+Shathak+Word+docs+push+IcedID+Bokbot/26674/
* https://isc.sans.edu/forums/diary/TA551+Shathak+Word+docs+push+IcedID+Bokbot/26438/
* https://www.malware-traffic-analysis.net/2021/09/14/index.html

## Literature

The following _articles_ explain our unique predictive cyber threat intelligence:

* [VulDB Cyber Threat Intelligence Documentation](https://vuldb.com/?kb.cti)
* [Cyber Threat Intelligence - Early Anticipation of Attacks](https://www.scip.ch/en/?labs.20201022)

## License

(c) [1997-2023](https://vuldb.com/?kb.changelog) by [vuldb.com](https://vuldb.com/?kb.about). All data on this page is shared under the license [CC BY-NC-SA 4.0](https://creativecommons.org/licenses/by-nc-sa/4.0/). Questions? Check the [FAQ](https://vuldb.com/?kb.faq), read the [documentation](https://vuldb.com/?kb) or [contact us](https://vuldb.com/?contact)!
