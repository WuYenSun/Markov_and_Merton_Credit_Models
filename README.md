# Markov_and_Merton_Credit_Models

In this project, we review two credit models: the Markov Chain model and the Structural model.

The Markov model leverages the concept of Markov chains to assess the creditworthiness and default probabilities of entities over time. The transitions between these states are governed by a transition matrix, which captures the risk-neutral probabilities of moving from one credit state to another. Its simplicity, interpretability, and ability to capture time-varying credit dynamics make the Markov credit model a valuable tool in credit risk management and pricing of credit-sensitive instruments.
Our project reveals that the credit spread term structure displays a negative slope for a distressed firm and a positive slope for a healthy firm within the Markov model. The intuition is that the initial state is less relevant as time progresses.

The structural model developed by Robert C. Merton in 1974 offers insights into the dynamics among a firm's internal stakeholders. 
However, its practical applicability is limited due to its stringent assumptions. 
Furthermore, the credit spread term structure generated by this model exhibits collapsing spreads for short maturities, which contradicts the behavior observed in real markets.
The literature proposes more sophisticated approaches, such as continuously withholding information or utilizing curved barriers. 
However, in practice, these models have limited or negligible applications.
