# SmokeLoader - Cyber Threat Intelligence

These _indicators_ were reported, collected, and generated during the [VulDB CTI analysis](https://vuldb.com/?kb.cti) of the campaign known as _SmokeLoader_. The _activity monitoring_ correlates data from social media, forums, chat rooms, and darknet markets. It helps to determine associated actors, specific activities, expected intentions, emerging research, and ongoing attacks. Our unique _predictive model_ uses _big data_ to forecast activities and their characteristics.

_Live data_ and more _analysis capabilities_ are available at [https://vuldb.com/?actor](https://vuldb.com/?actor)

## Countries

These _countries_ are directly (e.g. origin of attacks) or indirectly (e.g. access by proxy) associated with SmokeLoader:

* [US](https://vuldb.com/?country.us)
* [CN](https://vuldb.com/?country.cn)
* [ES](https://vuldb.com/?country.es)
* ...

There are 13 more country items available. Please use our online service to access the data.

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
1 | [5.9.224.217](https://vuldb.com/?ip.5.9.224.217) | static.217.224.9.5.clients.your-server.de | [SmokeLoader](https://vuldb.com/?actor.smokeloader) | High
2 | [5.135.183.146](https://vuldb.com/?ip.5.135.183.146) | freya.stelas.de | [SmokeLoader](https://vuldb.com/?actor.smokeloader) | High
3 | [5.196.8.173](https://vuldb.com/?ip.5.196.8.173) | vps-b5645e9a.vps.ovh.net | [SmokeLoader](https://vuldb.com/?actor.smokeloader) | High
4 | [13.107.21.200](https://vuldb.com/?ip.13.107.21.200) | - | [SmokeLoader](https://vuldb.com/?actor.smokeloader) | High
5 | [20.45.1.107](https://vuldb.com/?ip.20.45.1.107) | - | [SmokeLoader](https://vuldb.com/?actor.smokeloader) | High
6 | [23.0.48.75](https://vuldb.com/?ip.23.0.48.75) | a23-0-48-75.deploy.static.akamaitechnologies.com | [SmokeLoader](https://vuldb.com/?actor.smokeloader) | High
7 | [23.0.209.167](https://vuldb.com/?ip.23.0.209.167) | a23-0-209-167.deploy.static.akamaitechnologies.com | [SmokeLoader](https://vuldb.com/?actor.smokeloader) | High
8 | [23.3.13.154](https://vuldb.com/?ip.23.3.13.154) | a23-3-13-154.deploy.static.akamaitechnologies.com | [SmokeLoader](https://vuldb.com/?actor.smokeloader) | High
9 | [23.6.69.99](https://vuldb.com/?ip.23.6.69.99) | a23-6-69-99.deploy.static.akamaitechnologies.com | [SmokeLoader](https://vuldb.com/?actor.smokeloader) | High
10 | [23.13.211.142](https://vuldb.com/?ip.23.13.211.142) | a23-13-211-142.deploy.static.akamaitechnologies.com | [SmokeLoader](https://vuldb.com/?actor.smokeloader) | High
11 | [23.20.239.12](https://vuldb.com/?ip.23.20.239.12) | ec2-23-20-239-12.compute-1.amazonaws.com | [SmokeLoader](https://vuldb.com/?actor.smokeloader) | Medium
12 | [23.66.61.153](https://vuldb.com/?ip.23.66.61.153) | a23-66-61-153.deploy.static.akamaitechnologies.com | [SmokeLoader](https://vuldb.com/?actor.smokeloader) | High
13 | [23.193.177.127](https://vuldb.com/?ip.23.193.177.127) | a23-193-177-127.deploy.static.akamaitechnologies.com | [SmokeLoader](https://vuldb.com/?actor.smokeloader) | High
14 | [23.218.40.161](https://vuldb.com/?ip.23.218.40.161) | a23-218-40-161.deploy.static.akamaitechnologies.com | [SmokeLoader](https://vuldb.com/?actor.smokeloader) | High
15 | [23.221.48.201](https://vuldb.com/?ip.23.221.48.201) | a23-221-48-201.deploy.static.akamaitechnologies.com | [SmokeLoader](https://vuldb.com/?actor.smokeloader) | High
16 | [27.102.67.144](https://vuldb.com/?ip.27.102.67.144) | - | [SmokeLoader](https://vuldb.com/?actor.smokeloader) | High
17 | ... | ... | ... | ...

There are 63 more IOC items available. Please use our online service to access the data.

## TTP - Tactics, Techniques, Procedures

_Tactics, techniques, and procedures_ (TTP) summarize the suspected MITRE ATT&CK techniques used within SmokeLoader. This data is unique as it uses our predictive model for actor profiling.

ID | Technique | Weakness | Description | Confidence
-- | --------- | -------- | ----------- | ----------
1 | T1006 | CWE-21, CWE-22, CWE-23 | Pathname Traversal | High
2 | T1040 | CWE-319 | Authentication Bypass by Capture-replay | High
3 | T1055 | CWE-74 | Injection | High
4 | T1059 | CWE-88, CWE-94 | Cross Site Scripting | High
5 | T1059.007 | CWE-79, CWE-80 | Cross Site Scripting | High
6 | ... | ... | ... | ...

There are 20 more TTP items available. Please use our online service to access the data.

## IOA - Indicator of Attack

These _indicators of attack_ (IOA) list the potential fragments used for technical activities like reconnaissance, exploitation, privilege escalation, and exfiltration during SmokeLoader. This data is unique as it uses our predictive model for actor profiling.

ID | Type | Indicator | Confidence
-- | ---- | --------- | ----------
1 | File | `.htaccess` | Medium
2 | File | `.pref.xml` | Medium
3 | File | `/admin/admin_login.php` | High
4 | File | `/admin/edit-doc.php` | High
5 | File | `/admin/profile/save_profile` | High
6 | File | `/aux` | Low
7 | File | `/cgi-bin/koha/acqui/supplier.pl?op=enter` | High
8 | File | `/cgi-bin/luci` | High
9 | File | `/ClickAndBanexDemo/admin/admin.asp` | High
10 | File | `/config.cgi?webmin` | High
11 | File | `/config/getuser` | High
12 | File | `/debug/pprof` | Medium
13 | File | `/etc/config/rpcd` | High
14 | File | `/etc/gsissh/sshd_config` | High
15 | File | `/etc/passwd` | Medium
16 | File | `/gateway/services/EdgeServiceImpl` | High
17 | File | `/getcfg.php` | Medium
18 | File | `/goform/dir_setWanWifi` | High
19 | File | `/goform/telnet` | High
20 | File | `/goform/WanParameterSetting` | High
21 | File | `/HNAP1` | Low
22 | File | `/include/makecvs.php` | High
23 | File | `/js/app.js` | Medium
24 | File | `/knomi/analyze` | High
25 | File | `/mgmt/tm/util/bash` | High
26 | File | `/monitoring` | Medium
27 | File | `/opt/pia/ruby/64/ruby` | High
28 | File | `/Pwrchute` | Medium
29 | File | `/reports/rwservlet` | High
30 | File | `/scripts/iisadmin/bdir.htr` | High
31 | File | `/setSystemAdmin` | High
32 | File | `/skyboxview-softwareupdate/services/CollectorSoftwareUpdate` | High
33 | File | `/tmp` | Low
34 | File | `/tmp/csman/0` | Medium
35 | File | `/ui/cbpc/login` | High
36 | File | `/uncpath/` | Medium
37 | File | `/usr/local/psa/admin/sbin/wrapper` | High
38 | File | `/var/hnap/timestamp` | High
39 | File | `/vloggers_merch/admin/?page=product/manage_product` | High
40 | File | `/webmail/` | Medium
41 | File | `/wordpress/wp-admin/admin.php` | High
42 | File | `/wp-content/plugins/forum-server/feed.php` | High
43 | File | `/{ADMIN-FILE}/` | High
44 | File | `a2billing/customer/iridium_threed.php` | High
45 | File | `address.html` | Medium
46 | File | `adm/systools.asp` | High
47 | File | `admin/admin_login.php` | High
48 | File | `admin/dashboard.php` | High
49 | ... | ... | ...

There are 423 more IOA items available (file, library, argument, input value, pattern, network port). Please use our online service to access the data.

## References

The following list contains _external sources_ which discuss the campaign and the associated activities:

* https://asec.ahnlab.com/en/36634/
* https://blog.talosintelligence.com/2020/01/threat-roundup-0124-0131.html
* https://blog.talosintelligence.com/2021/07/threat-roundup-0716-0723.html
* https://community.blueliv.com/#!/s/6333fa0182df417ed0331a1d
* https://isc.sans.edu/forums/diary/Resumethemed+malspam+pushing+Smoke+Loader/23054/
* https://research.checkpoint.com/2019/2019-resurgence-of-smokeloader/
* https://unit42.paloaltonetworks.com/analysis-of-smoke-loader-in-new-tsunami-campaign/

## Literature

The following _articles_ explain our unique predictive cyber threat intelligence:

* [VulDB Cyber Threat Intelligence Documentation](https://vuldb.com/?kb.cti)
* [Cyber Threat Intelligence - Early Anticipation of Attacks](https://www.scip.ch/en/?labs.20201022)

## License

(c) [1997-2023](https://vuldb.com/?kb.changelog) by [vuldb.com](https://vuldb.com/?kb.about). All data on this page is shared under the license [CC BY-NC-SA 4.0](https://creativecommons.org/licenses/by-nc-sa/4.0/). Questions? Check the [FAQ](https://vuldb.com/?kb.faq), read the [documentation](https://vuldb.com/?kb) or [contact us](https://vuldb.com/?contact)!
