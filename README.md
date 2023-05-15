# Google-colab-prevent-disconnect
## Running long sessions on Google Colab without any activity can cause the session to disconnect, losing all the data and variables from the earlier executed cells. This can be prevented by entering the following code into the browser console (opened by pressing Ctrl + Shift + I).

### function ClickConnect() {
###    console.log("Working");
###    document.querySelector("colab-toolbar-button").click();
### }
### setInterval(ClickConnect, 60000);



Source: [How to prevent Google Colab from disconnecting ?](https://medium.com/@shivamrawat_756/how-to-prevent-google-colab-from-disconnecting-717b88a128c0)
