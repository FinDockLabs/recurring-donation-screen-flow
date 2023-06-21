<a href="https://githubsfdeploy.herokuapp.com?owner=FinDockLabs&repo=https://github.com/FinDockLabs/recurring-donation-screen-flow&ref=main">
  <img alt="Deploy to Salesforce"
       src="https://raw.githubusercontent.com/afawcett/githubsfdeploy/master/deploy.png">
</a>

# Screen flow: Create NPSP Recurring Donation with FinDock BACS

A simple screen flow for use from a Contact record to create a Recurring Donation in NPSP, including the creation of a FinDock Payment Profile for storing the account details for BACS. The flow also harnesses FinDock's bank account checker to validate the account number and sort code before creation.

## Installation

Simply install and activate the flow (Screen Flow - BACS Recurring Donation). You can then include it on your Contact page layout or trigger it an Action on the Contact object. (When adding to a Page Layout, make sure to tick the checkbox to Pass the record ID into the variable recordId.)
To deploy the flow to your Salesforce environment, you can:
- use `sfdx`.
- press the "Deploy to Salesforce" button at the top of this README and then press "Login to Salesforce" in the top right of your screen.
- any other deployment method you prefer.

## Notes

This is only meant to be a starter to get you going - feel free to customise this flow to meet the needs of your nonprofit with additional fields and actions.

# Contributing

When contributing to this repository, please first discuss the change you wish to make via an issue or any other method with FinDock before making a change.

# Support

FinDock Labs is a non-supported group in FinDock that releases applications. Despite the name, assistance for any of these applications is not provided by FinDock Support because they are not officially supported features. For a list of these apps, visit the FinDock Labs account on Github. 

# License

This project is licensed under the MIT License - see the [LICENSE](/LICENSE) file for details