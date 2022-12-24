# Nanocore - Cyber Threat Intelligence

These _indicators_ were reported, collected, and generated during the [VulDB CTI analysis](https://vuldb.com/?kb.cti) of the actor known as [Nanocore](https://vuldb.com/?actor.nanocore). The _activity monitoring_ correlates data from social media, forums, chat rooms, and darknet markets. It helps to determine associated actors, specific activities, expected intentions, emerging research, and ongoing attacks. Our unique _predictive model_ uses _big data_ to forecast activities and their characteristics.

_Live data_ and more _analysis capabilities_ are available at [https://vuldb.com/?actor.nanocore](https://vuldb.com/?actor.nanocore)

## Campaigns

The following _campaigns_ are known and can be associated with Nanocore:

* Tax-Themed Phishing

## Countries

These _countries_ are directly (e.g. origin of attacks) or indirectly (e.g. access by proxy) associated with Nanocore:

* [US](https://vuldb.com/?country.us)
* [FR](https://vuldb.com/?country.fr)
* [CN](https://vuldb.com/?country.cn)
* ...

There are 12 more country items available. Please use our online service to access the data.

## IOC - Indicator of Compromise

These _indicators of compromise_ (IOC) indicate associated network resources which are known to be part of research and attack activities of Nanocore.

ID | IP address | Hostname | Campaign | Confidence
-- | ---------- | -------- | -------- | ----------
1 | [8.8.8.8](https://vuldb.com/?ip.8.8.8.8) | dns.google | - | High
2 | [20.42.65.92](https://vuldb.com/?ip.20.42.65.92) | - | - | High
3 | [23.221.227.169](https://vuldb.com/?ip.23.221.227.169) | a23-221-227-169.deploy.static.akamaitechnologies.com | - | High
4 | [23.230.152.134](https://vuldb.com/?ip.23.230.152.134) | - | - | High
5 | [23.235.221.158](https://vuldb.com/?ip.23.235.221.158) | vps53141.inmotionhosting.com | Tax-Themed Phishing | High
6 | [31.31.196.51](https://vuldb.com/?ip.31.31.196.51) | server222.hosting.reg.ru | - | High
7 | [34.102.136.180](https://vuldb.com/?ip.34.102.136.180) | 180.136.102.34.bc.googleusercontent.com | - | Medium
8 | [34.117.168.233](https://vuldb.com/?ip.34.117.168.233) | 233.168.117.34.bc.googleusercontent.com | - | Medium
9 | [38.6.77.91](https://vuldb.com/?ip.38.6.77.91) | - | - | High
10 | [45.33.6.223](https://vuldb.com/?ip.45.33.6.223) | sqlite.org | - | High
11 | [45.77.55.161](https://vuldb.com/?ip.45.77.55.161) | 45.77.55.161.vultrusercontent.com | - | High
12 | [45.133.174.131](https://vuldb.com/?ip.45.133.174.131) | - | - | High
13 | [54.91.59.199](https://vuldb.com/?ip.54.91.59.199) | ec2-54-91-59-199.compute-1.amazonaws.com | - | Medium
14 | [64.190.63.111](https://vuldb.com/?ip.64.190.63.111) | - | - | High
15 | [66.96.160.130](https://vuldb.com/?ip.66.96.160.130) | 130.160.96.66.static.eigbox.net | - | High
16 | [74.139.80.187](https://vuldb.com/?ip.74.139.80.187) | cpe-74-139-80-187.kya.res.rr.com | - | High
17 | [75.2.26.18](https://vuldb.com/?ip.75.2.26.18) | a6b5b419953ac02a6.awsglobalaccelerator.com | - | High
18 | ... | ... | ... | ...

There are 69 more IOC items available. Please use our online service to access the data.

## TTP - Tactics, Techniques, Procedures

_Tactics, techniques, and procedures_ (TTP) summarize the suspected MITRE ATT&CK techniques used by _Nanocore_. This data is unique as it uses our predictive model for actor profiling.

ID | Technique | Weakness | Description | Confidence
-- | --------- | -------- | ----------- | ----------
1 | T1006 | CWE-22 | Pathname Traversal | High
2 | T1040 | CWE-319 | Authentication Bypass by Capture-replay | High
3 | T1055 | CWE-74 | Injection | High
4 | T1059 | CWE-88, CWE-94 | Cross Site Scripting | High
5 | ... | ... | ... | ...

There are 17 more TTP items available. Please use our online service to access the data.

## IOA - Indicator of Attack

These _indicators of attack_ (IOA) list the potential fragments used for technical activities like reconnaissance, exploitation, privilege escalation, and exfiltration by Nanocore. This data is unique as it uses our predictive model for actor profiling.

ID | Type | Indicator | Confidence
-- | ---- | --------- | ----------
1 | File | `/cgi/ansi` | Medium
2 | File | `/etc/password` | High
3 | File | `/etc/sudoers` | Medium
4 | File | `/forum/away.php` | High
5 | File | `/iissamples` | Medium
6 | File | `/php/` | Low
7 | File | `/php_action/createUser.php` | High
8 | File | `/Pwrchute` | Medium
9 | File | `/secure/admin/RestoreDefaults.jspa` | High
10 | File | `/services/details.asp` | High
11 | File | `/uncpath/` | Medium
12 | File | `/var/yp` | Low
13 | File | `/webapps/blogs-journals/execute/editBlogEntry` | High
14 | File | `/_vti_pvt/access.cnf` | High
15 | File | `14all.cgi` | Medium
16 | File | `500error.jsp` | Medium
17 | File | `ab.c` | Low
18 | File | `account_update.php` | High
19 | File | `adclick.php` | Medium
20 | File | `add.php` | Low
21 | File | `addentry.php` | Medium
22 | File | `additem.asp` | Medium
23 | File | `addressbook.php/options.php/search.php/help.php` | High
24 | File | `admin/password_forgotten.php` | High
25 | File | `admin_ug_auth.php` | High
26 | File | `advserver.exe` | High
27 | File | `aolsecurityprivate.class` | High
28 | File | `astrocam.cgi` | Medium
29 | File | `as_web.exe/as_web4.exe` | High
30 | File | `auction.cgi` | Medium
31 | File | `books.php` | Medium
32 | File | `browser.php` | Medium
33 | File | `browser/liferay/browser.html?Type` | High
34 | File | `bttv-driver.c` | High
35 | File | `bugzilla_email_append.pl` | High
36 | File | `bug_update_advanced_page.php/bug_update_page.php/view_bug_advanced_page.php/view_bug_page.php` | High
37 | File | `calendar.php` | Medium
38 | File | `cat.php` | Low
39 | File | `catalog.asp` | Medium
40 | File | `cgi-bin` | Low
41 | File | `cgicso.c` | Medium
42 | File | `charities.cron` | High
43 | File | `check_me.mod.php` | High
44 | File | `cio_main.c` | Medium
45 | File | `clients/resources/ajax/ajax_new_admin.php` | High
46 | File | `cloud.php` | Medium
47 | ... | ... | ...

There are 410 more IOA items available (file, library, argument, input value, pattern, network port). Please use our online service to access the data.

## References

The following list contains _external sources_ which discuss the actor and the associated activities:

* https://blog.talosintelligence.com/2019/09/threat-roundup-0913-0920.html
* https://blog.talosintelligence.com/2021/07/threat-roundup-0716-0723.html
* https://blog.talosintelligence.com/2021/12/threat-roundup-1126-1203.html
* https://blog.talosintelligence.com/2022/04/threat-roundup-0401-0408.html
* https://blog.talosintelligence.com/2022/07/threat-roundup-0715-0722.html
* https://blog.talosintelligence.com/2022/08/threat-roundup-0812-0819.html
* https://blog.talosintelligence.com/2022/09/threat-roundup-0826-0902.html
* https://blog.talosintelligence.com/2022/09/threat-roundup-0909-0916.html
* https://blog.talosintelligence.com/2022/09/threat-roundup-0916-0923.html
* https://blog.talosintelligence.com/threat-roundup-1021-1028-2/
* https://blog.talosintelligence.com/threat-roundup-1028-1104/
* https://github.com/executemalware/Malware-IOCs/blob/main/2022-01-12%20Remcos%20IOCs
* https://github.com/executemalware/Malware-IOCs/blob/main/2022-02-15%20Nanocore%20IOCs
* https://isc.sans.edu/forums/diary/Malspam+delivers+NanoCore+RAT/21615/
* https://unit42.paloaltonetworks.com/nanocorerat-behind-an-increase-in-tax-themed-phishing-e-mails/

## Literature

The following _articles_ explain our unique predictive cyber threat intelligence:

* [VulDB Cyber Threat Intelligence Documentation](https://vuldb.com/?kb.cti)
* [Cyber Threat Intelligence - Early Anticipation of Attacks](https://www.scip.ch/en/?labs.20201022)

## License

(c) [1997-2022](https://vuldb.com/?kb.changelog) by [vuldb.com](https://vuldb.com/?kb.about). All data on this page is shared under the license [CC BY-NC-SA 4.0](https://creativecommons.org/licenses/by-nc-sa/4.0/). Questions? Check the [FAQ](https://vuldb.com/?kb.faq), read the [documentation](https://vuldb.com/?kb) or [contact us](https://vuldb.com/?contact)!
