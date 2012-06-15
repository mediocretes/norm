norm (Not ORM)
====

A mongo ruby driver wrapper that includes all the stuff you were about to implement on your own.

The Plan:
====

version 0.1
----

 * Add norm to connection creation in a painless way
 * Prove that norm can put itself where it needs to go in the driver
 * Auto-persist connections if you want
 
version 0.2
----

 * BSON::OrderedHashWithIndifferentAccess
 
version 0.n
----

 * ActiveModel (or at least ActiveModel style) validations
 * Schema Validations
 * Full Schema Enforcement, if that's what you really want, you sick bastard
 * Versioning and lazy migrations as first class members
 * Some sort of indexing thing
 * T-shirts with a snazzy logo
 * Schema inferences maybe, or some sort of inspector/summarizer
 * Make it more like OpenStruct, but not slow like OpenStruct
 * Smart Replset target selector if reading from secondaries
