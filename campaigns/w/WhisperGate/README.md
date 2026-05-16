# WhisperGate - Cyber Threat Intelligence

These _indicators_ were reported, collected, and generated during the [VulDB CTI analysis](https://vuldb.com/?kb.cti) of the campaign known as _WhisperGate_. The _activity monitoring_ correlates data from social media, forums, chat rooms, and darknet markets. It helps to determine associated actors, specific activities, expected intentions, emerging research, and ongoing attacks. Our unique _predictive model_ uses _big data_ to forecast activities and their characteristics.

_Live data_ and more _analysis capabilities_ are available at [https://vuldb.com/?actor](https://vuldb.com/?actor)

## Countries

These _countries_ are directly (e.g. origin of attacks) or indirectly (e.g. access by proxy) associated with WhisperGate:

* [US](https://vuldb.com/?country.us)
* [CH](https://vuldb.com/?country.ch)
* [RU](https://vuldb.com/?country.ru)
* ...

There are 8 more country items available. Please use our online service to access the data.

## Actors

These _actors_ are associated with WhisperGate or other actors linked to the campaign.

ID | Actor | Confidence
-- | ----- | ----------
1 | [GRU Unit 29155](https://vuldb.com/?actor.gru_unit_29155) | High
2 | [WhisperGate](https://vuldb.com/?actor.whispergate) | High

## IOC - Indicator of Compromise

These _indicators of compromise_ (IOC) indicate associated network resources which are known to be part of research and attack activities of WhisperGate.

ID | IP address | Hostname | Actor | Confidence
-- | ---------- | -------- | ----- | ----------
1 | [5.226.139.66](https://vuldb.com/?ip.5.226.139.66) | 66.139.226.5.baremetal.zare.com | [WhisperGate](https://vuldb.com/?actor.whispergate) | High
2 | [45.141.87.11](https://vuldb.com/?ip.45.141.87.11) | - | [WhisperGate](https://vuldb.com/?actor.whispergate) | High
3 | [46.101.242.222](https://vuldb.com/?ip.46.101.242.222) | kukij.com | [WhisperGate](https://vuldb.com/?actor.whispergate) | High
4 | [62.173.140.223](https://vuldb.com/?ip.62.173.140.223) | vserver.tbits.ru | [WhisperGate](https://vuldb.com/?actor.whispergate) | High
5 | [79.124.8.66](https://vuldb.com/?ip.79.124.8.66) | - | [WhisperGate](https://vuldb.com/?actor.whispergate) | High
6 | ... | ... | ... | ...

There are 20 more IOC items available. Please use our online service to access the data.

## TTP - Tactics, Techniques, Procedures

_Tactics, techniques, and procedures_ (TTP) summarize the suspected MITRE ATT&CK techniques used within WhisperGate. This data is unique as it uses our predictive model for actor profiling.

ID | Technique | Weakness | Description | Confidence
-- | --------- | -------- | ----------- | ----------
1 | T1006 | CWE-22, CWE-24, CWE-36 | Path Traversal | High
2 | T1059 | CWE-94, CWE-1321 | Argument Injection | High
3 | T1059.007 | CWE-79, CWE-80 | Basic Cross Site Scripting | High
4 | T1068 | CWE-266, CWE-284 | Execution with Unnecessary Privileges | High
5 | ... | ... | ... | ...

There are 18 more TTP items available. Please use our online service to access the data.

## IOA - Indicator of Attack

These _indicators of attack_ (IOA) list the potential fragments used for technical activities like reconnaissance, exploitation, privilege escalation, and exfiltration during WhisperGate. This data is unique as it uses our predictive model for actor profiling.

ID | Type | Indicator | Confidence
-- | ---- | --------- | ----------
1 | File | `/?explorer/index/zip` | High
2 | File | `/actuator` | Medium
3 | File | `/addProduct.php` | High
4 | File | `/admin/` | Low
5 | File | `/admin/?page=zone` | High
6 | File | `/admin/activity.php` | High
7 | File | `/admin/add-subadmins.php` | High
8 | File | `/Admin/additems.php` | High
9 | File | `/admin/add_area.php` | High
10 | File | `/admin/add_payroll.php` | High
11 | File | `/Admin/changepassword.php` | High
12 | File | `/admin/completed-requests.php` | High
13 | File | `/Admin/delete-fee.php` | High
14 | File | `/admin/delete_activity.php` | High
15 | File | `/admin/delete_user.php` | High
16 | File | `/admin/edit-art-product-detail.php?editid=2` | High
17 | File | `/admin/edit-user.php` | High
18 | File | `/admin/editsite.php` | High
19 | File | `/admin/edit_activity_query.php` | High
20 | File | `/admin/expenses.php` | High
21 | File | `/admin/includes/edit_post.php` | High
22 | File | `/admin/index.php?page=user-profile` | High
23 | File | `/admin/login.php` | High
24 | File | `/admin/login_query.php` | High
25 | File | `/admin/modules/lesson/index.php` | High
26 | File | `/admin/quesadd.php` | High
27 | File | `/admin/system/variableList.do` | High
28 | File | `/admin/system/variableSave.do` | High
29 | File | `/adminapi/system/file/openfile` | High
30 | File | `/administrator/addcategory.php` | High
31 | File | `/Administrator/PHP/AdminAddUser.php` | High
32 | File | `/Administrator/PHP/AdminUpdateUser.php` | High
33 | File | `/Administrator/PHP/AdminViewSongs.php` | High
34 | File | `/admin_delete.php` | High
35 | File | `/ajax.php?action=save_payroll` | High
36 | File | `/ajax.php?Ajax=GetModal_Sensor_Graph` | High
37 | File | `/api/File/downloadFile` | High
38 | File | `/api/jobs` | Medium
39 | File | `/api/sys/login` | High
40 | File | `/app/api/controller/collect.php` | High
41 | File | `/app/checkout/delete.php` | High
42 | File | `/app/checkout/update.php` | High
43 | File | `/app/complaint.php` | High
44 | File | `/app/Jobs/Util/Import.php` | High
45 | File | `/app/register.php?action=reg` | High
46 | File | `/app/sys1.php` | High
47 | File | `/assetsGroupReport/assetsService.j%73p` | High
48 | File | `/base/safe_setting/` | High
49 | File | `/bin/httpd` | Medium
50 | File | `/blog/bContent/save` | High
51 | File | `/boaform/formSysCmd` | High
52 | File | `/boafrm/formDMZ` | High
53 | File | `/boafrm/formTmultiAP` | High
54 | File | `/boafrm/formWsc` | High
55 | File | `/cgi-bin/cstecgi.cgi` | High
56 | File | `/cgi-bin/imode_alldata.php` | High
57 | File | `/cgi-bin/wlogin.cgi` | High
58 | File | `/contact_us.php` | High
59 | File | `/controller/api/hotelList.php` | High
60 | File | `/controller/api/Room.php` | High
61 | File | `/core/preview` | High
62 | File | `/customer_details.php` | High
63 | ... | ... | ...

There are 547 more IOA items available (file, library, argument, input value, pattern, network port). Please use our online service to access the data.

## References

The following list contains _external sources_ which discuss the campaign and the associated activities:

* https://blog.cyble.com/2022/02/01/whispergate-malware-deep-dive-analysis/
* https://blogs.blackberry.com/en/2022/01/threat-thursday-whispergate-wiper
* https://www.cisa.gov/news-events/cybersecurity-advisories/aa24-249a

## Literature

The following _articles_ explain our unique predictive cyber threat intelligence:

* [VulDB Cyber Threat Intelligence Documentation](https://vuldb.com/?kb.cti)
* [Cyber Threat Intelligence - Early Anticipation of Attacks](https://www.scip.ch/en/?labs.20201022)

## License

(c) [1997-2026](https://vuldb.com/?kb.changelog) by [vuldb.com](https://vuldb.com/?kb.about). All data on this page is shared under the license [CC BY-NC-SA 4.0](https://creativecommons.org/licenses/by-nc-sa/4.0/). Questions? Check the [FAQ](https://vuldb.com/?kb.faq), read the [documentation](https://vuldb.com/?kb) or [contact us](https://vuldb.com/?contact)!
