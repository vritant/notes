# 1. Probability
## Terms
 - event
 - outcome
 - contingency table

# 2. Conditional Probability
## Notes
 - P( A | B ) a given b
 - how B influences A
 - dependent/independant => P(A|B) = P(A and B) / P(B)
   - these are probabilities. not numbers. even in denominator.
 - independent => P(A|B) = P(A), P(A and B) = P(A) * P(B)
 - law of total probability
   - p(A) = p(A and B) + p(A and ~B)
   - where A and B are comprehensive exhaustive
 - Bayes Theorem
   - sometimes easier to get P(B|A) and compute P(A|B)
   - P(A|B) = (P(A) / P(B)) * P(B|A)

# 3 Descriptive Statistics and Probability Distributions
## Notes
 - average is bad for skewed data
 - why does stdev use squares instead of modulus?
   - easier to work with. derivatives of modulus is non-trivial, for example.
 - random variables ( RV )
   - discrete
     - probability mass function
   - continuous
     - probability density function
   - points have mass areas have density? what?
 - probability distribution is like a histogram of probabilities
 - for discreet RVs, prob distribution is not a connected line, but scattered dots.
 - expected value of random variable => E(x) = Sigma ( p(A) * value(a) )
   - when we know the value of the variable, we use the small letter.
   - expected value is a mean measurement of a random variable
   - use SUMPRODUCT function
 - expected stdev of random variable = sqroot( Sigma ( sq(p(A) * value(a) - E(x) ) ) )
   - basically, weight the deviation by probabilities
 - Y = k X
   - E(Y) = k E(X)
   - Var(Y) = k^2 Var(X)
 - Y = aX + bZ
   - Var(Y) = a^2 Var(X) + b^2 Var(Z)..... not! correlation?
     - only if X and Z are independant
 - E(X + Y) = E(X) + E(Y)
 - E(XY) = E(X)E(Y)... for independant vars
 
# 4 Normal Distribution
## Notes
 - X ~ N ( Mu , Sigma )
   - X folllows a normal dist. with mean Mu and Stdev Sigma
 - St Normal Dist = Z ~ N (0, 1^2 )
   - Z is standard normal random variable
