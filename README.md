[![Star on GitHub](https://img.shields.io/github/stars/kauemurakami/app_version_update.svg?style=flat&logo=github&colorB=deeppink&label=stars)](https://github.com/omarnasser199789/app_version_update_lite)

Favorite Button is a flutter library that allows you to create heart and star shaped favorite featured buttons with animation effects too.

## [Omar Nasser](https://github.com/omarnasser199789)
<img src="https://avatars.githubusercontent.com/u/22509641?s=96&v=4" alt="Omar Nasser" width="50" height="50" style="border-radius: 50%;">

[![GitHub](https://img.shields.io/badge/GitHub-gray)](https://github.com/omarnasser199789)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-blue)](https://www.linkedin.com/in/omar-mouhamad-nasser/)
[![Portfolio](https://img.shields.io/badge/Portfolio-orange)](https://omar-nasser-portfolio.web.app/#/)



##  How to use it.

the default effects is Icons.favorite
```dart
  FavoriteButton(
            valueChanged: (_) {
            },
          ),
```

and you can also define custom effects.
```dart
 FavoriteButton(
            valueChanged: (_isFavorite) {
              print('Is Favorite $_isFavorite)');
            },
          )
```


## parameters

| parameter                  | description                                                     | default                                                                                                                                                                               |
| -------------------------- |-----------------------------------------------------------------| ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| icon                       | Icon                                                            | 60.0                                                                                                                                                                                  |
| iconSize                       | size of button widget                                           | 60.0                                                                                                                                                                                  |
| iconColor          | color of button widget                                          | red for heart and yellow for star button respectively                                                                                                                                                    |
| valueChanged                | Function that returns boolean value for current state of button | This is a required parameter                                                                                                                                                                            |
| isFavorite or isStarred                | Default state of button                                         | This is a optional parameter                                                                                                                                                                            |
                                                                                                                                                               |

