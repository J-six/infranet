# Infranet
This is a fork of ByteNet which had a collection of issues. Such as a lack of it being userfriendly, lack of remote functions
I've added remote functions that allow both client and server to share functions. Including the server invoking the client, it is a concern and is not recommended however I've implemented some safety, such as: The invoke being dropped after the client has not responded for 5 minutes, aswell as the invoke being wrapped in a pcall.

-# Infrastructure + Network -> Infranet
