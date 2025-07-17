# Sandworm Team - Cyber Threat Intelligence

These _indicators_ were reported, collected, and generated during the [VulDB CTI analysis](https://vuldb.com/?kb.cti) of the actor known as [Sandworm Team](https://vuldb.com/?actor.sandworm_team). The _activity monitoring_ correlates data from social media, forums, chat rooms, and darknet markets. It helps to determine associated actors, specific activities, expected intentions, emerging research, and ongoing attacks. Our unique _predictive model_ uses _big data_ to forecast activities and their characteristics.

_Live data_ and more _analysis capabilities_ are available at [https://vuldb.com/?actor.sandworm_team](https://vuldb.com/?actor.sandworm_team)

## Campaigns

The following _campaigns_ are known and can be associated with Sandworm Team:

* BlackEnergy
* Ukraine

## Countries

These _countries_ are directly (e.g. origin of attacks) or indirectly (e.g. access by proxy) associated with Sandworm Team:

* [CN](https://vuldb.com/?country.cn)
* [LA](https://vuldb.com/?country.la)
* [US](https://vuldb.com/?country.us)
* ...

There are 15 more country items available. Please use our online service to access the data.

## IOC - Indicator of Compromise

These _indicators of compromise_ (IOC) indicate associated network resources which are known to be part of research and attack activities of Sandworm Team.

ID | IP address | Hostname | Campaign | Confidence
-- | ---------- | -------- | -------- | ----------
1 | [5.9.32.230](https://vuldb.com/?ip.5.9.32.230) | static.230.32.9.5.clients.your-server.de | BlackEnergy | High
2 | [5.61.38.31](https://vuldb.com/?ip.5.61.38.31) | - | BlackEnergy | High
3 | [5.79.80.166](https://vuldb.com/?ip.5.79.80.166) | - | BlackEnergy | High
4 | [5.133.8.46](https://vuldb.com/?ip.5.133.8.46) | d8046.artnet.gda.pl | - | High
5 | [5.149.254.114](https://vuldb.com/?ip.5.149.254.114) | mail1.auditoriavanzada.info | BlackEnergy | High
6 | [5.255.87.39](https://vuldb.com/?ip.5.255.87.39) | - | BlackEnergy | High
7 | [31.210.111.154](https://vuldb.com/?ip.31.210.111.154) | . | BlackEnergy | High
8 | [37.220.34.56](https://vuldb.com/?ip.37.220.34.56) | - | BlackEnergy | High
9 | [45.56.93.83](https://vuldb.com/?ip.45.56.93.83) | li895-83.members.linode.com | Ukraine | High
10 | ... | ... | ... | ...

There are 34 more IOC items available. Please use our online service to access the data.

## TTP - Tactics, Techniques, Procedures

_Tactics, techniques, and procedures_ (TTP) summarize the suspected MITRE ATT&CK techniques used by _Sandworm Team_. This data is unique as it uses our predictive model for actor profiling.

ID | Technique | Weakness | Description | Confidence
-- | --------- | -------- | ----------- | ----------
1 | T1006 | CWE-21, CWE-22, CWE-23, CWE-37, CWE-44 | Path Traversal | High
2 | T1055 | CWE-74 | Improper Neutralization of Data within XPath Expressions | High
3 | T1059 | CWE-88, CWE-94, CWE-1321 | Argument Injection | High
4 | T1059.007 | CWE-79, CWE-80 | Basic Cross Site Scripting | High
5 | T1068 | CWE-250, CWE-264, CWE-269, CWE-284 | Execution with Unnecessary Privileges | High
6 | ... | ... | ... | ...

There are 22 more TTP items available. Please use our online service to access the data.

## IOA - Indicator of Attack

These _indicators of attack_ (IOA) list the potential fragments used for technical activities like reconnaissance, exploitation, privilege escalation, and exfiltration by Sandworm Team. This data is unique as it uses our predictive model for actor profiling.

ID | Type | Indicator | Confidence
-- | ---- | --------- | ----------
1 | File | `.travis.yml` | Medium
2 | File | `/+CSCOE+/logon.html` | High
3 | File | `/adfs/ls` | Medium
4 | File | `/admin.php?p=/Area/index#tab=t2` | High
5 | File | `/admin/add_ikev2.php` | High
6 | File | `/admin/admin_action.php` | High
7 | File | `/admin/category_save.php` | High
8 | File | `/admin/file_manager/export` | High
9 | File | `/admin/index2.html` | High
10 | File | `/admin/list_ipAddressPolicy.php` | High
11 | File | `/admin/manage_model.php` | High
12 | File | `/admin/manage_user.php` | High
13 | File | `/admin/search-vehicle.php` | High
14 | File | `/admin/subject.php` | High
15 | File | `/admin/system/dict/add.json?sqlid=system.dict.save` | High
16 | File | `/admin/twitter.php` | High
17 | File | `/admin_topic.php?action=delall` | High
18 | File | `/api/cron/settings/setJob/` | High
19 | File | `/api/v1/settings` | High
20 | File | `/api/v1/toolbox/device/update/swap` | High
21 | File | `/api2/html/` | Medium
22 | File | `/app/zentao/module/repo/model.php` | High
23 | File | `/bin/httpd` | Medium
24 | File | `/bitrix/admin/ldap_server_edit.php` | High
25 | File | `/building/backmgr/urlpage/mobileurl/configfile/jx2_config.ini` | High
26 | File | `/catalog/all-products` | High
27 | File | `/cgi-bin/cstecgi.cgi` | High
28 | File | `/cgi-bin/ExportSettings.sh` | High
29 | File | `/cgi-bin/koha/catalogue/search.pl` | High
30 | File | `/classes/SystemSettings.php?f=update_settings` | High
31 | File | `/cloudstore/ecode/setup/ecology_dev.zip` | High
32 | File | `/com/esafenet/servlet/policy/HookService.java` | High
33 | File | `/doctor/appointment-bwdates-reports-details.php` | High
34 | File | `/edit-subject.php` | High
35 | File | `/edit.php` | Medium
36 | File | `/endpoint/add-user.php` | High
37 | File | `/etc/postfix/sender_login` | High
38 | File | `/etc/shadow.sample` | High
39 | File | `/extensions/realestate/index.php/properties/list/list-with-sidebar/realties` | High
40 | File | `/file-manager/upload.php` | High
41 | File | `/foms/routers/place-order.php` | High
42 | File | `/forum/away.php` | High
43 | ... | ... | ...

There are 367 more IOA items available (file, library, argument, input value, pattern, network port). Please use our online service to access the data.

## References

The following list contains _external sources_ which discuss the actor and the associated activities:

* https://blog.google/threat-analysis-group/ukraine-remains-russias-biggest-cyber-focus-in-2023/
* https://ddanchev.blogspot.com/2022/06/exclusive-exposing-grus-unit-74455.html
* https://media.defense.gov/2020/May/28/2002306626/-1/-1/0/CSA%20Sandworm%20Actors%20Exploiting%20Vulnerability%20in%20Exim%20Transfer%20Agent%2020200528.pdf
* https://otx.alienvault.com/pulse/62552abdd7e44d9aba08636d
* https://www.threatminer.org/report.php?q=BlackEnergy2_Plugins_Router.pdf&y=2014
* https://www.welivesecurity.com/2016/01/03/blackenergy-sshbeardoor-details-2015-attacks-ukrainian-news-media-electric-industry/
* https://www.welivesecurity.com/2016/12/13/rise-telebots-analyzing-disruptive-killdisk-attacks/
* https://www.welivesecurity.com/2017/06/30/telebots-back-supply-chain-attacks-against-ukraine/
* https://www.welivesecurity.com/2018/10/11/new-telebots-backdoor-linking-industroyer-notpetya/

## Literature

The following _articles_ explain our unique predictive cyber threat intelligence:

* [VulDB Cyber Threat Intelligence Documentation](https://vuldb.com/?kb.cti)
* [Cyber Threat Intelligence - Early Anticipation of Attacks](https://www.scip.ch/en/?labs.20201022)

## License

(c) [1997-2025](https://vuldb.com/?kb.changelog) by [vuldb.com](https://vuldb.com/?kb.about). All data on this page is shared under the license [CC BY-NC-SA 4.0](https://creativecommons.org/licenses/by-nc-sa/4.0/). Questions? Check the [FAQ](https://vuldb.com/?kb.faq), read the [documentation](https://vuldb.com/?kb) or [contact us](https://vuldb.com/?contact)!
