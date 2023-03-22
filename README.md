# Stock-Management-System
So,The Stock Management System (SMS) refers to the system and processes to manage the stock of organization with the involvement of Technology . This system can be used to store the details of the stock, stock maintenance, update the stock based on the sales details, and generate sales and stock report daily or weekly based.

## Introduction
* The Existing Stock Management System Has Been A Very Non Efficient One, It is time consuming and non effective, this makes it non economical for a organization to use it as it uses lots of manual labour and unorganized paper work.
* So,The Stock Management System (SMS) refers to the system and processes to manage the stock of organization with the involvement of Technology . This system can be used to store the details of the stock, stock maintenance, update the stock based on the sales details, and generate sales and stock report daily or weekly based. 
* This project is categorize individual aspects for the sales and stock management system. In this system we are solving different problem affecting to direct sales management and purchase management.
* Stock Management System is important to ensure quality control in businesses that handle transactions resolving around consumer goods. Without proper stock control, a large retail store may run out of stock on an important item. A good stock management system will alert the wholesaler when it is time to record. Stock Management System is also on important means of automatically tracking large shipment. An automated Stock Management System helps to minimize the errors while recording the stock.

## Algorithm

### Part 1: Storing data.
* Two HashMap are used in this program.
* One HashMap is for the stocks(hm1) and the other is for the costs of the items(hm2).
* The HashMap used here are of the type of String to Integer.
Where the user stores the item name in the key of the HashMap and stores the cost or stock in the value of the HashMap
* Initializing the HashMap.

 * Here hm1 takes the stock values, and hm2 takes the price of the items.
"'HashMap<String,Integer> hm1=new HashMap<String,Integer>();
HashMap<String,Integer> hm2=new HashMap<String,Integer>();"'
* To add the item and the stocks,
"'System.out.print("item:"); String item=scan.next(); System.out.print("stock:"); int stock=scan.nextInt(); hm1.put(item,stock);"'

* To add the price the code is
"'System.out.print("item:"); String item=scan.next(); System.out.print("cost:"); int cost=scan.nextInt(); hm2.put(item,cost);"'
* If user wants to exit from providing information, user needs to Enter (-1).

### Part 2: Billing.
* While billing, the price of the item is known by hm2, and the stock value is deducted from hm1.

### Part 3: Printing stock value.
* If the user wants to know the stocks at the moment, he needs to Enter “stock”.

### Part 4: Assembling part 1, part 2 and part 3 in main function.
* An infinite while loop is used, so that the user can get to whatever parts he needs after end of the loop.
* Inside the Infinite while loop the user will be asked what does he want to do,
System.out.println("TO DO?");
- →If user wants to provide information, user needs to enter ‘add’.
- →If user wants to go to billing, user needs to enter ‘bill’.
- →If user wants to know the stock value, user needs to enter ‘stocks’.
* The input will be scanned by the system. String to_do=scan.next();
* If the input is ‘add’, System will take the user to provide information i.e. part 1.

if(to_do.equals("add"))
{

//part 1;
}

* If the input is ‘billing’, System will take the user to billing i.e. part 2.if(to_do.equals("bill"))
{

//part 2;
}

#### To know more access the pdf file 

* If the input is ‘stocks’, System will print the stocks i.e. part 3. if(to_do.equals("stock"))



//part3;

