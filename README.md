# covid19-cases-switzerland

The data has been collected from:

- Official BAG [Twitter Account](https://twitter.com/BAG_OFSP_UFSP)
- BFS [Hospital Beds](https://www.bfs.admin.ch/bfs/de/home/statistiken/gesundheit/gesundheitswesen/spitaeler/infrastruktur-beschaeftigung-finanzen.assetdetail.10647166.html)
- Data for [NW](https://www.nw.ch/gesundheitsamtdienste/6044#Anzahl%C2%A0Erkrankungen)
- Data for [BE](https://www.besondere-lage.sites.be.ch/besondere-lage_sites/de/index/corona/index.html#originRequestUrl=www.be.ch/corona)
- Data for [SG](https://www.sg.ch/tools/informationen-coronavirus.html)
- Data for [TI](https://www4.ti.ch/area-media/comunicati/), Grazie [@sarahhu87422283](https://twitter.com/sarahhu87422283), Danke [vecirex](https://twitter.com/vecirex)
- Data for [NE](https://www.ne.ch/autorites/DFS/SCSP/medecin-cantonal/maladies-vaccinations/Pages/Coronavirus.aspx), Merci [@borisfritscher](https://twitter.com/borisfritscher)
- Data for [AG](https://www.ag.ch/de/themen_1/coronavirus_2/coronavirus.jsp), Danke [@BachliMeyer](https://twitter.com/BachliMeyer)
- Data for [GR](https://www.youtube.com/channel/UCEcqzK6vbCuIvxLiJCAMVuA)
- Data for [AI](https://www.ai.ch/themen/gesundheit-alter-und-soziales/gesundheitsfoerderung-und-praevention/uebertragbare-krankheiten/coronavirus), Danke [@BachliMeyer](https://twitter.com/BachliMeyer)
- Data for [UR](https://www.ur.ch/themen/2920),
- Data for [VS](https://www.vs.ch/de/web/coronavirus), Merci [@enno_hermann](https://twitter.com/enno_hermann)
- Data for [BS](https://www.coronavirus.bs.ch/)
- Data for [JU](https://www.jura.ch/fr/Autorites/Coronavirus/Accueil/Coronavirus-Informations-officielles-a-la-population-jurassienne.html)
- Data for [GE](https://www.ge.ch/covid-19-coronavirus-geneve/situation-epidemiologique-geneve) Merci [@ThomasGriessen](https://twitter.com/ThomasGriessen)
- Data for [LU](https://www.luzernerzeitung.ch/zentralschweiz/luzern/so-will-die-luzerner-regierung-die-massnahmen-des-bundes-umsetzen-lukb-stellt-50-millionen-franken-bereit-ld.1204954), Danke [@neph_b](https://twitter.com/neph_b) \*Data ard from the video.
- Data for [VD](https://www.vd.ch/toutes-les-actualites/hotline-et-informations-sur-le-coronavirus/), Merci [@f_giroud](https://twitter.com/f_giroud)
- Data for [TG](https://www.tg.ch/news/fachdossier-coronavirus.html/10552), Danke [@KeveHilfi](https://twitter.com/KeveHilfi)
- Data for [ZH](https://github.com/openZH/covid_19), Danke, [@zdavatz](https://twitter.com/zdavatz)
- Data for [SH](https://sh.ch/CMS/Webseite/Kanton-Schaffhausen/Beh-rde/Verwaltung/Departement-des-Innern/Gesundheitsamt-3209198-DE.html), Danke [@BachliMeyer](https://twitter.com/BachliMeyer)
- Data for [BL](https://www.baselland.ch/), Danke [@BachliMeyer](https://twitter.com/BachliMeyer), the MVP ;-)
- Data for [BL](https://www.coronavirus.bs.ch/)
- Data for [ZG](https://www.zg.ch/behoerden/gesundheitsdirektion/direktionssekretariat/aktuell/coronavirus-ausreichende-testkapazitaeten-im-kanton-zug-vorhanden)
- Data for [FR](https://www.fr.ch/de/covid19/gesundheit/covid-19/coronavirus-entwicklungen-der-situation)
- Data for [SO](https://twitter.com/KantonSolothurn/)

- Important: The data for 18. 03. 2020 has been calculated from the incidence data [published by the BAG](https://www.bag.admin.ch/dam/bag/de/dokumente/mt/k-und-i/aktuelle-ausbrueche-pandemien/2019-nCoV/covid-19-lagebericht.pdf.download.pdf/COVID-19_Epidemiologische_Lage_Schweiz.pdf). However, this data seems to be outdated or based on different population numbers than the data from the 2018 census I used. However, the latter is rather unlikely. I have thus merged all values from the BAG that are HIGHER than those from the cantonal sources into the table.

Preliminary diagnoses (not confirmed by Geneva) are counted as cases.

There are missing numbers now. I suggest to either get them via fitting or interpolation.

## Interactive Dashboard

- https://dashcoch.herokuapp.com/

## Map Overview of Swiss data

- http://corona-ch.surge.sh/
