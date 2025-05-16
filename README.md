# Students of Photonics - unitn

[stuphos.physics.unitn.it](stuphos.physics.unitn.it)

Base theme: [PaperMod](https://github.com/adityatelange/hugo-PaperMod/)

Changes:
- Changes colors: [css](assets/css/extended/override_themes.css)
- Custom Homepage: [home](layouts/_default/home.html)
    - Include link to Social 
    - Filter events such that we display only the ones in future or the last one
- Custom List to include Cover [list](layouts/_default/home.html)
    - check [about](content/about/_index.md) on how to include GDrive images
- Hack to link social for each event and author: [social](layouts/partials/post_canonical.html)
- Use TOML instead of YAML
