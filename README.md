# DPO Standalone Wordpress

## Page Setup

Create three pages, one each for checkout, payment success and payment failure.

For example, name them
- DPO Standalone Demo 
- DPO Standalone Success 
- DPO Standalone Failure

and note the URL slug for each, which will be used in configuring return URLs.

Add the short code [dpo_standalone_payment_checkout] to the checkout page, which will display the checkout form.

Add the short code [dpo_standalone_payment_success] to the success page.

Add the short code [dpo_standalone_payment_failure] to the failure page.


## Configuration
Configuration is by means of the **DPO Standalone Plugin** menu item on the Admin Menu Bar.

The options are:
- `Company Token` - this is account number given to you by DPO e.g 9F416C11-127B-4DE2-AC7F-D5710E4C5E0A
- `Service Type` - this is the service type given by DPO e.g 3854
- `Success URL` - the URL slug of the success page
- `Failure URL` - the URL of the failure page
- `Test Mode` - check this to use the sandbox (test) account, where no real transactions are processed.

- Logo Options - check to enable which logos will be displayed on the checkout page 

