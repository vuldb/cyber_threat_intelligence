# Naikon - Cyber Threat Intelligence

These _indicators_ were reported, collected, and generated during the [VulDB CTI analysis](https://vuldb.com/?kb.cti) of the actor known as [Naikon](https://vuldb.com/?actor.naikon). The _activity monitoring_ correlates data from social media, forums, chat rooms, and darknet markets. It helps to determine associated actors, specific activities, expected intentions, emerging research, and ongoing attacks. Our unique _predictive model_ uses _big data_ to forecast activities and their characteristics.

_Live data_ and more _analysis capabilities_ are available at [https://vuldb.com/?actor.naikon](https://vuldb.com/?actor.naikon)

## Campaigns

The following _campaigns_ are known and can be associated with Naikon:

* Camerashy

## Countries

These _countries_ are directly (e.g. origin of attacks) or indirectly (e.g. access by proxy) associated with Naikon:

* [FR](https://vuldb.com/?country.fr)
* [US](https://vuldb.com/?country.us)
* [CN](https://vuldb.com/?country.cn)
* ...

There are 1 more country items available. Please use our online service to access the data.

## IOC - Indicator of Compromise

These _indicators of compromise_ (IOC) indicate associated network resources which are known to be part of research and attack activities of Naikon.

ID | IP address | Hostname | Campaign | Confidence
-- | ---------- | -------- | -------- | ----------
1 | [47.241.127.190](https://vuldb.com/?ip.47.241.127.190) | - | - | High
2 | [50.117.115.89](https://vuldb.com/?ip.50.117.115.89) | - | Camerashy | High
3 | [50.117.115.90](https://vuldb.com/?ip.50.117.115.90) | - | Camerashy | High
4 | [65.19.141.203](https://vuldb.com/?ip.65.19.141.203) | shibakov.org | Camerashy | High
5 | ... | ... | ... | ...

There are 17 more IOC items available. Please use our online service to access the data.

## TTP - Tactics, Techniques, Procedures

_Tactics, techniques, and procedures_ (TTP) summarize the suspected MITRE ATT&CK techniques used by _Naikon_. This data is unique as it uses our predictive model for actor profiling.

ID | Technique | Weakness | Description | Confidence
-- | --------- | -------- | ----------- | ----------
1 | T1006 | CWE-21, CWE-22, CWE-24, CWE-28 | Pathname Traversal | High
2 | T1055 | CWE-74 | Injection | High
3 | T1059 | CWE-94, CWE-1321 | Cross Site Scripting | High
4 | T1059.007 | CWE-79 | Cross Site Scripting | High
5 | ... | ... | ... | ...

There are 16 more TTP items available. Please use our online service to access the data.

## IOA - Indicator of Attack

These _indicators of attack_ (IOA) list the potential fragments used for technical activities like reconnaissance, exploitation, privilege escalation, and exfiltration by Naikon. This data is unique as it uses our predictive model for actor profiling.

ID | Type | Indicator | Confidence
-- | ---- | --------- | ----------
1 | File | `.github/workflows/combine-prs.yml` | High
2 | File | `/api/public/signup` | High
3 | File | `/api/v3/flows/instances/default-user-settings-flow/execute/` | High
4 | File | `/back/index.php/user/User/?1` | High
5 | File | `/cgi-bin/editBookmark` | High
6 | File | `/cms/category/list` | High
7 | File | `/csms/?page=contact_us` | High
8 | File | `/csms/admin/?page=user/manage_user` | High
9 | File | `/env` | Low
10 | File | `/fos/admin/ajax.php?action=login` | High
11 | File | `/fos/admin/index.php?page=menu` | High
12 | File | `/goform/addUserName` | High
13 | File | `/new` | Low
14 | File | `/omos/admin/?page=user/list` | High
15 | File | `/picturesPreview` | High
16 | File | `/SkycaijiApp/admin/controller/Mystore.php` | High
17 | File | `/v1/sql-runner` | High
18 | File | `01article.php` | High
19 | File | `AbstractScheduleJob.java` | High
20 | File | `actionpack/lib/action_dispatch/middleware/templates/routes/_table.html.erb` | High
21 | File | `actions/UploadAction.php` | High
22 | File | `add_contestant.php` | High
23 | File | `adm/menu_list_update.php` | High
24 | File | `admin/manage_user.php` | High
25 | File | `admin/page-login.php` | High
26 | File | `admin/panels/entry/admin.entry.list.php` | High
27 | File | `admin/panels/uploader/admin.uploader.php` | High
28 | File | `administrator/components/com_joomgallery/views/config/tmpl/default.php` | High
29 | File | `agent/listener/templates/tail.html` | High
30 | File | `ajax_represent.php` | High
31 | File | `announce.php` | Medium
32 | File | `api.php` | Low
33 | File | `api/src/main/java/org/openmrs/module/appointmentscheduling/AppointmentRequest.java` | High
34 | File | `api/src/main/java/org/openmrs/module/appointmentscheduling/validator/AppointmentTypeValidator.java` | High
35 | File | `app.py` | Low
36 | File | `app/api/songs.py` | High
37 | File | `app/business/impl/ReviewServiceImpl.java` | High
38 | File | `app/config/passport.js` | High
39 | File | `app/controller/insertarSliderAjax.php` | High
40 | File | `app/controllers/code_caller_controller.php` | High
41 | File | `app/controllers/curupira/passwords_controller.rb` | High
42 | File | `app/controllers/geopoll_controller.rb` | High
43 | File | `app/controllers/image_controller.rb` | High
44 | File | `app/controllers/oauth.js` | High
45 | File | `app/controllers/uploaded_files_controller.rb` | High
46 | File | `app/parameters/sipity/parameters/search_criteria_for_works_parameter.rb` | High
47 | File | `application/controllers/Restapi.php` | High
48 | File | `application/controllers/timedtext.php` | High
49 | File | `application/libraries/LanguageTask.php` | High
50 | ... | ... | ...

There are 431 more IOA items available (file, library, argument, input value, pattern, network port). Please use our online service to access the data.

## References

The following list contains _external sources_ which discuss the actor and the associated activities:

* http://cdn2.hubspot.net/hubfs/454298/Project_CAMERASHY_ThreatConnect_Copyright_2015.pdf
* https://1275.ru/ioc/164/lotus-panda-apt-iocs/
* https://research.checkpoint.com/2020/naikon-apt-cyber-espionage-reloaded/
* https://vxug.fakedoma.in/archive/APTs/2021/2021.04.23(1)/NAIKON.pdf
* https://www.threatminer.org/report.php?q=TheNaikonAPT-MsnMM1.pdf&y=2015

## Literature

The following _articles_ explain our unique predictive cyber threat intelligence:

* [VulDB Cyber Threat Intelligence Documentation](https://vuldb.com/?kb.cti)
* [Cyber Threat Intelligence - Early Anticipation of Attacks](https://www.scip.ch/en/?labs.20201022)

## License

(c) [1997-2023](https://vuldb.com/?kb.changelog) by [vuldb.com](https://vuldb.com/?kb.about). All data on this page is shared under the license [CC BY-NC-SA 4.0](https://creativecommons.org/licenses/by-nc-sa/4.0/). Questions? Check the [FAQ](https://vuldb.com/?kb.faq), read the [documentation](https://vuldb.com/?kb) or [contact us](https://vuldb.com/?contact)!
