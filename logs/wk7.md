I hadn't thought much about forms before, but once we went through the elements -- `<form>`, `<label>`, `<input>`, `<textarea>`, `<select>`, `<button>` -- I realized they're everywhere. The part that stuck most was the `type` attribute on inputs. Just by writing `type="email"`, the browser handles format validation for free. Same with `type="password"` hiding characters, or `type="date"` giving you a date picker. That's a lot of built-in behavior I would have otherwise tried to replicate with JavaScript.

The accessibility point was also important: always pair `<label>` with `for` and
the input's `id`. 

Really cool to find out submitting a form with `method="GET"` literally puts the values in the URL -- including the password field. Switching to POST hides that. What surprised me more was seeing how much information a POST request sends to the server beyond just the form inputs: IP address, browser, OS. That felt like a good reminder that the web is not as private as it looks.

### What I built
I built `contact.html` with name, email, subject, and message fields, styled with Flexbox. I also split the CSS into a separate `contact.css` external stylesheet, which felt cleaner and more realistic as a workflow. I also added form for the mini project.

Media queries make sense conceptually -- you define breakpoints where the layout shifts. But the bigger insight was that a lot of responsive behavior is already built into Flexbox and Grid if you use `flex-wrap` or `auto-fit`. You can get a lot done without writing a single media query.

The key takeaway for this course is that I don't need to write Tailwind from
scratch -- I need to be able to read it, identify what it's doing, and modify it
confidently. That feels like a realistic bar.

---

## Questions / Things to Follow Up On
When would you actually choose vanilla CSS over Tailwind for a new project?
I get that Tailwind is AI-friendly but it feels like it trades one kind ofcomplexity for another (lots of classes in the HTML instead of rules in a stylesheet).
## Quiz 2 Prep

Covering: selectors, box model, display types, Flexbox and Grid, CSS variables, transitions, forms, responsive design basics. Same format as Quiz 1 -- paper, closed book, 30 minutes. Going to review the selector specificity rules and the form element attributes since those feel most quiz-prone.