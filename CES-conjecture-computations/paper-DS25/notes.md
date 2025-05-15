# Computational Verification of Rational Torsion on X₁(p)

This repository contains the code **`DS25-code.m`**, developed to reproduce and verify the computational claims made in the 
paper “On Some Open Cases of a Conjecture of Conrad, Edixhoven and Stein”, co-authored by Michael Stoll and me.

## Description

The script takes a prime *p* as input, computes:

1. The full rational torsion subgroup of the Jacobian of the modular curve X₁(p), and  
2. Its rational cuspidal subgroup.

It then checks whether these two subgroups coincide. 

## Usage

By default, the code runs for *p = 29*, corresponding to the first open case of the conjecture resolved in the paper 
[Torsion points on elliptic curves over number fields of small degree](https://msp.org/ant/2023/17-2/p01.xhtml) that inspired this work. 

You can test additional cases by uncommenting the line "// p := ;", choosing your favourite prime, and supplying the appropriate Hecke operator as given in the tables of the paper. 
So far, computations have been carried out up to the prime p = 113; larger primes may require significantly more CPU time and multiple attempts.
