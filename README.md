<!--
*** Thanks for checking out the Best-README-Template. If you have a suggestion
*** that would make this better, please fork the repo and create a pull request
*** or simply open an issue with the tag "enhancement".
*** Thanks again! Now go create something AMAZING! :D
***
***
***
*** To avoid retyping too much info. Do a search and replace for the following:
*** github_username, repo_name, twitter_handle, email, project_title, project_description
-->



<!-- PROJECT SHIELDS -->
<!--
*** I'm using markdown "reference style" links for readability.
*** Reference links are enclosed in brackets [ ] instead of parentheses ( ).
*** See the bottom of this document for the declaration of the reference variables
*** for contributors-url, forks-url, etc. This is an optional, concise syntax you may use.
*** https://www.markdownguide.org/basic-syntax/#reference-style-links
-->



<!-- PROJECT LOGO -->
<br />
<p align="center">

  <h3 align="center">URL SHORTENER</h3>

  <p align="center">
    <br />
    <a href="https://github.com/zkeshtkar/url"><strong>Explore the docs »</strong></a>
    <br />
    <br />
    <a href="https://github.com/zkeshtkar/url">View Demo</a>
    ·
    <a href="https://github.com/zkeshtkar/url/issues">Report Bug</a>
    ·
    <a href="https://github.com/zkeshtkar/url/issues">Request Feature</a>
  </p>




<!-- TABLE OF CONTENTS -->
<details open="open">
  <summary><h2 style="display: inline-block">Table of Contents</h2></summary>
  <ol>
    <li>
      <a href="#About The Project">About The Project</a>
    </li>
    <li>
      <a href="#getting-started">Getting Started</a>
    </li>
    <li><a href="#usage">Usage</a></li>
    <li><a href="#roadmap">Roadmap</a></li>
    <li><a href="#contributing">Contributing</a></li>
    <li><a href="#license">License</a></li>
    <li><a href="#contact">Contact</a></li>
  </ol>
</details>



<!-- ABOUT THE PROJECT -->
## About The Project
`Url Shortener` is URL shortening service and a link management platform


### Built With

* [Zahra Keshtkar](https://github.com/zkeshtkar)


<!-- GETTING STARTED -->
### Creating Database

this comments are useful for creating dataBase in your project :
```
   dotnet tool install --global dotnet-ef
   
   dotnet ef migrations add Booking.AppDbContext
   
   dotnet ef database update
```

### Run

You can write this comments in your terminal for runnig your project :

```
   dotnet run
```
 so you can see your project in this address: https://localhost:5001  or   http://localhost:5000
 
### Run Tests
  When you want to run tests,you should use this comments in your terminal :
  
  ```
   cd yourprojectname/tests
   
   dotnet test
  ```
 
### Usage

1. If you want to make short your url , you can use this comment :
```
    curl -X POST -H "Content-Type: application/json" -d '{"LongUrl": "your url","ShortUrl":""}' http://localhost:5000/urls
  
```
2. And if you want to redirec to the url by short url ,use this comment :
```
   curl -i http://localhost:5000/Your Route name/shortUrl
 
```



<!-- CONTRIBUTING -->
## Contributing

Contributions are what make the open source community such an amazing place to be learn, inspire, and create. Any contributions you make are **greatly appreciated**.

1. Fork the Project
2. Create your Feature Branch (`git checkout -b feature/AmazingFeature`)
3. Commit your Changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the Branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request



<!-- LICENSE -->
## License

Distributed under the MIT License. See `LICENSE` for more information.



<!-- CONTACT -->
## Contact

Zahra Keshtkar - [zkeshtkarz@gmail.com](zkeshtkarz@gmail.com)

Project Link: [https://github.com/zkeshtkar/url](https://github.com/zkeshtkar/url)







<!-- MARKDOWN LINKS & IMAGES -->
<!-- https://www.markdownguide.org/basic-syntax/#reference-style-links -->
[contributors-shield]: https://img.shields.io/github/contributors/github_username/repo.svg?style=for-the-badge
[contributors-url]: https://github.com/github_username/repo/graphs/contributors
[forks-shield]: https://img.shields.io/github/forks/github_username/repo.svg?style=for-the-badge
[forks-url]: https://github.com/github_username/repo/network/members
[stars-shield]: https://img.shields.io/github/stars/github_username/repo.svg?style=for-the-badge
[stars-url]: https://github.com/github_username/repo/stargazers
[issues-shield]: https://img.shields.io/github/issues/github_username/repo.svg?style=for-the-badge
[issues-url]: https://github.com/github_username/repo/issues
[license-shield]: https://img.shields.io/github/license/github_username/repo.svg?style=for-the-badge
[license-url]: https://github.com/github_username/repo/blob/master/LICENSE.txt
[linkedin-shield]: https://img.shields.io/badge/-LinkedIn-black.svg?style=for-the-badge&logo=linkedin&colorB=555
[linkedin-url]: https://linkedin.com/in/github_username
