
<p align="center">
  <img width="266" height="185" src="pix/logo.png">
</p>


# Marlowe 2.0 tutorials


This document gives an overview of a set of Marlowe tutorials.

> __Important note:__ these tutorials address the current version of Marlowe,  2.0, which irons out
> a number of infelicities in earlier versions. Marlowe 2.0 is implemented in _Meadow in the Cloud_, available [here](https://prod.meadow.marlowe.iohkdev.io).
>
> The version covered in the ISoLA paper, and supported in the original version of Meadow that includes Blockly, is tagged as **v1.3**
> and is available [here](https://github.com/input-output-hk/marlowe/tree/v1.3). 
>


##  [Introducing Marlowe](./introducing-marlowe.md)

This tutorial gives an overview of the ideas behind Marlowe, as a domain-specific language embedded in Haskell. It also introduces commitments and timeouts, which are central to how Marlowe works in a blockchain context. 

## [A first example: the escrow contract](./escrow-ex.md)

This tutorial introduces a simple financial contract in pseudocode, before explaining how it is modified to work in Marlowe, giving the first example of a Marlowe contract.


## [Marlowe as a Haskell data type](./marlowe-data.md)

This tutorial formally introduces Marlowe as a Haskell data type, building on the escrow example in the previous tutorial. It also describes the different types used by the model, as well as discussing a number of assumptions about the infrastructure in which contracts will be run.

## [Understanding the semantics](./marlowe-semantics.md)

This tutorial gives an introduction to the formal semantics of Marlowe by presenting an overview of the key Haskell definitions that interpret inputs and transactions, as well as fitting those into a schematic overview of how the components of the semantics work together.

## [Embedded Marlowe](./embedded-marlowe.md)

This tutorial shows how to use some simple features of Haskell to write Marlowe contracts that are more readable, maintainable and reusable, by revisiting the  escrow contract.


## [Using Marlowe](./using-marlowe.md)

This tutorial shows you how to use Marlowe from within Haskell, and in particular shows how to exercise a contract using the semantics given in the [earlier tutorial](./marlowe-semantics.md).


## [Meadow in the cloud](./meadow-overview.md) 

This tutorial introduces Meadow in the cloud, an online tool for creating embedded Marlowe contracts, and interactively stepping through their execution.

<!--
## [Other functions in Marlowe: analysis](./analysis.md)

This tutorial shows how Marlowe contracts can be analysed _without_ having to be executed. This made much easier because Marlowe is a special-purpose DSL, rather than a general-purpose language like Plutus.
-->

## [ACTUS and Marlowe](./actus-marlowe.md)

This tutorial gives an introduction to the general idea of the ACTUS taxonomy, plus examples implemented in Marlowe.

## [Implementing Marlowe in Plutus](./marlowe-plutus.md)

So far these tutorials have dealt with Marlowe as a “stand alone” artefact; this tutorial describes how Marlowe is implemented on blockchain, using the “mockchain” that provides a high-fidelity simulation of the Cardano SL layer.

