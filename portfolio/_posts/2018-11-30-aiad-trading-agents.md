---
layout: post
title:  "JADE Trading Agents Simullation"
date:   2018-11-30 23:50:37 +0100
categories: jekyll update
tags: aiad.png
author: Tiago
excerpt: A 2D game for the Minix operating system, developed in C using only the C standard library and Minix's OS API.
---

Programing Language: `Java`

Repository: [`https://github.com/TiagoJoseMagalhaes/AIAD`](https://github.com/TiagoJoseMagalhaes/AIAD)

# Description

This work was developed as a part of an agents and distributed artificial intelligence class, and its aim was to develop a highly parallelized intelligent system through the usage of agents in the JADE framework. Our group chose to develop a simulation of the stock market and its trading agents the goal being to understand what type of investment strategy would yield the highest profit margins. An agent's behavior would be characterized through its current amount of money and its risk aversion index, these would be fed into custom formulas that would dictate their likelihood of investing in any given stock each day. Agents could buy stock directly from the trading index at the start of time, but would then have to trade with each other as the index no longer had stocks to sell. The index would sell stocks at a fixed price, however, when agents traded with each other, there is a negotiation process they go through that is defined by their risk aversion and another set of formulas that defines their purchase offers.