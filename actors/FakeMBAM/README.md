# FakeMBAM - Cyber Threat Intelligence

These _indicators_ were reported, collected, and generated during the [VulDB CTI analysis](https://vuldb.com/?kb.cti) of the actor known as [FakeMBAM](https://vuldb.com/?actor.fakembam). The _activity monitoring_ correlates data from social media, forums, chat rooms, and darknet markets. It helps to determine associated actors, specific activities, expected intentions, emerging research, and ongoing attacks. Our unique _predictive model_ uses _big data_ to forecast activities and their characteristics.

_Live data_ and more _analysis capabilities_ are available at [https://vuldb.com/?actor.fakembam](https://vuldb.com/?actor.fakembam)

## Countries

These _countries_ are directly (e.g. origin of attacks) or indirectly (e.g. access by proxy) associated with FakeMBAM:

* [NL](https://vuldb.com/?country.nl)
* [US](https://vuldb.com/?country.us)
* [CN](https://vuldb.com/?country.cn)
* ...

There are 5 more country items available. Please use our online service to access the data.

## IOC - Indicator of Compromise

These _indicators of compromise_ (IOC) indicate associated network resources which are known to be part of research and attack activities of FakeMBAM.

ID | IP address | Hostname | Campaign | Confidence
-- | ---------- | -------- | -------- | ----------
1 | [15.236.226.247](https://vuldb.com/?ip.15.236.226.247) | ec2-15-236-226-247.eu-west-3.compute.amazonaws.com | - | Medium
2 | [18.159.45.239](https://vuldb.com/?ip.18.159.45.239) | ec2-18-159-45-239.eu-central-1.compute.amazonaws.com | - | Medium
3 | [18.184.46.95](https://vuldb.com/?ip.18.184.46.95) | ec2-18-184-46-95.eu-central-1.compute.amazonaws.com | - | Medium
4 | [34.254.170.193](https://vuldb.com/?ip.34.254.170.193) | ec2-34-254-170-193.eu-west-1.compute.amazonaws.com | - | Medium
5 | ... | ... | ... | ...

There are 15 more IOC items available. Please use our online service to access the data.

## TTP - Tactics, Techniques, Procedures

_Tactics, techniques, and procedures_ (TTP) summarize the suspected MITRE ATT&CK techniques used by _FakeMBAM_. This data is unique as it uses our predictive model for actor profiling.

ID | Technique | Weakness | Description | Confidence
-- | --------- | -------- | ----------- | ----------
1 | T1006 | CWE-21, CWE-22, CWE-23 | Path Traversal | High
2 | T1040 | CWE-294 | Authentication Bypass by Capture-replay | High
3 | T1055 | CWE-74 | Improper Neutralization of Data within XPath Expressions | High
4 | T1059 | CWE-94 | Argument Injection | High
5 | T1059.007 | CWE-79, CWE-80 | Cross Site Scripting | High
6 | ... | ... | ... | ...

There are 19 more TTP items available. Please use our online service to access the data.

## IOA - Indicator of Attack

These _indicators of attack_ (IOA) list the potential fragments used for technical activities like reconnaissance, exploitation, privilege escalation, and exfiltration by FakeMBAM. This data is unique as it uses our predictive model for actor profiling.

ID | Type | Indicator | Confidence
-- | ---- | --------- | ----------
1 | File | `.travis.yml` | Medium
2 | File | `/admin/conferences/get-all-status/` | High
3 | File | `/admin/conferences/list/` | High
4 | File | `/admin/countrymanagement.php` | High
5 | File | `/admin/general/change-lang` | High
6 | File | `/admin/group/list/` | High
7 | File | `/admin/renewaldue.php` | High
8 | File | `/admin/subnets/ripe-query.php` | High
9 | File | `/admin/usermanagement.php` | High
10 | File | `/api/v1/attack` | High
11 | File | `/api/v1/bait/set` | High
12 | File | `/apply.cgi` | Medium
13 | File | `/backups/` | Medium
14 | File | `/CCMAdmin/serverlist.asp` | High
15 | File | `/cgi-bin/editBookmark` | High
16 | File | `/Config/SaveUploadedHotspotLogoFile` | High
17 | File | `/core/conditions/AbstractWrapper.java` | High
18 | File | `/cwms/admin/?page=articles/view_article/` | High
19 | File | `/debug/pprof` | Medium
20 | File | `/edituser.php` | High
21 | File | `/export` | Low
22 | File | `/file?action=download&file` | High
23 | File | `/forum/away.php` | High
24 | File | `/front/roomtype-details.php` | High
25 | File | `/hardware` | Medium
26 | File | `/horde/imp/search.php` | High
27 | File | `/index.php` | Medium
28 | File | `/librarian/bookdetails.php` | High
29 | File | `/login` | Low
30 | File | `/modules/tasks/gantt.php` | High
31 | File | `/monitoring` | Medium
32 | File | `/one_church/churchprofile.php` | High
33 | File | `/opt/zimbra/jetty/webapps/zimbra/public` | High
34 | File | `/plugin/LiveChat/getChat.json.php` | High
35 | File | `/plugins/servlet/audit/resource` | High
36 | File | `/plugins/servlet/project-config/PROJECT/roles` | High
37 | File | `/replication` | Medium
38 | File | `/RestAPI` | Medium
39 | File | `/sitemagic/index.php` | High
40 | File | `/siteminderagent/pwcgi/smpwservicescgi.exe` | High
41 | ... | ... | ...

There are 350 more IOA items available (file, library, argument, input value, pattern, network port). Please use our online service to access the data.

## References

The following list contains _external sources_ which discuss the actor and the associated activities:

* https://github.com/avast/ioc/tree/master/FakeMBAM

## Literature

The following _articles_ explain our unique predictive cyber threat intelligence:

* [VulDB Cyber Threat Intelligence Documentation](https://vuldb.com/?kb.cti)
* [Cyber Threat Intelligence - Early Anticipation of Attacks](https://www.scip.ch/en/?labs.20201022)

## License

(c) [1997-2024](https://vuldb.com/?kb.changelog) by [vuldb.com](https://vuldb.com/?kb.about). All data on this page is shared under the license [CC BY-NC-SA 4.0](https://creativecommons.org/licenses/by-nc-sa/4.0/). Questions? Check the [FAQ](https://vuldb.com/?kb.faq), read the [documentation](https://vuldb.com/?kb) or [contact us](https://vuldb.com/?contact)!
