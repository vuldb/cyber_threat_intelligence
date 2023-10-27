# PsiXBot - Cyber Threat Intelligence

These _indicators_ were reported, collected, and generated during the [VulDB CTI analysis](https://vuldb.com/?kb.cti) of the actor known as [PsiXBot](https://vuldb.com/?actor.psixbot). The _activity monitoring_ correlates data from social media, forums, chat rooms, and darknet markets. It helps to determine associated actors, specific activities, expected intentions, emerging research, and ongoing attacks. Our unique _predictive model_ uses _big data_ to forecast activities and their characteristics.

_Live data_ and more _analysis capabilities_ are available at [https://vuldb.com/?actor.psixbot](https://vuldb.com/?actor.psixbot)

## Countries

These _countries_ are directly (e.g. origin of attacks) or indirectly (e.g. access by proxy) associated with PsiXBot:

* [US](https://vuldb.com/?country.us)
* [CN](https://vuldb.com/?country.cn)
* [GB](https://vuldb.com/?country.gb)
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
1 | T1006 | CWE-21, CWE-22, CWE-23, CWE-24 | Pathname Traversal | High
2 | T1040 | CWE-294 | Authentication Bypass by Capture-replay | High
3 | T1055 | CWE-74 | Injection | High
4 | T1059 | CWE-88, CWE-94, CWE-1321 | Cross Site Scripting | High
5 | T1059.007 | CWE-79, CWE-80 | Cross Site Scripting | High
6 | ... | ... | ... | ...

There are 22 more TTP items available. Please use our online service to access the data.

## IOA - Indicator of Attack

These _indicators of attack_ (IOA) list the potential fragments used for technical activities like reconnaissance, exploitation, privilege escalation, and exfiltration by PsiXBot. This data is unique as it uses our predictive model for actor profiling.

ID | Type | Indicator | Confidence
-- | ---- | --------- | ----------
1 | File | `$HOME/.printers` | High
2 | File | `/admin/?page=user/list` | High
3 | File | `/admin/add-services.php` | High
4 | File | `/admin/add_user_modal.php` | High
5 | File | `/admin/admin-profile.php` | High
6 | File | `/admin/ajax.php?action=confirm_order` | High
7 | File | `/admin/edit-doc.php` | High
8 | File | `/admin/maintenance/view_designation.php` | High
9 | File | `/admin/news/news_ok.php` | High
10 | File | `/admin/service.php` | High
11 | File | `/admin/sys_sql_query.php` | High
12 | File | `/ajax.php?action=read_msg` | High
13 | File | `/api/ping` | Medium
14 | File | `/api/plugin/uninstall` | High
15 | File | `/api /v3/auth` | High
16 | File | `/bcms/admin/?page=user/list` | High
17 | File | `/blog` | Low
18 | File | `/blog-single.php` | High
19 | File | `/card_scan.php` | High
20 | File | `/cgi-bin/adm.cgi` | High
21 | File | `/cgi-bin/jumpto.php?class=user&page=config_save&isphp=1` | High
22 | File | `/cgi-bin/koha/catalogue/search.pl` | High
23 | File | `/cgi-bin/wlogin.cgi` | High
24 | File | `/classes/Master.php?f=save_inquiry` | High
25 | File | `/collection/all` | High
26 | File | `/config/getuser` | High
27 | File | `/cwc/login` | Medium
28 | File | `/de/cgi/dfs_guest/` | High
29 | File | `/debug/pprof` | Medium
30 | File | `/download` | Medium
31 | File | `/Duty/AjaxHandle/UpLoadFloodPlanFile.ashx` | High
32 | File | `/Duty/AjaxHandle/UploadHandler.ashx` | High
33 | File | `/etc/gsissh/sshd_config` | High
34 | File | `/etc/puppetlabs/puppetserver/conf.d/ca.conf` | High
35 | File | `/etc/quagga` | Medium
36 | File | `/etc/quantum/quantum.conf` | High
37 | File | `/forms/doLogin` | High
38 | File | `/forum/away.php` | High
39 | File | `/goform/SetNetControlList` | High
40 | File | `/goform/telnet` | High
41 | File | `/goform/WanParameterSetting` | High
42 | File | `/h/calendar` | Medium
43 | File | `/home/cavesConsole` | High
44 | File | `/hrm/employeeadd.php` | High
45 | File | `/inc/extensions.php` | High
46 | File | `/include/makecvs.php` | High
47 | File | `/index.php` | Medium
48 | File | `/jeecg-boot/jmreport/upload` | High
49 | File | `/js/app.js` | Medium
50 | File | `/listplace/user/ticket/create` | High
51 | File | `/load.php` | Medium
52 | File | `/mail.php` | Medium
53 | File | `/mgmt/tm/util/bash` | High
54 | File | `/modules/profile/index.php` | High
55 | File | `/modules/tasks/summary.inc.php` | High
56 | ... | ... | ...

There are 485 more IOA items available (file, library, argument, input value, pattern, network port). Please use our online service to access the data.

## References

The following list contains _external sources_ which discuss the actor and the associated activities:

* https://github.com/fox-it/psixbot/blob/master/c2_ips.txt
* https://github.com/fox-it/psixbot/blob/master/dns_servers.txt

## Literature

The following _articles_ explain our unique predictive cyber threat intelligence:

* [VulDB Cyber Threat Intelligence Documentation](https://vuldb.com/?kb.cti)
* [Cyber Threat Intelligence - Early Anticipation of Attacks](https://www.scip.ch/en/?labs.20201022)

## License

(c) [1997-2023](https://vuldb.com/?kb.changelog) by [vuldb.com](https://vuldb.com/?kb.about). All data on this page is shared under the license [CC BY-NC-SA 4.0](https://creativecommons.org/licenses/by-nc-sa/4.0/). Questions? Check the [FAQ](https://vuldb.com/?kb.faq), read the [documentation](https://vuldb.com/?kb) or [contact us](https://vuldb.com/?contact)!
