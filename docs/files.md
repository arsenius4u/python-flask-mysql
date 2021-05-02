# All files
Brief description of what each file does

- `static/`
  - `bg.jpg` background picture for homepage
- `templates/` all htmls files
  - `addAirplane.html` page for staff to add an airplane
  - `addAirplaneConfirm.html` page confirming adding airplane was successful
  - `addAirport.html` page for staff to add an airport
  - `agent.html` main page for booking agent
  - `changeFlight.html` page for staff to change status of flights
  - `commission.html` page to show commision in a specify time range
  - `createFlight.html` page for staff to create a new flight
  - `customer.html` main page for customer
  - `error.html` general error page which returns back to the main page (index.html)
  - `index.html` main page of the app
  - `login.html` login page of the app
  - `purchaseAgent.html`, `purchaseCustomer.html` page for booking agent and customer to purchase tickets
  - `registerAgent.html`, `registerCustomer.html`, `registerStaff.html` register page for booking agent, customer, and airline staff
  - `search.html` page for users to search without logging in
  - `searchFlights.html` results page when users search without logging in
  - `searchAgent.html`, `searchCustomer.html`, `searchStaff.html` page for agent, customer and staff to search for flights
  - `searchStaffResults.html` results for staff searching for flights (limited to their airline)
  - `staff.html` main page for staff
  - `viewAgents.html` page for staff to search info about agents
  - `viewAgentsCommission.html` results page for staff after searching for agents based on commission
  - `viewAgentsSales.html` results page for staff after searching for agents based on ticket sales
  - `viewCustomers.html` search for customers on a flight, and search for the most frequent customer
  - `viewCustomersResults.html` results for searching for customers on a flight
  - `viewReports.html` Show graph for tickets sold in last year and search for stats based on range
  - `viewReportsDate.html` Show tickets sold in date range specified
  - `viewReportsPast.html` Show tickets sold in last year/month
- `agent.py` functions for agent's home page to: 1) get ticket counts, commission 2) search through flights
- `appdef.py` defines the configurations of the app
- `customer.py` functions for customers to: 1) view all flights 2) search through flights
- `init.py` initialize the app
- `login.py` login authentication
- `publicinfo.py` search flights without logging in
- `purchase.py` functions for purchasing tickets by customers and booking agents
- `register.py` register functions for customer, agent, and staff
- `staff.py` functions for staff home page and all of their use cases