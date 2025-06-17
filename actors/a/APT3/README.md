# APT3 - Cyber Threat Intelligence

These _indicators_ were reported, collected, and generated during the [VulDB CTI analysis](https://vuldb.com/?kb.cti) of the actor known as [APT3](https://vuldb.com/?actor.apt3). The _activity monitoring_ correlates data from social media, forums, chat rooms, and darknet markets. It helps to determine associated actors, specific activities, expected intentions, emerging research, and ongoing attacks. Our unique _predictive model_ uses _big data_ to forecast activities and their characteristics.

_Live data_ and more _analysis capabilities_ are available at [https://vuldb.com/?actor.apt3](https://vuldb.com/?actor.apt3)

## Campaigns

The following _campaigns_ are known and can be associated with APT3:

* CVE-2015-5119
* Double Tap

## Countries

These _countries_ are directly (e.g. origin of attacks) or indirectly (e.g. access by proxy) associated with APT3:

* [CN](https://vuldb.com/?country.cn)
* [US](https://vuldb.com/?country.us)
* [RU](https://vuldb.com/?country.ru)
* ...

There are 20 more country items available. Please use our online service to access the data.

## IOC - Indicator of Compromise

These _indicators of compromise_ (IOC) indicate associated network resources which are known to be part of research and attack activities of APT3.

ID | IP address | Hostname | Campaign | Confidence
-- | ---------- | -------- | -------- | ----------
1 | [23.99.20.198](https://vuldb.com/?ip.23.99.20.198) | - | - | High
2 | [54.169.89.240](https://vuldb.com/?ip.54.169.89.240) | ec2-54-169-89-240.ap-southeast-1.compute.amazonaws.com | - | Medium
3 | [104.151.248.173](https://vuldb.com/?ip.104.151.248.173) | 173.248-151-104.rdns.scalabledns.com | Double Tap | High
4 | ... | ... | ... | ...

There are 8 more IOC items available. Please use our online service to access the data.

## TTP - Tactics, Techniques, Procedures

_Tactics, techniques, and procedures_ (TTP) summarize the suspected MITRE ATT&CK techniques used by _APT3_. This data is unique as it uses our predictive model for actor profiling.

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

These _indicators of attack_ (IOA) list the potential fragments used for technical activities like reconnaissance, exploitation, privilege escalation, and exfiltration by APT3. This data is unique as it uses our predictive model for actor profiling.

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
13 | File | `/ajax.php?action=read_msg` | High
14 | File | `/api/authentication/login` | High
15 | File | `/api/clusters/local/topics/{topic}/messages` | High
16 | File | `/api/gen/clients/{language}` | High
17 | File | `/API/info` | Medium
18 | File | `/app/options.py` | High
19 | File | `/bin/httpd` | Medium
20 | File | `/cgi-bin/cstecgi.cgi` | High
21 | File | `/cgi-bin/supervisor/adcommand.cgi` | High
22 | File | `/cgi-bin/tosei_kikai.php` | High
23 | File | `/cgi-bin/wapopen` | High
24 | File | `/ci_spms/admin/category` | High
25 | File | `/ci_spms/admin/search/searching/` | High
26 | File | `/classes/Master.php?f=delete_appointment` | High
27 | File | `/classes/Master.php?f=delete_train` | High
28 | File | `/Content/Template/root/reverse-shell.aspx` | High
29 | File | `/cov/triggerEnvCov` | High
30 | File | `/ctcprotocol/Protocol` | High
31 | File | `/dashboard/admin/del_plan.php` | High
32 | File | `/dashboard/approve-reject.php` | High
33 | File | `/dashboard/menu-list.php` | High
34 | File | `/debug/pprof` | Medium
35 | File | `/dede/file_manage_control.php` | High
36 | File | `/detailed.php` | High
37 | File | `/dist/index.js` | High
38 | File | `/DXR.axd` | Medium
39 | File | `/ebics-server/ebics.aspx` | High
40 | File | `/EXCU_SHELL` | Medium
41 | File | `/ffos/classes/Master.php?f=save_category` | High
42 | File | `/forum/away.php` | High
43 | File | `/general/address/private/address/query/delete.php` | High
44 | File | `/goform/ate` | Medium
45 | File | `/goform/form2systime.cgi` | High
46 | File | `/goform/formSetLog` | High
47 | File | `/goform/formWlanSetup_Wizard` | High
48 | File | `/goform/formWlanWizardSetup` | High
49 | File | `/goform/modifyDhcpRule` | High
50 | File | `/goform/ModifyPppAuthWhiteMac` | High
51 | ... | ... | ...

There are 443 more IOA items available (file, library, argument, input value, pattern, network port). Please use our online service to access the data.

## References

The following list contains _external sources_ which discuss the actor and the associated activities:

* https://github.com/fireeye/iocs/blob/master/APT3/62f65dae-9475-44b0-a9eb-c1baebbd9885.ioc
* https://github.com/fireeye/iocs/blob/master/APT3/db0b6ac6-874a-498e-892b-ac7c2020e061.ioc
* https://www.fireeye.com/blog/threat-research/2014/11/operation_doubletap.html
* https://www.fireeye.com/blog/threat-research/2015/07/demonstrating_hustle.html
* https://www.recordedfuture.com/chinese-mss-behind-apt3/
* https://www.threatminer.org/report.php?q=APTGroupUPSTargetsUSGovernmentwithHackingTeamFlashExploit-PaloAltoNetworksBlogPaloAltoNetworksBlog.pdf&y=2015
* https://www.threatminer.org/report.php?q=OperationDoubleTap.pdf&y=2014
* https://www.threatminer.org/report.php?q=SecondAdobeFlashZero-DayCVE-2015-5122fromHackingTeamExploitedinStrategicWebCompromiseTargetingJapaneseVictims%C2%ABThreatResearchBlog_FireEyeInc.pdf&y=2015

## Literature

The following _articles_ explain our unique predictive cyber threat intelligence:

* [VulDB Cyber Threat Intelligence Documentation](https://vuldb.com/?kb.cti)
* [Cyber Threat Intelligence - Early Anticipation of Attacks](https://www.scip.ch/en/?labs.20201022)

## License

(c) [1997-2025](https://vuldb.com/?kb.changelog) by [vuldb.com](https://vuldb.com/?kb.about). All data on this page is shared under the license [CC BY-NC-SA 4.0](https://creativecommons.org/licenses/by-nc-sa/4.0/). Questions? Check the [FAQ](https://vuldb.com/?kb.faq), read the [documentation](https://vuldb.com/?kb) or [contact us](https://vuldb.com/?contact)!
