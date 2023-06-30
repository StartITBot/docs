
# Crafting – Do it yourself

Crafting in StartIT allows users to combine various ingredients to create new items or products. This guide will provide
an overview of how crafting works and explain how to configure crafting recipes in the bot.

## Listing Crafting Recipes

Crafting recipes are created and managed by administrators. These recipes define the required ingredients and the
resulting product. Users can view the available recipes through the `/craft list` command. This command displays a list
of all available recipes, along with their names and descriptions.

## Obtaining resources

To craft a recipe, you need to gather all the necessary ingredients. These ingredients can include items, roles,
cases, or even a certain amount of money. The recipe description will provide details about the required ingredients.
You can acquire the ingredients through various means such as purchasing them from the shop, receiving them from other
users, or completing specific tasks. Administrators sometimes don't say all the ingredients in the recipe description,
so you need to figure out yourself what items you need to craft the recipe.

Sometimes the ingredients are rare and difficult to obtain, making the resulting product more valuable.
This encourages you to engage in trade and collaborate with others to obtain the ingredients you need. It also
creates a sense of accomplishment when you successfully craft a recipe. The resulting product can be used by you
or sold on the user-market. This creates a dynamic economy where you can specialize in either item production through
crafting or item trading through the user-market.

Once you have gathered all the required ingredients, you can initiate the crafting process. The bot will check if
you meet all the requirements and probably consume the ingredients in the process. If successful, you will receive
the resulting product.

## Crafting process

To start crafting, use the command `/craft recipe <name>`, where `<name>` represents the name of the recipe you want to
create. It's worth noting that `<name>` is recipe name from `/craft list` command, not the name of the resulting
product. Once you initiate the crafting process, the bot checks if they meet all the requirements for
the recipe. If the requirements are met, the ingredients are consumed, and you will receive the crafted product.
If the requirements are not met, the crafting attempt fails without consuming ingredients. Bot won't tell you what
ingredient you are missing, so you need to figure it out yourself.
