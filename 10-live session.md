cmd ma absolute directory dein cd.. sa aik directory pechy chly jaty hein cd. ma usy directory ma rhty hein new directory bnany ka liye mkdir likh KAR AGY US KA NAME da dein diresctory check krny ka liye dir likhy tap ka mtlb programming ma auto complete hota hai agy libraries install karwaty hein

_**steps invovled in data visualization** _

**step 1 import librarie like**

import seaborn as sns

**step2 set a theme** 

sns.set_theme(style="ticks", color_codes=true)

**step3 import data set you can also import your own data set**

kashti=sns.load_dataset("titanic")

print(kashti)

**step4 plot basic graph with 1 variable (count)**

p = sns.countplot(x="sex ",data=kashti)
plt.show()

**step4 plot basic graph with 2 variable (count plot) with title**

p = sns.countplot(x="sex ", ,data=kashti, hue="class")

p.set_title("title name")

plt.show()

