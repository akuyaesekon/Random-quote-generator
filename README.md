# Random-quote-generator
1.Set up a React project using create-react-app or your preferred method.
2.Create a wrapper element with the id of "quote-box" in your App component.
3.Within the "quote-box" element, create a div with an id of "text" to display the quote text, and another div with an id of "author" to display the author's name.
4.Create a button element with an id of "new-quote" to fetch a new quote and display it on the page. You can use an API like https://type.fit/api/quotes to fetch the quotes.
5.Create an anchor element with an id of "tweet-quote" that opens a Twitter intent to tweet the current quote. Use the href attribute with the "https://twitter.com/intent/tweet" URL and add the quote text and author's name as parameters to the URL using template literals.
6.Add a state to your App component to store the current quote and author.
7.Use the useEffect hook to fetch a new quote from the API when the component mounts and store it in the state.
8.Add an onClick event listener to the "new-quote" button that fetches a new quote and updates the state with the new quote and author.
9.Use conditional rendering to display the quote text and author on the page.
10.Use CSS to center the "quote-box" wrapper element horizontally.
11.Test your app and make sure it meets all the user stories mentioned in the project description.
12.Deploy your app to a hosting service like Netlify or GitHub Pages.
