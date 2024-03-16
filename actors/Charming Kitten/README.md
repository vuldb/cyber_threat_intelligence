# Charming Kitten - Cyber Threat Intelligence

These _indicators_ were reported, collected, and generated during the [VulDB CTI analysis](https://vuldb.com/?kb.cti) of the actor known as [Charming Kitten](https://vuldb.com/?actor.charming_kitten). The _activity monitoring_ correlates data from social media, forums, chat rooms, and darknet markets. It helps to determine associated actors, specific activities, expected intentions, emerging research, and ongoing attacks. Our unique _predictive model_ uses _big data_ to forecast activities and their characteristics.

_Live data_ and more _analysis capabilities_ are available at [https://vuldb.com/?actor.charming_kitten](https://vuldb.com/?actor.charming_kitten)

## Campaigns

The following _campaigns_ are known and can be associated with Charming Kitten:

* CVE-2021-34473 / CVE-2021-34523 / CVE-2021-31207
* HYPERSCRAPE
* Log4Shell

## Countries

These _countries_ are directly (e.g. origin of attacks) or indirectly (e.g. access by proxy) associated with Charming Kitten:

* [CN](https://vuldb.com/?country.cn)
* [US](https://vuldb.com/?country.us)
* [NL](https://vuldb.com/?country.nl)
* ...

There are 8 more country items available. Please use our online service to access the data.

## IOC - Indicator of Compromise

These _indicators of compromise_ (IOC) indicate associated network resources which are known to be part of research and attack activities of Charming Kitten.

ID | IP address | Hostname | Campaign | Confidence
-- | ---------- | -------- | -------- | ----------
1 | [5.79.69.198](https://vuldb.com/?ip.5.79.69.198) | - | - | High
2 | [5.79.69.206](https://vuldb.com/?ip.5.79.69.206) | - | - | High
3 | [5.79.105.153](https://vuldb.com/?ip.5.79.105.153) | - | - | High
4 | [5.79.105.156](https://vuldb.com/?ip.5.79.105.156) | - | - | High
5 | [5.79.105.161](https://vuldb.com/?ip.5.79.105.161) | - | - | High
6 | [5.79.105.165](https://vuldb.com/?ip.5.79.105.165) | - | - | High
7 | [5.152.202.51](https://vuldb.com/?ip.5.152.202.51) | h5-152-202-51.host.redstation.co.uk | - | High
8 | [5.152.202.52](https://vuldb.com/?ip.5.152.202.52) | h5-152-202-52.host.redstation.co.uk | - | High
9 | [31.3.236.90](https://vuldb.com/?ip.31.3.236.90) | h31-3-236-90.host.redstation.co.uk | - | High
10 | [31.3.236.91](https://vuldb.com/?ip.31.3.236.91) | h31-3-236-91.host.redstation.co.uk | - | High
11 | [31.3.236.92](https://vuldb.com/?ip.31.3.236.92) | h31-3-236-92.host.redstation.co.uk | - | High
12 | [37.220.8.13](https://vuldb.com/?ip.37.220.8.13) | h37-220-8-13.host.redstation.co.uk | - | High
13 | [46.17.97.37](https://vuldb.com/?ip.46.17.97.37) | - | - | High
14 | [46.17.97.40](https://vuldb.com/?ip.46.17.97.40) | - | - | High
15 | [46.17.97.240](https://vuldb.com/?ip.46.17.97.240) | - | - | High
16 | [46.17.97.243](https://vuldb.com/?ip.46.17.97.243) | - | - | High
17 | [51.254.254.217](https://vuldb.com/?ip.51.254.254.217) | me14.mecide.com | - | High
18 | [51.255.28.57](https://vuldb.com/?ip.51.255.28.57) | - | - | High
19 | [54.36.217.8](https://vuldb.com/?ip.54.36.217.8) | ip8.ip-54-36-217.eu | - | High
20 | [54.37.164.254](https://vuldb.com/?ip.54.37.164.254) | - | - | High
21 | [54.38.49.6](https://vuldb.com/?ip.54.38.49.6) | ip6.ip-54-38-49.eu | Log4Shell | High
22 | [69.30.221.126](https://vuldb.com/?ip.69.30.221.126) | - | - | High
23 | ... | ... | ... | ...

There are 87 more IOC items available. Please use our online service to access the data.

## TTP - Tactics, Techniques, Procedures

_Tactics, techniques, and procedures_ (TTP) summarize the suspected MITRE ATT&CK techniques used by _Charming Kitten_. This data is unique as it uses our predictive model for actor profiling.

ID | Technique | Weakness | Description | Confidence
-- | --------- | -------- | ----------- | ----------
1 | T1006 | CWE-21, CWE-22, CWE-23, CWE-24 | Path Traversal | High
2 | T1040 | CWE-294, CWE-319 | Authentication Bypass by Capture-replay | High
3 | T1055 | CWE-74 | Injection | High
4 | T1059 | CWE-88, CWE-94, CWE-1321 | Argument Injection | High
5 | T1059.007 | CWE-79, CWE-80 | Cross Site Scripting | High
6 | ... | ... | ... | ...

There are 20 more TTP items available. Please use our online service to access the data.

## IOA - Indicator of Attack

These _indicators of attack_ (IOA) list the potential fragments used for technical activities like reconnaissance, exploitation, privilege escalation, and exfiltration by Charming Kitten. This data is unique as it uses our predictive model for actor profiling.

ID | Type | Indicator | Confidence
-- | ---- | --------- | ----------
1 | File | `/?p=products` | Medium
2 | File | `/admin.php/accessory/filesdel.html` | High
3 | File | `/admin/?page=user/manage` | High
4 | File | `/admin/add-new.php` | High
5 | File | `/admin/controller/JobLogController.java` | High
6 | File | `/admin/doctors.php` | High
7 | File | `/alphaware/summary.php` | High
8 | File | `/api/` | Low
9 | File | `/api/admin/store/product/list` | High
10 | File | `/api/baskets/{name}` | High
11 | File | `/api/stl/actions/search` | High
12 | File | `/api/sys/login` | High
13 | File | `/api/sys/set_passwd` | High
14 | File | `/api/trackedEntityInstances` | High
15 | File | `/api/v2/cli/commands` | High
16 | File | `/apply.cgi` | Medium
17 | File | `/aux` | Low
18 | File | `/bin/ate` | Medium
19 | File | `/boat/login.php` | High
20 | File | `/booking/show_bookings/` | High
21 | File | `/cgi-bin` | Medium
22 | File | `/cgi-bin/wlogin.cgi` | High
23 | File | `/changePassword` | High
24 | File | `/Content/Template/root/reverse-shell.aspx` | High
25 | File | `/cwms/classes/Master.php?f=save_contact` | High
26 | File | `/dashboard/add-blog.php` | High
27 | File | `/data/remove` | Medium
28 | File | `/debug/pprof` | Medium
29 | File | `/ecshop/admin/template.php` | High
30 | File | `/env` | Low
31 | File | `/etc/passwd` | Medium
32 | File | `/forum/away.php` | High
33 | File | `/group1/uploa` | High
34 | File | `/index.php` | Medium
35 | File | `/librarian/bookdetails.php` | High
36 | File | `/nagiosxi/admin/banner_message-ajaxhelper.php` | High
37 | File | `/php-sms/admin/?page=user/manage_user` | High
38 | File | `/reservation/add_message.php` | High
39 | File | `/resources//../` | High
40 | File | `/testConnection` | High
41 | File | `/tmp/ppd.trace` | High
42 | File | `/user/inc/workidajax.php` | High
43 | File | `/user/updatePwd` | High
44 | ... | ... | ...

There are 382 more IOA items available (file, library, argument, input value, pattern, network port). Please use our online service to access the data.

## References

The following list contains _external sources_ which discuss the actor and the associated activities:

* https://blog.google/threat-analysis-group/new-iranian-apt-data-extraction-tool/
* https://github.com/blackorbird/APT_REPORT/tree/master/Charming%20Kitten
* https://research.checkpoint.com/2022/apt35-exploits-log4j-vulnerability-to-distribute-new-modular-powershell-toolkit/
* https://thedfirreport.com/2022/03/21/apt35-automates-initial-access-using-proxyshell/
* https://vxug.fakedoma.in/archive/APTs/2021/2021.01.08/Charming%20Kitten.pdf
* https://www.clearskysec.com/wp-content/uploads/2017/12/Charming_Kitten_2017.pdf

## Literature

The following _articles_ explain our unique predictive cyber threat intelligence:

* [VulDB Cyber Threat Intelligence Documentation](https://vuldb.com/?kb.cti)
* [Cyber Threat Intelligence - Early Anticipation of Attacks](https://www.scip.ch/en/?labs.20201022)

## License

(c) [1997-2024](https://vuldb.com/?kb.changelog) by [vuldb.com](https://vuldb.com/?kb.about). All data on this page is shared under the license [CC BY-NC-SA 4.0](https://creativecommons.org/licenses/by-nc-sa/4.0/). Questions? Check the [FAQ](https://vuldb.com/?kb.faq), read the [documentation](https://vuldb.com/?kb) or [contact us](https://vuldb.com/?contact)!
