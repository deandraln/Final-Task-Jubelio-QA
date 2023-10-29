# Final-Task-Jubelio-QA
Final Task Jubelio QA - Batch Oktober 2023 - Deandra Leyla Nabila

**Prerequisites**
- Ensure that you have Ruby installed. To check if Ruby is already installed, use the following command: `$rvm list`.
- Make sure you have Cucumber installed. To check if Cucumber is already installed, use the following command: `$cucumber --version`.

**Preparation Steps**
1. Add the following lines to your `Gemfile`:
   ```ruby
   source 'https://rubygems.org'

   gem 'capybara'
   gem 'cucumber'
   gem 'pry'
   gem 'rspec'
   gem 'webdrivers'
   ```

2. Run the following command to install all dependencies using Bundler:
   ```
   bundle install
   ```

3. Add an environment file like the one below to `features/support/env.rb`.

4. Run the following command to initialize Cucumber:
   ```
   cucumber --init
   ```

5. Ensure you have a text editor (e.g., Visual Studio Code) installed.

6. Install the Cucumber extension in your text editor.

**How to Run Automation Scenarios Locally**
1. Clone this repository using the following command:
   ```
   [git clone https://github.com/deandraln/Final-Task-Jubelio-QA.git]
   ```
2. Open this repository in your text editor.
3. Open the terminal in your text editor.
4. To run all scenarios, use the following command:
   ```
   cucumber
   ```
5. To run specific or multiple scenarios, use tags like this:
   ```
   bundle exec cucumber -t @login
   ```

By following the above steps, you will be able to run automation scenarios locally on this repository. 
