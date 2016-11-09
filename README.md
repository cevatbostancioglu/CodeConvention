## CodeConvention

## WHY ? ? 
When software engineers/developers love writing code, they will really hate you when you tell write code like this, make function names like that, don't use pointer there and so on. But this kind of conventions are very important for companies and modern software development. 

For example, some people like functions names with positive logic( isBroadcastPacket() ) and some others like negative logic( isNotBroadcastPacket() ). If you don't decide posive or negative logic for your framework/API/product, people maybe get confused and your software product will be fail at some point. I have seen before noLog(awesome naming) variable to control mySql debug logs and one of my friend who writes logs API, he get confused, writes code with positive logic(if(nolog)) , don't test the code and publish in repo and We are making dataloggers working with mySql db system so all of the device function working on mySql. When we sell the product(200x) , one week later our dataloggers can't connect to local mySql database and there is no log. So a lot of debugging the code staff and finally we check mySql server parameters and we saw "mysql too much connection" error. Our software is constantly trying open new mySql db connection and software logic can't understand connected to local server. So we can't see this error because we don't have a time to make 1 week testing device function. Sometimes our ram/device can't handle that much connection, device is rebooted by it self and we can't understand problem, we have to run system like 1 week. So just basic naming stuff take a lot of time for us and we really lost our reputation at that point and we have to update 200x product by connecting each one of them.

As a conclusion , if you are software developer and you writes discordant code then don't give a sh*t about the software convention, you are far away from modern software engineering/development.


## INFO
This documents will describe how to write C/C++, Java codes when you are part of software development team. You don't need to be or must follow this structre, you can declare your convention. Docs will be available ASAP!
