# Drive-Migration
This is a script to migrate your google drive files from your old account to your new account.


First install the python packages.
* Terminal
  ```sh
  !pip install google-auth google-auth-oauthlib google-auth-httplib2 google-api-python-client
  ```
Then mount your drive
* Terminal
  ```sh
  from google.colab import drive
  drive.mount('/content/drive')
  ```
Run the script and done! You have now moved your files from your old account to your current account.
