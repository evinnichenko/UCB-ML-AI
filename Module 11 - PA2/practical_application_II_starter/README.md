# Practical Application 2

Link to the Jupyter notebook: [link](/prompt_II.ipynb)

WARNING! In order to save space, all outputs were cleared. To get some of the graphs you need to run the notebook on your computer.

## Findings

I was able to make and fit a Ridge regression model that successfully predicted car price with relatively decent MSE. I was also able to find a nubmer of factors that influence car price the most, listed below, and make a small function to try that model.

- Of manufacturers, Tesla, Toyota, Porsche, and Lexus have very good markup coefficients, as do some others like Mersedes, Audi, and Ram. more popular budget car manufacturers, like Nissan, Hyundai, Kia, and Mitsubishi are on the opposite, experiencing pretty severe negative markup. This is actually tied into the specific models, but that required too much outside information and wasn't analyzed.
- Diesel usually sells for more money than other types, and gas cars are cheaper;
- Of types, trucks, convertibles, and coupe are the ones with markup. Sedans, SUVs, and hatchbacks, on the other hand, are usually marked down;
- Obviously, clean and lien cars sell for more than other title statuses. interestingly, offering a car as parts only is a good way to recuperate some of the loss if that is the only chance at selling it;
- Manual transmission is more expensive, and "other" (IIRC, it was electrical) are much cheaper, but overall there is little change depending on transmission type;
- 4WD cars are much more valued than others, and FWD are less so, with RWD in almost exact middle;
- Finally, you can expect higher prices if you are selling in CA, AK, AL, TN, or UT, and lower prices if you are located in NY, OH, or PA
