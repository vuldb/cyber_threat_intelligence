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
* [ES](https://vuldb.com/?country.es)
* [NL](https://vuldb.com/?country.nl)
* ...

There are 12 more country items available. Please use our online service to access the data.

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
23 | [69.30.224.244](https://vuldb.com/?ip.69.30.224.244) | ramuran.eveningcatcher.com | - | High
24 | ... | ... | ... | ...

There are 90 more IOC items available. Please use our online service to access the data.

## TTP - Tactics, Techniques, Procedures

_Tactics, techniques, and procedures_ (TTP) summarize the suspected MITRE ATT&CK techniques used by _Charming Kitten_. This data is unique as it uses our predictive model for actor profiling.

ID | Technique | Weakness | Description | Confidence
-- | --------- | -------- | ----------- | ----------
1 | T1006 | CWE-21, CWE-22, CWE-23 | Pathname Traversal | High
2 | T1040 | CWE-319 | Authentication Bypass by Capture-replay | High
3 | T1055 | CWE-74 | Injection | High
4 | T1059 | CWE-88, CWE-94 | Cross Site Scripting | High
5 | ... | ... | ... | ...

There are 17 more TTP items available. Please use our online service to access the data.

## IOA - Indicator of Attack

These _indicators of attack_ (IOA) list the potential fragments used for technical activities like reconnaissance, exploitation, privilege escalation, and exfiltration by Charming Kitten. This data is unique as it uses our predictive model for actor profiling.

ID | Type | Indicator | Confidence
-- | ---- | --------- | ----------
1 | File | `//proc/kcore` | Medium
2 | File | `/about.php` | Medium
3 | File | `/ad_js.php` | Medium
4 | File | `/Ap4RtpAtom.cpp` | High
5 | File | `/app/options.py` | High
6 | File | `/bcms/admin/?page=user/list` | High
7 | File | `/bsms/?page=manage_account` | High
8 | File | `/cgi-bin/login.cgi` | High
9 | File | `/cgi-bin/luci/api/wireless` | High
10 | File | `/ci_hms/massage_room/edit/1` | High
11 | File | `/core/conditions/AbstractWrapper.java` | High
12 | File | `/dashboard/reports/logs/view` | High
13 | File | `/debian/patches/load_ppp_generic_if_needed` | High
14 | File | `/debug/pprof` | Medium
15 | File | `/etc/hosts` | Medium
16 | File | `/fuel/index.php/fuel/logs/items` | High
17 | File | `/fuel/sitevariables/delete/4` | High
18 | File | `/goform/setmac` | High
19 | File | `/hprms/admin/doctors/manage_doctor.php` | High
20 | File | `/index/jobfairol/show/` | High
21 | File | `/librarian/bookdetails.php` | High
22 | File | `/manage-apartment.php` | High
23 | File | `/mgmt/tm/util/bash` | High
24 | File | `/modules/caddyhttp/rewrite/rewrite.go` | High
25 | File | `/pages/apply_vacancy.php` | High
26 | File | `/plugin/LiveChat/getChat.json.php` | High
27 | File | `/proc/<PID>/mem` | High
28 | File | `/simple_chat_bot/admin/?page=user/manage_user` | High
29 | ... | ... | ...

There are 249 more IOA items available (file, library, argument, input value, pattern, network port). Please use our online service to access the data.

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

(c) [1997-2022](https://vuldb.com/?kb.changelog) by [vuldb.com](https://vuldb.com/?kb.about). All data on this page is shared under the license [CC BY-NC-SA 4.0](https://creativecommons.org/licenses/by-nc-sa/4.0/). Questions? Check the [FAQ](https://vuldb.com/?kb.faq), read the [documentation](https://vuldb.com/?kb) or [contact us](https://vuldb.com/?contact)!
