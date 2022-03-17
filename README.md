# jsonion-stem

A jsonion stem is the smallest reasonable particle, a data point that's framed in context of its own evolution and that of its related counterparts. In its core, jsonion stem entangles properties that surpass and extend a data node in its own terms; it is therefore an augmentation of a given data entity.

There is a contemporary quest for the optimal data node structure, verifiable in a distributed setting. Database relations are a well-known concept in modern web stacks, however the challenge remains to organize and store database documents in a way that minimizes the burden of distributing data storage, access and its validation to the passing of time.

Public and private blockchains have come to offer a rather viable solution to this end, locking in data nodes in order of creation, but meanwhile making it difficult to decouple this randomly scattered data without sacrificing its undisputable validity. However, if there was real-world logic applied to data distribution, who stores it and for whom, efficiency of using such distributed databases would rapidly increase – but then the concept of a shared chain would inevitably collapse.

This challenge guides you to rethink this dynamic by introducing the public blockchain merely as the storage for checksums, validation hashes derived from individual data nodes (some would call this a hyperchain).

The question remains that of which data entity is to be considered front-facing, which data node invokes its relations (this line of thought also touches caching configuration).

The rest is pure determinism; in predictably sorting the included data nodes, in determining the protocols for safe-keeping checksums over long periods of time and sharing data among peers. The importance here is that to maintain data consistency, any removed data subparts will need to leave behind their partial checksums, as situated in the broader context of a particular data node. So that's settled, in theory.

Going back to the roots, jsonion stem is a layer that augments a data node, in this case with properties regarding validation and the included related data. It can extend a given data node in more than just one way, though.

Here's an example of a vigorously augmented data node (without exposing schema or components):

```javascript

var exampleDataNode = {
id: `${id}`,
__: {
  validation: {},
  actions: {},
  time: {},
  src: {}, rels: {},
  augm: {}, embed: {},
  stats: {}, chksum: {},
  subset: {}, private: {},
},
/* ... */
};

```

For creating an asset, one that will outlast an eternity of an overcrowded blockchain, it is vital to establish deep understanding of its real-world use-cases, the contexts in which the virtual resource is shared among peers and finally, what the logical concept might be in terms of archiving.

One example of a user-facing data entity is shared in yet anothet repository at [github.com/jsonion](https://github.com/jsonion/leapgest). Its beauty lies in the ripples it creates in the physical world, resonating with aesthetics of body moving in the virtual realm, alike. It's a concept of greater significance.

Forks welcome!
