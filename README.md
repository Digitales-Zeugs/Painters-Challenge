# DZ Painters 

This is a painting company. We need to automate the quote process for our clients to book our services online.

## Rules

* Each piece takes 2 minutes.
* Each color switch takes 1 minute.
* Beginner painter needs to switch colors for every piece.
* Expert painter can paint all same colors in a row
### Example:

```bash
# paint ([piece_1_color, piece_2_color, ...., piece_n_color])
$ paint([red, blue, red, green])
$ paint([red, blue, red, green, orange, red, blue])


#Expected result.

beginner => 20
expert => 17
```

## Steps

1) Planify. Explore. Diagram.
2) Create the function for the junior painter.
3) Create the function for the senior painter.

## Contributing
Pull requests are welcome. For major changes, please open an issue first to discuss what you would like to change.

Please make sure to update tests as appropriate.

## License
[MIT](https://choosealicense.com/licenses/mit/)
