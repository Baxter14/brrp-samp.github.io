
<style>
        .navbar {
            border-radius: 30px;
            display: flex;
            justify-content: space-between;
            align-items: center;
            background-color: black;
            padding: 10px;
            height: 60px;
        }
        .navbar a {
            text-decoration: none;
            color: grey;
            display: inline-block;
            margin-right: 20px;
            font-weight: bold;
        }
        .navbar img {
            width: 50px; /* Adjust the width as needed */
            height: auto; /* Maintain aspect ratio */
        }
        h1 {
            text-align: center;
            color: black;
        }
        body {
            background-image: url("img/Background.png");
        }
        .button {
            display: flex;
            align-items: center;
            background-color: transparent;
            border: none;
        }
        .button img {
            width: 25px;
            height: auto;
            margin-right: 10px;
        }
        .button span {
            color: black;
        }
        .button.tiktok span {
            color: white;
            font-weight: bold;
        }
        .button.discord span {
            color: white;
            font-weight: bold;
        }
        .discordbutton {
            font-weight: bold;
            border: none;
            text-decoration-thickness: 5px;
            display: block;
            margin: auto;
            width: 200px; /* Adjust the width as needed */
            height: 35px; /* Adjust the height as needed */
            background-color: #7289d9;
            color: white;
        }
        .tiktokbutton {
            font-weight: bold;
            border: none;
            text-decoration-thickness: 5px;
            display: block;
            margin: auto;
            width: 200px; /* Adjust the width as needed */
            height: 35px; /* Adjust the height as needed */
            background-color: grey;
            color: white;
        }
        .gridbuttons {
            font-weight: bold;
            border: none;
            text-decoration-thickness: 5px;
            display: block;
            margin: auto;
            width: 200px; /* Adjust the width as needed */
            height: 35px; /* Adjust the height as needed */
            background-color: blue;
            color: white;
        }
        .navbar img.rp-logo {
            width: 50px;
            height: auto;
        }
        .right-buttons {
            display: flex;
            align-items: center;
        }
        .servertitle p {
            display: block;
            margin: 65%;
            width: 300px;
            height: 35px;
            color: white;
            font-size: large;
            font-family: Impact, Haettenschweiler, 'Arial Narrow Bold', sans-serif;
        }
        .button.discord {
        display: flex; /* Add this line */
        align-items: center; /* Add this line */
    }

    .button.tiktok {
        display: flex; /* Add this line */
        align-items: center; /* Add this line */
    }
</style>




<div class="navbar">
        <img src="img/Rplogo.png" alt="RP Logo" class="rp-logo">
        <div class="servertitle">
            <p>Blue Ridge Roleplay</p>
        </div>
        <div class="right-buttons">
            <a href="https://www.tiktok.com/@officalblueridgeroleplay" class="button tiktok">
                <button class="tiktokbutton">
                    <img src="img/Tiktok.png" alt="Tiktok Logo">
                    <span>Check us out on Tiktok</span>
                </button>
            </a>
            <a href="https://discord.gg/EyNkNp9R8z" class="button discord">
                <button class="discordbutton">
                    <img src="img/Discord.png" alt="Discord Logo">
                    <span>Join us on Discord</span>
                </button>
            </a>
        </div>
    </div>