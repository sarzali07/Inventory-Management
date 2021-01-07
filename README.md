<h1>Laravel Inventory</h1>
<p>The Inventory Management is a web application that manages inventory, sales, and transactions for small businesses.</p>
<p>Also, This application has a rich UI interface which provides valuable statistics about sales, products, income, expenses, and transactions.</p>
<p>Beginners as well as intermediate developers can learn a lot from it. In general, this application controls most of the activities of a small organization. Therefore, this program is simple as well as informative for a business that requires selling products.</p>
<p>Some features of inventory management system are:</p>
<ul>
    <li>Register products, categories, receipts, users, and others.</li>
    <li>Reports and statistics on income and expenditure.</li>
    <li>Manage sales, payments, and transactions.</li>
    <li>View clients’ payment history.</li>
</ul>
<h1>Requirements</h1>
<ul>
<li>PHP between 7.0 and 7.1 - migration to newer symfony is needed before we support current php 7.x</p>
<li>A MySQL or PostgreSQL database</p>
</ul>
<h1>Installation Steps</h1>
<ul>
    <li>git clone https://github.com/sarzali07/Inventory-Management.git</li>
    <li>cd Inventory-Management</li>
    <li>composer install</li>
    <li>cp .env.example .env</li>
    <li>create a database and add credentials to .evn in mysql section.</li>
    <li>php artisan key:generate</li>
    <li>php artisan storage:link</li>
    <li>php artisan migrate</li>
    <li>php artisan serve</li>
</ul>

<p>Here are some snippets of the system:</p>
<img src="https://www.sarfarazlaghari.com/assets/uploads/2021/01/4-1-1024x506.png">
<h5>Login/Registration</h5>

<img src="https://www.sarfarazlaghari.com/assets/uploads/2021/01/1-768x377-1.png">
<h5>Dashboard</h5>

<img src="https://www.sarfarazlaghari.com/assets/uploads/2021/01/2-1024x502.png">
<h5>Transactions List</h5>

<img src="https://www.sarfarazlaghari.com/assets/uploads/2021/01/3-1024x501.png">
<h5>Inventory Statistics</h5>
