# Technical Test - Software Engineer - Angular

## General Description

Create a simple TAX calculator using the [Angular](https://angular.io/) SPA framework

For reference, Gross Amount is calculated as follows:

`[Net Amount] * (1 + ([TaxRate] / 100)`

- Use Bootstrap in your views to make it responsive.
- Use async await as you see fit.
- We use [Jasmine](http://jasmine.github.io), MSTest and [Moq](http://code.google.com/p/moq) at Applicita, references have been added using [NuGet](http://nuget.codeplex.com/) Packages. Everything is in place for you to just write the code (no "File > New Project" required).
- Please DO NOT fork this project on Github, as we want to be sure candidates' test submissions are original.

## Task requirements

- All stories to be completed with an appropriate level of testing.
- No actual database implementation is required, feel free to stub it out.
- Your code should trend towards being SOLID.
- Please download the [code](https://github.com/Applicita/Test-Software-Engineer-Angular), complete the tasks as you see fit.
- Send us a Dropbox/Skydrive/whatever link to your zipped code to info@applicita.com or attach a zip file directly to the email.
- Please don't spend too long on this test; 120 minutes at most.

## Extra Credit

- Secure the API Endpoint(s)
- Add Telemetry / Logging

## Task Stories

Please complete each story in order.

---

### Task 1 - Input Net Amount

1. Allow user to input Net Amount of Tax.
2. Display Gross Amount of Tax.
3. Write test(s) to prove the code works properly.

#### Acceptance criteria

- Standard Rate of Tax is 20%.
- User should be able to type in Net Amount.

---

### Task 2 - Store Tax Rate

1. Allow user to store tax rate.
2. Change code from Task 1 to retrieve stored tax rate.
3. Write test(s) to prove the code works properly.

#### Acceptance criteria

- Current Tax Rate is retrieved from data store.
- Gross amount is calculated based on the current amount in the data store.

---

### Task 3 - Correctly display Gross Amount

1. Display Gross Amount to 2 decimal places.
2. Write test(s) to prove the code works properly.

#### Acceptance criteria

- Gross amount correctly rounded to 2 decimal places (1.316 should round to 1.32).

---

### Task 4 - Store and Select Multiple Tax Rates

1. Allow user to store multiple tax rates as a *Description* and *Value*.
2. Allow user to select description when entering Net Amount.
3. Use selected tax rate to calculate Gross Amount.
4. Write test(s) to prove the code works properly.

#### Acceptance criteria

- 20% tax for "Computer Games".
- 5% tax for "Children's Clothing".
- No tax for everything else.

---

This test was inspired by the JustGiving Recruitment Test which you can find [here](https://github.com/JustGiving/Recruitment-Test), big shout out goes out to them.

Thanks for your time, looking forward to seeing your answers.