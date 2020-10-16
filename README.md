# employee-expense-management-system
Expense management system for employees at an organization.
## Tech Stack
- MongoDB
- Express.js
- Node.js

## Setting up on local system


1) Install Mongo DB (https://www.mongodb.com/download-center/enterprise) and NodeJS (https://nodejs.org/en/) on your system.
2) Clone the project.

```bash
git clone https://github.com/ShivamS72/employee-expense-management-system.git
```
3) Change directory to the required folder. 

```bash
cd employee-expense-management-system
```
4) Install the dependencies using:
```bash
npm install
```
5) Use two terminals. In one terminal run command:
 ```bash
mongod
``` 
6) In other terminal run the main file i.e. ***app.js*** using:
```bash
node app.js
```
7) Open ***localhost:3000*** on your browser.

## Working
On the front-end, the user will have two options:
- Add expense
- View expense

**Add expense** - The user will need to add his phone number, name, select the type of expense and the amount. There can be two possibilities :
* If the employee already exists, then the expense of the user needs to be updated in the database.
* If the employee does not exists, then the employee with the given phone number will be created. After that, his expense would be added to the database.

**View expense** - The user will be able to view the expenses of the employees existing in the database. Various expenses as well as the total expense will be shown for each employee.

## To be added soon
* Employees will be able to add scanned images of bill, which will then be processed through OCR.
* For daily transport and food bills, employee cards with barcode will be used. A barcode scanner will be used and the expense will be directly udpdated into the database.
