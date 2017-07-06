# About
[SPy] - This fork of the library looks to address a need for being able to Select a static type from a Dynamic expression as noted in the following StackOverflow articles:
https://stackoverflow.com/questions/1465700/system-linq-dynamic-select-new-into-a-listt-or-any-other-enumerabl
https://stackoverflow.com/questions/44915453/select-clause-using-system-linq-dynamic-is-returning-expected-fault

This implementation comes from a contribution from dahlbyk on the first link. Not sure why none of the forks to date appear to have implemented this option, but here you go.

From meatGUY - 
As far as I know the history is somewhat similar to this.

This project takes his beggining as .NET 3.5 library created by Microsoft for some reason - if I am not mistaken there should be some articles in the MSDN Magazine at least about a parser engine that is used here.

Then it was ported to .NET 4.0 by @kahanu and shared on the GitHub for public use according to MSPL licence.

Then @NArnott forked from the @kahanu repository (by this time it was not supported for a while) and did a great job - he introduced unit-tests, web documentation and lots of stuff (for some period of time I was contributing to his fork). 

Then sometime ago @NArnott dismissed the NuGet package and deleted the documentation from hosted Azure instance and I took ownership of the library and uploaded a [package][1] and create a host for [documentation][2].

[1]: https://www.nuget.org/packages/AK.System.Linq.Dynamic/ "NuGet - Dynamic Linq Library"
[2]: http://ak-dynamic-linq.azurewebsites.net

# Credits
I would like to thank everyone who put his effort in this project. 

# What's next?
I use this library on several production project that is why it gets updated with new features but most of the time it is not. The project itself is alive and I will encouradge you to report bugs and propose feature requests (if I would have time I will do both).

# P.S
Hope I didn't missed anything +)
