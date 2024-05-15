# AI-demo
Integrating OpenAI API into a JavaScript-based web app

Relies on OpenWeather map API to get weather information to that location

got to https://home.openweathermap.org/api_keys to access your API key

# Get Started
configure codespace devcontainer to use portforwarding for vite

`
"portsAttributes" : {
   "5173": {
     "label": "Vite port" ,
     "onAutoForward": "openPreview"
  }
},
  "forwardPorts": [5173]
  `

install vite

`npm install vite@latest`

-javascript + SWC

under package.json >> scripts change "vite" to "vite --host" to specificcally use host env provides

Run env

`npm run dev`
