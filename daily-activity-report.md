# Daily activity report

## Day 1

Solve test problems in Scala.js, verify the main construct  in the  web-based simulator

## Day 2

Refactor scafi dsl for javascript, test main API.

## Day 3

Create graph model abstraction

## Day 4

Test graph model, start to create web page skeleton. Studying scala-css and scala-tags libraries.

## Day 5

Adapt webpage with scala-tags and scala-css, adapt webpack configuration. Start to study phaser. Performance tests, problems with iteration (Set are much slower than js.Array, find a solution). *target performance* : 1000 node with 4 neighbours at 30 fps.

## Day 6

Phaser facade

## Day 7

Phaser facade. Problem in test with costum configuration. link : https://github.com/scalacenter/scalajs-bundler/issues/130

## End sprint 1, considerations

The overall development performance isn't so good. There was different problems linked to scala.js. I hope to perform better in the new sprint.

## Day 8

Fix problems for scalatest: remove phaser object in testing with a specific webpack configuration. This is a workaround, find a cleaner solution. Stop work on phaser facade.

## Day 9

Define a structure for the application. Currently no specific UI framework was used, all the computation depens on a stream of side effects that alter the backend status.

## Day 10

Test the simulation execution (this task isn't in the sprint, but during the system structure i want to verify if the view works as expected)