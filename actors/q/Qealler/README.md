# Qealler - Cyber Threat Intelligence

These _indicators_ were reported, collected, and generated during the [VulDB CTI analysis](https://vuldb.com/?kb.cti) of the actor known as [Qealler](https://vuldb.com/?actor.qealler). The _activity monitoring_ correlates data from social media, forums, chat rooms, and darknet markets. It helps to determine associated actors, specific activities, expected intentions, emerging research, and ongoing attacks. Our unique _predictive model_ uses _big data_ to forecast activities and their characteristics.

_Live data_ and more _analysis capabilities_ are available at [https://vuldb.com/?actor.qealler](https://vuldb.com/?actor.qealler)

## Countries

These _countries_ are directly (e.g. origin of attacks) or indirectly (e.g. access by proxy) associated with Qealler:

* [US](https://vuldb.com/?country.us)
* [NL](https://vuldb.com/?country.nl)
* [GB](https://vuldb.com/?country.gb)
* ...

There are 20 more country items available. Please use our online service to access the data.

## IOC - Indicator of Compromise

These _indicators of compromise_ (IOC) indicate associated network resources which are known to be part of research and attack activities of Qealler.

ID | IP address | Hostname | Campaign | Confidence
-- | ---------- | -------- | -------- | ----------
1 | [79.143.87.120](https://vuldb.com/?ip.79.143.87.120) | bairdroome.info | - | High
2 | [139.59.76.44](https://vuldb.com/?ip.139.59.76.44) | server1.agorimtech.com | - | High
3 | [146.185.139.123](https://vuldb.com/?ip.146.185.139.123) | - | - | High
4 | ... | ... | ... | ...

There are 4 more IOC items available. Please use our online service to access the data.

## TTP - Tactics, Techniques, Procedures

_Tactics, techniques, and procedures_ (TTP) summarize the suspected MITRE ATT&CK techniques used by _Qealler_. This data is unique as it uses our predictive model for actor profiling.

ID | Technique | Weakness | Description | Confidence
-- | --------- | -------- | ----------- | ----------
1 | T1006 | CWE-21, CWE-22, CWE-425 | Path Traversal | High
2 | T1040 | CWE-319 | Authentication Bypass by Capture-replay | High
3 | T1055 | CWE-74 | Improper Neutralization of Data within XPath Expressions | High
4 | T1059 | CWE-88, CWE-94 | Argument Injection | High
5 | T1059.007 | CWE-79, CWE-80 | Basic Cross Site Scripting | High
6 | T1068 | CWE-264, CWE-266, CWE-269, CWE-271, CWE-284 | Execution with Unnecessary Privileges | High
7 | ... | ... | ... | ...

There are 23 more TTP items available. Please use our online service to access the data.

## IOA - Indicator of Attack

These _indicators of attack_ (IOA) list the potential fragments used for technical activities like reconnaissance, exploitation, privilege escalation, and exfiltration by Qealler. This data is unique as it uses our predictive model for actor profiling.

ID | Type | Indicator | Confidence
-- | ---- | --------- | ----------
1 | File | `.procmailrc` | Medium
2 | File | `/+CSCOE+/logon.html` | High
3 | File | `/.env` | Low
4 | File | `/?ajax-request=jnews` | High
5 | File | `/Admin/login.php` | High
6 | File | `/api/blade-user/export-user` | High
7 | File | `/api/cron/settings/setJob/` | High
8 | File | `/api/swaggerui/static` | High
9 | File | `/api/v1/users/{user_name_or_id}/activate` | High
10 | File | `/api/v2/cli/commands` | High
11 | File | `/bin/boa` | Medium
12 | File | `/cachesys/csp` | High
13 | File | `/cas/logout` | Medium
14 | File | `/cgi-bin/cstecgi.cgi` | High
15 | File | `/cgi-bin/mesh.cgi?page=upgrade` | High
16 | File | `/cgi-bin/nas_sharing.cgi` | High
17 | File | `/cgi-bin/photocenter_mgr.cgi` | High
18 | File | `/cgi-bin/supervisor/PwdGrp.cgi` | High
19 | File | `/cgi-bin/wlogin.cgi` | High
20 | File | `/classes/Users.php?f=save` | High
21 | File | `/common/info.cgi` | High
22 | File | `/context.json` | High
23 | File | `/core/vb/vurl.php` | High
24 | File | `/dashboard/snapshot/*?orgId=0` | High
25 | File | `/dl/dl_print.php` | High
26 | File | `/etc/shadow.sample` | High
27 | File | `/export` | Low
28 | File | `/foms/routers/place-order.php` | High
29 | File | `/forum/away.php` | High
30 | File | `/gaia-job-admin/user/add` | High
31 | File | `/home.jsp` | Medium
32 | File | `/hrm/controller/employee.php` | High
33 | File | `/icingaweb2/navigation/add` | High
34 | File | `/importexport.php` | High
35 | File | `/include/chart_generator.php` | High
36 | File | `/index.php` | Medium
37 | File | `/iwgallery/pictures/details.asp` | High
38 | File | `/librarian/bookdetails.php` | High
39 | File | `/log/download.php` | High
40 | File | `/Log/Query?appid=0B736354-9473-4D66-B9C0-15CAC149EB05&tabid=tab_0B73635494734D66B9C015CAC149EB05` | High
41 | File | `/login` | Low
42 | File | `/login.php` | Medium
43 | File | `/loginsave.php` | High
44 | File | `/LogoStore/search.php` | High
45 | File | `/MTFWU` | Low
46 | File | `/new` | Low
47 | ... | ... | ...

There are 408 more IOA items available (file, library, argument, input value, pattern, network port). Please use our online service to access the data.

## References

The following list contains _external sources_ which discuss the actor and the associated activities:

* https://github.com/jeFF0Falltrades/IoCs/blob/master/Broadbased/qealler_rat.md
* https://threatfox.abuse.ch
* https://twitter.com/BushidoToken/status/1375226105058189316
* https://twitter.com/wwp96/status/1338893270437552129

## Literature

The following _articles_ explain our unique predictive cyber threat intelligence:

* [VulDB Cyber Threat Intelligence Documentation](https://vuldb.com/?kb.cti)
* [Cyber Threat Intelligence - Early Anticipation of Attacks](https://www.scip.ch/en/?labs.20201022)

## License

(c) [1997-2026](https://vuldb.com/?kb.changelog) by [vuldb.com](https://vuldb.com/?kb.about). All data on this page is shared under the license [CC BY-NC-SA 4.0](https://creativecommons.org/licenses/by-nc-sa/4.0/). Questions? Check the [FAQ](https://vuldb.com/?kb.faq), read the [documentation](https://vuldb.com/?kb) or [contact us](https://vuldb.com/?contact)!
