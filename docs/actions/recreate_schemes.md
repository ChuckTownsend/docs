<!--
This file is auto-generated and will be re-generated every time the docs are updated.
To modify it, go to its source at https://github.com/fastlane/fastlane/blob/master/fastlane/lib/fastlane/actions/recreate_schemes.rb
-->

# recreate_schemes


Recreate not shared Xcode project schemes







recreate_schemes ||
---|---
Supported platforms | ios, mac
Author | @jerolimov



## 1 Example

```ruby
recreate_schemes(project: "./path/to/MyApp.xcodeproj")
```





## Parameters

Key | Description | Default
----|-------------|--------
  `project` | The Xcode project | 

<em id="parameters-legend-dynamic">* = default value is dependent on the user's system</em>


<hr />

## Documentation

To show the documentation in your terminal, run
```no-highlight
fastlane action recreate_schemes
```

<hr />

## CLI

It is recommended to add the above action into your `Fastfile`, however sometimes you might want to run one-offs. To do so, you can run the following command from your terminal

```no-highlight
fastlane run recreate_schemes
```

To pass parameters, make use of the `:` symbol, for example

```no-highlight
fastlane run recreate_schemes parameter1:"value1" parameter2:"value2"
```

It's important to note that the CLI supports primative types like integers, floats, booleans, and strings. Arrays can be passed as a comma delimited string (e.g. `param:"1,2,3"`). Hashes are not currently supported.

It is recommended to add all _fastlane_ actions you use to your `Fastfile`.

<hr />

## Source code

This action, just like the rest of _fastlane_, is fully open source, <a href="https://github.com/fastlane/fastlane/blob/master/fastlane/lib/fastlane/actions/recreate_schemes.rb" target="_blank">view the source code on GitHub</a>

<hr />

<a href="/actions/"><b>Back to actions</b></a>
