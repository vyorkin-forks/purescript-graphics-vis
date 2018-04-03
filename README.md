# purescript-graphics-vis

A library for interactively creating graphics visualizations in the browser using PSCi and the WebAudio and Canvas APIs.

Note: Internet Explorer and Safari are [not currently supported](https://developer.mozilla.org/en-US/docs/Web/API/MediaDevices/getUserMedia#Browser_compatibility).


## How to reproduce the issue

```bash
$ npm i
$ bower i
$ npm run repl
```

- Open `http://localhost:8080/`

You should see error in your devtools console.

- Evaluate expressions in PSCi:

    ```text
    PSCi, version 0.10.2
    Type :? for help

    Bundling Javascript...
    Serving http://localhost:8080/. Waiting for connections...

    > import Graphics.Vis.Example
    > animate scene
    ```

- Play some music and enjoy the show!

![Example](images/example.gif)
