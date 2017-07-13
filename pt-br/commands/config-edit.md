# config:edit
Edite a configuração selecionada.

**commands.generate.doc.gitbook.messages.usage:**
```
$ drupal config:edit [arguments]
$ ced  
$ cdit  
```

## commands.generate.doc.gitbook.messages.arguments
commands.generate.doc.gitbook.messages.argument | commands.generate.doc.gitbook.messages.details
---------|-------------
config-name | Nome da configuração.
editor | Editor.

## commands.generate.doc.gitbook.messages.examples
* Edit system cron configurations with "vim" (default editor).
```
$ drupal config:edit system.cron
```
* Edit system cron configurations with "gedit".
```
$ drupal config:edit system.cron gedit
```