# OptionPricing
Hi guys! I have decided to expand the list of my repositories, so I have decided to post some of my old projects. This was actually my Bachelor Thesis and the way I started to code.
The script is a Tkinter User interface which is really well explained in the application itself, that is why I want to keep this README file short. The interface is based on different pages that contains various European Option calculators using Black-Merton-Scholes model. It also provide the Greeks of the options already calculated.

One of the most interesting features can be found in the last pages, where the calculator allows to hedge through the Greeks a portfolio of option, providing you the choice for which Greeks you are interested to hedge (delta, gamma, ...). While the code itself is simple, it provides a calculator for hedging dynamically a portfolio, the calculations for the exact amount of contracts required is carried out with Dantzig's Simplex which allows to minimize the cost of the hedging portfolio.

In case you are interested I can provide the full Thesis which carefully explain each step taken. Just contact me at bronzetti97@gmail.com
