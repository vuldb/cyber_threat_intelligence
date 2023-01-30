# Dealply - Cyber Threat Intelligence

These _indicators_ were reported, collected, and generated during the [VulDB CTI analysis](https://vuldb.com/?kb.cti) of the actor known as [Dealply](https://vuldb.com/?actor.dealply). The _activity monitoring_ correlates data from social media, forums, chat rooms, and darknet markets. It helps to determine associated actors, specific activities, expected intentions, emerging research, and ongoing attacks. Our unique _predictive model_ uses _big data_ to forecast activities and their characteristics.

_Live data_ and more _analysis capabilities_ are available at [https://vuldb.com/?actor.dealply](https://vuldb.com/?actor.dealply)

## Countries

These _countries_ are directly (e.g. origin of attacks) or indirectly (e.g. access by proxy) associated with Dealply:

* [IT](https://vuldb.com/?country.it)

## IOC - Indicator of Compromise

These _indicators of compromise_ (IOC) indicate associated network resources which are known to be part of research and attack activities of Dealply.

ID | IP address | Hostname | Campaign | Confidence
-- | ---------- | -------- | -------- | ----------
1 | [5.9.9.18](https://vuldb.com/?ip.5.9.9.18) | static.18.9.9.5.clients.your-server.de | - | High
2 | [13.248.196.204](https://vuldb.com/?ip.13.248.196.204) | a64c2b794233c60a6.awsglobalaccelerator.com | - | High
3 | [23.0.52.194](https://vuldb.com/?ip.23.0.52.194) | a23-0-52-194.deploy.static.akamaitechnologies.com | - | High
4 | [23.3.126.219](https://vuldb.com/?ip.23.3.126.219) | a23-3-126-219.deploy.static.akamaitechnologies.com | - | High
5 | [23.54.219.51](https://vuldb.com/?ip.23.54.219.51) | a23-54-219-51.deploy.static.akamaitechnologies.com | - | High
6 | [23.221.50.122](https://vuldb.com/?ip.23.221.50.122) | a23-221-50-122.deploy.static.akamaitechnologies.com | - | High
7 | [34.231.131.84](https://vuldb.com/?ip.34.231.131.84) | ec2-34-231-131-84.compute-1.amazonaws.com | - | Medium
8 | ... | ... | ... | ...

There are 29 more IOC items available. Please use our online service to access the data.

## TTP - Tactics, Techniques, Procedures

_Tactics, techniques, and procedures_ (TTP) summarize the suspected MITRE ATT&CK techniques used by _Dealply_. This data is unique as it uses our predictive model for actor profiling.

ID | Technique | Weakness | Description | Confidence
-- | --------- | -------- | ----------- | ----------
1 | T1006 | CWE-21, CWE-22, CWE-35 | Pathname Traversal | High
2 | T1040 | CWE-294, CWE-319 | Authentication Bypass by Capture-replay | High
3 | T1055 | CWE-74 | Injection | High
4 | T1059 | CWE-94, CWE-1321 | Cross Site Scripting | High
5 | T1059.007 | CWE-79, CWE-80 | Cross Site Scripting | High
6 | ... | ... | ... | ...

There are 22 more TTP items available. Please use our online service to access the data.

## IOA - Indicator of Attack

These _indicators of attack_ (IOA) list the potential fragments used for technical activities like reconnaissance, exploitation, privilege escalation, and exfiltration by Dealply. This data is unique as it uses our predictive model for actor profiling.

ID | Type | Indicator | Confidence
-- | ---- | --------- | ----------
1 | File | `/admin/ajax.php?action=delete_transaction` | High
2 | File | `/admin/ajax.php?action=delete_uploads` | High
3 | File | `/admin/ajax.php?action=delete_user` | High
4 | File | `/admin/ajax.php?action=delete_window` | High
5 | File | `/admin/ajax.php?action=save_queue` | High
6 | File | `/admin/ajax.php?action=save_window` | High
7 | File | `/admin/backups/work-dir` | High
8 | File | `/admin/manage_user.php` | High
9 | File | `/api/upload` | Medium
10 | File | `/apply.cgi` | Medium
11 | File | `/bsms_ci/index.php/book` | High
12 | File | `/classes/Master.php?f=delete_brand` | High
13 | File | `/config/api/v1/reboot` | High
14 | File | `/formNewSchedule` | High
15 | File | `/formPasswordAuth` | High
16 | File | `/formPasswordSetup` | High
17 | File | `/formSysLog` | Medium
18 | File | `/formSystemCheck` | High
19 | File | `/formWizardPassword` | High
20 | File | `/forums.php?action=post` | High
21 | File | `/fos/admin/ajax.php?action=login` | High
22 | File | `/fos/admin/index.php?page=menu` | High
23 | File | `/graphql` | Medium
24 | File | `/inxedu/demo_inxedu_open/src/main/resources/mybatis/inxedu/website/WebsiteImagesMapper.xml` | High
25 | File | `/login/index.php` | High
26 | File | `/medicines/profile.php` | High
27 | File | `/opt/Citrix/ICAClient/util/ctxwebhelper` | High
28 | File | `/output/outdbg.c` | High
29 | File | `/output/outieee.c` | High
30 | File | `/queuing/index.php?page=display` | High
31 | File | `/rrdp` | Low
32 | File | `/search.php` | Medium
33 | File | `/setNTP.cgi` | Medium
34 | File | `/subtitles.php` | High
35 | File | `/sys/dict/queryTableData` | High
36 | File | `/tiki-importer.php` | High
37 | File | `/tmp` | Low
38 | File | `/tpts/manage_user.php` | High
39 | File | `/u/username.json` | High
40 | File | `/upload` | Low
41 | File | `/www/include/filesave.php` | High
42 | ... | ... | ...

There are 362 more IOA items available (file, library, argument, input value, pattern, network port). Please use our online service to access the data.

## References

The following list contains _external sources_ which discuss the actor and the associated activities:

* https://blog.talosintelligence.com/2020/01/threat-roundup-0124-0131.html
* https://blog.talosintelligence.com/2020/05/threat-roundup-0522-0529.html
* https://blog.talosintelligence.com/2020/08/threat-roundup-0821-0827.html

## Literature

The following _articles_ explain our unique predictive cyber threat intelligence:

* [VulDB Cyber Threat Intelligence Documentation](https://vuldb.com/?kb.cti)
* [Cyber Threat Intelligence - Early Anticipation of Attacks](https://www.scip.ch/en/?labs.20201022)

## License

(c) [1997-2023](https://vuldb.com/?kb.changelog) by [vuldb.com](https://vuldb.com/?kb.about). All data on this page is shared under the license [CC BY-NC-SA 4.0](https://creativecommons.org/licenses/by-nc-sa/4.0/). Questions? Check the [FAQ](https://vuldb.com/?kb.faq), read the [documentation](https://vuldb.com/?kb) or [contact us](https://vuldb.com/?contact)!
