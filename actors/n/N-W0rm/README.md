# N-W0rm - Cyber Threat Intelligence

These _indicators_ were reported, collected, and generated during the [VulDB CTI analysis](https://vuldb.com/?kb.cti) of the actor known as [N-W0rm](https://vuldb.com/?actor.n-w0rm). The _activity monitoring_ correlates data from social media, forums, chat rooms, and darknet markets. It helps to determine associated actors, specific activities, expected intentions, emerging research, and ongoing attacks. Our unique _predictive model_ uses _big data_ to forecast activities and their characteristics.

_Live data_ and more _analysis capabilities_ are available at [https://vuldb.com/?actor.n-w0rm](https://vuldb.com/?actor.n-w0rm)

## Countries

These _countries_ are directly (e.g. origin of attacks) or indirectly (e.g. access by proxy) associated with N-W0rm:

* [US](https://vuldb.com/?country.us)
* [CN](https://vuldb.com/?country.cn)
* [ES](https://vuldb.com/?country.es)
* ...

There are 18 more country items available. Please use our online service to access the data.

## IOC - Indicator of Compromise

These _indicators of compromise_ (IOC) indicate associated network resources which are known to be part of research and attack activities of N-W0rm.

ID | IP address | Hostname | Campaign | Confidence
-- | ---------- | -------- | -------- | ----------
1 | [2.56.254.54](https://vuldb.com/?ip.2.56.254.54) | - | - | High
2 | [5.188.159.44](https://vuldb.com/?ip.5.188.159.44) | - | - | High
3 | [20.48.21.149](https://vuldb.com/?ip.20.48.21.149) | - | - | High
4 | [23.7.53.229](https://vuldb.com/?ip.23.7.53.229) | a23-7-53-229.deploy.static.akamaitechnologies.com | - | High
5 | [23.8.82.173](https://vuldb.com/?ip.23.8.82.173) | a23-8-82-173.deploy.static.akamaitechnologies.com | - | High
6 | [23.9.169.37](https://vuldb.com/?ip.23.9.169.37) | a23-9-169-37.deploy.static.akamaitechnologies.com | - | High
7 | [23.204.189.35](https://vuldb.com/?ip.23.204.189.35) | a23-204-189-35.deploy.static.akamaitechnologies.com | - | High
8 | [35.83.156.201](https://vuldb.com/?ip.35.83.156.201) | ec2-35-83-156-201.us-west-2.compute.amazonaws.com | - | Medium
9 | [35.168.183.178](https://vuldb.com/?ip.35.168.183.178) | ec2-35-168-183-178.compute-1.amazonaws.com | - | Medium
10 | [37.113.171.12](https://vuldb.com/?ip.37.113.171.12) | dynamicip-37-113-171-12.pppoe.chel.ertelecom.ru | - | High
11 | [37.120.141.147](https://vuldb.com/?ip.37.120.141.147) | - | - | High
12 | [37.120.141.190](https://vuldb.com/?ip.37.120.141.190) | - | - | High
13 | [37.139.129.243](https://vuldb.com/?ip.37.139.129.243) | - | - | High
14 | [42.157.128.69](https://vuldb.com/?ip.42.157.128.69) | - | - | High
15 | ... | ... | ... | ...

There are 57 more IOC items available. Please use our online service to access the data.

## TTP - Tactics, Techniques, Procedures

_Tactics, techniques, and procedures_ (TTP) summarize the suspected MITRE ATT&CK techniques used by _N-W0rm_. This data is unique as it uses our predictive model for actor profiling.

ID | Technique | Weakness | Description | Confidence
-- | --------- | -------- | ----------- | ----------
1 | T1006 | CWE-21, CWE-22, CWE-23, CWE-29, CWE-425 | Path Traversal | High
2 | T1055 | CWE-74, CWE-643 | Improper Neutralization of Data within XPath Expressions | High
3 | T1059 | CWE-88, CWE-94 | Argument Injection | High
4 | T1059.007 | CWE-79, CWE-80 | Cross Site Scripting | High
5 | T1068 | CWE-250, CWE-264, CWE-269, CWE-284 | Execution with Unnecessary Privileges | High
6 | ... | ... | ... | ...

There are 18 more TTP items available. Please use our online service to access the data.

## IOA - Indicator of Attack

These _indicators of attack_ (IOA) list the potential fragments used for technical activities like reconnaissance, exploitation, privilege escalation, and exfiltration by N-W0rm. This data is unique as it uses our predictive model for actor profiling.

ID | Type | Indicator | Confidence
-- | ---- | --------- | ----------
1 | File | `/.pomerium` | Medium
2 | File | `/admin/add_ikev2.php` | High
3 | File | `/admin/ajax.php?action=delete_user` | High
4 | File | `/admin/category_save.php` | High
5 | File | `/Admin/changepassword.php` | High
6 | File | `/admin/emp-profile-avatar.php` | High
7 | File | `/admin/general-setting` | High
8 | File | `/admin/inquiries/view_inquiry.php` | High
9 | File | `/admin/list_ipAddressPolicy.php` | High
10 | File | `/admin/manage_model.php` | High
11 | File | `/admin/manage_user.php` | High
12 | File | `/admin/projects/{projectname}/skills/{skillname}/video` | High
13 | File | `/admin/service` | High
14 | File | `/admin/subject.php` | High
15 | File | `/api/v1/custom_component` | High
16 | File | `/applications/core/modules/admin/editor/toolbar.php` | High
17 | File | `/applications/nexus/modules/front/store/store.php` | High
18 | File | `/building/backmgr/urlpage/mobileurl/configfile/jx2_config.ini` | High
19 | File | `/catalog/all-products` | High
20 | File | `/cgi-bin/cstecgi.cgi` | High
21 | File | `/cgi-bin/nas_sharing.cgi` | High
22 | File | `/cgi-bin/photocenter_mgr.cgi` | High
23 | File | `/classes/Master.php` | High
24 | File | `/classes/Master.php?f=delete_category` | High
25 | File | `/classes/Master.php?f=save_medicine` | High
26 | File | `/classes/Users.php?f=delete` | High
27 | File | `/classes/Users.php?f=save` | High
28 | File | `/config/api/v1/reboot` | High
29 | File | `/DXR.axd` | Medium
30 | File | `/edit-subject.php` | High
31 | File | `/endpoint/add-user.php` | High
32 | File | `/etc/postfix/sender_login` | High
33 | File | `/etc/shadow` | Medium
34 | File | `/formSysLog` | Medium
35 | File | `/forum/away.php` | High
36 | File | `/goform/SetIpMacBind` | High
37 | File | `/goform/SetOnlineDevName` | High
38 | File | `/goform/SetSysTimeCfg` | High
39 | File | `/goform/WifiExtraSet` | High
40 | ... | ... | ...

There are 343 more IOA items available (file, library, argument, input value, pattern, network port). Please use our online service to access the data.

## References

The following list contains _external sources_ which discuss the actor and the associated activities:

* https://threatfox.abuse.ch

## Literature

The following _articles_ explain our unique predictive cyber threat intelligence:

* [VulDB Cyber Threat Intelligence Documentation](https://vuldb.com/?kb.cti)
* [Cyber Threat Intelligence - Early Anticipation of Attacks](https://www.scip.ch/en/?labs.20201022)

## License

(c) [1997-2024](https://vuldb.com/?kb.changelog) by [vuldb.com](https://vuldb.com/?kb.about). All data on this page is shared under the license [CC BY-NC-SA 4.0](https://creativecommons.org/licenses/by-nc-sa/4.0/). Questions? Check the [FAQ](https://vuldb.com/?kb.faq), read the [documentation](https://vuldb.com/?kb) or [contact us](https://vuldb.com/?contact)!
