# Metatron

A system for claiming ownership of random numbers

## Summary

What can you do if you own a 128-bit random number? The number itself, being random, contains no information. But you can associate it with whatever information you want. And as the owner of the random number, only you can create or change that association.

## The Extensible Identifier (xid)

An extensible identifier (xid for short) is a special kind of [UUID](https://en.wikipedia.org/wiki/Universally_unique_identifier) (universally unique identifier). An example of one is `d084b2c2-cb07-41bb-ad7c-2f4b6d0626d2`. You can generate as many new ones as you like at the [Online UUID Generator](https://www.uuidgenerator.net/).

An xid is a random UUID that is specified in the `xid` field of a metadata file in IPFS. The owner of an xid is the first one to claim an xid by publishing the metadata on IPFS and authorizing the association on a supported blockchain.

## IPFS

IPFS is a distributed system for storing and accessing files, websites, applications, and data.

