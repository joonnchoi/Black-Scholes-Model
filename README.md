# Black-Scholes Option Pricing Model

This repository contains an implementation of the Black-Scholes option pricing model, a mathematical model for calculating the theoretical price of European-style options.

## Overview

The Black-Scholes model, also known as the Black-Scholes-Merton (BSM) model, is a mathematical model for pricing options contracts. Published by Fischer Black and Myron Scholes in their 1973 paper "The Pricing of Options and Corporate Liabilities", the model revolutionized the financial world and remains fundamental to modern financial theory.

## The Model

The Black-Scholes formula for calculating the price of a European call option is:

C = S₀N(d₁) - Ke^(-rT)N(d₂)

Where:
- C = Call option price
- S₀ = Current stock price
- K = Strike price
- r = Risk-free interest rate
- T = Time to maturity
- N = Cumulative distribution function of standard normal distribution
- d₁ = (ln(S₀/K) + (r + σ²/2)T) / (σ√T)
- d₂ = d₁ - σ√T
- σ = Volatility of the stock price

## Features

- Implementation of the Black-Scholes formula for European options
- Support for both call and put options
- Calculation of option Greeks (Delta, Gamma, Theta, Vega, Rho)
- Visualization tools for option pricing analysis
- Comprehensive test suite

## Getting Started

(Coming soon)

## Usage

(Coming soon)

## Contributing

Contributions are welcome! Please feel free to submit a Pull Request.

## License

This project is licensed under the MIT License - see the LICENSE file for details.

## References

1. Black, F., & Scholes, M. (1973). The Pricing of Options and Corporate Liabilities. Journal of Political Economy, 81(3), 637-654.
2. Hull, J. C. Options, Futures, and Other Derivatives. Pearson Education.