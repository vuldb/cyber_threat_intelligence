# Black Basta - Cyber Threat Intelligence

These _indicators_ were reported, collected, and generated during the [VulDB CTI analysis](https://vuldb.com/?kb.cti) of the actor known as [Black Basta](https://vuldb.com/?actor.black_basta). The _activity monitoring_ correlates data from social media, forums, chat rooms, and darknet markets. It helps to determine associated actors, specific activities, expected intentions, emerging research, and ongoing attacks. Our unique _predictive model_ uses _big data_ to forecast activities and their characteristics.

_Live data_ and more _analysis capabilities_ are available at [https://vuldb.com/?actor.black_basta](https://vuldb.com/?actor.black_basta)

## Campaigns

The following _campaigns_ are known and can be associated with Black Basta:

* Qbot

## Countries

These _countries_ are directly (e.g. origin of attacks) or indirectly (e.g. access by proxy) associated with Black Basta:

* [US](https://vuldb.com/?country.us)
* [GB](https://vuldb.com/?country.gb)
* [RU](https://vuldb.com/?country.ru)
* ...

There are 31 more country items available. Please use our online service to access the data.

## IOC - Indicator of Compromise

These _indicators of compromise_ (IOC) indicate associated network resources which are known to be part of research and attack activities of Black Basta.

ID | IP address | Hostname | Campaign | Confidence
-- | ---------- | -------- | -------- | ----------
1 | [5.62.43.252](https://vuldb.com/?ip.5.62.43.252) | r-252-43-62-5.consumer-pool.prcdn.net | - | High
2 | [5.196.124.228](https://vuldb.com/?ip.5.196.124.228) | ip228.ip-5-196-124.eu | - | High
3 | [23.106.160.188](https://vuldb.com/?ip.23.106.160.188) | - | - | High
4 | [24.49.232.96](https://vuldb.com/?ip.24.49.232.96) | 24-49-232-96.resi.cgocable.ca | Qbot | High
5 | [24.64.114.59](https://vuldb.com/?ip.24.64.114.59) | S0106b06ebfd79790.cg.shawcable.net | Qbot | High
6 | [24.178.196.44](https://vuldb.com/?ip.24.178.196.44) | 024-178-196-044.biz.spectrum.com | - | High
7 | [37.186.54.185](https://vuldb.com/?ip.37.186.54.185) | - | - | High
8 | [39.44.144.182](https://vuldb.com/?ip.39.44.144.182) | - | - | High
9 | [45.63.1.88](https://vuldb.com/?ip.45.63.1.88) | 45.63.1.88.vultrusercontent.com | - | High
10 | [45.67.229.148](https://vuldb.com/?ip.45.67.229.148) | vm978261.stark-industries.solutions | - | High
11 | [45.87.154.208](https://vuldb.com/?ip.45.87.154.208) | vm1075965.stark-industries.solutions | - | High
12 | [45.133.216.39](https://vuldb.com/?ip.45.133.216.39) | vm627637.stark-industries.solutions | - | High
13 | [45.153.241.167](https://vuldb.com/?ip.45.153.241.167) | - | - | High
14 | [46.176.222.241](https://vuldb.com/?ip.46.176.222.241) | ppp046176222241.access.hol.gr | - | High
15 | [47.23.89.126](https://vuldb.com/?ip.47.23.89.126) | ool-2f17597e.static.optonline.net | - | High
16 | [69.46.15.147](https://vuldb.com/?ip.69.46.15.147) | 69-46-15-147.static.hvvc.us | - | High
17 | ... | ... | ... | ...

There are 66 more IOC items available. Please use our online service to access the data.

## TTP - Tactics, Techniques, Procedures

_Tactics, techniques, and procedures_ (TTP) summarize the suspected MITRE ATT&CK techniques used by _Black Basta_. This data is unique as it uses our predictive model for actor profiling.

ID | Technique | Weakness | Description | Confidence
-- | --------- | -------- | ----------- | ----------
1 | T1006 | CWE-21, CWE-22, CWE-23 | Pathname Traversal | High
2 | T1040 | CWE-294, CWE-319 | Authentication Bypass by Capture-replay | High
3 | T1055 | CWE-74 | Injection | High
4 | T1059 | CWE-88, CWE-94 | Cross Site Scripting | High
5 | T1059.007 | CWE-79, CWE-80 | Cross Site Scripting | High
6 | ... | ... | ... | ...

There are 20 more TTP items available. Please use our online service to access the data.

## IOA - Indicator of Attack

These _indicators of attack_ (IOA) list the potential fragments used for technical activities like reconnaissance, exploitation, privilege escalation, and exfiltration by Black Basta. This data is unique as it uses our predictive model for actor profiling.

ID | Type | Indicator | Confidence
-- | ---- | --------- | ----------
1 | File | `/+CSCOE+/logon.html` | High
2 | File | `/admin/admin.php` | High
3 | File | `/admin/attendance_row.php` | High
4 | File | `/admin/maintenance/view_designation.php` | High
5 | File | `/admin/user/manage_user.php` | High
6 | File | `/api/trackedEntityInstances` | High
7 | File | `/bin/login.php` | High
8 | File | `/cgi-bin/system_mgr.cgi` | High
9 | File | `/cgi/sshcheck.cgi` | High
10 | File | `/common/logViewer/logViewer.jsf` | High
11 | File | `/ConsoleHelp/` | High
12 | File | `/etc/sudoers` | Medium
13 | File | `/export` | Low
14 | File | `/horde/imp/search.php` | High
15 | File | `/index.php` | Medium
16 | File | `/jsoa/hntdCustomDesktopActionContent` | High
17 | File | `/LEPTON_stable_2.2.2/upload/admins/media/index.php` | High
18 | File | `/login` | Low
19 | File | `/messageboard/view.php` | High
20 | File | `/modules/projects/vw_files.php` | High
21 | File | `/opensis/modules/grades/InputFinalGrades.php` | High
22 | File | `/opensis/modules/users/Staff.php` | High
23 | File | `/plesk-site-preview/` | High
24 | File | `/proc/self/environ` | High
25 | File | `/rest/api/2/user/picker` | High
26 | File | `/s/` | Low
27 | File | `/secure/admin/InsightDefaultCustomFieldConfig.jspa` | High
28 | File | `/secure/QueryComponent!Default.jspa` | High
29 | File | `/sendrcpackage?keyid=-2544&keysymbol=-4081` | High
30 | File | `/services` | Medium
31 | File | `/system?action=ServiceAdmin` | High
32 | File | `/var/WEB-GUI/cgi-bin/downloadfile.cgi` | High
33 | File | `/vicidial/user_stats.php` | High
34 | File | `/websocket/exec` | High
35 | File | `access.conf` | Medium
36 | File | `adclick.php` | Medium
37 | File | `addsuppliers.php` | High
38 | File | `admin.php` | Medium
39 | File | `admin.php?m=backup&c=backup&a=doback` | High
40 | File | `admin.remository.php` | High
41 | File | `admin/admin_users.php` | High
42 | File | `admin/login.php` | High
43 | File | `admin/upload.php` | High
44 | File | `administers` | Medium
45 | File | `Administrator_list.php` | High
46 | File | `advancedsetup_websiteblocking.html` | High
47 | File | `affich.php` | Medium
48 | File | `ajax_mail_autoreply.php` | High
49 | File | `ajax_save_name.php` | High
50 | File | `album_portal.php` | High
51 | File | `allocator.cc` | Medium
52 | File | `announcements.php` | High
53 | File | `ap1.com` | Low
54 | File | `apache2/modsecurity.c` | High
55 | File | `api_jsonrpc.php` | High
56 | File | `app/admin/controller/Ajax.php` | High
57 | File | `App/Modules/Admin/Tpl/default/Public/dwz/uploadify/scripts/uploadify.swf` | High
58 | File | `application.php` | High
59 | File | `apply.cgi` | Medium
60 | File | `asp:.jpg` | Medium
61 | File | `authfiles/login.asp` | High
62 | ... | ... | ...

There are 547 more IOA items available (file, library, argument, input value, pattern, network port). Please use our online service to access the data.

## References

The following list contains _external sources_ which discuss the actor and the associated activities:

* https://1275.ru/ioc/311/black-basta-apt-iocs/
* https://get.zerofox.com/rs/143-DHV-007/images/ZeroFox-Intelligence-Update-Black-Basta-Ransomware-Report-2023.pdf
* https://www.cybereason.com/blog/threat-alert-aggressive-qakbot-campaign-and-the-black-basta-ransomware-group-targeting-u.s.-companies
* https://www.trendmicro.com/de_de/research/22/f/black-basta-ransomware-operators-expand-their-attack-arsenal-wit.html

## Literature

The following _articles_ explain our unique predictive cyber threat intelligence:

* [VulDB Cyber Threat Intelligence Documentation](https://vuldb.com/?kb.cti)
* [Cyber Threat Intelligence - Early Anticipation of Attacks](https://www.scip.ch/en/?labs.20201022)

## License

(c) [1997-2023](https://vuldb.com/?kb.changelog) by [vuldb.com](https://vuldb.com/?kb.about). All data on this page is shared under the license [CC BY-NC-SA 4.0](https://creativecommons.org/licenses/by-nc-sa/4.0/). Questions? Check the [FAQ](https://vuldb.com/?kb.faq), read the [documentation](https://vuldb.com/?kb) or [contact us](https://vuldb.com/?contact)!
