# CS-360 Reflection

The app, BalanceBuddy, is about making it easy to track weight and stay consistent with progress goals. I wanted to build something simple and useful, so the main features focus on logging weight, viewing past entries in a grid, and getting SMS reminders (if the user opts in). The UI was designed to be clean and intuitive, making sure everything was easy to navigate. I kept the layout simple, used a calming blue theme, and made sure it worked even if users denied permissions, so the app still functions without notifications.

When coding the app, I broke everything into smaller tasks, focusing on one feature at a time. I used SQLite for storing data, SharedPreferences for login, and made sure the app handled permissions properly, especially for SMS. One thing that really stood out was how important it is to test things incrementally—fixing small bugs as I built each feature instead of waiting until the end. This is definitely a strategy I’ll keep using in future projects.

To make sure everything worked smoothly, I tested the app on different Android devices and emulators, checking for bugs, UI glitches, and crashes. This testing made a huge difference, especially for things like keyboard behavior, database performance, and screen resizing issues. It showed me how even small UI tweaks can really improve the user experience.

There were definitely some challenges along the way. One of the biggest ones was handling user authentication securely while keeping it simple. Another challenge was making sure the UI worked well on all screen sizes and didn’t break when the keyboard popped up. Adding scrolling views and auto-closing the keyboard really helped.

One part of the app I’m really proud of is how well the weight tracking system works. It’s easy to use, data stays saved even after closing the app, and the UI is clear and visually appealing. This whole project gave me a solid experience in building a full mobile app, and I know I’ll be applying everything I’ve learned here to future projects.
