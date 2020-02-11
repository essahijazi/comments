# comments

Line comments start with // and end at the end of the line 
They can be added on their own line or at the end of a line

//This is a valid comment
System.out.print("Hello World");

System.out.print("Hello World"); //This is a valid comment

*********************************************

Multi Line comments start with /* and end with */
They can span multiple lines such as

/*
* this is 
* a multi line 
* comment
*/

Or, they can span one line. They do not have to be at the end of the line

System.out.print("Hello World"); /*This is a valid comment*/
System.out.print(/*This is a valid comment*/"Hello World"); 
/*This is a valid comment*/System.out.print("Hello World");

*********************************************

JavaDoc comments start with /** and end with */. JavaDoc utility allows you to generate class documentation using this notation

/**
* This method takes two arguments and returns their total
*/
