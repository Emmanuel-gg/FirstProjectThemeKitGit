--- THEME KIT ---
# GET ALL THEMES [Any]
Get all the themes in the store $my_store
> theme get --list -p="$theme_password" -s="$my_store"

# CREATE A THEME [Theme_Directory]
Creates a theme with a name $theme_name in the store $my_store, with the info of the current directory
themes\Theme> theme new -p="$theme_password" -s="$my_store" --name=$theme_name

# CLONE A THEME [Theme_Directory]
Obtain the theme $theme_id files in the store $my_store in the current directory
themes> theme get -p="$theme_password" -s="$my_store" --themeid=$theme_id

--- SHOPIFY CLI ---
# START DEV SERVER [Theme_Directory]
Start a dev server of the current theme directory
themes\Theme> shopify theme dev -s "$my_store"

