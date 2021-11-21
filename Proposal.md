# CIS 190 Final Project Proposal- An Duong and Lance Tan
## High-Frequency Trading Bot

## Premise:

Our project will be a high frequency trading bot. It basically takes in real-time data from the stock market, calculates technical indicators, and passes it to a trading execution algorithm that tells the user to either buy, sell, or hold a decision. Real-time data is tentative as we might be planning to simplify it using static data.

## Libraries and Frameworks:

We will be using the Standard Template Library for things such as containers, locks, and threads. We will also be using JSON parser and IEX (Investors Exchange) API. 

## C++ Features and Structure:

We expect to use I/O streams, references, containers, unique pointers / RAII, and multithreading. We will be using separate classes for acquiring IEX data (static), parsing JSON data from IEX data, performing calculations on the technical data. No class hierarchy or series of class templates will be used. Our trading algorithm takes in the technical data and returns a trading decision through the output stream. 

## Expected Time for Implementation:

We expect to spend around 6 hours studying algorithmic trading and trading strategies, 2 hours implementing IEX API, 2 hours implementing JSON Parser, 1-4 hours on technical data calculations depending on how many indicators we want to use, and 3-4 hours for the trading algorithm.

## Work Split:

We plan to work together on every part of the project instead of splitting up the tasks.

