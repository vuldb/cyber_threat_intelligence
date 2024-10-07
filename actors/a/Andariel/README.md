# Andariel - Cyber Threat Intelligence

These _indicators_ were reported, collected, and generated during the [VulDB CTI analysis](https://vuldb.com/?kb.cti) of the actor known as [Andariel](https://vuldb.com/?actor.andariel). The _activity monitoring_ correlates data from social media, forums, chat rooms, and darknet markets. It helps to determine associated actors, specific activities, expected intentions, emerging research, and ongoing attacks. Our unique _predictive model_ uses _big data_ to forecast activities and their characteristics.

_Live data_ and more _analysis capabilities_ are available at [https://vuldb.com/?actor.andariel](https://vuldb.com/?actor.andariel)

## Campaigns

The following _campaigns_ are known and can be associated with Andariel:

* Cobalt Strike
* CVE-2023-46604
* Metasploit
* ...

There are 1 more campaign items available. Please use our online service to access the data.

## Countries

These _countries_ are directly (e.g. origin of attacks) or indirectly (e.g. access by proxy) associated with Andariel:

* [CN](https://vuldb.com/?country.cn)
* [US](https://vuldb.com/?country.us)
* [GB](https://vuldb.com/?country.gb)
* ...

There are 13 more country items available. Please use our online service to access the data.

## IOC - Indicator of Compromise

These _indicators of compromise_ (IOC) indicate associated network resources which are known to be part of research and attack activities of Andariel.

ID | IP address | Hostname | Campaign | Confidence
-- | ---------- | -------- | -------- | ----------
1 | [4.246.144.112](https://vuldb.com/?ip.4.246.144.112) | - | - | High
2 | [4.246.149.227](https://vuldb.com/?ip.4.246.149.227) | - | - | High
3 | [8.213.128.76](https://vuldb.com/?ip.8.213.128.76) | - | - | High
4 | [13.76.133.68](https://vuldb.com/?ip.13.76.133.68) | - | - | High
5 | [27.102.107.224](https://vuldb.com/?ip.27.102.107.224) | - | - | High
6 | [27.102.107.230](https://vuldb.com/?ip.27.102.107.230) | - | - | High
7 | [27.102.107.233](https://vuldb.com/?ip.27.102.107.233) | - | - | High
8 | ... | ... | ... | ...

There are 27 more IOC items available. Please use our online service to access the data.

## TTP - Tactics, Techniques, Procedures

_Tactics, techniques, and procedures_ (TTP) summarize the suspected MITRE ATT&CK techniques used by _Andariel_. This data is unique as it uses our predictive model for actor profiling.

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

These _indicators of attack_ (IOA) list the potential fragments used for technical activities like reconnaissance, exploitation, privilege escalation, and exfiltration by Andariel. This data is unique as it uses our predictive model for actor profiling.

ID | Type | Indicator | Confidence
-- | ---- | --------- | ----------
1 | File | `/.env` | Low
2 | File | `/act/ActDao.xml` | High
3 | File | `/admin/article.php` | High
4 | File | `/admin/comment.php` | High
5 | File | `/admin/index.php` | High
6 | File | `/admin/index2.html` | High
7 | File | `/admin/uesrs.php&action=type&userrole=Admin&userid=3` | High
8 | File | `/api/sys/set_passwd` | High
9 | File | `/api/v1/terminal/sessions/?limit=1` | High
10 | File | `/assets/something/services/AppModule.class` | High
11 | File | `/authenticate.php` | High
12 | File | `/bin/boa` | Medium
13 | File | `/blog` | Low
14 | File | `/cgi-bin/login.cgi` | High
15 | File | `/cgi-bin/luci/api/wireless` | High
16 | File | `/cgi-bin/system_mgr.cgi` | High
17 | File | `/cgi-bin/wapopen` | High
18 | File | `/cgi-bin/webproc` | High
19 | File | `/cgi-bin/wlogin.cgi` | High
20 | File | `/classes/SystemSettings.php?f=update_settings` | High
21 | File | `/conf/app.conf` | High
22 | File | `/dev/urandom` | Medium
23 | File | `/dist/index.js` | High
24 | File | `/Duty/AjaxHandle/UploadFloodPlanFileUpdate.ashx` | High
25 | File | `/endpoint/delete-account.php` | High
26 | File | `/etc/postfix/sender_login` | High
27 | File | `/etc/quantum/quantum.conf` | High
28 | File | `/fax/fax_send.php` | High
29 | File | `/files/list-file` | High
30 | File | `/forum/away.php` | High
31 | File | `/getcfg.php` | Medium
32 | File | `/goform/RGFirewallEL` | High
33 | File | `/HNAP1` | Low
34 | File | `/inc/parser/xhtml.php` | High
35 | File | `/index.php?menu=asterisk_cli` | High
36 | File | `/jsoa/hntdCustomDesktopActionContent` | High
37 | File | `/lists/index.php` | High
38 | File | `/login.html` | Medium
39 | File | `/medical/inventories.php` | High
40 | File | `/mgmt/tm/util/bash` | High
41 | File | `/mobilebroker/ServiceToBroker.svc/Json/Connect` | High
42 | File | `/modules/projects/vw_files.php` | High
43 | File | `/new` | Low
44 | File | `/plain` | Low
45 | ... | ... | ...

There are 391 more IOA items available (file, library, argument, input value, pattern, network port). Please use our online service to access the data.

## References

The following list contains _external sources_ which discuss the actor and the associated activities:

* https://asec.ahnlab.com/en/56405/
* https://asec.ahnlab.com/en/59073/
* https://asec.ahnlab.com/en/59318/
* https://asec.ahnlab.com/en/59904/
* https://asec.ahnlab.com/en/63192/
* https://asec.ahnlab.com/en/66088/

## Literature

The following _articles_ explain our unique predictive cyber threat intelligence:

* [VulDB Cyber Threat Intelligence Documentation](https://vuldb.com/?kb.cti)
* [Cyber Threat Intelligence - Early Anticipation of Attacks](https://www.scip.ch/en/?labs.20201022)

## License

(c) [1997-2024](https://vuldb.com/?kb.changelog) by [vuldb.com](https://vuldb.com/?kb.about). All data on this page is shared under the license [CC BY-NC-SA 4.0](https://creativecommons.org/licenses/by-nc-sa/4.0/). Questions? Check the [FAQ](https://vuldb.com/?kb.faq), read the [documentation](https://vuldb.com/?kb) or [contact us](https://vuldb.com/?contact)!
