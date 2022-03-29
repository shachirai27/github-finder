Using create-react-app, tailwind css and daisy ui plugin to make a github finder project that uses the github API.
**Tailwind Docs**: https://tailwindcss.com/docs/guides/create-react-app
**DaisyUI Docs**: https://daisyui.com/
**Github APIs Docs**: https://docs.github.com/en/rest/overview/resources-in-the-rest-api
Github Users API: https://api.github.com/users/<username or not>
Github Search API: https://api.github.com/search/users?q=<whatever you wanna search>
process.env.REACT_APP_GITHUB_TOKEN: used this variable to increase the X-RateLimit-Limit for requests per minute. It increases from 10 without token to 30 with it. This token will expire soon that's why adding it in a public repository. Please replace with your own token.
