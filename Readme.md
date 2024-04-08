# Basic Websit State Transition Testing
Allowing users to sign-up, log in and log out.

## State transition table and test case

| Initial State   | Event          | Next State                    |
|-----------------|----------------|-------------------------------|
| Log in page     | Log in         | User is logged into the site |
| Log in page     | Incorrect login details   | login page       |
| Log in page     | User hasn't signed up yet | sign up page    |
| User is logged into the site | Log out | Log out page                  |
| Sign up page    | Sign up        | User is logged into the site |

Covering all states test:
| Events | States               |
|--------|----------------------|
| start  | Login page           |
| Log in | User doesn't have an account yet |
| Sign up| Success, user is logged into the site |
| Log out| Log out page         |
| Log in | Incorrect login details  |
| Log in | User is logged into the site |


## State transition diagram



![Week5_Unit1_Extending Testing](https://github.com/yulingyou/QE_Week5_Extending-Testing_Unit1_Challenge/assets/100756965/cc2d931f-898f-4582-9168-be1605e5476d)