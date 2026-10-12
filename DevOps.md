# DevOps
---
## 01 LECTURE

### ***REQUIREMENTS For DevOps***
---
**Myth about devops** 

- devops is not a technology it's a methodlogy
- **programing knowledge is not required** programming ki requirement na hony ki aik or waja b hai ka devops ma programming ka kam developer ka hai
  
- we require **basic of linux** linux aik distributing system hai is ka baray mein bad ma baat ho gi kisy na humy laptop chalana nai seekhaia blky hum seekh gye hein.
  
- Prior **IT experience** not reqired.
  
- non technical bnda b kar skta hai.

**Why Organizaton Needs DevOps Specialist**

+ suppose kry humein aik application bnani hai **Aarogy Setu** 
  jis covid 19 ka positive patients ki location pata chl sky government project dety hai ka humy esy application chyie company ka manager team sa meeting krta hai hai unhy btata hai ka humy eesy application chyie team btaty hai ka humy 6 mah lgy ga esy application bnany mein ya devops sa **phly kaam krny ka tariqa hai.devops sa ya kam 10 din mein ho jaye ga**

+ **FAST DELIVERY** agr ap na kha hai ka ap 10 din ma projext kar ka da ga tou 10 din mein hi kar ka dena hai ya na ho ka ap 2 3 mah bad dein ya company ki reputation bnaty or begarti hai jo market mein phly aye ga whi market ko grab kry ga.
+ **HIGHER QUALITY** market ma rhny ka liye ap ko customer ka satisfaction or phly app sa achy quality deny ho gi.e,g PAyTM
+ **[LESS Capex(capital expendicure)jo lagat shiru mein lgany pry + Opex(operational expendicure)kaam ko chalny mein jo kharcha aye]** apka khrachaa kitna hai india mein aeroplane industry ghaty mwin chal rhy hein.agr ap ko lagat ziada a rhy hai or profit kam tou ap ziada der tak bussiness nai kar skty.
+ **REDUCED OUTRAGES**  ya sab sa important jo agr ap services hi nai provide kar skty tou kisy chz ka b faida nai.airbnb hotel pa discount deta hai lkin ap jab b jao koi hotel khali nai hota services hi nai hoty tou koi faida nai kesy chz ka. customer ko service miln chyie esa na ho k jab b wo kuch purchase kar rha ho tou ap ka server down chly agr esa 2 3 bar howa tou wo isy istemal krna bnd kar dety hein.
+ jo kama mily wo **project** hota hai jo kam da wo **client** aik company project ki base pa hi chalty hai company ma aik manager us ka nechy us ki team jha pa kam huna hai wo **onsite** jha pa kam ho rha ho wo **offshore** agar aik teeam kaam kar rhy hai tou company ko projectt ka liye naye bndy rkhny pry ga is trha market mein **new hirings** aty hein company naye bndy hire kry gi jid mein 2 lakh salary wala developer sa lekr 10 15 hzr waly fresher b rkhy gi.
+ company sab sa phly devloper hire kry ga developer is application ka liye code tyar krry  ga **coding devops engineeer** ko nai krny hoty code ka bad aik executable file bnai ga **.exe** extention waly file bnyny ka bad testing ho gi testing ka liye ehlada team hoty hai like jab humy email deny hai tou likhy bhupinder@xyz.com tou ya error da ga testing isy liye krty hein.
+ **QUALITY ASSURANCE** mein agar ya app bnai hai ya user friendly hai y nai.
+ **DEPLOY** client site pa ja ka deploy krty hein
+ **MAINTENCE + Employee training** 

isy procedure ko **SDLC(software developement life cycle)** khty hein.it is also called waterfall method.ap code ko change nai kar skty.

![alt text](image-1.png)

+ code developer sa build tak la jany ka kam **Jenkin** krta hai jenkin connection ka liye istemal hota hai
+  build ka andar **Maven** istemal krty hein 
+  test mein **selenium** istemal ho ga lkin is ka devops sa koi talq nai hai
+  **DEPLOY** bhut important hai is mein hum **Chef/Ansible/Docker or Kubernetes/puppet** ka istemal kar skty hein.
+  **MONITORING** ma **Nagios ya Cloudwatch** istemal krty hein

## 02 LECTURE
### ***DevOps Tutorial***
---
sab sa phly **developer** code likhta haius ka bad isy **build** kiya jata hai build krny ka bad isy **testing** ka liye bhj diya jata hai phir isy **quality assurance** ka lliye bhj dia jata hai  us ka bad isy **deploy** kiya jata hai us ka bad kuch din iski **maintaince** dhky jaty hai or is ka bd last pa is ki **monitoring** hoty hai.

![alt text](image-2.png)

+ DevOps sa phly kam is SDLC method sa hota tha aik **development team or aik operations team** in dono ma mukhtalif mamlat ki waja sa larai rhty thy. 

+ dono department ka ilawa inki apis ma v larai rhty thy
+ **EVERYTHING IS MANUAL** so it will take more more and more time.
+ in problems ki waja sa aik nai team bnai gai jis ka nam hai **DevOps**  .
+ **DEVOPS ENGINEER** wo bnda hai jo ya sary kam kar skta ya smjh skta ho.

***for AUTOMATION***
---
+ jab **developer** code bnai ga tou wo  **git** pa dal da ga **Jenkins** automatically **build** ko bhj da ga. agr **build** ma koi error ajaye tou wo **Jenkins** ko btaye ga **Jenkins**  **developer** ko update kar da ga developer fix kar ka **git** pa bhj da ga. is tariqy sa kam automate hota hai.
  
+ har lvl pa different types ka tool use hoty hein
  
+ **deploy** mein **chef,docker,kubernetes,ansible or puppet** use hota hai agr 100 server pa koi chz update krny hai tou in tools sa aik sth kar skty hein.  
  
+ **monitoring** mein hum **cloudwatch** istemal krty hein.

***AWS DEVOPS TOOLS***
---
1. codecommit 
2. codedeploy
3. codepipeline

***AZURE DEVOPS TOOLS***
---
1.  repo
2.  artifact

**chef ansible ya open source hai jo aws ya azure wo open source nai hein** isy liye companies general purpose ko ziada prefer krty hein bjeaka jo dependent hun.

***DEVOPS DEF***
---
**Implementing an automation on each and every step**
---
***DevOps Stages***

![alt text](image-3.png)

+ **VERSION CONTROL** mtlb developer jo b kam kar rha hai wo wo yha pa likhy ga.tool jo istemal ho rha hai wo hai **git**.
  
+ **continuous integration** mein code ko review krty hein or agr koi msla aye tou isy dubara wapis bhjty hein **version control** ki trf wo isy solve kar ka subara git pa dal deta hai.

***CI/CD***(Continuous integration + Continuous delivery)

+ **continuous delivery** yha pa code build kry ga uski executable file bnai ga or isy test kry ga testing server pa yha pa hum **Maven** ka istemal kryga

+ **continuos deployment** tou yha pa proper application ki trha dhky ga yha pa bhut sary tools a jate hein jesy **chef ansible kubernetes**.

***methods that were used before devops***
---

![alt text](image-4.png)

+ first is **waterfall methadology** is mein kam jo ho gia ho gia isy change nai kar skty.

+ successor of waterfall is **Agile methadology** is mein hum kam ko choty choty modules mein devide kar ke kam krty hein ya sirf **software developement** lvl pa kam krty hai is sa method ma har bnda apna kam hi krta tha .**silos**.

+ agile methadology ka successor **Devops** hai ya **developement or operation** dono lvl pa kam krta hai.aik bnda hi kam manage kry ga.

+ thg


 