# Amazon Page Clone
 
 <!-- TABLE OF CONTENTS -->
<details open="open">
  <summary>Summary</summary>
  <ol>
    <li>
      <a href="#about-the-project">About the Project</a>
      <ul>
        <li><a href="#build-with">Build With</a></li>
        <li><a href="#visual">Visual</a></li>
      </ul>
    </li>
    <li>
      <a href="#how-to-use">How to use</a>
      <ul>
        <li><a href="#prerequisites">Prerequisites</a></li>
        <li><a href="#installation">Installation</a></li>
      </ul>
    </li>
    <li><a href="#license">License</a></li>
  </ol>
</details>

<!-- ABOUT THE PROJECT -->
## About the project

The project aims to recreate the visual interface of the Amazon web page, specifically the book sales session, using the resources of the utility-first CSS framework Tailwind version 3. This application was developed together with Matheus Batisti's course - Tailwind CSS do básico ao avançado.

<!-- BUILD WITH -->
### Build With
The technologies used in this project were:
* [TailwindCSS](https://tailwindcss.com)
* [CSS](https://developer.mozilla.org/en-US/docs/Web/CSS)
* [HTML5](https://developer.mozilla.org/en-US/docs/Web/HTML)


<!-- VISUAL -->
### Visual

<div align="center">
 <img src="https://user-images.githubusercontent.com/43687521/222936487-750bf67c-c230-41ea-b3a2-56807607b214.png">
</div>
<div align="center">
 <img src="https://user-images.githubusercontent.com/43687521/222936853-574f9f88-6358-4480-ad1e-1ef08f5209c6.png">
</div>

Original web-site [here](https://www.amazon.com.br/Livros/b/?ie=UTF8&node=6740748011&ref_=nav_cs_books) (It may have changed a bit over time)

<!-- HOW TO USE -->
## How to Use

### Prerequisites

``` git and npm ```

### Installation

1- Clone this repository.
``` 
git clone https://github.com/felype-carvalho/amazon-page-clone.git
```

2- Access the */src* folder inside the project directory by your terminal/cmd.
``` 
cd amazon-page-clone/src/
```

3- Open *index.html* fil. If you are using VSCode, you can use the Live Server extension to run an application on localhost:5500.

4- (Optional) You can make changes to the project using the Tailwind CLI build process. In the root folder of the project, enter the command to run the build.
``` 
npx tailwindcss -i tailwind.css -o src/css/styles.css --watch
```

 
<!-- LICENSE -->
## License

Distributed under the MIT license. See `LICENSE` for more information.
