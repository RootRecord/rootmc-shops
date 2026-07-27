# Commands and permissions

## Commands

| Command | Description | Permission | Usage |
|---------|-------------|------------|-------|
| `/buy` | Buy from the cheapest in-stock player chest shop | `` | `/buy <item> [amount] / /buy confirm <shop-id> <amount> / /buy cancel` |
| `/sell` | Sell to the highest-paying player buy shop | `` | `/sell <item/all> [amount] / /sell confirm <shop-id> <amount> / /sell confirmall / /sell cancel` |
| `/shop` | Create and manage player chest shops | `` | `/shop <create [price]/stock/editprice/editqty/edittype/remove/cancel/reload/purge/avg>` |
| `/shops` | Browse all items a player has for sale | `` | `/shops <player> / /shop for create/manage` |
| `/items` | Open your shops browse GUI | `` | `/items [player]` |
| `/market` | Open the shops browse GUI | `` | `/market [player]` |

## Permissions

| Permission | Description | Default |
|------------|-------------|---------|
| `rootshops.create` | Create a RootMC shop | `true` |
| `rootshops.admin` | Admin shop commands (/shop editprice, remove, reload) | `false` |

