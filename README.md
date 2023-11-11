<h1 align="center">Netflix-Recommendation-System</h1>
<p><font size="3">
A web-app which can be used to get recommendations for a series/movie, the app recommends a list of media according to list of entered choices of movies/series in your preferred language using <strong>Python</strong> and <strong>Flask</strong> for backend and <strong>HTML</strong>, <strong>CSS</strong> and <strong>JavaScript</strong> for frontend.
</p>

 # This web-app contains 3 main pages:
- [Home Page](#home-page)
- [Recommendation Page](#recommendation-page)
- [Movie Detail Page](#movie-detail-page)
- [Netflix Page](#netflix-page)

## Home Page
The user may select a list of their favorite movies and TV shows, as well as their chosen language, on this page. For example, I submitted a list with two horror movies (Insidious and Insidious Chapter 2), an action series (Supergirl), and a drama series (Suits) as my selections, and English and Hindi as my chosen languages.
Clicking on the Get Started button the user will see the list of recommendations.
![](/app/static/screenshots/Screenshot-HomePage.png)

## Recommendation Page
The user will see poster pictures for all of the recommended movies and shows, organized by IMDb score.
![](/app/static/screenshots/Screenshot-RecommendationPage1.png)
![](/app/static/screenshots/Screenshot-RecommendationPage2.png)

Clicking on any poster image, the user will be sent to the Movie Details page for the corresponding title.

## Movie Detail Page
Here are the full information of the user-selected title, such as the genre, movie summary, languages in which the film is accessible, IMDb scores, directors, writers, and actors, and so on. The user will also find a link to the related title's Netflix page at the bottom of the page. 
![](/app/static/screenshots/Screenshot-MovieDetailPage1.png)
![](/app/static/screenshots/Screenshot-MovieDetailPage2.png)

## Netflix Page
This page is not part of my web-app, but it is an example of what the user will see if they click on the Netflix Link for the title.
You may use your Netflix account and view the movie or series of your choice from our suggestions.
![](/app/static/screenshots/Screenshot-NetflixPage.png)

# How To Use

To be able to use this web app locally in a development environment you will need the following:

1) You will need [Git](https://git-scm.com) installed on your computer.

2) Then From your terminal, you should do the following:

```cmd
# Clone this repository
git clone https://github.com/Darshan1412/Netflix-Recommendation-System-ML-Project.git

# Go into the repository
cd netflix-recommendation-system

# Install requirements (if you already haven't)
pip install -r requirements.txt

```
3) To run this application you don't need to have any special configuration but make sure you don't change the directory of the project otherwise you can recieve errors while you try to run the app.

4) You can run the Netflix React App using the following command from your terminal:

```
# Run the app
>>set FLASK_APP=app.py
>>flask run
```

# TeamMates

👤 **Darshan Jain**
- Github: https://github.com/Darshan1412
- Linkedin: https://www.linkedin.com/in/Darshan-Jain1/
- Email: darshanjain768@gmail.com

👤 **Cryus Coutinho**
- Github: https://github.com/CyrusCoutinho
- Linkedin: https://www.linkedin.com/in/cyrus-coutinho-4b406b20a/
- Email: cyruscoutinho77@gmail.com

👤 **Elston Farel**
- Github: https://github.com/ElstonFarel
- Linkedin: https://www.linkedin.com/in/elston-farel-019a821a7/
- Email: elstonfarel@gmail.com

👤 **Seona Dabre**
- Github: 
- Linkedin: https://www.linkedin.com/in/seona-dabre-3b0666248/
- Email: dabreseona18@gmail.com



# Show Your Support 

Give a ⭐️ if you like this project!
