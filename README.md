## Getting Started
---

#### 0. Prerequisite
1. XAMPP for linux
#### 1. What
Open source CMS. There are 2 types of wordpress:
1. wordpress.org
Adv: plugins, full customization abilities
Disadv: Self-hosted, manual update & backup
2. wordpress.com (free version)
Adv: Free hosting, automatically update & backup
Dis: limited plugins/themes and storage space (3GB), restriction on customization

#### 2. Set-up
1. Start XAMPP
2. Go to localhost/phpmyadmin
3. create mysql database
4. Download Wordpress.org, extract to opt/lamp/htdocs
5. Rename wordpress folder
6. Set username password & login

Modify    : http://localhost/wordpress/wp-admin/
View site : http://localhost/wordpress/
## Introduction
---
#### 1. Menu
- Media: asset
- Post: article
- Page
- Comments: approve / disapproved / delete comment
- Appearance
  - Theme
  - Customize: edit and preview
  - Widget
  - Menu
  - Background
  - Theme Editor
- Plugin
- User
- Tools > export import
- Settings > thumbnail size, permalink (url structure), privacy
#### 2. Page & Post
Pages are use for static content, whereas posts are for more timely content that is regularly updated. Post are better when grouped with category

#### 3. Customize

#### 4. Widget and Menu
#### 5. Plugin
If there is connection error problem in plugin, open wp-config and this line after define('DB_COLLATE', ..)
```
define('FS_METHOD', 'direct');

```
#### 6. Theme


## Resource
1. Video [Intro to wordpress](https://class.buildwithangga.com/course_playing/wordpressorg-website-development/1)
2. Install on [Linux](https://www.cloudways.com/blog/install-wordpress-on-linux/)