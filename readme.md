# Cobra HTML Toolkit
The Cobra HTML Toolkit is a component that is used within burpsuite for HTML rendering.

I created this project to allow any burpsuite plugin to tap into that
functionality. And updated the project in order to function with Java 1.7+

## Usage
Add the following in your `build.gradle` to include this toolkit.
```
repositories {
  maven { url 'https://jetpack.io' }
}

dependencies {
  compileOnly 'com.github.vdbaan:CobraHTMLToolkit:0.98.5'
}
```
