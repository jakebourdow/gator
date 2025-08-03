psql postgres
\c gator

exit to close

regenerate database/ go code: sqlc generate

from sql/schema run to goose up and down versions:
goose postgres postgres://jake:@localhost:5432/gator up/down

To add a name: go run . register <name>
To login with a registered name: go run . login <name>