# Summary.md:
-For the Expand part, I went into `cardTemplate.html` and swapped out the hardcoded colors for CSS variables. I added a `:host` block with stuff like `--card-bg`, `--card-border`, and `--title-color` so it’s easier to update styles later without digging through everything.
-I didn’t touch the HTML or layout — it still works exactly the same as the original lab. This just makes the styles more flexible and a bit cleaner to manage.
