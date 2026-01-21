# Hello there, check out my projects

## Warcraft Group Logs (https://warcraftgrouplogs.onrender.com/)
Website and addon combination for World of Warcraft. Created to easily fetch all players in your group with the addon, created with LUA. This addon generates a link to my website, with all necessary data.

The website, created using ReactJS (working on converting to TypeScript), reads the parameter from the url and fetches every single players data from the API exposed by Warcraftlogs.com, using GraphQL.
I have setup a redis cahce, that after fetching the data from the API, i temporary save it here, to reduce on API calls which are limited. 



### Technologies used:

Addon (https://github.com/Adamhviid/WarcraftGroupLogs_addon):
- LUA

Frontend (https://github.com/Adamhviid/WarcraftGroupLogs):
- ReactJS (With some TypeScript)

Backend (https://github.com/Adamhviid/WarcraftGroupLogs_backend):
- Python, with FlaskAPI
- Redis
- GraphQL queries

Hosted on render.com

<!--
**Adamhviid/Adamhviid** is a ✨ _special_ ✨ repository because its `README.md` (this file) appears on your GitHub profile.

Here are some ideas to get you started:

- 🔭 I’m currently working on ...
- 🌱 I’m currently learning ...
- 👯 I’m looking to collaborate on ...
- 🤔 I’m looking for help with ...
- 💬 Ask me about ...
- 📫 How to reach me: ...
- 😄 Pronouns: ...
- ⚡ Fun fact: ...
-->
