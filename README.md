# vectorize
### A comparison of numpy vectorization and for loops.

A week or so ago I was talking with a friend and she was complaining about... idk something to do with Python vs IDL. Anyway, the whole Numpy is faster than native Python thing was brought up and she was saying that it wasn't and that people were still doing for loops (in the form of list comprehension) with np arrays. I was going to try to send her an article on vectorization but was honestly unsatisfied with the articles out there, so I figured I'd throw together a quick Jupy nb and try to compare the different ways of doing array math. She's not really a SWE or DS person, but has to interact with data a fair amount for her research. The point I'm trying to get at is that apparently some SWE's that she works with are just throwing lists into np, putting together some (allegedly) hard to read list comprehension, and saying that's faster than standard python. I mean, I think we should be better than that; but let's find out.
