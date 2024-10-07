# Gootloader - Cyber Threat Intelligence

These _indicators_ were reported, collected, and generated during the [VulDB CTI analysis](https://vuldb.com/?kb.cti) of the actor known as [Gootloader](https://vuldb.com/?actor.gootloader). The _activity monitoring_ correlates data from social media, forums, chat rooms, and darknet markets. It helps to determine associated actors, specific activities, expected intentions, emerging research, and ongoing attacks. Our unique _predictive model_ uses _big data_ to forecast activities and their characteristics.

_Live data_ and more _analysis capabilities_ are available at [https://vuldb.com/?actor.gootloader](https://vuldb.com/?actor.gootloader)

## Campaigns

The following _campaigns_ are known and can be associated with Gootloader:

* Cobalt Strike

## Countries

These _countries_ are directly (e.g. origin of attacks) or indirectly (e.g. access by proxy) associated with Gootloader:

* [ES](https://vuldb.com/?country.es)
* [RU](https://vuldb.com/?country.ru)
* [US](https://vuldb.com/?country.us)
* ...

There are 14 more country items available. Please use our online service to access the data.

## IOC - Indicator of Compromise

These _indicators of compromise_ (IOC) indicate associated network resources which are known to be part of research and attack activities of Gootloader.

ID | IP address | Hostname | Campaign | Confidence
-- | ---------- | -------- | -------- | ----------
1 | [5.8.18.7](https://vuldb.com/?ip.5.8.18.7) | - | - | High
2 | [35.206.117.64](https://vuldb.com/?ip.35.206.117.64) | 64.117.206.35.bc.googleusercontent.com | - | Medium
3 | [44.242.99.40](https://vuldb.com/?ip.44.242.99.40) | ec2-44-242-99-40.us-west-2.compute.amazonaws.com | - | Medium
4 | [45.150.108.213](https://vuldb.com/?ip.45.150.108.213) | mail.i-likefood.co | Cobalt Strike | High
5 | [46.4.197.237](https://vuldb.com/?ip.46.4.197.237) | server4.one3erver.com | - | High
6 | [52.42.122.102](https://vuldb.com/?ip.52.42.122.102) | ec2-52-42-122-102.us-west-2.compute.amazonaws.com | - | Medium
7 | [54.39.18.111](https://vuldb.com/?ip.54.39.18.111) | orion.privatedns.com.br | - | High
8 | ... | ... | ... | ...

There are 30 more IOC items available. Please use our online service to access the data.

## TTP - Tactics, Techniques, Procedures

_Tactics, techniques, and procedures_ (TTP) summarize the suspected MITRE ATT&CK techniques used by _Gootloader_. This data is unique as it uses our predictive model for actor profiling.

ID | Technique | Weakness | Description | Confidence
-- | --------- | -------- | ----------- | ----------
1 | T1006 | CWE-21, CWE-22, CWE-23 | Path Traversal | High
2 | T1040 | CWE-294, CWE-319 | Authentication Bypass by Capture-replay | High
3 | T1055 | CWE-74 | Improper Neutralization of Data within XPath Expressions | High
4 | T1059 | CWE-94 | Argument Injection | High
5 | T1059.007 | CWE-79, CWE-80 | Cross Site Scripting | High
6 | ... | ... | ... | ...

There are 22 more TTP items available. Please use our online service to access the data.

## IOA - Indicator of Attack

These _indicators of attack_ (IOA) list the potential fragments used for technical activities like reconnaissance, exploitation, privilege escalation, and exfiltration by Gootloader. This data is unique as it uses our predictive model for actor profiling.

ID | Type | Indicator | Confidence
-- | ---- | --------- | ----------
1 | File | `.config/Yubico` | High
2 | File | `/admin/SensitiveWords` | High
3 | File | `/admin/sign/out` | High
4 | File | `/backupsettings.conf` | High
5 | File | `/cgi-bin/kerbynet` | High
6 | File | `/cgi-bin/return.cgi` | High
7 | File | `/checkLogin.cgi` | High
8 | File | `/csms/admin/?page=user/list` | High
9 | File | `/depotHead/list` | High
10 | File | `/etc/postfix/sender_login` | High
11 | File | `/forms/web_importTFTP` | High
12 | File | `/framework/modules/users/models/user.php` | High
13 | File | `/goform/openSchedWifi` | High
14 | File | `/HNAP1` | Low
15 | File | `/Home/GetAttachment` | High
16 | File | `/lesson/controller.php` | High
17 | File | `/mkshope/login.php` | High
18 | File | `/model/viewProduct.php` | High
19 | File | `/objects/getImageMP4.php` | High
20 | File | `/objects/getSpiritsFromVideo.php` | High
21 | File | `/payu/icpcheckout/` | High
22 | File | `/php_action/createUser.php` | High
23 | File | `/rest/review-coverage-chart/1.0/data/<repository_name>/.json` | High
24 | File | `/see_more_details.php` | High
25 | File | `/show_news.php` | High
26 | File | `/src/jfif.c` | Medium
27 | File | `/tracking/admin/view_itprofile.php` | High
28 | File | `/tracking/nbproject/` | High
29 | File | `/uncpath/` | Medium
30 | File | `/usr/local/www/pkg.php` | High
31 | File | `/v1/continue` | Medium
32 | File | `/v1/tokens` | Medium
33 | File | `/web/Public/Conn.php` | High
34 | File | `/www/cgi-bin/cstecgi.cgi` | High
35 | File | `adaptive-images-script.php` | High
36 | File | `admin.php` | Medium
37 | File | `admin/backupdb.php` | High
38 | File | `admin/getparam.cgi` | High
39 | ... | ... | ...

There are 338 more IOA items available (file, library, argument, input value, pattern, network port). Please use our online service to access the data.

## References

The following list contains _external sources_ which discuss the actor and the associated activities:

* https://fieldeffect.com/blog/sample-templates-targeted-in-recent-gootloader-campaign
* https://github.com/sophoslabs/IoCs/blob/master/Troj-gootloader.csv
* https://socradar.io/new-gootloader-variant-gootbot-changes-the-game-in-malware-tactics/
* https://thedfirreport.com/2022/05/09/seo-poisoning-a-gootloader-story/
* https://threatfox.abuse.ch
* https://tria.ge/220104-dp6htaadcn

## Literature

The following _articles_ explain our unique predictive cyber threat intelligence:

* [VulDB Cyber Threat Intelligence Documentation](https://vuldb.com/?kb.cti)
* [Cyber Threat Intelligence - Early Anticipation of Attacks](https://www.scip.ch/en/?labs.20201022)

## License

(c) [1997-2024](https://vuldb.com/?kb.changelog) by [vuldb.com](https://vuldb.com/?kb.about). All data on this page is shared under the license [CC BY-NC-SA 4.0](https://creativecommons.org/licenses/by-nc-sa/4.0/). Questions? Check the [FAQ](https://vuldb.com/?kb.faq), read the [documentation](https://vuldb.com/?kb) or [contact us](https://vuldb.com/?contact)!
