# Basic Websit State Transition Testing
Allowing users to sign-up, log in and log out.

## State transition table and test case

| Initial State   | Event          | Next State                    |
|-----------------|----------------|-------------------------------|
| Log in page     | Log in         | User is logged into the site |
| Log in page     | Log in         | Incorrect login details, users back to the login page       |
| Log in page     | Log in         | User hasn't signed up yet, sign up page    |
| User is logged into the site | Log out | Log out page                  |
| Sign up page    | Sign up        | Success, user is logged into the site |

Covering all states test:
| Events | States               |
|--------|----------------------|
| start  | Login page           |
| Log in | User doesn't have an account yet |
| Sign up| Success, user is logged into the site |
| Log out| Log out page         |


## State transition diagram



<img src="https://github.com/yulingyou/QE_Week5_Extending-Testing_Unit1_Challenge/issues/1#issue-2231490915">