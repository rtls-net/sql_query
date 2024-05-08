# sql_query

### ` find count by a group `
     SELECT symbol , COUNT(symbol) as count_name FROM auth_db.trade_data GROUP BY symbol;
