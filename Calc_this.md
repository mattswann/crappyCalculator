# Crappy Calculator V2
___

### Adding it up
Here we go again...
Let's make a `ruby` console based Calculator that a user can enter 2 (or more) numbers and a mathematical operator and expect the correct output to be displayed.

You calculator should be able to handle more advance arithmatic too. 

#### Menus
Consider using a menu to help the user.
Something like this...

```ruby
puts "Welcome to the Crappy Calculator"
puts "\n"
puts "\n"
puts "Please choose from the following to contine"
puts "\n"
puts "(b)asic, (a)dvanced, (m)ortgage, bm(i), (t)rip or (q)uit: "
gets.chomp.downcase

#hint use a while loop until the user chooses 'q'

```


### Extension
Add a bit more functionality to your app and allow users to calculate the following

* Kilometres per Litre
* BIM
* Mortgage
