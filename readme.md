## BASTA! Spring 2017 Keynote

### Introduction

At [BASTA! Spring 2017](https://basta.net/) I participated in the keynote together with my friends [Roman Schacherl](https://twitter.com/rschacherl) and [Manfred Steyer](https://twitter.com/manfredsteyer?lang=de). The overall topic of the keynote was **change**. How did our jobs change in the last years? How do we deal with the speed of change in software development? Manfred talked about his move from ASP.NET to Angular. Roman's focus were new UI paradigms. I was invited of my transition to SaaS, Cloud, Microservices, etc.

I thought that if I would be the "boring" server guy ;-) surrounded by fancy UIs, I wanted to go all in. I decided to put PowerPoint aside and build my slides with [KittikJS](https://github.com/kittikjs). *KiT* means *Keynote in Terminal*. So the library allows you to you create ASCII presentations in a terminal. Awesome, isn't it?

This docker image contains my keynote slide deck implemented with KittikJS (CLI), [YAML](https://de.wikipedia.org/wiki/YAML), Node.js, and Docker.

### Quickstart

#### Step 1

Pull the latest image:

```
docker pull rstropek/basta-spring-2017-keynote
```

#### Step 2

Run the presentation:

```
docker run -it --rm rstropek/basta-spring-2017-keynote
```
