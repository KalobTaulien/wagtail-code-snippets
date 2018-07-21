# Wagtail 2+ Code Snippets
The purpose of this repo is to link to helpful GitHub Gists for Wagtail code snippets. If you're looking for an awesome list of Wagtail Repo's, checkout [Awesome Wagtail](https://github.com/springload/awesome-wagtail)

# Code Snippets/Gists
### How to limit one page type per site
Add a `@classmethod` to your page to make sure only one page type can exist. For example, your website probably only needs one `HomePage`. [Gist here](https://gist.github.com/KalobTaulien/bbc1d88ec9d9d3f1640b4e8e05032dc7)

### Adding custom info to your templates
Adding custom context to your pages. If you need to make API requests, or pull in data from other pages, this is how you would add it to your page. A good example is a Blog Listing Page. You need to automatically pull in a QuerySet of your Blog Detail Pages. [Gist to Overwrite & Add Context](https://gist.github.com/KalobTaulien/7502cdd33ba6ff1470dfdb4542e64a9a)

### Changing the title and help text of a default Wagtail Page field
You may wish to overwrite the default Wagtail Page Title and Help Text (or any of the other fields a Page comes with). [Gist for changing default title and help_text](https://gist.github.com/KalobTaulien/fd647fabfb5210203c697dc5694d2633)

### Removing the Promote and Settings
You may wish to limit what admins can do. For instance, if you wanted to remove the Settings Panel because you don't want admins to set a publish and unpublish date, you'd want to remove that option from the admin. Set the `promote_panels` and `settings_panels` to `[]` to do this. [Gist example here](https://gist.github.com/KalobTaulien/c201e4cf33ddc609425aff8448e3ad7b)

### Adding tags to your Page
If your creating a blog or a type of website that relies on loosely connected data, such as Tags, you can add them to your page quite easily. [Gist example here](https://gist.github.com/KalobTaulien/ca225bb28e791823eea1c6332e30821b)

### Adding a Banner Mixin to your Wagtail Pages
Most websites follow a design or pattern, such as having a Banner (banner title, text and image) on several pages. No need to write this over and over, just write it as an Abstract Class. [Gist example here](https://gist.github.com/KalobTaulien/b56accf20f64f4991fe174469053c0f9)

### Adding Streamfields to a custom Wagtail Page
Streamfields are unique to Wagtail. They are entire blocks, or sections, of a page that you can rearrange. This gives the admin the ability to adjust their pages without giving them the option to edit the code or change settings. [Gist example here](https://gist.github.com/KalobTaulien/098656ee1f706634fd69743304038229)

### Creating a new Snippet
A snippet is a small piece of code you want to associate with some of your Pages, but not all of them. An example would be Blog Categories. You want to be able to add and remove them, or edit them if there's a typo. [Gist example here](https://gist.github.com/KalobTaulien/10f9cae6c7f38d2e62679b4d8e710d69)

### Adding a Blog with a Listing Page and Detail Pages
Most websites have some form of blog. In this Gist you'll find almost copy-and-paste code for adding a blog to your Wagtail wesbite. [Gist code here](https://gist.github.com/KalobTaulien/d70d0e725c5b9b9064b936c636c3acd9)