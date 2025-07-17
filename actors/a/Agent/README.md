# Agent - Cyber Threat Intelligence

These _indicators_ were reported, collected, and generated during the [VulDB CTI analysis](https://vuldb.com/?kb.cti) of the actor known as [Agent](https://vuldb.com/?actor.agent). The _activity monitoring_ correlates data from social media, forums, chat rooms, and darknet markets. It helps to determine associated actors, specific activities, expected intentions, emerging research, and ongoing attacks. Our unique _predictive model_ uses _big data_ to forecast activities and their characteristics.

_Live data_ and more _analysis capabilities_ are available at [https://vuldb.com/?actor.agent](https://vuldb.com/?actor.agent)

## Countries

These _countries_ are directly (e.g. origin of attacks) or indirectly (e.g. access by proxy) associated with Agent:

* [CN](https://vuldb.com/?country.cn)
* [US](https://vuldb.com/?country.us)
* [CH](https://vuldb.com/?country.ch)
* ...

There are 17 more country items available. Please use our online service to access the data.

## IOC - Indicator of Compromise

These _indicators of compromise_ (IOC) indicate associated network resources which are known to be part of research and attack activities of Agent.

ID | IP address | Hostname | Campaign | Confidence
-- | ---------- | -------- | -------- | ----------
1 | [45.58.190.82](https://vuldb.com/?ip.45.58.190.82) | mta.boltoclose.com | - | High
2 | [46.23.69.44](https://vuldb.com/?ip.46.23.69.44) | webdiversion.uk2.net | - | High
3 | [64.32.22.101](https://vuldb.com/?ip.64.32.22.101) | - | - | High
4 | [66.96.147.117](https://vuldb.com/?ip.66.96.147.117) | 117.147.96.66.static.eigbox.net | - | High
5 | [68.65.121.51](https://vuldb.com/?ip.68.65.121.51) | strategic.com.ua | - | High
6 | ... | ... | ... | ...

There are 21 more IOC items available. Please use our online service to access the data.

## TTP - Tactics, Techniques, Procedures

_Tactics, techniques, and procedures_ (TTP) summarize the suspected MITRE ATT&CK techniques used by _Agent_. This data is unique as it uses our predictive model for actor profiling.

ID | Technique | Weakness | Description | Confidence
-- | --------- | -------- | ----------- | ----------
1 | T1006 | CWE-21, CWE-22, CWE-23, CWE-24, CWE-425 | Path Traversal | High
2 | T1055 | CWE-74 | Improper Neutralization of Data within XPath Expressions | High
3 | T1059 | CWE-88, CWE-94, CWE-1321 | Argument Injection | High
4 | T1059.007 | CWE-79, CWE-80 | Basic Cross Site Scripting | High
5 | T1068 | CWE-250, CWE-264, CWE-269, CWE-284 | Execution with Unnecessary Privileges | High
6 | ... | ... | ... | ...

There are 20 more TTP items available. Please use our online service to access the data.

## IOA - Indicator of Attack

These _indicators of attack_ (IOA) list the potential fragments used for technical activities like reconnaissance, exploitation, privilege escalation, and exfiltration by Agent. This data is unique as it uses our predictive model for actor profiling.

ID | Type | Indicator | Confidence
-- | ---- | --------- | ----------
1 | File | `/+CSCOE+/logon.html` | High
2 | File | `/act/ActDao.xml` | High
3 | File | `/add-students.php` | High
4 | File | `/admin.php?p=/Area/index#tab=t2` | High
5 | File | `/admin/` | Low
6 | File | `/admin/admin-update-employee.php` | High
7 | File | `/admin/booktime.php` | High
8 | File | `/admin/change-image.php` | High
9 | File | `/admin/index.php/web/ajax_all_lists` | High
10 | File | `/admin/login.php` | High
11 | File | `/admin/member_save.php` | High
12 | File | `/admin/search-vehicle.php` | High
13 | File | `/admin/voters_row.php` | High
14 | File | `/ajax.php?action=read_msg` | High
15 | File | `/api` | Low
16 | File | `/api/authentication/login` | High
17 | File | `/api/clusters/local/topics/{topic}/messages` | High
18 | File | `/api/gen/clients/{language}` | High
19 | File | `/API/info` | Medium
20 | File | `/app/options.py` | High
21 | File | `/bin/httpd` | Medium
22 | File | `/cgi-bin/cstecgi.cgi` | High
23 | File | `/cgi-bin/supervisor/adcommand.cgi` | High
24 | File | `/cgi-bin/tosei_kikai.php` | High
25 | File | `/cgi-bin/wapopen` | High
26 | File | `/ci_spms/admin/category` | High
27 | File | `/ci_spms/admin/search/searching/` | High
28 | File | `/classes/Master.php?f=delete_appointment` | High
29 | File | `/classes/Master.php?f=delete_train` | High
30 | File | `/Controller/Ajaxfileupload.ashx` | High
31 | File | `/cov/triggerEnvCov` | High
32 | File | `/ctcprotocol/Protocol` | High
33 | File | `/dashboard/admin/del_plan.php` | High
34 | File | `/dashboard/approve-reject.php` | High
35 | File | `/dashboard/menu-list.php` | High
36 | File | `/dashboard/updatelogo.php` | High
37 | File | `/debug/pprof` | Medium
38 | File | `/dede/file_manage_control.php` | High
39 | File | `/detailed.php` | High
40 | File | `/device.rsp?opt=sys&cmd=___S_O_S_T_R_E_A_MAX___` | High
41 | File | `/dist/index.js` | High
42 | File | `/DXR.axd` | Medium
43 | File | `/ebics-server/ebics.aspx` | High
44 | File | `/empty_rooms.php` | High
45 | File | `/etc/openshift/server_priv.pem` | High
46 | File | `/EXCU_SHELL` | Medium
47 | File | `/ffos/classes/Master.php?f=save_category` | High
48 | File | `/forum/away.php` | High
49 | File | `/general/address/private/address/query/delete.php` | High
50 | File | `/goform/ate` | Medium
51 | File | `/goform/form2systime.cgi` | High
52 | File | `/goform/formSetLog` | High
53 | ... | ... | ...

There are 464 more IOA items available (file, library, argument, input value, pattern, network port). Please use our online service to access the data.

## References

The following list contains _external sources_ which discuss the actor and the associated activities:

* https://blog.talosintelligence.com/2018/01/threat-round-up-0105-0512.html
* https://github.com/sophoslabs/IoCs/blob/master/Troj-Agent-BKJE.csv

## Literature

The following _articles_ explain our unique predictive cyber threat intelligence:

* [VulDB Cyber Threat Intelligence Documentation](https://vuldb.com/?kb.cti)
* [Cyber Threat Intelligence - Early Anticipation of Attacks](https://www.scip.ch/en/?labs.20201022)

## License

(c) [1997-2025](https://vuldb.com/?kb.changelog) by [vuldb.com](https://vuldb.com/?kb.about). All data on this page is shared under the license [CC BY-NC-SA 4.0](https://creativecommons.org/licenses/by-nc-sa/4.0/). Questions? Check the [FAQ](https://vuldb.com/?kb.faq), read the [documentation](https://vuldb.com/?kb) or [contact us](https://vuldb.com/?contact)!
