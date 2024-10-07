# XOR DDoS - Cyber Threat Intelligence

These _indicators_ were reported, collected, and generated during the [VulDB CTI analysis](https://vuldb.com/?kb.cti) of the actor known as [XOR DDoS](https://vuldb.com/?actor.xor_ddos). The _activity monitoring_ correlates data from social media, forums, chat rooms, and darknet markets. It helps to determine associated actors, specific activities, expected intentions, emerging research, and ongoing attacks. Our unique _predictive model_ uses _big data_ to forecast activities and their characteristics.

_Live data_ and more _analysis capabilities_ are available at [https://vuldb.com/?actor.xor_ddos](https://vuldb.com/?actor.xor_ddos)

## Countries

These _countries_ are directly (e.g. origin of attacks) or indirectly (e.g. access by proxy) associated with XOR DDoS:

* [US](https://vuldb.com/?country.us)
* [CN](https://vuldb.com/?country.cn)
* [SG](https://vuldb.com/?country.sg)
* ...

There are 2 more country items available. Please use our online service to access the data.

## IOC - Indicator of Compromise

These _indicators of compromise_ (IOC) indicate associated network resources which are known to be part of research and attack activities of XOR DDoS.

ID | IP address | Hostname | Campaign | Confidence
-- | ---------- | -------- | -------- | ----------
1 | [23.228.113.246](https://vuldb.com/?ip.23.228.113.246) | - | - | High
2 | [23.248.237.29](https://vuldb.com/?ip.23.248.237.29) | - | - | High
3 | [23.253.46.64](https://vuldb.com/?ip.23.253.46.64) | - | - | High
4 | [43.229.113.27](https://vuldb.com/?ip.43.229.113.27) | - | - | High
5 | [43.249.172.214](https://vuldb.com/?ip.43.249.172.214) | - | - | High
6 | [54.36.15.96](https://vuldb.com/?ip.54.36.15.96) | ip96.ip-54-36-15.eu | - | High
7 | ... | ... | ... | ...

There are 26 more IOC items available. Please use our online service to access the data.

## TTP - Tactics, Techniques, Procedures

_Tactics, techniques, and procedures_ (TTP) summarize the suspected MITRE ATT&CK techniques used by _XOR DDoS_. This data is unique as it uses our predictive model for actor profiling.

ID | Technique | Weakness | Description | Confidence
-- | --------- | -------- | ----------- | ----------
1 | T1006 | CWE-22, CWE-23 | Path Traversal | High
2 | T1040 | CWE-319 | Authentication Bypass by Capture-replay | High
3 | T1055 | CWE-74 | Improper Neutralization of Data within XPath Expressions | High
4 | T1059 | CWE-94 | Argument Injection | High
5 | ... | ... | ... | ...

There are 16 more TTP items available. Please use our online service to access the data.

## IOA - Indicator of Attack

These _indicators of attack_ (IOA) list the potential fragments used for technical activities like reconnaissance, exploitation, privilege escalation, and exfiltration by XOR DDoS. This data is unique as it uses our predictive model for actor profiling.

ID | Type | Indicator | Confidence
-- | ---- | --------- | ----------
1 | File | `/admin/general.cgi` | High
2 | File | `/admin/reminders/manage_reminder.php` | High
3 | File | `/API/info` | Medium
4 | File | `/CCMAdmin/serverlist.asp` | High
5 | File | `/cgi/get_param.cgi` | High
6 | File | `/csms/admin/inquiries/view_details.php` | High
7 | File | `/cstecgi.cgi` | Medium
8 | File | `/files.md5` | Medium
9 | File | `/forum/away.php` | High
10 | File | `/home/search` | Medium
11 | File | `/hrm/employeeview.php` | High
12 | File | `/include/chart_generator.php` | High
13 | File | `/librarian/bookdetails.php` | High
14 | File | `/login` | Low
15 | File | `/messageboard/view.php` | High
16 | File | `/modules/profile/index.php` | High
17 | File | `/one_church/userregister.php` | High
18 | File | `/out.php` | Medium
19 | File | `/owa/auth/logon.aspx` | High
20 | File | `/public/plugins/` | High
21 | File | `/SAP_Information_System/controllers/add_admin.php` | High
22 | File | `/SASWebReportStudio/logonAndRender.do` | High
23 | File | `/secure/admin/InsightDefaultCustomFieldConfig.jspa` | High
24 | File | `/secure/admin/ViewInstrumentation.jspa` | High
25 | File | `/SVFE2/pages/feegroups/country_group.jsf` | High
26 | File | `/textpattern/index.php` | High
27 | File | `/tmp` | Low
28 | File | `/upfile.cgi` | Medium
29 | File | `/v2/quantum/save-data-upload-big-file` | High
30 | File | `/wordpress/wp-admin/admin.php` | High
31 | File | `4.edu.php` | Medium
32 | File | `account_footer.php` | High
33 | File | `adclick.php` | Medium
34 | File | `add_edit_cat.asp` | High
35 | File | `add_edit_user.asp` | High
36 | File | `admin.cropcanvas.php` | High
37 | ... | ... | ...

There are 320 more IOA items available (file, library, argument, input value, pattern, network port). Please use our online service to access the data.

## References

The following list contains _external sources_ which discuss the actor and the associated activities:

* https://bazaar.abuse.ch/browse/signature/XorDDoS/
* https://bazaar.abuse.ch/sample/0e817a2325c215997de15851152a66924874739eeff5da4b434e5d36c83a76eb/
* https://bazaar.abuse.ch/sample/0f00c2e074c6284c556040012ef23357853ccac4ad1373d1dea683562dc24bca/
* https://bazaar.abuse.ch/sample/022e101f1d4671796972c9ae6eed81920a59003e751a0fd449b543f630ba36a8/
* https://bazaar.abuse.ch/sample/5a7d7f1d53f039e7b69cf8d040cc043d1264b14107a8a73034e6b90d8e81f87a/
* https://bazaar.abuse.ch/sample/76741721aede86e5d9a78da5dd349cc7f418a993eba77457c00b27aa627f9882/
* https://bazaar.abuse.ch/sample/b1b32e4ca117a393ad2dec01b112819864f34261a56b0dbebe5263840f769076/
* https://bazaar.abuse.ch/sample/b84cf164fde12dd07192aa44f1b943044610539fd979e0f9359d44062f21a612/
* https://bazaar.abuse.ch/sample/b242c3eca68edc7c09505570455398cce9b02689287690971762899d1fb2b1a8/
* https://bazaar.abuse.ch/sample/b277f80d0f288f4284dd071ccf388dad5cb99ac2ba3e6708c0496406dac09799/
* https://bazaar.abuse.ch/sample/c0b0225201fd3a4c08245e58bbb4b844e0d3426e89b9ac3fc34db37d994fb182
* https://bazaar.abuse.ch/sample/ccc4e17f1cb512b4710372f10908a3852968c7ae547dca563e76d472e7136689/
* https://bazaar.abuse.ch/sample/da3d038a95cb558469ee54f695c4be745a50824079c8d377a279a7c46d415aa4/
* https://bazaar.abuse.ch/sample/ea40ecec0b30982fbb1662e67f97f0e9d6f43d2d587f2f588525fae683abea73/
* https://bazaar.abuse.ch/sample/f4a25e8d960c631699e1b9adab8d29e5e4a2ae0d3be1c7739275a6a72b9b0876/
* https://bazaar.abuse.ch/sample/f48d2e608faeb0747b32205489e8ca88a3b10ecfd3c2cc2ff31fabf11fac03b3/
* https://de.darktrace.com/blog/to-be-xor-not-to-be-how-respond-could-have-stopped-a-surprise-ddos-incident
* https://isc.sans.edu/diary/rss/30880
* https://urlhaus.abuse.ch/url/1653849/

## Literature

The following _articles_ explain our unique predictive cyber threat intelligence:

* [VulDB Cyber Threat Intelligence Documentation](https://vuldb.com/?kb.cti)
* [Cyber Threat Intelligence - Early Anticipation of Attacks](https://www.scip.ch/en/?labs.20201022)

## License

(c) [1997-2024](https://vuldb.com/?kb.changelog) by [vuldb.com](https://vuldb.com/?kb.about). All data on this page is shared under the license [CC BY-NC-SA 4.0](https://creativecommons.org/licenses/by-nc-sa/4.0/). Questions? Check the [FAQ](https://vuldb.com/?kb.faq), read the [documentation](https://vuldb.com/?kb) or [contact us](https://vuldb.com/?contact)!
