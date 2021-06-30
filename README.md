# Install

`npm install`

---

# Things to add

- Create a config folder with a `.env` file and add the following as `key = value`
  - PORT = 2121 (can be any port example: 3000)
  - CLOUD_NAME = `your cloudinary cloud name`
  - CLOUD_API_KEY = `your cloudinary api key`
  - CLOUD_API_SECRET = `your cloudinary api secret`
  - MS_COMPUTER_VISION_SUBSCRIPTION_KEY = `your Microsoft Subscription Key`
  - MS_COMPUTER_VISION_ENDPOINT = `your Microsoft Computer Vision Endpoint`
  - MS_FACE_ENDPOINT = `your Microsoft Face Endpoint`
  - MS_FACE_SUB_KEY = `your Microsoft Face Key`

---

# Run

`npm start`

# extra things I had to do to make it work from the template..
      - change the 'name' from package.json to '<one-word>' it was formatted "how are you doing" and was giving errors/red lines so maybe it doesnt like the spaces.
      - npm i axios 
      - npm i nodemon
      - delete everything in app.js that doesnt have to do w finding brands
      - configure the ejs to display what you want to the user
    