# BazarLoader - Cyber Threat Intelligence

These _indicators_ were reported, collected, and generated during the [VulDB CTI analysis](https://vuldb.com/?kb.cti) of the actor known as [BazarLoader](https://vuldb.com/?actor.bazarloader). The _activity monitoring_ correlates data from social media, forums, chat rooms, and darknet markets. It helps to determine associated actors, specific activities, expected intentions, emerging research, and ongoing attacks. Our unique _predictive model_ uses _big data_ to forecast activities and their characteristics.

_Live data_ and more _analysis capabilities_ are available at [https://vuldb.com/?actor.bazarloader](https://vuldb.com/?actor.bazarloader)

## Countries

These _countries_ are directly (e.g. origin of attacks) or indirectly (e.g. access by proxy) associated with BazarLoader:

* [US](https://vuldb.com/?country.us)
* [CN](https://vuldb.com/?country.cn)
* [DK](https://vuldb.com/?country.dk)
* ...

There are 21 more country items available. Please use our online service to access the data.

## IOC - Indicator of Compromise

These _indicators of compromise_ (IOC) indicate associated network resources which are known to be part of research and attack activities of BazarLoader.

ID | IP address | Hostname | Campaign | Confidence
-- | ---------- | -------- | -------- | ----------
1 | [13.225.230.232](https://vuldb.com/?ip.13.225.230.232) | server-13-225-230-232.jfk51.r.cloudfront.net | - | High
2 | [13.226.32.216](https://vuldb.com/?ip.13.226.32.216) | server-13-226-32-216.ewr53.r.cloudfront.net | - | High
3 | [18.67.60.164](https://vuldb.com/?ip.18.67.60.164) | server-18-67-60-164.iad89.r.cloudfront.net | - | High
4 | [23.56.10.219](https://vuldb.com/?ip.23.56.10.219) | a23-56-10-219.deploy.static.akamaitechnologies.com | - | High
5 | [23.62.25.178](https://vuldb.com/?ip.23.62.25.178) | a23-62-25-178.deploy.static.akamaitechnologies.com | - | High
6 | [23.95.238.122](https://vuldb.com/?ip.23.95.238.122) | 23-95-238-122-host.colocrossing.com | - | High
7 | [23.106.223.174](https://vuldb.com/?ip.23.106.223.174) | - | - | High
8 | [23.160.193.217](https://vuldb.com/?ip.23.160.193.217) | unknown.ip-xfer.net | - | High
9 | [23.193.217.119](https://vuldb.com/?ip.23.193.217.119) | a23-193-217-119.deploy.static.akamaitechnologies.com | - | High
10 | [31.171.251.118](https://vuldb.com/?ip.31.171.251.118) | ch.ns.mon0.li | - | High
11 | [31.214.240.203](https://vuldb.com/?ip.31.214.240.203) | - | - | High
12 | [34.209.40.84](https://vuldb.com/?ip.34.209.40.84) | ec2-34-209-40-84.us-west-2.compute.amazonaws.com | - | Medium
13 | [34.221.188.35](https://vuldb.com/?ip.34.221.188.35) | ec2-34-221-188-35.us-west-2.compute.amazonaws.com | - | Medium
14 | [34.222.222.126](https://vuldb.com/?ip.34.222.222.126) | ec2-34-222-222-126.us-west-2.compute.amazonaws.com | - | Medium
15 | [40.76.4.15](https://vuldb.com/?ip.40.76.4.15) | - | - | High
16 | [40.112.72.205](https://vuldb.com/?ip.40.112.72.205) | - | - | High
17 | [40.113.200.201](https://vuldb.com/?ip.40.113.200.201) | - | - | High
18 | ... | ... | ... | ...

There are 68 more IOC items available. Please use our online service to access the data.

## TTP - Tactics, Techniques, Procedures

_Tactics, techniques, and procedures_ (TTP) summarize the suspected MITRE ATT&CK techniques used by _BazarLoader_. This data is unique as it uses our predictive model for actor profiling.

ID | Technique | Weakness | Description | Confidence
-- | --------- | -------- | ----------- | ----------
1 | T1059.007 | CWE-79, CWE-80 | Cross Site Scripting | High
2 | T1068 | CWE-264, CWE-284 | Execution with Unnecessary Privileges | High
3 | T1110.001 | CWE-307, CWE-798 | Improper Restriction of Excessive Authentication Attempts | High
4 | ... | ... | ... | ...

There are 7 more TTP items available. Please use our online service to access the data.

## IOA - Indicator of Attack

These _indicators of attack_ (IOA) list the potential fragments used for technical activities like reconnaissance, exploitation, privilege escalation, and exfiltration by BazarLoader. This data is unique as it uses our predictive model for actor profiling.

ID | Type | Indicator | Confidence
-- | ---- | --------- | ----------
1 | File | `.htaccess` | Medium
2 | File | `.user` | Low
3 | File | `/.dbus-keyrings` | High
4 | File | `/api` | Low
5 | File | `/catalog/admin/categories.php?cPath=&action=new_product` | High
6 | File | `/cgi-bin/system_mgr.cgi` | High
7 | File | `/common/ticket_associated_tickets.php` | High
8 | File | `/common/user_profile.php` | High
9 | File | `/Content/Template/root/reverse-shell.aspx` | High
10 | File | `/debug/pprof` | Medium
11 | File | `/getcfg.php` | Medium
12 | File | `/goform/form2userconfig.cgi` | High
13 | File | `/include/makecvs.php` | High
14 | File | `/includes/db_adodb.php` | High
15 | File | `/objects/pluginSwitch.json.php` | High
16 | File | `/PluXml/core/admin/parametres_edittpl.php` | High
17 | File | `/register.do` | Medium
18 | File | `/rest/api/latest/groupuserpicker` | High
19 | File | `/rest/project-templates/1.0/createshared` | High
20 | File | `/restoreinfo.cgi` | High
21 | File | `/secure/admin/InsightDefaultCustomFieldConfig.jspa` | High
22 | File | `/see_more_details.php` | High
23 | File | `/sendrcpackage?keyid=-2544&keysymbol=-4081` | High
24 | File | `/services` | Medium
25 | File | `/uncpath/` | Medium
26 | File | `/usr/local/vesta/bin` | High
27 | File | `/usr/sbin/suexec` | High
28 | File | `/v3/credentials` | High
29 | File | `/var/log/monkeyd/master.log` | High
30 | File | `/var/passwd` | Medium
31 | File | `/var/run/storage_account_root` | High
32 | File | `/webconsole/APIController` | High
33 | File | `/websocket` | Medium
34 | File | `802dot1xclientcert.cgi` | High
35 | File | `account.asp` | Medium
36 | File | `Account.aspx` | Medium
37 | File | `ActionsAndOperations` | High
38 | File | `adclick.php` | Medium
39 | File | `add.php` | Low
40 | File | `admin/?n=tags&c=index&a=doSaveTags` | High
41 | File | `admin/admin.shtml` | High
42 | File | `admin/db-backup-security/db-backup-security.php` | High
43 | File | `admin/graph_trend.php` | High
44 | File | `administrator/components/com_media/helpers/media.php` | High
45 | File | `adminquery.php` | High
46 | File | `agent_links.pl` | High
47 | File | `ajax/render/widget_php` | High
48 | File | `Ap4StssAtom.cpp` | High
49 | File | `Ap4StszAtom.cpp` | High
50 | File | `apetag.c` | Medium
51 | File | `app/system/language/admin/language_general.class.php` | High
52 | File | `apply_sec.cgi` | High
53 | File | `app\contacts\contact_times.php` | High
54 | File | `Archive.java` | Medium
55 | File | `article.php` | Medium
56 | ... | ... | ...

There are 484 more IOA items available (file, library, argument, input value, pattern, network port). Please use our online service to access the data.

## References

The following list contains _external sources_ which discuss the actor and the associated activities:

* https://blog.talosintelligence.com/2021/05/threat-roundup-0514-0521.html
* https://blog.talosintelligence.com/2022/02/threat-roundup-0211-0218.html
* https://blog.talosintelligence.com/2022/03/threat-roundup-0311-0318.html
* https://isc.sans.edu/forums/diary/April+2021+Forensic+Quiz+Answers+and+Analysis/27308/
* https://isc.sans.edu/forums/diary/Stolen+Images+Evidence+Campaign+Continues+Pushing+BazarLoader+Malware/27816/
* https://isc.sans.edu/forums/diary/TA551+Shathak+continues+pushing+BazarLoader+infections+lead+to+Cobalt+Strike/27738/
* https://twitter.com/_pr4gma/status/1347617681197961225

## Literature

The following _articles_ explain our unique predictive cyber threat intelligence:

* [VulDB Cyber Threat Intelligence Documentation](https://vuldb.com/?kb.cti)
* [Cyber Threat Intelligence - Early Anticipation of Attacks](https://www.scip.ch/en/?labs.20201022)

## License

(c) [1997-2022](https://vuldb.com/?kb.changelog) by [vuldb.com](https://vuldb.com/?kb.about). All data on this page is shared under the license [CC BY-NC-SA 4.0](https://creativecommons.org/licenses/by-nc-sa/4.0/). Questions? Check the [FAQ](https://vuldb.com/?kb.faq), read the [documentation](https://vuldb.com/?kb) or [contact us](https://vuldb.com/?contact)!
