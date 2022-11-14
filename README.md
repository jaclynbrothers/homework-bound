# Homework Bound

This application was created for students in order to keep track of their classroom assignments and upcoming tests. The user can create, save, edit, and delete their assignment while setting an upcoming due date.

**Link to project:** http://homeworkbound.herokuapp.com/

https://user-images.githubusercontent.com/102431119/194131205-e6c79715-1c71-4c89-b53c-c8ee6d2c7c36.mp4

## How It's Made

**Tech used:** Embedded JavaScript (EJS), CSS, Node, Express, MongoDB, and deployed with Heroku.

**Additional Packages/Dependencies used:** bcrypt, dotenv, express-flash, express-session, mongoose, morgan, nodemon, passport, passport-local, and validator.

Homework Bound was a project I worked on with a team of developers to test our understanding of MVC architecture and how user logins are added. In the week that we had to develop this project, my team and I assigned tasks on GitHub Projects, which you can view here: https://github.com/users/JulienMellon/projects/1

## Required Dependencies

- `npm install`
- Create a `.env` file in the /config folder and add the following as `key: value`
  - PORT = 8000 (can be any port example: 3000)
  - DB_STRING: `your database URI` 
- Add a .gitignore file with `.env` and `node_modules`
- `npm start`

## Optimizations

- Create a weekly assignment tracker calendar view to look at current/upcoming assignments.
- Teachers will have the ability to add, edit, and delete existing assignments that are tied to a specific class while student users will only be able to mark those assignments as whether they were completed.
- Student users will make private, threaded comments under each assignment for the teacher to read when they require further clarification.
- Users will have Google authentication as another way to login.

## Lessons Learned

I learned how to incorporate consistent styling across multiple web pages, as well as the use of partials to reuse code. I greatly enjoyed collaborating with a team to brainstorm ideas, debug issues through mob and pair programming, and allocate tasks while supporting each other throughout the development process. 

## Team Members

<a href="https://github.com/JulienMellon">Julien Mellon</a>,
            <a href="https://github.com/jaclynbrothers">Jaclyn Brothers</a>,
            <a href="https://github.com/gaildev10">Gail Giles</a>,
            <a href="https://github.com/mathung">Matt Hung</a>,
            <a href="https://github.com/ztlaw">Walt Lungan</a>,
            <a href="https://github.com/phuphaju">Nischaya Khatiwada</a>, & 
            <a href="https://github.com/neffcodes">James Neff</a>.

## Other Projects

<table bordercolor="#66b2b2">
  <tr>
    <td width="33.3%"  style="align:center;" valign="top">
	<a target="_blank" href="https://github.com/jaclynbrothers/squawk-space">Squawk Space</a>
    	<br>
    	<a target="_blank" href="https://github.com/jaclynbrothers/squawk-space">
    	<img src="https://media.giphy.com/media/7dsiIBgG8OuU95SUvF/giphy.gif" width="100%"  alt="Squawk Space">
        </a>
    </td>
    <td width="33.3%" valign="top">
	<a target="_blank" href="https://github.com/jaclynbrothers/artist-portfolio">Artist Portfolio</a>
      	<br>
        <a target="_blank" href="https://github.com/jaclynbrothers/artist-portfolio">
          <img src="https://media.giphy.com/media/OtZnHQvpwaGOxKxoi1/giphy.gif" width="100%" alt="Artist Portfolio Website">
        </a>
    </td>
    <td width="33.3%" valign="top">
	<a target="_blank" href="https://github.com/jaclynbrothers/movie-recommendations-api">Movie Recommendations API</a>
        <br>
        <a target="_blank" href="https://github.com/jaclynbrothers/movie-recommendations-api">
          <img src="https://media.giphy.com/media/MkNt7t4yHfgI8bnwF9/giphy.gif" width="100%" alt="Movie Recommendations">
        </a>
    </td>
  </tr>
</table>
