# PsiXBot - Cyber Threat Intelligence

These _indicators_ were collected during the [VulDB CTI analysis](https://vuldb.com/?kb.cti) of the actor known as [PsiXBot](https://vuldb.com/?actor.psixbot). The _activity monitoring_ correlates data from social media, forums, chat rooms, and darknet markets. It helps to determine associated actors, specific activities, expected intentions, emerging research, and ongoing attacks. Our unique _predictive model_ is able to forecast activities and their characteristics.

_Live data_ and more _analysis capabilities_ are available at [https://vuldb.com/?actor.psixbot](https://vuldb.com/?actor.psixbot)

## Countries

These _countries_ are directly (e.g. origin of attacks) or indirectly (e.g. access by proxy) associated with PsiXBot:

* US
* CN
* DE
* ...

There are 18 more country items available. Please use our online service to access the data.

## IOC - Indicator of Compromise

These _indicators of compromise_ (IOC) indicate associated network resources which are known to be part of research and attack activities of PsiXBot.

ID | IP address | Hostname | Campaign | Confidence
-- | ---------- | -------- | -------- | ----------
1 | 2.15.835.1 | - | - | High
2 | 5.135.183.146 | freya.stelas.de | - | High
3 | 5.154.191.67 | - | - | High
4 | 14.42.81.85 | - | - | High
5 | 31.3.135.232 | mirror.tillo.ch | - | High
6 | 31.148.220.69 | - | - | High
7 | 31.171.251.118 | ch.ns.mon0.li | - | High
8 | 37.44.212.194 | - | - | High
9 | 37.44.213.26 | - | - | High
10 | 37.44.213.27 | - | - | High
11 | 37.44.213.98 | - | - | High
12 | 37.44.213.187 | - | - | High
13 | 37.44.213.188 | - | - | High
14 | 37.44.213.189 | - | - | High
15 | ... | ... | ... | ...

There are 55 more IOC items available. Please use our online service to access the data.

## TTP - Tactics, Techniques, Procedures

_Tactics, techniques, and procedures_ (TTP) summarize the suspected ATT&CK techniques used by PsiXBot. This data is unique as it uses our predictive model for actor profiling.

ID | Technique | Weakness | Description | Confidence
-- | --------- | -------- | ----------- | ----------
1 | T1059.007 | CWE-79, CWE-80 | Cross Site Scripting | High
2 | T1068 | CWE-264, CWE-284 | Execution with Unnecessary Privileges | High
3 | T1110.001 | CWE-798 | Improper Restriction of Excessive Authentication Attempts | High
4 | ... | ... | ... | ...

There are 7 more TTP items available. Please use our online service to access the data.

## IOA - Indicator of Attack

These _indicators of attack_ (IOA) list the potential fragments used for technical activities like reconnaissance, exploitation, privilege escalation, and exfiltration by PsiXBot. This data is unique as it uses our predictive model for actor profiling.

ID | Type | Indicator | Confidence
-- | ---- | --------- | ----------
1 | File | `/?Page=Node/OBJ=/System/DeviceFolder/DeviceFolder/DateTime/Action=Submit` | High
2 | File | `/bin/boa` | Medium
3 | File | `/config/getuser` | High
4 | File | `/de/cgi/dfs_guest/` | High
5 | File | `/download` | Medium
6 | File | `/etc/gsissh/sshd_config` | High
7 | File | `/etc/passwd` | Medium
8 | File | `/etc/quantum/quantum.conf` | High
9 | File | `/etc/shadow` | Medium
10 | File | `/forum/away.php` | High
11 | File | `/getcfg.php` | Medium
12 | File | `/goform/telnet` | High
13 | File | `/goform/WanParameterSetting` | High
14 | File | `/inc/extensions.php` | High
15 | File | `/include/makecvs.php` | High
16 | File | `/modules/profile/index.php` | High
17 | File | `/modules/tasks/summary.inc.php` | High
18 | File | `/payu/icpcheckout/` | High
19 | File | `/property-list/property_view.php` | High
20 | File | `/public/login.htm` | High
21 | File | `/req_password_user.php` | High
22 | File | `/resourceNode/jdbcResourceEdit.jsf` | High
23 | File | `/resourceNode/resources.jsf` | High
24 | File | `/rest/project-templates/1.0/createshared` | High
25 | File | `/rom-0` | Low
26 | File | `/secure/QueryComponent!Default.jspa` | High
27 | File | `/trx_addons/v2/get/sc_layout` | High
28 | File | `/uncpath/` | Medium
29 | File | `/usr/local/WowzaStreamingEngine/bin/` | High
30 | File | `/usr/syno/etc/mount.conf` | High
31 | File | `/var/log/nginx` | High
32 | File | `/var/WEB-GUI/cgi-bin/telnet.cgi` | High
33 | File | `/WEB-INF/web.xml` | High
34 | File | `/_next` | Low
35 | File | `3.6.cpj` | Low
36 | File | `404.php` | Low
37 | File | `a-b-membres.php` | High
38 | File | `ActionsAndOperations` | High
39 | File | `adclick.php` | Medium
40 | File | `add_2_basket.asp` | High
41 | File | `add_vhost.php` | High
42 | File | `admin.asp` | Medium
43 | File | `admin.aspx` | Medium
44 | File | `admin.php` | Medium
45 | File | `admin/aboutus.php` | High
46 | File | `admin/member_details.php` | High
47 | File | `admin_chatconfig.php` | High
48 | File | `ajaxp.php` | Medium
49 | File | `alphabet.php` | Medium
50 | File | `article2/comments.inc.php` | High
51 | File | `articles/edit.php` | High
52 | File | `assp.pl` | Low
53 | File | `auth-gss2.c` | Medium
54 | File | `authent.php4` | Medium
55 | ... | ... | ...

There are 478 more IOA items available (file, library, argument, input value, pattern, network port). Please use our online service to access the data.

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
