# TA505 - Cyber Threat Intelligence

These _indicators_ were reported, collected, and generated during the [VulDB CTI analysis](https://vuldb.com/?kb.cti) of the actor known as [TA505](https://vuldb.com/?actor.ta505). The _activity monitoring_ correlates data from social media, forums, chat rooms, and darknet markets. It helps to determine associated actors, specific activities, expected intentions, emerging research, and ongoing attacks. Our unique _predictive model_ uses _big data_ to forecast activities and their characteristics.

_Live data_ and more _analysis capabilities_ are available at [https://vuldb.com/?actor.ta505](https://vuldb.com/?actor.ta505)

## Campaigns

The following _campaigns_ are known and can be associated with TA505:

* Ammyy
* SDBbot
* servhelper
* ...

There are 1 more campaign items available. Please use our online service to access the data.

## Countries

These _countries_ are directly (e.g. origin of attacks) or indirectly (e.g. access by proxy) associated with TA505:

* [US](https://vuldb.com/?country.us)
* [RU](https://vuldb.com/?country.ru)
* [CN](https://vuldb.com/?country.cn)
* ...

There are 17 more country items available. Please use our online service to access the data.

## IOC - Indicator of Compromise

These _indicators of compromise_ (IOC) indicate associated network resources which are known to be part of research and attack activities of TA505.

ID | IP address | Hostname | Campaign | Confidence
-- | ---------- | -------- | -------- | ----------
1 | [5.149.252.171](https://vuldb.com/?ip.5.149.252.171) | absolutecorporation.info | SDBbot | High
2 | [5.149.254.25](https://vuldb.com/?ip.5.149.254.25) | bmc.srv60.swdc.ams1.nl.fortunix.net | - | High
3 | [27.102.118.143](https://vuldb.com/?ip.27.102.118.143) | - | - | High
4 | [37.59.52.229](https://vuldb.com/?ip.37.59.52.229) | bemta-05.srv.sopeople.net | SDBbot | High
5 | [45.8.126.7](https://vuldb.com/?ip.45.8.126.7) | mail01.bivoic.com | SDBbot | High
6 | [45.63.101.210](https://vuldb.com/?ip.45.63.101.210) | 45.63.101.210.vultr.com | servhelper | Medium
7 | [45.76.206.149](https://vuldb.com/?ip.45.76.206.149) | 45.76.206.149.vultr.com | - | Medium
8 | [45.76.223.177](https://vuldb.com/?ip.45.76.223.177) | 45.76.223.177.vultr.com | - | Medium
9 | [45.77.16.211](https://vuldb.com/?ip.45.77.16.211) | 45.77.16.211.vultr.com | - | Medium
10 | [45.142.214.119](https://vuldb.com/?ip.45.142.214.119) | vm293088.pq.hosting | - | High
11 | [46.161.27.241](https://vuldb.com/?ip.46.161.27.241) | - | Servhelper/Flawedgrace | High
12 | ... | ... | ... | ...

There are 42 more IOC items available. Please use our online service to access the data.

## TTP - Tactics, Techniques, Procedures

_Tactics, techniques, and procedures_ (TTP) summarize the suspected MITRE ATT&CK techniques used by _TA505_. This data is unique as it uses our predictive model for actor profiling.

ID | Technique | Weakness | Description | Confidence
-- | --------- | -------- | ----------- | ----------
1 | T1059.007 | CWE-79, CWE-80 | Cross Site Scripting | High
2 | T1068 | CWE-264, CWE-266, CWE-284 | Execution with Unnecessary Privileges | High
3 | T1110.001 | CWE-798 | Improper Restriction of Excessive Authentication Attempts | High
4 | ... | ... | ... | ...

There are 6 more TTP items available. Please use our online service to access the data.

## IOA - Indicator of Attack

These _indicators of attack_ (IOA) list the potential fragments used for technical activities like reconnaissance, exploitation, privilege escalation, and exfiltration by TA505. This data is unique as it uses our predictive model for actor profiling.

ID | Type | Indicator | Confidence
-- | ---- | --------- | ----------
1 | File | `/admin/config.php?display=disa&view=form` | High
2 | File | `/cgi-bin/webproc` | High
3 | File | `/common/ticket_associated_tickets.php` | High
4 | File | `/crmeb/crmeb/services/UploadService.php` | High
5 | File | `/dus/shopliste/index.php` | High
6 | File | `/etc/path` | Medium
7 | File | `/etc/shadow` | Medium
8 | File | `/inc/parser/xhtml.php` | High
9 | File | `/include/chart_generator.php` | High
10 | File | `/modules/tasks/summary.inc.php` | High
11 | File | `/nagiosql/admin/checkcommands.php` | High
12 | File | `/rest/api/2/user/picker` | High
13 | File | `/secure/QueryComponent!Default.jspa` | High
14 | File | `/tmp` | Low
15 | File | `/ui/artifactimport/upload` | High
16 | File | `/uncpath/` | Medium
17 | File | `/usr/5bin/su` | Medium
18 | File | `/usr/bin/mail` | High
19 | File | `/usr/bin/pkexec` | High
20 | File | `/var/dt/` | Medium
21 | File | `/var/WEB-GUI/cgi-bin/telnet.cgi` | High
22 | File | `00.jsp` | Low
23 | File | `account_activations/edit` | High
24 | File | `adclick.php` | Medium
25 | File | `AddResolution.jspa` | High
26 | File | `admin.asp` | Medium
27 | File | `admin.jcomments.php` | High
28 | File | `admin.php` | Medium
29 | File | `admin/` | Low
30 | File | `admin/manage-comments.php` | High
31 | File | `administration/comments.php` | High
32 | File | `AdminViewError/AdminAddadmin` | High
33 | File | `agentdisplay.php` | High
34 | File | `ajax.php` | Medium
35 | File | `ajaxhelper.php` | High
36 | File | `album_portal.php` | High
37 | File | `al_initialize.php` | High
38 | File | `app/call_centers/cmd.php` | High
39 | File | `arch/x86/kvm/hyperv.c` | High
40 | File | `auction.cgi` | Medium
41 | ... | ... | ...

There are 350 more IOA items available (file, library, argument, input value, pattern, network port). Please use our online service to access the data.

## References

The following list contains _external sources_ which discuss the actor and the associated activities:

* https://documents.trendmicro.com/assets/TA505_tactics_HTML_RATs_techniques_latest_campaigns_appendix.pdf
* https://securityintelligence.com/posts/ta505-continues-to-infect-networks-with-sdbbot-rat/
* https://www.cybereason.com/blog/threat-actor-ta505-targets-financial-enterprises-using-lolbins-and-a-new-backdoor-malware
* https://www.deepinstinct.com/2019/04/02/new-servhelper-variant-employs-excel-4-0-macro-to-drop-signed-payload/
* https://www.proofpoint.com/us/threat-insight/post/leaked-ammyy-admin-source-code-turned-malware
* https://www.proofpoint.com/us/threat-insight/post/servhelper-and-flawedgrace-new-malware-introduced-ta505
* https://www.proofpoint.com/us/threat-insight/post/ta505-abusing-settingcontent-ms-within-pdf-files-distribute-flawedammyy-rat
* https://www.proofpoint.com/us/threat-insight/post/ta505-distributes-new-sdbbot-remote-access-trojan-get2-downloader
* https://www.zerofox.com/blog/ta505-halloween-malware/

## Literature

The following _articles_ explain our unique predictive cyber threat intelligence:

* [VulDB Cyber Threat Intelligence Documentation](https://vuldb.com/?kb.cti)
* [Cyber Threat Intelligence - Early Anticipation of Attacks](https://www.scip.ch/en/?labs.20201022)

## License

(c) [1997-2022](https://vuldb.com/?kb.changelog) by [vuldb.com](https://vuldb.com/?kb.about). All data on this page is shared under the license [CC BY-NC-SA 4.0](https://creativecommons.org/licenses/by-nc-sa/4.0/). Questions? Check the [FAQ](https://vuldb.com/?kb.faq), read the [documentation](https://vuldb.com/?kb) or [contact us](https://vuldb.com/?contact)!
