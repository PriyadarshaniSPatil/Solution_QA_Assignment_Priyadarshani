
Once the setup is ready. i.e once you have installed all the required tools, run the command below from the root of this repository. (from a terminal on Mac or a DOS prompt on Windows 10).

```````````````
npm install
```````````````

Now, you should be able to see the homepage tests succeed by running this command:

```````````````````````
npm run homepage-test
```````````````````````

You should see the test pass, as it evaluates a website in your Chrome browser.

Your assignment
----------------

1) Go the file named src/homepage-test.js and add new lines of code which verifies the following: (one question is already solved for you)
    - Given 
        the site 'https://uat.oktaxrolls.com/' is up and running
    - When 
        the user navigates to the homepage
    - Then
        - The list 'Select County' is not empty.
        - The county 'Garfield' is present in the map. (already solved for you)
        - Hovering over 'Garfield' county will display the county treasurer info.
        - Take screenshots wherever required via the script itself (no manual screenshots).

Run the script and verify if the test succeeds.


2) Add a new file named src/county-test.js and create a test which verifies the following:
    - Given 
        the site 'https://uat.oktaxrolls.com/' is up and running
    - When 
        the user navigates to the 'Garfield' county page
    - Then
        - The treasurer's name is visible in the page.
        - The banner image is visible in the background.
        - Take screenshots wherever required via the script itself (no manual screenshots).

Run the script and verify if the test succeeds.


3) Look at the documentation for Test Cafe online. Can you complete the command in package.json named "run-all-tests"? See if you can get this command working: ```npm run run-all-tests```.


4) Navigate to this URL- 'https://uat.oktaxrolls.com/searchTaxRoll/Garfield'. 
This page would give details about different tax payments for 'Garfield' county.
Write down all the scenarios that you think can be tested on this particular page. We're considering this as pure manual testing question and hence you can make use of an excel sheet to write down the test cases. Make sure you're using proper test case writing format (for eg : test steps, expected results etc)


All the very best !! This is your chance to show off your automation skills , so be creative !!
