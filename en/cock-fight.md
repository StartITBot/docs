
# Cock-fight – Unleash the feathers of competition

The Cock-fight feature allows users to engage in virtual cock-fights using chickens that can be purchased from the
server shop. In the default configuration, each chicken has a standard chance of winning set at 50%. This section will
guide you through how cock-fights work and how to configure them on your bot.

## Participation in chicken fight

Before participating in fight, be sure that you have living chicken in your `/backpack`. If not, purchase one in server
shop (In default configuration: `/buy chicken` command).

To participate in a chicken fight, invoke the `/cock-fight <bet>` command, where `<bet>` represents the amount of
virtual money they want to wager on their chicken. The user's chicken will then enter the battle against another (bot)
chicken.

![](../assets/v13.png)

- If the user's chicken wins the fight, its strength increases, and its winning rate is adjusted by one percentage
  point.
- If the user's chicken loses the fight, it dies, and the user will need to purchase a new chicken from the server shop.

## Admin: Configuring chicken fights

To set up and configure chicken fights in your server, follow the steps below:

1. Open your bot's dashboard and navigate to the chicken fight section.
2. Enable the "Display item in shop" option to make chickens available for purchase in the server shop.
3. Optionally, you can customize the name of the chicken to better fit your server's theme or language.

![](../assets/v12.gif)

Once you have completed these steps, the `/cock-fight` command will be ready to use with the default configuration.

While the default configuration works fine, you can further customize the chicken fight feature by adjusting the
following
options:

### Default Win Chance

You can specify the default win chance for each chicken. This represents the initial winning rate when a chicken is
purchased. (Default: 50%)

### Max Win Chance

You can set the maximum win chance that a chicken can achieve. As chickens win fights, their winning rate can increase
up to this maximum value. (Default: 70%)

### Cooldown

You can set a cooldown to limit how often the chicken fight command can be used. Specify the maximum number of uses
within the cooldown duration.

- **Maximum Number of Uses:** Set the maximum number of cock-fight uses within the cooldown period.
- **Cooldown Duration:** Define the duration of the cooldown period using a specific time format.

### Bet Limit

If desired, you can impose limits on the amount that users can bet in a single chicken fight.

- **Minimal Bet:** Specify the minimum bet amount allowed.
- **Maximal Bet:** Set the maximum bet amount permitted.

With these configuration options, you can fine-tune the chicken fight feature according to your server's preferences and
requirements. Remember to save your changes after configuring the chicken fight settings to apply them to StartIT bot.

Now that you have an understanding of how chicken fights work and how to configure them, you can provide your users with
an
exciting and interactive experience in your Discord server.
