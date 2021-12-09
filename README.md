This POC of a CRDT (Conflict-Free Replicated Data Type) has been done by following a tutorial from the next site: https://medium.com/blocksurvey/tutorial-how-to-build-a-real-time-collaborative-app-using-crdt-in-angular-44098525d5b

Technology used:

- `YJS` NPM module as CRDT framework
- `TypeScript` as back-end language
- `Angular` as front-end framework
- `y-websocket` NPM module for
- `codemirror` NPM module as `YJS` predefined binding for real-time collaboration text editor.

Once cloned, please run the next commands in the root of the project:
`npm install yjs y-websocket codemirror y-codemirror`
`npm install -D @types/codemirror`

Then run the next command to start the application in localhost on a random unused port. Run this once per user on different terminals:
`ng serve --port`

![GitHub Logo](/images/crdt.png)