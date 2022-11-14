# Secret Santa Script

This is a simple Ruby script for assigning secret Santas and emailing everyone their assignment.

## Usage

- Clone the repo
- Copy each of the `.yml.example` files in `config/` to a corresponding `.yml` and customize.
- Use the 'group' option in `people.yml` if you would like to prevent intra-household assignment.
	- If you want anyone to get anyone, just use a unique name for each person's group
- Run `ruby secret_santa.rb` and examine the output
- Modify `letter_template.erb`, if you like, and repeat.
- When you're satisfied, run `REALLY_SENDING=true ruby secret_santa.rb`
