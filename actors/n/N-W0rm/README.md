# N-W0rm - Cyber Threat Intelligence

These _indicators_ were reported, collected, and generated during the [VulDB CTI analysis](https://vuldb.com/?kb.cti) of the actor known as [N-W0rm](https://vuldb.com/?actor.n-w0rm). The _activity monitoring_ correlates data from social media, forums, chat rooms, and darknet markets. It helps to determine associated actors, specific activities, expected intentions, emerging research, and ongoing attacks. Our unique _predictive model_ uses _big data_ to forecast activities and their characteristics.

_Live data_ and more _analysis capabilities_ are available at [https://vuldb.com/?actor.n-w0rm](https://vuldb.com/?actor.n-w0rm)

## Countries

These _countries_ are directly (e.g. origin of attacks) or indirectly (e.g. access by proxy) associated with N-W0rm:

* [US](https://vuldb.com/?country.us)
* [CN](https://vuldb.com/?country.cn)
* [RU](https://vuldb.com/?country.ru)
* ...

There are 24 more country items available. Please use our online service to access the data.

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
15 | [43.248.98.121](https://vuldb.com/?ip.43.248.98.121) | - | - | High
16 | ... | ... | ... | ...

There are 58 more IOC items available. Please use our online service to access the data.

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

There are 22 more TTP items available. Please use our online service to access the data.

## IOA - Indicator of Attack

These _indicators of attack_ (IOA) list the potential fragments used for technical activities like reconnaissance, exploitation, privilege escalation, and exfiltration by N-W0rm. This data is unique as it uses our predictive model for actor profiling.

ID | Type | Indicator | Confidence
-- | ---- | --------- | ----------
1 | File | `/+CSCOE+/logon.html` | High
2 | File | `/.pomerium` | Medium
3 | File | `/add_new_invoice.php` | High
4 | File | `/admin/?page=bike` | High
5 | File | `/admin/?page=musics/manage_music` | High
6 | File | `/admin/add_ikev2.php` | High
7 | File | `/admin/ajax.php?action=delete_user` | High
8 | File | `/admin/apply.php` | High
9 | File | `/admin/book-details.php` | High
10 | File | `/admin/bwdates-report-details.php` | High
11 | File | `/admin/category_save.php` | High
12 | File | `/admin/cms_content.php` | High
13 | File | `/admin/create-package.php` | High
14 | File | `/admin/doAdminAction.php?act=addCate` | High
15 | File | `/admin/edit-brand.php` | High
16 | File | `/admin/emp-profile-avatar.php` | High
17 | File | `/admin/forms/option_lists/edit.php` | High
18 | File | `/admin/inquiries/view_inquiry.php` | High
19 | File | `/admin/list_ipAddressPolicy.php` | High
20 | File | `/admin/manage_model.php` | High
21 | File | `/admin/manage_user.php` | High
22 | File | `/admin/order.php` | High
23 | File | `/admin/projects/{projectname}/skills/{skillname}/video` | High
24 | File | `/admin/robot.php` | High
25 | File | `/admin/sou.php` | High
26 | File | `/admin/subject.php` | High
27 | File | `/admin/users.php` | High
28 | File | `/api/v1/custom_component` | High
29 | File | `/api/v2/cli/commands` | High
30 | File | `/building/backmgr/urlpage/mobileurl/configfile/jx2_config.ini` | High
31 | File | `/car-rental-management-system/admin/index.php?page=manage_car` | High
32 | File | `/cgi-bin/apkg_mgr.cgi` | High
33 | File | `/cgi-bin/cstecgi.cgi` | High
34 | File | `/cgi-bin/nas_sharing.cgi` | High
35 | File | `/cgi-bin/photocenter_mgr.cgi` | High
36 | File | `/classes/Master.php` | High
37 | File | `/classes/Master.php?f=delete_category` | High
38 | File | `/classes/Master.php?f=delete_record` | High
39 | File | `/classes/Master.php?f=save_medicine` | High
40 | File | `/classes/SystemSettings.php?f=update_settings` | High
41 | File | `/classes/Users.php?f=delete` | High
42 | File | `/classes/Users.php?f=save` | High
43 | File | `/cloudstore/ecode/setup/ecology_dev.zip` | High
44 | File | `/deal/{note_id}/note` | High
45 | File | `/detailed.php` | High
46 | File | `/downloadFile.php` | High
47 | File | `/dtale/chart-data/1` | High
48 | File | `/DXR.axd` | Medium
49 | File | `/edit-subject.php` | High
50 | File | `/endpoint/add-folder.php` | High
51 | File | `/endpoint/add-user.php` | High
52 | File | `/etc/postfix/sender_login` | High
53 | File | `/etc/shadow` | Medium
54 | File | `/etc/shadow.sample` | High
55 | File | `/file_manager/login.php` | High
56 | File | `/film-rating.php` | High
57 | File | `/filter.php` | Medium
58 | File | `/foms/routers/place-order.php` | High
59 | File | `/formSysLog` | Medium
60 | File | `/forum/away.php` | High
61 | ... | ... | ...

There are 537 more IOA items available (file, library, argument, input value, pattern, network port). Please use our online service to access the data.

## References

The following list contains _external sources_ which discuss the actor and the associated activities:

* https://threatfox.abuse.ch

## Literature

The following _articles_ explain our unique predictive cyber threat intelligence:

* [VulDB Cyber Threat Intelligence Documentation](https://vuldb.com/?kb.cti)
* [Cyber Threat Intelligence - Early Anticipation of Attacks](https://www.scip.ch/en/?labs.20201022)

## License

(c) [1997-2024](https://vuldb.com/?kb.changelog) by [vuldb.com](https://vuldb.com/?kb.about). All data on this page is shared under the license [CC BY-NC-SA 4.0](https://creativecommons.org/licenses/by-nc-sa/4.0/). Questions? Check the [FAQ](https://vuldb.com/?kb.faq), read the [documentation](https://vuldb.com/?kb) or [contact us](https://vuldb.com/?contact)!
