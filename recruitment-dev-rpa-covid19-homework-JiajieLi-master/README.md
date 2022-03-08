# Homework: UiPath COVID-19 Data Scraping

Please read and follow the task requirements below. You have 7 days to finish this homework.

## Tasks

Implement an attended process which performs the following steps:

1. Fetch the latest COVID-19 data including:
   - Daily new cases in China
   - Total cases and deaths for each province in China
2. Create a new Excel file based on the provided template `Raw Data.xlsx`.
3. Fill the `Daily New Cases` and `Total Cases by Province` sheets with the data from step 1.
4. Create another Excel file based on the provided template `Monthly Report.xlsx`.
5. Calculates monthly new cases based on the daily data, and write the result into the `Monthly New Cases` sheet.
6. Send these two Excel files to `saiqi.jia@compass.com` with the subject `RPA Homework from <Your Name Here>`.

It's highly suggested to fetch the COVID-19 data from this [Google Search](https://www.google.com/search?q=COVID-19+new+cases+in+China) result page. But if you find it difficult to scrap from that graph chart, you can use other data sources per your needs.

When you finished your code:

1. Create a new branch based on `master` (DO NOT fork this repo).
2. Commit your code on this new branch and create a PR.
3. Tell your HR that you have finished your homework.

## Some notes to help you get higher scores

- Accurately scrap the data from this [Google Search](https://www.google.com/search?q=COVID-19+new+cases+in+China) page.
- Split the homework into smaller pieces, complete them one by one, and make small Git commits with clean commit messages.
- The code should be clean and easy to read.
- The variable and parameter names are self-explanatory.
- No typo.
- Carefully organize your code structure.
- Provide proper comments/annotations, but only when it's necessary.
- Utilize new technologies from the latest UiPath version to show your deep understanding to UiPath.
- It's not enforced to use the provided `Main.xaml`. You can delete and recreate one in case you find it not useful.
- Both VB.NET and C# are accepted.

If you have any questions, please feel free to [raise issues](../../issues) in this repo. We're glad to help you.
