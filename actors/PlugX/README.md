# PlugX - Cyber Threat Intelligence

These _indicators_ were reported, collected, and generated during the [VulDB CTI analysis](https://vuldb.com/?kb.cti) of the actor known as [PlugX](https://vuldb.com/?actor.plugx). The _activity monitoring_ correlates data from social media, forums, chat rooms, and darknet markets. It helps to determine associated actors, specific activities, expected intentions, emerging research, and ongoing attacks. Our unique _predictive model_ uses _big data_ to forecast activities and their characteristics.

_Live data_ and more _analysis capabilities_ are available at [https://vuldb.com/?actor.plugx](https://vuldb.com/?actor.plugx)

## Countries

These _countries_ are directly (e.g. origin of attacks) or indirectly (e.g. access by proxy) associated with PlugX:

* [CN](https://vuldb.com/?country.cn)
* [US](https://vuldb.com/?country.us)
* [AU](https://vuldb.com/?country.au)
* ...

There are 11 more country items available. Please use our online service to access the data.

## IOC - Indicator of Compromise

These _indicators of compromise_ (IOC) indicate associated network resources which are known to be part of research and attack activities of PlugX.

ID | IP address | Hostname | Campaign | Confidence
-- | ---------- | -------- | -------- | ----------
1 | [13.213.157.52](https://vuldb.com/?ip.13.213.157.52) | ec2-13-213-157-52.ap-southeast-1.compute.amazonaws.com | - | Medium
2 | [18.138.107.235](https://vuldb.com/?ip.18.138.107.235) | ec2-18-138-107-235.ap-southeast-1.compute.amazonaws.com | - | Medium
3 | [34.92.30.54](https://vuldb.com/?ip.34.92.30.54) | 54.30.92.34.bc.googleusercontent.com | - | Medium
4 | [34.96.224.146](https://vuldb.com/?ip.34.96.224.146) | 146.224.96.34.bc.googleusercontent.com | - | Medium
5 | [35.220.176.90](https://vuldb.com/?ip.35.220.176.90) | 90.176.220.35.bc.googleusercontent.com | - | Medium
6 | [35.220.214.142](https://vuldb.com/?ip.35.220.214.142) | 142.214.220.35.bc.googleusercontent.com | - | Medium
7 | [42.99.117.92](https://vuldb.com/?ip.42.99.117.92) | - | - | High
8 | [42.99.117.95](https://vuldb.com/?ip.42.99.117.95) | - | - | High
9 | [43.254.217.165](https://vuldb.com/?ip.43.254.217.165) | - | - | High
10 | [45.32.125.79](https://vuldb.com/?ip.45.32.125.79) | manages.space | - | High
11 | [45.76.188.118](https://vuldb.com/?ip.45.76.188.118) | - | - | High
12 | [45.77.16.91](https://vuldb.com/?ip.45.77.16.91) | 45.77.16.91.vultrusercontent.com | - | High
13 | [45.142.166.112](https://vuldb.com/?ip.45.142.166.112) | - | - | High
14 | [45.207.50.104](https://vuldb.com/?ip.45.207.50.104) | - | - | High
15 | [45.248.87.140](https://vuldb.com/?ip.45.248.87.140) | - | - | High
16 | ... | ... | ... | ...

There are 61 more IOC items available. Please use our online service to access the data.

## TTP - Tactics, Techniques, Procedures

_Tactics, techniques, and procedures_ (TTP) summarize the suspected MITRE ATT&CK techniques used by _PlugX_. This data is unique as it uses our predictive model for actor profiling.

ID | Technique | Weakness | Description | Confidence
-- | --------- | -------- | ----------- | ----------
1 | T1006 | CWE-21, CWE-22, CWE-23 | Pathname Traversal | High
2 | T1055 | CWE-74 | Injection | High
3 | T1059 | CWE-88, CWE-94 | Cross Site Scripting | High
4 | T1059.007 | CWE-79, CWE-80 | Cross Site Scripting | High
5 | ... | ... | ... | ...

There are 18 more TTP items available. Please use our online service to access the data.

## IOA - Indicator of Attack

These _indicators of attack_ (IOA) list the potential fragments used for technical activities like reconnaissance, exploitation, privilege escalation, and exfiltration by PlugX. This data is unique as it uses our predictive model for actor profiling.

ID | Type | Indicator | Confidence
-- | ---- | --------- | ----------
1 | File | `/+CSCOE+/logon.html` | High
2 | File | `/admin.php?action=themeinstall` | High
3 | File | `/admin/` | Low
4 | File | `/admin/ajax/avatar.php` | High
5 | File | `/admin/uploads.php` | High
6 | File | `/admin/users.php?source=edit_user&id=1` | High
7 | File | `/api/` | Low
8 | File | `/api/trackedEntityInstances` | High
9 | File | `/apply_noauth.cgi` | High
10 | File | `/cgi-bin/portal` | High
11 | File | `/context/%2e/WEB-INF/web.xml` | High
12 | File | `/controller/Index.php` | High
13 | File | `/domains/index.fts` | High
14 | File | `/download` | Medium
15 | File | `/etc/passwd` | Medium
16 | File | `/forum/away.php` | High
17 | File | `/foundry/modules/news/newscolumns.php` | High
18 | File | `/ghost/preview` | High
19 | File | `/GponForm/device_Form?script/` | High
20 | File | `/include/config.cache.php` | High
21 | File | `/index.php/admin/tag/add.html` | High
22 | File | `/jeecg-boot/sys/common/upload` | High
23 | File | `/lan.asp` | Medium
24 | File | `/LDMS/frm_splitfrm.aspx` | High
25 | File | `/modules/profile/index.php` | High
26 | File | `/Mum.Geo.Services/DataAccessService.svc` | High
27 | File | `/NAGErrors` | Medium
28 | File | `/out.php` | Medium
29 | File | `/replication` | Medium
30 | File | `/RestAPI` | Medium
31 | File | `/secure/QueryComponent!Default.jspa` | High
32 | File | `/service/upload` | High
33 | File | `/smstest.html` | High
34 | File | `/start-stop` | Medium
35 | File | `/subscribe/subscribe` | High
36 | File | `/tmp` | Low
37 | File | `/uncpath/` | Medium
38 | File | `/WEB-INF/web.xml` | High
39 | File | `/wp-json/oembed/1.0/embed?url` | High
40 | File | `/_error` | Low
41 | File | `actions/authenticate.php` | High
42 | File | `adclick.php` | Medium
43 | File | `addlyricsform.php` | High
44 | File | `addmerchpicform.php` | High
45 | File | `addresses_export.php` | High
46 | ... | ... | ...

There are 396 more IOA items available (file, library, argument, input value, pattern, network port). Please use our online service to access the data.

## References

The following list contains _external sources_ which discuss the actor and the associated activities:

* https://1275.ru/ioc/146/plugx-malware-iocs/
* https://blogs.mcafee.jp/plugx-a-talisman-to-behold
* https://community.blueliv.com/#!/s/610141e982df417ed032f4e2
* https://twitter.com/0xrb/status/1469184108030955529
* https://twitter.com/0xrb/status/1470678183301181441
* https://twitter.com/0xrb/status/1478253942123347968
* https://twitter.com/0xrb/status/1482976719300890629
* https://twitter.com/0xrb/status/1484467191445475328

## Literature

The following _articles_ explain our unique predictive cyber threat intelligence:

* [VulDB Cyber Threat Intelligence Documentation](https://vuldb.com/?kb.cti)
* [Cyber Threat Intelligence - Early Anticipation of Attacks](https://www.scip.ch/en/?labs.20201022)

## License

(c) [1997-2023](https://vuldb.com/?kb.changelog) by [vuldb.com](https://vuldb.com/?kb.about). All data on this page is shared under the license [CC BY-NC-SA 4.0](https://creativecommons.org/licenses/by-nc-sa/4.0/). Questions? Check the [FAQ](https://vuldb.com/?kb.faq), read the [documentation](https://vuldb.com/?kb) or [contact us](https://vuldb.com/?contact)!
