# FunBooks
This is a single-page online bookshop application FunBooks using the MEAN stack (MongoDB, Express.JS, AngularJS, and Node.js).
Users can check the book listed in the bookstore, find their detailed information, sign in, add books to their carts, checkout, sign out and so on.
(It is Assignmnet2 of COMP3322 Modern Technologies on World Wide Web)

To load the webpage:
1.	Open terminal1. Go to file mongodb and start MongoDB server using:
        $./bin/mongod --../FunBooks/data
2.  Open terminal2, go to mongodb file and use：
		    $./bin/mongo 
        $use assignment2
    Note: We store data in the database named 'assignment2'. One can see the contents of the two collections in this database     using 'db.userCollection.find()/db.bookCollection.find()'
3. Open terminal3, use:
        ($npm install //if you have not installed the dependencies in the node_modules folder)
        $npm start
4. Webpage loads at http://localhost:3000
    
