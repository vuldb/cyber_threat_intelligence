# BumbleBee - Cyber Threat Intelligence

These _indicators_ were reported, collected, and generated during the [VulDB CTI analysis](https://vuldb.com/?kb.cti) of the campaign known as _BumbleBee_. The _activity monitoring_ correlates data from social media, forums, chat rooms, and darknet markets. It helps to determine associated actors, specific activities, expected intentions, emerging research, and ongoing attacks. Our unique _predictive model_ uses _big data_ to forecast activities and their characteristics.

_Live data_ and more _analysis capabilities_ are available at [https://vuldb.com/?actor](https://vuldb.com/?actor)

## Countries

These _countries_ are directly (e.g. origin of attacks) or indirectly (e.g. access by proxy) associated with BumbleBee:

* [US](https://vuldb.com/?country.us)
* [RU](https://vuldb.com/?country.ru)
* [CN](https://vuldb.com/?country.cn)
* ...

There are 34 more country items available. Please use our online service to access the data.

## Actors

These _actors_ are associated with BumbleBee or other actors linked to the campaign.

ID | Actor | Confidence
-- | ----- | ----------
1 | [xHunt](https://vuldb.com/?actor.xhunt) | High
2 | [Exotic Lily](https://vuldb.com/?actor.exotic_lily) | High

## IOC - Indicator of Compromise

These _indicators of compromise_ (IOC) indicate associated network resources which are known to be part of research and attack activities of BumbleBee.

ID | IP address | Hostname | Actor | Confidence
-- | ---------- | -------- | ----- | ----------
1 | [23.81.246.187](https://vuldb.com/?ip.23.81.246.187) | - | [Exotic Lily](https://vuldb.com/?actor.exotic_lily) | High
2 | [23.92.127.18](https://vuldb.com/?ip.23.92.127.18) | - | [xHunt](https://vuldb.com/?actor.xhunt) | High
3 | [46.246.3.253](https://vuldb.com/?ip.46.246.3.253) | - | [xHunt](https://vuldb.com/?actor.xhunt) | High
4 | [46.246.3.254](https://vuldb.com/?ip.46.246.3.254) | - | [xHunt](https://vuldb.com/?actor.xhunt) | High
5 | [77.243.191.20](https://vuldb.com/?ip.77.243.191.20) | - | [xHunt](https://vuldb.com/?actor.xhunt) | High
6 | [82.102.21.219](https://vuldb.com/?ip.82.102.21.219) | - | [xHunt](https://vuldb.com/?actor.xhunt) | High
7 | [84.17.55.68](https://vuldb.com/?ip.84.17.55.68) | unn-84-17-55-68.cdn77.com | [xHunt](https://vuldb.com/?actor.xhunt) | High
8 | ... | ... | ... | ...

There are 26 more IOC items available. Please use our online service to access the data.

## TTP - Tactics, Techniques, Procedures

_Tactics, techniques, and procedures_ (TTP) summarize the suspected MITRE ATT&CK techniques used within BumbleBee. This data is unique as it uses our predictive model for actor profiling.

ID | Technique | Weakness | Description | Confidence
-- | --------- | -------- | ----------- | ----------
1 | T1059.007 | CWE-79, CWE-80 | Cross Site Scripting | High
2 | T1068 | CWE-264, CWE-284 | Execution with Unnecessary Privileges | High
3 | T1110.001 | CWE-307, CWE-798 | Improper Restriction of Excessive Authentication Attempts | High
4 | ... | ... | ... | ...

There are 7 more TTP items available. Please use our online service to access the data.

## IOA - Indicator of Attack

These _indicators of attack_ (IOA) list the potential fragments used for technical activities like reconnaissance, exploitation, privilege escalation, and exfiltration during BumbleBee. This data is unique as it uses our predictive model for actor profiling.

ID | Type | Indicator | Confidence
-- | ---- | --------- | ----------
1 | File | `%PROGRAMDATA%\Razer\Synapse3\Service\bin` | High
2 | File | `/+CSCOE+/logon.html` | High
3 | File | `/6/api.php?function=command&class=remote&Cc='ls'` | High
4 | File | `/about.php` | Medium
5 | File | `/admin.php?action=themeinstall` | High
6 | File | `/admin/contenttemp` | High
7 | File | `/admin/modules/system/custom_field.php` | High
8 | File | `/api/crontab` | Medium
9 | File | `/app1/admin#foo` | High
10 | File | `/bin/boa` | Medium
11 | File | `/category_view.php` | High
12 | File | `/cgi-bin/wapopen` | High
13 | File | `/cgi-mod/lookup.cgi` | High
14 | File | `/cgi?1&5` | Medium
15 | File | `/config/getuser` | High
16 | File | `/debug/pprof` | Medium
17 | File | `/forum/away.php` | High
18 | File | `/gracemedia-media-player/templates/files/ajax_controller.php` | High
19 | File | `/iissamples` | Medium
20 | File | `/interface/main/backup.php` | High
21 | File | `/new` | Low
22 | File | `/public/plugins/` | High
23 | File | `/sbin/gs_config` | High
24 | File | `/secure/QueryComponent!Default.jspa` | High
25 | File | `/uncpath/` | Medium
26 | File | `/uploads/dede` | High
27 | File | `/usr/bin/pkexec` | High
28 | File | `/usr/sbin/nagios` | High
29 | File | `/usr/sbin/suexec` | High
30 | File | `/webman/info.cgi` | High
31 | File | `/wp-admin/admin-ajax.php` | High
32 | File | `/wp-json/oembed/1.0/embed?url` | High
33 | File | `/wp-json/wc/v3/webhooks` | High
34 | File | `14all.cgi/14all-1.1.cgi/traffic.cgi/mrtg.cgi` | High
35 | File | `adclick.php` | Medium
36 | File | `admin.php?m=admin&c=site&a=save` | High
37 | File | `admin.php?page=languages` | High
38 | File | `admin/admin_users.php` | High
39 | File | `admin/bitrix.mpbuilder_step2.php` | High
40 | File | `admin/bitrix.xscan_worker.php` | High
41 | File | `admin/conf_users_edit.php` | High
42 | File | `admin/mcart_xls_import.php` | High
43 | File | `admin/ops/reports/ops/news.php` | High
44 | File | `admin/orion.extfeedbackform_efbf_forms.php` | High
45 | File | `adminer.php` | Medium
46 | ... | ... | ...

There are 394 more IOA items available (file, library, argument, input value, pattern, network port). Please use our online service to access the data.

## References

The following list contains _external sources_ which discuss the campaign and the associated activities:

* https://blog.google/threat-analysis-group/exposing-initial-access-broker-ties-conti/
* https://unit42.paloaltonetworks.com/bumblebee-webshell-xhunt-campaign/

## Literature

The following _articles_ explain our unique predictive cyber threat intelligence:

* [VulDB Cyber Threat Intelligence Documentation](https://vuldb.com/?kb.cti)
* [Cyber Threat Intelligence - Early Anticipation of Attacks](https://www.scip.ch/en/?labs.20201022)

## License

(c) [1997-2022](https://vuldb.com/?kb.changelog) by [vuldb.com](https://vuldb.com/?kb.about). All data on this page is shared under the license [CC BY-NC-SA 4.0](https://creativecommons.org/licenses/by-nc-sa/4.0/). Questions? Check the [FAQ](https://vuldb.com/?kb.faq), read the [documentation](https://vuldb.com/?kb) or [contact us](https://vuldb.com/?contact)!
