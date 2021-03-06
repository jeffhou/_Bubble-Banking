# Bubble Banking
Bank Statement Reinvented through Data Visualization

Project hacked together for HackDuke 2015

Technologies Used: Flask, Python 3.5, D3.js, Capital One API (api.reimaginebanking.com)

Goals & Features

  Our application is a robust tool used to interpret bank statements in a very intuitive way. The classic model of financial statements consists of difficult to read income statements and lists of transactions. As a result, users are often not immediately provided with the important data. Our project is designed to empower users to make more informed decisions about their finances. Therefore, we designed our interface with user ease-of access in mind. Our interface allows users to select their user accounts and then specify which bank account they want to view (i.e. checkings, savings, credit card, etc.) After specifying an account, the user is presented an elegant home page where they can see four main classes of activity: deposits, withdrawals, transactions, and purchases. Each of these bubbles links to separate bubbles containing more information about that specific type of activity. For example, entering the "Purchases" page allows a user to see who their most commonly visited merchants are and where they spend the most money. Clicking on specific merchants at this point gives individualized purchase information in a timeline format depicting all purchases the user made with that merchant over the past month. The transactions page provides a user with a chart of all accounts in which they have completed tranactionss over the past month, and clicking on a specific transaction provides a timeline view of all transaction information with that specific account. Similarly, the "withdrawals" and "deposits" pages provide users a timeline of all withdrawals and deposits, respectively, that the users have completed in the past month. All of our features are linked together to ensure ease of access to any page and in order to maximize user understanding, the sizes of our figures are scaled accordingly to the monetary value.

Programming Strategy

  We programmed the back-end using Capital One API and Flask and designed the front-end, including all of the charts with D3.js.
  Multiple pages were seperated into individual html files which each read specific data.
