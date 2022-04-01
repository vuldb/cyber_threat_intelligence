# xStart - Cyber Threat Intelligence

These _indicators_ were reported, collected, and generated during the [VulDB CTI analysis](https://vuldb.com/?kb.cti) of the actor known as [xStart](https://vuldb.com/?actor.xstart). The _activity monitoring_ correlates data from social media, forums, chat rooms, and darknet markets. It helps to determine associated actors, specific activities, expected intentions, emerging research, and ongoing attacks. Our unique _predictive model_ uses _big data_ to forecast activities and their characteristics.

_Live data_ and more _analysis capabilities_ are available at [https://vuldb.com/?actor.xstart](https://vuldb.com/?actor.xstart)

## Countries

These _countries_ are directly (e.g. origin of attacks) or indirectly (e.g. access by proxy) associated with xStart:

* [CN](https://vuldb.com/?country.cn)
* [US](https://vuldb.com/?country.us)
* [DE](https://vuldb.com/?country.de)
* ...

There are 14 more country items available. Please use our online service to access the data.

## IOC - Indicator of Compromise

These _indicators of compromise_ (IOC) indicate associated network resources which are known to be part of research and attack activities of xStart.

ID | IP address | Hostname | Campaign | Confidence
-- | ---------- | -------- | -------- | ----------
1 | [8.210.23.243](https://vuldb.com/?ip.8.210.23.243) | - | - | High
2 | [8.210.29.183](https://vuldb.com/?ip.8.210.29.183) | - | - | High
3 | [8.210.43.38](https://vuldb.com/?ip.8.210.43.38) | - | - | High
4 | [8.210.66.64](https://vuldb.com/?ip.8.210.66.64) | - | - | High
5 | [8.210.74.149](https://vuldb.com/?ip.8.210.74.149) | - | - | High
6 | [8.210.120.8](https://vuldb.com/?ip.8.210.120.8) | - | - | High
7 | [8.210.130.151](https://vuldb.com/?ip.8.210.130.151) | - | - | High
8 | [34.92.61.61](https://vuldb.com/?ip.34.92.61.61) | 61.61.92.34.bc.googleusercontent.com | - | Medium
9 | [36.99.196.223](https://vuldb.com/?ip.36.99.196.223) | - | - | High
10 | [39.99.245.93](https://vuldb.com/?ip.39.99.245.93) | - | - | High
11 | [39.102.48.190](https://vuldb.com/?ip.39.102.48.190) | - | - | High
12 | [42.48.120.127](https://vuldb.com/?ip.42.48.120.127) | - | - | High
13 | ... | ... | ... | ...

There are 47 more IOC items available. Please use our online service to access the data.

## TTP - Tactics, Techniques, Procedures

_Tactics, techniques, and procedures_ (TTP) summarize the suspected MITRE ATT&CK techniques used by _xStart_. This data is unique as it uses our predictive model for actor profiling.

ID | Technique | Weakness | Description | Confidence
-- | --------- | -------- | ----------- | ----------
1 | T1059.007 | CWE-79, CWE-80 | Cross Site Scripting | High
2 | T1068 | CWE-264, CWE-266, CWE-284 | Execution with Unnecessary Privileges | High
3 | T1110.001 | CWE-798 | Improper Restriction of Excessive Authentication Attempts | High
4 | ... | ... | ... | ...

There are 7 more TTP items available. Please use our online service to access the data.

## IOA - Indicator of Attack

These _indicators of attack_ (IOA) list the potential fragments used for technical activities like reconnaissance, exploitation, privilege escalation, and exfiltration by xStart. This data is unique as it uses our predictive model for actor profiling.

ID | Type | Indicator | Confidence
-- | ---- | --------- | ----------
1 | File | `%SYSTEMDRIVE%\totalcmd\TOTALCMD64.EXE` | High
2 | File | `.kss.pid` | Medium
3 | File | `/+CSCOE+/logon.html` | High
4 | File | `/api/collection/findone` | High
5 | File | `/api/crontab` | Medium
6 | File | `/category_view.php` | High
7 | File | `/cgi-bin/loaddata.py` | High
8 | File | `/cgi-sys/FormMail-clone.cgi` | High
9 | File | `/debug/pprof` | Medium
10 | File | `/etc/passwd` | Medium
11 | File | `/forum/away.php` | High
12 | File | `/framework/modules/users/models/user.php` | High
13 | File | `/getcfg.php` | Medium
14 | File | `/goform/setportList` | High
15 | File | `/goform/setVLAN` | High
16 | File | `/goform/wlanPrimaryNetwork` | High
17 | File | `/GponForm/usb_Form?script/` | High
18 | File | `/groups/31-twitter-basics` | High
19 | File | `/modules/profile/index.php` | High
20 | File | `/scdmz.cmd` | Medium
21 | File | `/tmp` | Low
22 | File | `/tmp/before` | Medium
23 | File | `/uncpath/` | Medium
24 | File | `/User/saveUser` | High
25 | File | `/usr/bin/vmware-mount` | High
26 | File | `/var/WEB-GUI/cgi-bin/downloadfile.cgi` | High
27 | File | `/WEB-INF/web.xml` | High
28 | File | `/_vti_pvt/access.cnf` | High
29 | File | `3/qq_connect2.0/API/class/ErrorCase.class.php` | High
30 | File | `accountsettings_add.html` | High
31 | File | `aclient.exe` | Medium
32 | File | `adclick.php` | Medium
33 | File | `addentry.php` | Medium
34 | File | `add_comment.php` | High
35 | File | `admin.php` | Medium
36 | File | `admin.php?c=update&f=unzip` | High
37 | File | `admin/ajax/op_kandidat.php` | High
38 | File | `admin/conf_users_edit.php` | High
39 | File | `admin/domain-fields/` | High
40 | File | `admin/index.asp` | High
41 | File | `admin/member_deal.php` | High
42 | File | `admin/news.php` | High
43 | File | `AdminLoginInterceptor.java` | High
44 | File | `admins.js` | Medium
45 | File | `advancedsearch.php` | High
46 | ... | ... | ...

There are 400 more IOA items available (file, library, argument, input value, pattern, network port). Please use our online service to access the data.

## References

The following list contains _external sources_ which discuss the actor and the associated activities:

* https://github.com/PwCUK-CTO/SANSCTISummit2021-xStart/blob/main/indicators/Indicators_IPs.csv

## Literature

The following _articles_ explain our unique predictive cyber threat intelligence:

* [VulDB Cyber Threat Intelligence Documentation](https://vuldb.com/?kb.cti)
* [Cyber Threat Intelligence - Early Anticipation of Attacks](https://www.scip.ch/en/?labs.20201022)

## License

(c) [1997-2022](https://vuldb.com/?kb.changelog) by [vuldb.com](https://vuldb.com/?kb.about). All data on this page is shared under the license [CC BY-NC-SA 4.0](https://creativecommons.org/licenses/by-nc-sa/4.0/). Questions? Check the [FAQ](https://vuldb.com/?kb.faq), read the [documentation](https://vuldb.com/?kb) or [contact us](https://vuldb.com/?contact)!
