# BlackEnergy - Cyber Threat Intelligence

These _indicators_ were reported, collected, and generated during the [VulDB CTI analysis](https://vuldb.com/?kb.cti) of the campaign known as _BlackEnergy_. The _activity monitoring_ correlates data from social media, forums, chat rooms, and darknet markets. It helps to determine associated actors, specific activities, expected intentions, emerging research, and ongoing attacks. Our unique _predictive model_ uses _big data_ to forecast activities and their characteristics.

_Live data_ and more _analysis capabilities_ are available at [https://vuldb.com/?actor](https://vuldb.com/?actor)

## Countries

These _countries_ are directly (e.g. origin of attacks) or indirectly (e.g. access by proxy) associated with BlackEnergy:

* [CN](https://vuldb.com/?country.cn)
* [US](https://vuldb.com/?country.us)
* [ES](https://vuldb.com/?country.es)
* ...

There are 15 more country items available. Please use our online service to access the data.

## Actors

These _actors_ are associated with BlackEnergy or other actors linked to the campaign.

ID | Actor | Confidence
-- | ----- | ----------
1 | [Sandworm Team](https://vuldb.com/?actor.sandworm_team) | High
2 | [BlackEnergy](https://vuldb.com/?actor.blackenergy) | High

## IOC - Indicator of Compromise

These _indicators of compromise_ (IOC) indicate associated network resources which are known to be part of research and attack activities of BlackEnergy.

ID | IP address | Hostname | Actor | Confidence
-- | ---------- | -------- | ----- | ----------
1 | [5.9.32.230](https://vuldb.com/?ip.5.9.32.230) | static.230.32.9.5.clients.your-server.de | [BlackEnergy](https://vuldb.com/?actor.blackenergy) | High
2 | [5.61.38.31](https://vuldb.com/?ip.5.61.38.31) | - | [BlackEnergy](https://vuldb.com/?actor.blackenergy) | High
3 | [5.79.80.166](https://vuldb.com/?ip.5.79.80.166) | - | [BlackEnergy](https://vuldb.com/?actor.blackenergy) | High
4 | [5.149.254.114](https://vuldb.com/?ip.5.149.254.114) | mail1.auditoriavanzada.info | [BlackEnergy](https://vuldb.com/?actor.blackenergy) | High
5 | [5.255.87.39](https://vuldb.com/?ip.5.255.87.39) | - | [BlackEnergy](https://vuldb.com/?actor.blackenergy) | High
6 | [31.210.111.154](https://vuldb.com/?ip.31.210.111.154) | - | [BlackEnergy](https://vuldb.com/?actor.blackenergy) | High
7 | ... | ... | ... | ...

There are 24 more IOC items available. Please use our online service to access the data.

## TTP - Tactics, Techniques, Procedures

_Tactics, techniques, and procedures_ (TTP) summarize the suspected MITRE ATT&CK techniques used within BlackEnergy. This data is unique as it uses our predictive model for actor profiling.

ID | Technique | Weakness | Description | Confidence
-- | --------- | -------- | ----------- | ----------
1 | T1006 | CWE-21, CWE-22, CWE-23, CWE-28 | Pathname Traversal | High
2 | T1040 | CWE-294, CWE-319 | Authentication Bypass by Capture-replay | High
3 | T1055 | CWE-74 | Injection | High
4 | T1059 | CWE-88, CWE-94 | Cross Site Scripting | High
5 | T1059.007 | CWE-79, CWE-80 | Cross Site Scripting | High
6 | ... | ... | ... | ...

There are 19 more TTP items available. Please use our online service to access the data.

## IOA - Indicator of Attack

These _indicators of attack_ (IOA) list the potential fragments used for technical activities like reconnaissance, exploitation, privilege escalation, and exfiltration during BlackEnergy. This data is unique as it uses our predictive model for actor profiling.

ID | Type | Indicator | Confidence
-- | ---- | --------- | ----------
1 | File | `/about.php` | Medium
2 | File | `/admin.php/accessory/filesdel.html` | High
3 | File | `/admin/?page=user/manage` | High
4 | File | `/admin/add-new.php` | High
5 | File | `/admin/doctors.php` | High
6 | File | `/admin/submit-articles` | High
7 | File | `/ad_js.php` | Medium
8 | File | `/alphaware/summary.php` | High
9 | File | `/api/` | Low
10 | File | `/api/admin/store/product/list` | High
11 | File | `/api/v2/cli/commands` | High
12 | File | `/app/options.py` | High
13 | File | `/attachments` | Medium
14 | File | `/boat/login.php` | High
15 | File | `/bsms_ci/index.php/book` | High
16 | File | `/cgi-bin/luci/api/wireless` | High
17 | File | `/cgi-bin/wlogin.cgi` | High
18 | File | `/context/%2e/WEB-INF/web.xml` | High
19 | File | `/dashboard/reports/logs/view` | High
20 | File | `/debian/patches/load_ppp_generic_if_needed` | High
21 | File | `/debug/pprof` | Medium
22 | File | `/etc/hosts` | Medium
23 | File | `/forum/away.php` | High
24 | File | `/goform/setmac` | High
25 | File | `/goform/wizard_end` | High
26 | File | `/manage-apartment.php` | High
27 | File | `/medicines/profile.php` | High
28 | File | `/modules/caddyhttp/rewrite/rewrite.go` | High
29 | File | `/out.php` | Medium
30 | File | `/owa/auth/logon.aspx` | High
31 | File | `/pages/apply_vacancy.php` | High
32 | File | `/pet_shop/admin/?page=maintenance/manage_category` | High
33 | File | `/proc/<PID>/mem` | High
34 | File | `/proxy` | Low
35 | File | `/reservation/add_message.php` | High
36 | File | `/spip.php` | Medium
37 | File | `/tmp` | Low
38 | File | `/uncpath/` | Medium
39 | File | `/upload` | Low
40 | File | `/vendor/htmlawed/htmlawed/htmLawedTest.php` | High
41 | File | `/vendor/views/add_product.php` | High
42 | ... | ... | ...

There are 360 more IOA items available (file, library, argument, input value, pattern, network port). Please use our online service to access the data.

## References

The following list contains _external sources_ which discuss the campaign and the associated activities:

* http://blogs.mcafee.jp/blackenergy-cb6d
* https://www.threatminer.org/report.php?q=BlackEnergy2_Plugins_Router.pdf&y=2014
* https://www.welivesecurity.com/2016/01/03/blackenergy-sshbeardoor-details-2015-attacks-ukrainian-news-media-electric-industry/

## Literature

The following _articles_ explain our unique predictive cyber threat intelligence:

* [VulDB Cyber Threat Intelligence Documentation](https://vuldb.com/?kb.cti)
* [Cyber Threat Intelligence - Early Anticipation of Attacks](https://www.scip.ch/en/?labs.20201022)

## License

(c) [1997-2023](https://vuldb.com/?kb.changelog) by [vuldb.com](https://vuldb.com/?kb.about). All data on this page is shared under the license [CC BY-NC-SA 4.0](https://creativecommons.org/licenses/by-nc-sa/4.0/). Questions? Check the [FAQ](https://vuldb.com/?kb.faq), read the [documentation](https://vuldb.com/?kb) or [contact us](https://vuldb.com/?contact)!
