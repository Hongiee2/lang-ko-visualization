# lang-ko-visualization
: 한글 문장에 대한 감정분석과 시각화

### [Demo](https://gcp-nlp.herokuapp.com/)

--- 

### Install
`npm install`

### Key (GCP Natural Language API)
`(YOUR_PROJECT_DIRECTORY)/GCP-key.json`

### Usage
`export PORT=(PORT_NUMBER_YOU_WANT)` 

`export GOOGLE_APPLICATION_CREDENTIALS=./GCP-key.json` 

`npm run server-start` 

### Web
`http://localhost:(PORT_NUMBER_YOU_WANT)`

--- 

### Server (Node.js, Express)

#### `middleware/lang.js`
- [GCP - Cloud Natural Language API](https://cloud.google.com/natural-language/docs/quickstart-client-libraries?hl=ko)를 참고하여 작성

#### GET
- /gcp-lang?text=안녕하세요

---

### Client (VanillaJS, p5.js)
- 문장에 대해서 감정 분석 후 시각화

---


```
1.clone
1-1. install node
1-2. install git bash
1-3. open git bash
1-4. move project directory
2.key file "GCP_key.json" in root directory
3.npm install
4.export PORT="YOUR PORT"
5.export GOOGLE_APPLICATION_CREDENTIALS=./GCP-key.json
6.npm start
```
