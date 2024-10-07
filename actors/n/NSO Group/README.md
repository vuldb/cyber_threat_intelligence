# NSO Group - Cyber Threat Intelligence

These _indicators_ were reported, collected, and generated during the [VulDB CTI analysis](https://vuldb.com/?kb.cti) of the actor known as [NSO Group](https://vuldb.com/?actor.nso_group). The _activity monitoring_ correlates data from social media, forums, chat rooms, and darknet markets. It helps to determine associated actors, specific activities, expected intentions, emerging research, and ongoing attacks. Our unique _predictive model_ uses _big data_ to forecast activities and their characteristics.

_Live data_ and more _analysis capabilities_ are available at [https://vuldb.com/?actor.nso_group](https://vuldb.com/?actor.nso_group)

## Campaigns

The following _campaigns_ are known and can be associated with NSO Group:

* Amnesty International Attacks
* Mansoor Attack
* Pegasus

## Countries

These _countries_ are directly (e.g. origin of attacks) or indirectly (e.g. access by proxy) associated with NSO Group:

* [DE](https://vuldb.com/?country.de)
* [US](https://vuldb.com/?country.us)
* [CH](https://vuldb.com/?country.ch)
* ...

There are 10 more country items available. Please use our online service to access the data.

## IOC - Indicator of Compromise

These _indicators of compromise_ (IOC) indicate associated network resources which are known to be part of research and attack activities of NSO Group.

ID | IP address | Hostname | Campaign | Confidence
-- | ---------- | -------- | -------- | ----------
1 | [3.13.132.96](https://vuldb.com/?ip.3.13.132.96) | ec2-3-13-132-96.us-east-2.compute.amazonaws.com | Pegasus | Medium
2 | [3.16.75.157](https://vuldb.com/?ip.3.16.75.157) | ec2-3-16-75-157.us-east-2.compute.amazonaws.com | Pegasus | Medium
3 | [13.58.85.100](https://vuldb.com/?ip.13.58.85.100) | ec2-13-58-85-100.us-east-2.compute.amazonaws.com | Pegasus | Medium
4 | [13.59.79.240](https://vuldb.com/?ip.13.59.79.240) | ec2-13-59-79-240.us-east-2.compute.amazonaws.com | Pegasus | Medium
5 | [18.191.63.125](https://vuldb.com/?ip.18.191.63.125) | ec2-18-191-63-125.us-east-2.compute.amazonaws.com | Pegasus | Medium
6 | [18.217.13.50](https://vuldb.com/?ip.18.217.13.50) | ec2-18-217-13-50.us-east-2.compute.amazonaws.com | Pegasus | Medium
7 | [18.225.12.72](https://vuldb.com/?ip.18.225.12.72) | ec2-18-225-12-72.us-east-2.compute.amazonaws.com | Pegasus | Medium
8 | [23.239.16.143](https://vuldb.com/?ip.23.239.16.143) | li685-143.members.linode.com | Pegasus | High
9 | [45.32.105.249](https://vuldb.com/?ip.45.32.105.249) | 45.32.105.249.vultrusercontent.com | Pegasus | Medium
10 | [45.60.241.11](https://vuldb.com/?ip.45.60.241.11) | - | - | High
11 | ... | ... | ... | ...

There are 42 more IOC items available. Please use our online service to access the data.

## TTP - Tactics, Techniques, Procedures

_Tactics, techniques, and procedures_ (TTP) summarize the suspected MITRE ATT&CK techniques used by _NSO Group_. This data is unique as it uses our predictive model for actor profiling.

ID | Technique | Weakness | Description | Confidence
-- | --------- | -------- | ----------- | ----------
1 | T1006 | CWE-21, CWE-22, CWE-23, CWE-24, CWE-35 | Path Traversal | High
2 | T1040 | CWE-294, CWE-319 | Authentication Bypass by Capture-replay | High
3 | T1055 | CWE-74 | Improper Neutralization of Data within XPath Expressions | High
4 | T1059 | CWE-88, CWE-94, CWE-1321 | Argument Injection | High
5 | T1059.007 | CWE-79, CWE-80 | Cross Site Scripting | High
6 | ... | ... | ... | ...

There are 22 more TTP items available. Please use our online service to access the data.

## IOA - Indicator of Attack

These _indicators of attack_ (IOA) list the potential fragments used for technical activities like reconnaissance, exploitation, privilege escalation, and exfiltration by NSO Group. This data is unique as it uses our predictive model for actor profiling.

ID | Type | Indicator | Confidence
-- | ---- | --------- | ----------
1 | File | `.ssh/authorized_keys` | High
2 | File | `/admin/#maintenance_sysTask/edit` | High
3 | File | `/admin/?/snippet/edit/3` | High
4 | File | `/admin/action/add_con.php` | High
5 | File | `/admin/action/new-feed.php` | High
6 | File | `/admin/ajax.php?action=login` | High
7 | File | `/admin/app` | Medium
8 | File | `/admin/ballot_down.php` | High
9 | File | `/admin/cmsWebFile/doUpload` | High
10 | File | `/admin/config_save.php` | High
11 | File | `/admin/domain_management.php?id=0&list=whitelist&remove=pligg.com` | High
12 | File | `/admin/edit_visitor.php` | High
13 | File | `/admin/info.php` | High
14 | File | `/admin/plugin.php` | High
15 | File | `/admin/template.php` | High
16 | File | `/admin/template/update` | High
17 | File | `/admin/userSys_deal.php?mudi=infoSet` | High
18 | File | `/alphaware/summary.php` | High
19 | File | `/api/monitors/import` | High
20 | File | `/api/sys/login` | High
21 | File | `/application/index/controller/Unity.php` | High
22 | File | `/apply.cgi` | Medium
23 | File | `/cgi-bin/cstecgi.cgi` | High
24 | File | `/cgi-bin/cstecgi.cgi?action=login&flag=1` | High
25 | File | `/cgi-bin/koha/catalogue/search.pl` | High
26 | File | `/cgi-bin/webdav_mgr.cgi` | High
27 | File | `/classes/Master.php?f=delete_inquiry` | High
28 | File | `/classes/Users.php` | High
29 | File | `/cupseasylive/grndisplay.php` | High
30 | File | `/dashboard/updatelogo.php` | High
31 | File | `/dipam/save-delegates.php` | High
32 | File | `/ecommerce/support_ticket` | High
33 | File | `/etc/controller-agent/agent.conf` | High
34 | File | `/etc/openshift/server_priv.pem` | High
35 | File | `/forms/web_importTFTP` | High
36 | File | `/forum/away.php` | High
37 | File | `/front/admin/tenancyDetail.php` | High
38 | File | `/goform/GetParentControlInfo` | High
39 | File | `/goform/SetSysTimeCfg` | High
40 | File | `/goform/SysToolReboot` | High
41 | ... | ... | ...

There are 352 more IOA items available (file, library, argument, input value, pattern, network port). Please use our online service to access the data.

## References

The following list contains _external sources_ which discuss the actor and the associated activities:

* https://citizenlab.ca/2016/08/million-dollar-dissident-iphone-zero-day-nso-group-uae/
* https://citizenlab.ca/2018/07/nso-spyware-targeting-amnesty-international/
* https://citizenlab.ca/2021/08/bahrain-hacks-activists-with-nso-group-zero-click-iphone-exploits/
* https://citizenlab.ca/2022/07/geckospy-pegasus-spyware-used-against-thailands-pro-democracy-movement/
* https://www.amnesty.org/en/latest/research/2021/07/forensic-methodology-report-how-to-catch-nso-groups-pegasus/
* https://www.nsogroup.com

## Literature

The following _articles_ explain our unique predictive cyber threat intelligence:

* [VulDB Cyber Threat Intelligence Documentation](https://vuldb.com/?kb.cti)
* [Cyber Threat Intelligence - Early Anticipation of Attacks](https://www.scip.ch/en/?labs.20201022)

## License

(c) [1997-2024](https://vuldb.com/?kb.changelog) by [vuldb.com](https://vuldb.com/?kb.about). All data on this page is shared under the license [CC BY-NC-SA 4.0](https://creativecommons.org/licenses/by-nc-sa/4.0/). Questions? Check the [FAQ](https://vuldb.com/?kb.faq), read the [documentation](https://vuldb.com/?kb) or [contact us](https://vuldb.com/?contact)!
