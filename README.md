## A CHAT GPT BASED QUESTION SETTER FOR TEACHERS
Made By- Deepankar Varma

## QuickStart       

1. Clone this repository.
2. Add your OpenAI API key to .env file (sign up at https://beta.openai.com for account / key)
3. Install node_modules by running `npm install` or `yarn install` in terminal
4. In `pages/api/openai.js` you construct your request to OpenAI API
5. In `pages/index.js` you tweak your UI/UX
6. Start the dev server with `yarn dev` or `npm run dev` command
7. Run `setx` command in cmd for setting the API Key in the environment variables
8. Incase you get browser outdated error, run `npm install browserslist`
9. For any other major errors try removing the node modues , package.json and run the `npm install` again.


## For help related to API connection visit [OpenAI](https://help.openai.com/en/articles/5112595-best-practices-for-api-key-safety)



## How to use

Simply paste a paragraph in the first textarea and then enter the number of MCQ questions you need in the second textarea.Finally use the Frame Questions button to generate questions. The maximum questions generated at a time is 10 (Limitation from CHAT GPT). 


## Working Screenshot

<img src="https://miro.medium.com/v2/resize:fit:1100/0*-U316Ioh1PHQ42xC"></img>


## Tips

If you don't have a setup on your computer that allow to run code locally, then use https://replit.com/

