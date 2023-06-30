
# Concept of items, why they are important

Items are a key aspect of the economy plugin, adding depth and interactivity to the server. Users can obtain items
through various means, such as purchasing them from the `/shop`, buying second-hand items from the `/market`, or
receiving them as gifts from other players using the `/give-item` command. Items are stored in the user's backpack, and
they can be used with the `/use-item` command, provided the item is configured for use.

## Using items for customizing user roles and permissions

Items can be configured to grant users special roles or permissions when used. This allows for personalization and
differentiation among server members, creating a sense of uniqueness and status.

Let's say you have an item called "VIP Pass". When a user purchases and uses this item, it can automatically assign them
a special role that grants access to exclusive channels or features on the server. This not only adds a layer of
customization but also makes users feel valued and recognized. You can also create cheaper items that gives VIP for
3/7/30 days.

## Using items for simulating businesses or activities

Items can simulate businesses or activities within your server, providing users with additional ways to earn virtual
currency or unique benefits.

Consider creating an item called "Bakery." When a user owns this item and uses it with the /collect-income command, they
receive a certain amount of virtual currency every 24 hours as bakery income. This encourages users to collect items and
engage in economic strategies within the server.

## Using items for offering discounts and benefits in the shop

Items can be configured to provide discounts or special benefits in the server's shop. This incentivizes users to
acquire and use specific items, creating a dynamic economy within the server.

Let's say you have an item called "Discount Card". When a user owns this item, it reduces the prices of items in the
shop by a certain percentage. This encourages users to collect the item and actively participate in the server's
economy, as they can save virtual currency on their purchases.

## Using items for increasing earnings from the /work command

Items can be utilized to enhance the earnings obtained through the server's /work command, providing users with a way to
boost their income and progress.

For instance, you can introduce an item called the "Work Efficiency Booster". When a user owns and equips this item, it
increases the amount of virtual currency or experience points they receive from performing the /work command. This
encourages users to acquire and use the item to maximize their earnings within the server's economy.

## Using items for increasing points from leveling and chatting

Items can be employed to augment the points users earn through leveling systems or engaging in chat interactions. This
introduces a sense of progression and rewards active participation.

For instance, you can create an item called the "Experience Amplifier". When a user possesses this item, it increases
the amount of experience points they earn for each level gained. This enables users to level up faster and unlock
additional perks or abilities within the server.

## Using items for extending bank limit

Some items can be configured to extend the maximum amount of money a user can keep in their bank. This creates a
progression system where users strive to obtain these items to increase their financial capabilities.

For example, an item called "Banker's Charm" can be configured to increase the bank limit by a certain amount when used.
Users who possess this item can store more virtual currency in their bank, providing them with a strategic advantage and
sense of progression within the server.

## Using items as a one-time pass for manual action

Items can serve as one-time passes for manual actions or special privileges within the server. This allows you to grant
users unique abilities or access to exclusive features.

For example, you can create an item called "Global Announcement Pass". When a user purchases and uses this item, the
server owner gets notified and lets the user send a global server announcement. Additionally, if you run for example a
Minecraft server, you can create items that users can exchange for in-game additions or perks.

Or if you're a YouTuber, you can create an item called "Video Pass". Users who purchase can be included at the end of
your videos as a personalized shout-out or thank you. This adds a special touch to your content and allows you to engage
directly with your audience. Or, you can create item called "Call Pass" that allows users to join a private voice call
with you.

## Using items as a way to take taxes

All items have a configuration option called "Item Owner" that can be set to a specific role or item. This allows you to
distribute earnings from the shop among the owners of those roles/items. You can use it to allow users send a quick
donation to all your server vips, or you can create an item called the "Shop Manager" that revises all the money from
the shop.

Also, you can create "Tax Office" item in their backpack, they receive a portion of the taxes collected
from commands like /work, /pay, or /collect-income. This encourages users to acquire the item and participate in
economic activities within the server. It also provides a way for server owners to manage and distribute income
effectively.

## Using items as crafting ingredients

Items can be used as crafting ingredients to create more advanced items or unlock unique features. This adds depth and
complexity to the server's economy and gameplay.

For example, you can create items such as "Wood", "String". Then, with the /crafting command, users can combine these
items to craft a "Hammer" item. The Hammer item can have different uses, such as breaking down other
items, unlocking special channels, or providing additional benefits. By making the Hammer item unobtainable in the shop,
you encourage users to engage in crafting and trading on the user market (/market command).

You can also design more intricate crafting systems that require multiple items and time investment, creating
opportunities for users to specialize in item production and generate income solely from crafting and selling items on
/market.

## Using items as decorative and collectible items

Not all items need to have functional or gameplay-related purposes. Some items can serve as decorative or collectible
assets, allowing users to express themselves or showcase their achievements within the server.

For instance, you can create cosmetic items such as "Golden Crown" or "Rare Pet." These items do not have any functional
effects but can be visually displayed in a user's profile or inventory. Users can trade or showcase these collectible
items, fostering a sense of ownership and personalization.

## Cases - special type of items with element of surprise

Items can also be used to enhance gameplay or interactions among users. They can introduce new mechanics, mini-games, or
challenges that make the server more entertaining and engaging. There is a **special type of item** called "Case" that,
when used, randomly drop other items, cases, roles, or sometimes just nothing.

![](../assets/v10.png)

When using a case (with /use-item command), the outcome is determined by chance. This adds an element of excitement and
surprise to the server experience. For instance, you can create a case called "Mystery Box". When a user uses this case,
it grants them a surprise reward, such as additional virtual currency, special roles, or unique items, but there is 60%
chance that the user will get nothing. You can't imagine how much fun it is to get rare item from cheap case!

## Conclusion

These are just a few examples of the various use cases for items within StartIT's economy plugin. By
strategically configuring and utilizing items, you can create an immersive and dynamic economy that enhances the overall
user experience in your server. The possibilities are virtually limitless, and you can tailor the items to suit the
theme, interests, and dynamics of your community.
