# Ponystealer - Cyber Threat Intelligence

These _indicators_ were reported, collected, and generated during the [VulDB CTI analysis](https://vuldb.com/?kb.cti) of the actor known as [Ponystealer](https://vuldb.com/?actor.ponystealer). The _activity monitoring_ correlates data from social media, forums, chat rooms, and darknet markets. It helps to determine associated actors, specific activities, expected intentions, emerging research, and ongoing attacks. Our unique _predictive model_ uses _big data_ to forecast activities and their characteristics.

_Live data_ and more _analysis capabilities_ are available at [https://vuldb.com/?actor.ponystealer](https://vuldb.com/?actor.ponystealer)

## Countries

These _countries_ are directly (e.g. origin of attacks) or indirectly (e.g. access by proxy) associated with Ponystealer:

* [US](https://vuldb.com/?country.us)
* [CN](https://vuldb.com/?country.cn)
* [MS](https://vuldb.com/?country.ms)
* ...

There are 31 more country items available. Please use our online service to access the data.

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
8 | [45.76.142.81](https://vuldb.com/?ip.45.76.142.81) | 45.76.142.81.vultrusercontent.com | - | High
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
1 | T1059.007 | CWE-79, CWE-80 | Cross Site Scripting | High
2 | T1068 | CWE-250, CWE-264, CWE-266, CWE-284 | Execution with Unnecessary Privileges | High
3 | T1110.001 | CWE-798 | Improper Restriction of Excessive Authentication Attempts | High
4 | ... | ... | ... | ...

There are 9 more TTP items available. Please use our online service to access the data.

## IOA - Indicator of Attack

These _indicators of attack_ (IOA) list the potential fragments used for technical activities like reconnaissance, exploitation, privilege escalation, and exfiltration by Ponystealer. This data is unique as it uses our predictive model for actor profiling.

ID | Type | Indicator | Confidence
-- | ---- | --------- | ----------
1 | File | `/+CSCOE+/logon.html` | High
2 | File | `/.env` | Low
3 | File | `/.ssh/authorized_keys` | High
4 | File | `/admin/default.asp` | High
5 | File | `/ajax/networking/get_netcfg.php` | High
6 | File | `/assets/ctx` | Medium
7 | File | `/checkLogin.cgi` | High
8 | File | `/cms/print.php` | High
9 | File | `/concat?/%2557EB-INF/web.xml` | High
10 | File | `/Content/Template/root/reverse-shell.aspx` | High
11 | File | `/data/remove` | Medium
12 | File | `/etc/passwd` | Medium
13 | File | `/goforms/rlminfo` | High
14 | File | `/login` | Low
15 | File | `/mifs/c/i/reg/reg.html` | High
16 | File | `/navigate/navigate_download.php` | High
17 | File | `/owa/auth/logon.aspx` | High
18 | File | `/p` | Low
19 | File | `/password.html` | High
20 | File | `/proc/ioports` | High
21 | File | `/property-list/property_view.php` | High
22 | File | `/ptms/classes/Users.php` | High
23 | File | `/rest` | Low
24 | File | `/rest/api/2/search` | High
25 | File | `/s/` | Low
26 | File | `/scripts/cpan_config` | High
27 | File | `/secure/admin/InsightDefaultCustomFieldConfig.jspa` | High
28 | File | `/server-info` | Medium
29 | File | `/services/system/setup.json` | High
30 | File | `/uncpath/` | Medium
31 | File | `/vloggers_merch/?p=view_product` | High
32 | File | `/webconsole/APIController` | High
33 | File | `/websocket/exec` | High
34 | File | `/wp-admin/admin-ajax.php` | High
35 | File | `/wp-json` | Medium
36 | File | `/wp-json/oembed/1.0/embed?url` | High
37 | File | `/_next` | Low
38 | File | `4.edu.php\conn\function.php` | High
39 | File | `14all.cgi/14all-1.1.cgi/traffic.cgi/mrtg.cgi` | High
40 | File | `a2billing/customer/iridium_threed.php` | High
41 | File | `adclick.php` | Medium
42 | File | `addentry.php` | Medium
43 | File | `admin.php?s=/Channel/add.html` | High
44 | File | `admin/category.inc.php` | High
45 | File | `admin/class-bulk-editor-list-table.php` | High
46 | File | `admin/conf_users_edit.php` | High
47 | File | `admin/dl_sendmail.php` | High
48 | File | `admin/index.php` | High
49 | File | `admin/password_forgotten.php` | High
50 | ... | ... | ...

There are 436 more IOA items available (file, library, argument, input value, pattern, network port). Please use our online service to access the data.

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

(c) [1997-2022](https://vuldb.com/?kb.changelog) by [vuldb.com](https://vuldb.com/?kb.about). All data on this page is shared under the license [CC BY-NC-SA 4.0](https://creativecommons.org/licenses/by-nc-sa/4.0/). Questions? Check the [FAQ](https://vuldb.com/?kb.faq), read the [documentation](https://vuldb.com/?kb) or [contact us](https://vuldb.com/?contact)!
