2. The value returned if you get the machine's balance after it has printed a ticket is: 0. This is because the printTicket() method returns the balance to 0 every time it prints a ticket.

3. Inserting too much money into the machine doesn't get you a refund. Even if you do not insert enough money (eg: Ticket price is 5$, but you only insert 1$, the machine still prints a ticket. This is because there is no code that verifies whether the amount of money inserted is = to the cost of a ticket.

6. For the labClass class, it should be 'public class labClass' and for the Student, 'public class Student'

7. Yes, it does matter. Writing 'class public TicketMachine' makes the class diagram criss-crossed with red (since it's an error).

8. Yes, it is possible. You don't have to write private/public in order to make the outer wrapper function.

9. You cannot delete the word "class" from the TicketMachine's outer wrapper because it basically removes the entire class (which means that we no longer have a class, just as if we removed the entire frame of a building. You still have all the furnitures left, but you can't live in it).

10. *This is answered after I've done many of the later steps, and I no longer remember what the original code looks like* The constructor is: public ticketMachine(int price), the fields are: private int price; private int balance; private int total; private int status;. The methods are: getPrice(), getAmount(), insertMoney(int amount), status(), getTotal(), prompt(), printTicket().

11. The two main differences that, firstly, I've noticed are that the constructor needs to have the same name as the class it belongs to. The methods could be named 'RandomHotdog' and still work properly if the body functions properly, but the constructor will not. Secondly, the constructor does not have a return type (such as 'void', 'int', etc).

12. The first is an int, the second and third are both class types.

13. Since we now know what the 'type' is, we know that the names are: alive, tutor and game.

14. Class names need to start with a capital letter, and should also not be something like an int or boolean. So, the class names are: Student, Server, Person and Game.

16. Yes, or there will be an error message. 

17. private int status;

18. The 'Student' class.

19. It has two parameters: title and double price. 'title' is a String, and price is a 'double'.

20. Yes, if we don't assign the parameters to the fields of the class, they will just vanish. Some of its fields might be: author (String), price (int), word count (int), house of edition (String), etc. However, I don't think we can know for certain that these will be names of its fields. For all we know, a book might also have no author name, no page count, or be a completely blank book.

21. name = petsName;

22. public Date(String month, int day, int year)

24. A call to getBalance can be caracterized as "How much money is in the machine?" though it would only work after inserting money and before printing a ticket.

25. No, not at all. The name of the accessor method doesn't have to be the same as the name of the field associated with it in order for it to work.

27.

28. getPrice uses 'public int', while printTicket uses 'public void'. This is because getPrice needs to return a value (int), while printTicket's goal isn't to return something (void).

31. score = score + points;

32. Yes, since its a setter, which means that it changes the state of an object to something new. We can create a new student object and use System.out.println() to see how many credits the student had before and after the change. I think that we just have to make sure to write the code for adding the extra credit in-between the two system prints (so that it works properly).

33. price = price - amount;

34. public void setAge(int currentAge)
{
  age = currentAge;
}

35. public void setAlive(boolean status)
{
  alive = status;
}

36. After modifying the constructor to make it so that price = price, any price related method only returns zero (instead of the actual price that we put in)

37. The exact output is: My cat had green eyes.

39. In that case, the price will no longer be an int (the actual prive that we've set, but simply: price

40. Again, it will simply be printed out as: # price cents.

42. No, they do not return the same price, as they do not have the same ticket price when we created them. This is because they are different instances of the same thing. 

43. Yes, the printf prints out exactly the same thing as before. From what I've seen and tested, %d seems to be used to add a number (int). Since the price is at the end of the line, but is still printed in the exact same place on the terminal, I'm assuming that %d basically gets replaced by the int(?). %n I really had no idea, so I had to do a quick search online, and I found out that it means newline, used to go to the next line, so its use here is to jump to the next line after printing out "cents."

44. It now no longer asks you to input the price when you create a new TicketMachine object.

45. You now have 2 options when creating a TicketMachine, either make it so that the price is a set amount or input the price manually.


