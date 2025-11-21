# Taiwanese Organizations - Cyber Threat Intelligence

These _indicators_ were reported, collected, and generated during the [VulDB CTI analysis](https://vuldb.com/?kb.cti) of the campaign known as _Taiwanese Organizations_. The _activity monitoring_ correlates data from social media, forums, chat rooms, and darknet markets. It helps to determine associated actors, specific activities, expected intentions, emerging research, and ongoing attacks. Our unique _predictive model_ uses _big data_ to forecast activities and their characteristics.

_Live data_ and more _analysis capabilities_ are available at [https://vuldb.com/?actor](https://vuldb.com/?actor)

## Countries

These _countries_ are directly (e.g. origin of attacks) or indirectly (e.g. access by proxy) associated with Taiwanese Organizations:

* [CN](https://vuldb.com/?country.cn)
* [US](https://vuldb.com/?country.us)

## Actors

These _actors_ are associated with Taiwanese Organizations or other actors linked to the campaign.

ID | Actor | Confidence
-- | ----- | ----------
1 | [Flax Typhoon](https://vuldb.com/?actor.flax_typhoon) | High
2 | [Winos](https://vuldb.com/?actor.winos) | High
3 | [UNK_DropPitch](https://vuldb.com/?actor.unk_droppitch) | High

## IOC - Indicator of Compromise

These _indicators of compromise_ (IOC) indicate associated network resources which are known to be part of research and attack activities of Taiwanese Organizations.

ID | IP address | Hostname | Actor | Confidence
-- | ---------- | -------- | ----- | ----------
1 | [39.98.208.61](https://vuldb.com/?ip.39.98.208.61) | - | [Flax Typhoon](https://vuldb.com/?actor.flax_typhoon) | High
2 | [45.88.192.118](https://vuldb.com/?ip.45.88.192.118) | Host-By.DMIT.com | [Flax Typhoon](https://vuldb.com/?actor.flax_typhoon) | High
3 | [45.141.139.222](https://vuldb.com/?ip.45.141.139.222) | - | [UNK_DropPitch](https://vuldb.com/?actor.unk_droppitch) | High
4 | [45.195.149.224](https://vuldb.com/?ip.45.195.149.224) | - | [Flax Typhoon](https://vuldb.com/?actor.flax_typhoon) | High
5 | [45.204.1.247](https://vuldb.com/?ip.45.204.1.247) | - | [Flax Typhoon](https://vuldb.com/?actor.flax_typhoon) | High
6 | [45.204.1.248](https://vuldb.com/?ip.45.204.1.248) | - | [Flax Typhoon](https://vuldb.com/?actor.flax_typhoon) | High
7 | ... | ... | ... | ...

There are 24 more IOC items available. Please use our online service to access the data.

## TTP - Tactics, Techniques, Procedures

_Tactics, techniques, and procedures_ (TTP) summarize the suspected MITRE ATT&CK techniques used within Taiwanese Organizations. This data is unique as it uses our predictive model for actor profiling.

ID | Technique | Weakness | Description | Confidence
-- | --------- | -------- | ----------- | ----------
1 | T1006 | CWE-22, CWE-24 | Path Traversal | High
2 | T1055 | CWE-74 | Improper Neutralization of Data within XPath Expressions | High
3 | T1059 | CWE-94 | Argument Injection | High
4 | T1059.007 | CWE-79 | Basic Cross Site Scripting | High
5 | T1068 | CWE-264, CWE-266, CWE-269, CWE-284 | Execution with Unnecessary Privileges | High
6 | ... | ... | ... | ...

There are 20 more TTP items available. Please use our online service to access the data.

## IOA - Indicator of Attack

These _indicators of attack_ (IOA) list the potential fragments used for technical activities like reconnaissance, exploitation, privilege escalation, and exfiltration during Taiwanese Organizations. This data is unique as it uses our predictive model for actor profiling.

ID | Type | Indicator | Confidence
-- | ---- | --------- | ----------
1 | File | `/adfs/ls` | Medium
2 | File | `/admin-api/bpm/model/deploy` | High
3 | File | `/admin.php?m=Acquisi&a=testcj&lid=1` | High
4 | File | `/admin.php?p=/Area/index#tab=t2` | High
5 | File | `/admin/aboutPost.php` | High
6 | File | `/admin/article/list` | High
7 | File | `/admin/change-password.php` | High
8 | File | `/admin/group/edit.do` | High
9 | File | `/admin/ImgUpdaPost.php` | High
10 | File | `/admin/index2.html` | High
11 | File | `/admin/member_save.php` | High
12 | File | `/admin/settings/index.php?page=accounts` | High
13 | File | `/admin/template_admin.php` | High
14 | File | `/admin/upload.php` | High
15 | File | `/admin/user/edit.do` | High
16 | File | `/adminprofile.php` | High
17 | File | `/admin_ping.htm` | High
18 | File | `/adv_arpspoofing.php` | High
19 | File | `/adv_dhcps.php` | High
20 | File | `/adv_macbypass.php` | High
21 | File | `/allreaders.html` | High
22 | File | `/all_student.php` | High
23 | File | `/analysisProject/pagingQueryData` | High
24 | File | `/animalsupdate.php` | High
25 | File | `/Ant_Suxin.php` | High
26 | File | `/api/authentication/login` | High
27 | File | `/api/Common/uploadFile` | High
28 | File | `/api/stl/actions/search` | High
29 | File | `/api/system/other` | High
30 | File | `/Api/TinyMce/UploadAjaxAPI.ashx` | High
31 | File | `/api/upload.php` | High
32 | File | `/api/v1/admin/` | High
33 | File | `/api/v1/getbaseconfig` | High
34 | File | `/api/v1/settings` | High
35 | File | `/api/wizard/getCapability` | High
36 | File | `/api/wizard/getCapabilityWeb` | High
37 | File | `/api/wizard/getLanguage` | High
38 | File | `/api/wizard/getSpecs` | High
39 | File | `/api/wizard/getsyncpppoecfg` | High
40 | File | `/api/wizard/setLanguage` | High
41 | File | `/api/wizard/setsyncpppoecfg` | High
42 | File | `/app/admin/controller/api/Plugs.php` | High
43 | File | `/app/controller/Api.php` | High
44 | File | `/application/models/ApplicationDataObject.class.php` | High
45 | File | `/auth.asp` | Medium
46 | File | `/bin/gpio` | Medium
47 | File | `/bin/httpd` | Medium
48 | File | `/boa/formWSC` | Medium
49 | File | `/boafrm/formDMZ` | High
50 | File | `/boafrm/formDosCfg` | High
51 | File | `/boafrm/formFilter` | High
52 | File | `/boafrm/formIpQoS` | High
53 | File | `/boafrm/formMapDel` | High
54 | File | `/boafrm/formMapDelDevice` | High
55 | File | `/boafrm/formMultiAP` | High
56 | File | `/boafrm/formNtp` | High
57 | File | `/boafrm/formPortFw` | High
58 | File | `/boafrm/formReflashClientTbl` | High
59 | File | `/boafrm/formSaveConfig` | High
60 | File | `/boafrm/formSetLg` | High
61 | File | `/boafrm/formSiteSurveyProfile` | High
62 | File | `/boafrm/formStaticDHCP` | High
63 | File | `/boafrm/formStats` | High
64 | File | `/boafrm/formSysCmd` | High
65 | File | `/boafrm/formSysLog` | High
66 | File | `/boafrm/formVlan` | High
67 | File | `/boafrm/formWdsEncrypt` | High
68 | File | `/boafrm/formWirelessTbl` | High
69 | ... | ... | ...

There are 605 more IOA items available (file, library, argument, input value, pattern, network port). Please use our online service to access the data.

## References

The following list contains _external sources_ which discuss the campaign and the associated activities:

* https://www.fortinet.com/blog/threat-research/threat-group-targets-companies-in-taiwan
* https://www.microsoft.com/en-us/security/blog/2023/08/24/flax-typhoon-using-legitimate-software-to-quietly-access-taiwanese-organizations/
* https://www.proofpoint.com/us/blog/threat-insight/phish-china-aligned-espionage-actors-ramp-up-taiwan-semiconductor-targeting

## Literature

The following _articles_ explain our unique predictive cyber threat intelligence:

* [VulDB Cyber Threat Intelligence Documentation](https://vuldb.com/?kb.cti)
* [Cyber Threat Intelligence - Early Anticipation of Attacks](https://www.scip.ch/en/?labs.20201022)

## License

(c) [1997-2025](https://vuldb.com/?kb.changelog) by [vuldb.com](https://vuldb.com/?kb.about). All data on this page is shared under the license [CC BY-NC-SA 4.0](https://creativecommons.org/licenses/by-nc-sa/4.0/). Questions? Check the [FAQ](https://vuldb.com/?kb.faq), read the [documentation](https://vuldb.com/?kb) or [contact us](https://vuldb.com/?contact)!
