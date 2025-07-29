Features I want:
 - Have a reactive page
 - Have it tell me what the weather is for the day
 - Have it tell me what time it is
 - Have it tell me any other information I want, configurable using a config
 - Make it so that I can enter in my daily weigh in ever morning
 - Notifying me when I forget to do my weigh in (via email, telegram or any other means)
 - Make a device or use an old device mounted to an arm or directly on my desk


Pages:
  1) index.html
    - The 'dashboard' page.
    - Will contain New
  2) weighin.html
    - Is the page that will be redirected to or iframed at a specific time set in a config file.
    - This is the page that will send a notification.
    - Redirects back to the index when a weight has been inputted.
    - Will save the weight into a database by sending an api request to a local server (maybe could be reworked so a local server doesn't have to be used?)