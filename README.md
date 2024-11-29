# GIT-HUB-Demo

GIT HUB Demo is a sample project to illustrate that how we should used git in our project work.

# Table of Content

- [Introduction to Project](#introduction)
- [Requirements](#requirements)
- [Installation](#installation)
- [Configuration](#configuration)
- [FAQ](#faq)
- [How to Do?](#howtodo)
- [References](#references)

<a name='introduction'></a>

## Introduction to Project

Write about the project here.

<a name='requirements'></a>

## Requirements

This module requires the following modules:

- [Views](https://www.some.com/path/here)
- [Panels](https://www.some.com/path/here)

<a name='installation'></a>

## Installation

```sh
 $ sudo apt-get update
 $ sudo apt install openjdk-21-jdk -y
 $ sudo apt install nodejs -y
```

<a name='configuration'></a>

## Configuration

### Java Configuration

```java
package com.techhub.demo.config;

import org.springframework.context.annotation.Bean;
import org.springframework.context.annotation.Configuration;

@Configuration
public class SpringConfiguration{

    @Bean
    public String myBean(){
        return "Hello World";
    }
}
```

### JavaScript Configuration

```javascript
'use strict';

let CONFIG = {
    String myBean = "Hello World";
}
```

### Python Configuration

```python
class Config:
  def __init__(self, message):
    self.message = message

cnf = Config("Hello World")
```

### System Configuration

1. Go to Administration » Configuration » Content authoring » Text formats
   and editors
1. Edit a text format, for example "Basic HTML"
1. Enable a Glossify filter and configure it under "Filter settings"

<a name='faq'></a>

## FAQ

**Q: I want to prevent robots from indexing my custom error pages by
setting the robots meta tag in the HTML head to "noindex".**

**A:** There is no need to. **Customerror** returns the correct HTTP
status codes (403 and 404). This will prevent robots from indexing the
error pages.

**Q: I want to customize the custom error template output.**

**A:** In your theme template folder for your site, copy the template
provided by the **Customerror** module
(i.e. `templates/customerror.html.twig`) and then make your
modifications there.

**Q: I want to have a different template for my 404 and 403 pages.**

**A:** Copy `customerror.html.twig` to
`customerror--404.html.twig` and `customerror--403.html.twig`. You
do not need a `customerror.html.twig` for this to work.

<a name='howtodo'></a>

## How to Do?

Simple Text = Text

Italic text = _text_

Bold text = **text**

Strikethrough = ~~text~~

<a name='references'></a>

## References

- [ ] [TechHub]
- [x] [Drupal]
- [x] [ReadMe]
- [x] [IBM]

[TechHub]: https://www.youtube.com/@TechEduHub
[Drupal]: https://www.drupal.org/docs/develop/managing-a-drupalorg-theme-module-or-distribution-project/documenting-your-project/readmemd-template
[ReadMe]: https://github.com/othneildrew/Best-README-Template/blob/main/README.md
[IBM]: https://dataplatform.cloud.ibm.com/docs/content/wsj/analyze-data/markd-jupyter.html?context=cpdaas
