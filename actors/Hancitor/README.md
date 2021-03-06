# Hancitor - Cyber Threat Intelligence

These _indicators_ were reported, collected, and generated during the [VulDB CTI analysis](https://vuldb.com/?kb.cti) of the actor known as [Hancitor](https://vuldb.com/?actor.hancitor). The _activity monitoring_ correlates data from social media, forums, chat rooms, and darknet markets. It helps to determine associated actors, specific activities, expected intentions, emerging research, and ongoing attacks. Our unique _predictive model_ uses _big data_ to forecast activities and their characteristics.

_Live data_ and more _analysis capabilities_ are available at [https://vuldb.com/?actor.hancitor](https://vuldb.com/?actor.hancitor)

## Campaigns

The following _campaigns_ are known and can be associated with Hancitor:

* Cobalt Strike

## Countries

These _countries_ are directly (e.g. origin of attacks) or indirectly (e.g. access by proxy) associated with Hancitor:

* [US](https://vuldb.com/?country.us)
* [CN](https://vuldb.com/?country.cn)
* [CA](https://vuldb.com/?country.ca)
* ...

There are 14 more country items available. Please use our online service to access the data.

## IOC - Indicator of Compromise

These _indicators of compromise_ (IOC) indicate associated network resources which are known to be part of research and attack activities of Hancitor.

ID | IP address | Hostname | Campaign | Confidence
-- | ---------- | -------- | -------- | ----------
1 | [5.196.129.108](https://vuldb.com/?ip.5.196.129.108) | - | - | High
2 | [8.208.9.98](https://vuldb.com/?ip.8.208.9.98) | - | - | High
3 | [8.208.77.171](https://vuldb.com/?ip.8.208.77.171) | - | - | High
4 | [8.209.119.208](https://vuldb.com/?ip.8.209.119.208) | - | - | High
5 | [8.211.241.0](https://vuldb.com/?ip.8.211.241.0) | - | - | High
6 | [10.0.2.2](https://vuldb.com/?ip.10.0.2.2) | - | - | High
7 | [23.228.100.130](https://vuldb.com/?ip.23.228.100.130) | gewrig.cerned.com | - | High
8 | [23.236.75.32](https://vuldb.com/?ip.23.236.75.32) | - | - | High
9 | [24.172.35.186](https://vuldb.com/?ip.24.172.35.186) | rrcs-24-172-35-186.midsouth.biz.rr.com | - | High
10 | [24.209.225.196](https://vuldb.com/?ip.24.209.225.196) | cpe-24-209-225-196.cinci.res.rr.com | - | High
11 | [24.229.13.112](https://vuldb.com/?ip.24.229.13.112) | cpe-static-raysautorepair-rtr.cmts.mlf.ptd.net | - | High
12 | [24.240.249.177](https://vuldb.com/?ip.24.240.249.177) | 024-240-249-177.biz.spectrum.com | - | High
13 | [27.121.64.185](https://vuldb.com/?ip.27.121.64.185) | cp185.ezyreg.com | - | High
14 | [27.124.124.97](https://vuldb.com/?ip.27.124.124.97) | server-2p-r17.ipv4.per01.ds.network | - | High
15 | [31.44.184.36](https://vuldb.com/?ip.31.44.184.36) | - | - | High
16 | [31.44.184.62](https://vuldb.com/?ip.31.44.184.62) | - | - | High
17 | [34.213.214.65](https://vuldb.com/?ip.34.213.214.65) | ec2-34-213-214-65.us-west-2.compute.amazonaws.com | - | Medium
18 | [45.40.182.1](https://vuldb.com/?ip.45.40.182.1) | ip-45-40-182-1.ip.secureserver.net | - | High
19 | [45.49.169.80](https://vuldb.com/?ip.45.49.169.80) | cpe-45-49-169-80.socal.res.rr.com | - | High
20 | [45.153.73.33](https://vuldb.com/?ip.45.153.73.33) | - | - | High
21 | ... | ... | ... | ...

There are 79 more IOC items available. Please use our online service to access the data.

## TTP - Tactics, Techniques, Procedures

_Tactics, techniques, and procedures_ (TTP) summarize the suspected MITRE ATT&CK techniques used by _Hancitor_. This data is unique as it uses our predictive model for actor profiling.

ID | Technique | Weakness | Description | Confidence
-- | --------- | -------- | ----------- | ----------
1 | T1006 | CWE-21, CWE-22, CWE-23 | Pathname Traversal | High
2 | T1040 | CWE-294, CWE-319 | Authentication Bypass by Capture-replay | High
3 | T1055 | CWE-74 | Injection | High
4 | T1059 | CWE-88, CWE-94 | Cross Site Scripting | High
5 | T1059.007 | CWE-79, CWE-80 | Cross Site Scripting | High
6 | ... | ... | ... | ...

There are 22 more TTP items available. Please use our online service to access the data.

## IOA - Indicator of Attack

These _indicators of attack_ (IOA) list the potential fragments used for technical activities like reconnaissance, exploitation, privilege escalation, and exfiltration by Hancitor. This data is unique as it uses our predictive model for actor profiling.

ID | Type | Indicator | Confidence
-- | ---- | --------- | ----------
1 | File | `/../conf/config.properties` | High
2 | File | `/auth/session` | High
3 | File | `/concat?/%2557EB-INF/web.xml` | High
4 | File | `/download` | Medium
5 | File | `/files.md5` | Medium
6 | File | `/forum/away.php` | High
7 | File | `/images/` | Medium
8 | File | `/inc/extensions.php` | High
9 | File | `/inc/parser/xhtml.php` | High
10 | File | `/lists/index.php` | High
11 | File | `/login` | Low
12 | File | `/modules/profile/index.php` | High
13 | File | `/nova/bin/console` | High
14 | File | `/objects/getImageMP4.php` | High
15 | File | `/one_church/userregister.php` | High
16 | File | `/out.php` | Medium
17 | File | `/owa/auth/logon.aspx` | High
18 | File | `/public/plugins/` | High
19 | File | `/replication` | Medium
20 | File | `/req_password_user.php` | High
21 | File | `/SAP_Information_System/controllers/add_admin.php` | High
22 | File | `/SASWebReportStudio/logonAndRender.do` | High
23 | File | `/secure/admin/InsightDefaultCustomFieldConfig.jspa` | High
24 | File | `/secure/admin/ViewInstrumentation.jspa` | High
25 | File | `/secure/QueryComponent!Default.jspa` | High
26 | File | `/SSOPOST/metaAlias/%realm%/idpv2` | High
27 | File | `/trx_addons/v2/get/sc_layout` | High
28 | File | `/uncpath/` | Medium
29 | File | `/usr/syno/etc/mount.conf` | High
30 | File | `/v2/quantum/save-data-upload-big-file` | High
31 | File | `/WEB-INF/web.xml` | High
32 | File | `/web/entry/en/address/adrsSetUserWizard.cgi` | High
33 | File | `/wp-json/oembed/1.0/embed?url` | High
34 | File | `4.edu.php` | Medium
35 | ... | ... | ...

There are 301 more IOA items available (file, library, argument, input value, pattern, network port). Please use our online service to access the data.

## References

The following list contains _external sources_ which discuss the actor and the associated activities:

* https://isc.sans.edu/forums/diary/Campaign+evolution+Hancitor+changes+its+Word+macros/24376/
* https://isc.sans.edu/forums/diary/Campaign+evolution+Hancitor+malspam+starts+pushing+Ursnif+this+week/24256/
* https://isc.sans.edu/forums/diary/Hancitor+activity+resumes+after+a+hoilday+break/26980/
* https://isc.sans.edu/forums/diary/Hancitor+distributed+through+coronavirusthemed+malspam/25892/
* https://isc.sans.edu/forums/diary/Hancitor+malspam+uses+DDE+attack/22936/
* https://isc.sans.edu/forums/diary/Hancitor+tries+XLL+as+initial+malware+file/27618/
* https://isc.sans.edu/forums/diary/HancitorPony+malspam/22053/
* https://isc.sans.edu/forums/diary/HancitorPonyVawtrak+malspam/21919/
* https://isc.sans.edu/forums/diary/June+2021+Forensic+Contest+Answers+and+Analysis/27582/
* https://isc.sans.edu/forums/diary/Malspam+pushing+Word+documents+with+Hancitor+malware/22858/
* https://isc.sans.edu/forums/diary/RTF+files+for+Hancitor+utilize+exploit+for+CVE201711882/23271/
* https://thedfirreport.com/2021/06/28/hancitor-continues-to-push-cobalt-strike/
* https://thedfirreport.com/2021/11/01/from-zero-to-domain-admin/

## Literature

The following _articles_ explain our unique predictive cyber threat intelligence:

* [VulDB Cyber Threat Intelligence Documentation](https://vuldb.com/?kb.cti)
* [Cyber Threat Intelligence - Early Anticipation of Attacks](https://www.scip.ch/en/?labs.20201022)

## License

(c) [1997-2022](https://vuldb.com/?kb.changelog) by [vuldb.com](https://vuldb.com/?kb.about). All data on this page is shared under the license [CC BY-NC-SA 4.0](https://creativecommons.org/licenses/by-nc-sa/4.0/). Questions? Check the [FAQ](https://vuldb.com/?kb.faq), read the [documentation](https://vuldb.com/?kb) or [contact us](https://vuldb.com/?contact)!
