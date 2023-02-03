# Flask-library-to-manage-a-microfinance-system
a simple API code in Python using the Flask library to manage a microfinance system

This code creates an in-memory database of clients with their balances, and implements the following endpoints:

/add_client: Accepts a POST request with a JSON payload containing a "client_id" and "client_name" key, and adds a new client to the database.
/get_client_balance: Accepts a GET request with a "client_id" query parameter, and returns the balance of the client with the given ID.
/update_client_balance: Accepts a POST request with a JSON payload containing a "client_id" and "new_balance" key, and updates the balance of the client with the given ID.
