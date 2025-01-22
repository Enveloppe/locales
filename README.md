# Locales

This repository contains all locale for translating Obsidian GitHub Publisher.

## Directive
### Adding a new language
- Copy the `en.json`
- Name it with the name of the locale in the format : `locale.json`
- Translate it
- Save the file
- Create a PR.

> [!warning]
> For new language, an update of the plugin is needed. This will be done in the next interation of the plugin, as a hook was set to automatically add it. 

### Update a translation
- Open the file you want to edit
- Translate the fields
- Save
- Create a PR

 > [!warning]
 > Do not translate token between `{{}}`, as `{{- repo.owner}}`

You can test the translation in the main plugin using the directive of developping here.

> [!NOTE]
> English is not the main language of @Mara-Li and some string can be inaccurate in english. If you need, you can use the french translation as a reference. If you notice some spelling mistake, the correction is also welcome!
