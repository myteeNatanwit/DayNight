Day Night
=========

Very simple time detecting to change the Dom to its day/night class. However, this required as an important feature of the project with Toptal. The sample shows a few classes affect by the time. By adding a timer, the UI can be richer presented. 

#idea
Checking current loading time, if it is between 7am and 8pm then it is day time.
document.documentElement.className= "day";
or 
document.documentElement.className= "night";

#Usage
can try something like this for night class

.night h1{
color: green;
}

.night body{
background: url('asset/night.jpg') no-repeat;
background-color: DarkCyan ;
background-size:cover;
color:blue;
}
and in day class

.day h1{
color: yellow;
}

.day body{
background: url('asset/day.jpg') no-repeat;
background-size:cover;
background-color: gray;
color:red;
}


#Note
It is very simple code, read it then. At later stage, you will see how it works nicely in other project.
