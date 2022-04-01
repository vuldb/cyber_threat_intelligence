# Gandcrab - Cyber Threat Intelligence

These _indicators_ were reported, collected, and generated during the [VulDB CTI analysis](https://vuldb.com/?kb.cti) of the actor known as [Gandcrab](https://vuldb.com/?actor.gandcrab). The _activity monitoring_ correlates data from social media, forums, chat rooms, and darknet markets. It helps to determine associated actors, specific activities, expected intentions, emerging research, and ongoing attacks. Our unique _predictive model_ uses _big data_ to forecast activities and their characteristics.

_Live data_ and more _analysis capabilities_ are available at [https://vuldb.com/?actor.gandcrab](https://vuldb.com/?actor.gandcrab)

## Countries

These _countries_ are directly (e.g. origin of attacks) or indirectly (e.g. access by proxy) associated with Gandcrab:

* [US](https://vuldb.com/?country.us)
* [ES](https://vuldb.com/?country.es)
* [FR](https://vuldb.com/?country.fr)
* ...

There are 7 more country items available. Please use our online service to access the data.

## IOC - Indicator of Compromise

These _indicators of compromise_ (IOC) indicate associated network resources which are known to be part of research and attack activities of Gandcrab.

ID | IP address | Hostname | Campaign | Confidence
-- | ---------- | -------- | -------- | ----------
1 | [3.64.163.50](https://vuldb.com/?ip.3.64.163.50) | ec2-3-64-163-50.eu-central-1.compute.amazonaws.com | - | Medium
2 | [5.39.221.60](https://vuldb.com/?ip.5.39.221.60) | - | - | High
3 | [5.135.183.146](https://vuldb.com/?ip.5.135.183.146) | freya.stelas.de | - | High
4 | [13.76.158.123](https://vuldb.com/?ip.13.76.158.123) | - | - | High
5 | [20.50.64.11](https://vuldb.com/?ip.20.50.64.11) | - | - | High
6 | [34.102.136.180](https://vuldb.com/?ip.34.102.136.180) | 180.136.102.34.bc.googleusercontent.com | - | Medium
7 | [35.205.61.67](https://vuldb.com/?ip.35.205.61.67) | 67.61.205.35.bc.googleusercontent.com | - | Medium
8 | [39.107.34.197](https://vuldb.com/?ip.39.107.34.197) | - | - | High
9 | [45.118.145.96](https://vuldb.com/?ip.45.118.145.96) | - | - | High
10 | [51.254.25.115](https://vuldb.com/?ip.51.254.25.115) | ip115.ip-51-254-25.eu | - | High
11 | ... | ... | ... | ...

There are 40 more IOC items available. Please use our online service to access the data.

## TTP - Tactics, Techniques, Procedures

_Tactics, techniques, and procedures_ (TTP) summarize the suspected MITRE ATT&CK techniques used by _Gandcrab_. This data is unique as it uses our predictive model for actor profiling.

ID | Technique | Weakness | Description | Confidence
-- | --------- | -------- | ----------- | ----------
1 | T1040 | CWE-294 | Authentication Bypass by Capture-replay | High
2 | T1059.007 | CWE-79, CWE-80 | Cross Site Scripting | High
3 | T1068 | CWE-250, CWE-264, CWE-266, CWE-284 | Execution with Unnecessary Privileges | High
4 | ... | ... | ... | ...

There are 9 more TTP items available. Please use our online service to access the data.

## IOA - Indicator of Attack

These _indicators of attack_ (IOA) list the potential fragments used for technical activities like reconnaissance, exploitation, privilege escalation, and exfiltration by Gandcrab. This data is unique as it uses our predictive model for actor profiling.

ID | Type | Indicator | Confidence
-- | ---- | --------- | ----------
1 | File | `%PROGRAMDATA%\checkmk\agent\local` | High
2 | File | `/admin/comment.php` | High
3 | File | `/admin/doctors/manage_doctor.php` | High
4 | File | `/admin/news/sort_ok.php` | High
5 | File | `/api/version` | Medium
6 | File | `/app1/admin#foo` | High
7 | File | `/appsuite` | Medium
8 | File | `/article/add` | Medium
9 | File | `/config/service/host.go` | High
10 | File | `/Controller/ChinaCityController.class.php` | High
11 | File | `/coreframe/app/guestbook/myissue.php` | High
12 | File | `/cwms/classes/Master.php?f=save_contact` | High
13 | File | `/goform/setAdInfoDetail` | High
14 | File | `/goform/SetPptpServerCfg` | High
15 | File | `/hub/api/user` | High
16 | File | `/ics?tool=search` | High
17 | File | `/info.xml` | Medium
18 | File | `/it-IT/splunkd/__raw/services/get_snapshot` | High
19 | File | `/js/js-parser.c` | High
20 | File | `/knowage/restful-services/documentnotes/saveNote` | High
21 | File | `/netact/sct` | Medium
22 | File | `/nova/bin/bfd` | High
23 | File | `/php/passport/index.php` | High
24 | File | `/run/courier/authdaemon` | High
25 | File | `/run/spice-vdagentd/spice-vdagent-sock` | High
26 | File | `/settings/profile` | High
27 | File | `/thruk/#cgi-bin/status.cgi?style=combined` | High
28 | File | `/usr/local/bin/mjs` | High
29 | File | `Access/DownloadFeed_Mnt/FileUpload_Upd.cfm` | High
30 | File | `action.setdefaulttemplate.php` | High
31 | File | `ActiveServices.java` | High
32 | File | `Addons/file/mod.file.php` | High
33 | ... | ... | ...

There are 277 more IOA items available (file, library, argument, input value, pattern, network port). Please use our online service to access the data.

## References

The following list contains _external sources_ which discuss the actor and the associated activities:

* https://blog.talosintelligence.com/2020/09/threat-roundup-0904-0911.html
* https://blog.talosintelligence.com/2021/10/threat-roundup-1001-1008.html
* https://blog.talosintelligence.com/2021/10/threat-roundup-1015-1022.html
* https://community.blueliv.com/#!/s/5afd59bd82df413e376682f2
* https://precisionsec.com/threat-intelligence-feeds/gandcrab/

## Literature

The following _articles_ explain our unique predictive cyber threat intelligence:

* [VulDB Cyber Threat Intelligence Documentation](https://vuldb.com/?kb.cti)
* [Cyber Threat Intelligence - Early Anticipation of Attacks](https://www.scip.ch/en/?labs.20201022)

## License

(c) [1997-2022](https://vuldb.com/?kb.changelog) by [vuldb.com](https://vuldb.com/?kb.about). All data on this page is shared under the license [CC BY-NC-SA 4.0](https://creativecommons.org/licenses/by-nc-sa/4.0/). Questions? Check the [FAQ](https://vuldb.com/?kb.faq), read the [documentation](https://vuldb.com/?kb) or [contact us](https://vuldb.com/?contact)!
