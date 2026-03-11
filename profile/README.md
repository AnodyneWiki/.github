# AnodyneWiki

### Templated Frontend

Articles are generated on the fly by text/template templates from a set of data derived from an array of cheminformatics and pharmacology databases.

[/index](https://anodyne.wiki/index/substance)
[/substance/amphetamine](https://anodyne.wiki/substance/amphetamine)
![Example Article Top](example_article_top.png)
![Example Article Bottom](example_article_bottom.png)

[/substituted/tryptamine](https://anodyne.wiki/substituted/tryptamine)
![Example Substitution](example_substitution.png)

[/user/0xea](https://anodyne.wiki/user/0xea)
[/user/magnus](https://anodyne.wiki/user/magnus)
![Example User Base](example_user_base.png)
![Example User Matrix](example_user_matrix.png)
![Example User Annotations](example_user_annotations.png)

### API Backend

For further assistance gladly reach out to: [0xea](https://anodyne.wiki/user/0xea)

* Substance index: [/api/index/substance](/api/index/substance)
    * Query substance: [/api/substance/](/api/substance/amphetamine)
* Query substitution class: [/api/substituted/](/api/substituted/amphetamine)
* Pharmacological class index: [/api/class/](/api/index/class)
    * Query pharmacological class: [/api/class/](/api/class/stimulant)
* Querying routes of administration: [/api/index/administration/](/api/index/administration)
    * Querying routes of administration: [/api/administaration/](/api/administration/intravenous)
* User index: [/api/index/user/](/api/index/user)
* Querying user: [/api/user/](/api/user/0xea)

### Dependencies
- caddy (templated frontend and reverse-proxy)
- golang (backend api)
- ruby
- ruby-httparty (database scrapping)
- [molpic](https://github.com/coderobe/molpic) (our CDK based cannonicalized molecular structure generation tool)
