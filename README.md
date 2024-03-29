# Course Assignment Javascript 2
#
This is our link to our Trello board:

https://trello.com/b/dJFo7crJ/javascript-2-courseassignment
## Goal

To apply knowledge of JavaScript techniques to implement the front end functionality for a social media application.

## API

The API you are using for this project can be found under **Social EndPoints** at the [Noroff API documentation](https://noroff-api-docs.netlify.app/).

## Brief

You have been tasked with producing a new JavaScript front end client for an existing social media platform. The client application must be attractive and responsive, but you have an otherwise blank slate in terms of theme design language.

Using the provided API and API documentation, create a functioning user interface that allows for **viewing, posting, editing and deleting** social media content.

Social API routes require authorization via JWT (JSON Web Tokens). You will need to register an account and login to access your token.

In order to complete the required features you will also need to make use of `GET`, `POST`, `PUT`, and `DELETE` HTTP methods.

Using localStorage is highly recommended, especially for storing JWT tokens.

A finished project fulfills the requirements below with an easy to use and error-free user interface.

### Required Features

The following user stories are required for a passing submission:

- User with `@noroff.no` or `@stud.noroff.no` email can register profile
- Registered user can login
- User can view a post content feed
- User can filter the post content feed
- User can search the post content feed
- User can view a post content item by ID
- User can create a post content item
- User can update a post content item
- User can delete a post content item

### Additional Features

The following user stories are optional:

- User can create a comment on a post
- User can edit profile media
- User can follow/unfollow a profile
- User can react to a post content item

### Team Work:

This assignment allows for team work in groups of 2 students. Students forming a work group will need to coordinate closely throughout the planning, development and testing processes. By working in a pair you are expected to implement additional features.

Commit regularly and use branches to prevent conflicts with your teammate as you work on the same codebase.

## Development Process:

1. Use this repository for the project.
2. Create a `js2` branch from the default `master` or `main` branch.
3. You may use either Trello or GitHub Projects to manage your development tasks. If you are using Trello please make sure that your board is public and that a link is provided in your `readme.md` file. Make sure to detail tasks accurately and divide them evenly if working a group.

Examples of overly vague tasks:

- Make the HTML for the post page
- Website Styling
- JavaScript for API
- Test the website

Examples of detailed & accurate tasks:

- Create search form HTML
- Search form SCSS styling
- Filter posts function
- Implement search event listener

4. Review the [API Guide](https://noroff-api-docs.netlify.app/social-endpoints/authentication) and [API Documentation](https://nf-api.onrender.com/docs).
5. Plan your approach, desired features and work strategy.
6. Implement the required features as per your work plan.

> All PRs should be made to `js2` not to the default branch.

> For example, branch `search-functionality` should be created from, and merged into, branch `js2`.

8. Submit a link to your repository at the correct branch on the Moodle forum for peer review.
9. Review 2 of your peers projects. (4 per team)

> [Video Resource: Branching and providing feedback](https://vimeo.com/725676411/fabede2ebb)

10. Open a Pull Request from `js2` into the default branch. Contact a teacher on Teams for their feedback. If there is a particular area of concern please ensure to pass this on with your request. Add this teacher as a reviewer on your PR. Please make sure to plan for this review prior to your deadline.
11. Implement the feedback gathered from your review, but leave the PR open.
12. Deliver the link to this PR in Moodle. A passing submission will be approved and merged by the reviewer. This is a direct analogue of the professional review process.

## Restrictions

- Required functionality must be implemented in original, pure JavaScript.
- A CSS Framework may be used to build the application UI.
- A `.gitignore` file must be provided including `node_modules`. This folder must be untracked.
- Content posted on the API is public and associated with your identity. Be appropriate and respectful.

## Resources

- [API Guide](https://noroff-api-docs.netlify.app/social-endpoints/authentication)
- [API Documentation](https://nf-api.onrender.com/docs).
