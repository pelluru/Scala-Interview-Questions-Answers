# Scala-Interview-Questions-Answers
Scala Interview Questions/Answers

Here are collected the populare Scala inverview questions/answers.

//TODO rewrite this text below.
General Questions:

What did you learn yesterday/this week?
Why and how did you start learning Scala?
What excites or interests you about coding in Scala?
What is a recent technical challenge you experienced and how did you solve it?
Talk about your preferred development environment. (OS, Editor or IDE, Tools, etc.)
What are your thoughts about the other JVM languages compared to Scala?
Do you think that the Scala language and community is mature enough?
Language Questions:

What is the difference between a var, a val and def?
What is the difference between a trait and an abstract class?
What is the difference between an object and a class?
What is a case class?
What is the difference between a Java future and a Scala future?
What is the difference between unapply and apply, when would you use them?
What is a companion object?
What is the difference between the following terms and types in Scala: Nil, Null, None, Nothing?
What is Unit?
What is the difference between a call-by-value and call-by-name parameter?
How does Scala's Stream trait levarages call-by-name?
Define uses for the Option monad and good practices it provides.
How does yield work?
Explain the implicit parameter precedence.
Functional Programming Questions:

What is a monad?
What are the monad axioms?
What Scala data types are, or behave like, monads?
What are the basic and optional requirement/s to conform a Monad?
Explain higher order functions.
What is gained from using immutable objects?
What operations is a for comprehension syntactic sugar for?
What is tail recursion?
How does it differentiate from common recursion?
What issues are there with tail recursive functions in the JVM?
How does the Scala compiler optimize a tail recursive function?
How do you ensure that the compiler optimizes the tail recursive function?
What is function currying?
What are implicit parameters?
What is and which are the uses of: Enumerators, Enumeratees and Iteratee
Reactive Programming Questions:

Explain the actor model.
Explain the Reactive Manifesto.
What are benefits of non-blocking (asynchronous I/O) over blocking (synchronous I/O).
Do you think that Scala has the same async spirit as Node.js?
Explain the difference between ‘concurrency’ and ‘parallelism,’ and name some constructs you can use in Scala to leverage both.
What is the global ExecutionContext?
What does the global ExecutionContext underlay?
Coding Questions:

How can you make a List[String] from a List[List[String]]?
What is the difference (if any) between these 2 statements?
  var x = immutable.set[Int]
  val y = mutable.set[Int]
Fun Questions:

What's a cool project that you've recently worked on?
What testing framework for Scala do you use?
What do you know about property based testing frameworks, such as Scalacheck?
Do you like ‘scalaz‘?

First, I would say, think why you need a Scala developer. Is it really Scala that you need? Think about what comes along with Scala (IDE, build tools, libs, another layer of complexity above Java etc ...). Back to the question. It goes in two aspects: Theoretical understanding and practical abilities. don't let the "theory" thing fool you. It's as important in Scala as practicality is important in Java.

Theoretical

See if they know what functional paradigm is really about. Ask them to compare the two paradigms (FP vs imperative that is) in philosophy and practice. If they can give examples from languages that has full or partial support for FP, then it's a plus for them.
Theory and practice mingled

See if they can actually do functional programming in the right way. Ask them about lists, maps, zipping and recursion. Then comes the closures, lambdas, reduction, higher order functions and immutability.
Practical

See if they can refactor an imperative code snippet into a good functional alternative (see above). Try a loop that implements some math or something along these lines.

Find their taste for functional vs imperative style. Opt for a more functional style but take caution it doesn't get to the extremes on the developer's side.

See how much they know about Scala libs (e.g. Lift, dispatch etc) and tools (e.g. SBT, fsc, IDEA).

See how well they can leverage Java (code -and- tools). Scala is tightly coupled to Java specially in more serious environments. Knowing this is a big plus.

Theoretical

Ask them to compare Scala to Java (PHP, C++, Objective C or whatever) and require them to tell you what is wrong with Scala. See if they understand the problems as well as the advantages. Ask them to give real-world examples of when Scala's shortcomings may cause trouble (e.g. It's hard for new Joes to get along, it's immature as support is very limited compared to Java etc)
Practical

See if they are connected to the community. Ask them about Martin Odersky and David Pollak. Ask them to name few Scala projects and describe them to you (Facebook, Twitter, FourSquare, DBPedia and DBPedia SpotLight). See if they know how exactly Scala is used in these projects. Have they read the articles, watched the videos, etc.?

Ask them about the books (there are only a few). The more they know the better.

As one final word of caution I may say that brilliant languages have this strange potential to attract the wrong people. Be careful about the kind that comes to Scala for all the wrong reasons. Here are few:

Scala is for the privileged (I feel smart, I feel so different from other Joes, I've got a brand new shiny Ph.D, I hate imperative because it's for the retarded, Java is superficial, Scala is so elegant, etc.). This type is not productive in serious projects and difficult to get along with.
I'm in love with Scala's syntax and would love to write my DSL everywhere I get the chance to code. This kind loves to exploit Scala's peculiarities to the last drop in a destructive way. They feel great to write cryptic and over-concise code to the point of being illegible. This kind is particularly dangerous as their code is unreadable. Their giveaway is their love for operator overloading, strange names and writing one-liners.
I stick with Scala to the last drop no matter what. This is the naive purist type. They can't trade off and project suffers when a hybrid approach is required as is the case with real world projects.
P.S: If you found a good Joe then please by all means let me know as we need some ;)
