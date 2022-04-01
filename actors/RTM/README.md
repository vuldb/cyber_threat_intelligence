# RTM - Cyber Threat Intelligence

These _indicators_ were reported, collected, and generated during the [VulDB CTI analysis](https://vuldb.com/?kb.cti) of the actor known as [RTM](https://vuldb.com/?actor.rtm). The _activity monitoring_ correlates data from social media, forums, chat rooms, and darknet markets. It helps to determine associated actors, specific activities, expected intentions, emerging research, and ongoing attacks. Our unique _predictive model_ uses _big data_ to forecast activities and their characteristics.

_Live data_ and more _analysis capabilities_ are available at [https://vuldb.com/?actor.rtm](https://vuldb.com/?actor.rtm)

## Campaigns

The following _campaigns_ are known and can be associated with RTM:

* Buhtrap/Buran

## Countries

These _countries_ are directly (e.g. origin of attacks) or indirectly (e.g. access by proxy) associated with RTM:

* [NL](https://vuldb.com/?country.nl)
* [US](https://vuldb.com/?country.us)
* [CH](https://vuldb.com/?country.ch)
* ...

There are 5 more country items available. Please use our online service to access the data.

## IOC - Indicator of Compromise

These _indicators of compromise_ (IOC) indicate associated network resources which are known to be part of research and attack activities of RTM.

ID | IP address | Hostname | Campaign | Confidence
-- | ---------- | -------- | -------- | ----------
1 | [5.45.71.239](https://vuldb.com/?ip.5.45.71.239) | parkino.net | Buhtrap/Buran | High
2 | [5.154.190.167](https://vuldb.com/?ip.5.154.190.167) | - | - | High
3 | [5.154.190.168](https://vuldb.com/?ip.5.154.190.168) | - | - | High
4 | [5.154.190.189](https://vuldb.com/?ip.5.154.190.189) | - | - | High
5 | [5.154.191.57](https://vuldb.com/?ip.5.154.191.57) | - | - | High
6 | [5.154.191.154](https://vuldb.com/?ip.5.154.191.154) | - | - | High
7 | [5.154.191.174](https://vuldb.com/?ip.5.154.191.174) | - | - | High
8 | [5.154.191.225](https://vuldb.com/?ip.5.154.191.225) | - | - | High
9 | [37.1.206.78](https://vuldb.com/?ip.37.1.206.78) | - | - | High
10 | ... | ... | ... | ...

There are 36 more IOC items available. Please use our online service to access the data.

## TTP - Tactics, Techniques, Procedures

_Tactics, techniques, and procedures_ (TTP) summarize the suspected MITRE ATT&CK techniques used by _RTM_. This data is unique as it uses our predictive model for actor profiling.

ID | Technique | Weakness | Description | Confidence
-- | --------- | -------- | ----------- | ----------
1 | T1059.007 | CWE-79, CWE-80 | Cross Site Scripting | High
2 | T1068 | CWE-264, CWE-284 | Execution with Unnecessary Privileges | High
3 | T1110.001 | CWE-307, CWE-798 | Improper Restriction of Excessive Authentication Attempts | High
4 | ... | ... | ... | ...

There are 6 more TTP items available. Please use our online service to access the data.

## IOA - Indicator of Attack

These _indicators of attack_ (IOA) list the potential fragments used for technical activities like reconnaissance, exploitation, privilege escalation, and exfiltration by RTM. This data is unique as it uses our predictive model for actor profiling.

ID | Type | Indicator | Confidence
-- | ---- | --------- | ----------
1 | File | `.travis.yml` | Medium
2 | File | `/.env` | Low
3 | File | `/admin.php` | Medium
4 | File | `/admin/config.php?display=disa&view=form` | High
5 | File | `/category_view.php` | High
6 | File | `/dev/kmem` | Medium
7 | File | `/file?action=download&file` | High
8 | File | `/medical/inventories.php` | High
9 | File | `/monitoring` | Medium
10 | File | `/NAGErrors` | Medium
11 | File | `/plugins/servlet/audit/resource` | High
12 | File | `/plugins/servlet/project-config/PROJECT/roles` | High
13 | File | `/PreviewHandler.ashx` | High
14 | File | `/proc/ioports` | High
15 | File | `/replication` | Medium
16 | File | `/RestAPI` | Medium
17 | File | `/rom-0` | Low
18 | File | `/tmp` | Low
19 | File | `/tmp/speedtest_urls.xml` | High
20 | File | `/uncpath/` | Medium
21 | File | `/var/log/nginx` | High
22 | File | `/wp-admin/admin.php` | High
23 | File | `14all.cgi/14all-1.1.cgi/traffic.cgi/mrtg.cgi` | High
24 | File | `abook_database.php` | High
25 | File | `admin-ajax.php?action=get_wdtable order[0][dir]` | High
26 | File | `admin/index.php` | High
27 | File | `admin/login.php` | High
28 | File | `admin\model\catalog\download.php` | High
29 | File | `ajax/render/widget_php` | High
30 | File | `apcupsd.pid` | Medium
31 | File | `api/sms/send-sms` | High
32 | File | `api/v1/alarms` | High
33 | File | `application/controller/InstallerController.php` | High
34 | File | `arch/powerpc/kvm/book3s_rtas.c` | High
35 | File | `arformcontroller.php` | High
36 | File | `auth-gss2.c` | Medium
37 | ... | ... | ...

There are 319 more IOA items available (file, library, argument, input value, pattern, network port). Please use our online service to access the data.

## References

The following list contains _external sources_ which discuss the actor and the associated activities:

* https://www.group-ib.com/blog/rtm
* https://www.welivesecurity.com/2019/04/30/buhtrap-backdoor-ransomware-advertising-platform/
* https://www.welivesecurity.com/wp-content/uploads/2017/02/Read-The-Manual.pdf

## Literature

The following _articles_ explain our unique predictive cyber threat intelligence:

* [VulDB Cyber Threat Intelligence Documentation](https://vuldb.com/?kb.cti)
* [Cyber Threat Intelligence - Early Anticipation of Attacks](https://www.scip.ch/en/?labs.20201022)

## License

(c) [1997-2022](https://vuldb.com/?kb.changelog) by [vuldb.com](https://vuldb.com/?kb.about). All data on this page is shared under the license [CC BY-NC-SA 4.0](https://creativecommons.org/licenses/by-nc-sa/4.0/). Questions? Check the [FAQ](https://vuldb.com/?kb.faq), read the [documentation](https://vuldb.com/?kb) or [contact us](https://vuldb.com/?contact)!
