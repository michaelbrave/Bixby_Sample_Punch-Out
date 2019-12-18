# Bixby Sample Punch-Out

## For Bixby Developers  

**The Problem:** You need to leave bixby and go to a website. There is a right and a wrong way to do this.  

**Vocabulary:** Things that leave the app are called a punch-out.  

**Reasoning:** As a rule of thumb we are trying to communicate to the user that this will exit bixby and not be misleading.  

**The Incorrect Example:** Uses an onclick and a results-view workaround. This is misleading to the user as the user would not expect the image click take them out of bixby.    
<img src="https://github.com/michaelbrave/Bixby_Sample_Punch-Out/blob/master/incorrect1.png" width="200" height="400">
<img src="https://github.com/michaelbrave/Bixby_Sample_Punch-Out/blob/master/incorrect2.png" width="200" height="400">

**The Correct Example:** Uses what's called an attribution link, this is not misleading to the user as it clearly shows with it's icon that this would leave bixby.  
<img src="https://github.com/michaelbrave/Bixby_Sample_Punch-Out/blob/master/correct.png" width="200" height="400"> 

**Resources that may be useful:**  

https://bixbydevelopers.com/dev/docs/reference/type/layout-macro-def.content.attribution-link  

https://bixbydevelopers.com/dev/docs/dev-guide/design-guides/design-principles.ux-policies  

https://stackoverflow.com/questions/57354598/how-can-i-implement-this-punch-out-from-bixby-to-android-app  

https://bixbydevelopers.com/dev/docs/reference/type/result-view.app-launch.payload-uri  

https://bixbydevelopers.com/dev/docs/reference/type/result-view  

https://stackoverflow.com/questions/55698017/how-do-i-have-bixby-use-app-launch-to-open-google-maps/55817611#55817611  

https://stackoverflow.com/questions/53607074/click-cell-card-and-redirect-external-url
