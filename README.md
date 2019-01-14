# MARADJS
(Machine Learning Repository Applied to Dynamic JavaScript Files Analysis)

## Limitation of Commercial Antiviruses

In spite of being questioned there is more than one decade, the modus operandi of the antiviruses is based on signatures when the suspicious file is consulted in databases named blacklist. Therefore, it is only necessary that the hash of the suspect record is not detected by the antivirus so that the malware is not recognized. The hash acts as an exclusive identifier for a specific record. So, knowing the limitations of the commercial antiviruses, it is not a complicated assignment to make and convey variations of a malicious application. To do this, it is sufficient to form small changes to the first malware with routines that, effectively, have no utility for the program, such as repetition loops and conditional deviations without enlightening in their systems. These futile alterations, however, make the hash of the malware changed from the first malware hash. Thus, malware, expanded with broken schedules, will not be recognized by the antivirus, which cataloged the first noxious record. It is widely known that there are botnets capable for creating and conveying variations, in a computerized way, of the same unique malware. We conclude that antiviruses, based on signatures, have no action when submitted to variations of the same malware.

Through the platform VirusTotal, the proposed work investigates 86 commercial antivirus with their respective results presented in Table 1. We have utilized 990 malicious JavaScript collected from the MARADJS database. The objective of this paper is to check the number of virtual threats cataloged by the antiviruses. The inspiration is that the unused virtual plagues play a crucial part in combating malevolent applications. Then, the bigger the database of malware, named blacklist, the superior the defense given by the antivirus. Fig. 1 gives the chart of the strategy proposed in block graph. At first, JavaScrits malware records are submitted to the VirusTotal service server. After that, JS files are checked by the 86 commercial antiviruses connected to VirusTotal. In this way, antivirus computer program gives its diagnostics for JS files submitted to the platform. VirusTotal allows the issuance of three diverse sorts of diagnostics: malware, benign and omission.

The first option of VirusTotal, the antivirus analyzes the harm of the suspicious file. Within the proposed exploratory environment, all submitted records are malware cataloged by occurrence responders. Before long, the antivirus hits when it identifies the threat of the file being explored. Malware discovery shows that your antivirus gives a dependable benefit against cyber-intrusions. In the second option, within the proposed paper, when the antivirus detected the benignity of the file, it is a situation of a false negative, since all files are malicious. This means that the file being explored is malware, but the antivirus confirms to benignity wrongly. In the last option, the antivirus does not emanate opinion around the suspicious file. The omission shows that the file filtered has never been checked by the antivirus so it has small robustness to check it at runtime. The omission of the determination by the antivirus shows to its acition limitation on large-scale systems.

Table 1 gives the results about of the 86 commercial antiviruses assessed. Kaspersky and ZoneAlarm antivirus accomplished the most excellent detections, being able to identify 99.40% of the malware examined. A major issue in combating malicious applications is the truth that antivirus engineers do not share their particular dark records of malware due to commercial questions. Through Table 1 the proposed paper focuses to an exasperating figure of this issue; the same antivirus merchant does not indeed unveil its databases between its distinctive antivirus programs. Note, for case, that the K7GW (Enterprise Version) and K7AntiVirus antiviruses belongs to the same company, but their malicious database are not shared with each other. In this manner, the commercial issues, of a same company, they do not help the combat against malwares. It complements that antivirus sellers are not fundamentally concerned with dodging cyber-invasions, but with maximizing their profits. 

Malware discovery vary from 0% to 99.40%, depending of the antivirus. On average, the 86 antiviruses were able to identify 42.17% of malware assessed, with a standard deviation of 45.44. The tall standard deviation shows that the detection of malicious samples can shift significantly depending on the antivirus chosen. It is concluded that the assurance, against cyber attacks, is due to the choice of a vigorous antivirus bolstered by an expansive and upgraded blacklist. On average, the antivirus detailed false negatives in 25.56% of the cases, with a standard deviation of 38.97. To set the benignity of malware can involve in unrecoverable harms. An individual or institution, for instance, would trust on a specific malicious application when, in truth, it is malware. On average, antiviruses were omitted in 32.27% of the tests, with a standard deviation of 45.91. The omission of the examination shows the limitation of the antivirus within the location of malwares at run time.

It is included as difficulty within the battle against malicious applications that commercial antiviruses do not hold a standard malware classification as seen in Table 2. We chose 3 of 990 JavaScrits malware to illustrate the different of given evaluations by commercial antivirus. As there is no standard, antiviruses grant the names they need, for example a company might to define a JS malware as "JS/Nemucod.fg" and another company recognizes it as "Trojan.Script.ExpKit.ededny". So, the absence of a standard hampers cyber-surveillance methodologies since each category of malware must have distinctive medicines (vaccines). We concluded that it is almost impossible that a supervised machine learning uses pattern recognition to categories of JS malicious. Since of that confounding tangle of MultiClass Classification, given by antiviruses as seen inTable 2 is measurably difficult that any machine learning procedure will get generalization capability.

###### Table 1 – Results of 86 commercial antiviruses.

| Antivirus            | Detection (%) | False negative (%) | Omission (%) |
|----------------------|---------------|--------------------|--------------|
| Kaspersky            | 99.40         | 0.30               | 0.30         |
| ZoneAlarm            | 99.40         | 0.10               | 0.50         |
| NANO-Antivirus       | 99.20         | 0.40               | 0.40         |
| McAfee               | 99.00         | 1.00               | 0.00         |
| Sophos               | 99.00         | 1.00               | 0.00         |
| Avira                | 99.00         | 0.30               | 0.70         |
| Cyren                | 98.90         | 0.80               | 0.30         |
| Ad-Aware             | 98.70         | 0.80               | 0.50         |
| Arcabit              | 98.60         | 1.40               | 0.00         |
| Fortinet             | 98.60         | 1.20               | 0.20         |
| MicroWorld-eScan     | 98.60         | 1.20               | 0.20         |
| Emsisoft             | 98.50         | 0.80               | 0.70         |
| MAX                  | 98.50         | 0.50               | 1.00         |
| Avast                | 98.40         | 1.60               | 0.00         |
| AVG                  | 98.40         | 1.60               | 0.00         |
| ESET-NOD32           | 98.40         | 1.60               | 0.00         |
| McAfee-GW-Edition    | 98.30         | 1.50               | 0.20         |
| Microsoft            | 98.20         | 1.80               | 0.00         |
| BitDefender          | 97.90         | 0.60               | 1.50         |
| Qihoo-360            | 97.50         | 1.10               | 1.40         |
| ALYac                | 97.40         | 0.60               | 2.00         |
| GData                | 95.60         | 1.80               | 2.60         |
| Symantec             | 95.30         | 4.50               | 0.20         |
| Tencent              | 94.80         | 4.70               | 0.50         |
| Baidu                | 94.60         | 3.80               | 1.60         |
| AegisLab             | 92.70         | 5.70               | 1.60         |
| TrendMicro-HouseCall | 92.40         | 5.70               | 1.90         |
| F-Secure             | 90.00         | 9.90               | 0.10         |
| Rising               | 88.50         | 10.20              | 1.30         |
| Ikarus               | 87.70         | 7.90               | 4.40         |
| CAT-QuickHeal        | 86.80         | 13.10              | 0.10         |
| TrendMicro           | 86.60         | 9.30               | 4.10         |
| AVware               | 85.10         | 14.50              | 0.40         |
| VIPRE                | 84.90         | 14.20              | 0.90         |
| AhnLab-V3            | 75.30         | 24.70              | 0.00         |
| F-Prot               | 72.90         | 26.80              | 0.30         |
| DrWeb                | 64.00         | 36.00              | 0.00         |
| Comodo               | 46.40         | 53.50              | 0.10         |
| Antiy-AVL            | 30.90         | 65.80              | 3.30         |
| Jiangmin             | 30.00         | 69.20              | 0.80         |
| ViRobot              | 28.20         | 71.70              | 0.10         |
| ClamAV               | 6.30          | 92.90              | 0.80         |
| Zillya               | 6.20          | 90.70              | 3.10         |
| K7AntiVirus          | 5.80          | 94.10              | 0.10         |
| K7GW                 | 5.80          | 94.00              | 0.20         |
| VBA32                | 3.60          | 96.10              | 0.30         |
| Panda                | 3.30          | 96.70              | 0.00         |
| Bkav                 | 2.00          | 97.70              | 0.30         |
| Zoner                | 0.50          | 99.00              | 0.50         |
| Yandex               | 0.20          | 99.70              | 0.10         |
| Kingsoft             | 0.00          | 99.90              | 0.10         |
| SUPERAntiSpyware     | 0.00          | 99.80              | 0.20         |
| TheHacker            | 0.00          | 99.70              | 0.30         |
| TotalDefense         | 0.00          | 99.70              | 0.30         |
| nProtect             | 0.00          | 99.60              | 0.40         |
| CMC                  | 0.00          | 99.50              | 0.50         |
| Malwarebytes         | 0.00          | 97.80              | 2.20         |
| WhiteArmor           | 0.00          | 97.10              | 2.90         |
| Webroot              | 0.00          | 70.00              | 30.00        |
| Paloalto             | 0.00          | 0.50               | 99.50        |
| Endgame              | 0.00          | 0.20               | 99.80        |
| Invincea             | 0.00          | 0.20               | 99.80        |
| Agnitum              | 0.00          | 0.00               | 100.00       |
| ahnlab               | 0.00          | 0.00               | 100.00       |
| Alibaba              | 0.00          | 0.00               | 100.00       |
| AntiVir              | 0.00          | 0.00               | 100.00       |
| a-squared            | 0.00          | 0.00               | 100.00       |
| Authentium           | 0.00          | 0.00               | 100.00       |
| ByteHero             | 0.00          | 0.00               | 100.00       |
| Command              | 0.00          | 0.00               | 100.00       |
| Commtouch            | 0.00          | 0.00               | 100.00       |
| CrowdStrike          | 0.00          | 0.00               | 100.00       |
| Cylance              | 0.00          | 0.00               | 100.00       |
| eSafe                | 0.00          | 0.00               | 100.00       |
| eTrust-Vet           | 0.00          | 0.00               | 100.00       |
| Ewido                | 0.00          | 0.00               | 100.00       |
| FileAdvisor          | 0.00          | 0.00               | 100.00       |
| NOD32                | 0.00          | 0.00               | 100.00       |
| Norman               | 0.00          | 0.00               | 100.00       |
| PCTools              | 0.00          | 0.00               | 100.00       |
| Prevx                | 0.00          | 0.00               | 100.00       |
| SAVMail              | 0.00          | 0.00               | 100.00       |
| SentinelOne          | 0.00          | 0.00               | 100.00       |
| Sunbelt              | 0.00          | 0.00               | 100.00       |
| VirusBuster          | 0.00          | 0.00               | 100.00       |
| Webwasher-Gateway    | 0.00          | 0.00               | 100.00       |

###### Table 2 – Miscellaneous classifications of commercial antiviruses.

| Antivirus            | 20160325_700f670c9dbcd83a0ff2745728b59999   | 20160325_114dfa25f5c2d0ef5579a5bf69f27838   | 20151210_885e2f78e18c980debab1b1800c360a2    |
|----------------------|---------------------------------------------|---------------------------------------------|----------------------------------------------|
| McAfee-GW-Edition    | JS/Nemucod.fg                               | JS/Nemucod.fg                               | Benign                                       |
| NANO-Antivirus       | Trojan.Script.ExpKit.ededny                 | Trojan.Script.Nemucod.ebkagz                | Trojan.Script.Kryptik.dzcqji                 |
| AegisLab             | Js.Locky.Gen!c                              | Troj.Js.Agent!c                             | Omission                                     |
| Kaspersky            | HEUR:Exploit.Script.Generic                 | Trojan-Downloader.JS.Cryptoload.nz          | Trojan-Downloader.JS.Cryptoload.at           |
| ZoneAlarm            | HEUR:Exploit.Script.Generic                 | Trojan-Downloader.JS.Cryptoload.nz          | Trojan-Downloader.JS.Cryptoload.at           |
| Avast                | Benign                                      | Other:Malware-gen [Trj]                     | JS:Decode-CFZ [Trj]                          |
| AVG                  | Benign                                      | Other:Malware-gen [Trj]                     | JS:Decode-CFZ [Trj]                          |
| ESET-NOD32           | JS/TrojanDownloader.Nemucod.ML              | JS/TrojanDownloader.Nemucod.ML              | JS/TrojanDownloader.Nemucod.CI               |
| McAfee               | JS/Nemucod.fg                               | JS/Nemucod.fg                               | Benign                                       |
| Avira                | JS/Dldr.Locky.LM                            | JS/Dldr.Locky.LM                            | HTML/ExpKit.Gen2                             |
| Sophos AV            | Troj/JsDwnLdr-J                             | Troj/JsDwnLdr-J                             | Troj/Dloadr-EAH                              |
| Symantec             | JS.Downloader                               | JS.Downloader                               | JS.Downloader                                |
| Ikarus               | Trojan-Ransom.Script.Locky                  | Trojan-Ransom.Script.Locky                  | Trojan-Ransom.Script.Nemucod                 |
| MAX                  | malware (ai score=85)                       | malware (ai score=100)                      | Malware (ai score=84)                        |
| TrendMicro-HouseCall | JS_LOCKY.BO                                 | JS_LOCKY.BO                                 | Benign                                       |
| Emsisoft             | Generic.JS.DownloaderK.4D92FC2D (B)         | Trojan.JS.Agent.KML (B)                     | JS:Trojan.Crypt.NR (B)                       |
| GData                | Script.Trojan.Obfus.V@gen                   | Script.Trojan.Obfus.V@gen                   | Omission                                     |
| BitDefender          | Generic.JS.DownloaderK.4D92FC2D             | Trojan.JS.Agent.KML                         | Omission                                     |
| Tencent              | Js.Trojan-downloader.Js.Szbs                | Heur:Trojan.Script.Generic.7028554.0        | Js.Trojan-downloader.Cryptoload.Dyfx         |
| Arcabit              | HEUR.JS.Trojan.b                            | HEUR.JS.Trojan.b                            | JS:Trojan.Crypt.NR                           |
| MicroWorld-eScan     | Omission                                    | Omission                                    | Omission                                     |
| Microsoft            | TrojanDownloader:JS/Nemucod                 | TrojanDownloader:JS/Nemucod                 | TrojanDownloader:JS/Swabfex                  |
| Ad-Aware             | Generic.JS.DownloaderK.4D92FC2D             | Trojan.JS.Agent.KML                         | JS:Trojan.Crypt.NR                           |
| DrWeb                | Benign                                      | JS.DownLoader.2766                          | Benign                                       |
| TrendMicro-HouseCall | JS_LOCKY.BO                                 | JS_LOCKY.BO                                 | Benign                                       |
| Zillya               | Benign                                      | Benign                                      | Omission                                     |
| VBA32                | Benign                                      | Benign                                      | Benign                                       |
| Cyren                | JS/Tescrypt.A!Camelot                       | JS/Tescrypt.A!Camelot                       | Benign                                       |
| F-Prot               | Benign                                      | Benign                                      | JS/Downldr.CZ.gen                            |
| Comodo               | Benign                                      | Benign                                      | Benign                                       |
| F-Secure             | Generic.JS.DownloaderK.4D92FC2D             | Trojan.JS.Agent.KML                         | JS:Trojan.Crypt.NR                           |
| TotalDefense         | Benign                                      | Benign                                      | Benign                                       |
| Yandex               | Benign                                      | Benign                                      | Benign                                       |
| CAT-QuickHeal        | Benign                                      | JS.Swabfex.GP                               | Benign                                       |
| Jiangmin             | Benign                                      | TrojanDownloader.JS.baoj                    | TrojanDownloader.JS.wc                       |
| Qihoo-360            | trojan.js.downloader.1                      | trojan.js.downloader.1                      | js.url.downloader.c                          |
| AhnLab-V3            | JS/Downloader                               | JS/Downloader                               | JS/Downloader                                |
| ClamAV               | Benign                                      | Benign                                      | Omission                                     |
| Fortinet             | JS/Nemucod.BF21!tr                          | JS/Nemucod.BF21!tr                          | JS/Nemucod.CI!tr                             |
| AVware               | Benign                                      | Benign                                      | Trojan-Downloader.JS.Agent.csz (v)           |
| K7GW                 | Benign                                      | Benign                                      | Benign                                       |
| K7AntiVirus          | Benign                                      | Benign                                      | Trojan ( 0001140e1 )                         |
| Antiy-AVL            | Trojan/Win32.TGeneric                       | Trojan/Win32.TGeneric                       | Omission                                     |
| Webroot              | Omission                                    | Benign                                      | Omission                                     |
| Panda                | Benign                                      | Benign                                      | JS/Downloader.WMJ                            |
| ViRobot              | JS.S.Downloader.4266                        | JS.S.Downloader.4335                        | Benign                                       |
| Rising               | Downloader.Nemucod!8.34 (TOPIS:sjCy6UIBc2I) | Downloader.Nemucod!8.34 (TOPIS:NAWJv5cr2FR) | Downloader.Swabfex!8.3DE (TOPIS:YwJeGiQGF9H) |
| TheHacker            | Benign                                      | Benign                                      | Omission                                     |
| Kingsoft             | Benign                                      | Benign                                      | Benign                                       |
| Invincea             | Omission                                    | Omission                                    | Omission                                     |
| Zoner                | Benign                                      | Benign                                      | Benign                                       |
| Baidu                | JS.Trojan.Nemucod.ca                        | JS.Trojan.Nemucod.ca                        | Omission                                     |
| VIPRE                | Benign                                      | Benign                                      | Trojan-Downloader.JS.Agent.csz (v)           |
| Malwarebytes         | Benign                                      | Benign                                      | Omission                                     |
| Cylance              | Omission                                    | Omission                                    | Omission                                     |
| WhiteArmor           | Benign                                      | Benign                                      | Benign                                       |
| Alibaba              | Omission                                    | Omission                                    | Omission                                     |
| ALYac                | Trojan.JS.Downloader.Agent                  | Trojan.JS.Downloader.Agent                  | JS:Trojan.Crypt.NR                           |
| Bkav                 | Benign                                      | Benign                                      | Benign                                       |
| Paloalto             | Omission                                    | Omission                                    | Omission                                     |
| SentinelOne          | Omission                                    | Omission                                    | Omission                                     |
| Endgame              | Omission                                    | Omission                                    | Omission                                     |
| CrowdStrike Falcon   | Omission                                    | Omission                                    | Omission                                     |
| Agnitum              | Omission                                    | Omission                                    | Omission                                     |
| ByteHero             | Omission                                    | Omission                                    | Omission                                     |
| Norman               | Omission                                    | Omission                                    | Omission                                     |
| Ahnlab-V3            | JS/Downloader                               | JS/Downloader                               | JS/Downloader                                |
| AntiVir              | Omission                                    | Omission                                    | Omission                                     |
| Commtouch            | Omission                                    | Omission                                    | Omission                                     |
| VirusBuster          | Omission                                    | Omission                                    | Omission                                     |
| ESET- NOD32          | JS/TrojanDownloader.Nemucod.ML              | Omission                                    | Omission                                     |
| eSafe                | Omission                                    | Omission                                    | Omission                                     |
| eTrust-Vet           | Omission                                    | Omission                                    | Omission                                     |
| Authentium           | Omission                                    | Omission                                    | Omission                                     |
| Prevx                | Omission                                    | Omission                                    | Omission                                     |
| Sunbelt              | Omission                                    | Omission                                    | Omission                                     |
| PCTools              | Omission                                    | Omission                                    | Omission                                     |
| a-squared            | Omission                                    | Omission                                    | Omission                                     |
| Command              | Omission                                    | Omission                                    | Omission                                     |
| SAVMail              | Omission                                    | Omission                                    | Omission                                     |
| FileAdvisor          | Omission                                    | Omission                                    | Omission                                     |
| Ewido                | Omission                                    | Omission                                    | Omission                                     |
| Webwasher-Gateway    | Omission                                    | Omission                                    | Omission                                     |
| CMC                  | Benign                                      | Benign                                      | Benign                                       |
| nProtect             | Benign                                      | Benign                                      | Omission                                     |
| SUPERAntiSpyware     | Benign                                      | Benign                                      | Benign                                       |

## Materials and Methods

This paper aims to elaborate the MARADJS (Machine Learning Repository Applied to Dynamic JavaScript Files Analysis), a database that allows the classification of .js files between malicious and benigns. MARADJS consists of 990 JavaScript files malware and 990 other benign JavaScript files. The MARADJS database, therefore, is suitable for learning with machine learning, considering that the js files presented the same amount in the different classes (benign and malwares). The aim is that biased classifiers, in relation to a certain class, do not have their favoring rates favored.

In relation to virtual plagues, MARADJS extracted malicious JavaScript files from Github which is a repository of malware samples to provide security researchers, incident responders, forensic analysts, and the morbidly curious access to samples of live malicious code. With regard to benign .js files, the catalog was given from the application repository JQuery Plugin Registry. It is emphasized that all benign files have been audited by VirusTotal. Therefore, benign .js files, contained in MARADJS, have had their benevolence attested by the world's leading commercial antivirus. The results obtained by the analyzes of the benign and malware files, resulting from the VirusTotal audit, are available for consultation at the MARADJS virtual address.

The objective of the creation of the MARADJS database is to give full possibility of the proposed methodology being replicated by third parties in future works. Therefore, MARADJS freely makes available all its benign and malware samples:

• extension files js,

• Virustotal audits,

• Dynamic analysis of the Cuckoo Sandbox.

It is concluded that our MARADJS database enables transparency and impartiality to the research, besides demonstrating the veracity of the results achieved. So, it is expected that MARADJS will serve as the basis for the creation of new scientific works aimed at NGAVs.
