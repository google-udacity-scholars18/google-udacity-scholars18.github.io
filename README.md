# Google Developer Scholarship Projects

> Showcase of student project built for 2017-2018 Google Developer Scholarship

We built this website to show some of the final projects built by the students of 2018 Google Scholarship by Udacity.

## How to add your project?

To add your final project to the website, create a new entry in the file which corresponds to your track:

|Track|File|
|-|-|
|ABND|[`_data/abnd.yml`](_data/abnd.yml)|
|AND|[`_data/and.yml`](_data/and.yml)|
|FEND|[`_data/fend.yml`](_data/fend.yml)|
|MWS|[`_data/mws.yml`](_data/mws.yml)|

You can edit this file on github by clicking on 🖋 icon and submitting submitting your changes via PR. 

#### Entry format

- **`name`** *(required)* The name of your App/Website
- **`banner`**  *(required)* Link to banner image uploaded to [imgur.com](https://imgur.com/)
- **`links`** *(required)* Links to the website/play store/github repo.
	- **`title`** Link title, this would usually be the website name, e.g. `Play Store` or `Github`
	- **`icon`** Icon descriptor from the list of [supported icons](#supported-icons)
	- **`url`** Link URL
- **`description`** *(required)* Short description of your project
- **`author`** *(required)* Your full name
- `author_location` *(optional)* City and Country of your residence
- `author_avatar` *(optional)* Link to your photo or avatar uploaded to [imgur.com](https://imgur.com/)
- `author_links` *(optional)* Add links to your social-media accounts, e.g. Github, Twitter, Facebook
  - **`title`** The link title, e.g. the name of the website
  - **`icon`** Icon descriptor from the list of [supported icons](#supported-icons)
  - **`url`** Link URL

#### Supported Icons

You may use following icons in your **`links`** and `author_links`:

|`icon`||
|-|-|
|`playstore`|<img src="/assets/Google_play_icon.png" width="16" height="16" /> Play Store Link|
|`fdroid`|<img src="/assets/fdroid-logo.png" width="16" height="16"/> F-Droid Link|
|`web`|<img src="/assets/Network_icon.png" width="16" height="16"/> Website Link|
|`medium`|Medium Profile Icon|
|`dribbble`|Dribbble Profile Icon|
|`facebook`|Facebook Profile Icon|
|`github`|Github Profile Icon|
|`instagram`|Instagram Profile Icon|
|`linkedin`|LinkedIn Profile Icon|
|`pinterest`|Pinterest Profile Icon|
|`mastodon`|Mastodon Profile Icon|
|`twitter`|Twitter Profile Icon|
|`youtube`|Youtube Profile Icon|
|`googleplus`|G+ Profile Icon|

## Contribute

If you'd like to contribute to the codebase, proceed to [CONTRIBUTING.md](CONTRIBUTING.md). Contributions are welcome!

