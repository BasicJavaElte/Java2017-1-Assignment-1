# Assignment 1 - The Taubate Pregnant

![Taubate Pregnant Picture](http://s2.glbimg.com/WbrblpkBMpk8y9riqM6040gUD4sdIs5pE77h-yAgkwdIoz-HdGixxa_8qOZvMp3w/s.glbimg.com/jo/g1/f/original/2012/11/07/falsa_gravida1.jpg)


The Taubaté Pregnant is having her kids soon. The problem is that they are too many and she needs a system to register them. Furthermore, this is not her only pregnancy, she is planning to get pregnant again.

Since they are too many, you need to create a software where the doctor can register each of them, regardless the order it is inserted, and that may help her further, for instance, when she needs to call the kids for lunch, not to forget anyone.

![Edu Guedes](https://pbs.twimg.com/media/Ch462kjWUAAtgZt.jpg)

Edu, a famous TV Presenter got emotional and is moving efforts to collect donations for the kids, since the donations are A LOT, it is important to handle these gifts as well.

The software should give the following possibilities for the users


* Add new baby
* List Babies by age
* List Babies by name
* Add gift
* List gifts


The class Baby should have the following methods:

    // public class Baby

    //Constructors:
    new Baby();
    new Baby(String birthday, String name, char gender)
    new Baby(Date birthday, String name, char gender)

    // Getters and Setters


    // If a given kid is older than the current one
    boolean isOlder(Baby baby)

    // The actual age of the kid in days
    int howOld()

You are free to create other methods that are not listed above and may help your development. ( cof cof toString cof cof equals )


The class Gift should handle the following information:

* Name of the person who gave the gift
* Description of the gift
* Date from when the gift was given

The class Gift has no strict implementation rules, but, you should follow the concepts and conventions learnt in class.




## Constraints
  * The dates shown to the user should always be day/month/year Hour:Minutes, day and month 2 digits, year 4 digits, followed by hour and minutes;
  * The software should already have some objects pre-filled (some persons and gifts)
  * The Class containing the main must be called **BabyRegister**;
  * The other classes should be Baby and Gift;


## Libraries
  The following but not restricted to:
  * Use Java.text.SimpleDateFormat for the dates formatting and parsing (if necessary)
  * You can use the Java.util.ArrayList for storing the objects

## Scoring
Maximum 100 points divided by:
  * 20 points for each menu option
    * Syntax error removes 100% of the 20 points;
    * Semantic mistakes remove up to 50%;
    * Convention and Lexical mistakes remove up to 50%;
  * Not following the given instructions or naming, cancel the points.  

## Rules
  * Individual Assignment;
  * Except from the Java default libraries, all the sent code MUST BE YOURS, plagiarism will be graded with zero and may be subject of sanctions given by ELTE regulations;
  * Copied assignment gives zero score for both (except GitHub),take care of your source code;
  * In case of copy of a GitHub public repository, the date of the commit will be considered, the latest commit will be considered plagiarism;
  * Github delivered assignments will have the code considered until the last commit prior the deadline. (in case of none, the mark is zero);
  * Do not send anything else then folders and .java files;
  * You can pre-send the code until 2 days prior deadline to ask for feedbacks;
  * Instructions for sending will be available on the Canvas assignment;
  * Assignments containing IDE imports or IDE projects will not be considered.


## Extra Points
  * Delivering on GitHub (public or private repo), sending the link via canvas. (+10%)
  * Put the list of gifts inside each baby and make the management inside the Baby class. (+10%)

## DATES
  * **Delivery 29th of October before midnight**
  * Consultation session: 24th October from 14 to 16 (same lab as the classes).
  * Last pre-send date is 27th of October.
