# ABCS - Adaptive bandit cache selection

select method store Multi-Armed Bandit

## Disclaimer

It is experimental solution. Because choosing an algorithm during program execution multiplies memory consumption

## Problem

I would like to make an algorithm based on statistical data so that it independently chooses the optimal storage method during operation.
Because choosing a specific algorithm for specific tasks is a separate research work

## Input

### In create cache

- Start algorithm
- Count storage elements
- We won't stop business logic for restructed cache

### In runtime

- Hitrate into start algorithm


### Questions

- When we need migrate from start algorithm to new?

## Idea

TODO

## Usage

TODO

### Supported cached methods

- Random
- LRU by default
- LFU
- 2Q
- ARC

## Reference

TODO

## Implementarions

- LRU, ARC, 2Q [golang-lru](https://github.com/hashicorp/golang-lru)
- LFUDA [lfuda-go](https://github.com/bparli/lfuda-go/)
- Multi-Armed Bandit(MAB) [go-bandit](https://github.com/alextanhongpin/go-bandit)
