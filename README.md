## CodeConvention

## WHY ? ? 
When software engineers/developers love writing code, they will really hate you when you tell write code like this, make function names like that, don't use pointer there and so on. But this kind of conventions are very important for companies and modern software development. 

For example, some people like functions names with positive logic( isBroadcastPacket() ) and some others like negative logic( isNotBroadcastPacket() ). If you don't decide posive or negative logic for your framework/API, people maybe get confused and your software product will be fail at some point. I have seen before noLog(awesome naming) variable to control mySql debug logs and one of my friend who writes logs API gets confused, writes code with positive logic and don't test the code and we are making dataloggers working with mySql db system. When we sell the product(200x) , one week later our dataloggers can't connect to local mySql database and there is no log. So we check mySql server parameters and we saw "mysql too much connection" error. Our software is constantly trying open new mySql db connection and software logic can't understand connected to local server. So we can't see this error because we don't have a time to make 1 week test and we have to update 200x product by connecting each one of them and so on. 

As a conclusion , if you are sort of software developer and you writes discordant code and don't give a sh*t about the software convention, you are far away from modern software engineering.


## INFO
This documents will describe how to write C/C++, Java codes when you are part of software development team. You don't need to be or must follow this structre, you can declare your convention. Docs will be available ASAP!
