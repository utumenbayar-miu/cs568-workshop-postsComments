# CS568 - Posts and Comments Workshop - HOC, Forms, Router, Axios, React Context
Backend API:

Fake blog and comments API on https://jsonplaceholder.typicode.com/guide/.
*	List all posts - GET - https://jsonplaceholder.typicode.com/posts/
*	Store a post - POST - https://jsonplaceholder.typicode.com/posts/
*	Get a post by id - GET - https://jsonplaceholder.typicode.com/posts/1/
*	Edit a post - PUT - https://jsonplaceholder.typicode.com/posts/1/
*	Delete a post - DELETE - https://jsonplaceholder.typicode.com/posts/1/
*	Get comments for a post - GET - https://jsonplaceholder.typicode.com/posts/1/comments  

Requirements:
*	Create a HOC (withPosts) that gets all posts from the backend API. 
*	Create routes below:
    * /posts – Lists all posts. Delete, detail, edit buttons are here
    * /posts/1 – Show specific post details. When clicking on the comment, it should navigate to /posts/1/comments and render the comments in the <Outlet>. 
    * /posts/add – Add a post
    *	/posts/1/edit – Edit a post
*	Composition – List Items in the ```<p>``` or ```<li>``` tag. PostItem component simply renders children and the parent Posts component sends the content between tags dynamically.
*	Store user preference in React context. Based on the preference, list posts in the ```<p>``` or ```<li>``` tag. Just read the user preference from context. No provider is necessary, only the consumer.
*	There must be no warning or errors in the log or terminal.
