React Virtual Keyboard
=====================

Currently WiP:

A on-screen keyboard (OSK) Component that works in the browser for reactJS. Useful for Kiosk Touchscreens.

Based on the Virtual Keyboard using jQuery:
https://mottie.github.io/Keyboard/

* [Mottie Keyboard](https://mottie.github.io/Keyboard/)

### Usage

#### Import Keyboard
```
import Keyboard from 'Keyboard';
```

#### Use Keyboard Element
`
<Keyboard value={ this.state.textarea } options={{type:'textarea', layout:'qwerty', autoAccept: true, alwaysOpen: false, appendLocally: true, color:'light', class:'sxcycx'}} callbackParent={this.onTextareaChanged} />
`
You can use the following Options: https://github.com/Mottie/Keyboard/wiki/Options


#### Return updated values
```
onTextareaChanged(newState) {
        this.setState({ textarea: newState });
    }
```

### Dependencies

* React
* Webpack
* jQuery
* [Mottie Keyboard](https://mottie.github.io/Keyboard/)
