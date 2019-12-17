# Bixby Sample Punch-Out

For Bixby Developers.  

There are times when you need to leave Bixby, either to a website, another app, or for some other reason. There are correct and incorrect ways to do this, and as a rule of thumb the basic idea behind what is correct or not is that "as long as it communicates properly to the user that this would make them leave" then it is probably ok. So that's what this is about, clarity of intent for the user.  

These are to show examples of the correct use of a punch-out component and an incorrect one. Each is stored as a seperate project to be used as example code.  

The Correct punchout shown in the correct example uses what's called an attribution link, this is not misleading to the user as it clearly shows with it's icon that this would leave bixby.  
<img src="https://github.com/michaelbrave/Bixby_Sample_Punch-Out/blob/master/correct.png" width="200" height="400">

The Incorrect Punchout used in the incorrect example uses an onclick and a results-view workaround. This is misleading to the user as the user would not expect the image click take them out of bixby.    
<img src="https://github.com/michaelbrave/Bixby_Sample_Punch-Out/blob/master/incorrect1.png" width="200" height="400">
<img src="https://github.com/michaelbrave/Bixby_Sample_Punch-Out/blob/master/incorrect2.png" width="200" height="400">



Resources that may be useful:  

https://bixbydevelopers.com/dev/docs/reference/type/layout-macro-def.content.attribution-link  

https://bixbydevelopers.com/dev/docs/dev-guide/design-guides/design-principles.ux-policies  

https://stackoverflow.com/questions/57354598/how-can-i-implement-this-punch-out-from-bixby-to-android-app  

https://bixbydevelopers.com/dev/docs/reference/type/result-view.app-launch.payload-uri  

https://bixbydevelopers.com/dev/docs/reference/type/result-view  

https://stackoverflow.com/questions/55698017/how-do-i-have-bixby-use-app-launch-to-open-google-maps/55817611#55817611  
