# N-W0rm - Cyber Threat Intelligence

These _indicators_ were reported, collected, and generated during the [VulDB CTI analysis](https://vuldb.com/?kb.cti) of the actor known as [N-W0rm](https://vuldb.com/?actor.n-w0rm). The _activity monitoring_ correlates data from social media, forums, chat rooms, and darknet markets. It helps to determine associated actors, specific activities, expected intentions, emerging research, and ongoing attacks. Our unique _predictive model_ uses _big data_ to forecast activities and their characteristics.

_Live data_ and more _analysis capabilities_ are available at [https://vuldb.com/?actor.n-w0rm](https://vuldb.com/?actor.n-w0rm)

## Countries

These _countries_ are directly (e.g. origin of attacks) or indirectly (e.g. access by proxy) associated with N-W0rm:

* [CN](https://vuldb.com/?country.cn)
* [US](https://vuldb.com/?country.us)
* [ES](https://vuldb.com/?country.es)
* ...

There are 17 more country items available. Please use our online service to access the data.

## IOC - Indicator of Compromise

These _indicators of compromise_ (IOC) indicate associated network resources which are known to be part of research and attack activities of N-W0rm.

ID | IP address | Hostname | Campaign | Confidence
-- | ---------- | -------- | -------- | ----------
1 | [20.48.21.149](https://vuldb.com/?ip.20.48.21.149) | - | - | High
2 | [23.7.53.229](https://vuldb.com/?ip.23.7.53.229) | a23-7-53-229.deploy.static.akamaitechnologies.com | - | High
3 | [23.8.82.173](https://vuldb.com/?ip.23.8.82.173) | a23-8-82-173.deploy.static.akamaitechnologies.com | - | High
4 | [23.9.169.37](https://vuldb.com/?ip.23.9.169.37) | a23-9-169-37.deploy.static.akamaitechnologies.com | - | High
5 | [23.204.189.35](https://vuldb.com/?ip.23.204.189.35) | a23-204-189-35.deploy.static.akamaitechnologies.com | - | High
6 | [35.83.156.201](https://vuldb.com/?ip.35.83.156.201) | ec2-35-83-156-201.us-west-2.compute.amazonaws.com | - | Medium
7 | [35.168.183.178](https://vuldb.com/?ip.35.168.183.178) | ec2-35-168-183-178.compute-1.amazonaws.com | - | Medium
8 | [37.120.141.147](https://vuldb.com/?ip.37.120.141.147) | - | - | High
9 | [37.120.141.190](https://vuldb.com/?ip.37.120.141.190) | - | - | High
10 | ... | ... | ... | ...

There are 36 more IOC items available. Please use our online service to access the data.

## TTP - Tactics, Techniques, Procedures

_Tactics, techniques, and procedures_ (TTP) summarize the suspected MITRE ATT&CK techniques used by _N-W0rm_. This data is unique as it uses our predictive model for actor profiling.

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

These _indicators of attack_ (IOA) list the potential fragments used for technical activities like reconnaissance, exploitation, privilege escalation, and exfiltration by N-W0rm. This data is unique as it uses our predictive model for actor profiling.

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
16 | File | `/bin/ate` | Medium
17 | File | `/boat/login.php` | High
18 | File | `/bsms_ci/index.php/book` | High
19 | File | `/cgi-bin` | Medium
20 | File | `/cgi-bin/luci/api/wireless` | High
21 | File | `/cgi-bin/wlogin.cgi` | High
22 | File | `/context/%2e/WEB-INF/web.xml` | High
23 | File | `/dashboard/reports/logs/view` | High
24 | File | `/debian/patches/load_ppp_generic_if_needed` | High
25 | File | `/debug/pprof` | Medium
26 | File | `/env` | Low
27 | File | `/etc/hosts` | Medium
28 | File | `/forum/away.php` | High
29 | File | `/goform/setmac` | High
30 | File | `/goform/wizard_end` | High
31 | File | `/horde/util/go.php` | High
32 | File | `/index.php` | Medium
33 | File | `/manage-apartment.php` | High
34 | File | `/medicines/profile.php` | High
35 | File | `/modules/caddyhttp/rewrite/rewrite.go` | High
36 | File | `/pages/apply_vacancy.php` | High
37 | File | `/php-sms/admin/?page=user/manage_user` | High
38 | File | `/proc/<PID>/mem` | High
39 | File | `/proxy` | Low
40 | File | `/reservation/add_message.php` | High
41 | File | `/spip.php` | Medium
42 | File | `/tmp` | Low
43 | ... | ... | ...

There are 372 more IOA items available (file, library, argument, input value, pattern, network port). Please use our online service to access the data.

## References

The following list contains _external sources_ which discuss the actor and the associated activities:

* https://threatfox.abuse.ch

## Literature

The following _articles_ explain our unique predictive cyber threat intelligence:

* [VulDB Cyber Threat Intelligence Documentation](https://vuldb.com/?kb.cti)
* [Cyber Threat Intelligence - Early Anticipation of Attacks](https://www.scip.ch/en/?labs.20201022)

## License

(c) [1997-2023](https://vuldb.com/?kb.changelog) by [vuldb.com](https://vuldb.com/?kb.about). All data on this page is shared under the license [CC BY-NC-SA 4.0](https://creativecommons.org/licenses/by-nc-sa/4.0/). Questions? Check the [FAQ](https://vuldb.com/?kb.faq), read the [documentation](https://vuldb.com/?kb) or [contact us](https://vuldb.com/?contact)!
