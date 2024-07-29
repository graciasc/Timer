# Timer
> This is a Progressive webapp that will track a fast / slow timer for people trying to track there pace.

## Todos:
- Goal Working Prototype in 24 Hours 
-  Groomed Design / Implementation in 1 Week
# App 
- two inputs : minutes / seconds 
- label ( fast / slow )
- container / maybe the fullscreen / black / white
- start button
- sound / web audio / announce the label
- Use web service worker to allow for sound broadcasting when phone is locked. 

## Web Server Worker API - offline access (pwa)
**details coming soon**

## Web Speech API example

```js
// Function to read text from the webpage
function readPageText() {
    // Get all text content from the body of the webpage
    const text = document.body.innerText;
    
    // Create a new SpeechSynthesisUtterance instance
    const utterance = new SpeechSynthesisUtterance(text);
    
    // Speak the text
    speechSynthesis.speak(utterance);
}

// Run the function to read the page text
readPageText();
```
