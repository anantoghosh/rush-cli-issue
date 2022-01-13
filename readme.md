# Rush cli issue

## Case 1
In stencil folder
- Run `rushx start`
- `Ctrl+C` after dev server is started
- Try to run other commands

## Case 2
- Run `rush select` custom command.
- Select and run the stencil `start` command.
- `Ctrl+C` after dev server is started
- Try to run other commands

## Note
- `rush select-node` which directly runs the rush-select script via node does not exhibit this problem.
