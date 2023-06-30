
An user can register a new supermarket providing it's name and address

The system will check if there's any supermarket in the same zip code. If already exists a supermarket in the zip code registered, system will show user all supermarket in zip code mentioned then ask user to confirm he is registering a different supermarket in the same zip code

Necessary data for supermarket registration:

name
zip code
street name
street number
city
state
country

all data can be edited and saved in one history

When an user edit a supermarket, the old register is inactivated (deleted at) and a new register is created with parent id referencing the old record. This way we can have a history saying witch user edited witch field in a record