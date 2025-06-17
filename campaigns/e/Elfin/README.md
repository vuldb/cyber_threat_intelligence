# Elfin - Cyber Threat Intelligence

These _indicators_ were reported, collected, and generated during the [VulDB CTI analysis](https://vuldb.com/?kb.cti) of the campaign known as _Elfin_. The _activity monitoring_ correlates data from social media, forums, chat rooms, and darknet markets. It helps to determine associated actors, specific activities, expected intentions, emerging research, and ongoing attacks. Our unique _predictive model_ uses _big data_ to forecast activities and their characteristics.

_Live data_ and more _analysis capabilities_ are available at [https://vuldb.com/?actor](https://vuldb.com/?actor)

## Countries

These _countries_ are directly (e.g. origin of attacks) or indirectly (e.g. access by proxy) associated with Elfin:

* [US](https://vuldb.com/?country.us)
* [GB](https://vuldb.com/?country.gb)
* [RU](https://vuldb.com/?country.ru)
* ...

There are 17 more country items available. Please use our online service to access the data.

## Actors

These _actors_ are associated with Elfin or other actors linked to the campaign.

ID | Actor | Confidence
-- | ----- | ----------
1 | [APT33](https://vuldb.com/?actor.apt33) | High

## IOC - Indicator of Compromise

These _indicators of compromise_ (IOC) indicate associated network resources which are known to be part of research and attack activities of Elfin.

ID | IP address | Hostname | Actor | Confidence
-- | ---------- | -------- | ----- | ----------
1 | [5.79.127.177](https://vuldb.com/?ip.5.79.127.177) | - | [APT33](https://vuldb.com/?actor.apt33) | High
2 | [5.187.21.70](https://vuldb.com/?ip.5.187.21.70) | - | [APT33](https://vuldb.com/?actor.apt33) | High
3 | [5.187.21.71](https://vuldb.com/?ip.5.187.21.71) | - | [APT33](https://vuldb.com/?actor.apt33) | High
4 | [8.26.21.117](https://vuldb.com/?ip.8.26.21.117) | 117.21.26.8.serverpronto.com | [APT33](https://vuldb.com/?actor.apt33) | High
5 | [8.26.21.119](https://vuldb.com/?ip.8.26.21.119) | ns1.glasscitysoftware.net | [APT33](https://vuldb.com/?actor.apt33) | High
6 | [8.26.21.120](https://vuldb.com/?ip.8.26.21.120) | ns2.glasscitysoftware.net | [APT33](https://vuldb.com/?actor.apt33) | High
7 | [8.26.21.220](https://vuldb.com/?ip.8.26.21.220) | mail2.boldinbox.com | [APT33](https://vuldb.com/?actor.apt33) | High
8 | [8.26.21.221](https://vuldb.com/?ip.8.26.21.221) | mail3.boldinbox.com | [APT33](https://vuldb.com/?actor.apt33) | High
9 | ... | ... | ... | ...

There are 32 more IOC items available. Please use our online service to access the data.

## TTP - Tactics, Techniques, Procedures

_Tactics, techniques, and procedures_ (TTP) summarize the suspected MITRE ATT&CK techniques used within Elfin. This data is unique as it uses our predictive model for actor profiling.

ID | Technique | Weakness | Description | Confidence
-- | --------- | -------- | ----------- | ----------
1 | T1006 | CWE-22, CWE-23, CWE-35, CWE-425 | Path Traversal | High
2 | T1040 | CWE-294, CWE-319 | Authentication Bypass by Capture-replay | High
3 | T1055 | CWE-74 | Improper Neutralization of Data within XPath Expressions | High
4 | T1059 | CWE-88, CWE-94 | Argument Injection | High
5 | T1059.007 | CWE-79, CWE-80 | Basic Cross Site Scripting | High
6 | ... | ... | ... | ...

There are 21 more TTP items available. Please use our online service to access the data.

## IOA - Indicator of Attack

These _indicators of attack_ (IOA) list the potential fragments used for technical activities like reconnaissance, exploitation, privilege escalation, and exfiltration during Elfin. This data is unique as it uses our predictive model for actor profiling.

ID | Type | Indicator | Confidence
-- | ---- | --------- | ----------
1 | File | `/+CSCOE+/logon.html` | High
2 | File | `/admin/?page=system_info/contact_info` | High
3 | File | `/admin/index.php` | High
4 | File | `/admin/login.php` | High
5 | File | `/admin/process_category_add.php` | High
6 | File | `/admin/produts/controller.php` | High
7 | File | `/admin/update-clients.php` | High
8 | File | `/admin/user/team` | High
9 | File | `/api/esps` | Medium
10 | File | `/api/login/auth` | High
11 | File | `/Api/TinyMce/UploadAjax.ashx` | High
12 | File | `/backupsettings.conf` | High
13 | File | `/book-services.php` | High
14 | File | `/cgi-bin/cstecgi.cgi` | High
15 | File | `/cgi-bin/system_mgr.cgi` | High
16 | File | `/common/logViewer/logViewer.jsf` | High
17 | File | `/crmeb/app/admin/controller/store/CopyTaobao.php` | High
18 | File | `/dashboard/admin/new_submit.php` | High
19 | File | `/en/blog-comment-4` | High
20 | File | `/export` | Low
21 | File | `/fladmin/jump.php` | High
22 | File | `/fladmin/sysconfig_doedit.php` | High
23 | File | `/foms/routers/cancel-order.php` | High
24 | File | `/forum/away.php` | High
25 | File | `/goform/aspForm` | High
26 | File | `/h/` | Low
27 | File | `/hocms/classes/Master.php?f=delete_collection` | High
28 | File | `/horde/util/go.php` | High
29 | File | `/index.php` | Medium
30 | File | `/mifs/c/i/reg/reg.html` | High
31 | File | `/ms/cms/content/list.do` | High
32 | File | `/opt/zimbra/jetty/webapps/zimbra/public` | High
33 | File | `/orms/` | Low
34 | File | `/plesk-site-preview/` | High
35 | File | `/project/PROJECTNAME/reports/` | High
36 | File | `/protocol/iscuser/uploadiscuser.php` | High
37 | File | `/public/login.htm` | High
38 | ... | ... | ...

There are 327 more IOA items available (file, library, argument, input value, pattern, network port). Please use our online service to access the data.

## References

The following list contains _external sources_ which discuss the campaign and the associated activities:

* https://symantec-enterprise-blogs.security.com/blogs/threat-intelligence/elfin-apt33-espionage
* https://www.symantec.com/blogs/threat-intelligence/elfin-apt33-espionage

## Literature

The following _articles_ explain our unique predictive cyber threat intelligence:

* [VulDB Cyber Threat Intelligence Documentation](https://vuldb.com/?kb.cti)
* [Cyber Threat Intelligence - Early Anticipation of Attacks](https://www.scip.ch/en/?labs.20201022)

## License

(c) [1997-2025](https://vuldb.com/?kb.changelog) by [vuldb.com](https://vuldb.com/?kb.about). All data on this page is shared under the license [CC BY-NC-SA 4.0](https://creativecommons.org/licenses/by-nc-sa/4.0/). Questions? Check the [FAQ](https://vuldb.com/?kb.faq), read the [documentation](https://vuldb.com/?kb) or [contact us](https://vuldb.com/?contact)!
