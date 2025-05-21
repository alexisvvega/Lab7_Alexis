Alexis Vega
1) **Where would you fit your automated tests in your Recipe project development pipeline? Select one of the following and explain why.**

- [X] Within a Github action that runs whenever code is pushed 
- [ ] Manually run them locally before pushing code
- [ ] Run them all after all development is completed

The reason is because it ensures that any new code is automatically tested before being merged and helps catch any bugs early on.

2) Would you use an end to end test to check if a function is returning the correct output? (yes/no)

I would not because end-to-end tests are meant to simulate user workflows and test the full application behavior, not individual function outputs.

3) What is the difference between navigation and snapshot mode?

Navigation mode tests page load performance whereas Snapshot mode captures a static view to check for content/accessibility issues.

4) Name three things we could do to improve the CSE 110 shop site based on the Lighthouse results.

  - Serve images in next-gen formats
      - Reduces image size and improves performance.
  - Minify and reduce unused JavaScript
      - Speeds up load times and reduces main thread work.
  - Add a <meta name="viewport"> tag
      - Improves mobile layout and responsiveness.


