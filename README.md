# WikiAPI
Created an API (Application Programming Interface) which uses various requests and saves articles to mongodb database with a title and content.

After cloning go to the root directory and run the following command :
npm install

This command will check into package.json file and install the required node modules in the root directory.
After that in the file app.js, replace the mongoDB database name with whatever you wish for.

mongoose.connect("mongodb://localhost:27017/wikiDB", {useNewUrlParser:true});

Mine was wikiDB, you can replace with yours.
Then in the Schema you can define yours with various fields.
I have used chained routing so make sure you dont add a semicolon(;) after any of the routing method until and unless it is a last one.
