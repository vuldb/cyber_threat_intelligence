# Shell Crew - Cyber Threat Intelligence

These _indicators_ were reported, collected, and generated during the [VulDB CTI analysis](https://vuldb.com/?kb.cti) of the actor known as [Shell Crew](https://vuldb.com/?actor.shell_crew). The _activity monitoring_ correlates data from social media, forums, chat rooms, and darknet markets. It helps to determine associated actors, specific activities, expected intentions, emerging research, and ongoing attacks. Our unique _predictive model_ uses _big data_ to forecast activities and their characteristics.

_Live data_ and more _analysis capabilities_ are available at [https://vuldb.com/?actor.shell_crew](https://vuldb.com/?actor.shell_crew)

## Campaigns

The following _campaigns_ are known and can be associated with Shell Crew:

* StreamEx

## Countries

These _countries_ are directly (e.g. origin of attacks) or indirectly (e.g. access by proxy) associated with Shell Crew:

* [CN](https://vuldb.com/?country.cn)
* [US](https://vuldb.com/?country.us)
* [ES](https://vuldb.com/?country.es)
* ...

There are 16 more country items available. Please use our online service to access the data.

## IOC - Indicator of Compromise

These _indicators of compromise_ (IOC) indicate associated network resources which are known to be part of research and attack activities of Shell Crew.

ID | IP address | Hostname | Campaign | Confidence
-- | ---------- | -------- | -------- | ----------
1 | [12.0.742.112](https://vuldb.com/?ip.12.0.742.112) | - | - | High
2 | [31.210.102.210](https://vuldb.com/?ip.31.210.102.210) | . | StreamEx | High
3 | [43.249.81.209](https://vuldb.com/?ip.43.249.81.209) | - | StreamEx | High
4 | [43.249.81.210](https://vuldb.com/?ip.43.249.81.210) | - | - | High
5 | [50.115.138.215](https://vuldb.com/?ip.50.115.138.215) | 50-115-138-215.genericreverse.com | - | High
6 | ... | ... | ... | ...

There are 22 more IOC items available. Please use our online service to access the data.

## TTP - Tactics, Techniques, Procedures

_Tactics, techniques, and procedures_ (TTP) summarize the suspected MITRE ATT&CK techniques used by _Shell Crew_. This data is unique as it uses our predictive model for actor profiling.

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

These _indicators of attack_ (IOA) list the potential fragments used for technical activities like reconnaissance, exploitation, privilege escalation, and exfiltration by Shell Crew. This data is unique as it uses our predictive model for actor profiling.

ID | Type | Indicator | Confidence
-- | ---- | --------- | ----------
1 | File | `/?p=products` | Medium
2 | File | `/about.php` | Medium
3 | File | `/admin.php/accessory/filesdel.html` | High
4 | File | `/admin/?page=user/manage` | High
5 | File | `/admin/add-new.php` | High
6 | File | `/admin/doctors.php` | High
7 | File | `/admin/submit-articles` | High
8 | File | `/ad_js.php` | Medium
9 | File | `/alphaware/summary.php` | High
10 | File | `/api/` | Low
11 | File | `/api/admin/store/product/list` | High
12 | File | `/api/stl/actions/search` | High
13 | File | `/api/v2/cli/commands` | High
14 | File | `/app/options.py` | High
15 | File | `/attachments` | Medium
16 | File | `/boat/login.php` | High
17 | File | `/bsms_ci/index.php/book` | High
18 | File | `/cgi-bin` | Medium
19 | File | `/cgi-bin/luci/api/wireless` | High
20 | File | `/cgi-bin/wlogin.cgi` | High
21 | File | `/context/%2e/WEB-INF/web.xml` | High
22 | File | `/dashboard/reports/logs/view` | High
23 | File | `/debian/patches/load_ppp_generic_if_needed` | High
24 | File | `/debug/pprof` | Medium
25 | File | `/etc/hosts` | Medium
26 | File | `/forum/away.php` | High
27 | File | `/goform/setmac` | High
28 | File | `/goform/wizard_end` | High
29 | File | `/manage-apartment.php` | High
30 | File | `/medicines/profile.php` | High
31 | File | `/modules/caddyhttp/rewrite/rewrite.go` | High
32 | File | `/pages/apply_vacancy.php` | High
33 | File | `/proc/<PID>/mem` | High
34 | File | `/proxy` | Low
35 | File | `/reservation/add_message.php` | High
36 | File | `/spip.php` | Medium
37 | File | `/tmp` | Low
38 | File | `/uncpath/` | Medium
39 | ... | ... | ...

There are 340 more IOA items available (file, library, argument, input value, pattern, network port). Please use our online service to access the data.

## References

The following list contains _external sources_ which discuss the actor and the associated activities:

* https://blogs.blackberry.com/en/2017/02/shell-crew-variants-continue-to-fly-under-big-avs-radar
* https://www.threatminer.org/report.php?q=RSAIncidentResponseEmergingThreatProfile_ShellCrew.pdf&y=2014
* https://www.threatminer.org/report.php?q=ShellCrewVariantsContinuetoFlyUnderBigAV%E2%80%99sRadar-Cylance.pdf&y=2017

## Literature

The following _articles_ explain our unique predictive cyber threat intelligence:

* [VulDB Cyber Threat Intelligence Documentation](https://vuldb.com/?kb.cti)
* [Cyber Threat Intelligence - Early Anticipation of Attacks](https://www.scip.ch/en/?labs.20201022)

## License

(c) [1997-2023](https://vuldb.com/?kb.changelog) by [vuldb.com](https://vuldb.com/?kb.about). All data on this page is shared under the license [CC BY-NC-SA 4.0](https://creativecommons.org/licenses/by-nc-sa/4.0/). Questions? Check the [FAQ](https://vuldb.com/?kb.faq), read the [documentation](https://vuldb.com/?kb) or [contact us](https://vuldb.com/?contact)!
