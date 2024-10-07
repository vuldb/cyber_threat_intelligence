# Agent - Cyber Threat Intelligence

These _indicators_ were reported, collected, and generated during the [VulDB CTI analysis](https://vuldb.com/?kb.cti) of the actor known as [Agent](https://vuldb.com/?actor.agent). The _activity monitoring_ correlates data from social media, forums, chat rooms, and darknet markets. It helps to determine associated actors, specific activities, expected intentions, emerging research, and ongoing attacks. Our unique _predictive model_ uses _big data_ to forecast activities and their characteristics.

_Live data_ and more _analysis capabilities_ are available at [https://vuldb.com/?actor.agent](https://vuldb.com/?actor.agent)

## Countries

These _countries_ are directly (e.g. origin of attacks) or indirectly (e.g. access by proxy) associated with Agent:

* [US](https://vuldb.com/?country.us)
* [CN](https://vuldb.com/?country.cn)
* [CH](https://vuldb.com/?country.ch)
* ...

There are 21 more country items available. Please use our online service to access the data.

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
4 | T1059.007 | CWE-79, CWE-80 | Cross Site Scripting | High
5 | T1068 | CWE-250, CWE-264, CWE-269, CWE-284 | Execution with Unnecessary Privileges | High
6 | ... | ... | ... | ...

There are 21 more TTP items available. Please use our online service to access the data.

## IOA - Indicator of Attack

These _indicators of attack_ (IOA) list the potential fragments used for technical activities like reconnaissance, exploitation, privilege escalation, and exfiltration by Agent. This data is unique as it uses our predictive model for actor profiling.

ID | Type | Indicator | Confidence
-- | ---- | --------- | ----------
1 | File | `/+CSCOE+/logon.html` | High
2 | File | `/act/ActDao.xml` | High
3 | File | `/admin.php?p=/Area/index#tab=t2` | High
4 | File | `/admin/` | Low
5 | File | `/admin/admin-update-employee.php` | High
6 | File | `/ajax.php?action=read_msg` | High
7 | File | `/api` | Low
8 | File | `/api/clusters/local/topics/{topic}/messages` | High
9 | File | `/api/gen/clients/{language}` | High
10 | File | `/API/info` | Medium
11 | File | `/app/options.py` | High
12 | File | `/bin/httpd` | Medium
13 | File | `/cgi-bin/supervisor/adcommand.cgi` | High
14 | File | `/cgi-bin/tosei_kikai.php` | High
15 | File | `/cgi-bin/wapopen` | High
16 | File | `/ci_spms/admin/category` | High
17 | File | `/ci_spms/admin/search/searching/` | High
18 | File | `/classes/Master.php?f=delete_appointment` | High
19 | File | `/classes/Master.php?f=delete_train` | High
20 | File | `/Content/Template/root/reverse-shell.aspx` | High
21 | File | `/Controller/Ajaxfileupload.ashx` | High
22 | File | `/ctcprotocol/Protocol` | High
23 | File | `/dashboard/menu-list.php` | High
24 | File | `/dashboard/updatelogo.php` | High
25 | File | `/debug/pprof` | Medium
26 | File | `/detailed.php` | High
27 | File | `/dist/index.js` | High
28 | File | `/DXR.axd` | Medium
29 | File | `/ebics-server/ebics.aspx` | High
30 | File | `/etc/openshift/server_priv.pem` | High
31 | File | `/EXCU_SHELL` | Medium
32 | File | `/ffos/classes/Master.php?f=save_category` | High
33 | File | `/forum/away.php` | High
34 | File | `/goform/form2systime.cgi` | High
35 | File | `/goform/modifyDhcpRule` | High
36 | File | `/goform/ModifyPppAuthWhiteMac` | High
37 | File | `/goform/net\_Web\_get_value` | High
38 | File | `/goform/setStaOffline` | High
39 | File | `/goform/WizardHandle` | High
40 | File | `/goforms/rlminfo` | High
41 | File | `/GponForm/usb_restore_Form?script/` | High
42 | File | `/group1/uploa` | High
43 | File | `/hedwig.cgi` | Medium
44 | File | `/HNAP1` | Low
45 | File | `/HNAP1/SetClientInfo` | High
46 | ... | ... | ...

There are 400 more IOA items available (file, library, argument, input value, pattern, network port). Please use our online service to access the data.

## References

The following list contains _external sources_ which discuss the actor and the associated activities:

* https://blog.talosintelligence.com/2018/01/threat-round-up-0105-0512.html
* https://github.com/sophoslabs/IoCs/blob/master/Troj-Agent-BKJE.csv

## Literature

The following _articles_ explain our unique predictive cyber threat intelligence:

* [VulDB Cyber Threat Intelligence Documentation](https://vuldb.com/?kb.cti)
* [Cyber Threat Intelligence - Early Anticipation of Attacks](https://www.scip.ch/en/?labs.20201022)

## License

(c) [1997-2024](https://vuldb.com/?kb.changelog) by [vuldb.com](https://vuldb.com/?kb.about). All data on this page is shared under the license [CC BY-NC-SA 4.0](https://creativecommons.org/licenses/by-nc-sa/4.0/). Questions? Check the [FAQ](https://vuldb.com/?kb.faq), read the [documentation](https://vuldb.com/?kb) or [contact us](https://vuldb.com/?contact)!
