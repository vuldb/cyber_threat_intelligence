# REvil - Cyber Threat Intelligence

These _indicators_ were reported, collected, and generated during the [VulDB CTI analysis](https://vuldb.com/?kb.cti) of the actor known as [REvil](https://vuldb.com/?actor.revil). The _activity monitoring_ correlates data from social media, forums, chat rooms, and darknet markets. It helps to determine associated actors, specific activities, expected intentions, emerging research, and ongoing attacks. Our unique _predictive model_ uses _big data_ to forecast activities and their characteristics.

_Live data_ and more _analysis capabilities_ are available at [https://vuldb.com/?actor.revil](https://vuldb.com/?actor.revil)

## Campaigns

The following _campaigns_ are known and can be associated with REvil:

* CVE-2019-2725

## Countries

These _countries_ are directly (e.g. origin of attacks) or indirectly (e.g. access by proxy) associated with REvil:

* [US](https://vuldb.com/?country.us)
* [RU](https://vuldb.com/?country.ru)
* [CN](https://vuldb.com/?country.cn)
* ...

There are 13 more country items available. Please use our online service to access the data.

## IOC - Indicator of Compromise

These _indicators of compromise_ (IOC) indicate associated network resources which are known to be part of research and attack activities of REvil.

ID | IP address | Hostname | Campaign | Confidence
-- | ---------- | -------- | -------- | ----------
1 | [5.230.195.226](https://vuldb.com/?ip.5.230.195.226) | - | - | High
2 | [18.223.199.234](https://vuldb.com/?ip.18.223.199.234) | ec2-18-223-199-234.us-east-2.compute.amazonaws.com | - | Medium
3 | [45.9.148.108](https://vuldb.com/?ip.45.9.148.108) | mx1.dendrite.network | - | High
4 | [45.33.2.79](https://vuldb.com/?ip.45.33.2.79) | li956-79.members.linode.com | - | High
5 | [45.33.18.44](https://vuldb.com/?ip.45.33.18.44) | li972-44.members.linode.com | - | High
6 | [45.33.20.235](https://vuldb.com/?ip.45.33.20.235) | li974-235.members.linode.com | - | High
7 | [45.33.23.183](https://vuldb.com/?ip.45.33.23.183) | li977-183.members.linode.com | - | High
8 | [45.33.30.197](https://vuldb.com/?ip.45.33.30.197) | li1047-197.members.linode.com | - | High
9 | [45.55.211.79](https://vuldb.com/?ip.45.55.211.79) | - | CVE-2019-2725 | High
10 | [45.56.79.23](https://vuldb.com/?ip.45.56.79.23) | li929-23.members.linode.com | - | High
11 | ... | ... | ... | ...

There are 41 more IOC items available. Please use our online service to access the data.

## TTP - Tactics, Techniques, Procedures

_Tactics, techniques, and procedures_ (TTP) summarize the suspected MITRE ATT&CK techniques used by _REvil_. This data is unique as it uses our predictive model for actor profiling.

ID | Technique | Weakness | Description | Confidence
-- | --------- | -------- | ----------- | ----------
1 | T1006 | CWE-22, CWE-24, CWE-28, CWE-425 | Path Traversal | High
2 | T1055 | CWE-74 | Improper Neutralization of Data within XPath Expressions | High
3 | T1059 | CWE-88, CWE-94 | Argument Injection | High
4 | T1059.007 | CWE-79, CWE-80 | Basic Cross Site Scripting | High
5 | T1068 | CWE-264, CWE-269, CWE-284 | Execution with Unnecessary Privileges | High
6 | ... | ... | ... | ...

There are 19 more TTP items available. Please use our online service to access the data.

## IOA - Indicator of Attack

These _indicators of attack_ (IOA) list the potential fragments used for technical activities like reconnaissance, exploitation, privilege escalation, and exfiltration by REvil. This data is unique as it uses our predictive model for actor profiling.

ID | Type | Indicator | Confidence
-- | ---- | --------- | ----------
1 | File | `/.htpasswd` | Medium
2 | File | `/academy/tutor/filter` | High
3 | File | `/ad-list` | Medium
4 | File | `/admin/ajax.php?action=save_settings` | High
5 | File | `/admin/case-type` | High
6 | File | `/admin/manage_complaint.php` | High
7 | File | `/admin/suppliers/view_details.php` | High
8 | File | `/ajax.php?action=read_msg` | High
9 | File | `/api/authentication/login` | High
10 | File | `/api/jolokia org.jolokia.http.HttpRequestHandler#handlePostRequest` | High
11 | File | `/api/sys/login` | High
12 | File | `/api/sys/ng-alain/getDictItemsByTable/` | High
13 | File | `/api/sys/set_passwd` | High
14 | File | `/api/v2/open/rowsInfo` | High
15 | File | `/app/sys1.php` | High
16 | File | `/assets/something/services/AppModule.class` | High
17 | File | `/building/backmgr/urlpage/mobileurl/configfile/jx2_config.ini` | High
18 | File | `/cas/logout` | Medium
19 | File | `/catalog/all-products` | High
20 | File | `/category_view.php` | High
21 | File | `/cgi-bin/adm.cgi` | High
22 | File | `/cgi-bin/mesh.cgi?page=upgrade` | High
23 | File | `/cgi-bin/nasset.cgi` | High
24 | File | `/cgi-bin/nas_sharing.cgi` | High
25 | File | `/cgi-bin/nightled.cgi` | High
26 | File | `/cgi-bin/touchlist_sync.cgi` | High
27 | File | `/cgi-bin/vitogate.cgi` | High
28 | File | `/cgi-bin/webadminget.cgi` | High
29 | File | `/classes/Master.php` | High
30 | File | `/classes/Users.php?f=save` | High
31 | File | `/cms/process.php` | High
32 | File | `/debug/pprof` | Medium
33 | File | `/desktop_app/file.ajax.php?action=uploadfile` | High
34 | File | `/downloadFile.php` | High
35 | File | `/DXR.axd` | Medium
36 | File | `/emap/devicePoint_addImgIco?hasSubsystem=true` | High
37 | File | `/env` | Low
38 | File | `/etc/shadow` | Medium
39 | File | `/find-a-match` | High
40 | File | `/forum/away.php` | High
41 | File | `/friends` | Medium
42 | File | `/friends/ajax_invite` | High
43 | File | `/goform/SetNetControlList` | High
44 | File | `/goform/SetStaticRouteCfg` | High
45 | File | `/HNAP1` | Low
46 | File | `/HNAP1/` | Low
47 | File | `/hrm/controller/employee.php` | High
48 | ... | ... | ...

There are 419 more IOA items available (file, library, argument, input value, pattern, network port). Please use our online service to access the data.

## References

The following list contains _external sources_ which discuss the actor and the associated activities:

* https://blog.talosintelligence.com/2019/04/sodinokibi-ransomware-exploits-weblogic.html
* https://blogs.blackberry.com/en/2021/11/revil-under-the-microscope
* https://ddanchev.blogspot.com/2022/01/exposing-internet-connected_24.html
* https://de.darktrace.com/blog/blackmatters-smash-and-grab-tactics-and-the-need-for-respond
* https://thedfirreport.com/2021/03/29/sodinokibi-aka-revil-ransomware/
* https://www.darktrace.com/en/blog/darktraces-cyber-ai-analyst-investigates-sodinokibi-r-evil-ransomware/
* https://www.varonis.com/blog/revil-msp-supply-chain-attack/

## Literature

The following _articles_ explain our unique predictive cyber threat intelligence:

* [VulDB Cyber Threat Intelligence Documentation](https://vuldb.com/?kb.cti)
* [Cyber Threat Intelligence - Early Anticipation of Attacks](https://www.scip.ch/en/?labs.20201022)

## License

(c) [1997-2025](https://vuldb.com/?kb.changelog) by [vuldb.com](https://vuldb.com/?kb.about). All data on this page is shared under the license [CC BY-NC-SA 4.0](https://creativecommons.org/licenses/by-nc-sa/4.0/). Questions? Check the [FAQ](https://vuldb.com/?kb.faq), read the [documentation](https://vuldb.com/?kb) or [contact us](https://vuldb.com/?contact)!
