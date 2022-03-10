# xHunt - Cyber Threat Intelligence

These _indicators_ were reported, collected, and generated during the [VulDB CTI analysis](https://vuldb.com/?kb.cti) of the actor known as [xHunt](https://vuldb.com/?actor.xhunt). The _activity monitoring_ correlates data from social media, forums, chat rooms, and darknet markets. It helps to determine associated actors, specific activities, expected intentions, emerging research, and ongoing attacks. Our unique _predictive model_ uses _big data_ to forecast activities and their characteristics.

_Live data_ and more _analysis capabilities_ are available at [https://vuldb.com/?actor.xhunt](https://vuldb.com/?actor.xhunt)

## Campaigns

The following _campaigns_ are known and can be associated with xHunt:

* BumbleBee

## Countries

These _countries_ are directly (e.g. origin of attacks) or indirectly (e.g. access by proxy) associated with xHunt:

* [US](https://vuldb.com/?country.us)
* [CN](https://vuldb.com/?country.cn)
* [NL](https://vuldb.com/?country.nl)
* ...

There are 34 more country items available. Please use our online service to access the data.

## IOC - Indicator of Compromise

These _indicators of compromise_ (IOC) indicate associated network resources which are known to be part of research and attack activities of xHunt.

ID | IP address | Hostname | Campaign | Confidence
-- | ---------- | -------- | -------- | ----------
1 | [23.92.127.18](https://vuldb.com/?ip.23.92.127.18) | - | BumbleBee | High
2 | [46.246.3.253](https://vuldb.com/?ip.46.246.3.253) | - | BumbleBee | High
3 | [46.246.3.254](https://vuldb.com/?ip.46.246.3.254) | - | BumbleBee | High
4 | [77.243.191.20](https://vuldb.com/?ip.77.243.191.20) | - | BumbleBee | High
5 | [82.102.21.219](https://vuldb.com/?ip.82.102.21.219) | - | BumbleBee | High
6 | [84.17.55.68](https://vuldb.com/?ip.84.17.55.68) | unn-84-17-55-68.cdn77.com | BumbleBee | High
7 | [85.203.46.99](https://vuldb.com/?ip.85.203.46.99) | - | BumbleBee | High
8 | ... | ... | ... | ...

There are 26 more IOC items available. Please use our online service to access the data.

## TTP - Tactics, Techniques, Procedures

_Tactics, techniques, and procedures_ (TTP) summarize the suspected ATT&CK techniques used by _xHunt_. This data is unique as it uses our predictive model for actor profiling.

ID | Technique | Weakness | Description | Confidence
-- | --------- | -------- | ----------- | ----------
1 | T1040 | CWE-294 | Authentication Bypass by Capture-replay | High
2 | T1059.007 | CWE-79, CWE-80 | Cross Site Scripting | High
3 | T1068 | CWE-264, CWE-284 | Execution with Unnecessary Privileges | High
4 | ... | ... | ... | ...

There are 9 more TTP items available. Please use our online service to access the data.

## IOA - Indicator of Attack

These _indicators of attack_ (IOA) list the potential fragments used for technical activities like reconnaissance, exploitation, privilege escalation, and exfiltration by xHunt. This data is unique as it uses our predictive model for actor profiling.

ID | Type | Indicator | Confidence
-- | ---- | --------- | ----------
1 | File | `/+CSCOE+/logon.html` | High
2 | File | `/../../conf/template/uhttpd.json` | High
3 | File | `/about.php` | Medium
4 | File | `/account/register` | High
5 | File | `/app1/admin#foo` | High
6 | File | `/articles/welcome-to-your-site#comments-head` | High
7 | File | `/assets/ctx` | Medium
8 | File | `/bin/boa` | Medium
9 | File | `/cgi?1&5` | Medium
10 | File | `/config/getuser` | High
11 | File | `/configs/application.ini` | High
12 | File | `/debug/pprof` | Medium
13 | File | `/etc/sudoers` | Medium
14 | File | `/export` | Low
15 | File | `/forum/away.php` | High
16 | File | `/gracemedia-media-player/templates/files/ajax_controller.php` | High
17 | File | `/iissamples` | Medium
18 | File | `/index.pl` | Medium
19 | File | `/login` | Low
20 | File | `/public/plugins/` | High
21 | File | `/sbin/gs_config` | High
22 | File | `/settings` | Medium
23 | File | `/Storage/Emulated/0/Telegram/Telegram` | High
24 | File | `/uncpath/` | Medium
25 | File | `/Upload/admin/index.php?module=forum-management&action=add` | High
26 | File | `/uploads/dede` | High
27 | File | `/usr/bin/pkexec` | High
28 | File | `/usr/sbin/nagios` | High
29 | File | `/WEB-INF/web.xml` | High
30 | File | `/webman/info.cgi` | High
31 | File | `/wp-json/oembed/1.0/embed?url` | High
32 | File | `/wp-json/wc/v3/webhooks` | High
33 | File | `/_next` | Low
34 | File | `14all.cgi/14all-1.1.cgi/traffic.cgi/mrtg.cgi` | High
35 | File | `adclick.php` | Medium
36 | File | `admin.php?m=admin&c=site&a=save` | High
37 | File | `admin.php?page=languages` | High
38 | File | `admin/backupdb.php` | High
39 | File | `admin/bitrix.mpbuilder_step2.php` | High
40 | File | `admin/bitrix.xscan_worker.php` | High
41 | File | `admin/conf_users_edit.php` | High
42 | File | `admin/gb-dashboard-widget.php` | High
43 | File | `admin/mcart_xls_import.php` | High
44 | File | `admin/modules/tools/ip_history_logs.php` | High
45 | File | `admin/ops/reports/ops/news.php` | High
46 | File | `admin/orion.extfeedbackform_efbf_forms.php` | High
47 | ... | ... | ...

There are 405 more IOA items available (file, library, argument, input value, pattern, network port). Please use our online service to access the data.

## References

The following list contains _external sources_ which discuss the actor and the associated activities:

* https://unit42.paloaltonetworks.com/bumblebee-webshell-xhunt-campaign/
* https://unit42.paloaltonetworks.com/xhunt-campaign-backdoors/

## Literature

The following _articles_ explain our unique predictive cyber threat intelligence:

* [VulDB Cyber Threat Intelligence Documentation](https://vuldb.com/?kb.cti)
* [Cyber Threat Intelligence - Early Anticipation of Attacks](https://www.scip.ch/en/?labs.20201022)

## License

(c) [1997-2022](https://vuldb.com/?kb.changelog) by [vuldb.com](https://vuldb.com/?kb.about). All data on this page is shared under the license [CC BY-NC-SA 4.0](https://creativecommons.org/licenses/by-nc-sa/4.0/). Questions? Check the [FAQ](https://vuldb.com/?kb.faq), read the [documentation](https://vuldb.com/?kb) or [contact us](https://vuldb.com/?contact)!
