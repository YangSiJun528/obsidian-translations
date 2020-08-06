# Translate Obsidian

Help translate Obsidian into your language.

### Request a language

If the language you want to translate doesn't exist as a JSON file yet, submit an issue so that we can create a template for you to get started.

### Submit changes

To translate, [fork this repo](https://guides.github.com/activities/forking/) and edit the JSON file of your language. After that, [submit a pull request](https://guides.github.com/activities/forking/).

Note that you don't have to clone your fork to make the edits; you can do everything on GitHub's web UI. Simply open a file in your own forked repo and click on the pencil icon to start editing.

### Translating

The trasnlation JSON file consists of key value pairs. The key should give you a good idea of where the text is in the app.

To translate, simply edit the value. For example, let's say you see

```json
"plugin": "Plugin"
```

Simply change it to:

```json
"plugin": "pLU9IN"
```

where "pLU9IN" is the phrase "plugin" in the target language. I'm using leetspeak as an example here.

If you encounter something like

```json
"label-welcome": "Welcome, {{name}}!"
```
leave the `{{name}}` part alone and do not translate it. "name" is not part of the text and will be replaced by the appropriate value when the app runs.