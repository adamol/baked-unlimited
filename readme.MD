This project is for a fictitious bakery company.
The company buys baking ingredients from suppliers, bakes the bread, and sells them to bakeries.
The company also has its own online store as well as a few bakery retailers.

For this the company IT will need to provide:
- Inventory Management
    + Plan which ingredients need to be bought based on orders
    + Baking ingredients are purchased from vendors
    + Vendor management
- Customer Relations Management
    + Customers are bakeries which purchase the baked goods
    + Lead management
    + Sales counter
    + Email marketing to customers / leads
    + Invoices and reminders
- Human Resources
    + Employee management
    + Payroll
    + Vacation / Sick leave
    + Managing contractors
- Accounting
    + Expenses
    + Sales
- Online Store
    + Gather data for BI analysis
    + Promotions based on BI
    + Deals based on BI

Tech stack:
- Code will probably be mostly PHP, but perhaps some python, java or golang
- Will use terraform to setup server(s) (with digital ocean or AWS)
- Will probably use either docker swarm or kubernetes
- Perhaps ansible for installing docker
- Probably Travis CI for CI/CD
- Automatic deploy to staging and manual deploy to production

