# Vice Society - Cyber Threat Intelligence

These _indicators_ were reported, collected, and generated during the [VulDB CTI analysis](https://vuldb.com/?kb.cti) of the actor known as [Vice Society](https://vuldb.com/?actor.vice_society). The _activity monitoring_ correlates data from social media, forums, chat rooms, and darknet markets. It helps to determine associated actors, specific activities, expected intentions, emerging research, and ongoing attacks. Our unique _predictive model_ uses _big data_ to forecast activities and their characteristics.

_Live data_ and more _analysis capabilities_ are available at [https://vuldb.com/?actor.vice_society](https://vuldb.com/?actor.vice_society)

## Countries

These _countries_ are directly (e.g. origin of attacks) or indirectly (e.g. access by proxy) associated with Vice Society:

* [US](https://vuldb.com/?country.us)
* [DE](https://vuldb.com/?country.de)
* [GB](https://vuldb.com/?country.gb)
* ...

There are 14 more country items available. Please use our online service to access the data.

## IOC - Indicator of Compromise

These _indicators of compromise_ (IOC) indicate associated network resources which are known to be part of research and attack activities of Vice Society.

ID | IP address | Hostname | Campaign | Confidence
-- | ---------- | -------- | -------- | ----------
1 | [5.39.222.67](https://vuldb.com/?ip.5.39.222.67) | - | - | High
2 | [5.161.136.176](https://vuldb.com/?ip.5.161.136.176) | static.176.136.161.5.clients.your-server.de | - | High
3 | [5.161.150.40](https://vuldb.com/?ip.5.161.150.40) | static.40.150.161.5.clients.your-server.de | - | High
4 | [5.226.141.196](https://vuldb.com/?ip.5.226.141.196) | 196.141.226.5.baremetal.zare.com | - | High
5 | [5.226.141.198](https://vuldb.com/?ip.5.226.141.198) | 198.141.226.5.baremetal.zare.com | - | High
6 | [5.255.99.59](https://vuldb.com/?ip.5.255.99.59) | - | - | High
7 | [5.255.100.101](https://vuldb.com/?ip.5.255.100.101) | - | - | High
8 | [5.255.101.30](https://vuldb.com/?ip.5.255.101.30) | - | - | High
9 | [5.255.103.142](https://vuldb.com/?ip.5.255.103.142) | - | - | High
10 | [5.255.104.237](https://vuldb.com/?ip.5.255.104.237) | - | - | High
11 | ... | ... | ... | ...

There are 40 more IOC items available. Please use our online service to access the data.

## TTP - Tactics, Techniques, Procedures

_Tactics, techniques, and procedures_ (TTP) summarize the suspected MITRE ATT&CK techniques used by _Vice Society_. This data is unique as it uses our predictive model for actor profiling.

ID | Technique | Weakness | Description | Confidence
-- | --------- | -------- | ----------- | ----------
1 | T1006 | CWE-21, CWE-22, CWE-36, CWE-37, CWE-425 | Path Traversal | High
2 | T1040 | CWE-319 | Authentication Bypass by Capture-replay | High
3 | T1055 | CWE-74 | Improper Neutralization of Data within XPath Expressions | High
4 | T1059 | CWE-88, CWE-94 | Argument Injection | High
5 | T1059.007 | CWE-79, CWE-80 | Basic Cross Site Scripting | High
6 | T1068 | CWE-250, CWE-264, CWE-269, CWE-284 | Execution with Unnecessary Privileges | High
7 | ... | ... | ... | ...

There are 23 more TTP items available. Please use our online service to access the data.

## IOA - Indicator of Attack

These _indicators of attack_ (IOA) list the potential fragments used for technical activities like reconnaissance, exploitation, privilege escalation, and exfiltration by Vice Society. This data is unique as it uses our predictive model for actor profiling.

ID | Type | Indicator | Confidence
-- | ---- | --------- | ----------
1 | File | `.rhosts` | Low
2 | File | `/+CSCOE+/logon.html` | High
3 | File | `/?r=email/api/mark&op=delFromSend` | High
4 | File | `/add-students.php` | High
5 | File | `/addclient1.php` | High
6 | File | `/admin/action/edit_chicken.php` | High
7 | File | `/admin/action/update-deworm.php` | High
8 | File | `/admin/admin-profile.php` | High
9 | File | `/admin/assets/plugins/DataTables/media/unit_testing/templates/dom_data.php` | High
10 | File | `/admin/foreigner-bwdates-reports-details.php` | High
11 | File | `/admin/home.php?con=add` | High
12 | File | `/admin/invoice.php` | High
13 | File | `/admin/maintenance/view_designation.php` | High
14 | File | `/admin/pages/edit_chicken.php` | High
15 | File | `/admin/robot.php` | High
16 | File | `/admin/system.html` | High
17 | File | `/admin/update-clients.php` | High
18 | File | `/ajax.php` | Medium
19 | File | `/api/baskets/{name}` | High
20 | File | `/api/plugin/uninstall` | High
21 | File | `/api2/html/` | Medium
22 | File | `/app/Http/Controllers/ImageController.php` | High
23 | File | `/application/index/controller/File.php` | High
24 | File | `/application/index/controller/Icon.php` | High
25 | File | `/application/index/controller/Screen.php` | High
26 | File | `/application/websocket/controller/Setting.php` | High
27 | File | `/Applications/Utilities/Terminal` | High
28 | File | `/Attachment/fromImageUrl` | High
29 | File | `/b2b-supermarket/shopping-cart` | High
30 | File | `/bin/boa` | Medium
31 | File | `/cgi-bin/cstecgi.cgi` | High
32 | File | `/cgi-bin/cstecgi.cgi?action=login` | High
33 | File | `/cgi-bin/nas_sharing.cgi` | High
34 | File | `/cgi-bin/photocenter_mgr.cgi` | High
35 | File | `/classes/Master.php?f=delete_category` | High
36 | File | `/classes/SystemSettings.php?f=update_settings` | High
37 | File | `/classes/Users.php?f=save` | High
38 | File | `/classes/Users.php?f=save_client` | High
39 | File | `/cms/category/list` | High
40 | File | `/dev/shm` | Medium
41 | File | `/downloadFile.php` | High
42 | File | `/edit.php` | Medium
43 | File | `/edit_book.php` | High
44 | File | `/edoc/doctor/patient.php` | High
45 | File | `/Employer/EditProfile.php` | High
46 | File | `/endpoint/update-tracker.php` | High
47 | File | `/etc/passwd` | Medium
48 | File | `/etc/shadow` | Medium
49 | File | `/Forms/tools_test_1` | High
50 | File | `/forum/away.php` | High
51 | File | `/forum/PostPrivateMessage` | High
52 | File | `/general/search.php?searchtype=simple` | High
53 | File | `/goform/formSetMACFilter` | High
54 | ... | ... | ...

There are 472 more IOA items available (file, library, argument, input value, pattern, network port). Please use our online service to access the data.

## References

The following list contains _external sources_ which discuss the actor and the associated activities:

* https://github.com/prodaft/malware-ioc/tree/b1312c87c1b9de8b519e8416fa819cef04cea004/ViceSociety
* https://github.com/sophoslabs/IoCs/blob/master/2311%20Vice%20Society%20-%20Rhysida%20IoCs.csv
* https://www.cisa.gov/uscert/ncas/alerts/aa22-249a

## Literature

The following _articles_ explain our unique predictive cyber threat intelligence:

* [VulDB Cyber Threat Intelligence Documentation](https://vuldb.com/?kb.cti)
* [Cyber Threat Intelligence - Early Anticipation of Attacks](https://www.scip.ch/en/?labs.20201022)

## License

(c) [1997-2024](https://vuldb.com/?kb.changelog) by [vuldb.com](https://vuldb.com/?kb.about). All data on this page is shared under the license [CC BY-NC-SA 4.0](https://creativecommons.org/licenses/by-nc-sa/4.0/). Questions? Check the [FAQ](https://vuldb.com/?kb.faq), read the [documentation](https://vuldb.com/?kb) or [contact us](https://vuldb.com/?contact)!
