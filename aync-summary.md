#async article summary


Hot off the heels of RustFest Barcelona and the stabilization of async/.await.Rust’s most anticipated language features has finally landed.The stabilization of async/.await also coincides nicely with another event I’m excited about: This week saw the release of the most recent entries in the mainline Pokémon games, Pokémon Sword and Shield

#what is async ?
Asynchronous simply means multiple tasks are running on the same time on a single thread .multi-threading can be related but its a different idea/theory .multi-threading is beneficial for CPU-BOUNDED tasks .Parallel or concurrent programming can be favorable when the program spends a lot of time waiting for the server to give response .these tasks are known IO-bound task .When we reach a point where we need the result of an asynchronous function, we must .await it .


Async in rust is slightly different from what we use in other languages .

   #An async function does not (necessarily) start executing immediately

to start an asynchronous function you should add .await in it or by the help of an executor , launch it .Until this happens, all you have is a Future that has not started .

#advantages of Async
1.it is less time consuming.
2.improve performances 
3.improved responsiveness