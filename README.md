## Using a sample dataset to build a public Tableau dashboard

Tableau public URL to follow, once it's live


The motivation for this project is showcase the process of building out a data visualization -- the cleaning and feature engineering needed to prep a dataset so that it does what you're expecting when dropped into Tableau.

For this example, I used one of Tableau's "resource" files -- the data for all players in EA's FIFA18 video game, a soccer simulation. I'm using the data to visualize some fairly well-understood features of the data:
- The "aging curve" -- professional players generally have a "peak" of one or more seasons when they are at their best, preceded by a ramp-up as their talent matures and followed by a decline as they age into their 30s (and 40s, in some cases). Generally, attacking players peak earlier than defenders, who peak earlier than goalkeepers.

- The FIFA18 game includes a "valuation" column, which is based on what the player would cost another team to acquire. Unlike in American professional sports, transactions in most soccer leagues take the form of a purchase (instead of a trade), in which the player is allowed to negotiate a new contract with the new team. So, where applicable, these valuations are informed by actual transactions.

- The game also includes a "wages" column, although I'm less confident about the accuracy of this information -- while player-purchases by a team may show up in accounting ledgers (or are leaked by players' agents), what the players are themselves paid is more secretive. In addition, players often have performance incentives or other complex contract structures that make any reported wage just a best-available-estimate. However, we may be able to see some trends, so I figure it's worth exploring.
