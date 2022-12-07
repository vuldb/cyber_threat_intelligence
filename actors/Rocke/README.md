# Rocke - Cyber Threat Intelligence

These _indicators_ were reported, collected, and generated during the [VulDB CTI analysis](https://vuldb.com/?kb.cti) of the actor known as [Rocke](https://vuldb.com/?actor.rocke). The _activity monitoring_ correlates data from social media, forums, chat rooms, and darknet markets. It helps to determine associated actors, specific activities, expected intentions, emerging research, and ongoing attacks. Our unique _predictive model_ uses _big data_ to forecast activities and their characteristics.

_Live data_ and more _analysis capabilities_ are available at [https://vuldb.com/?actor.rocke](https://vuldb.com/?actor.rocke)

## Countries

These _countries_ are directly (e.g. origin of attacks) or indirectly (e.g. access by proxy) associated with Rocke:

* [CN](https://vuldb.com/?country.cn)
* [US](https://vuldb.com/?country.us)
* [ES](https://vuldb.com/?country.es)
* ...

There are 2 more country items available. Please use our online service to access the data.

## IOC - Indicator of Compromise

These _indicators of compromise_ (IOC) indicate associated network resources which are known to be part of research and attack activities of Rocke.

ID | IP address | Hostname | Campaign | Confidence
-- | ---------- | -------- | -------- | ----------
1 | [23.234.4.151](https://vuldb.com/?ip.23.234.4.151) | - | - | High
2 | [23.234.4.153](https://vuldb.com/?ip.23.234.4.153) | - | - | High
3 | [27.193.180.224](https://vuldb.com/?ip.27.193.180.224) | - | - | High
4 | [27.210.170.197](https://vuldb.com/?ip.27.210.170.197) | - | - | High
5 | [27.221.28.231](https://vuldb.com/?ip.27.221.28.231) | - | - | High
6 | [27.221.54.252](https://vuldb.com/?ip.27.221.54.252) | - | - | High
7 | [36.103.236.221](https://vuldb.com/?ip.36.103.236.221) | - | - | High
8 | [36.103.247.121](https://vuldb.com/?ip.36.103.247.121) | - | - | High
9 | [36.248.26.205](https://vuldb.com/?ip.36.248.26.205) | - | - | High
10 | [42.56.76.104](https://vuldb.com/?ip.42.56.76.104) | - | - | High
11 | [42.202.141.230](https://vuldb.com/?ip.42.202.141.230) | - | - | High
12 | [42.236.125.84](https://vuldb.com/?ip.42.236.125.84) | hn.kd.ny.adsl | - | High
13 | [43.224.225.220](https://vuldb.com/?ip.43.224.225.220) | - | - | High
14 | [43.242.166.88](https://vuldb.com/?ip.43.242.166.88) | - | - | High
15 | [52.167.219.168](https://vuldb.com/?ip.52.167.219.168) | - | - | High
16 | [58.215.145.137](https://vuldb.com/?ip.58.215.145.137) | - | - | High
17 | [58.216.107.77](https://vuldb.com/?ip.58.216.107.77) | - | - | High
18 | ... | ... | ... | ...

There are 70 more IOC items available. Please use our online service to access the data.

## TTP - Tactics, Techniques, Procedures

_Tactics, techniques, and procedures_ (TTP) summarize the suspected MITRE ATT&CK techniques used by _Rocke_. This data is unique as it uses our predictive model for actor profiling.

ID | Technique | Weakness | Description | Confidence
-- | --------- | -------- | ----------- | ----------
1 | T1006 | CWE-21, CWE-22, CWE-23, CWE-24 | Pathname Traversal | High
2 | T1040 | CWE-294 | Authentication Bypass by Capture-replay | High
3 | T1055 | CWE-74 | Injection | High
4 | T1059 | CWE-88, CWE-94 | Cross Site Scripting | High
5 | ... | ... | ... | ...

There are 18 more TTP items available. Please use our online service to access the data.

## IOA - Indicator of Attack

These _indicators of attack_ (IOA) list the potential fragments used for technical activities like reconnaissance, exploitation, privilege escalation, and exfiltration by Rocke. This data is unique as it uses our predictive model for actor profiling.

ID | Type | Indicator | Confidence
-- | ---- | --------- | ----------
1 | File | `../FILEDIR` | Medium
2 | File | `.htaccess` | Medium
3 | File | `/about.php` | Medium
4 | File | `/Admin/dashboard.php` | High
5 | File | `/admin/login.php` | High
6 | File | `/admin/students/view_student.php` | High
7 | File | `/baseOpLog.do` | High
8 | File | `/cgi-bin/kerbynet` | High
9 | File | `/cgi-bin/webproc` | High
10 | File | `/cmscp/ext/collect/fetch_url.do` | High
11 | File | `/CommunitySSORedirect.jsp` | High
12 | File | `/coreframe/app/attachment/admin/index.php` | High
13 | File | `/ctpms/admin/?page=applications/view_application` | High
14 | File | `/debug/pprof` | Medium
15 | File | `/etc/quagga` | Medium
16 | File | `/gaia-job-admin/user/add` | High
17 | File | `/goform/form2WizardStep4` | High
18 | File | `/goform/setPptpUserList` | High
19 | File | `/HNAP1` | Low
20 | File | `/index.php` | Medium
21 | File | `/Items/*/RemoteImages/Download` | High
22 | File | `/modx/manager/` | High
23 | File | `/ofrs/admin/?page=user/manage_user` | High
24 | File | `/p1/p2/:name` | Medium
25 | File | `/php-sms/classes/Master.php?f=save_quote` | High
26 | File | `/proxy` | Low
27 | File | `/rdms/admin/?page=user/manage_user` | High
28 | File | `/recreate.php` | High
29 | File | `/redbin/rpwebutilities.exe/text` | High
30 | File | `/requests.php` | High
31 | File | `/saml/login` | Medium
32 | File | `/ScadaBR/login.htm` | High
33 | File | `/secure/QueryComponent!Default.jspa` | High
34 | File | `/sys/ui/extend/varkind/custom.jsp` | High
35 | File | `/system/sshkeys.js` | High
36 | File | `/template/edit` | High
37 | File | `/upload` | Low
38 | ... | ... | ...

There are 329 more IOA items available (file, library, argument, input value, pattern, network port). Please use our online service to access the data.

## References

The following list contains _external sources_ which discuss the actor and the associated activities:

* https://blog.talosintelligence.com/2018/08/rocke-champion-of-monero-miners.html
* https://blog.talosintelligence.com/2018/12/cryptomining-campaigns-2018.html
* https://unit42.paloaltonetworks.com/malware-used-by-rocke-group-evolves-to-evade-detection-by-cloud-security-products/
* https://unit42.paloaltonetworks.com/rockein-the-netflow/
* https://www.anomali.com/blog/rocke-evolves-its-arsenal-with-a-new-malware-family-written-in-golang

## Literature

The following _articles_ explain our unique predictive cyber threat intelligence:

* [VulDB Cyber Threat Intelligence Documentation](https://vuldb.com/?kb.cti)
* [Cyber Threat Intelligence - Early Anticipation of Attacks](https://www.scip.ch/en/?labs.20201022)

## License

(c) [1997-2022](https://vuldb.com/?kb.changelog) by [vuldb.com](https://vuldb.com/?kb.about). All data on this page is shared under the license [CC BY-NC-SA 4.0](https://creativecommons.org/licenses/by-nc-sa/4.0/). Questions? Check the [FAQ](https://vuldb.com/?kb.faq), read the [documentation](https://vuldb.com/?kb) or [contact us](https://vuldb.com/?contact)!
