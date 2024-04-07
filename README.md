# Bot-Css-






/* This CSS rule sets the default font size of the entire document */
html {
  font-size: 16px;
}

/* These CSS rules sets the text direction of the paragraph (RTL or LTR) */
p,
.bpw-from-bot > div,
#input-message {
  direction: ltr;
}

/* This rule changes the color of the text in the input message */
#input-message {
  color: #000000;
}

/* Changes the color of the new message indicator */
.bpw-new-messages-indicator {
  background-color: #f5f5f5;
  color: #ffffff;
}

.bpw-header-container {
  margin: 10px;
  background: linear-gradient(45deg, #600000, black, #0b111e, #0b111e, black, #600000); /* Adjust the angle and colors as needed */
  border-radius: 10px;
  position: relative;
  overflow: hidden;
  border: 1px;
  border-radius: 10px;
  color: #ffffff;
}

.bpw-header-name{
  color: #ffffff;
}

/* Styling for the typing bubble */
.bpw-typing-bubble {
  background: #000000;
}

/* Styling for the chat bubble content */
.bpw-chat-bubble-content {
  background-color: #f5f5f5;
  border-radius: 3px;
  border: 1px transparent;
}

/* Styling for the date container, header name, and header subtitle */
.bpw-date-container,
.bpw-header-name,
.bpw-header-subtitle {
  color: #ffffff;
}

/* Styling for the layout of the chat bubble. Width, height, border, position and radius of the chat bubble */
.bpw-layout {
  width: 360px !important;
  height: 60vh;
  border-radius: 10px;
  right: 50px;
  bottom: 5px;
  border: 2px;
}
/* Responsive design rules for devices with width less than or equal to 767px */
@media screen and (max-device-width: 767px) {
  .bpw-layout {
    width: 80% !important;
    height: 60%;
    right: 11%;
    bottom: 200px;
    border-radius: 2;
  }
}


/* Changes the fill color of the header icons to white */
.bpw-header-icon,
.bpw-header-icon svg,
.bpw-header-icon svg path {
  fill: #ffffff !important;
}

/* Changes the color of the placeholder text in the input message */
#input-message::placeholder {
  color: rgba(0,0,0,.30);
}

.bpw-composer textarea{
  outline: none !important;
  border: 1px solid rgba(0,0,0,.15);
}
.bpw-composer textarea:focus{
  outline: none !important;
  border: 1px solid rgba(0,0,0,.30);
}

/* Styling for the keyboard single choice option */
.bpw-keyboard-single-choice {
  background-color: #ffffff;
  border: none;
}

/* Styling for the buttons in the chat interface */
.bpw-button,
.bpw-button-alt {
  background-color: #dcdcdc;
  color: #000000;
  border-radius: 10px;
  border: none;
}


/* Styling for hover effect on the buttons in the chat interface */
.bpw-button:hover,
.bpw-button-alt:hover {
  background-color: #f5f5f5;
}


/* Styling for hyperlinks in the chat interface */
a {
  color: #ffffff;
  text-decoration: underline;
}

/* Styling for the chat container, including color, scrollbar width and color, and border */
.bpw-chat-container {
  background: linear-gradient(45deg, black, #0b111e, #0b111e, black, #600000); /* Adjust colors and direction as needed */
  scrollbar-width: thin;
  scrollbar-color: #f5f5f5 #0b111e;
  border: none;
}


/* Styling for the chat bubble content when it's from the bot */
.bpw-from-bot .bpw-chat-bubble .bpw-chat-bubble-content {
  background-color: #f5f5f5;
  color: #000000;
}

.bpw-from-user .bpw-chat-bubble .bpw-chat-bubble-content {
  background: linear-gradient(45deg, #600000, black, #0b111e, #0b111e, black, #600000); /* Adjust the angle and colors as needed */
  color: #ffffff;
}

/* Styling for the composer section of the chat interface */
.bpw-composer {
  background: linear-gradient(0deg, #600000, #f2f3f4, #f2f3f4, #f2f3f4, #0b111e);
  border-top: none;
}


/* Styling for the scrollbar in the chat container */
.bpw-chat-container::-webkit-scrollbar,
.bpw-chat-container::-moz-scrollbar {
  width: 10px;
  background-color: #ffffff;
  border: none;
}

/* Styling for the avatar of the bot */
.bpw-bot-avatar img,
.bpw-bot-avatar svg {
  background: #000000;
  border: 3px solid #ffffff;
}

/* Styling for the general scrollbar in the web page */
::-webkit-scrollbar {
  width: 0.5rem;
}

/* Styling for the track of the general scrollbar and the chat container scrollbar */
::-webkit-scrollbar-track,
.bpw-chat-container::-webkit-scrollbar-track,
.bpw-chat-container::-moz-scrollbar-track {
  background-color: transparent;
}

/* Styling for the thumb of the general scrollbar and the chat container scrollbar */
::-webkit-scrollbar-thumb,
.bpw-chat-container::-webkit-scrollbar-thumb,
.bpw-chat-container::-moz-scrollbar-thumb {
  background-color: #ffffff;
  border-radius: 1rem;
  border: 0.5rem solid transparent;
}

.bpw-floating-button i svg path {
  fill: linear-gradient(135deg, #600000, black, #0b111e, #0b111e, black, #600000); /* Adjust the angle and colors as needed */
}



/* Styling for the 'powered by' section of the chat interface */
.bpw-powered {
  text-align: center;
  padding: 10px;
  color: #000000;
  background: #ffffff;
  font-size: 14px;
  border-bottom-right-radius: 10px;
  border-bottom-left-radius: 10px;
}

/* Styling for the hyperlinks in the 'powered by' section of the chat interface */
.bpw-powered a {
  color: #000000;
  text-decoration: underline;
}

/* Styling for hover effect on the hyperlinks in the 'powered by' section of the chat interface */
.bpw-powered a:hover {
  text-decoration: underline;
}

.bpw-send-button{
  background: #6675fa;
}


/* Change Bot Widget Icon */

.bpw-widget-btn{
  border-radius: 50%;
  background:#600000;
}


.bpw-floating-button {
    position: fixed;
    bottom: 20px;
    right: 20px;
    width: 50px;
    height: 50px;
    border-radius: 50%;
    background-color: #0a0c10;
    box-shadow: 0 2px 5px rgba(0, 0, 0, 0.2);
    cursor: pointer;
    z-index: 9999;
}

.bpw-floating-button::before {
    content: "";
    background: url("https://www.livehelp100.com/wp-content/uploads/2021/11/solution-security.png");
    background-repeat: no-repeat;
    background-position: center;
    background-size: contain;
    height: 30px; /* Adjust as needed */
    width: 30px; /* Adjust as needed */
    position: absolute;
    top: 50%;
    left: 50%;
    transform: translate(-50%, -50%);
}

/* Hover effect */
.bpw-floating-button:hover {
    background-color: #0056b3;
}



.bpw-floating-button {
  box-shadow: none !important;
}


// .bpw-floating-button > i {
// display: none;
// }
