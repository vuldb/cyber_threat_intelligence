# ERMAC - Cyber Threat Intelligence

These _indicators_ were reported, collected, and generated during the [VulDB CTI analysis](https://vuldb.com/?kb.cti) of the actor known as [ERMAC](https://vuldb.com/?actor.ermac). The _activity monitoring_ correlates data from social media, forums, chat rooms, and darknet markets. It helps to determine associated actors, specific activities, expected intentions, emerging research, and ongoing attacks. Our unique _predictive model_ uses _big data_ to forecast activities and their characteristics.

_Live data_ and more _analysis capabilities_ are available at [https://vuldb.com/?actor.ermac](https://vuldb.com/?actor.ermac)

## Countries

These _countries_ are directly (e.g. origin of attacks) or indirectly (e.g. access by proxy) associated with ERMAC:

* [CN](https://vuldb.com/?country.cn)
* [US](https://vuldb.com/?country.us)
* [RU](https://vuldb.com/?country.ru)
* ...

There are 12 more country items available. Please use our online service to access the data.

## IOC - Indicator of Compromise

These _indicators of compromise_ (IOC) indicate associated network resources which are known to be part of research and attack activities of ERMAC.

ID | IP address | Hostname | Campaign | Confidence
-- | ---------- | -------- | -------- | ----------
1 | [5.42.199.3](https://vuldb.com/?ip.5.42.199.3) | - | - | High
2 | [5.42.199.22](https://vuldb.com/?ip.5.42.199.22) | - | - | High
3 | [5.42.199.91](https://vuldb.com/?ip.5.42.199.91) | - | - | High
4 | [5.182.87.142](https://vuldb.com/?ip.5.182.87.142) | showy-push.aeza.network | - | High
5 | [20.108.0.165](https://vuldb.com/?ip.20.108.0.165) | - | - | High
6 | [20.210.252.118](https://vuldb.com/?ip.20.210.252.118) | - | - | High
7 | [20.249.63.72](https://vuldb.com/?ip.20.249.63.72) | - | - | High
8 | [31.41.244.187](https://vuldb.com/?ip.31.41.244.187) | - | - | High
9 | [35.90.154.240](https://vuldb.com/?ip.35.90.154.240) | ec2-35-90-154-240.us-west-2.compute.amazonaws.com | - | Medium
10 | [35.91.53.224](https://vuldb.com/?ip.35.91.53.224) | ec2-35-91-53-224.us-west-2.compute.amazonaws.com | - | Medium
11 | [38.242.209.185](https://vuldb.com/?ip.38.242.209.185) | vmi1543263.contaboserver.net | - | High
12 | [43.129.215.239](https://vuldb.com/?ip.43.129.215.239) | - | - | High
13 | [45.77.68.120](https://vuldb.com/?ip.45.77.68.120) | 45.77.68.120.vultrusercontent.com | - | High
14 | [45.93.201.92](https://vuldb.com/?ip.45.93.201.92) | - | - | High
15 | [45.141.85.25](https://vuldb.com/?ip.45.141.85.25) | - | - | High
16 | ... | ... | ... | ...

There are 62 more IOC items available. Please use our online service to access the data.

## TTP - Tactics, Techniques, Procedures

_Tactics, techniques, and procedures_ (TTP) summarize the suspected MITRE ATT&CK techniques used by _ERMAC_. This data is unique as it uses our predictive model for actor profiling.

ID | Technique | Weakness | Description | Confidence
-- | --------- | -------- | ----------- | ----------
1 | T1006 | CWE-21, CWE-22, CWE-23, CWE-24 | Pathname Traversal | High
2 | T1040 | CWE-294, CWE-319 | Authentication Bypass by Capture-replay | High
3 | T1055 | CWE-74 | Injection | High
4 | T1059 | CWE-88, CWE-94, CWE-1321 | Cross Site Scripting | High
5 | T1059.007 | CWE-79, CWE-80 | Cross Site Scripting | High
6 | ... | ... | ... | ...

There are 20 more TTP items available. Please use our online service to access the data.

## IOA - Indicator of Attack

These _indicators of attack_ (IOA) list the potential fragments used for technical activities like reconnaissance, exploitation, privilege escalation, and exfiltration by ERMAC. This data is unique as it uses our predictive model for actor profiling.

ID | Type | Indicator | Confidence
-- | ---- | --------- | ----------
1 | File | `/?p=products` | Medium
2 | File | `/admin.php/accessory/filesdel.html` | High
3 | File | `/admin.php/admin/vod/data.html` | High
4 | File | `/admin/?page=user/manage` | High
5 | File | `/admin/add-new.php` | High
6 | File | `/admin/controller/JobLogController.java` | High
7 | File | `/admin/doctors.php` | High
8 | File | `/admin/index.php` | High
9 | File | `/alphaware/summary.php` | High
10 | File | `/api/` | Low
11 | File | `/api/admin/store/product/list` | High
12 | File | `/api/baskets/{name}` | High
13 | File | `/api/stl/actions/search` | High
14 | File | `/api/sys/login` | High
15 | File | `/api/sys/set_passwd` | High
16 | File | `/api/trackedEntityInstances` | High
17 | File | `/api/v2/cli/commands` | High
18 | File | `/app/options.py` | High
19 | File | `/aux` | Low
20 | File | `/bin/ate` | Medium
21 | File | `/boat/login.php` | High
22 | File | `/booking/show_bookings/` | High
23 | File | `/cgi-bin` | Medium
24 | File | `/cgi-bin/viewcert` | High
25 | File | `/cgi-bin/wlogin.cgi` | High
26 | File | `/changePassword` | High
27 | File | `/Content/Template/root/reverse-shell.aspx` | High
28 | File | `/cstecgi.cgi` | Medium
29 | File | `/dashboard/add-blog.php` | High
30 | File | `/data/remove` | Medium
31 | File | `/debug/pprof` | Medium
32 | File | `/ecshop/admin/template.php` | High
33 | File | `/env` | Low
34 | File | `/film-rating.php` | High
35 | File | `/forms/doLogin` | High
36 | File | `/forum/away.php` | High
37 | File | `/forum/PostPrivateMessage` | High
38 | File | `/group1/uploa` | High
39 | File | `/home/masterConsole` | High
40 | File | `/index.php` | Medium
41 | File | `/librarian/bookdetails.php` | High
42 | File | `/nagiosxi/admin/banner_message-ajaxhelper.php` | High
43 | File | `/php-sms/admin/?page=user/manage_user` | High
44 | File | `/reservation/add_message.php` | High
45 | File | `/resources//../` | High
46 | File | `/rom-0` | Low
47 | File | `/ServletAPI/accounts/login` | High
48 | File | `/spip.php` | Medium
49 | File | `/student/bookdetails.php` | High
50 | File | `/testConnection` | High
51 | File | `/tmp/ppd.trace` | High
52 | File | `/user/updatePwd` | High
53 | File | `/userLogin.asp` | High
54 | File | `/vendor/htmlawed/htmlawed/htmLawedTest.php` | High
55 | File | `/video-sharing-script/watch-video.php` | High
56 | File | `/vm/admin/doctors.php` | High
57 | File | `/wireless/security.asp` | High
58 | File | `/wp-admin/admin-ajax.php` | High
59 | File | `/wp-content/plugins/woocommerce/templates/emails/plain/` | High
60 | File | `Access.app/Contents/Resources/kcproxy` | High
61 | ... | ... | ...

There are 531 more IOA items available (file, library, argument, input value, pattern, network port). Please use our online service to access the data.

## References

The following list contains _external sources_ which discuss the actor and the associated activities:

* https://community.blueliv.com/#!/s/6290743382df41552632f5fe
* https://research.nccgroup.com/2023/09/11/from-ermac-to-hook-investigating-the-technical-differences-between-two-android-malware-variants/
* https://search.censys.io/hosts/5.182.87.142
* https://search.censys.io/hosts/64.227.41.169
* https://search.censys.io/hosts/77.91.68.183
* https://search.censys.io/hosts/77.105.146.199
* https://search.censys.io/hosts/82.147.85.136
* https://search.censys.io/hosts/88.99.210.25
* https://search.censys.io/hosts/91.92.246.222
* https://search.censys.io/hosts/91.92.252.193
* https://search.censys.io/hosts/94.131.111.119
* https://search.censys.io/hosts/178.236.246.210
* https://search.censys.io/hosts/193.222.96.25
* https://search.censys.io/hosts/193.233.255.253
* https://search.censys.io/hosts/194.33.191.202
* https://threatfox.abuse.ch
* https://tracker.viriback.com/index.php?q=91.92.251.71
* https://twitter.com/0xrb/status/1564222855830597632
* https://twitter.com/ReBensk/status/1695321207766127094
* https://www.threatfabric.com/blogs/ermac-another-cerberus-reborn.html
* https://www.trendmicro.com/de_de/research/22/g/examining-new-dawdropper-banking-dropper-and-daas-on-the-dark-we.html
* https://www.virustotal.com/gui/file/f642d2c6a70828028e0f3f7e9b9a87537c6556870cdf4602ee992091040a1850/detection

## Literature

The following _articles_ explain our unique predictive cyber threat intelligence:

* [VulDB Cyber Threat Intelligence Documentation](https://vuldb.com/?kb.cti)
* [Cyber Threat Intelligence - Early Anticipation of Attacks](https://www.scip.ch/en/?labs.20201022)

## License

(c) [1997-2024](https://vuldb.com/?kb.changelog) by [vuldb.com](https://vuldb.com/?kb.about). All data on this page is shared under the license [CC BY-NC-SA 4.0](https://creativecommons.org/licenses/by-nc-sa/4.0/). Questions? Check the [FAQ](https://vuldb.com/?kb.faq), read the [documentation](https://vuldb.com/?kb) or [contact us](https://vuldb.com/?contact)!
