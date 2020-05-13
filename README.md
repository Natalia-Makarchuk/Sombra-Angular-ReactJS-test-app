# Angular / ReactJs test app

## App description
You're a blog owner.

## _As user:_
1. You can see your blog Home page, with a list of articles.
2. Each article should include title, short description and creation date.
3. There shoul be presented button for open article details page. This page need to include full description, images, creation date.
4. New users can subscribe to the blog: on the home page should be a button "Subscribe", on click - appear modal window with subscription form, where the user can enter email, first name, last name.

## _As admin:_
1. You need to login as administrator. 
2. Admin panel should include:
- Home page (list of all articles with search by title and description, ability to delete article). From the home page redirect to the article details page.
- Article details page: show full article info with edit.
- Create an article page (form for creating a new article). After creation, a new article should appear in the list.
- Users page (table list of your subscribers). With filter (by banned/active) and search (by email, name), pagination, sorting. With an action button to ban or activate user.
3. Logout.

P.S.
Use angular reactive form (with input fields, textarea, drop-downs, validation and error messages).
Show tooltips on errors and success (for ex., form saved successfully, element edited or deleted successfully or no).

_Optional:_
CI/CD process

## Requirements Angular
- Use router guards.
- Implement routing with lazy loading.
- Get current router state (get router params).
- Use different types of Angular Directives, optional: implement custom directive.
- Use Pipes, optional: create custom pipe.
- Use reactive form.
- Add form fields validation.
- Implement communication between components (parent-child, siblings).
- Create common components.
- Use RxJs (subscribe, unsubscribe,  Subject, optional: try different ways to unsubscribe, BehaviourSubject, different RxJs operators).
- Use Angular Material for styling.
- Use HttpClient for fetch requests (you could use some json generator or some real time db).
- Don't forget to create interfaces, 'any' type is unacceptable.
- Optional: Unit-testing.


## Requirements ReactJs
- Use class components.
- Use functional components.
- Use functional component hooks.
- Use component state.
- Use redux state.
- Use redux form.
- Use react router (i.e. get params from route).
- Use typescrtipt.
- Use axios for fetch requests (you could use some json generator or some real time db).
- Prevent component render without data.
- Don't forget to create interfaces, 'any' type is unacceptable.
- Use styling library (for ex., antd, bootstrap).
- Optional: Use middlewares.
- Optional: Unit-testing.


### Useful links Angular
https://angular.io/guide/styleguide
https://github.com/sudheerj/angular-interview-questions#write-a-pictorial-diagram-of-angular-architecture

### Useful links ReactJs
https://medium.com/@konstankino/2019-reactjs-best-practices-design-patterns-516e1c3ca06a
https://towardsdatascience.com/react-best-practices-804def6d5215
https://xsltdev.ru/react/


