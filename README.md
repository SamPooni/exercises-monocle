#Scala Exercises - Monocle

------------------------


## Run Locally

- Clone this repository, compile and publish the project:

~~~ sh
git clone git@github.com:scala-exercises/exercises-monocle.git
cd exercises-monocle/
sbt compile publishLocal # it is important to first run the `compile` command alone
~~~

- Clone the `evaluator` and run it:

~~~ sh
git clone git@github.com:scala-exercises/evaluator.git
cd evaluator/
sbt "project evaluator-server" run
~~~

- Clone the `scala-exercises` fork:

~~~ sh
git clone git@github.com:scala-exercises/scala-exercises.git
~~~

- Follow the database setup instructions given
  [here](https://github.com/scala-exercises/scala-exercises#configure-the-database)

- Add the following line the `server/conf/application.dev.conf`:

~~~
evaluator.secretKey="secretKey"
~~~

- Run the server:

~~~ sh
sbt -mem 1500 run
~~~

This repository hosts a template content library for the [Scala Exercises](https://www.scala-exercises.org/) platform, including interactive exercises related to the [Monocle](https://github.com/julien-truffaut/Monocle) optics library for Scala (and [Scala.js](https://www.scala-js.org/)).

## About Scala exercises

"Scala Exercises" brings exercises for the Stdlib, Cats, Shapeless and many other great libraries for Scala to your browser. Offering hundreds of solvable exercises organized into several categories covering the basics of the Scala language and it's most important libraries.

Scala Exercises is available at [scala-exercises.org](https://scala-exercises.org).

## Contributing

Contributions welcome! Please join our [Gitter channel](https://gitter.im/scala-exercises/scala-exercises)
to get involved, or visit our [GitHub site](https://github.com/scala-exercises).

##License

Copyright (C) 2015-2016 47 Degrees, LLC.
Reactive, scalable software solutions.
http://47deg.com
hello@47deg.com

Licensed under the Apache License, Version 2.0 (the "License");
you may not use this file except in compliance with the License.
You may obtain a copy of the License at

http://www.apache.org/licenses/LICENSE-2.0

Unless required by applicable law or agreed to in writing, software
distributed under the License is distributed on an "AS IS" BASIS,
WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
See the License for the specific language governing permissions and
limitations under the License.