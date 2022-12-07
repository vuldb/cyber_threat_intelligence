# PsiXBot - Cyber Threat Intelligence

These _indicators_ were reported, collected, and generated during the [VulDB CTI analysis](https://vuldb.com/?kb.cti) of the actor known as [PsiXBot](https://vuldb.com/?actor.psixbot). The _activity monitoring_ correlates data from social media, forums, chat rooms, and darknet markets. It helps to determine associated actors, specific activities, expected intentions, emerging research, and ongoing attacks. Our unique _predictive model_ uses _big data_ to forecast activities and their characteristics.

_Live data_ and more _analysis capabilities_ are available at [https://vuldb.com/?actor.psixbot](https://vuldb.com/?actor.psixbot)

## Countries

These _countries_ are directly (e.g. origin of attacks) or indirectly (e.g. access by proxy) associated with PsiXBot:

* [US](https://vuldb.com/?country.us)
* [CN](https://vuldb.com/?country.cn)
* [ES](https://vuldb.com/?country.es)
* ...

There are 21 more country items available. Please use our online service to access the data.

## IOC - Indicator of Compromise

These _indicators of compromise_ (IOC) indicate associated network resources which are known to be part of research and attack activities of PsiXBot.

ID | IP address | Hostname | Campaign | Confidence
-- | ---------- | -------- | -------- | ----------
1 | [2.15.835.1](https://vuldb.com/?ip.2.15.835.1) | - | - | High
2 | [5.135.183.146](https://vuldb.com/?ip.5.135.183.146) | freya.stelas.de | - | High
3 | [5.154.191.67](https://vuldb.com/?ip.5.154.191.67) | - | - | High
4 | [14.42.81.85](https://vuldb.com/?ip.14.42.81.85) | - | - | High
5 | [31.3.135.232](https://vuldb.com/?ip.31.3.135.232) | mirror.tillo.ch | - | High
6 | [31.148.220.69](https://vuldb.com/?ip.31.148.220.69) | - | - | High
7 | [31.171.251.118](https://vuldb.com/?ip.31.171.251.118) | ch.ns.mon0.li | - | High
8 | [37.44.212.194](https://vuldb.com/?ip.37.44.212.194) | - | - | High
9 | [37.44.213.26](https://vuldb.com/?ip.37.44.213.26) | - | - | High
10 | [37.44.213.27](https://vuldb.com/?ip.37.44.213.27) | - | - | High
11 | [37.44.213.98](https://vuldb.com/?ip.37.44.213.98) | - | - | High
12 | [37.44.213.187](https://vuldb.com/?ip.37.44.213.187) | - | - | High
13 | [37.44.213.188](https://vuldb.com/?ip.37.44.213.188) | - | - | High
14 | [37.44.213.189](https://vuldb.com/?ip.37.44.213.189) | - | - | High
15 | ... | ... | ... | ...

There are 55 more IOC items available. Please use our online service to access the data.

## TTP - Tactics, Techniques, Procedures

_Tactics, techniques, and procedures_ (TTP) summarize the suspected MITRE ATT&CK techniques used by _PsiXBot_. This data is unique as it uses our predictive model for actor profiling.

ID | Technique | Weakness | Description | Confidence
-- | --------- | -------- | ----------- | ----------
1 | T1006 | CWE-21, CWE-22, CWE-23 | Pathname Traversal | High
2 | T1040 | CWE-294 | Authentication Bypass by Capture-replay | High
3 | T1055 | CWE-74 | Injection | High
4 | T1059 | CWE-88, CWE-94, CWE-1321 | Cross Site Scripting | High
5 | T1059.007 | CWE-79, CWE-80 | Cross Site Scripting | High
6 | ... | ... | ... | ...

There are 20 more TTP items available. Please use our online service to access the data.

## IOA - Indicator of Attack

These _indicators of attack_ (IOA) list the potential fragments used for technical activities like reconnaissance, exploitation, privilege escalation, and exfiltration by PsiXBot. This data is unique as it uses our predictive model for actor profiling.

ID | Type | Indicator | Confidence
-- | ---- | --------- | ----------
1 | File | `/admin/news/news_ok.php` | High
2 | File | `/api/plugin/uninstall` | High
3 | File | `/bcms/admin/?page=user/list` | High
4 | File | `/bin/boa` | Medium
5 | File | `/card_scan.php` | High
6 | File | `/cgi-bin/wlogin.cgi` | High
7 | File | `/config/getuser` | High
8 | File | `/cwc/login` | Medium
9 | File | `/de/cgi/dfs_guest/` | High
10 | File | `/debug/pprof` | Medium
11 | File | `/download` | Medium
12 | File | `/etc/gsissh/sshd_config` | High
13 | File | `/etc/passwd` | Medium
14 | File | `/etc/puppetlabs/puppetserver/conf.d/ca.conf` | High
15 | File | `/etc/quantum/quantum.conf` | High
16 | File | `/etc/shadow` | Medium
17 | File | `/forum/away.php` | High
18 | File | `/getcfg.php` | Medium
19 | File | `/goform/telnet` | High
20 | File | `/goform/WanParameterSetting` | High
21 | File | `/h/calendar` | Medium
22 | File | `/inc/extensions.php` | High
23 | File | `/include/makecvs.php` | High
24 | File | `/mgmt/tm/util/bash` | High
25 | File | `/modules/profile/index.php` | High
26 | File | `/modules/tasks/summary.inc.php` | High
27 | File | `/monitoring` | Medium
28 | File | `/nova/bin/console` | High
29 | File | `/nova/bin/detnet` | High
30 | File | `/out.php` | Medium
31 | File | `/payu/icpcheckout/` | High
32 | File | `/php-sms/classes/Master.php?f=save_quote` | High
33 | File | `/property-list/property_view.php` | High
34 | File | `/public/login.htm` | High
35 | File | `/req_password_user.php` | High
36 | File | `/rest/project-templates/1.0/createshared` | High
37 | File | `/rom-0` | Low
38 | File | `/secure/QueryComponent!Default.jspa` | High
39 | File | `/trx_addons/v2/get/sc_layout` | High
40 | File | `/uncpath/` | Medium
41 | File | `/usr/local/WowzaStreamingEngine/bin/` | High
42 | File | `/usr/syno/etc/mount.conf` | High
43 | File | `/var/WEB-GUI/cgi-bin/telnet.cgi` | High
44 | File | `/WEB-INF/web.xml` | High
45 | File | `/wp-json` | Medium
46 | File | `/_next` | Low
47 | File | `404.php` | Low
48 | File | `a-b-membres.php` | High
49 | File | `acropora/crypto/asn1_common.c` | High
50 | ... | ... | ...

There are 436 more IOA items available (file, library, argument, input value, pattern, network port). Please use our online service to access the data.

## References

The following list contains _external sources_ which discuss the actor and the associated activities:

* https://github.com/fox-it/psixbot/blob/master/c2_ips.txt
* https://github.com/fox-it/psixbot/blob/master/dns_servers.txt

## Literature

The following _articles_ explain our unique predictive cyber threat intelligence:

* [VulDB Cyber Threat Intelligence Documentation](https://vuldb.com/?kb.cti)
* [Cyber Threat Intelligence - Early Anticipation of Attacks](https://www.scip.ch/en/?labs.20201022)

## License

(c) [1997-2022](https://vuldb.com/?kb.changelog) by [vuldb.com](https://vuldb.com/?kb.about). All data on this page is shared under the license [CC BY-NC-SA 4.0](https://creativecommons.org/licenses/by-nc-sa/4.0/). Questions? Check the [FAQ](https://vuldb.com/?kb.faq), read the [documentation](https://vuldb.com/?kb) or [contact us](https://vuldb.com/?contact)!
