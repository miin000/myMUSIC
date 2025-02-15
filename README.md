# YourMUSIC
<img src="https://github.com/miin000/YourMUSIC/blob/main/images/introview.png">
<h1>About me</h1>
<ul>
    <a href = 'https://github.com/miin000' ><li>PHẠM QUANG MINH - 23010489</li></a>
</ul>
<h1>About my project</h1>
<p>This is a music website that provides users with a flexible and convenient platform to listen to music and create personal playlists.
Users can register an account, create a personal profile, and customize their playlists according to their preferences. The website also supports sharing and updating information about favorite songs, helping users connect with the music-loving community.</p>
<p>Detailed project documentation is <a href='https://docs.google.com/document/d/1qB0hNLCN4cUHvEM798GSxUkMZhVVwMd_MrQn3euLO0I/edit?tab=t.0'>here</a></p>

<h2>Main functions include:</h2>
<ul>
    <li>account management</li>
     <li>Manage personal page</li>
     <li>Manage songs</li>
     <li>Manage playlists</li>
</ul>

<h2>Use Case</h2>
<div align='center'>
    <img src='https://github.com/miin000/YourMUSIC/blob/main/images/usecase.png'>
</div>

<h1 align='center'>How to deploy - Local Development</h1>
Clone the Repository:

    git clone https://github.com/miin000/YourMUSIC.git
    cd myMusicApp
    
Install Dependencies:

    composer install
    npm install
    
Set Up Environment Variables:


    cp .env.example .env
    php artisan key:generate
    
Configure Database Settings:

Edit the .env file to match your local database settings.

Run Migrations and Seed the Database:


    php artisan migrate --seed
    
Start the Local Development Server:

    php artisan serve
    
Visit the Application:

Open your browser and navigate to http://localhost:8000

<h3>Our product: <a href='https://studious-engine-jjqpggrv69v434vg.github.dev/'>Link website</a></h3>
<h1 align='center'>Some picture about our website</h1>
<h2>Login, register</h2>
<div align='center'>
    <img src='https://github.com/miin000/YourMUSIC/blob/main/images/loginAndRegister.png'>
    <img src='https://github.com/miin000/YourMUSIC/blob/main/images/login.png'>
    <img src='https://github.com/miin000/YourMUSIC/blob/main/images/register.png'>
</div>

<h2>Home page</h2>
<div align='center' >
    <img src='https://github.com/miin000/YourMUSIC/blob/main/images/home.png'>
</div>
<hr>
<h2>Songs view</h2>
<div align='center' >
    <img src='https://github.com/miin000/YourMUSIC/blob/main/images/songs.png'>
    <img src='https://github.com/miin000/YourMUSIC/blob/main/images/playSong.png'>
</div>
<hr>
<h2>Library</h2>
<div align='center' >
    <img src='https://github.com/miin000/YourMUSIC/blob/main/images/library.png'>
    <img src='https://github.com/miin000/YourMUSIC/blob/main/images/playlist.png'>
</div>
<hr>
<h2>Profile</h2>
<div align='center' >
    <img src='https://github.com/miin000/YourMUSIC/blob/main/images/profile.png'>
</div>
