# Kroger Coupon Selenium Script

This is a basic Selenium IDE script designed to interact with Kroger's coupon website. The script includes a series of automated tasks such as scrolling, clicking, and executing various actions related to coupon clipping and removal. The script is divided into multiple tests to handle different operations.

## Features

- **Scrolling**: Scrolls the webpage to specified positions for easier interaction.
- **Coupon Interaction**: Clips and removes coupons from the Kroger savings page.
- **Dynamic Interaction**: Includes a loop to repeatedly clip coupons while a certain condition is met.
- **Pause**: Introduces a delay in the script for wait times between actions.
- **Echoing**: Outputs values for debugging or tracking the flow of the script.

## Components

### Test 1: `kroger`
- **Scroll**: Scrolls the page to a specified position.
- **Click 'In-Store' Coupons**: Clicks the button to filter in-store coupons.
- **Scroll Again**: Scrolls the page further to make additional elements visible.
- **Open Homepage**: Opens the Kroger homepage.
- **Execute Custom Scripts**: Runs custom scripts that return specific values (100 and 0).
- **Pause**: Pauses the script for an extended period.
- **Echo**: Outputs a computed value (`count + 1`).

### Test 2: `Kroger_Coupon_Clip`
- **Open Coupons Page**: Opens the Kroger coupons page.
- **Clip Coupons**: Clicks the 'In-Store' filter and clips coupons within a loop, which repeats until a certain count (150).
- **Loop**: Loops the process of clipping coupons based on a specified condition.

### Test 3: `Remove`
- **Open My Coupons Page**: Opens the page containing the user's clipped coupons.
- **Remove Coupons**: Clips coupons from the "My Coupons" page by clicking the 'Unclip' button, repeating the process until a condition is met.

## Usage

1. Load this script into Selenium IDE.
2. Execute the tests to automate coupon clipping or removal.
3. Modify any timeouts or conditions based on your needs.

This script serves as a simple automation tool for handling coupons on Kroger’s website and can be customized for further actions based on user preferences.

As always, Gold tier monthly sponsors receive an updated script.
