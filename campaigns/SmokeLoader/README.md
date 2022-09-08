# SmokeLoader - Cyber Threat Intelligence

These _indicators_ were reported, collected, and generated during the [VulDB CTI analysis](https://vuldb.com/?kb.cti) of the campaign known as _SmokeLoader_. The _activity monitoring_ correlates data from social media, forums, chat rooms, and darknet markets. It helps to determine associated actors, specific activities, expected intentions, emerging research, and ongoing attacks. Our unique _predictive model_ uses _big data_ to forecast activities and their characteristics.

_Live data_ and more _analysis capabilities_ are available at [https://vuldb.com/?actor](https://vuldb.com/?actor)

## Countries

These _countries_ are directly (e.g. origin of attacks) or indirectly (e.g. access by proxy) associated with SmokeLoader:

* [US](https://vuldb.com/?country.us)
* [CN](https://vuldb.com/?country.cn)
* [ES](https://vuldb.com/?country.es)
* ...

There are 11 more country items available. Please use our online service to access the data.

## Actors

These _actors_ are associated with SmokeLoader or other actors linked to the campaign.

ID | Actor | Confidence
-- | ----- | ----------
1 | [SmokeLoader](https://vuldb.com/?actor.smokeloader) | High
2 | [Amadey Bot](https://vuldb.com/?actor.amadey_bot) | High

## IOC - Indicator of Compromise

These _indicators of compromise_ (IOC) indicate associated network resources which are known to be part of research and attack activities of SmokeLoader.

ID | IP address | Hostname | Actor | Confidence
-- | ---------- | -------- | ----- | ----------
1 | [5.135.183.146](https://vuldb.com/?ip.5.135.183.146) | freya.stelas.de | [SmokeLoader](https://vuldb.com/?actor.smokeloader) | High
2 | [5.196.8.173](https://vuldb.com/?ip.5.196.8.173) | vps-b5645e9a.vps.ovh.net | [SmokeLoader](https://vuldb.com/?actor.smokeloader) | High
3 | [13.107.21.200](https://vuldb.com/?ip.13.107.21.200) | - | [SmokeLoader](https://vuldb.com/?actor.smokeloader) | High
4 | [20.45.1.107](https://vuldb.com/?ip.20.45.1.107) | - | [SmokeLoader](https://vuldb.com/?actor.smokeloader) | High
5 | [23.0.48.75](https://vuldb.com/?ip.23.0.48.75) | a23-0-48-75.deploy.static.akamaitechnologies.com | [SmokeLoader](https://vuldb.com/?actor.smokeloader) | High
6 | [23.0.209.167](https://vuldb.com/?ip.23.0.209.167) | a23-0-209-167.deploy.static.akamaitechnologies.com | [SmokeLoader](https://vuldb.com/?actor.smokeloader) | High
7 | [23.3.13.154](https://vuldb.com/?ip.23.3.13.154) | a23-3-13-154.deploy.static.akamaitechnologies.com | [SmokeLoader](https://vuldb.com/?actor.smokeloader) | High
8 | [23.6.69.99](https://vuldb.com/?ip.23.6.69.99) | a23-6-69-99.deploy.static.akamaitechnologies.com | [SmokeLoader](https://vuldb.com/?actor.smokeloader) | High
9 | [23.13.211.142](https://vuldb.com/?ip.23.13.211.142) | a23-13-211-142.deploy.static.akamaitechnologies.com | [SmokeLoader](https://vuldb.com/?actor.smokeloader) | High
10 | [23.20.239.12](https://vuldb.com/?ip.23.20.239.12) | ec2-23-20-239-12.compute-1.amazonaws.com | [SmokeLoader](https://vuldb.com/?actor.smokeloader) | Medium
11 | [23.66.61.153](https://vuldb.com/?ip.23.66.61.153) | a23-66-61-153.deploy.static.akamaitechnologies.com | [SmokeLoader](https://vuldb.com/?actor.smokeloader) | High
12 | [23.193.177.127](https://vuldb.com/?ip.23.193.177.127) | a23-193-177-127.deploy.static.akamaitechnologies.com | [SmokeLoader](https://vuldb.com/?actor.smokeloader) | High
13 | [23.218.40.161](https://vuldb.com/?ip.23.218.40.161) | a23-218-40-161.deploy.static.akamaitechnologies.com | [SmokeLoader](https://vuldb.com/?actor.smokeloader) | High
14 | ... | ... | ... | ...

There are 54 more IOC items available. Please use our online service to access the data.

## TTP - Tactics, Techniques, Procedures

_Tactics, techniques, and procedures_ (TTP) summarize the suspected MITRE ATT&CK techniques used within SmokeLoader. This data is unique as it uses our predictive model for actor profiling.

ID | Technique | Weakness | Description | Confidence
-- | --------- | -------- | ----------- | ----------
1 | T1006 | CWE-21, CWE-22, CWE-23 | Pathname Traversal | High
2 | T1055 | CWE-74 | Injection | High
3 | T1059 | CWE-88, CWE-94 | Cross Site Scripting | High
4 | T1059.007 | CWE-79, CWE-80 | Cross Site Scripting | High
5 | T1068 | CWE-264, CWE-269, CWE-274, CWE-284 | Execution with Unnecessary Privileges | High
6 | ... | ... | ... | ...

There are 18 more TTP items available. Please use our online service to access the data.

## IOA - Indicator of Attack

These _indicators of attack_ (IOA) list the potential fragments used for technical activities like reconnaissance, exploitation, privilege escalation, and exfiltration during SmokeLoader. This data is unique as it uses our predictive model for actor profiling.

ID | Type | Indicator | Confidence
-- | ---- | --------- | ----------
1 | File | `.htaccess` | Medium
2 | File | `.pref.xml` | Medium
3 | File | `/bin/appmgr` | Medium
4 | File | `/cgi-bin/editBookmark` | High
5 | File | `/cgi-bin/koha/acqui/supplier.pl?op=enter` | High
6 | File | `/cgi-bin/luci` | High
7 | File | `/cgi-bin/pass` | High
8 | File | `/cgi/ansi` | Medium
9 | File | `/ClickAndBanexDemo/admin/admin.asp` | High
10 | File | `/config.cgi?webmin` | High
11 | File | `/config/getuser` | High
12 | File | `/etc/gsissh/sshd_config` | High
13 | File | `/etc/passwd` | Medium
14 | File | `/etc/sudoers` | Medium
15 | File | `/gateway/services/EdgeServiceImpl` | High
16 | File | `/getcfg.php` | Medium
17 | File | `/goform/dir_setWanWifi` | High
18 | File | `/goform/GetNewDir` | High
19 | File | `/goform/telnet` | High
20 | File | `/goform/WanParameterSetting` | High
21 | File | `/hnap.cgi` | Medium
22 | File | `/HNAP1` | Low
23 | File | `/include/makecvs.php` | High
24 | File | `/includes/common.inc.php` | High
25 | File | `/knomi/analyze` | High
26 | File | `/mgmt/tm/util/bash` | High
27 | File | `/monitoring` | Medium
28 | File | `/opt/pia/ruby/64/ruby` | High
29 | File | `/opt/tms/bin/cli` | High
30 | File | `/out.php` | Medium
31 | File | `/outgoing.php` | High
32 | File | `/Pwrchute` | Medium
33 | File | `/reports/rwservlet` | High
34 | File | `/scripts/iisadmin/bdir.htr` | High
35 | File | `/skyboxview-softwareupdate/services/CollectorSoftwareUpdate` | High
36 | File | `/tmp` | Low
37 | File | `/tmp/csman/0` | Medium
38 | File | `/ui/cbpc/login` | High
39 | File | `/uncpath/` | Medium
40 | File | `/usr/local/psa/admin/sbin/wrapper` | High
41 | File | `/var/avamar/f_cache.dat` | High
42 | File | `/var/hnap/timestamp` | High
43 | File | `/var/run/storage_account_root` | High
44 | File | `/webmail/` | Medium
45 | File | `/wordpress/wp-admin/admin.php` | High
46 | File | `/wp-content/plugins/forum-server/feed.php` | High
47 | File | `/{ADMIN-FILE}/` | High
48 | File | `a2billing/customer/iridium_threed.php` | High
49 | File | `address.html` | Medium
50 | ... | ... | ...

There are 436 more IOA items available (file, library, argument, input value, pattern, network port). Please use our online service to access the data.

## References

The following list contains _external sources_ which discuss the campaign and the associated activities:

* https://asec.ahnlab.com/en/36634/
* https://blog.talosintelligence.com/2020/01/threat-roundup-0124-0131.html
* https://blog.talosintelligence.com/2021/07/threat-roundup-0716-0723.html
* https://isc.sans.edu/forums/diary/Resumethemed+malspam+pushing+Smoke+Loader/23054/
* https://research.checkpoint.com/2019/2019-resurgence-of-smokeloader/
* https://unit42.paloaltonetworks.com/analysis-of-smoke-loader-in-new-tsunami-campaign/

## Literature

The following _articles_ explain our unique predictive cyber threat intelligence:

* [VulDB Cyber Threat Intelligence Documentation](https://vuldb.com/?kb.cti)
* [Cyber Threat Intelligence - Early Anticipation of Attacks](https://www.scip.ch/en/?labs.20201022)

## License

(c) [1997-2022](https://vuldb.com/?kb.changelog) by [vuldb.com](https://vuldb.com/?kb.about). All data on this page is shared under the license [CC BY-NC-SA 4.0](https://creativecommons.org/licenses/by-nc-sa/4.0/). Questions? Check the [FAQ](https://vuldb.com/?kb.faq), read the [documentation](https://vuldb.com/?kb) or [contact us](https://vuldb.com/?contact)!
