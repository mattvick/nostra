# Value Proposition

The following is my analysis of the idea, and its value proposition (why a customer would choose to use this product or service). I understand that being analytical takes some of the fun out of things. It also reduces risk. If you prefer high fun, high risk, I suggest you [jump out of an aeroplane without a parachute](https://www.youtube.com/watch?v=aPC_h9Vmlxw). 

## Pain points

A pain point is a user frustration with an existing product, process or service that they use.

- What are the user pain points this product will solve?
- Why would a potential user choose to use our service rather than [existing betting mechanisms](#existing-betting-mechanisms)?

## Existing Betting Mechanisms

- [1:1 Betting](#11-betting)
- [Sweepstake](#sweepstake)
- [Odds](#odds)

### 1:1 Betting

An agreement between two people. May be a verbal or written agreement, made in person, over the phone or via a chat app etc.

- Example: I bet you £10 that Arsenal will beat Liverpool today.
- Number of players: 2
- Mechanism: winner pays loser.
- Limitations: doesn’t work for more than 2 people

What pain points do people who make this kind of bet have?

- I have little guarentee that the loser will pay me
- I'm worried that the loser may disagreement about the outcome (similar to above)
- I can't bet with more than one person this way
- ... ?

### Sweepstake

An agreement between a group of people. Typically a group of friends or colleagues.

- Example: Which team will win the World Cup?
- Number of players: multiple, without limit. 
- Mechanism: Each player bets the same amount. The winner/winners take all.
- Limitations: works best when there are multiple horses or teams and only one winner. I assume this is more of a cultural limitaion than a practical (real) limitation

What pain points do people who make this kind of bet have?

- I don't want to make the effort to set up the sweepstake, invite my friends and collect the money, even using one of the many apps that are freely available this is too much effort for me 
- ... ?

### Odds

- Example: a bookmaker offers odds of 30/1 that a specific horse will win a race. 
- Number of players: multiple, without limit. 
- Mechanism: the bookmaker sets the odds and adjusts these as more punters bet. Typically the bookmaker makes money whatever is the outcome. A punter wins their stake back plus an additional amount calculated based on the odds.

What pain points do people who make this kind of bet have?

- ... ?

## Traditional agreement types

- Gentleman’s agreement (hand shake)
- Written agreement (on the back of an envelope, etc.)
- Use of third party to hold the money
  - Friend
  - Barman
  - Sweepstake app
  - Bookmaker

## Suggested Prediction Mechanism

- [Predictors](#predictors)
- [Backers](#backers)
- [Refuters](#refuters)
- [Predictions](#predictions)

### Predictors

A predictor is a user who creates a prediction.

### Backers

A backer is a user who financially backs a prediction.

### Refuters

A refuter is a user who bets financially against a prediction.

### Predictions

A prediction would look similar to a tweet on Twitter. There would be the user's prediction as a short string of text, under their profile picture, their username, and the date and time. There would also be buttons to "back" or "refute", much as apps like Facebook and YouTube have like and dislike buttons. The current amounts staked fore and against the preditions. The odds for and against, which would be calculated by the ratio between the total amounts staked for and against. A button to share your prediction.

Users can make multiple predictions.

Predictions must be in some way [verifiable](#verification-of-the-outcome). There would need to be a mechanism to police this. This could probably be community driven. Non-verifiable predictions could be removed by the community in a similar way to how the Wikipedia community removes inaccurate or unverified information.

- Betting cut off date
- End date - optional?

### Visibility

There could be open both public and private predictions.

- **Public predictions:** Publicly visible on and found via Google etc. Anyone can bet for or against.
- **Private predictions:** Only invited people can view and can bet for or against.

### Duplication

- We could allow duplication of private predictions.
- We may want to limit duplication of predictions as people stand to win more money when the number of people betting on a prediction is higher. If we have to many duplicates the number of better will be spread amoung these in some cases leading to smaller winnings.
- We could use but human users, moderators, and large language models like GPT3 to halp find duplicates.

### Predicting

Cut off date must be set. When no more bets will be accepted.

### Verification of the outcome

How does the system know **when** and **if** the perdiction is correct? 

Maybe we could leave this up to the community to decide, and define a specific quorum of complaints that must be reached before we would arbitrate.

### Backing

A user clicks the "Back prediction" button (may be a thumbs up icon) and then stakes an amount of fiat currency using, paypal or a debit or credit card etc. to make the payment.

### Refuting

A user clicks the "Refute prediction" button (may be a thumbs up icon) and then stakes an amount of fiat currency using, paypal or a debit or credit card etc. to make the payment.

### Payout

Once a prediction has passed [how would this be determined, and by whom?](#verification-of-the-outcome) the payout would be split as follows:

Total amount bet = the total of all bets fore and against.

If the prediction is correct the predictor receives 10% of the total staked.
If the prediction is incorrect the app receives 10% of the total staked.

The remaining 90% is devided amoung the winning group, either the backers or the refuters, based on the percentage value of their stake within the group.

- A [spreadsheet](https://docs.google.com/spreadsheets/d/1a6uRaUK5cMSEDcnfpF3CfpDJWa5NDmWhAqhyzfwHy_Y/edit?usp=sharing) with two sheets (tabs at the bootom)
  - The first sheet shows a payout calculation for a prediction that had roughly 50/50 backer and refuters
  - The second sheet shows a payout calculation for a prediction that had more backer than refuters
