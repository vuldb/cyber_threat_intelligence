# Rocke - Cyber Threat Intelligence

These _indicators_ were reported, collected, and generated during the [VulDB CTI analysis](https://vuldb.com/?kb.cti) of the actor known as [Rocke](https://vuldb.com/?actor.rocke). The _activity monitoring_ correlates data from social media, forums, chat rooms, and darknet markets. It helps to determine associated actors, specific activities, expected intentions, emerging research, and ongoing attacks. Our unique _predictive model_ uses _big data_ to forecast activities and their characteristics.

_Live data_ and more _analysis capabilities_ are available at [https://vuldb.com/?actor.rocke](https://vuldb.com/?actor.rocke)

## Countries

These _countries_ are directly (e.g. origin of attacks) or indirectly (e.g. access by proxy) associated with Rocke:

* [CN](https://vuldb.com/?country.cn)
* [US](https://vuldb.com/?country.us)
* [RU](https://vuldb.com/?country.ru)
* ...

There are 1 more country items available. Please use our online service to access the data.

## IOC - Indicator of Compromise

These _indicators of compromise_ (IOC) indicate associated network resources which are known to be part of research and attack activities of Rocke.

ID | IP address | Hostname | Campaign | Confidence
-- | ---------- | -------- | -------- | ----------
1 | [23.234.4.151](https://vuldb.com/?ip.23.234.4.151) | - | - | High
2 | [23.234.4.153](https://vuldb.com/?ip.23.234.4.153) | - | - | High
3 | [27.221.28.231](https://vuldb.com/?ip.27.221.28.231) | - | - | High
4 | [27.221.54.252](https://vuldb.com/?ip.27.221.54.252) | - | - | High
5 | [36.103.236.221](https://vuldb.com/?ip.36.103.236.221) | - | - | High
6 | [36.103.247.121](https://vuldb.com/?ip.36.103.247.121) | - | - | High
7 | [36.248.26.205](https://vuldb.com/?ip.36.248.26.205) | - | - | High
8 | [42.56.76.104](https://vuldb.com/?ip.42.56.76.104) | - | - | High
9 | [42.202.141.230](https://vuldb.com/?ip.42.202.141.230) | - | - | High
10 | [42.236.125.84](https://vuldb.com/?ip.42.236.125.84) | hn.kd.ny.adsl | - | High
11 | [43.224.225.220](https://vuldb.com/?ip.43.224.225.220) | - | - | High
12 | [43.242.166.88](https://vuldb.com/?ip.43.242.166.88) | - | - | High
13 | [58.215.145.137](https://vuldb.com/?ip.58.215.145.137) | - | - | High
14 | [58.216.107.77](https://vuldb.com/?ip.58.216.107.77) | - | - | High
15 | [58.218.208.13](https://vuldb.com/?ip.58.218.208.13) | - | - | High
16 | ... | ... | ... | ...

There are 62 more IOC items available. Please use our online service to access the data.

## TTP - Tactics, Techniques, Procedures

_Tactics, techniques, and procedures_ (TTP) summarize the suspected MITRE ATT&CK techniques used by _Rocke_. This data is unique as it uses our predictive model for actor profiling.

ID | Technique | Weakness | Description | Confidence
-- | --------- | -------- | ----------- | ----------
1 | T1059.007 | CWE-79, CWE-80 | Cross Site Scripting | High
2 | T1068 | CWE-264, CWE-284 | Execution with Unnecessary Privileges | High
3 | T1110.001 | CWE-307, CWE-798 | Improper Restriction of Excessive Authentication Attempts | High
4 | ... | ... | ... | ...

There are 7 more TTP items available. Please use our online service to access the data.

## IOA - Indicator of Attack

These _indicators of attack_ (IOA) list the potential fragments used for technical activities like reconnaissance, exploitation, privilege escalation, and exfiltration by Rocke. This data is unique as it uses our predictive model for actor profiling.

ID | Type | Indicator | Confidence
-- | ---- | --------- | ----------
1 | File | `%PROGRAMDATA%\checkmk\agent\local` | High
2 | File | `.htaccess` | Medium
3 | File | `/#/CampaignManager/users` | High
4 | File | `//` | Low
5 | File | `/admin.php?action=themeinstall` | High
6 | File | `/admin/index.php?id=themes&action=edit_template&filename=blog` | High
7 | File | `/admin/login.php` | High
8 | File | `/apply_noauth.cgi` | High
9 | File | `/article/comment` | High
10 | File | `/audit/log/log_management.php` | High
11 | File | `/backup/lispbx-CONF-YYYY-MM-DD.tar` | High
12 | File | `/bin/login` | Medium
13 | File | `/bin/sh` | Low
14 | File | `/cgi-bin/login` | High
15 | File | `/check_availability.php` | High
16 | File | `/classes/profile.class.php` | High
17 | File | `/crmeb/crmeb/services/UploadService.php` | High
18 | File | `/dev/tty` | Medium
19 | File | `/downloads/` | Medium
20 | File | `/IISADMPWD` | Medium
21 | File | `/inc/session.php` | High
22 | File | `/index.php` | Medium
23 | File | `/mcms/view.do` | High
24 | File | `/member/index/login.html` | High
25 | File | `/modules/certinfo/index.php` | High
26 | File | `/post/editing` | High
27 | File | `/public/plugins/` | High
28 | File | `/restful-services/publish` | High
29 | File | `/ScadaBR/login.htm` | High
30 | File | `/secure/admin/InsightDefaultCustomFieldConfig.jspa` | High
31 | File | `/system/tool/ping.php` | High
32 | File | `/upload` | Low
33 | File | `/usr/bin/pkexec` | High
34 | File | `/usr/sbin/mini_httpd` | High
35 | File | `/vendor/phpdocumentor/reflection-docblock/tests/phpDocumentor/Reflection/DocBlock/Tag/LinkTagTeet.php` | High
36 | File | `?location=search` | High
37 | File | `account/login.php` | High
38 | File | `add.asp` | Low
39 | File | `admin.home.php` | High
40 | File | `admin.php` | Medium
41 | ... | ... | ...

There are 355 more IOA items available (file, library, argument, input value, pattern, network port). Please use our online service to access the data.

## References

The following list contains _external sources_ which discuss the actor and the associated activities:

* https://blog.talosintelligence.com/2018/08/rocke-champion-of-monero-miners.html
* https://unit42.paloaltonetworks.com/malware-used-by-rocke-group-evolves-to-evade-detection-by-cloud-security-products/
* https://unit42.paloaltonetworks.com/rockein-the-netflow/
* https://www.anomali.com/blog/rocke-evolves-its-arsenal-with-a-new-malware-family-written-in-golang

## Literature

The following _articles_ explain our unique predictive cyber threat intelligence:

* [VulDB Cyber Threat Intelligence Documentation](https://vuldb.com/?kb.cti)
* [Cyber Threat Intelligence - Early Anticipation of Attacks](https://www.scip.ch/en/?labs.20201022)

## License

(c) [1997-2022](https://vuldb.com/?kb.changelog) by [vuldb.com](https://vuldb.com/?kb.about). All data on this page is shared under the license [CC BY-NC-SA 4.0](https://creativecommons.org/licenses/by-nc-sa/4.0/). Questions? Check the [FAQ](https://vuldb.com/?kb.faq), read the [documentation](https://vuldb.com/?kb) or [contact us](https://vuldb.com/?contact)!
