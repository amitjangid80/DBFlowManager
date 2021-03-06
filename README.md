# DBFlowManager

[ ![Download](https://api.bintray.com/packages/wajahatkarim3/DBFlowManager/com.wajahatkarim3.DBFlowManager/images/download.svg?version=3.1.1) ](https://bintray.com/wajahatkarim3/DBFlowManager/com.wajahatkarim3.DBFlowManager/3.1.1/link) [![Android Arsenal](https://img.shields.io/badge/Android%20Arsenal-DBFlowManager-brightgreen.svg?style=flat)](https://android-arsenal.com/details/1/4956) [![API](https://img.shields.io/badge/API-15%2B-blue.svg?style=flat)](https://android-arsenal.com/api?level=15)

A quick and easy database manager and viewer plugin library for your DBFlow databases to view, insert, delete, update the tables directly inside your app.
## Inspiration & Description
Databases are the crucial part in mobile apps these days. And in android, SQLite is the go-to solution for integrating databases. Recently, [RaizLabs DBFlow][dflib] has been proven to be quite easy and fast ORM for SQLite databases. But, to test SQLite databases in app, I was using [DatabaseManager][dmlib], but it wasn't compatible with DBFlow. So, I created this [DBFlowManager][dbmlib] for this purpose.
In short, 
```
DBFlow + DatabaseManager = DBFlowManager
```
Using this library, you can easily view, insert, delete, update the tables of your app's DBFlow database directly from your app by using just a single line of code.

## Features
  - View all your tables data in tabular format
  - Insert rows to your tables
  - Update rows
  - Delete rows
  - Delete tables
  - Drop tables
  - Write your own custom queries and view the results. (Create statements, joins, etc)
  - Change data in the tables and see how you application responds

# Demo

Install [Demo][demk] from [Releases][rels] in your device and click on DBFlow Manager Activity button!

# Screenshots
![N|Solid](https://github.com/wajahatkarim3/DBFlowManager/blob/master/Art/screens.png)
  
# Installation

Add it to your project's root build.gradle with:

```groovy
allprojects {
    repositories {
        jcenter()
        maven { url "https://jitpack.io" }
    }
}
```
and then in your app's build.gradle file:
```groovy
dependencies {
  compile 'com.wajahatkarim3.DBFlowManager:DBFlowManager:3.1.1-v1'
}
```

Or add DBFlowManager as a new dependency inside your pom.xml

```xml
<dependency> 
  <groupId>com.wajahatkarim3.DBFlowManager</groupId>
  <artifactId>DBFlowManager</artifactId> 
  <version>3.1.1-v1</version> 
  <type>pom</type> 
</dependency>
```

# How to Use
To start DBFlowManager activity from your activity or fragment:
```java
DBFlowManagerActivity.launchDatabaseManager(context, MyAppDatabase.class);
```
# Libs used in DBFlowManager Library
- DBFlow ([https://github.com/Raizlabs/DBFlow][dflib])
- DatabaseManager ([https://github.com/sanathp/DatabaseManager_For_Android][dmlib])

Donations
=============

This project needs you! If you would like to support this project's further development, the creator of this project or the continuous maintenance of this project, feel free to donate. Your donation is highly appreciated (and I love food, coffee and beer). Thank you!

**PayPal**

* **[Donate $5](https://www.paypal.me/WajahatKarim/5)**: Thank's for creating this project, here's a tea (or some juice) for you!
* **[Donate $10](https://www.paypal.me/WajahatKarim/10)**: Wow, I am stunned. Let me take you to the movies!
* **[Donate $15](https://www.paypal.me/WajahatKarim/15)**: I really appreciate your work, let's grab some lunch!
* **[Donate $25](https://www.paypal.me/WajahatKarim/25)**: That's some awesome stuff you did right there, dinner is on me!
* **[Donate $50](https://www.paypal.me/WajahatKarim/50)**: I really really want to support this project, great job!
* **[Donate $100](https://www.paypal.me/WajahatKarim/100)**: You are the man! This project saved me hours (if not days) of struggle and hard work, simply awesome!
* **[Donate $2799](https://www.paypal.me/WajahatKarim/2799)**: Go buddy, buy Macbook Pro for yourself!
Of course, you can also choose what you want to donate, all donations are awesome!

# Developed By
```
Wajahat Karim
```
- Website (http://wajahatkarim.com)
- Twitter (http://twitter.com/wajahatkarim)
- Medium (http://www.medium.com/@wajahatkarim3)
- LinkedIn (http://www.linkedin.com/in/wajahatkarim)

# How to Contribute
1. Fork it
2. Create your feature branch (git checkout -b my-new-feature)
3. Commit your changes (git commit -am 'Add some feature')
4. Push to the branch (git push origin my-new-feature)
5. Create new Pull Request

# License

    Copyright 2016 Wajahat Karim

    Licensed under the Apache License, Version 2.0 (the "License");
    you may not use this file except in compliance with the License.
    You may obtain a copy of the License at

       http://www.apache.org/licenses/LICENSE-2.0

    Unless required by applicable law or agreed to in writing, software
    distributed under the License is distributed on an "AS IS" BASIS,
    WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
    See the License for the specific language governing permissions and
    limitations under the License.


[dflib]: <https://github.com/Raizlabs/DBFlow>
[dmlib]: <https://github.com/sanathp/DatabaseManager_For_Android>
[dbmlib]: <https://github.com/wajahatkarim3/DBFlowManager>
[demk]: <https://github.com/wajahatkarim3/DBFlowManager/releases/download/3.1.1-v1/Demo_3.1.1-v1.apk>
[rels]: <https://github.com/wajahatkarim3/DBFlowManager/releases>
[eml]: <mailto:wajahatkarim3@gmail.com>
