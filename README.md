# Neuchâtel: law history in git

The law of the canton of Neuchâtel (République et Canton de Neuchâtel, Switzerland) as a git history: one file per article, one commit per change on the day it took effect. `git blame` and `git log` work line by line; checking out a date gives the text in force that day.

It follows the shared design of [lexifina/global-law](https://github.com/lexifina/global-law), which places it at `ch-ne/`. The federal law is in [lexifina/switzerland-law](https://github.com/lexifina/switzerland-law).

The text is in French, the canton's official language, exactly as published.

## What this repository holds

328 acts with 328 versions so far, starting with the cantonal constitution. The RSN publishes only the current text of each act, so each act has one version: the text as the collection gives it on its "Etat au" date. It holds the constitution, the laws (lois) and the règlements in force, in the order of the systematic collection, added in parts; arrêtés, decrees, agreements and repealed acts are not included yet.

| Folder | Act | Versions | History |
| --- | --- | ---: | --- |
| `101-cst-ne/` | Constitution de la République et Canton de Neuchâtel (101) | 1 | current text only, in force since 14 June 2026 |
| `120-lalidv/` | Loi d’application de la loi fédérale sur l’interdiction de se dissimuler le visage (LALIDV) (120) | 1 | current text only, in force since 1 January 2026 |
| `131-0-ldcn/` | Loi sur le droit de cité neuchâtelois (LDCN) (131.0) | 1 | current text only, in force since 1 January 2026 |
| `132-0-lhrch/` | Loi concernant l'harmonisation des registres officiels de personnes et le contrôle des habitants (LHRCH), du l3 novembre 2009 (132.0) | 1 | current text only, in force since 1 January 2026 |
| `132-04/` | Loi sur l'intégration et la cohésion multiculturelle (132.04) | 1 | current text only, in force since 15 March 2023 |
| `141-ldp/` | Loi sur les droits politiques (LDP) (141) | 1 | current text only, in force since 24 October 2024 |
| `150-5/` | Loi sur le traitement de données à des fins de gestion administrative et financière au sein de l'État (150.5) | 1 | current text only, in force since 1 January 2018 |
| `150-10-lresp/` | Loi sur la responsabilité des collectivités publiques et de leurs agents (Loi sur la responsabilité) (LResp) (150.10) | 1 | current text only, in force since 1 January 2026 |
| `150-20-lpao/` | Loi sur la publication des actes officiels (LPAO) (150.20) | 1 | current text only, in force since 1 January 2017 |
| `150-32/` | Loi sur la vidéosurveillance des installations de l'État (150.32) | 1 | current text only, in force since 1 January 2019 |
| `150-33-ltdfo/` | Loi sur le traitement des données dans le domaine de la formation et de l’orientation (LTDFO) (150.33) | 1 | current text only, in force since 1 July 2026 |
| `150-50-lbdeee/` | Loi portant sur la base de données des établissements, entreprises et entités du canton de Neuchâtel (LBDEEE) (150.50) | 1 | current text only, in force since 1 January 2018 |
| `151-10-ogc/` | Loi d'organisation du Grand Conseil (OGC) (151.10) | 1 | current text only, in force since 11 March 2026 |
| `151-110/` | Loi sur la haute surveillance de la gestion des autorités judiciaires et l'exercice des autres compétences du Grand Conseil en matière judiciaire (loi sur la haute surveillance, LHS) (151.110) | 1 | current text only, in force since 1 January 2026 |
| `151-115/` | Loi sur le droit de pétition (LDPé) (151.115) | 1 | current text only, in force since 1 July 2019 |
| `152-100-lce/` | Loi sur l'organisation du Conseil d'Etat et de l'administration cantonale (LCE) (152.100) | 1 | current text only, in force since 1 January 2026 |
| `152-130-lpa/` | Loi sur la procédure administrative (LPA) (152.130) | 1 | current text only, in force since 1 January 2026 |
| `152-510-lst/` | Loi sur le statut de la fonction publique (LSt) (152.510) | 1 | current text only, in force since 1 April 2026 |
| `152-550-lcpfpub/` | Loi sur la Caisse de pensions pour la fonction publique du canton de Neuchâtel (LCPFPub) (152.550) | 1 | current text only, in force since 1 January 2026 |
| `161-1-ojn/` | Loi d'organisation judiciaire neuchâteloise (OJN) (161.1) | 1 | current text only, in force since 1 February 2026 |
| `161-2-laj/` | Loi sur l’assistance judiciaire (LAJ) (161.2) | 1 | current text only, in force since 1 January 2025 |
| `161-3-lmcp/` | Loi sur la médiation civile et pénale (LMCP) (161.3) | 1 | current text only, in force since 1 January 2026 |
| `164-1-ltfrais/` | Loi fixant le tarif des frais, des émoluments de chancellerie et des dépens en matière civile, pénale et administrative (LTFrais) (164.1) | 1 | current text only, in force since 1 April 2023 |
| `165-10-lav/` | Loi sur la profession d'avocat ou d'avocate (LAv) (165.10) | 1 | current text only, in force since 1 January 2026 |
| `166-10-ln/` | Loi sur le notariat (LN) (166.10) | 1 | current text only, in force since 1 January 2026 |
| `171-1-lco/` | Loi sur les communes (LCo) (171.1) | 1 | current text only, in force since 1 January 2026 |
| `171-16-lpfi/` | Loi sur la péréquation financière intercommunale (LPFI) (171.16) | 1 | current text only, in force since 1 January 2026 |
| `172-41-lfac/` | Loi sur le fonds d'aide aux communes (LFAC) (172.41) | 1 | current text only, in force since 1 January 2024 |
| `211-1-li-cc/` | Loi concernant l'introduction du code civil suisse (LI-CC) (211.1) | 1 | current text only, in force since 27 May 2025 |
| `212-120-10/` | Loi sur le partenariat enregistré (212.120.10) | 1 | current text only, in force since 1 January 2026 |
| `213-32-lapea/` | Loi concernant les autorités de protection de l'enfant et de l'adulte (LAPEA) (213.32) | 1 | current text only, in force since 1 January 2021 |
| `213-221-lrace/` | Loi sur le recouvrement et l'avance des contributions d'entretien (LRACE) (213.221) | 1 | current text only, in force since 1 January 2026 |
| `214-10-lacdm/` | Loi sur le traitement des actes à cause de mort et actes similaires (LACDM) (214.10) | 1 | current text only, in force since 1 January 2026 |
| `215-411-6-lerf/` | Loi concernant le tarif des émoluments du registre foncier (LERF) (215.411.6) | 1 | current text only, in force since 1 January 2026 |
| `224-1-li-co/` | Loi d'introduction du code des obligations (LI-CO) (224.1) | 1 | current text only, in force since 1 January 2026 |
| `251-1-li-cpc/` | Loi d'introduction du code de procédure civile (LI-CPC) (251.1) | 1 | current text only, in force since 1 July 2019 |
| `261-1-lilp/` | Loi d'introduction de la loi fédérale sur la poursuite pour dettes et la faillite (LILP) (261.1) | 1 | current text only, in force since 1 January 2026 |
| `322-0-li-cpp/` | Loi d’introduction du Code de procédure pénale suisse (LI-CPP) (322.0) | 1 | current text only, in force since 13 March 2024 |
| `322-05-lvd/` | Loi sur la lutte contre la violence domestique (LVD) (322.05) | 1 | current text only, in force since 1 January 2020 |
| `323-0-li-ppmin/` | Loi d'introduction de la loi fédérale sur la procédure pénale applicable aux mineurs (LI-PPMin) (323.0) | 1 | current text only, in force since 1 January 2025 |
| `351-0-lpmpa/` | Loi sur l'exécution des peines et des mesures pour les personnes adultes (LPMPA) (351.0) | 1 | current text only, in force since 1 January 2026 |
| `400-1-lae/` | Loi sur l'accueil des enfants (LAE) (400.1) | 1 | current text only, in force since 1 January 2026 |
| `410-10-los/` | Loi sur l'organisation scolaire (LOS) (410.10) | 1 | current text only, in force since 1 July 2026 |
| `410-23-las/` | Loi concernant les autorités scolaires (LAS) (410.23) | 1 | current text only, in force since 1 January 2026 |
| `410-82-lsaj/` | Loi sur le soutien aux activités de jeunesse extra-scolaires (LSAJ) (410.82) | 1 | current text only, in force since 1 January 2026 |
| `410-131/` | Loi sur l'enseignement secondaire supérieur (410.131) | 1 | current text only, in force since 1 July 2026 |
| `410-810-losp/` | Loi sur l'orientation scolaire et professionnelle (LOSP) (410.810) | 1 | current text only, in force since 1 July 2026 |
| `414-10-lfp/` | Loi sur la formation professionnelle (LFP) (414.10) | 1 | current text only, in force since 1 July 2026 |
| `414-111-lfapp/` | Loi instituant un fonds pour l'apprentissage et le perfectionnement professionnel (LFAPP) (414.111) | 1 | current text only, in force since 1 January 2026 |
| `414-112-lifp/` | Loi sur l'insertion des jeunes en formation professionnelle (LIFP) (414.112) | 1 | current text only, in force since 17 August 2022 |
| `414-231-0-lcnip/` | Loi sur le Centre neuchâtelois d'intégration professionnelle (LCNIP) (414.231.0) | 1 | current text only, in force since 1 January 2026 |
| `416-100-lune/` | Loi sur l’Université de Neuchâtel (LUNE) (416.100) | 1 | current text only, in force since 1 January 2026 |
| `416-633-3-hep-bejune/` | Loi sur la Haute école pédagogique (HEP-BEJUNE) (416.633.3) | 1 | current text only, in force since 1 March 2024 |
| `417-10-lsport/` | Loi sur le sport (LSport) (417.10) | 1 | current text only, in force since 27 May 2025 |
| `418-10-laf/` | Loi sur les aides à la formation (LAF) (418.10) | 1 | current text only, in force since 1 January 2026 |
| `442-20-larch/` | Loi sur l'archivage (LArch) (442.20) | 1 | current text only, in force since 1 January 2026 |
| `442-41/` | Loi concernant l'aide à la lecture publique et aux bibliothèques (442.41) | 1 | current text only, in force since 27 May 2025 |
| `451-01-leac/` | Loi sur l’encouragement des activités culturelles et artistiques (LEAC) (451.01) | 1 | current text only, in force since 1 November 2024 |
| `451-20-lfmc/` | Loi sur la formation musicale (LFMC) (451.20) | 1 | current text only, in force since 1 July 2026 |
| `461-30-lspc/` | Loi sur la sauvegarde du patrimoine culturel (LSPC) (461.30) | 1 | current text only, in force since 1 January 2026 |
| `465-0-lilpa/` | Loi d'introduction de la législation fédérale sur la protection des animaux (LILPA) (465.0) | 1 | current text only, in force since 1 January 2026 |
| `521-1-la-lppci/` | Loi d'application de la législation fédérale sur la protection de la population et sur la protection civile (LA-LPPCi) (521.1) | 1 | current text only, in force since 1 January 2026 |
| `565-1/` | Loi sur les sépultures (inhumation gratuite) (565.1) | 1 | current text only, in force since 27 May 2025 |
| `601-lfinec/` | Loi sur les finances de l'Etat et des communes (LFinEC) (601) | 1 | current text only, in force since 1 January 2026 |
| `601-3-lccfi/` | Loi sur le contrôle des finances (LCCFI) (601.3) | 1 | current text only, in force since 1 January 2026 |
| `601-8-lsub/` | Loi sur les subventions (LSub) (601.8) | 1 | current text only, in force since 1 January 2026 |
| `601-70-laimp/` | Loi portant adhésion à l'Accord intercantonal sur les marchés publics (LAIMP) (601.70) | 1 | current text only, in force since 1 January 2011 |
| `621-lbcn/` | Loi sur la Banque cantonale neuchâteloise (LBCN) (621) | 1 | current text only, in force since 1 May 2025 |
| `631-0-lcdir/` | Loi sur les contributions directes (LCdir) (631.0) | 1 | current text only, in force since 1 January 2026 |
| `631-2/` | Loi sur la redistribution du produit de l'impôt communal sur le bénéfice et le capital des personnes morales entre les communes (631.2) | 1 | current text only, in force since 1 January 2025 |
| `633-0-lsucc/` | Loi instituant un impôt sur les successions et sur les donations entre vifs (LSucc) (633.0) | 1 | current text only, in force since 27 May 2025 |
| `635-0-ldmi/` | Loi concernant la perception de droits de mutation sur les transferts immobiliers (LDMI) (635.0) | 1 | current text only, in force since 1 January 2026 |
| `636-20-lchiens/` | Loi sur les chiens (LChiens) (636.20) | 1 | current text only, in force since 1 January 2026 |
| `637-20-lrifd/` | Loi concernant la répartition de la part du canton au produit de l'impôt fédéral direct (LRIFD) (637.20) | 1 | current text only, in force since 1 January 2017 |
| `701-0-lcat/` | Loi cantonale sur l'aménagement du territoire (LCAT) (701.0) | 1 | current text only, in force since 1 January 2026 |
| `701-2-lmd/` | Loi sur la mobilité douce (LMD) (701.2) | 1 | current text only, in force since 1 April 2018 |
| `701-6-li-lcpr/` | Loi d'introduction de la loi fédérale sur les chemins pour piétons et les chemins de randonnée pédestre (LI-LCPR) (701.6) | 1 | current text only, in force since 1 January 2026 |
| `710-lexup/` | Loi sur l'expropriation pour cause d'utilité publique (LEXUP) (710) | 1 | current text only, in force since 1 January 2026 |
| `720-0-lconstr/` | Loi sur les constructions (LConstr.) (720.0) | 1 | current text only, in force since 1 January 2026 |
| `727-0-ludp/` | Loi sur l'utilisation du domaine public (LUDP) (727.0) | 1 | current text only, in force since 1 January 2026 |
| `727-2-lscn/` | Loi sur le stationnement des communautés nomades (LSCN) (727.2) | 1 | current text only, in force since 1 January 2026 |
| `731-250/` | Loi sur le fonds cantonal des eaux (731.250) | 1 | current text only, in force since 1 July 2022 |
| `735-10-lrvp/` | Loi sur les routes et voies publiques (LRVP) (735.10) | 1 | current text only, in force since 22 April 2026 |
| `735-15-lrnrp/` | Loi sur les routes nationales, ainsi que sur les routes principales et autres routes bénéficiant de contributions de la Confédération (LRNRP) (735.15) | 1 | current text only, in force since 1 January 2020 |
| `735-17-lern/` | Loi sur l’entretien des routes nationales (LERN) (735.17) | 1 | current text only, in force since 1 September 2020 |
| `740-1-lcen/` | Loi cantonale sur l’énergie (LCEn) (740.1) | 1 | current text only, in force since 1 January 2026 |
| `740-101-lael/` | Loi sur l’approvisionnement en électricité (LAEL) (740.101) | 1 | current text only, in force since 1 January 2026 |
| `751-0/` | Loi d'introduction de la législation fédérale sur la géoinformation (LGéo): loi cantonale sur la géoinformation (LCGéo) (751.0) | 1 | current text only, in force since 1 January 2026 |
| `761-10-li-lcr/` | Loi d'introduction des prescriptions fédérales sur la circulation routière (LI-LCR) (761.10) | 1 | current text only, in force since 1 January 2020 |
| `761-20-ltvrb/` | Loi sur la taxe des véhicules automobiles, des remorques et des bateaux (LTVRB) (761.20) | 1 | current text only, in force since 1 January 2026 |
| `761-400-lscan/` | Loi sur le service cantonal des automobiles et de la navigation (LSCAN) (761.400) | 1 | current text only, in force since 1 January 2026 |
| `765-1-ltp/` | Loi sur les transports publics (LTP) (765.1) | 1 | current text only, in force since 1 January 2026 |
| `767-1-ldro/` | Loi sur les drones (LDro) (767.1) | 1 | current text only, in force since 1 January 2026 |
| `780-li-lscpt/` | Loi d'introduction de la loi fédérale sur la surveillance de la correspondance par poste et télécommunication (LI-LSCPT) (780) | 1 | current text only, in force since 1 January 2015 |
| `801-102/` | Loi d’exécution de la loi fédérale relative à l’encouragement de la formation dans le domaine des soins infirmiers (801.102) | 1 | current text only, in force since 1 September 2024 |
| `802-310-lcnp/` | Loi sur le Centre neuchâtelois de psychiatrie (LCNP) (802.310) | 1 | current text only, in force since 1 January 2026 |
| `805-10-lpge/` | Loi sur la protection et la gestion des eaux (LPGE) (805.10) | 1 | current text only, in force since 1 January 2026 |
| `805-30-ldsp/` | Loi sur les déchets et les sites pollués (LDSP) (805.30) | 1 | current text only, in force since 1 January 2026 |
| `806-0-la-ldal/` | Loi d'application de loi fédérale sur les denrées alimentaires et les objets usuels (LA-LDAl) (806.0) | 1 | current text only, in force since 1 January 2026 |
| `813-10-lempl/` | Loi sur l'emploi et l'assurance-chômage (LEmpl) (813.10) | 1 | current text only, in force since 1 January 2026 |
| `820-22-linca/` | Loi sur l’inclusion et l’accompagnement des personnes vivant avec un handicap (LIncA) (820.22) | 1 | current text only, in force since 1 January 2026 |
| `820-30-lcpc/` | Loi d'introduction de la loi fédérale sur les prestations complémentaires à l'AVS et à l'AI (LCPC) (820.30) | 1 | current text only, in force since 1 January 2026 |
| `822-10-lilafam/` | Loi d'introduction de la loi fédérale sur les allocations familiales (LILAFam) (822.10) | 1 | current text only, in force since 1 January 2026 |
| `831-0-lasoc/` | Loi sur l'action sociale (LASoc) (831.0) | 1 | current text only, in force since 1 January 2026 |
| `831-3-llps/` | Loi sur la lutte et la prévention contre le surendettement (LLPS) (831.3) | 1 | current text only, in force since 1 January 2026 |
| `831-4-lhacops/` | Loi sur l'harmonisation et la coordination des prestations sociales (LHaCoPS) (831.4) | 1 | current text only, in force since 1 January 2017 |
| `832-10-lesea/` | Loi sur l'aide financière aux établissements spécialisés pour enfants et adolescents du canton (LESEA) (832.10) | 1 | current text only, in force since 1 January 2010 |
| `832-30-lfinems/` | Loi sur le financement des établissements médico-sociaux (LFinEMS) (832.30) | 1 | current text only, in force since 1 January 2026 |
| `841-0-lal/` | Loi sur l'aide au logement (LAL) (841.0) | 1 | current text only, in force since 1 January 2011 |
| `841-00-lal2/` | Loi sur l'aide au logement (LAL2) (841.00) | 1 | current text only, in force since 23 August 2023 |
| `846-0-lval/` | Loi limitant la mise en vente d'appartements loués (LVAL) (846.0) | 1 | current text only, in force since 1 January 2026 |
| `861-10-lpdiens/` | Loi sur la prévention et la défense contre les incendies et les éléments naturels, ainsi que les secours (LPDIENS) (861.10) | 1 | current text only, in force since 1 January 2026 |
| `863-10-lab/` | Loi sur la préservation et l’assurance des bâtiments (LAB) (863.10) | 1 | current text only, in force since 1 January 2026 |
| `900-1-lade/` | Loi sur l'appui au développement économique (LADE) (900.1) | 1 | current text only, in force since 1 April 2016 |
| `901-02-lelpr/` | Loi d'exécution de la loi fédérale sur la politique régionale (LELPR) (901.02) | 1 | current text only, in force since 1 January 2026 |
| `913-1-lasa/` | Loi sur les améliorations structurelles dans l'agriculture (LASA) (913.1) | 1 | current text only, in force since 1 January 2026 |
| `916-120-lvit/` | Loi sur la viticulture (LVit) (916.120) | 1 | current text only, in force since 1 January 2026 |
| `921-1-lcfo/` | Loi cantonale sur les forêts (LCFo) (921.1) | 1 | current text only, in force since 1 January 2026 |
| `922-10-lfs/` | Loi sur la faune sauvage (LFS) (922.10) | 1 | current text only, in force since 1 February 2025 |
| `923-10-lfaq/` | Loi sur la faune aquatique (LFAq) (923.10) | 1 | current text only, in force since 1 January 2026 |
| `931-1-luss/` | Loi sur l’utilisation du sous-sol (LUSS) (931.1) | 1 | current text only, in force since 1 January 2026 |
| `933-10-lep/` | Loi sur les établissements publics (LEP) (933.10) | 1 | current text only, in force since 1 January 2026 |
| `933-20-ltour/` | Loi sur l'appui au développement touristique (LTour) (933.20) | 1 | current text only, in force since 1 January 2026 |
| `933-52-liljar/` | Loi d’introduction de la loi fédérale sur les jeux d’argent (LILJAr) (933.52) | 1 | current text only, in force since 1 January 2026 |
| `941-2-lbcmp/` | Loi sur le bureau de contrôle des ouvrages en métaux précieux (LBCMP) (941.2) | 1 | current text only, in force since 1 January 2025 |
| `941-011-lhocom/` | Loi sur les heures d'ouverture des commerces (LHOCom) (941.011) | 1 | current text only, in force since 1 January 2025 |
| `941-70-lprost/` | Loi sur la prostitution et la pornographie (LProst) (941.70) | 1 | current text only, in force since 1 January 2026 |
| `961-1-lccap/` | Loi sur la Caisse cantonale d'assurance populaire (LCCAP) (961.1) | 1 | current text only, in force since 1 January 2026 |
| `991/` | Loi sur l'aide humanitaire et la coopération au développement (991) | 1 | current text only, in force since 1 July 2022 |
| `131-1-rldcn/` | Règlement d’exécution de la loi sur le droit de cité neuchâtelois (RLDCN) (131.1) | 1 | current text only, in force since 27 May 2025 |
| `132-01-rhrch/` | Règlement d'exécution de la loi sur l'harmonisation des registres officiels de personnes et le contrôle des habitants (RHRCH) (132.01) | 1 | current text only, in force since 27 May 2025 |
| `132-03-ccma/` | Règlement de la commission consultative en matière d’asile (CCMA) (132.03) | 1 | current text only, in force since 1 January 2026 |
| `132-041/` | Règlement sur l’intégration et la cohésion multiculturelle (132.041) | 1 | current text only, in force since 1 January 2026 |
| `141-01-reldp/` | Règlement d'exécution de la loi sur les droits politiques (RELDP) (141.01) | 1 | current text only, in force since 1 June 2026 |
| `150-22-relpao/` | Règlement d’exécution de la loi sur la publication des actes officiels (RELPAO) (150.22) | 1 | current text only, in force since 5 May 2018 |
| `150-51/` | Règlement d’exécution de la loi sur le traitement de données à des fins de gestion administrative et financière au sein de l’État (150.51) | 1 | current text only, in force since 1 January 2019 |
| `150-401-relgsu/` | Règlement d'exécution de la loi sur le guichet sécurisé unique (RELGSU) (150.401) | 1 | current text only, in force since 5 May 2026 |
| `150-501-relbdeee/` | Règlement d’exécution de la loi sur la base de données des établissements, entreprises et entités du Canton de Neuchâtel (RELBDEEE) (150.501) | 1 | current text only, in force since 27 May 2025 |
| `151-20/` | Règlement sur l’indemnisation des membres et membres suppléants du Grand Conseil (151.20) | 1 | current text only, in force since 27 May 2025 |
| `151-104/` | Règlement d’organisation et de fonctionnement de la commission de gestion et d’évaluation (151.104) | 1 | current text only, in force since 26 November 2024 |
| `151-105/` | Règlement d'organisation et de fonctionnement de la commission des finances (151.105) | 1 | current text only, in force since 2 May 2023 |
| `151-106/` | Règlement de la commission des affaires extérieures concernant les délégations (151.106) | 1 | current text only, in force since 3 September 2013 |
| `151-107/` | Règlement de fonctionnement de la commission des affaires extérieures (151.107) | 1 | current text only, in force since 24 September 2024 |
| `151-108/` | Règlement de la commission des pétitions et des grâces sur le traitement des demandes de grâce (151.108) | 1 | current text only, in force since 8 January 2014 |
| `152-100-00/` | Règlement protocolaire de la République et Canton de Neuchâtel (152.100.00) | 1 | current text only, in force since 1 January 2023 |
| `152-100-01-ro-dsdc/` | Règlement d’organisation du Département de la sécurité, de la digitalisation et de la culture (RO-DSDC) (152.100.01) | 1 | current text only, in force since 27 May 2025 |
| `152-100-001/` | Règlement sur l'organisation du Conseil d'Etat (152.100.001) | 1 | current text only, in force since 1 June 2008 |
| `152-100-02-ro-decs/` | Règlement d’organisation du Département de l’économie et de la cohésion sociale (RO-DECS) (152.100.02) | 1 | current text only, in force since 27 May 2025 |
| `152-100-03-ro-ddte/` | Règlement d’organisation du Département du développement territorial et de l’environnement (RO-DDTE) (152.100.03) | 1 | current text only, in force since 1 July 2026 |
| `152-100-003/` | Règlement de gestion opérationnelle des services de l'administration cantonale neuchâteloise (Règlement GestionNE) (152.100.003) | 1 | current text only, in force since 1 July 2024 |
| `152-100-04-ro-dsjs/` | Règlement d’organisation du Département de la santé, de la jeunesse et des sports (RO-DSJS) (152.100.04) | 1 | current text only, in force since 1 September 2025 |
| `152-100-05-ro-dffi/` | Règlement d’organisation du Département de la formation et des finances (RO-DFFI) (152.100.05) | 1 | current text only, in force since 27 May 2025 |
| `152-100-06-ro-chan/` | Règlement d’organisation de la chancellerie d’État (RO-CHAN) (152.100.06) | 1 | current text only, in force since 27 May 2025 |
| `152-111-1/` | Règlement d'application de la loi sur la politique familiale et l'égalité entre hommes et femmes (152.111.1) | 1 | current text only, in force since 27 May 2025 |
| `152-150-20/` | Règlement fixant les émoluments relatifs à la santé publique (152.150.20) | 1 | current text only, in force since 26 August 2026 |
| `152-511-rst/` | Règlement général d'application de la loi sur le statut de la fonction publique (RSt) (152.511) | 1 | current text only, in force since 1 January 2026 |
| `152-511-4/` | Règlement relatif aux obligations attachées à certaines fonctions de l'administration cantonale (152.511.4) | 1 | current text only, in force since 1 September 2025 |
| `152-511-5/` | Règlement relatif à l'interdiction de fumer dans les locaux de l'administration de la République et Canton de Neuchâtel (152.511.5) | 1 | current text only, in force since 27 May 2025 |
| `152-511-103/` | Règlement sur la fixation et l'évolution des traitements du personnel policier et administratif transféré à la Police neuchâteloise (152.511.103) | 1 | current text only, in force since 1 January 2014 |
| `152-511-105/` | Règlement concernant la protection de la santé et la sécurité du travail au sein de l’administration cantonale (152.511.105) | 1 | current text only, in force since 1 April 2025 |
| `152-512-rdf/` | Règlement des fonctionnaires (RDF) (152.512) | 1 | current text only, in force since 1 January 2023 |
| `152-513-rsten/` | Règlement général d'application de la loi sur le statut de la fonction publique dans l'enseignement (RSten) (152.513) | 1 | current text only, in force since 1 August 2026 |
| `161-12/` | Règlement de la Conférence judiciaire (161.12) | 1 | current text only, in force since 1 October 2018 |
| `161-30-rlmcp/` | Règlement d’exécution de la loi sur la médiation civile et pénale (RLMCP) (161.30) | 1 | current text only, in force since 27 May 2025 |
| `162-104/` | Règlement du Tribunal cantonal (162.104) | 1 | current text only, in force since 1 January 2026 |
| `162-105/` | Règlement du Tribunal d’instance du Canton de Neuchâtel (162.105) | 1 | current text only, in force since 1 January 2020 |
| `165-101-rlav/` | Règlement d'exécution de la loi sur la profession d'avocat ou d'avocate (RLAv) (165.101) | 1 | current text only, in force since 27 May 2025 |
| `166-101-reln/` | Règlement d'exécution de la loi sur le notariat (RELN) (166.101) | 1 | current text only, in force since 27 May 2025 |
| `166-101-3/` | Règlement organique du Conseil notarial (166.101.3) | 1 | current text only, in force since 27 May 2025 |
| `166-102/` | Règlement sur la formation des stagiaires notaires (166.102) | 1 | current text only, in force since 27 May 2025 |
| `171-160-ralpfi/` | Règlement d'application de la loi sur la péréquation financière intercommunale (RALPFI) (171.160) | 1 | current text only, in force since 27 May 2025 |
| `172-410-ralfac/` | Règlement d'application de la loi sur le fonds d'aide aux communes (RALFAC) (172.410) | 1 | current text only, in force since 1 September 2025 |
| `212-120-rec/` | Règlement sur l’état civil (REC) (212.120) | 1 | current text only, in force since 27 May 2025 |
| `213-31/` | Règlement du service de protection de l'adulte et de la jeunesse (213.31) | 1 | current text only, in force since 27 May 2025 |
| `214-101-re-lacdm/` | Règlement d'exécution de la loi sur le traitement des actes à cause de mort et actes similaires (RE-LACDM) (214.101) | 1 | current text only, in force since 27 May 2025 |
| `215-411-rrf/` | Règlement sur le registre foncier (RRF) (215.411) | 1 | current text only, in force since 1 May 2026 |
| `215-421-rlcmo/` | Règlement d'exécution de la loi cantonale sur la mensuration officielle (RLCMO) (215.421) | 1 | current text only, in force since 27 May 2025 |
| `322-003/` | Règlement de fonctionnement de la commission de dangerosité (322.003) | 1 | current text only, in force since 6 June 2018 |
| `322-040/` | Règlement d'exécution de la loi d'introduction de la loi fédérale sur l'aide aux victimes d'infractions (322.040) | 1 | current text only, in force since 1 January 2026 |
| `354-24/` | Règlement sur l’exécution des peines privatives de liberté sous surveillance électronique (354.24) | 1 | current text only, in force since 1 January 2018 |
| `400-10-regae/` | Règlement général sur l’accueil des enfants (REGAE) (400.10) | 1 | current text only, in force since 1 August 2025 |
| `410-131-6-rpt/` | Règlement transitoire d'exécution de la loi fédérale concernant l’adoption et la modification d’actes dans le cadre de la réforme de la péréquation financière et de la répartition des tâches entre la Confédération et les cantons (RPT) en matière de formation scolaire spéciale (REFOSCOS) (410.131.6) | 1 | current text only, in force since 1 January 2026 |
| `410-246-rise/` | Règlement de l'informatique scolaire dans l'enseignement obligatoire et postobligatoire (RISE) (410.246) | 1 | current text only, in force since 27 May 2025 |
| `411-110/` | Règlement des études des lycées cantonaux (admission, promotion et examens) (411.110) | 1 | current text only, in force since 1 January 2026 |
| `414-110/` | Règlement d’application de la loi sur la formation professionnelle (414.110) | 1 | current text only, in force since 1 January 2026 |
| `414-110-01-rg-cpne/` | Règlement général du Centre de formation professionnelle neuchâtelois (RG-CPNE) (414.110.01) | 1 | current text only, in force since 1 January 2026 |
| `414-110-1/` | Règlement général des filières de maturité professionnelle (414.110.1) | 1 | current text only, in force since 31 July 2026 |
| `414-110-2/` | Règlement concernant le projet pilote pour la maturité professionnelle flexible anticipée (414.110.2) | 1 | current text only, in force since 15 August 2024 |
| `414-110-14/` | Règlement interne du Centre de formation professionnelle neuchâtelois (414.110.14) | 1 | current text only, in force since 1 January 2026 |
| `414-110-14-1/` | Règlement concernant les filières de préapprentissage et de transition (414.110.14.1) | 1 | current text only, in force since 1 January 2026 |
| `414-110-15/` | Règlement concernant la filière CFC de commerce modèle i (intégré) en école à plein temps  (414.110.15) | 1 | current text only, in force since 1 January 2026 |
| `414-110-16/` | Règlement concernant la filière menant au certificat d’école de culture générale et à la maturité spécialisée (414.110.16) | 1 | current text only, in force since 27 May 2025 |
| `414-110-160-die/` | Règlement concernant la filière EPD ES Direction d’institution de l’enfance (DIE) (414.110.160) | 1 | current text only, in force since 1 January 2026 |
| `414-110-171/` | Règlement portant sur le cours préparatoire et l’examen complémentaire permettant aux titulaires d’un certificat fédéral de maturité professionnelle ou d’un certificat de maturité spécialisée reconnu au niveau suisse d’être admis aux hautes écoles universitaires (414.110.171) | 1 | current text only, in force since 1 January 2026 |
| `414-111-0-rfapp/` | Règlement d’application de la loi instituant un fonds pour l’apprentissage et le perfectionnement professionnel (RFAPP) (414.111.0) | 1 | current text only, in force since 27 May 2025 |
| `414-112-0-rlifp/` | Règlement d’application de la loi sur l’insertion des jeunes en formation professionnelle (RLIFP) (414.112.0) | 1 | current text only, in force since 1 January 2026 |
| `414-212/` | Règlement général concernant les filières ES (414.212) | 1 | current text only, in force since 1 January 2026 |
| `414-231-01-cnip/` | Règlement d'organisation du Centre neuchâtelois d'intégration professionnelle (CNIP) (414.231.01) | 1 | current text only, in force since 1 January 2026 |
| `414-293/` | Règlement concernant la formation professionnelle de droguiste diplômé-e ES (414.293) | 1 | current text only, in force since 1 January 2026 |
| `414-321-3/` | Règlement instituant de subir un test d'aptitudes avant l'entrée en apprentissage dans les professions de mécatronicien-ne d'automobiles, mécanicien-ne en maintenance d'automobiles et assistant-e en maintenance d'automobiles (414.321.3) | 1 | current text only, in force since 27 May 2025 |
| `416-110/` | Règlement de la Commission de recours en matière d’examens de l’Université de Neuchâtel (416.110) | 1 | current text only, in force since 1 January 2026 |
| `416-192/` | Règlement de la Cité des étudiants (416.192) | 1 | current text only, in force since 1 January 2026 |
| `417-103/` | Règlement relatif aux programmes Sports-Arts-Études, Sports-Arts-Apprentissage et Sport-Élite dans l’enseignement postobligatoire (sports-arts et formation) (417.103) | 1 | current text only, in force since 1 January 2026 |
| `417-105/` | Règlement du sport scolaire facultatif (417.105) | 1 | current text only, in force since 27 May 2025 |
| `418-110-rlaf/` | Règlement d’application de la loi sur les aides à la formation (RLAF) (418.110) | 1 | current text only, in force since 1 January 2026 |
| `442-23/` | Règlement d'exécution de la loi sur l'archivage (442.23) | 1 | current text only, in force since 27 May 2025 |
| `442-411/` | Règlement concernant l'octroi de subventions en faveur des bibliothèques communales (442.411) | 1 | current text only, in force since 27 May 2025 |
| `451-03-releac/` | Règlement d’application de la loi sur l’encouragement des activités culturelles et artistiques (RELEAC) (451.03) | 1 | current text only, in force since 18 May 2026 |
| `451-21-rfmc/` | Règlement d’application de la loi sur la formation musicale cantonale (RFMC) (451.21) | 1 | current text only, in force since 24 August 2026 |
| `461-13/` | Règlement d'exécution des dispositions de l'ordonnance fédérale sur les paiements directs relatives aux contributions pour la qualité de la biodiversité de niveau II et pour la mise en réseau (461.13) | 1 | current text only, in force since 1 January 2026 |
| `461-100-relcpn/` | Règlement d'exécution de la loi sur la protection de la nature (RELCPN) (461.100) | 1 | current text only, in force since 1 August 2013 |
| `461-301-rlspc/` | Règlement d’application de la loi sur la sauvegarde du patrimoine culturel (RLSPC) (461.301) | 1 | current text only, in force since 25 January 2021 |
| `465-01-relilpa/` | Règlement d'application de la loi d'introduction de la législation fédérale sur la protection des animaux (RELILPA) (465.01) | 1 | current text only, in force since 1 August 2013 |
| `503-1/` | Règlement d'administration des établissements et installations militaires du canton de Neuchâtel (503.1) | 1 | current text only, in force since 27 May 2025 |
| `521-10/` | Règlement d'exécution de la loi d'application de la législation fédérale sur la protection de la population et sur la protection civile (521.10) | 1 | current text only, in force since 27 May 2025 |
| `521-11/` | Règlement de l'unité neuchâteloise d'intervention psychosociale UNIP (521.11) | 1 | current text only, in force since 27 May 2025 |
| `601-0-rlfinec/` | Règlement général d'exécution de la loi sur les finances de l'Etat et des Communes (RLFinEC) (601.0) | 1 | current text only, in force since 22 October 2025 |
| `601-30/` | Règlement du service financier (601.30) | 1 | current text only, in force since 1 September 2025 |
| `601-50/` | Règlement sur le contrôle des finances (601.50) | 1 | current text only, in force since 27 May 2025 |
| `601-80-relsub/` | Règlement d'exécution de la loi sur les subventions (RELSub) (601.80) | 1 | current text only, in force since 17 February 2025 |
| `601-720-relcmp/` | Règlement d’exécution de la loi cantonale sur les marchés publics (RELCMP) (601.720) | 1 | current text only, in force since 27 May 2025 |
| `631-01-relcdir/` | Règlement général d'application de la loi sur les contributions directes (RELCdir) (631.01) | 1 | current text only, in force since 27 May 2025 |
| `631-03/` | Règlement concernant la perception de l'impôt cantonal direct, de l'impôt communal direct et de leurs contributions annexes (631.03) | 1 | current text only, in force since 27 May 2025 |
| `631-011/` | Règlement concernant les remises d’impôt (631.011) | 1 | current text only, in force since 1 September 2024 |
| `631-014/` | Règlement concernant l'accès aux données fiscales par le guichet sécurisé unique (631.014) | 1 | current text only, in force since 27 May 2025 |
| `631-022-rei/` | Règlement concernant la détermination de l'estimation cadastrale des immeubles (bâtiments et terrains non agricoles) (REI) (631.022) | 1 | current text only, in force since 27 May 2025 |
| `631-023-reiagr/` | Règlement concernant la détermination de l'estimation cadastrale des immeubles (bâtiment et terrains affectés à l'économie rurale) (REIAgr) (631.023) | 1 | current text only, in force since 27 May 2025 |
| `631-31/` | Règlement concernant l’imposition à la source (631.31) | 1 | current text only, in force since 1 January 2024 |
| `636-21-rcc/` | Règlement relatif aux cours pour propriétaires de chiens (RCC) (636.21) | 1 | current text only, in force since 1 January 2021 |
| `636-201-relchiens/` | Règlement d’exécution de la loi sur les chiens (RELChiens) (636.201) | 1 | current text only, in force since 1 March 2024 |
| `701-02-relcat/` | Règlement d'exécution de la loi cantonale sur l'aménagement du territoire (RELCAT) (701.02) | 1 | current text only, in force since 1 July 2026 |
| `701-20/` | Règlement d’exécution de la loi sur la mobilité douce (701.20) | 1 | current text only, in force since 1 April 2018 |
| `701-60/` | Règlement d'exécution de la loi d'introduction de la loi fédérale sur les chemins pour piétons et les chemins de randonnée pédestre (701.60) | 1 | current text only, in force since 1 August 2013 |
| `705-10-relem/` | Règlement d'exécution de la loi sur l'extraction de matériaux (RELEM) (705.10) | 1 | current text only, in force since 1 August 2013 |
| `720-1-relconstr/` | Règlement d'exécution de la loi sur les constructions (RELConstr.) (720.1) | 1 | current text only, in force since 1 June 2026 |
| `720-6-rsatacgsu/` | Règlement sur le système automatisé de traitement des autorisations de construire et son accès par le guichet sécurisé unique (RSATACGSU) (720.6) | 1 | current text only, in force since 1 January 2026 |
| `727-01/` | Règlement d'exécution de la loi sur l'utilisation du domaine public (727.01) | 1 | current text only, in force since 1 August 2013 |
| `727-02/` | Règlement sur les plastiques à usage unique (727.02) | 1 | current text only, in force since 1 January 2023 |
| `727-20-relscn/` | Règlement d’exécution de la loi sur le stationnement des communautés nomades (RELSCN) (727.20) | 1 | current text only, in force since 1 May 2026 |
| `731-151/` | Règlement sur les piscines, les plages et les lieux de baignade publics (731.151) | 1 | current text only, in force since 1 April 2022 |
| `731-250-1-rufce/` | Règlement d'utilisation du fonds cantonal des eaux (RUFCE) (731.250.1) | 1 | current text only, in force since 1 January 2024 |
| `735-100-relrvp/` | Règlement d’exécution de la loi sur les routes et voies publiques (RELRVP) (735.100) | 1 | current text only, in force since 22 April 2024 |
| `735-151/` | Règlement d'exécution de la loi d'introduction de la législation fédérale sur les routes nationales (735.151) | 1 | current text only, in force since 1 January 2020 |
| `735-170-relern/` | Règlement d’exécution de la loi sur l’entretien des routes nationales (ReLERN) (735.170) | 1 | current text only, in force since 1 January 2026 |
| `740-10-relcen/` | Règlement d’exécution de la loi cantonale sur l’énergie (RELCEn) (740.10) | 1 | current text only, in force since 6 July 2026 |
| `740-101-0-relael/` | Règlement d’exécution de la loi sur l’approvisionnement en électricité (RELAEL) (740.101.0) | 1 | current text only, in force since 1 January 2026 |
| `751-01/` | Règlement d'exécution de la loi cantonale sur la géoinformation (RLCGéo) (751.01) | 1 | current text only, in force since 1 January 2026 |
| `765-100-ratv/` | Règlement concernant l'octroi d'autorisations cantonales pour le transport des voyageurs (RATV) (765.100) | 1 | current text only, in force since 27 May 2025 |
| `767-10-reldro/` | Règlement d’exécution de la loi sur les drones (RELDro) (767.10) | 1 | current text only, in force since 1 January 2026 |
| `801-100/` | Règlement concernant l'exercice des professions médicales universitaires et des autres professions de la santé (801.100) | 1 | current text only, in force since 27 May 2025 |
| `801-103/` | Règlement d’exécution de la loi d’exécution de la loi fédérale relative à l’encouragement de la formation dans le domaine des soins infirmiers (801.103) | 1 | current text only, in force since 1 January 2026 |
| `802-105-rsptp/` | Règlement sur les soins préhospitaliers et les transports de patients (RSPTP) (802.105) | 1 | current text only, in force since 1 January 2026 |
| `802-550/` | Règlement d’application de la loi fédérale sur les centres de consultation en matière de grossesse (802.550) | 1 | current text only, in force since 1 March 2024 |
| `804-10/` | Règlement sur les produits thérapeutiques, les pharmacies et les drogueries (804.10) | 1 | current text only, in force since 1 January 2026 |
| `804-30/` | Règlement d'application de la loi fédérale sur les stupéfiants (804.30) | 1 | current text only, in force since 27 May 2025 |
| `805-100-rlpge/` | Règlement d'exécution de la loi sur la protection et la gestion des eaux (RLPGE) (805.100) | 1 | current text only, in force since 1 September 2025 |
| `805-301-rldsp/` | Règlement d’exécution de la loi sur les déchets et les sites pollués (RLDSP) (805.301) | 1 | current text only, in force since 1 September 2025 |
| `806-12/` | Règlement concernant l’abattage des animaux (806.12) | 1 | current text only, in force since 1 October 2020 |
| `807-10/` | Règlement concernant l'application de la loi fédérale sur la lutte contre les maladies transmissibles de l'homme (807.10) | 1 | current text only, in force since 27 May 2025 |
| `807-13/` | Règlement d'application des prescriptions fédérales sur la lutte contre la tuberculose (807.13) | 1 | current text only, in force since 27 May 2025 |
| `807-201/` | Règlement sur les vaccinations et les revaccinations (807.201) | 1 | current text only, in force since 1 March 2024 |
| `807-301-rpp/` | Règlement concernant la protection des patients hospitalisés en milieu psychiatrique (RPP) (807.301) | 1 | current text only, in force since 1 January 2026 |
| `810-40/` | Règlement concernant l'office cantonal de conciliation en matière de conflits collectifs du travail (810.40) | 1 | current text only, in force since 27 May 2025 |
| `811-30/` | Règlement d'exécution de la loi fédérale sur le travail à domicile (811.30) | 1 | current text only, in force since 27 May 2025 |
| `811-101/` | Règlement d’application de la loi fédérale sur le travail 5.11.24 (811.101) | 1 | current text only, in force since 1 February 2025 |
| `813-100-relpac/` | Règlement d'exécution de la législation en matière de placement public et d'assurance-chômage (RELPAC) (813.100) | 1 | current text only, in force since 27 May 2025 |
| `813-100-0-rsalmin/` | Règlement portant sur l'application des dispositions de la loi sur l'emploi et l'assurance-chômage relatives au salaire minimum neuchâtelois (RSalMin) (813.100.0) | 1 | current text only, in force since 1 November 2025 |
| `813-100-01/` | Règlement d'organisation de la commission tripartite de l’assurance-chômage (813.100.01) | 1 | current text only, in force since 1 May 2017 |
| `813-110-reliloc/` | Règlement d'exécution de la législation en matière de licenciements collectifs, de licenciements importants, de placement privé et de location de services (RELILOC) (813.110) | 1 | current text only, in force since 27 May 2025 |
| `813-111/` | Règlement d'organisation de la commission tripartite chargée de l'observation du marché du travail (813.111) | 1 | current text only, in force since 27 May 2025 |
| `820-101/` | Règlement d'exécution de la loi d'application de la loi fédérale sur l'assurance-vieillesse et survivants et de la loi fédérale sur l'assurance-invalidité (820.101) | 1 | current text only, in force since 27 May 2025 |
| `820-104/` | Règlement de la Caisse cantonale de compensation (820.104) | 1 | current text only, in force since 27 May 2025 |
| `820-105/` | Règlement fixant l'organisation et les attributions de la commission de gestion de la Caisse cantonale de compensation (820.105) | 1 | current text only, in force since 27 May 2025 |
| `820-221-relinca/` | Règlement d’exécution de la loi sur l’inclusion et l’accompagnement des personnes vivant avec un handicap (ReLIncA) (820.221) | 1 | current text only, in force since 1 January 2026 |
| `820-223-repra/` | Règlement sur la planification et la reconnaissance des appartements LASDom (REPRA) (820.223) | 1 | current text only, in force since 23 August 2023 |
| `820-301-rlcpc/` | Règlement d'exécution de la loi d'introduction de la loi fédérale sur les prestations complémentaires à l'AVS et à l'AI (RLCPC) (820.301) | 1 | current text only, in force since 1 January 2021 |
| `820-304-rfmpc/` | Règlement relatif au remboursement des frais de maladie et des frais résultant de l'invalidité en matière de prestations complémentaires (RFMPC) (820.304) | 1 | current text only, in force since 1 June 2017 |
| `821-530/` | Règlement relatif au permis de conducteur de machines de travail (permis de machiniste) (821.530) | 1 | current text only, in force since 1 January 2026 |
| `822-31/` | Règlement de la Caisse cantonale de compensation pour allocations familiales (822.31) | 1 | current text only, in force since 27 May 2025 |
| `822-101-relilafam/` | Règlement d'exécution de la loi d'introduction de la loi fédérale sur les allocations familiales (RELILAFam) (822.101) | 1 | current text only, in force since 27 May 2025 |
| `823-31-rccnac/` | Règlement relatif à la Caisse cantonale neuchâteloise d'assurance-chômage (RCCNAC) (823.31) | 1 | current text only, in force since 27 May 2025 |
| `823-201-rmip/` | Règlement concernant les mesures d’intégration professionnelle (RMIP) (823.201) | 1 | current text only, in force since 1 January 2026 |
| `831-01-relasoc/` | Règlement d'exécution de la loi sur l'action sociale (RELASoc) (831.01) | 1 | current text only, in force since 27 May 2025 |
| `831-30-rllps/` | Règlement d’exécution de la loi sur la lutte et la prévention contre le surendettement (RLLPS) (831.30) | 1 | current text only, in force since 27 May 2025 |
| `831-40-relhacops/` | Règlement d'exécution de la loi sur l'harmonisation et la coordination des prestations sociales (RELHaCoPS) (831.40) | 1 | current text only, in force since 27 May 2025 |
| `832-35-rrcgt/` | Règlement sur la reconnaissance des conditions générales de travail des établissements médico-sociaux (art. 24 LFinEMS) (RRCGT) (832.35) | 1 | current text only, in force since 1 July 2018 |
| `832-101-relesea/` | Règlement d’exécution de la loi sur l’aide financière aux établissements spécialisés pour enfants et adolescent du canton (RELESEA) (832.101) | 1 | current text only, in force since 1 January 2026 |
| `832-300-rfines/` | Règlement sur le financement des établissements spécialisés (RFinES) (832.300) | 1 | current text only, in force since 3 November 2025 |
| `841-01-ral/` | Règlement d'exécution de la loi sur l'aide au logement (RAL) (841.01) | 1 | current text only, in force since 27 May 2025 |
| `841-010-ral2/` | Règlement d'exécution de la loi sur l'aide au logement (RAL2) (841.010) | 1 | current text only, in force since 1 January 2026 |
| `841-101/` | Règlement relatif à l'exécution du décret concernant la participation de l'Etat et des communes à la construction de maisons d'habitation (841.101) | 1 | current text only, in force since 27 May 2025 |
| `841-110/` | Règlement relatif à l'exécution du décret concernant la participation de l'Etat et des communes à la construction de maisons d'habitation (841.110) | 1 | current text only, in force since 27 May 2025 |
| `841-111/` | Règlement relatif à l'exécution du décret concernant la participation de l'Etat et des communes à la construction de maisons d'habitation (841.111) | 1 | current text only, in force since 27 May 2025 |
| `841-300/` | Règlement d'application des décrets concernant l'aide à la construction de logements à loyer modeste des 24 mai 1954, 12 février 1957, 21 mai 1959, 23 octobre 1961, 13 avril 1965 et 25 mars 1968 (841.300) | 1 | current text only, in force since 27 May 2025 |
| `843-101/` | Règlement d'exécution du décret concernant l'encouragement à la transformation et à la modernisation de logements anciens (843.101) | 1 | current text only, in force since 27 May 2025 |
| `843-121/` | Règlement d'exécution du décret concernant l'encouragement à la transformation et à la modernisation de logements anciens (843.121) | 1 | current text only, in force since 27 May 2025 |
| `861-100-ralpdiens/` | Règlement d'application de la loi sur la prévention et la défense contre les incendies et les éléments naturels, ainsi que les secours (RALPDIENS) (861.100) | 1 | current text only, in force since 16 February 2026 |
| `861-102-rrc/` | Règlement sur le ramonage et le contrôle des installations thermiques (RRC) (861.102) | 1 | current text only, in force since 1 January 2026 |
| `863-105/` | Règlement concernant l'accès aux données de l'assurance immobilière par le guichet sécurisé unique (863.105) | 1 | current text only, in force since 30 September 2019 |
| `900-10-relade/` | Règlement d'exécution de la loi sur l'appui au développement économique (RELADE) (900.10) | 1 | current text only, in force since 1 January 2026 |
| `901-020-ralelpr/` | Règlement d'application de la loi d'exécution de la loi fédérale sur la politique régionale (RALELPR) (901.020) | 1 | current text only, in force since 27 May 2025 |
| `910-10-relpagr/` | Règlement général d'exécution de la loi sur la promotion de l'agriculture (RELPAgr) (910.10) | 1 | current text only, in force since 13 May 2026 |
| `910-11/` | Règlement relatif à la reconversion en agriculture biologique des terres de l’État de Neuchâtel (910.11) | 1 | current text only, in force since 1 January 2021 |
| `913-10-relasa/` | Règlement d'exécution de la loi sur les améliorations structurelles dans l'agriculture (RELASA) (913.10) | 1 | current text only, in force since 1 January 2025 |
| `916-120-0/` | Règlement d'exécution de la loi sur la viticulture (916.120.0) | 1 | current text only, in force since 1 August 2013 |
| `916-120-6/` | Règlement départemental relatif au subventionnement des traitements viticoles aériens par drones (916.120.6) | 1 | current text only, in force since 1 January 2026 |
| `916-120-9/` | Règlement relatif aux mesures de soutien à l’arrachage des vignes pour la période 2026-2027 dans le cadre des améliorations structurelles (916.120.9) | 1 | current text only, in force since 1 January 2026 |
| `916-201/` | Règlement concernant la protection des végétaux (916.201) | 1 | current text only, in force since 1 January 2026 |
| `916-310-0/` | Règlement concernant la production animale (916.310.0) | 1 | current text only, in force since 1 August 2013 |
| `916-420-2/` | Règlement concernant les équipes d'intervention en cas d'épizooties hautement contagieuses (916.420.2) | 1 | current text only, in force since 1 May 2023 |
| `916-421/` | Règlement concernant la police sanitaire des animaux (916.421) | 1 | current text only, in force since 1 August 2013 |
| `916-421-35/` | Règlement relatif aux émoluments en matière de lutte contre les épizooties et d’élimination des cadavres d’animaux (916.421.35) | 1 | current text only, in force since 1 January 2026 |
| `916-423/` | Règlement concernant la police sanitaire des abeilles (916.423) | 1 | current text only, in force since 1 January 2017 |
| `921-10-relcfo/` | Règlement d'exécution de la loi cantonale sur les forêts (RELCFo) (921.10) | 1 | current text only, in force since 18 September 2024 |
| `922-101-rlfs/` | Règlement d'exécution de la loi sur la faune sauvage (RLFS) (922.101) | 1 | current text only, in force since 1 March 2026 |
| `922-101-1-rch/` | Règlement de chasse (RCh) (922.101.1) | 1 | current text only, in force since 1 January 2023 |
| `923-101-rlfaq/` | Règlement d'exécution de la loi sur la faune aquatique (RLFAq) ) (923.101) | 1 | current text only, in force since 1 August 2013 |
| `931-12/` | Règlement concernant l'utilisation et la surveillance des anciennes carrières en galeries du Val-de-Travers (931.12) | 1 | current text only, in force since 1 August 2013 |
| `933-53-reliljar/` | Règlement d’exécution de la loi d’introduction de la loi fédérale sur les jeux d’argent (RELILJAr) (933.53) | 1 | current text only, in force since 27 May 2025 |
| `933-201-reltour/` | Règlement d'exécution de la loi sur l'appui au développement touristique (RELTour) (933.201) | 1 | current text only, in force since 27 May 2025 |
| `933-401/` | Règlement d'exécution de la loi sur le cinéma (933.401) | 1 | current text only, in force since 27 May 2025 |
| `941-010-rcom/` | Règlement de police du commerce (RCom) (941.010) | 1 | current text only, in force since 19 August 2026 |
| `941-011-1-relhocom/` | Règlement d'exécution de la loi sur les heures d'ouverture des commerces (RELHOCom) (941.011.1) | 1 | current text only, in force since 1 January 2017 |
| `941-20/` | Règlement transitoire d’administration du bureau de contrôle des ouvrages en métaux précieux de La Chaux-de-Fonds (941.20) | 1 | current text only, in force since 27 May 2025 |
| `941-71-relprost/` | Règlement d'exécution de la loi sur la prostitution et la pornographie (RELProst) (941.71) | 1 | current text only, in force since 27 May 2025 |
| `944-151-larm/` | Règlement d'application de la loi fédérale sur les armes, les accessoires d'armes et les munitions (LArm) (944.151) | 1 | current text only, in force since 1 January 2026 |
| `944-161/` | Règlement concernant les substances explosibles (944.161) | 1 | current text only, in force since 1 January 2026 |
| `961-10-rccap/` | Règlement d'exécution de la loi sur la Caisse cantonale d'assurance populaire (RCCAP) (961.10) | 1 | current text only, in force since 10 December 2025 |

## Source

The Recueil systématique de la législation neuchâteloise (RSN), published by the Chancellerie d'Etat at <https://rsn.ne.ch/>, as the HTML edition of each act.

## Dates

- Each commit is dated at **noon, Europe/Zurich, on the day the version took effect**.
- Each act's single version is dated by the "Etat au" date the RSN prints on it; it is the "oldest version available" and is credited to the publisher. Earlier wording is not held.
- `--before="YYYY-MM-DD"` alone uses your clock's time of day; use `T23:59:59Z` or `tools/on.py`.

## Files

`<act>/art-005.md` is Art. 5, `art-005a.md` Art. 5a; `ingress.md` holds the title, date and preamble; `gliederung.md` the headings of titles, chapters and sections. One paragraph or list item per line. Footnote markers are left out.

## How it is checked

- Every version of every act is read back from git on the day it took effect and on the day before (`tools/check_repo.py`); both must match `corpus.json`.
- The letters and digits of every version equal those of the source document, and every article's text appears in it in order.
- Health checks: no merge commits, commit dates never go backwards, nothing dated in the future, and every commit's trailers parse.

## What "author" means

The author of each act's first commit is the publisher (RSN), because the text is the current consolidation rather than the act as adopted, with an e-mail address that cannot exist. The committer is always Lexifina.

## Limits

This is not an official publication. The binding text is the one published in the Feuille officielle and the Recueil de la législation neuchâteloise. Only the current wording is held. Footnotes (which name the amending acts) are not included. Only the acts listed above are included.
