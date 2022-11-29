# tinytrack
tiny tool to track activities written in bash with fzf and basic tools like sed

## How to use
Define a list of activities, eg medication in line, eg
```
activities="androcur\nE\nantidepressants\nasthma meds"
```

This list will be then piped to fzf, after selecting one activity it's appended to the end of the list.

If you wish only to view the list you can run the app and close it with ctrl+c

## Screenshot

![Screenshot 2022-11-29 at 17 18 14](https://user-images.githubusercontent.com/4799048/204584004-47feb1d3-9912-498c-86d3-25cf93b461e1.png)
