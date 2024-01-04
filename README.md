# [TERMINAL | Website](https://manasraj-terminal.vercel.app/)


![Vercel](https://img.shields.io/badge/vercel-%23000000.svg?style=for-the-badge&logo=vercel&logoColor=white)
![Vite](https://img.shields.io/badge/vite-%23646CFF.svg?style=for-the-badge&logo=vite&logoColor=white)
![TypeScript](https://img.shields.io/badge/typescript-%23007ACC.svg?style=for-the-badge&logo=typescript&logoColor=white)
![HTML5](https://img.shields.io/badge/html5-%23E34F26.svg?style=for-the-badge&logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/css3-%231572B6.svg?style=for-the-badge&logo=css3&logoColor=white)

Create your own terminal Check out [manasraj-termial](https://manasraj-terminal.vercel.app/) for an example.

## Features
* **[Tab]** for auto completion.
* **[Esc]** to clear the input line.
* **[↑][↓]** to scroll through your command history.


## Configuration

You can Configure your details in config.json file.

```json
{
  "title": "Manas's Terminal",
  "username": "visitor",
  "hostname": "asimov",
  "social": {
    "email": "dev.manas@protonmail.com",
    "github": "root-Manas",
    "linkedin": "manasraj-singh"
  },
  "aboutGreeting": "Hello Mate.",
  "projects": [
    [
      "Project Name",
      "Project Description",
      "Project Link"
    ],
    [
      "Another Project Name",
      "Another Project Description",
      "Another Project Link"
    ]
  ],
  "colors": {

  }
}
```

## Run the Project Locally:

Clone the repository
```shell
git clone https://github.com/root-Manas/Terminal-portfolio
```
Go to the project directory
```shell
cd Terminal-portfolio
```
Install the dependencies
```shell
npm install #This installs package.json dependencies
```
```
Start the server
```shell
npm run dev 
```
#This starts the vite server but locally. When in production use npm run build on Vercel or Netlify