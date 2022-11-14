# Secret Santa Script

This is a simple Ruby script for assigning secret Santas and emailing everyone their assignment. Use the 'group' option in people.yml if you would like to prevent intra-household assignment.

## Usage

- Clone the repo
- Copy each of the `.yml.example` files in `config/` to a corresponding `.yml` and customize.
- Run `ruby secret_santa.rb` and examine the output
- Modify `letter_template.erb`, if you like, and repeat.
- When you're satisfied, run `REALLY_SENDING=true ruby secret_santa.rb`
