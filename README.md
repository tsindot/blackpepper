# blackpepper

Blackpepper is a type-safe Scala DSL for dealing with Cassandra

    Recipes.select(_.description, _.author).where(_.url eqs r.url).one

Consider [BlackpepperSpec.scala](https://github.com/whiskteam/blackpepper/blob/master/src/test/scala/com/whisk/blackpepper/test/BlackpepperSpec.scala) and [QuerySpec.scala](https://github.com/whiskteam/blackpepper/blob/master/src/test/scala/com/whisk/blackpepper/test/QuerySpec.scala) as an example


## Dependency

    resolvers += "Whisk Snapshots" at "http://whisklabs.github.io/mvn-repo/snapshots/"
    
    libraryDependencies += "com.whisk" %% "blackpepper" % "0.1.0-b02aa73"

    
