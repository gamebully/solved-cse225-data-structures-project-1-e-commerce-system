Download Link: https://assignmentchef.com/product/solved-cse225-data-structures-project-1-e-commerce-system
<br>
In this project, you are expected to develop a program in C programming language that imitates e commerce web sites.

Products, customers and the baskets exist in the system. Each product has an id, name, category and a price attributes. Each customer has an id, name, surname and the basket list of his/her all shopping records. Each shopping has its own basket. Each basket has basket id, a list of product inside it and the total amount of all products inside the basket.

There are three input files; one of them contains the full product list (id, name, category, price), the second one contains the customer list (id, name, surname). Third one contains some already prepared basked records (customer id, basket id, product id). Values in input files are <u>tab separated</u>.




<table width="259">

 <tbody>

  <tr>

   <td width="91"><strong>Customer </strong></td>

   <td width="82"><strong>Basket </strong></td>

   <td width="86"><strong>Product </strong></td>

  </tr>

  <tr>

   <td width="91"><strong>id </strong></td>

   <td width="82">id</td>

   <td width="86">id</td>

  </tr>

  <tr>

   <td width="91"><strong>name </strong></td>

   <td width="82">product list</td>

   <td width="86">name</td>

  </tr>

  <tr>

   <td width="91"><strong>surname </strong></td>

   <td width="82">amount</td>

   <td width="86">category</td>

  </tr>

  <tr>

   <td width="91"><strong>basket list </strong></td>

   <td width="82"> </td>

   <td width="86">price</td>

  </tr>

 </tbody>

</table>




Products must be inserted to product linked list alphabetically ordered according to product name. If you check the customer input file, you will notice that customer id starts from 1 and it increases 1 by 1 for each customer. Customers will be inserted to customer linked list each new item will be placed end of the list. The last customer’s id always will be the highest id value in the list. If you check the basket input file you will notice that basket id’s start from 1 and increase 1 by 1 for the same customer. Baskets must be inserted to the end of the basket list of related customer each time.




First, these input files must be read and loaded then a main menu that includes the following commands is required:




<ol>

 <li><strong>Add a customer: </strong>First list all current customers by printing their id, name and surname. Then, the user will be prompted to enter a name and a surname for a new customer. The names are assumed to be unique, so, your program should check whether the entered name exists in the system. The id of newly added customer will be one more than the customer’s id that is at the end of the list. Basket list of newly added customer will be initially empty. <strong>After adding new customer, print all customers again.</strong></li>

</ol>




<ol start="2">

 <li><strong>Add basket: </strong>This operation contains some sub operations</li>

</ol>

<strong> </strong>

<ul>

 <li><strong>List customers: </strong>Firstly, all customer name, surname and id’s must be listed.</li>

 <li><strong>Select one of the customers: </strong>Enter the id of a customer that you can see in the list printed in 2.a. So that, new basket will be added to that specific customer.</li>

 <li><strong>List the products: </strong>All product products ids, names, category and price must be printed.</li>

 <li><strong>Add a product: </strong>The user will be prompted to enter a product id that product will be added to the basket.</li>

 <li><strong>Complete shopping: </strong>When user want to complete shopping user should enter “-1” than the total amount of the basket must be calculated and must be written to the amount field of related basket.</li>

</ul>

<strong> </strong>

<ol start="3">

 <li><strong>Remove customer: </strong>First list all current customers by printing their id, name and surname. Then, the user will be prompted to enter the name and surname of a customer to remove specific customer record. <strong>After removing the customer, print all customers again. </strong></li>

</ol>

<strong> </strong>

<ol start="4">

 <li><strong>List the customers who bought a specific product: </strong>Firstly products must be listed. The user will be prompted to enter one of the product id among list. Output will be the list of customers who bought the selected product.</li>

 <li><strong>List the total shopping amounts of each customer: </strong>When user selects this operation the total shopping amounts of each customer must be listed. Each basket already has its own amount value. So you need to sum up the amount of baskets according for each customer and result must be printed. If a customer has no shopping indicate it while printing.</li>

</ol>

<strong> </strong>

<ol start="6">

 <li><strong>Exit </strong></li>

</ol>

<strong> </strong>

<strong> </strong>

<strong>Note:</strong> Your code can be tested with different scenarios so the content of the input files is not fixed.















































