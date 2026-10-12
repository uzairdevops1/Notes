# BASIC OF PYTHON

## 1-OPERATORS

operators ko run krny ka kfy tariqy hoty hein yha par hum dekhy ga terminal mein operator kesy run krty hein 

- sab sa phla operator addition(+) ka hai.we can write in cmd for use of addition operator.
  > print(2+2)
- second operator subtraction ka hai. isy istemal krny ka liiye cmd ma  likhne pry ga.
  > print(3-2)
- third operator multiplication ka hai.  values ko multiply krny ka liye hum histeric ka sign use krty hein like .
  > print(3*2)
- forth operator division ka hai.values ko divide krny k liye istemal  hota hai like we have to write for dividing two values it will show values in like float values.
  > print(9/2) 
- fifth operator is floor division(//). In this operator after dividing num is round off to smaller num.
  > print(10//3)
- sixth operator is modulus or remainder.
  > print(9%2)

   in this operator it will simplify like 2*4=8 but the remainder that is remaining is 1.which means the number left over after divide.

- seventh operator is exponent(**).this operator is used to give power to number.
  > print(2**3)

spaces are meaning less in python.

**PEMDAS**(paranthesis, exponenece, multiply, divide, add, subtract) is sequence sa python code run krta hai.it will work left to right.M D & A S

## 2-STRINGS

koi b text jo excel ma use ho within single comma,double quotation mark ya 3 quotation mark usko strings bolty hein.

>print("hello, world")
>
>print("that was my first program")
>
>print('thanks god')
>
>print("actually i'm enjoying it")
>
>print('''yes i know that it is multi line string i just wanna practice it''')

agar ap spaces string ka bhir lgae ga tou koi impact nai pry ga lkin agr ap sapces andar lgae ga tou wo exactly output ma b show hon gi.

## 3-comments

program ma jo code b hum run nahi krwana chahty usy hum comment out kar da ga comment out krny ka 2 tariqy hein aik **#** lga ka dusra **ctrl+/**. e.g 
>#print(2+5)
>
>print("for comment") isy select kar ka ctrl+/ dba dein

it will work in up to down.

## variables

variables object hoty hein containing spercific values.agar hum x=5 likhy tou x variable hai or is ki value 5 haii.ya aik integer variable hia.isy trha agr hum y="this is string" is mein y variable hai or is ka samny is ki value assign ki hoi hai ya aik string variable hai.

>x=8
>
>print(x)
>
>y="uzair"
>
>print(y)
>
>x=6 
>
>print(x)
>
>y=x+4
>
>print(y)


### types/class of variable

type of variable check krny ka liye print likh ka is andar type(variable) likhay ga like **print(type(x))** tou is ki  class a jaye gi

**rules to assign a variable**

1- the variable name should not start with a number

2-the variable name should not contain special character we can only use characters or numbers or underscores.

3- the keywords cannot used as variables

4- do not space between variables.

5- short or descripted

6- python is a case sensitive language so be careful while assigning variables.

>fruit_basket="mangoes"
>
>print(fruit_basket)
>
>type(print(fruit_basket))

is code mein fruit_basket aik variable jis mein mangoes value assign ki gai hai.nechy output ka liye print ka function use kia howa hai.3 line mein variable ki type/class check krny ka liye code likha gia hai.is ki class string aye gi.

## 4-input variables

user sa sawal pochny ka liye hum **input function** use kkrty hein like ma program bnata hun apko fruit konsa pasnd hai khud user ya customer choose kar la ga.

**simple input function**

>fruit_basket="mangoes"
>
>print(fruit_basket)
>
>fruit_basket=input("which is your favourite fruit?  ")
>
>print(fruit_basket)

is code ma addition sirf input fuction ki hovy hai websites mein b esy tariqy sa sawal pochty hein.

**input function of 2 stage**

>name=input("what is your name? ")
>
>greetings="hello"
>
>print(greetings,  name )

is program ma phly hum na name variable rkha values mein input fuction use kia gia hai jis main nam pochha gia hai . second line mein greetings variable or agy string value . third line mein print fuction use kar ky bataia gia hai k phly greetings print kry phir name.

**third stage input function**

>name=input("what is your name? ")
>
>age=input("what is your age? ")
>
>greetings="hello!"
>
>print(greetings, name, ",you are still young " )

basically ya bi same hi hai bas is ma 3 input perimeters diye hein jis mein aik mein name pochta hai 2sra ma age pochta hai or 3sry mein greetings hai.print ma in ki sequence ya di hai ka phly greetings phir nam phir age or jab user age btaye ga tou ya us ki jaga pa you ARE STILL YOUNG likh da ga.

## 5-conditional logical operator

**logical operators are either "true or false" or "yes or no" or "1 or 0"**

- equal to                    ==

- not equal to                !=

- less than                   <

- greater than                >

- less than or equal to       <=

- greater than or equal to    >=

agar hum python sa pochty hein 4 equal to 4 tou wo error da ga pyton sa us ka syntax ka mutabik question pochty hein like

> print(4==4)
> 
> print(4!=4)
> 
> print(4>3)
> 
> print(3>6)
>
> print(5<6)
>
>  print(3<=5)

**application of logical operators**

>ali_age=4
>
>age_at_school=5
>
>print(ali_age==age_at_school)

ya program bnia hai jis mein bchy ki age add kar ka pata kar skty hrin ka wo school ka liye eligible b hai ya nai.phly line ma bchy ki age btaty hein dusry line ma school ka liye required age third line ma equal ka operator laga ka pata kia jta hai ka bchy ki age school jany ka qabil hai ya nai.

hum jab netflix pa ya khy pa b movies waqera dhkty hein wha pa age ka pochty hein wo b esy method sa hoty hein

**another method**

>hammad_age=input("how old is hammad? ")
>
>hammad_age=int(hammad_age)
>
>age_at_school=5
>
>print(hammad_age==age_at_school)

is program ma input function or logical  operator or type conversion istemal kiye gye hein

## 6-type conversion


aik data type ko dusry data type ma convert krny ko type conversion khty hein

>x=10
>
>y=10.2
>
>z="uzair"
>
>print(type(x))
>
>print(type(y))
>
>print(type(z))

is code mein x integer hai y float hai or z string hai

**implicit type conversion**

> print(x*y)
 
 ***implicit ma python khud convert kar leta hai or***

 agar hum x ko y sa multiply kren class float ma aye gi jab b integer ko float sa multiply ya plus kren ga tou class float mein aye gi

**explicit type conversion**

>age=input("what is your age? ")
>
> #age=int(age)
>
>print(age, type(int(age)))

***explicit mein hunmy khud krny hoty hai***

phly line mein hum na input function lga ka user ki age pochy or dusry code mein hum na age ki class change ki hai or 3ry line ma hum na 2 sry line ko comment out kar ky or method sa class change ki

## 7-if else & elif statements

_**IF STATEMENT**_

>hammad_age=2
>
>required_age=5
>
>if hammad_age==required_age:
>
>    print("hammad  can join school")
  
  is code ki phly line ma age btaye hai dusry ma required age btaye hai 3sry ma if statement or equal ka operator istemal karky btaia ya pocha gia hia ka agr age, required age ka equal hia tou print kry hammad can join school .

_**if else**_

  jab ap if satement likhty hein tou ya b btaye ka gr ya statement true na ho tou ya print kar dy usky liye hum **if else** ka use krty hein. like

  >hammad_age=2
>
>required_age=5
>
>if hammad_age==required_age:
>
>    print("hammad  can join school")
> 
> else
>  
>    print("hammad can not go tto school")

_**elif statement**_

 >hammad_age=2
>
>required_age=5
>
>if hammad_age==required_age:
>
>    print("hammad  can join school")
>
> elif hammad_age>required_age 
>
> print("hammad should join higher school")
> 
> else
>  
>    print("hammad can not join school")

elif mein hum bas multiple conditions use kr skty hein


## 8-functions 

basiclly funtion **reuseable block of code** hota hai

agar program mein koi kam bar bar krna ho tou us ka function bna lo is sa ap ko
bar bar code nai likhna pry ga blky ap jab b function ko call kro ga function chal
jaye g

**defining a function**

def print_codanics()
>print("we are learning with uzair")
>
>print("we are learning with uzair")
>
>print("we are learning with uzair")

is line mein 3 cheezy hein phly or print ma wo data hai jisy hum function bnana chahty hein

-  **def**  -->    define krny ka liye sab sa phly
likhty hein ya aik python ki command hai
- **print_codanics** --> ya funtion ka nam hai
- **( )** --> ya paremeters function ka liye lazi hai

> print_codanics 

ab hum jab b print codanics print kry ga tou ya function clhy ga

**another way of defining a function**

>def print_codanics():
>
>text="we are learning with uzair"
>
>        print(text) 
>
>        print(text)
>
>        print(text)
>
>print_codanics()
 
 **third way of defining a function**

>def print_codanics(text):
>
>     print(text)
> 
>     print(text)
> 
>     print(text)
>
>print_codanics("we are learning with uzair")
 

 **defininig a function with if,else & elif statement**

>def school_calculator(age):
>
   >   if age<=5:
   >
   >      print( "you can join school" )
   >
   > else:
   >
   >     print( "you are not old enough for school")
   >
>school_calculator(3)

is program ma phly line ma def ka function use howa hai baqi program as usual or end ma def  ka function ko input dia hai jis pa process kar ka us na output da dia 

## 9-loops

**Loop ka matlab hai ek hi code ko baar-baar chalana (repeat karna)**

jesa ka ap sabhy janty hein ka jab aik bcha 5 sa 10 saal ka hota hai tou uski mama usy rozana subha utha ka school bhjty hein until jab tak wo khud tyar ho kar jany ka qabil na ho jaye

2 trha ka loops hein

- while loop
- for loop

1. **while loop**

Jab tak condition True ho, loop chalta rahega.while loop ko infinite loop
b khty hein

>x=0
>
 >  while (x<=5):
>
 >    print(x)
 >
  >  x=x+1

phly line ma x=0 define kia or while function ko use kia jia ma conditional logical operator use kia ka jab tak x 5 ka less than ya equal hai tou x print hota rhy phir print ka functiona use kar ky btia ka x ko print kry or forth line ma increment opertOR USE KIA   agr ya na krty tou x ki value infinite chlty rhty is liye while loop ma increment or decrement operator ko lazmi use krna chyie

2. **for loop**

Jab tak condition True ho, loop chalta rahega

     for x in range(6, 13):
         print(x)

jo range di gai hai jab tak is range ma value ayein gi loop chlta rhy ga for example

>days=["mon","tues","wed","thur,"fri","sat","sun"]
>        
>
>for d in days:
>
>   if(d=="fri"):break
> 
>    print(d)

hum na aik array bnai or dusry line ma isy d ka nam da dia 3 line ma hum na logical operator use kia or us ka bad break lga di us ka bad print d kar dia

## 10-import libraries

bhut saray programmers hai jinhu na bhut sary functions define kiye hovy hein tou khud sa function define krny ki bajye open source ap unky fucntion use ka skty hein for example **agar ap chahty hein ka pi ki value print kry** tou hum math ki library import krty heun import krny ka baad math ka sary function hum use kar skty hein like

>import math
>
>print("the value of pi", math.pi)

>import statistics
>
>x=[150, 250, 350, 450]
>
>print(statistics.mean(x))

agar hum ya command dein ga tou iska mean ajye ga is trha sa hum different type ka statistics ki libraires ko use krsty hein is ma kia kia hai hum statistic. kar ka tab dabaye ga tou saby options a jaye ga

**important libraries**

- numpy
- pandas
  
## 11-trouble_shooting

**trouble shooting is the process of finding and fixing errors in the program 
there are three main types of error**

- syntax error
- run time error
- logical error
  
1. **syntax error**

agar hum language ka syntax ka according code nai likhy tou ya syntax error ho ga like

>print("missing commas)

missing commas

2. **run time error**

program run krty waqt error aye like when we divide something to zero mathe matically error ko run time error keh akty hein

> print(25/0)

3. **logical** **error**
 
 poor knowlege of programmer like 

 >name="uzair"
 >
 >print("hello uzair")

 ia error main user ki apny ghlty hoty hai.ya error sab sa difficult hai trouble shooting ma