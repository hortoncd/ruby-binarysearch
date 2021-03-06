[![CircleCI](https://circleci.com/gh/hortoncd/ruby-binarysearch.svg?style=svg)](https://circleci.com/gh/hortoncd/ruby-binarysearch)

Description
===========

Ruby implementations of the binary search algorithm that assumes the array is already sorted. One version monkey patches the Array class, and the other implements a new class that works with an array to avoid monkey patching.

Testing
=======

Tests with rspec.

```
bundle install --path ./vendor
bundle exec rspec
```

License and Author
==================

- Author:: Chris Horton (<hortoncd@gmail.com>)
- Copyright:: 2016, Chris Horton

Licensed under the Apache License, Version 2.0 (the "License");
you may not use this file except in compliance with the License.
You may obtain a copy of the License at

    http://www.apache.org/licenses/LICENSE-2.0

Unless required by applicable law or agreed to in writing, software
distributed under the License is distributed on an "AS IS" BASIS,
WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
See the License for the specific language governing permissions and
limitations under the License.
