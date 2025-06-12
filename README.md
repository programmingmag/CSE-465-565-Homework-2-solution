# CSE-465-565-Homework-2-solution

Download Here: [CSE 465/565 Homework #2 solution](https://jarviscodinghub.com/assignment/cse-465-565-homework-2-solution/)

For Custom/Original Work email jarviscodinghub@gmail.com/whatsapp +1(541)423-7793

(1). (25/20) Write an ASP program that can determine if one person is a great uncle or great aunt to another person, that is
if one person is an uncle or aunt of one’s mother or father. The great uncle and great aunt can obtain their status via
marriage. The great niece/great nephew status is never obtained via marriage.
The program you write should run with the DLV solver and should define two relations:
great_uncle(X, Y) – X is a great uncle to Y
great_aunt(X, Y) – X is a great aunt to Y
To test your program, use the following family information:
married(male1, female1). % male1 and female1 are married
mother(female1, male2). % female1 is the mother of male2
father(male1, male2). % male1 is the father of male2
mother(female1, male3).
father(male1, male3).
mother(female1, female2).
father(male1, female2).
married(male2, female3).
mother(female3, male4).
father(male2, male4).
mother(female3, male8).
father(male2, male8).
married(male3, female4).
mother(female4, female5).
father(male3, female5).
mother(female4, male5).
father(male3, male5).
married(male6, female2).
2
married(male4, female6).
mother(female6, female7).
father(male4, female7).
mother(female6, male7).
father(male4, male7).
married(male8, female8).
mother(female8, female9).
father(male8, female9).
married(male7, female10).
Here is a graphical view of this family tree:
It is your responsibility to add facts about who is a person (e.g., person(male1).) and facts to specify the sex of each
person (e.g. sex_of(male1, male).). You can reuse code from the family knowledge base we wrote in class.
Write a general rule to say that married is a symmetric relation.
(2). (22/17) Write an ASP program to be run with the DLV solver that encodes the following knowledge:
American citizens normally live in the United States. American diplomats may or may not live in the United States.
John, Miriam, and Caleb are American citizens. John lives in Italy. Miriam is an American diplomat. Assume that
people only live in one country – their main place of residence.
Make sure that the inferences made by your program about the place of residence of John, Miriam, and Caleb mimic those
of a cautious reasoner. Use the methodology illustrated in class and described in the handouts to represent defaults and
their exceptions. The program you write should define the relation:
lives(X, Y) – person X lives in country Y
CSE 465 students: assume that you have complete information about who is a diplomat or not. Your program should infer
that John does not live in the United States; it is unknown whether Miriam lives in the United States or not; Caleb lives in
the United States.
3
CSE 565 students: assume that we have incomplete information about who is a diplomat or not. Your program should
infer that John does not live in the United States; it is unknown whether Miriam lives in the United States or not; it is
unknown whether Miriam lives in the United States or not.
(3). (25/20) Write an ASP program to be run with the DLV solver that solves the following problem using the generateand-test methodology:
Given a round table with six chairs and a group of six people, some of whom are married and some of whom do not
like each other, find a seating assignment for members of this group such that husbands and wives are seated next to
each other and no neighbors dislike each other.
Use and extend the starter code provided in the file problem3.txt. Make sure to define the relation:
seated(P, C) – person P is sitting on chair number C
(4). (0/20) (Only for CSE 565 students) Write an ASP program to be run with the DLV solver that solves the following
problem using the generate-and-test methodology:
At a recent Pets Anonymous reunion, the attendees were discussing which pets they had recently owned. Four people
were attending: James, Kevin, Becky, and Rita. At each point in time (i.e., past and present), each person owned only
one pet and each pet was owned by only one person. James used to have a dog. The person who used to own a mouse
now owns a cat. The person who used to have a cat does not have a mouse. Kevin now has or used to have a dog, I
can’t remember which. Becky has never owned a mouse, not now and not in the past. Only one person now owns the
pet they previously had and that pet is a hamster.
Use and extend the starter code provided in the file problem4.txt. Define the relations:
had(Person, Pet) – in the past, person Person owned pet Pet
has(Person, Pet) – right now, person Person owns pet Pet
(5). (25/20) Write a report that evaluates the language of Answer Set Prolog (ASP) using the four main criteria learned in
class. Use the table below and write at least two ideas in each cell.
Criterion Pros Cons
Readability
Writeability
Reliability
Cost
(6). (3/3) Write a short summary of the contributions of each team member for each problem in this homework
assignment. Specify if members participated in the initial development of the solution vs. verification & validation.

