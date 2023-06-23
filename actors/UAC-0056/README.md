# UAC-0056 - Cyber Threat Intelligence

These _indicators_ were reported, collected, and generated during the [VulDB CTI analysis](https://vuldb.com/?kb.cti) of the actor known as [UAC-0056](https://vuldb.com/?actor.uac-0056). The _activity monitoring_ correlates data from social media, forums, chat rooms, and darknet markets. It helps to determine associated actors, specific activities, expected intentions, emerging research, and ongoing attacks. Our unique _predictive model_ uses _big data_ to forecast activities and their characteristics.

_Live data_ and more _analysis capabilities_ are available at [https://vuldb.com/?actor.uac-0056](https://vuldb.com/?actor.uac-0056)

## Campaigns

The following _campaigns_ are known and can be associated with UAC-0056:

* Cobalt Strike
* Graphiron
* GraphSteel/GrimPlant
* ...

There are 1 more campaign items available. Please use our online service to access the data.

## Countries

These _countries_ are directly (e.g. origin of attacks) or indirectly (e.g. access by proxy) associated with UAC-0056:

* [US](https://vuldb.com/?country.us)
* [RU](https://vuldb.com/?country.ru)
* [TR](https://vuldb.com/?country.tr)
* ...

There are 17 more country items available. Please use our online service to access the data.

## IOC - Indicator of Compromise

These _indicators of compromise_ (IOC) indicate associated network resources which are known to be part of research and attack activities of UAC-0056.

ID | IP address | Hostname | Campaign | Confidence
-- | ---------- | -------- | -------- | ----------
1 | [31.42.185.63](https://vuldb.com/?ip.31.42.185.63) | dedicated.vsys.host | Ukraine | High
2 | [45.84.0.116](https://vuldb.com/?ip.45.84.0.116) | n5336.md | - | High
3 | [45.146.164.37](https://vuldb.com/?ip.45.146.164.37) | - | Ukraine | High
4 | ... | ... | ... | ...

There are 12 more IOC items available. Please use our online service to access the data.

## TTP - Tactics, Techniques, Procedures

_Tactics, techniques, and procedures_ (TTP) summarize the suspected MITRE ATT&CK techniques used by _UAC-0056_. This data is unique as it uses our predictive model for actor profiling.

ID | Technique | Weakness | Description | Confidence
-- | --------- | -------- | ----------- | ----------
1 | T1006 | CWE-21, CWE-22, CWE-23, CWE-425 | Pathname Traversal | High
2 | T1040 | CWE-294, CWE-319 | Authentication Bypass by Capture-replay | High
3 | T1055 | CWE-74 | Injection | High
4 | T1059 | CWE-94 | Cross Site Scripting | High
5 | T1059.007 | CWE-79, CWE-80 | Cross Site Scripting | High
6 | ... | ... | ... | ...

There are 18 more TTP items available. Please use our online service to access the data.

## IOA - Indicator of Attack

These _indicators of attack_ (IOA) list the potential fragments used for technical activities like reconnaissance, exploitation, privilege escalation, and exfiltration by UAC-0056. This data is unique as it uses our predictive model for actor profiling.

ID | Type | Indicator | Confidence
-- | ---- | --------- | ----------
1 | File | `/admin.php` | Medium
2 | File | `/admin/?page=system_info/contact_info` | High
3 | File | `/admin/doctors/view_doctor.php` | High
4 | File | `/admin/edit_user.php` | High
5 | File | `/admin/products/controller.php?action=add` | High
6 | File | `/admin/question/edit` | High
7 | File | `/admin/students/manage.php` | High
8 | File | `/adminlogin.asp` | High
9 | File | `/api/` | Low
10 | File | `/app/controller/Books.php` | High
11 | File | `/auth/register` | High
12 | File | `/bifs/field_decode.c` | High
13 | File | `/bin/proc.cgi` | High
14 | File | `/cgi/get_param.cgi` | High
15 | File | `/common/download_agent_installer.php` | High
16 | File | `/common/run_cross_report.php` | High
17 | File | `/Core/Ap4File.cpp` | High
18 | File | `/csms/?page=contact_us` | High
19 | File | `/debug/pprof` | Medium
20 | File | `/dev/audio` | Medium
21 | File | `/DS/LM_API/api/SelectionService/InsertQueryWithActiveRelationsReturnId` | High
22 | File | `/DXR.axd` | Medium
23 | File | `/etc/crash` | Medium
24 | File | `/etc/master.passwd` | High
25 | File | `/etc/passwd` | Medium
26 | File | `/etc/shadow` | Medium
27 | File | `/EXCU_SHELL` | Medium
28 | File | `/forum/away.php` | High
29 | File | `/goform/addressNat` | High
30 | File | `/goform/AddSysLogRule` | High
31 | File | `/goform/aspForm` | High
32 | File | `/goform/NatStaticSetting` | High
33 | File | `/goform/WifiBasicSet` | High
34 | File | `/hocms/classes/Master.php?f=delete_collection` | High
35 | File | `/index.php` | Medium
36 | File | `/index.php?module=configuration/application` | High
37 | File | `/index.php?route=extension/module/so_filter_shop_by/filter_data` | High
38 | File | `/isomedia/box_funcs.c` | High
39 | File | `/isomedia/meta.c` | High
40 | File | `/kruxton/receipt.php` | High
41 | File | `/opt/zimbra/jetty/webapps/zimbra/public` | High
42 | File | `/pages/animals.php` | High
43 | File | `/pages/apply_vacancy.php` | High
44 | File | `/php-sms/admin/?page=services/manage_service` | High
45 | File | `/php_action/editProductImage.php` | High
46 | File | `/plesk-site-preview/` | High
47 | File | `/project/PROJECTNAME/reports/` | High
48 | File | `/sacco_shield/manage_loan.php` | High
49 | File | `/scene_manager/scene_dump.c` | High
50 | ... | ... | ...

There are 431 more IOA items available (file, library, argument, input value, pattern, network port). Please use our online service to access the data.

## References

The following list contains _external sources_ which discuss the actor and the associated activities:

* https://1275.ru/ioc/533/unc2589-iocs/
* https://blog.malwarebytes.com/threat-intelligence/2022/07/cobalt-strikes-again-uac-0056-continues-to-target-ukraine-in-its-latest-campaign/
* https://cert.gov.ua/article/18419
* https://cert.gov.ua/article/37704
* https://cert.gov.ua/article/38374
* https://cert.gov.ua/article/39882
* https://community.blueliv.com/#!/s/624be71d82df413eb235593a
* https://symantec-enterprise-blogs.security.com/blogs/threat-intelligence/nodaria-ukraine-infostealer
* https://unit42.paloaltonetworks.com/ukraine-targeted-outsteel-saintbot/
* https://www.sentinelone.com/blog/threat-actor-uac-0056-targeting-ukraine-with-fake-translation-software/

## Literature

The following _articles_ explain our unique predictive cyber threat intelligence:

* [VulDB Cyber Threat Intelligence Documentation](https://vuldb.com/?kb.cti)
* [Cyber Threat Intelligence - Early Anticipation of Attacks](https://www.scip.ch/en/?labs.20201022)

## License

(c) [1997-2023](https://vuldb.com/?kb.changelog) by [vuldb.com](https://vuldb.com/?kb.about). All data on this page is shared under the license [CC BY-NC-SA 4.0](https://creativecommons.org/licenses/by-nc-sa/4.0/). Questions? Check the [FAQ](https://vuldb.com/?kb.faq), read the [documentation](https://vuldb.com/?kb) or [contact us](https://vuldb.com/?contact)!
