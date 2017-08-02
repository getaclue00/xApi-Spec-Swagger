# xApi-Spec-Swagger
## What
This project is an attempt at the [xApi](https://www.adlnet.gov/xAPI) [Spec](https://github.com/adlnet/xAPI-Spec) implementation using [OpenAPI](https://github.com/OAI/OpenAPI-Specification) and [Swagger](https://swagger.io/). 

**This is a WIP. I'm developing this on my free time. If you notice any errata, please feel free to submit issues (with proposals) or a pull request.**

There are several implementations of the [xApi Spec](https://github.com/adlnet/xAPI-Spec) available (just do a search on github). However, the problem is that they are implemented in a specific language or framework. Since xApi is a specification, all of the projects should be similar and there shouldn't be much duplication going on. Moreover, there is currently a lack of open source LRS implementations for the various languages and frameworks. 

## Why
Through this project, I am hoping to remove this barrier.
The aim of this implementation is to save you time in generating a RESTful APi that is conformant to [xApi Spec](https://github.com/adlnet/xAPI-Spec). Thus, you can focus your resources on the LRS business logic implementation. Conveniently, [ADL LRS](https://github.com/adlnet/ADL_LRS) or [LearningLocker](https://github.com/LearningLocker/learninglocker) projects can be then used as a template to building the aforementioned business logic. I sincerely hope this will save you, both, time and money. 

## How
1) By using this implementation and [Swagger](https://swagger.io/), you will be able to quickly generate a new project and create your RESTful APi that is conformant to [xApi Spec](https://github.com/adlnet/xAPI-Spec). 
2) Then, you will be able to save some money if you need to have an internal LRS, low on funds, or just for experimentation. There will be no need to rely on external resources as long as this spec is kept up to date with [xApi Spec](https://github.com/adlnet/xAPI-Spec). 

## Note
This is meant to be complimentary to the various [current](https://adopters.adlnet.gov/) [solutions](https://experienceapi.com/adopters/). There are obvious benefits in purchasing the off-the-shelf products. However, since this is a specification... there shouldn't be much drastic change once implemented.
