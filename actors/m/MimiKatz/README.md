# MimiKatz - Cyber Threat Intelligence

These _indicators_ were reported, collected, and generated during the [VulDB CTI analysis](https://vuldb.com/?kb.cti) of the actor known as [MimiKatz](https://vuldb.com/?actor.mimikatz). The _activity monitoring_ correlates data from social media, forums, chat rooms, and darknet markets. It helps to determine associated actors, specific activities, expected intentions, emerging research, and ongoing attacks. Our unique _predictive model_ uses _big data_ to forecast activities and their characteristics.

_Live data_ and more _analysis capabilities_ are available at [https://vuldb.com/?actor.mimikatz](https://vuldb.com/?actor.mimikatz)

## Countries

These _countries_ are directly (e.g. origin of attacks) or indirectly (e.g. access by proxy) associated with MimiKatz:

* [IN](https://vuldb.com/?country.in)
* [US](https://vuldb.com/?country.us)
* [FR](https://vuldb.com/?country.fr)
* ...

There are 6 more country items available. Please use our online service to access the data.

## IOC - Indicator of Compromise

These _indicators of compromise_ (IOC) indicate associated network resources which are known to be part of research and attack activities of MimiKatz.

ID | IP address | Hostname | Campaign | Confidence
-- | ---------- | -------- | -------- | ----------
1 | [5.42.84.155](https://vuldb.com/?ip.5.42.84.155) | craven-sand1.aeza.network | - | High
2 | [20.117.118.95](https://vuldb.com/?ip.20.117.118.95) | - | - | High
3 | [20.172.222.179](https://vuldb.com/?ip.20.172.222.179) | - | - | High
4 | [20.197.11.115](https://vuldb.com/?ip.20.197.11.115) | - | - | High
5 | [38.55.193.31](https://vuldb.com/?ip.38.55.193.31) | - | - | High
6 | [38.180.109.29](https://vuldb.com/?ip.38.180.109.29) | - | - | High
7 | [39.98.204.142](https://vuldb.com/?ip.39.98.204.142) | - | - | High
8 | [39.101.170.107](https://vuldb.com/?ip.39.101.170.107) | - | - | High
9 | [43.138.140.179](https://vuldb.com/?ip.43.138.140.179) | - | - | High
10 | [43.157.65.53](https://vuldb.com/?ip.43.157.65.53) | - | - | High
11 | [45.150.108.3](https://vuldb.com/?ip.45.150.108.3) | - | - | High
12 | [52.151.88.215](https://vuldb.com/?ip.52.151.88.215) | - | - | High
13 | [62.109.5.25](https://vuldb.com/?ip.62.109.5.25) | aeroflot.me | - | High
14 | ... | ... | ... | ...

There are 53 more IOC items available. Please use our online service to access the data.

## TTP - Tactics, Techniques, Procedures

_Tactics, techniques, and procedures_ (TTP) summarize the suspected MITRE ATT&CK techniques used by _MimiKatz_. This data is unique as it uses our predictive model for actor profiling.

ID | Technique | Weakness | Description | Confidence
-- | --------- | -------- | ----------- | ----------
1 | T1006 | CWE-21, CWE-22, CWE-23, CWE-24 | Path Traversal | High
2 | T1040 | CWE-319 | Authentication Bypass by Capture-replay | High
3 | T1055 | CWE-74 | Improper Neutralization of Data within XPath Expressions | High
4 | T1059 | CWE-94, CWE-1321 | Argument Injection | High
5 | T1059.007 | CWE-79, CWE-80 | Basic Cross Site Scripting | High
6 | ... | ... | ... | ...

There are 20 more TTP items available. Please use our online service to access the data.

## IOA - Indicator of Attack

These _indicators of attack_ (IOA) list the potential fragments used for technical activities like reconnaissance, exploitation, privilege escalation, and exfiltration by MimiKatz. This data is unique as it uses our predictive model for actor profiling.

ID | Type | Indicator | Confidence
-- | ---- | --------- | ----------
1 | File | `%PROGRAMDATA%\Razer\Synapse3\Service\bin` | High
2 | File | `/.vnc/sesman_${username}_passwd` | High
3 | File | `/?page=reports` | High
4 | File | `/admin-manage-user.php` | High
5 | File | `/admin/` | Low
6 | File | `/admin/add_ikev2.php` | High
7 | File | `/admin/admin-profile.php` | High
8 | File | `/admin/borrow_add.php` | High
9 | File | `/admin/category_row.php` | High
10 | File | `/admin/communitymanagement.php` | High
11 | File | `/admin/emp-profile-avatar.php` | High
12 | File | `/admin/index.php?page=categories` | High
13 | File | `/admin/login.php` | High
14 | File | `/Admin/login.php` | High
15 | File | `/admin/project/update/2` | High
16 | File | `/admin/request-received-bydonar.php` | High
17 | File | `/admin/students/manage.php` | High
18 | File | `/admin/success_story.php` | High
19 | File | `/admin/SysModule/upload/ajaxmodel/upload/uploadfilepath/sysmodule_1` | High
20 | File | `/ajax.php?action=load_answered` | High
21 | File | `/api/v2/cli/commands` | High
22 | File | `/cgi-bin/cstecgi.cgi` | High
23 | File | `/cgi-bin/nas_sharing.cgi` | High
24 | File | `/classes/Master.php` | High
25 | File | `/classes/Users.php?f=save` | High
26 | File | `/control/activate_case.php` | High
27 | File | `/debug/pprof` | Medium
28 | File | `/download` | Medium
29 | File | `/download/image` | High
30 | File | `/edit1.php` | Medium
31 | File | `/Employee/edit-profile.php` | High
32 | File | `/Employer/EditProfile.php` | High
33 | File | `/Employer/ManageJob.php` | High
34 | File | `/etc/sysconfig/btrfsmaintenance` | High
35 | File | `/firewall/policy/` | High
36 | File | `/forgot.php` | Medium
37 | File | `/forum/away.php` | High
38 | File | `/general/email/inbox/delete_webmail.php` | High
39 | File | `/getcfg.php` | Medium
40 | File | `/goform/addWifiMacFilter` | High
41 | File | `/goform/formEasySetTimezone` | High
42 | File | `/goform/SetSysTimeCfg` | High
43 | File | `/hedwig.cgi` | Medium
44 | File | `/ims/login.php` | High
45 | ... | ... | ...

There are 389 more IOA items available (file, library, argument, input value, pattern, network port). Please use our online service to access the data.

## References

The following list contains _external sources_ which discuss the actor and the associated activities:

* https://search.censys.io/hosts/5.42.84.155
* https://search.censys.io/hosts/20.117.118.95
* https://search.censys.io/hosts/20.172.222.179
* https://search.censys.io/hosts/20.197.11.115
* https://search.censys.io/hosts/34.46.171.85+85.171.46.34.bc.googleusercontent.com
* https://search.censys.io/hosts/38.55.193.31
* https://search.censys.io/hosts/38.180.109.29
* https://search.censys.io/hosts/39.98.204.142
* https://search.censys.io/hosts/39.101.170.107
* https://search.censys.io/hosts/43.138.140.179
* https://search.censys.io/hosts/43.157.65.53
* https://search.censys.io/hosts/45.150.108.3
* https://search.censys.io/hosts/52.151.88.215
* https://search.censys.io/hosts/62.109.5.25
* https://search.censys.io/hosts/62.109.5.25+117.54.129.180.unknown.m1.com.sg.prodejdilu.cz
* https://search.censys.io/hosts/62.109.5.25+184.88.78.218.dial.xw.sh.dynamic.163data.com.cn.prodejdilu.cz
* https://search.censys.io/hosts/80.76.51.159
* https://search.censys.io/hosts/81.16.6.166
* https://search.censys.io/hosts/81.95.8.174
* https://search.censys.io/hosts/81.169.141.174
* https://search.censys.io/hosts/83.136.254.53
* https://search.censys.io/hosts/83.136.255.209
* https://search.censys.io/hosts/84.201.150.223
* https://search.censys.io/hosts/86.125.233.221
* https://search.censys.io/hosts/89.197.154.116
* https://search.censys.io/hosts/94.237.29.84
* https://search.censys.io/hosts/94.237.31.241
* https://search.censys.io/hosts/94.237.55.77
* https://search.censys.io/hosts/94.237.59.211
* https://search.censys.io/hosts/94.237.87.140
* https://search.censys.io/hosts/94.237.101.5
* https://search.censys.io/hosts/100.1.226.154
* https://search.censys.io/hosts/101.42.158.190
* https://search.censys.io/hosts/103.142.9.181
* https://search.censys.io/hosts/103.142.9.183
* https://search.censys.io/hosts/106.51.16.29
* https://search.censys.io/hosts/106.55.181.138
* https://search.censys.io/hosts/108.143.124.130
* https://search.censys.io/hosts/117.50.177.30
* https://search.censys.io/hosts/117.72.36.133
* https://search.censys.io/hosts/120.25.163.165
* https://search.censys.io/hosts/121.5.73.12
* https://search.censys.io/hosts/124.221.38.181
* https://search.censys.io/hosts/124.221.47.70
* https://search.censys.io/hosts/147.45.156.121
* https://search.censys.io/hosts/149.88.74.5
* https://search.censys.io/hosts/165.232.161.164
* https://search.censys.io/hosts/165.232.186.159
* https://search.censys.io/hosts/167.99.60.195
* https://search.censys.io/hosts/169.239.129.45
* https://search.censys.io/hosts/172.233.1.11
* https://search.censys.io/hosts/173.249.57.136
* https://search.censys.io/hosts/176.145.117.173
* https://search.censys.io/hosts/178.63.172.2
* https://search.censys.io/hosts/182.153.48.169
* https://search.censys.io/hosts/185.203.216.41
* https://search.censys.io/hosts/188.127.249.150
* https://search.censys.io/hosts/188.166.125.132
* https://search.censys.io/hosts/192.248.154.28
* https://search.censys.io/hosts/193.32.178.182
* https://search.censys.io/hosts/209.94.59.99
* https://search.censys.io/hosts/209.151.146.107
* https://search.censys.io/hosts/209.151.153.216
* https://search.censys.io/hosts/209.151.154.222
* https://search.censys.io/hosts/213.199.51.167
* https://search.censys.io/hosts/218.250.51.135

## Literature

The following _articles_ explain our unique predictive cyber threat intelligence:

* [VulDB Cyber Threat Intelligence Documentation](https://vuldb.com/?kb.cti)
* [Cyber Threat Intelligence - Early Anticipation of Attacks](https://www.scip.ch/en/?labs.20201022)

## License

(c) [1997-2024](https://vuldb.com/?kb.changelog) by [vuldb.com](https://vuldb.com/?kb.about). All data on this page is shared under the license [CC BY-NC-SA 4.0](https://creativecommons.org/licenses/by-nc-sa/4.0/). Questions? Check the [FAQ](https://vuldb.com/?kb.faq), read the [documentation](https://vuldb.com/?kb) or [contact us](https://vuldb.com/?contact)!
