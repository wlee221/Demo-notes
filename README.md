# Demo-notes
#### app.js
```js
<AmplifyChatbot
  botTitle="Chatbot Lex"
  botName="BookTrip_dev"
  welcomeMessage="Hello, how can I help you?"
  voiceEnabled={true}
>
  <div slot="header" className="header-slot">
    <img src={logo} height="40px" />
    Amplify Bot
  </div>
</AmplifyChatbot>
```
#### app.css
```css
:root {
  --amplify-primary-color: #febcc8;
}

amplify-chatbot {
  margin-top: 20px;
  --width: 450px;
  --height: 600px;
  --header-color: rgb(40, 40, 40);
  --bot-background-color: #eaebff;
  --bot-text-color: rgb(40, 40, 40);
  --user-background-color: #febcc8;
}

.header-slot {
  padding: 1.25rem 0.375rem 1.25rem 0.375rem;
  text-align: center;
  font-size: 1.6rem;
}

img {
  height: 30px;
}

```
