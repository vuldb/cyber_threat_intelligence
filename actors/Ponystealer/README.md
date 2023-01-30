# Ponystealer - Cyber Threat Intelligence

These _indicators_ were reported, collected, and generated during the [VulDB CTI analysis](https://vuldb.com/?kb.cti) of the actor known as [Ponystealer](https://vuldb.com/?actor.ponystealer). The _activity monitoring_ correlates data from social media, forums, chat rooms, and darknet markets. It helps to determine associated actors, specific activities, expected intentions, emerging research, and ongoing attacks. Our unique _predictive model_ uses _big data_ to forecast activities and their characteristics.

_Live data_ and more _analysis capabilities_ are available at [https://vuldb.com/?actor.ponystealer](https://vuldb.com/?actor.ponystealer)

## Countries

These _countries_ are directly (e.g. origin of attacks) or indirectly (e.g. access by proxy) associated with Ponystealer:

* [US](https://vuldb.com/?country.us)
* [CN](https://vuldb.com/?country.cn)
* [MS](https://vuldb.com/?country.ms)
* ...

There are 30 more country items available. Please use our online service to access the data.

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
1 | T1006 | CWE-21, CWE-22, CWE-23, CWE-24 | Pathname Traversal | High
2 | T1040 | CWE-319 | Authentication Bypass by Capture-replay | High
3 | T1055 | CWE-74 | Injection | High
4 | T1059 | CWE-88, CWE-94 | Cross Site Scripting | High
5 | T1059.007 | CWE-79, CWE-80 | Cross Site Scripting | High
6 | ... | ... | ... | ...

There are 20 more TTP items available. Please use our online service to access the data.

## IOA - Indicator of Attack

These _indicators of attack_ (IOA) list the potential fragments used for technical activities like reconnaissance, exploitation, privilege escalation, and exfiltration by Ponystealer. This data is unique as it uses our predictive model for actor profiling.

ID | Type | Indicator | Confidence
-- | ---- | --------- | ----------
1 | File | `/+CSCOE+/logon.html` | High
2 | File | `/.ssh/authorized_keys` | High
3 | File | `/admin/default.asp` | High
4 | File | `/ajax/networking/get_netcfg.php` | High
5 | File | `/app/options.py` | High
6 | File | `/bin/httpd` | Medium
7 | File | `/cdsms/classes/Master.php?f=delete_enrollment` | High
8 | File | `/cgi-bin/wapopen` | High
9 | File | `/ci_spms/admin/category` | High
10 | File | `/ci_spms/admin/search/searching/` | High
11 | File | `/classes/Master.php?f=delete_appointment` | High
12 | File | `/classes/Master.php?f=delete_train` | High
13 | File | `/cms/print.php` | High
14 | File | `/concat?/%2557EB-INF/web.xml` | High
15 | File | `/Content/Template/root/reverse-shell.aspx` | High
16 | File | `/ctcprotocol/Protocol` | High
17 | File | `/dashboard/menu-list.php` | High
18 | File | `/data/remove` | Medium
19 | File | `/ffos/classes/Master.php?f=save_category` | High
20 | File | `/forum/away.php` | High
21 | File | `/goforms/rlminfo` | High
22 | File | `/Items/*/RemoteImages/Download` | High
23 | File | `/login` | Low
24 | File | `/menu.html` | Medium
25 | File | `/navigate/navigate_download.php` | High
26 | File | `/ocwbs/admin/?page=user/manage_user` | High
27 | File | `/ofrs/admin/?page=user/manage_user` | High
28 | File | `/out.php` | Medium
29 | File | `/owa/auth/logon.aspx` | High
30 | File | `/password.html` | High
31 | File | `/php_action/fetchSelectedUser.php` | High
32 | File | `/proc/ioports` | High
33 | File | `/property-list/property_view.php` | High
34 | File | `/ptms/classes/Users.php` | High
35 | File | `/resources//../` | High
36 | File | `/rest/api/2/search` | High
37 | File | `/s/` | Low
38 | File | `/scripts/cpan_config` | High
39 | File | `/secure/admin/InsightDefaultCustomFieldConfig.jspa` | High
40 | File | `/server-info` | Medium
41 | File | `/services/system/setup.json` | High
42 | File | `/spip.php` | Medium
43 | File | `/sys/dict/queryTableData` | High
44 | File | `/tmp` | Low
45 | File | `/uncpath/` | Medium
46 | File | `/vloggers_merch/?p=view_product` | High
47 | File | `/webconsole/APIController` | High
48 | File | `/websocket/exec` | High
49 | ... | ... | ...

There are 426 more IOA items available (file, library, argument, input value, pattern, network port). Please use our online service to access the data.

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

(c) [1997-2023](https://vuldb.com/?kb.changelog) by [vuldb.com](https://vuldb.com/?kb.about). All data on this page is shared under the license [CC BY-NC-SA 4.0](https://creativecommons.org/licenses/by-nc-sa/4.0/). Questions? Check the [FAQ](https://vuldb.com/?kb.faq), read the [documentation](https://vuldb.com/?kb) or [contact us](https://vuldb.com/?contact)!
