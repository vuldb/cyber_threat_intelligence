# Camerashy - Cyber Threat Intelligence

These _indicators_ were reported, collected, and generated during the [VulDB CTI analysis](https://vuldb.com/?kb.cti) of the campaign known as _Camerashy_. The _activity monitoring_ correlates data from social media, forums, chat rooms, and darknet markets. It helps to determine associated actors, specific activities, expected intentions, emerging research, and ongoing attacks. Our unique _predictive model_ uses _big data_ to forecast activities and their characteristics.

_Live data_ and more _analysis capabilities_ are available at [https://vuldb.com/?actor](https://vuldb.com/?actor)

## Countries

These _countries_ are directly (e.g. origin of attacks) or indirectly (e.g. access by proxy) associated with Camerashy:

* [FR](https://vuldb.com/?country.fr)
* [US](https://vuldb.com/?country.us)

## Actors

These _actors_ are associated with Camerashy or other actors linked to the campaign.

ID | Actor | Confidence
-- | ----- | ----------
1 | [Naikon](https://vuldb.com/?actor.naikon) | High

## IOC - Indicator of Compromise

These _indicators of compromise_ (IOC) indicate associated network resources which are known to be part of research and attack activities of Camerashy.

ID | IP address | Hostname | Actor | Confidence
-- | ---------- | -------- | ----- | ----------
1 | [50.117.115.89](https://vuldb.com/?ip.50.117.115.89) | - | [Naikon](https://vuldb.com/?actor.naikon) | High
2 | [50.117.115.90](https://vuldb.com/?ip.50.117.115.90) | - | [Naikon](https://vuldb.com/?actor.naikon) | High
3 | [65.19.141.203](https://vuldb.com/?ip.65.19.141.203) | shibakov.org | [Naikon](https://vuldb.com/?actor.naikon) | High
4 | ... | ... | ... | ...

There are 9 more IOC items available. Please use our online service to access the data.

## TTP - Tactics, Techniques, Procedures

_Tactics, techniques, and procedures_ (TTP) summarize the suspected MITRE ATT&CK techniques used within Camerashy. This data is unique as it uses our predictive model for actor profiling.

ID | Technique | Weakness | Description | Confidence
-- | --------- | -------- | ----------- | ----------
1 | T1006 | CWE-21, CWE-22, CWE-24, CWE-28 | Pathname Traversal | High
2 | T1055 | CWE-74 | Injection | High
3 | T1059 | CWE-94, CWE-1321 | Cross Site Scripting | High
4 | T1059.007 | CWE-79 | Cross Site Scripting | High
5 | ... | ... | ... | ...

There are 16 more TTP items available. Please use our online service to access the data.

## IOA - Indicator of Attack

These _indicators of attack_ (IOA) list the potential fragments used for technical activities like reconnaissance, exploitation, privilege escalation, and exfiltration during Camerashy. This data is unique as it uses our predictive model for actor profiling.

ID | Type | Indicator | Confidence
-- | ---- | --------- | ----------
1 | File | `.github/workflows/combine-prs.yml` | High
2 | File | `/admin/api/admin/v2_products` | High
3 | File | `/admin/api/theme-edit/` | High
4 | File | `/api/public/signup` | High
5 | File | `/back/index.php/user/User/?1` | High
6 | File | `/cms/category/list` | High
7 | File | `/csms/?page=contact_us` | High
8 | File | `/csms/admin/?page=user/manage_user` | High
9 | File | `/fos/admin/ajax.php?action=login` | High
10 | File | `/fos/admin/index.php?page=menu` | High
11 | File | `/goform/addUserName` | High
12 | File | `/omos/admin/?page=user/list` | High
13 | File | `/picturesPreview` | High
14 | File | `/SkycaijiApp/admin/controller/Mystore.php` | High
15 | File | `/v1/sql-runner` | High
16 | File | `01article.php` | High
17 | File | `AbstractScheduleJob.java` | High
18 | File | `actionpack/lib/action_dispatch/middleware/templates/routes/_table.html.erb` | High
19 | File | `actions/UploadAction.php` | High
20 | File | `add_contestant.php` | High
21 | File | `adm/menu_list_update.php` | High
22 | File | `admin/manage_user.php` | High
23 | File | `admin/page-login.php` | High
24 | File | `admin/panels/entry/admin.entry.list.php` | High
25 | File | `admin/panels/uploader/admin.uploader.php` | High
26 | File | `administrator/components/com_joomgallery/views/config/tmpl/default.php` | High
27 | File | `agent/listener/templates/tail.html` | High
28 | File | `ajax_represent.php` | High
29 | File | `announce.php` | Medium
30 | File | `api.php` | Low
31 | File | `api/src/main/java/org/openmrs/module/appointmentscheduling/AppointmentRequest.java` | High
32 | File | `api/src/main/java/org/openmrs/module/appointmentscheduling/validator/AppointmentTypeValidator.java` | High
33 | File | `app.py` | Low
34 | File | `app/api/songs.py` | High
35 | File | `app/business/impl/ReviewServiceImpl.java` | High
36 | File | `app/config/passport.js` | High
37 | File | `app/controller/insertarSliderAjax.php` | High
38 | File | `app/controllers/code_caller_controller.php` | High
39 | File | `app/controllers/curupira/passwords_controller.rb` | High
40 | File | `app/controllers/geopoll_controller.rb` | High
41 | File | `app/controllers/image_controller.rb` | High
42 | File | `app/controllers/oauth.js` | High
43 | File | `app/controllers/uploaded_files_controller.rb` | High
44 | File | `app/parameters/sipity/parameters/search_criteria_for_works_parameter.rb` | High
45 | File | `application/controllers/Restapi.php` | High
46 | File | `application/controllers/timedtext.php` | High
47 | File | `application/libraries/LanguageTask.php` | High
48 | File | `App\Manage\Controller\ArticleController.class.php` | High
49 | File | `arta/common/middleware.py` | High
50 | File | `auth.inc.php` | Medium
51 | ... | ... | ...

There are 439 more IOA items available (file, library, argument, input value, pattern, network port). Please use our online service to access the data.

## References

The following list contains _external sources_ which discuss the campaign and the associated activities:

* http://cdn2.hubspot.net/hubfs/454298/Project_CAMERASHY_ThreatConnect_Copyright_2015.pdf

## Literature

The following _articles_ explain our unique predictive cyber threat intelligence:

* [VulDB Cyber Threat Intelligence Documentation](https://vuldb.com/?kb.cti)
* [Cyber Threat Intelligence - Early Anticipation of Attacks](https://www.scip.ch/en/?labs.20201022)

## License

(c) [1997-2023](https://vuldb.com/?kb.changelog) by [vuldb.com](https://vuldb.com/?kb.about). All data on this page is shared under the license [CC BY-NC-SA 4.0](https://creativecommons.org/licenses/by-nc-sa/4.0/). Questions? Check the [FAQ](https://vuldb.com/?kb.faq), read the [documentation](https://vuldb.com/?kb) or [contact us](https://vuldb.com/?contact)!
