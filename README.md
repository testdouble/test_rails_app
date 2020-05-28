This repository exists to confirm that you have a working installation of Ruby
and Rails.

The application and test steps presuppose that you have Ruby 2.6.6 installed. [Please follow these installation instructions if this is your first time installing Ruby.](https://github.com/rbenv/rbenv#installation)

To test your installation, please execute the following steps:
1. Run `gem install rails` 
2. Clone this repository
3. From the root of the repository, run `bundle install`
4. Run `rails db:setup` to set up the database

To confirm your installation:
1. Run `rails s` to start a server. Navigate to `localhost:3000` - you should
   see a welcome message on this page.
2. Run `rails test` to run the (empty) test suite. You should see output
   similar to that below:

   ```terminal
   Running via Spring preloader in process 84668
   Run options: --seed 4801

   # Running:



   Finished in 0.125063s, 0.0000 runs/s, 0.0000 assertions/s.
   0 runs, 0 assertions, 0 failures, 0 errors, 0 skips
   ```
