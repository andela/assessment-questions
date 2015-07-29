##world


| name        |      continent     |  area    | population | gdp |
|----------   |:-------------:     |------:   |----------: |----:|
| Afghanistan |  South Asia        | 652225   |26000000    |     |
| Albania     |  Europe            | 28728    |3200000     | 6656000000    |
| Algeria     |  Middle East       | 2400000  |32900000    | 75012000000    |
| Andorra     |  Europe            | 468      |64000       |     |
| Brazil      |  South America     | 8550000  |182800000   |  564852000000   |
| Colombia    |  South America     | 1140000  |45600000    |     |
| Nauru       |  Asia-Pacific      | 21       |9900        |     |
| Uzbekistan  |  Central Asia      | 447000   |26000000    |     |


1. Select the answer which shows the problem with this SQL code - the intended result should be the single row    containing 'France':

  ```sql
    SELECT continent
     FROM world
    WHERE 'name' = 'France'
  ```
  - continent should be 'continent'
  - 'name' should be name
  - 'France' should be "France"
  - 'France' should be France
  - = should be IN

2. Select the code which would reveal the name and population of countries in Europe and Asia

  ```sql
      SELECT name
      FROM world
      WHERE continent IN ('Europe', 'Asia')
    ```

   ```sql
      SELECT name, population
      FROM world
      WHERE continent IN ('Europe', 'Asia')
    ```

    ```sql
      SELECT name, population
      FROM world
      WHERE name IN (Europe Asia)
    ```

    ```sql
      SELECT name, population
      FROM world
      WHERE name IS ('Europe', 'Asia')
    ```

    ```sql
      SELECT name, population
      FROM world
      WHERE continent = ('Europe', 'Asia')
    ```

3. Select the result that would be obtained from this code:

    ```sql
      SELECT name FROM world
      WHERE continent = 'South America'
      AND population > 40000000
    ```
    | name        |
    | :---------: |
    | Afghanistan |
    | Brazil      |
    | Colombia    |


    | name        |
    | :---------: |
    | Brazil      |


    | name        |
    | :---------: |
    | Brazil      |
    | Colombia    |

    | name        |name|
    | :---------: |:---: |
    | Brazil      |South America|
    | Colombia    |South America|

    | name        |name|
    | :---------: |:---: |
    | Brazil      |182800000|
    | Colombia    |45600000|

4. How would you design an efficient database schema for a user authorization system?

 - [ ]  Table names: `users`, `permissions`; Columns: `users.permissions` (ENUM)
 - [ ]  Table names: `users`, `roles`, `users_roles`; Columns: `users_roles.role_id` (INT), `users_roles.user_id` (INT)
 - [ ]  Table names: `users`, `roles`; Columns: `roles.id` (INT, *unique*), `users.role_id` (INT)
 - [ ]  **Tables: `users`, `permissions`, `roles`, `permissions_roles`; Columns: `users.role_id` (INT, *unique*), `permissons_roles.role_id` (INT)**
