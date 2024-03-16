# Loda - Cyber Threat Intelligence

These _indicators_ were reported, collected, and generated during the [VulDB CTI analysis](https://vuldb.com/?kb.cti) of the actor known as [Loda](https://vuldb.com/?actor.loda). The _activity monitoring_ correlates data from social media, forums, chat rooms, and darknet markets. It helps to determine associated actors, specific activities, expected intentions, emerging research, and ongoing attacks. Our unique _predictive model_ uses _big data_ to forecast activities and their characteristics.

_Live data_ and more _analysis capabilities_ are available at [https://vuldb.com/?actor.loda](https://vuldb.com/?actor.loda)

## Countries

These _countries_ are directly (e.g. origin of attacks) or indirectly (e.g. access by proxy) associated with Loda:

* [VN](https://vuldb.com/?country.vn)
* [SH](https://vuldb.com/?country.sh)
* [US](https://vuldb.com/?country.us)
* ...

There are 8 more country items available. Please use our online service to access the data.

## IOC - Indicator of Compromise

These _indicators of compromise_ (IOC) indicate associated network resources which are known to be part of research and attack activities of Loda.

ID | IP address | Hostname | Campaign | Confidence
-- | ---------- | -------- | -------- | ----------
1 | [2.58.56.188](https://vuldb.com/?ip.2.58.56.188) | powered.by.rdp.sh | - | High
2 | [3.141.204.47](https://vuldb.com/?ip.3.141.204.47) | ec2-3-141-204-47.us-east-2.compute.amazonaws.com | - | Medium
3 | [13.40.105.36](https://vuldb.com/?ip.13.40.105.36) | ec2-13-40-105-36.eu-west-2.compute.amazonaws.com | - | Medium
4 | [34.174.95.150](https://vuldb.com/?ip.34.174.95.150) | 150.95.174.34.bc.googleusercontent.com | - | Medium
5 | [37.0.14.214](https://vuldb.com/?ip.37.0.14.214) | - | - | High
6 | [45.155.249.183](https://vuldb.com/?ip.45.155.249.183) | - | - | High
7 | ... | ... | ... | ...

There are 25 more IOC items available. Please use our online service to access the data.

## TTP - Tactics, Techniques, Procedures

_Tactics, techniques, and procedures_ (TTP) summarize the suspected MITRE ATT&CK techniques used by _Loda_. This data is unique as it uses our predictive model for actor profiling.

ID | Technique | Weakness | Description | Confidence
-- | --------- | -------- | ----------- | ----------
1 | T1006 | CWE-21, CWE-22, CWE-23 | Path Traversal | High
2 | T1040 | CWE-294 | Authentication Bypass by Capture-replay | High
3 | T1055 | CWE-74 | Injection | High
4 | T1059 | CWE-88, CWE-94 | Argument Injection | High
5 | T1059.007 | CWE-79, CWE-80 | Cross Site Scripting | High
6 | ... | ... | ... | ...

There are 21 more TTP items available. Please use our online service to access the data.

## IOA - Indicator of Attack

These _indicators of attack_ (IOA) list the potential fragments used for technical activities like reconnaissance, exploitation, privilege escalation, and exfiltration by Loda. This data is unique as it uses our predictive model for actor profiling.

ID | Type | Indicator | Confidence
-- | ---- | --------- | ----------
1 | File | `/admin/add-category.php` | High
2 | File | `/admin/config/uploadicon.php` | High
3 | File | `/admin/course.php` | High
4 | File | `/admin/general/change-lang` | High
5 | File | `/admin/index2.html` | High
6 | File | `/admin/list_resource_icon.php?action=delete` | High
7 | File | `/admin/orders/view_order.php` | High
8 | File | `/admin/plugin.php` | High
9 | File | `/adv_resource` | High
10 | File | `/alogin.html` | Medium
11 | File | `/api/authentication/login` | High
12 | File | `/api/upload.php` | High
13 | File | `/api/v1/terminal/sessions/?limit=1` | High
14 | File | `/api/v4/opengraph` | High
15 | File | `/api/{org_id}/users/{email_id}` | High
16 | File | `/app/api/controller/default/Sqlite.php` | High
17 | File | `/app/zentao/module/repo/model.php` | High
18 | File | `/application/index/controller/Pay.php` | High
19 | File | `/bookstore/bookPerPub.php` | High
20 | File | `/cgi-bin/cstecgi.cgi` | High
21 | File | `/cgi-bin/cstecgi.cgi?action=login` | High
22 | File | `/cgi-bin/qcmap_auth` | High
23 | File | `/cgi-bin/vitogate.cgi` | High
24 | File | `/collection/all` | High
25 | File | `/configs/application.ini` | High
26 | File | `/course/filterRecords/` | High
27 | File | `/cupseasylive/taxcodecreate.php` | High
28 | File | `/download/image` | High
29 | File | `/DXR.axd` | Medium
30 | File | `/ecrire/exec/puce_statut.php` | High
31 | File | `/files/` | Low
32 | File | `/forum/away.php` | High
33 | File | `/getcfg.php` | Medium
34 | File | `/goform/goform_get_cmd_process` | High
35 | File | `/goform/setAutoPing` | High
36 | File | `/goform/setModules` | High
37 | File | `/goform/telnet` | High
38 | File | `/gracemedia-media-player/templates/files/ajax_controller.php` | High
39 | File | `/gui/terminal_tool.cgi` | High
40 | File | `/h/autoSaveDraft` | High
41 | File | `/include/file.php` | High
42 | File | `/index.php?menu=asterisk_cli` | High
43 | File | `/install.php?m=install&c=index&a=step3` | High
44 | ... | ... | ...

There are 384 more IOA items available (file, library, argument, input value, pattern, network port). Please use our online service to access the data.

## References

The following list contains _external sources_ which discuss the actor and the associated activities:

* https://app.any.run/tasks/0370524d-75ee-4ea2-ad99-01e40a8d6b4a
* https://threatfox.abuse.ch
* https://www.virustotal.com/gui/file/052fba70767b01cb674b9311a220181a87bdf47161280bb6335c6024e163139c/detection

## Literature

The following _articles_ explain our unique predictive cyber threat intelligence:

* [VulDB Cyber Threat Intelligence Documentation](https://vuldb.com/?kb.cti)
* [Cyber Threat Intelligence - Early Anticipation of Attacks](https://www.scip.ch/en/?labs.20201022)

## License

(c) [1997-2024](https://vuldb.com/?kb.changelog) by [vuldb.com](https://vuldb.com/?kb.about). All data on this page is shared under the license [CC BY-NC-SA 4.0](https://creativecommons.org/licenses/by-nc-sa/4.0/). Questions? Check the [FAQ](https://vuldb.com/?kb.faq), read the [documentation](https://vuldb.com/?kb) or [contact us](https://vuldb.com/?contact)!
