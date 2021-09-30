# APT28 - Cyber Threat Intelligence

The indicators are related to [VulDB CTI analysis](https://vuldb.com/?doc.cti) of the actor known as [APT28](https://vuldb.com/?actor.apt28). The activity monitoring correlates data from social media, forums, chat rooms, and darknet markets. It helps to determine associated actors, activities, intentions, emerging research, and attacks. Our unique predictive model is able to forecast activities and their characteristics.

Live data and more analysis capabilities are available at [https://vuldb.com/?actor.apt28](https://vuldb.com/?actor.apt28)

## Campaigns

The following campaigns are known and can be associated with APT28:

* Carberp
* Fysbis
* Global Brute Force
* ...

There are 3 more campaign items available. Please use our online service to access the data.

## Countries

These countries are directly (e.g. origin of attacks) or indirectly (e.g. access by proxy) associated with APT28:

* US
* DE
* ES
* ...

There are 52 more country items available. Please use our online service to access the data.

## IOC - Indicator of Compromise

These indicators of compromise indicate associated network ressources which are known to be part of research and attack activities of APT28.

ID | IP address | Hostname | Confidence
-- | ---------- | -------- | ----------
1 | 5.63.153.177 | 5-63-153-177.ovz.vps.regruhosting.ru | High
2 | 5.100.155.82 | 5.100.155-82.publicdomainregistry.com | High
3 | 5.100.155.91 | 5.100.155-91.publicdomainregistry.com | High
4 | 5.135.183.154 | ns3290077.ip-5-135-183.eu | High
5 | 5.199.171.58 | - | High
6 | 23.163.0.59 | naomi.rem2d.com | High
7 | 23.227.196.21 | 23-227-196-21.static.hvvc.us | High
8 | 23.227.196.215 | 23-227-196-215.static.hvvc.us | High
9 | 23.227.196.217 | 23-227-196-217.static.hvvc.us | High
10 | 31.184.198.23 | - | High
11 | 31.184.198.38 | - | High
12 | 31.220.43.99 | - | High
13 | 31.220.61.251 | - | High
14 | 37.235.52.18 | 18.52.235.37.in-addr.arpa | High
15 | 45.32.129.185 | 45.32.129.185.vultr.com | Medium
16 | 45.32.227.21 | 45.32.227.21.mobiltel.mx | High
17 | 45.64.105.23 | - | High
18 | 45.124.132.127 | - | High
19 | 46.19.138.66 | ab2.alchibasystems.in.net | High
20 | 46.21.147.55 | 55.147.21.46.in-addr.arpa | High
21 | ... | ... | ...

There are 211 more IOC items available. Please use our online service to access the data.

## TTP - Tactics, Techniques, Procedures

Tactics, techniques, and procedures summarize the suspected ATT&CK techniques used by APT28. This data is unique as it uses our predictive model for actor profiling.

ID | Technique | Description | Confidence
-- | --------- | ----------- | ----------
1 | T1040 | Authentication Bypass by Capture-replay | High
2 | T1059.007 | Cross Site Scripting | High
3 | T1068 | Execution with Unnecessary Privileges | High
4 | T1110.001 | Improper Restriction of Excessive Authentication Attempts | High
5 | T1211 | 7PK Security Features | High
6 | ... | ... | ...

There are 10 more TTP items available. Please use our online service to access the data.

## IOA - Indicator of Attack

These indicators of attack list the potential fragments used for technical activities like reconnaissance, exploitation, privilege escalation, and exfiltration by APT28. This data is unique as it uses our predictive model for actor profiling.

ID | Type | Indicator | Confidence
-- | ---- | --------- | ----------
1 | File | `.htaccess` | Medium
2 | File | `.procmailrc` | Medium
3 | File | `/$({curl` | Medium
4 | File | `/+CSCOE+/logon.html` | High
5 | File | `/.env` | Low
6 | File | `/.ssh/authorized_keys` | High
7 | File | `/.vnc/sesman_${username}_passwd` | High
8 | File | `/account/details.php` | High
9 | File | `/admin.php` | Medium
10 | File | `/admin/adclass.php` | High
11 | ... | ... | ...

There are 2654 more IOA items available. Please use our online service to access the data.

## References

The following list contains external sources which discuss the actor and the associated activities:

* https://documents.trendmicro.com/assets/wp/wp-two-years-of-pawn-storm.pdf
* https://github.com/blackorbird/APT_REPORT/blob/master/APT28/IOC/2019-04-05-ioc-mark.txt
* https://github.com/blackorbird/APT_REPORT/blob/master/APT28/IOC/2019-04-09-ioc-mark.txt
* https://github.com/fireeye/iocs/blob/master/APT28/e1cbf7ca-4938-4d3c-a7e6-3ff966516191.ioc
* https://media.defense.gov/2020/Aug/13/2002476465/-1/-1/0/CSA_DROVORUB_RUSSIAN_GRU_MALWARE_AUG_2020.PDF
* https://media.defense.gov/2021/Jul/01/2002753896/-1/-1/1/CSA_GRU_GLOBAL_BRUTE_FORCE_CAMPAIGN_UOO158036-21.PDF
* https://msrc-blog.microsoft.com/2019/08/05/corporate-iot-a-path-to-intrusion/
* https://netzpolitik.org/2015/digital-attack-on-german-parliament-investigative-report-on-the-hack-of-the-left-party-infrastructure-in-bundestag/
* https://paper.seebug.org/papers/APT/APT_CyberCriminal_Campagin/2015/2015.11.04_Evolving_Threats/cct-w08_evolving-threats-dissection-of-a-cyber-espionage-attack.pdf
* https://unit42.paloaltonetworks.com/a-look-into-fysbis-sofacys-linux-backdoor/
* https://unit42.paloaltonetworks.com/dear-joohn-sofacy-groups-global-campaign/
* https://unit42.paloaltonetworks.com/unit42-new-sofacy-attacks-against-us-government-agency/
* https://unit42.paloaltonetworks.com/unit42-sofacy-continues-global-attacks-wheels-new-cannon-trojan/
* https://unit42.paloaltonetworks.com/unit42-sofacy-groups-parallel-attacks/
* https://unit42.paloaltonetworks.com/unit42-sofacys-komplex-os-x-trojan/
* https://unit42.paloaltonetworks.com/unit42-xagentosx-sofacys-xagent-macos-tool/
* https://www.accenture.com/t20181129T203820Z__w__/us-en/_acnmedia/PDF-90/Accenture-snakemackerel-delivers-zekapab-malware.pdf#zoom=50
* https://www.crowdstrike.com/blog/bears-midst-intrusion-democratic-national-committee/
* https://www.ncsc.gov.uk/files/NCSC_APT28.pdf
* https://www.threatminer.org/report.php?q=ASongofIntelandFancy_ExploitingFancyBear%E2%80%99suseofSSLcertificate.pdf&y=2018
* https://www.threatminer.org/report.php?q=eset-sednit-part-2-ESET.pdf&y=2016
* https://www.threatminer.org/report.php?q=eset-sednit-part1-ESET.pdf&y=2016
* https://www.threatminer.org/report.php?q=FancyBearcontinuetooperatethroughphishingemailsandmuchmore_ESET.pdf&y=2017
* https://www.threatminer.org/report.php?q=OperationRussianDoll.pdf&y=2015
* https://www.threatminer.org/report.php?q=TheDeceptionProjectANewJapanese-CentricThreat-Cylance.pdf&y=2017
* https://www.threatminer.org/report.php?q=ThreatConnectandFidelisTeamUptoExploretheDCCCBreach-ThreatConnect.pdf&y=2016
* https://www.threatminer.org/report.php?q=ThreatConnectIdentifiesFANCYBEARWorldAnti-DopingAgencyBreach-ThreatConnect.pdf&y=2016
* https://www.threatminer.org/report.php?q=wp-operation-pawn-storm.pdf&y=2014
* https://www.welivesecurity.com/2019/05/22/journey-zebrocy-land/
* https://www.welivesecurity.com/wp-content/uploads/2016/10/eset-sednit-part-2.pdf
* https://www.welivesecurity.com/wp-content/uploads/2016/10/eset-sednit-part3.pdf
* https://www.welivesecurity.com/wp-content/uploads/2018/09/ESET-LoJax.pdf

## Literature

The following articles explain our unique predictive cyber threat intelligence:

* [VulDB Cyber Threat Intelligence Documentation](https://vuldb.com/?doc.cti)
* [Cyber Threat Intelligence - Early Anticipation of Attacks](https://www.scip.ch/en/?labs.20201022)

## License

(c) [1997-2021](https://vuldb.com/?doc.changelog) by [vuldb.com](https://vuldb.com/?doc.about). All data on this page is shared under the license [CC BY-NC-SA 4.0](https://creativecommons.org/licenses/by-nc-sa/4.0/). Questions? Check the [FAQ](https://vuldb.com/?doc.faq), read the [documentation](https://vuldb.com/?doc) or [contact us](https://vuldb.com/?contact)!
