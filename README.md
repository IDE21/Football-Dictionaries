# Football-Dictionaries
At SDA & INE

### Description:

This Python script is designed to process and organize football player data that is initially provided as a list of lists. Each list represents a player with various attributes such as their position, name, and country. The script includes three main functions that progressively transform and organize this data into more structured and meaningful formats.

### Key Functions:

1. **`convert_players_to_dicts(players_list)`**:
   - **Purpose**: Converts each player's list of attributes into a dictionary. This allows each piece of data (like the player's position, name, or country) to be easily accessed using descriptive keys.

2. **`group_players_by_position(players_list)`**:
   - **Purpose**: Groups the player dictionaries by their playing positions. This function organizes the players into a dictionary where each key represents a position, and the corresponding value is a list of players who play that position.

3. **`group_players_by_country_and_position(players_list)`**:
   - **Purpose**: Adds an additional layer of organization by first grouping players by their country, and then by their position within each country. The result is a nested dictionary where players are categorized both by their country and their position, making it easier to analyze teams and squads based on these criteria.

### Overall Functionality:

- **Data Transformation**: The script starts by transforming raw player data into a more structured dictionary format.
- **Grouping by Position**: It then organizes these player dictionaries by their positions on the field, creating an easy-to-navigate structure for analyzing players by role.
- **Grouping by Country and Position**: Finally, it groups the players by their country and further categorizes them by position within each country, providing a comprehensive view of the players based on both nationality and field position.

### Conclusion:

This script provides a robust solution for managing and analyzing football player data, converting unstructured lists into organized dictionaries. This structured approach simplifies the process of accessing and examining player information based on specific attributes like position and country.
