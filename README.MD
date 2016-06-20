# Kata Template
The [Agile Katas](http://agilekatas.co.uk/) template for new katas.

## Description
This is a template used by Agile Katas when starting new katas. The template includes a gradle wrapper for building code and running tests. Also included are a variety of testing libraries for unit and integration tests.

## How to use
Download the project- either as a zip, using `git clone`, or whatever or method you fancy. If you're going to be writing integration tests, open up the `build.gradle` file and edit the integration test task to have the correct glue code location. It's currently set to `uk.co.agilekatas.katas`, so change it to wherever your step definitions are.

## Examples
Agile Katas has a number of katas built on this template, you can find a full list of them on the [Agile Katas Repositories Page](https://github.com/AgileKatas?tab=repositories), or you can look at any of the repositories below:

- [Agile Katas Tamagotchi Kata](https://github.com/AgileKatas/TamagotchiKata-Java)
- [Agile Katas Rock Paper Scissors Kata](https://github.com/AgileKatas/RockPaperScissorsKata-Java)

## Included libraries

| Library        | Version |
|----------------|---------|
| JUnit          | 4.12    |
| AssertJ        | 3.4.1   |
| Cucumber-Java  | 1.2.4   |
| Cucumber-JUnit | 1.2.4   |
