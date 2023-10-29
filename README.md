# Typelevel Toolkit

A toolkit of great libraries to get started building Typelevel apps on JVM, Node.js, and Native! Our very own flavour of the [Scala Toolkit].

```scala
//> using toolkit typelevel:latest

import cats.effect.*

object Hello extends IOApp.Simple:
  def run = IO.println("Hello toolkit!")
```

To get started, install [scala-cli](https://scala-cli.virtuslab.org/install/) and download the accompanying [template](https://github.com/typelevel/toolkit.g8) in a folder called `typelevel`. Then, run this command: 

``` sh
$ scala-cli --power new typelevel/toolkit.g8
```

And finally, to run your new script:

```sh
$ scala-cli run <YourScript>.scala
Compiling project [Scala X.X.X, JVM (X)]
Compiled project [Scala X.X.X, JVM (X)]
Hello, World!
```

# Libraries included

* [Cats] and [Cats Effect]
* [FS2] and [FS2 I/O]
* [FS2 Data Csv] and its generic module
* [http4s Ember client]
* [Circe] and http4s integration
* [Decline Effect]
* [Munit Cats Effect]

[Scala Toolkit]: https://docs.scala-lang.org/toolkit/introduction.html
[Cats]: https://typelevel.org/cats
[Cats Effect]: https://typelevel.org/cats-effect
[FS2]: https://fs2.io/#/
[FS2 I/O]: https://fs2.io/#/io
[FS2 Data Csv]: https://fs2-data.gnieh.org/documentation/csv/
[http4s Ember Client]: https://http4s.org/v0.23/docs/client.html
[Circe]: https://circe.github.io/circe/
[Decline Effect]: https://ben.kirw.in/decline/effect.html
[Munit Cats Effect]: https://github.com/typelevel/munit-cats-effect
